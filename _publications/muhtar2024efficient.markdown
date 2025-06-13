---
layout: publication
title: 'Streamadapter: Efficient Test Time Adaptation From Contextual Streams'
authors: Dilxat Muhtar, Yelong Shen, Yaming Yang, Xiaodong Liu, Yadong Lu, Jianfeng Liu, Yuefeng Zhan, Hao Sun, Weiwei Deng, Feng Sun, Xueliang Zhang, Jianfeng Gao, Weizhu Chen, Qi Zhang
conference: "Arxiv"
year: 2024
bibkey: muhtar2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.09289"}
tags: ['Prompting', 'Model Architecture', 'In-Context Learning']
---
In-context learning (ICL) allows large language models (LLMs) to adapt to new
tasks directly from the given demonstrations without requiring gradient
updates. While recent advances have expanded context windows to accommodate
more demonstrations, this approach increases inference costs without
necessarily improving performance. To mitigate these issues, We propose
StreamAdapter, a novel approach that directly updates model parameters from
context at test time, eliminating the need for explicit in-context
demonstrations. StreamAdapter employs context mapping and weight absorption
mechanisms to dynamically transform ICL demonstrations into parameter updates
with minimal additional parameters. By reducing reliance on numerous in-context
examples, StreamAdapter significantly reduce inference costs and allows for
efficient inference with constant time complexity, regardless of demonstration
count. Extensive experiments across diverse tasks and model architectures
demonstrate that StreamAdapter achieves comparable or superior adaptation
capability to ICL while requiring significantly fewer demonstrations. The
superior task adaptation and context encoding capabilities of StreamAdapter on
both language understanding and generation tasks provides a new perspective for
adapting LLMs at test time using context, allowing for more efficient
adaptation across scenarios and more cost-effective inference
