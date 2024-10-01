---
layout: publication
title: 'Beyond Labels: Aligning Large Language Models With Human-like Reasoning'
authors: Kabir Muhammad Rafsan, Sultan Rafeed Mohammad, Asif Ihsanul Haque, Ahad Jawad Ibn, Rahman Fuad, Amin Mohammad Ruhul, Mohammed Nabeel, Rahman Shafin
conference: "Arxiv"
year: 2024
bibkey: kabir2024beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.11879"}
  - {name: "Code", url: "https://github.com/apurba-nsu-rnd-lab/DFAR"}
tags: ['Ethics And Bias', 'Fine Tuning', 'Has Code', 'Pretraining Methods', 'Responsible AI', 'Training Techniques']
---
Aligning large language models (LLMs) with a human reasoning approach ensures that LLMs produce morally correct and human-like decisions. Ethical concerns are raised because current models are prone to generating false positives and providing malicious responses. To contribute to this issue, we have curated an ethics dataset named Dataset for Aligning Reasons (DFAR), designed to aid in aligning language models to generate human-like reasons. The dataset comprises statements with ethical-unethical labels and their corresponding reasons. In this study, we employed a unique and novel fine-tuning approach that utilizes ethics labels and their corresponding reasons (L+R), in contrast to the existing fine-tuning approach that only uses labels (L). The original pre-trained versions, the existing fine-tuned versions, and our proposed fine-tuned versions of LLMs were then evaluated on an ethical-unethical classification task and a reason-generation task. Our proposed fine-tuning strategy notably outperforms the others in both tasks, achieving significantly higher accuracy scores in the classification task and lower misalignment rates in the reason-generation task. The increase in classification accuracies and decrease in misalignment rates indicate that the L+R fine-tuned models align more with human ethics. Hence, this study illustrates that injecting reasons has substantially improved the alignment of LLMs, resulting in more human-like responses. We have made the DFAR dataset and corresponding codes publicly available at https://github.com/apurba-nsu-rnd-lab/DFAR.
