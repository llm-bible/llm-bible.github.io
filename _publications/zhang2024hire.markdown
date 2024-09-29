---
layout: publication
title: Hire A Linguist!&#58; Learning Endangered Languages With In-context Linguistic Descriptions
authors: Zhang Kexun, Choi Yee Man, Song Zhenqiao, He Taiqi, Wang William Yang, Li Lei
conference: "Arxiv"
year: 2024
bibkey: zhang2024hire
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.18025"}
  - {name: "Code", url: "https://github.com/LLiLab/llm4endangeredlang"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'Training Techniques']
---
How can large language models (LLMs) process and translate endangered languages Many languages lack a large corpus to train a decent LLM; therefore existing LLMs rarely perform well in unseen endangered languages. On the contrary we observe that 2000 endangered languages though without a large corpus have a grammar book or a dictionary. We propose LINGOLLM a training-free approach to enable an LLM to process unseen languages that hardly occur in its pre-training. Our key insight is to demonstrate linguistic knowledge of an unseen language in an LLMs prompt including a dictionary a grammar book and morphologically analyzed input text. We implement LINGOLLM on top of two models GPT-4 and Mixtral and evaluate their performance on 5 tasks across 8 endangered or low-resource languages. Our results show that LINGOLLM elevates translation capability from GPT-4s 0 to 10.5 BLEU for 10 language directions. Our findings demonstrate the tremendous value of linguistic knowledge in the age of LLMs for endangered languages. Our data code and model generations can be found at https://github.com/LLiLab/llm4endangeredlang."
