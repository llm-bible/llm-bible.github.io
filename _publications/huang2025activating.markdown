---
layout: publication
title: 'Aircache: Activating Inter-modal Relevancy KV Cache Compression For Efficient Large Vision-language Model Inference'
authors: Kai Huang, Hao Zou, Bochen Wang, Ye Xi, Zhen Xie, Hao Wang
conference: "Arxiv"
year: 2025
bibkey: huang2025activating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.23956"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Multimodal Models', 'Tools', 'Transformer', 'Prompting', 'Attention Mechanism']
---
Recent advancements in Large Visual Language Models (LVLMs) have gained
significant attention due to their remarkable reasoning capabilities and
proficiency in generalization. However, processing a large number of visual
tokens and generating long-context outputs impose substantial computational
overhead, leading to excessive demands for key-value (KV) cache. To address
this critical bottleneck, we propose AirCache, a novel KV cache compression
method aimed at accelerating LVLMs inference. This work systematically
investigates the correlations between visual and textual tokens within the
attention mechanisms of LVLMs. Our empirical analysis reveals considerable
redundancy in cached visual tokens, wherein strategically eliminating these
tokens preserves model performance while significantly accelerating context
generation. Inspired by these findings, we introduce an elite observation
window for assessing the importance of visual components in the KV cache,
focusing on stable inter-modal relevancy modeling with enhanced
multi-perspective consistency. Additionally, we develop an adaptive layer-wise
budget allocation strategy that capitalizes on the strength and skewness of
token importance distribution, showcasing superior efficiency compared to
uniform allocation. Comprehensive evaluations across multiple LVLMs and
benchmarks demonstrate that our method achieves comparable performance to the
full cache while retaining only 10% of visual KV cache, thereby reducing
decoding latency by 29% to 66% across various batch size and prompt length of
inputs. Notably, as cache retention rates decrease, our method exhibits
increasing performance advantages over existing approaches.
