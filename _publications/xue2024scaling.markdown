---
layout: publication
title: Longvila Scaling Long45;context Visual Language Models For Long Videos
authors: Xue Fuzhao, Chen Yukang, Li Dacheng, Hu Qinghao, Zhu Ligeng, Li Xiuyu, Fang Yunhao, Tang Haotian, Yang Shang, Liu Zhijian, He Ethan, Yin Hongxu, Molchanov Pavlo, Kautz Jan, Fan Linxi, Zhu Yuke, Lu Yao, Han Song
conference: "Arxiv"
year: 2024
bibkey: xue2024scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.10188"}
tags: ['Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Long45;context capability is critical for multi45;modal foundation models especially for long video understanding. We introduce LongVILA a full45;stack solution for long45;context visual45;language models by co45;designing the algorithm and system. For model training we upgrade existing VLMs to support long video understanding by incorporating two additional stages i.e. long context extension and long supervised fine45;tuning. However training on long video is computationally and memory intensive. We introduce the long45;context Multi45;Modal Sequence Parallelism (MM45;SP) system that efficiently parallelizes long video training and inference enabling 2M context length training on 256 GPUs without any gradient checkpointing. LongVILA efficiently extends the number of video frames of VILA from 8 to 1024 improving the long video captioning score from 2.00 to 3.26 (out of 5) achieving 99.537; accuracy in 140045;frame (274k context length) video needle45;in45;a45;haystack. LongVILA45;8B demonstrates consistent accuracy improvements on long videos in the VideoMME benchmark as the number of frames increases. Besides MM45;SP is 2.1x 45; 5.7x faster than ring sequence parallelism and 1.1x 45; 1.4x faster than Megatron with context parallelism + tensor parallelism. Moreover it seamlessly integrates with Hugging Face Transformers.
