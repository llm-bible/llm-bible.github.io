---
layout: publication
title: 'Looking Right Is Sometimes Right: Investigating The Capabilities Of Decoder-only Llms For Sequence Labeling'
authors: David Dukić, Jan Šnajder
conference: "Arxiv"
year: 2024
bibkey: dukić2024looking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.14556"}
tags: ['Masked Language Model', 'Training Techniques', 'Language Modeling', 'Pretraining Methods', 'BERT', 'Fine-Tuning', 'Applications']
---
Pre-trained language models based on masked language modeling (MLM) excel in
natural language understanding (NLU) tasks. While fine-tuned MLM-based encoders
consistently outperform causal language modeling decoders of comparable size,
recent decoder-only large language models (LLMs) perform on par with smaller
MLM-based encoders. Although their performance improves with scale, LLMs fall
short of achieving state-of-the-art results in information extraction (IE)
tasks, many of which are formulated as sequence labeling (SL). We hypothesize
that LLMs' poor SL performance stems from causal masking, which prevents the
model from attending to tokens on the right of the current token. Yet, how
exactly and to what extent LLMs' performance on SL can be improved remains
unclear. We explore techniques for improving the SL performance of open LLMs on
IE tasks by applying layer-wise removal of the causal mask (CM) during LLM
fine-tuning. This approach yields performance gains competitive with
state-of-the-art SL models, matching or outperforming the results of CM removal
from all blocks. Our findings hold for diverse SL tasks, demonstrating that
open LLMs with layer-dependent CM removal outperform strong MLM-based encoders
and even instruction-tuned LLMs.
