<p align="center">
  <img src="https://raw.githubusercontent.com/HiTOP-Ontologies/hitop-ontology/main/docs/assets/images/hitop-logo/web/hitop-logo-256-transparent.png" alt="HiTOP Ontology logo" width="120">
</p>

<h1 align="center">HiTOP Ontology Project</h1>

<p align="center">
  A machine-readable representation of the <strong>Hierarchical Taxonomy of Psychopathology (HiTOP)</strong>
</p>

<p align="center">
  <a href="https://hitop-ontologies.github.io/hitop-ontology/">Documentation</a> ·
  <a href="https://github.com/HiTOP-Ontologies/hitop-ontology">Repository</a> ·
  <a href="https://github.com/HiTOP-Ontologies/hitop-ontology/releases/latest">Latest release</a> ·
  <a href="http://purl.org/hitop">Ontology IRI</a>
</p>

---

Mental-health datasets describe related constructs with different labels,
instrument items, local codes and operational definitions. The HiTOP Ontology
provides a shared semantic layer for them:

- **RDF/OWL ontology** of the HiTOP hierarchy (superspectra, spectra,
  subfactors, components, traits) under `http://purl.org/hitop`
- **Stable identifiers.** HiTOP base codes are frozen from release 0.1.0 on
- **Factorization models.** Clinically reviewed alternative hierarchies are
  linked to the core ontology
- **Manifestation records.** Study-, instrument- and dataset-specific
  operationalizations are kept separate from the underlying constructs
- **Python tooling** for code generation, validation and format conversion
  (RDF/XML, Turtle, OWL)

### Repositories

| Repository | Description |
| --- | --- |
| [hitop-ontology](https://github.com/HiTOP-Ontologies/hitop-ontology) | Core ontology, identifiers, factorizations and tooling |

### Citation

Please cite the ontology using the metadata in
[`CITATION.cff`](https://github.com/HiTOP-Ontologies/hitop-ontology/blob/main/CITATION.cff)
(GitHub: *Cite this repository*).

### Scope

The HiTOP Ontology is intended for research and semantic interoperability. It
is **not** a diagnostic instrument and does not provide clinical advice.
