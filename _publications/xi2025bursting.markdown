---
layout: publication
title: 'Bursting Filter Bubble: Enhancing Serendipity Recommendations With Aligned Large Language Models'
authors: Yunjia Xi, Muyan Weng, Wen Chen, Chao Yi, Dian Chen, Gaoyang Guo, Mao Zhang, Jian Wu, Yuning Jiang, Qingwen Liu, Yong Yu, Weinan Zhang
conference: "Arxiv"
year: 2025
bibkey: xi2025bursting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.13539"}
tags: ['Tools', 'GPT', 'Ethics and Bias', 'Model Architecture', 'Reinforcement Learning', 'RecSys', 'Training Techniques']
---
Recommender systems (RSs) often suffer from the feedback loop phenomenon,
e.g., RSs are trained on data biased by their recommendations. This leads to
the filter bubble effect that reinforces homogeneous content and reduces user
satisfaction. To this end, serendipity recommendations, which offer unexpected
yet relevant items, are proposed. Recently, large language models (LLMs) have
shown potential in serendipity prediction due to their extensive world
knowledge and reasoning capabilities. However, they still face challenges in
aligning serendipity judgments with human assessments, handling long user
behavior sequences, and meeting the latency requirements of industrial RSs. To
address these issues, we propose SERAL (Serendipity Recommendations with
Aligned Large Language Models), a framework comprising three stages: (1)
Cognition Profile Generation to compress user behavior into multi-level
profiles; (2) SerenGPT Alignment to align serendipity judgments with human
preferences using enriched training data; and (3) Nearline Adaptation to
integrate SerenGPT into industrial RSs pipelines efficiently. Online
experiments demonstrate that SERAL improves exposure ratio (PVR), clicks, and
transactions of serendipitous items by 5.7%, 29.56%, and 27.6%, enhancing user
experience without much impact on overall revenue. Now, it has been fully
deployed in the "Guess What You Like" of the Taobao App homepage.
