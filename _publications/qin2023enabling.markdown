---
layout: publication
title: Enabling On45;device Large Language Model Personalization With Self45;supervised Data Selection And Synthesis
authors: Qin Ruiyang, Xia Jun, Jia Zhenge, Jiang Meng, Abbasi Ahmed, Zhou Peipei, Hu Jingtong, Shi Yiyu
conference: "Arxiv"
year: 2023
bibkey: qin2023enabling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.12275"}
tags: ['Ethics And Bias', 'RAG', 'Tools']
---
After a large language model (LLM) is deployed on edge devices it is desirable for these devices to learn from user45;generated conversation data to generate user45;specific and personalized responses in real45;time. However user45;generated data usually contains sensitive and private information and uploading such data to the cloud for annotation is not preferred if not prohibited. While it is possible to obtain annotation locally by directly asking users to provide preferred responses such annotations have to be sparse to not affect user experience. In addition the storage of edge devices is usually too limited to enable large45;scale fine45;tuning with full user45;generated data. It remains an open question how to enable on45;device LLM personalization considering sparse annotation and limited on45;device storage. In this paper we propose a novel framework to select and store the most representative data online in a self45;supervised way. Such data has a small memory footprint and allows infrequent requests of user annotations for further fine45;tuning. To enhance fine45;tuning quality multiple semantically similar pairs of question texts and expected responses are generated using the LLM. Our experiments show that the proposed framework achieves the best user45;specific content45;generating capability (accuracy) and fine45;tuning speed (performance) compared with vanilla baselines. To the best of our knowledge this is the very first on45;device LLM personalization framework.
