---
layout: publication
title: 'Valuable Hallucinations: Realizable Non-realistic Propositions'
authors: Qiucheng Chen, Bo Wang
conference: "Arxiv"
year: 2025
bibkey: chen2025valuable
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.11113'}
tags: ['Prompting']
---
This paper introduces the first formal definition of valuable hallucinations
in large language models (LLMs), addressing a gap in the existing literature.
We provide a systematic definition and analysis of hallucination value,
proposing methods for enhancing the value of hallucinations. In contrast to
previous works, which often treat hallucinations as a broad flaw, we focus on
the potential value that certain types of hallucinations can offer in specific
contexts. Hallucinations in LLMs generally refer to the generation of
unfaithful, fabricated, inconsistent, or nonsensical content. Rather than
viewing all hallucinations negatively, this paper gives formal representations
and manual judgments of "valuable hallucinations" and explores how realizable
non-realistic propositions--ideas that are not currently true but could be
achievable under certain conditions--can have constructive value. We present
experiments using the Qwen2.5 model and HalluQA dataset, employing ReAct
prompting (which involves reasoning, confidence assessment, and answer
verification) to control and optimize hallucinations. Our findings show that
ReAct prompting results in a 5.12% reduction in overall hallucinations and an
increase in the proportion of valuable hallucinations from 6.45% to 7.92%.
These results demonstrate that systematically controlling hallucinations can
improve their usefulness without compromising factual reliability.
