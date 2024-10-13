---
layout: publication
title: 'Sparse And Dense Approaches For The Full-rank Retrieval Of Responses For Dialogues'
authors: Penha Gustavo, Hauff Claudia
conference: "Arxiv"
year: 2022
bibkey: penha2022sparse
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2204.10558"}
  - {name: "Code", url: "https://github.com/Guzpenha/transformer_rankers/tree/full_rank_retrieval_dialogues"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Ranking responses for a given dialogue context is a popular benchmark in
which the setup is to re-rank the ground-truth response over a limited set of
\\(n\\) responses, where \\(n\\) is typically 10. The predominance of this setup in
conversation response ranking has lead to a great deal of attention to building
neural re-rankers, while the first-stage retrieval step has been overlooked.
Since the correct answer is always available in the candidate list of \\(n\\)
responses, this artificial evaluation setup assumes that there is a first-stage
retrieval step which is always able to rank the correct response in its top-\\(n\\)
list. In this paper we focus on the more realistic task of full-rank retrieval
of responses, where \\(n\\) can be up to millions of responses. We investigate both
dialogue context and response expansion techniques for sparse retrieval, as
well as zero-shot and fine-tuned dense retrieval approaches. Our findings based
on three different information-seeking dialogue datasets reveal that a learned
response expansion technique is a solid baseline for sparse retrieval. We find
the best performing method overall to be dense retrieval with intermediate
training, i.e. a step after the language model pre-training where sentence
representations are learned, followed by fine-tuning on the target
conversational data. We also investigate the intriguing phenomena that harder
negatives sampling techniques lead to worse results for the fine-tuned dense
retrieval models. The code and datasets are available at
https://github.com/Guzpenha/transformer_rankers/tree/full_rank_retrieval_dialogues.
