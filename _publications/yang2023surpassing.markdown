---
layout: publication
title: Surpassing GPT45;4 Medical Coding With A Two45;stage Approach
authors: Yang Zhichao, Batra Sanjit Singh, Stremmel Joel, Halperin Eran
conference: "Arxiv"
year: 2023
bibkey: yang2023surpassing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.13735"}
tags: ['Applications', 'Ethics And Bias', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
Recent advances in large language models (LLMs) show potential for clinical applications such as clinical decision support and trial recommendations. However the GPT45;4 LLM predicts an excessive number of ICD codes for medical coding tasks leading to high recall but low precision. To tackle this challenge we introduce LLM45;codex a two45;stage approach to predict ICD codes that first generates evidence proposals using an LLM and then employs an LSTM45;based verification stage. The LSTM learns from both the LLMs high recall and human experts high precision using a custom loss function. Our model is the only approach that simultaneously achieves state45;of45;the45;art results in medical coding accuracy accuracy on rare codes and sentence45;level evidence identification to support coding decisions without training on human45;annotated evidence according to experiments on the MIMIC dataset.
