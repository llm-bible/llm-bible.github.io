---
layout: publication
title: 'Cape: Context-aware Prompt Perturbation Mechanism With Differential Privacy'
authors: Haoqi Wu, Wei Dai, Li Wang, Qiang Yan
conference: "Arxiv"
year: 2025
bibkey: wu2025context
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.05922"}
tags: ['Prompting', 'Efficiency and Optimization', 'Model Architecture', 'GPT']
---
Large Language Models (LLMs) have gained significant popularity due to their remarkable capabilities in text understanding and generation. However, despite their widespread deployment in inference services such as ChatGPT, concerns about the potential leakage of sensitive user data have arisen. Existing solutions primarily rely on privacy-enhancing technologies to mitigate such risks, facing the trade-off among efficiency, privacy, and utility. To narrow this gap, we propose Cape, a context-aware prompt perturbation mechanism based on differential privacy, to enable efficient inference with an improved privacy-utility trade-off. Concretely, we introduce a hybrid utility function that better captures the token similarity. Additionally, we propose a bucketized sampling mechanism to handle large sampling space, which might lead to long-tail phenomenons. Extensive experiments across multiple datasets, along with ablation studies, demonstrate that Cape achieves a better privacy-utility trade-off compared to prior state-of-the-art works.
