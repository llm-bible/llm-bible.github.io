---
layout: publication
title: 'Cognitive Overload Attack:prompt Injection For Long Context'
authors: Bibek Upadhayay, Vahid Behzadan, Amin Karbasi
conference: "Arxiv"
year: 2024
bibkey: upadhayay2024cognitive
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.11272'}
tags: ['In-Context Learning', 'Security', 'GPT', 'Model Architecture', 'Training Techniques', 'Prompting', 'Reinforcement Learning', 'Responsible AI']
---
Large Language Models (LLMs) have demonstrated remarkable capabilities in
performing tasks across various domains without needing explicit retraining.
This capability, known as In-Context Learning (ICL), while impressive, exposes
LLMs to a variety of adversarial prompts and jailbreaks that manipulate
safety-trained LLMs into generating undesired or harmful output. In this paper,
we propose a novel interpretation of ICL in LLMs through the lens of cognitive
neuroscience, by drawing parallels between learning in human cognition with
ICL. We applied the principles of Cognitive Load Theory in LLMs and empirically
validate that similar to human cognition, LLMs also suffer from cognitive
overload a state where the demand on cognitive processing exceeds the available
capacity of the model, leading to potential errors. Furthermore, we
demonstrated how an attacker can exploit ICL to jailbreak LLMs through
deliberately designed prompts that induce cognitive overload on LLMs, thereby
compromising the safety mechanisms of LLMs. We empirically validate this threat
model by crafting various cognitive overload prompts and show that advanced
models such as GPT-4, Claude-3.5 Sonnet, Claude-3 OPUS, Llama-3-70B-Instruct,
Gemini-1.0-Pro, and Gemini-1.5-Pro can be successfully jailbroken, with attack
success rates of up to 99.99%. Our findings highlight critical vulnerabilities
in LLMs and underscore the urgency of developing robust safeguards. We propose
integrating insights from cognitive load theory into the design and evaluation
of LLMs to better anticipate and mitigate the risks of adversarial attacks. By
expanding our experiments to encompass a broader range of models and by
highlighting vulnerabilities in LLMs' ICL, we aim to ensure the development of
safer and more reliable AI systems.
