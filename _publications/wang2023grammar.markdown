---
layout: publication
title: Grammar Prompting for Domain-Specific Language Generation with Large Language Models
authors: Wang Bailin, Wang Zi, Wang Xuezhi, Cao Yuan, Saurous Rif A., Kim Yoon
conference: "Arxiv"
year: 2023
bibkey: wang2023grammar
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.19234"}
tags: ['In Context Learning', 'Prompting']
---
Large language models (LLMs) can learn to perform a wide range of natural language tasks from just a handful of in-context examples. However for generating strings from highly structured languages (e.g. semantic parsing to complex domain-specific languages) it is challenging for the LLM to generalize from just a few exemplars. We propose a simple approach to enable LLMs to use external knowledge and domain-specific constraints expressed through a grammar in Backus--Naur Form (BNF) during in-context learning. Grammar prompting augments each demonstration example with a specialized grammar that is minimally sufficient for generating the particular output example where the specialized grammar is a subset of the full DSL grammar. For inference the LLM first predicts a BNF grammar given a test input and then generates the output according to the rules of the grammar. Experiments demonstrate that grammar prompting can enable LLMs to perform competitively on a diverse set of DSL generation tasks including semantic parsing (SMCalFlow Overnight GeoQuery) PDDL planning and SMILES-based molecule generation.
