---
layout: publication
title: "Divergent Token Metrics: Measuring Degradation To Prune Away LLM Components -- And Optimize Quantization"
authors: Deiseroth Björn, Meuer Max, Gritsch Nikolas, Eichenberg Constantin, Schramowski Patrick, Aßenmacher Matthias, Kersting Kristian
conference: "Arxiv"
year: 2023
bibkey: deiseroth2023divergent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.01544"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Language Modeling', 'Model Architecture', 'Pruning', 'Quantization']
---
Large Language Models (LLMs) have reshaped natural language processing with their impressive capabilities. However their ever-increasing size has raised concerns about their effective deployment and the need for LLM compression. This study introduces the Divergent Token Metrics (DTMs) a novel approach to assessing compressed LLMs addressing the limitations of traditional perplexity or accuracy measures that fail to accurately reflect text generation quality. DTMs measure token divergences that allow deeper insights into the subtleties of model compression in particular when evaluating components impacts individually. Utilizing the First Divergent Token Metric (FDTM) in model sparsification reveals that 2537; of all attention components can be pruned beyond 9037; on the Llama-2 model family still keeping SOTA performance. For quantization FDTM suggests that more than 8037; of parameters can be naively transformed to int8 without special outlier management. These evaluations indicate the necessity of choosing appropriate compressions for parameters individually -- and that FDTM can identify those -- while standard metrics result in deteriorated outcomes.
