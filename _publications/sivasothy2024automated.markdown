---
layout: publication
title: 'Ragprobe: An Automated Approach For Evaluating RAG Applications'
authors: Shangeetha Sivasothy, Scott Barnett, Stefanus Kurniawan, Zafaryab Rasool, Rajesh Vasa
conference: "Arxiv"
year: 2024
bibkey: sivasothy2024automated
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.19019"}
tags: ['RAG', 'Prompting', 'Applications', 'Reinforcement Learning']
---
Retrieval Augmented Generation (RAG) is increasingly being used when building
Generative AI applications. Evaluating these applications and RAG pipelines is
mostly done manually, via a trial and error process. Automating evaluation of
RAG pipelines requires overcoming challenges such as context misunderstanding,
wrong format, incorrect specificity, and missing content. Prior works therefore
focused on improving evaluation metrics as well as enhancing components within
the pipeline using available question and answer datasets. However, they have
not focused on 1) providing a schema for capturing different types of
question-answer pairs or 2) creating a set of templates for generating
question-answer pairs that can support automation of RAG pipeline evaluation.
In this paper, we present a technique for generating variations in
question-answer pairs to trigger failures in RAG pipelines. We validate 5
open-source RAG pipelines using 3 datasets. Our approach revealed the highest
failure rates when prompts combine multiple questions: 91% for questions when
spanning multiple documents and 78% for questions from a single document;
indicating a need for developers to prioritise handling these combined
questions. 60% failure rate was observed in academic domain dataset and 53% and
62% failure rates were observed in open-domain datasets. Our automated approach
outperforms the existing state-of-the-art methods, by increasing the failure
rate by 51% on average per dataset. Our work presents an automated approach for
continuously monitoring the health of RAG pipelines, which can be integrated
into existing CI/CD pipelines, allowing for improved quality.
