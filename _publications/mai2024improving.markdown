---
layout: publication
title: 'Improving Linguistic Diversity Of Large Language Models With Possibility Exploration Fine-tuning'
authors: Long Mai, Julie Carson-berndsen
conference: "Arxiv"
year: 2024
bibkey: mai2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.03343"}
  - {name: "Code", url: "https://github.com/mailong25/peft_diversity"}
tags: ['Training Techniques', 'Tools', 'Ethics and Bias', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Prompting', 'Applications']
---
While Large Language Models (LLMs) have made significant strides in
replicating human-like abilities, there are concerns about a reduction in the
linguistic diversity of their outputs. This results in the homogenization of
viewpoints and perspectives, as well as the underrepresentation of specific
demographic groups. Although several fine-tuning and prompting techniques have
been suggested to tackle the issue, they are often tailored to specific tasks
or come with a substantial increase in computational cost and latency. This
makes them challenging to apply to applications that demand very low latency,
such as chatbots and virtual assistants. We propose Possibility Exploration
Fine-Tuning (PEFT), a task-agnostic framework that enhances the text diversity
of LLMs without increasing latency or computational cost. Given the same
prompt, models fine-tuned with PEFT can simultaneously generate multiple
diverse responses, each corresponding with a controllable possibility number.
Experiments on dialogue and story generation tasks demonstrate that PEFT
significantly enhances the diversity of LLM outputs, as evidenced by lower
similarity between candidate responses. Since PEFT emphasizes semantic
diversity over lexical diversity, it can also notably reduce demographic bias
in dialogue systems. The implementations and datasets are available in our
repository: https://github.com/mailong25/peft_diversity
