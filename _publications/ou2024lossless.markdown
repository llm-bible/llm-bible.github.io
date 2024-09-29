---
layout: publication
title: Lossless Acceleration Of Large Language Model Via Adaptive N45;gram Parallel Decoding
authors: Ou Jie, Chen Yueming, Tian Wenhong
conference: "Arxiv"
year: 2024
bibkey: ou2024lossless
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.08698"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques']
---
While Large Language Models (LLMs) have shown remarkable abilities they are hindered by significant resource consumption and considerable latency due to autoregressive processing. In this study we introduce Adaptive N45;gram Parallel Decoding (ANPD) an innovative and lossless approach that accelerates inference by allowing the simultaneous generation of multiple tokens. ANPD incorporates a two45;stage approach it begins with a rapid drafting phase that employs an N45;gram module which adapts based on the current interactive context followed by a verification phase during which the original LLM assesses and confirms the proposed tokens. Consequently ANPD preserves the integrity of the LLMs original output while enhancing processing speed. We further leverage a multi45;level architecture for the N45;gram module to enhance the precision of the initial draft consequently reducing inference latency. ANPD eliminates the need for retraining or extra GPU memory making it an efficient and plug45;and45;play enhancement. In our experiments models such as LLaMA and its fine45;tuned variants have shown speed improvements up to 3.67x validating the effectiveness of our proposed ANPD.
