---
layout: publication
title: 'Chain-of-scrutiny: Detecting Backdoor Attacks For Large Language Models'
authors: Xi Li, Ruofan Mao, Yusen Zhang, Renze Lou, Chen Wu, Jiaqi Wang
conference: "Arxiv"
year: 2024
bibkey: li2024chain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.05948"}
tags: ['Tools', 'Ethics and Bias', 'Applications', 'RAG', 'Interpretability', 'Security', 'Prompting']
---
Large Language Models (LLMs), especially those accessed via APIs, have demonstrated impressive capabilities across various domains. However, users without technical expertise often turn to (untrustworthy) third-party services, such as prompt engineering, to enhance their LLM experience, creating vulnerabilities to adversarial threats like backdoor attacks. Backdoor-compromised LLMs generate malicious outputs to users when inputs contain specific "triggers" set by attackers. Traditional defense strategies, originally designed for small-scale models, are impractical for API-accessible LLMs due to limited model access, high computational costs, and data requirements. To address these limitations, we propose Chain-of-Scrutiny (CoS) which leverages LLMs' unique reasoning abilities to mitigate backdoor attacks. It guides the LLM to generate reasoning steps for a given input and scrutinizes for consistency with the final output -- any inconsistencies indicating a potential attack. It is well-suited for the popular API-only LLM deployments, enabling detection at minimal cost and with little data. User-friendly and driven by natural language, it allows non-experts to perform the defense independently while maintaining transparency. We validate the effectiveness of CoS through extensive experiments on various tasks and LLMs, with results showing greater benefits for more powerful LLMs.
