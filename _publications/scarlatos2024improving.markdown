---
layout: publication
title: "Improving The Validity Of Automatically Generated Feedback Via Reinforcement Learning"
authors: Scarlatos Alexander, Smith Digory, Woodhead Simon, Lan Andrew
conference: "Arxiv"
year: 2024
bibkey: scarlatos2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.01304"}
tags: ['Agentic', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Automatically generating feedback via large language models (LLMs) in intelligent tutoring systems and online learning platforms has the potential to improve the learning outcomes of many students. However both feedback generation and evaluation are challenging feedback content has to be valid especially in subjects like math which requires models to understand the problem the solution and where the students error lies. Feedback also has to be pedagogically valid to reflect effective tutoring strategies such as explaining possible misconceptions and encouraging the student among other desirable features. In this work we address both problems of automatically generating and evaluating feedback while considering both correctness and alignment. First we propose a rubric for evaluating math feedback and show that GPT-4 is able to effectively use it to annotate human-written and LLM-generated feedback. Second we propose a framework for feedback generation that optimizes both correctness and alignment using reinforcement learning (RL). Specifically we use GPT-4s annotations to create preferences over feedback pairs in an augmented dataset for training via direct preference optimization (DPO). We show that our methods significantly increase the correctness and alignment of generated feedback with Llama 2 an open-source LLM qualitatively analyze our generation and evaluation systems using case studies and outline several areas for future work.
