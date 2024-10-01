---
layout: publication
title: 'Multilingual Machine Translation With Large Language Models: Empirical Results And Analysis'
authors: Zhu Wenhao, Liu Hongyi, Dong Qingxiu, Xu Jingjing, Huang Shujian, Kong Lingpeng, Chen Jiajun, Li Lei
conference: "Arxiv"
year: 2023
bibkey: zhu2023multilingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.04675"}
  - {name: "Code", url: "https://github.com/NJUNLP/MMT-LLM"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture']
---
Large language models (LLMs) have demonstrated remarkable potential in handling multilingual machine translation (MMT). In this paper, we systematically investigate the advantages and challenges of LLMs for MMT by answering two questions: 1) How well do LLMs perform in translating massive languages? 2) Which factors affect LLMs' performance in translation? We thoroughly evaluate eight popular LLMs, including ChatGPT and GPT-4. Our empirical results show that translation capabilities of LLMs are continually involving. GPT-4 has beat the strong supervised baseline NLLB in 40.91&#37; of translation directions but still faces a large gap towards the commercial translation system like Google Translate, especially on low-resource languages. Through further analysis, we discover that LLMs exhibit new working patterns when used for MMT. First, LLM can acquire translation ability in a resource-efficient way and generate moderate translation even on zero-resource languages. Second, instruction semantics can surprisingly be ignored when given in-context exemplars. Third, cross-lingual exemplars can provide better task guidance for low-resource translation than exemplars in the same language pairs. Code will be released at: https://github.com/NJUNLP/MMT-LLM.
