---
layout: publication
title: Memory-assisted prompt editing to improve GPT-3 after deployment
authors: Madaan Aman, Tandon Niket, Clark Peter, Yang Yiming
conference: "Arxiv"
year: 2022
bibkey: madaan2022memory
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2201.06009"}
  - {name: "Code", url: "https://www.memprompt.com/"}
tags: ['ARXIV', 'GPT', 'Has Code', 'Prompt', 'Tools', 'Training Techniques']
---
Large LMs such as GPT-3 are powerful but can commit mistakes that are obvious to humans. For example GPT-3 would mistakenly interpret What word is similar to good to mean a homophone while the user intended a synonym. Our goal is to effectively correct such errors via user interactions with the system but without retraining which will be prohibitively costly. We pair GPT-3 with a growing memory of recorded cases where the model misunderstood the users intents along with user feedback for clarification. Such a memory allows our system to produce enhanced prompts for any new query based on the user feedback for error correction on similar cases in the past. On four tasks (two lexical tasks two advanced ethical reasoning tasks) we show how a (simulated) user can interactively teach a deployed GPT-3 substantially increasing its accuracy over the queries with different kinds of misunderstandings by the GPT-3. Our approach is a step towards the low-cost utility enhancement for very large pre-trained LMs. Code data and instructions to implement MEMPROMPT for a new task at https://www.memprompt.com/.
