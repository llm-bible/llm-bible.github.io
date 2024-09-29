---
layout: publication
title: Generating Medically-accurate Summaries Of Patient-provider Dialogue&#58; A Multi-stage Approach Using Large Language Models
authors: Nair Varun, Schumacher Elliot, Kannan Anitha
conference: "Arxiv"
year: 2023
bibkey: nair2023generating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.05982"}
tags: ['Applications', 'Few Shot', 'GPT', 'Model Architecture', 'Prompting']
---
A medical providers summary of a patient visit serves several critical purposes including clinical decision-making facilitating hand-offs between providers and as a reference for the patient. An effective summary is required to be coherent and accurately capture all the medically relevant information in the dialogue despite the complexity of patient-generated language. Even minor inaccuracies in visit summaries (for example summarizing patient does not have a fever when a fever is present) can be detrimental to the outcome of care for the patient. This paper tackles the problem of medical conversation summarization by discretizing the task into several smaller dialogue-understanding tasks that are sequentially built upon. First we identify medical entities and their affirmations within the conversation to serve as building blocks. We study dynamically constructing few-shot prompts for tasks by conditioning on relevant patient information and use GPT-3 as the backbone for our experiments. We also develop GPT-derived summarization metrics to measure performance against reference summaries quantitatively. Both our human evaluation study and metrics for medical correctness show that summaries generated using this approach are clinically accurate and outperform the baseline approach of summarizing the dialog in a zero-shot single-prompt setting.
