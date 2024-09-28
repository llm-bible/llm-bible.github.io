---
layout: publication
title: Jailbroken How Does LLM Safety Training Fail
authors: Wei Alexander, Haghtalab Nika, Steinhardt Jacob
conference: "Arxiv"
year: 2023
bibkey: wei2023jailbroken
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.02483"}
tags: ['ARXIV', 'Chatgpt', 'GPT', 'LLM', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Responsible AI', 'Security']
---
Large language models trained for safety and harmlessness remain susceptible to adversarial misuse as evidenced by the prevalence of jailbreak attacks on early releases of ChatGPT that elicit undesired behavior. Going beyond recognition of the issue we investigate why such attacks succeed and how they can be created. We hypothesize two failure modes of safety training competing objectives and mismatched generalization. Competing objectives arise when a models capabilities and safety goals conflict while mismatched generalization occurs when safety training fails to generalize to a domain for which capabilities exist. We use these failure modes to guide jailbreak design and then evaluate state-of-the-art models including OpenAIs GPT-4 and Anthropics Claude v1.3 against both existing and newly designed attacks. We find that vulnerabilities persist despite the extensive red-teaming and safety-training efforts behind these models. Notably new attacks utilizing our failure modes succeed on every prompt in a collection of unsafe requests from the models red-teaming evaluation sets and outperform existing ad hoc jailbreaks. Our analysis emphasizes the need for safety-capability parity -- that safety mechanisms should be as sophisticated as the underlying model -- and argues against the idea that scaling alone can resolve these safety failure modes.
