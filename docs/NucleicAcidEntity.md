---
parent: Entities
title: biolink:NucleicAcidEntity
grand_parent: Classes
layout: default
---

# Class: NucleicAcidEntity


A nucleic acid entity is a molecular entity characterized by availability in gene databases of nucleotide-based sequence representations of its precise sequence; for convenience of representation, partial sequences of various kinds are included.

URI: [biolink:NucleicAcidEntity](https://w3id.org/biolink/vocab/NucleicAcidEntity)


---

![img](https://yuml.me/diagram/nofunky;dir:TB/class/[Transcript],[SequenceVariant],[SequenceFeatureRelationship],[PhysicalEssence],[OrganismTaxon],[OntologyClass],[GenomicSequenceLocalization]-%20object%201..1%3E[NucleicAcidEntity%7Chas_biological_sequence:biological_sequence%20%3F;is_metabolite(i):boolean%20%3F;available_from(i):drug_availability_enum%20%2A;max_tolerated_dose(i):string%20%3F;is_toxic(i):boolean%20%3F;id(i):string;iri(i):iri_type%20%3F;type(i):string%20%3F;name(i):label_type%20%3F;description(i):narrative_text%20%3F;source(i):label_type%20%3F],[GenomicSequenceLocalization]-%20subject%201..1%3E[NucleicAcidEntity],[SequenceFeatureRelationship]-%20object%201..1%3E[NucleicAcidEntity],[SequenceFeatureRelationship]-%20subject%201..1%3E[NucleicAcidEntity],[NucleicAcidEntity]uses%20-.-%3E[GenomicEntity],[NucleicAcidEntity]uses%20-.-%3E[PhysicalEssence],[NucleicAcidEntity]uses%20-.-%3E[OntologyClass],[NucleicAcidEntity]%5E-[Transcript],[NucleicAcidEntity]%5E-[Exon],[NucleicAcidEntity]%5E-[CodingSequence],[MolecularEntity]%5E-[NucleicAcidEntity],[NamedThing],[MolecularEntity],[GenomicSequenceLocalization],[GenomicEntity],[Exon],[CodingSequence],[ChemicalEntityOrGeneOrGeneProduct],[ChemicalEntity],[Attribute],[Agent])

---


## Identifier prefixes

 * PUBCHEM.COMPOUND
 * CHEMBL.COMPOUND
 * UNII
 * CHEBI
 * MESH
 * CAS
 * GTOPDB
 * HMDB
 * KEGG.COMPOUND
 * ChemBank
 * Aeolus
 * PUBCHEM.SUBSTANCE
 * INCHI
 * INCHIKEY
 * KEGG.GLYCAN
 * KEGG.ENVIRON

## Parents

 *  is_a: [MolecularEntity](MolecularEntity.md) - A molecular entity is a chemical entity composed of individual or covalently bonded atoms.

## Uses Mixins

 *  mixin: [GenomicEntity](GenomicEntity.md)
 *  mixin: [PhysicalEssence](PhysicalEssence.md) - Semantic mixin concept.  Pertains to entities that have physical properties such as mass, volume, or charge.
 *  mixin: [OntologyClass](OntologyClass.md) - a concept or class in an ontology, vocabulary or thesaurus. Note that nodes in a biolink compatible KG can be considered both instances of biolink classes, and OWL classes in their own right. In general you should not need to use this class directly. Instead, use the appropriate biolink class. For example, for the GO concept of endocytosis (GO:0006897), use bl:BiologicalProcess as the type.

## Children

 * [CodingSequence](CodingSequence.md)
 * [Exon](Exon.md) - A region of the transcript sequence within a gene which is not removed from the primary RNA transcript by RNA splicing.
 * [Transcript](Transcript.md) - An RNA synthesized on a DNA or RNA template by an RNA polymerase.

## Referenced by class

 *  **[NamedThing](NamedThing.md)** *[affects expression of](affects_expression_of.md)*  <sub>0..\*</sub>  **[NucleicAcidEntity](NucleicAcidEntity.md)**
 *  **[ChemicalEntityOrGeneOrGeneProduct](ChemicalEntityOrGeneOrGeneProduct.md)** *[affects folding of](affects_folding_of.md)*  <sub>0..\*</sub>  **[NucleicAcidEntity](NucleicAcidEntity.md)**
 *  **[ChemicalEntityOrGeneOrGeneProduct](ChemicalEntityOrGeneOrGeneProduct.md)** *[affects mutation rate of](affects_mutation_rate_of.md)*  <sub>0..\*</sub>  **[NucleicAcidEntity](NucleicAcidEntity.md)**
 *  **[NamedThing](NamedThing.md)** *[decreases expression of](decreases_expression_of.md)*  <sub>0..\*</sub>  **[NucleicAcidEntity](NucleicAcidEntity.md)**
 *  **[ChemicalEntityOrGeneOrGeneProduct](ChemicalEntityOrGeneOrGeneProduct.md)** *[decreases folding of](decreases_folding_of.md)*  <sub>0..\*</sub>  **[NucleicAcidEntity](NucleicAcidEntity.md)**
 *  **[ChemicalEntity](ChemicalEntity.md)** *[decreases mutation rate of](decreases_mutation_rate_of.md)*  <sub>0..\*</sub>  **[NucleicAcidEntity](NucleicAcidEntity.md)**
 *  **[GenomicSequenceLocalization](GenomicSequenceLocalization.md)** *[genomic sequence localization➞object](genomic_sequence_localization_object.md)*  <sub>1..1</sub>  **[NucleicAcidEntity](NucleicAcidEntity.md)**
 *  **[GenomicSequenceLocalization](GenomicSequenceLocalization.md)** *[genomic sequence localization➞subject](genomic_sequence_localization_subject.md)*  <sub>1..1</sub>  **[NucleicAcidEntity](NucleicAcidEntity.md)**
 *  **[NucleicAcidEntity](NucleicAcidEntity.md)** *[has sequence location](has_sequence_location.md)*  <sub>0..\*</sub>  **[NucleicAcidEntity](NucleicAcidEntity.md)**
 *  **[NamedThing](NamedThing.md)** *[increases expression of](increases_expression_of.md)*  <sub>0..\*</sub>  **[NucleicAcidEntity](NucleicAcidEntity.md)**
 *  **[ChemicalEntityOrGeneOrGeneProduct](ChemicalEntityOrGeneOrGeneProduct.md)** *[increases folding of](increases_folding_of.md)*  <sub>0..\*</sub>  **[NucleicAcidEntity](NucleicAcidEntity.md)**
 *  **[ChemicalEntity](ChemicalEntity.md)** *[increases mutation rate of](increases_mutation_rate_of.md)*  <sub>0..\*</sub>  **[NucleicAcidEntity](NucleicAcidEntity.md)**
 *  **[SequenceVariant](SequenceVariant.md)** *[is sequence variant of](is_sequence_variant_of.md)*  <sub>0..\*</sub>  **[NucleicAcidEntity](NucleicAcidEntity.md)**
 *  **[SequenceFeatureRelationship](SequenceFeatureRelationship.md)** *[sequence feature relationship➞object](sequence_feature_relationship_object.md)*  <sub>1..1</sub>  **[NucleicAcidEntity](NucleicAcidEntity.md)**
 *  **[SequenceFeatureRelationship](SequenceFeatureRelationship.md)** *[sequence feature relationship➞subject](sequence_feature_relationship_subject.md)*  <sub>1..1</sub>  **[NucleicAcidEntity](NucleicAcidEntity.md)**
 *  **[NucleicAcidEntity](NucleicAcidEntity.md)** *[sequence location of](sequence_location_of.md)*  <sub>0..\*</sub>  **[NucleicAcidEntity](NucleicAcidEntity.md)**

## Attributes


### Inherited from chemical entity:

 * [trade name](trade_name.md)  <sub>0..1</sub>
     * Range: [ChemicalEntity](ChemicalEntity.md)
 * [available from](available_from.md)  <sub>0..\*</sub>
     * Range: [drug_availability_enum](drug_availability_enum.md)
 * [max tolerated dose](max_tolerated_dose.md)  <sub>0..1</sub>
     * Description: The highest dose of a drug or treatment that does not cause unacceptable side effects. The maximum tolerated dose is determined in clinical trials by testing increasing doses on different groups of people until the highest dose with acceptable side effects is found. Also called MTD.
     * Range: [String](types/String.md)
 * [is toxic](is_toxic.md)  <sub>0..1</sub>
     * Range: [Boolean](types/Boolean.md)

### Inherited from entity:

 * [id](id.md)  <sub>1..1</sub>
     * Description: A unique identifier for an entity. Must be either a CURIE shorthand for a URI or a complete URI
     * Range: [String](types/String.md)
     * in subsets: (translator_minimal)
 * [iri](iri.md)  <sub>0..1</sub>
     * Description: An IRI for an entity. This is determined by the id using expansion rules.
     * Range: [IriType](types/IriType.md)
     * in subsets: (translator_minimal,samples)
 * [category](category.md)  <sub>0..\*</sub>
     * Description: Name of the high level ontology class in which this entity is categorized. Corresponds to the label for the biolink entity type class.
 * In a neo4j database this MAY correspond to the neo4j label tag.
 * In an RDF database it should be a biolink model class URI.
This field is multi-valued. It should include values for ancestors of the biolink class; for example, a protein such as Shh would have category values `biolink:Protein`, `biolink:GeneProduct`, `biolink:MolecularEntity`, ...
In an RDF database, nodes will typically have an rdf:type triples. This can be to the most specific biolink class, or potentially to a class more specific than something in biolink. For example, a sequence feature `f` may have a rdf:type assertion to a SO class such as TF_binding_site, which is more specific than anything in biolink. Here we would have categories {biolink:GenomicEntity, biolink:MolecularEntity, biolink:NamedThing}
     * Range: [CategoryType](types/CategoryType.md)
     * in subsets: (translator_minimal)
 * [type](type.md)  <sub>0..1</sub>
     * Range: [String](types/String.md)
 * [description](description.md)  <sub>0..1</sub>
     * Description: a human-readable description of an entity
     * Range: [NarrativeText](types/NarrativeText.md)
     * in subsets: (translator_minimal)
 * [source](source.md)  <sub>0..1</sub>
     * Description: a lightweight analog to the association class 'has provider' slot, which is the string name, or the authoritative (i.e. database) namespace, designating the origin of the entity to which the slot belongs.
     * Range: [LabelType](types/LabelType.md)
     * in subsets: (translator_minimal)
 * [provided by](provided_by.md)  <sub>0..\*</sub>
     * Description: connects an association to the agent (person, organization or group) that provided it
     * Range: [Agent](Agent.md)
 * [has attribute](has_attribute.md)  <sub>0..\*</sub>
     * Description: connects any entity to an attribute
     * Range: [Attribute](Attribute.md)
     * in subsets: (samples)

### Inherited from genomic entity:

 * [has biological sequence](has_biological_sequence.md)  <sub>0..1</sub>
     * Description: connects a genomic feature to its sequence
     * Range: [BiologicalSequence](types/BiologicalSequence.md)

### Inherited from macromolecular machine mixin:

 * [macromolecular machine mixin➞name](macromolecular_machine_mixin_name.md)  <sub>0..1</sub>
     * Description: genes are typically designated by a short symbol and a full name. We map the symbol to the default display name and use an additional slot for full name
     * Range: [SymbolType](types/SymbolType.md)
     * in subsets: (translator_minimal,samples)

### Inherited from molecular entity:

 * [is metabolite](is_metabolite.md)  <sub>0..1</sub>
     * Description: indicates whether a molecular entity is a metabolite
     * Range: [Boolean](types/Boolean.md)

### Inherited from named thing:

 * [named thing➞category](named_thing_category.md)  <sub>1..\*</sub>
     * Description: Name of the high level ontology class in which this entity is categorized. Corresponds to the label for the biolink entity type class.
 * In a neo4j database this MAY correspond to the neo4j label tag.
 * In an RDF database it should be a biolink model class URI.
This field is multi-valued. It should include values for ancestors of the biolink class; for example, a protein such as Shh would have category values `biolink:Protein`, `biolink:GeneProduct`, `biolink:MolecularEntity`, ...
In an RDF database, nodes will typically have an rdf:type triples. This can be to the most specific biolink class, or potentially to a class more specific than something in biolink. For example, a sequence feature `f` may have a rdf:type assertion to a SO class such as TF_binding_site, which is more specific than anything in biolink. Here we would have categories {biolink:GenomicEntity, biolink:MolecularEntity, biolink:NamedThing}
     * Range: [NamedThing](NamedThing.md)
     * in subsets: (translator_minimal)

### Inherited from thing with taxon:

 * [in taxon](in_taxon.md)  <sub>0..\*</sub>
     * Description: connects an entity to its taxonomic classification. Only certain kinds of entities can be taxonomically classified; see 'thing with taxon'
     * Range: [OrganismTaxon](OrganismTaxon.md)
     * in subsets: (translator_minimal)

## Other properties

|  |  |  |
| --- | --- | --- |
| **Aliases:** | | sequence feature |
|  | | genomic entity |
| **In Subsets:** | | model_organism_database |
|  | | translator_minimal |
| **Exact Mappings:** | | SO:0000110 |
| **Narrow Mappings:** | | STY:T086 |
|  | | STY:T114 |
