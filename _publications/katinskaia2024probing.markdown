---
layout: publication
title: 'Probing The Category Of Verbal Aspect In Transformer Language Models'
authors: Anisia Katinskaia, Roman Yangarber
conference: "Arxiv"
year: 2024
bibkey: katinskaia2024probing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.02335"}
tags: ['Fine-Tuning', 'Transformer', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'BERT']
---
We investigate how pretrained language models (PLM) encode the grammatical
category of verbal aspect in Russian. Encoding of aspect in transformer LMs has
not been studied previously in any language. A particular challenge is posed by
"alternative contexts": where either the perfective or the imperfective aspect
is suitable grammatically and semantically. We perform probing using BERT and
RoBERTa on alternative and non-alternative contexts. First, we assess the
models' performance on aspect prediction, via behavioral probing. Next, we
examine the models' performance when their contextual representations are
substituted with counterfactual representations, via causal probing. These
counterfactuals alter the value of the "boundedness" feature--a semantic
feature, which characterizes the action in the context. Experiments show that
BERT and RoBERTa do encode aspect--mostly in their final layers. The
counterfactual interventions affect perfective and imperfective in opposite
ways, which is consistent with grammar: perfective is positively affected by
adding the meaning of boundedness, and vice versa. The practical implications
of our probing results are that fine-tuning only the last layers of BERT on
predicting aspect is faster and more effective than fine-tuning the whole
model. The model has high predictive uncertainty about aspect in alternative
contexts, which tend to lack explicit hints about the boundedness of the
described action.
