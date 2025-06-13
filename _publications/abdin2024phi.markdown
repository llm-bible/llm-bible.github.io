---
layout: publication
title: 'Phi-4 Technical Report'
authors: Marah Abdin, Jyoti Aneja, Harkirat Behl, Sébastien Bubeck, Ronen Eldan, Suriya Gunasekar, Michael Harrison, Russell J. Hewett, Mojan Javaheripi, Piero Kauffmann, James R. Lee, Yin Tat Lee, Yuanzhi Li, Weishung Liu, Caio C. T. Mendes, Anh Nguyen, Eric Price, Gustavo De Rosa, Olli Saarikivi, Adil Salim, Shital Shah, Xin Wang, Rachel Ward, Yue Wu, Dingli Yu, Cyril Zhang, Yi Zhang
conference: "Arxiv"
year: 2024
bibkey: abdin2024phi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.08905"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Distillation', 'GPT', 'Pre-Training']
---
We present phi-4, a 14-billion parameter language model developed with a
training recipe that is centrally focused on data quality. Unlike most language
models, where pre-training is based primarily on organic data sources such as
web content or code, phi-4 strategically incorporates synthetic data throughout
the training process. While previous models in the Phi family largely distill
the capabilities of a teacher model (specifically GPT-4), phi-4 substantially
surpasses its teacher model on STEM-focused QA capabilities, giving evidence
that our data-generation and post-training techniques go beyond distillation.
Despite minimal changes to the phi-3 architecture, phi-4 achieves strong
performance relative to its size -- especially on reasoning-focused benchmarks
-- due to improved data, training curriculum, and innovations in the
post-training scheme.
