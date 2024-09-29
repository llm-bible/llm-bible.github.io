---
layout: publication
title: "Sensitivity, Performance, Robustness: Deconstructing The Effect Of Sociodemographic Prompting"
authors: Beck Tilman, Schuff Hendrik, Lauscher Anne, Gurevych Iryna
conference: "Arxiv"
year: 2023
bibkey: beck2023deconstructing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.07034"}
  - {name: "Code", url: "https://github.com/UKPLab/arxiv2023-sociodemographic-prompting"}
tags: ['Applications', 'Has Code', 'Multimodal Models', 'Prompting', 'Security', 'Survey Paper']
---
Annotators sociodemographic backgrounds (i.e. the individual compositions of their gender age educational background etc.) have a strong impact on their decisions when working on subjective NLP tasks such as toxic language detection. Often heterogeneous backgrounds result in high disagreements. To model this variation recent work has explored sociodemographic prompting a technique which steers the output of prompt-based models towards answers that humans with specific sociodemographic profiles would give. However the available NLP literature disagrees on the efficacy of this technique - it remains unclear for which tasks and scenarios it can help and the role of the individual factors in sociodemographic prompting is still unexplored. We address this research gap by presenting the largest and most comprehensive study of sociodemographic prompting today. We analyze its influence on model sensitivity performance and robustness across seven datasets and six instruction-tuned model families. We show that sociodemographic information affects model predictions and can be beneficial for improving zero-shot learning in subjective NLP tasks. However its outcomes largely vary for different model types sizes and datasets and are subject to large variance with regards to prompt formulations. Most importantly our results show that sociodemographic prompting should be used with care for sensitive applications such as toxicity annotation or when studying LLM alignment. Code and data https://github.com/UKPLab/arxiv2023-sociodemographic-prompting"
