---
layout: publication
title: AvatarGPT All-in-One Framework for Motion Understanding Planning Generation and Beyond
authors: Zhou Zixiang, Wan Yu, Wang Baoyuan
conference: "Arxiv"
year: 2023
bibkey: zhou2023avatargpt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.16468"}
tags: ['Ethics And Bias', 'GPT', 'Model Architecture', 'Tools']
---
Large Language Models(LLMs) have shown remarkable emergent abilities in unifying almost all (if not every) NLP tasks. In the human motion-related realm however researchers still develop siloed models for each task. Inspired by InstuctGPT and the generalist concept behind Gato we introduce AvatarGPT an All-in-One framework for motion understanding planning generations as well as other tasks such as motion in-between synthesis. AvatarGPT treats each task as one type of instruction fine-tuned on the shared LLM. All the tasks are seamlessly interconnected with language as the universal interface constituting a closed-loop within the framework. To achieve this human motion sequences are first encoded as discrete tokens which serve as the extended vocabulary of LLM. Then an unsupervised pipeline to generate natural language descriptions of human action sequences from in-the-wild videos is developed. Finally all tasks are jointly trained. Extensive experiments show that AvatarGPT achieves SOTA on low-level tasks and promising results on high-level tasks demonstrating the effectiveness of our proposed All-in-One framework. Moreover for the first time AvatarGPT enables a principled approach by iterative traversal of the tasks within the closed-loop for unlimited long-motion synthesis.
