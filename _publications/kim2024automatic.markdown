---
layout: publication
title: Automatic Jailbreaking Of The Text-to-image Generative AI Systems
authors: Kim Minseon, Lee Hyomin, Gong Boqing, Zhang Huishuai, Hwang Sung Ju
conference: "Arxiv"
year: 2024
bibkey: kim2024automatic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.16567"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Responsible AI', 'Security', 'Tools']
---
Recent AI systems have shown extremely powerful performance even surpassing human performance on various tasks such as information retrieval language generation and image generation based on large language models (LLMs). At the same time there are diverse safety risks that can cause the generation of malicious contents by circumventing the alignment in LLMs which are often referred to as jailbreaking. However most of the previous works only focused on the text-based jailbreaking in LLMs and the jailbreaking of the text-to-image (T2I) generation system has been relatively overlooked. In this paper we first evaluate the safety of the commercial T2I generation systems such as ChatGPT Copilot and Gemini on copyright infringement with naive prompts. From this empirical study we find that Copilot and Gemini block only 1237; and 1737; of the attacks with naive prompts respectively while ChatGPT blocks 8437; of them. Then we further propose a stronger automated jailbreaking pipeline for T2I generation systems which produces prompts that bypass their safety guards. Our automated jailbreaking framework leverages an LLM optimizer to generate prompts to maximize degree of violation from the generated images without any weight updates or gradient computation. Surprisingly our simple yet effective approach successfully jailbreaks the ChatGPT with 11.037; block rate making it generate copyrighted contents in 7637; of the time. Finally we explore various defense strategies such as post-generation filtering and machine unlearning techniques but found that they were inadequate which suggests the necessity of stronger defense mechanisms.
