---
layout: publication
title: 'VPO: Aligning Text-to-video Generation Models With Prompt Optimization'
authors: Jiale Cheng, Ruiliang Lyu, Xiaotao Gu, Xiao Liu, Jiazheng Xu, Yida Lu, Jiayan Teng, Zhuoyi Yang, Yuxiao Dong, Jie Tang, Hongning Wang, Minlie Huang
conference: "Arxiv"
year: 2025
bibkey: cheng2025aligning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.20491'}
  - {name: "Code", url: 'https://github.com/thu-coai/VPO'}
tags: ['Has Code', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Responsible AI', 'Pretraining Methods']
---
Video generation models have achieved remarkable progress in text-to-video
tasks. These models are typically trained on text-video pairs with highly
detailed and carefully crafted descriptions, while real-world user inputs
during inference are often concise, vague, or poorly structured. This gap makes
prompt optimization crucial for generating high-quality videos. Current methods
often rely on large language models (LLMs) to refine prompts through in-context
learning, but suffer from several limitations: they may distort user intent,
omit critical details, or introduce safety risks. Moreover, they optimize
prompts without considering the impact on the final video quality, which can
lead to suboptimal results. To address these issues, we introduce VPO, a
principled framework that optimizes prompts based on three core principles:
harmlessness, accuracy, and helpfulness. The generated prompts faithfully
preserve user intents and, more importantly, enhance the safety and quality of
generated videos. To achieve this, VPO employs a two-stage optimization
approach. First, we construct and refine a supervised fine-tuning (SFT) dataset
based on principles of safety and alignment. Second, we introduce both
text-level and video-level feedback to further optimize the SFT model with
preference learning. Our extensive experiments demonstrate that VPO
significantly improves safety, alignment, and video quality compared to
baseline methods. Moreover, VPO shows strong generalization across video
generation models. Furthermore, we demonstrate that VPO could outperform and be
combined with RLHF methods on video generation models, underscoring the
effectiveness of VPO in aligning video generation models. Our code and data are
publicly available at https://github.com/thu-coai/VPO.
