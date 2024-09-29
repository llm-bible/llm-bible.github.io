---
layout: publication
title: Educating Llms Like Human Students Structure45;aware Injection Of Domain Knowledge
authors: Liu Kai, Chen Ze, Fu Zhihang, Jiang Rongxin, Zhou Fan, Chen Yaowu, Wu Yue, Ye Jieping
conference: "Arxiv"
year: 2024
bibkey: liu2024educating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.16724"}
tags: ['Applications', 'Fine Tuning', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
This paper presents a pioneering methodology termed StructTuning to efficiently transform foundation Large Language Models (LLMs) into domain specialists. It significantly minimizes the training corpus requirement to a mere 0.337; while achieving an impressive 5037; of traditional knowledge injection performance. Our method is inspired by the educational processes for human students particularly how structured domain knowledge from textbooks is absorbed and then applied to tackle real45;world challenges through specific exercises. Based on this we propose a novel two45;stage knowledge injection strategy Structure45;aware Continual Pre45;Training (SCPT) and Structure45;aware Supervised Fine45;Tuning (SSFT). In the SCPT phase we organize the training data into an auto45;generated taxonomy of domain knowledge enabling LLMs to effectively memorize textual segments linked to specific expertise within the taxonomys architecture. Subsequently in the SSFT phase we explicitly prompt models to reveal the underlying knowledge structure in their outputs leveraging this structured domain insight to address practical problems adeptly. Our ultimate method has undergone extensive evaluations across model architectures and scales using closed45;book question45;answering tasks on LongBench and MMedBench datasets. Remarkably our method matches 5037; of the improvement displayed by the state45;of45;the45;art MMedLM2 on MMedBench but with only 0.337; quantity of the training corpus. This breakthrough showcases the potential to scale up our StructTuning for stronger domain45;specific LLMs. Code will be made public soon.
