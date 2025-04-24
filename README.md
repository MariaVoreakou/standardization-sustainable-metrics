# 📊 Modeling Software Metrics Using SysML: Towards Sustainable AMQP Systems
## 🧠 Overview
This research project explores the use of SysML (Systems Modeling Language) to model and analyze software metrics, with a specific focus on identifying sustainability metrics relevant to AMQP (Advanced Message Queuing Protocol)-based systems. The study builds on a foundational paper that catalogs a range of software metrics, and extends this work by proposing a tailored set of metrics for the unique characteristics of AMQP software.

## 📚 Background
Modeling software metrics is critical for understanding and improving software quality, maintainability, and sustainability. SysML provides a robust framework for visual modeling and systems thinking, making it a strong candidate for representing and analyzing these metrics.

AMQP is widely used in distributed systems for message-oriented middleware. However, assessing its sustainability—especially in terms of energy efficiency, scalability, and maintainability—remains a challenge.

## 🎯 Objectives
To transform and model software metrics using SysML based on an established paper.

To identify, evaluate, and propose sustainable metrics specific to AMQP software systems.

To demonstrate the applicability of SysML in representing both traditional and sustainability-focused software metrics.

## 🧾 Literature Base
The core metrics used as a foundation for this study are derived from:
Metrics for Sustainable Data Centers

A comprehensive taxonomy of Metrics for Sustainable Data Centers

```@article{reddy2017metrics,
title={Metrics for sustainable data centers},
author={Reddy, V Dinesh and Setz, Brian and Rao, G Subrahmanya VRK and Gangadharan, GR and Aiello, Marco},
journal={IEEE Transactions on Sustainable Computing},
volume={2},
number={3},
pages={290--303},
year={2017},
publisher={IEEE}
}
```

This paper categorizes Data center energy metrics across various dimensions such as complexity, performance, maintainability, and modularity.

## 🔬 Methodology
-  **Metric Extraction**
  
Extracted existing software metrics from the aforementioned paper.

- **SysML Modeling**

Created SysML diagrams (Requirement, Block Definition, Activity, and Parametric) to represent the metrics.

- **Sustainability Evaluation**

Mapped metrics to software dimensions (e.g. energy use, resource consumption, lifecycle cost) for AMQP systems.

- **Gap Analysis**

Identified missing metrics or limitations in current models when applied to AMQP-based software.

- **Proposal of New Metrics**

Introduced new or modified metrics tailored for assessing sustainability in AMQP contexts.

## 📈 Results (WIP)
Initial models demonstrate SysML’s potential in visualizing metric interdependencies.

Sustainability-centric metrics such as "Message Throughput per Watt" and more are going to be proposed.

Diagrams and results will be shared in the `/diagrams` directory as the project progresses.

## 💡 Discussion
The research highlights the gap between traditional software metrics and those required for assessing long-term sustainability in message-oriented middleware. SysML offers a structured and visual way to integrate these metrics into system design processes.

## ✅ Conclusion
This work aims to bridge systems modeling with sustainability assessment in software engineering, particularly for AMQP-based architectures. It demonstrates that SysML can serve not just for requirement and architecture modeling, but also for meaningful metric analysis.

## 📂 Repository Structure
```
├── README.md
├── /diagrams             
├──── /datacenter-level   # SysML models in .svg format created based on the state of the art paper
├──── /software-level     # SysML models in .svg format created for our research
├──── /cloud-related      # SysML models in .svg format created for our research cloud related
├── /papers               # Reference materials and annotated base papers
├── /misc                 # Other files used for this research

```
