---
layout: publication
title: 'Saying No Is An Art: Contextualized Fallback Responses For Unanswerable Dialogue Queries'
authors: Ashish Shrivastava, Kaustubh Dhole, Abhinav Bhatt, Sharvani Raghunath
conference: "Arxiv"
year: 2020
bibkey: shrivastava2020saying
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2012.01873'}
tags: ['Transformer', 'Applications', 'Model Architecture', 'Pretraining Methods']
---
Despite end-to-end neural systems making significant progress in the last
decade for task-oriented as well as chit-chat based dialogue systems, most
dialogue systems rely on hybrid approaches which use a combination of
rule-based, retrieval and generative approaches for generating a set of ranked
responses. Such dialogue systems need to rely on a fallback mechanism to
respond to out-of-domain or novel user queries which are not answerable within
the scope of the dialog system. While, dialog systems today rely on static and
unnatural responses like "I don't know the answer to that question" or "I'm not
sure about that", we design a neural approach which generates responses which
are contextually aware with the user query as well as say no to the user. Such
customized responses provide paraphrasing ability and contextualization as well
as improve the interaction with the user and reduce dialogue monotonicity. Our
simple approach makes use of rules over dependency parses and a text-to-text
transformer fine-tuned on synthetic data of question-response pairs generating
highly relevant, grammatical as well as diverse questions. We perform automatic
and manual evaluations to demonstrate the efficacy of the system.
