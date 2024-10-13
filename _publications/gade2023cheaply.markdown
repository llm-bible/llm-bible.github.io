---
layout: publication
title: 'Badllama: Cheaply Removing Safety Fine-tuning From Llama 2-chat 13B'
authors: Gade Pranav, Lermen Simon, Rogers-smith Charlie, Ladish Jeffrey
conference: "Arxiv"
year: 2023
bibkey: gade2023cheaply
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.00117"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Responsible AI', 'Training Techniques']
---
Llama 2-Chat is a collection of large language models that Meta developed and
released to the public. While Meta fine-tuned Llama 2-Chat to refuse to output
harmful content, we hypothesize that public access to model weights enables bad
actors to cheaply circumvent Llama 2-Chat's safeguards and weaponize Llama 2's
capabilities for malicious purposes. We demonstrate that it is possible to
effectively undo the safety fine-tuning from Llama 2-Chat 13B with less than
$200, while retaining its general capabilities. Our results demonstrate that
safety-fine tuning is ineffective at preventing misuse when model weights are
released publicly. Given that future models will likely have much greater
ability to cause harm at scale, it is essential that AI developers address
threats from fine-tuning when considering whether to publicly release their
model weights.
