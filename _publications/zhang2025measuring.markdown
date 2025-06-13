---
layout: publication
title: 'Measuring Faithfulness And Abstention: An Automated Pipeline For Evaluating Llm-generated 3-ply Case-based Legal Arguments'
authors: Li Zhang, Morgan Gray, Jaromir Savelka, Kevin D. Ashley
conference: "Arxiv"
year: 2025
bibkey: zhang2025measuring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.00694"}
tags: ['Uncategorized']
---
Large Language Models (LLMs) demonstrate potential in complex legal tasks like argument generation, yet their reliability remains a concern. Building upon pilot work assessing LLM generation of 3-ply legal arguments using human evaluation, this paper introduces an automated pipeline to evaluate LLM performance on this task, specifically focusing on faithfulness (absence of hallucination), factor utilization, and appropriate abstention. We define hallucination as the generation of factors not present in the input case materials and abstention as the model's ability to refrain from generating arguments when instructed and no factual basis exists. Our automated method employs an external LLM to extract factors from generated arguments and compares them against the ground-truth factors provided in the input case triples (current case and two precedent cases). We evaluated eight distinct LLMs on three tests of increasing difficulty: 1) generating a standard 3-ply argument, 2) generating an argument with swapped precedent roles, and 3) recognizing the impossibility of argument generation due to lack of shared factors and abstaining. Our findings indicate that while current LLMs achieve high accuracy (over 90%) in avoiding hallucination on viable argument generation tests (Tests 1 & 2), they often fail to utilize the full set of relevant factors present in the cases. Critically, on the abstention test (Test 3), most models failed to follow instructions to stop, instead generating spurious arguments despite the lack of common factors. This automated pipeline provides a scalable method for assessing these crucial LLM behaviors, highlighting the need for improvements in factor utilization and robust abstention capabilities before reliable deployment in legal settings. Link: https://lizhang-aiandlaw.github.io/An-Automated-Pipeline-for-Evaluating-LLM-Generated-3-ply-Case-Based-Legal-Arguments/
