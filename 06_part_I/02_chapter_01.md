### Chapter 1 

# Levels of Description

Archival material can be described at many different levels.

A finding aid may consist of only one level of description (single-level descriptions), or it may include many different levels of description (multilevel descriptions). A finding aid that consists of multiple levels of description may provide information at successively narrower levels of arrangement (such as subseries, files, and even items) for some series while confining information to a single level of hierarchy for others.<sup>[1](#myfootnote1)</sup>

DACS does not attempt to define the proper level of description for any set of archival materials. Archivists should follow the prescriptions of their institutions and apply their own judgment in making such determinations.

DACS defines twenty-five elements that are useful in creating systems for describing archival materials. These systems can be of any type, ranging from simple paper-based files to complex digital information management systems. The output products of these systems—archival descriptions of all kinds and formats, printed on paper or encoded in EAD or MARC 21—must include at minimum a set of discrete descriptive elements that convey standardized information about the archival materials and creators being described. These DACS elements constitute a refinement of the twenty-six high-level elements of archival description defined in the General International Standard Archival Description (ISAD[G]).

Not all of the DACS elements are required in every archival description. Combinations of descriptive elements will vary, depending on whether the archivist considers a specific description to be preliminary or complete and whether it describes archival materials at a single level (e.g., collection level or item level) or at multiple levels that have a whole-part relationship.

Simple archival descriptive systems can be constructed using only the twenty-five elements articulated and defined by this standard; however, more detailed archival descriptive and management systems may require a number of additional elements, either defined by companion standards or standardized at the local level to meet the requirements of a specific repository.

The following requirements specify particular elements from Part I of DACS that should be used in output products—from basic collection-level accession records to fully encoded, multilevel finding aids—intended for the use of archivists or researchers in managing and using archival materials. They articulate a "minimum," "optimum," and "added value" usage of the elements defined by DACS but are not intended to preclude use of other descriptive data that a repository deems necessary for its own descriptive systems or products. DACS does not specify the order or arrangement of elements in a particular descriptive output. Some systems or output formats, such as MARC 21 or EAD, provide specific guidance on the ordering of some or all elements. Others, such as a repository's preliminary accession record or a print finding aid, should include DACS elements in a logical and consistent manner determined by the repository's own procedures and standard practices. The requirements that follow are divided into two sections, one for single-level descriptions and one for multilevel descriptions.

## Requirements for Single-level Descriptions

Following are examples of single-level descriptions:

*   A preliminary accession record
*   A MARC 21 record not linked to other MARC 21 records
*   A database record in a repository's collections management database that describes archival materials only at a single level
*   A METS (Metadata Encoding and Transmission Standard)<sup>[2](#myfootnote2)</sup> record for a description of archival materials

Single-level descriptions can describe archival materials at _any level_, from large accumulations commonly referred to by archivists as collections, record groups, fonds, or record series, to single items and any level in between. They can, however, only describe that material at one level.

### Single-level Required

A single-level description with the minimum number of DACS elements includes:

*   Reference Code Element (2.1)
*   Name and Location of Repository Element (2.2)
*   Title Element (2.3)
*   Date Element (2.4)
*   Extent Element (2.5)
*   Name of Creator(s) Element (2.6) _(if known)_
*   Scope and Content Element (3.1)
*   Conditions Governing Access Element (4.1)
*   Languages and Scripts of the Material Element (4.5)
*   Rights Statements for Archival Description (8.2)

### Single-level Optimum

A single-level description with the optimum number of DACS elements has all of the elements included in Single-level Minimum above, plus the following:

*   Administrative/Biographical History Element (2.7)
*   Access points (See Overview of Archival Description)

### Single-level Added Value

A single-level description using DACS elements to provide added value for researchers includes all of the elements in Single-level Optimum above, plus any other relevant elements the repository wishes to include.

## Requirements for Multilevel Descriptions

Following are examples of multilevel descriptions:

*   A preliminary collection inventory or register (regardless of whether presented in print or encoded in EAD or another encoding scheme)
*   A full collection inventory or register (regardless of whether presented in print or encoded in EAD or another encoding scheme)
*   Multiple linked MARC 21 records
*   A database record in a repository's collections management database that describes archival materials at more than one level

Multilevel descriptions can describe archival materials beginning at any level (e.g., collection level, series level) and must include at least one sublevel. Typical multilevel descriptions begin with large accumulations commonly referred to by archivists as collections, record groups, fonds, or record series. ISAD(G) envisions a descriptive framework that recognizes four levels: fonds, series, file, and item; however, DACS elements can be used to describe materials arranged according to this or any other scheme of articulating levels of arrangement of archival materials.

Within systems that communicate archival description to users, it is often the case that descriptive elements may be shared, inherited, or otherwise linked across and between entities. Traditionally, inheritance has been implicitly presented as hierarchy within the idiom of the print finding aid where frontmatter (collection-level descriptive notes, creator elements, conditions governing access and use, repository information, etc.) applies to archival descriptions on subsequent pages. However, in modern networked archival information systems (relational databases, linked data systems, etc.) linkages, relationships, and inheritances can be non-hierarchical. This makes it particularly important for outputs from these systems to clearly explain relationships so that a user understands which records, agents, or activities an archival description governs.

When a multilevel description is created, the information provided at each descriptive aggregate must be relevant to the material being described within that group.<sup>[3](#myfootnote3)</sup> For instance, archivists should provide administrative and biographical information appropriate and specific to the records being described within that aggregation. Information that is common to component parts should be provided where most generally appropriate and should not be repeated within component parts unless doing so would provide clarity. 

### Multilevel Required

The _top_ level of a multilevel description with the minimum number of DACS elements includes:

*   Reference Code Element (2.1)
*   Name and Location of Repository Element (2.2)
*   Title Element (2.3)
*   Date Element (2.4)
*   Extent Element (2.5)
*   Name of Creator(s) Element (2.6) _(if known)_
*   Scope and Content Element (3.1)
    _Note: In a minimum description, this element may simply provide a short abstract of the scope and content of the materials being described._
*   Conditions Governing Access Element (4.1)
*   Languages and Scripts of the Material Element (4.5)
*   Rights Statements for Archival Description (8.2)
*   Identification of the whole-part relationship of the _top_ level to at least the _next subsequent_ level in the multilevel description. This may be done through internal tracking within a particular descriptive system; if so, the output must be able to explicitly identify this relationship.

Each _subsequent_ level of a multilevel description should include:

*   All of the elements used at higher levels, unless the information is the same as that of a higher level or if it is desirable to provide more specific information.

_Notes:_

*   Name of Creator(s) Element (2.6): _At subsequent levels of a multilevel description, this element is required only if the person(s) or organization(s) responsible for the creation or accumulation of the material at the subsequent level differs from the higher level(s). This can also be accomplished by using the Name Segment of the Title Element (2.3)._
*   Scope and Content Element (3.1): _Scope and contents are typically necessary for large units of aggregation and are not required at the file or item level if the Title Element (2.3) is sufficient to describe the material._

*   Identification of the whole-part relationship of _each_ level to at least the _next subsequent_ level in the multilevel description. This may be done through internal tracking within a particular descriptive system or through an explicit statement of the relationship.

### Multilevel Optimum

The _top_ level of a multilevel description with the optimum number of DACS elements includes all of the elements in Multilevel Minimum above, plus the following:

*   Administrative/Biographical History Element (2.7)
*   Scope and Content Element (3.1)
    _Note: In an optimum description, this element should include a full description of the scope and content of the materials being described._
*   Access points (See Overview of Archival Description.)

Each _subsequent_ level of that multilevel description should include:

*   All of the elements included at the higher levels of the multilevel description, unless the information is the same as that of a higher level or if it is desirable to provide more specific information.
*   Identification of the whole-part relationship of _each_ level to at least the _next subsequent_ level in the multilevel description. This may be done through internal tracking within a particular descriptive system or through an explicit statement of the relationship.

### Multilevel Added Value

A multilevel description using DACS elements to provide added value for researchers should include all of the elements in Multilevel Optimum above, plus any other elements the repository wishes to include.

Each _subsequent_ level of that multilevel description should include:

*   All of the elements included at the higher levels of the multilevel description, unless the information is the same as that of a higher level or it is desirable to provide more specific information.
*   Identification of the whole-part relationship of _each_ level to at least the _next subsequent_ level in the multilevel description. This may be done thorugh internal tracking within a particular descriptive system or through an explicit statement of the relationship.

* * *

<a name="myfootnote1">[1]</a>: For more information, refer to International Council on Archives, _ISAD(G): General International Standard Archival Description,_ 2nd ed., adopted by the Committee on Descriptive Standards, Stockholm, Sweden, September 19–22, 1999, accessed February 19, 2013, [https://web.archive.org/web/20170329064327/http://www.icacds.org.uk/eng/ISAD(G).pdf](https://web.archive.org/web/20170329064327/http://www.icacds.org.uk/eng/ISAD(G).pdf).

<a name="myfootnote2">[2]</a>: The METS standard is an XML schema for encoding descriptive, administrative, and structural metadata for objects within a digital library. It is an initiative of the Digital Library Federation and is maintained by the Library of Congress. Information is available at http://www.loc.gov/standards/mets/.

<a name="myfootnote3">[3]</a>:  In the voluminous papers of a prominent family, there may be one letter from George Washington within a small cache of a distant cousin’s correspondence. It would be inaccurate and inappropriate to say that the collection is about George Washington, although an archivist may include this kind of description within the series or file that includes that letter. Similarly, if part of a collection has specific conditions governing access, it is useful to provide an overview of all access restriction types at the collection level but it is also important to provide specific conditions governing access at the more granular level where this information would be relevant.
