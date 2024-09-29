---
layout: publication
title: Mask The Bias\: Improving Domain-adaptive Generalization Of Ctc-based ASR With Internal Language Model Estimation
authors: Das Nilaksh, Sunkara Monica, Bodapati Sravan, Cai Jinglun, Kulshreshtha Devang, Farris Jeff, Kirchhoff Katrin
conference: "Arxiv"
year: 2023
bibkey: das2023mask
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.03837"}
tags: ['Attention Mechanism', 'Ethics And Bias', 'Fine Tuning', 'GPT', 'Language Modeling', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
End-to-end ASR models trained on large amount of data tend to be implicitly biased towards language semantics of the training data. Internal language model estimation (ILME) has been proposed to mitigate this bias for autoregressive models such as attention-based encoder-decoder and RNN-T. Typically ILME is performed by modularizing the acoustic and language components of the model architecture and eliminating the acoustic input to perform log-linear interpolation with the text-only posterior. However for CTC-based ASR it is not as straightforward to decouple the model into such acoustic and language components as CTC log-posteriors are computed in a non-autoregressive manner. In this work we propose a novel ILME technique for CTC-based ASR models. Our method iteratively masks the audio timesteps to estimate a pseudo log-likelihood of the internal LM by accumulating log-posteriors for only the masked timesteps. Extensive evaluation across multiple out-of-domain datasets reveals that the proposed approach improves WER by up to 9.837; and OOV F1-score by up to 24.637; relative to Shallow Fusion when only text data from target domain is available. In the case of zero-shot domain adaptation with no access to any target domain data we demonstrate that removing the source domain bias with ILME can still outperform Shallow Fusion to improve WER by up to 9.337; relative.
