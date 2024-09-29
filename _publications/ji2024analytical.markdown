---
layout: publication
title: ANAH Analytical Annotation Of Hallucinations In Large Language Models
authors: Ji Ziwei, Gu Yuzhe, Zhang Wenwei, Lyu Chengqi, Lin Dahua, Chen Kai
conference: "Arxiv"
year: 2024
bibkey: ji2024analytical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.20315"}
tags: ['Applications', 'GPT', 'Model Architecture', 'RAG']
---
Reducing the textit123;hallucination125; problem of Large Language Models (LLMs) is crucial for their wide applications. A comprehensive and fine45;grained measurement of the hallucination is the first key step for the governance of this issue but is under45;explored in the community. Thus we present textbf123;ANAH125; a bilingual dataset that offers textbf123;AN125;alytical textbf123;A125;nnotation of textbf123;H125;allucinations in LLMs within Generative Question Answering. Each answer sentence in our dataset undergoes rigorous annotation involving the retrieval of a reference fragment the judgment of the hallucination type and the correction of hallucinated content. ANAH consists of ~12k sentence45;level annotations for ~4.3k LLM responses covering over 700 topics constructed by a human45;in45;the45;loop pipeline. Thanks to the fine granularity of the hallucination annotations we can quantitatively confirm that the hallucinations of LLMs progressively accumulate in the answer and use ANAH to train and evaluate hallucination annotators. We conduct extensive experiments on studying generative and discriminative annotators and show that although current open45;source LLMs have difficulties in fine45;grained hallucination annotation the generative annotator trained with ANAH can surpass all open45;source LLMs and GPT45;3.5 obtain performance competitive with GPT45;4 and exhibits better generalization ability on unseen questions.
