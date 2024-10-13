---
layout: publication
title: 'Cinepile: A Long Video Question Answering Dataset And Benchmark'
authors: Rawal Ruchit, Saifullah Khalid, Basri Ronen, Jacobs David, Somepalli Gowthami, Goldstein Tom
conference: "Arxiv"
year: 2024
bibkey: rawal2024long
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.08813"}
tags: ['Applications', 'Multimodal Models']
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
scene. Additionally, we evaluate recent video-centric LLMs, both open-source
and proprietary, on the test split of our dataset. The findings reveal that
even state-of-the-art video-centric LLMs significantly lag behind human
performance in these tasks, highlighting the complexity and challenge inherent
in video understanding. The dataset is available at
https://hf.co/datasets/tomg-group-umd/cinepile
