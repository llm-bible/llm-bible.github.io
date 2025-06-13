---
layout: publication
title: 'Do You See Me : A Multidimensional Benchmark For Evaluating Visual Perception In Multimodal Llms'
authors: Aditya Kanade, Tanuja Ganu
conference: "Arxiv"
year: 2025
bibkey: kanade2025do
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.02022"}
  - {name: "Code", url: "https://github.com/microsoft/Do-You-See-Me"}
tags: ['Multimodal Models', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'Has Code', 'Attention Mechanism']
---
Multimodal Large Language Models (MLLMs) show reasoning promise, yet their visual perception is a critical bottleneck. Strikingly, MLLMs can produce correct answers even while misinterpreting crucial visual elements, masking these underlying failures. Our preliminary study on a joint perception-reasoning dataset revealed that for one leading MLLM, 29% of its correct answers to reasoning questions still exhibited visual perception errors. To systematically address this, we introduce "Do You See Me", a scalable benchmark with 1,758 images and 2,612 questions. It spans seven human-psychology inspired subtasks in 2D and 3D, featuring controllable complexity to rigorously evaluate MLLM visual skills. Our findings on 3 leading closed-source and 5 major open-source models reveal a stark deficit: humans achieve 96.49% accuracy, while top MLLMs average below 50%. This performance gap widens rapidly with increased task complexity (e.g., from 12% to 45% in the visual form constancy subtask). Further analysis into the root causes suggests that failures stem from challenges like misallocated visual attention and the instability of internal representations for fine-grained details, especially at or below encoder patch resolution. This underscores an urgent need for MLLMs with truly robust visual perception. The benchmark dataset, source code and evaluation scripts are available at https://github.com/microsoft/Do-You-See-Me.
