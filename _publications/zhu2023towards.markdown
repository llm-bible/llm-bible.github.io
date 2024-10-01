---
layout: publication
title: 'Towards An On-device Agent For Text Rewriting'
authors: Zhu Yun, Liu Yinxiao, Stahlberg Felix, Kumar Shankar, Chen Yu-hui, Luo Liangchen, Shu Lei, Liu Renjie, Chen Jindong, Meng Lei
conference: "Arxiv"
year: 2023
bibkey: zhu2023towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.11807"}
tags: ['Agentic', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large Language Models (LLMs) have demonstrated impressive capabilities for text rewriting. Nonetheless, the large sizes of these models make them impractical for on-device inference, which would otherwise allow for enhanced privacy and economical inference. Creating a smaller yet potent language model for text rewriting presents a formidable challenge because it requires balancing the need for a small size with the need to retain the emergent capabilities of the LLM, that requires costly data collection. To address the above challenge, we introduce a new instruction tuning approach for building a mobile-centric text rewriting model. Our strategies enable the generation of high quality training data without any human labeling. In addition, we propose a heuristic reinforcement learning framework which substantially enhances performance without requiring preference data. To further bridge the performance gap with the larger server-side model, we propose an effective approach that combines the mobile rewrite agent with the server model using a cascade. To tailor the text rewriting tasks to mobile scenarios, we introduce MessageRewriteEval, a benchmark that focuses on text rewriting for messages through natural language instructions. Through empirical experiments, we demonstrate that our on-device model surpasses the current state-of-the-art LLMs in text rewriting while maintaining a significantly reduced model size. Notably, we show that our proposed cascading approach improves model performance.
