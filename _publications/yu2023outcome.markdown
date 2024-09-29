---
layout: publication
title: OVM Outcome-supervised Value Models For Planning In Mathematical Reasoning
authors: Yu Fei, Gao Anningzhe, Wang Benyou
conference: "Arxiv"
year: 2023
bibkey: yu2023outcome
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09724"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) often struggle with maintaining accuracy throughout multiple multiple reasoning steps especially in mathematical reasoning where an error in earlier steps can propagate to subsequent ones and it ultimately leading to an incorrect answer. To reduce error propagation guided decoding is employed to direct the LM decoding on a step-by-step basis. We argue that in guided decoding assessing the potential of an incomplete reasoning path can be more advantageous than simply ensuring per-step correctness as the former approach leads towards a correct final answer. This transforms the task into a (textit)value estimation problem in planning. Inspired by the findings that (textit)outcome supervision for guided decoding essentially acts as a value model we propose Outcome-supervised Value Model (OVM) that employs outcome supervision for training a value model which prioritizes steps that lead to accurate conclusions. Furthermore the OVM eliminates the need for labor-intensive annotations of step-level correctness thereby significantly enhancing its scalability. Our experiments on two multi-step mathematical reasoning datasets GSM8K and Game of 24 demonstrate the superior performance of the OVM model. Notably in GSM8K our (textbf)OVM-7B model achieves state-of-the-art results among LLMs up to 13B parameters; especially it does not utilize GPT-4 or code execution. These findings offer a novel perspective on the role of outcome supervision in training value models for multi-step reasoning tasks and provide theoretical justification for its advantage in value estimation for guided decoding.
