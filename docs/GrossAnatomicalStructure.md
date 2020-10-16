---
parent: Classes
title: biolink:GrossAnatomicalStructure
grand_parent: Browse Biolink Model
layout: default
---

# Type: GrossAnatomicalStructure




URI: [biolink:GrossAnatomicalStructure](https://w3id.org/biolink/vocab/GrossAnatomicalStructure)

UBERON:0010000
{: .mapping-label }

SIO:010046
{: .mapping-label }

WIKIDATA:Q4936952
{: .mapping-label }

UMLSSC:T017
{: .mapping-label }

UMLSST:anst
{: .mapping-label }

UMLSSC:T021
{: .mapping-label }

UMLSST:ffas
{: .mapping-label }

UMLSSC:T023
{: .mapping-label }

UMLSST:bpoc
{: .mapping-label }

UMLSSC:T024
{: .mapping-label }

UMLSST:tisu
{: .mapping-label }

UMLSSC:T018
{: .mapping-label }

UMLSST:emst
{: .mapping-label }


---

![img](http://yuml.me/diagram/nofunky;dir:TB/class/[OrganismTaxon],[AnatomicalEntity]%5E-[GrossAnatomicalStructure%7Cid(i):string;name(i):label_type;category(i):category_type%20%2B],[AnatomicalEntity])

---


## Identifier prefixes

 * UBERON
 * PO
 * FAO

## Parents

 *  is_a: [AnatomicalEntity](AnatomicalEntity.md) - A subcellular location, cell type or gross anatomical part

## Attributes


### Inherited from gene product:

 * [id](id.md)  <sub>REQ</sub>
    * Description: A unique identifier for a thing. Must be either a CURIE shorthand for a URI or a complete URI
    * range: [String](types/String.md)
    * in subsets: (translator_minimal)
 * [name](name.md)  <sub>REQ</sub>
    * Description: A human-readable name for a thing
    * range: [LabelType](types/LabelType.md)
    * in subsets: (translator_minimal)

### Inherited from named thing:

 * [category](category.md)  <sub>1..*</sub>
    * Description: Name of the high level ontology class in which this entity is categorized. Corresponds to the label for the biolink entity type class. In a neo4j database this MAY correspond to the neo4j label tag
    * range: [CategoryType](types/CategoryType.md)
    * in subsets: (translator_minimal)

### Inherited from thing with taxon:

 * [in taxon](in_taxon.md)  <sub>0..*</sub>
    * Description: connects a thing to a class representing a taxon
    * range: [OrganismTaxon](OrganismTaxon.md)
    * in subsets: (translator_minimal)

## Other properties

|  |  |  |
| --- | --- | --- |
| **Aliases:** | | tissue |
|  | | organ |
| **Mappings:** | | UBERON:0010000 |
|  | | SIO:010046 |
|  | | WIKIDATA:Q4936952 |
|  | | UMLSSC:T017 |
|  | | UMLSST:anst |
|  | | UMLSSC:T021 |
|  | | UMLSST:ffas |
|  | | UMLSSC:T023 |
|  | | UMLSST:bpoc |
|  | | UMLSSC:T024 |
|  | | UMLSST:tisu |
|  | | UMLSSC:T018 |
|  | | UMLSST:emst |
