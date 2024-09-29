---
layout: publication
title: A Stitch In Time Saves Nine&#58; Detecting And Mitigating Hallucinations Of Llms By Validating Low-confidence Generation
authors: Varshney Neeraj, Yao Wenlin, Zhang Hongming, Chen Jianshu, Yu Dong
conference: "Arxiv"
year: 2023
bibkey: varshney2023stitch
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.03987"}
tags: ['Applications', 'GPT', 'Model Architecture', 'RAG', 'Reinforcement Learning']
---
Recently developed large language models have achieved remarkable success in generating fluent and coherent text. However these models often tend to hallucinate which critically hampers their reliability. In this work we address this crucial problem and propose an approach that actively detects and mitigates hallucinations during the generation process. Specifically we first identify the candidates of potential hallucination leveraging the models logit output values check their correctness through a validation procedure mitigate the detected hallucinations and then continue with the generation process. Through extensive experiments with GPT-3.5 (text-davinci-003) on the article generation task we first demonstrate the individual efficacy of our detection and mitigation techniques. Specifically the detection technique achieves a recall of ~8837; and the mitigation technique successfully mitigates 57.637; of the correctly detected hallucinations. Importantly our mitigation technique does not introduce new hallucinations even in the case of incorrectly detected hallucinations i.e. false positives. Then we show that the proposed active detection and mitigation approach successfully reduces the hallucinations of the GPT-3.5 model from 47.537; to 14.537; on average. We further demonstrate the effectiveness and wide applicability of our approach through additional studies including performance on different types of questions (multi-hop and false premise questions) and with another LLM from a different model family (Vicuna). In summary our work contributes to improving the reliability and trustworthiness of large language models a crucial step en route to enabling their widespread adoption in real-world applications.
