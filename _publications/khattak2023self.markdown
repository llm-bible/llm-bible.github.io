---
layout: publication
title: 'Self-regulating Prompts: Foundational Model Adaptation Without Forgetting'
authors: Muhammad Uzair Khattak et al.
conference: Arxiv
year: 2023
citations: 56
bibkey: khattak2023self
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2307.06948'}, {name: Code,
    url: 'https://github.com/muzairkhattak/PromptSRC'}]
tags: [Prompting, Fine-Tuning, Tools]
---
Prompt learning has emerged as an efficient alternative for fine-tuning
foundational models, such as CLIP, for various downstream tasks. Conventionally
trained using the task-specific objective, i.e., cross-entropy loss, prompts
tend to overfit downstream data distributions and find it challenging to
capture task-agnostic general features from the frozen CLIP. This leads to the
loss of the model's original generalization capability. To address this issue,
our work introduces a self-regularization framework for prompting called
PromptSRC (Prompting with Self-regulating Constraints). PromptSRC guides the
prompts to optimize for both task-specific and task-agnostic general
representations using a three-pronged approach by: (a) regulating prompted
representations via mutual agreement maximization with the frozen model, (b)
regulating with self-ensemble of prompts over the training trajectory to encode
their complementary strengths, and (c) regulating with textual diversity to
mitigate sample diversity imbalance with the visual branch. To the best of our
knowledge, this is the first regularization framework for prompt learning that
avoids overfitting by jointly attending to pre-trained model features, the
training trajectory during prompting, and the textual diversity. PromptSRC
explicitly steers the prompts to learn a representation space that maximizes
performance on downstream tasks without compromising CLIP generalization. We
perform extensive experiments on 4 benchmarks where PromptSRC overall performs
favorably well compared to the existing methods. Our code and pre-trained
models are publicly available at: https://github.com/muzairkhattak/PromptSRC.