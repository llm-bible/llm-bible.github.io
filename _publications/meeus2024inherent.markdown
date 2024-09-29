---
layout: publication
title: "Inherent Challenges Of Post-hoc Membership Inference For Large Language Models"
authors: Meeus Matthieu, Jain Shubham, Rei Marek, De Montjoye Yves-alexandre
conference: "Arxiv"
year: 2024
bibkey: meeus2024inherent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.17975"}
tags: ['Pretraining Methods', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
Large Language Models (LLMs) are often trained on vast amounts of undisclosed data motivating the development of post-hoc Membership Inference Attacks (MIAs) to gain insight into their training data composition. However in this paper we identify inherent challenges in post-hoc MIA evaluation due to potential distribution shifts between collected member and non-member datasets. Using a simple bag-of-words classifier we demonstrate that datasets used in recent post-hoc MIAs suffer from significant distribution shifts in some cases achieving near-perfect distinction between members and non-members. This implies that previously reported high MIA performance may be largely attributable to these shifts rather than model memorization. We confirm that randomized controlled setups eliminate such shifts and thus enable the development and fair evaluation of new MIAs. However we note that such randomized setups are rarely available for the latest LLMs making post-hoc data collection still required to infer membership for real-world LLMs. As a potential solution we propose a Regression Discontinuity Design (RDD) approach for post-hoc data collection which substantially mitigates distribution shifts. Evaluating various MIA methods on this RDD setup yields performance barely above random guessing in stark contrast to previously reported results. Overall our findings highlight the challenges in accurately measuring LLM memorization and the need for careful experimental design in (post-hoc) membership inference tasks.
