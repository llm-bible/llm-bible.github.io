---
layout: publication
title: Gemini Goes To Med School\: Exploring The Capabilities Of Multimodal Large Language Models On Medical Challenge Problems & Hallucinations
authors: Pal Ankit, Sankarasubbu Malaikannan
conference: "Arxiv"
year: 2024
bibkey: pal2024gemini
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.07023"}
  - {name: "Code", url: "https://github.com/promptslab/RosettaEval"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Prompting', 'Responsible AI']
---
Large language models have the potential to be valuable in the healthcare industry but its crucial to verify their safety and effectiveness through rigorous evaluation. For this purpose we comprehensively evaluated both open-source LLMs and Googles new multimodal LLM called Gemini across Medical reasoning hallucination detection and Medical Visual Question Answering tasks. While Gemini showed competence it lagged behind state-of-the-art models like MedPaLM 2 and GPT-4 in diagnostic accuracy. Additionally Gemini achieved an accuracy of 61.4537; on the medical VQA dataset significantly lower than GPT-4Vs score of 8837;. Our analysis revealed that Gemini is highly susceptible to hallucinations overconfidence and knowledge gaps which indicate risks if deployed uncritically. We also performed a detailed analysis by medical subject and test type providing actionable feedback for developers and clinicians. To mitigate risks we applied prompting strategies that improved performance. Additionally we facilitated future research and development by releasing a Python module for medical LLM evaluation and establishing a dedicated leaderboard on Hugging Face for medical domain LLMs. Python module can be found at https://github.com/promptslab/RosettaEval"
