---
layout: publication
title: 'Explain Less, Understand More: Jargon Detection Via Personalized Parameter-efficient Fine-tuning'
authors: Bohao Wu, Qingyun Wang, Yue Guo
conference: "Arxiv"
year: 2025
bibkey: wu2025explain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.16227"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'ACL', 'Interpretability and Explainability', 'Prompting']
---
Personalizing jargon detection and explanation is essential for making technical documents accessible to readers with diverse disciplinary backgrounds. However, tailoring models to individual users typically requires substantial annotation efforts and computational resources due to user-specific finetuning. To address this, we present a systematic study of personalized jargon detection, focusing on methods that are both efficient and scalable for real-world deployment. We explore two personalization strategies: (1) lightweight fine-tuning using Low-Rank Adaptation (LoRA) on open-source models, and (2) personalized prompting, which tailors model behavior at inference time without retaining. To reflect realistic constraints, we also investigate hybrid approaches that combine limited annotated data with unsupervised user background signals. Our personalized LoRA model outperforms GPT-4 by 21.4% in F1 score and exceeds the best performing oracle baseline by 8.3%. Remarkably, our method achieves comparable performance using only 10% of the annotated training data, demonstrating its practicality for resource-constrained settings. Our study offers the first work to systematically explore efficient, low-resource personalization of jargon detection using open-source language models, offering a practical path toward scalable, user-adaptive NLP system.
