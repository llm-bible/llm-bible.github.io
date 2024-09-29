---
layout: publication
title: Red Teaming Visual Language Models
authors: Li Mukai, Li Lei, Yin Yuwei, Ahmed Masood, Liu Zhenguang, Liu Qi
conference: "Arxiv"
year: 2024
bibkey: li2024red
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.12915"}
tags: ['Bias Mitigation', 'Ethics And Bias', 'Fairness', 'Fine Tuning', 'GPT', 'Model Architecture', 'Multimodal Models', 'Responsible AI']
---
VLMs (Vision45;Language Models) extend the capabilities of LLMs (Large Language Models) to accept multimodal inputs. Since it has been verified that LLMs can be induced to generate harmful or inaccurate content through specific test cases (termed as Red Teaming) how VLMs perform in similar scenarios especially with their combination of textual and visual inputs remains a question. To explore this problem we present a novel red teaming dataset RTVLM which encompasses 10 subtasks (e.g. image misleading multi45;modal jail45;breaking face fairness etc) under 4 primary aspects (faithfulness privacy safety fairness). Our RTVLM is the first red45;teaming dataset to benchmark current VLMs in terms of these 4 different aspects. Detailed analysis shows that 10 prominent open45;sourced VLMs struggle with the red teaming in different degrees and have up to 3137; performance gap with GPT45;4V. Additionally we simply apply red teaming alignment to LLaVA45;v1.5 with Supervised Fine45;tuning (SFT) using RTVLM and this bolsters the models performance with 1037; in RTVLM test set 1337; in MM45;Hal and without noticeable decline in MM45;Bench overpassing other LLaVA45;based models with regular alignment data. This reveals that current open45;sourced VLMs still lack red teaming alignment. Our code and datasets will be open45;source.
