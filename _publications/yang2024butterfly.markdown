---
layout: publication
title: The Butterfly Effect Of Model Editing\: Few Edits Can Trigger Large Language Models Collapse
authors: Yang Wanli, Sun Fei, Ma Xinyu, Liu Xun, Yin Dawei, Cheng Xueqi
conference: "Arxiv"
year: 2024
bibkey: yang2024butterfly
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.09656"}
tags: ['Attention Mechanism', 'Ethics And Bias', 'GPT', 'Model Architecture', 'Reinforcement Learning']
---
Although model editing has shown promise in revising knowledge in Large Language Models (LLMs) its impact on the inherent capabilities of LLMs is often overlooked. In this work we reveal a critical phenomenon even a single edit can trigger model collapse manifesting as significant performance degradation in various benchmark tasks. However benchmarking LLMs after each edit while necessary to prevent such collapses is impractically time-consuming and resource-intensive. To mitigate this we propose using perplexity as a surrogate metric validated by extensive experiments demonstrating changes in an edited models perplexity are strongly correlated with its downstream task performances. We further conduct an in-depth study on sequential editing a practical setting for real-world scenarios across various editing methods and LLMs focusing on hard cases from our previous single edit studies. The results indicate that nearly all examined editing methods result in model collapse after only few edits. To facilitate further research we have utilized GPT-3.5 to develop a new dataset HardEdit based on those hard cases. This dataset aims to establish the foundation for pioneering research in reliable model editing and the mechanisms underlying editing-induced model collapse. We hope this work can draw the communitys attention to the potential risks inherent in model editing practices.
