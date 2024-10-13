---
layout: publication
title: 'Regressive Side Effects Of Training Language Models To Mimic Student Misconceptions'
authors: Sonkar Shashank, Liu Naiming, Baraniuk Richard G.
conference: "Arxiv"
year: 2024
bibkey: sonkar2024regressive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.15156"}
tags: ['Fine Tuning', 'Training Techniques', 'Uncategorized']
---
This paper presents a novel exploration into the regressive side effects of
training Large Language Models (LLMs) to mimic student misconceptions for
personalized education. We highlight the problem that as LLMs are trained to
more accurately mimic student misconceptions, there is a compromise in the
factual integrity and reasoning ability of the models. Our work involved
training an LLM on a student-tutor dialogue dataset to predict student
responses. The results demonstrated a decrease in the model's performance
across multiple benchmark datasets, including the ARC reasoning challenge and
TruthfulQA, which evaluates the truthfulness of model's generated responses.
Furthermore, the HaluEval Dial dataset, used for hallucination detection, and
MemoTrap, a memory-based task dataset, also reported a decline in the model
accuracy. To combat these side effects, we introduced a "hallucination token"
technique. This token, appended at the beginning of each student response
during training, instructs the model to switch between mimicking student
misconceptions and providing factually accurate responses. Despite the
significant improvement across all datasets, the technique does not completely
restore the LLM's baseline performance, indicating the need for further
research in this area. This paper contributes to the ongoing discussion on the
use of LLMs for student modeling, emphasizing the need for a balance between
personalized education and factual accuracy.
