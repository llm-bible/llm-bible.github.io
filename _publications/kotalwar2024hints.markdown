---
layout: publication
title: Hints-in-browser\: Benchmarking Language Models For Programming Feedback Generation
authors: Kotalwar Nachiket, Gotovos Alkis, Singla Adish
conference: "Arxiv"
year: 2024
bibkey: kotalwar2024hints
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.05053"}
tags: ['Applications', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Quantization', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Generative AI and large language models hold great promise in enhancing programming education by generating individualized feedback and hints for learners. Recent works have primarily focused on improving the quality of generated feedback to achieve human tutors quality. While quality is an important performance criterion it is not the only criterion to optimize for real-world educational deployments. In this paper we benchmark language models for programming feedback generation across several performance criteria including quality cost time and data privacy. The key idea is to leverage recent advances in the new paradigm of in-browser inference that allow running these models directly in the browser thereby providing direct benefits across cost and data privacy. To boost the feedback quality of small models compatible with in-browser inference engines we develop a fine-tuning pipeline based on GPT-4 generated synthetic data. We showcase the efficacy of fine-tuned Llama3-8B and Phi3-3.8B 4-bit quantized models using WebLLMs in-browser inference engine on three different Python programming datasets. We will release the full implementation along with a web app and datasets to facilitate further research on in-browser language models.
