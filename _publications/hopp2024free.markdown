---
layout: publication
title: 'Free To Play: UN Trade And Development''s Experience With Developing Its Own Open-source Retrieval Augmented Generation Large Language Model Application'
authors: Hopp Daniel
conference: "Arxiv"
year: 2024
bibkey: hopp2024free
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.16896"}
tags: ['Attention Mechanism', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques', 'Transformer']
---
Generative artificial intelligence (AI), and in particular Large Language Models (LLMs), have exploded in popularity and attention since the release to the public of ChatGPT's Generative Pre-trained Transformer (GPT)-3.5 model in November of 2022. Due to the power of these general purpose models and their ability to communicate in natural language, they can be useful in a range of domains, including the work of official statistics and international organizations. However, with such a novel and seemingly complex technology, it can feel as if generative AI is something that happens to an organization, something that can be talked about but not understood, that can be commented on but not contributed to. Additionally, the costs of adoption and operation of proprietary solutions can be both uncertain and high, a barrier for often cost-constrained international organizations. In the face of these challenges, United Nations Trade and Development (UNCTAD), through its Global Crisis Response Group (GCRG), has explored and developed its own open-source Retrieval Augmented Generation (RAG) LLM application. RAG makes LLMs aware of and more useful for the organization's domain and work. Developing in-house solutions comes with pros and cons, with pros including cost, flexibility, and fostering institutional knowledge. Cons include time and skill investments and gaps and application polish and power. The three libraries developed to produce the app, nlp\_pipeline for document processing and statistical analysis, local\_rag\_llm for running a local RAG LLM, and streamlit\_rag for the user interface, are publicly available on PyPI and GitHub with Dockerfiles. A fourth library, local\_llm\_finetune, is also available for fine-tuning existing LLMs which can then be used in the application.
