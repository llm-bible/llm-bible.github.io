---
layout: publication
title: 'What Features In Prompts Jailbreak Llms? Investigating The Mechanisms Behind Attacks'
authors: Nathalie Kirch, Constantin Weisser, Severin Field, Helen Yannakoudakis, Stephen Casper
conference: "Arxiv"
year: 2024
bibkey: kirch2024what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.03343"}
tags: ['Responsible AI', 'Security', 'Reinforcement Learning', 'RAG', 'Prompting']
---
Jailbreaks have been a central focus of research regarding the safety and reliability of large language models (LLMs), yet the mechanisms underlying these attacks remain poorly understood. While previous studies have predominantly relied on linear methods to detect jailbreak attempts and model refusals, we take a different approach by examining both linear and non-linear features in prompts that lead to successful jailbreaks. First, we introduce a novel dataset comprising 10,800 jailbreak attempts spanning 35 diverse attack methods. Leveraging this dataset, we train probes to classify successful from unsuccessful jailbreaks using the latent representations corresponding to prompt tokens. Notably, we find that even when probes achieve high accuracy in predicting the success of jailbreaks, their performance often fails to generalize to unseen attack methods. This reveals that different jailbreaking strategies exploit different non-linear, non-universal features. Next, we demonstrate that non-linear probes provide a powerful tool for steering model behavior. Specifically, we use these probes to guide targeted latent space perturbations, enabling us to effectively modulate the model's robustness against jailbreaks. Overall, our findings challenge the assumption that jailbreaks can be fully understood through linear or simple universal prompt features alone, highlighting the importance of a nuanced understanding of the mechanisms behind LLM vulnerabilities.
