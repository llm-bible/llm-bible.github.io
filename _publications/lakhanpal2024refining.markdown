---
layout: publication
title: 'Refining Text-to-image Generation: Towards Accurate Training-free Glyph-enhanced Image Generation'
authors: Sanyam Lakhanpal, Shivang Chopra, Vinija Jain, Aman Chadha, Man Luo
conference: "Arxiv"
year: 2024
bibkey: lakhanpal2024refining
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.16422"}
tags: ['Tools', 'Applications', 'Model Architecture', 'Merging', 'Training Techniques', 'Attention Mechanism', 'Prompting']
---
Over the past few years, Text-to-Image (T2I) generation approaches based on
diffusion models have gained significant attention. However, vanilla diffusion
models often suffer from spelling inaccuracies in the text displayed within the
generated images. The capability to generate visual text is crucial, offering
both academic interest and a wide range of practical applications. To produce
accurate visual text images, state-of-the-art techniques adopt a
glyph-controlled image generation approach, consisting of a text layout
generator followed by an image generator that is conditioned on the generated
text layout. Nevertheless, our study reveals that these models still face three
primary challenges, prompting us to develop a testbed to facilitate future
research. We introduce a benchmark, LenCom-Eval, specifically designed for
testing models' capability in generating images with Lengthy and Complex visual
text. Subsequently, we introduce a training-free framework to enhance the
two-stage generation approaches. We examine the effectiveness of our approach
on both LenCom-Eval and MARIO-Eval benchmarks and demonstrate notable
improvements across a range of evaluation metrics, including CLIPScore, OCR
precision, recall, F1 score, accuracy, and edit distance scores. For instance,
our proposed framework improves the backbone model, TextDiffuser, by more than
23% and 13.5% in terms of OCR word F1 on LenCom-Eval and MARIO-Eval,
respectively. Our work makes a unique contribution to the field by focusing on
generating images with long and rare text sequences, a niche previously
unexplored by existing literature
