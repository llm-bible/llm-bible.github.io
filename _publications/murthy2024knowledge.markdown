---
layout: publication
title: 'KCIF: Knowledge-conditioned Instruction Following'
authors: Rudra Murthy, Praveen Venkateswaran, Prince Kumar, Danish Contractor
conference: "Arxiv"
year: 2024
bibkey: murthy2024knowledge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12972"}
tags: ['RAG', 'Tools']
---
LLM evaluation benchmarks have traditionally separated the testing of knowledge/reasoning capabilities from instruction following. In this work, we study the interaction between knowledge and instruction following, and observe that LLMs struggle to follow simple answer modifying instructions, and are also distracted by instructions that should have no bearing on the original knowledge task answer. We leverage existing multiple-choice answer based knowledge benchmarks and apply a set of simple instructions which include manipulating text (eg.: change case), numeric quantities (eg.: increase value, change formatting), operate on lists (eg.: sort answer candidates) and distractor instructions (eg.: change case of numeric answers). We evaluate models at varying parameter sizes (1B-405B) from different model families and find that, surprisingly, all models report a significant drop in performance on such simple task compositions. While large-sized and frontier models report performance drops of 40-50%, in small and medium sized models the drop is severe (sometimes exceeding 80%). Our results highlight a limitation in the traditional separation of knowledge/reasoning and instruction following, and suggest that joint-study of these capabilities are important. We release our benchmark dataset, evaluation framework code, and results for future work.
