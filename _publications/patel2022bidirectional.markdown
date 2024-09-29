---
layout: publication
title: Bidirectional Language Models Are Also Few45;shot Learners
authors: Patel Ajay, Li Bryan, Rasooli Mohammad Sadegh, Constant Noah, Raffel Colin, Callison-burch Chris
conference: "Arxiv"
year: 2022
bibkey: patel2022bidirectional
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2209.14500"}
tags: ['Applications', 'BERT', 'Fine Tuning', 'GPT', 'Language Modeling', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Large language models such as GPT45;3 (Brown et al. 2020) can perform arbitrary tasks without undergoing fine45;tuning after being prompted with only a few labeled examples. An arbitrary task can be reformulated as a natural language prompt and a language model can be asked to generate the completion indirectly performing the task in a paradigm known as prompt45;based learning. To date emergent prompt45;based learning capabilities have mainly been demonstrated for unidirectional language models. However bidirectional language models pre45;trained on denoising objectives such as masked language modeling produce stronger learned representations for transfer learning. This motivates the possibility of prompting bidirectional models but their pre45;training objectives have made them largely incompatible with the existing prompting paradigm. We present SAP (Sequential Autoregressive Prompting) a technique that enables the prompting of bidirectional models. Utilizing the machine translation task as a case study we prompt the bidirectional mT5 model (Xue et al. 2021) with SAP and demonstrate its few45;shot and zero45;shot translations outperform the few45;shot translations of unidirectional models like GPT45;3 and XGLM (Lin et al. 2021) despite mT5s approximately 5037; fewer parameters. We further show SAP is effective on question answering and summarization. For the first time our results demonstrate prompt45;based learning is an emergent property of a broader class of language models rather than only unidirectional models.
