---
layout: publication
title: 'Controlling Hallucinations At Word Level In Data-to-text Generation'
authors: Clément Rebuffel, Marco Roberti, Laure Soulier, Geoffrey Scoutheeten, Rossella Cancelliere, Patrick Gallinari
conference: "Arxiv"
year: 2021
bibkey: rebuffel2021controlling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2102.02810"}
tags: ['Language Modeling', 'Training Techniques', 'Applications', 'RAG']
---
Data-to-Text Generation (DTG) is a subfield of Natural Language Generation
aiming at transcribing structured data in natural language descriptions. The
field has been recently boosted by the use of neural-based generators which
exhibit on one side great syntactic skills without the need of hand-crafted
pipelines; on the other side, the quality of the generated text reflects the
quality of the training data, which in realistic settings only offer
imperfectly aligned structure-text pairs. Consequently, state-of-art neural
models include misleading statements - usually called hallucinations - in their
outputs. The control of this phenomenon is today a major challenge for DTG, and
is the problem addressed in the paper.
  Previous work deal with this issue at the instance level: using an alignment
score for each table-reference pair. In contrast, we propose a finer-grained
approach, arguing that hallucinations should rather be treated at the word
level. Specifically, we propose a Multi-Branch Decoder which is able to
leverage word-level labels to learn the relevant parts of each training
instance. These labels are obtained following a simple and efficient scoring
procedure based on co-occurrence analysis and dependency parsing. Extensive
evaluations, via automated metrics and human judgment on the standard WikiBio
benchmark, show the accuracy of our alignment labels and the effectiveness of
the proposed Multi-Branch Decoder. Our model is able to reduce and control
hallucinations, while keeping fluency and coherence in generated texts. Further
experiments on a degraded version of ToTTo show that our model could be
successfully used on very noisy settings.
