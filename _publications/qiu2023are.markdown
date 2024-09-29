---
layout: publication
title: 'Are Large Language Models Temporally Grounded?'
authors: Qiu Yifu, Zhao Zheng, Ziser Yftah, Korhonen Anna, Ponti Edoardo M., Cohen Shay B.
conference: "Arxiv"
year: 2023
bibkey: qiu2023are
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.08398"}
  - {name: "Code", url: "https://github.com/yfqiu-nlp/temporal-llms"}
tags: ['GPT', 'Has Code', 'In Context Learning', 'Model Architecture', 'Prompting', 'Training Techniques']
---
Are Large language models (LLMs) temporally grounded Since LLMs cannot perceive and interact with the environment it is impossible to answer this question directly. Instead we provide LLMs with textual narratives and probe them with respect to their common-sense knowledge of the structure and duration of events their ability to order events along a timeline and self-consistency within their temporal model (e.g. temporal relations such as after and before are mutually exclusive for any pair of events). We evaluate state-of-the-art LLMs (such as LLaMA 2 and GPT-4) on three tasks reflecting these abilities. Generally we find that LLMs lag significantly behind both human performance as well as small-scale specialised LMs. In-context learning instruction tuning and chain-of-thought prompting reduce this gap only to a limited degree. Crucially LLMs struggle the most with self-consistency displaying incoherent behaviour in at least 27.2337; of their predictions. Contrary to expectations we also find that scaling the model size does not guarantee positive gains in performance. To explain these results we study the sources from which LLMs may gather temporal information we find that sentence ordering in unlabelled texts available during pre-training is only weakly correlated with event ordering. Moreover public instruction tuning mixtures contain few temporal tasks. Hence we conclude that current LLMs lack a consistent temporal model of textual narratives. Code datasets and LLM outputs are available at https://github.com/yfqiu-nlp/temporal-llms."
