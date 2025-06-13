---
layout: publication
title: 'M2m-gen: A Multimodal Framework For Automated Background Music Generation In Japanese Manga Using Large Language Models'
authors: Megha Sharma, Muhammad Taimoor Haseeb, Gus Xia, Yoshimasa Tsuruoka
conference: "Arxiv"
year: 2024
bibkey: sharma2024multimodal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.09928"}
tags: ['GPT', 'Tools', 'Multimodal Models', 'Model Architecture']
---
This paper introduces M2M Gen, a multi modal framework for generating
background music tailored to Japanese manga. The key challenges in this task
are the lack of an available dataset or a baseline. To address these
challenges, we propose an automated music generation pipeline that produces
background music for an input manga book. Initially, we use the dialogues in a
manga to detect scene boundaries and perform emotion classification using the
characters faces within a scene. Then, we use GPT4o to translate this low level
scene information into a high level music directive. Conditioned on the scene
information and the music directive, another instance of GPT 4o generates page
level music captions to guide a text to music model. This produces music that
is aligned with the mangas evolving narrative. The effectiveness of M2M Gen is
confirmed through extensive subjective evaluations, showcasing its capability
to generate higher quality, more relevant and consistent music that complements
specific scenes when compared to our baselines.
