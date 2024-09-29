---
layout: publication
title: Can Llms Learn From Previous Mistakes Investigating Llms Errors To Boost For Reasoning
authors: Tong Yongqi, Li Dawei, Wang Sizhe, Wang Yujia, Teng Fei, Shang Jingbo
conference: "Arxiv"
year: 2024
bibkey: tong2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.20046"}
  - {name: "Code", url: "https://github.com/YookiTong/Learn&#45;from&#45;Mistakes&#45;CotErrorSet&#125;&#125;"}
tags: ['Has Code', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Recent works have shown the benefits to LLMs from fine45;tuning golden45;standard Chain45;of45;Thought (CoT) rationales or using them as correct examples in few45;shot prompting. While humans can indeed imitate correct examples learning from our mistakes is another vital aspect of human cognition. Hence a question naturally arises textit123;can LLMs learn and benefit from their mistakes especially for their reasoning 125; This study investigates this problem from both the prompting and model45;tuning perspectives. We begin by introducing textsc123;CoTErrorSet125; a new benchmark with 609432 questions each designed with both correct and error references and demonstrating the types and reasons for making such mistakes. To explore the effectiveness of those mistakes we design two methods (1) textbf123;Self45;rethinking125; prompting guides LLMs to rethink whether they have made similar previous mistakes; and (2) textbf123;Mistake tuning125; involves finetuning models in both correct and incorrect reasoning domains rather than only tuning models to learn ground truth in traditional methodology. We conduct a series of experiments to prove LLMs can obtain benefits from mistakes in both directions. Our two methods offer potentially cost45;effective strategies by leveraging errors to enhance reasoning capabilities which costs significantly less than creating meticulously hand45;crafted golden references. We ultimately make a thorough analysis of the reasons behind LLMs errors which provides directions that future research needs to overcome. textsc123;CoTErrorSet125; will be published soon on texttt123;url123;https://github.com/YookiTong/Learn&#45;from&#45;Mistakes&#45;CotErrorSet&#125;&#125;.
