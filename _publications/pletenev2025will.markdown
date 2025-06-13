---
layout: publication
title: 'Will It Still Be True Tomorrow? Multilingual Evergreen Question Classification To Improve Trustworthy QA'
authors: Sergey Pletenev, Maria Marina, Nikolay Ivanov, Daria Galimzianova, Nikita Krayko, Mikhail Salnikov, Vasily Konovalov, Alexander Panchenko, Viktor Moskvoretskii
conference: "Arxiv"
year: 2025
bibkey: pletenev2025will
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.21115'}
tags: ['GPT', 'Model Architecture', 'Applications', 'Training Techniques', 'Reinforcement Learning']
---
Large Language Models (LLMs) often hallucinate in question answering (QA) tasks. A key yet underexplored factor contributing to this is the temporality of questions -- whether they are evergreen (answers remain stable over time) or mutable (answers change). In this work, we introduce EverGreenQA, the first multilingual QA dataset with evergreen labels, supporting both evaluation and training. Using EverGreenQA, we benchmark 12 modern LLMs to assess whether they encode question temporality explicitly (via verbalized judgments) or implicitly (via uncertainty signals). We also train EG-E5, a lightweight multilingual classifier that achieves SoTA performance on this task. Finally, we demonstrate the practical utility of evergreen classification across three applications: improving self-knowledge estimation, filtering QA datasets, and explaining GPT-4o retrieval behavior.
