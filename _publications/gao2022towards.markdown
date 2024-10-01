---
layout: publication
title: 'WAVPROMPT: Towards Few-shot Spoken Language Understanding With Frozen Language Models'
authors: Gao Heting, Ni Junrui, Qian Kaizhi, Zhang Yang, Chang Shiyu, Hasegawa-johnson Mark
conference: "Arxiv"
year: 2022
bibkey: gao2022towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2203.15863"}
  - {name: "Code", url: "https://github.com/Hertin/WavPrompt"}
tags: ['Few Shot', 'Fine Tuning', 'Has Code', 'Multimodal Models', 'Pretraining Methods', 'Prompting', 'Tools', 'Training Techniques']
---
"Large-scale auto-regressive language models pretrained on massive text have demonstrated their impressive ability to perform new natural language tasks with only a few text examples, without the need for fine-tuning. Recent studies further show that such a few-shot learning ability can be extended to the text-image setting by training an encoder to encode the images into embeddings functioning like the text embeddings of the language model. Interested in exploring the possibility of transferring the few-shot learning ability to the audio-text setting, we propose a novel speech understanding framework, WavPrompt, where we finetune a wav2vec model to generate a sequence of audio embeddings understood by the language model. We show that WavPrompt is a few-shot learner that can perform speech understanding tasks better than a naive text baseline. We conduct detailed ablation studies on different components and hyperparameters to empirically identify the best model configuration. In addition, we conduct a non-speech understanding experiment to show WavPrompt can extract more information than just the transcriptions. Code is available at https://github.com/Hertin/WavPrompt"
