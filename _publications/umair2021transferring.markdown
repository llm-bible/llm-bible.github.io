---
layout: publication
title: "Transferring Semantic Knowledge Into Language Encoders"
authors: Umair Mohammad, Ferraro Francis
conference: "Arxiv"
year: 2021
bibkey: umair2021transferring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.07382"}
tags: ['Model Architecture', 'Pretraining Methods', 'Transformer']
---
We introduce semantic form mid-tuning an approach for transferring semantic knowledge from semantic meaning representations into transformer-based language encoders. In mid-tuning we learn to align the text of general sentences -- not tied to any particular inference task -- and structured semantic representations of those sentences. Our approach does not require gold annotated semantic representations. Instead it makes use of automatically generated semantic representations such as from off-the-shelf PropBank and FrameNet semantic parsers. We show that this alignment can be learned implicitly via classification or directly via triplet loss. Our method yields language encoders that demonstrate improved predictive performance across inference reading comprehension textual similarity and other semantic tasks drawn from the GLUE SuperGLUE and SentEval benchmarks. We evaluate our approach on three popular baseline models where our experimental results and analysis concludes that current pre-trained language models can further benefit from structured semantic frames with the proposed mid-tuning method as they inject additional task-agnostic knowledge to the encoder improving the generated embeddings as well as the linguistic properties of the given model as evident from improvements on a popular sentence embedding toolkit and a variety of probing tasks.
