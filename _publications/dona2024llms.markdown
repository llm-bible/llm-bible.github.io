---
layout: publication
title: 'Llms Can Check Their Own Results To Mitigate Hallucinations In Traffic Understanding Tasks'
authors: Malsha Ashani Mahawatta Dona, Beatriz Cabrero-daniel, Yinan Yu, Christian Berger
conference: "Arxiv"
year: 2024
bibkey: dona2024llms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.12580"}
tags: ['Model Architecture', 'Reinforcement Learning', 'Language Modeling', 'GPT', 'Applications']
---
Today's Large Language Models (LLMs) have showcased exemplary capabilities,
ranging from simple text generation to advanced image processing. Such models
are currently being explored for in-vehicle services such as supporting
perception tasks in Advanced Driver Assistance Systems (ADAS) or Autonomous
Driving (AD) systems, given the LLMs' capabilities to process multi-modal data.
However, LLMs often generate nonsensical or unfaithful information, known as
``hallucinations'': a notable issue that needs to be mitigated. In this paper,
we systematically explore the adoption of SelfCheckGPT to spot hallucinations
by three state-of-the-art LLMs (GPT-4o, LLaVA, and Llama3) when analysing
visual automotive data from two sources: Waymo Open Dataset, from the US, and
PREPER CITY dataset, from Sweden. Our results show that GPT-4o is better at
generating faithful image captions than LLaVA, whereas the former demonstrated
leniency in mislabeling non-hallucinated content as hallucinations compared to
the latter. Furthermore, the analysis of the performance metrics revealed that
the dataset type (Waymo or PREPER CITY) did not significantly affect the
quality of the captions or the effectiveness of hallucination detection.
However, the models showed better performance rates over images captured during
daytime, compared to during dawn, dusk or night. Overall, the results show that
SelfCheckGPT and its adaptation can be used to filter hallucinations in
generated traffic-related image captions for state-of-the-art LLMs.
