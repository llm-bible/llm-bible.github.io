---
layout: publication
title: 'Self-judge: Selective Instruction Following With Alignment Self-evaluation'
authors: Hai Ye, Hwee Tou Ng
conference: "Arxiv"
year: 2024
bibkey: ye2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.00935"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'Distillation', 'GPT', 'Fine-Tuning']
---
Pre-trained large language models (LLMs) can be tailored to adhere to human
instructions through instruction tuning. However, due to shifts in the
distribution of test-time data, they may not always execute instructions
accurately, potentially generating factual errors or misaligned content when
acting as chat assistants. To enhance the reliability of LLMs in following
instructions, we propose the study of selective instruction following, whereby
the system declines to execute instructions if the anticipated response quality
is low. We train judge models that can predict numerical quality scores for
model responses. To address data scarcity, we introduce Self-J, a novel
self-training framework for developing judge models without needing
human-annotated quality scores. Our method leverages the model's inherent
self-evaluation capability to extract information about response quality from
labeled instruction-tuning data. It incorporates a gold reference answer to
facilitate self-evaluation and recalibrates by assessing the semantic
similarity between the response sample and the gold reference. During the
training phase, we implement self-distillation as a regularization technique to
enhance the capability of reference-free estimation. To validate alignment
evaluation on general instruction-following tasks, we collect large-scale
high-quality instructions from Hugging Face for model training and evaluation.
Extensive experiments on five open-source models show that our method
correlates much more with GPT-4 than strong baselines, e.g., supervised models
distilled from GPT-4 and GPT-3.5-turbo. Our analysis shows our model's strong
generalization across domains. Additionally, our judge models serve as good
reward models, e.g., boosting WizardLM-13B-V1.2 from 89.17 to 92.48 and from
12.03 to 15.90 in version v1 and v2 of AlpacaEval respectively using best-of-32
sampling with our judge models.
