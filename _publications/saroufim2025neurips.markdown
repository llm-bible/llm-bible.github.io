---
layout: publication
title: 'Neurips 2023 LLM Efficiency Fine-tuning Competition'
authors: Mark Saroufim, Yotam Perlitz, Leshem Choshen, Luca Antiga, Greg Bowyer, Christian Puhrsch, Driss Guessous, Supriya Rao, Geeta Chauhan, Ashvini Kumar, Jindal Pawan Kumar, Rajpoot Ankur Parikh, Joe Isaacson, Weiwei Yang
conference: "Arxiv"
year: 2025
bibkey: saroufim2025neurips
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.13507"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Pretraining Methods', 'Fine-Tuning', 'NeurIPS']
---
Our analysis of the NeurIPS 2023 large language model (LLM) fine-tuning
competition revealed the following trend: top-performing models exhibit
significant overfitting on benchmark datasets, mirroring the broader issue of
benchmark overfitting on popular leaderboards and that data curation is
essential in order to get a high performing LLM. The competition, which
consisted of two stages - an open evaluation stage with publicly available
tasks and a closed evaluation stage with unseen tasks - allowed us to assess
the generalizability of fine-tuned LLMs. Our results highlight the limitations
of current benchmark-based evaluation schemes for generative models and
demonstrate the need for more robust evaluation methods. Notably, the winning
submissions utilized standard open-source libraries and focused primarily on
data curation. To facilitate further research and promote reproducibility, we
release all competition entries, Docker files, and evaluation infrastructure,
providing a valuable resource for the community to explore fine-tuning,
overfitting, and reproducibility in LLMs.
