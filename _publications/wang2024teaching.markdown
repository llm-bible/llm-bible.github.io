---
layout: publication
title: 'RNR: Teaching Large Language Models To Follow Roles And Rules'
authors: Kuan Wang, Alexander Bukharin, Haoming Jiang, Qingyu Yin, Zhengyang Wang, Tuo Zhao, Jingbo Shang, Chao Zhang, Bing Yin, Xian Li, Jianshu Chen, Shiyang Li
conference: "Arxiv"
year: 2024
bibkey: wang2024teaching
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.13733"}
tags: ['Fine-Tuning', 'Tools', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Instruction fine-tuning (IFT) elicits instruction following capabilities and
steers the behavior of large language models (LLMs) via supervised learning.
However, existing models trained on open-source IFT datasets only have the
ability to follow instructions from users, and often fail to follow complex
role and rules specified by developers, a.k.a. system prompts. The ability to
follow these roles and rules is essential for deployment, as it ensures that
the model safely interacts with users within developer defined guidelines. To
improve such role and rule following ability, we propose \model, an automated
data generation pipeline that generates diverse roles and rules from existing
IFT instructions, along with corresponding responses. This data can then be
used to train models that follow complex system prompts. The models are
evaluated on our newly created benchmarks for role and rule following ability,
as well as standard instruction-following benchmarks and general NLP tasks. Our
framework significantly improves role and rule following capability in LLMs, as
evidenced by over 25% increase in pass-rate on rule adherence, i.e. following
all requirements, in our experiments with the Alpaca and Ultrachat datasets.
Moreover, our models achieves this increase without any regression on popular
instruction following benchmarks.
