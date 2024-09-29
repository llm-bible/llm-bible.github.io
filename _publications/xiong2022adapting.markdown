---
layout: publication
title: Adapting Pretrained Text45;to45;text Models For Long Text Sequences
authors: Xiong Wenhan, Gupta Anchit, Toshniwal Shubham, Mehdad Yashar, Yih Wen-tau
conference: "Arxiv"
year: 2022
bibkey: xiong2022adapting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2209.10052"}
  - {name: "Code", url: "https://github.com/facebookresearch/bart&#95;ls"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Survey Paper', 'Training Techniques', 'Transformer']
---
We present an empirical study of adapting an existing pretrained text45;to45;text model for long45;sequence inputs. Through a comprehensive study along three axes of the pretraining pipeline 45;45; model architecture optimization objective and pretraining corpus we propose an effective recipe to build long45;context models from existing short45;context models. Specifically we replace the full attention in transformers with pooling45;augmented blockwise attention and pretrain the model with a masked45;span prediction task with spans of varying length. In terms of the pretraining corpus we find that using randomly concatenated short45;documents from a large open45;domain corpus results in better performance than using existing long document corpora which are typically limited in their domain coverage. With these findings we build a long45;context model that achieves competitive performance on long45;text QA tasks and establishes the new state of the art on five long45;text summarization datasets often outperforming previous methods with larger model sizes. Our code has been released at https://github.com/facebookresearch/bart&#95;ls.
