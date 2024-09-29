---
layout: publication
title: Entgpt Linking Generative Large Language Models With Knowledge Bases
authors: Ding Yifan, Poudel Amrit, Zeng Qingkai, Weninger Tim, Veeramani Balaji, Bhattacharya Sanmitra
conference: "Arxiv"
year: 2024
bibkey: ding2024linking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.06738"}
tags: ['Applications', 'Fine Tuning', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Training Techniques']
---
The ability of Large Language Models (LLMs) to generate factually correct output remains relatively unexplored due to the lack of fact45;checking and knowledge grounding during training and inference. In this work we aim to address this challenge through the Entity Disambiguation (ED) task. We first consider prompt engineering and design a three45;step hard45;prompting method to probe LLMs ED performance without supervised fine45;tuning (SFT). Overall the prompting method improves the micro45;F95;1 score of the original vanilla models by a large margin on some cases up to 3637; and higher and obtains comparable performance across 10 datasets when compared to existing methods with SFT. We further improve the knowledge grounding ability through instruction tuning (IT) with similar prompts and responses. The instruction45;tuned model not only achieves higher micro45;F1 score performance as compared to several baseline methods on supervised entity disambiguation tasks with an average micro45;F95;1 improvement of 2.137; over the existing baseline models but also obtains higher accuracy on six Question Answering (QA) tasks in the zero45;shot setting. Our methodologies apply to both open45; and closed45;source LLMs.
