---
layout: publication
title: Medalign: A Clinician-generated Dataset For Instruction Following With Electronic Medical Records
authors: Fleming Scott L., Lozano Alejandro, Haberkorn William J., Jindal Jenelle A., Reis Eduardo P., Thapa Rahul, Blankemeier Louis, Genkins Julian Z., Steinberg Ethan, Nayak Ashwin, Patel Birju S., Chiang Chia-chun, Callahan Alison, Huo Zepeng, Gatidis Sergios, Adams Scott J., Fayanju Oluseyi, Shah Shreya J., Savage Thomas, Goh Ethan, Chaudhari Akshay S., Aghaeepour Nima, Sharp Christopher, Pfeffer Michael A., Liang Percy, Chen Jonathan H., Morse Keith E., Brunskill Emma P., Fries Jason A., Shah Nigam H.
conference: "Arxiv"
year: 2023
bibkey: fleming2023clinician
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.14089"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Model Architecture', 'Reinforcement Learning', 'Survey Paper']
---
The ability of large language models (LLMs) to follow natural language instructions with human-level fluency suggests many opportunities in healthcare to reduce administrative burden and improve quality of care. However evaluating LLMs on realistic text generation tasks for healthcare remains challenging. Existing question answering datasets for electronic health record (EHR) data fail to capture the complexity of information needs and documentation burdens experienced by clinicians. To address these challenges we introduce MedAlign a benchmark dataset of 983 natural language instructions for EHR data. MedAlign is curated by 15 clinicians (7 specialities) includes clinician-written reference responses for 303 instructions and provides 276 longitudinal EHRs for grounding instruction-response pairs. We used MedAlign to evaluate 6 general domain LLMs having clinicians rank the accuracy and quality of each LLM response. We found high error rates ranging from 3537; (GPT-4) to 6837; (MPT-7B-Instruct) and an 8.337; drop in accuracy moving from 32k to 2k context lengths for GPT-4. Finally we report correlations between clinician rankings and automated natural language generation metrics as a way to rank LLMs without human review. We make MedAlign available under a research data use agreement to enable LLM evaluations on tasks aligned with clinician needs and preferences.
