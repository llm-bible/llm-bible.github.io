---
layout: publication
title: 'Mitigating LLM Hallucinations Via Conformal Abstention'
authors: Yasin Abbasi Yadkori, Ilja Kuzborskij, David Stutz, András György, Adam Fisch, Arnaud Doucet, Iuliya Beloshapka, Wei-hung Weng, Yao-yuan Yang, Csaba Szepesvári, Ali Taylan Cemgil, Nenad Tomasev
conference: "Arxiv"
year: 2024
bibkey: yadkori2024mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.01563"}
tags: ['RAG', 'Applications', 'Reinforcement Learning']
---
We develop a principled procedure for determining when a large language model
(LLM) should abstain from responding (e.g., by saying "I don't know") in a
general domain, instead of resorting to possibly "hallucinating" a non-sensical
or incorrect answer. Building on earlier approaches that use self-consistency
as a more reliable measure of model confidence, we propose using the LLM itself
to self-evaluate the similarity between each of its sampled responses for a
given query. We then further leverage conformal prediction techniques to
develop an abstention procedure that benefits from rigorous theoretical
guarantees on the hallucination rate (error rate). Experimentally, our
resulting conformal abstention method reliably bounds the hallucination rate on
various closed-book, open-domain generative question answering datasets, while
also maintaining a significantly less conservative abstention rate on a dataset
with long responses (Temporal Sequences) compared to baselines using
log-probability scores to quantify uncertainty, while achieveing comparable
performance on a dataset with short answers (TriviaQA). To evaluate the
experiments automatically, one needs to determine if two responses are
equivalent given a question. Following standard practice, we use a thresholded
similarity function to determine if two responses match, but also provide a
method for calibrating the threshold based on conformal prediction, with
theoretical guarantees on the accuracy of the match prediction, which might be
of independent interest.
