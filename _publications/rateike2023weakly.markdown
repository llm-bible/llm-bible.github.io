---
layout: publication
title: Weakly Supervised Detection of Hallucinations in LLM Activations
authors: Rateike Miriam, Cintas Celia, Wamburu John, Akumu Tanya, Speakman Skyler
conference: "Arxiv"
year: 2023
bibkey: rateike2023weakly
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.02798"}
tags: ['BERT', 'Bias Mitigation', 'Ethics And Bias', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
We propose an auditing method to identify whether a large language model (LLM) encodes patterns such as hallucinations in its internal states which may propagate to downstream tasks. We introduce a weakly supervised auditing technique using a subset scanning approach to detect anomalous patterns in LLM activations from pre-trained models. Importantly our method does not need knowledge of the type of patterns a-priori. Instead it relies on a reference dataset devoid of anomalies during testing. Further our approach enables the identification of pivotal nodes responsible for encoding these patterns which may offer crucial insights for fine-tuning specific sub-networks for bias mitigation. We introduce two new scanning methods to handle LLM activations for anomalous sentences that may deviate from the expected distribution in either direction. Our results confirm prior findings of BERTs limited internal capacity for encoding hallucinations while OPT appears capable of encoding hallucination information internally. Importantly our scanning approach without prior exposure to false statements performs comparably to a fully supervised out-of-distribution classifier.
