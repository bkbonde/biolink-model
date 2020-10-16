---
parent: Classes
title: biolink:AnatomicalEntity
grand_parent: Browse Biolink Model
layout: default
---

# Type: AnatomicalEntity


A subcellular location, cell type or gross anatomical part

URI: [biolink:AnatomicalEntity](https://w3id.org/biolink/vocab/AnatomicalEntity)

SIO:010046
{: .mapping-label }

UBERON:0001062
{: .mapping-label }

WIKIDATA:Q4936952
{: .mapping-label }

UMLSSG:ANAT
{: .mapping-label }

UMLSSC:T022
{: .mapping-label }

UMLSST:bdsy
{: .mapping-label }

UMLSSC:T029
{: .mapping-label }

UMLSST:blor
{: .mapping-label }

UMLSSC:T030
{: .mapping-label }

UMLSST:bsoj
{: .mapping-label }

UMLSSC:T031
{: .mapping-label }

UMLSST:bdsu
{: .mapping-label }


---

![img](http://yuml.me/diagram/nofunky;dir:TB/class/[ThingWithTaxon],[PhysicalEntity],[OrganismalEntity],[OrganismTaxon],[GrossAnatomicalStructure],[GeneToExpressionSiteAssociation],[GeneOrGeneProduct],[DiseaseOrPhenotypicFeatureAssociationToLocationAssociation],[CellularComponent],[Cell],[AnatomicalEntityToAnatomicalEntityPartOfAssociation],[AnatomicalEntityToAnatomicalEntityOntogenicAssociation],[AnatomicalEntityToAnatomicalEntityAssociation],[AnatomicalEntityToAnatomicalEntityAssociation]-%20object%201..1%3E[AnatomicalEntity%7Cid(i):string;name(i):label_type;category(i):category_type%20%2B],[AnatomicalEntityToAnatomicalEntityAssociation]-%20subject%201..1%3E[AnatomicalEntity],[AnatomicalEntityToAnatomicalEntityOntogenicAssociation]-%20object%201..1%3E[AnatomicalEntity],[AnatomicalEntityToAnatomicalEntityOntogenicAssociation]-%20subject%201..1%3E[AnatomicalEntity],[AnatomicalEntityToAnatomicalEntityPartOfAssociation]-%20object%201..1%3E[AnatomicalEntity],[AnatomicalEntityToAnatomicalEntityPartOfAssociation]-%20subject%201..1%3E[AnatomicalEntity],[DiseaseOrPhenotypicFeatureAssociationToLocationAssociation]-%20object%201..1%3E[AnatomicalEntity],[GeneToExpressionSiteAssociation]-%20object%201..1%3E[AnatomicalEntity],[AnatomicalEntity]uses%20-.-%3E[ThingWithTaxon],[AnatomicalEntity]uses%20-.-%3E[PhysicalEntity],[AnatomicalEntity]%5E-[GrossAnatomicalStructure],[AnatomicalEntity]%5E-[CellularComponent],[AnatomicalEntity]%5E-[Cell],[OrganismalEntity]%5E-[AnatomicalEntity])

---


## Identifier prefixes

 * UBERON
 * GO
 * CL
 * UMLS
 * MESH
 * NCIT

## Parents

 *  is_a: [OrganismalEntity](OrganismalEntity.md) - A named entity that is either a part of an organism, a whole organism, population or clade of organisms, excluding molecular entities

## Uses Mixins

 *  mixin: [ThingWithTaxon](ThingWithTaxon.md) - A mixin that can be used on any entity with a taxon
 *  mixin: [PhysicalEntity](PhysicalEntity.md) - An entity that has physical properties such as mass, volume, or charge

## Children

 * [Cell](Cell.md)
 * [CellularComponent](CellularComponent.md) - A location in or around a cell
 * [GrossAnatomicalStructure](GrossAnatomicalStructure.md)

## Referenced by class

 *  **[AnatomicalEntityToAnatomicalEntityAssociation](AnatomicalEntityToAnatomicalEntityAssociation.md)** *[anatomical entity to anatomical entity association➞object](anatomical_entity_to_anatomical_entity_association_object.md)*  <sub>REQ</sub>  **[AnatomicalEntity](AnatomicalEntity.md)**
 *  **[AnatomicalEntityToAnatomicalEntityAssociation](AnatomicalEntityToAnatomicalEntityAssociation.md)** *[anatomical entity to anatomical entity association➞subject](anatomical_entity_to_anatomical_entity_association_subject.md)*  <sub>REQ</sub>  **[AnatomicalEntity](AnatomicalEntity.md)**
 *  **[AnatomicalEntityToAnatomicalEntityOntogenicAssociation](AnatomicalEntityToAnatomicalEntityOntogenicAssociation.md)** *[anatomical entity to anatomical entity ontogenic association➞object](anatomical_entity_to_anatomical_entity_ontogenic_association_object.md)*  <sub>REQ</sub>  **[AnatomicalEntity](AnatomicalEntity.md)**
 *  **[AnatomicalEntityToAnatomicalEntityOntogenicAssociation](AnatomicalEntityToAnatomicalEntityOntogenicAssociation.md)** *[anatomical entity to anatomical entity ontogenic association➞subject](anatomical_entity_to_anatomical_entity_ontogenic_association_subject.md)*  <sub>REQ</sub>  **[AnatomicalEntity](AnatomicalEntity.md)**
 *  **[AnatomicalEntityToAnatomicalEntityPartOfAssociation](AnatomicalEntityToAnatomicalEntityPartOfAssociation.md)** *[anatomical entity to anatomical entity part of association➞object](anatomical_entity_to_anatomical_entity_part_of_association_object.md)*  <sub>REQ</sub>  **[AnatomicalEntity](AnatomicalEntity.md)**
 *  **[AnatomicalEntityToAnatomicalEntityPartOfAssociation](AnatomicalEntityToAnatomicalEntityPartOfAssociation.md)** *[anatomical entity to anatomical entity part of association➞subject](anatomical_entity_to_anatomical_entity_part_of_association_subject.md)*  <sub>REQ</sub>  **[AnatomicalEntity](AnatomicalEntity.md)**
 *  **[DiseaseOrPhenotypicFeatureAssociationToLocationAssociation](DiseaseOrPhenotypicFeatureAssociationToLocationAssociation.md)** *[disease or phenotypic feature association to location association➞object](disease_or_phenotypic_feature_association_to_location_association_object.md)*  <sub>REQ</sub>  **[AnatomicalEntity](AnatomicalEntity.md)**
 *  **[GeneOrGeneProduct](GeneOrGeneProduct.md)** *[expressed in](expressed_in.md)*  <sub>0..*</sub>  **[AnatomicalEntity](AnatomicalEntity.md)**
 *  **[GeneToExpressionSiteAssociation](GeneToExpressionSiteAssociation.md)** *[gene to expression site association➞object](gene_to_expression_site_association_object.md)*  <sub>REQ</sub>  **[AnatomicalEntity](AnatomicalEntity.md)**

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
| **Mappings:** | | SIO:010046 |
|  | | UBERON:0001062 |
|  | | WIKIDATA:Q4936952 |
|  | | UMLSSG:ANAT |
|  | | UMLSSC:T022 |
|  | | UMLSST:bdsy |
|  | | UMLSSC:T029 |
|  | | UMLSST:blor |
|  | | UMLSSC:T030 |
|  | | UMLSST:bsoj |
|  | | UMLSSC:T031 |
|  | | UMLSST:bdsu |
