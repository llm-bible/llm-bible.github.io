---
layout: publication
title: 'DOTS: Learning To Reason Dynamically In Llms Via Optimal Reasoning Trajectories Search'
authors: Murong Yue, Wenlin Yao, Haitao Mi, Dian Yu, Ziyu Yao, Dong Yu
conference: "Arxiv"
year: 2024
bibkey: yue2024learning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.03864'}
tags: ['Attention Mechanism', 'Training Techniques', 'Model Architecture', 'Fine-Tuning', 'Prompting', 'Pretraining Methods']
---
Enhancing the capability of large language models (LLMs) in reasoning has
gained significant attention in recent years. Previous studies have
demonstrated the effectiveness of various prompting strategies in aiding LLMs
in reasoning (called "reasoning actions"), such as step-by-step thinking,
reflecting before answering, solving with programs, and their combinations.
However, these approaches often applied static, predefined reasoning actions
uniformly to all questions, without considering the specific characteristics of
each question or the capability of the task-solving LLM. In this paper, we
propose DOTS, an approach enabling LLMs to reason dynamically via optimal
reasoning trajectory search, tailored to the specific characteristics of each
question and the inherent capability of the task-solving LLM. Our approach
involves three key steps: i) defining atomic reasoning action modules that can
be composed into various reasoning action trajectories; ii) searching for the
optimal action trajectory for each training question through iterative
exploration and evaluation for the specific task-solving LLM; and iii) using
the collected optimal trajectories to train an LLM to plan for the reasoning
trajectories of unseen questions. In particular, we propose two learning
paradigms, i.e., fine-tuning an external LLM as a planner to guide the
task-solving LLM, or directly fine-tuning the task-solving LLM with an
internalized capability for reasoning actions planning. Our experiments across
eight reasoning tasks show that our method consistently outperforms static
reasoning techniques and the vanilla instruction tuning approach. Further
analysis reveals that our method enables LLMs to adjust their computation based
on problem complexity, allocating deeper thinking and reasoning to harder
problems.
