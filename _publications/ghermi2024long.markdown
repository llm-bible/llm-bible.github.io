---
layout: publication
title: 'Long Story Short: Story-level Video Understanding From 20K Short Films'
authors: Ridouane Ghermi, Xi Wang, Vicky Kalogeiton, Ivan Laptev
conference: "Arxiv"
year: 2024
bibkey: ghermi2024long
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.10221'}
tags: ['Multimodal Models', 'Applications', 'Training Techniques', 'Pretraining Methods']
---
Recent developments in vision-language models have significantly advanced
video understanding. Existing datasets and tasks, however, have notable
limitations. Most datasets are confined to short videos with limited events and
narrow narratives. For example, datasets with instructional and egocentric
videos often depict activities of one person in a single scene. Although
existing movie datasets offer richer content, they are often limited to
short-term tasks, lack publicly available videos, and frequently encounter data
leakage issues given the use of subtitles and other information about
commercial movies during LLM pretraining. To address the above limitations, we
propose Short-Films 20K (SF20K), the largest publicly available movie dataset.
SF20K is composed of 20,143 amateur films and offers long-term video tasks in
the form of multiple-choice and open-ended question answering. Our extensive
analysis of SF20K reveals minimal data leakage, emphasizes the need for
long-term reasoning, and demonstrates the strong performance of recent VLMs.
Finally, we show that instruction tuning on the SF20K-Train set substantially
improves model performance, paving the way for future progress in long-term
video understanding.
