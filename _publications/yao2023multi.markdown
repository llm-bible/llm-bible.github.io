---
layout: publication
title: Deltazip Multi45;tenant Language Model Serving Via Delta Compression
authors: Yao Xiaozhe, Klimovic Ana
conference: "Arxiv"
year: 2023
bibkey: yao2023multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.05215"}
tags: ['Efficiency And Optimization']
---
Fine45;tuning large language models (LLMs) for downstream tasks can greatly improve model quality however serving many different fine45;tuned LLMs concurrently for users in multi45;tenant environments is challenging. Dedicating GPU memory for each model is prohibitively expensive and naively swapping large model weights in and out of GPU memory is slow. Our key insight is that fine45;tuned models can be quickly swapped in and out of GPU memory by extracting and compressing the delta between each model and its pre45;trained base model. We propose DeltaZip an LLM serving system that efficiently serves multiple full45;parameter fine45;tuned models concurrently by aggressively compressing model deltas by a factor of 6× to 8× while maintaining high model quality. DeltaZip increases serving throughput by 1.5× to 3× and improves SLO attainment compared to a vanilla HuggingFace serving system.
