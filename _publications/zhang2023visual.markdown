---
layout: publication
title: 'Visual Attention Prompted Prediction And Learning'
authors: Yifei Zhang, Siyi Gu, Bo Pan, Guangji Bai, Meikang Qiu, Xiaofeng Yang, Liang Zhao
conference: "Arxiv"
year: 2023
bibkey: zhang2023visual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.08420"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Interpretability and Explainability', 'Prompting', 'Attention Mechanism']
---
Visual explanation (attention)-guided learning uses not only labels but also
explanations to guide model reasoning process. While visual attention-guided
learning has shown promising results, it requires a large number of explanation
annotations that are time-consuming to prepare. However, in many real-world
situations, it is usually desired to prompt the model with visual attention
without model retraining. For example, when doing AI-assisted cancer
classification on a medical image, users (e.g., clinicians) can provide the AI
model with visual attention prompt on which areas are indispensable and which
are precluded. Despite its promising objectives, achieving visual
attention-prompted prediction presents several major challenges: 1) How can the
visual prompt be effectively integrated into the model's reasoning process? 2)
How should the model handle samples that lack visual prompts? 3) What is the
impact on the model's performance when a visual prompt is imperfect? This paper
introduces a novel framework for attention-prompted prediction and learning,
utilizing visual prompts to steer the model's reasoning process. To improve
performance in non-prompted situations and align it with prompted scenarios, we
propose a co-training approach for both non-prompted and prompted models,
ensuring they share similar parameters and activations. Additionally, for
instances where the visual prompt does not encompass the entire input image, we
have developed innovative attention prompt refinement methods. These methods
interpolate the incomplete prompts while maintaining alignment with the model's
explanations. Extensive experiments on four datasets demonstrate the
effectiveness of our proposed framework in enhancing predictions for samples
both with and without prompt.
