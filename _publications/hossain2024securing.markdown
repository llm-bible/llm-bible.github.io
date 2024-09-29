---
layout: publication
title: Securing Vision45;language Models With A Robust Encoder Against Jailbreak And Adversarial Attacks
authors: Hossain Md Zarif, Imteaj Ahmed
conference: "Arxiv"
year: 2024
bibkey: hossain2024securing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.07353"}
  - {name: "Code", url: "https://github.com/speedlab&#45;git/Robust&#45;Encoder&#45;against&#45;Jailbreak&#45;attack.git"}
tags: ['Applications', 'Has Code', 'Model Architecture', 'Multimodal Models', 'RAG', 'Reinforcement Learning', 'Responsible AI', 'Security']
---
Large Vision45;Language Models (LVLMs) trained on multimodal big datasets have significantly advanced AI by excelling in vision45;language tasks. However these models remain vulnerable to adversarial attacks particularly jailbreak attacks which bypass safety protocols and cause the model to generate misleading or harmful responses. This vulnerability stems from both the inherent susceptibilities of LLMs and the expanded attack surface introduced by the visual modality. We propose Sim45;CLIP+ a novel defense mechanism that adversarially fine45;tunes the CLIP vision encoder by leveraging a Siamese architecture. This approach maximizes cosine similarity between perturbed and clean samples facilitating resilience against adversarial manipulations. Sim45;CLIP+ offers a plug45;and45;play solution allowing seamless integration into existing LVLM architectures as a robust vision encoder. Unlike previous defenses our method requires no structural modifications to the LVLM and incurs minimal computational overhead. Sim45;CLIP+ demonstrates effectiveness against both gradient45;based adversarial attacks and various jailbreak techniques. We evaluate Sim45;CLIP+ against three distinct jailbreak attack strategies and perform clean evaluations using standard downstream datasets including COCO for image captioning and OKVQA for visual question answering. Extensive experiments demonstrate that Sim45;CLIP+ maintains high clean accuracy while substantially improving robustness against both gradient45;based adversarial attacks and jailbreak techniques. Our code and robust vision encoders are available at https://github.com/speedlab&#45;git/Robust&#45;Encoder&#45;against&#45;Jailbreak&#45;attack.git.
