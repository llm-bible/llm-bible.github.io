---
layout: publication
title: 'Empowering Large Language Model For Continual Video Question Answering With Collaborative Prompting'
authors: Chen Cai, Zheng Wang, Jianjun Gao, Wenyang Liu, Ye Lu, Runzhong Zhang, Kim-hui Yap
conference: "Arxiv"
year: 2024
bibkey: cai2024empowering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.00771"}
tags: ['Training Techniques', 'Tools', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Applications']
---
In recent years, the rapid increase in online video content has underscored
the limitations of static Video Question Answering (VideoQA) models trained on
fixed datasets, as they struggle to adapt to new questions or tasks posed by
newly available content. In this paper, we explore the novel challenge of
VideoQA within a continual learning framework, and empirically identify a
critical issue: fine-tuning a large language model (LLM) for a sequence of
tasks often results in catastrophic forgetting. To address this, we propose
Collaborative Prompting (ColPro), which integrates specific question constraint
prompting, knowledge acquisition prompting, and visual temporal awareness
prompting. These prompts aim to capture textual question context, visual
content, and video temporal dynamics in VideoQA, a perspective underexplored in
prior research. Experimental results on the NExT-QA and DramaQA datasets show
that ColPro achieves superior performance compared to existing approaches,
achieving 55.14% accuracy on NExT-QA and 71.24% accuracy on DramaQA,
highlighting its practical relevance and effectiveness.
