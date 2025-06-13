---
layout: publication
title: 'Ai-university: An Llm-based Platform For Instructional Alignment To Scientific Classrooms'
authors: Mostafa Faghih Shojaei, Rahul Gulati, Benjamin A. Jasperson, Shangshang Wang, Simone Cimolato, Dangli Cao, Willie Neiswanger, Krishna Garikipati
conference: "Arxiv"
year: 2025
bibkey: shojaei2025ai
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.08846"}
tags: ['Fine-Tuning', 'Tools', 'Survey Paper', 'RAG', 'Training Techniques', 'Pretraining Methods']
---
We introduce AI University (AI-U), a flexible framework for AI-driven course
content delivery that adapts to instructors' teaching styles. At its core, AI-U
fine-tunes a large language model (LLM) with retrieval-augmented generation
(RAG) to generate instructor-aligned responses from lecture videos, notes, and
textbooks. Using a graduate-level finite-element-method (FEM) course as a case
study, we present a scalable pipeline to systematically construct training
data, fine-tune an open-source LLM with Low-Rank Adaptation (LoRA), and
optimize its responses through RAG-based synthesis. Our evaluation - combining
cosine similarity, LLM-based assessment, and expert review - demonstrates
strong alignment with course materials. We also have developed a prototype web
application, available at https://my-ai-university.com, that enhances
traceability by linking AI-generated responses to specific sections of the
relevant course material and time-stamped instances of the open-access video
lectures. Our expert model is found to have greater cosine similarity with a
reference on 86% of test cases. An LLM judge also found our expert model to
outperform the base Llama 3.2 model approximately four times out of five. AI-U
offers a scalable approach to AI-assisted education, paving the way for broader
adoption in higher education. Here, our framework has been presented in the
setting of a class on FEM - a subject that is central to training PhD and
Master students in engineering science. However, this setting is a particular
instance of a broader context: fine-tuning LLMs to research content in science.
