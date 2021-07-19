This repository includes a Threat Actor Type Ontology based on Intel's Threat Agent Library (TAL) [1], i.e., this is an **ontological representation of TAL with the addition of inferential statements (equivalent classes)** that using a reasoner automatically deduct the type of an adversary (see this [Figure](https://github.com/Vasileios-Mavroeidis/cti-knowledge-representation/blob/main/Threat-Agent-Library/figure.png) for actor types and their defining characteristics). This is achieved by using a set of attributes (e.g., motivation, outcome, objectives, and resources) that can characterize an adversary directly or their operations.

- The file tal.owl includes the actor type classes, relationships, and characterization attributes.
- The file tal-axioms.owl includes the inferential statements (equivalency) of threat actor types based on the characterization attributes.
- The file tal.owl imports the tal-axioms.owl file.
