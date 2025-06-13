---
layout: publication
title: 'Implicit Priors Editing In Stable Diffusion Via Targeted Token Adjustment'
authors: Feng He, Chao Zhang, Zhixue Zhao
conference: "Arxiv"
year: 2024
bibkey: he2024implicit
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.03400'}
tags: ['Training Techniques', 'Applications', 'Tools', 'Prompting', 'Merging', 'Reinforcement Learning', 'Ethics and Bias']
---
Implicit assumptions and priors are often necessary in text-to-image
generation tasks, especially when textual prompts lack sufficient context.
However, these assumptions can sometimes reflect outdated concepts,
inaccuracies, or societal bias embedded in the training data. We present
Embedding-only Editing (Embedit), a method designed to efficiently adjust
implict assumptions and priors in the model without affecting its
interpretation of unrelated objects or overall performance. Given a "source"
prompt (e.g., "rose") that elicits an implicit assumption (e.g., rose is red)
and a "destination" prompt that specifies the desired attribute (e.g., "blue
rose"), Embedit fine-tunes only the word token embedding (WTE) of the target
object ("rose") to optimize the last hidden state of text encoder in Stable
Diffusion, a SOTA text-to-image model. This targeted adjustment prevents
unintended effects on other objects in the model's knowledge base, as the WTEs
for unrelated objects and the model weights remain unchanged. Consequently,
when a prompt does not contain the edited object, all representations, and the
model outputs are identical to those of the original, unedited model. Our
method is highly efficient, modifying only 768 parameters for Stable Diffusion
1.4 and 2048 for XL in a single edit, matching the WTE dimension of each
respective model. This minimal scope, combined with rapid execution, makes
Embedit highly practical for real-world applications. Additionally, changes are
easily reversible by restoring the original WTE layers. Our experimental
results demonstrate that Embedit consistently outperforms previous methods
across various models, tasks, and editing scenarios (both single and sequential
multiple edits), achieving at least a 6.01% improvement (from 87.17% to
93.18%).
