---
layout: publication
title: 'Model Tampering Attacks Enable More Rigorous Evaluations Of LLM Capabilities'
authors: Zora Che, Stephen Casper, Robert Kirk, Anirudh Satheesh, Stewart Slocum, Lev E Mckinney, Rohit Gandikota, Aidan Ewart, Domenic Rosati, Zichu Wu, Zikui Cai, Bilal Chughtai, Yarin Gal, Furong Huang, Dylan Hadfield-menell
conference: "Arxiv"
year: 2025
bibkey: che2025model
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.05209"}
tags: ['Security', 'Training Techniques', 'Tools', 'Pretraining Methods', 'Fine-Tuning']
---
Evaluations of large language model (LLM) risks and capabilities are
increasingly being incorporated into AI risk management and governance
frameworks. Currently, most risk evaluations are conducted by designing inputs
that elicit harmful behaviors from the system. However, this approach suffers
from two limitations. First, input-output evaluations cannot evaluate realistic
risks from open-weight models. Second, the behaviors identified during any
particular input-output evaluation can only lower-bound the model's
worst-possible-case input-output behavior. As a complementary method for
eliciting harmful behaviors, we propose evaluating LLMs with model tampering
attacks which allow for modifications to latent activations or weights. We pit
state-of-the-art techniques for removing harmful LLM capabilities against a
suite of 5 input-space and 6 model tampering attacks. In addition to
benchmarking these methods against each other, we show that (1) model
resilience to capability elicitation attacks lies on a low-dimensional
robustness subspace; (2) the attack success rate of model tampering attacks can
empirically predict and offer conservative estimates for the success of
held-out input-space attacks; and (3) state-of-the-art unlearning methods can
easily be undone within 16 steps of fine-tuning. Together these results
highlight the difficulty of suppressing harmful LLM capabilities and show that
model tampering attacks enable substantially more rigorous evaluations than
input-space attacks alone.
