---
title: "SynLogic: Synthesizing Verifiable Reasoning Data at Scale for Learning Logical Reasoning and Beyond"
collection: publications
permalink: /publications/synlogic-reasoning-data-scale
type: "conference"
date: "2025-01-01"
venue: "arXiv preprint 2025"
location: "Online"
excerpt: "We propose SynLogic, a framework for synthesizing massive amounts of verifiable reasoning data at scale by leveraging symbolic logic to generate diverse reasoning tasks and their solutions."
first_author: true
authors: "Junteng Liu, Yuanxiang Fan, Zhuo Jiang, Han Ding, Yongyi Hu, Chi Zhang, Yiqi Shi, Shitong Weng, Aili Chen, Shiqi Chen, Yunan Huang, Mozhi Zhang, Pengyu Zhao, Junjie Yan, Junxian He"
paperurl: "https://arxiv.org/abs/2501.09287"
citation: "Junteng Liu, Yuanxiang Fan, Zhuo Jiang, Han Ding, Yongyi Hu, Chi Zhang, Yiqi Shi, Shitong Weng, Aili Chen, Shiqi Chen, Yunan Huang, Mozhi Zhang, Pengyu Zhao, Junjie Yan, Junxian He. SynLogic: Synthesizing Verifiable Reasoning Data at Scale for Learning Logical Reasoning and Beyond. arXiv preprint 2025.
---

We introduce **SynLogic**, a framework for generating verifiable reasoning data at scale to address the scarcity of high-quality reasoning datasets for large language model training. By leveraging symbolic logic as a foundation, SynLogic can generate tasks of arbitrary complexity with guaranteed verifiability of solutions.

The key contributions of SynLogic include:

* **Scalable Reasoning Data Generation**: We propose a symbolic-to-natural framework that transforms logical formulas into readable and challenging reasoning problems in natural language, creating datasets of unbounded size and diversity.

* **Verifiable Quality Control**: Every generated sample has a logically grounded ground truth, enabling both automated and human verification of reasoning correctness.

* **Diverse Task Typologies**: SynLogic supports mixing rule-encoding and example-based reasoning, allowing models to learn both types of reasoning patterns effectively.

* **Empirical Validation**: We demonstrate that models trained with SynLogic-generated data achieve significant improvements in logical reasoning benchmarks, and we analyze the transfer effects on broader NLP tasks.
