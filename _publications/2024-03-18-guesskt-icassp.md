---
title: "GuessKT: Improving Knowledge Tracing via Considering Guess Behaviors"
collection: publications
category: conferences
permalink: /publication/guesskt-icassp-2024
excerpt: 'We propose GuessKT, a knowledge tracing model that explicitly models students’ guess behaviors to improve the reliability of learning feedback and enhance prediction accuracy across multiple datasets.'
date: 2024-3-18
venue: 'ICASSP 2024 - 2024 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)'
---
Knowledge tracing (KT) aims to predict students’ responses to given questions based on their historical question-answering interactions. Recent studies have proposed multiple types of KT models, mainly relying on learners’ feedback to capture the evolution of their knowledge states. However, these models leave the influence of learners’ guess behaviors out of consideration. These behaviors would cause unreliable feedback and mislead the inference process of the KT models. Exploring the guess behaviors is important since it can potentially help us understand realistic learning interactions for more accurate knowledge state estimations. In this paper, we propose GuessKT to better trace the learning progress by introducing the guess behaviors into learning feedback attribution, leading to improved prediction performance. Specifically, a windowed attention network is proposed to capture rich information from local interactions, which enhances the reliability of extracted historical feedback. Furthermore, a recovery network is proposed to recover the students’ responses after additional mask processing, which bolsters the model’s ability to recognize guess behaviors. Experiments on five datasets show that our model GuessKT advanced predictive performance over other baselines.
