---
layout: publication
title: 'Editing Common Sense In Transformers'
authors: Gupta Anshita, Mondal Debanjan, Sheshadri Akshay Krishna, Zhao Wenlong, Li Xiang Lorraine, Wiegreffe Sarah, Tandon Niket
conference: "Arxiv"
year: 2023
bibkey: gupta2023editing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14956"}
tags: ['Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Editing model parameters directly in Transformers makes updating open-source transformer-based models possible without re-training (Meng et al. 2023). However these editing methods have only been evaluated on statements about encyclopedic knowledge with a single correct answer. Commonsense knowledge with multiple correct answers e.g. an apple can be green or red but not transparent has not been studied but is as essential for enhancing transformers reliability and usefulness. In this paper we investigate whether commonsense judgments are causally associated with localized editable parameters in Transformers and we provide an affirmative answer. We find that directly applying the MEMIT editing algorithm results in sub-par performance and improve it for the commonsense domain by varying edit tokens and improving the layer selection strategy i.e. (MEMIT_CSK). GPT-2 Large and XL models edited using (MEMIT_CSK) outperform best-fine-tuned baselines by 10.9737; and 10.7337; F1 scores on PEP3k and 20Q datasets. In addition we propose a novel evaluation dataset PROBE SET that contains unaffected and affected neighborhoods affected paraphrases and affected reasoning challenges. (MEMIT_CSK) performs well across the metrics while fine-tuning baselines show significant trade-offs between unaffected and affected metrics. These results suggest a compelling future direction for incorporating feedback about common sense into Transformers through direct model editing.
