---
layout: publication
title: Dialogue Meaning Representation For Task45;oriented Dialogue Systems
authors: Hu Xiangkun, Dai Junqi, Yan Hang, Zhang Yi, Guo Qipeng, Qiu Xipeng, Zhang Zheng
conference: "Arxiv"
year: 2022
bibkey: hu2022dialogue
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2204.10989"}
tags: ['Applications', 'Tools']
---
Dialogue meaning representation formulates natural language utterance semantics in their conversational context in an explicit and machine45;readable form. Previous work typically follows the intent45;slot framework which is easy for annotation yet limited in scalability for complex linguistic expressions. A line of works alleviates the representation issue by introducing hierarchical structures but challenging to express complex compositional semantics such as negation and coreference. We propose Dialogue Meaning Representation (DMR) a pliable and easily extendable representation for task45;oriented dialogue. Our representation contains a set of nodes and edges to represent rich compositional semantics. Moreover we propose an inheritance hierarchy mechanism focusing on domain extensibility. Additionally we annotated DMR45;FastFood a multi45;turn dialogue dataset with more than 70k utterances with DMR. We propose two evaluation tasks to evaluate different dialogue models and a novel coreference resolution model GNNCoref for the graph45;based coreference resolution task. Experiments show that DMR can be parsed well with pre45;trained Seq2Seq models and GNNCoref outperforms the baseline models by a large margin.
