---
layout: publication
title: Hints45;in45;browser Benchmarking Language Models For Programming Feedback Generation
authors: Kotalwar Nachiket, Gotovos Alkis, Singla Adish
conference: "Arxiv"
year: 2024
bibkey: kotalwar2024hints
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.05053"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Quantization', 'RAG', 'Reinforcement Learning']
---
Generative AI and large language models hold great promise in enhancing programming education by generating individualized feedback and hints for learners. Recent works have primarily focused on improving the quality of generated feedback to achieve human tutors quality. While quality is an important performance criterion it is not the only criterion to optimize for real45;world educational deployments. In this paper we benchmark language models for programming feedback generation across several performance criteria including quality cost time and data privacy. The key idea is to leverage recent advances in the new paradigm of in45;browser inference that allow running these models directly in the browser thereby providing direct benefits across cost and data privacy. To boost the feedback quality of small models compatible with in45;browser inference engines we develop a fine45;tuning pipeline based on GPT45;4 generated synthetic data. We showcase the efficacy of fine45;tuned Llama345;8B and Phi345;3.8B 445;bit quantized models using WebLLMs in45;browser inference engine on three different Python programming datasets. We will release the full implementation along with a web app and datasets to facilitate further research on in45;browser language models.
