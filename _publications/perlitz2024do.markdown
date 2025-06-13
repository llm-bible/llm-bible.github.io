---
layout: publication
title: 'Do These LLM Benchmarks Agree? Fixing Benchmark Evaluation With Benchbench'
authors: Yotam Perlitz, Ariel Gera, Ofir Arviv, Asaf Yehudai, Elron Bandel, Eyal Shnarch, Michal Shmueli-scheuer, Leshem Choshen
conference: "Arxiv"
year: 2024
bibkey: perlitz2024do
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.13696'}
tags: ['Reinforcement Learning', 'Security']
---
Recent advancements in Language Models (LMs) have catalyzed the creation of
multiple benchmarks, designed to assess these models' general capabilities. A
crucial task, however, is assessing the validity of the benchmarks themselves.
This is most commonly done via Benchmark Agreement Testing (BAT), where new
benchmarks are validated against established ones using some agreement metric
(e.g., rank correlation). Despite the crucial role of BAT for benchmark
builders and consumers, there are no standardized procedures for such agreement
testing. This deficiency can lead to invalid conclusions, fostering mistrust in
benchmarks and upending the ability to properly choose the appropriate
benchmark to use. By analyzing over 40 prominent benchmarks, we demonstrate how
some overlooked methodological choices can significantly influence BAT results,
potentially undermining the validity of conclusions. To address these
inconsistencies, we propose a set of best practices for BAT and demonstrate how
utilizing these methodologies greatly improves BAT robustness and validity. To
foster adoption and facilitate future research,, we introduce BenchBench, a
python package for BAT, and release the BenchBench-leaderboard, a
meta-benchmark designed to evaluate benchmarks using their peers. Our findings
underscore the necessity for standardized BAT, ensuring the robustness and
validity of benchmark evaluations in the evolving landscape of language model
research.
  BenchBench Package: github.com/IBM/BenchBench
  Leaderboard: hf.co/spaces/IBM/BenchBench
