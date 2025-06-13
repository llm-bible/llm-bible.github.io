---
layout: publication
title: 'Reading Between The Lines: Exploring Infilling In Visual Narratives'
authors: Khyathi Raghavi Chandu, Ruo-ping Dong, Alan Black
conference: "Arxiv"
year: 2020
bibkey: chandu2020reading
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.13944"}
  - {name: "Code", url: "https://visual-narratives.github.io/Visual-Narratives/"}
tags: ['Training Techniques', 'Has Code']
---
Generating long form narratives such as stories and procedures from multiple
modalities has been a long standing dream for artificial intelligence. In this
regard, there is often crucial subtext that is derived from the surrounding
contexts. The general seq2seq training methods render the models shorthanded
while attempting to bridge the gap between these neighbouring contexts. In this
paper, we tackle this problem by using \textit\{infilling\} techniques involving
prediction of missing steps in a narrative while generating textual
descriptions from a sequence of images. We also present a new large scale
\textit\{visual procedure telling\} (ViPT) dataset with a total of 46,200
procedures and around 340k pairwise images and textual descriptions that is
rich in such contextual dependencies. Generating steps using infilling
technique demonstrates the effectiveness in visual procedures with more
coherent texts. We conclusively show a METEOR score of 27.51 on procedures
which is higher than the state-of-the-art on visual storytelling. We also
demonstrate the effects of interposing new text with missing images during
inference. The code and the dataset will be publicly available at
https://visual-narratives.github.io/Visual-Narratives/.
