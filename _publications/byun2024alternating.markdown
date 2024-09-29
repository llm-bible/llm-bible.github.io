---
layout: publication
title: ARES Alternating Reinforcement Learning And Supervised Fine45;tuning For Enhanced Multi45;modal Chain45;of45;thought Reasoning Through Diverse AI Feedback
authors: Byun Ju-seung, Chun Jiyun, Kil Jihyung, Perrault Andrew
conference: "Arxiv"
year: 2024
bibkey: byun2024alternating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.00087"}
tags: ['Agentic', 'Fine Tuning', 'GPT', 'Model Architecture', 'Multimodal Models', 'RAG', 'Reinforcement Learning']
---
Large Multimodal Models (LMMs) excel at comprehending human instructions and demonstrate remarkable results across a broad spectrum of tasks. Reinforcement Learning from Human Feedback (RLHF) and AI Feedback (RLAIF) further refine LLMs by aligning them with specific preferences. These methods primarily use ranking45;based feedback for entire generations. With advanced AI models (Teacher) such as GPT45;4 and Claude 3 Opus we can request various types of detailed feedback that are expensive for humans to provide. We propose a two45;stage algorithm ARES that Alternates REinforcement Learning (RL) and Supervised Fine45;Tuning (SFT). First we request the Teacher to score how much each sentence contributes to solving the problem in a Chain45;of45;Thought (CoT). This sentence45;level feedback allows us to consider individual valuable segments providing more granular rewards for the RL procedure. Second we ask the Teacher to correct the wrong reasoning after the RL stage. The RL procedure requires massive efforts for hyperparameter tuning and often generates errors like repetitive words and incomplete sentences. With the correction feedback we stabilize the RL fine45;tuned model through SFT. We conduct experiments on multi45;model dataset ScienceQA and A45;OKVQA to demonstrate the effectiveness of our proposal. ARES rationale reasoning achieves around 7037; win rate against baseline models judged by GPT45;4o. Additionally we observe that the improved rationale reasoning leads to a 2.537; increase in inference answer accuracy on average for the multi45;modal datasets.
