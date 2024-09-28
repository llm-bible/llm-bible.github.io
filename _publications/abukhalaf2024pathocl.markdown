---
layout: publication
title: PathOCL Path-Based Prompt Augmentation for OCL Generation with GPT-4
authors: Abukhalaf Seif, Hamdaqa Mohammad, Khomh Foutse
conference: "Arxiv"
year: 2024
bibkey: abukhalaf2024pathocl
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.12450"}
tags: ['ARXIV', 'Applications', 'GPT', 'LLM', 'Prompt', 'Tools']
---
The rapid progress of AI-powered programming assistants such as GitHub Copilot has facilitated the development of software applications. These assistants rely on large language models (LLMs) which are foundation models (FMs) that support a wide range of tasks related to understanding and generating language. LLMs have demonstrated their ability to express UML model specifications using formal languages like the Object Constraint Language (OCL). However the context size of the prompt is limited by the number of tokens an LLM can process. This limitation becomes significant as the size of UML class models increases. In this study we introduce PathOCL a novel path-based prompt augmentation technique designed to facilitate OCL generation. PathOCL addresses the limitations of LLMs specifically their token processing limit and the challenges posed by large UML class models. PathOCL is based on the concept of chunking which selectively augments the prompts with a subset of UML classes relevant to the English specification. Our findings demonstrate that PathOCL compared to augmenting the complete UML class model (UML-Augmentation) generates a higher number of valid and correct OCL constraints using the GPT-4 model. Moreover the average prompt size crafted using PathOCL significantly decreases when scaling the size of the UML class models.
