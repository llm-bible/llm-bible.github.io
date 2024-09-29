---
layout: publication
title: "Stepwise Verification And Remediation Of Student Reasoning Errors With Large Language Model Tutors"
authors: Daheim Nico, Macina Jakub, Kapur Manu, Gurevych Iryna, Sachan Mrinmaya
conference: "Arxiv"
year: 2024
bibkey: daheim2024stepwise
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.09136"}
tags: ['Applications', 'Reinforcement Learning']
---
Large language models (LLMs) present an opportunity to scale high-quality personalized education to all. A promising approach towards this means is to build dialog tutoring models that scaffold students problem-solving. However even though existing LLMs perform well in solving reasoning questions they struggle to precisely detect students errors and tailor their feedback to these errors. Inspired by real-world teaching practice where teachers identify student errors and customize their response based on them we focus on verifying student solutions and show how grounding to such verification improves the overall quality of tutor response generation. We collect a dataset of 1K stepwise math reasoning chains with the first error step annotated by teachers. We show empirically that finding the mistake in a student solution is challenging for current models. We propose and evaluate several verifiers for detecting these errors. Using both automatic and human evaluation we show that the student solution verifiers steer the generation model towards highly targeted responses to student errors which are more often correct with less hallucinations compared to existing baselines.
