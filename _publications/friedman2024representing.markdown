---
layout: publication
title: Representing Rule-based Chatbots with Transformers
authors: Friedman Dan, Panigrahi Abhishek, Chen Danqi
conference: "Arxiv"
year: 2024
bibkey: friedman2024representing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.10949"}
tags: ['ARXIV', 'Model Architecture', 'Transformer']
---
Transformer-based chatbots can conduct fluent natural-sounding conversations but we have limited understanding of the mechanisms underlying their behavior. Prior work has taken a bottom-up approach to understanding Transformers by constructing Transformers for various synthetic and formal language tasks such as regular expressions and Dyck languages. However it is not obvious how to extend this approach to understand more naturalistic conversational agents. In this work we take a step in this direction by constructing a Transformer that implements the ELIZA program a classic rule-based chatbot. ELIZA illustrates some of the distinctive challenges of the conversational setting including both local pattern matching and long-term dialog state tracking. We build on constructions from prior work -- in particular for simulating finite-state automata -- showing how simpler constructions can be composed and extended to give rise to more sophisticated behavior. Next we train Transformers on a dataset of synthetically generated ELIZA conversations and investigate the mechanisms the models learn. Our analysis illustrates the kinds of mechanisms these models tend to prefer -- for example models favor an induction head mechanism over a more precise position based copying mechanism; and using intermediate generations to simulate recurrent data structures like ELIZAs memory mechanisms. Overall by drawing an explicit connection between neural chatbots and interpretable symbolic mechanisms our results offer a new setting for mechanistic analysis of conversational agents.
