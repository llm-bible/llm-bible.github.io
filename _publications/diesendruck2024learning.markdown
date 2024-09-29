---
layout: publication
title: Learning How To Ask Cycle45;consistency Refines Prompts In Multimodal Foundation Models
authors: Diesendruck Maurice, Lin Jianzhe, Imani Shima, Mahalingam Gayathri, Xu Mingyang, Zhao Jie
conference: "Arxiv"
year: 2024
bibkey: diesendruck2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.08756"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Multimodal Models', 'Prompting', 'Tools', 'Training Techniques']
---
When LLMs perform zero45;shot inference they typically use a prompt with a task specification and generate a completion. However there is no work to explore the possibility of the reverse 45; going from completion to task specification. In this paper we employ both directions to perform cycle45;supervised learning entirely in45;context. Our goal is to create a forward map f X 45; Y (e.g. image 45; generated caption) coupled with a backward map g Y 45; X (e.g. caption 45; generated image) to construct a cycle45;consistency loss (formulated as an update to the prompt) to enforce g(f(X)) ~= X. The technique called CyclePrompt uses cycle45;consistency as a free supervisory signal to iteratively craft the prompt. Importantly CyclePrompt reinforces model performance without expensive fine45;tuning without training data and without the complexity of external environments (e.g. compilers APIs). We demonstrate CyclePrompt in two domains code generation and image captioning. Our results on the HumanEval coding benchmark put us in first place on the leaderboard among models that do not rely on extra training data or usage of external environments and third overall. Compared to the GPT4 baseline we improve accuracy from 80.537; to 87.237;. In the vision45;language space we generate detailed image captions which outperform baseline zero45;shot GPT4V captions when tested against natural (VQAv2) and diagrammatic (FigureQA) visual question45;answering benchmarks. To the best of our knowledge this is the first use of self45;supervised learning for prompting.
