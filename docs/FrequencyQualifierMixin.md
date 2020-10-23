---
parent: Mixins
title: biolink:FrequencyQualifierMixin
grand_parent: Browse Biolink Model
layout: default
---

# Class: FrequencyQualifierMixin


Qualifier for frequency type associations

URI: [biolink:FrequencyQualifierMixin](https://w3id.org/biolink/vocab/FrequencyQualifierMixin)


---

![img](http://yuml.me/diagram/nofunky;dir:TB/class/[FrequencyValue],[FrequencyValue]%3Cfrequency%20qualifier%200..1-%20[FrequencyQualifierMixin],[VariantToPopulationAssociation]uses%20-.-%3E[FrequencyQualifierMixin],[FrequencyQualifierMixin]%5E-[EntityToFeatureOrDiseaseQualifiers],[VariantToPopulationAssociation],[EntityToFeatureOrDiseaseQualifiers])

---


## Children

 * [EntityToFeatureOrDiseaseQualifiers](EntityToFeatureOrDiseaseQualifiers.md) - Qualifiers for entity to disease or phenotype associations

## Mixin for

 * [VariantToPopulationAssociation](VariantToPopulationAssociation.md) (mixin)  - An association between a variant and a population, where the variant has particular frequency in the population

## Referenced by class


## Attributes


### Own

 * [frequency qualifier](frequency_qualifier.md)  <sub>OPT</sub>
    * Description: a qualifier used in a phenotypic association to state how frequent the phenotype is observed in the subject
    * range: [FrequencyValue](FrequencyValue.md)