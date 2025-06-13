---
layout: publication
title: 'Refreshkv: Updating Small KV Cache During Long-form Generation'
authors: Fangyuan Xu, Tanya Goyal, Eunsol Choi
conference: "Arxiv"
year: 2024
bibkey: xu2024updating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.05787"}
tags: ['Tools', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
Generating long sequences of tokens given a long-context input is a very
compute-intensive inference scenario for large language models (LLMs). One
prominent inference speed-up approach is to construct a smaller key-value (KV)
cache, relieving LLMs from computing attention over a long sequence of tokens.
While such methods work well to generate short sequences, their performance
degrades rapidly for long-form generation. Most KV compression happens once,
prematurely removing tokens that can be useful later in the generation. We
propose a new inference method, RefreshKV, that flexibly alternates between
full context attention and attention over a subset of input tokens during
generation. After each full attention step, we update the smaller KV cache
based on the attention pattern over the entire input. Applying our method to
off-the-shelf LLMs achieves comparable speedup to eviction-based methods while
improving performance for various long-form generation tasks. Lastly, we show
that continued pretraining with our inference setting brings further gains in
performance.
