---
layout: publication
title: 'Can NLP Models Correctly Reason Over Contexts That Break The Common Assumptions?'
authors: Neeraj Varshney, Mihir Parmar, Nisarg Patel, Divij Handa, Sayantan Sarkar, Man Luo, Chitta Baral
conference: "Arxiv"
year: 2023
bibkey: varshney2023can
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2305.12096'}
  - {name: "Code", url: 'https://github.com/nrjvarshney/break_the_common_assumptions'}
tags: ['Has Code', 'RAG', 'Training Techniques', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Pre-Training']
---
Pre-training on large corpora of text enables the language models to acquire
a vast amount of factual and commonsense knowledge which allows them to achieve
remarkable performance on a variety of language understanding tasks. They
typically acquire this knowledge by learning from the pre-training text and
capturing certain patterns from it. However, real-world settings often present
scenarios that do not abide by these patterns i.e. scenarios that break the
common assumptions. Can state-of-the-art NLP models correctly reason over the
contexts of such scenarios?
  Addressing the above question, in this paper, we investigate the ability of
models to correctly reason over contexts that break the common assumptions. To
this end, we first systematically create evaluation data in which each data
instance consists of (a) a common assumption, (b) a context that follows the
assumption, (c) a context that breaks the assumption, and (d) questions based
on the contexts. Then, through evaluations on multiple models including GPT-3
and Flan T5, we show that while doing fairly well on contexts that follow the
common assumptions, the models struggle to correctly reason over contexts that
break those assumptions. Specifically, the performance gap is as high as 20%
absolute points. Furthermore, we thoroughly analyze these results revealing
several interesting findings. We believe our work and findings will encourage
and facilitate further research in developing more robust models that can also
reliably reason over contexts that break the common assumptions. Data is
available at \url\{https://github.com/nrjvarshney/break_the_common_assumptions\}.
