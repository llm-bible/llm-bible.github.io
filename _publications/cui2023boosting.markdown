---
layout: publication
title: 'Ultrafeedback: Boosting Language Models With Scaled AI Feedback'
authors: Cui Ganqu, Yuan Lifan, Ding Ning, Yao Guanming, He Bingxiang, Zhu Wei, Ni Yuan, Xie Guotong, Xie Ruobing, Lin Yankai, Liu Zhiyuan, Sun Maosong
conference: "Arxiv"
year: 2023
bibkey: cui2023boosting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.01377"}
  - {name: "Code", url: "https://github.com/thunlp/UltraFeedback"}
tags: ['Agentic', 'Ethics And Bias', 'GPT', 'Has Code', 'Model Architecture', 'Reinforcement Learning']
---
Learning from human feedback has become a pivot technique in aligning large language models (LLMs) with human preferences. However acquiring vast and premium human feedback is bottlenecked by time labor and human capability resulting in small sizes or limited topics of current datasets. This further hinders feedback learning as well as alignment research within the open-source community. To address this issue we explore how to go beyond human feedback and collect high-quality textitAI feedback automatically for a scalable alternative. Specifically we identify textbfscale and diversity as the key factors for feedback data to take effect. Accordingly we first broaden instructions and responses in both amount and breadth to encompass a wider range of user-assistant interactions. Then we meticulously apply a series of techniques to mitigate annotation biases for more reliable AI feedback. We finally present textscUltraFeedback a large-scale high-quality and diversified AI feedback dataset which contains over 1 million GPT-4 feedback for 250k user-assistant conversations from various aspects. Built upon textscUltraFeedback we align a LLaMA-based model by best-of-(n) sampling and reinforcement learning demonstrating its exceptional performance on chat benchmarks. Our work validates the effectiveness of scaled AI feedback data in constructing strong open-source chat language models serving as a solid foundation for future feedback learning research. Our data and models are available at https://github.com/thunlp/UltraFeedback."
