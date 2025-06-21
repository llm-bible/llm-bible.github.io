---
layout: publication
title: Jointly Optimizing Diversity And Relevance In Neural Response Generation
authors: Xiang Gao et al.
conference: Arxiv
year: 2019
citations: 18
bibkey: gao2019jointly
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1902.11205'}]
tags: [RAG]
---
Although recent neural conversation models have shown great potential, they
often generate bland and generic responses. While various approaches have been
explored to diversify the output of the conversation model, the improvement
often comes at the cost of decreased relevance. In this paper, we propose a
SpaceFusion model to jointly optimize diversity and relevance that essentially
fuses the latent space of a sequence-to-sequence model and that of an
autoencoder model by leveraging novel regularization terms. As a result, our
approach induces a latent space in which the distance and direction from the
predicted response vector roughly match the relevance and diversity,
respectively. This property also lends itself well to an intuitive
visualization of the latent space. Both automatic and human evaluation results
demonstrate that the proposed approach brings significant improvement compared
to strong baselines in both diversity and relevance.