---
layout: publication
title: Spqr A Sparse45;quantized Representation For Near45;lossless LLM Weight Compression
authors: Dettmers Tim, Svirschevski Ruslan, Egiazarian Vage, Kuznedelev Denis, Frantar Elias, Ashkboos Saleh, Borzunov Alexander, Hoefler Torsten, Alistarh Dan
conference: "Arxiv"
year: 2023
bibkey: dettmers2023sparse
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.03078"}
tags: ['Applications', 'Efficiency And Optimization', 'Pretraining Methods', 'Quantization', 'Reinforcement Learning', 'Training Techniques']
---
Recent advances in large language model (LLM) pretraining have led to high45;quality LLMs with impressive abilities. By compressing such LLMs via quantization to 345;4 bits per parameter they can fit into memory45;limited devices such as laptops and mobile phones enabling personalized use. However quantization down to 345;4 bits per parameter usually leads to moderate45;to45;high accuracy losses especially for smaller models in the 145;10B parameter range which are well45;suited for edge deployments. To address this accuracy issue we introduce the Sparse45;Quantized Representation (SpQR) a new compressed format and quantization technique which enables for the first time near45;lossless compression of LLMs across model scales while reaching similar compression levels to previous methods. SpQR works by identifying and isolating outlier weights which cause particularly45;large quantization errors and storing them in higher precision while compressing all other weights to 345;4 bits and achieves relative accuracy losses of less than 137; in perplexity for highly45;accurate LLaMA and Falcon LLMs. This makes it possible to run 33B parameter LLM on a single 24 GB consumer GPU without any performance degradation at 1537; speedup thus making powerful LLMs available to consumer without any downsides. SpQR comes with efficient algorithms for both encoding weights into its format as well as decoding them efficiently at runtime. Specifically we provide an efficient GPU inference algorithm for SpQR which yields faster inference than 1645;bit baselines at similar accuracy while enabling memory compression gains of more than 4x.
