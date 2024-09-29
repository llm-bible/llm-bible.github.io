---
layout: publication
title: Andes Defining And Enhancing Quality45;of45;experience In Llm45;based Text Streaming Services
authors: Liu Jiachen, Wu Zhiyu, Chung Jae-won, Lai Fan, Lee Myungjin, Chowdhury Mosharaf
conference: "Arxiv"
year: 2024
bibkey: liu2024defining
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.16283"}
tags: ['Pretraining Methods', 'RAG']
---
The advent of large language models (LLMs) has transformed text45;based services enabling capabilities ranging from real45;time translation to AI45;driven chatbots. However existing serving systems primarily focus on optimizing server45;side aggregate metrics like token generation throughput ignoring individual user experience with streamed text. As a result under high and/or bursty load a significant number of users can receive unfavorable service quality or poor Quality45;of45;Experience (QoE). In this paper we first formally define QoE of text streaming services where text is delivered incrementally and interactively to users by considering the end45;to45;end token delivery process throughout the entire interaction with the user. Thereafter we propose Andes a QoE45;aware serving system that enhances user experience for LLM45;enabled text streaming services. At its core Andes strategically allocates contended GPU resources among multiple requests over time to optimize their QoE. Our evaluations demonstrate that compared to the state45;of45;the45;art LLM serving systems like vLLM Andes improves the average QoE by up to 3.2× under high request rate or alternatively it attains up to 1.6× higher request rate while preserving high QoE.
