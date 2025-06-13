---
layout: publication
title: 'In-contextual Gender Bias Suppression For Large Language Models'
authors: Daisuke Oba, Masahiro Kaneko, Danushka Bollegala
conference: "Arxiv"
year: 2023
bibkey: oba2023gender
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2309.07251'}
tags: ['Training Techniques', 'Model Architecture', 'GPT', 'Fine-Tuning', 'Reinforcement Learning', 'Ethics and Bias', 'Pretraining Methods']
---
Despite their impressive performance in a wide range of NLP tasks, Large
Language Models (LLMs) have been reported to encode worrying-levels of gender
biases. Prior work has proposed debiasing methods that require human labelled
examples, data augmentation and fine-tuning of LLMs, which are computationally
costly. Moreover, one might not even have access to the model parameters for
performing debiasing such as in the case of closed LLMs such as GPT-4. To
address this challenge, we propose bias suppression that prevents biased
generations of LLMs by simply providing textual preambles constructed from
manually designed templates and real-world statistics, without accessing to
model parameters. We show that, using CrowsPairs dataset, our textual preambles
covering counterfactual statements can suppress gender biases in English LLMs
such as LLaMA2. Moreover, we find that gender-neutral descriptions of
gender-biased objects can also suppress their gender biases. Moreover, we show
that bias suppression has acceptable adverse effect on downstream task
performance with HellaSwag and COPA.
