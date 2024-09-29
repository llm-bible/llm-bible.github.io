---
layout: publication
title: Mammoth2 Scaling Instructions From The Web
authors: Yue Xiang, Zheng Tuney, Zhang Ge, Chen Wenhu
conference: "Arxiv"
year: 2024
bibkey: yue2024scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.03548"}
tags: ['Distillation', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Training Techniques']
---
Instruction tuning improves the reasoning abilities of large language models (LLMs) with data quality and scalability being the crucial factors. Most instruction tuning data come from human crowd45;sourcing or GPT45;4 distillation. We propose a paradigm to efficiently harvest 10 million naturally existing instruction data from the pre45;training web corpus to enhance LLM reasoning. Our approach involves (1) recalling relevant documents (2) extracting instruction45;response pairs and (3) refining the extracted pairs using open45;source LLMs. Fine45;tuning base LLMs on this dataset we build MAmmoTH2 models which significantly boost performance on reasoning benchmarks. Notably MAmmoTH245;7Bs (Mistral) performance increases from 1137; to 36.737; on MATH and from 3637; to 68.437; on GSM8K without training on any in45;domain data. Further training MAmmoTH2 on public instruction tuning datasets yields MAmmoTH245;Plus achieving state45;of45;the45;art performance on several reasoning and chatbot benchmarks. Our work demonstrates how to harvest large45;scale high45;quality instruction data without costly human annotation or GPT45;4 distillation providing a new paradigm for building better instruction tuning data.
