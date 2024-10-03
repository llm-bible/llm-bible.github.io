---
layout: publication
title: 'Benchmarking Trustworthiness Of Multimodal Large Language Models: A Comprehensive Study'
authors: Zhang Yichi, Huang Yao, Sun Yitong, Liu Chang, Zhao Zhe, Fang Zhengwei, Wang Yifan, Chen Huanran, Yang Xiao, Wei Xingxing, Su Hang, Dong Yinpeng, Zhu Jun
conference: "Arxiv"
year: 2024
bibkey: zhang2024benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07057"}
  - {name: "Code", url: "https://multi-trust.github.io/"}
tags: ['Bias Mitigation', 'Ethics And Bias', 'Fairness', 'Has Code', 'Multimodal Models', 'Responsible AI', 'Security']
---
Despite the superior capabilities of Multimodal Large Language Models (MLLMs) across diverse tasks, they still face significant trustworthiness challenges. Yet, current literature on the assessment of trustworthy MLLMs remains limited, lacking a holistic evaluation to offer thorough insights into future improvements. In this work, we establish MultiTrust, the first comprehensive and unified benchmark on the trustworthiness of MLLMs across five primary aspects: truthfulness, safety, robustness, fairness, and privacy. Our benchmark employs a rigorous evaluation strategy that addresses both multimodal risks and cross-modal impacts, encompassing 32 diverse tasks with self-curated datasets. Extensive experiments with 21 modern MLLMs reveal some previously unexplored trustworthiness issues and risks, highlighting the complexities introduced by the multimodality and underscoring the necessity for advanced methodologies to enhance their reliability. For instance, typical proprietary models still struggle with the perception of visually confusing images and are vulnerable to multimodal jailbreaking and adversarial attacks; MLLMs are more inclined to disclose privacy in text and reveal ideological and cultural biases even when paired with irrelevant images in inference, indicating that the multimodality amplifies the internal risks from base LLMs. Additionally, we release a scalable toolbox for standardized trustworthiness research, aiming to facilitate future advancements in this important field. Code and resources are publicly available at: https://multi-trust.github.io/.
