## Description
This repository includes a Threat Actor Type Ontology [1] based on Intel's Threat Agent Library (TAL) [2][3], i.e., this is an **ontological representation of TAL with the addition of inferential statements (equivalent classes)** that by using a reasoner are used to automatically deduct the type of an adversary (see this [Figure](https://github.com/Vasileios-Mavroeidis/cti-knowledge-representation/blob/main/Threat-Agent-Library/figure.png) for actor types and their defining characteristics). This is achieved by using a set of attributes (e.g., motivation, outcome, objectives, and resources) that can characterize an adversary directly or their operations.

- The file tal.owl includes the actor type classes, relationships, and characterization attributes.
- The file tal-axioms.owl includes the inferential statements (equivalency) of threat actor types based on the characterization attributes.
- The file tal.owl imports the tal-axioms.owl file.

## Note
This work will be maintained and extended by the OASIS (SDO) [Threat Actor Context (TAC)](https://www.oasis-open.org/committees/tac/) Technical Committee.



## References

[1] Mavroeidis, V., Hohimer, R., Casey, T., and Jøsang, A. (2021). Threat Actor Type Inference and Characterization within Cyber Threat Intelligence.

[2] Casey, T. (2007). Threat Agent Library Helps Identify Information Security Risks.

[3] Casey, T. (2015). Understanding Cyberthreat Motivations to Improve Defense.


## Acknowledgements
- Vasileios Mavroeidis
- Ryan Hohimer
- Tim Casey
