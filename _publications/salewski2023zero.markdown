---
layout: publication
title: Zero-shot Translation Of Attention Patterns In VQA Models To Natural Language
authors: Salewski Leonard, Koepke A. Sophia, Lensch Hendrik P. A., Akata Zeynep
conference: "Arxiv"
year: 2023
bibkey: salewski2023zero
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.05043"}
  - {name: "Code", url: "https://github.com/ExplainableML/ZS-A2T"}
tags: ['Applications', 'Attention Mechanism', 'Has Code', 'Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
Converting a models internals to text can yield human-understandable insights about the model. Inspired by the recent success of training-free approaches for image captioning we propose ZS-A2T a zero-shot framework that translates the transformer attention of a given model into natural language without requiring any training. We consider this in the context of Visual Question Answering (VQA). ZS-A2T builds on a pre-trained large language model (LLM) which receives a task prompt question and predicted answer as inputs. The LLM is guided to select tokens which describe the regions in the input image that the VQA model attended to. Crucially we determine this similarity by exploiting the text-image matching capabilities of the underlying VQA model. Our framework does not require any training and allows the drop-in replacement of different guiding sources (e.g. attribution instead of attention maps) or language models. We evaluate this novel task on textual explanation datasets for VQA giving state-of-the-art performances for the zero-shot setting on GQA-REX and VQA-X. Our code is available at https://github.com/ExplainableML/ZS-A2T."
