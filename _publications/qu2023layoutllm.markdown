---
layout: publication
title: Layoutllm45;t2i Eliciting Layout Guidance From LLM For Text45;to45;image Generation
authors: Qu Leigang, Wu Shengqiong, Fei Hao, Nie Liqiang, Chua Tat-seng
conference: "Arxiv"
year: 2023
bibkey: qu2023layoutllm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.05095"}
  - {name: "Code", url: "https://layoutllm&#45;t2i.github.io"}
tags: ['Applications', 'Has Code', 'Merging', 'Prompting']
---
In the text45;to45;image generation field recent remarkable progress in Stable Diffusion makes it possible to generate rich kinds of novel photorealistic images. However current models still face misalignment issues (e.g. problematic spatial relation understanding and numeration failure) in complex natural scenes which impedes the high45;faithfulness text45;to45;image generation. Although recent efforts have been made to improve controllability by giving fine45;grained guidance (e.g. sketch and scribbles) this issue has not been fundamentally tackled since users have to provide such guidance information manually. In this work we strive to synthesize high45;fidelity images that are semantically aligned with a given textual prompt without any guidance. Toward this end we propose a coarse45;to45;fine paradigm to achieve layout planning and image generation. Concretely we first generate the coarse45;grained layout conditioned on a given textual prompt via in45;context learning based on Large Language Models. Afterward we propose a fine45;grained object45;interaction diffusion method to synthesize high45;faithfulness images conditioned on the prompt and the automatically generated layout. Extensive experiments demonstrate that our proposed method outperforms the state45;of45;the45;art models in terms of layout and image generation. Our code and settings are available at https://layoutllm&#45;t2i.github.io.
