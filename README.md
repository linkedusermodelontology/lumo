# The Linked User Model Ontology (LUMO)
The Linked User Model Ontology (LUMO) is a mid-level ontology which semantically represents user-pertinent information in the networked media domain.

This work is licensed under a [Creative Commons Attribution-ShareAlike License (version 3.0)](http://creativecommons.org/licenses/by-sa/3.0/). This copyright applies to the LUMO Ontology, the LUMO mappings ontology and accompanying documentation.

The LUMO ontology was initially developed within the [LinkedTV](http://linkedtv.eu/) project (orginally named Linked**TV** User Model Ontology), in order to enable semantic personalization and contextualization in the networked media domain. 

It is since ectended in the premises of the [Hyper360](http://www.hyper360.eu/) H2020 project, to enrich it with more mid-level knowledge across various media sub-domains.

LUMO is designed as an OWL ontology, with its expressivity restricted to the OWL 2 RL profile, in order to maintain the minimal complexity and address scalability and user privacy issues. LUMO is currently accompanied by a separate mappings ontology, modeling mappings of LUMO to several existing ontologies and vocabularies.

Current version maps to:
- [DBPedia schema](http://wiki.dbpedia.org/Ontology)
- [schema.org](http://schema.org/docs/schemaorg.owl)
- [NERD ontology](http://nerd.eurecom.fr/ontology/)
- [IPTC news codes](http://webtlab.it.uc3m.es/results/NEWS/subjectcodes.owl) - as categorized by WebTLab 
- [GUMO](http://www.ubisworld.org/ubisworld/documents/gumo/2.0/gumo.owl)

These mappings were produced with the use of the [LogMap]( http://code.google.com/p/logmap-matcher/) (Logic-based and Scalable Ontology Matching) tool and revised manually.

In version 2.0, mappings automatically produced with LogMap, but not revised manually, are added for: 
- [HyperDB](https://wordpress.org/plugins/hyperdb/) and 
- [YAGO2S](https://www.mpi-inf.mpg.de/departments/databases-and-information-systems/research/yago-naga/yago/#c10444)

In version 3.0, mappings have not been significantly extended.

## Future work:
- Distribute knowledge to several ontologies, with one *core* ontology including most upper concepts, relations and axioms and several more specific ontologies for specific, populous, sub-domains (e.g. LUMO-Arts, LUMO-Sports, etc.). Subdomains will be connected to *core* and potentially with each other. 
- Further extend the arts-culture, healtgh and social events subdomains. 
- Update mappings to current versions of connected schemata to cover the entirety of v3.0.
