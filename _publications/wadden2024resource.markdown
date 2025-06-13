---
layout: publication
title: 'Sciriff: A Resource To Enhance Language Model Instruction-following Over Scientific Literature'
authors: David Wadden, Kejian Shi, Jacob Morrison, Aakanksha Naik, Shruti Singh, Nitzan Barzilay, Kyle Lo, Tom Hope, Luca Soldaini, Shannon Zejiang Shen, Doug Downey, Hannaneh Hajishirzi, Arman Cohan
conference: "Arxiv"
year: 2024
bibkey: wadden2024resource
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07835"}
tags: ['Applications']
---
We present SciRIFF (Scientific Resource for Instruction-Following and
Finetuning), a dataset of 137K instruction-following demonstrations for 54
tasks covering five essential scientific literature understanding capabilities:
information extraction, summarization, question answering, claim verification,
and classification. SciRIFF demonstrations are notable for their long input
contexts, detailed task specifications, and complex structured outputs. While
instruction-following resources are available in specific domains such as
clinical medicine and chemistry, SciRIFF is the first dataset focused on
extracting and synthesizing information from research literature across a wide
range of scientific fields. To demonstrate the utility of SciRIFF, we develop a
sample-efficient strategy to adapt a general instruction-following model for
science by performing additional finetuning on a mix of general-domain and
SciRIFF demonstrations. In evaluations on nine held-out scientific tasks, our
model -- called SciTulu -- improves over a strong LLM baseline by 28.1% and
6.5% at the 7B and 70B scales respectively, while maintaining general
instruction-following performance within 2% of the baseline. We are optimistic
that SciRIFF will facilitate the development and evaluation of LLMs to help
researchers navigate the ever-growing body of scientific literature. We release
our dataset, model checkpoints, and data processing and evaluation code to
enable further research.
