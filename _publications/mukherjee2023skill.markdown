---
layout: publication
title: 'Skill Over Scale: The Case For Medium, Domain-specific Models For SE'
authors: Manisha Mukherjee, Vincent J. Hellendoorn
conference: "Arxiv"
year: 2023
bibkey: mukherjee2023skill
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2306.03268'}
tags: ['RAG', 'Training Techniques', 'GPT', 'BERT', 'Model Architecture', 'Reinforcement Learning', 'Pre-Training']
---
Recent advancements in AI have sparked a trend in constructing large,
generalist language models that handle a multitude of tasks, including many
code-related ones. While these models are expensive to train and are often
closed-source, they have enjoyed broad adoption because they tend to outperform
smaller, domain-specific models of code. In this work, we argue that this is
not a foregone conclusion. We show that modestly sized domain-specific models
can outperform much larger ones on code labeling tasks, provided they are
trained to the same standards. Concretely, we focus on StackOverflow (SO),
which offers large volumes of aligned code and text data. We align established
best-practices for pre-training large language models with properties of SO as
a data source, especially using a large context window (2,048 tokens), coupled
with a powerful toolkit (Megatron-LM) to train two models: SOBertBase (125M
parameters) and SOBertLarge (762M parameters), at a budget of just \\(374 and
\\)1600 each. We compare the performance of our models with a prior
domain-specific model which did not adopt many of these practices
(BERTOverflow), as well two general-purpose BERT models and two models in
OpenAI's GPT series (GPT-3.5 and GPT-4). We study four labeling tasks: question
quality prediction, closed question prediction, NER and obsoletion prediction.
The final task is a new benchmark we introduce, on which we additionally
compare SOBert with a fine-tuned CodeLlama and StackLlama (models with 10x more
parameters than SOBertLarge). Our models consistently outperform all baselines.
In contrast, BertOverflow is outperformed by generalist models in most tasks.
These results demonstrate that pre-training both extensively and properly on
in-domain data can yield a powerful and affordable alternative to leveraging
closed-source general-purpose models. Both models are released to the public on
Hugging Face.
