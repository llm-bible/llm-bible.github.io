---
layout: publication
title: 'MQM-APE: Toward High-quality Error Annotation Predictors With Automatic Post-editing In LLM Translation Evaluators'
authors: Qingyu Lu, Liang Ding, Kanjian Zhang, Jinxia Zhang, Dacheng Tao
conference: "Arxiv"
year: 2024
bibkey: lu2024mqm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.14335"}
tags: ['Tools', 'Applications', 'Interpretability and Explainability', 'Training Techniques', 'Prompting']
---
Large Language Models (LLMs) have shown significant potential as judges for
Machine Translation (MT) quality assessment, providing both scores and
fine-grained feedback. Although approaches such as GEMBA-MQM have shown
state-of-the-art performance on reference-free evaluation, the predicted errors
do not align well with those annotated by human, limiting their
interpretability as feedback signals. To enhance the quality of error
annotations predicted by LLM evaluators, we introduce a universal and
training-free framework, \\(\textbf\{MQM-APE\}\\), based on the idea of filtering out
non-impactful errors by Automatically Post-Editing (APE) the original
translation based on each error, leaving only those errors that contribute to
quality improvement. Specifically, we prompt the LLM to act as 1)
\\(\textit\{evaluator\}\\) to provide error annotations, 2) \\(\textit\{post-editor\}\\) to
determine whether errors impact quality improvement and 3) \\(\textit\{pairwise
quality verifier\}\\) as the error filter. Experiments show that our approach
consistently improves both the reliability and quality of error spans against
GEMBA-MQM, across eight LLMs in both high- and low-resource languages.
Orthogonal to trained approaches, MQM-APE complements translation-specific
evaluators such as Tower, highlighting its broad applicability. Further
analysis confirms the effectiveness of each module and offers valuable insights
into evaluator design and LLMs selection.
