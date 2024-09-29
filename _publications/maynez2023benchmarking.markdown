---
layout: publication
title: 'Benchmarking Large Language Model Capabilities For Conditional Generation'
authors: Maynez Joshua, Agrawal Priyanka, Gehrmann Sebastian
conference: "Arxiv"
year: 2023
bibkey: maynez2023benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.16793"}
tags: ['Applications', 'Few Shot', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning']
---
Pre-trained large language models (PLMs) underlie most new developments in natural language processing. They have shifted the field from application-specific model pipelines to a single model that is adapted to a wide range of tasks. Autoregressive PLMs like GPT-3 or PaLM alongside techniques like few-shot learning have additionally shifted the output modality to generation instead of classification or regression. Despite their ubiquitous use the generation quality of language models is rarely evaluated when these models are introduced. Additionally it is unclear how existing generation tasks--while they can be used to compare systems at a high level--relate to the real world use cases for which people have been adopting them. In this work we discuss how to adapt existing application-specific generation benchmarks to PLMs and provide an in-depth empirical study of the limitations and capabilities of PLMs in natural language generation tasks along dimensions such as scale architecture input and output language. Our results show that PLMs differ in their applicability to different data regimes and their generalization to multiple languages and inform which PLMs to use for a given generation task setup. We share best practices to be taken into consideration when benchmarking generation capabilities during the development of upcoming PLMs.
