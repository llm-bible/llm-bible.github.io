---
layout: publication
title: From Yes-men To Truth-tellers: Addressing Sycophancy In Large Language Models With Pinpoint Tuning
authors: Chen Wei, Huang Zhen, Xie Liang, Lin Binbin, Li Houqiang, Lu Le, Tian Xinmei, Cai Deng, Zhang Yonggang, Wan Wenxiao, Shen Xu, Ye Jieping
conference: "Arxiv"
year: 2024
bibkey: chen2024from
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.01658"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Large Language Models (LLMs) tend to prioritize adherence to user prompts over providing veracious responses leading to the sycophancy issue. When challenged by users LLMs tend to admit mistakes and provide inaccurate responses even if they initially provided the correct answer. Recent works propose to employ supervised fine-tuning (SFT) to mitigate the sycophancy issue while it typically leads to the degeneration of LLMs general capability. To address the challenge we propose a novel supervised pinpoint tuning (SPT) where the region-of-interest modules are tuned for a given objective. Specifically SPT first reveals and verifies a small percentage (<537;) of the basic modules which significantly affect a particular behavior of LLMs. i.e. sycophancy. Subsequently SPT merely fine-tunes these identified modules while freezing the rest. To verify the effectiveness of the proposed SPT we conduct comprehensive experiments demonstrating that SPT significantly mitigates the sycophancy issue of LLMs (even better than SFT). Moreover SPT introduces limited or even no side effects on the general capability of LLMs. Our results shed light on how to precisely effectively and efficiently explain and improve the targeted ability of LLMs.
