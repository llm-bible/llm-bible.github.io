---
layout: publication
title: 'Cotran: An Llm-based Code Translator Using Reinforcement Learning With Feedback From Compiler And Symbolic Execution'
authors: Prithwish Jana, Piyush Jha, Haoyang Ju, Gautham Kishore, Aryan Mahajan, Vijay Ganesh
conference: "Arxiv"
year: 2023
bibkey: jana2023llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.06755"}
tags: ['Fine-Tuning', 'Agentic', 'GPT', 'Tools', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
In this paper, we present an LLM-based code translation method and an
associated tool called CoTran, that translates whole-programs from one
high-level programming language to another. Existing LLM-based code translation
methods lack training to ensure that the translated code reliably compiles or
bears substantial functional equivalence to the input code. In our work, we
fine-tune an LLM using reinforcement learning, incorporating compiler feedback,
and symbolic execution (symexec)-based testing feedback to assess functional
equivalence between the input and output programs. The idea is to guide an LLM
during fine-tuning, via compiler and symexec-based testing feedback, by letting
it know how far it is from producing perfect translations. We conduct extensive
experiments comparing CoTran with 14 other code translation tools, including
human-written transpilers, LLM-based translation tools, and ChatGPT. Using a
benchmark of over \num\{57000\} code pairs in Java and Python, we demonstrate
that CoTran outperforms the other tools on relevant metrics such as compilation
accuracy (CompAcc) and functional equivalence accuracy (FEqAcc). For example,
in Python-to-Java translation, CoTran achieves 48.68% FEqAcc and 76.98%
CompAcc, whereas the nearest competing tool (PLBART-base) gets 38.26% and
75.77% respectively. Additionally, CoTran, built on top of CodeT5, improves
FEqAcc by +14.89% and CompAcc by +8.14% for Python-to-Java (resp., +12.94% and
+4.30% for Java-to-Python).
