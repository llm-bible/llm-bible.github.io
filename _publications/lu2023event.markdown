---
layout: publication
title: Event Extraction As Question Generation And Answering
authors: Di Lu, Shihao Ran, Joel Tetreault, Alejandro Jaimes
conference: Arxiv
year: 2023
citations: 17
bibkey: lu2023event
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2307.05567'}]
tags: [RAG]
---
Recent work on Event Extraction has reframed the task as Question Answering
(QA), with promising results. The advantage of this approach is that it
addresses the error propagation issue found in traditional token-based
classification approaches by directly predicting event arguments without
extracting candidates first. However, the questions are typically based on
fixed templates and they rarely leverage contextual information such as
relevant arguments. In addition, prior QA-based approaches have difficulty
handling cases where there are multiple arguments for the same role. In this
paper, we propose QGA-EE, which enables a Question Generation (QG) model to
generate questions that incorporate rich contextual information instead of
using fixed templates. We also propose dynamic templates to assist the training
of QG model. Experiments show that QGA-EE outperforms all prior
single-task-based models on the ACE05 English dataset.