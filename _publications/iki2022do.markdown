---
layout: publication
title: "Do Berts Learn To Use Browser User Interface? Exploring Multi-step Tasks With Unified Vision-and-language Berts"
authors: Iki Taichi, Aizawa Akiko
conference: "Arxiv"
year: 2022
bibkey: iki2022do
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2203.07828"}
tags: ['BERT', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Transformer']
---
Pre-trained Transformers are good foundations for unified multi-task models owing to their task-agnostic representation. Pre-trained Transformers are often combined with text-to-text framework to execute multiple tasks by a single model. Performing a task through a graphical user interface (GUI) is another candidate to accommodate various tasks including multi-step tasks with vision and language inputs. However few papers combine pre-trained Transformers with performing through GUI. To fill this gap we explore a framework in which a model performs a task by manipulating the GUI implemented with web pages in multiple steps. We develop task pages with and without page transitions and propose a BERT extension for the framework. We jointly trained our BERT extension with those task pages and made the following observations. (1) The model learned to use both task pages with and without page transition. (2) In four out of five tasks without page transitions the model performs greater than 7537; of the performance of the original BERT which does not use browsers. (3) The model did not generalize effectively on unseen tasks. These results suggest that we can fine-tune BERTs to multi-step tasks through GUIs and there is room for improvement in their generalizability. Code will be available online.
