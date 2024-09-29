---
layout: publication
title: Multiqg45;ti Towards Question Generation From Multi45;modal Sources
authors: Wang Zichao, Baraniuk Richard
conference: "Arxiv"
year: 2023
bibkey: wang2023multiqg
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.04643"}
tags: ['GPT', 'Model Architecture', 'Prompting', 'RAG']
---
We study the new problem of automatic question generation (QG) from multi45;modal sources containing images and texts significantly expanding the scope of most of the existing work that focuses exclusively on QG from only textual sources. We propose a simple solution for our new problem called MultiQG45;TI which enables a text45;only question generator to process visual input in addition to textual input. Specifically we leverage an image45;to45;text model and an optical character recognition model to obtain the textual description of the image and extract any texts in the image respectively and then feed them together with the input texts to the question generator. We only fine45;tune the question generator while keeping the other components fixed. On the challenging ScienceQA dataset we demonstrate that MultiQG45;TI significantly outperforms ChatGPT with few45;shot prompting despite having hundred45;times less trainable parameters. Additional analyses empirically confirm the necessity of both visual and textual signals for QG and show the impact of various modeling choices.
