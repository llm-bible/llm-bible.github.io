---
layout: publication
title: Primacy Effect of ChatGPT
authors: Wang Yiwei, Cai Yujun, Chen Muhao, Liang Yuxuan, Hooi Bryan
conference: "Arxiv"
year: 2023
bibkey: wang2023primacy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.13206"}
  - {name: "Code", url: "https://github.com/wangywUST/PrimacyEffectGPT"}
tags: ['ARXIV', 'Fine Tuning', 'Has Code', 'Pretraining Methods', 'Prompt']
---
Instruction-tuned large language models (LLMs) such as ChatGPT have led to promising zero-shot performance in discriminative natural language understanding (NLU) tasks. This involves querying the LLM using a prompt containing the question and the candidate labels to choose from. The question-answering capabilities of ChatGPT arise from its pre-training on large amounts of human-written text as well as its subsequent fine-tuning on human preferences which motivates us to ask Does ChatGPT also inherits humans cognitive biases In this paper we study the primacy effect of ChatGPT the tendency of selecting the labels at earlier positions as the answer. We have two main findings i) ChatGPTs decision is sensitive to the order of labels in the prompt; ii) ChatGPT has a clearly higher chance to select the labels at earlier positions as the answer. We hope that our experiments and analyses provide additional insights into building more reliable ChatGPT-based solutions. We release the source code at https://github.com/wangywUST/PrimacyEffectGPT.
