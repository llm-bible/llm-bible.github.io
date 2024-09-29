---
layout: publication
title: Gentus Simulating User Behaviour And Language In Task-oriented Dialogues With Generative Transformers
authors: Lin Hsien-chin, Geishauser Christian, Feng Shutong, Lubis Nurul, Van Niekerk Carel, Heck Michael, Gašić Milica
conference: "Arxiv"
year: 2022
bibkey: lin2022gentus
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2208.10817"}
tags: ['Agentic', 'Applications', 'Efficiency And Optimization', 'Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
User simulators (USs) are commonly used to train task-oriented dialogue systems (DSs) via reinforcement learning. The interactions often take place on semantic level for efficiency but there is still a gap from semantic actions to natural language which causes a mismatch between training and deployment environment. Incorporating a natural language generation (NLG) module with USs during training can partly deal with this problem. However since the policy and NLG of USs are optimised separately these simulated user utterances may not be natural enough in a given context. In this work we propose a generative transformer-based user simulator (GenTUS). GenTUS consists of an encoder-decoder structure which means it can optimise both the user policy and natural language generation jointly. GenTUS generates both semantic actions and natural language utterances preserving interpretability and enhancing language variation. In addition by representing the inputs and outputs as word sequences and by using a large pre-trained language model we can achieve generalisability in feature representation. We evaluate GenTUS with automatic metrics and human evaluation. Our results show that GenTUS generates more natural language and is able to transfer to an unseen ontology in a zero-shot fashion. In addition its behaviour can be further shaped with reinforcement learning opening the door to training specialised user simulators.
