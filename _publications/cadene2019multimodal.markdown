---
layout: publication
title: 'MUREL: Multimodal Relational Reasoning For Visual Question Answering'
authors: Remi Cadene, Hedi Ben-younes, Matthieu Cord, Nicolas Thome
conference: Arxiv
year: 2019
citations: 200
bibkey: cadene2019multimodal
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1902.09487'}, {name: Code,
    url: 'https://github.com/Cadene/murel.bootstrap.pytorch'}]
tags: [Multimodal Models, RAG]
---
Multimodal attentional networks are currently state-of-the-art models for
Visual Question Answering (VQA) tasks involving real images. Although attention
allows to focus on the visual content relevant to the question, this simple
mechanism is arguably insufficient to model complex reasoning features required
for VQA or other high-level tasks.
  In this paper, we propose MuRel, a multimodal relational network which is
learned end-to-end to reason over real images. Our first contribution is the
introduction of the MuRel cell, an atomic reasoning primitive representing
interactions between question and image regions by a rich vectorial
representation, and modeling region relations with pairwise combinations.
Secondly, we incorporate the cell into a full MuRel network, which
progressively refines visual and question interactions, and can be leveraged to
define visualization schemes finer than mere attention maps.
  We validate the relevance of our approach with various ablation studies, and
show its superiority to attention-based methods on three datasets: VQA 2.0,
VQA-CP v2 and TDIUC. Our final MuRel network is competitive to or outperforms
state-of-the-art results in this challenging context.
  Our code is available: https://github.com/Cadene/murel.bootstrap.pytorch