---
layout: publication
title: WILBUR&#58; Adaptive In-context Learning For Robust And Accurate Web Agents
authors: Lutz Michael, Bohra Arth, Saroyan Manvel, Harutyunyan Artem, Campagna Giovanni
conference: "Arxiv"
year: 2024
bibkey: lutz2024adaptive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.05902"}
tags: ['Agentic', 'Fine Tuning', 'In Context Learning', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
In the realm of web agent research achieving both generalization and accuracy remains a challenging problem. Due to high variance in website structure existing approaches often fail. Moreover existing fine-tuning and in-context learning techniques fail to generalize across multiple websites. We introduce Wilbur an approach that uses a differentiable ranking model and a novel instruction synthesis technique to optimally populate a black-box large language models prompt with task demonstrations from previous runs. To maximize end-to-end success rates we also propose an intelligent backtracking mechanism that learns and recovers from its mistakes. Finally we show that our ranking model can be trained on data from a generative auto-curriculum which samples representative goals from an LLM runs the agent and automatically evaluates it with no manual annotation. Wilbur achieves state-of-the-art results on the WebVoyager benchmark beating text-only models by 837; overall and up to 3637; on certain websites. On the same benchmark Wilbur is within 537; of a strong multi-modal model despite only receiving textual inputs and further analysis reveals a substantial number of failures are due to engineering challenges of operating the web.
