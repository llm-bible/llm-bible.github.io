---
layout: publication
title: Pseudo45;ood Training For Robust Language Models
authors: Sundararaman Dhanasekar, Mehta Nikhil, Carin Lawrence
conference: "Arxiv"
year: 2022
bibkey: sundararaman2022pseudo
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.09132"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
While pre45;trained large45;scale deep models have garnered attention as an important topic for many downstream natural language processing (NLP) tasks such models often make unreliable predictions on out45;of45;distribution (OOD) inputs. As such OOD detection is a key component of a reliable machine45;learning model for any industry45;scale application. Common approaches often assume access to additional OOD samples during the training stage however outlier distribution is often unknown in advance. Instead we propose a post hoc framework called POORE 45; POsthoc pseudo45;Ood REgularization that generates pseudo45;OOD samples using in45;distribution (IND) data. The model is fine45;tuned by introducing a new regularization loss that separates the embeddings of IND and OOD data which leads to significant gains on the OOD prediction task during testing. We extensively evaluate our framework on three real45;world dialogue systems achieving new state45;of45;the45;art in OOD detection.
