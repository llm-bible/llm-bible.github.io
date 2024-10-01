---
layout: publication
title: 'Infovisdial: An Informative Visual Dialogue Dataset By Bridging Large Multimodal And Language Models'
authors: Wen Bingbing, Yang Zhengyuan, Wang Jianfeng, Gan Zhe, Howe Bill, Wang Lijuan
conference: "Arxiv"
year: 2023
bibkey: wen2023informative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.13503"}
tags: ['GPT', 'Model Architecture', 'Multimodal Models', 'Prompting', 'RAG']
---
In this paper, we build a visual dialogue dataset, named InfoVisDial, which provides rich informative answers in each round even with external knowledge related to the visual content. Different from existing datasets where the answer is compact and short, InfoVisDial contains long free-form answers with rich information in each round of dialogue. For effective data collection, the key idea is to bridge the large-scale multimodal model (e.g., GIT) and the language models (e.g., GPT-3). GIT can describe the image content even with scene text, while GPT-3 can generate informative dialogue based on the image description and appropriate prompting techniques. With such automatic pipeline, we can readily generate informative visual dialogue data at scale. Then, we ask human annotators to rate the generated dialogues to filter the low-quality conversations.Human analyses show that InfoVisDial covers informative and diverse dialogue topics: \(54.4\%\) of the dialogue rounds are related to image scene texts, and \(36.7\%\) require external knowledge. Each round's answer is also long and open-ended: \(87.3\%\) of answers are unique with an average length of \(8.9\), compared with \(27.37\%\) and \(2.9\) in VisDial. Last, we propose a strong baseline by adapting the GIT model for the visual dialogue task and fine-tune the model on InfoVisDial. Hopefully, our work can motivate more effort on this direction.
