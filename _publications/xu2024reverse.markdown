---
layout: publication
title: 'Reverse Image Retrieval Cues Parametric Memory In Multimodal Llms'
authors: Xu Jialiang, Moor Michael, Leskovec Jure
conference: "Arxiv"
year: 2024
bibkey: xu2024reverse
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.18740"}
tags: ['Agentic', 'Applications', 'GPT', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning']
---
Despite impressive advances in recent multimodal large language models (MLLMs) state-of-the-art models such as from the GPT-4 suite still struggle with knowledge-intensive tasks. To address this we consider Reverse Image Retrieval (RIR) augmented generation a simple yet effective strategy to augment MLLMs with web-scale reverse image search results. RIR robustly improves knowledge-intensive visual question answering (VQA) of GPT-4V by 37-4337; GPT-4 Turbo by 25-2737; and GPT-4o by 18-2037; in terms of open-ended VQA evaluation metrics. To our surprise we discover that RIR helps the model to better access its own world knowledge. Concretely our experiments suggest that RIR augmentation helps by providing further visual and textual cues without necessarily containing the direct answer to a query. In addition we elucidate cases in which RIR can hurt performance and conduct a human evaluation. Finally we find that the overall advantage of using RIR makes it difficult for an agent that can choose to use RIR to perform better than an approach where RIR is the default setting.
