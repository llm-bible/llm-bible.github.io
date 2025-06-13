---
layout: publication
title: 'Position Is Power: System Prompts As A Mechanism Of Bias In Large Language Models (llms)'
authors: Anna Neumann, Elisabeth Kirsten, Muhammad Bilal Zafar, Jatinder Singh
conference: "Arxiv"
year: 2025
bibkey: neumann2025position
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.21091"}
tags: ['Model Architecture', 'Reinforcement Learning', 'Ethics and Bias', 'Interpretability', 'Prompting', 'Applications', 'Attention Mechanism']
---
System prompts in Large Language Models (LLMs) are predefined directives that guide model behaviour, taking precedence over user inputs in text processing and generation. LLM deployers increasingly use them to ensure consistent responses across contexts. While model providers set a foundation of system prompts, deployers and third-party developers can append additional prompts without visibility into others' additions, while this layered implementation remains entirely hidden from end-users. As system prompts become more complex, they can directly or indirectly introduce unaccounted for side effects. This lack of transparency raises fundamental questions about how the position of information in different directives shapes model outputs. As such, this work examines how the placement of information affects model behaviour. To this end, we compare how models process demographic information in system versus user prompts across six commercially available LLMs and 50 demographic groups. Our analysis reveals significant biases, manifesting in differences in user representation and decision-making scenarios. Since these variations stem from inaccessible and opaque system-level configurations, they risk representational, allocative and potential other biases and downstream harms beyond the user's ability to detect or correct. Our findings draw attention to these critical issues, which have the potential to perpetuate harms if left unexamined. Further, we argue that system prompt analysis must be incorporated into AI auditing processes, particularly as customisable system prompts become increasingly prevalent in commercial AI deployments.
