---
layout: publication
title: 'Speak Out Of Turn: Safety Vulnerability Of Large Language Models In Multi-turn Dialogue'
authors: Zhenhong Zhou, Jiuyang Xiang, Haopeng Chen, Quan Liu, Zherui Li, Sen Su
conference: "Arxiv"
year: 2024
bibkey: zhou2024speak
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.17262"}
tags: ['Responsible AI', 'Security', 'Reinforcement Learning']
---
Large Language Models (LLMs) have been demonstrated to generate illegal or
unethical responses, particularly when subjected to "jailbreak." Research on
jailbreak has highlighted the safety issues of LLMs. However, prior studies
have predominantly focused on single-turn dialogue, ignoring the potential
complexities and risks presented by multi-turn dialogue, a crucial mode through
which humans derive information from LLMs. In this paper, we argue that humans
could exploit multi-turn dialogue to induce LLMs into generating harmful
information. LLMs may not intend to reject cautionary or borderline unsafe
queries, even if each turn is closely served for one malicious purpose in a
multi-turn dialogue. Therefore, by decomposing an unsafe query into several
sub-queries for multi-turn dialogue, we induced LLMs to answer harmful
sub-questions incrementally, culminating in an overall harmful response. Our
experiments, conducted across a wide range of LLMs, indicate current
inadequacies in the safety mechanisms of LLMs in multi-turn dialogue. Our
findings expose vulnerabilities of LLMs in complex scenarios involving
multi-turn dialogue, presenting new challenges for the safety of LLMs.
