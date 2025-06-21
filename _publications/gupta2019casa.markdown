---
layout: publication
title: 'CASA-NLU: Context-aware Self-attentive Natural Language Understanding For
  Task-oriented Chatbots'
authors: Arshit Gupta, Peng Zhang, Garima Lalwani, Mona Diab
conference: Arxiv
year: 2019
citations: 19
bibkey: gupta2019casa
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.08705'}]
tags: []
---
Natural Language Understanding (NLU) is a core component of dialog systems.
It typically involves two tasks - intent classification (IC) and slot labeling
(SL), which are then followed by a dialogue management (DM) component. Such NLU
systems cater to utterances in isolation, thus pushing the problem of context
management to DM. However, contextual information is critical to the correct
prediction of intents and slots in a conversation. Prior work on contextual NLU
has been limited in terms of the types of contextual signals used and the
understanding of their impact on the model. In this work, we propose a
context-aware self-attentive NLU (CASA-NLU) model that uses multiple signals,
such as previous intents, slots, dialog acts and utterances over a variable
context window, in addition to the current user utterance. CASA-NLU outperforms
a recurrent contextual NLU baseline on two conversational datasets, yielding a
gain of up to 7% on the IC task for one of the datasets. Moreover, a
non-contextual variant of CASA-NLU achieves state-of-the-art performance for IC
task on standard public datasets - Snips and ATIS.