---
layout: publication
title: Domain45;specific Code Language Models Unraveling The Potential For HPC Codes And Tasks
authors: Kadosh Tal, Hasabnis Niranjan, Vo Vy A., Schneider Nadav, Krien Neva, Capota Mihai, Wasay Abdul, Ahmed Nesreen, Willke Ted, Tamir Guy, Pinter Yuval, Mattson Timothy, Oren Gal
conference: "Arxiv"
year: 2023
bibkey: kadosh2023domain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.13322"}
tags: ['Applications', 'GPT', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
With easier access to powerful compute resources there is a growing trend in AI for software development to develop larger language models (LLMs) to address a variety of programming tasks. Even LLMs applied to tasks from the high45;performance computing (HPC) domain are huge in size and demand expensive compute resources for training. This is partly because these LLMs for HPC tasks are obtained by finetuning existing LLMs that support several natural and/or programming languages. We found this design choice confusing 45; why do we need large LMs trained on natural languages and programming languages unrelated to HPC for HPC45;specific tasks In this line of work we aim to question choices made by existing LLMs by developing smaller LMs for specific domains 45; we call them domain45;specific LMs. Specifically we start off with HPC as a domain and build an HPC45;specific LM named MonoCoder that is orders of magnitude smaller than existing LMs but delivers similar if not better performance on non45;HPC and HPC tasks. Specifically we pre45;trained MonoCoder on an HPC45;specific dataset (named HPCorpus) of C and C++ programs mined from GitHub. We evaluated the performance of MonoCoder against conventional multi45;lingual LLMs. Results demonstrate that MonoCoder although much smaller than existing LMs achieves similar results on normalized45;perplexity tests and much better ones in CodeBLEU competence for high45;performance and parallel code generations. Furthermore fine45;tuning the base model for the specific task of parallel code generation (OpenMP parallel for pragmas) demonstrates outstanding results compared to GPT especially when local misleading semantics are removed by our novel pre45;processor Tokompiler showcasing the ability of domain45;specific models to assist in HPC45;relevant tasks.
