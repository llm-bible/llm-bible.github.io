---
layout: publication
title: 'Tractable Control For Autoregressive Language Generation'
authors: Zhang Honghua, Dang Meihua, Peng Nanyun, Broeck Guy Van Den
conference: "Arxiv"
year: 2023
bibkey: zhang2023tractable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.07438"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Tools']
---
"Despite the success of autoregressive large language models in text generation, it remains a major challenge to generate text that satisfies complex constraints: sampling from the conditional distribution \({\Pr}(\text{text} | \alpha)\) is intractable for even the simplest lexical constraints \(\alpha\). To overcome this challenge, we propose to use tractable probabilistic models (TPMs) to impose lexical constraints in autoregressive text generation models, which we refer to as GeLaTo (Generating Language with Tractable Constraints). To demonstrate the effectiveness of this framework, we use distilled hidden Markov models, where we can efficiently compute \({\Pr}(\text{text} | \alpha)\), to guide autoregressive generation from GPT2. GeLaTo achieves state-of-the-art performance on challenging benchmarks for constrained text generation (e.g., CommonGen), beating various strong baselines by a large margin. Our work not only opens up new avenues for controlling large language models but also motivates the development of more expressive TPMs."
