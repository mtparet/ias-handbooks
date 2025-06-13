# ias-handbooks
Infrastructure as Software Handbooks: strategy, architecture, tooling, use cases, pitfalls

# Infrastructure as Software

**Infrastructure as Code** defined how to build infrastructure using code, commonly implemented using static definition files.
Pocess applying these static definition files can vary, usually handles creation and modification of the infrastructure based on the definition files.

**Infrastructure as Software** consolidates definition files and processes into a single software system. It goes beyond creating/updating infrastructure and can also directly interact with created infrastructure to operate it. The whole infrastructure management is consolidated into a single software system which guarantees consistency, reliability, usuability and complexity absorption.

It is not really a new concept but rather the definition of the holistic approach needed to get the benefits of Infrastructure as Software.
It can be applied to any infrastructure whatever the technology, the hosting, the provider, the language, the framework, etc.

[Kubernetes Operators](https://kubernetes.io/docs/concepts/extend-kubernetes/operator/#motivation) are a good example of Infrastructure as Software.
