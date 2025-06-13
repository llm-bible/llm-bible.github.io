---
layout: publication
title: 'Are You Human? An Adversarial Benchmark To Expose Llms'
authors: Gilad Gressel, Rahul Pankajakshan, Yisroel Mirsky
conference: "Arxiv"
year: 2024
bibkey: gressel2024are
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.09569'}
tags: ['Reinforcement Learning', 'Prompting', 'Security', 'Tools']
---
Large Language Models (LLMs) have demonstrated an alarming ability to
impersonate humans in conversation, raising concerns about their potential
misuse in scams and deception. Humans have a right to know if they are
conversing to an LLM. We evaluate text-based prompts designed as challenges to
expose LLM imposters in real-time. To this end we compile and release an
open-source benchmark dataset that includes 'implicit challenges' that exploit
an LLM's instruction-following mechanism to cause role deviation, and 'exlicit
challenges' that test an LLM's ability to perform simple tasks typically easy
for humans but difficult for LLMs. Our evaluation of 9 leading models from the
LMSYS leaderboard revealed that explicit challenges successfully detected LLMs
in 78.4% of cases, while implicit challenges were effective in 22.9% of
instances. User studies validate the real-world applicability of our methods,
with humans outperforming LLMs on explicit challenges (78% vs 22% success
rate). Our framework unexpectedly revealed that many study participants were
using LLMs to complete tasks, demonstrating its effectiveness in detecting both
AI impostors and human misuse of AI tools. This work addresses the critical
need for reliable, real-time LLM detection methods in high-stakes
conversations.
