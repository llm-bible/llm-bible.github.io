---
layout: publication
title: Cotran An Llm-based Code Translator Using Reinforcement Learning With Feedback From Compiler And Symbolic Execution
authors: Jana Prithwish, Jha Piyush, Ju Haoyang, Kishore Gautham, Mahajan Aryan, Ganesh Vijay
conference: "Arxiv"
year: 2023
bibkey: jana2023llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.06755"}
tags: ['Agentic', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
In this paper we present an LLM-based code translation method and an associated tool called CoTran that translates whole-programs from one high-level programming language to another. Current LLM-based code translation methods lack a training approach to ensure that the translated code reliably compiles or bears substantial functional equivalence to the input code. In our work we train an LLM via reinforcement learning by modifying the fine-tuning process to incorporate compiler feedback and symbolic execution (symexec)-based equivalence testing feedback that checks for functional equivalence between the input and output programs. The idea is to guide an LLM-in-training via compiler and symexec-based testing feedback by letting it know how far it is from producing perfect translations. We report on extensive experiments comparing CoTran with 14 other code translation tools that include human-written transpilers LLM-based translation tools and ChatGPT over a benchmark of more than 57000 Java-Python equivalent pairs and we show that CoTran outperforms them on relevant metrics such as compilation accuracy (CompAcc) and functional equivalence accuracy (FEqAcc). For example our tool achieves 48.6837; FEqAcc 76.9837; CompAcc for Python-to-Java translation whereas the nearest competing tool (PLBART-base) only gets 38.2637; and 75.7737; resp. Also built upon CodeT5 CoTran achieves +11.2337; +14.8937; improvement on FEqAcc and +4.0737; +8.1437; on CompAcc for Java-to-Python and Python-to-Java translation resp.
