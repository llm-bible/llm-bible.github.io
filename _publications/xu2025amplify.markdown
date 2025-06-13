---
layout: publication
title: 'Amplify Adjacent Token Differences: Enhancing Long Chain-of-thought Reasoning With Shift-ffn'
authors: Yao Xu, Mingyu Xu, Fangyu Lei, Wangtao Sun, Xiangrong Zeng, Bingning Wang, Guang Liu, Shizhu He, Jun Zhao, Kang Liu
conference: "Arxiv"
year: 2025
bibkey: xu2025amplify
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.17153'}
  - {name: "Code", url: 'https://anonymous.4open.science/r/Shift-FFN'}
tags: ['Has Code', 'Training Techniques', 'Model Architecture', 'Fine-Tuning', 'Pretraining Methods']
---
Recently, models such as OpenAI-o1 and DeepSeek-R1 have demonstrated remarkable performance on complex reasoning tasks through Long Chain-of-Thought (Long-CoT) reasoning. Although distilling this capability into student models significantly enhances their performance, this paper finds that fine-tuning LLMs with full parameters or LoRA with a low rank on long CoT data often leads to Cyclical Reasoning, where models repeatedly reiterate previous inference steps until the maximum length limit. Further analysis reveals that smaller differences in representations between adjacent tokens correlates with a higher tendency toward Cyclical Reasoning. To mitigate this issue, this paper proposes Shift Feedforward Networks (Shift-FFN), a novel approach that edits the current token's representation with the previous one before inputting it to FFN. This architecture dynamically amplifies the representation differences between adjacent tokens. Extensive experiments on multiple mathematical reasoning tasks demonstrate that LoRA combined with Shift-FFN achieves higher accuracy and a lower rate of Cyclical Reasoning across various data sizes compared to full fine-tuning and standard LoRA. Our data and code are available at https://anonymous.4open.science/r/Shift-FFN
