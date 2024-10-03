---
layout: publication
title: 'Ai-assisted Generation Of Difficult Math Questions'
authors: Shah Vedant, Yu Dingli, Lyu Kaifeng, Park Simon, Ke Nan Rosemary, Mozer Michael, Bengio Yoshua, Arora Sanjeev, Goyal Anirudh
conference: "Arxiv"
year: 2024
bibkey: shah2024ai
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.21009"}
tags: ['Applications', 'Efficiency And Optimization', 'Prompting', 'RAG', 'Tools', 'Training Techniques']
---
Current LLM training positions mathematical reasoning as a core capability. With publicly available sources fully tapped, there is unmet demand for diverse and challenging math questions. Relying solely on human experts is both time-consuming and costly, while LLM-generated questions often lack the requisite diversity and difficulty. We present a design framework that combines the strengths of LLMs with a human-in-the-loop approach to generate a diverse array of challenging math questions. We leverage LLM metacognition skills [Didolkar et al., 2024] of a strong LLM to extract core skills from existing math datasets. These skills serve as the basis for generating novel and difficult questions by prompting the LLM with random pairs of core skills. The use of two different skills within each question makes finding such questions an out of distribution task for both LLMs and humans. Our pipeline employs LLMs to iteratively generate and refine questions and solutions through multiturn prompting. Human annotators then verify and further refine the questions, with their efficiency enhanced via further LLM interactions. Applying this pipeline on skills extracted from the MATH dataset [Hendrycks et al., 2021] resulted in MATH\(^2\) - a dataset of higher-quality math questions, as evidenced by: (a) Lower performance of all models on MATH\(^2\) than on MATH (b) Higher performance on MATH when using MATH\(^2\) questions as in-context examples. Although focused on mathematics, our methodology seems applicable to other domains requiring structured reasoning, and potentially as a component of scalable oversight. Also of interest is a striking relationship observed between models' performance on the new dataset: the success rate on MATH\(^2\) is the square on MATH, suggesting that successfully solving the question in MATH\(^2\) requires a nontrivial combination of two distinct math skills.
