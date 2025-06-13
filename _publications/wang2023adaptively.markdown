---
layout: publication
title: 'Adaptively Clustering Neighbor Elements For Image-text Generation'
authors: Zihua Wang, Xu Yang, Hanwang Zhang, Haiyang Xu, Ming Yan, Fei Huang, Yu Zhang
conference: "Arxiv"
year: 2023
bibkey: wang2023adaptively
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2301.01955"}
  - {name: "Code", url: "https://github.com/ZihuaEvan/ACFModel/}{[here]"}
tags: ['Multimodal Models', 'Model Architecture', 'Language Modeling', 'Pretraining Methods', 'Transformer', 'Has Code', 'Applications', 'Attention Mechanism']
---
We propose a novel Transformer-based image-to-text generation model termed as
\textbf\{ACF\} that adaptively clusters vision patches into object regions and
language words into phrases to implicitly learn object-phrase alignments for
better visual-text coherence. To achieve this, we design a novel self-attention
layer that applies self-attention over the elements in a local cluster window
instead of the whole sequence. The window size is softly decided by a
clustering matrix that is calculated by the current input data and thus this
process is adaptive. By stacking these revised self-attention layers to
construct ACF, the small clusters in the lower layers can be grouped into a
bigger cluster, \eg vision/language. ACF clusters small objects/phrases into
bigger ones. In this gradual clustering process, a parsing tree is generated
which embeds the hierarchical knowledge of the input sequence. As a result, by
using ACF to build the vision encoder and language decoder, the hierarchical
object-phrase alignments are embedded and then transferred from vision to
language domains in two popular image-to-text tasks: Image captioning and
Visual Question Answering. The experiment results demonstrate the effectiveness
of ACF, which outperforms most SOTA captioning and VQA models and achieves
comparable scores compared with some large-scale pre-trained models. Our code
is available \href\{https://github.com/ZihuaEvan/ACFModel/\}\{[here]\}.
