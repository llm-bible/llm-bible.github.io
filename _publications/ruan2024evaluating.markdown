---
layout: publication
title: 'Liveideabench: Evaluating Llms'' Divergent Thinking For Scientific Idea Generation With Minimal Context'
authors: Kai Ruan, Xuan Wang, Jixiang Hong, Peng Wang, Yang Liu, Hao Sun
conference: "Arxiv"
year: 2024
bibkey: ruan2024evaluating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.17596'}
tags: ['Training Techniques', 'Prompting', 'Reinforcement Learning', 'Tools']
---
While Large Language Models (LLMs) demonstrate remarkable capabilities in
scientific tasks such as literature analysis and experimental design (e.g.,
accurately extracting key findings from papers or generating coherent
experimental procedures), existing evaluation benchmarks primarily assess
performance using rich contextual inputs. We introduce LiveIdeaBench, a
comprehensive benchmark evaluating LLMs' scientific idea generation by
assessing divergent thinking capabilities using single-keyword prompts. Drawing
from Guilford's creativity theory, our benchmark employs a dynamic panel of
state-of-the-art LLMs to assess generated ideas across five key dimensions:
originality, feasibility, fluency, flexibility, and clarity. Through extensive
experimentation with over 40 leading models across 1,180 keywords spanning 22
scientific domains, we reveal that the scientific idea generation capabilities
measured by our benchmark, are poorly predicted by standard metrics of general
intelligence. Our results demonstrate that models like QwQ-32B-preview achieve
creative performance comparable to top-tier models such as
claude-3.7-sonnet:thinking, despite significant gaps in their general
intelligence scores. These findings highlight the need for specialized
evaluation benchmarks for scientific idea generation and suggest that enhancing
these idea generation capabilities in LLMs may require different training
strategies than those used for improving general problem-solving abilities,
potentially enabling a wider range of AI tools tailored for different stages of
the scientific process.
