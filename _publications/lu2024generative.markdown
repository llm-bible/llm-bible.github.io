---
layout: publication
title: "Generative Students: Using Llm-simulated Student Profiles To Support Question Item Evaluation"
authors: Lu Xinyi, Wang Xu
conference: "Arxiv"
year: 2024
bibkey: lu2024generative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.11591"}
tags: ['GPT', 'Merging', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools']
---
Evaluating the quality of automatically generated question items has been a long standing challenge. In this paper we leverage LLMs to simulate student profiles and generate responses to multiple-choice questions (MCQs). The generative students responses to MCQs can further support question item evaluation. We propose Generative Students a prompt architecture designed based on the KLI framework. A generative student profile is a function of the list of knowledge components the student has mastered has confusion about or has no evidence of knowledge of. We instantiate the Generative Students concept on the subject domain of heuristic evaluation. We created 45 generative students using GPT-4 and had them respond to 20 MCQs. We found that the generative students produced logical and believable responses that were aligned with their profiles. We then compared the generative students responses to real students responses on the same set of MCQs and found a high correlation. Moreover there was considerable overlap in the difficult questions identified by generative students and real students. A subsequent case study demonstrated that an instructor could improve question quality based on the signals provided by Generative Students.
