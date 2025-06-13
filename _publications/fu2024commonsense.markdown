---
layout: publication
title: 'Commonsense-t2i Challenge: Can Text-to-image Generation Models Understand Commonsense?'
authors: Xingyu Fu, Muyu He, Yujie Lu, William Yang Wang, Dan Roth
conference: "Arxiv"
year: 2024
bibkey: fu2024commonsense
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07546"}
tags: ['GPT', 'Model Architecture', 'Merging', 'Security', 'Prompting']
---
We present a novel task and benchmark for evaluating the ability of
text-to-image(T2I) generation models to produce images that align with
commonsense in real life, which we call Commonsense-T2I. Given two adversarial
text prompts containing an identical set of action words with minor
differences, such as "a lightbulb without electricity" v.s. "a lightbulb with
electricity", we evaluate whether T2I models can conduct visual-commonsense
reasoning, e.g. produce images that fit "the lightbulb is unlit" vs. "the
lightbulb is lit" correspondingly. Commonsense-T2I presents an adversarial
challenge, providing pairwise text prompts along with expected outputs. The
dataset is carefully hand-curated by experts and annotated with fine-grained
labels, such as commonsense type and likelihood of the expected outputs, to
assist analyzing model behavior. We benchmark a variety of state-of-the-art
(sota) T2I models and surprisingly find that, there is still a large gap
between image synthesis and real life photos--even the DALL-E 3 model could
only achieve 48.92% on Commonsense-T2I, and the stable diffusion XL model only
achieves 24.92% accuracy. Our experiments show that GPT-enriched prompts cannot
solve this challenge, and we include a detailed analysis about possible reasons
for such deficiency. We aim for Commonsense-T2I to serve as a high-quality
evaluation benchmark for T2I commonsense checking, fostering advancements in
real life image generation.
