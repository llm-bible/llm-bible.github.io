---
layout: publication
title: 'Quantifying And Attributing The Hallucination Of Large Language Models Via Association Analysis'
authors: Li Du, Yequan Wang, Xingrun Xing, Yiqun Ya, Xiang Li, Xin Jiang, Xuezhi Fang
conference: "Arxiv"
year: 2023
bibkey: du2023quantifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.05217"}
tags: ['Pretraining Methods', 'Training Techniques', 'Fine-Tuning']
---
Although demonstrating superb performance on various NLP tasks, large
language models (LLMs) still suffer from the hallucination problem, which
threatens the reliability of LLMs. To measure the level of hallucination of
LLMs, previous works first categorize the hallucination according to the
phenomenon similarity, then quantify the proportion that model outputs contain
hallucinatory contents. However, such hallucination rates could easily be
distorted by confounders. Moreover, such hallucination rates could not reflect
the reasons for the hallucination, as similar hallucinatory phenomena may
originate from different sources. To address these issues, we propose to
combine the hallucination level quantification and hallucination reason
investigation through an association analysis, which builds the relationship
between the hallucination rate of LLMs with a set of risk factors. In this way,
we are able to observe the hallucination level under each value of each risk
factor, examining the contribution and statistical significance of each risk
factor, meanwhile excluding the confounding effect of other factors.
Additionally, by recognizing the risk factors according to a taxonomy of model
capability, we reveal a set of potential deficiencies in commonsense
memorization, relational reasoning, and instruction following, which may
further provide guidance for the pretraining and supervised fine-tuning process
of LLMs to mitigate the hallucination.
