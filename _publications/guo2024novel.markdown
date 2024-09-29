---
layout: publication
title: A Novel Paradigm Boosting Translation Capabilities of Large Language Models
authors: Guo Jiaxin, Yang Hao, Li Zongyao, Wei Daimeng, Shang Hengchao, Chen Xiaoyu
conference: "Arxiv"
year: 2024
bibkey: guo2024novel
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.11430"}
tags: ['Applications', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
This paper presents a study on strategies to enhance the translation capabilities of large language models (LLMs) in the context of machine translation (MT) tasks. The paper proposes a novel paradigm consisting of three stages Secondary Pre-training using Extensive Monolingual Data Continual Pre-training with Interlinear Text Format Documents and Leveraging Source-Language Consistent Instruction for Supervised Fine-Tuning. Previous research on LLMs focused on various strategies for supervised fine-tuning (SFT) but their effectiveness has been limited. While traditional machine translation approaches rely on vast amounts of parallel bilingual data our paradigm highlights the importance of using smaller sets of high-quality bilingual data. We argue that the focus should be on augmenting LLMs cross-lingual alignment abilities during pre-training rather than solely relying on extensive bilingual data during SFT. Experimental results conducted using the Llama2 model particularly on Chinese-Llama2 after monolingual augmentation demonstrate the improved translation capabilities of LLMs. A significant contribution of our approach lies in Stage2 Continual Pre-training with Interlinear Text Format Documents which requires less than 1B training data making our method highly efficient. Additionally in Stage3 we observed that setting instructions consistent with the source language benefits the supervised fine-tuning process. Experimental results demonstrate that our approach surpasses previous work and achieves superior performance compared to models such as NLLB-54B and GPT3.5-text-davinci-003 despite having a significantly smaller parameter count of only 7B or 13B. This achievement establishes our method as a pioneering strategy in the field of machine translation.
