---
layout: publication
title: Many45;shot In45;context Learning
authors: Agarwal Rishabh, Singh Avi, Zhang Lei M., Bohnet Bernd, Rosias Luis, Chan Stephanie, Zhang Biao, Anand Ankesh, Abbas Zaheer, Nova Azade, Co-reyes John D., Chu Eric, Behbahani Feryal, Faust Aleksandra, Larochelle Hugo
conference: "Arxiv"
year: 2024
bibkey: agarwal2024many
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.11018"}
tags: ['Ethics And Bias', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) excel at few45;shot in45;context learning (ICL) 45;45; learning from a few examples provided in context at inference without any weight updates. Newly expanded context windows allow us to investigate ICL with hundreds or thousands of examples 45;45; the many45;shot regime. Going from few45;shot to many45;shot we observe significant performance gains across a wide variety of generative and discriminative tasks. While promising many45;shot ICL can be bottlenecked by the available amount of human45;generated examples. To mitigate this limitation we explore two new settings Reinforced and Unsupervised ICL. Reinforced ICL uses model45;generated chain45;of45;thought rationales in place of human examples. Unsupervised ICL removes rationales from the prompt altogether and prompts the model only with domain45;specific questions. We find that both Reinforced and Unsupervised ICL can be quite effective in the many45;shot regime particularly on complex reasoning tasks. Finally we demonstrate that unlike few45;shot learning many45;shot learning is effective at overriding pretraining biases can learn high45;dimensional functions with numerical inputs and performs comparably to fine45;tuning. Our analysis also reveals the limitations of next45;token prediction loss as an indicator of downstream ICL performance.
