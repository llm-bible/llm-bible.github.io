---
layout: publication
title: Low-Resource Languages Jailbreak GPT-4
authors: Yong Zheng-xin, Menghini Cristina, Bach Stephen H.
conference: "Arxiv"
year: 2023
bibkey: yong2023low
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.02446"}
tags: ['ARXIV', 'Applications', 'GPT', 'LLM', 'RAG', 'Responsible AI', 'Security', 'Tools', 'Training Techniques']
---
AI safety training and red-teaming of large language models (LLMs) are measures to mitigate the generation of unsafe content. Our work exposes the inherent cross-lingual vulnerability of these safety mechanisms resulting from the linguistic inequality of safety training data by successfully circumventing GPT-4s safeguard through translating unsafe English inputs into low-resource languages. On the AdvBenchmark GPT-4 engages with the unsafe translated inputs and provides actionable items that can get the users towards their harmful goals 79 of the time which is on par with or even surpassing state-of-the-art jailbreaking attacks. Other high-/mid-resource languages have significantly lower attack success rate which suggests that the cross-lingual vulnerability mainly applies to low-resource languages. Previously limited training on low-resource languages primarily affects speakers of those languages causing technological disparities. However our work highlights a crucial shift this deficiency now poses a risk to all LLMs users. Publicly available translation APIs enable anyone to exploit LLMs safety vulnerabilities. Therefore our work calls for a more holistic red-teaming efforts to develop robust multilingual safeguards with wide language coverage.
