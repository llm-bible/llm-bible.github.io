---
layout: publication
title: Editing Common Sense In Transformers
authors: Gupta Anshita, Mondal Debanjan, Sheshadri Akshay Krishna, Zhao Wenlong, Li Xiang Lorraine, Wiegreffe Sarah, Tandon Niket
conference: "Arxiv"
year: 2023
bibkey: gupta2023editing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14956"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Editing model parameters directly in Transformers makes updating open45;source transformer45;based models possible without re45;training (Meng et al. 2023). However these editing methods have only been evaluated on statements about encyclopedic knowledge with a single correct answer. Commonsense knowledge with multiple correct answers e.g. an apple can be green or red but not transparent has not been studied but is as essential for enhancing transformers reliability and usefulness. In this paper we investigate whether commonsense judgments are causally associated with localized editable parameters in Transformers and we provide an affirmative answer. We find that directly applying the MEMIT editing algorithm results in sub45;par performance and improve it for the commonsense domain by varying edit tokens and improving the layer selection strategy i.e. MEMIT95;123;CSK125;. GPT45;2 Large and XL models edited using MEMIT95;123;CSK125; outperform best45;fine45;tuned baselines by 10.9737; and 10.7337; F1 scores on PEP3k and 20Q datasets. In addition we propose a novel evaluation dataset PROBE SET that contains unaffected and affected neighborhoods affected paraphrases and affected reasoning challenges. MEMIT95;123;CSK125; performs well across the metrics while fine45;tuning baselines show significant trade45;offs between unaffected and affected metrics. These results suggest a compelling future direction for incorporating feedback about common sense into Transformers through direct model editing.
