---
layout: publication
title: 'Unraveling Downstream Gender Bias From Large Language Models: A Study On AI Educational Writing Assistance'
authors: Thiemo Wambsganss, Xiaotian Su, Vinitra Swamy, Seyed Parsa Neshaei, Roman Rietsche, Tanja Käser
conference: "Arxiv"
year: 2023
bibkey: wambsganss2023unraveling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.03311"}
tags: ['Ethics and Bias', 'Model Architecture', 'GPT', 'Reinforcement Learning']
---
Large Language Models (LLMs) are increasingly utilized in educational tasks
such as providing writing suggestions to students. Despite their potential,
LLMs are known to harbor inherent biases which may negatively impact learners.
Previous studies have investigated bias in models and data representations
separately, neglecting the potential impact of LLM bias on human writing. In
this paper, we investigate how bias transfers through an AI writing support
pipeline. We conduct a large-scale user study with 231 students writing
business case peer reviews in German. Students are divided into five groups
with different levels of writing support: one classroom group with
feature-based suggestions and four groups recruited from Prolific -- a control
group with no assistance, two groups with suggestions from fine-tuned GPT-2 and
GPT-3 models, and one group with suggestions from pre-trained GPT-3.5. Using
GenBit gender bias analysis, Word Embedding Association Tests (WEAT), and
Sentence Embedding Association Test (SEAT) we evaluate the gender bias at
various stages of the pipeline: in model embeddings, in suggestions generated
by the models, and in reviews written by students. Our results demonstrate that
there is no significant difference in gender bias between the resulting peer
reviews of groups with and without LLM suggestions. Our research is therefore
optimistic about the use of AI writing support in the classroom, showcasing a
context where bias in LLMs does not transfer to students' responses.
