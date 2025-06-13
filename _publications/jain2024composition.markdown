---
layout: publication
title: 'Composition Of Experts: A Modular Compound AI System Leveraging Large Language Models'
authors: Swayambhoo Jain, Ravi Raju, Bo Li, Zoltan Csaki, Jonathan Li, Kaizhao Liang, Guoyao Feng, Urmish Thakkar, Anand Sampat, Raghu Prabhakar, Sumati Jairath
conference: "Arxiv"
year: 2024
bibkey: jain2024composition
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.01868"}
tags: ['Training Techniques', 'RAG', 'Tools', 'Model Architecture']
---
Large Language Models (LLMs) have achieved remarkable advancements, but their
monolithic nature presents challenges in terms of scalability, cost, and
customization. This paper introduces the Composition of Experts (CoE), a
modular compound AI system leveraging multiple expert LLMs. CoE leverages a
router to dynamically select the most appropriate expert for a given input,
enabling efficient utilization of resources and improved performance. We
formulate the general problem of training a CoE and discuss inherent
complexities associated with it. We propose a two-step routing approach to
address these complexities that first uses a router to classify the input into
distinct categories followed by a category-to-expert mapping to obtain desired
experts. CoE offers a flexible and cost-effective solution to build compound AI
systems. Our empirical evaluation demonstrates the effectiveness of CoE in
achieving superior performance with reduced computational overhead. Given that
CoE comprises of many expert LLMs it has unique system requirements for
cost-effective serving. We present an efficient implementation of CoE
leveraging SambaNova SN40L RDUs unique three-tiered memory architecture. CoEs
obtained using open weight LLMs Qwen/Qwen2-7B-Instruct, google/gemma-2-9b-it,
google/gemma-2-27b-it, meta-llama/Llama-3.1-70B-Instruct and
Qwen/Qwen2-72B-Instruct achieve a score of \\(59.4\\) with merely \\(31\\) billion
average active parameters on Arena-Hard and a score of \\(9.06\\) with \\(54\\) billion
average active parameters on MT-Bench.
