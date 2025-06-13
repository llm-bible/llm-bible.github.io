---
layout: publication
title: 'Daydreamer At Cqs-gen 2025: Generating Critical Questions Through Argument Scheme Completion'
authors: Wendi Zhou, Ameer Saadat-yazdi, Nadin Kökciyan
conference: "Arxiv"
year: 2025
bibkey: zhou2025daydreamer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.15554"}
  - {name: "Code", url: "https://git.ecdf.ed.ac.uk/s2236454/DayDreamer-CQs-Gen}{DayDreamer"}
tags: ['RAG', 'Has Code', 'Prompting']
---
Critical questions are essential resources to provoke critical thinking when encountering an argumentative text. We present our system for the Critical Questions Generation (CQs-Gen) Shared Task at ArgMining 2025. Our approach leverages large language models (LLMs) with chain-of-thought prompting to generate critical questions guided by Walton's argumentation schemes. For each input intervention, we conversationally prompt LLMs to instantiate the corresponding argument scheme template to first obtain structured arguments, and then generate relevant critical questions. Following this, we rank all the available critical questions by prompting LLMs to select the top 3 most helpful questions based on the original intervention text. This combination of structured argumentation theory and step-by-step reasoning enables the generation of contextually relevant and diverse critical questions. Our pipeline achieves competitive performance in the final test set, showing its potential to foster critical thinking given argumentative text and detect missing or uninformed claims. Code available at \href\{https://git.ecdf.ed.ac.uk/s2236454/DayDreamer-CQs-Gen\}\{DayDreamer\}.
