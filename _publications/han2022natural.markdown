---
layout: publication
title: "FOLIO: Natural Language Reasoning With First-order Logic"
authors: Han Simeng, Schoelkopf Hailey, Zhao Yilun, Qi Zhenting, Riddell Martin, Zhou Wenfei, Coady James, Peng David, Qiao Yujie, Benson Luke, Sun Lucy, Wardle-solano Alex, Szabo Hannah, Zubova Ekaterina, Burtell Matthew, Fan Jonathan, Liu Yixin, Wong Brian, Sailor Malcolm, Ni Ansong, Nan Linyong, Kasai Jungo, Yu Tao, Zhang Rui, Fabbri Alexander R., Kryscinski Wojciech, Yavuz Semih, Liu Ye, Lin Xi Victoria, Joty Shafiq, Zhou Yingbo, Xiong Caiming, Ying Rex, Cohan Arman, Radev Dragomir
conference: "Arxiv"
year: 2022
bibkey: han2022natural
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2209.00840"}
tags: ['Applications', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Large language models (LLMs) have achieved remarkable performance on a variety of natural language understanding tasks. However existing benchmarks are inadequate in measuring the complex logical reasoning capabilities of a model. We present FOLIO a human-annotated logically complex and diverse dataset for reasoning in natural language (NL) equipped with first-order logic (FOL) annotations. FOLIO consists of 1430 examples (unique conclusions) each paired with one of 487 sets of premises used to deductively reason for the validity of each conclusion. The logical correctness of the premises and conclusions is ensured by their FOL annotations which are automatically verified by an FOL inference engine. In addition to the main NL reasoning task NL-FOL pairs in FOLIO constitute a new NL-FOL translation dataset. Our experiments on FOLIO systematically evaluate the FOL reasoning ability of supervised fine-tuning on medium-sized language models. For both NL reasoning and NL-FOL translation we benchmark multiple state-of-the-art language models. Our results show that a subset of FOLIO presents a challenge for one of the most capable Large Language Model (LLM) publicly available GPT-4.
