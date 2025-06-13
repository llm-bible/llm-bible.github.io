---
layout: publication
title: 'Synthetic Patient-physician Dialogue Generation From Clinical Notes Using LLM'
authors: Trisha Das, Dina Albassam, Jimeng Sun
conference: "Arxiv"
year: 2024
bibkey: das2024synthetic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.06285"}
tags: ['Prompting', 'Model Architecture', 'Applications', 'GPT']
---
Medical dialogue systems (MDS) enhance patient-physician communication,
improve healthcare accessibility, and reduce costs. However, acquiring suitable
data to train these systems poses significant challenges. Privacy concerns
prevent the use of real conversations, necessitating synthetic alternatives.
Synthetic dialogue generation from publicly available clinical notes offers a
promising solution to this issue, providing realistic data while safeguarding
privacy. Our approach, SynDial, uses a single LLM iteratively with zero-shot
prompting and a feedback loop to generate and refine high-quality synthetic
dialogues. The feedback consists of weighted evaluation scores for similarity
and extractiveness. The iterative process ensures dialogues meet predefined
thresholds, achieving superior extractiveness as a result of the feedback loop.
Additionally, evaluation shows that the generated dialogues excel in factuality
metric compared to the baselines and has comparable diversity scores with GPT4.
