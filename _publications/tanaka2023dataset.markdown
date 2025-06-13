---
layout: publication
title: 'Slidevqa: A Dataset For Document Visual Question Answering On Multiple Images'
authors: Ryota Tanaka, Kyosuke Nishida, Kosuke Nishida, Taku Hasegawa, Itsumi Saito, Kuniko Saito
conference: "Arxiv"
year: 2023
bibkey: tanaka2023dataset
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2301.04883"}
tags: ['Model Architecture', 'Applications', 'Attention Mechanism']
---
Visual question answering on document images that contain textual, visual,
and layout information, called document VQA, has received much attention
recently. Although many datasets have been proposed for developing document VQA
systems, most of the existing datasets focus on understanding the content
relationships within a single image and not across multiple images. In this
study, we propose a new multi-image document VQA dataset, SlideVQA, containing
2.6k+ slide decks composed of 52k+ slide images and 14.5k questions about a
slide deck. SlideVQA requires complex reasoning, including single-hop,
multi-hop, and numerical reasoning, and also provides annotated arithmetic
expressions of numerical answers for enhancing the ability of numerical
reasoning. Moreover, we developed a new end-to-end document VQA model that
treats evidence selection and question answering in a unified
sequence-to-sequence format. Experiments on SlideVQA show that our model
outperformed existing state-of-the-art QA models, but that it still has a large
gap behind human performance. We believe that our dataset will facilitate
research on document VQA.
