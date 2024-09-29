---
layout: publication
title: A Frustratingly Simple Approach For End45;to45;end Image Captioning
authors: Luo Ziyang, Xi Yadong, Zhang Rongsheng, Ma Jing
conference: "Arxiv"
year: 2022
bibkey: luo2022frustratingly
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2201.12723"}
tags: ['Applications', 'Attention Mechanism', 'GPT', 'Language Modeling', 'Merging', 'Model Architecture', 'Tools', 'Training Techniques']
---
Image Captioning is a fundamental task to join vision and language concerning about cross45;modal understanding and text generation. Recent years witness the emerging attention on image captioning. Most of existing works follow a traditional two45;stage training paradigm. Before training the captioning models an extra object detector is utilized to recognize the objects in the image at first. However they require sizeable datasets with fine45;grained object annotation for training the object detector which is a daunting task. In addition the errors of the object detectors are easy to propagate to the following captioning models degenerating models performance. To alleviate such defects we propose a frustratingly simple but highly effective end45;to45;end image captioning framework Visual Conditioned GPT (VC45;GPT) by connecting the pre45;trained visual encoder (CLIP45;ViT) and language decoder (GPT2). Different from the vanilla connection method that directly inserts the cross45;attention modules into GPT2 we come up with a self45;ensemble cross45;modal fusion mechanism that comprehensively considers both the single45; and cross45;modal knowledge. As a result we do not need extra object detectors for model training. Experimental results conducted on three popular image captioning benchmarks (MSCOCO Flickr30k and NoCaps) demonstrate that our VC45;GPT achieves either the best or the second45;best performance across all evaluation metrics over extensive baseline systems.
