---
layout: publication
title: AMGPT\: A Large Language Model For Contextual Querying In Additive Manufacturing
authors: Chandrasekhar Achuth, Chan Jonathan, Ogoke Francis, Ajenifujah Olabode, Farimani Amir Barati
conference: "Arxiv"
year: 2024
bibkey: chandrasekhar2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.00031"}
tags: ['GPT', 'Model Architecture', 'RAG', 'Tools', 'Training Techniques']
---
Generalized large language models (LLMs) such as GPT-4 may not provide specific answers to queries formulated by materials science researchers. These models may produce a high-level outline but lack the capacity to return detailed instructions on manufacturing and material properties of novel alloys. Enhancing a smaller model with specialized domain knowledge may provide an advantage over large language models which cannot be retrained quickly enough to keep up with the rapid pace of research in metal additive manufacturing (AM). We introduce AMGPT a specialized LLM text generator designed for metal AM queries. The goal of AMGPT is to assist researchers and users in navigating the extensive corpus of literature in AM. Instead of training from scratch we employ a pre-trained Llama2-7B model from Hugging Face in a Retrieval-Augmented Generation (RAG) setup utilizing it to dynamically incorporate information from (sim)50 AM papers and textbooks in PDF format. Mathpix is used to convert these PDF documents into TeX format facilitating their integration into the RAG pipeline managed by LlamaIndex. Expert evaluations of this project highlight that specific embeddings from the RAG setup accelerate response times and maintain coherence in the generated text.
