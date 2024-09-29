---
layout: publication
title: A Fine45;tuning Dataset And Benchmark For Large Language Models For Protein Understanding
authors: Shen Yiqing, Chen Zan, Mamalakis Michail, He Luhan, Xia Haiyang, Li Tianbin, Su Yanzhou, He Junjun, Wang Yu Guang
conference: "Arxiv"
year: 2024
bibkey: shen2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.05540"}
tags: ['Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
The parallels between protein sequences and natural language in their sequential structures have inspired the application of large language models (LLMs) to protein understanding. Despite the success of LLMs in NLP their effectiveness in comprehending protein sequences remains an open question largely due to the absence of datasets linking protein sequences to descriptive text. Researchers have then attempted to adapt LLMs for protein understanding by integrating a protein sequence encoder with a pre45;trained LLM. However this adaptation raises a fundamental question Can LLMs originally designed for NLP effectively comprehend protein sequences as a form of language Current datasets fall short in addressing this question due to the lack of a direct correlation between protein sequences and corresponding text descriptions limiting the ability to train and evaluate LLMs for protein understanding effectively. To bridge this gap we introduce ProteinLMDataset a dataset specifically designed for further self45;supervised pretraining and supervised fine45;tuning (SFT) of LLMs to enhance their capability for protein sequence comprehension. Specifically ProteinLMDataset includes 17.46 billion tokens for pretraining and 893000 instructions for SFT. Additionally we present ProteinLMBench the first benchmark dataset consisting of 944 manually verified multiple45;choice questions for assessing the protein understanding capabilities of LLMs. ProteinLMBench incorporates protein45;related details and sequences in multiple languages establishing a new standard for evaluating LLMs abilities in protein comprehension. The large language model InternLM245;7B pretrained and fine45;tuned on the ProteinLMDataset outperforms GPT45;4 on ProteinLMBench achieving the highest accuracy score.
