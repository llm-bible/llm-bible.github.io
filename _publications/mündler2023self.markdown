---
layout: publication
title: Self45;contradictory Hallucinations Of Large Language Models Evaluation Detection And Mitigation
authors: Mündler Niels, He Jingxuan, Jenko Slobodan, Vechev Martin
conference: "Arxiv"
year: 2023
bibkey: mündler2023self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.15852"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Model Architecture', 'Prompting', 'Tools']
---
Large language models (large LMs) are susceptible to producing text that contains hallucinated content. An important instance of this problem is self45;contradiction where the LM generates two contradictory sentences within the same context. In this work we present a comprehensive investigation into self45;contradiction for various instruction45;tuned LMs covering evaluation detection and mitigation. Our primary evaluation task is open45;domain text generation but we also demonstrate the applicability of our approach to shorter question answering. Our analysis reveals the prevalence of self45;contradictions e.g. in 17.737; of all sentences produced by ChatGPT. We then propose a novel prompting45;based framework designed to effectively detect and mitigate self45;contradictions. Our detector achieves high accuracy e.g. around 8037; F1 score when prompting ChatGPT. The mitigation algorithm iteratively refines the generated text to remove contradictory information while preserving text fluency and informativeness. Importantly our entire framework is applicable to black45;box LMs and does not require retrieval of external knowledge. Rather our method complements retrieval45;based methods as a large portion of self45;contradictions (e.g. 35.237; for ChatGPT) cannot be verified using online text. Our approach is practically effective and has been released as a push45;button tool to benefit the public at https://chatprotect.ai/.
