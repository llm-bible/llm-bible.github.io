---
layout: publication
title: Stylip&#58; Multi-scale Style-conditioned Prompt Learning For Clip-based Domain Generalization
authors: Bose Shirsha, Jha Ankit, Fini Enrico, Singha Mainak, Ricci Elisa, Banerjee Biplab
conference: "Arxiv"
year: 2023
bibkey: bose2023multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2302.09251"}
tags: ['Ethics And Bias', 'Prompting', 'RAG']
---
Large-scale foundation models such as CLIP have demonstrated impressive zero-shot generalization performance on downstream tasks leveraging well-designed language prompts. However these prompt learning techniques often struggle with domain shift limiting their generalization capabilities. In our study we tackle this issue by proposing StyLIP a novel approach for Domain Generalization (DG) that enhances CLIPs classification performance across domains. Our method focuses on a domain-agnostic prompt learning strategy aiming to disentangle the visual style and content information embedded in CLIPs pre-trained vision encoder enabling effortless adaptation to novel domains during inference. To achieve this we introduce a set of style projectors that directly learn the domain-specific prompt tokens from the extracted multi-scale style features. These generated prompt embeddings are subsequently combined with the multi-scale visual content features learned by a content projector. The projectors are trained in a contrastive manner utilizing CLIPs fixed vision and text backbones. Through extensive experiments conducted in five different DG settings on multiple benchmark datasets we consistently demonstrate that StyLIP outperforms the current state-of-the-art (SOTA) methods.
