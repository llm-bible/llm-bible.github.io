---
layout: publication
title: 'Trans-env: A Framework For Evaluating The Linguistic Robustness Of Llms Against English Varieties'
authors: Jiyoung Lee, Seungho Kim, Jieun Han, Jun-min Lee, Kitaek Kim, Alice Oh, Edward Choi
conference: "Arxiv"
year: 2025
bibkey: lee2025trans
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.20875'}
  - {name: "Code", url: 'https://github.com/jiyounglee-0523/TransEnV'}
  - {name: "Code", url: 'https://huggingface.co/collections/jiyounglee0523/transenv-681eadb3c0c8cf363b363fb1'}
tags: ['Has Code', 'Security', 'Fairness', 'Tools', 'Bias Mitigation', 'Reinforcement Learning', 'Ethics and Bias']
---
Large Language Models (LLMs) are predominantly evaluated on Standard American English (SAE), often overlooking the diversity of global English varieties. This narrow focus may raise fairness concerns as degraded performance on non-standard varieties can lead to unequal benefits for users worldwide. Therefore, it is critical to extensively evaluate the linguistic robustness of LLMs on multiple non-standard English varieties. We introduce Trans-EnV, a framework that automatically transforms SAE datasets into multiple English varieties to evaluate the linguistic robustness. Our framework combines (1) linguistics expert knowledge to curate variety-specific features and transformation guidelines from linguistic literature and corpora, and (2) LLM-based transformations to ensure both linguistic validity and scalability. Using Trans-EnV, we transform six benchmark datasets into 38 English varieties and evaluate seven state-of-the-art LLMs. Our results reveal significant performance disparities, with accuracy decreasing by up to 46.3% on non-standard varieties. These findings highlight the importance of comprehensive linguistic robustness evaluation across diverse English varieties. Each construction of Trans-EnV was validated through rigorous statistical testing and consultation with a researcher in the field of second language acquisition, ensuring its linguistic validity. Our code and datasets are publicly available at https://github.com/jiyounglee-0523/TransEnV and https://huggingface.co/collections/jiyounglee0523/transenv-681eadb3c0c8cf363b363fb1.
