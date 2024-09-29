---
layout: publication
title: Parrot Multilingual Visual Instruction Tuning
authors: Sun Hai-long, Zhou Da-wei, Li Yang, Lu Shiyin, Yi Chao, Chen Qing-guo, Xu Zhao, Luo Weihua, Zhang Kaifu, Zhan De-chuan, Ye Han-jia
conference: "Arxiv"
year: 2024
bibkey: sun2024parrot
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.02539"}
  - {name: "Code", url: "https://github.com/AIDC-AI/Parrot"}
tags: ['Attention Mechanism', 'Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
The rapid development of Multimodal Large Language Models (MLLMs) like GPT-4V has marked a significant step towards artificial general intelligence. Existing methods mainly focus on aligning vision encoders with LLMs through supervised fine-tuning (SFT) to endow LLMs with multimodal abilities making MLLMs inherent ability to react to multiple languages progressively deteriorate as the training process evolves. We empirically find that the imbalanced SFT datasets primarily composed of English-centric image-text pairs lead to significantly reduced performance in non-English languages. This is due to the failure of aligning the vision encoder and LLM with multilingual tokens during the SFT process. In this paper we introduce Parrot a novel method that utilizes textual guidance to drive visual token alignment at the language level. Parrot makes the visual tokens condition on diverse language inputs and uses Mixture-of-Experts (MoE) to promote the alignment of multilingual tokens. Specifically to enhance non-English visual tokens alignment we compute the cross-attention using the initial visual features and textual embeddings the result of which is then fed into the MoE router to select the most relevant experts. The selected experts subsequently convert the initial visual tokens into language-specific visual tokens. Moreover considering the current lack of benchmarks for evaluating multilingual capabilities within the field we collect and make available a Massive Multilingual Multimodal Benchmark which includes 6 languages 15 categories and 12000 questions named as MMMB. Our method not only demonstrates state-of-the-art performance on multilingual MMBench and MMMB but also excels across a broad range of multimodal tasks. Both the source code and the training dataset of Parrot will be made publicly available. Code is available at https://github.com/AIDC-AI/Parrot.
