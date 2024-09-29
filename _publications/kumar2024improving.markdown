---
layout: publication
title: Improving Socratic Question Generation Using Data Augmentation And Preference Optimization
authors: Kumar Nischal Ashok, Lan Andrew
conference: "Arxiv"
year: 2024
bibkey: kumar2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.00199"}
tags: ['Agentic', 'Efficiency And Optimization', 'Prompting', 'Reinforcement Learning']
---
The Socratic method is a way of guiding students toward solving a problem independently without directly revealing the solution to the problem. Although this method has been shown to significantly improve student learning outcomes it remains a complex labor45;intensive task for instructors. Large language models (LLMs) can be used to augment human effort by automatically generating Socratic questions for students. However existing methods that involve prompting these LLMs sometimes produce invalid outputs e.g. those that directly reveal the solution to the problem or provide irrelevant or premature questions. To alleviate this problem inspired by reinforcement learning with AI feedback (RLAIF) we first propose a data augmentation method to enrich existing Socratic questioning datasets with questions that are invalid in specific ways. Next we propose a method to optimize open45;source LLMs such as LLama 2 to prefer ground45;truth questions over generated invalid ones using direct preference optimization (DPO). Our experiments on a Socratic questions dataset for student code debugging show that a DPO45;optimized 7B LLama 2 model can effectively avoid generating invalid questions and as a result outperforms existing state45;of45;the45;art prompting methods.
