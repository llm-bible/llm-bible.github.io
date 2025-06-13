---
layout: publication
title: 'Cinepile: A Long Video Question Answering Dataset And Benchmark'
authors: Ruchit Rawal, Khalid Saifullah, Miquel Farré, Ronen Basri, David Jacobs, Gowthami Somepalli, Tom Goldstein
conference: "Arxiv"
year: 2024
bibkey: rawal2024long
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.08813"}
tags: ['Fine-Tuning', 'Applications', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models']
---
Current datasets for long-form video understanding often fall short of
providing genuine long-form comprehension challenges, as many tasks derived
from these datasets can be successfully tackled by analyzing just one or a few
random frames from a video. To address this issue, we present a novel dataset
and benchmark, CinePile, specifically designed for authentic long-form video
understanding. This paper details our innovative approach for creating a
question-answer dataset, utilizing advanced LLMs with human-in-the-loop and
building upon human-generated raw data. Our comprehensive dataset comprises
305,000 multiple-choice questions (MCQs), covering various visual and
multimodal aspects, including temporal comprehension, understanding
human-object interactions, and reasoning about events or actions within a
scene. Additionally, we fine-tuned open-source Video-LLMs on the training split
and evaluated both open-source and proprietary video-centric LLMs on the test
split of our dataset. The findings indicate that although current models
underperform compared to humans, fine-tuning these models can lead to
significant improvements in their performance.
