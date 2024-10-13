---
layout: publication
title: 'Efficient Finetuning Large Language Models For Vietnamese Chatbot'
authors: Doan Vu-thuan, Truong Quoc-truong, Nguyen Duc-vu, Nguyen Vinh-tiep, Luu Thuy-ngan Nguyen
conference: "Arxiv"
year: 2023
bibkey: doan2023efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.04646"}
tags: ['Fine Tuning', 'GPT', 'Model Architecture', 'RAG', 'Training Techniques']
---
Large language models (LLMs), such as GPT-4, PaLM, and LLaMa, have been shown
to achieve remarkable performance across a variety of natural language tasks.
Recent advancements in instruction tuning bring LLMs with ability in following
user's instructions and producing human-like responses. However, the high costs
associated with training and implementing LLMs pose challenges to academic
research. Furthermore, the availability of pretrained LLMs and instruction-tune
datasets for Vietnamese language is limited. To tackle these concerns, we
leverage large-scale instruction-following datasets from open-source projects,
namely Alpaca, GPT4All, and Chat-Doctor, which cover general domain and
specific medical domain. To the best of our knowledge, these are the first
instructional dataset for Vietnamese. Subsequently, we utilize
parameter-efficient tuning through Low-Rank Adaptation (LoRA) on two open LLMs:
Bloomz (Multilingual) and GPTJ-6B (Vietnamese), resulting four models:
Bloomz-Chat, Bloomz-Doctor, GPTJ-Chat, GPTJ-Doctor.Finally, we assess the
effectiveness of our methodology on a per-sample basis, taking into
consideration the helpfulness, relevance, accuracy, level of detail in their
responses. This evaluation process entails the utilization of GPT-4 as an
automated scoring mechanism. Despite utilizing a low-cost setup, our method
demonstrates about 20-30\% improvement over the original models in our
evaluation tasks.
