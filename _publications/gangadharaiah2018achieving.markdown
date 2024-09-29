---
layout: publication
title: Achieving Fluency And Coherency In Task45;oriented Dialog
authors: Gangadharaiah Rashmi, Narayanaswamy Balakrishnan, Elkan Charles
conference: "Arxiv"
year: 2018
bibkey: gangadharaiah2018achieving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1804.03799"}
tags: ['Agentic', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
We consider real world task45;oriented dialog settings where agents need to generate both fluent natural language responses and correct external actions like database queries and updates. We demonstrate that when applied to customer support chat transcripts Sequence to Sequence (Seq2Seq) models often generate short incoherent and ungrammatical natural language responses that are dominated by words that occur with high frequency in the training data. These phenomena do not arise in synthetic datasets such as bAbI where we show Seq2Seq models are nearly perfect. We develop techniques to learn embeddings that succinctly capture relevant information from the dialog history and demonstrate that nearest neighbor based approaches in this learned neural embedding space generate more fluent responses. However we see that these methods are not able to accurately predict when to execute an external action. We show how to combine nearest neighbor and Seq2Seq methods in a hybrid model where nearest neighbor is used to generate fluent responses and Seq2Seq type models ensure dialog coherency and generate accurate external actions. We show that this approach is well suited for customer support scenarios where agents responses are typically script45;driven and correct external actions are critically important. The hybrid model on the customer support data achieves a 7837; relative improvement in fluency scores and a 13037; improvement in accuracy of external calls.
