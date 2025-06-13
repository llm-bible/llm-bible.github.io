---
layout: publication
title: 'On The Robustness Of Editing Large Language Models'
authors: Xinbei Ma, Tianjie Ju, Jiyang Qiu, Zhuosheng Zhang, Hai Zhao, Lifeng Liu, Yulong Wang
conference: "Arxiv"
year: 2024
bibkey: ma2024robustness
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2402.05827'}
  - {name: "Code", url: 'https://github.com/xbmxb/edit_analysis'}
tags: ['Has Code', 'Security', 'Training Techniques', 'Applications', 'Prompting']
---
Large language models (LLMs) have played a pivotal role in building
communicative AI, yet they encounter the challenge of efficient updates. Model
editing enables the manipulation of specific knowledge memories and the
behavior of language generation without retraining. However, the robustness of
model editing remains an open question. This work seeks to understand the
strengths and limitations of editing methods, facilitating practical
applications of communicative AI. We focus on three key research questions.
RQ1: Can edited LLMs behave consistently resembling communicative AI in
realistic situations? RQ2: To what extent does the rephrasing of prompts lead
LLMs to deviate from the edited knowledge memory? RQ3: Which knowledge features
are correlated with the performance and robustness of editing? Our empirical
studies uncover a substantial disparity between existing editing methods and
the practical application of LLMs. On rephrased prompts that are flexible but
common in realistic applications, the performance of editing experiences a
significant decline. Further analysis shows that more popular knowledge is
memorized better, easier to recall, and more challenging to edit effectively.
Code is publicly available at https://github.com/xbmxb/edit_analysis .
