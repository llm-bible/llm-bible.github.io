---
layout: publication
title: 'Cancer-myth: Evaluating AI Chatbot On Patient Questions With False Presuppositions'
authors: Wang Bill Zhu, Tianqi Chen, Ching Ying Lin, Jade Law, Mazen Jizzini, Jorge J. Nieva, Ruishan Liu, Robin Jia
conference: "Arxiv"
year: 2025
bibkey: zhu2025cancer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.11373"}
tags: ['Agentic', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Security']
---
Cancer patients are increasingly turning to large language models (LLMs) as a
new form of internet search for medical information, making it critical to
assess how well these models handle complex, personalized questions. However,
current medical benchmarks focus on medical exams or consumer-searched
questions and do not evaluate LLMs on real patient questions with detailed
clinical contexts. In this paper, we first evaluate LLMs on cancer-related
questions drawn from real patients, reviewed by three hematology oncology
physicians. While responses are generally accurate, with GPT-4-Turbo scoring
4.13 out of 5, the models frequently fail to recognize or address false
presuppositions in the questions-posing risks to safe medical decision-making.
To study this limitation systematically, we introduce Cancer-Myth, an
expert-verified adversarial dataset of 585 cancer-related questions with false
presuppositions. On this benchmark, no frontier LLM -- including GPT-4o,
Gemini-1.Pro, and Claude-3.5-Sonnet -- corrects these false presuppositions
more than 30% of the time. Even advanced medical agentic methods do not prevent
LLMs from ignoring false presuppositions. These findings expose a critical gap
in the clinical reliability of LLMs and underscore the need for more robust
safeguards in medical AI systems.
