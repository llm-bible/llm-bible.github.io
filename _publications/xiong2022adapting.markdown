---
layout: publication
title: Adapting Pretrained Text-to-text Models For Long Text Sequences
authors: Xiong Wenhan, Gupta Anchit, Toshniwal Shubham, Mehdad Yashar, Yih Wen-tau
conference: "Arxiv"
year: 2022
bibkey: xiong2022adapting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2209.10052"}
  - {name: "Code", url: "https://github.com/facebookresearch/bart_ls"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Survey Paper', 'Training Techniques', 'Transformer']
---
We present an empirical study of adapting an existing pretrained text-to-text model for long-sequence inputs. Through a comprehensive study along three axes of the pretraining pipeline -- model architecture optimization objective and pretraining corpus we propose an effective recipe to build long-context models from existing short-context models. Specifically we replace the full attention in transformers with pooling-augmented blockwise attention and pretrain the model with a masked-span prediction task with spans of varying length. In terms of the pretraining corpus we find that using randomly concatenated short-documents from a large open-domain corpus results in better performance than using existing long document corpora which are typically limited in their domain coverage. With these findings we build a long-context model that achieves competitive performance on long-text QA tasks and establishes the new state of the art on five long-text summarization datasets often outperforming previous methods with larger model sizes. Our code has been released at https://github.com/facebookresearch/bart_ls.
