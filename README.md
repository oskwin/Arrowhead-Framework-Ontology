# Arrowhead Framework Ontology (AFO)

The **Arrowhead Framework Ontology (AFO)** provides a semantic model for describing Arrowhead local cloud architectures, including systems, services, hosts, and their relationships.  
It aims to enable **semantic interoperability** in **industrial automation and cyber-physical systems (CPS)** by aligning with the **Industrial Data Ontology (IDO) v4.0**, which is based on ISO 15926 and the Basic Formal Ontology (BFO).

## Features

- Ontology modeling of:
  - **Systems** and **Units**
  - **Services** (provided and consumed)
  - **Hosts** and deployment relations
  - **Service interactions** (`providesTo`, `consumes`, etc.)

## :package: Repository Structure

```plaintext
Arrowhead-Framework-Ontology/
|   ├── ontology/
|   |   └── afo.ttl 
```

## About

- Developed using the mbaigo implementation of the Arrowhead framework:
```plaintext
https://github.com/sdoque/systems
```

- Knowledge graph generation requires the KGrapher system. 

## Presented In
- https://doi.org/10.5281/zenodo.18731224

## :suspect: Author
- Oskar Wintercorn <br>
GitHub: [@oskwin]

