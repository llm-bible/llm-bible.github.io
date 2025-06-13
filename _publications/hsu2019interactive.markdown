---
layout: publication
title: 'Dixit: Interactive Visual Storytelling Via Term Manipulation'
authors: Chao-chun Hsu, Yu-hua Chen, Zi-yuan Chen, Hsin-yu Lin, Ting-hao 'kenneth' Huang, Lun-wei Ku
conference: "Arxiv"
year: 2019
bibkey: hsu2019interactive
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/1903.02230'}
tags: ['Transformer', 'Model Architecture', 'Pretraining Methods']
---
In this paper, we introduce Dixit, an interactive visual storytelling system
that the user interacts with iteratively to compose a short story for a photo
sequence. The user initiates the process by uploading a sequence of photos.
Dixit first extracts text terms from each photo which describe the objects
(e.g., boy, bike) or actions (e.g., sleep) in the photo, and then allows the
user to add new terms or remove existing terms. Dixit then generates a short
story based on these terms. Behind the scenes, Dixit uses an LSTM-based model
trained on image caption data and FrameNet to distill terms from each image and
utilizes a transformer decoder to compose a context-coherent story. Users
change images or terms iteratively with Dixit to create the most ideal story.
Dixit also allows users to manually edit and rate stories. The proposed
procedure opens up possibilities for interpretable and controllable visual
storytelling, allowing users to understand the story formation rationale and to
intervene in the generation process.
