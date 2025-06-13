---
layout: publication
title: 'The Compressor-retriever Architecture For Language Model OS'
authors: Yuan Yang, Siheng Xiong, Ehsan Shareghi, Faramarz Fekri
conference: "Arxiv"
year: 2024
bibkey: yang2024compressor
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.01495"}
  - {name: "Code", url: "https://github.com/gblackout/LM-OS"}
tags: ['Agentic', 'Multimodal Models', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Has Code', 'Prompting', 'In-Context Learning']
---
Recent advancements in large language models (LLMs) have significantly
enhanced their capacity to aggregate and process information across multiple
modalities, enabling them to perform a wide range of tasks such as multimodal
data querying, tool usage, web interactions, and handling long documents. These
capabilities pave the way for transforming LLMs from mere chatbots into
general-purpose agents capable of interacting with the real world. This paper
explores the concept of using a language model as the core component of an
operating system (OS), effectively acting as a CPU that processes data stored
in a context window, which functions as RAM. A key challenge in realizing such
an LM OS is managing the life-long context and ensuring statefulness across
sessions, a feature limited by the current session-based interaction paradigm
due to context window size limit. To address this, we introduce
compressor-retriever, a model-agnostic architecture designed for life-long
context management. Unlike other long-context solutions such as
retrieval-augmented generation, our approach exclusively uses the base model's
forward function to compress and retrieve context, ensuring end-to-end
differentiability. Preliminary experiments demonstrate the effectiveness of
this architecture in in-context learning tasks, marking a step towards the
development of a fully stateful LLM OS. Project repo available at:
https://github.com/gblackout/LM-OS
