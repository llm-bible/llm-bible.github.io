---
layout: publication
title: 'HOP: History-and-order Aware Pre-training For Vision-and-language Navigation'
authors: Yanyuan Qiao et al.
conference: Arxiv
year: 2022
citations: 24
bibkey: qiao2022history
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.11591'}]
tags: [Pre-Training, Reinforcement Learning, Agentic]
---
Pre-training has been adopted in a few of recent works for
Vision-and-Language Navigation (VLN). However, previous pre-training methods
for VLN either lack the ability to predict future actions or ignore the
trajectory contexts, which are essential for a greedy navigation process. In
this work, to promote the learning of spatio-temporal visual-textual
correspondence as well as the agent's capability of decision making, we propose
a novel history-and-order aware pre-training paradigm (HOP) with VLN-specific
objectives that exploit the past observations and support future action
prediction. Specifically, in addition to the commonly used Masked Language
Modeling (MLM) and Trajectory-Instruction Matching (TIM), we design two proxy
tasks to model temporal order information: Trajectory Order Modeling (TOM) and
Group Order Modeling (GOM). Moreover, our navigation action prediction is also
enhanced by introducing the task of Action Prediction with History (APH), which
takes into account the history visual perceptions. Extensive experimental
results on four downstream VLN tasks (R2R, REVERIE, NDH, RxR) demonstrate the
effectiveness of our proposed method compared against several state-of-the-art
agents.