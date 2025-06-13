---
layout: publication
title: 'Linear Representations Of Political Perspective Emerge In Large Language Models'
authors: Junsol Kim, James Evans, Aaron Schein
conference: "Arxiv"
year: 2025
bibkey: kim2025linear
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.02080'}
tags: ['Attention Mechanism', 'Interpretability and Explainability', 'Transformer', 'RAG', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Large language models (LLMs) have demonstrated the ability to generate text
that realistically reflects a range of different subjective human perspectives.
This paper studies how LLMs are seemingly able to reflect more liberal versus
more conservative viewpoints among other political perspectives in American
politics. We show that LLMs possess linear representations of political
perspectives within activation space, wherein more similar perspectives are
represented closer together. To do so, we probe the attention heads across the
layers of three open transformer-based LLMs (Llama-2-7b-chat,
Mistral-7b-instruct, Vicuna-7b). We first prompt models to generate text from
the perspectives of different U.S. lawmakers. We then identify sets of
attention heads whose activations linearly predict those lawmakers' DW-NOMINATE
scores, a widely-used and validated measure of political ideology. We find that
highly predictive heads are primarily located in the middle layers, often
speculated to encode high-level concepts and tasks. Using probes only trained
to predict lawmakers' ideology, we then show that the same probes can predict
measures of news outlets' slant from the activations of models prompted to
simulate text from those news outlets. These linear probes allow us to
visualize, interpret, and monitor ideological stances implicitly adopted by an
LLM as it generates open-ended responses. Finally, we demonstrate that by
applying linear interventions to these attention heads, we can steer the model
outputs toward a more liberal or conservative stance. Overall, our research
suggests that LLMs possess a high-level linear representation of American
political ideology and that by leveraging recent advances in mechanistic
interpretability, we can identify, monitor, and steer the subjective
perspective underlying generated text.
