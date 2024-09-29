---
layout: publication
title: 'Small Language Models Learn Enhanced Reasoning Skills From Medical Textbooks'
authors: Kim Hyunjae, Hwang Hyeon, Lee Jiwoo, Park Sihyeon, Kim Dain, Lee Taewhoo, Yoon Chanwoong, Sohn Jiwoong, Choi Donghee, Kang Jaewoo
conference: "Arxiv"
year: 2024
bibkey: kim2024small
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.00376"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Security']
---
While recent advancements in commercial large language models (LM) have shown promising results in medical tasks their closed-source nature poses significant privacy and security concerns hindering their widespread use in the medical field. Despite efforts to create open-source models their limited parameters often result in insufficient multi-step reasoning capabilities required for solving complex medical problems. To address this we introduce Meerkat a new family of medical AI systems ranging from 7 to 70 billion parameters. The models were trained using our new synthetic dataset consisting of high-quality chain-of-thought reasoning paths sourced from 18 medical textbooks along with diverse instruction-following datasets. Our systems achieved remarkable accuracy across six medical benchmarks surpassing the previous best models such as MediTron and BioMistral and GPT-3.5 by a large margin. Notably Meerkat-7B surpassed the passing threshold of the United States Medical Licensing Examination (USMLE) for the first time for a 7B-parameter model while Meerkat-70B outperformed GPT-4 by an average of 1.337;. Additionally Meerkat-70B correctly diagnosed 21 out of 38 complex clinical cases outperforming humans 13.8 and closely matching GPT-4s 21.8. Our systems offered more detailed free-form responses to clinical queries compared to existing small models approaching the performance level of large commercial models. This significantly narrows the performance gap with large LMs showcasing its effectiveness in addressing complex medical challenges.
