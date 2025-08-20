---
layout: page
title: HotSwap - Serverless Cold Start Optimization
description: Novel provider-side optimization for reducing cold-start latency in serverless computing
img: assets/img/hotswap.jpg
importance: 1
category: systems
related_publications: true
---

HotSwap is a groundbreaking provider-side cold-start optimization system for serverless computing that addresses the fundamental challenge of dependency loading during function initialization. This research introduces cross-function optimization strategies that respect vendor cache constraints while significantly improving cold-start performance.

## Research Objectives

The primary goal is to optimize serverless cold-start performance by:
- **Cross-Function Optimization**: Developing strategies that benefit multiple functions simultaneously
- **Dependency Sharing**: Enabling efficient sharing of common dependencies across functions
- **Cache Constraint Compliance**: Respecting provider-side cache limitations
- **Production Scalability**: Implementing solutions that work at cloud scale

## Technical Approach

HotSwap employs several innovative techniques:

### Pre-Warming Strategy
- **Live Dependency Migration**: Transferring pre-initialized dependency images to new function instances
- **Cross-Function Sharing**: Single pre-warmed dependency image shared among multiple functions
- **Cache Efficiency**: Optimizing cache utilization while respecting vendor constraints

### Performance Optimization
- **Dependency Acceleration**: 2.2x to 3.2x improvement in dependency loading for large functions
- **Space Efficiency**: 88% space savings compared to function-specific optimization methods
- **Azure Trace Validation**: Real-world validation using production Azure traces

## Key Outcomes

This research has achieved:
- **2.2x to 3.2x acceleration** in dependency loading for serverless functions
- **88% space savings** compared to previous optimization methods
- Publication at IEEE CLOUD 2025
- Validation on seven representative functions from FunctionBench

## Impact

HotSwap's contributions are essential for:
- **Performance Improvement**: Significantly faster serverless function execution
- **Cost Reduction**: Lower cold-start penalties in serverless environments
- **Resource Efficiency**: Better utilization of provider-side caching resources
- **Production Readiness**: Scalable solutions for real-world cloud deployments

## Related Publications

- **HotSwap: Enabling Live Dependency Sharing in Serverless Computing** (IEEE CLOUD 2025)

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/hotswap.jpg" title="HotSwap Performance Analysis" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    <strong>Figure:</strong> The relationship between invocation rate $\lambda$ and expected cold starts with keep-alive time $T=15$ minutes, using function distribution from Azure. Each serverless function was assigned to a bucket $[x, x+0.001]$, where the $\lambda$ of the serverless function was between $x$ and $x+0.001$ invocations per minute. The y-value for a bucket represents the normalized number of functions in that bucket, demonstrating the distribution of cold-start patterns across different invocation frequencies.
</div>
