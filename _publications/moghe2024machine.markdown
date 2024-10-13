---
layout: publication
title: 'Machine Translation Meta Evaluation Through Translation Accuracy Challenge Sets'
authors: Moghe Nikita, Fazla Arnisa, Amrhein Chantal, Kocmi Tom, Steedman Mark, Birch Alexandra, Sennrich Rico, Guillou Liane
conference: "Arxiv"
year: 2024
bibkey: moghe2024machine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.16313"}
tags: ['Applications', 'Reinforcement Learning']
---
Recent machine translation (MT) metrics calibrate their effectiveness by
correlating with human judgement but without any insights about their behaviour
across different error types. Challenge sets are used to probe specific
dimensions of metric behaviour but there are very few such datasets and they
either focus on a limited number of phenomena or a limited number of language
pairs. We introduce ACES, a contrastive challenge set spanning 146 language
pairs, aimed at discovering whether metrics can identify 68 translation
accuracy errors. These phenomena range from simple alterations at the
word/character level to more complex errors based on discourse and real-world
knowledge. We conduct a large-scale study by benchmarking ACES on 50 metrics
submitted to the WMT 2022 and 2023 metrics shared tasks. We benchmark metric
performance, assess their incremental performance over successive campaigns,
and measure their sensitivity to a range of linguistic phenomena. We also
investigate claims that Large Language Models (LLMs) are effective as MT
evaluators by evaluating on ACES. Our results demonstrate that different metric
families struggle with different phenomena and that LLM-based methods fail to
demonstrate reliable performance. Our analyses indicate that most metrics
ignore the source sentence, tend to prefer surface-level overlap and end up
incorporating properties of base models which are not always beneficial. We
expand ACES to include error span annotations, denoted as SPAN-ACES and we use
this dataset to evaluate span-based error metrics showing these metrics also
need considerable improvement. Finally, we provide a set of recommendations for
building better MT metrics, including focusing on error labels instead of
scores, ensembling, designing strategies to explicitly focus on the source
sentence, focusing on semantic content and choosing the right base model for
representations.
