---
layout: publication
title: 'Improved Instruction Ordering In Recipe-grounded Conversation'
authors: Le Duong Minh, Guo Ruohao, Xu Wei, Ritter Alan
conference: "Arxiv"
year: 2023
bibkey: le2023improved
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.17280"}
  - {name: "Code", url: "https://github.com/octaviaguo/ChattyChef"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Reinforcement Learning']
---
In this paper we study the task of instructional dialogue and focus on the cooking domain. Analyzing the generated output of the GPT-J model we reveal that the primary challenge for a recipe-grounded dialog system is how to provide the instructions in the correct order. We hypothesize that this is due to the models lack of understanding of user intent and inability to track the instruction state (i.e. which step was last instructed). Therefore we propose to explore two auxiliary subtasks namely User Intent Detection and Instruction State Tracking to support Response Generation with improved instruction grounding. Experimenting with our newly collected dataset ChattyChef shows that incorporating user intent and instruction state information helps the response generation model mitigate the incorrect order issue. Furthermore to investigate whether ChatGPT has completely solved this task we analyze its outputs and find that it also makes mistakes (10.737; of the responses) about half of which are out-of-order instructions. We will release ChattyChef to facilitate further research in this area at https://github.com/octaviaguo/ChattyChef."
