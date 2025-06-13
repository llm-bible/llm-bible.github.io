---
layout: publication
title: 'A Fine-tuning Dataset And Benchmark For Large Language Models For Protein Understanding'
authors: Yiqing Shen, Zan Chen, Michail Mamalakis, Luhan He, Haiyang Xia, Tianbin Li, Yanzhou Su, Junjun He, Yu Guang Wang
conference: "Arxiv"
year: 2024
bibkey: shen2024fine
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.05540'}
tags: ['Training Techniques', 'Model Architecture', 'GPT', 'Fine-Tuning', 'Pretraining Methods']
---
The parallels between protein sequences and natural language in their
sequential structures have inspired the application of large language models
(LLMs) to protein understanding. Despite the success of LLMs in NLP, their
effectiveness in comprehending protein sequences remains an open question,
largely due to the absence of datasets linking protein sequences to descriptive
text. Researchers have then attempted to adapt LLMs for protein understanding
by integrating a protein sequence encoder with a pre-trained LLM. However, this
adaptation raises a fundamental question: "Can LLMs, originally designed for
NLP, effectively comprehend protein sequences as a form of language?" Current
datasets fall short in addressing this question due to the lack of a direct
correlation between protein sequences and corresponding text descriptions,
limiting the ability to train and evaluate LLMs for protein understanding
effectively. To bridge this gap, we introduce ProteinLMDataset, a dataset
specifically designed for further self-supervised pretraining and supervised
fine-tuning (SFT) of LLMs to enhance their capability for protein sequence
comprehension. Specifically, ProteinLMDataset includes 17.46 billion tokens for
pretraining and 893,000 instructions for SFT. Additionally, we present
ProteinLMBench, the first benchmark dataset consisting of 944 manually verified
multiple-choice questions for assessing the protein understanding capabilities
of LLMs. ProteinLMBench incorporates protein-related details and sequences in
multiple languages, establishing a new standard for evaluating LLMs' abilities
in protein comprehension. The large language model InternLM2-7B, pretrained and
fine-tuned on the ProteinLMDataset, outperforms GPT-4 on ProteinLMBench,
achieving the highest accuracy score.
