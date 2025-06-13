---
layout: publication
title: 'Interaction Is All You Need? A Study Of Robots Ability To Understand And Execute'
authors: Kushal Koshti, Nidhir Bhavsar
conference: "Arxiv"
year: 2023
bibkey: koshti2023interaction
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.07150"}
tags: ['Transformer', 'Model Architecture', 'Pretraining Methods']
---
This paper aims to address a critical challenge in robotics, which is
enabling them to operate seamlessly in human environments through natural
language interactions. Our primary focus is to equip robots with the ability to
understand and execute complex instructions in coherent dialogs to facilitate
intricate task-solving scenarios. To explore this, we build upon the Execution
from Dialog History (EDH) task from the Teach benchmark. We employ a
multi-transformer model with BART LM. We observe that our best configuration
outperforms the baseline with a success rate score of 8.85 and a
goal-conditioned success rate score of 14.02. In addition, we suggest an
alternative methodology for completing this task. Moreover, we introduce a new
task by expanding the EDH task and making predictions about game plans instead
of individual actions. We have evaluated multiple BART models and an LLaMA2
LLM, which has achieved a ROGUE-L score of 46.77 for this task.
