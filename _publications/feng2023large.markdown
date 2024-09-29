---
layout: publication
title: LLM4VG&#58; Large Language Models Evaluation For Video Grounding
authors: Feng Wei, Wang Xin, Chen Hong, Zhang Zeyang, Chen Houlun, Song Zihan, Zhou Yuwei, Yang Yuekui, Wu Haiyang, Zhu Wenwu
conference: "Arxiv"
year: 2023
bibkey: feng2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.14206"}
tags: ['Prompting']
---
Recently researchers have attempted to investigate the capability of LLMs in handling videos and proposed several video LLM models. However the ability of LLMs to handle video grounding (VG) which is an important time-related video task requiring the model to precisely locate the start and end timestamps of temporal moments in videos that match the given textual queries still remains unclear and unexplored in literature. To fill the gap in this paper we propose the LLM4VG benchmark which systematically evaluates the performance of different LLMs on video grounding tasks. Based on our proposed LLM4VG we design extensive experiments to examine two groups of video LLM models on video grounding (i) the video LLMs trained on the text-video pairs (denoted as VidLLM) and (ii) the LLMs combined with pretrained visual description models such as the video/image captioning model. We propose prompt methods to integrate the instruction of VG and description from different kinds of generators including caption-based generators for direct visual description and VQA-based generators for information enhancement. We also provide comprehensive comparisons of various VidLLMs and explore the influence of different choices of visual models LLMs prompt designs etc as well. Our experimental evaluations lead to two conclusions (i) the existing VidLLMs are still far away from achieving satisfactory video grounding performance and more time-related video tasks should be included to further fine-tune these models and (ii) the combination of LLMs and visual models shows preliminary abilities for video grounding with considerable potential for improvement by resorting to more reliable models and further guidance of prompt instructions.
