---
layout: publication
title: 'Hdflow: Enhancing LLM Complex Problem-solving With Hybrid Thinking And Dynamic Workflows'
authors: Wenlin Yao, Haitao Mi, Dong Yu
conference: "Arxiv"
year: 2024
bibkey: yao2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.17433"}
  - {name: "Code", url: "https://github.com/wenlinyao/HDFlow}."}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Has Code']
---
Despite recent advancements in large language models (LLMs), their
performance on complex reasoning problems requiring multi-step thinking and
combining various skills is still limited. To address this, we propose a novel
framework HDFlow for complex reasoning with LLMs that combines fast and slow
thinking modes in an adaptive manner. Our approach consists of two key
components: 1) a new approach for slow, deliberate reasoning called Dynamic
Workflow, which automatically decomposes complex problems into more manageable
sub-tasks and dynamically designs a workflow to assemble specialized LLM or
symbolic reasoning tools to solve sub-tasks; 2) Hybrid Thinking, a general
framework that dynamically combines fast and slow thinking based on problem
complexity. Finally, we propose an easy-to-scale method for automatically
synthesizing a large-scale dataset of 27K challenging reasoning problems for
complex reasoning and a hybrid thinking tuning method that trains smaller LLMs
on this dataset to internalize the fast/slow hybrid reasoning strategies.
Experiments on four reasoning benchmark datasets demonstrate that our slow
thinking with dynamic workflows significantly outperforms Chain-of-Thought, and
hybrid thinking achieves the highest accuracy while providing an effective
balance between computational efficiency and performance. Fine-tuning using our
hybrid thinking approach also significantly boosts the complex reasoning
capabilities of open-source language models. The results showcase the promise
of slow thinking, dynamic workflows, and hybrid thinking in expanding the
frontier of complex problem-solving with LLMs\footnote\{Code and data will be
released at \url\{https://github.com/wenlinyao/HDFlow\}.\}.
