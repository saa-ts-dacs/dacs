# Overview of Archival Description

The principal objective of archival description is the creation of access tools that assist users in discovering desired records. The nature of archival materials, their distribution across many institutions, and the physical requirements of archival repositories necessitate the creation of these descriptive surrogates, which can then be consulted in lieu of directly browsing through quantities of original documents. The archivist must consult other standards and protocols in addition to DACS to construct a robust system of access. This section describes the roles of those standards and protocols and that of DACS within the larger context of the creation of archival descriptions.

## Access Tools

DACS is a standard that is independent of particular forms of output in given information systems, such as manual and electronic catalogs, databases, and other finding aid formats. However, archivists recognize that these rules do not exist as abstractions but will be implemented in actual systems. In practice, DACS will be used principally with the two most commonly employed forms of access tools, catalogs and inventories, though it may be useful in the construction of guides and calendars as well. Archivists must recognize that the systems in which these descriptions appear have functionality and requirements that extend beyond simply presenting the descriptions of archival materials based on Part I and information about the creators of archival records created according to the rules in Part II.

When descriptive information is managed in a locally developed database or presented as entries in a card catalog or as a typescript inventory, local decisions must be made about database design and presentation or the layout of data on the card or printed inventory. When descriptions are recorded in a standard electronic format—MARC 21, EAD, or both—an archivist will have to master the encoding scheme in which the data is stored electronically. Various publications are instructive in the application of these two standards, while the official documentation for each is available in print and online and is cited in Appendix B.<sup>1</sup>

Beyond the details of their respective encoding protocols, both MARC 21 and EAD require the inclusion of data that supplements the information specified in DACS. MARC 21 includes a series of fields of coded information that assist in machine processing of data, such as the dates of the material. The structure of and permissible values for these codes may be found in the MARC 21 documentation. In EAD, the EAD Header element contains information about the electronic file. Its formulation is described in the _Encoded Archival Description Tag Library_.

## Access Points

Then there is the matter of "access points." While archival description is narrative, and electronic catalogs and databases typically provide full-text searching of every word in the text, information systems often also identify specific terms, codes, concepts, and names for which specialized indexes are created to permit faster and more precise searching. In a manual environment, these terms appear as entry headings on catalog records. A variety of protocols, both standardized and local, determine which of the names and terms in a description become "access points" for searching in this way, as well as the form in which they appear. For example, Element 3.1 of DACS instructs the archivist to include in the scope and content element information about the "subject matter to which the records pertain, such as topics, events, people, and organizations." The natural language terminology used to describe such a topic in the scope and content statement must be subsequently translated into the formal syntax of a subject heading, as specified by a standardized thesaurus like the _Library of Congress Authorities_.<sup>2</sup> For example, a collection might contain information about railroads in Montana. After consulting the Library of Congress subject headings and reviewing the directions in the _Subject Cataloging Manual: Subject Headings_ on the formulation of compound subject terms, the archivist will establish the access point as Railroads—Montana. When embedded in a MARC 21 record, the coding will be

    650 b0 ‡a Railroads ‡z Montana

If this data is placed in an EAD finding aid, the resulting encoding will look like this:

    <controlaccess>
      <subject source="lcsh">Railroads--Montana</subject>
    </controlaccess>

Once rendered in a consistent form and included in electronic indexes or as headings in a card file, such standardized data become a powerful tool for researchers to discover materials related to that topic.

It is a local decision as to which names, terms, and concepts found in a description will be included as formal access points, but repositories should provide them in all types of descriptions. Such indexing becomes increasingly important as archivists make encoded finding aids and digital content available to end users through a variety of repository-based and consortial online resource discovery tools.

Access points fall into six broad categories:

*   Names
*   Places
*   Subjects
*   Documentary forms
*   Occupations
*   Functions

Each category is described below and contains a discussion of the parts of the descriptive record in which the concepts that are rendered as access points may be found. The standard format of such terms can be developed locally but preferably will be taken from standard thesauri such as those in Appendix B.

