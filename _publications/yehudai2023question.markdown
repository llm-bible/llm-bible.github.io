---
layout: publication
title: 'QAID: Question Answering Inspired Few-shot Intent Detection'
authors: Yehudai Asaf, Vetzler Matan, Mass Yosi, Lazar Koren, Cohen Doron, Carmeli Boaz
conference: "Arxiv"
year: 2023
bibkey: yehudai2023question
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.01593"}
tags: ['Applications', 'Few Shot', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Intent detection with semantically similar fine-grained intents is a challenging task. To address it, we reformulate intent detection as a question-answering retrieval task by treating utterances and intent names as questions and answers. To that end, we utilize a question-answering retrieval architecture and adopt a two stages training schema with batch contrastive loss. In the pre-training stage, we improve query representations through self-supervised training. Then, in the fine-tuning stage, we increase contextualized token-level similarity scores between queries and answers from the same intent. Our results on three few-shot intent detection benchmarks achieve state-of-the-art performance.
