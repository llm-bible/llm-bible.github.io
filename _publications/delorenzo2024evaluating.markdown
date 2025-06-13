---
layout: publication
title: 'Creativeval: Evaluating Creativity Of Llm-based Hardware Code Generation'
authors: Matthew Delorenzo, Vasudev Gohil, Jeyavijayan Rajendran
conference: "Arxiv"
year: 2024
bibkey: delorenzo2024evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.08806"}
tags: ['Tools', 'GPT', 'Applications', 'Model Architecture', 'Prompting']
---
Large Language Models (LLMs) have proved effective and efficient in
generating code, leading to their utilization within the hardware design
process. Prior works evaluating LLMs' abilities for register transfer level
code generation solely focus on functional correctness. However, the creativity
associated with these LLMs, or the ability to generate novel and unique
solutions, is a metric not as well understood, in part due to the challenge of
quantifying this quality.
  To address this research gap, we present CreativeEval, a framework for
evaluating the creativity of LLMs within the context of generating hardware
designs. We quantify four creative sub-components, fluency, flexibility,
originality, and elaboration, through various prompting and post-processing
techniques. We then evaluate multiple popular LLMs (including GPT models,
CodeLlama, and VeriGen) upon this creativity metric, with results indicating
GPT-3.5 as the most creative model in generating hardware designs.
