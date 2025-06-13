---
layout: publication
title: 'Extractgpt: Exploring The Potential Of Large Language Models For Product Attribute Value Extraction'
authors: Alexander Brinkmann, Roee Shraga, Christian Bizer
conference: "Arxiv"
year: 2023
bibkey: brinkmann2023exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.12537"}
tags: ['Fine-Tuning', 'Tools', 'GPT', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'BERT', 'Few-Shot', 'Prompting']
---
E-commerce platforms require structured product data in the form of
attribute-value pairs to offer features such as faceted product search or
attribute-based product comparison. However, vendors often provide unstructured
product descriptions, necessitating the extraction of attribute-value pairs
from these texts. BERT-based extraction methods require large amounts of
task-specific training data and struggle with unseen attribute values. This
paper explores using large language models (LLMs) as a more training-data
efficient and robust alternative. We propose prompt templates for zero-shot and
few-shot scenarios, comparing textual and JSON-based target schema
representations. Our experiments show that GPT-4 achieves the highest average
F1-score of 85% using detailed attribute descriptions and demonstrations.
Llama-3-70B performs nearly as well, offering a competitive open-source
alternative. GPT-4 surpasses the best PLM baseline by 5% in F1-score.
Fine-tuning GPT-3.5 increases the performance to the level of GPT-4 but reduces
the model's ability to generalize to unseen attribute values.
