---
layout: publication
title: 'Distilling Multi-modal Large Language Models For Autonomous Driving'
authors: Deepti Hegde, Rajeev Yasarla, Hong Cai, Shizhong Han, Apratim Bhattacharyya, Shweta Mahajan, Litian Liu, Risheek Garrepalli, Vishal M. Patel, Fatih Porikli
conference: "Arxiv"
year: 2025
bibkey: hegde2025distilling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.09757"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'RAG', 'Reinforcement Learning']
---
Autonomous driving demands safe motion planning, especially in critical
"long-tail" scenarios. Recent end-to-end autonomous driving systems leverage
large language models (LLMs) as planners to improve generalizability to rare
events. However, using LLMs at test time introduces high computational costs.
To address this, we propose DiMA, an end-to-end autonomous driving system that
maintains the efficiency of an LLM-free (or vision-based) planner while
leveraging the world knowledge of an LLM. DiMA distills the information from a
multi-modal LLM to a vision-based end-to-end planner through a set of specially
designed surrogate tasks. Under a joint training strategy, a scene encoder
common to both networks produces structured representations that are
semantically grounded as well as aligned to the final planning objective.
Notably, the LLM is optional at inference, enabling robust planning without
compromising on efficiency. Training with DiMA results in a 37% reduction in
the L2 trajectory error and an 80% reduction in the collision rate of the
vision-based planner, as well as a 44% trajectory error reduction in longtail
scenarios. DiMA also achieves state-of-the-art performance on the nuScenes
planning benchmark.
