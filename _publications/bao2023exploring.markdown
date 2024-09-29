---
layout: publication
title: "Exploring Iterative Enhancement For Improving Learnersourced Multiple-choice Question Explanations With Large Language Models"
authors: Bao Qiming, Leinonen Juho, Peng Alex Yuxuan, Zhong Wanjun, Gendron Gaël, Pistotti Timothy, Huang Alice, Denny Paul, Witbrock Michael, Liu Jiamou
conference: "Arxiv"
year: 2023
bibkey: bao2023exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.10444"}
tags: ['Applications', 'GPT', 'Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Tools']
---
Large language models exhibit superior capabilities in processing and understanding language yet their applications in educational contexts remain underexplored. Learnersourcing enhances learning by engaging students in creating their own educational content. When learnersourcing multiple-choice questions creating explanations for the solution of a question is a crucial step; it helps other students understand the solution and promotes a deeper understanding of related concepts. However it is often difficult for students to craft effective solution explanations due to limited subject understanding. To help scaffold the task of automated explanation generation we present and evaluate a framework called ILearner-LLM that iteratively enhances the generated explanations for the given questions with large language models. Comprising an explanation generation model and an explanation evaluation model the framework generates high-quality student-aligned explanations by iteratively feeding the quality rating score from the evaluation model back into the instruction prompt of the explanation generation model. Experimental results demonstrate the effectiveness of our ILearner-LLM on LLaMA2-13B and GPT-4 to generate higher quality explanations that are closer to those written by students on five PeerWise datasets. Our findings represent a promising path to enrich the learnersourcing experience for students and to enhance the capabilities of large language models for educational applications.
