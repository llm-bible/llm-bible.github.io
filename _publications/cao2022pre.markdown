---
layout: publication
title: "Pre-trained Neural Language Models For Automatic Mobile App User Feedback Answer Generation"
authors: Cao Yue, Fard Fatemeh H.
conference: "Arxiv"
year: 2022
bibkey: cao2022pre
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2202.02294"}
tags: ['Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Studies show that developers answers to the mobile app users feedbacks on app stores can increase the apps star rating. To help app developers generate answers that are related to the users issues recent studies develop models to generate the answers automatically. Aims The app response generation models use deep neural networks and require training data. Pre-Trained neural language Models (PTM) used in Natural Language Processing (NLP) take advantage of the information they learned from a large corpora in an unsupervised manner and can reduce the amount of required training data. In this paper we evaluate PTMs to generate replies to the mobile app user feedbacks. Method We train a Transformer model from scratch and fine-tune two PTMs to evaluate the generated responses which are compared to RRGEN a current app response model. We also evaluate the models with different portions of the training data. Results The results on a large dataset evaluated by automatic metrics show that PTMs obtain lower scores than the baselines. However our human evaluation confirms that PTMs can generate more relevant and meaningful responses to the posted feedbacks. Moreover the performance of PTMs has less drop compared to other models when the amount of training data is reduced to 1/3. Conclusion PTMs are useful in generating responses to app reviews and are more robust models to the amount of training data provided. However the prediction time is 19X than RRGEN. This study can provide new avenues for research in adapting the PTMs for analyzing mobile app user feedbacks. Index Terms-mobile app user feedback analysis neural pre-trained language models automatic answer generation
