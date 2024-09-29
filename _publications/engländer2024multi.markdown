---
layout: publication
title: M2QA Multi45;domain Multilingual Question Answering
authors: Engländer Leon, Sterz Hannah, Poth Clifton, Pfeiffer Jonas, Kuznetsov Ilia, Gurevych Iryna
conference: "Arxiv"
year: 2024
bibkey: engländer2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.01091"}
  - {name: "Code", url: "https://github.com/UKPLab/m2qa"}
tags: ['Applications', 'Has Code', 'Security']
---
Generalization and robustness to input variation are core desiderata of machine learning research. Language varies along several axes most importantly language instance (e.g. French) and domain (e.g. news). While adapting NLP models to new languages within a single domain or to new domains within a single language is widely studied research in joint adaptation is hampered by the lack of evaluation datasets. This prevents the transfer of NLP systems from well45;resourced languages and domains to non45;dominant language45;domain combinations. To address this gap we introduce M2QA a multi45;domain multilingual question answering benchmark. M2QA includes 13500 SQuAD 2.045;style question45;answer instances in German Turkish and Chinese for the domains of product reviews news and creative writing. We use M2QA to explore cross45;lingual cross45;domain performance of fine45;tuned models and state45;of45;the45;art LLMs and investigate modular approaches to domain and language adaptation. We witness 1) considerable performance variations across domain45;language combinations within model classes and 2) considerable performance drops between source and target language45;domain combinations across all model sizes. We demonstrate that M2QA is far from solved and new methods to effectively transfer both linguistic and domain45;specific information are necessary. We make M2QA publicly available at https://github.com/UKPLab/m2qa.
