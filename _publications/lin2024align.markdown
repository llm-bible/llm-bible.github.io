---
layout: publication
title: 'Align-slm: Textless Spoken Language Models With Reinforcement Learning From AI Feedback'
authors: Guan-ting Lin, Prashanth Gurunath Shivakumar, Aditya Gourav, Yile Gu, Ankur Gandhe, Hung-yi Lee, Ivan Bulyko
conference: "Arxiv"
year: 2024
bibkey: lin2024align
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.01834"}
tags: ['Agentic', 'GPT', 'Efficiency and Optimization', 'Tools', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Prompting']
---
While textless Spoken Language Models (SLMs) have shown potential in end-to-end speech-to-speech modeling, they still lag behind text-based Large Language Models (LLMs) in terms of semantic coherence and relevance. This work introduces the Align-SLM framework, which leverages preference optimization inspired by Reinforcement Learning with AI Feedback (RLAIF) to enhance the semantic understanding of SLMs. Our approach generates multiple speech continuations from a given prompt and uses semantic metrics to create preference data for Direct Preference Optimization (DPO). We evaluate the framework using ZeroSpeech 2021 benchmarks for lexical and syntactic modeling, the spoken version of the StoryCloze dataset for semantic coherence, and other speech generation metrics, including the GPT4-o score and human evaluation. Experimental results show that our method achieves state-of-the-art performance for SLMs on most benchmarks, highlighting the importance of preference optimization to improve the semantics of SLMs.
