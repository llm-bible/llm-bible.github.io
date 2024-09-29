---
layout: publication
title: What In-context Learning quot;learnsquot; In-context Disentangling Task Recognition And Task Learning
authors: Pan Jane, Gao Tianyu, Chen Howard, Chen Danqi
conference: "Arxiv"
year: 2023
bibkey: pan2023what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.09731"}
tags: ['GPT', 'In Context Learning', 'Model Architecture', 'Prompting', 'RAG', 'Training Techniques']
---
Large language models (LLMs) exploit in-context learning (ICL) to solve tasks with only a few demonstrations but its mechanisms are not yet well-understood. Some works suggest that LLMs only recall already learned concepts from pre-training while others hint that ICL performs implicit learning over demonstrations. We characterize two ways through which ICL leverages demonstrations. Task recognition (TR) captures the extent to which LLMs can recognize a task through demonstrations -- even without ground-truth labels -- and apply their pre-trained priors whereas task learning (TL) is the ability to capture new input-label mappings unseen in pre-training. Using a wide range of classification datasets and three LLM families (GPT-3 LLaMA and OPT) we design controlled experiments to disentangle the roles of TR and TL in ICL. We show that (1) models can achieve non-trivial performance with only TR and TR does not further improve with larger models or more demonstrations; (2) LLMs acquire TL as the model scales and TLs performance consistently improves with more demonstrations in context. Our findings unravel two different forces behind ICL and we advocate for discriminating them in future ICL research due to their distinct nature.
