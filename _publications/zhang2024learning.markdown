---
layout: publication
title: Wings Learning Multimodal Llms Without Text45;only Forgetting
authors: Zhang Yi-kai, Lu Shiyin, Li Yang, Ma Yanqing, Chen Qing-guo, Xu Zhao, Luo Weihua, Zhang Kaifu, Zhan De-chuan, Ye Han-jia
conference: "Arxiv"
year: 2024
bibkey: zhang2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.03496"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning']
---
Multimodal large language models (MLLMs) initiated with a trained LLM first align images with text and then fine45;tune on multimodal mixed inputs. However the MLLM catastrophically forgets the text45;only instructions which do not include images and can be addressed within the initial LLM. In this paper we present Wings a novel MLLM that excels in both text45;only dialogues and multimodal comprehension. Analyzing MLLM attention in multimodal instructions reveals that text45;only forgetting is related to the attention shifts from pre45;image to post45;image text. From that we construct extra modules that act as the boosted learner to compensate for the attention shift. The complementary visual and textual learners like wings on either side are connected in parallel within each layers attention block. Initially image and text inputs are aligned with visual learners operating alongside the main attention balancing focus on visual elements. Textual learners are later collaboratively integrated with attention45;based routing to blend the outputs of the visual and textual learners. We design the Low45;Rank Residual Attention (LoRRA) to guarantee high efficiency for learners. Our experimental results demonstrate that Wings outperforms equally45;scaled MLLMs in both text45;only and visual question45;answering tasks. On a newly constructed Interleaved Image45;Text (IIT) benchmark Wings exhibits superior performance from text45;only45;rich to multimodal45;rich question45;answering tasks.
