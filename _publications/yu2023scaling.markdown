---
layout: publication
title: Scaling Autoregressive Multi45;modal Models Pretraining And Instruction Tuning
authors: Yu Lili, Shi Bowen, Pasunuru Ramakanth, Muller Benjamin, Golovneva Olga, Wang Tianlu, Babu Arun, Tang Binh, Karrer Brian, Sheynin Shelly, Ross Candace, Polyak Adam, Howes Russell, Sharma Vasu, Xu Puxin, Tamoyan Hovhannes, Ashual Oron, Singer Uriel, Li Shang-wen, Zhang Susan, James Richard, Ghosh Gargi, Taigman Yaniv, Fazel-zarandi Maryam, Celikyilmaz Asli, Zettlemoyer Luke, Aghajanyan Armen
conference: "Arxiv"
year: 2023
bibkey: yu2023scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.02591"}
tags: ['Applications', 'Fine Tuning', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
We present CM3Leon (pronounced Chameleon) a retrieval45;augmented token45;based decoder45;only multi45;modal language model capable of generating and infilling both text and images. CM3Leon uses the CM3 multi45;modal architecture but additionally shows the extreme benefits of scaling up and tuning on more diverse instruction45;style data. It is the first multi45;modal model trained with a recipe adapted from text45;only language models including a large45;scale retrieval45;augmented pre45;training stage and a second multi45;task supervised fine45;tuning (SFT) stage. It is also a general45;purpose model that can do both text45;to45;image and image45;to45;text generation allowing us to introduce self45;contained contrastive decoding methods that produce high45;quality outputs. Extensive experiments demonstrate that this recipe is highly effective for multi45;modal models. CM3Leon achieves state45;of45;the45;art performance in text45;to45;image generation with 5x less training compute than comparable methods (zero45;shot MS45;COCO FID of 4.88). After SFT CM3Leon can also demonstrate unprecedented levels of controllability in tasks ranging from language45;guided image editing to image45;controlled generation and segmentation.
