---
layout: publication
title: 'Can Performant Llms Be Ethical? Quantifying The Impact Of Web Crawling Opt-outs'
authors: Dongyang Fan, Vinko Sabolčec, Matin Ansaripour, Ayush Kumar Tarun, Martin Jaggi, Antoine Bosselut, Imanol Schlag
conference: "Arxiv"
year: 2025
bibkey: fan2025can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.06219"}
tags: ['Training Techniques', 'Pretraining Methods']
---
The increasing adoption of web crawling opt-outs by copyright holders of
online content raises critical questions about the impact of data compliance on
large language model (LLM) performance. However, little is known about how
these restrictions (and the resultant filtering of pretraining datasets) affect
the capabilities of models trained using these corpora. In this work, we
conceptualize this effect as the \\(\textit\{data compliance gap\}\\) (DCG), which
quantifies the performance difference between models trained on datasets that
comply with web crawling opt-outs, and those that do not. We measure the data
compliance gap in two settings: pretraining models from scratch and continual
pretraining from existing compliant models (simulating a setting where
copyrighted data could be integrated later in pretraining). Our experiments
with 1.5B models show that, as of January 2025, compliance with web data
opt-outs does not degrade general knowledge acquisition (close to 0% DCG).
However, in specialized domains such as biomedical research, excluding major
publishers leads to performance declines. These findings suggest that while
general-purpose LLMs can be trained to perform equally well using fully open
data, performance in specialized domains may benefit from access to
high-quality copyrighted sources later in training. Our study provides
empirical insights into the long-debated trade-off between data compliance and
downstream model performance, informing future discussions on AI training
practices and policy decisions.
