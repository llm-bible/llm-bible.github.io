---
layout: publication
title: Refuse Whenever You Feel Unsafe Improving Safety in LLMs via Decoupled Refusal Training
authors: Yuan Youliang, Jiao Wenxiang, Wang Wenxuan, Huang Jen-tse, Xu Jiahao, Liang Tian, He Pinjia, Tu Zhaopeng
conference: "Arxiv"
year: 2024
bibkey: yuan2024refuse
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.09121"}
  - {name: "Code", url: "https://github.com/RobustNLP/DeRTa"}
tags: ['ARXIV', 'Ethics And Bias', 'GPT', 'Has Code', 'LLM', 'NLP', 'Prompt', 'Responsible AI', 'Security']
---
This study addresses a critical gap in safety tuning practices for Large Language Models (LLMs) by identifying and tackling a refusal position bias within safety tuning data which compromises the models ability to appropriately refuse generating unsafe content. We introduce a novel approach Decoupled Refusal Training (DeRTa) designed to empower LLMs to refuse compliance to harmful prompts at any response position significantly enhancing their safety capabilities. DeRTa incorporates two novel components (1) Maximum Likelihood Estimation (MLE) with Harmful Response Prefix which trains models to recognize and avoid unsafe content by appending a segment of harmful response to the beginning of a safe response and (2) Reinforced Transition Optimization (RTO) which equips models with the ability to transition from potential harm to safety refusal consistently throughout the harmful response sequence. Our empirical evaluation conducted using LLaMA3 and Mistral model families across six attack scenarios demonstrates that our method not only improves model safety without compromising performance but also surpasses well-known models such as GPT-4 in defending against attacks. Importantly our approach successfully defends recent advanced attack methods (e.g. CodeAttack) that have jailbroken GPT-4 and LLaMA3-70B-Instruct. Our code and data can be found at https://github.com/RobustNLP/DeRTa.
