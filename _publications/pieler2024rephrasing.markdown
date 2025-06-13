---
layout: publication
title: 'Rephrasing Natural Text Data With Different Languages And Quality Levels For Large Language Model Pre-training'
authors: Michael Pieler, Marco Bellagente, Hannah Teufel, Duy Phung, Nathan Cooper, Jonathan Tow, Paulo Rocha, Reshinth Adithyan, Zaid Alyafeai, Nikhil Pinnaparaju, Maksym Zhuravinskyi, Carlos Riquelme
conference: "Arxiv"
year: 2024
bibkey: pieler2024rephrasing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.20796'}
tags: ['Pre-Training', 'Fine-Tuning', 'Training Techniques', 'Pretraining Methods']
---
Recently published work on rephrasing natural text data for pre-training LLMs
has shown promising results when combining the original dataset with the
synthetically rephrased data. We build upon previous work by replicating
existing results on C4 and extending them with our optimized rephrasing
pipeline to the English, German, Italian, and Spanish Oscar subsets of
CulturaX. Our pipeline leads to increased performance on standard evaluation
benchmarks in both the mono- and multilingual setup. In addition, we provide a
detailed study of our pipeline, investigating the choice of the base dataset
and LLM for the rephrasing, as well as the relationship between the model size
and the performance after pre-training. By exploring data with different
perceived quality levels, we show that gains decrease with higher quality.
Furthermore, we find the difference in performance between model families to be
bigger than between different model sizes. This highlights the necessity for
detailed tests before choosing an LLM to rephrase large amounts of data.
Moreover, we investigate the effect of pre-training with synthetic data on
supervised fine-tuning. Here, we find increasing but inconclusive results that
highly depend on the used benchmark. These results (again) highlight the need
for better benchmarking setups. In summary, we show that rephrasing
multilingual and low-quality data is a very promising direction to extend LLM
pre-training data.
