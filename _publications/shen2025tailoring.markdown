---
layout: publication
title: 'Gpiot: Tailoring Small Language Models For Iot Program Synthesis And Development'
authors: Leming Shen, Qiang Yang, Xinyu Huang, Zijing Ma, Yuanqing Zheng
conference: "Arxiv"
year: 2025
bibkey: shen2025tailoring
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.00686'}
tags: ['RAG', 'Efficiency and Optimization', 'Model Architecture', 'Applications', 'Training Techniques', 'Fine-Tuning', 'GPT', 'Pretraining Methods']
---
Code Large Language Models (LLMs) enhance software development efficiency by
automatically generating code and documentation in response to user
requirements. However, code LLMs cannot synthesize specialized programs when
tasked with IoT applications that require domain knowledge. While
Retrieval-Augmented Generation (RAG) offers a promising solution by fetching
relevant domain knowledge, it necessitates powerful cloud LLMs (e.g., GPT-4) to
process user requirements and retrieved contents, which raises significant
privacy concerns. This approach also suffers from unstable networks and
prohibitive LLM query costs. Moreover, it is challenging to ensure the
correctness and relevance of the fetched contents. To address these issues, we
propose GPIoT, a code generation system for IoT applications by fine-tuning
locally deployable Small Language Models (SLMs) on IoT-specialized datasets.
SLMs have smaller model sizes, allowing efficient local deployment and
execution to mitigate privacy concerns and network uncertainty. Furthermore, by
fine-tuning the SLMs with our IoT-specialized datasets, the SLMs' ability to
synthesize IoT-related programs can be substantially improved. To evaluate
GPIoT's capability in synthesizing programs for IoT applications, we develop a
benchmark, IoTBench. Extensive experiments and user trials demonstrate the
effectiveness of GPIoT in generating IoT-specialized code, outperforming
state-of-the-art code LLMs with an average task accuracy increment of 64.7% and
significant improvements in user satisfaction.
