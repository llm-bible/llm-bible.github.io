---
layout: publication
title: Codeultrafeedback An Llm45;as45;a45;judge Dataset For Aligning Large Language Models To Coding Preferences
authors: Weyssow Martin, Kamanda Aton, Sahraoui Houari
conference: "Arxiv"
year: 2024
bibkey: weyssow2024llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.09032"}
tags: ['Agentic', 'Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Tools']
---
Evaluating the alignment of large language models (LLMs) with user45;defined coding preferences is a challenging endeavour that requires a deep assessment of LLMs outputs. Existing methods and benchmarks rely primarily on automated metrics and static analysis tools which often fail to capture the nuances of user instructions and LLM outputs. To address this gap we propose using the LLM45;as45;a45;Judge methodology to evaluate the alignment of LLMs with coding preferences. Based on this approach we present CodeUltraFeedback a comprehensive dataset designed to facilitate the evaluation and improvement of LLM alignment. CodeUltraFeedback consists of 10000 coding instructions each annotated with four responses generated from a diverse pool of 14 LLMs. These responses are ranked based on five distinct coding preferences using GPT45;3.5 as a judge providing both numerical scores and detailed textual feedback. Our analysis of CodeUltraFeedback reveals that responses from GPT45;3.5 and GPT45;4 are generally preferred over those from open45;weight LLMs highlighting significant differences in alignment between closed and open45;weight models. In turn we explore the usage of CodeUltraFeedback as feedback data to fine45;tune and align CodeLlama45;7B45;Instruct using supervised fine45;tuning (SFT) and reinforcement learning from AI feedback (RLAIF) with direct preference optimization (DPO). The resulting aligned CodeLlama45;7B45;Instruct model outperforms larger LLMs in terms of alignment with coding preferences and shows improved functional correctness on the HumanEval+ benchmark compared to the original instruct model. Therefore our contributions bridge the gap in preference tuning of LLMs for code and set the stage for further advancements in model alignment and RLAIF in automated software engineering.
