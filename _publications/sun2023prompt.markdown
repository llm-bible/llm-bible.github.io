---
layout: publication
title: 'A Prompt Learning Framework For Source Code Summarization'
authors: Sun Weisong, Fang Chunrong, You Yudu, Chen Yuchen, Liu Yi, Wang Chong, Zhang Jian, Zhang Quanjun, Qian Hanwei, Zhao Wei, Liu Yang, Chen Zhenyu
conference: "Arxiv"
year: 2023
bibkey: sun2023prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.16066"}
tags: ['Agentic', 'Applications', 'Efficiency And Optimization', 'Few Shot', 'Fine Tuning', 'Pretraining Methods', 'Prompting', 'Tools', 'Training Techniques']
---
(Source) code summarization is the task of automatically generating natural
language summaries for given code snippets. Such summaries play a key role in
helping developers understand and maintain source code. Recently, with the
successful application of large language models (LLMs) in numerous fields,
software engineering researchers have also attempted to adapt LLMs to solve
code summarization tasks. The main adaptation schemes include instruction
prompting and task-oriented fine-tuning. However, instruction prompting
involves designing crafted prompts for zero-shot learning or selecting
appropriate samples for few-shot learning and requires users to have
professional domain knowledge, while task-oriented fine-tuning requires high
training costs. In this paper, we propose a novel prompt learning framework for
code summarization called PromptCS. PromptCS trains a prompt agent that can
generate continuous prompts to unleash the potential for LLMs in code
summarization. Compared to the human-written discrete prompt, the continuous
prompts are produced under the guidance of LLMs and are therefore easier to
understand by LLMs. PromptCS freezes the parameters of LLMs when training the
prompt agent, which can greatly reduce the requirements for training resources.
We evaluate PromptCS on the CodeSearchNet dataset involving multiple
programming languages. The results show that PromptCS significantly outperforms
instruction prompting schemes on all four widely used metrics. In some base
LLMs, e.g., CodeGen-Multi-2B and StarCoderBase-1B and -3B, PromptCS even
outperforms the task-oriented fine-tuning scheme. More importantly, the
training efficiency of PromptCS is faster than the task-oriented fine-tuning
scheme, with a more pronounced advantage on larger LLMs. The results of the
human evaluation demonstrate that PromptCS can generate more good summaries
compared to baselines.
