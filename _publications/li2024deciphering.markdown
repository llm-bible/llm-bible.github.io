---
layout: publication
title: 'Deciphering The Chaos: Enhancing Jailbreak Attacks Via Adversarial Prompt Translation'
authors: Qizhang Li, Xiaochen Yang, Wangmeng Zuo, Yiwen Guo
conference: "Arxiv"
year: 2024
bibkey: li2024deciphering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.11317"}
  - {name: "Code", url: "https://github.com/qizhangli/Adversarial-Prompt-Translator"}
tags: ['Responsible AI', 'GPT', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Security', 'Has Code', 'Prompting']
---
Automatic adversarial prompt generation provides remarkable success in
jailbreaking safely-aligned large language models (LLMs). Existing
gradient-based attacks, while demonstrating outstanding performance in
jailbreaking white-box LLMs, often generate garbled adversarial prompts with
chaotic appearance. These adversarial prompts are difficult to transfer to
other LLMs, hindering their performance in attacking unknown victim models. In
this paper, for the first time, we delve into the semantic meaning embedded in
garbled adversarial prompts and propose a novel method that "translates" them
into coherent and human-readable natural language adversarial prompts. In this
way, we can effectively uncover the semantic information that triggers
vulnerabilities of the model and unambiguously transfer it to the victim model,
without overlooking the adversarial information hidden in the garbled text, to
enhance jailbreak attacks. It also offers a new approach to discovering
effective designs for jailbreak prompts, advancing the understanding of
jailbreak attacks. Experimental results demonstrate that our method
significantly improves the success rate of jailbreak attacks against various
safety-aligned LLMs and outperforms state-of-the-arts by large margins. With at
most 10 queries, our method achieves an average attack success rate of 81.8% in
attacking 7 commercial closed-source LLMs, including GPT and Claude-3 series,
on HarmBench. Our method also achieves over 90% attack success rates against
Llama-2-Chat models on AdvBench, despite their outstanding resistance to
jailbreak attacks. Code at:
https://github.com/qizhangli/Adversarial-Prompt-Translator.
