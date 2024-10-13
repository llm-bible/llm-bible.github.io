---
layout: publication
title: 'Understanding Performance Of Long-document Ranking Models Through Comprehensive Evaluation And Leaderboarding'
authors: Boytsov Leonid, Akinpelu David, Lin Tianyi, Gao Fangwei, Zhao Yutian, Huang Jeffrey, Katyal Nipun, Nyberg Eric
conference: "Arxiv"
year: 2022
bibkey: boytsov2022understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2207.01262"}
tags: ['Attention Mechanism', 'Ethics And Bias', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
We evaluated 20+ Transformer models for ranking of long documents (including
recent LongP models trained with FlashAttention) and compared them with a
simple FirstP baseline, which applies the same model to the truncated input (at
most 512 tokens). We used MS MARCO Documents v1 as a primary training set and
evaluated both the zero-shot transferred and fine-tuned models.
  On MS MARCO, TREC DLs, and Robust04 no long-document model outperformed
FirstP by more than 5% in NDCG and MRR (when averaged over all test sets). We
conjectured this was not due to models' inability to process long context, but
due to a positional bias of relevant passages, whose distribution was skewed
towards the beginning of documents. We found direct evidence of this bias in
some test sets, which motivated us to create MS MARCO FarRelevant (based on MS
MARCO Passages) where the relevant passages were not present among the first
512 tokens.
  Unlike standard collections where we saw both little benefit from
incorporating longer contexts and limited variability in model performance
(within a few %), experiments on MS MARCO FarRelevant uncovered dramatic
differences among models. The FirstP models performed roughly at the
random-baseline level in both zero-shot and fine-tuning scenarios. Simple
aggregation models including MaxP and PARADE Attention had good zero-shot
accuracy, but benefited little from fine-tuning. Most other models had poor
zero-shot performance (sometimes at a random baseline level), but outstripped
MaxP by as much as 13-28% after fine-tuning. Thus, the positional bias not only
diminishes benefits of processing longer document contexts, but also leads to
model overfitting to positional bias and performing poorly in a zero-shot
setting when the distribution of relevant passages changes substantially. We
make our software and data available.
