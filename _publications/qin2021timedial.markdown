---
layout: publication
title: TIMEDIAL Temporal Commonsense Reasoning In Dialog
authors: Qin Lianhui, Gupta Aditya, Upadhyay Shyam, He Luheng, Choi Yejin, Faruqui Manaal
conference: "Arxiv"
year: 2021
bibkey: qin2021timedial
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2106.04571"}
  - {name: "Code", url: "https://github.com/google-research-datasets/timedial"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods']
---
Everyday conversations require understanding everyday events which in turn requires understanding temporal commonsense concepts interwoven with those events. Despite recent progress with massive pre-trained language models (LMs) such as T5 and GPT-3 their capability of temporal reasoning in dialogs remains largely under-explored. In this paper we present the first study to investigate pre-trained LMs for their temporal reasoning capabilities in dialogs by introducing a new task and a crowd-sourced English challenge set TIMEDIAL. We formulate TIME-DIAL as a multiple-choice cloze task with over 1.1K carefully curated dialogs. Empirical results demonstrate that even the best performing models struggle on this task compared to humans with 23 absolute points of gap in accuracy. Furthermore our analysis reveals that the models fail to reason about dialog context correctly; instead they rely on shallow cues based on existing temporal patterns in context motivating future research for modeling temporal concepts in text and robust contextual reasoning about them. The dataset is publicly available at https://github.com/google-research-datasets/timedial.
