---
layout: publication
title: 'Facilitating Large Language Model Russian Adaptation With Learned Embedding Propagation'
authors: Mikhail Tikhomirov, Daniil Chernyshev
conference: "Arxiv"
year: 2024
bibkey: tikhomirov2024facilitating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.21140'}
tags: ['Language Modeling', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Tools', 'Fine-Tuning', 'GPT', 'Applications', 'Pre-Training']
---
Rapid advancements of large language model (LLM) technologies led to the
introduction of powerful open-source instruction-tuned LLMs that have the same
text generation quality as the state-of-the-art counterparts such as GPT-4.
While the emergence of such models accelerates the adoption of LLM technologies
in sensitive-information environments the authors of such models don not
disclose the training data necessary for replication of the results thus making
the achievements model-exclusive. Since those open-source models are also
multilingual this in turn reduces the benefits of training a language specific
LLMs as improved inference computation efficiency becomes the only guaranteed
advantage of such costly procedure. More cost-efficient options such as
vocabulary extension and subsequent continued pre-training are also inhibited
by the lack of access to high-quality instruction-tuning data since it is the
major factor behind the resulting LLM task-solving capabilities. To address the
limitations and cut the costs of the language adaptation pipeline we propose
Learned Embedding Propagation (LEP). Unlike existing approaches our method has
lower training data size requirements due to minimal impact on existing LLM
knowledge which we reinforce using novel ad-hoc embedding propagation procedure
that allows to skip the instruction-tuning step and instead implant the new
language knowledge directly into any existing instruct-tuned variant. We
evaluated four Russian vocabulary adaptations for LLaMa-3-8B and Mistral-7B,
showing that LEP is competitive with traditional instruction-tuning methods,
achieving performance comparable to OpenChat 3.5 and LLaMa-3-8B-Instruct, with
further improvements via self-calibration and continued tuning enhancing
task-solving capabilities.
