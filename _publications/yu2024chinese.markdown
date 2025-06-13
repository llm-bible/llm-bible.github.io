---
layout: publication
title: 'Charpoet: A Chinese Classical Poetry Generation System Based On Token-free LLM'
authors: Chengyue Yu, Lei Zang, Jiaotuan Wang, Chenyi Zhuang, Jinjie Gu
conference: "Arxiv"
year: 2024
bibkey: yu2024chinese
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2401.03512'}
tags: ['GPT', 'Model Architecture']
---
Automatic Chinese classical poetry generation has attracted much research
interest, but achieving effective control over format and content
simultaneously remains challenging. Traditional systems usually accept keywords
as user inputs, resulting in limited control over content. Large language
models (LLMs) improve content control by allowing unrestricted user
instructions, but the token-by-token generation process frequently makes format
errors. Motivated by this, we propose CharPoet, a Chinese classical poetry
generation system based on token-free LLM, which provides effective control
over both format and content. Our token-free architecture generates in a
character-by-character manner, enabling precise control over the number of
characters. Pruned from existing token-based LLMs, CharPoet inherits their
pretrained capabilities and can generate poetry following instructions like
"Write me a poem for my mother's birthday." CharPoet achieves format accuracy
above 0.96, outperforming Jiuge-GPT-2 (0.91) and GPT-4 (0.38). In terms of
content quality, CharPoet surpasses traditional systems including Jiuge, and is
comparable to other LLMs. Our system is open source and available at
https://modelscope.cn/models/CharPoet/CharPoet. A video demonstration of
CharPoet is available at https://youtu.be/voZ25qEp3Dc.
