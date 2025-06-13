---
layout: publication
title: 'Physgame: Uncovering Physical Commonsense Violations In Gameplay Videos'
authors: Meng Cao, Haoran Tang, Haoze Zhao, Hangyu Guo, Jiaheng Liu, Ge Zhang, Ruyang Liu, Qiang Sun, Ian Reid, Xiaodan Liang
conference: "Arxiv"
year: 2024
bibkey: cao2024uncovering
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.01800'}
tags: ['Reinforcement Learning', 'Efficiency and Optimization', 'Training Techniques']
---
Recent advancements in video-based large language models (Video LLMs) have
witnessed the emergence of diverse capabilities to reason and interpret dynamic
visual content. Among them, gameplay videos stand out as a distinctive data
source, often containing glitches that defy physics commonsense. This
characteristic renders them an effective benchmark for assessing the
under-explored capability of physical commonsense understanding in video LLMs.
In this paper, we propose PhysGame as a pioneering benchmark to evaluate
physical commonsense violations in gameplay videos. PhysGame comprises 880
videos associated with glitches spanning four fundamental domains (i.e.,
mechanics, kinematics, optics, and material properties) and across 12 distinct
physical commonsense. Through extensively evaluating various state-ofthe-art
video LLMs, our findings reveal that the performance of current open-source
video LLMs significantly lags behind that of proprietary counterparts. To
bridge this gap, we curate an instruction tuning dataset PhysInstruct with
140,057 question-answering pairs to facilitate physical commonsense learning.
In addition, we also propose a preference optimization dataset PhysDPO with
34,358 training pairs, where the dis-preferred responses are generated
conditioned on misleading titles (i.e., meta information hacking), fewer frames
(i.e., temporal hacking) and lower spatial resolutions (i.e., spatial hacking).
Based on the suite of datasets, we propose PhysVLM as a physical
knowledge-enhanced video LLM. Extensive experiments on both physical-oriented
benchmark PhysGame and general video understanding benchmarks demonstrate the
state-ofthe-art performance of PhysVLM.
