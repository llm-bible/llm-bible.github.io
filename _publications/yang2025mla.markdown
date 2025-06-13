---
layout: publication
title: 'Mla-trust: Benchmarking Trustworthiness Of Multimodal LLM Agents In GUI Environments'
authors: Xiao Yang, Jiawei Chen, Jun Luo, Zhengwei Fang, Yinpeng Dong, Hang Su, Jun Zhu
conference: "Arxiv"
year: 2025
bibkey: yang2025mla
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.01616"}
tags: ['Responsible AI', 'Agentic', 'Tools', 'Applications', 'Reinforcement Learning', 'Security', 'Multimodal Models']
---
The emergence of multimodal LLM-based agents (MLAs) has transformed interaction paradigms by seamlessly integrating vision, language, action and dynamic environments, enabling unprecedented autonomous capabilities across GUI applications ranging from web automation to mobile systems. However, MLAs introduce critical trustworthiness challenges that extend far beyond traditional language models' limitations, as they can directly modify digital states and trigger irreversible real-world consequences. Existing benchmarks inadequately tackle these unique challenges posed by MLAs' actionable outputs, long-horizon uncertainty and multimodal attack vectors. In this paper, we introduce MLA-Trust, the first comprehensive and unified framework that evaluates the MLA trustworthiness across four principled dimensions: truthfulness, controllability, safety and privacy. We utilize websites and mobile applications as realistic testbeds, designing 34 high-risk interactive tasks and curating rich evaluation datasets. Large-scale experiments involving 13 state-of-the-art agents reveal previously unexplored trustworthiness vulnerabilities unique to multimodal interactive scenarios. For instance, proprietary and open-source GUI-interacting MLAs pose more severe trustworthiness risks than static MLLMs, particularly in high-stakes domains; the transition from static MLLMs into interactive MLAs considerably compromises trustworthiness, enabling harmful content generation in multi-step interactions that standalone MLLMs would typically prevent; multi-step execution, while enhancing the adaptability of MLAs, involves latent nonlinear risk accumulation across successive interactions, circumventing existing safeguards and resulting in unpredictable derived risks. Moreover, we present an extensible toolbox to facilitate continuous evaluation of MLA trustworthiness across diverse interactive environments.
