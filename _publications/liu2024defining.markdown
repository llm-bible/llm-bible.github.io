---
layout: publication
title: Andes: Defining And Enhancing Quality-of-experience In Llm-based Text Streaming Services
authors: Liu Jiachen, Wu Zhiyu, Chung Jae-won, Lai Fan, Lee Myungjin, Chowdhury Mosharaf
conference: "Arxiv"
year: 2024
bibkey: liu2024defining
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.16283"}
tags: ['Pretraining Methods', 'RAG']
---
The advent of large language models (LLMs) has transformed text-based services enabling capabilities ranging from real-time translation to AI-driven chatbots. However existing serving systems primarily focus on optimizing server-side aggregate metrics like token generation throughput ignoring individual user experience with streamed text. As a result under high and/or bursty load a significant number of users can receive unfavorable service quality or poor Quality-of-Experience (QoE). In this paper we first formally define QoE of text streaming services where text is delivered incrementally and interactively to users by considering the end-to-end token delivery process throughout the entire interaction with the user. Thereafter we propose Andes a QoE-aware serving system that enhances user experience for LLM-enabled text streaming services. At its core Andes strategically allocates contended GPU resources among multiple requests over time to optimize their QoE. Our evaluations demonstrate that compared to the state-of-the-art LLM serving systems like vLLM Andes improves the average QoE by up to 3.2(times) under high request rate or alternatively it attains up to 1.6(times) higher request rate while preserving high QoE.
