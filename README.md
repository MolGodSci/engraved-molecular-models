# Engraved molecular models

Free, 3D-printable ball-and-stick models of real molecules, with the **element symbol engraved on every atom**.
A student holding the model can read which atom is which and how the atoms are connected, without a colour key and even
from a single-colour print. The models are made for chemistry teachers, students and makers.

Project page: https://molgod.org/engraved-molecular-models/

## What is in this repository

```
models/<CAS>/<name>.stl          the printable mesh (binary STL, coordinates in angstrom)
models/<CAS>/<name>-render.png   a preview render of the same mesh
models/<CAS>/metadata.json       CAS number, name, formula, PubChem CID, SHA-256 of the STL, citation DOI, Commons URL
```

- Geometry comes from PubChem computed 3D conformers; atomic coordinates and connectivity are not changed.
- Each STL is byte-for-byte the same file as the one on Wikimedia Commons (the SHA-256 in `metadata.json` lets you check it).
- **Scale before printing:** STL has no unit and these files are in angstrom, so scale them (for example 10x) in your slicer.
- New molecules are added over time; this list is regenerated on every update.

## Licence

All models, renders and metadata are licensed under **Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)**,
see [LICENSE](LICENSE). Credit "MolGod.org", link to the original and to the licence, say what you changed, and share
adaptations under the same licence. Suggested attribution:

> "<Molecule> 3D model by MolGod.org, https://molgod.org/engraved-molecular-models/, CC BY-SA 4.0"

## How to cite

Please cite the **Zenodo concept DOI** of each molecule (column "Cite" below). It always resolves to the latest version of the
record. This repository has no DOI of its own; it is a mirror for convenient download, not a separate dataset.
`CITATION.cff` describes the collection.

Themed collections of the same models are also deposited in research repositories (B2SHARE, OSF); they are linked from the
project page above.

## Models (10)

| Molecule | CAS | Formula | Cite (Zenodo concept DOI) | Wikimedia Commons | PubChem CID |
|---|---|---|---|---|---|
| [Epichlorohydrin](models/106-89-8/) | 106-89-8 | C3H5ClO | [10.5281/zenodo.23296190](https://doi.org/10.5281/zenodo.23296190) | [Commons](https://commons.wikimedia.org/wiki/File%3AEpichlorohydrin-3D-molecular-model-engraved-CAS-106-89-8.stl) | [7835](https://pubchem.ncbi.nlm.nih.gov/compound/7835) |
| [Glycidyl methacrylate](models/106-91-2/) | 106-91-2 | C7H10O3 | [10.5281/zenodo.23296252](https://doi.org/10.5281/zenodo.23296252) | [Commons](https://commons.wikimedia.org/wiki/File%3AGlycidyl_methacrylate-3D-molecular-model-engraved-CAS-106-91-2.stl) | [7837](https://pubchem.ncbi.nlm.nih.gov/compound/7837) |
| [1-Bromopropane](models/106-94-5/) | 106-94-5 | C3H7Br | [10.5281/zenodo.23277518](https://doi.org/10.5281/zenodo.23277518) | [Commons](https://commons.wikimedia.org/wiki/File%3A1-Bromopropane-3D-molecular-model-engraved-CAS-106-94-5.stl) | [7840](https://pubchem.ncbi.nlm.nih.gov/compound/7840) |
| [1,2-Dichloroethane](models/107-06-2/) | 107-06-2 | C2H4Cl2 | [10.5281/zenodo.23283187](https://doi.org/10.5281/zenodo.23283187) | [Commons](https://commons.wikimedia.org/wiki/File%3A1%2C2-Dichloroethane-3D-molecular-model-engraved-CAS-107-06-2.stl) | [11](https://pubchem.ncbi.nlm.nih.gov/compound/11) |
| [Acetic Anhydride](models/108-24-7/) | 108-24-7 | C4H6O3 | [10.5281/zenodo.23277159](https://doi.org/10.5281/zenodo.23277159) | [Commons](https://commons.wikimedia.org/wiki/File%3AAcetic_Anhydride-3D-molecular-model-engraved-CAS-108-24-7.stl) | [7918](https://pubchem.ncbi.nlm.nih.gov/compound/7918) |
| [Pentane](models/109-66-0/) | 109-66-0 | C5H12 | [10.5281/zenodo.23277165](https://doi.org/10.5281/zenodo.23277165) | [Commons](https://commons.wikimedia.org/wiki/File%3APentane-3D-molecular-model-engraved-CAS-109-66-0.stl) | [8003](https://pubchem.ncbi.nlm.nih.gov/compound/8003) |
| [Hexane](models/110-54-3/) | 110-54-3 | C6H14 | [10.5281/zenodo.23277584](https://doi.org/10.5281/zenodo.23277584) | [Commons](https://commons.wikimedia.org/wiki/File%3AHexane-3D-molecular-model-engraved-CAS-110-54-3.stl) | [8058](https://pubchem.ncbi.nlm.nih.gov/compound/8058) |
| [Cyclohexane](models/110-82-7/) | 110-82-7 | C6H12 | [10.5281/zenodo.23277175](https://doi.org/10.5281/zenodo.23277175) | [Commons](https://commons.wikimedia.org/wiki/File%3ACyclohexane-3D-molecular-model-engraved-CAS-110-82-7.stl) | [8078](https://pubchem.ncbi.nlm.nih.gov/compound/8078) |
| [Perfluorooctanesulfonic acid](models/1763-23-1/) | 1763-23-1 | C8HF17O3S | [10.5281/zenodo.23454095](https://doi.org/10.5281/zenodo.23454095) | [Commons](https://commons.wikimedia.org/wiki/File%3APerfluorooctanesulfonic_acid-3D-molecular-model-engraved-CAS-1763-23-1.stl) | [74483](https://pubchem.ncbi.nlm.nih.gov/compound/74483) |
| [L-menthol](models/2216-51-5/) | 2216-51-5 | C10H20O | [10.5281/zenodo.23274432](https://doi.org/10.5281/zenodo.23274432) | [Commons](https://commons.wikimedia.org/wiki/File%3AL-menthol-3D-molecular-model-engraved-CAS-2216-51-5.stl) | [16666](https://pubchem.ncbi.nlm.nih.gov/compound/16666) |

## Source structures

Kim, S., Chen, J., Cheng, T., et al. (2025). PubChem 2025 update. *Nucleic Acids Research*, 53(D1), D1516-D1525.
https://doi.org/10.1093/nar/gkae1059

## Contact

Questions, classroom feedback and requests for a molecule by its CAS number: https://molgod.org/contact/
