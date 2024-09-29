---
layout: publication
title: QAID Question Answering Inspired Few45;shot Intent Detection
authors: Yehudai Asaf, Vetzler Matan, Mass Yosi, Lazar Koren, Cohen Doron, Carmeli Boaz
conference: "Arxiv"
year: 2023
bibkey: yehudai2023question
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.01593"}
tags: ['Applications', 'Model Architecture', 'Training Techniques']
---
Intent detection with semantically similar fine45;grained intents is a challenging task. To address it we reformulate intent detection as a question45;answering retrieval task by treating utterances and intent names as questions and answers. To that end we utilize a question45;answering retrieval architecture and adopt a two stages training schema with batch contrastive loss. In the pre45;training stage we improve query representations through self45;supervised training. Then in the fine45;tuning stage we increase contextualized token45;level similarity scores between queries and answers from the same intent. Our results on three few45;shot intent detection benchmarks achieve state45;of45;the45;art performance.
