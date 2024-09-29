---
layout: publication
title: Tree Of Thoughts Deliberate Problem Solving With Large Language Models
authors: Shunyu Yao, Dian Yu, Jeffrey Zhao, Izhak Shafran, Thomas L. Griffiths, Yuan Cao, Karthik Narasimhan
conference: "Arxiv"
year: 2023
bibkey: yao2023tree
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2305.10601v2"}
  - {name: "Code", url: "https://github.com/princeton&#45;nlp/tree&#45;of&#45;thought&#45;llm"}
tags: ['Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'Tools']
---
Language models are increasingly being deployed for general problem solving across a wide range of tasks but are still confined to token45;level left45;to45;right decision45;making processes during inference. This means they can fall short in tasks that require exploration strategic lookahead or where initial decisions play a pivotal role. To surmount these challenges we introduce a new framework for language model inference Tree of Thoughts (ToT) which generalizes over the popular Chain of Thought approach to prompting language models and enables exploration over coherent units of text (thoughts) that serve as intermediate steps toward problem solving. ToT allows LMs to perform deliberate decision making by considering multiple different reasoning paths and self45;evaluating choices to decide the next course of action as well as looking ahead or backtracking when necessary to make global choices. Our experiments show that ToT significantly enhances language models problem45;solving abilities on three novel tasks requiring non45;trivial planning or search Game of 24 Creative Writing and Mini Crosswords. For instance in Game of 24 while GPT45;4 with chain45;of45;thought prompting only solved 437; of tasks our method achieved a success rate of 7437;. Code repo with all prompts https://github.com/princeton&#45;nlp/tree&#45;of&#45;thought&#45;llm.
