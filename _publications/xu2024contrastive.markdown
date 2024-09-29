---
layout: publication
title: Contrastive Preference Optimization\: Pushing The Boundaries Of LLM Performance In Machine Translation
authors: Xu Haoran, Sharaf Amr, Chen Yunmo, Tan Weiting, Shen Lingfeng, Van Durme Benjamin, Murray Kenton, Kim Young Jin
conference: "Arxiv"
year: 2024
bibkey: xu2024contrastive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.08417"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Moderate-sized large language models (LLMs) -- those with 7B or 13B parameters -- exhibit promising machine translation (MT) performance. However even the top-performing 13B LLM-based translation models like ALMA does not match the performance of state-of-the-art conventional encoder-decoder translation models or larger-scale LLMs such as GPT-4. In this study we bridge this performance gap. We first assess the shortcomings of supervised fine-tuning for LLMs in the MT task emphasizing the quality issues present in the reference data despite being human-generated. Then in contrast to SFT which mimics reference translations we introduce Contrastive Preference Optimization (CPO) a novel approach that trains models to avoid generating adequate but not perfect translations. Applying CPO to ALMA models with only 22K parallel sentences and 12M parameters yields significant improvements. The resulting model called ALMA-R can match or exceed the performance of the WMT competition winners and GPT-4 on WMT21 WMT22 and WMT23 test datasets.
