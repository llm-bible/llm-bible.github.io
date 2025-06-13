---
layout: publication
title: 'Evaluating The Efficacy Of LLM Safety Solutions : The Palit Benchmark Dataset'
authors: Sayon Palit, Daniel Woods
conference: "Arxiv"
year: 2025
bibkey: palit2025evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.13028"}
tags: ['Responsible AI', 'Tools', 'GPT', 'Ethics and Bias', 'Model Architecture', 'Interpretability', 'Security', 'Prompting']
---
Large Language Models (LLMs) are increasingly integrated into critical systems in industries like healthcare and finance. Users can often submit queries to LLM-enabled chatbots, some of which can enrich responses with information retrieved from internal databases storing sensitive data. This gives rise to a range of attacks in which a user submits a malicious query and the LLM-system outputs a response that creates harm to the owner, such as leaking internal data or creating legal liability by harming a third-party. While security tools are being developed to counter these threats, there is little formal evaluation of their effectiveness and usability. This study addresses this gap by conducting a thorough comparative analysis of LLM security tools. We identified 13 solutions (9 closed-source, 4 open-source), but only 7 were evaluated due to a lack of participation by proprietary model owners.To evaluate, we built a benchmark dataset of malicious prompts, and evaluate these tools performance against a baseline LLM model (ChatGPT-3.5-Turbo). Our results show that the baseline model has too many false positives to be used for this task. Lakera Guard and ProtectAI LLM Guard emerged as the best overall tools showcasing the tradeoff between usability and performance. The study concluded with recommendations for greater transparency among closed source providers, improved context-aware detections, enhanced open-source engagement, increased user awareness, and the adoption of more representative performance metrics.
