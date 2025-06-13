---
layout: publication
title: 'On The Robustness Tradeoff In Fine-tuning'
authors: Kunyang Li, Jean-charles Noirot Ferrand, Ryan Sheatsley, Blaine Hoak, Yohan Beugin, Eric Pauley, Patrick Mcdaniel
conference: "Arxiv"
year: 2025
bibkey: li2025robustness
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.14836"}
tags: ['Fine-Tuning', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
Fine-tuning has become the standard practice for adapting pre-trained
(upstream) models to downstream tasks. However, the impact on model robustness
is not well understood. In this work, we characterize the robustness-accuracy
trade-off in fine-tuning. We evaluate the robustness and accuracy of fine-tuned
models over 6 benchmark datasets and 7 different fine-tuning strategies. We
observe a consistent trade-off between adversarial robustness and accuracy.
Peripheral updates such as BitFit are more effective for simple tasks--over 75%
above the average measured with area under the Pareto frontiers on CIFAR-10 and
CIFAR-100. In contrast, fine-tuning information-heavy layers, such as attention
layers via Compacter, achieves a better Pareto frontier on more complex
tasks--57.5% and 34.6% above the average on Caltech-256 and CUB-200,
respectively. Lastly, we observe that robustness of fine-tuning against
out-of-distribution data closely tracks accuracy. These insights emphasize the
need for robustness-aware fine-tuning to ensure reliable real-world
deployments.
