---
parent: Classes
title: biolink:Zygosity
grand_parent: Browse Biolink Model
layout: default
---

# Type: Zygosity




URI: [biolink:Zygosity](https://w3id.org/biolink/vocab/Zygosity)

GENO:0000133
{: .mapping-label }


---

![img](http://yuml.me/diagram/nofunky;dir:TB/class/[Genotype]-%20has%20zygosity%200..1%3E[Zygosity%7Cid(i):string;name(i):label_type;category(i):category_type%20%2B],[Attribute]%5E-[Zygosity],[QuantityValue],[OntologyClass],[NamedThing],[Genotype],[Attribute])

---


## Parents

 *  is_a: [Attribute](Attribute.md) - A property or characteristic of an entity. For example, an apple may have properties such as color, shape, age, crispiness. An environmental sample may have attributes such as depth, lat, long, material.

## Referenced by class

 *  **[NamedThing](NamedThing.md)** *[has zygosity](has_zygosity.md)*  <sub>OPT</sub>  **[Zygosity](Zygosity.md)**

## Attributes


### Inherited from attribute:

 * [has attribute type](has_attribute_type.md)  <sub>OPT</sub>
    * Description: connects an attribute to a class that describes it
    * range: [OntologyClass](OntologyClass.md)
    * in subsets: (samples)
 * [has quantitative value](has_quantitative_value.md)  <sub>0..*</sub>
    * Description: connects an attribute to a value
    * range: [QuantityValue](QuantityValue.md)
    * in subsets: (samples)
 * [has qualitative value](has_qualitative_value.md)  <sub>OPT</sub>
    * Description: connects an attribute to a value
    * range: [NamedThing](NamedThing.md)
    * in subsets: (samples)

### Inherited from named thing:

 * [id](id.md)  <sub>REQ</sub>
    * Description: A unique identifier for a thing. Must be either a CURIE shorthand for a URI or a complete URI
    * range: [String](types/String.md)
    * in subsets: (translator_minimal)
 * [name](name.md)  <sub>REQ</sub>
    * Description: A human-readable name for a thing
    * range: [LabelType](types/LabelType.md)
    * in subsets: (translator_minimal)
 * [category](category.md)  <sub>1..*</sub>
    * Description: Name of the high level ontology class in which this entity is categorized. Corresponds to the label for the biolink entity type class. In a neo4j database this MAY correspond to the neo4j label tag
    * range: [CategoryType](types/CategoryType.md)
    * in subsets: (translator_minimal)

## Other properties

|  |  |  |
| --- | --- | --- |
| **Mappings:** | | GENO:0000133 |
