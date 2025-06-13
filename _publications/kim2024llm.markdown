---
layout: publication
title: 'Llm-as-an-interviewer: Beyond Static Testing Through Dynamic LLM Evaluation'
authors: Eunsu Kim, Juyoung Suk, Seungone Kim, Niklas Muennighoff, Dongkwan Kim, Alice Oh
conference: "Arxiv"
year: 2024
bibkey: kim2024llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.10424"}
  - {name: "Code", url: "https://github.com/interview-eval/"}
tags: ['Tools', 'Ethics and Bias', 'RAG', 'Reinforcement Learning', 'Has Code']
---
We introduce LLM-as-an-Interviewer, a novel paradigm for evaluating large language models (LLMs). This approach leverages multi-turn interactions where the LLM interviewer actively provides feedback on responses and poses follow-up questions to the evaluated LLM. At the start of the interview, the LLM interviewer dynamically modifies datasets to generate initial questions, mitigating data contamination. We apply the LLM-as-an-Interviewer framework to evaluate six models on the MATH and DepthQA tasks. Our results show that the framework effectively provides insights into LLM performance, including the quality of initial responses, adaptability to feedback, and ability to address follow-up queries like clarification or additional knowledge requests. The framework also addresses key limitations of conventional methods like LLM-as-a-Judge, including verbosity bias and inconsistency across runs. Finally, we propose the Interview Report, which aggregates insights from the interview process, providing examples and a comprehensive analysis of the LLM's strengths and weaknesses. This report offers a detailed snapshot of the model's real-world applicability. The code for our framework is publicly available at https://github.com/interview-eval/.
