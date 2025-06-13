---
layout: publication
title: 'Using GPT-4 To Augment Unbalanced Data For Automatic Scoring'
authors: Luyang Fang, Gyeong-geon Lee, Xiaoming Zhai
conference: "Arxiv"
year: 2023
bibkey: fang2023using
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.18365"}
tags: ['Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'GPT', 'BERT', 'Prompting']
---
Machine learning-based automatic scoring faces challenges with unbalanced
student responses across scoring categories. To address this, we introduce a
novel text data augmentation framework leveraging GPT-4, a generative large
language model, specifically tailored for unbalanced datasets in automatic
scoring. Our experimental dataset comprised student written responses to four
science items. We crafted prompts for GPT-4 to generate responses, especially
for minority scoring classes, enhancing the data set. We then finetuned
DistillBERT for automatic scoring based on the augmented and original datasets.
Model performance was assessed using accuracy, precision, recall, and F1
metrics. Our findings revealed that incorporating GPT-4-augmented data
remarkedly improved model performance, particularly for precision and F1
scores. Interestingly, the extent of improvement varied depending on the
specific dataset and the proportion of augmented data used. Notably, we found
that a varying amount of augmented data (20%-40%) was needed to obtain stable
improvement for automatic scoring. Comparisons with models trained on
additional student-written responses suggest that GPT-4 augmented models match
those trained with student data. This research underscores the potential and
effectiveness of data augmentation techniques utilizing generative large
language models like GPT-4 in addressing unbalanced datasets within automated
assessment.
