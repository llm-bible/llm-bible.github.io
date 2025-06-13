---
layout: publication
title: 'Gradpower: Powering Gradients For Faster Language Model Pre-training'
authors: Mingze Wang, Jinbo Wang, Jiaqi Zhang, Wei Wang, Peng Pei, Xunliang Cai, Weinan E, Lei Wu
conference: "Arxiv"
year: 2025
bibkey: wang2025powering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.24275"}
tags: ['Training Techniques', 'Pre-Training', 'Model Architecture', 'Reinforcement Learning']
---
We propose GradPower, a lightweight gradient-transformation technique for accelerating language model pre-training. Given a gradient vector \\(g=(g_i)_i\\), GradPower first applies the elementwise sign-power transformation: \\(\varphi_p(g)=(\{\rm sign\}(g_i)|g_i|^p)_\{i\}\\) for a fixed \\(p>0\\), and then feeds the transformed gradient into a base optimizer. Notably, GradPower requires only a single-line code change and no modifications to the base optimizer's internal logic, including the hyperparameters. When applied to Adam (termed AdamPower), GradPower consistently achieves lower terminal loss across diverse architectures (LLaMA, Qwen2MoE), parameter scales (66M to 2B), datasets (C4, OpenWebText), and learning-rate schedules (cosine, warmup-stable-decay). The most pronounced gains are observed when training modern mixture-of-experts models with warmup-stable-decay schedules. GradPower also integrates seamlessly with other state-of-the-art optimizers, such as Muon, yielding further improvements. Finally, we provide theoretical analyses that reveal the underlying mechanism of GradPower and highlights the influence of gradient noise.
