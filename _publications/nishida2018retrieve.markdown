---
layout: publication
title: 'Retrieve-and-read: Multi-task Learning Of Information Retrieval And Reading
  Comprehension'
authors: Kyosuke Nishida, Itsumi Saito, Atsushi Otsuka, Hisako Asano, Junji Tomita
conference: CIKM 2018 October 22-26 2018 Torino Italy
year: 2018
citations: 30
bibkey: nishida2018retrieve
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1808.10628'}]
tags: [RAG, Applications]
---
This study considers the task of machine reading at scale (MRS) wherein,
given a question, a system first performs the information retrieval (IR) task
of finding relevant passages in a knowledge source and then carries out the
reading comprehension (RC) task of extracting an answer span from the passages.
Previous MRS studies, in which the IR component was trained without considering
answer spans, struggled to accurately find a small number of relevant passages
from a large set of passages. In this paper, we propose a simple and effective
approach that incorporates the IR and RC tasks by using supervised multi-task
learning in order that the IR component can be trained by considering answer
spans. Experimental results on the standard benchmark, answering SQuAD
questions using the full Wikipedia as the knowledge source, showed that our
model achieved state-of-the-art performance. Moreover, we thoroughly evaluated
the individual contributions of our model components with our new Japanese
dataset and SQuAD. The results showed significant improvements in the IR task
and provided a new perspective on IR for RC: it is effective to teach which
part of the passage answers the question rather than to give only a relevance
score to the whole passage.