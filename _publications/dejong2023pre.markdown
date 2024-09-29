---
layout: publication
title: Pre45;computed Memory Or On45;the45;fly Encoding A Hybrid Approach To Retrieval Augmentation Makes The Most Of Your Compute
authors: De Jong Michiel, Zemlyanskiy Yury, Fitzgerald Nicholas, Ainslie Joshua, Sanghai Sumit, Sha Fei, Cohen William
conference: "Arxiv"
year: 2023
bibkey: dejong2023pre
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2301.10448"}
tags: ['Merging', 'Pretraining Methods']
---
Retrieval45;augmented language models such as Fusion45;in45;Decoder are powerful setting the state of the art on a variety of knowledge45;intensive tasks. However they are also expensive due to the need to encode a large number of retrieved passages. Some work avoids this cost by pre45;encoding a text corpus into a memory and retrieving dense representations directly. However pre45;encoding memory incurs a severe quality penalty as the memory representations are not conditioned on the current input. We propose LUMEN a hybrid between these two extremes pre45;computing the majority of the retrieval representation and completing the encoding on the fly using a live encoder that is conditioned on the question and fine45;tuned for the task. We show that LUMEN significantly outperforms pure memory on multiple question45;answering tasks while being much cheaper than FiD and outperforms both for any given compute budget. Moreover the advantage of LUMEN over FiD increases with model size.
