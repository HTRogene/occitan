# HTRogène - Spain

<table border="0" width="100%" style="width: 100%; border:0;">
  <tr>
    <td align="left"><img src="https://projet.biblissima.fr/sites/default/files/logos/biblissima-baseline-sombre-france2030.png" height="150px" /></td>
    <td align="right"><img src="https://projet.biblissima.fr/sites/default/files/styles/large_600x600_/public/2024-08/illustration-htrogene-carre.png" height="150px" /></td>
  </tr>
</table>

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
![characters badge](badges/characters.svg) ![regions badge](badges/regions.svg) ![lines badge](badges/lines.svg) ![files badge](badges/files.svg)

## Introduction

HTRogène is an exploratory project funded by Biblissima+, aiming to develop generic models for automatic transcription of medieval and early modern manuscripts.  
This repository focuses on the Medieval Occitan corpus, providing ground-truth data for Handwritten Text Recognition (HTR) and layout segmentation.  
The dataset is designed to support the creation of robust and reliable HTR models for Occitan manuscripts.

| Shelfmark                               | Links                                              | Type   |   Century | Color Pages   |   Main Zones |   Lines |   Characters | Genre      |
|-----------------------------------------|----------------------------------------------------|--------|-----------|---------------|--------------|---------|--------------|------------|
| London, British Library, Harley MS 3041 | [**B**](https://data.biblissima.fr/entity/Q272358) | prose  |        14 | ✗             |            1 |      38 |         1634 | Narratives |
| London, British Library, Harley MS 7403 | [**B**](https://data.biblissima.fr/entity/Q272405) | verse  |        14 | ✗             |           10 |     175 |         3690 | Poetry     |
| Paris, BnF, fr. 13059                   | [**B**](https://data.biblissima.fr/entity/Q46358)  | verse  |        14 | ✗             |           12 |     350 |         7414 | Narratives |

This dataset is part of [CATMuS Medieval](https://huggingface.co/datasets/CATMuS/medieval). More on CATMuS [here](https://catmus-guidelines.github.io/).

## Dataset Overview

The dataset comprises carefully selected manuscripts, each containing approximately 10 columns of text (equivalent to 5 bi-column pages or 10 single-column pages).  
The data adheres to the Segmonto guidelines, ensuring consistency and compatibility with other datasets following the same standards.  
Each image is accompanied by two XML files:

- Files suffixed with `.chocomufin.xml` are normalized for compliance with broader datasets.
- The other XML files contain repository-specific information.

We recommend using the normalized `.chocomufin.xml` files for most applications.


### Total number of pages

65

### Regions

- MainZone (101)
- DigitizationArtefactZone (28)
- NumberingZone (31)
- MarginTextZone (27)
- StampZone (1)
- RunningTitleZone (3)
- GraphicZone (2)
- DropCapitalZone (6)

### Lines

- HeadingLine (68)
- DefaultLine (2808)
- InterlinearLine (4)


## Funding and Support

This project is funded by Biblissima+, an observatory for medieval and Renaissance written cultural heritage.  
Biblissima+ focuses on the study of the circulation of books and the transmission of texts from the 8th to 18th centuries.  
Learn more at the [Biblissima+ project page](https://projet.biblissima.fr/fr/appels-projets/projets-retenus/htrogene).

## License

This dataset is licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0).  
You are free to share and adapt the material, provided appropriate credit is given.

## Citation

If you use this dataset in your research, please cite it as follows:

> Wiedner, M., & Couffignal, G., & Chagué, A., & Clérice, T. HTRogène, Occitan corpus of ground-truth for Handwritten Text Recognition and Layout Segmentation [Data set]. https://github.com/HTRogene/occitan


## Acknowledgments

We extend our gratitude to the transcribers and supervisors who contributed to the creation of this dataset.  

Special thanks to Biblissima+ for their financial support and commitment to advancing the study of medieval manuscripts.

For more information about the HTRogène project and other related resources, please visit the [Biblissima+ project page](https://projet.biblissima.fr/fr/appels-projets/projets-retenus/htrogene).
