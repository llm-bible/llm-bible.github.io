---
layout: publication
title: 'A Preliminary Study On Using Large Language Models In Software Pentesting'
authors: Shashwat Kumar, Hahn Francis, Ou Xinming, Goldgof Dmitry, Hall Lawrence, Ligatti Jay, Rajgopalan S. Raj, Tabari Armin Ziaie
conference: "Arxiv"
year: 2024
bibkey: shashwat2024preliminary
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.17459"}
tags: ['Agentic', 'GPT', 'Model Architecture', 'Prompting', 'Security', 'Tools', 'Training Techniques']
---
Large language models (LLM) are perceived to offer promising potentials for
automating security tasks, such as those found in security operation centers
(SOCs). As a first step towards evaluating this perceived potential, we
investigate the use of LLMs in software pentesting, where the main task is to
automatically identify software security vulnerabilities in source code. We
hypothesize that an LLM-based AI agent can be improved over time for a specific
security task as human operators interact with it. Such improvement can be
made, as a first step, by engineering prompts fed to the LLM based on the
responses produced, to include relevant contexts and structures so that the
model provides more accurate results. Such engineering efforts become
sustainable if the prompts that are engineered to produce better results on
current tasks, also produce better results on future unknown tasks. To examine
this hypothesis, we utilize the OWASP Benchmark Project 1.2 which contains
2,740 hand-crafted source code test cases containing various types of
vulnerabilities. We divide the test cases into training and testing data, where
we engineer the prompts based on the training data (only), and evaluate the
final system on the testing data. We compare the AI agent's performance on the
testing data against the performance of the agent without the prompt
engineering. We also compare the AI agent's results against those from
SonarQube, a widely used static code analyzer for security testing. We built
and tested multiple versions of the AI agent using different off-the-shelf LLMs
-- Google's Gemini-pro, as well as OpenAI's GPT-3.5-Turbo and GPT-4-Turbo (with
both chat completion and assistant APIs). The results show that using LLMs is a
viable approach to build an AI agent for software pentesting that can improve
through repeated use and prompt engineering.
