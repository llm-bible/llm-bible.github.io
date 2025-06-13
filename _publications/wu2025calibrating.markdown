---
layout: publication
title: 'Calibrating Translation Decoding With Quality Estimation On Llms'
authors: Di Wu, Yibin Lei, Christof Monz
conference: "Arxiv"
year: 2025
bibkey: wu2025calibrating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.19044"}
  - {name: "Code", url: "https://github.com/moore3930/calibrating-llm-mt"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Applications']
---
Neural machine translation (NMT) systems typically employ maximum a posteriori (MAP) decoding to select the highest-scoring translation from the distribution mass. However, recent evidence highlights the inadequacy of MAP decoding, often resulting in low-quality or even pathological hypotheses -- the decoding objective is not aligned with real-world translation quality. This paper proposes calibrating hypothesis likelihoods with translation quality from a distribution view by directly optimizing their Pearson correlation -- thereby enhancing the effectiveness of translation decoding. With our method, translation on large language models (LLMs) improves substantially after limited training (2K instances per direction). This improvement is orthogonal to those achieved through supervised fine-tuning, leading to substantial gains across a broad range of metrics and human evaluations -- even when applied to top-performing translation-specialized LLMs fine-tuned on high-quality translation data, such as Tower, or when compared to recent preference optimization methods, like CPO. Moreover, the calibrated translation likelihood can directly serve as a strong proxy for translation quality, closely approximating or even surpassing some state-of-the-art translation quality estimation models, like CometKiwi. Lastly, our in-depth analysis demonstrates that calibration enhances the effectiveness of MAP decoding, thereby enabling greater efficiency in real-world deployment. The resulting state-of-the-art translation model, which covers 10 languages, along with the accompanying code and human evaluation data, has been released to the community: https://github.com/moore3930/calibrating-llm-mt.
