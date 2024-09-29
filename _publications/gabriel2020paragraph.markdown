---
layout: publication
title: Paragraph45;level Commonsense Transformers With Recurrent Memory
authors: Gabriel Saadia, Bhagavatula Chandra, Shwartz Vered, Bras Ronan Le, Forbes Maxwell, Choi Yejin
conference: "Arxiv"
year: 2020
bibkey: gabriel2020paragraph
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.01486"}
tags: ['Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Transformer']
---
Human understanding of narrative texts requires making commonsense inferences beyond what is stated explicitly in the text. A recent model COMET can generate such implicit commonsense inferences along several dimensions such as pre45; and post45;conditions motivations and mental states of the participants. However COMET was trained on commonsense inferences of short phrases and is therefore discourse45;agnostic. When presented with each sentence of a multi45;sentence narrative it might generate inferences that are inconsistent with the rest of the narrative. We present the task of discourse45;aware commonsense inference. Given a sentence within a narrative the goal is to generate commonsense inferences along predefined dimensions while maintaining coherence with the rest of the narrative. Such large45;scale paragraph45;level annotation is hard to get and costly so we use available sentence45;level annotations to efficiently and automatically construct a distantly supervised corpus. Using this corpus we train PARA45;COMET a discourse45;aware model that incorporates paragraph45;level information to generate coherent commonsense inferences from narratives. PARA45;COMET captures both semantic knowledge pertaining to prior world knowledge and episodic knowledge involving how current events relate to prior and future events in a narrative. Our results show that PARA45;COMET outperforms the sentence45;level baselines particularly in generating inferences that are both coherent and novel.
