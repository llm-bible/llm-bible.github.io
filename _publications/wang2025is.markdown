---
layout: publication
title: 'Is Your Prompt Safe? Investigating Prompt Injection Attacks Against Open-source Llms'
authors: Jiawen Wang, Pritha Gupta, Ivan Habernal, Eyke Hüllermeier
conference: "Arxiv"
year: 2025
bibkey: wang2025is
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.14368'}
tags: ['Prompting', 'Security']
---
Recent studies demonstrate that Large Language Models (LLMs) are vulnerable to different prompt-based attacks, generating harmful content or sensitive information. Both closed-source and open-source LLMs are underinvestigated for these attacks. This paper studies effective prompt injection attacks against the \\(\mathbf\{14\}\\) most popular open-source LLMs on five attack benchmarks. Current metrics only consider successful attacks, whereas our proposed Attack Success Probability (ASP) also captures uncertainty in the model's response, reflecting ambiguity in attack feasibility. By comprehensively analyzing the effectiveness of prompt injection attacks, we propose a simple and effective hypnotism attack; results show that this attack causes aligned language models, including Stablelm2, Mistral, Openchat, and Vicuna, to generate objectionable behaviors, achieving around \\(90\\)% ASP. They also indicate that our ignore prefix attacks can break all \\(\mathbf\{14\}\\) open-source LLMs, achieving over \\(60\\)% ASP on a multi-categorical dataset. We find that moderately well-known LLMs exhibit higher vulnerability to prompt injection attacks, highlighting the need to raise public awareness and prioritize efficient mitigation strategies.
