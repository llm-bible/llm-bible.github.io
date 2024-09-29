---
layout: publication
title: Fine45;tuning Large Language Models For Domain45;specific Machine Translation
authors: Zheng Jiawei, Hong Hanghai, Wang Xiaoli, Su Jingsong, Liang Yonggui, Wu Shikai
conference: "Arxiv"
year: 2024
bibkey: zheng2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.15061"}
tags: ['Applications', 'Fine Tuning', 'Prompting', 'Training Techniques']
---
Large language models (LLMs) have made significant progress in machine translation (MT). However their potential in domain45;specific MT remains under45;explored. Current LLM45;based MT systems still face several challenges. First for LLMs with in45;context learning their effectiveness is highly sensitive to input translation examples and processing them can increase inference costs. They often require extra post45;processing due to over45;generation. Second LLMs with fine45;tuning on domain45;specific data often require high training costs for domain adaptation and may weaken the zero45;shot MT capabilities of LLMs due to over45;specialization. The aforementioned methods can struggle to translate rare words in domain transfer scenarios. To address these challenges this paper proposes a prompt45;oriented fine45;tuning method denoted as LlamaIT to effectively and efficiently fine45;tune a general45;purpose LLM for domain45;specific MT tasks. First we construct a task45;specific mix45;domain dataset which is then used to fine45;tune the LLM with LoRA. This can eliminate the need for input translation examples post45;processing or over45;specialization. By zero45;shot prompting with instructions we adapt the MT tasks to the target domain at inference time. To further elicit the MT capability for rare words we construct new prompts by incorporating domain45;specific bilingual vocabulary. We also conduct extensive experiments on both publicly available and self45;constructed datasets. The results show that our LlamaIT can significantly enhance the domain45;specific MT capabilities of the LLM meanwhile preserving its zero45;shot MT capabilities.
