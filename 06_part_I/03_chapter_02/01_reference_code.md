# 2.1  Reference Code Element

## Purpose and Scope
This element provides a unique identifier for the unit being described.  The identifier may consist of three subelements:  a local identifier, a code for the repository, and a code for the country.

Commentary:  This typically alphanumeric identifier frequently serves as a succinct local means of referring to the materials.  When delivering a descriptive record outside of the repository holding the materials, this element should also contain a nationally sanctioned code for the repository and an internationally standardized code for the country in which the repository is located.  Taken together, these three subelements form a unique machine-readable identifier for the materials being described.

  * The local identifier code is a means of gaining access to the description of the materials or to the documents themselves.  Determining the structure and function(s) of a local identifier code are matters of institutional policy.
  * Examples of local identifiers include accession numbers, record group numbers, and call numbers.
  * The repository identifier code is required only for purposes of consortial, national, or international exchange.  The full name of the institution is recorded in the Name and Location of Repository Element (2.2).
  The country identifier code is required only for purposes of consortial, national, or international exchange.

## Sources of Information
**2.1.1.**  The codes for country and repository are taken from national and international code lists.  Repositories should develop a local system that uniquely identifies discrete materials.

## General Rules
**2.1.2.**  Record a reference code that consists of a local identifier, a repository identifier, and a country identifier in accordance with the following rules.

### Local Identifier
**2.1.3.**  At the highest level of a multilevel description or in a single level description, provide a unique identifier for the materials being described in accordance with the institution’s administrative control system.  Optionally, supply unique identifiers at lower levels of a multilevel description.

```
95-24
Records collection identifier, Gay, Lesbian, Bisexual, Transgender Historical Society

MC22
Personal papers collection identifier, Scripps Institute of Oceanography Archives

632
Manuscript group identifier, Manuscripts and Archives, Yale University Library

79-GC-2-134
Record group, series, album, and item identifier, National Archives and Records Administration
```

### Repository Identifier
**2.1.4.**  Provide a repository code assigned by the national organization responsible for assigning and maintaining repository identifiers<sup>[1](#footnote1)</sup>.

```
CUI
  Repository code for the University of California, Irvine Libraries

TxU-Hu
  Repository code for the Harry Ransom Humanities Research Center, The University of Texas at Austin
```
### Country Identifier
**2.1.5.**  Provide a country code for the location of the repository as assigned by the International Standards Organization<sup>[2](#footnote2)</sup>.
```
US
  Code for the United States

Ca
  Code for Canada
```
* * *

<a name="footnote1">[1]</a>: The Library of Congress is responsible for assigning repository codes and maintaining the list of assigned codes in the United States. National repository codes are constructed in accordance with the latest version of ISO 15511 (International standard identifier for libraries and related organizations).

<a name="footnote2">[2]</a>: The two-character country code is found in the latest version of ISO 3166-1 (Codes for the representation of names of countries and their subdivisions).  While EAD requires the use of the ISO
3166-1 standard for names of countries, the MARC 21 standard has not yet adopted this code list.  Use the code appropriate to the output system for a given description.  The MARC Code List for Countries is used in archival cataloging (e.g., mixed materials) to indicate the country of the repository in the 008 field.
