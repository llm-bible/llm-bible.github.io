---
layout: publication
title: 'See What You Are Told: Visual Attention Sink In Large Multimodal Models'
authors: Seil Kang, Jinyeong Kim, Junhyeok Kim, Seong Jae Hwang
conference: "Arxiv"
year: 2025
bibkey: kang2025see
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.03321"}
tags: ['Transformer', 'RAG', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'Multimodal Models']
---
Large multimodal models (LMMs) "see" images by leveraging the attention
mechanism between text and visual tokens in the transformer decoder. Ideally,
these models should focus on key visual information relevant to the text token.
However, recent findings indicate that LMMs have an extraordinary tendency to
consistently allocate high attention weights to specific visual tokens, even
when these tokens are irrelevant to the corresponding text. In this study, we
investigate the property behind the appearance of these irrelevant visual
tokens and examine their characteristics. Our findings show that this behavior
arises due to the massive activation of certain hidden state dimensions, which
resembles the attention sink found in language models. Hence, we refer to this
phenomenon as the visual attention sink. In particular, our analysis reveals
that removing the irrelevant visual sink tokens does not impact model
performance, despite receiving high attention weights. Consequently, we recycle
the attention to these tokens as surplus resources, redistributing the
attention budget to enhance focus on the image. To achieve this, we introduce
Visual Attention Redistribution (VAR), a method that redistributes attention in
image-centric heads, which we identify as innately focusing on visual
information. VAR can be seamlessly applied across different LMMs to improve
performance on a wide range of tasks, including general vision-language tasks,
visual hallucination tasks, and vision-centric tasks, all without the need for
additional training, models, or inference steps. Experimental results
demonstrate that VAR enables LMMs to process visual information more
effectively by adjusting their internal attention mechanisms, offering a new
direction to enhancing the multimodal capabilities of LMMs.
