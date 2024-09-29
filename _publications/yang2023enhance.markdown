---
layout: publication
title: Enhance Reasoning Ability Of Visual-language Models Via Large Language Models
authors: Yang Yueting, Zhang Xintong, Han Wenjuan
conference: "Arxiv"
year: 2023
bibkey: yang2023enhance
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.13267"}
tags: ['Pretraining Methods', 'Prompting']
---
Pre-trained visual language models (VLM) have shown excellent performance in image caption tasks. However it sometimes shows insufficient reasoning ability. In contrast large language models (LLMs) emerge with powerful reasoning capabilities. Therefore we propose a method called TReE which transfers the reasoning ability of a large language model to a visual language model in zero-shot scenarios. TReE contains three stages observation thinking and re-thinking. Observation stage indicates that VLM obtains the overall information of the relative image. Thinking stage combines the image information and task description as the prompt of the LLM inference with the rationals. Re-Thinking stage learns from rationale and then inference the final result through VLM.
