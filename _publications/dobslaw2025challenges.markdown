---
layout: publication
title: 'Challenges In Testing Large Language Model Based Software: A Faceted Taxonomy'
authors: Felix Dobslaw, Robert Feldt, Juyeon Yoon, Shin Yoo
conference: "Arxiv"
year: 2025
bibkey: dobslaw2025challenges
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.00481"}
tags: ['ACL', 'Agentic', 'Tools']
---
Large Language Models (LLMs) and Multi-Agent LLMs (MALLMs) introduce
non-determinism unlike traditional or machine learning software, requiring new
approaches to verifying correctness beyond simple output comparisons or
statistical accuracy over test datasets.
  This paper presents a taxonomy for LLM test case design, informed by both the
research literature, our experience, and open-source tools that represent the
state of practice. We identify key variation points that impact test
correctness and highlight open challenges that the research, industry, and
open-source communities must address as LLMs become integral to software
systems.
  Our taxonomy defines four facets of LLM test case design, addressing
ambiguity in both inputs and outputs while establishing best practices. It
distinguishes variability in goals, the system under test, and inputs, and
introduces two key oracle types: atomic and aggregated. Our mapping indicates
that current tools insufficiently account for these variability points,
highlighting the need for closer collaboration between academia and
practitioners to improve the reliability and reproducibility of LLM testing.
