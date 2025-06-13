---
layout: publication
title: 'AI-TA: Towards An Intelligent Question-answer Teaching Assistant Using Open-source Llms'
authors: Yann Hicke, Anmol Agarwal, Qianou Ma, Paul Denny
conference: "NeurIPS Workshop on Generative AI for Education (GAIED) 2023"
year: 2023
bibkey: hicke2023ai
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.02775"}
tags: ['Fine-Tuning', 'Tools', 'Efficiency and Optimization', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Responding to the thousands of student questions on online QA platforms each
semester has a considerable human cost, particularly in computing courses with
rapidly growing enrollments. To address the challenges of scalable and
intelligent question-answering (QA), we introduce an innovative solution that
leverages open-source Large Language Models (LLMs) from the LLaMA-2 family to
ensure data privacy. Our approach combines augmentation techniques such as
retrieval augmented generation (RAG), supervised fine-tuning (SFT), and
learning from human preferences data using Direct Preference Optimization
(DPO). Through extensive experimentation on a Piazza dataset from an
introductory CS course, comprising 10,000 QA pairs and 1,500 pairs of
preference data, we demonstrate a significant 30% improvement in the quality of
answers, with RAG being a particularly impactful addition. Our contributions
include the development of a novel architecture for educational QA, extensive
evaluations of LLM performance utilizing both human assessments and LLM-based
metrics, and insights into the challenges and future directions of educational
data processing. This work paves the way for the development of AI-TA, an
intelligent QA assistant customizable for courses with an online QA platform
