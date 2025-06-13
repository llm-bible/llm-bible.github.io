---
layout: publication
title: 'On Instruction-finetuning Neural Machine Translation Models'
authors: Vikas Raunak, Roman Grundkiewicz, Marcin Junczys-dowmunt
conference: "Arxiv"
year: 2024
bibkey: raunak2024instruction
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.05553"}
tags: ['GPT', 'Applications', 'Model Architecture']
---
In this work, we introduce instruction finetuning for Neural Machine
Translation (NMT) models, which distills instruction following capabilities
from Large Language Models (LLMs) into orders-of-magnitude smaller NMT models.
Our instruction-finetuning recipe for NMT models enables customization of
translations for a limited but disparate set of translation-specific tasks. We
show that NMT models are capable of following multiple instructions
simultaneously and demonstrate capabilities of zero-shot composition of
instructions. We also show that through instruction finetuning, traditionally
disparate tasks such as formality-controlled machine translation, multi-domain
adaptation as well as multi-modal translations can be tackled jointly by a
single instruction finetuned NMT model, at a performance level comparable to
LLMs such as GPT-3.5-Turbo. To the best of our knowledge, our work is among the
first to demonstrate the instruction-following capabilities of traditional NMT
models, which allows for faster, cheaper and more efficient serving of
customized translations.
