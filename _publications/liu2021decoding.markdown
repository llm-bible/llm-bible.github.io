---
layout: publication
title: Dexperts Decoding45;time Controlled Text Generation With Experts And Anti45;experts
authors: Liu Alisa, Sap Maarten, Lu Ximing, Swayamdipta Swabha, Bhagavatula Chandra, Smith Noah A., Choi Yejin
conference: "Arxiv"
year: 2021
bibkey: liu2021decoding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2105.03023"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Model Architecture']
---
Despite recent advances in natural language generation it remains challenging to control attributes of generated text. We propose DExperts Decoding45;time Experts a decoding45;time method for controlled text generation that combines a pretrained language model with expert LMs and/or anti45;expert LMs in a product of experts. Intuitively under the ensemble tokens only get high probability if they are considered likely by the experts and unlikely by the anti45;experts. We apply DExperts to language detoxification and sentiment45;controlled generation where we outperform existing controllable generation methods on both automatic and human evaluations. Moreover because DExperts operates only on the output of the pretrained LM it is effective with (anti45;)experts of smaller size including when operating on GPT45;3. Our work highlights the promise of tuning small LMs on text with (un)desirable attributes for efficient decoding45;time steering.
