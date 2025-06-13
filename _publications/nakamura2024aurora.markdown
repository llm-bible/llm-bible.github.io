---
layout: publication
title: 'Aurora-m: Open Source Continual Pre-training For Multilingual Language And Code'
authors: Taishi Nakamura, Mayank Mishra, Simone Tedeschi, Yekun Chai, Jason T Stillerman, Felix Friedrich, Prateek Yadav, Tanmay Laud, Vu Minh Chien, Terry Yue Zhuo, Diganta Misra, Ben Bogin, Xuan-son Vu, Marzena Karpinska, Arnav Varma Dantuluri, Wojciech Kusa, Tommaso Furlanello, Rio Yokota, Niklas Muennighoff, Suhas Pai, Tosin Adewumi, Veronika Laippala, Xiaozhe Yao, Adalberto Junior, Alpay Ariyak, Aleksandr Drozd, Jordan Clive, Kshitij Gupta, Liangyu Chen, Qi Sun, Ken Tsui, Noah Persaud, Nour Fahmy, Tianlong Chen, Mohit Bansal, Nicolo Monti, Tai Dang, Ziyang Luo, Tien-tung Bui, Roberto Navigli, Virendra Mehta, Matthew Blumberg, Victor May, Huu Nguyen, Sampo Pyysalo
conference: "Arxiv"
year: 2024
bibkey: nakamura2024aurora
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.00399'}
  - {name: "Code", url: 'https://huggingface.co/aurora-m'}
tags: ['Has Code', 'RAG', 'Security', 'Applications', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Pre-Training', 'Responsible AI', 'Pretraining Methods']
---
Pretrained language models are an integral part of AI applications, but their
high computational cost for training limits accessibility. Initiatives such as
Bloom and StarCoder aim to democratize access to pretrained models for
collaborative community development. Despite these efforts, such models
encounter challenges such as limited multilingual capabilities, risks of
catastrophic forgetting during continual pretraining, and the high costs of
training models from scratch, alongside the need to align with AI safety
standards and regulatory frameworks.
  This paper presents Aurora-M, a 15B parameter multilingual open-source model
trained on English, Finnish, Hindi, Japanese, Vietnamese, and code. Continually
pretrained from StarCoderPlus on 435B additional tokens, Aurora-M surpasses 2T
tokens in total training token count. It is the first open-source multilingual
model fine-tuned on human-reviewed safety instructions, thus aligning its
development not only with conventional red-teaming considerations, but also
with the specific concerns articulated in the Biden-Harris Executive Order on
the Safe, Secure, and Trustworthy Development and Use of Artificial
Intelligence.
  We evaluate Aurora-M across a wide range of tasks and languages, showcasing
its robustness against catastrophic forgetting and its superior performance in
multilingual settings, particularly in safety evaluations. We open-source
Aurora-M and its variants to encourage responsible open-source development of
large language models at https://huggingface.co/aurora-m.
