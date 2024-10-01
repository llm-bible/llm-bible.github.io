---
layout: publication
title: 'Gradient-based Word Substitution For Obstinate Adversarial Examples Generation In Language Models'
authors: Wang Yimu, Shi Peng, Zhang Hongyang
conference: "Arxiv"
year: 2023
bibkey: wang2023gradient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.12507"}
tags: ['Applications', 'BERT', 'GPT', 'Model Architecture', 'Security']
---
'In this paper, we study the problem of generating obstinate (over-stability) adversarial examples by word substitution in NLP, where input text is meaningfully changed but the model''s prediction does not, even though it should. Previous word substitution approaches have predominantly focused on manually designed antonym-based strategies for generating obstinate adversarial examples, which hinders its application as these strategies can only find a subset of obstinate adversarial examples and require human efforts. To address this issue, in this paper, we introduce a novel word substitution method named GradObstinate, a gradient-based approach that automatically generates obstinate adversarial examples without any constraints on the search space or the need for manual design principles. To empirically evaluate the efficacy of GradObstinate, we conduct comprehensive experiments on five representative models (Electra, ALBERT, Roberta, DistillBERT, and CLIP) finetuned on four NLP benchmarks (SST-2, MRPC, SNLI, and SQuAD) and a language-grounding benchmark (MSCOCO). Extensive experiments show that our proposed GradObstinate generates more powerful obstinate adversarial examples, exhibiting a higher attack success rate compared to antonym-based methods. Furthermore, to show the transferability of obstinate word substitutions found by GradObstinate, we replace the words in four representative NLP benchmarks with their obstinate substitutions. Notably, obstinate substitutions exhibit a high success rate when transferred to other models in black-box settings, including even GPT-3 and ChatGPT. Examples of obstinate adversarial examples found by GradObstinate are available at https://huggingface.co/spaces/anonauthors/SecretLanguage.'
