---
layout: publication
title: Ganprompt Enhancing Robustness In Llm-based Recommendations With Gan-enhanced Diversity Prompts
authors: Li Xinyu, Zhao Chuang, Zhao Hongke, Wu Likang, He Ming
conference: "Arxiv"
year: 2024
bibkey: li2024ganprompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.09671"}
tags: ['Ethics And Bias', 'Prompting', 'Security', 'Tools']
---
In recent years LLM has demonstrated remarkable proficiency in comprehending and generating natural language with a growing prevalence in the domain of recommender systems. However LLM continues to face a significant challenge in that it is highly susceptible to the influence of prompt words. This inconsistency in response to minor alterations in prompt input may compromise the accuracy and resilience of recommendation models. To address this issue this paper proposes GANPrompt a multi-dimensional large language model prompt diversity framework based on Generative Adversarial Networks (GANs). The framework enhances the models adaptability and stability to diverse prompts by integrating GAN generation techniques with the deep semantic understanding capabilities of LLMs. GANPrompt first trains a generator capable of producing diverse prompts by analysing multidimensional user behavioural data. These diverse prompts are then used to train the LLM to improve its performance in the face of unseen prompts. Furthermore to ensure a high degree of diversity and relevance of the prompts this study introduces a mathematical theory-based diversity constraint mechanism that optimises the generated prompts to ensure that they are not only superficially distinct but also semantically cover a wide range of user intentions. Through extensive experiments on multiple datasets we demonstrate the effectiveness of the proposed framework especially in improving the adaptability and robustness of recommender systems in complex and dynamic environments. The experimental results demonstrate that GANPrompt yields substantial enhancements in accuracy and robustness relative to existing state-of-the-art methodologies.
