---
layout: publication
title: MART Improving LLM Safety With Multi45;round Automatic Red45;teaming
authors: Ge Suyu, Zhou Chunting, Hou Rui, Khabsa Madian, Wang Yi-chia, Wang Qifan, Han Jiawei, Mao Yuning
conference: "Arxiv"
year: 2023
bibkey: ge2023improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.07689"}
tags: ['Applications', 'Prompting', 'Responsible AI', 'Security']
---
Red45;teaming is a common practice for mitigating unsafe behaviors in Large Language Models (LLMs) which involves thoroughly assessing LLMs to identify potential flaws and addressing them with responsible and accurate responses. While effective manual red45;teaming is costly and existing automatic red45;teaming typically discovers safety risks without addressing them. In this paper we propose a Multi45;round Automatic Red45;Teaming (MART) method which incorporates both automatic adversarial prompt writing and safe response generation significantly increasing red45;teaming scalability and the safety of the target LLM. Specifically an adversarial LLM and a target LLM interplay with each other in an iterative manner where the adversarial LLM aims to generate challenging prompts that elicit unsafe responses from the target LLM while the target LLM is fine45;tuned with safety aligned data on these adversarial prompts. In each round the adversarial LLM crafts better attacks on the updated target LLM while the target LLM also improves itself through safety fine45;tuning. On adversarial prompt benchmarks the violation rate of an LLM with limited safety alignment reduces up to 84.737; after 4 rounds of MART achieving comparable performance to LLMs with extensive adversarial prompt writing. Notably model helpfulness on non45;adversarial prompts remains stable throughout iterations indicating the target LLM maintains strong performance on instruction following.
