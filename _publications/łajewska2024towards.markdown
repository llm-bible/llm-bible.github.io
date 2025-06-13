---
layout: publication
title: 'Towards Reliable And Factual Response Generation: Detecting Unanswerable Questions In Information-seeking Conversations'
authors: Weronika Łajewska, Krisztian Balog
conference: "Arxiv"
year: 2024
bibkey: łajewska2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.11452"}
tags: ['Training Techniques']
---
Generative AI models face the challenge of hallucinations that can undermine
users' trust in such systems. We approach the problem of conversational
information seeking as a two-step process, where relevant passages in a corpus
are identified first and then summarized into a final system response. This way
we can automatically assess if the answer to the user's question is present in
the corpus. Specifically, our proposed method employs a sentence-level
classifier to detect if the answer is present, then aggregates these
predictions on the passage level, and eventually across the top-ranked passages
to arrive at a final answerability estimate. For training and evaluation, we
develop a dataset based on the TREC CAsT benchmark that includes answerability
labels on the sentence, passage, and ranking levels. We demonstrate that our
proposed method represents a strong baseline and outperforms a state-of-the-art
LLM on the answerability prediction task.
