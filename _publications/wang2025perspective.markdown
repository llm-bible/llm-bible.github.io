---
layout: publication
title: 'Perspective Transition Of Large Language Models For Solving Subjective Tasks'
authors: Xiaolong Wang, Yuanchi Zhang, Ziyue Wang, Yuzhuang Xu, Fuwen Luo, Yile Wang, Peng Li, Yang Liu
conference: "Arxiv"
year: 2025
bibkey: wang2025perspective
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.09265'}
tags: ['GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Ethics and Bias', 'In-Context Learning']
---
Large language models (LLMs) have revolutionized the field of natural
language processing, enabling remarkable progress in various tasks. Different
from objective tasks such as commonsense reasoning and arithmetic
question-answering, the performance of LLMs on subjective tasks is still
limited, where the perspective on the specific problem plays crucial roles for
better interpreting the context and giving proper response. For example, in
certain scenarios, LLMs may perform better when answering from an expert role
perspective, potentially eliciting their relevant domain knowledge. In
contrast, in some scenarios, LLMs may provide more accurate responses when
answering from a third-person standpoint, enabling a more comprehensive
understanding of the problem and potentially mitigating inherent biases. In
this paper, we propose Reasoning through Perspective Transition (RPT), a method
based on in-context learning that enables LLMs to dynamically select among
direct, role, and third-person perspectives for the best way to solve
corresponding subjective problem. Through extensive experiments on totally 12
subjective tasks by using both closed-source and open-source LLMs including
GPT-4, GPT-3.5, Llama-3, and Qwen-2, our method outperforms widely used single
fixed perspective based methods such as chain-of-thought prompting and expert
prompting, highlights the intricate ways that LLMs can adapt their perspectives
to provide nuanced and contextually appropriate responses for different
problems.
