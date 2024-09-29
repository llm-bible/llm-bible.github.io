---
layout: publication
title: Large Language Models For Compiler Optimization
authors: Cummins Chris, Seeker Volker, Grubisic Dejan, Elhoushi Mostafa, Liang Youwei, Roziere Baptiste, Gehring Jonas, Gloeckle Fabian, Hazelwood Kim, Synnaeve Gabriel, Leather Hugh
conference: "Arxiv"
year: 2023
bibkey: cummins2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.07062"}
tags: ['Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
We explore the novel application of Large Language Models to code optimization. We present a 7B45;parameter transformer model trained from scratch to optimize LLVM assembly for code size. The model takes as input unoptimized assembly and outputs a list of compiler options to best optimize the program. Crucially during training we ask the model to predict the instruction counts before and after optimization and the optimized code itself. These auxiliary learning tasks significantly improve the optimization performance of the model and improve the models depth of understanding. We evaluate on a large suite of test programs. Our approach achieves a 3.037; improvement in reducing instruction counts over the compiler outperforming two state45;of45;the45;art baselines that require thousands of compilations. Furthermore the model shows surprisingly strong code reasoning abilities generating compilable code 9137; of the time and perfectly emulating the output of the compiler 7037; of the time.
