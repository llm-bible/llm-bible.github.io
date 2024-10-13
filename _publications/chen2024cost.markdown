---
layout: publication
title: 'Cost-effective Instruction Learning For Pathology Vision And Language Analysis'
authors: Chen Kaitao, Liu Mianxin, Yan Fang, Ma Lei, Shi Xiaoming, Wang Lilong, Wang Xiaosong, Zhu Lifeng, Wang Zhe, Zhou Mu, Zhang Shaoting
conference: "Arxiv"
year: 2024
bibkey: chen2024cost
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.17734"}
tags: ['Applications', 'Few Shot', 'GPT', 'Large Scale Training', 'Model Architecture', 'Multimodal Models', 'Prompting', 'Security', 'Tools', 'Training Techniques']
---
The advent of vision-language models fosters the interactive conversations
between AI-enabled models and humans. Yet applying these models into clinics
must deal with daunting challenges around large-scale training data, financial,
and computational resources. Here we propose a cost-effective instruction
learning framework for conversational pathology named as CLOVER. CLOVER only
trains a lightweight module and uses instruction tuning while freezing the
parameters of the large language model. Instead of using costly GPT-4, we
propose well-designed prompts on GPT-3.5 for building generation-based
instructions, emphasizing the utility of pathological knowledge derived from
the Internet source. To augment the use of instructions, we construct a
high-quality set of template-based instructions in the context of digital
pathology. From two benchmark datasets, our findings reveal the strength of
hybrid-form instructions in the visual question-answer in pathology. Extensive
results show the cost-effectiveness of CLOVER in answering both open-ended and
closed-ended questions, where CLOVER outperforms strong baselines that possess
37 times more training parameters and use instruction data generated from
GPT-4. Through the instruction tuning, CLOVER exhibits robustness of few-shot
learning in the external clinical dataset. These findings demonstrate that
cost-effective modeling of CLOVER could accelerate the adoption of rapid
conversational applications in the landscape of digital pathology.
