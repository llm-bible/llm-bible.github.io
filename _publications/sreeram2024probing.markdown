---
layout: publication
title: "Probing Multimodal Llms As World Models For Driving"
authors: Sreeram Shiva, Wang Tsun-hsuan, Maalouf Alaa, Rosman Guy, Karaman Sertac, Rus Daniela
conference: "Arxiv"
year: 2024
bibkey: sreeram2024probing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.05956"}
tags: ['Ethics And Bias', 'Fine Tuning', 'GPT', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
We provide a sober look at the application of Multimodal Large Language Models (MLLMs) within the domain of autonomous driving and challenge/verify some common assumptions focusing on their ability to reason and interpret dynamic driving scenarios through sequences of images/frames in a closed-loop control environment. Despite the significant advancements in MLLMs like GPT-4V their performance in complex dynamic driving environments remains largely untested and presents a wide area of exploration. We conduct a comprehensive experimental study to evaluate the capability of various MLLMs as world models for driving from the perspective of a fixed in-car camera. Our findings reveal that while these models proficiently interpret individual images they struggle significantly with synthesizing coherent narratives or logical sequences across frames depicting dynamic behavior. The experiments demonstrate considerable inaccuracies in predicting (i) basic vehicle dynamics (forward/backward acceleration/deceleration turning right or left) (ii) interactions with other road actors (e.g. identifying speeding cars or heavy traffic) (iii) trajectory planning and (iv) open-set dynamic scene reasoning suggesting biases in the models training data. To enable this experimental study we introduce a specialized simulator DriveSim designed to generate diverse driving scenarios providing a platform for evaluating MLLMs in the realms of driving. Additionally we contribute the full open-source code and a new dataset Eval-LLM-Drive for evaluating MLLMs in driving. Our results highlight a critical gap in the current capabilities of state-of-the-art MLLMs underscoring the need for enhanced foundation models to improve their applicability in real-world dynamic environments.
