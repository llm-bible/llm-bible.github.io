---
layout: publication
title: 'Evaluating Multilingual Long-context Models For Retrieval And Reasoning'
authors: Ameeta Agrawal, Andy Dang, Sina Bagheri Nezhad, Rhitabrat Pokharel, Russell Scheinberg
conference: "Arxiv"
year: 2024
bibkey: agrawal2024evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.18006"}
tags: ['Model Architecture', 'GPT']
---
Recent large language models (LLMs) demonstrate impressive capabilities in
handling long contexts, some exhibiting near-perfect recall on synthetic
retrieval tasks. However, these evaluations have mainly focused on English text
and involved a single target sentence within lengthy contexts. Our work
investigates how LLM performance generalizes to multilingual settings with
multiple hidden target sentences. We create a new dataset -- mLongRR -- to
comprehensively evaluate several multilingual long-context LLMs on retrieval
and reasoning tasks across five languages: English, Vietnamese, Indonesian,
Swahili, and Somali. These languages share the Latin script but belong to
distinct language families and resource levels. Our analysis reveals a
significant performance gap between languages. The best-performing models such
as Gemini-1.5 and GPT-4o, achieve around 96% accuracy in English to around 36%
in Somali with a single target sentence. However, this accuracy drops to 40% in
English and 0% in Somali when dealing with three target sentences. Our findings
highlight the challenges long-context LLMs face when processing longer
contexts, an increase in the number of target sentences, or languages of lower
resource levels.
