---
layout: publication
title: OVM Outcome45;supervised Value Models For Planning In Mathematical Reasoning
authors: Yu Fei, Gao Anningzhe, Wang Benyou
conference: "Arxiv"
year: 2023
bibkey: yu2023outcome
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09724"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) often struggle with maintaining accuracy throughout multiple multiple reasoning steps especially in mathematical reasoning where an error in earlier steps can propagate to subsequent ones and it ultimately leading to an incorrect answer. To reduce error propagation guided decoding is employed to direct the LM decoding on a step45;by45;step basis. We argue that in guided decoding assessing the potential of an incomplete reasoning path can be more advantageous than simply ensuring per45;step correctness as the former approach leads towards a correct final answer. This transforms the task into a textit123;value estimation125; problem in planning. Inspired by the findings that textit123;outcome supervision for guided decoding essentially acts as a value model125; we propose Outcome45;supervised Value Model (OVM) that employs outcome supervision for training a value model which prioritizes steps that lead to accurate conclusions. Furthermore the OVM eliminates the need for labor45;intensive annotations of step45;level correctness thereby significantly enhancing its scalability. Our experiments on two multi45;step mathematical reasoning datasets GSM8K and Game of 24 demonstrate the superior performance of the OVM model. Notably in GSM8K our textbf123;OVM45;7B model achieves state45;of45;the45;art results among LLMs up to 13B parameters125;; especially it does not utilize GPT45;4 or code execution. These findings offer a novel perspective on the role of outcome supervision in training value models for multi45;step reasoning tasks and provide theoretical justification for its advantage in value estimation for guided decoding.
