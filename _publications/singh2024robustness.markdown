---
layout: publication
title: 'Robustness Of Llms To Perturbations In Text'
authors: Ayush Singh, Navpreet Singh, Shubham Vatsal
conference: "Arxiv"
year: 2024
bibkey: singh2024robustness
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.08989"}
tags: ['Model Architecture', 'Reinforcement Learning', 'Security', 'BERT', 'Prompting']
---
Having a clean dataset has been the foundational assumption of most natural
language processing (NLP) systems. However, properly written text is rarely
found in real-world scenarios and hence, oftentimes invalidates the
aforementioned foundational assumption. Recently, Large language models (LLMs)
have shown impressive performance, but can they handle the inevitable noise in
real-world data? This work tackles this critical question by investigating
LLMs' resilience against morphological variations in text. To that end, we
artificially introduce varying levels of noise into a diverse set of datasets
and systematically evaluate LLMs' robustness against the corrupt variations of
the original text. Our findings show that contrary to popular beliefs,
generative LLMs are quiet robust to noisy perturbations in text. This is a
departure from pre-trained models like BERT or RoBERTa whose performance has
been shown to be sensitive to deteriorating noisy text. Additionally, we test
LLMs' resilience on multiple real-world benchmarks that closely mimic commonly
found errors in the wild. With minimal prompting, LLMs achieve a new
state-of-the-art on the benchmark tasks of Grammar Error Correction (GEC) and
Lexical Semantic Change (LSC). To empower future research, we also release a
dataset annotated by humans stating their preference for LLM vs.
human-corrected outputs along with the code to reproduce our results.
