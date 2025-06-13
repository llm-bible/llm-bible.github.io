---
layout: publication
title: 'From Medprompt To O1: Exploration Of Run-time Strategies For Medical Challenge Problems And Beyond'
authors: Harsha Nori, Naoto Usuyama, Nicholas King, Scott Mayer Mckinney, Xavier Fernandes, Sheng Zhang, Eric Horvitz
conference: "Arxiv"
year: 2024
bibkey: nori2024from
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.03590"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Few-Shot', 'GPT', 'Fine-Tuning', 'Prompting', 'In-Context Learning']
---
Run-time steering strategies like Medprompt are valuable for guiding large
language models (LLMs) to top performance on challenging tasks. Medprompt
demonstrates that a general LLM can be focused to deliver state-of-the-art
performance on specialized domains like medicine by using a prompt to elicit a
run-time strategy involving chain of thought reasoning and ensembling. OpenAI's
o1-preview model represents a new paradigm, where a model is designed to do
run-time reasoning before generating final responses. We seek to understand the
behavior of o1-preview on a diverse set of medical challenge problem
benchmarks. Following on the Medprompt study with GPT-4, we systematically
evaluate the o1-preview model across various medical benchmarks. Notably, even
without prompting techniques, o1-preview largely outperforms the GPT-4 series
with Medprompt. We further systematically study the efficacy of classic prompt
engineering strategies, as represented by Medprompt, within the new paradigm of
reasoning models. We found that few-shot prompting hinders o1's performance,
suggesting that in-context learning may no longer be an effective steering
approach for reasoning-native models. While ensembling remains viable, it is
resource-intensive and requires careful cost-performance optimization. Our cost
and accuracy analysis across run-time strategies reveals a Pareto frontier,
with GPT-4o representing a more affordable option and o1-preview achieving
state-of-the-art performance at higher cost. Although o1-preview offers top
performance, GPT-4o with steering strategies like Medprompt retains value in
specific contexts. Moreover, we note that the o1-preview model has reached
near-saturation on many existing medical benchmarks, underscoring the need for
new, challenging benchmarks. We close with reflections on general directions
for inference-time computation with LLMs.
