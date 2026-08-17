---
title: "On the Perception Bottleneck of VLMs for Chart Understanding"
collection: publications
permalink: /publications/perception-bottleneck-vlms-chart-understanding
type: "conference"
date: "2025-01-01"
venue: "arXiv preprint 2025
location: "Online"
excerpt: "We identify and characterize a perception bottleneck in vision-language models that limits their ability to accurately interpret visual information from charts."
first_author: true
authors: "Junteng Liu, Weihao Zeng, Xiwen Zhang, Yijun Wang, Zifei Shan, Junxian He"
paperurl: "https://arxiv.org/abs/2501.10853"
citation: "Junteng Liu, Weihao Zeng, Xiwen Zhang, Yijun Wang, Zifei Shan, Junxian He. On the Perception Bottleneck of VLMs for Chart Understanding. arXiv preprint 2025.
---

We investigate the **perception bottleneck** of vision-language models (VLMs) for chart understanding, revealing that current VLMs often fail at the fundamental step of accurately perceiving visual elements in charts. Our analysis identifies key limitations in how VLMs encode spatial relationships, text extraction, and visual pattern recognition in chart images, leading to systematic errors in downstream chart understanding.

The key findings include:

* **Spatial Perception Failure**: VLMs struggle with accurately localizing and identifying chart components such as axes, legends, data points, and labels.
* **Text Extraction Errors**: OCR-like perception errors affect the model's ability to extract textual information from chart images.
* **Propagation of Errors**: Even well-performing VLMs suffer from compound errors, where small perception failures cascade into larger comprehensions about chart meaning.
* **Training Dynamics**: We analyze how standard pre-training and instruction-tuning approaches affect the perception capabilities of VLMs.
