---
layout: publication
title: PEARL Personalizing Large Language Model Writing Assistants With Generation-calibrated Retrievers
authors: Mysore Sheshera, Lu Zhuoran, Wan Mengting, Yang Longqi, Menezes Steve, Baghaee Tina, Gonzalez Emmanuel Barajas, Neville Jennifer, Safavi Tara
conference: "Arxiv"
year: 2023
bibkey: mysore2023pearl
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09180"}
tags: ['Efficiency And Optimization', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Powerful large language models have facilitated the development of writing assistants that promise to significantly improve the quality and efficiency of composition and communication. However a barrier to effective assistance is the lack of personalization in LLM outputs to the authors communication style and specialized knowledge. In this paper we address this challenge by proposing PEARL a retrieval-augmented LLM writing assistant personalized with a generation-calibrated retriever. Our retriever is trained to select historic user-authored documents for prompt augmentation such that they are likely to best personalize LLM generations for a user request. We propose two key novelties for training our retriever 1) A training data selection method that identifies user requests likely to benefit from personalization and documents that provide that benefit; and 2) A scale-calibrating KL-divergence objective that ensures that our retriever closely tracks the benefit of a document for personalized generation. We demonstrate the effectiveness of PEARL in generating personalized workplace social media posts and Reddit comments. Finally we showcase the potential of a generation-calibrated retriever to double as a performance predictor and further improve low-quality generations via LLM chaining.
