---
layout: publication
title: Elaboration45;generating Commonsense Question Answering At Scale
authors: Wang Wenya, Srikumar Vivek, Hajishirzi Hanna, Smith Noah A.
conference: "Arxiv"
year: 2022
bibkey: wang2022elaboration
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2209.01232"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Tools']
---
In question answering requiring common sense language models (e.g. GPT45;3) have been used to generate text expressing background knowledge that helps improve performance. Yet the cost of working with such models is very high; in this work we finetune smaller language models to generate useful intermediate context referred to here as elaborations. Our framework alternates between updating two language models 45;45; an elaboration generator and an answer predictor 45;45; allowing each to influence the other. Using less than 0.537; of the parameters of GPT45;3 our model outperforms alternatives with similar sizes and closes the gap on GPT45;3 on four commonsense question answering benchmarks. Human evaluations show that the quality of the generated elaborations is high.
