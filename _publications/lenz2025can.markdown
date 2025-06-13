---
layout: publication
title: 'Can Open Source Large Language Models Be Used For Tumor Documentation In Germany? -- An Evaluation On Urological Doctors'' Notes'
authors: Stefan Lenz, Arsenij Ustjanzew, Marco Jeray, Meike Ressing, Torsten Panholzer
conference: "Arxiv"
year: 2025
bibkey: lenz2025can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.12106"}
  - {name: "Code", url: "https://github.com/stefan-m-lenz/UroLlmEval"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Few-Shot', 'Tools', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Prompting', 'In-Context Learning']
---
Tumor documentation in Germany is largely done manually, requiring reading patient records and entering data into structured databases. Large language models (LLMs) could potentially enhance this process by improving efficiency and reliability. This evaluation tests eleven different open source LLMs with sizes ranging from 1-70 billion model parameters on three basic tasks of the tumor documentation process: identifying tumor diagnoses, assigning ICD-10 codes, and extracting the date of first diagnosis. For evaluating the LLMs on these tasks, a dataset of annotated text snippets based on anonymized doctors' notes from urology was prepared. Different prompting strategies were used to investigate the effect of the number of examples in few-shot prompting and to explore the capabilities of the LLMs in general. The models Llama 3.1 8B, Mistral 7B, and Mistral NeMo 12 B performed comparably well in the tasks. Models with less extensive training data or having fewer than 7 billion parameters showed notably lower performance, while larger models did not display performance gains. Examples from a different medical domain than urology could also improve the outcome in few-shot prompting, which demonstrates the ability of LLMs to handle tasks needed for tumor documentation. Open source LLMs show a strong potential for automating tumor documentation. Models from 7-12 billion parameters could offer an optimal balance between performance and resource efficiency. With tailored fine-tuning and well-designed prompting, these models might become important tools for clinical documentation in the future. The code for the evaluation is available from https://github.com/stefan-m-lenz/UroLlmEval. We also release the dataset as a new valuable resource that addresses the shortage of authentic and easily accessible benchmarks in German-language medical NLP.
