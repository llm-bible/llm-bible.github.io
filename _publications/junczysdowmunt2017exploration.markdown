---
layout: publication
title: 'An Exploration Of Neural Sequence-to-sequence Architectures For Automatic Post-editing'
authors: Junczys-dowmunt Marcin, Grundkiewicz Roman
conference: "Arxiv"
year: 2017
bibkey: junczysdowmunt2017exploration
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1706.04138"}
tags: ['Applications', 'Attention Mechanism', 'Fine Tuning', 'Model Architecture']
---
In this work, we explore multiple neural architectures adapted for the task of automatic post-editing of machine translation output. We focus on neural end-to-end models that combine both inputs \(mt\) (raw MT output) and \(src\) (source language input) in a single neural architecture, modeling $\\{mt, src\\} \rightarrow pe$ directly. Apart from that, we investigate the influence of hard-attention models which seem to be well-suited for monolingual tasks, as well as combinations of both ideas. We report results on data sets provided during the WMT-2016 shared task on automatic post-editing and can demonstrate that dual-attention models that incorporate all available data in the APE scenario in a single model improve on the best shared task system and on all other published results after the shared task. Dual-attention models that are combined with hard attention remain competitive despite applying fewer changes to the input.
