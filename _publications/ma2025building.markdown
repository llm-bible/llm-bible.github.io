---
layout: publication
title: 'Building Instruction-tuning Datasets From Human-written Instructions With Open-weight Large Language Models'
authors: Youmi Ma, Sakae Mizuki, Kazuki Fujii, Taishi Nakamura, Masanari Ohi, Hinari Shimada, Taihei Shiotani, Koshiro Saito, Koki Maeda, Kakeru Hattori, Takumi Okamoto, Shigeki Ishida, Rio Yokota, Hiroya Takamura, Naoaki Okazaki
conference: "Arxiv"
year: 2025
bibkey: ma2025building
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.23714"}
tags: ['Applications', 'Fine-Tuning', 'Reinforcement Learning']
---
Instruction tuning is crucial for enabling Large Language Models (LLMs) to
solve real-world tasks. Prior work has shown the effectiveness of
instruction-tuning data synthesized solely from LLMs, raising a fundamental
question: Do we still need human-originated signals for instruction tuning?
This work answers the question affirmatively: we build state-of-the-art
instruction-tuning datasets sourced from human-written instructions, by simply
pairing them with LLM-generated responses. LLMs fine-tuned on our datasets
consistently outperform those fine-tuned on existing ones. Our data
construction approach can be easily adapted to other languages; we build
datasets for Japanese and confirm that LLMs tuned with our data reach
state-of-the-art performance. Analyses suggest that instruction-tuning in a new
language allows LLMs to follow instructions, while the tuned models exhibit a
notable lack of culture-specific knowledge in that language. The datasets and
fine-tuned models will be publicly available. Our datasets, synthesized with
open-weight LLMs, are openly distributed under permissive licenses, allowing
for diverse use cases.
