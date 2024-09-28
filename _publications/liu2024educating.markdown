---
layout: publication
title: Educating LLMs like Human Students Structure-aware Injection of Domain Knowledge
authors: Liu Kai, Chen Ze, Fu Zhihang, Jiang Rongxin, Zhou Fan, Chen Yaowu, Wu Yue, Ye Jieping
conference: "Arxiv"
year: 2024
bibkey: liu2024educating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.16724"}
tags: ['ARXIV', 'Fine Tuning', 'LLM', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning']
---
This paper presents a pioneering methodology termed StructTuning to efficiently transform foundation Large Language Models (LLMs) into domain specialists. It significantly minimizes the training corpus requirement to a mere 0.3 while achieving an impressive 50 of traditional knowledge injection performance. Our method is inspired by the educational processes for human students particularly how structured domain knowledge from textbooks is absorbed and then applied to tackle real-world challenges through specific exercises. Based on this we propose a novel two-stage knowledge injection strategy Structure-aware Continual Pre-Training (SCPT) and Structure-aware Supervised Fine-Tuning (SSFT). In the SCPT phase we organize the training data into an auto-generated taxonomy of domain knowledge enabling LLMs to effectively memorize textual segments linked to specific expertise within the taxonomys architecture. Subsequently in the SSFT phase we explicitly prompt models to reveal the underlying knowledge structure in their outputs leveraging this structured domain insight to address practical problems adeptly. Our ultimate method has undergone extensive evaluations across model architectures and scales using closed-book question-answering tasks on LongBench and MMedBench datasets. Remarkably our method matches 50 of the improvement displayed by the state-of-the-art MMedLM2 on MMedBench but with only 0.3 quantity of the training corpus. This breakthrough showcases the potential to scale up our StructTuning for stronger domain-specific LLMs. Code will be made public soon.
