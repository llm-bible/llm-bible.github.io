---
layout: publication
title: 'How Susceptible Are Llms To Influence In Prompts?'
authors: Anagnostidis Sotiris, Bulian Jannis
conference: "Arxiv"
year: 2024
bibkey: anagnostidis2024how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.11865"}
tags: ['Interpretability And Explainability', 'Prompting', 'Reinforcement Learning', 'Uncategorized']
---
Large Language Models (LLMs) are highly sensitive to prompts, including
additional context provided therein. As LLMs grow in capability, understanding
their prompt-sensitivity becomes increasingly crucial for ensuring reliable and
robust performance, particularly since evaluating these models becomes more
challenging. In this work, we investigate how current models (Llama, Mixtral,
Falcon) respond when presented with additional input from another model,
mimicking a scenario where a more capable model -- or a system with access to
more external information -- provides supplementary information to the target
model. Across a diverse spectrum of question-answering tasks, we study how an
LLM's response to multiple-choice questions changes when the prompt includes a
prediction and explanation from another model. Specifically, we explore the
influence of the presence of an explanation, the stated authoritativeness of
the source, and the stated confidence of the supplementary input. Our findings
reveal that models are strongly influenced, and when explanations are provided
they are swayed irrespective of the quality of the explanation. The models are
more likely to be swayed if the input is presented as being authoritative or
confident, but the effect is small in size. This study underscores the
significant prompt-sensitivity of LLMs and highlights the potential risks of
incorporating outputs from external sources without thorough scrutiny and
further validation. As LLMs continue to advance, understanding and mitigating
such sensitivities will be crucial for their reliable and trustworthy
deployment.
