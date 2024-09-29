---
layout: publication
title: Context45;aware Visual Policy Network For Fine45;grained Image Captioning
authors: Zha Zheng-jun, Liu Daqing, Zhang Hanwang, Zhang Yongdong, Wu Feng
conference: "Arxiv"
year: 2019
bibkey: zha2019context
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1906.02365"}
tags: ['Attention Mechanism', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Transformer']
---
With the maturity of visual detection techniques we are more ambitious in describing visual content with open45;vocabulary fine45;grained and free45;form language i.e. the task of image captioning. In particular we are interested in generating longer richer and more fine45;grained sentences and paragraphs as image descriptions. Image captioning can be translated to the task of sequential language prediction given visual content where the output sequence forms natural language description with plausible grammar. However existing image captioning methods focus only on language policy while not visual policy and thus fail to capture visual context that are crucial for compositional reasoning such as object relationships (e.g. man riding horse) and visual comparisons (e.g. small(er) cat). This issue is especially severe when generating longer sequences such as a paragraph. To fill the gap we propose a Context45;Aware Visual Policy network (CAVP) for fine45;grained image45;to45;language generation image sentence captioning and image paragraph captioning. During captioning CAVP explicitly considers the previous visual attentions as context and decides whether the context is used for the current word/sentence generation given the current visual attention. Compared against traditional visual attention mechanism that only fixes a single visual region at each step CAVP can attend to complex visual compositions over time. The whole image captioning model 45;45; CAVP and its subsequent language policy network 45;45; can be efficiently optimized end45;to45;end by using an actor45;critic policy gradient method. We have demonstrated the effectiveness of CAVP by state45;of45;the45;art performances on MS45;COCO and Stanford captioning datasets using various metrics and sensible visualizations of qualitative visual context.
