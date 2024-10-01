---
layout: publication
title: 'Efficient Medical Question Answering With Knowledge-augmented Question Generation'
authors: Khlaut Julien, Dancette Corentin, Ferreres Elodie, Bennani Alaedine, Hérent Paul, Manceron Pierre
conference: "Arxiv"
year: 2024
bibkey: khlaut2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.14654"}
  - {name: "Code", url: "https://github.com/raidium-med/MQG"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'Training Techniques']
---
'In the expanding field of language model applications, medical knowledge representation remains a significant challenge due to the specialized nature of the domain. Large language models, such as GPT-4, obtain reasonable scores on medical question answering tasks, but smaller models are far behind. In this work, we introduce a method to improve the proficiency of a small language model in the medical domain by employing a two-fold approach. We first fine-tune the model on a corpus of medical textbooks. Then, we use GPT-4 to generate questions similar to the downstream task, prompted with textbook knowledge, and use them to fine-tune the model. Additionally, we introduce ECN-QA, a novel medical question answering dataset containing progressive questions'''' composed of related sequential questions. We show the benefits of our training strategy on this dataset. The study''s findings highlight the potential of small language models in the medical domain when appropriately fine-tuned. The code and weights are available at https://github.com/raidium-med/MQG.'
