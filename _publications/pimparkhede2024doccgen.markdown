---
layout: publication
title: Doccgen Document-based Controlled Code Generation
authors: Pimparkhede Sameer, Kammakomati Mehant, Tamilselvam Srikanth, Kumar Prince, Kumar Ashok Pon, Bhattacharyya Pushpak
conference: "Arxiv"
year: 2024
bibkey: pimparkhede2024doccgen
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11925"}
tags: ['Applications', 'Fine Tuning', 'In Context Learning', 'Pretraining Methods', 'Prompting', 'RAG', 'Tools', 'Training Techniques']
---
Recent developments show that Large Language Models (LLMs) produce state-of-the-art performance on natural language (NL) to code generation for resource-rich general-purpose languages like C++ Java and Python. However their practical usage for structured domain-specific languages (DSLs) such as YAML JSON is limited due to domain-specific schema grammar and customizations generally unseen by LLMs during pre-training. Efforts have been made to mitigate this challenge via in-context learning through relevant examples or by fine-tuning. However it suffers from problems such as limited DSL samples and prompt sensitivity but enterprises maintain good documentation of the DSLs. Therefore we propose DocCGen a framework that can leverage such rich knowledge by breaking the NL-to-Code generation task for structured code languages into a two-step process. First it detects the correct libraries using the library documentation that best matches the NL query. Then it utilizes schema rules extracted from the documentation of these libraries to constrain the decoding. We evaluate our framework for two complex structured languages Ansible YAML and Bash command consisting of two settings Out-of-domain (OOD) and In-domain (ID). Our extensive experiments show that DocCGen consistently improves different-sized language models across all six evaluation metrics reducing syntactic and semantic errors in structured code. We plan to open-source the datasets and code to motivate research in constrained code generation.
