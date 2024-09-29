---
layout: publication
title: Creating A Dataset For High-performance Computing Code Translation Using Llms A Bridge Between Openmp Fortran And C++
authors: Lei Bin, Ding Caiwen, Chen Le, Lin Pei-hung, Liao Chunhua
conference: "Arxiv"
year: 2023
bibkey: lei2023creating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.07686"}
  - {name: "Code", url: "https://github.com/bin123apple/Fortran-CPP-HPC-code-translation-dataset\}\{OpenMP-Fortran-CPP-Translation\"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
In this study we present a novel dataset for training machine learning models translating between OpenMP Fortran and C++ code. To ensure reliability and applicability the dataset is created from a range of representative open-source OpenMP benchmarks. It is also refined using a meticulous code similarity test. The effectiveness of our dataset is assessed using both quantitative (CodeBLEU) and qualitative (human evaluation) methods. We showcase how this dataset significantly elevates the translation competencies of large language models (LLMs). Specifically models without prior coding knowledge experienced a boost of (mathbf)(times)~5.1 in their CodeBLEU scores while models with some coding familiarity saw an impressive (mathbf)(times)~9.9-fold increase. The best fine-tuned model using our dataset outperforms GPT-4. It is also reaching human-level accuracy. This work underscores the immense potential of our dataset in propelling advancements in the domain of code translation for high-performance computing. The dataset is accessible at (href)https://github.com/bin123apple/Fortran-CPP-HPC-code-translation-dataset\}\{OpenMP-Fortran-CPP-Translation\}.
