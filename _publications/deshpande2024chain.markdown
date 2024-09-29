---
layout: publication
title: Chain-of-translation Prompting (cotr)\: A Novel Prompting Technique For Low Resource Languages
authors: Deshpande Tejas, Kowtal Nidhi, Joshi Raviraj
conference: "Arxiv"
year: 2024
bibkey: deshpande2024chain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.04512"}
tags: ['Applications', 'Language Modeling', 'Prompting']
---
This paper introduces Chain of Translation Prompting (CoTR) a novel strategy designed to enhance the performance of language models in low-resource languages. CoTR restructures prompts to first translate the input context from a low-resource language into a higher-resource language such as English. The specified task like generation classification or any other NLP function is then performed on the translated text with the option to translate the output back to the original language if needed. All these steps are specified in a single prompt. We demonstrate the effectiveness of this method through a case study on the low-resource Indic language Marathi. The CoTR strategy is applied to various tasks including sentiment analysis hate speech classification subject classification and text generation and its efficacy is showcased by comparing it with regular prompting methods. Our results underscore the potential of translation-based prompting strategies to significantly improve multilingual LLM performance in low-resource languages offering valuable insights for future research and applications. We specifically see the highest accuracy improvements with the hate speech detection task. The technique also has the potential to enhance the quality of synthetic data generation for underrepresented languages using LLMs.
