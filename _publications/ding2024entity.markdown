---
layout: publication
title: 'Entgpt: Entity Linking With Generative Large Language Models'
authors: Yifan Ding, Amrit Poudel, Qingkai Zeng, Tim Weninger, Balaji Veeramani, Sanmitra Bhattacharya
conference: "Arxiv"
year: 2024
bibkey: ding2024entity
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.06738"}
  - {name: "Code", url: "https://github.com/yifding/In_Context_EL"}
tags: ['Training Techniques', 'Model Architecture', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Prompting', 'Applications']
---
Entity Linking in natural language processing seeks to match text entities to their corresponding entries in a dictionary or knowledge base. Traditional approaches rely on contextual models, which can be complex, hard to train, and have limited transferability across different domains. Generative large language models like GPT offer a promising alternative but often underperform with naive prompts. In this study, we introduce EntGPT, employing advanced prompt engineering to enhance EL tasks. Our three-step hard-prompting method (EntGPT-P) significantly boosts the micro-F_1 score by up to 36% over vanilla prompts, achieving competitive performance across 10 datasets without supervised fine-tuning. Additionally, our instruction tuning method (EntGPT-I) improves micro-F_1 scores by 2.1% on average in supervised EL tasks and outperforms several baseline models in six Question Answering tasks. Our methods are compatible with both open-source and proprietary LLMs. All data and code are available on GitHub at https://github.com/yifding/In_Context_EL.
