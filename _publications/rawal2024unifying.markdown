---
layout: publication
title: 'Unmute: Unifying Navigation And Multimodal Dialogue-like Text Generation'
authors: Niyati Rawal, Roberto Bigazzi, Lorenzo Baraldi, Rita Cucchiara
conference: "Arxiv"
year: 2024
bibkey: rawal2024unifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.04423"}
tags: ['Agentic', 'GPT', 'Applications', 'RAG', 'Model Architecture', 'Language Modeling', 'ACL', 'Agent', 'Multimodal Models']
---
Smart autonomous agents are becoming increasingly important in various
real-life applications, including robotics and autonomous vehicles. One crucial
skill that these agents must possess is the ability to interact with their
surrounding entities, such as other agents or humans. In this work, we aim at
building an intelligent agent that can efficiently navigate in an environment
while being able to interact with an oracle (or human) in natural language and
ask for directions when it is unsure about its navigation performance. The
interaction is started by the agent that produces a question, which is then
answered by the oracle on the basis of the shortest trajectory to the goal. The
process can be performed multiple times during navigation, thus enabling the
agent to hold a dialogue with the oracle. To this end, we propose a novel
computational model, named UNMuTe, that consists of two main components: a
dialogue model and a navigator. Specifically, the dialogue model is based on a
GPT-2 decoder that handles multimodal data consisting of both text and images.
First, the dialogue model is trained to generate question-answer pairs: the
question is generated using the current image, while the answer is produced
leveraging future images on the path toward the goal. Subsequently, a VLN model
is trained to follow the dialogue predicting navigation actions or triggering
the dialogue model if it needs help. In our experimental analysis, we show that
UNMuTe achieves state-of-the-art performance on the main navigation tasks
implying dialogue, i.e. Cooperative Vision and Dialogue Navigation (CVDN) and
Navigation from Dialogue History (NDH), proving that our approach is effective
in generating useful questions and answers to guide navigation.
