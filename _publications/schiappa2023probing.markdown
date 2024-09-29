---
layout: publication
title: Probing Conceptual Understanding Of Large Visual45;language Models
authors: Schiappa Madeline, Abdullah Raiyaan, Azad Shehreen, Claypoole Jared, Cogswell Michael, Divakaran Ajay, Rawat Yogesh
conference: "Arxiv"
year: 2023
bibkey: schiappa2023probing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.03659"}
  - {name: "Code", url: "https://tinyurl.com/vlm&#45;robustness&#125;"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Security', 'Transformer']
---
In recent years large visual45;language (V+L) models have achieved great success in various downstream tasks. However it is not well studied whether these models have a conceptual grasp of the visual content. In this work we focus on conceptual understanding of these large V+L models. To facilitate this study we propose novel benchmarking datasets for probing three different aspects of content understanding 1) textit123;relations125; 2) textit123;composition125; and 3) textit123;context125;. Our probes are grounded in cognitive science and help determine if a V+L model can for example determine if snow garnished with a man is implausible or if it can identify beach furniture by knowing it is located on a beach. We experimented with many recent state45;of45;the45;art V+L models and observe that these models mostly textit123;fail to demonstrate125; a conceptual understanding. This study reveals several interesting insights such as that textit123;cross45;attention125; helps learning conceptual understanding and that CNNs are better with textit123;texture and patterns125; while Transformers are better at textit123;color and shape125;. We further utilize some of these insights and investigate a textit123;simple finetuning technique125; that rewards the three conceptual understanding measures with promising initial results. The proposed benchmarks will drive the community to delve deeper into conceptual understanding and foster advancements in the capabilities of large V+L models. The code and dataset is available at url123;https://tinyurl.com/vlm&#45;robustness&#125;
