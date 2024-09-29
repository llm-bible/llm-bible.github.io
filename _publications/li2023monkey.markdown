---
layout: publication
title: Monkey Image Resolution and Text Label Are Important Things for Large Multi-modal Models
authors: Li Zhang, Yang Biao, Liu Qiang, Ma Zhiyin, Zhang Shuo, Yang Jingxu, Sun Yabo, Liu Yuliang, Bai Xiang
conference: "Arxiv"
year: 2023
bibkey: li2023monkey
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.06607"}
  - {name: "Code", url: "https://github.com/Yuliang-Liu/Monkey"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Multimodal Models', 'RAG', 'Training Techniques']
---
Large Multimodal Models (LMMs) have shown promise in vision-language tasks but struggle with high-resolution input and detailed scene understanding. Addressing these challenges we introduce Monkey to enhance LMM capabilities. Firstly Monkey processes input images by dividing them into uniform patches each matching the size (e.g. 448x448) used in the original training of the well-trained vision encoder. Equipped with individual adapter for each patch Monkey can handle higher resolutions up to 1344x896 pixels enabling the detailed capture of complex visual information. Secondly it employs a multi-level description generation method enriching the context for scene-object associations. This two-part strategy ensures more effective learning from generated data the higher resolution allows for a more detailed capture of visuals which in turn enhances the effectiveness of comprehensive descriptions. Extensive ablative results validate the effectiveness of our designs. Additionally experiments on 18 datasets further demonstrate that Monkey surpasses existing LMMs in many tasks like Image Captioning and various Visual Question Answering formats. Specially in qualitative tests focused on dense text question answering Monkey has exhibited encouraging results compared with GPT4V. Code is available at https://github.com/Yuliang-Liu/Monkey.
