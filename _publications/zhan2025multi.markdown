---
layout: publication
title: 'MMRAG: Multi-mode Retrieval-augmented Generation With Large Language Models For Biomedical In-context Learning'
authors: Zaifu Zhan, Jun Wang, Shuang Zhou, Jiawen Deng, Rui Zhang
conference: "Arxiv"
year: 2025
bibkey: zhan2025multi
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.15954'}
tags: ['RAG', 'Applications', 'Tools', 'Prompting', 'In-Context Learning']
---
Objective: To optimize in-context learning in biomedical natural language
processing by improving example selection. Methods: We introduce a novel
multi-mode retrieval-augmented generation (MMRAG) framework, which integrates
four retrieval strategies: (1) Random Mode, selecting examples arbitrarily; (2)
Top Mode, retrieving the most relevant examples based on similarity; (3)
Diversity Mode, ensuring variation in selected examples; and (4) Class Mode,
selecting category-representative examples. This study evaluates MMRAG on three
core biomedical NLP tasks: Named Entity Recognition (NER), Relation Extraction
(RE), and Text Classification (TC). The datasets used include BC2GM for gene
and protein mention recognition (NER), DDI for drug-drug interaction extraction
(RE), GIT for general biomedical information extraction (RE), and HealthAdvice
for health-related text classification (TC). The framework is tested with two
large language models (Llama2-7B, Llama3-8B) and three retrievers (Contriever,
MedCPT, BGE-Large) to assess performance across different retrieval strategies.
Results: The results from the Random mode indicate that providing more examples
in the prompt improves the model's generation performance. Meanwhile, Top mode
and Diversity mode significantly outperform Random mode on the RE (DDI) task,
achieving an F1 score of 0.9669, a 26.4% improvement. Among the three
retrievers tested, Contriever outperformed the other two in a greater number of
experiments. Additionally, Llama 2 and Llama 3 demonstrated varying
capabilities across different tasks, with Llama 3 showing a clear advantage in
handling NER tasks. Conclusion: MMRAG effectively enhances biomedical
in-context learning by refining example selection, mitigating data scarcity
issues, and demonstrating superior adaptability for NLP-driven healthcare
applications.
