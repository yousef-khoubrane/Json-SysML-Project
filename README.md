# Json-SysML-Project

**Json-SysML: A Bidirectional JSON-Based Representation for SysML Models Enabling LLM-Augmented Model-Based Systems Engineering**

This repository hosts the project page for **Json-SysML**, a compact, AI-oriented representation of SysML v1 models designed to support Large Language Model integration in Model-Based Systems Engineering workflows.

The work is associated with a paper submitted to [**MODELS 2026**](https://conf.researchr.org/home/models-2026). This page will be updated with links to the published paper and the source-code repository once they become publicly available.

## Overview

SysML v1 models are commonly serialized using XML Metadata Interchange, or XMI. Although XMI supports interoperability between modeling tools, its verbosity, deeply nested structure, distributed references, and extensive tool-specific metadata make it inefficient for LLM-based processing.

Json-SysML addresses these limitations by providing:

* a compact JSON representation of SysML v1 models;
* an automated bidirectional conversion pipeline between Json-SysML and XMI;
* compatibility with existing MBSE environments;
* substantially reduced token usage compared with raw XMI.

Experimental results reported in the paper show an average token-count reduction of more than **97.6%** compared with raw XMI. Round-trip validation also demonstrates that Json-SysML models can be reconstructed and re-imported into conventional modeling tools while preserving their core structural and semantic information.

## Publication

**Conference:** ACM/IEEE 29th International Conference on Model Driven Engineering Languages and Systems ([MODELS 2026](https://conf.researchr.org/home/models-2026))

**Paper title:**
*Json-SysML: A Bidirectional JSON-Based Representation for SysML Models Enabling LLM-Augmented Model-Based Systems Engineering*

The paper link will be added here once the publication becomes available.

## Source Code

The Json-SysML implementation and conversion pipeline are being prepared for public release.

The source-code repository link will be added here once the implementation is published.

## Authors

* **Yousef Khoubrane**<br>
  DaSciM, LIX, École Polytechnique<br>
  Assystem Energy and Operation Services (AEOS)<br>
  ORCID: [0009-0008-6692-4480](https://orcid.org/0009-0008-6692-4480)

* **Nassara Elhadji Ille Gado**<br>
  Assystem Energy and Operation Services (AEOS)<br>
  ORCID: [0000-0002-7325-877X](https://orcid.org/0000-0002-7325-877X)

* **Rui Li**<br>
  Assystem Energy and Operation Services (AEOS)<br>
  ORCID: [0000-0003-2493-2665](https://orcid.org/0000-0003-2493-2665)

* **Helene Danlos**<br>
  Assystem Energy and Operation Services (AEOS)<br>
  ORCID: [0009-0006-6549-2052](https://orcid.org/0009-0006-6549-2052)

* **Nicolas Bureau**<br>
  Assystem Energy and Operation Services (AEOS)<br>
  ORCID: [0009-0008-2886-6697](https://orcid.org/0009-0008-2886-6697)

* **Lies Benmiloud Bechet**<br>
  Assystem Energy and Operation Services (AEOS)<br>
  ORCID: [0009-0009-1894-2382](https://orcid.org/0009-0009-1894-2382)

* **Robert Plana**<br>
  Assystem Energy and Operation Services (AEOS)<br>
  ORCID: [0000-0003-2378-8331](https://orcid.org/0000-0003-2378-8331)

* **Michalis Vazirgiannis**<br>
  DaSciM, LIX, École Polytechnique<br>
  ORCID: [0000-0001-5923-4440](https://orcid.org/0000-0001-5923-4440)


## Affiliations

* **Data Science and Mining Team (DaSciM), Computer Science Laboratory (LIX), École Polytechnique, Institut Polytechnique de Paris**, Palaiseau, France
* **Assystem Energy and Operation Services (AEOS)**, Courbevoie, France

## Keywords

Model-Based Systems Engineering, MBSE, Systems Modeling Language, SysML, Large Language Models, bidirectional model transformation, semantic representation, XML Metadata Interchange, XMI compression

## Contact

For questions about the project, contact:

**Yousef Khoubrane**<br>
[ykhoubrane@assystem.com](mailto:ykhoubrane@assystem.com)<br>
[khoubrane@lix.polytechnique.fr](mailto:khoubrane@lix.polytechnique.fr)

## Updates

This page will be updated as the project progresses, including:

* the official paper link;
* the source-code repository;
* schema documentation;
* citation information.
