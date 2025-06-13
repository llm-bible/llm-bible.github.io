---
layout: publication
title: 'FOCUS: First Order Concentrated Updating Scheme'
authors: Yizhou Liu, Ziming Liu, Jeff Gore
conference: "Arxiv"
year: 2025
bibkey: liu2025first
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.12243"}
tags: ['Training Techniques', 'Model Architecture', 'RAG', 'GPT', 'Pre-Training']
---
Large language models (LLMs) demonstrate remarkable performance, and
improving their pre-training process appears to be key to enhancing their
capabilities further. Based on the documented success of Adam, learning rate
decay, and weight decay, we hypothesize that the pre-training loss landscape
features a narrowing valley structure. Through experiments with synthetic loss
functions, we discover that when gradient query noise is high relative to the
valley's sharpness, Adam's performance falls behind that of Signum because Adam
reduces the effective step size too drastically. This observation led us to
develop FOCUS, an optimizer that enhances Signum by incorporating attraction
toward moving averaged parameters, allowing it to handle noise better while
maintaining larger step sizes. In training GPT-2, FOCUS proves to be more
stable than Signum and faster than Adam. These results suggest that gradient
noise may be an underappreciated limiting factor in LLM training, and FOCUS
offers promising solutions.
