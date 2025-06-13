---
layout: publication
title: 'SERPENT-VLM : Self-refining Radiology Report Generation Using Vision Language Models'
authors: Manav Nitin Kapadnis, Sohan Patnaik, Abhilash Nandy, Sourjyadip Ray, Pawan Goyal, Debdoot Sheet
conference: "Arxiv"
year: 2024
bibkey: kapadnis2024serpent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.17912"}
tags: ['Tools', 'GPT', 'RAG', 'Language Modeling', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models']
---
Radiology Report Generation (R2Gen) demonstrates how Multi-modal Large
Language Models (MLLMs) can automate the creation of accurate and coherent
radiological reports. Existing methods often hallucinate details in text-based
reports that don't accurately reflect the image content. To mitigate this, we
introduce a novel strategy, SERPENT-VLM (SElf Refining Radiology RePort
GENeraTion using Vision Language Models), which improves the R2Gen task by
integrating a self-refining mechanism into the MLLM framework. We employ a
unique self-supervised loss that leverages similarity between pooled image
representations and the contextual representations of the generated
radiological text, alongside the standard Causal Language Modeling objective,
to refine image-text representations. This allows the model to scrutinize and
align the generated text through dynamic interaction between a given image and
the generated text, therefore reducing hallucination and continuously enhancing
nuanced report generation. SERPENT-VLM outperforms existing baselines such as
LLaVA-Med, BiomedGPT, etc., achieving SoTA performance on the IU X-ray and
Radiology Objects in COntext (ROCO) datasets, and also proves to be robust
against noisy images. A qualitative case study emphasizes the significant
advancements towards more sophisticated MLLM frameworks for R2Gen, opening
paths for further research into self-supervised refinement in the medical
imaging domain.
