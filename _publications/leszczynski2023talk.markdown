---
layout: publication
title: Talk The Walk\: Synthetic Data Generation For Conversational Music Recommendation
authors: Leszczynski Megan, Zhang Shu, Ganti Ravi, Balog Krisztian, Radlinski Filip, Pereira Fernando, Chaganty Arun Tejasvi
conference: "Arxiv"
year: 2023
bibkey: leszczynski2023talk
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2301.11489"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Recommender systems are ubiquitous yet often difficult for users to control and adjust if recommendation quality is poor. This has motivated conversational recommender systems (CRSs) with control provided through natural language feedback. However as with most application domains building robust CRSs requires training data that reflects system usage(unicodex2014)here conversations with user utterances paired with items that cover a wide range of preferences. This has proved challenging to collect scalably using conventional methods. We address the question of whether it can be generated synthetically building on recent advances in natural language. We evaluate in the setting of item set recommendation noting the increasing attention to this task motivated by use cases like music news and recipe recommendation. We present TalkTheWalk which synthesizes realistic high-quality conversational data by leveraging domain expertise encoded in widely available curated item collections generating a sequence of hypothetical yet plausible item sets then using a language model to produce corresponding user utterances. We generate over one million diverse playlist curation conversations in the music domain and show these contain consistent utterances with relevant item sets nearly matching the quality of an existing but small human-collected dataset for this task. We demonstrate the utility of the generated synthetic dataset on a conversational item retrieval task and show that it improves over both unsupervised baselines and systems trained on a real dataset.
