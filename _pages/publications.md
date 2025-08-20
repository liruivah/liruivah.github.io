---
layout: page
permalink: /publications/
title: publications
description: Publications by categories in reversed chronological order.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<div class="section-header-bg" style="background-image: url('{{ '/assets/img/yellowstone.jpg' | relative_url }}'); background-size: cover; background-position: center; height: 200px; border-radius: 10px; margin-bottom: 20px; position: relative;">
</div>

<!-- Bibsearch Feature -->
{% include bib_search.liquid %}

<div class="publications">

<h2>Selected Publications</h2>

<div class="publication-item" style="margin-bottom: 30px; padding: 20px; border: 1px solid #e0e0e0; border-radius: 8px; background: white; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
  <h3 style="color: #2c3e50; margin-bottom: 10px; font-size: 1.3em;">BootSeer: Analyzing and Mitigating Initialization Bottlenecks in Large-Scale LLM Training</h3>
  <p style="color: #7f8c8d; margin-bottom: 8px; font-size: 0.95em;"><strong>Li, R.</strong>, Zhi, X., Chi, J., Yu, M., Huang, L., Zhu, J., Zhang, W., Ma, X., Liu, W., Zhu, Z., et al.</p>
  <p style="color: #34495e; margin-bottom: 12px; font-style: italic; font-size: 0.9em;">arXiv preprint arXiv:2507.12619, 2025</p>
  <p style="color: #2c3e50; margin-bottom: 15px; line-height: 1.6;">Large Language Models (LLMs) have become a cornerstone of modern AI, driving breakthroughs in natural language processing and expanding into multimodal jobs involving images, audio, and video. This work focuses on the increasingly critical issue of startup overhead in training: the delay before training jobs begin execution.</p>
  <a href="https://arxiv.org/pdf/2507.12619" class="btn btn-sm z-depth-0" target="_blank" style="background-color: #3498db; color: white; padding: 8px 16px; text-decoration: none; border-radius: 4px; font-size: 0.9em;">PDF</a>
</div>

<div class="publication-item" style="margin-bottom: 30px; padding: 20px; border: 1px solid #e0e0e0; border-radius: 8px; background: white; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
  <h3 style="color: #2c3e50; margin-bottom: 10px; font-size: 1.3em;">HotSwap: Enabling Live Dependency Sharing in Serverless Computing</h3>
  <p style="color: #7f8c8d; margin-bottom: 8px; font-size: 0.95em;"><strong>Li, R.</strong>, Cooperman, G., Tiwari, D.</p>
  <p style="color: #34495e; margin-bottom: 12px; font-style: italic; font-size: 0.9em;">Proceedings of the IEEE International Conference on Cloud Computing (CLOUD), 2025</p>
  <p style="color: #2c3e50; margin-bottom: 15px; line-height: 1.6;">This work presents HotSwap, a novel provider-side cold-start optimization for serverless computing. This optimization reduces cold-start time when booting and loading dependencies at runtime inside a function container.</p>
  <a href="https://arxiv.org/abs/2409.09202" class="btn btn-sm z-depth-0" target="_blank" style="background-color: #3498db; color: white; padding: 8px 16px; text-decoration: none; border-radius: 4px; font-size: 0.9em;">PDF</a>
</div>

<div class="publication-item" style="margin-bottom: 30px; padding: 20px; border: 1px solid #e0e0e0; border-radius: 8px; background: white; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
  <h3 style="color: #2c3e50; margin-bottom: 10px; font-size: 1.3em;">Automated Intelligent Healing for Cloud-Scale Data Centers</h3>
  <p style="color: #7f8c8d; margin-bottom: 8px; font-size: 0.95em;"><strong>Li, R.</strong>, Cheng, Z., Lee, P. P. C., Wang, P., Qiang, Y., Lan, L., He, C., Lu, J., Wang, M., Ding, X.</p>
  <p style="color: #34495e; margin-bottom: 12px; font-style: italic; font-size: 0.9em;">40th International Symposium on Reliable Distributed Systems (SRDS), 2021</p>
  <p style="color: #2c3e50; margin-bottom: 15px; line-height: 1.6;">We propose AIHS, an automated intelligent healing system that applies machine learning to achieve scalable self-healing in cloud-scale data centers. AIHS is designed as a full-fledged, general pipeline that supports various machine learning models for predicting accurate repair actions based on raw monitoring logs.</p>
  <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9603508" class="btn btn-sm z-depth-0" target="_blank" style="background-color: #3498db; color: white; padding: 8px 16px; text-decoration: none; border-radius: 4px; font-size: 0.9em;">PDF</a>
