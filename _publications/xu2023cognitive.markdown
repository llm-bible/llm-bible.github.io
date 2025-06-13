---
layout: publication
title: 'Cognitive Overload: Jailbreaking Large Language Models With Overloaded Logical Thinking'
authors: Nan Xu, Fei Wang, Ben Zhou, Bang Zheng Li, Chaowei Xiao, Muhao Chen
conference: "Arxiv"
year: 2023
bibkey: xu2023cognitive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09827"}
tags: ['Responsible AI', 'Security', 'Model Architecture', 'Reinforcement Learning', 'GPT']
---
While large language models (LLMs) have demonstrated increasing power, they
have also given rise to a wide range of harmful behaviors. As representatives,
jailbreak attacks can provoke harmful or unethical responses from LLMs, even
after safety alignment. In this paper, we investigate a novel category of
jailbreak attacks specifically designed to target the cognitive structure and
processes of LLMs. Specifically, we analyze the safety vulnerability of LLMs in
the face of (1) multilingual cognitive overload, (2) veiled expression, and (3)
effect-to-cause reasoning. Different from previous jailbreak attacks, our
proposed cognitive overload is a black-box attack with no need for knowledge of
model architecture or access to model weights. Experiments conducted on
AdvBench and MasterKey reveal that various LLMs, including both popular
open-source model Llama 2 and the proprietary model ChatGPT, can be compromised
through cognitive overload. Motivated by cognitive psychology work on managing
cognitive load, we further investigate defending cognitive overload attack from
two perspectives. Empirical studies show that our cognitive overload from three
perspectives can jailbreak all studied LLMs successfully, while existing
defense strategies can hardly mitigate the caused malicious uses effectively.
