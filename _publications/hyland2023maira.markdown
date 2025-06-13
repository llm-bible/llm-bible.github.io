---
layout: publication
title: 'MAIRA-1: A Specialised Large Multimodal Model For Radiology Report Generation'
authors: Stephanie L. Hyland, Shruthi Bannur, Kenza Bouzid, Daniel C. Castro, Mercy Ranjit, Anton Schwaighofer, Fernando Pérez-garcía, Valentina Salvatelli, Shaury Srivastav, Anja Thieme, Noel Codella, Matthew P. Lungren, Maria Teodora Wetscherek, Ozan Oktay, Javier Alvarez-valle
conference: "Arxiv"
year: 2023
bibkey: hyland2023maira
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.13668"}
  - {name: "Code", url: "https://aka.ms/maira"}
tags: ['RAG', 'Has Code', 'Survey Paper', 'Multimodal Models']
---
We present a radiology-specific multimodal model for the task for generating
radiological reports from chest X-rays (CXRs). Our work builds on the idea that
large language model(s) can be equipped with multimodal capabilities through
alignment with pre-trained vision encoders. On natural images, this has been
shown to allow multimodal models to gain image understanding and description
capabilities. Our proposed model (MAIRA-1) leverages a CXR-specific image
encoder in conjunction with a fine-tuned large language model based on
Vicuna-7B, and text-based data augmentation, to produce reports with
state-of-the-art quality. In particular, MAIRA-1 significantly improves on the
radiologist-aligned RadCliQ metric and across all lexical metrics considered.
Manual review of model outputs demonstrates promising fluency and accuracy of
generated reports while uncovering failure modes not captured by existing
evaluation practices. More information and resources can be found on the
project website: https://aka.ms/maira.
