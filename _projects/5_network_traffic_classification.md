---
layout: page
title: Network Traffic Classification with Deep Learning
description: EBSNN and BSNN - Novel neural network architectures for automated network traffic classification
img: assets/img/network_traffic.jpg
importance: 1
category: ml-for-systems
related_publications: true
---

This research introduces innovative deep learning approaches for network traffic classification, addressing the fundamental challenge of automatically identifying network protocols and applications. The work encompasses two major contributions: the Byte Segment Neural Network (BSNN) and its extended version (EBSNN), both designed to handle the complexity of modern network environments.

## Research Objectives

The primary goal is to advance network traffic classification through:
- **Automated Feature Learning**: Eliminating manual feature engineering requirements
- **Protocol Agnostic Design**: Handling both traditional and novel network protocols
- **Real-time Classification**: Enabling efficient packet-level and flow-level analysis
- **Production Deployment**: Implementing solutions in real-world network environments

## Technical Approach

The research employs several innovative neural network architectures:

### Byte Segment Neural Network (BSNN)
- **Packet Segmentation**: Dividing packets into header and payload segments
- **Recurrent Processing**: Using RNNs with attention mechanisms for segment encoding
- **Multi-class Support**: Handling multiple protocol classifications simultaneously
- **Novel Protocol Detection**: Identifying previously unseen network applications

### Extended Byte Segment Neural Network (EBSNN)
- **Enhanced Architecture**: Building upon BSNN with improved feature extraction
- **Side-channel Learning**: Incorporating header information for better performance
- **Flow-level Analysis**: Examining multiple packets for comprehensive classification
- **Attention Mechanisms**: Focusing on relevant packet segments for classification

## Key Outcomes

This research has achieved:
- **95.82% average F1-measure** in multi-classification for five protocols
- **Superior performance** over traditional ML and packet inspection methods
- **Novel protocol detection** capabilities for emerging applications
- Multiple publications in top-tier venues (TDSC, IWQoS, Information Sciences)

## Impact

The contributions advance network management and security:
- **Intrusion Detection**: Better identification of malicious network traffic
- **Network Management**: Automated traffic classification for QoS and monitoring
- **Security Enhancement**: Improved detection of network anomalies
- **Protocol Evolution**: Support for emerging network protocols and applications

## Related Publications

- **EBSNN: Extended Byte Segment Neural Network for Network Traffic Classification** (IEEE TDSC 2021)
- **Byte Segment Neural Network for Network Traffic Classification** (IEEE/ACM IWQoS 2018)
- **Novel Dynamic Multiple Classification System for Network Traffic** (Information Sciences 2019)

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/network_traffic.jpg" title="Network Traffic Analysis" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Deep learning-based network traffic classification system analyzing packet segments for automated protocol identification.
</div>

