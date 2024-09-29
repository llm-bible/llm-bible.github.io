---
layout: publication
title: Self45;icl Zero45;shot In45;context Learning With Self45;generated Demonstrations
authors: Chen Wei-lin, Wu Cheng-kuang, Chen Yun-nung, Chen Hsin-hsi
conference: "Arxiv"
year: 2023
bibkey: chen2023self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.15035"}
tags: ['Prompting', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large language models (LLMs) have exhibited striking in45;context learning (ICL) ability to adapt to target tasks with a few input45;output demonstrations. For better ICL different methods are proposed to select representative demonstrations from existing training corpora. However such settings are not aligned with real45;world practices as end45;users usually query LMs without access to demonstration pools. In this work we introduce Self45;ICL 45;45; a simple framework which bootstraps LMs intrinsic capabilities to perform zero45;shot ICL. Given a test input Self45;ICL first prompts the model to generate pseudo45;inputs. Next the model predicts pseudo45;labels for the pseudo45;inputs via zero45;shot prompting. Finally we perform ICL for the test input with the pseudo45;input45;label pairs as demonstrations. Evaluation on 23 BIG45;Bench Hard tasks shows Self45;ICL outperforms zero45;shot baselines on both average accuracy and head45;to45;head comparison. Moreover with zero45;shot chain45;of45;thought Self45;ICL achieves results comparable to using real demonstrations. Additionally we conduct a range of analyses to validate Self45;ICLs effectiveness and provide insights for its behaviors under different settings.
