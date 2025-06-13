---
layout: publication
title: 'Fivl: A Framework For Improved Vision-language Alignment Through The Lens Of Training, Evaluation And Explainability'
authors: Estelle Aflalo, Gabriela Ben Melech Stan, Tiep Le, Man Luo, Shachar Rosenman, Sayak Paul, Shao-yen Tseng, Vasudev Lal
conference: "Arxiv"
year: 2024
bibkey: aflalo2024framework
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.14672"}
  - {name: "Code", url: "https://github.com/IntelLabs/fivl"}
tags: ['Tools', 'Applications', 'Interpretability and Explainability', 'Model Architecture', 'Reinforcement Learning', 'Interpretability', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Multimodal Models']
---
Large Vision Language Models (LVLMs) have achieved significant progress in
integrating visual and textual inputs for multimodal reasoning. However, a
recurring challenge is ensuring these models utilize visual information as
effectively as linguistic content when both modalities are necessary to
formulate an accurate answer. We hypothesize that hallucinations arise due to
the lack of effective visual grounding in current LVLMs. Furthermore, current
vision-language benchmarks are not specifically measuring the degree to which
the answer require the visual input. This limitation makes it challenging to
confirm that the image is truly necessary, particularly in tasks like visual
question answering. In this work, we introduce FiVL, a novel method for
constructing datasets designed to train LVLMs for enhanced visual grounding and
also evaluate their effectiveness in achieving it. We demonstrate the value of
our datasets through three approaches. First, we introduce a novel training
task based on our augmented training dataset, resulting in better performance
than the baseline. Second, we present benchmarks to assess the model's ability
to use image as substantive evidence, rather than relying solely on linguistic
priors. Finally, we identify attention heads with the strongest vision-language
alignment, enabling explainability on visual-driven hallucinations. The code is
available at https://github.com/IntelLabs/fivl.
