---
layout: publication
title: 'Text2bim: Generating Building Models Using A Large Language Model-based Multi-agent Framework'
authors: Changyu Du, Sebastian Esser, Stavros Nousias, André Borrmann
conference: "Arxiv"
year: 2024
bibkey: du2024generating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.08054'}
tags: ['Agentic', 'Tools', 'Model Architecture']
---
The conventional BIM authoring process typically requires designers to master
complex and tedious modeling commands in order to materialize their design
intentions within BIM authoring tools. This additional cognitive burden
complicates the design process and hinders the adoption of BIM and model-based
design in the AEC (Architecture, Engineering, and Construction) industry. To
facilitate the expression of design intentions more intuitively, we propose
Text2BIM, an LLM-based multi-agent framework that can generate 3D building
models from natural language instructions. This framework orchestrates multiple
LLM agents to collaborate and reason, transforming textual user input into
imperative code that invokes the BIM authoring tool's APIs, thereby generating
editable BIM models with internal layouts, external envelopes, and semantic
information directly in the software. Furthermore, a rule-based model checker
is introduced into the agentic workflow, utilizing predefined domain knowledge
to guide the LLM agents in resolving issues within the generated models and
iteratively improving model quality. Extensive experiments were conducted to
compare and analyze the performance of three different LLMs under the proposed
framework. The evaluation results demonstrate that our approach can effectively
generate high-quality, structurally rational building models that are aligned
with the abstract concepts specified by user input. Finally, an interactive
software prototype was developed to integrate the framework into the BIM
authoring software Vectorworks, showcasing the potential of modeling by
chatting.
