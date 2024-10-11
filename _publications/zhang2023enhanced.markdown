---
layout: publication
title: 'Llavar: Enhanced Visual Instruction Tuning For Text-rich Image Understanding'
authors: Zhang Yanzhe, Zhang Ruiyi, Gu Jiuxiang, Zhou Yufan, Lipka Nedim, Yang Diyi, Sun Tong
conference: "Arxiv"
year: 2023
bibkey: zhang2023enhanced
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.17107"}
  - {name: "Code", url: "https://llavar.github.io/"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Tools', 'Uncategorized']
---
Instruction tuning unlocks the superior capability of Large Language Models (LLM) to interact with humans. Furthermore, recent instruction-following datasets include images as visual inputs, collecting responses for image-based instructions. However, visual instruction-tuned models cannot comprehend textual details within images well. This work enhances the current visual instruction tuning pipeline with text-rich images (e.g., movie posters, book covers, etc.). Specifically, we first use publicly available OCR tools to collect results on 422K text-rich images from the LAION dataset. Moreover, we prompt text-only GPT-4 with recognized texts and image captions to generate 16K conversations, each containing question-answer pairs for text-rich images. By combining our collected data with previous multi-modal instruction-following data, our model, LLaVAR, substantially improves the LLaVA model's capability on text-based VQA datasets (up to 20&#37; accuracy improvement) while achieving an accuracy of 91.42&#37; on ScienceQA. The GPT-4-based instruction-following evaluation also demonstrates the improvement of our model on both natural images and text-rich images. Through qualitative analysis, LLaVAR shows promising interaction (e.g., reasoning, writing, and elaboration) skills with humans based on the latest real-world online content that combines text and images. We make our code/data/models publicly available at https://llavar.github.io/.
