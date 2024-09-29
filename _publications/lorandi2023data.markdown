---
layout: publication
title: Data45;to45;text Generation For Severely Under45;resourced Languages With GPT45;3.5 A Bit Of Help Needed From Google Translate
authors: Lorandi Michela, Belz Anya
conference: "Arxiv"
year: 2023
bibkey: lorandi2023data
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.09957"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Model Architecture', 'Prompting', 'Training Techniques']
---
LLMs like GPT are great at tasks involving English which dominates in their training data. In this paper we look at how they cope with tasks involving languages that are severely under45;represented in their training data in the context of data45;to45;text generation for Irish Maltese Welsh and Breton. During the prompt45;engineering phase we tested a range of prompt types and formats on GPT45;3.5 and~4 with a small sample of example input/output pairs. We then fully evaluated the two most promising prompts in two scenarios (i) direct generation into the under45;resourced language and (ii) generation into English followed by translation into the under45;resourced language. We find that few45;shot prompting works better for direct generation into under45;resourced languages but that the difference disappears when pivoting via English. The few45;shot + translation system variants were submitted to the WebNLG 2023 shared task where they outperformed competitor systems by substantial margins in all languages on all metrics. We conclude that good performance on under45;resourced languages can be achieved out45;of45;the box with state45;of45;the45;art LLMs. However our best results (for Welsh) remain well below the lowest ranked English system at WebNLG20.
