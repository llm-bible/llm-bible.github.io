---
layout: publication
title: 'A Deep Generative Framework For Paraphrase Generation'
authors: Ankush Gupta, Arvind Agarwal, Prawaan Singh, Piyush Rai
conference: "Arxiv"
year: 2017
bibkey: gupta2017deep
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1709.05074"}
tags: ['Model Architecture', 'Applications', 'Tools']
---
Paraphrase generation is an important problem in NLP, especially in question
answering, information retrieval, information extraction, conversation systems,
to name a few. In this paper, we address the problem of generating paraphrases
automatically. Our proposed method is based on a combination of deep generative
models (VAE) with sequence-to-sequence models (LSTM) to generate paraphrases,
given an input sentence. Traditional VAEs when combined with recurrent neural
networks can generate free text but they are not suitable for paraphrase
generation for a given sentence. We address this problem by conditioning the
both, encoder and decoder sides of VAE, on the original sentence, so that it
can generate the given sentence's paraphrases. Unlike most existing models, our
model is simple, modular and can generate multiple paraphrases, for a given
sentence. Quantitative evaluation of the proposed method on a benchmark
paraphrase dataset demonstrates its efficacy, and its performance improvement
over the state-of-the-art methods by a significant margin, whereas qualitative
human evaluation indicate that the generated paraphrases are well-formed,
grammatically correct, and are relevant to the input sentence. Furthermore, we
evaluate our method on a newly released question paraphrase dataset, and
establish a new baseline for future research.