### Names

The names of persons, families, and organizations that are associated with a body of archival materials, either as the creator or the subject of the records, constitute an important pathway by which researchers discover relevant materials. Names that are rendered as _nominal access points_ can be found in several areas of the descriptive record:

*   Name of Creator(s) Element (2.6)
*   Title Element (2.3)
*   Scope and Content Element (3.1)
*   Administrative/Biographical History Element (2.7)
*   Custodial History Element (5.1)
*   Immediate Source of Acquisition Element (5.2)

At a minimum, an access point should be made for every name included in the Name of Creator(s) Element in a single-level description or at the highest level in a multilevel description. Names found in other descriptive elements may be utilized as access points in accordance with local or consortial practice.

### Places

The names of places and geographic features to which the records pertain may be important to researchers. Geographic place-names that should be considered for use as access points may be found in the following parts of the descriptive record:

*   Name of Creator(s) Element (2.6)
*   Title Element (2.3)
*   Scope and Content Element (3.1)
*   Administrative/Biographical History Element (2.7)

### Topical Subjects

The topical subject matter to which the records pertain is among the most important aspects of the archival materials. Terms suggesting topics that might be employed as access points may be found in the following areas of the descriptive record:

*   Title Element (2.3)
*   Scope and Content Element (3.1)
*   Administrative/Biographical History Element (2.7)

A variety of general and specialized subject thesauri, including the _Library of Congress Authorities,_ may be employed as the source for standardized terminology. The most commonly used of these are listed in Appendix B.

### Documentary Forms

Terms that indicate the documentary form(s) or intellectual characteristics of the records being described (e.g., minutes, diaries, reports, watercolors, or documentaries) provide the user with an indication of the content of the materials based on an understanding of the common properties of particular document types. For example, one can deduce the contents of ledgers because they are a standard form of accounting record, one that typically contains certain types of data. Documentary forms are most often noted in the following areas of the descriptive record:

*   Title Element (2.3)
*   Extent Element (2.5)
*   Scope and Content Element (3.1)

The _Art & Architecture Thesaurus_, the _Library of Congress Authorities_, or appropriate media-specific thesauri should be the first sources consulted for terms denoting documentary forms and literary genres.

### Occupations

The occupations, avocations, or other life interests of individuals that are documented in a body of archival material may be of significance to users. Such information is most often mentioned in the following areas of the descriptive record:

*   Scope and Content Element (3.1)
*   Administrative/Biographical History Element (2.7)

Again, the _Library of Congress Authorities_ is a widely used source of terms noting occupations and avocations. The U.S. Department of Labor's _Dictionary of Occupational Titles_ provides a structured enumeration of job titles.

### Functions and Activities

Terms indicating the function(s), activity(ies), transaction(s), and process(es) that generated the material being described help to define the context in which records were created. Examples of such concepts might be the regulation of hunting and fishing or the conservation of natural resources. Functions and activities are often noted in these areas of the descriptive record:

*   Title Element (2.3)
*   Scope and Content Element (3.1)
*   Administrative/Biographical History Element (2.7)

The _Art & Architecture Thesaurus_ contains a hierarchy of terms denoting functions. The _Library of Congress Authorities_ also may be employed.

* * *

[1] See Library of Congress, Network Development and MARC Standards Office, _MARC 21 Format for Bibliographic Data_ (Washington, DC: Library of Congress, 1999), http://www.loc.gov/marc/bibliographic/, and _Encoded Archival Description Tag Library—Version 2002_, prepared and maintained by the Encoded Archival Description Working Group of the Society of American Archivists and the Network Development and MARC Standards Office of the Library of Congress (Chicago, IL: Society of American Archivists, 2002).

[2] The _Library of Congress Authorities_ online resource (http://http://authorities.loc.gov) combines the _Library of Congress Name Authority File_ (LCNAF) and the _Library of Congress Subject Headings_ (LCSH).

