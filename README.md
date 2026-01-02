# Same-Data-Different-Models-2026
Repository for the Same Data Different Model (SDDM) tutorial hosted in the [European Semantic Web Conference (ESWC) 2026](https://2026.eswc-conferences.org) located in Dubrovnik, Croatia.

----

## Repository Layout
- `data/` — pointers to datasets used in the tutorial (e.g., PFAS)
- `sessions/` — individual methodology-focused sessions
- `use-cases/` — descriptions of tutorial use cases
- `index.md` — front page for the tutorial
- `README.md` — this page


---

## Tutorial Overview

Ontologies dictate how data are related and interpreted. Different ontology engineering methodologies lead to different hierarchies, constraints, modular structures, and reasoning behaviors—even when applied to the same dataset.

In this tutorial, participants will:
- Apply **multiple ontology modeling methodologies** to the same dataset
- Compare the resulting ontological structures
- Train **knowledge graph embeddings** on the produced triples
- Visualize and analyze semantic coherence using **t-SNE / UMAP**
- Discuss strengths, weaknesses, and interoperability implications

The tutorial uses the **PFAS dataset**, previously employed in SDDM 2024.

---

## Sessions

All sessions follow a common structure:
1. Short methodological introduction
2. Hands-on modeling
3. Embedding-based analysis and visualization
4. Comparative discussion

### Introductory Comparison
**Presenter:** Davide Di Pierro  

A high-level overview of contemporary ontology engineering methodologies, positioning LOT, XD, BRO, and BFO within the broader literature and motivating methodological choices.

---

### eXtreme Design (XD)
**Presenters:** Andrea Giovanni Nuzzolese, Anna Sofia Lippolis  

The **eXtreme Design (XD)** methodology leverages ontology design patterns to create small, reusable, and coherent ontology modules. It supports scalability and reuse and has been applied in large Semantic Web efforts such as DBpedia and Wikidata.

---

### Linked Open Terms (LOT) + Chowlk
**Presenter:** María Poveda-Villalón  

**Linked Open Terms (LOT)** is a reuse-oriented methodology that guides ontology development from requirements gathering through implementation and publication.  
This session also introduces **Chowlk**, a visual UML-style modeling framework that generates OWL/Turtle representations.


---


### Basic Formal Ontology (BFO)
**Presenter:** John Beverly  

This session applies the **Basic Formal Ontology (BFO)** method, emphasizing realist upper-ontology commitments and strict ontological distinctions.


---

### Hands-On Collaborative Modeling
Participants apply one or more methodologies to the PFAS dataset, guided by the session leads.

---

### Embedding Evaluation & Visualization
- Knowledge graph embeddings
- Dimensionality reduction using **t-SNE / UMAP**
- Visual inspection of semantic clusters and gaps

---

### Comparative Analysis
A joint discussion synthesizing results across methodologies, focusing on:
- Structural differences
- Semantic coherence
- Interoperability challenges
- Best practices

---
