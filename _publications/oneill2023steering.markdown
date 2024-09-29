---
layout: publication
title: Steering Language Generation\: Harnessing Contrastive Expert Guidance And Negative Prompting For Coherent And Diverse Synthetic Data Generation
authors: O'neill Charles, Ting Yuan-sen, Ciuca Ioana, Miller Jack, Bui Thang
conference: "Arxiv"
year: 2023
bibkey: oneill2023steering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.07645"}
tags: ['Applications', 'Prompting', 'Tools', 'Training Techniques']
---
Large Language Models (LLMs) hold immense potential to generate synthetic data of high quality and utility which has numerous applications from downstream model training to practical data utilisation. However contemporary models despite their impressive capacities consistently struggle to produce both coherent and diverse data. To address the coherency issue we introduce contrastive expert guidance where the difference between the logit distributions of fine-tuned and base language models is emphasised to ensure domain adherence. In order to ensure diversity we utilise existing real and synthetic examples as negative prompts to the model. We deem this dual-pronged approach to logit reshaping as STEER Semantic Text Enhancement via Embedding Repositioning. STEER operates at inference-time and systematically guides the LLMs to strike a balance between adherence to the data distribution (ensuring semantic fidelity) and deviation from prior synthetic examples or existing real datasets (ensuring diversity and authenticity). This delicate balancing act is achieved by dynamically moving towards or away from chosen representations in the latent space. STEER demonstrates improved performance over previous synthetic data generation techniques exhibiting better balance between data diversity and coherency across three distinct tasks hypothesis generation toxic and non-toxic comment generation and commonsense reasoning task generation. We demonstrate how STEER allows for fine-tuned control over the diversity-coherency trade-off via its hyperparameters highlighting its versatility.
