---
layout: publication
title: 'A Prompt Learning Framework For Source Code Summarization'
authors: Tingting Xu, Yun Miao, Chunrong Fang, Hanwei Qian, Xia Feng, Zhenpeng Chen, Chong Wang, Jian Zhang, Weisong Sun, Zhenyu Chen, Yang Liu
conference: "Arxiv"
year: 2023
bibkey: xu2023prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.16066"}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Few-Shot', 'Tools', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Applications']
---
(Source) code summarization is the task of automatically generating natural
language summaries (also called comments) for given code snippets. Recently,
with the successful application of large language models (LLMs) in numerous
fields, software engineering researchers have also attempted to adapt LLMs to
solve code summarization tasks. The main adaptation schemes include instruction
prompting, task-oriented (full-parameter) fine-tuning, and parameter-efficient
fine-tuning (PEFT). However, instruction prompting involves designing crafted
prompts and requires users to have professional domain knowledge, while
task-oriented fine-tuning requires high training costs, and effective, tailored
PEFT methods for code summarization are still lacking.
  This paper proposes an effective prompt learning framework for code
summarization called PromptCS. It no longer requires users to rack their brains
to design effective prompts. Instead, PromptCS trains a prompt agent that can
generate continuous prompts to unleash the potential for LLMs in code
summarization. Compared to the human-written discrete prompt, the continuous
prompts are produced under the guidance of LLMs and are therefore easier to
understand by LLMs. PromptCS is non-invasive to LLMs and freezes the parameters
of LLMs when training the prompt agent, which can greatly reduce the
requirements for training resources. Our comprehensive experimental results
show that PromptCS significantly outperforms instruction prompting schemes
(including zero-shot learning and few-shot learning) on all four widely used
metrics, and is comparable to the task-oriented fine-tuning scheme. In some
base LLMs, e.g., StarCoderBase-1B and -3B, PromptCS even outperforms the
task-oriented fine-tuning scheme. More importantly, the training efficiency of
PromptCS is faster than the task-oriented fine-tuning scheme, with a more
pronounced advantage on larger LLMs.
