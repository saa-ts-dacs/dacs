# 2.5  Extent Element

## Purpose and Scope
This element indicates the extent and the physical nature of the materials being described.  This is handled in two parts, a number (quantity) and an expression of the extent or material type.  The second part of the extent element may be either:

* the physical extent of the materials expressed either as the items, containers or carriers, or storage space occupied; or
* an enumeration of the material type(s), usually physical material type(s), to which the unit being described belongs.   Material types may be general or specific.

Repositories should establish a consistent method of articulating statements of extent.

If the description of particular media or individual items requires more detail, such as other physical characteristics or dimensions, see the specific chapters in AACR2 or the medium-specific rules indicated in the Introduction to Part I and Appendix B.

If the material type has been provided in the title statement, do not repeat it in the statement of extent.

Commentary:  It is important to include information about the quantity and physical nature of the materials for several reasons.  It enables users to eliminate material that is irrelevant to their needs; for example, a user may want only the material containing photographs.  It also enables users to plan their research:  knowing the quantity is important because it takes longer to go through 30 boxes or 20 hours of sound recordings than it does to go through one box or five hours.  The amount of detail provided at any level of description is a matter of institutional policy, depending on user needs and available resources.   At lower levels in a multilevel description, extent may be expressed as an enumeration of boxes or folders rather than as a narrative extent statement.

Further details about quantity and physical characteristics may also be provided in the Scope and Content Element (3.1).

## Exclusions
**2.5.1.**  Record information about physical characteristics that affect the use of the unit being described in the Physical Access Element (4.2).

## Sources of Information
**2.5.2.**  Derive the information from the materials themselves or take it from transfer documents.

## General Rules
**2.5.3.**  Record the numerical quantity associated with each expression of physical extent, containers or carriers, number of items, or material type, using the imperial system of measurement in Arabic numerals, unless the repository has made a decision to use the metric system.

**2.5.4.**  Record the quantity of the material in terms of its physical extent as linear or cubic feet, number of items, or number of containers or carriers.<sup>[1](#footnote1)</sup>
```
45 linear feet

5,321 items

16 boxes

2 film reels

15 folders

Box 10    Folder 6
```

**2.5.5.**  Optionally, record the quantity in terms of material type(s).  Material types may be general, such as textual materials,<sup>[2](#footnote2)</sup> graphic materials, cartographic materials, architectural and technical drawings, moving images, and sound recordings, or more specific types such as those found in AACR2 and various thesauri.<sup>[3](#footnote3)</sup>
```
10 boxes of textual materials

1,000 photographs

50 technical drawings

800 maps

12 audio cassettes
```

**2.5.6.**  Optionally, qualify the statement of physical extent to highlight the existence of material types that are important.
```
45 linear feet, including 200 photographs and 16 maps

3 boxes, including photographs and audio cassettes
```

## Multiple Statements of Extent
**2.5.7.**  If a parallel expression of extent is required or desirable, add this information in parentheses.
```
2,400 photographs (12 linear feet)

89.3 linear feet (150 boxes and 109 oversize folders)

71 maps (3.5 cubic feet)

1 diary (352 pages)

2.5.8.  Optionally, provide multiple statements of extent to highlight the existence of material types that are important.

12 linear feet of textual materials, 68 photographs, 16 architectural drawings
```

## Approximate Statements of Extent
**2.5.9.**  If parts of the material being described are numerous and the exact number cannot be readily ascertained, record an approximate number and indicate that it is an estimate.
```
approximately 35 linear feet

about 24,000 maps

circa 11,000 photographs
```

## Examples of Encoding for 2.5 Extent Element

Encoding at any level of description in EAD:
```
<physdesc><extent>45 linear feet</extent></physdesc>

<physdesc><extent>50 technical drawings</extent></physdesc>

<physdesc><extent>3 boxes, including photographs and audio cassettes</extent></physdesc>

<physdesc><extent>89.3 linear feet (150 boxes and 109 oversize folders)</extent></physdesc>

<physdesc><extent>12 linear feet of textual materials</extent>, <extent>68 photographic prints</extent>, <extent>16 architectural drawings</extent></physdesc>

<container type=”Box”>10</container>
<container type=”Folder”>6</container>
```

Encoding at the highest level of description in MARC 21:
```
300    bb    ‡a 45 ‡f linear feet

300    bb    ‡a 3 ‡f boxes, ‡b including photographs and audio cassettes

300    bb    ‡a 89.3 ‡f linear feet (150 boxes and 109 oversize folders)

300    bb    ‡a 12 ‡f linear feet of textual materials

300    bb    ‡a 68 ‡f photographs

300    bb    ‡a 33,000 ‡f items (69.0 linear feet)

```

* * *
<a name="footnote1">[1]</a>: It is recommended, though not required, that terms reflecting physical extent be spelled out rather than abbreviated, as abbreviations may not be understood by all users.
<a name="footnote2">[2]</a>: It is usually assumed that archival materials are generally textual in nature, so it may not be necessary to supply the term “textual materials” unless it is desirable to distinguish from other material types.
<a name="footnote3">[3]</a>: See especially Art and Architecture Thesaurus, Thesaurus for Graphic Material, and Library of Congress Authorities  (full citations provided in Appendix B).

