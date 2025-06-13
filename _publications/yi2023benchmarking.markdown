---
layout: publication
title: 'Benchmarking And Defending Against Indirect Prompt Injection Attacks On Large Language Models'
authors: Jingwei Yi, Yueqi Xie, Bin Zhu, Emre Kiciman, Guangzhong Sun, Xing Xie, Fangzhao Wu
conference: "Arxiv"
year: 2023
bibkey: yi2023benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.14197"}
tags: ['Security', 'Prompting', 'Applications']
---
The integration of large language models with external content has enabled
applications such as Microsoft Copilot but also introduced vulnerabilities to
indirect prompt injection attacks. In these attacks, malicious instructions
embedded within external content can manipulate LLM outputs, causing deviations
from user expectations. To address this critical yet under-explored issue, we
introduce the first benchmark for indirect prompt injection attacks, named
BIPIA, to assess the risk of such vulnerabilities. Using BIPIA, we evaluate
existing LLMs and find them universally vulnerable. Our analysis identifies two
key factors contributing to their success: LLMs' inability to distinguish
between informational context and actionable instructions, and their lack of
awareness in avoiding the execution of instructions within external content.
Based on these findings, we propose two novel defense mechanisms-boundary
awareness and explicit reminder-to address these vulnerabilities in both
black-box and white-box settings. Extensive experiments demonstrate that our
black-box defense provides substantial mitigation, while our white-box defense
reduces the attack success rate to near-zero levels, all while preserving the
output quality of LLMs. We hope this work inspires further research into
securing LLM applications and fostering their safe and reliable use.
