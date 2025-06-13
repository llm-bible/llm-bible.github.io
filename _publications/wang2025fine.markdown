---
layout: publication
title: 'Fine-tuning Open-source Large Language Models To Improve Their Performance On Radiation Oncology Tasks: A Feasibility Study To Investigate Their Potential Clinical Applications In Radiation Oncology'
authors: Peilong Wang, Zhengliang Liu, Yiwei Li, Jason Holmes, Peng Shu, Lian Zhang, Xiang Li, Quanzheng Li, Brady S. Laughlin, Diego Santos Toesca, Sujay A. Vora, Samir H. Patel, Terence T. Sio, Tianming Liu, Wei Liu
conference: "Arxiv"
year: 2025
bibkey: wang2025fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.17286"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Background: The radiation oncology clinical practice involves many steps
relying on the dynamic interplay of abundant text data. Large language models
have displayed remarkable capabilities in processing complex text information.
But their direct applications in specific fields like radiation oncology remain
underexplored.
  Purpose: This study aims to investigate whether fine-tuning LLMs with domain
knowledge can improve the performance on Task (1) treatment regimen generation,
Task (2) treatment modality selection (photon, proton, electron, or
brachytherapy), and Task (3) ICD-10 code prediction in radiation oncology.
  Methods: Data for 15,724 patient cases were extracted. Cases where patients
had a single diagnostic record, and a clearly identifiable primary treatment
plan were selected for preprocessing and manual annotation to have 7,903 cases
of the patient diagnosis, treatment plan, treatment modality, and ICD-10 code.
Each case was used to construct a pair consisting of patient diagnostics
details and an answer (treatment regimen, treatment modality, or ICD-10 code
respectively) for the supervised fine-tuning of these three tasks. Open source
LLaMA2-7B and Mistral-7B models were utilized for the fine-tuning with the
Low-Rank Approximations method. Accuracy and ROUGE-1 score were reported for
the fine-tuned models and original models. Clinical evaluation was performed on
Task (1) by radiation oncologists, while precision, recall, and F-1 score were
evaluated for Task (2) and (3). One-sided Wilcoxon signed-rank tests were used
to statistically analyze the results.
  Results: Fine-tuned LLMs outperformed original LLMs across all tasks with
p-value <= 0.001. Clinical evaluation demonstrated that over 60% of the
fine-tuned LLMs-generated treatment regimens were clinically acceptable.
Precision, recall, and F1-score showed improved performance of fine-tuned LLMs.
