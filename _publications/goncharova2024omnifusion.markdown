---
layout: publication
title: Omnifusion Technical Report
authors: Goncharova Elizaveta, Razzhigaev Anton, Mikhalchuk Matvey, Kurkin Maxim, Abdullaeva Irina, Skripkin Matvey, Oseledets Ivan, Dimitrov Denis, Kuznetsov Andrey
conference: "Arxiv"
year: 2024
bibkey: goncharova2024omnifusion
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.06212"}
  - {name: "Code", url: "https://github.com/AIRI-Institute/OmniFusion"}
tags: ['Has Code', 'Merging', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Last year multimodal architectures served up a revolution in AI-based approaches and solutions extending the capabilities of large language models (LLM). We propose an (textitOmniFusion) model based on a pretrained LLM and adapters for visual modality. We evaluated and compared several architecture design principles for better text and visual data coupling MLP and transformer adapters various CLIP ViT-based encoders (SigLIP InternVIT etc.) and their fusing approach image encoding method (whole image or tiles encoding) and two 7B LLMs (the proprietary one and open-source Mistral). Experiments on 8 visual-language benchmarks show the top score for the best OmniFusion setup in terms of different VQA tasks in comparison with open-source LLaVA-like solutions VizWiz Pope MM-Vet ScienceQA MMBench TextVQA VQAv2 MMMU. We also propose a variety of situations where OmniFusion provides highly-detailed answers in different domains housekeeping sightseeing culture medicine handwritten and scanned equations recognition etc. Mistral-based OmniFusion model is an open-source solution with weights training and inference scripts available at https://github.com/AIRI-Institute/OmniFusion.
