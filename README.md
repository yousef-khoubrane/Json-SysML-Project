# Json-SysML-Project

**Json-SysML: A Bidirectional JSON-Based Representation for SysML Models Enabling LLM-Augmented Model-Based Systems Engineering**

This repository hosts the project page for **Json-SysML**, a compact, AI-oriented representation of SysML v1 models designed to support Large Language Model integration in Model-Based Systems Engineering workflows.

**[Paper](https://doi.org/10.1145/3822455.3830325)** · **[Source code](https://github.com/yousef-khoubrane/Json-SysML)** · **[Paper code snapshot (Zenodo)](https://doi.org/10.5281/zenodo.23317739)** · **[Interactive syntax reference](./Json-SysML_Syntax.html)**

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

**Pages:** 69–79  
**DOI:** [10.1145/3822455.3830325](https://doi.org/10.1145/3822455.3830325)

### Citation

To cite the Json-SysML paper, use the following reference:

#### Paper

```bibtex
@inproceedings{10.1145/3822455.3830325,
    author = {Khoubrane, Yousef and Elhadji Ille Gado, Nassara and Li, Rui and Danlos, Helene and Bureau, Nicolas and Benmiloud Bechet, Lies and Plana, Robert and Vazirgiannis, Michalis},
    title = {Json-SysML: A Bidirectional JSON-Based Representation for SysML Models Enabling LLM-Augmented Model-Based Systems Engineering},
    booktitle = {Proceedings of the ACM/IEEE 29th International Conference on Model Driven Engineering Languages and Systems},
    year = {2026},
    publisher = {Association for Computing Machinery},
    pages = {69--79},
    doi = {10.1145/3822455.3830325},
    url = {https://doi.org/10.1145/3822455.3830325},
    series = {MODELS '26}
}
```

#### Software snapshot

If you use the Json-SysML code in your work, please also cite the software snapshot using its Zenodo DOI. The **v0.1.0** release is the archived snapshot of the code used to produce the results reported in the paper.

**DOI:** [10.5281/zenodo.23317739](https://doi.org/10.5281/zenodo.23317739)

```bibtex
@software{yousef_khoubrane_2026_23317739,
    author = {yousef-khoubrane},
    title = {yousef-khoubrane/Json-SysML: Json-SysML v0.1.0 — Initial release},
    month = oct,
    year = {2026},
    publisher = {Zenodo},
    version = {v0.1.0},
    doi = {10.5281/zenodo.23317739},
    url = {https://doi.org/10.5281/zenodo.23317739}
}
```

## Source Code

The implementation is available in the [**Json-SysML repository**](https://github.com/yousef-khoubrane/Json-SysML). For the exact code version used in the paper, use the [**v0.1.0 snapshot archived on Zenodo**](https://doi.org/10.5281/zenodo.23317739).

The repository includes:

* the XMI-to-Json-SysML and Json-SysML-to-XMI conversion pipelines for CATIA Magic;
* installation instructions and conversion options;
* example models;
* scripts and instructions for reproducing the paper’s evaluation.

## Syntax Reference

The [**interactive syntax reference**](./Json-SysML_Syntax.html) documents the model structure, nine supported diagram types, element definitions, and field conventions.

Use the explorer to inspect fields, select diagrams to include in a model, and copy or download a JSON template. Edit the exported template to replace placeholders and make identifiers and references consistent.

The reference is self-contained and can also be downloaded and opened locally.

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
