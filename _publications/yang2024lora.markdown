---
layout: publication
title: 'Lora-litee: A Computationally Efficient Framework For Chatbot Preference-tuning'
authors: Yahe Yang, Chunliang Tao, Xiaojing Fan
conference: "Arxiv"
year: 2024
bibkey: yang2024lora
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.09947'}
tags: ['Agentic', 'Model Architecture', 'Applications', 'Tools', 'Fine-Tuning', 'Training Techniques', 'GPT', 'Reinforcement Learning', 'Pretraining Methods']
---
Effective preference tuning is pivotal in aligning chatbot responses with
human expectations, enhancing user satisfaction and engagement. Traditional
approaches, notably Reinforcement Learning from Human Feedback (RLHF) as
employed in advanced models like GPT-4, have demonstrated considerable success
in this domain. However, RLHF methods are often computationally intensive and
resource-demanding, limiting their scalability and accessibility for broader
applications. To address these challenges, this study introduces LoRA-Lite
Ensemble (LoRA-LiteE), an innovative framework that combines Supervised
Fine-tuning (SFT) with Low-Rank Adaptation (LoRA) and Ensemble Learning
techniques to effectively aggregate predictions of lightweight models, which
aim to achieve a balance between the performance and computational cost.
Utilizing the Chatbot Arena benchmark dataset, we conduct a comprehensive
comparative analysis among our LoRA-LiteE model, corresponding base models at
different scales, and GPT-4 trained with RLHF. Our empirical results
demonstrate that the proposed LoRA-LiteE model achieves comparable performance
to un-finetuned GPT-4 and outperforms the single larger-scale models under
limited resource constraints. These findings highlight that our LoRA-LiteE
provides a feasible and efficient methodology for human preference prediction
in chatbot systems, enhancing scalability and accessibility, and thereby
broadening the applicability of preference-tuned chatbots in
resource-constrained environments.
