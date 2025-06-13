---
layout: publication
title: 'Lab-ai: Using Retrieval Augmentation To Enhance Language Models For Personalized Lab Test Interpretation In Clinical Medicine'
authors: Xiaoyu Wang, Haoyong Ouyang, Balu Bhasuran, Xiao Luo, Karim Hanna, Mia Liza A. Lustria, Carl Yang, Zhe He
conference: "Arxiv"
year: 2024
bibkey: wang2024lab
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.18986"}
tags: ['RAG', 'Model Architecture', 'GPT']
---
Accurate interpretation of lab results is crucial in clinical medicine, yet
most patient portals use universal normal ranges, ignoring conditional factors
like age and gender. This study introduces Lab-AI, an interactive system that
offers personalized normal ranges using retrieval-augmented generation (RAG)
from credible health sources. Lab-AI has two modules: factor retrieval and
normal range retrieval. We tested these on 122 lab tests: 40 with conditional
factors and 82 without. For tests with factors, normal ranges depend on
patient-specific information. Our results show GPT-4-turbo with RAG achieved a
0.948 F1 score for factor retrieval and 0.995 accuracy for normal range
retrieval. GPT-4-turbo with RAG outperformed the best non-RAG system by 33.5%
in factor retrieval and showed 132% and 100% improvements in question-level and
lab-level performance, respectively, for normal range retrieval. These findings
highlight Lab-AI's potential to enhance patient understanding of lab results.
