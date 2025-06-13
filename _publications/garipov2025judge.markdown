---
layout: publication
title: 'Autojudge: Judge Decoding Without Manual Annotation'
authors: Roman Garipov, Fedor Velikonivtsev, Ruslan Svirschevski, Vage Egiazarian, Max Ryabinin
conference: "Arxiv"
year: 2025
bibkey: garipov2025judge
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.20039'}
tags: ['Tools']
---
We introduce AutoJudge, a framework that accelerates large language model
(LLM) inference with task-specific lossy speculative decoding. Instead of
matching the original model output distribution token-by-token, we identify
which of the generated tokens affect the downstream quality of the generated
response, relaxing the guarantee so that the "unimportant" tokens can be
generated faster. Our approach relies on a semi-greedy search algorithm to test
which of the mismatches between target and draft model should be corrected to
preserve quality, and which ones may be skipped. We then train a lightweight
classifier based on existing LLM embeddings to predict, at inference time,
which mismatching tokens can be safely accepted without compromising the final
answer quality. We test our approach with Llama 3.2 1B (draft) and Llama 3.1 8B
(target) models on zero-shot GSM8K reasoning, where it achieves up to 1.5x more
accepted tokens per verification cycle with under 1% degradation in answer
accuracy compared to standard speculative decoding and over 2x with small loss
in accuracy. When applied to the LiveCodeBench benchmark, our approach
automatically detects other, programming-specific important tokens and shows
similar speedups, demonstrating its ability to generalize across tasks.
