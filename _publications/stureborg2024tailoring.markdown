---
layout: publication
title: 'Tailoring Vaccine Messaging With Common-ground Opinions'
authors: Rickard Stureborg, Sanxing Chen, Ruoyu Xie, Aayushi Patel, Christopher Li, Chloe Qinyu Zhu, Tingnan Hu, Jun Yang, Bhuwan Dhingra
conference: "Arxiv"
year: 2024
bibkey: stureborg2024tailoring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.10861"}
  - {name: "Code", url: "https://github.com/rickardstureborg/tailor-cgo"}
  - {name: "Code", url: "https://huggingface.co/datasets/DukeNLP/tailor-cgo"}
tags: ['Model Architecture', 'Reinforcement Learning', 'GPT', 'BERT', 'Has Code']
---
One way to personalize chatbot interactions is by establishing common ground
with the intended reader. A domain where establishing mutual understanding
could be particularly impactful is vaccine concerns and misinformation. Vaccine
interventions are forms of messaging which aim to answer concerns expressed
about vaccination. Tailoring responses in this domain is difficult, since
opinions often have seemingly little ideological overlap. We define the task of
tailoring vaccine interventions to a Common-Ground Opinion (CGO). Tailoring
responses to a CGO involves meaningfully improving the answer by relating it to
an opinion or belief the reader holds. In this paper we introduce TAILOR-CGO, a
dataset for evaluating how well responses are tailored to provided CGOs. We
benchmark several major LLMs on this task; finding GPT-4-Turbo performs
significantly better than others. We also build automatic evaluation metrics,
including an efficient and accurate BERT model that outperforms finetuned LLMs,
investigate how to successfully tailor vaccine messaging to CGOs, and provide
actionable recommendations from this investigation.
  Code and model weights: https://github.com/rickardstureborg/tailor-cgo
Dataset: https://huggingface.co/datasets/DukeNLP/tailor-cgo
