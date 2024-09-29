---
layout: publication
title: Documint Docstring Generation For Python Using Small Language Models
authors: Poudel Bibek, Cook Adam, Traore Sekou, Ameli Shelah
conference: "Arxiv"
year: 2024
bibkey: poudel2024docstring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.10243"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Effective communication specifically through documentation is the beating heart of collaboration among contributors in software development. Recent advancements in language models (LMs) have enabled the introduction of a new type of actor in that ecosystem LM-powered assistants capable of code generation optimization and maintenance. Our study investigates the efficacy of small language models (SLMs) for generating high-quality docstrings by assessing accuracy conciseness and clarity benchmarking performance quantitatively through mathematical formulas and qualitatively through human evaluation using Likert scale. Further we introduce DocuMint as a large-scale supervised fine-tuning dataset with 100000 samples. In quantitative experiments Llama 3 8B achieved the best performance across all metrics with conciseness and clarity scores of 0.605 and 64.88 respectively. However under human evaluation CodeGemma 7B achieved the highest overall score with an average of 8.3 out of 10 across all metrics. Fine-tuning the CodeGemma 2B model using the DocuMint dataset led to significant improvements in performance across all metrics with gains of up to 22.537; in conciseness. The fine-tuned model and the dataset can be found in HuggingFace and the code can be found in the repository.
