#Describing Archives: A Content Standard Workshop Series
##Video 13: Relationships between Authorities and Archival Materials
##July 2016
<br/>


**Slide 1: Introduction**

Hello, my name is Katrina Windon and I am a Photograph Archivist at the University of Nevada, Reno. Welcome to the thirteenth video in the Society of American Archivists instructional video series on Describing Archives: A Content Standard.

For those of you in the SAA’s Arrangement and Description Program, this tutorial is part of the required course on Describing Archives: A Content Standard. More information about the certificate program and requirements may be found at archivists.org.

 

In this video we will be going over the relationships between authorities and archival materials. Once this video is over, you should understand how to use authority records to standardize aspects of archival description and make certain collections metadata more easily harvested and shared. This video is free and available to anyone who wants to learn more about DACS, but if you sign up to take the DACS workshop for credit, you will be responsible for understanding this content, and there will be a quiz to test your understanding.

**Slide 2: Archival Content Standards**

As both DACS and ISAAR(CPF) note, authority records are vital tools for documenting the context of an archival record’s creation, but they’re most effective when they’re associated with the relevant archival materials, and with each other.

Why use authority records—and why use others’ authority records, whenever possible? It reduces duplication of labor, and increases the opportunity for interoperability across consortiums and content aggregators like SNAC and ArchiveGrid.

**Slide 3: Creating Connections Between Connections**

A stand-alone archival record is like a stub of a Wikipedia entry; but once its linked to archival records and related authority records, it becomes part of a larger story, one that can be shared amongst repositories through tools like the Social Networks and Archival Context (or SNAC) project.

**Slide 4: Entity Relationship Types**

Archival records can be created and influenced by a wide variety of people, organizations, and other agents. The exact nature of an entity’s relationship to a record may vary, and for a researcher it’s important to know whether the entity *created* the record, is *related* to the record, *translated* the record, or something else entirely. In order to ensure consistency in this area of archival description, several content standards and controlled vocabularies exist, some within larger standards and ontologies.

ISAAR(CPF), which DACS complies with and EAC-CPF supports, provides a framework for the description of the relationships between authorities and archival resources, and between authorities themselves.

ISAAR(CPF) entity relationship types may be described using an existing standard or by using one of four provided categories: Hierarchical, Temporal, Family, or Associative. These standardized categories can then be expounded upon in free-form description. *DACS* suggests using the same standardized categories developed by ISAAR(CPF) or using another vocabulary or standard, which should then be specified. DACS also offers narrative descriptions.

**Slide 5: Describing the Entity-Record Relationship**

DACS doesn’t prescribe any one vocabulary or standard for relator terms, but there are many options. For entity-record relationship description, the MARC Code List for Relators is one of the most commonly used, and has been endorsed by the Dublin Core Metadata Initiative (or DCMI).

Another possible vocabulary source is SCoRO, the Scholarly Contributions and Roles Ontology, which was designed for authors and publishers and could be a good fit for archivists working with institutional repositories. Other ontologies exist for other specialized data types, like the Agents facet of the Art and Architecture Thesaurus, which is the authority for the Creator Role element of the Categories for the Description of Works of Art standard, and is useful for art objects and museum collections.

These vocabularies may not always seem to be an exact fit for your collection needs—but DACS allows for narrative description to supplement controlled vocabulary terms where needed, and since most of the existing ontologies were designed to be as flexible as possible, this should meet most repository needs.

**Slide 6: Encoding the Entity-Record Relationship**

Once you have a completed authority record (or have found an existing authority record via the Library of Congress Name Authority, the Union List of Artist Names, or some name authority and you’ve selected a controlled vocabulary to describe the record relationships, it’s just a matter of linking the authority record to an archival record or to a related local authority record. Where this information is entered will depend on the metadata standard which you’re following.

In EAC-CPF, a related entity can be described within a &lt;cpfRelation&gt; tag; a related resource expressed within a &lt;resourceRelation&gt; tag; or a related function within a &lt;functionRelation&gt; tag.

In an EAD record, information about the entity-record relationship is expressed in the &lt;origination&gt; tag, within which the label element can be used to express the general category (such as “Creator”) and the role element to express a more specific relator type (such as “Photographer”).

In Dublin Core metadata, entity-record relator information typically goes within the contributor element, and is further refined if necessary by using MARC relator terms; some institutions however may instead use the creator element for this purpose.

However, as DACS notes, these connections can even be expressed in print-based authority files, though that considerably limits the interoperability and usability of the records.

**Slide 7: Thanks for Listening**

When implemented following professional standards, linking between authority records, archival records, and other resources can both provide a fuller context about the records’ creation and create a multitude of new access points to records—enhancing both discovery and understanding.

Thanks for listening, and be sure to check out the rest of the videos in the Society of American Archivists series on DACS to become an archival description pro!
