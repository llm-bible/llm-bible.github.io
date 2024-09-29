---
layout: publication
title: Cross45;task Generalization Via Natural Language Crowdsourcing Instructions
authors: Swaroop Mishra, Daniel Khashabi, Chitta Baral, Hannaneh Hajishirzi
conference: "Arxiv"
year: 2021
bibkey: mishra2021cross
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2104.08773v4"}
tags: ['Pretraining Methods', 'Training Techniques']
---
Humans (e.g. crowdworkers) have a remarkable ability in solving different tasks by simply reading textual instructions that define them and looking at a few examples. Despite the success of the conventional supervised learning on individual datasets such models often struggle with generalization across tasks (e.g. a question45;answering system cannot solve classification tasks). A long45;standing challenge in AI is to build a model that learns a new task by understanding the human45;readable instructions that define it. To study this we introduce NATURAL INSTRUCTIONS a dataset of 61 distinct tasks their human45;authored instructions and 193k task instances (input45;output pairs). The instructions are obtained from crowdsourcing instructions used to create existing NLP datasets and mapped to a unified schema. Using this meta45;dataset we measure cross45;task generalization by training models on seen tasks and measuring generalization to the remaining unseen ones. We adopt generative pre45;trained language models to encode task45;specific instructions along with input and generate task output. Our results indicate that models benefit from instructions when evaluated in terms of generalization to unseen tasks (1937; better for models utilizing instructions). These models however are far behind an estimated performance upperbound indicating significant room for more progress in this direction.
