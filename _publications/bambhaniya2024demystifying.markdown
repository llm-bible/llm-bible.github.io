---
layout: publication
title: 'Demystifying AI Platform Design For Distributed Inference Of Next-generation LLM Models'
authors: Abhimanyu Bambhaniya, Ritik Raj, Geonhwa Jeong, Souvik Kundu, Sudarshan Srinivasan, Suvinay Subramanian, Midhilesh Elavazhagan, Madhu Kumar, Tushar Krishna
conference: "Arxiv"
year: 2024
bibkey: bambhaniya2024demystifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.01698"}
  - {name: "Code", url: "https://github.com/abhibambhaniya/GenZ-LLM-Analyzer"}
  - {name: "Code", url: "https://genz-llm-analyzer.streamlit.app/"}
tags: ['Tools', 'Efficiency and Optimization', 'Applications', 'Model Architecture', 'Has Code']
---
Large language models (LLMs) have shown remarkable performance across a wide range of applications, often outperforming human experts. However, deploying these gigantic models efficiently for diverse inference use cases requires carefully designed hardware platforms with ample computing, memory, and network resources. With constant innovation in LLM serving optimizations and model architecture evolving at breakneck speed, the hardware requirements to meet Service Level Objectives (SLOs) remain an open research question.
  To answer the question, we present an analytical tool, GenZ, to efficiently navigate the relationship between diverse LLM model architectures(Dense, GQA, MoE, Mamba), LLM serving optimizations(Chunking, Speculative decoding, quanitization), and AI platform design parameters. Our tool estimates LLM inference performance metrics for the given scenario. We have validated against real hardware platforms running various different LLM models, achieving a max geomean error of 5.82.We use GenZ to identify compute, memory capacity, memory bandwidth, network latency, and network bandwidth requirements across diverse LLM inference use cases. We also study diverse architectural choices in use today (inspired by LLM serving platforms from several vendors) to help inform computer architects designing next-generation AI hardware accelerators and platforms. The trends and insights derived from GenZ can guide AI engineers deploying LLMs as well as computer architects designing next-generation hardware accelerators and platforms. Ultimately, this work sheds light on the platform design considerations for unlocking the full potential of large language models across a spectrum of applications. The source code is available at https://github.com/abhibambhaniya/GenZ-LLM-Analyzer . Users can also be tried it on at https://genz-llm-analyzer.streamlit.app/ without any setup on your web browser.
