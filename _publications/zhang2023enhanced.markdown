---
layout: publication
title: Llavar Enhanced Visual Instruction Tuning For Text45;rich Image Understanding
authors: Zhang Yanzhe, Zhang Ruiyi, Gu Jiuxiang, Zhou Yufan, Lipka Nedim, Yang Diyi, Sun Tong
conference: "Arxiv"
year: 2023
bibkey: zhang2023enhanced
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.17107"}
  - {name: "Code", url: "https://llavar.github.io/"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools']
---
Instruction tuning unlocks the superior capability of Large Language Models (LLM) to interact with humans. Furthermore recent instruction45;following datasets include images as visual inputs collecting responses for image45;based instructions. However visual instruction45;tuned models cannot comprehend textual details within images well. This work enhances the current visual instruction tuning pipeline with text45;rich images (e.g. movie posters book covers etc.). Specifically we first use publicly available OCR tools to collect results on 422K text45;rich images from the LAION dataset. Moreover we prompt text45;only GPT45;4 with recognized texts and image captions to generate 16K conversations each containing question45;answer pairs for text45;rich images. By combining our collected data with previous multi45;modal instruction45;following data our model LLaVAR substantially improves the LLaVA models capability on text45;based VQA datasets (up to 2037; accuracy improvement) while achieving an accuracy of 91.4237; on ScienceQA. The GPT45;445;based instruction45;following evaluation also demonstrates the improvement of our model on both natural images and text45;rich images. Through qualitative analysis LLaVAR shows promising interaction (e.g. reasoning writing and elaboration) skills with humans based on the latest real45;world online content that combines text and images. We make our code/data/models publicly available at https://llavar.github.io/.
