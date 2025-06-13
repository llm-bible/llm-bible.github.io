---
layout: publication
title: 'Livevlm: Efficient Online Video Understanding Via Streaming-oriented KV Cache And Retrieval'
authors: Zhenyu Ning, Guangda Liu, Qihao Jin, Wenchao Ding, Minyi Guo, Jieru Zhao
conference: "Arxiv"
year: 2025
bibkey: ning2025efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.15269"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Prompting', 'Applications']
---
Recent developments in Video Large Language Models (Video LLMs) have enabled models to process long video sequences and demonstrate remarkable performance. Nonetheless, studies predominantly focus on offline video question answering, neglecting memory usage and response speed that are essential in various real-world applications, such as Deepseek services, autonomous driving, and robotics. To mitigate these challenges, we propose \\(\textbf\{LiveVLM\}\\), a training-free framework specifically designed for streaming, online video understanding and real-time interaction. Unlike existing works that process videos only after one question is posed, LiveVLM constructs an innovative streaming-oriented KV cache to process video streams in real-time, retain long-term video details and eliminate redundant KVs, ensuring prompt responses to user queries. For continuous video streams, LiveVLM generates and compresses video key-value tensors (video KVs) to reserve visual information while improving memory efficiency. Furthermore, when a new question is proposed, LiveVLM incorporates an online question-answering process that efficiently fetches both short-term and long-term visual information, while minimizing interference from redundant context. Extensive experiments demonstrate that LiveVLM enables the foundation LLaVA-OneVision model to process 44\\(\times\\) number of frames on the same device, and achieves up to 5\\(\times\\) speedup in response speed compared with SoTA online methods at an input of 256 frames, while maintaining the same or better model performance.
