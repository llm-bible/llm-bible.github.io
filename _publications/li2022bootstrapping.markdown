---
layout: publication
title: 'BLIP: Bootstrapping Language-image Pre-training For Unified Vision-language
  Understanding And Generation'
authors: Junnan Li, Dongxu Li, Caiming Xiong, Steven Hoi
conference: Arxiv
year: 2022
citations: 540
bibkey: li2022bootstrapping
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2201.12086'}, {name: Code,
    url: 'https://github.com/salesforce/BLIP'}]
tags: [RAG, Pre-Training, Multimodal Models]
---
Vision-Language Pre-training (VLP) has advanced the performance for many
vision-language tasks. However, most existing pre-trained models only excel in
either understanding-based tasks or generation-based tasks. Furthermore,
performance improvement has been largely achieved by scaling up the dataset
with noisy image-text pairs collected from the web, which is a suboptimal
source of supervision. In this paper, we propose BLIP, a new VLP framework
which transfers flexibly to both vision-language understanding and generation
tasks. BLIP effectively utilizes the noisy web data by bootstrapping the
captions, where a captioner generates synthetic captions and a filter removes
the noisy ones. We achieve state-of-the-art results on a wide range of
vision-language tasks, such as image-text retrieval (+2.7% in average
recall@1), image captioning (+2.8% in CIDEr), and VQA (+1.6% in VQA score).
BLIP also demonstrates strong generalization ability when directly transferred
to video-language tasks in a zero-shot manner. Code, models, and datasets are
released at https://github.com/salesforce/BLIP.