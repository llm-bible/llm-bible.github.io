---
layout: publication
title: Self45;judge Selective Instruction Following With Alignment Self45;evaluation
authors: Ye Hai, Ng Hwee Tou
conference: "Arxiv"
year: 2024
bibkey: ye2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.00935"}
tags: ['Distillation', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Pre45;trained large language models (LLMs) can be tailored to adhere to human instructions through instruction tuning. However due to shifts in the distribution of test45;time data they may not always execute instructions accurately potentially generating factual errors or misaligned content when acting as chat assistants. To enhance the reliability of LLMs in following instructions we propose the study of selective instruction following whereby the system declines to execute instructions if the anticipated response quality is low. We train judge models that can predict numerical quality scores for model responses. To address data scarcity we introduce Self45;J a novel self45;training framework for developing judge models without needing human45;annotated quality scores. Our method leverages the models inherent self45;evaluation capability to extract information about response quality from labeled instruction45;tuning data. It incorporates a gold reference answer to facilitate self45;evaluation and recalibrates by assessing the semantic similarity between the response sample and the gold reference. During the training phase we implement self45;distillation as a regularization technique to enhance the capability of reference45;free estimation. To validate alignment evaluation on general instruction45;following tasks we collect large45;scale high45;quality instructions from Hugging Face for model training and evaluation. Extensive experiments on five open45;source models show that our method correlates much more with GPT45;4 than strong baselines e.g. supervised models distilled from GPT45;4 and GPT45;3.545;turbo. Our analysis shows our models strong generalization across domains. Additionally our judge models serve as good reward models e.g. boosting WizardLM45;13B45;V1.2 from 89.17 to 92.48 and from 12.03 to 15.90 in version v1 and v2 of AlpacaEval respectively using best45;of45;32 sampling with our judge models.
