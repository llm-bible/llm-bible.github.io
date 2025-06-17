---
layout: publication
title: Efficient Attention Mechanism For Visual Dialog That Can Handle All The Interactions
  Between Multiple Inputs
authors: Van-quang Nguyen, Masanori Suganuma, Takayuki Okatani
conference: Arxiv
year: 2019
citations: 32
bibkey: nguyen2019efficient
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.11390'}, {name: Code,
    url: 'https://github.com/davidnvq/visdial'}]
tags: [Transformer, Attention Mechanism, Tools, Model Architecture]
---
It has been a primary concern in recent studies of vision and language tasks
to design an effective attention mechanism dealing with interactions between
the two modalities. The Transformer has recently been extended and applied to
several bi-modal tasks, yielding promising results. For visual dialog, it
becomes necessary to consider interactions between three or more inputs, i.e.,
an image, a question, and a dialog history, or even its individual dialog
components. In this paper, we present a neural architecture named Light-weight
Transformer for Many Inputs (LTMI) that can efficiently deal with all the
interactions between multiple such inputs in visual dialog. It has a block
structure similar to the Transformer and employs the same design of attention
computation, whereas it has only a small number of parameters, yet has
sufficient representational power for the purpose. Assuming a standard setting
of visual dialog, a layer built upon the proposed attention block has less than
one-tenth of parameters as compared with its counterpart, a natural Transformer
extension. The experimental results on the VisDial datasets validate the
effectiveness of the proposed approach, showing improvements of the best NDCG
score on the VisDial v1.0 dataset from 57.59 to 60.92 with a single model, from
64.47 to 66.53 with ensemble models, and even to 74.88 with additional
finetuning. Our implementation code is available at
https://github.com/davidnvq/visdial.