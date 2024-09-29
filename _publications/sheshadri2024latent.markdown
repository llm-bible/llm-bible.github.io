---
layout: publication
title: Latent Adversarial Training Improves Robustness To Persistent Harmful Behaviors In Llms
authors: Sheshadri Abhay, Ewart Aidan, Guo Phillip, Lynch Aengus, Wu Cindy, Hebbar Vivek, Sleight Henry, Stickland Asa Cooper, Perez Ethan, Hadfield-menell Dylan, Casper Stephen
conference: "Arxiv"
year: 2024
bibkey: sheshadri2024latent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.15549"}
tags: ['Interpretability And Explainability', 'Pretraining Methods', 'RAG', 'Security', 'Training Techniques']
---
Large language models (LLMs) can often be made to behave in undesirable ways that they are explicitly fine45;tuned not to. For example the LLM red45;teaming literature has produced a wide variety of jailbreaking techniques to elicit harmful text from models that were fine45;tuned to be harmless. Recent work on red45;teaming model editing and interpretability suggests that this challenge stems from how (adversarial) fine45;tuning largely serves to suppress rather than remove undesirable capabilities from LLMs. Prior work has introduced latent adversarial training (LAT) as a way to improve robustness to broad classes of failures. These prior works have considered untargeted latent space attacks where the adversary perturbs latent activations to maximize loss on examples of desirable behavior. Untargeted LAT can provide a generic type of robustness but does not leverage information about specific failure modes. Here we experiment with targeted LAT where the adversary seeks to minimize loss on a specific competing task. We find that it can augment a wide variety of state45;of45;the45;art methods. First we use targeted LAT to improve robustness to jailbreaks outperforming a strong R2D2 baseline with orders of magnitude less compute. Second we use it to more effectively remove backdoors with no knowledge of the trigger. Finally we use it to more effectively unlearn knowledge for specific undesirable tasks in a way that is also more robust to re45;learning. Overall our results suggest that targeted LAT can be an effective tool for defending against harmful behaviors from LLMs.
