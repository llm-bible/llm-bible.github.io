---
layout: publication
title: 'Evaluating LLM Adaptation To Sociodemographic Factors: User Profile Vs. Dialogue History'
authors: Qishuai Zhong, Zongmin Li, Siqi Fan, Aixin Sun
conference: "Arxiv"
year: 2025
bibkey: zhong2025evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.21362"}
tags: ['Agentic', 'Survey Paper', 'Tools', 'Reinforcement Learning', 'RAG', 'Prompting', 'Applications']
---
Effective engagement by large language models (LLMs) requires adapting responses to users' sociodemographic characteristics, such as age, occupation, and education level. While many real-world applications leverage dialogue history for contextualization, existing evaluations of LLMs' behavioral adaptation often focus on single-turn prompts. In this paper, we propose a framework to evaluate LLM adaptation when attributes are introduced either (1) explicitly via user profiles in the prompt or (2) implicitly through multi-turn dialogue history. We assess the consistency of model behavior across these modalities. Using a multi-agent pipeline, we construct a synthetic dataset pairing dialogue histories with distinct user profiles and employ questions from the Value Survey Module (VSM 2013) (Hofstede and Hofstede, 2016) to probe value expression. Our findings indicate that most models adjust their expressed values in response to demographic changes, particularly in age and education level, but consistency varies. Models with stronger reasoning capabilities demonstrate greater alignment, indicating the importance of reasoning in robust sociodemographic adaptation.