</div>

<div class="publication-item" style="margin-bottom: 30px; padding: 20px; border: 1px solid #e0e0e0; border-radius: 8px; background: white; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
  <h3 style="color: #2c3e50; margin-bottom: 10px; font-size: 1.3em;">EBSNN: Extended Byte Segment Neural Network for Network Traffic Classification</h3>
  <p style="color: #7f8c8d; margin-bottom: 8px; font-size: 0.95em;">Xiao, X., Xiao, W., <strong>Li, R.</strong>, Luo, X., Zheng, H., Xia, S.</p>
  <p style="color: #34495e; margin-bottom: 12px; font-style: italic; font-size: 0.9em;">IEEE Transactions on Dependable and Secure Computing, 2021</p>
  <p style="color: #2c3e50; margin-bottom: 15px; line-height: 1.6;">We design a novel neural network, the Extended Byte Segment Neural Network (EBSNN), to classify network traffic. EBSNN first divides a packet into header segments and payload segments, which are then fed into encoders composed of the recurrent neural networks with the attention mechanism.</p>
  <a href="https://ieeexplore.ieee.org/abstract/document/9503323" class="btn btn-sm z-depth-0" target="_blank" style="background-color: #3498db; color: white; padding: 8px 16px; text-decoration: none; border-radius: 4px; font-size: 0.9em;">PDF</a>
</div>

<div class="publication-item" style="margin-bottom: 30px; padding: 20px; border: 1px solid #e0e0e0; border-radius: 8px; background: white; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
  <h3 style="color: #2c3e50; margin-bottom: 10px; font-size: 1.3em;">Novel Dynamic Multiple Classification System for Network Traffic</h3>
  <p style="color: #7f8c8d; margin-bottom: 8px; font-size: 0.95em;">Xiao, X., <strong>Li, R.*</strong>, Zheng, H., Ye, R., Sangaiah, A. K., Xia, S.</p>
  <p style="color: #34495e; margin-bottom: 12px; font-style: italic; font-size: 0.9em;">Information Sciences, 2019</p>
  <p style="color: #2c3e50; margin-bottom: 15px; line-height: 1.6;">We design a novel neural network, the Extended Byte Segment Neural Network (EBSNN), to classify network traffic. EBSNN first divides a packet into header segments and payload segments, which are then fed into encoders composed of the recurrent neural networks with the attention mechanism.</p>
  <a href="https://www.sciencedirect.com/science/article/abs/pii/S0020025518308569" class="btn btn-sm z-depth-0" target="_blank" style="background-color: #3498db; color: white; padding: 8px 16px; text-decoration: none; border-radius: 4px; font-size: 0.9em;">PDF</a>
</div>

<div class="publication-item" style="margin-bottom: 30px; padding: 20px; border: 1px solid #e0e0e0; border-radius: 8px; background: white; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
  <h3 style="color: #2c3e50; margin-bottom: 10px; font-size: 1.3em;">Byte Segment Neural Network for Network Traffic Classification</h3>
  <p style="color: #7f8c8d; margin-bottom: 8px; font-size: 0.95em;"><strong>Li, R.</strong>, Xiao, X., Ni, S., Zheng, H., Xia, S.</p>
  <p style="color: #34495e; margin-bottom: 12px; font-style: italic; font-size: 0.9em;">Proceedings of the IEEE/ACM 26th International Symposium on Quality of Service, 2018</p>
  <p style="color: #2c3e50; margin-bottom: 15px; line-height: 1.6;">We introduce the recurrent neural network to network traffic classification and design a novel neural network, the Byte Segment Neural Network (BSNN). BSNN treats network datagrams as input and gives the classification results directly.</p>
  <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7760799" class="btn btn-sm z-depth-0" target="_blank" style="background-color: #3498db; color: white; padding: 8px 16px; text-decoration: none; border-radius: 4px; font-size: 0.9em;">PDF</a>
</div>

</div>
