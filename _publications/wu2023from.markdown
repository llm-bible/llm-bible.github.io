---
layout: publication
title: From Language Modeling To Instruction Following Understanding The Behavior Shift In Llms After Instruction Tuning
authors: Wu Xuansheng, Yao Wenlin, Chen Jianshu, Pan Xiaoman, Wang Xiaoyang, Liu Ninghao, Yu Dong
conference: "Arxiv"
year: 2023
bibkey: wu2023from
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.00492"}
  - {name: "Code", url: "https://github.com/JacksonWuxs/Interpret&#95;Instruction&#95;Tuning&#95;LLMs"}
tags: ['Applications', 'Attention Mechanism', 'Has Code', 'Interpretability And Explainability', 'Language Modeling', 'Model Architecture', 'Prompting', 'RAG']
---
Large Language Models (LLMs) have achieved remarkable success where instruction tuning is the critical step in aligning LLMs with user intentions. In this work we investigate how the instruction tuning adjusts pre45;trained models with a focus on intrinsic changes. Specifically we first develop several local and global explanation methods including a gradient45;based method for input45;output attribution and techniques for interpreting patterns and concepts in self45;attention and feed45;forward layers. The impact of instruction tuning is then studied by comparing the explanations derived from the pre45;trained and instruction45;tuned models. This approach provides an internal perspective of the model shifts on a human45;comprehensible level. Our findings reveal three significant impacts of instruction tuning 1) It empowers LLMs to recognize the instruction parts of user prompts and promotes the response generation constantly conditioned on the instructions. 2) It encourages the self45;attention heads to capture more word45;word relationships about instruction verbs. 3) It encourages the feed45;forward networks to rotate their pre45;trained knowledge toward user45;oriented tasks. These insights contribute to a more comprehensive understanding of instruction tuning and lay the groundwork for future work that aims at explaining and optimizing LLMs for various applications. Our code and data are publicly available at https://github.com/JacksonWuxs/Interpret&#95;Instruction&#95;Tuning&#95;LLMs.
