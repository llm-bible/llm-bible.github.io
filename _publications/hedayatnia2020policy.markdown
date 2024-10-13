---
layout: publication
title: 'Policy-driven Neural Response Generation For Knowledge-grounded Dialogue Systems'
authors: Hedayatnia Behnam, Gopalakrishnan Karthik, Kim Seokhwan, Liu Yang, Eric Mihail, Hakkani-tur Dilek
conference: "Arxiv"
year: 2020
bibkey: hedayatnia2020policy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2005.12529"}
tags: ['Applications']
---
Open-domain dialogue systems aim to generate relevant, informative and
engaging responses. Seq2seq neural response generation approaches do not have
explicit mechanisms to control the content or style of the generated response,
and frequently result in uninformative utterances. In this paper, we propose
using a dialogue policy to plan the content and style of target responses in
the form of an action plan, which includes knowledge sentences related to the
dialogue context, targeted dialogue acts, topic information, etc. The
attributes within the action plan are obtained by automatically annotating the
publicly released Topical-Chat dataset. We condition neural response generators
on the action plan which is then realized as target utterances at the turn and
sentence levels. We also investigate different dialogue policy models to
predict an action plan given the dialogue context. Through automated and human
evaluation, we measure the appropriateness of the generated responses and check
if the generation models indeed learn to realize the given action plans. We
demonstrate that a basic dialogue policy that operates at the sentence level
generates better responses in comparison to turn level generation as well as
baseline models with no action plan. Additionally the basic dialogue policy has
the added effect of controllability.
