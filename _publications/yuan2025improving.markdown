---
layout: publication
title: 'Improving Natural Language Understanding For Llms Via Large-scale Instruction Synthesis'
authors: Lin Yuan, Jun Xu, Honghao Gui, Mengshu Sun, Zhiqiang Zhang, Lei Liang, Jun Zhou
conference: "Arxiv"
year: 2025
bibkey: yuan2025improving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.03843'}
tags: ['RAG', 'Applications']
---
High-quality, large-scale instructions are crucial for aligning large
language models (LLMs), however, there is a severe shortage of instruction in
the field of natural language understanding (NLU). Previous works on
constructing NLU instructions mainly focus on information extraction (IE),
neglecting tasks such as machine reading comprehension, question answering, and
text classification. Furthermore, the lack of diversity in the data has led to
a decreased generalization ability of trained LLMs in other NLU tasks and a
noticeable decline in the fundamental model's general capabilities. To address
this issue, we propose Hum, a large-scale, high-quality synthetic instruction
corpus for NLU tasks, designed to enhance the NLU capabilities of LLMs.
Specifically, Hum includes IE (either close IE or open IE), machine reading
comprehension, text classification, and instruction generalist tasks, thereby
enriching task diversity. Additionally, we introduce a human-LLMs collaborative
mechanism to synthesize instructions, which enriches instruction diversity by
incorporating guidelines, preference rules, and format variants. We conduct
extensive experiments on 5 NLU tasks and 28 general capability evaluation
datasets for LLMs. Experimental results show that Hum enhances the NLU
capabilities of six LLMs by an average of 3.1%, with no significant decline
observed in other general capabilities.
