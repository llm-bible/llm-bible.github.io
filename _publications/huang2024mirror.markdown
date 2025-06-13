---
layout: publication
title: 'Mirror-consistency: Harnessing Inconsistency In Majority Voting'
authors: Siyuan Huang, Zhiyuan Ma, Jintao Du, Changhua Meng, Weiqiang Wang, Zhouhan Lin
conference: "Arxiv"
year: 2024
bibkey: huang2024mirror
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.10857"}
tags: ['Reinforcement Learning']
---
Self-Consistency, a widely-used decoding strategy, significantly boosts the
reasoning capabilities of Large Language Models (LLMs). However, it depends on
the plurality voting rule, which focuses on the most frequent answer while
overlooking all other minority responses. These inconsistent minority views
often illuminate areas of uncertainty within the model's generation process. To
address this limitation, we present Mirror-Consistency, an enhancement of the
standard Self-Consistency approach. Our method incorporates a 'reflective
mirror' into the self-ensemble decoding process and enables LLMs to critically
examine inconsistencies among multiple generations. Additionally, just as
humans use the mirror to better understand themselves, we propose using
Mirror-Consistency to enhance the sample-based confidence calibration methods,
which helps to mitigate issues of overconfidence. Our experimental results
demonstrate that Mirror-Consistency yields superior performance in both
reasoning accuracy and confidence calibration compared to Self-Consistency.
