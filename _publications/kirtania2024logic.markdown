---
layout: publication
title: 'LOGIC-LM++: Multi-step Refinement For Symbolic Formulations'
authors: Shashank Kirtania, Priyanshu Gupta, Arjun Radhakirshna
conference: "Arxiv"
year: 2024
bibkey: kirtania2024logic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.02514'}
tags: ['RAG', 'Prompting']
---
In this paper we examine the limitations of Large Language Models (LLMs) for
complex reasoning tasks. Although recent works have started to employ formal
languages as an intermediate representation for reasoning tasks, they often
face challenges in accurately generating and refining these formal
specifications to ensure correctness. To address these issues, this paper
proposes Logic-LM++, an improvement on Logic-LM . It uses the ability of LLMs
to do pairwise comparisons, allowing the evaluation of the refinements
suggested by the LLM. The paper demonstrates that Logic-LM++ outperforms
Logic-LM and other contemporary techniques across natural language reasoning
tasks on three datasets, FOLIO, ProofWriter and AR-LSAT, with an average
improvement of 18.5% on standard prompting, 12.3% on chain of thought prompting
and 5% on Logic-LM.
