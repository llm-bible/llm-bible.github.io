---
layout: publication
title: "MEDIMP: 3D Medical Images With Clinical Prompts From Limited Tabular Data For Renal Transplantation"
authors: Milecki Leo, Kalogeiton Vicky, Bodard Sylvain, Anglicheau Dany, Correas Jean-michel, Timsit Marc-olivier, Vakalopoulou Maria
conference: "Arxiv"
year: 2023
bibkey: milecki2023medical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.12445"}
  - {name: "Code", url: "https://github.com/leomlck/MEDIMP"}
tags: ['Has Code', 'Pretraining Methods', 'Prompting', 'Tools']
---
Renal transplantation emerges as the most effective solution for end-stage renal disease. Occurring from complex causes a substantial risk of transplant chronic dysfunction persists and may lead to graft loss. Medical imaging plays a substantial role in renal transplant monitoring in clinical practice. However graft supervision is multi-disciplinary notably joining nephrology urology and radiology while identifying robust biomarkers from such high-dimensional and complex data for prognosis is challenging. In this work taking inspiration from the recent success of Large Language Models (LLMs) we propose MEDIMP -- Medical Images with clinical Prompts -- a model to learn meaningful multi-modal representations of renal transplant Dynamic Contrast-Enhanced Magnetic Resonance Imaging (DCE MRI) by incorporating structural clinicobiological data after translating them into text prompts. MEDIMP is based on contrastive learning from joint text-image paired embeddings to perform this challenging task. Moreover we propose a framework that generates medical prompts using automatic textual data augmentations from LLMs. Our goal is to learn meaningful manifolds of renal transplant DCE MRI interesting for the prognosis of the transplant or patient status (2 3 and 4 years after the transplant) fully exploiting the limited available multi-modal data most efficiently. Extensive experiments and comparisons with other renal transplant representation learning methods with limited data prove the effectiveness of MEDIMP in a relevant clinical setting giving new directions toward medical prompts. Our code is available at https://github.com/leomlck/MEDIMP."
