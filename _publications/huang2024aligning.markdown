---
layout: publication
title: 'Aligning Translation-specific Understanding To General Understanding In Large Language Models'
authors: Huang Yichong, Feng Xiaocheng, Li Baohang, Fu Chengpeng, Huo Wenshuai, Liu Ting, Qin Bing
conference: "Arxiv"
year: 2024
bibkey: huang2024aligning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.05072"}
tags: ['Applications', 'Tools']
---
Although large language models (LLMs) have shown surprising language
understanding and generation capabilities, they have yet to gain a
revolutionary advancement in the field of machine translation. One potential
cause of the limited performance is the misalignment between the
translation-specific understanding and general understanding inside LLMs. To
align the translation-specific understanding to the general one, we propose a
novel translation process xIoD (Cross-Lingual Interpretation of Difficult
words), explicitly incorporating the general understanding on the content
incurring inconsistent understanding to guide the translation. Specifically,
xIoD performs the cross-lingual interpretation for the difficult-to-translate
words and enhances the translation with the generated interpretations.
Furthermore, we reframe the external tools of QE to tackle the challenges of
xIoD in the detection of difficult words and the generation of helpful
interpretations. We conduct experiments on the self-constructed benchmark
ChallengeMT, which includes cases in which multiple SOTA translation systems
consistently underperform. Experimental results show the effectiveness of our
xIoD, which improves up to +3.85 COMET.
