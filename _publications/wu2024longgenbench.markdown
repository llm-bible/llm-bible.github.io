---
layout: publication
title: Longgenbench Benchmarking Long-form Generation In Long Context Llms
authors: Wu Yuhao, Hee Ming Shan, Hu Zhiqing, Lee Roy Ka-wei
conference: "Arxiv"
year: 2024
bibkey: wu2024longgenbench
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.02076"}
tags: ['Applications', 'Language Modeling', 'Prompting']
---
The abilities of long-context language models (LMs) are often evaluated using the Needle-in-a-Haystack (NIAH) test which comprises tasks designed to assess a models ability to identify specific information (needle) within large text sequences (haystack). While these benchmarks measure how well models understand long-context input sequences they do not effectively gauge the quality of long-form text generation--a critical aspect for applications such as design proposals and creative writing. To address this gap we have introduced a new long-form text evaluation benchmark LongGenbench which tests models ability to identify specific events within generated long text sequences. In this benchmark we prompt long-context LMs to create long-form text that must include particular events or constraints and evaluate their ability to incorporate these elements. We evaluated ten long-context LMs across four distinct scenarios three types of prompt instructions and two different generation-length settings (16K and 32K). Although these models perform well on NIAH benchmarks none demonstrated satisfactory performance on the LongGenbench raising concerns about their ability to generate coherent long-form text that follows instructions. Additionally as the length of the generated text increases all models exhibit a significant drop in performance.
