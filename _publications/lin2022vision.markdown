---
layout: publication
title: ADAPT Vision45;language Navigation With Modality45;aligned Action Prompts
authors: Lin Bingqian, Zhu Yi, Chen Zicong, Liang Xiwen, Liu Jianzhuang, Liang Xiaodan
conference: "Arxiv"
year: 2022
bibkey: lin2022vision
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.15509"}
tags: ['Agentic', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques', 'Transformer']
---
Vision45;Language Navigation (VLN) is a challenging task that requires an embodied agent to perform action45;level modality alignment i.e. make instruction45;asked actions sequentially in complex visual environments. Most existing VLN agents learn the instruction45;path data directly and cannot sufficiently explore action45;level alignment knowledge inside the multi45;modal inputs. In this paper we propose modAlity45;aligneD Action PrompTs (ADAPT) which provides the VLN agent with action prompts to enable the explicit learning of action45;level modality alignment to pursue successful navigation. Specifically an action prompt is defined as a modality45;aligned pair of an image sub45;prompt and a text sub45;prompt where the former is a single45;view observation and the latter is a phrase like walk past the chair. When starting navigation the instruction45;related action prompt set is retrieved from a pre45;built action prompt base and passed through a prompt encoder to obtain the prompt feature. Then the prompt feature is concatenated with the original instruction feature and fed to a multi45;layer transformer for action prediction. To collect high45;quality action prompts into the prompt base we use the Contrastive Language45;Image Pretraining (CLIP) model which has powerful cross45;modality alignment ability. A modality alignment loss and a sequential consistency loss are further introduced to enhance the alignment of the action prompt and enforce the agent to focus on the related prompt sequentially. Experimental results on both R2R and RxR show the superiority of ADAPT over state45;of45;the45;art methods.
