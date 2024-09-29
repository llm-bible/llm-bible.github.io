---
layout: publication
title: Pose Efficient Context Window Extension Of Llms Via Positional Skip45;wise Training
authors: Zhu Dawei, Yang Nan, Wang Liang, Song Yifan, Wu Wenhao, Wei Furu, Li Sujian
conference: "Arxiv"
year: 2023
bibkey: zhu2023efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.10400"}
tags: ['Ethics And Bias', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Large Language Models (LLMs) are trained with a pre45;defined context length restricting their use in scenarios requiring long inputs. Previous efforts for adapting LLMs to a longer length usually requires fine45;tuning with this target length (Full45;length fine45;tuning) suffering intensive training cost. To decouple train length from target length for efficient context window extension we propose Positional Skip45;wisE (PoSE) training that smartly simulates long inputs using a fixed context window. This is achieved by first dividing the original context window into several chunks then designing distinct skipping bias terms to manipulate the position indices of each chunk. These bias terms and the lengths of each chunk are altered for every training example allowing the model to adapt to all positions within target length. Experimental results show that PoSE greatly reduces memory and time overhead compared with Full45;length fine45;tuning with minimal impact on performance. Leveraging this advantage we have successfully extended the LLaMA model to 128k tokens using a 2k training context window. Furthermore we empirically confirm that PoSE is compatible with all RoPE45;based LLMs and position interpolation strategies. Notably our method can potentially support infinite length limited only by memory usage in inference. With ongoing progress for efficient inference we believe PoSE can further scale the context window beyond 128k.
