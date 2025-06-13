---
layout: publication
title: 'Targeted Visual Prompting For Medical Visual Question Answering'
authors: Sergio Tascon-morales, Pablo Márquez-neila, Raphael Sznitman
conference: "Arxiv"
year: 2024
bibkey: tasconmorales2024targeted
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.03043"}
  - {name: "Code", url: "https://github.com/sergiotasconmorales/locvqallm"}
tags: ['Multimodal Models', 'Model Architecture', 'Tools', 'Merging', 'Has Code', 'Prompting', 'Applications']
---
With growing interest in recent years, medical visual question answering
(Med-VQA) has rapidly evolved, with multimodal large language models (MLLMs)
emerging as an alternative to classical model architectures. Specifically,
their ability to add visual information to the input of pre-trained LLMs brings
new capabilities for image interpretation. However, simple visual errors cast
doubt on the actual visual understanding abilities of these models. To address
this, region-based questions have been proposed as a means to assess and
enhance actual visual understanding through compositional evaluation. To
combine these two perspectives, this paper introduces targeted visual prompting
to equip MLLMs with region-based questioning capabilities. By presenting the
model with both the isolated region and the region in its context in a
customized visual prompt, we show the effectiveness of our method across
multiple datasets while comparing it to several baseline models. Our code and
data are available at https://github.com/sergiotasconmorales/locvqallm.
