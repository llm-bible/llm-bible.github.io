---
layout: publication
title: 'DNR Bench: Benchmarking Over-reasoning In Reasoning Llms'
authors: Masoud Hashemi, Oluwanifemi Bamgbose, Sathwik Tejaswi Madhusudhan, Jishnu Sethumadhavan Nair, Aman Tiwari, Vikas Yadav
conference: "Arxiv"
year: 2025
bibkey: hashemi2025dnr
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.15793'}
tags: ['Security', 'GPT', 'Model Architecture', 'Training Techniques', 'Prompting', 'Reinforcement Learning']
---
Test-time scaling has significantly improved large language model
performance, enabling deeper reasoning to solve complex problems. However, this
increased reasoning capability also leads to excessive token generation and
unnecessary problem-solving attempts. We introduce Don\'t Reason Bench (DNR
Bench), a new benchmark designed to evaluate LLMs ability to robustly
understand the tricky reasoning triggers and avoiding unnecessary generation.
DNR Bench consists of 150 adversarially designed prompts that are easy for
humans to understand and respond to, but surprisingly not for many of the
recent prominent LLMs. DNR Bench tests models abilities across different
capabilities, such as instruction adherence, hallucination avoidance,
redundancy filtering, and unanswerable question recognition. We evaluate
reasoning LLMs (RLMs), including DeepSeek-R1, OpenAI O3-mini, Claude-3.7-sonnet
and compare them against a powerful non-reasoning model, e.g., GPT-4o. Our
experiments reveal that RLMs generate up to 70x more tokens than necessary,
often failing at tasks that simpler non-reasoning models handle efficiently
with higher accuracy. Our findings underscore the need for more effective
training and inference strategies in RLMs.
