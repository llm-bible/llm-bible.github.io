---
layout: publication
title: MEND Meta Demonstration Distillation For Efficient And Effective In45;context Learning
authors: Yichuan Li, Xiyao Ma, Sixing Lu, Kyumin Lee, Xiaohu Liu, Chenlei Guo
conference: "Arxiv"
year: 2024
bibkey: li2024meta
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2403.06914v2"}
tags: ['Attention Mechanism', 'Distillation', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Large Language models (LLMs) have demonstrated impressive in45;context learning (ICL) capabilities where a LLM makes predictions for a given test input together with a few input45;output pairs (demonstrations). Nevertheless the inclusion of demonstrations leads to a quadratic increase in the computational overhead of the self45;attention mechanism. Existing solutions attempt to distill lengthy demonstrations into compact vectors. However they often require task45;specific retraining or compromise LLMs in45;context learning performance. To mitigate these challenges we present Meta dEmonstratioN Distillation (MEND) where a language model learns to distill any lengthy demonstrations into vectors without retraining for a new downstream task. We exploit the knowledge distillation to enhance alignment between MEND and LLM achieving both efficiency and effectiveness simultaneously. MEND is endowed with the meta45;knowledge of distilling demonstrations through a two45;stage training process which includes meta45;distillation pretraining and fine45;tuning. Comprehensive evaluations across seven diverse ICL task partitions using decoder45;only (GPT45;2) and encoder45;decoder (T5) attest to MENDs prowess. It not only matches but often outperforms the Vanilla ICL as well as other state45;of45;the45;art distillation models while significantly reducing the computational demands. This innovation promises enhanced scalability and efficiency for the practical deployment of large language models
