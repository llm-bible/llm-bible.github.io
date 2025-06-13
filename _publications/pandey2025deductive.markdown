---
layout: publication
title: 'Deduce: Deductive Consistency As A Framework To Evaluate LLM Reasoning'
authors: Atharva Pandey, Kshitij Dubey, Rahul Sharma, Amit Sharma
conference: "Arxiv"
year: 2025
bibkey: pandey2025deductive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.07080"}
tags: ['Tools', 'Reinforcement Learning']
---
Despite great performance on Olympiad-level reasoning problems, frontier
large language models can still struggle on high school math when presented
with novel problems outside standard benchmarks. Going beyond final accuracy,
we propose a deductive consistency metric to analyze chain-of-thought output
from language models (LMs).Formally, deductive reasoning involves two subtasks:
understanding a set of input premises and inferring the conclusions that follow
from them. The proposed metric studies LMs' performance on these subtasks, with
the goal of explaining LMs' reasoning errors on novel problems: how well do LMs
understand input premises with increasing context lengths, and how well can
they infer conclusions over multiple reasoning hops? Since existing benchmarks
may be memorized, we develop a pipeline to evaluate LMs' deductive consistency
on novel, perturbed versions of benchmark problems. On novel grade school math
problems (GSM-8k), we find that LMs are fairly robust to increasing number of
input premises, but suffer significant accuracy decay as the number of
reasoning hops is increased. Interestingly, these errors are masked in the
original benchmark as all models achieve near 100% accuracy. As we increase the
number of solution steps using a synthetic dataset, prediction over multiple
hops still remains the major source of error compared to understanding input
premises. Other factors, such as shifts in language style or natural
propagation of early errors do not explain the trends. Our analysis provides a
new view to characterize LM reasoning -- as computations over a window of input
premises and reasoning hops -- that can provide unified evaluation across
problem domains.
