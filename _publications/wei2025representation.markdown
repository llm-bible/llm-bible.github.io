---
layout: publication
title: 'Rega: Representation-guided Abstraction For Model-based Safeguarding Of Llms'
authors: Zeming Wei, Chengcan Wu, Meng Sun
conference: "Arxiv"
year: 2025
bibkey: wei2025representation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.01770"}
  - {name: "Code", url: "https://github.com/weizeming/ReGA"}
tags: ['Responsible AI', 'Tools', 'Interpretability and Explainability', 'RAG', 'Reinforcement Learning', 'Merging', 'Security', 'Has Code', 'Prompting']
---
Large Language Models (LLMs) have achieved significant success in various tasks, yet concerns about their safety and security have emerged. In particular, they pose risks in generating harmful content and vulnerability to jailbreaking attacks. To analyze and monitor machine learning models, model-based analysis has demonstrated notable potential in stateful deep neural networks, yet suffers from scalability issues when extending to LLMs due to their vast feature spaces. In this paper, we propose ReGA, a model-based analysis framework with representation-guided abstraction, to safeguard LLMs against harmful prompts and generations. By leveraging safety-critical representations, which are low-dimensional directions emerging in hidden states that indicate safety-related concepts, ReGA effectively addresses the scalability issue when constructing the abstract model for safety modeling. Our comprehensive evaluation shows that ReGA performs sufficiently well in distinguishing between safe and harmful inputs, achieving an AUROC of 0.975 at the prompt level and 0.985 at the conversation level. Additionally, ReGA exhibits robustness to real-world attacks and generalization across different safety perspectives, outperforming existing safeguard paradigms in terms of interpretability and scalability. Overall, ReGA serves as an efficient and scalable solution to enhance LLM safety by integrating representation engineering with model-based abstraction, paving the way for new paradigms to utilize software insights for AI safety. Our code is available at https://github.com/weizeming/ReGA.
