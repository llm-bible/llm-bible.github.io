---
layout: publication
title: 'When "competency" In Reasoning Opens The Door To Vulnerability: Jailbreaking Llms Via Novel Complex Ciphers'
authors: Divij Handa, Zehua Zhang, Amir Saeidi, Shrinidhi Kumbhar, Chitta Baral
conference: "Arxiv"
year: 2024
bibkey: handa2024when
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.10601"}
tags: ['Responsible AI', 'Security', 'Training Techniques', 'Model Architecture', 'GPT']
---
Recent advancements in Large Language Model (LLM) safety have primarily
focused on mitigating attacks crafted in natural language or common ciphers
(e.g. Base64), which are likely integrated into newer models' safety training.
However, we reveal a paradoxical vulnerability: as LLMs advance in reasoning,
they inadvertently become more susceptible to novel jailbreaking attacks.
Enhanced reasoning enables LLMs to interpret complex instructions and decode
complex user-defined ciphers, creating an exploitable security gap. To study
this vulnerability, we introduce Attacks using Custom Encryptions (ACE), a
jailbreaking technique that encodes malicious queries with novel ciphers.
Extending ACE, we introduce Layered Attacks using Custom Encryptions (LACE),
which applies multi-layer ciphers to amplify attack complexity. Furthermore, we
develop CipherBench, a benchmark designed to evaluate LLMs' accuracy in
decoding encrypted benign text. Our experiments reveal a critical trade-off:
LLMs that are more capable of decoding ciphers are more vulnerable to these
jailbreaking attacks, with success rates on GPT-4o escalating from 40% under
ACE to 78% with LACE. These findings highlight a critical insight: as LLMs
become more adept at deciphering complex user ciphers--many of which cannot be
preemptively included in safety training--they become increasingly exploitable.
