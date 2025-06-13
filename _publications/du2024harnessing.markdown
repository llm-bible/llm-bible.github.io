---
layout: publication
title: 'Haloscope: Harnessing Unlabeled LLM Generations For Hallucination Detection'
authors: Xuefeng Du, Chaowei Xiao, Yixuan Li
conference: "Arxiv"
year: 2024
bibkey: du2024harnessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.17504"}
  - {name: "Code", url: "https://github.com/deeplearningwisc/haloscope"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Has Code', 'Prompting', 'Applications']
---
The surge in applications of large language models (LLMs) has prompted
concerns about the generation of misleading or fabricated information, known as
hallucinations. Therefore, detecting hallucinations has become critical to
maintaining trust in LLM-generated content. A primary challenge in learning a
truthfulness classifier is the lack of a large amount of labeled truthful and
hallucinated data. To address the challenge, we introduce HaloScope, a novel
learning framework that leverages the unlabeled LLM generations in the wild for
hallucination detection. Such unlabeled data arises freely upon deploying LLMs
in the open world, and consists of both truthful and hallucinated information.
To harness the unlabeled data, we present an automated membership estimation
score for distinguishing between truthful and untruthful generations within
unlabeled mixture data, thereby enabling the training of a binary truthfulness
classifier on top. Importantly, our framework does not require extra data
collection and human annotations, offering strong flexibility and practicality
for real-world applications. Extensive experiments show that HaloScope can
achieve superior hallucination detection performance, outperforming the
competitive rivals by a significant margin. Code is available at
https://github.com/deeplearningwisc/haloscope.
