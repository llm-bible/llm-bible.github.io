---
layout: publication
title: 'Vision-amplified Semantic Entropy For Hallucination Detection In Medical Visual Question Answering'
authors: Zehui Liao, Shishuai Hu, Ke Zou, Huazhu Fu, Liangli Zhen, Yong Xia
conference: "Arxiv"
year: 2025
bibkey: liao2025vision
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.20504"}
tags: ['Multimodal Models', 'Applications', 'Reinforcement Learning']
---
Multimodal large language models (MLLMs) have demonstrated significant
potential in medical Visual Question Answering (VQA). Yet, they remain prone to
hallucinations-incorrect responses that contradict input images, posing
substantial risks in clinical decision-making. Detecting these hallucinations
is essential for establishing trust in MLLMs among clinicians and patients,
thereby enabling their real-world adoption. Current hallucination detection
methods, especially semantic entropy (SE), have demonstrated promising
hallucination detection capacity for LLMs. However, adapting SE to medical
MLLMs by incorporating visual perturbations presents a dilemma. Weak
perturbations preserve image content and ensure clinical validity, but may be
overlooked by medical MLLMs, which tend to over rely on language priors. In
contrast, strong perturbations can distort essential diagnostic features,
compromising clinical interpretation. To address this issue, we propose Vision
Amplified Semantic Entropy (VASE), which incorporates weak image
transformations and amplifies the impact of visual input, to improve
hallucination detection in medical VQA. We first estimate the semantic
predictive distribution under weak visual transformations to preserve clinical
validity, and then amplify visual influence by contrasting this distribution
with that derived from a distorted image. The entropy of the resulting
distribution is estimated as VASE. Experiments on two medical open-ended VQA
datasets demonstrate that VASE consistently outperforms existing hallucination
detection methods.
