# chem-rdkit

Learning cheminformatics with RDKit through Jupyter notebooks.

## Tutorial Series

| #   | Notebook                                                                      | Topic                                                     |
| --- | ----------------------------------------------------------------------------- | --------------------------------------------------------- |
| 01  | [Molecular Representations](notebooks/01-molecular-representations.ipynb)     | SMILES, InChI, file formats, basic properties             |
| 02  | [Molecular Visualization](notebooks/02-molecular-visualization.ipynb)         | Drawing molecules, grid images, substructure highlighting |
| 03  | [Molecular Descriptors](notebooks/03-molecular-descriptors.ipynb)             | Physicochemical, topological, electronic descriptors, QED |
| 04  | [Substructure Searching](notebooks/04-substructure-searching.ipynb)           | SMARTS deep dive, functional group library, MCS           |
| 05  | [Fingerprints & Similarity](notebooks/05-fingerprints-and-similarity.ipynb)   | Morgan/ECFP, MACCS, Tanimoto, similarity matrices         |
| 06  | [Chemical Reactions](notebooks/06-chemical-reactions.ipynb)                   | Reaction SMARTS, named reactions, library enumeration     |
| 07  | [3D Conformers](notebooks/07-3d-conformers.ipynb)                             | Conformer generation, force fields, alignment             |
| 08  | [Molecular Datasets](notebooks/08-molecular-datasets.ipynb)                   | SDF/SMILES I/O, pandas integration, data curation         |
| 09  | [Drug-Likeness Filters](notebooks/09-drug-likeness-filters.ipynb)             | Lipinski, Veber, PAINS, multi-filter pipelines            |
| 10  | [Cheminformatics Workflows](notebooks/10-cheminformatics-workflows.ipynb)     | Scaffolds, clustering, diversity, virtual screening       |
| 11  | [Exercises](notebooks/11-exercises.ipynb)                                     | Practice problems for all topics                          |
| 12  | [Atom Feature Vector](notebooks/12-atom-feature-vector.ipynb)                 | Atom Feature Vector                                       |
| 13  | [3D Molecular Visualization](notebooks/13-3d-molecular-representations.ipynb) | 3D Molecular Visualtzation                                |

Each notebook includes chemistry refreshers that bridge wet-lab intuition to computational concepts.

## Setup

```bash
uv sync
```

## Run notebooks

```bash
uv run jupyter lab
```
