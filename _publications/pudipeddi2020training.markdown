---
layout: publication
title: 'Training Large Neural Networks With Constant Memory Using A New Execution Algorithm'
authors: Pudipeddi Bharadwaj, Mesmakhosroshahi Maral, Xi Jinwen, Bharadwaj Sujeeth
conference: "Arxiv"
year: 2020
bibkey: pudipeddi2020training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2002.05645"}
tags: ['BERT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Widely popular transformer-based NLP models such as BERT and Turing-NLG have
enormous capacity trending to billions of parameters. Current execution methods
demand brute-force resources such as HBM devices and high speed
interconnectivity for data parallelism. In this paper, we introduce a new
relay-style execution technique called L2L (layer-to-layer) where at any given
moment, the device memory is primarily populated only with the executing
layer(s)'s footprint. The model resides in the DRAM memory attached to either a
CPU or an FPGA as an entity we call eager param-server (EPS). To overcome the
bandwidth issues of shuttling parameters to and from EPS, the model is executed
a layer at a time across many micro-batches instead of the conventional method
of minibatches over whole model. L2L is implemented using 16GB V100 devices for
BERT-Large running it with a device batch size of up to 256. Our results show
45% reduction in memory and 40% increase in the throughput compared to the
state-of-the-art baseline. L2L is also able to fit models up to 50 Billion
parameters on a machine with a single 16GB V100 and 512GB CPU memory and
without requiring any model partitioning. L2L scales to arbitrary depth
allowing researchers to develop on affordable devices which is a big step
toward democratizing AI. By running the optimizer in the host EPS, we show a
new form of mixed precision for faster throughput and convergence. In addition,
the EPS enables dynamic neural architecture approaches by varying layers across
iterations. Finally, we also propose and demonstrate a constant memory
variation of L2L and we propose future enhancements. This work has been
performed on GPUs first, but also targeted towards all high TFLOPS/Watt
accelerators.
