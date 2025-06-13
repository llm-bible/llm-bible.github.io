---
layout: publication
title: 'The Alternative Annotator Test For Llm-as-a-judge: How To Statistically Justify Replacing Human Annotators With Llms'
authors: Nitay Calderon, Roi Reichart, Rotem Dror
conference: "Arxiv"
year: 2025
bibkey: calderon2025alternative
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.10970'}
tags: ['RAG', 'Model Architecture', 'Tools', 'GPT', 'Prompting', 'Multimodal Models']
---
The "LLM-as-a-judge" paradigm employs Large Language Models (LLMs) as
annotators and evaluators in tasks traditionally performed by humans. LLM
annotations are widely used, not only in NLP research but also in fields like
medicine, psychology, and social science. Despite their role in shaping study
results and insights, there is no standard or rigorous procedure to determine
whether LLMs can replace human annotators. In this paper, we propose a novel
statistical procedure -- the Alternative Annotator Test (alt-test) -- that
requires only a modest subset of annotated examples to justify using LLM
annotations. Additionally, we introduce a versatile and interpretable measure
for comparing LLM judges. To demonstrate our procedure, we curated a diverse
collection of ten datasets, consisting of language and vision-language tasks,
and conducted experiments with six LLMs and four prompting techniques. Our
results show that LLMs can sometimes replace humans with closed-source LLMs
(such as GPT-4o), outperforming open-source LLMs, and that prompting techniques
yield judges of varying quality. We hope this study encourages more rigorous
and reliable practices.
