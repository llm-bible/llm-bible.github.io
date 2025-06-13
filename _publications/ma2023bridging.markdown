---
layout: publication
title: 'Bridging Code Semantic And Llms: Semantic Chain-of-thought Prompting For Code Generation'
authors: Yingwei Ma, Yue Yu, Shanshan Li, Yu Jiang, Yong Guo, Yuanliang Zhang, Yutao Xie, Xiangke Liao
conference: "Arxiv"
year: 2023
bibkey: ma2023bridging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.10698"}
tags: ['GPT', 'Applications', 'RAG', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
Large language models (LLMs) have showcased remarkable prowess in code
generation. However, automated code generation is still challenging since it
requires a high-level semantic mapping between natural language requirements
and codes. Most existing LLMs-based approaches for code generation rely on
decoder-only causal language models often treate codes merely as plain text
tokens, i.e., feeding the requirements as a prompt input, and outputing code as
flat sequence of tokens, potentially missing the rich semantic features
inherent in source code. To bridge this gap, this paper proposes the "Semantic
Chain-of-Thought" approach to intruduce semantic information of code, named
SeCoT. Our motivation is that the semantic information of the source code (\eg
data flow and control flow) describes more precise program execution behavior,
intention and function. By guiding LLM consider and integrate semantic
information, we can achieve a more granular understanding and representation of
code, enhancing code generation accuracy. Meanwhile, while traditional
techniques leveraging such semantic information require complex static or
dynamic code analysis to obtain features such as data flow and control flow,
SeCoT demonstrates that this process can be fully automated via the intrinsic
capabilities of LLMs (i.e., in-context learning), while being generalizable and
applicable to challenging domains. While SeCoT can be applied with different
LLMs, this paper focuses on the powerful GPT-style models: ChatGPT(close-source
model) and WizardCoder(open-source model). The experimental study on three
popular DL benchmarks (i.e., HumanEval, HumanEval-ET and MBPP) shows that SeCoT
can achieves state-of-the-art performance, greatly improving the potential for
large models and code generation.
