---
layout: publication
title: 'Promises, Outlooks And Challenges Of Diffusion Language Modeling'
authors: Deschenaux Justin, Gulcehre Caglar
conference: "Arxiv"
year: 2024
bibkey: deschenaux2024outlooks
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11473"}
tags: ['Ethics And Bias', 'GPT', 'Language Modeling', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
The modern autoregressive Large Language Models (LLMs) have achieved outstanding performance on NLP benchmarks and they are deployed in the real world. However they still suffer from limitations of the autoregressive training paradigm. For example autoregressive token generation is notably slow and can be prone to (textit)exposure bias. The diffusion-based language models were proposed as an alternative to autoregressive generation to address some of these limitations. We evaluate the recently proposed Score Entropy Discrete Diffusion (SEDD) approach and show it is a promising alternative to autoregressive generation but it has some short-comings too. We empirically demonstrate the advantages and challenges of SEDD and observe that SEDD generally matches autoregressive models in perplexity and on benchmarks such as HellaSwag Arc or WinoGrande. Additionally we show that in terms of inference latency SEDD can be up to 4.5(times) more efficient than GPT-2. While SEDD allows conditioning on tokens at abitrary positions SEDD appears slightly weaker than GPT-2 for conditional generation given short prompts. Finally we reproduced the main results from the original SEDD paper.
