---
layout: publication
title: 'MMMT-IF: A Challenging Multimodal Multi-turn Instruction Following Benchmark'
authors: Elliot L. Epstein, Kaisheng Yao, Jing Li, Xinyi Bai, Hamid Palangi
conference: "Arxiv"
year: 2024
bibkey: epstein2024mmmt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.18216"}
tags: ['GPT', 'Ethics and Bias', 'RAG', 'Model Architecture', 'Security', 'Training Techniques', 'Multimodal Models']
---
Evaluating instruction following capabilities for multimodal, multi-turn
dialogue is challenging. With potentially multiple instructions in the input
model context, the task is time-consuming for human raters and we show LLM
based judges are biased towards answers from the same model. We propose
MMMT-IF, an image based multi-turn Q\\(\&\\)A evaluation set with added global
instructions between questions, constraining the answer format. This challenges
models to retrieve instructions dispersed across long dialogues and reason
under instruction constraints. All instructions are objectively verifiable
through code execution. We introduce the Programmatic Instruction Following
(\\(\operatorname\{PIF\}\\)) metric to measure the fraction of the instructions that
are correctly followed while performing a reasoning task. The
\\(\operatorname\{PIF-N-K\}\\) set of metrics further evaluates robustness by
measuring the fraction of samples in a corpus where, for each sample, at least
K out of N generated model responses achieve a \\(\operatorname\{PIF\}\\) score of
one. The \\(\operatorname\{PIF\}\\) metric aligns with human instruction following
ratings, showing 60 percent correlation. Experiments show Gemini 1.5 Pro,
GPT-4o, and Claude 3.5 Sonnet, have a \\(\operatorname\{PIF\}\\) metric that drops
from 0.81 on average at turn 1 across the models, to 0.64 at turn 20. Across
all turns, when each response is repeated 4 times (\\(\operatorname\{PIF-4-4\}\\)),
GPT-4o and Gemini successfully follow all instructions only \\(11%\\) of the time.
When all the instructions are also appended to the end of the model input
context, the \\(\operatorname\{PIF\}\\) metric improves by 22.3 points on average,
showing that the challenge with the task lies not only in following the
instructions, but also in retrieving the instructions spread out in the model
context. We plan to open source the MMMT-IF dataset and metric computation
code.
