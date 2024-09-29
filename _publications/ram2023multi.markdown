---
layout: publication
title: Multi45;task End45;to45;end Training Improves Conversational Recommendation
authors: Ram Naveen, Kuzmin Dima, Chio Ellie Ka In, Alzantot Moustafa Farid, Ontanon Santiago, Jash Ambarish, Li Judith Yue
conference: "Arxiv"
year: 2023
bibkey: ram2023multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.06218"}
tags: ['Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
In this paper we analyze the performance of a multitask end45;to45;end transformer model on the task of conversational recommendations which aim to provide recommendations based on a users explicit preferences expressed in dialogue. While previous works in this area adopt complex multi45;component approaches where the dialogue management and entity recommendation tasks are handled by separate components we show that a unified transformer model based on the T5 text45;to45;text transformer model can perform competitively in both recommending relevant items and generating conversation dialogue. We fine45;tune our model on the ReDIAL conversational movie recommendation dataset and create additional training tasks derived from MovieLens (such as the prediction of movie attributes and related movies based on an input movie) in a multitask learning setting. Using a series of probe studies we demonstrate that the learned knowledge in the additional tasks is transferred to the conversational setting where each task leads to a 937;45;5237; increase in its related probe score.
