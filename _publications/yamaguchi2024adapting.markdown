---
layout: publication
title: 'Elchat: Adapting Chat Language Models Using Only Target Unlabeled Language Data'
authors: Atsuki Yamaguchi, Terufumi Morishita, Aline Villavicencio, Nikolaos Aletras
conference: "Arxiv"
year: 2024
bibkey: yamaguchi2024adapting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.11704"}
tags: ['Responsible AI', 'Training Techniques', 'Pre-Training']
---
Vocabulary expansion (VE) is the de-facto approach to language adaptation of
large language models (LLMs) by adding new tokens and continuing pre-training
on target data. While this is effective for base models trained on unlabeled
data, it poses challenges for chat models trained to follow instructions
through labeled conversation data. Directly adapting the latter with VE on
target unlabeled data may result in forgetting chat abilities. While ideal,
target chat data is often unavailable or costly to create for low-resource
languages, and machine-translated alternatives are not always effective. To
address this issue, previous work proposed using a base and chat model from the
same family. This method first adapts the base LLM with VE on target unlabeled
data and then converts it to a chat model by adding a chat vector (CV) derived
from the weight difference between the source base and chat models. We propose
ElChat, a new language adaptation method for chat LLMs that adapts a chat model
directly on target unlabeled data, without a base model. It elicits chat
abilities by injecting information from the source chat model. ElChat offers
more robust and competitive target language and safety performance while
achieving superior English, chat, and instruction-following abilities compared
to CV.
