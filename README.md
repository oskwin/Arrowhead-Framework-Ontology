# Arrowhead Framework Ontology (AFO)

The **Arrowhead Framework Ontology (AFO)** provides a semantic model for describing Arrowhead local cloud architectures, including systems, services, hosts, and their relationships.
It aims to enable **semantic interoperability** in **industrial automation and cyber-physical systems (CPS)**.

**Version:** 1.1.0

## Features

- OWL ontology modeling of:
  - **Local Clouds** — including `SecureLocalCloud` and `ResilientLocalCloud` variants
  - **Systems** and **Unit Assets**
  - **Services** — `ProvidedService` and `ConsumedService`
  - **Husks**, **Servers**, **Hosts**, and **Endpoints**
  - **Core Arrowhead systems** — `Orchestrator`, `Serviceregistrar`, `CertificateAuthority`
- Object properties for service interaction (`providesService`, `consumesService`, `consumingFromSystem`, etc.)
- Data properties for deployment metadata (`hasIPaddress`, `usesPort`, `usesProtocol`, `hasUrl`, etc.)
- Disjointness axioms and cardinality constraints

## Repository Structure

```
Arrowhead-Framework-Ontology/
└── ontology/
    └── afo.ttl
└── shacl/
    └── afo-shapes.ttl
```

## About

Developed using the [mbaigo](https://github.com/sdoque/systems) implementation of the Arrowhead framework.

Knowledge graph generation from live Arrowhead deployments requires the KGrapher system.

For replication purposes clone the following mbaigo systems release:

```
git clone git@github.com:sdoque/systems.git --branch v0.1.0-alpha.3
```

Minimal startup should include:

- esr

- orchestrator

- kgrapher

## Publication

Published on Zenodo: [https://doi.org/10.5281/zenodo.18731224](https://doi.org/10.5281/zenodo.18731224)

## Author

Oskar Wintercorn — [@oskwin](https://github.com/oskwin)
