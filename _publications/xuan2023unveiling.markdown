---
layout: publication
title: Pink Unveiling The Power Of Referential Comprehension For Multi45;modal Llms
authors: Xuan Shiyu, Guo Qingpei, Yang Ming, Zhang Shiliang
conference: "Arxiv"
year: 2023
bibkey: xuan2023unveiling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.00582"}
  - {name: "Code", url: "https://github.com/SY&#45;Xuan/Pink"}
tags: ['Applications', 'Has Code', 'RAG', 'Tools', 'Training Techniques']
---
Multi45;modal Large Language Models (MLLMs) have shown remarkable capabilities in various multi45;modal tasks. Nevertheless their performance in fine45;grained image understanding tasks is still limited. To address this issue this paper proposes a new framework to enhance the fine45;grained image understanding abilities of MLLMs. Specifically we present a new method for constructing the instruction tuning dataset at a low cost by leveraging annotations in existing datasets. A self45;consistent bootstrapping method is also introduced to extend existing dense object annotations into high45;quality referring45;expression45;bounding45;box pairs. These methods enable the generation of high45;quality instruction data which includes a wide range of fundamental abilities essential for fine45;grained image perception. Moreover we argue that the visual encoder should be tuned during instruction tuning to mitigate the gap between full image perception and fine45;grained image perception. Experimental results demonstrate the superior performance of our method. For instance our model exhibits a 5.237; accuracy improvement over Qwen45;VL on GQA and surpasses the accuracy of Kosmos45;2 by 24.737; on RefCOCO95;val. We have also attained the top rank on the leaderboard of MMBench. This promising performance is achieved by training on only publicly available data making it easily reproducible. The models datasets and codes are publicly available at https://github.com/SY&#45;Xuan/Pink.
