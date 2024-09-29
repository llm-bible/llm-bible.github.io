---
layout: publication
title: Weak45;to45;strong Reasoning
authors: Yang Yuqing, Ma Yan, Liu Pengfei
conference: "Arxiv"
year: 2024
bibkey: yang2024weak
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.13647"}
  - {name: "Code", url: "https://github.com/GAIR&#45;NLP/weak&#45;to&#45;strong&#45;reasoning&#125;"}
tags: ['Efficiency And Optimization', 'Has Code', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
When large language models (LLMs) exceed human45;level capabilities it becomes increasingly challenging to provide full45;scale and accurate supervisions for these models. Weak45;to45;strong learning which leverages a less capable model to unlock the latent abilities of a stronger model proves valuable in this context. Yet the efficacy of this approach for complex reasoning tasks is still untested. Furthermore tackling reasoning tasks under the weak45;to45;strong setting currently lacks efficient methods to avoid blindly imitating the weak supervisor including its errors. In this paper we introduce a progressive learning framework that enables the strong model to autonomously refine its training data without requiring input from either a more advanced model or human45;annotated data. This framework begins with supervised fine45;tuning on a selective small but high45;quality dataset followed by preference optimization on contrastive samples identified by the strong model itself. Extensive experiments on the GSM8K and MATH datasets demonstrate that our method significantly enhances the reasoning capabilities of Llama245;70b using three separate weak models. This method is further validated in a forward45;looking experimental setup where Llama345;8b45;instruct effectively supervises Llama345;70b on the highly challenging OlympicArena dataset. This work paves the way for a more scalable and sophisticated strategy to enhance AI reasoning powers. All relevant code and resources are available in url123;https://github.com/GAIR&#45;NLP/weak&#45;to&#45;strong&#45;reasoning&#125;.
