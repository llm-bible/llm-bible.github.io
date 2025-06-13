---
layout: publication
title: 'Benchmark Inflation: Revealing LLM Performance Gaps Using Retro-holdouts'
authors: Jacob Haimes, Cenny Wenner, Kunvar Thaman, Vassil Tashev, Clement Neo, Esben Kran, Jason Schreiber
conference: "Arxiv"
year: 2024
bibkey: haimes2024benchmark
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.09247'}
tags: ['Training Techniques']
---
The training data for many Large Language Models (LLMs) is contaminated with
test data. This means that public benchmarks used to assess LLMs are
compromised, suggesting a performance gap between benchmark scores and actual
capabilities. Ideally, a private holdout set could be used to accurately verify
scores. Unfortunately, such datasets do not exist for most benchmarks, and
post-hoc construction of sufficiently similar datasets is non-trivial. To
address these issues, we introduce a systematic methodology for (i)
retrospectively constructing a holdout dataset for a target dataset, (ii)
demonstrating the statistical indistinguishability of this retro-holdout
dataset, and (iii) comparing LLMs on the two datasets to quantify the
performance gap due to the dataset's public availability. Applying these
methods to TruthfulQA, we construct and release Retro-Misconceptions, on which
we evaluate twenty LLMs and find that some have inflated scores by as much as
16 percentage points. Our results demonstrate that public benchmark scores do
not always accurately assess model properties, and underscore the importance of
improved data practices in the field.
