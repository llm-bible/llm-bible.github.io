---
layout: publication
title: WordGame Efficient Effective LLM Jailbreak via Simultaneous Obfuscation in Query and Response
authors: Zhang Tianrong, Cao Bochuan, Cao Yuanpu, Lin Lu, Mitra Prasenjit, Chen Jinghui
conference: "Arxiv"
year: 2024
bibkey: zhang2024wordgame
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.14023"}
tags: ['Applications', 'GPT', 'Model Architecture', 'RAG', 'Responsible AI', 'Security']
---
The recent breakthrough in large language models (LLMs) such as ChatGPT has revolutionized production processes at an unprecedented pace. Alongside this progress also comes mounting concerns about LLMs susceptibility to jailbreaking attacks which leads to the generation of harmful or unsafe content. While safety alignment measures have been implemented in LLMs to mitigate existing jailbreak attempts and force them to become increasingly complicated it is still far from perfect. In this paper we analyze the common pattern of the current safety alignment and show that it is possible to exploit such patterns for jailbreaking attacks by simultaneous obfuscation in queries and responses. Specifically we propose WordGame attack which replaces malicious words with word games to break down the adversarial intent of a query and encourage benign content regarding the games to precede the anticipated harmful content in the response creating a context that is hardly covered by any corpus used for safety alignment. Extensive experiments demonstrate that WordGame attack can break the guardrails of the current leading proprietary and open-source LLMs including the latest Claude-3 GPT-4 and Llama-3 models. Further ablation studies on such simultaneous obfuscation in query and response provide evidence of the merits of the attack strategy beyond an individual attack.
