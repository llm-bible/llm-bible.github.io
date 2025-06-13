---
layout: publication
title: 'Gersteinlab At Mediqa-chat 2023: Clinical Note Summarization From Doctor-patient Conversations Through Fine-tuning And In-context Learning'
authors: Xiangru Tang, Andrew Tran, Jeffrey Tan, Mark Gerstein
conference: "Arxiv"
year: 2023
bibkey: tang2023gersteinlab
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.05001"}
tags: ['Training Techniques', 'Model Architecture', 'Few-Shot', 'GPT', 'Pretraining Methods', 'BERT', 'Fine-Tuning', 'Prompting', 'Applications', 'In-Context Learning']
---
This paper presents our contribution to the MEDIQA-2023 Dialogue2Note shared
task, encompassing both subtask A and subtask B. We approach the task as a
dialogue summarization problem and implement two distinct pipelines: (a) a
fine-tuning of a pre-trained dialogue summarization model and GPT-3, and (b)
few-shot in-context learning (ICL) using a large language model, GPT-4. Both
methods achieve excellent results in terms of ROUGE-1 F1, BERTScore F1
(deberta-xlarge-mnli), and BLEURT, with scores of 0.4011, 0.7058, and 0.5421,
respectively. Additionally, we predict the associated section headers using
RoBERTa and SciBERT based classification models. Our team ranked fourth among
all teams, while each team is allowed to submit three runs as part of their
submission. We also utilize expert annotations to demonstrate that the notes
generated through the ICL GPT-4 are better than all other baselines. The code
for our submission is available.
