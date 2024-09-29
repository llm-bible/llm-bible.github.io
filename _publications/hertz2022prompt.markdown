---
layout: publication
title: Prompt45;to45;prompt Image Editing With Cross Attention Control
authors: Hertz Amir, Mokady Ron, Tenenbaum Jay, Aberman Kfir, Pritch Yael, Cohen-or Daniel
conference: "Arxiv"
year: 2022
bibkey: hertz2022prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2208.01626"}
tags: ['Applications', 'Attention Mechanism', 'Ethics And Bias', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Tools']
---
Recent large45;scale text45;driven synthesis models have attracted much attention thanks to their remarkable capabilities of generating highly diverse images that follow given text prompts. Such text45;based synthesis methods are particularly appealing to humans who are used to verbally describe their intent. Therefore it is only natural to extend the text45;driven image synthesis to text45;driven image editing. Editing is challenging for these generative models since an innate property of an editing technique is to preserve most of the original image while in the text45;based models even a small modification of the text prompt often leads to a completely different outcome. State45;of45;the45;art methods mitigate this by requiring the users to provide a spatial mask to localize the edit hence ignoring the original structure and content within the masked region. In this paper we pursue an intuitive prompt45;to45;prompt editing framework where the edits are controlled by text only. To this end we analyze a text45;conditioned model in depth and observe that the cross45;attention layers are the key to controlling the relation between the spatial layout of the image to each word in the prompt. With this observation we present several applications which monitor the image synthesis by editing the textual prompt only. This includes localized editing by replacing a word global editing by adding a specification and even delicately controlling the extent to which a word is reflected in the image. We present our results over diverse images and prompts demonstrating high45;quality synthesis and fidelity to the edited prompts.
