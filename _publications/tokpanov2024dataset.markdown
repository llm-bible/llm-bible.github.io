---
layout: publication
title: 'Zyda: A 1.3T Dataset For Open Language Modeling'
authors: Yury Tokpanov, Beren Millidge, Paolo Glorioso, Jonathan Pilault, Adam Ibrahim, James Whittington, Quentin Anthony
conference: "Arxiv"
year: 2024
bibkey: tokpanov2024dataset
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.01981"}
tags: ['Pretraining Methods', 'Language Modeling', 'Training Techniques', 'Tools']
---
The size of large language models (LLMs) has scaled dramatically in recent
years and their computational and data requirements have surged
correspondingly. State-of-the-art language models, even at relatively smaller
sizes, typically require training on at least a trillion tokens. This rapid
advancement has eclipsed the growth of open-source datasets available for
large-scale LLM pretraining. In this paper, we introduce Zyda (Zyphra Dataset),
a dataset under a permissive license comprising 1.3 trillion tokens, assembled
by integrating several major respected open-source datasets into a single,
high-quality corpus. We apply rigorous filtering and deduplication processes,
both within and across datasets, to maintain and enhance the quality derived
from the original datasets. Our evaluations show that Zyda not only competes
favorably with other open datasets like Dolma, FineWeb, and RefinedWeb, but
also substantially improves the performance of comparable models from the
Pythia suite. Our rigorous data processing methods significantly enhance Zyda's
effectiveness, outperforming even the best of its constituent datasets when
used independently.
