---
parent: Mixins
title: biolink:VariantToThingAssociation
grand_parent: Browse Biolink Model
layout: default
---

# Type: VariantToThingAssociation




URI: [biolink:VariantToThingAssociation](https://w3id.org/biolink/vocab/VariantToThingAssociation)


---

![img](http://yuml.me/diagram/nofunky;dir:TB/class/[SequenceVariant]%3Csubject%201..1-%20[VariantToThingAssociation%7Crelation(i):uriorcurie;id(i):string;negated(i):boolean%20%3F],[VariantToPopulationAssociation]uses%20-.-%3E[VariantToThingAssociation],[VariantToPhenotypicFeatureAssociation]uses%20-.-%3E[VariantToThingAssociation],[VariantToDiseaseAssociation]uses%20-.-%3E[VariantToThingAssociation],[Association]%5E-[VariantToThingAssociation],[VariantToPopulationAssociation],[VariantToPhenotypicFeatureAssociation],[VariantToDiseaseAssociation],[SequenceVariant],[Publication],[Provider],[OntologyClass],[NamedThing],[Association])

---


## Parents

 *  is_a: [Association](Association.md) - A typed association between two entities, supported by evidence

## Mixin for

 * [VariantToDiseaseAssociation](VariantToDiseaseAssociation.md) (mixin) 
 * [VariantToPhenotypicFeatureAssociation](VariantToPhenotypicFeatureAssociation.md) (mixin) 
 * [VariantToPopulationAssociation](VariantToPopulationAssociation.md) (mixin)  - An association between a variant and a population, where the variant has particular frequency in the population

## Referenced by class


## Attributes


### Own

 * [variant to thing association➞subject](variant_to_thing_association_subject.md)  <sub>REQ</sub>
    * Description: a sequence variant in which the allele state is associated with some other entity
    * range: [SequenceVariant](SequenceVariant.md)
    * Example:    
    * Example:    

### Inherited from association:

 * [subject](subject.md)  <sub>REQ</sub>
    * Description: connects an association to the subject of the association. For example, in a gene-to-phenotype association, the gene is subject and phenotype is object.
    * range: [NamedThing](NamedThing.md)
 * [relation](relation.md)  <sub>REQ</sub>
    * Description: The relation which describes an association between a subject and an object in a more granular manner. Usually this is a term from Relation Ontology, but it can be any edge CURIE.
    * range: [Uriorcurie](types/Uriorcurie.md)
 * [object](object.md)  <sub>REQ</sub>
    * Description: connects an association to the object of the association. For example, in a gene-to-phenotype association, the gene is subject and phenotype is object.
    * range: [NamedThing](NamedThing.md)
 * [association➞id](association_id.md)  <sub>REQ</sub>
    * Description: A unique identifier for an association
    * range: [String](types/String.md)
    * in subsets: (translator_minimal)
 * [negated](negated.md)  <sub>OPT</sub>
    * Description: if set to true, then the association is negated i.e. is not true
    * range: [Boolean](types/Boolean.md)
 * [association type](association_type.md)  <sub>OPT</sub>
    * Description: connects an association to the type of association (e.g. gene to phenotype)
    * range: [OntologyClass](OntologyClass.md)
 * [qualifiers](qualifiers.md)  <sub>0..*</sub>
    * Description: connects an association to qualifiers that modify or qualify the meaning of that association
    * range: [OntologyClass](OntologyClass.md)
 * [publications](publications.md)  <sub>0..*</sub>
    * Description: connects an association to publications supporting the association
    * range: [Publication](Publication.md)
 * [provided by](provided_by.md)  <sub>0..*</sub>
    * Description: connects an association to the agent (person, organization or group) that provided it
    * range: [Provider](Provider.md)

### Domain for slot:

 * [variant to thing association➞subject](variant_to_thing_association_subject.md)  <sub>REQ</sub>
    * Description: a sequence variant in which the allele state is associated with some other entity
    * range: [SequenceVariant](SequenceVariant.md)
    * Example:    
    * Example:    

## Other properties

|  |  |  |
| --- | --- | --- |
| **Local names:** | | variant annotation (ga4gh) |
