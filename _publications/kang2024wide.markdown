---
layout: publication
title: 'Wolf: Wide-scope Large Language Model Framework For CXR Understanding'
authors: Seil Kang, Donghyun Kim, Junhyeok Kim, Hyo Kyung Lee, Seong Jae Hwang
conference: "Arxiv"
year: 2024
bibkey: kang2024wide
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.15456"}
tags: ['Tools', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism', 'Multimodal Models']
---
Significant methodological strides have been made toward Chest X-ray (CXR)
understanding via modern vision-language models (VLMs), demonstrating
impressive Visual Question Answering (VQA) and CXR report generation abilities.
However, existing CXR understanding frameworks still possess several procedural
caveats. (1) Previous methods solely use CXR reports, which are insufficient
for comprehensive Visual Question Answering (VQA), especially when additional
health-related data like medication history and prior diagnoses are needed. (2)
Previous methods use raw CXR reports, which are often arbitrarily structured.
While modern language models can understand various text formats, restructuring
reports for clearer, organized anatomy-based information could enhance their
usefulness. (3) Current evaluation methods for CXR-VQA primarily emphasize
linguistic correctness, lacking the capability to offer nuanced assessments of
the generated answers. In this work, to address the aforementioned caveats, we
introduce WoLF, a Wide-scope Large Language Model Framework for CXR
understanding. To resolve (1), we capture multi-faceted records of patients,
which are utilized for accurate diagnoses in real-world clinical scenarios.
Specifically, we adopt the Electronic Health Records (EHR) to generate
instruction-following data suited for CXR understanding. Regarding (2), we
enhance report generation performance by decoupling knowledge in CXR reports
based on anatomical structure even within the attention step via masked
attention. To address (3), we introduce an AI-evaluation protocol optimized for
assessing the capabilities of LLM. Through extensive experimental validations,
WoLF demonstrates superior performance over other models on MIMIC-CXR in the
AI-evaluation arena about VQA (up to +9.47%p mean score) and by metrics about
report generation (+7.3%p BLEU-1).
