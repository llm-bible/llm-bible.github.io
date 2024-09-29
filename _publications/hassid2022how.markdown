---
layout: publication
title: How Much Does Attention Actually Attend Questioning The Importance Of Attention In Pretrained Transformers
authors: Hassid Michael, Peng Hao, Rotem Daniel, Kasai Jungo, Montero Ivan, Smith Noah A., Schwartz Roy
conference: "Arxiv"
year: 2022
bibkey: hassid2022how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2211.03495"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Transformer']
---
The attention mechanism is considered the backbone of the widely45;used Transformer architecture. It contextualizes the input by computing input45;specific attention matrices. We find that this mechanism while powerful and elegant is not as important as typically thought for pretrained language models. We introduce PAPA a new probing method that replaces the input45;dependent attention matrices with constant ones 45;45; the average attention weights over multiple inputs. We use PAPA to analyze several established pretrained Transformers on six downstream tasks. We find that without any input45;dependent attention all models achieve competitive performance 45;45; an average relative drop of only 837; from the probing baseline. Further little or no performance drop is observed when replacing half of the input45;dependent attention matrices with constant (input45;independent) ones. Interestingly we show that better45;performing models lose more from applying our method than weaker models suggesting that the utilization of the input45;dependent attention mechanism might be a factor in their success. Our results motivate research on simpler alternatives to input45;dependent attention as well as on methods for better utilization of this mechanism in the Transformer architecture.
