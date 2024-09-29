---
layout: publication
title: Mammoth&#58; Building Math Generalist Models Through Hybrid Instruction Tuning
authors: Yue Xiang, Qu Xingwei, Zhang Ge, Fu Yao, Huang Wenhao, Sun Huan, Su Yu, Chen Wenhu
conference: "Arxiv"
year: 2023
bibkey: yue2023building
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.05653"}
tags: ['Efficiency And Optimization', 'GPT', 'Model Architecture', 'RAG']
---
We introduce MAmmoTH a series of open-source large language models (LLMs) specifically tailored for general math problem-solving. The MAmmoTH models are trained on MathInstruct our meticulously curated instruction tuning dataset. MathInstruct is compiled from 13 math datasets with intermediate rationales six of which have rationales newly curated by us. It presents a unique hybrid of chain-of-thought (CoT) and program-of-thought (PoT) rationales and also ensures extensive coverage of diverse fields in math. The hybrid of CoT and PoT not only unleashes the potential of tool use but also allows different thought processes for different math problems. As a result the MAmmoTH series substantially outperform existing open-source models on nine mathematical reasoning datasets across all scales with an average accuracy gain between 1637; and 3237;. Remarkably our MAmmoTH-7B model reaches 3337; on MATH (a competition-level dataset) which exceeds the best open-source 7B model (WizardMath) by 2337; and the MAmmoTH-34B model achieves 4437; accuracy on MATH even surpassing GPT-4s CoT result. Our work underscores the importance of diverse problem coverage and the use of hybrid rationales in developing superior math generalist models.
