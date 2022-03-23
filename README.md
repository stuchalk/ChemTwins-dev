# ChemTwins-dev
The concept of digital twins has been around since [2002](https://en.wikipedia.org/wiki/Digital_twin) 
and describes a digital representation of a physical object or system.  Today digital twins can be 
realized by using semantic definition of known facts about a thing (assertions) using the Resource 
Description Framework ([RDF](https://www.w3.org/RDF/)).

This repository provides a set of 10,491 [JSON-LD](https://www.w3.org/TR/json-ld/) files (an encoding of RDF) organized in the SciData
framework format that each describe metadata, identifiers, descriptors, and a molecular graph for 
represent digital twins of chemical substances.

This idea was presented at the 2022 Spring American Chemical Society (ACS) meeting (presentation 
included above) and this site is available to solicit feedback from the community about the idea 
and how it might be improved/extended in the future to support semantic representation of chemical 
compounds, elements, ions etc.

In addition to the dataset (zip file above) and the presentation the following are also provided:
- a zip file of a mysql 'quads' database table of the converted semantic triples
  (actually quads - graphname added as fourth column)
- a spreadsheet summarizing statistics about the data in the quads database organized
  around the predicates in the triples

The community is invited to play with this resource and provide feedback via the repository as to the
usefulness and/or issues/updates/deletions needed to make it better for cheminformatic usage.

Stuart Chalk 3/23/22