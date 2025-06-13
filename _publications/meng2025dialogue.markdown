---
layout: publication
title: 'Dialogue Injection Attack: Jailbreaking Llms Through Context Manipulation'
authors: Wenlong Meng, Fan Zhang, Wendao Yao, Zhenyuan Guo, Yuwei Li, Chengkun Wei, Wenzhi Chen
conference: "Arxiv"
year: 2025
bibkey: meng2025dialogue
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.08195"}
tags: ['Tools', 'GPT', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Security', 'Prompting']
---
Large language models (LLMs) have demonstrated significant utility in a wide
range of applications; however, their deployment is plagued by security
vulnerabilities, notably jailbreak attacks. These attacks manipulate LLMs to
generate harmful or unethical content by crafting adversarial prompts. While
much of the current research on jailbreak attacks has focused on single-turn
interactions, it has largely overlooked the impact of historical dialogues on
model behavior. In this paper, we introduce a novel jailbreak paradigm,
Dialogue Injection Attack (DIA), which leverages the dialogue history to
enhance the success rates of such attacks. DIA operates in a black-box setting,
requiring only access to the chat API or knowledge of the LLM's chat template.
We propose two methods for constructing adversarial historical dialogues: one
adapts gray-box prefilling attacks, and the other exploits deferred responses.
Our experiments show that DIA achieves state-of-the-art attack success rates on
recent LLMs, including Llama-3.1 and GPT-4o. Additionally, we demonstrate that
DIA can bypass 5 different defense mechanisms, highlighting its robustness and
effectiveness.
