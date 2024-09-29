---
layout: publication
title: 'Hierarchical Prompting Taxonomy: A Universal Evaluation Framework For Large Language Models'
authors: Budagam Devichand, Kj Sankalp, Kumar Ashutosh, Jain Vinija, Chadha Aman
conference: "Arxiv"
year: 2024
bibkey: budagam2024hierarchical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12644"}
tags: ['Pretraining Methods', 'Prompting', 'Tools']
---
Assessing the effectiveness of large language models (LLMs) in addressing diverse tasks is essential for comprehending their strengths and weaknesses. Conventional evaluation techniques typically apply a single prompting strategy uniformly across datasets not considering the varying degrees of task complexity. We introduce the Hierarchical Prompting Taxonomy (HPT) a taxonomy that employs a Hierarchical Prompt Framework (HPF) composed of five unique prompting strategies arranged from the simplest to the most complex to assess LLMs more precisely and to offer a clearer perspective. This taxonomy assigns a score called the Hierarchical Prompting Score (HP-Score) to datasets as well as LLMs based on the rules of the taxonomy providing a nuanced understanding of their ability to solve diverse tasks and offering a universal measure of task complexity. Additionally we introduce the Adaptive Hierarchical Prompt framework which automates the selection of appropriate prompting strategies for each task. This study compares manual and adaptive hierarchical prompt frameworks using four instruction-tuned LLMs namely Llama 3 8B Phi 3 3.8B Mistral 7B and Gemma 7B across four datasets BoolQ CommonSenseQA (CSQA) IWSLT-2017 en-fr (IWSLT) and SamSum. Experiments demonstrate the effectiveness of HPT providing a reliable way to compare different tasks and LLM capabilities. This paper leads to the development of a universal evaluation metric that can be used to evaluate both the complexity of the datasets and the capabilities of LLMs. The implementation of both manual HPF and adaptive HPF is publicly available.
