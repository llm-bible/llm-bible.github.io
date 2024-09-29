---
layout: publication
title: Smoothllm Defending Large Language Models Against Jailbreaking Attacks
authors: Robey Alexander, Wong Eric, Hassani Hamed, Pappas George J.
conference: "Arxiv"
year: 2023
bibkey: robey2023defending
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.03684"}
  - {name: "Code", url: "https://github.com/arobey1/smooth-llm\"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Security']
---
Despite efforts to align large language models (LLMs) with human intentions widely-used LLMs such as GPT Llama and Claude are susceptible to jailbreaking attacks wherein an adversary fools a targeted LLM into generating objectionable content. To address this vulnerability we propose SmoothLLM the first algorithm designed to mitigate jailbreaking attacks. Based on our finding that adversarially-generated prompts are brittle to character-level changes our defense randomly perturbs multiple copies of a given input prompt and then aggregates the corresponding predictions to detect adversarial inputs. Across a range of popular LLMs SmoothLLM sets the state-of-the-art for robustness against the GCG PAIR RandomSearch and AmpleGCG jailbreaks. SmoothLLM is also resistant against adaptive GCG attacks exhibits a small though non-negligible trade-off between robustness and nominal performance and is compatible with any LLM. Our code is publicly available at (url)https://github.com/arobey1/smooth-llm\}.
