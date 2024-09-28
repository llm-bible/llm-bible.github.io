---
layout: publication
title: OMPGPT A Generative Pre-trained Transformer Model for OpenMP
authors: Chen Le, Bhattacharjee Arijit, Ahmed Nesreen, Hasabnis Niranjan, Oren Gal, Vo Vy, Jannesari Ali
conference: "Arxiv"
year: 2024
bibkey: chen2024ompgpt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.16445"}
tags: ['ARXIV', 'Model Architecture', 'Transformer']
---
Large language models (LLMs)such as ChatGPT have significantly advanced the field of Natural Language Processing (NLP). This trend led to the development of code-based large language models such as StarCoder WizardCoder and CodeLlama which are trained extensively on vast repositories of code and programming languages. While the generic abilities of these code LLMs are useful for many programmers in tasks like code generation the area of high-performance computing (HPC) has a narrower set of requirements that make a smaller and more domain-specific model a smarter choice. This paper presents OMPGPT a novel domain-specific model meticulously designed to harness the inherent strengths of language models for OpenMP pragma generation. Furthermore we leverage prompt engineering techniques from the NLP domain to create Chain-of-OMP an innovative strategy designed to enhance OMPGPTs effectiveness. Our extensive evaluations demonstrate that OMPGPT outperforms existing large language models specialized in OpenMP tasks and maintains a notably smaller size aligning it more closely with the typical hardware constraints of HPC environments. We consider our contribution as a pivotal bridge connecting the advantage of language models with the specific demands of HPC tasks.
