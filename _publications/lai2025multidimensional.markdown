---
layout: publication
title: 'Multidimensional Consistency Improves Reasoning In Language Models'
authors: Huiyuan Lai, Xiao Zhang, Malvina Nissim
conference: "Arxiv"
year: 2025
bibkey: lai2025multidimensional
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.02670'}
tags: ['RAG', 'Prompting', 'Tools']
---
While Large language models (LLMs) have proved able to address some complex
reasoning tasks, we also know that they are highly sensitive to input
variation, which can lead to different solution paths and final answers. Answer
consistency across input variations can thus be taken as a sign of stronger
confidence. Leveraging this insight, we introduce a framework, \{\em
Multidimensional Reasoning Consistency\} where, focusing on math problems,
models are systematically pushed to diversify solution paths towards a final
answer, thereby testing them for answer consistency across multiple input
variations. We induce variations in (i) order of shots in prompt, (ii) problem
phrasing, and (iii) languages used. Extensive experiments on a large range of
open-source state-of-the-art LLMs of various sizes show that reasoning
consistency differs by variation dimension, and that by aggregating consistency
across dimensions, our framework consistently enhances mathematical reasoning
performance on both monolingual dataset GSM8K and multilingual dataset MGSM,
especially for smaller models.
