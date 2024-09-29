---
layout: publication
title: CODE Contrasting Self45;generated Description To Combat Hallucination In Large Multi45;modal Models
authors: Junho Kim, Hyunjun Kim, Yeonju Kim, Yong Man Ro
conference: "Arxiv"
year: 2024
bibkey: kim2024contrasting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2406.01920v1"}
tags: ['Applications', 'RAG', 'Tools', 'Training Techniques']
---
Large Multi45;modal Models (LMMs) have recently demonstrated remarkable abilities in visual context understanding and coherent response generation. However alongside these advancements the issue of hallucinations has emerged as a significant challenge producing erroneous responses that are unrelated to the visual contents. In this paper we introduce a novel contrastive45;based decoding method COuntering DEscription Contrastive Decoding (CODE) which leverages self45;generated descriptions as contrasting references during the decoding phase of LMMs to address hallucination issues. CODE utilizes the comprehensive descriptions from model itself as visual counterpart to correct and improve response alignment with actual visual content. By dynamically adjusting the information flow and distribution of next45;token predictions in the LMMs vocabulary CODE enhances the coherence and informativeness of generated responses. Extensive experiments demonstrate that our method significantly reduces hallucinations and improves cross45;modal consistency across various benchmarks and cutting45;edge LMMs. Our method provides a simple yet effective decoding strategy that can be integrated to existing LMM frameworks without additional training.
