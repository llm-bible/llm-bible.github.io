---
layout: publication
title: A Careful Examination Of Large Language Model Performance On Grade School Arithmetic
authors: Zhang Hugh, Da Jeff, Lee Dean, Robinson Vaughn, Wu Catherine, Song Will, Zhao Tiffany, Raja Pranav, Slack Dylan, Lyu Qin, Hendryx Sean, Kaplan Russell, Lunati Michele, Yue Summer
conference: "Arxiv"
year: 2024
bibkey: zhang2024careful
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.00332"}
tags: ['Ethics And Bias', 'GPT', 'Model Architecture', 'Training Techniques']
---
Large language models (LLMs) have achieved impressive success on many benchmarks for mathematical reasoning. However there is growing concern that some of this performance actually reflects dataset contamination where data closely resembling benchmark questions leaks into the training data instead of true reasoning ability. To investigate this claim rigorously we commission Grade School Math 1000 (GSM1k). GSM1k is designed to mirror the style and complexity of the established GSM8k benchmark the gold standard for measuring elementary mathematical reasoning. We ensure that the two benchmarks are comparable across important metrics such as human solve rates number of steps in solution answer magnitude and more. When evaluating leading open- and closed-source LLMs on GSM1k we observe accuracy drops of up to 1337; with several families of models (e.g. Phi and Mistral) showing evidence of systematic overfitting across almost all model sizes. At the same time many models especially those on the frontier (e.g. Gemini/GPT/Claude) show minimal signs of overfitting. Further analysis suggests a positive relationship (Spearmans r^2=0.32) between a models probability of generating an example from GSM8k and its performance gap between GSM8k and GSM1k suggesting that many models may have partially memorized GSM8k.
