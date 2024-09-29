---
layout: publication
title: Llm.int8() 845;bit Matrix Multiplication For Transformers At Scale
authors: Dettmers Tim, Lewis Mike, Belkada Younes, Zettlemoyer Luke
conference: "Arxiv"
year: 2022
bibkey: dettmers2022matrix
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2208.07339"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Quantization', 'Transformer']
---
Large language models have been widely adopted but require significant GPU memory for inference. We develop a procedure for Int8 matrix multiplication for feed45;forward and attention projection layers in transformers which cut the memory needed for inference by half while retaining full precision performance. With our method a 175B parameter 16/3245;bit checkpoint can be loaded converted to Int8 and used immediately without performance degradation. This is made possible by understanding and working around properties of highly systematic emergent features in transformer language models that dominate attention and transformer predictive performance. To cope with these features we develop a two45;part quantization procedure LLM.int8(). We first use vector45;wise quantization with separate normalization constants for each inner product in the matrix multiplication to quantize most of the features. However for the emergent outliers we also include a new mixed45;precision decomposition scheme which isolates the outlier feature dimensions into a 1645;bit matrix multiplication while still more than 99.937; of values are multiplied in 845;bit. Using LLM.int8() we show empirically it is possible to perform inference in LLMs with up to 175B parameters without any performance degradation. This result makes such models much more accessible for example making it possible to use OPT45;175B/BLOOM on a single server with consumer GPUs. We open45;source our software.
