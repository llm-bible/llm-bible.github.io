---
layout: publication
title: 'Qwen2.5 Technical Report'
authors: Additional Authors Not Shown Qwen, Additional Authors Not Shown :, An Additional Authors Not Shown Yang, Baosong Additional Authors Not Shown Yang, Beichen Additional Authors Not Shown Zhang, Binyuan Additional Authors Not Shown Hui, Bo Additional Authors Not Shown Zheng, Bowen Additional Authors Not Shown Yu, Chengyuan Additional Authors Not Shown Li, Dayiheng Additional Authors Not Shown Liu, Fei Additional Authors Not Shown Huang, Haoran Additional Authors Not Shown Wei, Huan Additional Authors Not Shown Lin, Jian Additional Authors Not Shown Yang, Jianhong Additional Authors Not Shown Tu, Jianwei Additional Authors Not Shown Zhang, Jianxin Additional Authors Not Shown Yang, Jiaxi Additional Authors Not Shown Yang, Jingren Additional Authors Not Shown Zhou, Junyang Additional Authors Not Shown Lin, Kai Additional Authors Not Shown Dang, Keming Additional Authors Not Shown Lu, Keqin Additional Authors Not Shown Bao, Kexin Additional Authors Not Shown Yang, Le Additional Authors Not Shown Yu, Mei Additional Authors Not Shown Li, Mingfeng Additional Authors Not Shown Xue, Pei Additional Authors Not Shown Zhang, Qin Additional Authors Not Shown Zhu, Rui Additional Authors Not Shown Men, Runji Additional Authors Not Shown Lin, Tianhao Additional Authors Not Shown Li, Tianyi Additional Authors Not Shown Tang, Tingyu Additional Authors Not Shown Xia, Xingzhang Additional Authors Not Shown Ren, Xuancheng Additional Authors Not Shown Ren, Yang Additional Authors Not Shown Fan, Yang Additional Authors Not Shown Su, Yichang Additional Authors Not Shown Zhang, Yu Additional Authors Not Shown Wan, Yuqiong Additional Authors Not Shown Liu, Zeyu Additional Authors Not Shown Cui, Zhenru Additional Authors Not Shown Zhang, Zihan Additional Authors Not Shown Qiu
conference: "Arxiv"
year: 2024
bibkey: qwen2024technical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.15115"}
tags: ['Pre-Training', 'Agentic', 'GPT', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Language Modeling', 'Training Techniques', 'Multimodal Models']
---
In this report, we introduce Qwen2.5, a comprehensive series of large
language models (LLMs) designed to meet diverse needs. Compared to previous
iterations, Qwen 2.5 has been significantly improved during both the
pre-training and post-training stages. In terms of pre-training, we have scaled
the high-quality pre-training datasets from the previous 7 trillion tokens to
18 trillion tokens. This provides a strong foundation for common sense, expert
knowledge, and reasoning capabilities. In terms of post-training, we implement
intricate supervised finetuning with over 1 million samples, as well as
multistage reinforcement learning. Post-training techniques enhance human
preference, and notably improve long text generation, structural data analysis,
and instruction following. To handle diverse and varied use cases effectively,
we present Qwen2.5 LLM series in rich sizes. Open-weight offerings include base
and instruction-tuned models, with quantized versions available. In addition,
for hosted solutions, the proprietary models currently include two
mixture-of-experts (MoE) variants: Qwen2.5-Turbo and Qwen2.5-Plus, both
available from Alibaba Cloud Model Studio. Qwen2.5 has demonstrated top-tier
performance on a wide range of benchmarks evaluating language understanding,
reasoning, mathematics, coding, human preference alignment, etc. Specifically,
the open-weight flagship Qwen2.5-72B-Instruct outperforms a number of open and
proprietary models and demonstrates competitive performance to the
state-of-the-art open-weight model, Llama-3-405B-Instruct, which is around 5
times larger. Qwen2.5-Turbo and Qwen2.5-Plus offer superior cost-effectiveness
while performing competitively against GPT-4o-mini and GPT-4o respectively.
Additionally, as the foundation, Qwen2.5 models have been instrumental in
training specialized models such as Qwen2.5-Math, Qwen2.5-Coder, QwQ, and
multimodal models.
