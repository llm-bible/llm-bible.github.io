---
layout: publication
title: 'Few Shot Chain-of-thought Driven Reasoning To Prompt Llms For Open Ended Medical Question Answering'
authors: Saeel Sandeep Nachane, Ojas Gramopadhye, Prateek Chanda, Ganesh Ramakrishnan, Kshitij Sharad Jadhav, Yatin Nandwani, Dinesh Raghu, Sachindra Joshi
conference: "Arxiv"
year: 2024
bibkey: nachane2024few
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.04890"}
tags: ['Prompting', 'Applications', 'Reinforcement Learning']
---
In this paper, we propose a modified version of the MedQA-USMLE dataset,
named MEDQA-OPEN, which contains open-ended medical questions without options
to mimic clinical scenarios, along with clinician-approved reasoned answers.
Additionally, we implement a prompt driven by Chain of Thought (CoT) reasoning,
CLINICR, to mirror the prospective process of incremental reasoning, reaching a
correct response to medical questions. We empirically demonstrate how CLINICR
outperforms the state-of-the-art 5-shot CoT-based prompt (Li\'evin et al.,
2022). We also present an approach that mirrors real-life clinical practice by
first exploring multiple differential diagnoses through MCQ-CLINICR and
subsequently narrowing down to a final diagnosis using MCQ-ELIMINATIVE.
Finally, emphasizing the importance of response verification in medical
settings, we utilize a reward model mechanism, replacing the elimination
process performed by MCQ-ELIMINATIVE.
