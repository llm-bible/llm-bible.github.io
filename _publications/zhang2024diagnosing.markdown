---
layout: publication
title: 'Eventhallusion: Diagnosing Event Hallucinations In Video Llms'
authors: Jiacheng Zhang, Yang Jiao, Shaoxiang Chen, Na Zhao, Zhiyu Tan, Hao Li, Jingjing Chen
conference: "Arxiv"
year: 2024
bibkey: zhang2024diagnosing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.16597"}
  - {name: "Code", url: "https://github.com/Stevetich/EventHallusion"}
tags: ['Ethics and Bias', 'Multimodal Models', 'Has Code']
---
Recently, Multimodal Large Language Models (MLLMs) have made significant
progress in the video comprehension field. Despite remarkable content reasoning
and instruction following capabilities they demonstrated, the hallucination
problem of these VideoLLMs is less explored compared with its counterpart in
the image domain. To mitigate this gap, we propose EventHallusion, a novel
benchmark that focuses on assessing the VideoLLMs' hallucination toward event,
the crux of video analysis. From a hallucination attribution perspective, our
EventHallusion benchmark is curated to assess a VideoLLM's susceptibility
toward language priors and vision-language biases. On the other hand, we also
propose a simple yet effective method, called Temporal Contrastive Decoding
(TCD), to tackle the hallucination problems of VideoLLMs. The proposed TCD
method rectifies the model's bias toward its priors during the decoding stage
by comparing the original video with a modified version, in which temporal cues
are disrupted. Through comprehensive evaluation of eight open-source and two
closed-source VideoLLMs on the proposed EventHallusion benchmark, we observe
that the open-source models suffer significantly from hallucination problems,
whereas the closed-source ones perform markedly better. By further equipping
open-source VideoLLMs with the proposed TCD approach, evident performance
improvements are achieved across most metrics in the EventHallusion benchmark.
Our codes and benchmark data are available at
https://github.com/Stevetich/EventHallusion.
