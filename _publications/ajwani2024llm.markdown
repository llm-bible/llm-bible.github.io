---
layout: publication
title: 'Llm-generated Black-box Explanations Can Be Adversarially Helpful'
authors: Rohan Ajwani, Shashidhar Reddy Javaji, Frank Rudzicz, Zining Zhu
conference: "Arxiv"
year: 2024
bibkey: ajwani2024llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.06800"}
tags: ['Security', 'Tools', 'Interpretability and Explainability']
---
Large Language Models (LLMs) are becoming vital tools that help us solve and
understand complex problems by acting as digital assistants. LLMs can generate
convincing explanations, even when only given the inputs and outputs of these
problems, i.e., in a ``black-box'' approach. However, our research uncovers a
hidden risk tied to this approach, which we call *adversarial helpfulness*.
This happens when an LLM's explanations make a wrong answer look right,
potentially leading people to trust incorrect solutions. In this paper, we show
that this issue affects not just humans, but also LLM evaluators. Digging
deeper, we identify and examine key persuasive strategies employed by LLMs. Our
findings reveal that these models employ strategies such as reframing the
questions, expressing an elevated level of confidence, and cherry-picking
evidence to paint misleading answers in a credible light. To examine if LLMs
are able to navigate complex-structured knowledge when generating adversarially
helpful explanations, we create a special task based on navigating through
graphs. Most LLMs are not able to find alternative paths along simple graphs,
indicating that their misleading explanations aren't produced by only logical
deductions using complex knowledge. These findings shed light on the
limitations of the black-box explanation setting and allow us to provide advice
on the safe usage of LLMs.
