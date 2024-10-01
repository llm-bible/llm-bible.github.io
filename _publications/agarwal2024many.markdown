---
layout: publication
title: 'Many-shot In-context Learning'
authors: Agarwal Rishabh, Singh Avi, Zhang Lei M., Bohnet Bernd, Rosias Luis, Chan Stephanie, Zhang Biao, Anand Ankesh, Abbas Zaheer, Nova Azade, Co-reyes John D., Chu Eric, Behbahani Feryal, Faust Aleksandra, Larochelle Hugo
conference: "Arxiv"
year: 2024
bibkey: agarwal2024many
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.11018"}
tags: ['Ethics And Bias', 'Few Shot', 'Fine Tuning', 'In Context Learning', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) excel at few-shot in-context learning (ICL) -- learning from a few examples provided in context at inference, without any weight updates. Newly expanded context windows allow us to investigate ICL with hundreds or thousands of examples -- the many-shot regime. Going from few-shot to many-shot, we observe significant performance gains across a wide variety of generative and discriminative tasks. While promising, many-shot ICL can be bottlenecked by the available amount of human-generated examples. To mitigate this limitation, we explore two new settings: Reinforced and Unsupervised ICL. Reinforced ICL uses model-generated chain-of-thought rationales in place of human examples. Unsupervised ICL removes rationales from the prompt altogether, and prompts the model only with domain-specific questions. We find that both Reinforced and Unsupervised ICL can be quite effective in the many-shot regime, particularly on complex reasoning tasks. Finally, we demonstrate that, unlike few-shot learning, many-shot learning is effective at overriding pretraining biases, can learn high-dimensional functions with numerical inputs, and performs comparably to fine-tuning. Our analysis also reveals the limitations of next-token prediction loss as an indicator of downstream ICL performance.
