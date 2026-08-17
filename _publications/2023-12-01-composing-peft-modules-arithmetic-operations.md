---
title: "Composing Parameter-Efficient Modules with Arithmetic Operations"
collection: publications
permalink: /publications/composing-peft-modules-arithmetic-operations
type: "conference"
date: "2023-12-01"
venue: "NeurIPS 2023"
location: "New Orleans, Louisiana, USA"
excerpt: "We introduce arithmetic operations between parameter-efficient fine-tuning modules, enabling transfer and sharing of modules across different models and tasks."
first_author: false
authors: "Jinghan Zhang, Shiqi Chen, Junteng Liu, Junxian He"
paperurl: "https://arxiv.org/abs/2306.04155"
citation: "Jinghan Zhang, Shiqi Chen, Junteng Liu, Junxian He. Composing Parameter-Efficient Modules with Arithmetic Operations. In NeurIPS 2023."
---

We propose a method for composing parameter-efficient fine-tuning (PEFT) modules using arithmetic operations, enabling modules from one task to be transferred and reused across different models and fine-tuning scenarios. Our approach shows that PEFT modules can be treated as vectors and manipulated through addition, subtraction, and scaling.

Key contributions include:

* **Compositional PEFT**: Demonstrating that arithmetic combinations of PEFT modules produce effective models for new tasks.
* **Transfer Learning**: Showcasing zero-shot transfer of PEFT modules between different base models.
* **Modularity**: Enabling reusability of standard PEFT modules (LoRA, etc.) through arithmetic.
