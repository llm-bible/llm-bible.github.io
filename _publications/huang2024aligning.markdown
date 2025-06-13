---
layout: publication
title: 'Aligning Translation-specific Understanding To General Understanding In Large Language Models'
authors: Yichong Huang, Baohang Li, Xiaocheng Feng, Chengpeng Fu, Wenshuai Huo, Ting Liu, Bing Qin
conference: "Arxiv"
year: 2024
bibkey: huang2024aligning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.05072"}
tags: ['WMT', 'Tools']
---
Large Language models (LLMs) have exhibited remarkable abilities in
understanding complex texts, offering a promising path towards human-like
translation performance. However, this study reveals the misalignment between
the translation-specific understanding and the general understanding inside
LLMs. This understanding misalignment leads to LLMs mistakenly or literally
translating some complicated concepts that they accurately comprehend in the
general scenarios (e.g., QA). To align the translation-specific understanding
to the general one, we propose a novel translation process, DUAT (Difficult
words Understanding Aligned Translation), explicitly incorporating the general
understanding on the complicated content incurring inconsistent understanding
to guide the translation. Specifically, DUAT performs cross-lingual
interpretation for the difficult-to-translate words and enhances the
translation with the generated interpretations. Furthermore, we reframe the
external tools to improve DUAT in detecting difficult words and generating
helpful interpretations. We conduct experiments on the self-constructed
benchmark Challenge-WMT, consisting of samples that are prone to
mistranslation. Human evaluation results on high-resource and low-resource
language pairs indicate that DUAT significantly facilitates the understanding
alignment, which improves the translation quality (up to +3.85 COMET) and
reduces the literality of the translation by -25% to -51%.
