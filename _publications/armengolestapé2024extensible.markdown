---
layout: publication
title: Forklift An Extensible Neural Lifter
authors: Armengol-estapé Jordi, Rocha Rodrigo C. O., Woodruff Jackson, Minervini Pasquale, O'boyle Michael F. P.
conference: "Arxiv"
year: 2024
bibkey: armengolestapé2024extensible
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.16041"}
tags: ['Efficiency And Optimization', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Transformer']
---
The escalating demand to migrate legacy software across different Instruction Set Architectures (ISAs) has driven the development of assembly-to-assembly translators to map between their respective assembly languages. However the development of these tools requires substantial engineering effort. State-of-the-art approaches use lifting a technique where source assembly code is translated to an architecture-independent intermediate representation (IR) (for example the LLVM IR) and use a pre-existing compiler to recompile the IR to the target ISA. However the hand-written rules these lifters employ are sensitive to the particular compiler and optimization level used to generate the code and require significant engineering effort to support each new ISA. We propose Forklift the first neural lifter that learns how to translate assembly to LLVM IR using a token-level encoder-decoder Transformer. We show how to incrementally add support to new ISAs by fine tuning the assembly encoder and freezing the IR decoder improving the overall accuracy and efficiency. We collect millions of parallel LLVM IR x86 ARM and RISC-V programs across compilers and optimization levels to train Forklift and set up an input/output-based accuracy harness. We evaluate Forklift on two challenging benchmark suites and translate 2.5x more x86 programs than a state-of-the-art hand-written lifter and 4.4x more x86 programs than GPT-4 as well as enabling translation from new ISAs.
