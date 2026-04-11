---
title: "FetalSleepNet: A Transfer Learning Framework with Spectral Equalisation Domain Adaptation for Fetal Sleep Stage Classification"
collection: publications
category: manuscripts
permalink: /publication/fetalsleepnet-domain-adaptation
excerpt: "FetalSleepNet transfers adult sleep EEG knowledge to fetal sheep EEG using spectral equalisation and domain adaptation, improving cross-species fetal sleep stage classification."
date: 2026-04-08
venue: "IEEE Journal of Biomedical and Health Informatics"
paperurl: "https://ieeexplore.ieee.org/document/11478039"
---
Objective: Fetal sleep state classification is essential for identifying neurodevelopmental complications like hypoxia, but manual annotation is subjective and labor-intensive, and fetal EEG (fEEG) data is extremely scarce.

Methods: We propose FetalSleepNet, the first deep learning architecture specifically developed for automated sleep staging from the fEEG. To address the scarcity of labeled data, we implement the first cross-developmental (adult-to-fetal) and cross-species (human-to-sheep) transfer learning framework for this task, utilizing Spectral Equalisation (SE) to align the frequency-domain characteristics of adult human EEG with the fetal sheep target.

Results: Our findings prove the irreplaceable effectiveness of this adaptation: while direct transfer on raw EEG almost fails with only 18.7\% accuracy, applying SE allows even a frozen model to reach 73.6\% accuracy, effectively mitigating the cross-domain spectral mismatch. With full fine-tuning, FetalSleepNet achieves a state-of-the-art accuracy of 86.6\% and a macro F1-score of 62.5\%.

Conclusions: Beyond high-accuracy classification, FetalSleepNet establishes a robust "label engine" paradigm. By generating high-fidelity neurophysiological annotations, it facilitates a framework for training proxy sleep stagers on broader, non-invasive clinical modalities. This paves the way for scalable, real-time fetal monitoring and early risk prediction in clinical settings.
