---
layout: publication
title: 'Long-span Question-answering: Automatic Question Generation And Qa-system Ranking Via Side-by-side Evaluation'
authors: Bohnet Bernd, Swersky Kevin, Liu Rosanne, Awasthi Pranjal, Nova Azade, Snaider Javier, Sedghi Hanie, Parisi Aaron T, Collins Michael, Lazaridou Angeliki, Firat Orhan, Fiedel Noah
conference: "Arxiv"
year: 2024
bibkey: bohnet2024long
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.00179"}
tags: ['Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
We explore the use of long-context capabilities in large language models to
create synthetic reading comprehension data from entire books. Previous efforts
to construct such datasets relied on crowd-sourcing, but the emergence of
transformers with a context size of 1 million or more tokens now enables
entirely automatic approaches. Our objective is to test the capabilities of
LLMs to analyze, understand, and reason over problems that require a detailed
comprehension of long spans of text, such as questions involving character
arcs, broader themes, or the consequences of early actions later in the story.
We propose a holistic pipeline for automatic data generation including question
generation, answering, and model scoring using an ``Evaluator''. We find that a
relative approach, comparing answers between models in a pairwise fashion and
ranking with a Bradley-Terry model, provides a more consistent and
differentiating scoring mechanism than an absolute scorer that rates answers
individually. We also show that LLMs from different model families produce
moderate agreement in their ratings. We ground our approach using the manually
curated NarrativeQA dataset, where our evaluator shows excellent agreement with
human judgement and even finds errors in the dataset. Using our automatic
evaluation approach, we show that using an entire book as context produces
superior reading comprehension performance compared to baseline no-context
(parametric knowledge only) and retrieval-based approaches.
