# Canary: Early Warning System for Process Quality

Canary is an ecosystem to enable early warning functionality in existing architectures. It is designed to me modular, scalable, and easy to integrate with existing software and organizational processes. This way, it can be leveraged to provide `Shift Left` capabilities within an organization, allowing for early detection of potential issues when they are still easy to fix. Like a canary in a coal mine, it's intent is to send out a warning signal when something is going wrong, so adequate measures can be taken to prevent (economic) disaster.

## Business Context

### Problem Statement

* Many organisations struggle with operational issues caused by late detection of problems in their processes.
  * The cost of fixing issues increases exponentially the later they are detected.
* Many organisations struggle with the complexity of their software systems.
  * Inherent complexity of the problem domain makes it challenging for teams to understand the system as a whole.
  * A mix between older and newer technologies makes it hard to implement a consistent monitoring solution.
* Economic pressure to deliver software faster and cheaper has a trickle-down effect on the quality of the software.
  * This leads to a higher number of defects in production, which in turn leads to higher operational costs.
  * Development teams are unlikely to take the time to implement monitoring solutions due to feature pressure.
* Legislative requirements are becoming more stringent, requiring organisations to have a better understanding of their systems.
  * This is especially true in the financial and healthcare sectors, where the cost of non-compliance is high.
  * Compliance is often achieved through manual processes, which are error-prone, slow, and difficult to scale. 

> TODO: Add Causal loop diagram to illustrate the problem statement



### Value Proposition



## Architecture Overview

![System Context View](./resources/system_context.svg)