---
layout: publication
title: 'Deconfounded Causality-aware Parameter-efficient Fine-tuning For Problem-solving Improvement Of Llms'
authors: Wang Ruoyu, Li Xiaoxuan, Yao Lina
conference: "Arxiv"
year: 2024
bibkey: wang2024deconfounded
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.02686"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Fine Tuning', 'Interpretability And Explainability', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques']
---
Large Language Models (LLMs) have demonstrated remarkable efficiency in tackling various tasks based on human instructions, but recent studies reveal that these models often fail to achieve satisfactory results on questions involving reasoning, such as mathematics or physics questions. This phenomenon is usually attributed to the uncertainty regarding whether these models could genuinely comprehend the knowledge embedded in the text or merely learn to replicate the token distribution without a true understanding of the content. In this paper, we delve into this problem and aim to enhance the reasoning capabilities of LLMs. First, we investigate if the model has genuine reasoning capabilities by visualizing the text generation process at the attention and representation level. Then, we formulate the reasoning process of LLMs into a causal framework, which provides a formal explanation of the problems we observe in the visualization. Finally, building upon this causal framework, we propose Deconfounded Causal Adaptation (DCA), a novel parameter-efficient fine-tuning (PEFT) method to enhance the model's reasoning capabilities by encouraging the model to extract the general problem-solving skills and apply these skills to different questions. Experiments show that our method outperforms the baseline consistently across multiple benchmarks, and with only 1.2M tunable parameters, we achieve better or comparable results to other fine-tuning methods. This demonstrates the effectiveness and efficiency of our method in improving the overall accuracy and reliability of LLMs.
