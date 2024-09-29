---
layout: publication
title: 'Turning Generative Models Degenerate: The Power Of Data Poisoning Attacks'
authors: Jiang Shuli, Kadhe Swanand Ravindra, Zhou Yi, Ahmed Farhan, Cai Ling, Baracaldo Nathalie
conference: "Arxiv"
year: 2024
bibkey: jiang2024turning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.12281"}
tags: ['Applications', 'Fine Tuning', 'Pretraining Methods', 'Security', 'Training Techniques']
---
The increasing use of large language models (LLMs) trained by third parties raises significant security concerns. In particular malicious actors can introduce backdoors through poisoning attacks to generate undesirable outputs. While such attacks have been extensively studied in image domains and classification tasks they remain underexplored for natural language generation (NLG) tasks. To address this gap we conduct an investigation of various poisoning techniques targeting the LLMs fine-tuning phase via prefix-tuning a Parameter Efficient Fine-Tuning (PEFT) method. We assess their effectiveness across two generative tasks text summarization and text completion; and we also introduce new metrics to quantify the success and stealthiness of such NLG poisoning attacks. Through our experiments we find that the prefix-tuning hyperparameters and trigger designs are the most crucial factors to influence attack success and stealthiness. Moreover we demonstrate that existing popular defenses are ineffective against our poisoning attacks. Our study presents the first systematic approach to understanding poisoning attacks targeting NLG tasks during fine-tuning via PEFT across a wide range of triggers and attack settings. We hope our findings will aid the AI security community in developing effective defenses against such threats.
