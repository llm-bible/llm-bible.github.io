---
layout: publication
title: Cook2ltl Translating Cooking Recipes To LTL Formulae Using Large Language Models
authors: Mavrogiannis Angelos, Mavrogiannis Christoforos, Aloimonos Yiannis
conference: "Arxiv"
year: 2023
bibkey: mavrogiannis2023cook2ltl
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.00163"}
tags: ['Pretraining Methods', 'RAG', 'Tools']
---
Cooking recipes are challenging to translate to robot plans as they feature rich linguistic complexity temporally-extended interconnected tasks and an almost infinite space of possible actions. Our key insight is that combining a source of cooking domain knowledge with a formalism that captures the temporal richness of cooking recipes could enable the extraction of unambiguous robot-executable plans. In this work we use Linear Temporal Logic (LTL) as a formal language expressive enough to model the temporal nature of cooking recipes. Leveraging a pretrained Large Language Model (LLM) we present Cook2LTL a system that translates instruction steps from an arbitrary cooking recipe found on the internet to a set of LTL formulae grounding high-level cooking actions to a set of primitive actions that are executable by a manipulator in a kitchen environment. Cook2LTL makes use of a caching scheme that dynamically builds a queryable action library at runtime. We instantiate Cook2LTL in a realistic simulation environment (AI2-THOR) and evaluate its performance across a series of cooking recipes. We demonstrate that our system significantly decreases LLM API calls (-5137;) latency (-5937;) and cost (-4237;) compared to a baseline that queries the LLM for every newly encountered action at runtime.
