---
layout: publication
title: 'On-device Collaborative Language Modeling Via A Mixture Of Generalists And Specialists'
authors: Dongyang Fan, Bettina Messmer, Nikita Doikov, Martin Jaggi
conference: "ICML 2025"
year: 2024
bibkey: fan2024collaborative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.13931"}
tags: ['Efficiency and Optimization', 'Attention Mechanism', 'Language Modeling', 'Model Architecture']
---
On-device LLMs have gained increasing attention for their ability to enhance privacy and provide a personalized user experience. To facilitate private learning with scarce data, Federated Learning has become a standard approach. However, it faces challenges such as computational resource heterogeneity and data heterogeneity among end users. We propose CoMiGS (\\(\textbf\{Co\}\\)llaborative learning with a \\(\textbf\{Mi\}\\)xture of \\(\textbf\{G\}\\)eneralists and \\(\textbf\{S\}\\)pecialists), the first approach to address both challenges. A key innovation of our method is the bi-level optimization formulation of the Mixture-of-Experts learning objective, where the router is optimized using a separate validation set to ensure alignment with the target distribution. We solve our objective with alternating minimization, for which we provide a theoretical analysis. Our method shares generalist experts across users while localizing a varying number of specialist experts, thereby adapting to users' computational resources and preserving privacy. Through extensive experiments, we show CoMiGS effectively balances general and personalized knowledge for each token generation. We demonstrate that CoMiGS remains robust against overfitting-due to the generalists' regularizing effect-while adapting to local data through specialist expertise. We open source our codebase for collaborative LLMs.
