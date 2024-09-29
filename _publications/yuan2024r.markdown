---
layout: publication
title: R45;judge Benchmarking Safety Risk Awareness For LLM Agents
authors: Yuan Tongxin, He Zhiwei, Dong Lingzhong, Wang Yiming, Zhao Ruijie, Xia Tian, Xu Lizhen, Zhou Binglin, Li Fangqi, Zhang Zhuosheng, Wang Rui, Liu Gongshen
conference: "Arxiv"
year: 2024
bibkey: yuan2024r
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.10019"}
  - {name: "Code", url: "https://github.com/Lordog/R&#45;Judge"}
tags: ['Agentic', 'Applications', 'Ethics And Bias', 'GPT', 'Has Code', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Responsible AI']
---
Large language models (LLMs) have exhibited great potential in autonomously completing tasks across real45;world applications. Despite this these LLM agents introduce unexpected safety risks when operating in interactive environments. Instead of centering on LLM45;generated content safety in most prior studies this work addresses the imperative need for benchmarking the behavioral safety of LLM agents within diverse environments. We introduce R45;Judge a benchmark crafted to evaluate the proficiency of LLMs in judging and identifying safety risks given agent interaction records. R45;Judge comprises 162 records of multi45;turn agent interaction encompassing 27 key risk scenarios among 7 application categories and 10 risk types. It incorporates human consensus on safety with annotated safety labels and high45;quality risk descriptions. Evaluation of 9 LLMs on R45;Judge shows considerable room for enhancing the risk awareness of LLMs The best45;performing model GPT45;4 achieves 72.5237; in contrast to the human score of 89.0737; while all other models score less than the random. Moreover further experiments demonstrate that leveraging risk descriptions as environment feedback achieves substantial performance gains. With case studies we reveal that correlated to parameter amount risk awareness in open agent scenarios is a multi45;dimensional capability involving knowledge and reasoning thus challenging for current LLMs. R45;Judge is publicly available at https://github.com/Lordog/R&#45;Judge.
