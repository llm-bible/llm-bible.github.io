---
layout: publication
title: 'Agent-environment Alignment Via Automated Interface Generation'
authors: Kaiming Liu, Xuanyu Lei, Ziyue Wang, Peng Li, Yang Liu
conference: "Arxiv"
year: 2025
bibkey: liu2025agent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.21055"}
  - {name: "Code", url: "https://github.com/THUNLP-MT/ALIGN"}
tags: ['Agentic', 'Tools', 'Model Architecture', 'Reinforcement Learning', 'Has Code']
---
Large language model (LLM) agents have shown impressive reasoning capabilities in interactive decision-making tasks. These agents interact with environment through intermediate interfaces, such as predefined action spaces and interaction rules, which mediate the perception and action. However, mismatches often happen between the internal expectations of the agent regarding the influence of its issued actions and the actual state transitions in the environment, a phenomenon referred to as \textbf\{agent-environment misalignment\}. While prior work has invested substantially in improving agent strategies and environment design, the critical role of the interface still remains underexplored. In this work, we empirically demonstrate that agent-environment misalignment poses a significant bottleneck to agent performance. To mitigate this issue, we propose \textbf\{ALIGN\}, an \underline\{A\}uto-A\underline\{l\}igned \underline\{I\}nterface \underline\{G\}e\underline\{n\}eration framework that alleviates the misalignment by enriching the interface. Specifically, the ALIGN-generated interface enhances both the static information of the environment and the step-wise observations returned to the agent. Implemented as a lightweight wrapper, this interface achieves the alignment without modifying either the agent logic or the environment code. Experiments across multiple domains including embodied tasks, web navigation and tool-use, show consistent performance improvements, with up to a 45.67% success rate improvement observed in ALFWorld. Meanwhile, ALIGN-generated interface can generalize across different agent architectures and LLM backbones without interface regeneration. Code and experimental results are available at https://github.com/THUNLP-MT/ALIGN.
