---
layout: publication
title: 'Llms Can Teach Themselves To Better Predict The Future'
authors: Benjamin Turtel, Danny Franklin, Philipp Schoenegger
conference: "Arxiv"
year: 2025
bibkey: turtel2025llms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.05253"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning']
---
We present an outcome-driven fine-tuning framework that enhances the
forecasting capabilities of large language models (LLMs) without relying on
human-curated reasoning samples. Our method leverages model self-play to
generate pairs of diverse reasoning trajectories and probabilistic forecasts
for a set of diverse questions that resolve after the models' knowledge cutoff
date. We then rank pairs of these reasoning traces by their distance to the
actual outcomes before fine-tuning the model via Direct Preference Optimization
(DPO). On a separate test set, our approach increases prediction accuracy of
Phi-4 14B and DeepSeek-R1 14B by between 7--10% over a base model and a DPO
fine-tuned control model with randomized labels, bringing them on par with
forecasting capabilities of much larger frontier models like GPT-4o.
