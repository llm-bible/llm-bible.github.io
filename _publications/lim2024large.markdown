---
layout: publication
title: 'Large Language Models As In-context AI Generators For Quality-diversity'
authors: Bryan Lim, Manon Flageat, Antoine Cully
conference: "Arxiv"
year: 2024
bibkey: lim2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.15794"}
tags: ['Tools', 'Efficiency and Optimization', 'Applications', 'RAG', 'Few-Shot', 'Prompting']
---
Quality-Diversity (QD) approaches are a promising direction to develop
open-ended processes as they can discover archives of high-quality solutions
across diverse niches. While already successful in many applications, QD
approaches usually rely on combining only one or two solutions to generate new
candidate solutions. As observed in open-ended processes such as technological
evolution, wisely combining large diversity of these solutions could lead to
more innovative solutions and potentially boost the productivity of QD search.
In this work, we propose to exploit the pattern-matching capabilities of
generative models to enable such efficient solution combinations. We introduce
In-context QD, a framework of techniques that aim to elicit the in-context
capabilities of pre-trained Large Language Models (LLMs) to generate
interesting solutions using few-shot and many-shot prompting with
quality-diverse examples from the QD archive as context. Applied to a series of
common QD domains, In-context QD displays promising results compared to both QD
baselines and similar strategies developed for single-objective optimization.
Additionally, this result holds across multiple values of parameter sizes and
archive population sizes, as well as across domains with distinct
characteristics from BBO functions to policy search. Finally, we perform an
extensive ablation that highlights the key prompt design considerations that
encourage the generation of promising solutions for QD.
