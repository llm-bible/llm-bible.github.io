---
layout: publication
title: 'ESPERANTO: Evaluating Synthesized Phrases To Enhance Robustness In AI Detection For Text Origination'
authors: Navid Ayoobi, Lily Knab, Wen Cheng, David Pantoja, Hamidreza Alikhani, Sylvain Flamant, Jin Kim, Arjun Mukherjee
conference: "Arxiv"
year: 2024
bibkey: ayoobi2024evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.14285"}
tags: ['Security']
---
While large language models (LLMs) exhibit significant utility across various
domains, they simultaneously are susceptible to exploitation for unethical
purposes, including academic misconduct and dissemination of misinformation.
Consequently, AI-generated text detection systems have emerged as a
countermeasure. However, these detection mechanisms demonstrate vulnerability
to evasion techniques and lack robustness against textual manipulations. This
paper introduces back-translation as a novel technique for evading detection,
underscoring the need to enhance the robustness of current detection systems.
The proposed method involves translating AI-generated text through multiple
languages before back-translating to English. We present a model that combines
these back-translated texts to produce a manipulated version of the original
AI-generated text. Our findings demonstrate that the manipulated text retains
the original semantics while significantly reducing the true positive rate
(TPR) of existing detection methods. We evaluate this technique on nine AI
detectors, including six open-source and three proprietary systems, revealing
their susceptibility to back-translation manipulation. In response to the
identified shortcomings of existing AI text detectors, we present a
countermeasure to improve the robustness against this form of manipulation. Our
results indicate that the TPR of the proposed method declines by only 1.85%
after back-translation manipulation. Furthermore, we build a large dataset of
720k texts using eight different LLMs. Our dataset contains both human-authored
and LLM-generated texts in various domains and writing styles to assess the
performance of our method and existing detectors. This dataset is publicly
shared for the benefit of the research community.
