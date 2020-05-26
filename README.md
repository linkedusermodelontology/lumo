# The Linked User Model Ontology (LUMO)
The Linked User Model Ontology (LUMO) is a cross-domain ontology that constitutes the backgorund knowledge base (KB) to formally represent the contents of networked media items, in a manner pertinent to the media consumer. In addition, it models information about contextual information regarding the user/consumer, but also the content itself. 

Its main purpose is to provide a holistic and uniform vocabulary and schema, that is slim enough so as to enable tractable logical inference over the KB for the personalising content delivery by the media provider, but also concise enough so as to represent efficiently the diverse aspects of the generic media super-domain.

## Implementation
LUMO is designed as an OWL ontology, with its expressivity restricted to the OWL 2 RL profile, in order to maintain the minimal complexity and address scalability and user privacy issues. 

LUMO is currently accompanied by mappings to several existing ontologies and vocabularies, in separated OWL ontologies. Mappings were produced with the use of the [LogMap]( http://code.google.com/p/logmap-matcher/) (Logic-based and Scalable Ontology Matching) tool and, in most cases, revised manually.

Current version maps to:
- [DBPedia schema](http://wiki.dbpedia.org/Ontology)
- [schema.org](http://schema.org/docs/schemaorg.owl)
- [YAGO 4 Taxonomy](https://yago-knowledge.org/downloads/yago-4)
- [IPTC news codes](http://webtlab.it.uc3m.es/results/NEWS/subjectcodes.owl) - as [categorized by WebTLab](http://webtlab.it.uc3m.es/results/NEWS/ontologies.html)
- [GUMO](http://www.ubisworld.org/ubisworld/documents/gumo/2.0/gumo.owl)

## Licence
This work is licensed under a [Creative Commons Attribution-ShareAlike License (version 3.0)](http://creativecommons.org/licenses/by-sa/3.0/). This copyright applies to the LUMO Ontology, the LUMO mappings ontology and accompanying documentation.

## Publications
> Pending: publication of v4.

> Tsatsou, Dorothea, and Vasileios Mezaris. "LUMO: The LinkedTV user model ontology." European Semantic Web Conference. Springer, Cham, 2014. 

## Version history
The LUMO ontology was initially developed within the [LinkedTV](http://linkedtv.eu/) project (orginally named Linked**TV** User Model Ontology), in order to enable semantic personalization and contextualization in the networked media domain. 

It has since been extended in the premises of the [Hyper360](http://www.hyper360.eu/) H2020 project, to enrich it with more mid-level knowledge across various media sub-domains.

### Version 4.0
URI permanently changed to: (http://purl.org/lumo/) - *base*

Expansion of the fashion and lifestyle sub-domain (sub-areas included). Some expansions to 

Segmentation of the ontology into a family of interlinked sub-ontologies:

(Top level):
- Core - *URI: (http://purl.org/lumo/core/)*

(Second level):
- Context - *URI: (http://purl.org/lumo/context/)*
- Spatiotemporal - *URI: (http://purl.org/lumo/spatiotemporal/)*
- Agents - *URI: (http://purl.org/lumo/agent/)*
  
(Third level, domain-specific):
- Arts, culture, entertainment - *URI: (http://purl.org/lumo/artcult/)*
- Crime, law, justice - *URI: (http://purl.org/lumo/crimelaw/)*
- Disaster & accident - *URI: (http://purl.org/lumo/disacc/)*
- Economy, business, finance - *URI: (http://purl.org/lumo/economy/)*
- Education - *URI: (http://purl.org/lumo/edu/)*
- Health & well-being - *URI: (http://purl.org/lumo/health/)*
- Lifestyle & leisure - *URI: (http://purl.org/lumo/life/)*
- Nature & environment - *URI: (http://purl.org/lumo/natenv/)*
- Politics - *URI: (http://purl.org/lumo/politic/)*
- Religion & belief - *URI: (http://purl.org/lumo/religion/)*
- Science & technology - *URI: (http://purl.org/lumo/scitech/)*
- Society - *URI: (http://purl.org/lumo/soc/)*
- Sports - *URI: (http://purl.org/lumo/sport/)*
- Transportation - *URI: (http://purl.org/lumo/transportation/)*
- Unrest, conflicts, war  - *URI: (http://purl.org/lumo/unrest/)*
- Weather - *URI: (http://purl.org/lumo/weather/)*

Mappings for the expanded entities were re-produced (through LogMap) and revised manually. LUMO maps to:
- [DBPedia schema](http://wiki.dbpedia.org/Ontology)
- [schema.org](http://schema.org/docs/schemaorg.owl)
- [YAGO 4 Taxonomy](https://yago-knowledge.org/downloads/yago-4)
- [IPTC news codes](http://webtlab.it.uc3m.es/results/NEWS/subjectcodes.owl) - as [categorized by WebTLab](http://webtlab.it.uc3m.es/results/NEWS/ontologies.html)
- [GUMO](http://www.ubisworld.org/ubisworld/documents/gumo/2.0/gumo.owl)

### Version 3.0
Significant expansion to include domain specific semanics in the areas of music events, music, art and cultural history, educational and social events, exercise, health and wellbeing, consumer goods of various sorts, tourism and travel, and several sub-areas of the former. 

In version 3.0, mappings have not been extended.

### Version 2.0
Updates after use case testing in the premises of LinkedTV. Expansion of the *Arts-culture-entertainment* subdomain.

Mappings produced (automatically with LogMap), but **not** revised manually, were added for: 
- [HyperDB](https://wordpress.org/plugins/hyperdb/) and 
- [YAGO2S](https://www.mpi-inf.mpg.de/departments/databases-and-information-systems/research/yago-naga/yago/#c10444)

### Version 1.0
First model. Core hierarchy, object properties and axioms, especially w.r.t to topics and sub-topics, established. 

Mappings produced (automatically with LogMap) and revised manually to:
- [DBPedia schema](http://wiki.dbpedia.org/Ontology)
- [schema.org](http://schema.org/docs/schemaorg.owl)
- [NERD ontology](http://nerd.eurecom.fr/ontology/)
- [IPTC news codes](http://webtlab.it.uc3m.es/results/NEWS/subjectcodes.owl) - as [categorized by WebTLab](http://webtlab.it.uc3m.es/results/NEWS/ontologies.html)
- [GUMO](http://www.ubisworld.org/ubisworld/documents/gumo/2.0/gumo.owl)

## Future work:
- Additional domain-specific expansions.
