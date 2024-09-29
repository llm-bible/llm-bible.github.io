---
layout: publication
title: Larimar Large Language Models with Episodic Memory Control
authors: Das Payel, Chaudhury Subhajit, Nelson Elliot, Melnyk Igor, Swaminathan Sarath, Dai Sihui, Lozano Aurélie, Kollias Georgios, Chenthamarakshan Vijil, Jiří, Navrátil, Dan Soham, Chen Pin-yu
conference: "Arxiv"
year: 2024
bibkey: das2024larimar
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.11901"}
  - {name: "Code", url: "https://github.com/IBM/larimar"}
tags: ['Fine Tuning', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Efficient and accurate updating of knowledge stored in Large Language Models (LLMs) is one of the most pressing research challenges today. This paper presents Larimar - a novel brain-inspired architecture for enhancing LLMs with a distributed episodic memory. Larimars memory allows for dynamic one-shot updates of knowledge without the need for computationally expensive re-training or fine-tuning. Experimental results on multiple fact editing benchmarks demonstrate that Larimar attains accuracy comparable to most competitive baselines even in the challenging sequential editing setup but also excels in speed - yielding speed-ups of 8-10x depending on the base LLM - as well as flexibility due to the proposed architecture being simple LLM-agnostic and hence general. We further provide mechanisms for selective fact forgetting information leakage prevention and input context length generalization with Larimar and show their effectiveness. Our code is available at https://github.com/IBM/larimar
