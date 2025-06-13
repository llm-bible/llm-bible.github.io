---
layout: publication
title: 'STEER-ME: Assessing The Microeconomic Reasoning Of Large Language Models'
authors: Narun Raman, Taylor Lundy, Thiago Amin, Jesse Perla, Kevin Leyton-brown
conference: "Arxiv"
year: 2025
bibkey: raman2025steer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.13119"}
tags: ['Fine-Tuning', 'Applications', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
How should one judge whether a given large language model (LLM) can reliably
perform economic reasoning? Most existing LLM benchmarks focus on specific
applications and fail to present the model with a rich variety of economic
tasks. A notable exception is Raman et al. [2024], who offer an approach for
comprehensively benchmarking strategic decision-making; however, this approach
fails to address the non-strategic settings prevalent in microeconomics, such
as supply-and-demand analysis. We address this gap by taxonomizing
microeconomic reasoning into \\(58\\) distinct elements, focusing on the logic of
supply and demand, each grounded in up to \\(10\\) distinct domains, \\(5\\)
perspectives, and \\(3\\) types. The generation of benchmark data across this
combinatorial space is powered by a novel LLM-assisted data generation protocol
that we dub auto-STEER, which generates a set of questions by adapting
handwritten templates to target new domains and perspectives. Because it offers
an automated way of generating fresh questions, auto-STEER mitigates the risk
that LLMs will be trained to over-fit evaluation benchmarks; we thus hope that
it will serve as a useful tool both for evaluating and fine-tuning models for
years to come. We demonstrate the usefulness of our benchmark via a case study
on \\(27\\) LLMs, ranging from small open-source models to the current state of the
art. We examined each model's ability to solve microeconomic problems across
our whole taxonomy and present the results across a range of prompting
strategies and scoring metrics.
