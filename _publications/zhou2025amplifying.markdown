---
layout: publication
title: 'Safekey: Amplifying Aha-moment Insights For Safety Reasoning'
authors: Kaiwen Zhou, Xuandong Zhao, Gaowen Liu, Jayanth Srinivasa, Aosong Feng, Dawn Song, Xin Eric Wang
conference: "Arxiv"
year: 2025
bibkey: zhou2025amplifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.16186"}
tags: ['Responsible AI', 'Security', 'Model Architecture', 'Training Techniques', 'Tools', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Attention Mechanism']
---
Large Reasoning Models (LRMs) introduce a new generation paradigm of explicitly reasoning before answering, leading to remarkable improvements in complex tasks. However, they pose great safety risks against harmful queries and adversarial attacks. While recent mainstream safety efforts on LRMs, supervised fine-tuning (SFT), improve safety performance, we find that SFT-aligned models struggle to generalize to unseen jailbreak prompts. After thorough investigation of LRMs' generation, we identify a safety aha moment that can activate safety reasoning and lead to a safe response. This aha moment typically appears in the `key sentence', which follows models' query understanding process and can indicate whether the model will proceed safely. Based on these insights, we propose SafeKey, including two complementary objectives to better activate the safety aha moment in the key sentence: (1) a Dual-Path Safety Head to enhance the safety signal in the model's internal representations before the key sentence, and (2) a Query-Mask Modeling objective to improve the models' attention on its query understanding, which has important safety hints. Experiments across multiple safety benchmarks demonstrate that our methods significantly improve safety generalization to a wide range of jailbreak attacks and out-of-distribution harmful prompts, lowering the average harmfulness rate by 9.6%, while maintaining general abilities. Our analysis reveals how SafeKey enhances safety by reshaping internal attention and improving the quality of hidden representations.
