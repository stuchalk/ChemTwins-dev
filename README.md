# ChemTwins-dev
The concept of digital twins has been around since [2002](https://en.wikipedia.org/wiki/Digital_twin) 
and describes a digital representation of a physical object or system.  Today digital twins can be 
realized by using semantic definition of known facts about a thing (assertions) using the Resource 
Description Framework ([RDF](https://www.w3.org/RDF/)).

This repository provides a set of 10,491 [JSON-LD](https://www.w3.org/TR/json-ld/) files (an encoding of RDF) organized 
in the [SciData framework](https://stuchalk.github.io/scidata/) format that each describe metadata, identifiers, 
descriptors, and a molecular graph for representing digital twins of chemical substances ('chemical twins').

This idea was presented at the Spring 2022 American Chemical Society (ACS) meeting (presentation included above). This
repository is provided to solicit feedback from the community about how it might be evolved in the future to support 
semantic representation of chemical compounds, elements, ions etc. for semantic interoperability as part of making data 
[FAIR](https://doi.org/10.1038/sdata.2016.18).

In addition to the dataset (zip file above) and the presentation the following are also provided:
- a zip file of a mysql table of 'quads' where each JSON-LD file has been converted to its equivalent triple
  (actually quad - where the graph name added as a fourth column) and saved as a row in the table
- a spreadsheet summarizing statistics of the predicates in the 'quads' table rows
  (this present a picture of the types of 'things' that in files)

The community is invited to play with this resource and provide feedback via the repository as to the
usefulness and/or issues/updates/deletions needed to make it better for cheminformatic usage.

UPDATE: Individual files in the set are now available at 
[https://scidata.unf.edu/tranche/chemtwin/test](https://scidata.unf.edu/tranche/chemtwin/test)

Stuart Chalk 6/9/22

[![DOI](https://zenodo.org/badge/471474621.svg)](https://zenodo.org/badge/latestdoi/471474621)

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa] This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg