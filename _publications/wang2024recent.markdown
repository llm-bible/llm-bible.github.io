---
layout: publication
title: 'A Recent Evaluation On The Performance Of Llms On Radiation Oncology Physics Using Questions Of Randomly Shuffled Options'
authors: Peilong Wang, Jason Holmes, Zhengliang Liu, Dequan Chen, Tianming Liu, Jiajian Shen, Wei Liu
conference: "Arxiv"
year: 2024
bibkey: wang2024recent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.10622"}
tags: ['Prompting', 'Training Techniques', 'GPT', 'Model Architecture']
---
Purpose: We present an updated study evaluating the performance of large
language models (LLMs) in answering radiation oncology physics questions,
focusing on the recently released models.
  Methods: A set of 100 multiple-choice radiation oncology physics questions,
previously created by a well-experienced physicist, was used for this study.
The answer options of the questions were randomly shuffled to create "new" exam
sets. Five LLMs -- OpenAI o1-preview, GPT-4o, LLaMA 3.1 (405B), Gemini 1.5 Pro,
and Claude 3.5 Sonnet -- with the versions released before September 30, 2024,
were queried using these new exam sets. To evaluate their deductive reasoning
ability, the correct answer options in the questions were replaced with "None
of the above." Then, the explain-first and step-by-step instruction prompts
were used to test if this strategy improved their reasoning ability. The
performance of the LLMs was compared with the answers from medical physicists.
  Results: All models demonstrated expert-level performance on these questions,
with o1-preview even surpassing medical physicists with a majority vote. When
replacing the correct answer options with 'None of the above', all models
exhibited a considerable decline in performance, suggesting room for
improvement. The explain-first and step-by-step instruction prompts helped
enhance the reasoning ability of the LLaMA 3.1 (405B), Gemini 1.5 Pro, and
Claude 3.5 Sonnet models.
  Conclusion: These recently released LLMs demonstrated expert-level
performance in answering radiation oncology physics questions, exhibiting great
potential to assist in radiation oncology physics education and training.
