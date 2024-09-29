---
layout: publication
title: Can LLMs Learn from Previous Mistakes Investigating LLMs Errors to Boost for Reasoning
authors: Tong Yongqi, Li Dawei, Wang Sizhe, Wang Yujia, Teng Fei, Shang Jingbo
conference: "Arxiv"
year: 2024
bibkey: tong2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.20046"}
  - {name: "Code", url: "https://github.com/YookiTong/Learn-from-Mistakes-CotErrorSet"}
tags: ['Few Shot', 'Fine Tuning', 'Has Code', 'In Context Learning', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Recent works have shown the benefits to LLMs from fine-tuning golden-standard Chain-of-Thought (CoT) rationales or using them as correct examples in few-shot prompting. While humans can indeed imitate correct examples learning from our mistakes is another vital aspect of human cognition. Hence a question naturally arises textitcan LLMs learn and benefit from their mistakes especially for their reasoning This study investigates this problem from both the prompting and model-tuning perspectives. We begin by introducing textscCoTErrorSet a new benchmark with 609432 questions each designed with both correct and error references and demonstrating the types and reasons for making such mistakes. To explore the effectiveness of those mistakes we design two methods (1) textbfSelf-rethinking prompting guides LLMs to rethink whether they have made similar previous mistakes; and (2) textbfMistake tuning involves finetuning models in both correct and incorrect reasoning domains rather than only tuning models to learn ground truth in traditional methodology. We conduct a series of experiments to prove LLMs can obtain benefits from mistakes in both directions. Our two methods offer potentially cost-effective strategies by leveraging errors to enhance reasoning capabilities which costs significantly less than creating meticulously hand-crafted golden references. We ultimately make a thorough analysis of the reasons behind LLMs errors which provides directions that future research needs to overcome. textscCoTErrorSet will be published soon on texttturl https://github.com/YookiTong/Learn-from-Mistakes-CotErrorSet.
