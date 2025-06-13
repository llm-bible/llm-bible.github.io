---
layout: publication
title: 'Llm-based Evaluation Of Low-resource Machine Translation: A Reference-less Dialect Guided Approach With A Refined Sylheti-english Benchmark'
authors: Md. Atiqur Rahman, Sabrina Islam, Mushfiqul Haque Omi
conference: "Arxiv"
year: 2025
bibkey: rahman2025llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.12273"}
  - {name: "Code", url: "https://github.com/180041123-Atiq/MTEonLowResourceLanguage"}
tags: ['Prompting', 'Applications', 'Has Code', 'Tools']
---
Evaluating machine translation (MT) for low-resource languages poses a persistent challenge, primarily due to the limited availability of high quality reference translations. This issue is further exacerbated in languages with multiple dialects, where linguistic diversity and data scarcity hinder robust evaluation. Large Language Models (LLMs) present a promising solution through reference-free evaluation techniques; however, their effectiveness diminishes in the absence of dialect-specific context and tailored guidance. In this work, we propose a comprehensive framework that enhances LLM-based MT evaluation using a dialect guided approach. We extend the ONUBAD dataset by incorporating Sylheti-English sentence pairs, corresponding machine translations, and Direct Assessment (DA) scores annotated by native speakers. To address the vocabulary gap, we augment the tokenizer vocabulary with dialect-specific terms. We further introduce a regression head to enable scalar score prediction and design a dialect-guided (DG) prompting strategy. Our evaluation across multiple LLMs shows that the proposed pipeline consistently outperforms existing methods, achieving the highest gain of +0.1083 in Spearman correlation, along with improvements across other evaluation settings. The dataset and the code are available at https://github.com/180041123-Atiq/MTEonLowResourceLanguage.
