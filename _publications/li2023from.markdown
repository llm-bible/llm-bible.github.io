---
layout: publication
title: From Quantity to Quality Boosting LLM Performance with Self-Guided Data Selection for Instruction Tuning
authors: Li Ming, Zhang Yong, Li Zhitao, Chen Jiuhai, Chen Lichang, Cheng Ning, Wang Jianzong, Zhou Tianyi, Xiao Jing
conference: "Arxiv"
year: 2023
bibkey: li2023from
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.12032"}
  - {name: "Code", url: "https://github.com/tianyi-lab/Cherry_LLM"}
tags: ['ARXIV', 'Efficiency And Optimization', 'Has Code', 'LLM']
---
In the realm of Large Language Models (LLMs) the balance between instruction data quality and quantity is a focal point. Recognizing this we introduce a self-guided methodology for LLMs to autonomously discern and select cherry samples from open-source datasets effectively minimizing manual curation and potential cost for instruction tuning an LLM. Our key innovation the Instruction-Following Difficulty (IFD) metric emerges as a pivotal metric to identify discrepancies between a models expected responses and its intrinsic generation capability. Through the application of IFD cherry samples can be pinpointed leading to a marked uptick in model training efficiency. Empirical validations on datasets like Alpaca and WizardLM underpin our findings; with a mere 10 of original data input our strategy showcases improved results. This synthesis of self-guided cherry-picking and the IFD metric signifies a transformative leap in the instruction tuning of LLMs promising both efficiency and resource-conscious advancements. Codes data and models are available https://github.com/tianyi-lab/Cherry_LLM
