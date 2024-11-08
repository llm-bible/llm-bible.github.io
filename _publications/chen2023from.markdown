---
layout: publication
title: 'From Good To Great: Improving Math Reasoning With Tool-augmented Interleaf Prompting'
authors: Chen Nuo, Li Hongguang, Wang Baoyuan, Li Jia
conference: "Arxiv"
year: 2023
bibkey: chen2023from
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.05384"}
tags: ['GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Tools']
---
This paper investigates the performance of Large Language Models (LLMs) and
Tool-augmented LLMs in tackling complex mathematical reasoning tasks. We
introduce IMP-TIP: Improving Math Reasoning with Tool-augmented Interleaf
Prompting, a framework that combines the strengths of both LLMs and
Tool-augmented LLMs. IMP-TIP follows the ``From Good to Great" concept,
collecting multiple potential solutions from both LLMs and their Tool-Augmented
counterparts for the same math problem, and then selecting or re-generating the
most accurate answer after cross-checking these solutions via tool-augmented
interleaf prompting. The framework incorporates two key aspects: self-prompt
and tool-augmented interleaf prompting (TIP). The former allows LLMs to
autonomously refine and improve an initial prompt related to tool usage, while
the latter enables LLMs to derive the final answer by dynamically analyzing the
problem, cross-checking potential solutions, and revising previous reasoning
hints in an interleaved manner. Experimental analysis shows that IMP-TIP
achieves enhanced mathematical capabilities and outperforms traditional LLMs
and tool-augmented LLMs in accuracy and reasoning diversity on math reasoning
tasks. For instance, IMP-TIP can improve Tool-augmented ChatGPT on GSM8K-Hard
from 56.0% to 65.2%.
