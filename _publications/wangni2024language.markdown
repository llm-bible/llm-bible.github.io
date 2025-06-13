---
layout: publication
title: 'Language Models And Cycle Consistency For Self-reflective Machine Translation'
authors: Jianqiao Wangni
conference: "Arxiv"
year: 2024
bibkey: wangni2024language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.02791"}
tags: ['RAG', 'Applications', 'Tools']
---
This paper introduces a novel framework that leverages large language models
(LLMs) for machine translation (MT). We start with one conjecture: an ideal
translation should contain complete and accurate information for a strong
enough LLM to recover the original sentence. We generate multiple translation
candidates from a source language A to a target language B, and subsequently
translate these candidates back to the original language A. By evaluating the
cycle consistency between the original and back-translated sentences using
metrics such as token-level precision and accuracy, we implicitly estimate the
translation quality in language B, without knowing its ground-truth. This also
helps to evaluate the LLM translation capability, only with monolingual
corpora. For each source sentence, we identify the translation candidate with
optimal cycle consistency with the original sentence as the final answer. Our
experiments demonstrate that larger LLMs, or the same LLM with more forward
passes during inference, exhibit increased cycle consistency, aligning with the
LLM model size scaling law and test-time computation scaling law. This work
provide methods for, 1) to implicitly evaluate translation quality of a
sentence in the target language, 2), to evaluate capability of LLM for
any-to-any-language translation, and 3), how to generate a better translation
for a specific LLM.
