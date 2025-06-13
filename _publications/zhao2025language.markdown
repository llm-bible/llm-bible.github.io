---
layout: publication
title: 'Language Models Are Few-shot Graders'
authors: Chenyan Zhao, Mariana Silva, Seth Poulsen
conference: "Arxiv"
year: 2025
bibkey: zhao2025language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.13337"}
tags: ['Model Architecture', 'Few-Shot', 'RAG', 'GPT', 'Prompting']
---
Providing evaluations to student work is a critical component of effective
student learning, and automating its process can significantly reduce the
workload on human graders. Automatic Short Answer Grading (ASAG) systems,
enabled by advancements in Large Language Models (LLMs), offer a promising
solution for assessing and providing instant feedback for open-ended student
responses. In this paper, we present an ASAG pipeline leveraging
state-of-the-art LLMs. Our new LLM-based ASAG pipeline achieves better
performances than existing custom-built models on the same datasets. We also
compare the grading performance of three OpenAI models: GPT-4, GPT-4o, and
o1-preview. Our results demonstrate that GPT-4o achieves the best balance
between accuracy and cost-effectiveness. On the other hand, o1-preview, despite
higher accuracy, exhibits a larger variance in error that makes it less
practical for classroom use. We investigate the effects of incorporating
instructor-graded examples into prompts using no examples, random selection,
and Retrieval-Augmented Generation (RAG)-based selection strategies. Our
findings indicate that providing graded examples enhances grading accuracy,
with RAG-based selection outperforming random selection. Additionally,
integrating grading rubrics improves accuracy by offering a structured standard
for evaluation.
