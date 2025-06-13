---
layout: publication
title: 'Beavertalk: Oregon State University''s IWSLT 2025 Simultaneous Speech Translation System'
authors: Matthew Raffel, Victor Agostinelli, Lizhong Chen
conference: "Arxiv"
year: 2025
bibkey: raffel2025oregon
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.24016"}
tags: ['Fine-Tuning', 'INTERSPEECH', 'RAG', 'Prompting', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'SLT']
---
This paper discusses the construction, fine-tuning, and deployment of BeaverTalk, a cascaded system for speech-to-text translation as part of the IWSLT 2025 simultaneous translation task. The system architecture employs a VAD segmenter for breaking a speech stream into segments, Whisper Large V2 for automatic speech recognition (ASR), and Gemma 3 12B for simultaneous translation. Regarding the simultaneous translation LLM, it is fine-tuned via low-rank adaptors (LoRAs) for a conversational prompting strategy that leverages a single prior-sentence memory bank from the source language as context. The cascaded system participated in the English\\(\rightarrow\\)German and English\\(\rightarrow\\)Chinese language directions for both the low and high latency regimes. In particular, on the English\\(\rightarrow\\)German task, the system achieves a BLEU of 24.64 and 27.83 at a StreamLAAL of 1837.86 and 3343.73, respectively. Then, on the English\\(\rightarrow\\)Chinese task, the system achieves a BLEU of 34.07 and 37.23 at a StreamLAAL of 2216.99 and 3521.35, respectively.
