---
layout: publication
title: 'Can Llms Learn By Teaching? A Preliminary Study'
authors: Ning Xuefei, Wang Zifu, Li Shiyao, Lin Zinan, Yao Peiran, Fu Tianyu, Blaschko Matthew B., Dai Guohao, Yang Huazhong, Wang Yu
conference: "Arxiv"
year: 2024
bibkey: ning2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14629"}
  - {name: "Code", url: "https://github.com/imagination-research/lbt"}
tags: ['Distillation', 'Efficiency And Optimization', 'Fine Tuning', 'Has Code', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Teaching to improve student models (e.g. knowledge distillation) is an extensively studied methodology in LLMs. However for humans teaching not only improves students but also improves teachers. We ask Can LLMs also learn by teaching (LbT) If yes we can potentially unlock the possibility of continuously advancing the models without solely relying on human-produced data or stronger models. In this paper we provide a preliminary exploration of this ambitious agenda. We show that LbT ideas can be incorporated into existing LLM training/prompting pipelines and provide noticeable improvements. Specifically we design three methods each mimicking one of the three levels of LbT in humans observing students feedback learning from the feedback and learning iteratively with the goals of improving answer accuracy without training and improving models inherent capability with fine-tuning. The findings are encouraging. For example similar to LbT in human we see that (1) LbT can induce weak-to-strong generalization strong models can improve themselves by teaching other weak models; (2) Diversity in students might help teaching multiple students could be better than teaching one student or the teacher itself. We hope that this early promise can inspire future research on LbT and more broadly adopting the advanced techniques in education to improve LLMs. The code is available at https://github.com/imagination-research/lbt."
