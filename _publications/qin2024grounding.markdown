---
layout: publication
title: 'Grounding Is All You Need? Dual Temporal Grounding For Video Dialog'
authors: You Qin, Wei Ji, Xinze Lan, Hao Fei, Xun Yang, Dan Guo, Roger Zimmermann, Lizi Liao
conference: "Arxiv"
year: 2024
bibkey: qin2024grounding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.05767"}
tags: ['Tools', 'Attention Mechanism', 'Model Architecture', 'Reinforcement Learning']
---
In the realm of video dialog response generation, the understanding of video
content and the temporal nuances of conversation history are paramount. While a
segment of current research leans heavily on large-scale pretrained
visual-language models and often overlooks temporal dynamics, another delves
deep into spatial-temporal relationships within videos but demands intricate
object trajectory pre-extractions and sidelines dialog temporal dynamics. This
paper introduces the Dual Temporal Grounding-enhanced Video Dialog model
(DTGVD), strategically designed to merge the strengths of both dominant
approaches. It emphasizes dual temporal relationships by predicting dialog
turn-specific temporal regions, filtering video content accordingly, and
grounding responses in both video and dialog contexts. One standout feature of
DTGVD is its heightened attention to chronological interplay. By recognizing
and acting upon the dependencies between different dialog turns, it captures
more nuanced conversational dynamics. To further bolster the alignment between
video and dialog temporal dynamics, we've implemented a list-wise contrastive
learning strategy. Within this framework, accurately grounded turn-clip
pairings are designated as positive samples, while less precise pairings are
categorized as negative. This refined classification is then funneled into our
holistic end-to-end response generation mechanism. Evaluations using
AVSD@DSTC-7 and AVSD@DSTC-8 datasets underscore the superiority of our
methodology.
