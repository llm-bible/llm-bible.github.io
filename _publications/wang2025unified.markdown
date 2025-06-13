---
layout: publication
title: 'Veridebug: A Unified LLM For Verilog Debugging Via Contrastive Embedding And Guided Correction'
authors: Ning Wang, Bingkun Yao, Jie Zhou, Yuchen Hu, Xi Wang, Nan Guan, Zhe Jiang
conference: "Arxiv"
year: 2025
bibkey: wang2025unified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.19099"}
tags: ['GPT', 'Model Architecture']
---
Large Language Models (LLMs) have demonstrated remarkable potential in
debugging for various programming languages. However, the application of LLMs
to Verilog debugging remains insufficiently explored. Here, we present
VeriDebug, an approach that integrates contrastive representation and guided
correction capabilities for automated Verilog debugging. Unlike existing
methods, VeriDebug employs an embedding-based technique to accurately retrieve
internal information, followed by bug-fixing. VeriDebug unifies Verilog bug
detection and correction through a shared parameter space. By simultaneously
learning bug patterns and fixes, it streamlines debugging via contrastive
embedding and guided correction. Empirical results show the efficacy of
VeriDebug in enhancing Verilog debugging. Our VeriDebugLoc, Type model achieves
64.7 accuracy in bug fixing (Acc1), a significant improvement from the existing
open-source SOTAs 11.3. This performance not only outperforms open-source
alternatives but also exceeds larger closed-source models like GPT-3.5-turbo
(36.6), offering a more accurate alternative to conventional debugging methods.
