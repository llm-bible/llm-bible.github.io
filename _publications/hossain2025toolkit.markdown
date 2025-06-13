---
layout: publication
title: 'Safetunebed: A Toolkit For Benchmarking LLM Safety Alignment In Fine-tuning'
authors: Saad Hossain, Samanvay Vajpayee, Sirisha Rambhatla
conference: "Arxiv"
year: 2025
bibkey: hossain2025toolkit
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.00676'}
  - {name: "Code", url: 'https://github.com/criticalml-uw/SafeTuneBed'}
tags: ['Has Code', 'ACL', 'Security', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Responsible AI', 'Reinforcement Learning', 'TACL', 'Pretraining Methods']
---
As large language models (LLMs) become ubiquitous, parameter-efficient fine-tuning methods and safety-first defenses have proliferated rapidly. However, the number of approaches and their recent increase have resulted in diverse evaluations-varied datasets, metrics, and inconsistent threat settings-making it difficult to fairly compare safety, utility, and robustness across methods. To address this, we introduce SafeTuneBed, a benchmark and toolkit unifying fine-tuning and defense evaluation. SafeTuneBed (i) curates a diverse repository of multiple fine-tuning datasets spanning sentiment analysis, question-answering, multi-step reasoning, and open-ended instruction tasks, and allows for the generation of harmful-variant splits; (ii) enables integration of state-of-the-art defenses, including alignment-stage immunization, in-training safeguards, and post-tuning repair; and (iii) provides evaluators for safety (attack success rate, refusal consistency) and utility. Built on Python-first, dataclass-driven configs and plugins, SafeTuneBed requires minimal additional code to specify any fine-tuning regime, defense method, and metric suite, while ensuring end-to-end reproducibility. We showcase its value by benchmarking representative defenses across varied poisoning scenarios and tasks. By standardizing data, code, and metrics, SafeTuneBed is the first focused toolkit of its kind to accelerate rigorous and comparable research in safe LLM fine-tuning. Code is available at: https://github.com/criticalml-uw/SafeTuneBed
