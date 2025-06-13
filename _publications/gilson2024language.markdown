---
layout: publication
title: 'Language Enhanced Model For Eye (LEME): An Open-source Ophthalmology-specific Large Language Model'
authors: Aidan Gilson, Xuguang Ai, Qianqian Xie, Sahana Srinivasan, Krithi Pushpanathan, Maxwell B. Singer, Jimin Huang, Hyunjae Kim, Erping Long, Peixing Wan, Luciano V. Del Priore, Lucila Ohno-machado, Hua Xu, Dianbo Liu, Ron A. Adelman, Yih-chung Tham, Qingyu Chen
conference: "Arxiv"
year: 2024
bibkey: gilson2024language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.03740"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Large Language Models (LLMs) are poised to revolutionize healthcare.
Ophthalmology-specific LLMs remain scarce and underexplored. We introduced an
open-source, specialized LLM for ophthalmology, termed Language Enhanced Model
for Eye (LEME). LEME was initially pre-trained on the Llama2 70B framework and
further fine-tuned with a corpus of ~127,000 non-copyrighted training instances
curated from ophthalmology-specific case reports, abstracts, and open-source
study materials. We benchmarked LEME against eight other LLMs, namely, GPT-3.5,
GPT-4, three Llama2 models (7B, 13B, 70B), PMC-LLAMA 13B, Meditron 70B, and
EYE-Llama (another ophthalmology-specific LLM). Evaluations included four
internal validation tasks: abstract completion, fill-in-the-blank,
multiple-choice questions (MCQ), and short-answer QA. External validation tasks
encompassed long-form QA, MCQ, patient EHR summarization, and clinical QA.
Evaluation metrics included Rouge-L scores, accuracy, and expert evaluation of
correctness, completeness, and readability. In internal validations, LEME
consistently outperformed its counterparts, achieving Rouge-L scores of 0.20 in
abstract completion (all p<0.05), 0.82 in fill-in-the-blank (all p<0.0001), and
0.22 in short-answer QA (all p<0.0001, except versus GPT-4). In external
validations, LEME excelled in long-form QA with a Rouge-L of 0.19 (all
p<0.0001), ranked second in MCQ accuracy (0.68; all p<0.0001), and scored
highest in EHR summarization and clinical QA (ranging from 4.24 to 4.83 out of
5 for correctness, completeness, and readability).
  LEME's emphasis on robust fine-tuning and the use of non-copyrighted data
represents a breakthrough in open-source ophthalmology-specific LLMs, offering
the potential to revolutionize execution of clinical tasks while democratizing
research collaboration.
