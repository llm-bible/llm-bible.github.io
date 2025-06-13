---
layout: publication
title: 'It Is Too Many Options: Pitfalls Of Multiple-choice Questions In Generative AI And Medical Education'
authors: Shrutika Singh, Anton Alyakin, Daniel Alexander Alber, Jaden Stryker, Ai Phuong S Tong, Karl Sangwon, Nicolas Goff, Mathew De La Paz, Miguel Hernandez-rovira, Ki Yun Park, Eric Claude Leuthardt, Eric Karl Oermann
conference: "Arxiv"
year: 2025
bibkey: singh2025it
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.13508"}
tags: ['RAG', 'Model Architecture', 'GPT']
---
The performance of Large Language Models (LLMs) on multiple-choice question
(MCQ) benchmarks is frequently cited as proof of their medical capabilities. We
hypothesized that LLM performance on medical MCQs may in part be illusory and
driven by factors beyond medical content knowledge and reasoning capabilities.
To assess this, we created a novel benchmark of free-response questions with
paired MCQs (FreeMedQA). Using this benchmark, we evaluated three
state-of-the-art LLMs (GPT-4o, GPT-3.5, and LLama-3-70B-instruct) and found an
average absolute deterioration of 39.43% in performance on free-response
questions relative to multiple-choice (p = 1.3 * 10-5) which was greater than
the human performance decline of 22.29%. To isolate the role of the MCQ format
on performance, we performed a masking study, iteratively masking out parts of
the question stem. At 100% masking, the average LLM multiple-choice performance
was 6.70% greater than random chance (p = 0.002) with one LLM (GPT-4o)
obtaining an accuracy of 37.34%. Notably, for all LLMs the free-response
performance was near zero. Our results highlight the shortcomings in medical
MCQ benchmarks for overestimating the capabilities of LLMs in medicine, and,
broadly, the potential for improving both human and machine assessments using
LLM-evaluated free-response questions.
