---
layout: publication
title: "Prism: A Framework For Decoupling And Assessing The Capabilities Of Vlms"
authors: Qiao Yuxuan, Duan Haodong, Fang Xinyu, Yang Junming, Chen Lin, Zhang Songyang, Wang Jiaqi, Lin Dahua, Chen Kai
conference: "Arxiv"
year: 2024
bibkey: qiao2024framework
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14544"}
  - {name: "Code", url: "https://github.com/SparksJoe/Prism"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Tools', 'Training Techniques']
---
Vision Language Models (VLMs) demonstrate remarkable proficiency in addressing a wide array of visual questions which requires strong perception and reasoning faculties. Assessing these two competencies independently is crucial for model refinement despite the inherent difficulty due to the intertwined nature of seeing and reasoning in existing VLMs. To tackle this issue we present Prism an innovative framework designed to disentangle the perception and reasoning processes involved in visual question solving. Prism comprises two distinct stages a perception stage that utilizes a VLM to extract and articulate visual information in textual form and a reasoning stage that formulates responses based on the extracted visual information using a Large Language Model (LLM). This modular design enables the systematic comparison and assessment of both proprietary and open-source VLM for their perception and reasoning strengths. Our analytical framework provides several valuable insights underscoring Prisms potential as a cost-effective solution for vision-language tasks. By combining a streamlined VLM focused on perception with a powerful LLM tailored for reasoning Prism achieves superior results in general vision-language tasks while substantially cutting down on training and operational expenses. Quantitative evaluations show that Prism when configured with a vanilla 2B LLaVA and freely accessible GPT-3.5 delivers performance on par with VLMs 10 (times) larger on the rigorous multimodal benchmark MMStar. The project is released at https://github.com/SparksJoe/Prism."
