---
layout: publication
title: Demystifying Platform Requirements for Diverse LLM Inference Use Cases
authors: Bambhaniya Abhimanyu, Raj Ritik, Jeong Geonhwa, Kundu Souvik, Srinivasan Sudarshan, Elavazhagan Midhilesh, Kumar Madhu, Krishna Tushar
conference: "Arxiv"
year: 2024
bibkey: bambhaniya2024demystifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.01698"}
  - {name: "Code", url: "https://github.com/abhibambhaniya/GenZ-LLM-Analyzer"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Reinforcement Learning', 'Tools']
---
Large language models (LLMs) have shown remarkable performance across a wide range of applications often outperforming human experts. However deploying these parameter-heavy models efficiently for diverse inference use cases requires carefully designed hardware platforms with ample computing memory and network resources. With LLM deployment scenarios and models evolving at breakneck speed the hardware requirements to meet SLOs remains an open research question. In this work we present an analytical tool GenZ to study the relationship between LLM inference performance and various platform design parameters. Our analysis provides insights into configuring platforms for different LLM workloads and use cases. We quantify the platform requirements to support SOTA LLMs models like LLaMA and GPT-4 under diverse serving settings. Furthermore we project the hardware capabilities needed to enable future LLMs potentially exceeding hundreds of trillions of parameters. The trends and insights derived from GenZ can guide AI engineers deploying LLMs as well as computer architects designing next-generation hardware accelerators and platforms. Ultimately this work sheds light on the platform design considerations for unlocking the full potential of large language models across a spectrum of applications. The source code is available at https://github.com/abhibambhaniya/GenZ-LLM-Analyzer .
