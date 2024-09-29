---
layout: publication
title: Is Context Helpful For Chat Translation Evaluation?
authors: Agrawal Sweta, Farajian Amin, Fernandes Patrick, Rei Ricardo, Martins André F. T.
conference: "Arxiv"
year: 2024
bibkey: agrawal2024is
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.08314"}
tags: ['Ethics And Bias']
---
Despite the recent success of automatic metrics for assessing translation quality their application in evaluating the quality of machine-translated chats has been limited. Unlike more structured texts like news chat conversations are often unstructured short and heavily reliant on contextual information. This poses questions about the reliability of existing sentence-level metrics in this domain as well as the role of context in assessing the translation quality. Motivated by this we conduct a meta-evaluation of existing sentence-level automatic metrics primarily designed for structured domains such as news to assess the quality of machine-translated chats. We find that reference-free metrics lag behind reference-based ones especially when evaluating translation quality in out-of-English settings. We then investigate how incorporating conversational contextual information in these metrics affects their performance. Our findings show that augmenting neural learned metrics with contextual information helps improve correlation with human judgments in the reference-free scenario and when evaluating translations in out-of-English settings. Finally we propose a new evaluation metric Context-MQM that utilizes bilingual context with a large language model (LLM) and further validate that adding context helps even for LLM-based evaluation metrics.
