---
layout: publication
title: "Do Large Language Models And Humans Have Similar Behaviors In Causal Inference With Script Knowledge?"
authors: Hong Xudong, Ryzhova Margarita, Biondi Daniel Adrian, Demberg Vera
conference: "Arxiv"
year: 2023
bibkey: hong2023do
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.07311"}
  - {name: "Code", url: "https://github.com/tony-hong/causal-script"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning']
---
Recently large pre-trained language models (LLMs) have demonstrated superior language understanding abilities including zero-shot causal reasoning. However it is unclear to what extent their capabilities are similar to human ones. We here study the processing of an event B in a script-based story which causally depends on a previous event A. In our manipulation event A is stated negated or omitted in an earlier section of the text. We first conducted a self-paced reading experiment which showed that humans exhibit significantly longer reading times when causal conflicts exist ((neg) A (rightarrow) B) than under logical conditions (A (rightarrow) B). However reading times remain similar when cause A is not explicitly mentioned indicating that humans can easily infer event B from their script knowledge. We then tested a variety of LLMs on the same data to check to what extent the models replicate human behavior. Our experiments show that 1) only recent LLMs like GPT-3 or Vicuna correlate with human behavior in the (neg) A (rightarrow) B condition. 2) Despite this correlation all models still fail to predict that nil (rightarrow) B is less surprising than (neg) A (rightarrow) B indicating that LLMs still have difficulties integrating script knowledge. Our code and collected data set are available at https://github.com/tony-hong/causal-script."
