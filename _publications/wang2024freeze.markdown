---
layout: publication
title: 'Freeze-omni: A Smart And Low Latency Speech-to-speech Dialogue Model With Frozen LLM'
authors: Xiong Wang, Yangze Li, Chaoyou Fu, Yunhang Shen, Lei Xie, Ke Li, Xing Sun, Long Ma
conference: "Arxiv"
year: 2024
bibkey: wang2024freeze
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.00774"}
tags: ['Agentic', 'GPT', 'Tools', 'Applications', 'Model Architecture', 'Training Techniques', 'Multimodal Models']
---
Rapidly developing large language models (LLMs) have brought tremendous
intelligent applications. Especially, the GPT-4o's excellent duplex speech
interaction ability has brought impressive experience to users. Researchers
have recently proposed several multi-modal LLMs in this direction that can
achieve user-agent speech-to-speech conversations. This paper proposes a novel
speech-text multimodal LLM architecture called Freeze-Omni. Our main
contribution is that the speech input and output modalities can be easily
connected to a textual LLM while keeping the LLM's parameters frozen throughout
the training process. We design a three-stage training strategy for modeling
both the speech input and output, enabling Freeze-Omni to obtain
speech-to-speech conversation ability using text-speech paired data (such as
ASR and TTS data) and only 60,000 multi-round text Q&A data on 8 GPUs.
Moreover, we can effectively ensure that the intelligence of the Freeze-Omni in
the speech modality is at the same level compared with that in the text
modality of its backbone LLM, while achieving low latency end-to-end spoken
response. In addition, we also designed a method to achieve duplex dialogue
ability through multi-task training, giving Freeze-Omni a more natural style of
dialogue ability between users and agents. In summary, Freeze-Omni holds great
potential to conduct speech-to-speech dialogue based on a multimodal LLM under
the condition of a frozen LLM, avoiding the catastrophic forgetting problem
caused by limited data and training resources.
