---
layout: publication
title: No Thats Not What I Meant Handling Third Position Repair In Conversational Question Answering
authors: Balaraman Vevake, Eshghi Arash, Konstas Ioannis, Papaioannou Ioannis
conference: "Arxiv"
year: 2023
bibkey: balaraman2023no
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.16689"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Training Techniques']
---
The ability to handle miscommunication is crucial to robust and faithful conversational AI. People usually deal with miscommunication immediately as they detect it using highly systematic interactional mechanisms called repair. One important type of repair is Third Position Repair (TPR) whereby a speaker is initially misunderstood but then corrects the misunderstanding as it becomes apparent after the addressees erroneous response. Here we collect and publicly release Repair45;QA the first large dataset of TPRs in a conversational question answering (QA) setting. The data is comprised of the TPR turns corresponding dialogue contexts and candidate repairs of the original turn for execution of TPRs. We demonstrate the usefulness of the data by training and evaluating strong baseline models for executing TPRs. For stand45;alone TPR execution we perform both automatic and human evaluations on a fine45;tuned T5 model as well as OpenAIs GPT45;3 LLMs. Additionally we extrinsically evaluate the LLMs TPR processing capabilities in the downstream conversational QA task. The results indicate poor out45;of45;the45;box performance on TPRs by the GPT45;3 models which then significantly improves when exposed to Repair45;QA.
