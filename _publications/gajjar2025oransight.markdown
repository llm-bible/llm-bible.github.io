---
layout: publication
title: 'Oransight-2.0: Foundational Llms For O-RAN'
authors: Pranshav Gajjar, Vijay K. Shah
conference: "Arxiv"
year: 2025
bibkey: gajjar2025oransight
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.05200"}
tags: ['Fine-Tuning', 'Agentic', 'GPT', 'Tools', 'RAG', 'Model Architecture', 'Training Techniques']
---
Despite the transformative impact of Large Language Models (LLMs) across
critical domains such as healthcare, customer service, and business marketing,
their integration into Open Radio Access Networks (O-RAN) remains limited. This
gap is primarily due to the absence of domain-specific foundational models,
with existing solutions often relying on general-purpose LLMs that fail to
address the unique challenges and technical intricacies of O-RAN. To bridge
this gap, we introduce ORANSight-2.0 (O-RAN Insights), a pioneering initiative
aimed at developing specialized foundational LLMs tailored for O-RAN. Built on
18 LLMs spanning five open-source LLM frameworks, ORANSight-2.0 fine-tunes
models ranging from 1 to 70B parameters, significantly reducing reliance on
proprietary, closed-source models while enhancing performance for O-RAN. At the
core of ORANSight-2.0 is RANSTRUCT, a novel Retrieval-Augmented Generation
(RAG) based instruction-tuning framework that employs two LLM agents to create
high-quality instruction-tuning datasets. The generated dataset is then used to
fine-tune the 18 pre-trained open-source LLMs via QLoRA. To evaluate
ORANSight-2.0, we introduce srsRANBench, a novel benchmark designed for code
generation and codebase understanding in the context of srsRAN, a widely used
5G O-RAN stack. We also leverage ORANBench13K, an existing benchmark for
assessing O-RAN-specific knowledge. Our comprehensive evaluations demonstrate
that ORANSight-2.0 models outperform general-purpose and closed-source models,
such as ChatGPT-4o and Gemini, by 5.421% on ORANBench and 18.465% on
srsRANBench, achieving superior performance while maintaining lower
computational and energy costs. We also experiment with RAG-augmented variants
of ORANSight-2.0 LLMs and thoroughly evaluate their energy characteristics,
demonstrating costs for training, standard inference, and RAG-augmented
inference.
