---
layout: publication
title: TOPA Extend Large Language Models For Video Understanding Via Text45;only Pre45;alignment
authors: Li Wei, Fan Hehe, Wong Yongkang, Kankanhalli Mohan, Yang Yi
conference: "Arxiv"
year: 2024
bibkey: li2024extend
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.13911"}
tags: ['Agentic', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
Recent advancements in image understanding have benefited from the extensive use of web image45;text pairs. However video understanding remains a challenge despite the availability of substantial web video45;text data. This difficulty primarily arises from the inherent complexity of videos and the inefficient language supervision in recent web45;collected video45;text datasets. In this paper we introduce Text45;Only Pre45;Alignment (TOPA) a novel approach to extend large language models (LLMs) for video understanding without the need for pre45;training on real video data. Specifically we first employ an advanced LLM to automatically generate Textual Videos comprising continuous textual frames along with corresponding annotations to simulate real video45;text data. Then these annotated textual videos are used to pre45;align a language45;only LLM with the video modality. To bridge the gap between textual and real videos we employ the CLIP model as the feature extractor to align image and text modalities. During text45;only pre45;alignment the continuous textual frames encoded as a sequence of CLIP text features are analogous to continuous CLIP image features thus aligning the LLM with real video representation. Extensive experiments including zero45;shot evaluation and finetuning on various video understanding tasks demonstrate that TOPA is an effective and efficient framework for aligning video content with LLMs. In particular without training on any video data the TOPA45;Llama245;13B model achieves a Top45;1 accuracy of 51.037; on the challenging long45;form video understanding benchmark Egoschema. This performance surpasses previous video45;text pre45;training approaches and proves competitive with recent GPT45;3.545;based video agents.
