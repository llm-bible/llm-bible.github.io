---
layout: publication
title: ICL45;D3IE In45;context Learning With Diverse Demonstrations Updating For Document Information Extraction
authors: He Jiabang, Wang Lei, Hu Yi, Liu Ning, Liu Hui, Xu Xing, Shen Heng Tao
conference: "Arxiv"
year: 2023
bibkey: he2023icl
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.05063"}
  - {name: "Code", url: "https://github.com/MAEHCM/ICL&#45;D3IE"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Prompting', 'Tools', 'Training Techniques']
---
Large language models (LLMs) such as GPT45;3 and ChatGPT have demonstrated remarkable results in various natural language processing (NLP) tasks with in45;context learning which involves inference based on a few demonstration examples. Despite their successes in NLP tasks no investigation has been conducted to assess the ability of LLMs to perform document information extraction (DIE) using in45;context learning. Applying LLMs to DIE poses two challenges the modality and task gap. To this end we propose a simple but effective in45;context learning framework called ICL45;D3IE which enables LLMs to perform DIE with different types of demonstration examples. Specifically we extract the most difficult and distinct segments from hard training documents as hard demonstrations for benefiting all test instances. We design demonstrations describing relationships that enable LLMs to understand positional relationships. We introduce formatting demonstrations for easy answer extraction. Additionally the framework improves diverse demonstrations by updating them iteratively. Our experiments on three widely used benchmark datasets demonstrate that the ICL45;D3IE framework enables Davinci45;003/ChatGPT to achieve superior performance when compared to previous pre45;trained methods fine45;tuned with full training in both the in45;distribution (ID) setting and in the out45;of45;distribution (OOD) setting. Code is available at https://github.com/MAEHCM/ICL&#45;D3IE.
