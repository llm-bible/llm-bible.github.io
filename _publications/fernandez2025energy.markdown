---
layout: publication
title: 'Energy Considerations Of Large Language Model Inference And Efficiency Optimizations'
authors: Jared Fernandez, Clara Na, Vashisth Tiwari, Yonatan Bisk, Sasha Luccioni, Emma Strubell
conference: "Arxiv"
year: 2025
bibkey: fernandez2025energy
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.17674'}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Applications', 'Training Techniques', 'Tools', 'Reinforcement Learning']
---
As large language models (LLMs) scale in size and adoption, their
computational and environmental costs continue to rise. Prior benchmarking
efforts have primarily focused on latency reduction in idealized settings,
often overlooking the diverse real-world inference workloads that shape energy
use. In this work, we systematically analyze the energy implications of common
inference efficiency optimizations across diverse Natural Language Processing
(NLP) and generative Artificial Intelligence (AI) workloads, including
conversational AI and code generation. We introduce a modeling approach that
approximates real-world LLM workflows through a binning strategy for
input-output token distributions and batch size variations. Our empirical
analysis spans software frameworks, decoding strategies, GPU architectures,
online and offline serving settings, and model parallelism configurations. We
show that the effectiveness of inference optimizations is highly sensitive to
workload geometry, software stack, and hardware accelerators, demonstrating
that naive energy estimates based on FLOPs or theoretical GPU utilization
significantly underestimate real-world energy consumption. Our findings reveal
that the proper application of relevant inference efficiency optimizations can
reduce total energy use by up to 73% from unoptimized baselines. These insights
provide a foundation for sustainable LLM deployment and inform energy-efficient
design strategies for future AI infrastructure.
