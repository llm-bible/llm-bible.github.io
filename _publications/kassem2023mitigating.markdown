---
layout: publication
title: 'Mitigating Approximate Memorization In Language Models Via Dissimilarity Learned Policy'
authors: Aly M. Kassem
conference: "Arxiv"
year: 2023
bibkey: kassem2023mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.01550"}
tags: ['Agentic', 'Tools', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'BERT', 'Prompting']
---
Large Language models (LLMs) are trained on large amounts of data, which can
include sensitive information that may compromise personal privacy. LLMs showed
to memorize parts of the training data and emit those data verbatim when an
adversary prompts appropriately. Previous research has primarily focused on
data preprocessing and differential privacy techniques to address memorization
or prevent verbatim memorization exclusively, which can give a false sense of
privacy. However, these methods rely on explicit and implicit assumptions about
the structure of the data to be protected, which often results in an incomplete
solution to the problem. To address this, we propose a novel framework that
utilizes a reinforcement learning approach (PPO) to fine-tune LLMs to mitigate
approximate memorization. Our approach utilizes a negative similarity score,
such as BERTScore or SacreBLEU, as a reward signal to learn a dissimilarity
policy. Our results demonstrate that this framework effectively mitigates
approximate memorization while maintaining high levels of coherence and fluency
in the generated samples. Furthermore, our framework is robust in mitigating
approximate memorization across various circumstances, including longer
context, which is known to increase memorization in LLMs.
