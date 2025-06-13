---
layout: publication
title: 'Mapping Your Model: Assessing The Impact Of Adversarial Attacks On Llm-based Programming Assistants'
authors: John Heibel, Daniel Lowd
conference: "Arxiv"
year: 2024
bibkey: heibel2024mapping
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.11072"}
tags: ['Prompting', 'Security', 'Agentic']
---
LLM-based programming assistants offer the promise of programming faster but
with the risk of introducing more security vulnerabilities. Prior work has
studied how LLMs could be maliciously fine-tuned to suggest vulnerabilities
more often. With the rise of agentic LLMs, which may use results from an
untrusted third party, there is a growing risk of attacks on the model's
prompt. We introduce the Malicious Programming Prompt (MaPP) attack, in which
an attacker adds a small amount of text to a prompt for a programming task
(under 500 bytes). We show that our prompt strategy can cause an LLM to add
vulnerabilities while continuing to write otherwise correct code. We evaluate
three prompts on seven common LLMs, from basic to state-of-the-art commercial
models. Using the HumanEval benchmark, we find that our prompts are broadly
effective, with no customization required for different LLMs. Furthermore, the
LLMs that are best at HumanEval are also best at following our malicious
instructions, suggesting that simply scaling language models will not prevent
MaPP attacks. Using a dataset of eight CWEs in 16 scenarios, we find that MaPP
attacks are also effective at implementing specific and targeted
vulnerabilities across a range of models. Our work highlights the need to
secure LLM prompts against manipulation as well as rigorously auditing code
generated with the help of LLMs.
