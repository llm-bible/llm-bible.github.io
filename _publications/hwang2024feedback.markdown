---
layout: publication
title: Transformerfam: Feedback Attention Is Working Memory
authors: Hwang Dongseong, Wang Weiran, Huo Zhuoyuan, Sim Khe Chai, Mengibar Pedro Moreno
conference: "Arxiv"
year: 2024
bibkey: hwang2024feedback
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.09173"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Transformer']
---
While Transformers have revolutionized deep learning their quadratic attention complexity hinders their ability to process infinitely long inputs. We propose Feedback Attention Memory (FAM) a novel Transformer architecture that leverages a feedback loop to enable the network to attend to its own latent representations. This design fosters the emergence of working memory within the Transformer allowing it to process indefinitely long sequences. TransformerFAM requires no additional weights enabling seamless integration with pre-trained models. Our experiments show that TransformerFAM significantly improves Transformer performance on long-context tasks across various model sizes (1B 8B and 24B). These results showcase the potential to empower Large Language Models (LLMs) to process sequences of unlimited length.
