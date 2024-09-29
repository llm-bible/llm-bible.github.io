---
layout: publication
title: Fine45;grained Audio45;visual Joint Representations For Multimodal Large Language Models
authors: Sun Guangzhi, Yu Wenyi, Tang Changli, Chen Xianzhao, Tan Tian, Li Wei, Lu Lu, Ma Zejun, Zhang Chao
conference: "Arxiv"
year: 2023
bibkey: sun2023fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.05863"}
  - {name: "Code", url: "https://github.com/BriansIDP/AudioVisualLLM.git,"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Tools', 'Training Techniques']
---
Audio45;visual large language models (LLM) have drawn significant attention yet the fine45;grained combination of both input streams is rather under45;explored which is challenging but necessary for LLMs to understand general video inputs. To this end a fine45;grained audio45;visual joint representation (FAVOR) learning framework for multimodal LLMs is proposed in this paper which extends a text45;based LLM to simultaneously perceive speech and audio events in the audio input stream and images or videos in the visual input stream at the frame level. To fuse the audio and visual feature streams into joint representations and to align the joint space with the LLM input embedding space we propose a causal Q45;Former structure with a causal attention module to enhance the capture of causal relations of the audio45;visual frames across time. An audio45;visual evaluation benchmark (AVEB) is also proposed which comprises six representative single45;modal tasks with five cross45;modal tasks reflecting audio45;visual co45;reasoning abilities. While achieving competitive single45;modal performance on audio speech and image tasks in AVEB FAVOR achieved over 2037; accuracy improvements on the video question45;answering task when fine45;grained information or temporal causal reasoning is required. FAVOR in addition demonstrated remarkable video comprehension and reasoning abilities on tasks that are unprecedented by other multimodal LLMs. An interactive demo of FAVOR is available at https://github.com/BriansIDP/AudioVisualLLM.git, and the training code and model checkpoints will be released soon.
