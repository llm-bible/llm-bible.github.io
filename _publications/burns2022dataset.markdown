---
layout: publication
title: A Dataset For Interactive Vision-language Navigation With Unknown Command Feasibility
authors: Andrea Burns et al.
conference: Arxiv
year: 2022
citations: 17
bibkey: burns2022dataset
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2202.02312'}]
tags: [Agentic, Multimodal Models]
---
Vision-language navigation (VLN), in which an agent follows language
instruction in a visual environment, has been studied under the premise that
the input command is fully feasible in the environment. Yet in practice, a
request may not be possible due to language ambiguity or environment changes.
To study VLN with unknown command feasibility, we introduce a new dataset
Mobile app Tasks with Iterative Feedback (MoTIF), where the goal is to complete
a natural language command in a mobile app. Mobile apps provide a scalable
domain to study real downstream uses of VLN methods. Moreover, mobile app
commands provide instruction for interactive navigation, as they result in
action sequences with state changes via clicking, typing, or swiping. MoTIF is
the first to include feasibility annotations, containing both binary
feasibility labels and fine-grained labels for why tasks are unsatisfiable. We
further collect follow-up questions for ambiguous queries to enable research on
task uncertainty resolution. Equipped with our dataset, we propose the new
problem of feasibility prediction, in which a natural language instruction and
multimodal app environment are used to predict command feasibility. MoTIF
provides a more realistic app dataset as it contains many diverse environments,
high-level goals, and longer action sequences than prior work. We evaluate
interactive VLN methods using MoTIF, quantify the generalization ability of
current approaches to new app environments, and measure the effect of task
feasibility on navigation performance.