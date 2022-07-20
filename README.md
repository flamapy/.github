# FlamaPy
We present a Python-based AAFM framework that takes into consideration previous AAFM tool designs and enables multi-solver and multi-metamodel support for the integration of AAFM tooling on the Python ecosystem.
The main features of the framework are:
• Easy to extend by enabling the creation of new plugins following a semi-automatic generator approach.
• Support multiple variability models. Currently, it provides support for cardinality-based feature models. However, it is easy to integrate others such as attributed feature models
• Support multiple solvers. Currently, it provides support for SAT and BDD metasolvers, which enables more than ten different solvers.
• Support multiple operations. It is developed, having in mind multi-model operations and single-model operations. Currently, it provides more than ten operations for cardinality-based feature models
