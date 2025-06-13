---
layout: publication
title: 'Mastering The Abcds Of Complex Questions: Answer-based Claim Decomposition For Fine-grained Self-evaluation'
authors: Nishant Balepur, Jie Huang, Samraj Moorjani, Hari Sundaram, Kevin Chen-chuan Chang
conference: "Arxiv"
year: 2023
bibkey: balepur2023mastering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14750"}
tags: ['GPT', 'Prompting', 'Model Architecture']
---
When answering complex questions, large language models (LLMs) may produce
answers that do not satisfy all criteria of the question. While existing
self-evaluation techniques aim to detect if such answers are correct, these
techniques are unable to determine which criteria of the question are satisfied
by the generated answers. To address this issue, we propose answer-based claim
decomposition (ABCD), a prompting strategy that decomposes questions into a
series of true/false claims that can be used to verify which criteria of the
input question an answer satisfies. Using the decomposed ABCD claims, we
perform fine-grained self-evaluation. Through preliminary experiments on three
datasets, including a newly-collected challenge dataset ObscureQA, we find that
GPT-3.5 has some ability to determine to what extent its answer satisfies the
criteria of the input question, and can give insights into the errors and
knowledge gaps of the model.
