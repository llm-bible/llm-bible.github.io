---
layout: publication
title: 'A Role-specific Guided Large Language Model For Ophthalmic Consultation Based On Stylistic Differentiation'
authors: Fu Laiyi, Fan Binbin, Du Hongkai, Feng Yanxiang, Li Chunhua, Song Huping
conference: "Arxiv"
year: 2024
bibkey: fu2024role
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.18483"}
  - {name: "Code", url: "https://github.com/sperfu/EyeDoc"}
tags: ['Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Ophthalmology consultations are crucial for diagnosing, treating, and
preventing eye diseases. However, the growing demand for consultations exceeds
the availability of ophthalmologists. By leveraging large pre-trained language
models, we can design effective dialogues for specific scenarios, aiding in
consultations. Traditional fine-tuning strategies for question-answering tasks
are impractical due to increasing model size and often ignoring patient-doctor
role function during consultations. In this paper, we propose EyeDoctor, an
ophthalmic medical questioning large language model that enhances accuracy
through doctor-patient role perception guided and an augmented knowledge base
with external disease information. Experimental results show EyeDoctor achieves
higher question-answering precision in ophthalmology consultations. Notably,
EyeDoctor demonstrated a 7.25% improvement in Rouge-1 scores and a 10.16%
improvement in F1 scores on multi-round datasets compared to second best model
ChatGPT, highlighting the importance of doctor-patient role differentiation and
dynamic knowledge base expansion for intelligent medical consultations. EyeDoc
also serves as a free available web based service and souce code is available
at https://github.com/sperfu/EyeDoc.
