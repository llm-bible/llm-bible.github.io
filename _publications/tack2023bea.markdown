---
layout: publication
title: "The BEA 2023 Shared Task On Generating AI Teacher Responses In Educational Dialogues"
authors: Tack Anaïs, Kochmar Ekaterina, Yuan Zheng, Bibauw Serge, Piech Chris
conference: "Arxiv"
year: 2023
bibkey: tack2023bea
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.06941"}
tags: ['Applications', 'BERT', 'GPT', 'Model Architecture', 'Prompting']
---
This paper describes the results of the first shared task on the generation of teacher responses in educational dialogues. The goal of the task was to benchmark the ability of generative language models to act as AI teachers replying to a student in a teacher-student dialogue. Eight teams participated in the competition hosted on CodaLab. They experimented with a wide variety of state-of-the-art models including Alpaca Bloom DialoGPT DistilGPT-2 Flan-T5 GPT-2 GPT-3 GPT- 4 LLaMA OPT-2.7B and T5-base. Their submissions were automatically scored using BERTScore and DialogRPT metrics and the top three among them were further manually evaluated in terms of pedagogical ability based on Tack and Piech (2022). The NAISTeacher system which ranked first in both automated and human evaluation generated responses with GPT-3.5 using an ensemble of prompts and a DialogRPT-based ranking of responses for given dialogue contexts. Despite the promising achievements of the participating teams the results also highlight the need for evaluation metrics better suited to educational contexts.
