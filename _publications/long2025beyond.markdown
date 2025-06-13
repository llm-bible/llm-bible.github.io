---
layout: publication
title: 'Beyond In-context Learning: Aligning Long-form Generation Of Large Language Models Via Task-inherent Attribute Guidelines'
authors: Do Xuan Long, Duong Ngoc Yen, Do Xuan Trong, Luu Anh Tuan, Kenji Kawaguchi, Shafiq Joty, Min-yen Kan, Nancy F. Chen
conference: "Arxiv"
year: 2025
bibkey: long2025beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.01265"}
tags: ['Training Techniques', 'Few-Shot', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Applications', 'In-Context Learning']
---
In-context learning (ICL) is an important yet not fully understood ability of pre-trained large language models (LLMs). It can greatly enhance task performance using a few examples, termed demonstrations, without fine-tuning. Although effective in question answering, ICL often underperforms in long-form generation tasks such as summarization. Under appropriately realistic assumptions, we empirically and theoretically show that ICL demonstrations alone are insufficient to teach LLMs the task language and format distributions for generation. We argue for explicit exposure to the task distributions and hypothesize that defining them by prompting enhances model performance. To this end, we present LongGuide, which efficiently generates two parallel streams of guidelines capturing task language and format properties: (i) Metric Guidelines (MGs) that instruct models to optimize self-evaluated metrics; and (ii) Output Constraint Guidelines (OCGs) that constrain generation at both token and sentence levels. LongGuide automatically selects the best combination of guidelines, improving both strong open- and closed-source LLMs by over 5% in both zero- and few-shot settings. We show that LongGuide is generalizable, learnable by weak models to enhance strong ones, and integrates synergistically with automatic prompt optimizers.
