---
layout: publication
title: 'Scalable Qualitative Coding With Llms: Chain-of-thought Reasoning Matches Human Performance In Some Hermeneutic Tasks'
authors: Zackary Okun Dunivin
conference: "Arxiv"
year: 2024
bibkey: dunivin2024scalable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.15170"}
tags: ['Prompting', 'RAG', 'Model Architecture', 'GPT']
---
Qualitative coding, or content analysis, extracts meaning from text to
discern quantitative patterns across a corpus of texts. Recently, advances in
the interpretive abilities of large language models (LLMs) offer potential for
automating the coding process (applying category labels to texts), thereby
enabling human researchers to concentrate on more creative research aspects,
while delegating these interpretive tasks to AI. Our case study comprises a set
of socio-historical codes on dense, paragraph-long passages representative of a
humanistic study. We show that GPT-4 is capable of human-equivalent
interpretations, whereas GPT-3.5 is not. Compared to our human-derived gold
standard, GPT-4 delivers excellent intercoder reliability (Cohen's \\(\kappa \geq
0.79\\)) for 3 of 9 codes, and substantial reliability (\\(\kappa \geq 0.6\\)) for 8
of 9 codes. In contrast, GPT-3.5 greatly underperforms for all codes
(\\(mean(\kappa) = 0.34\\); \\(max(\kappa) = 0.55\\)). Importantly, we find that coding
fidelity improves considerably when the LLM is prompted to give rationale
justifying its coding decisions (chain-of-thought reasoning). We present these
and other findings along with a set of best practices for adapting traditional
codebooks for LLMs. Our results indicate that for certain codebooks,
state-of-the-art LLMs are already adept at large-scale content analysis.
Furthermore, they suggest the next generation of models will likely render AI
coding a viable option for a majority of codebooks.
