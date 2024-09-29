---
layout: publication
title: Sample Efficient Text Summarization Using A Single Pre45;trained Transformer
authors: Khandelwal Urvashi, Clark Kevin, Jurafsky Dan, Kaiser Lukasz
conference: "Arxiv"
year: 2019
bibkey: khandelwal2019sample
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1905.08836"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Language model (LM) pre45;training has resulted in impressive performance and sample efficiency on a variety of language understanding tasks. However it remains unclear how to best use pre45;trained LMs for generation tasks such as abstractive summarization particularly to enhance sample efficiency. In these sequence45;to45;sequence settings prior work has experimented with loading pre45;trained weights into the encoder and/or decoder networks but used non45;pre45;trained encoder45;decoder attention weights. We instead use a pre45;trained decoder45;only network where the same Transformer LM both encodes the source and generates the summary. This ensures that all parameters in the network including those governing attention over source states have been pre45;trained before the fine45;tuning step. Experiments on the CNN/Daily Mail dataset show that our pre45;trained Transformer LM substantially improves over pre45;trained Transformer encoder45;decoder networks in limited45;data settings. For instance it achieves 13.1 ROUGE45;2 using only 137; of the training data (~3000 examples) while pre45;trained encoder45;decoder models score 2.3 ROUGE45;2.
