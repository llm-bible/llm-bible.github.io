---
layout: publication
title: Taking A HINT Leveraging Explanations To Make Vision And Language Models More Grounded
authors: Selvaraju Ramprasaath R., Lee Stefan, Shen Yilin, Jin Hongxia, Ghosh Shalini, Heck Larry, Batra Dhruv, Parikh Devi
conference: "The IEEE International Conference on Computer Vision"
year: 2019
bibkey: selvaraju2019taking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1902.03751"}
tags: ['Applications', 'Attention Mechanism', 'Interpretability And Explainability', 'Model Architecture', 'RAG', 'Training Techniques']
---
Many vision and language models suffer from poor visual grounding 45; often falling back on easy45;to45;learn language priors rather than basing their decisions on visual concepts in the image. In this work we propose a generic approach called Human Importance45;aware Network Tuning (HINT) that effectively leverages human demonstrations to improve visual grounding. HINT encourages deep networks to be sensitive to the same input regions as humans. Our approach optimizes the alignment between human attention maps and gradient45;based network importances 45; ensuring that models learn not just to look at but rather rely on visual concepts that humans found relevant for a task when making predictions. We apply HINT to Visual Question Answering and Image Captioning tasks outperforming top approaches on splits that penalize over45;reliance on language priors (VQA45;CP and robust captioning) using human attention demonstrations for just 637; of the training data.
