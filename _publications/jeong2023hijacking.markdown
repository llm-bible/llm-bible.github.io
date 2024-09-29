---
layout: publication
title: Hijacking Context In Large Multi45;modal Models
authors: Jeong Joonhyun
conference: "ICLR"
year: 2023
bibkey: jeong2023hijacking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.07553"}
tags: ['Ethics And Bias', 'GPT', 'Model Architecture', 'Prompting', 'Security']
---
Recently Large Multi45;modal Models (LMMs) have demonstrated their ability to understand the visual contents of images given the instructions regarding the images. Built upon the Large Language Models (LLMs) LMMs also inherit their abilities and characteristics such as in45;context learning where a coherent sequence of images and texts are given as the input prompt. However we identify a new limitation of off45;the45;shelf LMMs where a small fraction of incoherent images or text descriptions mislead LMMs to only generate biased output about the hijacked context not the originally intended context. To address this we propose a pre45;filtering method that removes irrelevant contexts via GPT45;4V based on its robustness towards distribution shift within the contexts. We further investigate whether replacing the hijacked visual and textual contexts with the correlated ones via GPT45;4V and text45;to45;image models can help yield coherent responses.
