---
layout: publication
title: 'Bridging The Gap: Enhancing LLM Performance For Low-resource African Languages With New Benchmarks, Fine-tuning, And Cultural Adjustments'
authors: Tuka Alhanai, Adam Kasumovic, Mohammad Ghassemi, Aven Zitzelberger, Jessica Lundin, Guillaume Chabot-couture
conference: "Arxiv"
year: 2024
bibkey: alhanai2024bridging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.12417"}
tags: ['Fine-Tuning', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Large Language Models (LLMs) have shown remarkable performance across various
tasks, yet significant disparities remain for non-English languages, and
especially native African languages. This paper addresses these disparities by
creating approximately 1 million human-translated words of new benchmark data
in 8 low-resource African languages, covering a population of over 160 million
speakers of: Amharic, Bambara, Igbo, Sepedi (Northern Sotho), Shona, Sesotho
(Southern Sotho), Setswana, and Tsonga. Our benchmarks are translations of
Winogrande and three sections of MMLU: college medicine, clinical knowledge,
and virology. Using the translated benchmarks, we report previously unknown
performance gaps between state-of-the-art (SOTA) LLMs in English and African
languages. Finally, using results from over 400 fine-tuned models, we explore
several methods to reduce the LLM performance gap, including high-quality
dataset fine-tuning (using an LLM-as-an-Annotator), cross-lingual transfer, and
cultural appropriateness adjustments. Key findings include average mono-lingual
improvements of 5.6% with fine-tuning (with 5.4% average mono-lingual
improvements when using high-quality data over low-quality data), 2.9% average
gains from cross-lingual transfer, and a 3.0% out-of-the-box performance boost
on culturally appropriate questions. The publicly available benchmarks,
translations, and code from this study support further research and development
aimed at creating more inclusive and effective language technologies.
