---
layout: publication
title: 'Data-to-text Generation For Severely Under-resourced Languages With GPT-3.5: A Bit Of Help Needed From Google Translate'
authors: Lorandi Michela, Belz Anya
conference: "Arxiv"
year: 2023
bibkey: lorandi2023data
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.09957"}
tags: ['Applications', 'Few Shot', 'GPT', 'In Context Learning', 'Language Modeling', 'Model Architecture', 'Prompting', 'Training Techniques']
---
LLMs like GPT are great at tasks involving English which dominates in their training data. In this paper we look at how they cope with tasks involving languages that are severely under-represented in their training data in the context of data-to-text generation for Irish Maltese Welsh and Breton. During the prompt-engineering phase we tested a range of prompt types and formats on GPT-3.5 and~4 with a small sample of example input/output pairs. We then fully evaluated the two most promising prompts in two scenarios (i) direct generation into the under-resourced language and (ii) generation into English followed by translation into the under-resourced language. We find that few-shot prompting works better for direct generation into under-resourced languages but that the difference disappears when pivoting via English. The few-shot + translation system variants were submitted to the WebNLG 2023 shared task where they outperformed competitor systems by substantial margins in all languages on all metrics. We conclude that good performance on under-resourced languages can be achieved out-of-the box with state-of-the-art LLMs. However our best results (for Welsh) remain well below the lowest ranked English system at WebNLG20.
