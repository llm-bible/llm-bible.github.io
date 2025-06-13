---
layout: publication
title: 'Clean & Clear: Feasibility Of Safe LLM Clinical Guidance'
authors: Julia Ive, Felix Jozsa, Nick Jackson, Paulina Bondaronek, Ciaran Scott Hill, Richard Dobson
conference: "Arxiv"
year: 2025
bibkey: ive2025clean
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.20953'}
tags: ['RAG', 'Efficiency and Optimization', 'Responsible AI']
---
Background:
  Clinical guidelines are central to safe evidence-based medicine in modern
healthcare, providing diagnostic criteria, treatment options and monitoring
advice for a wide range of illnesses. LLM-empowered chatbots have shown great
promise in Healthcare Q&A tasks, offering the potential to provide quick and
accurate responses to medical inquiries.
  Our main objective was the development and preliminary assessment of an
LLM-empowered chatbot software capable of reliably answering clinical guideline
questions using University College London Hospital (UCLH) clinical guidelines.
  Methods: We used the open-weight Llama-3.1-8B LLM to extract relevant
information from the UCLH guidelines to answer questions. Our approach
highlights the safety and reliability of referencing information over its
interpretation and response generation. Seven doctors from the ward assessed
the chatbot's performance by comparing its answers to the gold standard.
  Results: Our chatbot demonstrates promising performance in terms of
relevance, with ~73% of its responses rated as very relevant, showcasing a
strong understanding of the clinical context. Importantly, our chatbot achieves
a recall of 1.00 for extracted guideline lines, substantially minimising the
risk of missing critical information. Approximately 78% of responses were rated
satisfactory in terms of completeness. A small portion (~14.5%) contained minor
unnecessary information, indicating occasional lapses in precision. The
chatbot' showed high efficiency, with an average completion time of 10 seconds,
compared to 30 seconds for human respondents. Evaluation of clinical reasoning
showed that 72% of the chatbot's responses were without flaws. Our chatbot
demonstrates significant potential to speed up and improve the process of
accessing locally relevant clinical information for healthcare professionals.
