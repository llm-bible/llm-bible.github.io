---
layout: publication
title: Bcamirs At Semeval-2024 Task 4 Beyond Words A Multimodal And Multilingual Exploration Of Persuasion In Memes
authors: Abaskohi Amirhossein, Dabiriaghdam Amirhossein, Wang Lele, Carenini Giuseppe
conference: "Arxiv"
year: 2024
bibkey: abaskohi2024bcamirs
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.03022"}
tags: ['BERT', 'Fine Tuning', 'GPT', 'Model Architecture', 'Multimodal Models', 'Tools']
---
Memes combining text and images frequently use metaphors to convey persuasive messages shaping public opinion. Motivated by this our team engaged in SemEval-2024 Task 4 a hierarchical multi-label classification task designed to identify rhetorical and psychological persuasion techniques embedded within memes. To tackle this problem we introduced a caption generation step to assess the modality gap and the impact of additional semantic information from images which improved our result. Our best model utilizes GPT-4 generated captions alongside meme text to fine-tune RoBERTa as the text encoder and CLIP as the image encoder. It outperforms the baseline by a large margin in all 12 subtasks. In particular it ranked in top-3 across all languages in Subtask 2a and top-4 in Subtask 2b demonstrating quantitatively strong performance. The improvement achieved by the introduced intermediate step is likely attributable to the metaphorical essence of images that challenges visual encoders. This highlights the potential for improving abstract visual semantics encoding.
