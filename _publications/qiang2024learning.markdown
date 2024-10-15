---
layout: publication
title: 'Learning To Poison Large Language Models During Instruction Tuning'
authors: Qiang Yao, Zhou Xiangyu, Zade Saleh Zare, Roshani Mohammad Amin, Zytko Douglas, Zhu Dongxiao
conference: "Arxiv"
year: 2024
bibkey: qiang2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.13459"}
  - {name: "Code", url: "https://github.com/RookieZxy/GBTL/blob/main/README.md"}
tags: ['Has Code', 'Security', 'Training Techniques', 'Uncategorized']
---
The advent of Large Language Models (LLMs) has marked significant
achievements in language processing and reasoning capabilities. Despite their
advancements, LLMs face vulnerabilities to data poisoning attacks, where
adversaries insert backdoor triggers into training data to manipulate outputs
for malicious purposes. This work further identifies additional security risks
in LLMs by designing a new data poisoning attack tailored to exploit the
instruction tuning process. We propose a novel gradient-guided backdoor trigger
learning approach to identify adversarial triggers efficiently, ensuring an
evasion of detection by conventional defenses while maintaining content
integrity. Through experimental validation across various LLMs and tasks, our
strategy demonstrates a high success rate in compromising model outputs;
poisoning only 1% of 4,000 instruction tuning samples leads to a Performance
Drop Rate (PDR) of around 80%. Our work highlights the need for stronger
defenses against data poisoning attack, offering insights into safeguarding
LLMs against these more sophisticated attacks. The source code can be found on
this GitHub repository: https://github.com/RookieZxy/GBTL/blob/main/README.md.
