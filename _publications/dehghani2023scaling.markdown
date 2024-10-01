---
layout: publication
title: 'Scaling Vision Transformers To 22 Billion Parameters'
authors: Dehghani Mostafa, Djolonga Josip, Mustafa Basil, Padlewski Piotr, Heek Jonathan, Gilmer Justin, Steiner Andreas, Caron Mathilde, Geirhos Robert, Alabdulmohsin Ibrahim, Jenatton Rodolphe, Beyer Lucas, Tschannen Michael, Arnab Anurag, Wang Xiao, Riquelme Carlos, Minderer Matthias, Puigcerver Joan, Evci Utku, Kumar Manoj, Van Steenkiste Sjoerd, Elsayed Gamaleldin F., Mahendran Aravindh, Yu Fisher, Oliver Avital, Huot Fantine, Bastings Jasmijn, Collier Mark Patrick, Gritsenko Alexey, Birodkar Vighnesh, Vasconcelos Cristina, Tay Yi, Mensink Thomas, Kolesnikov Alexander, Pavetić Filip, Tran Dustin, Kipf Thomas, Lučić Mario, Zhai Xiaohua, Keysers Daniel, Harmsen Jeremiah, Houlsby Neil
conference: "Arxiv"
year: 2023
bibkey: dehghani2023scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2302.05442"}
tags: ['Bias Mitigation', 'Ethics And Bias', 'Fairness', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Transformer']
---
The scaling of Transformers has driven breakthrough capabilities for language models. At present, the largest large language models (LLMs) contain upwards of 100B parameters. Vision Transformers (ViT) have introduced the same architecture to image and video modelling, but these have not yet been successfully scaled to nearly the same degree; the largest dense ViT contains 4B parameters (Chen et al., 2022). We present a recipe for highly efficient and stable training of a 22B-parameter ViT (ViT-22B) and perform a wide variety of experiments on the resulting model. When evaluated on downstream tasks (often with a lightweight linear model on frozen features), ViT-22B demonstrates increasing performance with scale. We further observe other interesting benefits of scale, including an improved tradeoff between fairness and performance, state-of-the-art alignment to human visual perception in terms of shape/texture bias, and improved robustness. ViT-22B demonstrates the potential for LLM-like scaling in vision, and provides key steps towards getting there.
