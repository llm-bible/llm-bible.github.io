---
layout: publication
title: 'Fine-grained Audio-visual Joint Representations For Multimodal Large Language Models'
authors: Guangzhi Sun, Wenyi Yu, Changli Tang, Xianzhao Chen, Tian Tan, Wei Li, Lu Lu, Zejun Ma, Chao Zhang
conference: "Arxiv"
year: 2023
bibkey: sun2023fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.05863"}
  - {name: "Code", url: "https://github.com/BriansIDP/AudioVisualLLM.git,"}
tags: ['Tools', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Multimodal Models']
---
Audio-visual large language models (LLM) have drawn significant attention,
yet the fine-grained combination of both input streams is rather
under-explored, which is challenging but necessary for LLMs to understand
general video inputs. To this end, a fine-grained audio-visual joint
representation (FAVOR) learning framework for multimodal LLMs is proposed in
this paper, which extends a text-based LLM to simultaneously perceive speech
and audio events in the audio input stream and images or videos in the visual
input stream, at the frame level. To fuse the audio and visual feature streams
into joint representations and to align the joint space with the LLM input
embedding space, we propose a causal Q-Former structure with a causal attention
module to enhance the capture of causal relations of the audio-visual frames
across time. An audio-visual evaluation benchmark (AVEB) is also proposed which
comprises six representative single-modal tasks with five cross-modal tasks
reflecting audio-visual co-reasoning abilities. While achieving competitive
single-modal performance on audio, speech and image tasks in AVEB, FAVOR
achieved over 20% accuracy improvements on the video question-answering task
when fine-grained information or temporal causal reasoning is required. FAVOR,
in addition, demonstrated remarkable video comprehension and reasoning
abilities on tasks that are unprecedented by other multimodal LLMs. An
interactive demo of FAVOR is available at
https://github.com/BriansIDP/AudioVisualLLM.git, and the training code and
model checkpoints will be released soon.
