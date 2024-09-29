---
layout: publication
title: Distilrr Transferring Code Repair For Low45;resource Programming Languages
authors: Wong Kyle, Amayuelas Alfonso, Pan Liangming, Wang William Yang
conference: "Arxiv"
year: 2024
bibkey: wong2024transferring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14867"}
tags: ['Applications', 'Tools']
---
Large language models (LLMs) have shown remarkable performance on code generation tasks. A recent application of LLMs for code generation is iterative code repair where a model fixes an incorrect program by rationalizing about errors and generating a new program. However code repair is primarily studied on high45;resource languages like Python and the frameworks efficacy is under45;explored on low45;resource languages. To apply code repair for low45;resource languages we propose Distilling Low45;Resource Repairs (DistiLRR) an approach that transfers the reasoning and code generation ability from a teacher model to a student model. Our results show that DistiLRR consistently outperforms baselines on low45;resource languages but has similar performance on high45;resource languages. To investigate this behavior we perform a further analysis and find that the correlation between rationale quality and code correctness is weaker than previously perceived. We hypothesize this weakness is magnified in low45;resource settings where base models lack deep knowledge of a programming language leading to wavering benefits of code repair between high45;resource and low45;resource languages.
