---
layout: publication
title: 'MAIRA-2: Grounded Radiology Report Generation'
authors: Shruthi Bannur, Kenza Bouzid, Daniel C. Castro, Anton Schwaighofer, Anja Thieme, Sam Bond-taylor, Maximilian Ilse, Fernando Pérez-garcía, Valentina Salvatelli, Harshita Sharma, Felix Meissen, Mercy Ranjit, Shaury Srivastav, Julia Gong, Noel C. F. Codella, Fabian Falck, Ozan Oktay, Matthew P. Lungren, Maria Teodora Wetscherek, Javier Alvarez-valle, Stephanie L. Hyland
conference: "Arxiv"
year: 2024
bibkey: bannur2024maira
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.04449'}
tags: ['Reinforcement Learning', 'RAG', 'Multimodal Models', 'Tools']
---
Radiology reporting is a complex task requiring detailed medical image
understanding and precise language generation, for which generative multimodal
models offer a promising solution. However, to impact clinical practice, models
must achieve a high level of both verifiable performance and utility. We
augment the utility of automated report generation by incorporating
localisation of individual findings on the image - a task we call grounded
report generation - and enhance performance by incorporating realistic
reporting context as inputs. We design a novel evaluation framework (RadFact)
leveraging the logical inference capabilities of large language models (LLMs)
to quantify report correctness and completeness at the level of individual
sentences, while supporting the new task of grounded reporting. We develop
MAIRA-2, a large radiology-specific multimodal model designed to generate chest
X-ray reports with and without grounding. MAIRA-2 achieves state of the art on
existing report generation benchmarks and establishes the novel task of
grounded report generation.
