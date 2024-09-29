---
layout: publication
title: On Context Utilization in Summarization with Large Language Models
authors: Ravaut Mathieu, Sun Aixin, Chen Nancy F., Joty Shafiq
conference: "Arxiv"
year: 2023
bibkey: ravaut2023context
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.10570"}
  - {name: "Code", url: "https://github.com/ntunlp/MiddleSum"}
tags: ['Applications', 'Ethics And Bias', 'Has Code', 'Reinforcement Learning', 'Survey Paper']
---
Large language models (LLMs) excel in abstractive summarization tasks delivering fluent and pertinent summaries. Recent advancements have extended their capabilities to handle long-input contexts exceeding 100k tokens. However in question answering language models exhibit uneven utilization of their input context. They tend to favor the initial and final segments resulting in a U-shaped performance pattern concerning where the answer is located within the input. This bias raises concerns particularly in summarization where crucial content may be dispersed throughout the source document(s). Besides in summarization mapping facts from the source to the summary is not trivial as salient content is usually re-phrased. In this paper we conduct the first comprehensive study on context utilization and position bias in summarization. Our analysis encompasses 6 LLMs 10 datasets and 5 evaluation metrics. We introduce a new evaluation benchmark called MiddleSum on the which we benchmark two alternative inference methods to alleviate position bias hierarchical summarization and incremental summarization. Our code and data can be found here https://github.com/ntunlp/MiddleSum.
