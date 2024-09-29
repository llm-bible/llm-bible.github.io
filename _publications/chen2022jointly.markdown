---
layout: publication
title: Pali A Jointly45;scaled Multilingual Language45;image Model
authors: Chen Xi, Wang Xiao, Changpinyo Soravit, Piergiovanni Aj, Padlewski Piotr, Salz Daniel, Goodman Sebastian, Grycner Adam, Mustafa Basil, Beyer Lucas, Kolesnikov Alexander, Puigcerver Joan, Ding Nan, Rong Keran, Akbari Hassan, Mishra Gaurav, Xue Linting, Thapliyal Ashish, Bradbury James, Kuo Weicheng, Seyedhosseini Mojtaba, Jia Chao, Ayan Burcu Karagol, Riquelme Carlos, Steiner Andreas, Angelova Anelia, Zhai Xiaohua, Houlsby Neil, Soricut Radu
conference: "Arxiv"
year: 2022
bibkey: chen2022jointly
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2209.06794"}
tags: ['Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques', 'Transformer']
---
Effective scaling and a flexible task interface enable large language models to excel at many tasks. We present PaLI (Pathways Language and Image model) a model that extends this approach to the joint modeling of language and vision. PaLI generates text based on visual and textual inputs and with this interface performs many vision language and multimodal tasks in many languages. To train PaLI we make use of large pre45;trained encoder45;decoder language models and Vision Transformers (ViTs). This allows us to capitalize on their existing capabilities and leverage the substantial cost of training them. We find that joint scaling of the vision and language components is important. Since existing Transformers for language are much larger than their vision counterparts we train a large 445;billion parameter ViT (ViT45;e) to quantify the benefits from even larger45;capacity vision models. To train PaLI we create a large multilingual mix of pretraining tasks based on a new image45;text training set containing 10B images and texts in over 100 languages. PaLI achieves state45;of45;the45;art in multiple vision and language tasks (such as captioning visual question45;answering scene45;text understanding) while retaining a simple modular and scalable design.
