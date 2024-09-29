---
layout: publication
title: RSVP Customer Intent Detection Via Agent Response Contrastive And Generative Pre45;training
authors: Tang Yu-chien, Wang Wei-yao, Yen An-zi, Peng Wen-chih
conference: "Arxiv"
year: 2023
bibkey: tang2023customer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.09773"}
tags: ['Agentic', 'Applications', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
The dialogue systems in customer services have been developed with neural models to provide users with precise answers and round45;the45;clock support in task45;oriented conversations by detecting customer intents based on their utterances. Existing intent detection approaches have highly relied on adaptively pre45;training language models with large45;scale datasets yet the predominant cost of data collection may hinder their superiority. In addition they neglect the information within the conversational responses of the agents which have a lower collection cost but are significant to customer intent as agents must tailor their replies based on the customers intent. In this paper we propose RSVP a self45;supervised framework dedicated to task45;oriented dialogues which utilizes agent responses for pre45;training in a two45;stage manner. Specifically we introduce two pre45;training tasks to incorporate the relations of utterance45;response pairs 1) Response Retrieval by selecting a correct response from a batch of candidates and 2) Response Generation by mimicking agents to generate the response to a given utterance. Our benchmark results for two real45;world customer service datasets show that RSVP significantly outperforms the state45;of45;the45;art baselines by 4.9537; for accuracy 3.437; for MRR35;64;3 and 2.7537; for MRR35;64;5 on average. Extensive case studies are investigated to show the validity of incorporating agent responses into the pre45;training stage.
