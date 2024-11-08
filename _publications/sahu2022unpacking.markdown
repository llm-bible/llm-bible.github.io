---
layout: publication
title: 'Unpacking Large Language Models With Conceptual Consistency'
authors: Sahu Pritish, Cogswell Michael, Gong Yunye, Divakaran Ajay
conference: "Arxiv"
year: 2022
bibkey: sahu2022unpacking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2209.15093"}
tags: ['Prompting']
---
If a Large Language Model (LLM) answers "yes" to the question "Are mountains
tall?" then does it know what a mountain is? Can you rely on it responding
correctly or incorrectly to other questions about mountains? The success of
Large Language Models (LLMs) indicates they are increasingly able to answer
queries like these accurately, but that ability does not necessarily imply a
general understanding of concepts relevant to the anchor query. We propose
conceptual consistency to measure a LLM's understanding of relevant concepts.
This novel metric measures how well a model can be characterized by finding out
how consistent its responses to queries about conceptually relevant background
knowledge are. To compute it we extract background knowledge by traversing
paths between concepts in a knowledge base and then try to predict the model's
response to the anchor query from the background knowledge. We investigate the
performance of current LLMs in a commonsense reasoning setting using the CSQA
dataset and the ConceptNet knowledge base. While conceptual consistency, like
other metrics, does increase with the scale of the LLM used, we find that
popular models do not necessarily have high conceptual consistency. Our
analysis also shows significant variation in conceptual consistency across
different kinds of relations, concepts, and prompts. This serves as a step
toward building models that humans can apply a theory of mind to, and thus
interact with intuitively.
