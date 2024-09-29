---
layout: publication
title: METAL Towards Multilingual Meta-evaluation
authors: Hada Rishav, Gumma Varun, Ahmed Mohamed, Bali Kalika, Sitaram Sunayana
conference: "Arxiv"
year: 2024
bibkey: hada2024metal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.01667"}
tags: ['Applications', 'Ethics And Bias', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Tools']
---
With the rising human-like precision of Large Language Models (LLMs) in numerous tasks their utilization in a variety of real-world applications is becoming more prevalent. Several studies have shown that LLMs excel on many standard NLP benchmarks. However it is challenging to evaluate LLMs due to test dataset contamination and the limitations of traditional metrics. Since human evaluations are difficult to collect there is a growing interest in the community to use LLMs themselves as reference-free evaluators for subjective metrics. However past work has shown that LLM-based evaluators can exhibit bias and have poor alignment with human judgments. In this study we propose a framework for an end-to-end assessment of LLMs as evaluators in multilingual scenarios. We create a carefully curated dataset covering 10 languages containing native speaker judgments for the task of summarization. This dataset is created specifically to evaluate LLM-based evaluators which we refer to as meta-evaluation (METAL). We compare the performance of LLM-based evaluators created using GPT-3.5-Turbo GPT-4 and PaLM2. Our results indicate that LLM-based evaluators based on GPT-4 perform the best across languages while GPT-3.5-Turbo performs poorly. Additionally we perform an analysis of the reasoning provided by LLM-based evaluators and find that it often does not match the reasoning provided by human judges.
