---
layout: publication
title: 'Understanding Layer Significance In LLM Alignment'
authors: Guangyuan Shi, Zexin Lu, Xiaoyu Dong, Wenlong Zhang, Xuanyu Zhang, Yujie Feng, Xiao-ming Wu
conference: "Arxiv"
year: 2024
bibkey: shi2024understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.17875"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Applications', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Aligning large language models (LLMs) through supervised fine-tuning is
essential for tailoring them to specific applications. Recent studies suggest
that alignment primarily adjusts a model's presentation style rather than its
foundational knowledge, indicating that only certain components of the model
are significantly impacted. To uncover how alignment affects model behavior at
a granular level, we propose identifying which layers within LLMs are most
critical to the alignment process. Our approach, named ILA, involves learning a
binary mask for the parameter changes in each layer during alignment, as an
indicator of layer significance. Experimental results reveal that, despite
substantial differences in alignment datasets, the important layers of a model
identified by ILA exhibit nearly 90% overlap, highlighting fundamental
patterns in LLM alignment. The results also indicate that freezing
non-essential layers improves overall model performance, while selectively
tuning the most critical layers significantly enhances fine-tuning efficiency
with minimal performance loss. Finally, we discuss how these findings extend
from LLM alignment to reasoning.
