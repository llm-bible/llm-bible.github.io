---
layout: publication
title: 'Debiasing Vison-language Models With Text-only Training'
authors: Yunfan Yang, Chaoquan Jiang, Zhiyu Lin, Jinlin Xiao, Jiaming Zhang, Jitao Sang
conference: "Arxiv"
year: 2024
bibkey: yang2024debiasing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.09365"}
tags: ['Security', 'Training Techniques', 'Multimodal Models', 'Tools', 'Reinforcement Learning', 'RAG', 'Ethics and Bias', 'Prompting', 'Applications']
---
Pre-trained vision-language models (VLMs), such as CLIP, have exhibited
remarkable performance across various downstream tasks by aligning text and
images in a unified embedding space. However, due to the imbalanced
distribution of pre-trained datasets, CLIP suffers from the bias problem in
real-world applications. Existing debiasing methods struggle to obtain
sufficient image samples for minority groups and incur high costs for group
labeling. To address the limitations, we propose a Text-Only Debiasing
framework called TOD, leveraging a text-as-image training paradigm to mitigate
visual biases. Specifically, this approach repurposes the text encoder to
function as an image encoder, thereby eliminating the need for image data.
Simultaneously, it utilizes a large language model (LLM) to generate a balanced
text dataset, which is then used for prompt tuning. However, we observed that
the model overfits to the text modality because label names, serving as
supervision signals, appear explicitly in the texts. To address this issue, we
further introduce a Multi-Target Prediction (MTP) task that motivates the model
to focus on complex contexts and distinguish between target and biased
information. Extensive experiments on the Waterbirds and CelebA datasets show
that our method significantly improves group robustness, achieving
state-of-the-art results among image-free methods and even competitive
performance compared to image-supervised methods. Furthermore, the proposed
method can be adapted to challenging scenarios with multiple or unknown bias
attributes, demonstrating its strong generalization and robustness.
