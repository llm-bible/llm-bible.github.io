---
layout: publication
title: QDA-SQL\: Questions Enhanced Dialogue Augmentation For Multi-turn Text-to-sql
authors: Sun Yinggang, Guo Ziming, Yu Haining, Liu Chuanyi, Li Xiang, Wang Bingxuan, Yu Xiangzhan, Zhao Tiancheng
conference: "Arxiv"
year: 2024
bibkey: sun2024qda
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.10593"}
  - {name: "Code", url: "https://github.com/mcxiaoxiao/QDA-SQL"}
tags: ['Fine Tuning', 'Has Code', 'Pretraining Methods', 'Training Techniques']
---
Fine-tuning large language models (LLMs) for specific domain tasks has achieved great success in Text-to-SQL tasks. However these fine-tuned models often face challenges with multi-turn Text-to-SQL tasks caused by ambiguous or unanswerable questions. It is desired to enhance LLMs to handle multiple types of questions in multi-turn Text-to-SQL tasks. To address this we propose a novel data augmentation method called QDA-SQL which generates multiple types of multi-turn Qamp;A pairs by using LLMs. In QDA-SQL we introduce a novel data augmentation method incorporating validation and correction mechanisms to handle complex multi-turn Text-to-SQL tasks. Experimental results demonstrate that QDA-SQL enables fine-tuned models to exhibit higher performance on SQL statement accuracy and enhances their ability to handle complex unanswerable questions in multi-turn Text-to-SQL tasks. The generation script and test set are released at https://github.com/mcxiaoxiao/QDA-SQL."
