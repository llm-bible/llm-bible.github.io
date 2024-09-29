---
layout: publication
title: CoRE-CoG Conversational Recommendation of Entities using Constrained Generation
authors: Srivastava Harshvardhan, Pruthi Kanav, Chakrabarti Soumen, Mausam
conference: "Arxiv"
year: 2023
bibkey: srivastava2023core
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.08511"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Pruning', 'RAG', 'Reinforcement Learning']
---
End-to-end conversational recommendation systems (CRS) generate responses by leveraging both dialog history and a knowledge base (KB). A CRS mainly faces three key challenges (1) at each turn it must decide if recommending a KB entity is appropriate; if so it must identify the most relevant KB entity to recommend; and finally it must recommend the entity in a fluent utterance that is consistent with the conversation history. Recent CRSs do not pay sufficient attention to these desiderata often generating unfluent responses or not recommending (relevant) entities at the right turn. We introduce a new CRS we call CoRE-CoG. CoRE-CoG addresses the limitations in prior systems by implementing (1) a recommendation trigger that decides if the system utterance should include an entity (2) a type pruning module that improves the relevance of recommended entities and (3) a novel constrained response generator to make recommendations while maintaining fluency. Together these modules ensure simultaneous accurate recommendation decisions and fluent system utterances. Experiments with recent benchmarks show the superiority particularly on conditional generation sub-tasks with close to 10 F1 and 4 Recall@1 percent points gain over baselines.
