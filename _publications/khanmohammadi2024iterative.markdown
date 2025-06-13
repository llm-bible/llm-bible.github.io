---
layout: publication
title: 'Iterative Prompt Refinement For Radiation Oncology Symptom Extraction Using Teacher-student Large Language Models'
authors: Reza Khanmohammadi, Ahmed I Ghanem, Kyle Verdecchia, Ryan Hall, Mohamed Elshaikh, Benjamin Movsas, Hassan Bagher-ebadian, Indrin Chetty, Mohammad M. Ghassemi, Kundan Thind
conference: "Arxiv"
year: 2024
bibkey: khanmohammadi2024iterative
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2402.04075'}
tags: ['Prompting', 'GPT', 'Model Architecture']
---
This study introduces a novel teacher-student architecture utilizing Large
Language Models (LLMs) to improve prostate cancer radiotherapy symptom
extraction from clinical notes. Mixtral, the student model, initially extracts
symptoms, followed by GPT-4, the teacher model, which refines prompts based on
Mixtral's performance. This iterative process involved 294 single symptom
clinical notes across 12 symptoms, with up to 16 rounds of refinement per
epoch. Results showed significant improvements in extracting symptoms from both
single and multi-symptom notes. For 59 single symptom notes, accuracy increased
from 0.51 to 0.71, precision from 0.52 to 0.82, recall from 0.52 to 0.72, and
F1 score from 0.49 to 0.73. In 375 multi-symptom notes, accuracy rose from 0.24
to 0.43, precision from 0.6 to 0.76, recall from 0.24 to 0.43, and F1 score
from 0.20 to 0.44. These results demonstrate the effectiveness of advanced
prompt engineering in LLMs for radiation oncology use.
