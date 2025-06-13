---
layout: publication
title: 'Bioprobench: Comprehensive Dataset And Benchmark In Biological Protocol Understanding And Reasoning'
authors: Yuyang Liu, Liuzhenghao Lv, Xiancheng Zhang, Li Yuan, Yonghong Tian
conference: "Arxiv"
year: 2025
bibkey: liu2025comprehensive
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.07889'}
  - {name: "Code", url: 'https://github.com/YuyangSunshine/bioprotocolbench'}
  - {name: "Code", url: 'https://huggingface.co/datasets/BioProBench/BioProBench'}
tags: ['Reinforcement Learning', 'Has Code', 'Responsible AI', 'Applications']
---
Biological protocols are fundamental to reproducibility and safety in life science research. While large language models (LLMs) perform well on general tasks, their systematic evaluation on these highly specialized, accuracy-critical, and inherently procedural texts remains limited. In this work, we present BioProBench, the first large-scale, multi-task benchmark for biological protocol understanding and reasoning. While there are several benchmark tasks involving protocol question answering, BioProBench provides a comprehensive suite of five core tasks: Protocol Question Answering, Step Ordering, Error Correction, Protocol Generation, and Protocol Reasoning, enabling a holistic evaluation of LLMs on procedural biological texts. Built upon 27K original protocols, it yields nearly 556K high-quality structured instances. We evaluate 12 mainstream open/closed-source LLMs. Experimental results reveal that some models perform well on basic understanding tasks (e.g., \sim70% PQA-Acc., >64% ERR F1), but struggle significantly with deep reasoning and structured generation tasks like ordering and generation. Furthermore, model comparisons show diverse performance: certain open-source models approach closed-source levels on some tasks, yet bio-specific small models lag behind general LLMs, indicating limitations on complex procedural content. Overall, BioProBench, through its task design and experimental findings, systematically reveals the fundamental challenges for current LLMs in procedural knowledge understanding, deep adaptability to specific domains, reliability of structured reasoning, and handling of sophisticated precision and safety constraints, providing key directions for future AI in the field of scientific experiment automation. The code and data are available at: https://github.com/YuyangSunshine/bioprotocolbench and https://huggingface.co/datasets/BioProBench/BioProBench.
