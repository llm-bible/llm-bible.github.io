---
layout: publication
title: 'Hijacking Large Language Models Via Adversarial In-context Learning'
authors: Xiangyu Zhou, Yao Qiang, Saleh Zare Zade, Prashant Khanduri, Dongxiao Zhu
conference: "Arxiv"
year: 2023
bibkey: zhou2023hijacking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09948"}
tags: ['RAG', 'Security', 'Prompting', 'In-Context Learning']
---
In-context learning (ICL) has emerged as a powerful paradigm leveraging LLMs for specific downstream tasks by utilizing labeled examples as demonstrations (demos) in the preconditioned prompts. Despite its promising performance, crafted adversarial attacks pose a notable threat to the robustness of LLMs. Existing attacks are either easy to detect, require a trigger in user input, or lack specificity towards ICL. To address these issues, this work introduces a novel transferable prompt injection attack against ICL, aiming to hijack LLMs to generate the target output or elicit harmful responses. In our threat model, the hacker acts as a model publisher who leverages a gradient-based prompt search method to learn and append imperceptible adversarial suffixes to the in-context demos via prompt injection. We also propose effective defense strategies using a few shots of clean demos, enhancing the robustness of LLMs during ICL. Extensive experimental results across various classification and jailbreak tasks demonstrate the effectiveness of the proposed attack and defense strategies. This work highlights the significant security vulnerabilities of LLMs during ICL and underscores the need for further in-depth studies.
