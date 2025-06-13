---
layout: publication
title: 'Automatic Prompt Selection For Large Language Models'
authors: Viet-tung Do, Van-khanh Hoang, Duy-hung Nguyen, Shahab Sabahi, Jeff Yang, Hajime Hotta, Minh-tien Nguyen, Hung Le
conference: "Arxiv"
year: 2024
bibkey: do2024automatic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.02717'}
tags: ['Prompting', 'Efficiency and Optimization', 'Training Techniques']
---
Large Language Models (LLMs) can perform various natural language processing
tasks with suitable instruction prompts. However, designing effective prompts
manually is challenging and time-consuming. Existing methods for automatic
prompt optimization either lack flexibility or efficiency. In this paper, we
propose an effective approach to automatically select the optimal prompt for a
given input from a finite set of synthetic candidate prompts. Our approach
consists of three steps: (1) clustering the training data and generating
candidate prompts for each cluster using an LLM-based prompt generator; (2)
synthesizing a dataset of input-prompt-output tuples for training a prompt
evaluator to rank the prompts based on their relevance to the input; (3) using
the prompt evaluator to select the best prompt for a new input at test time.
Our approach balances prompt generality-specificity and eliminates the need for
resource-intensive training and inference. It demonstrates competitive
performance on zero-shot question-answering datasets: GSM8K, MultiArith, and
AQuA.
