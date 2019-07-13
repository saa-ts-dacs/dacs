# 2.4  Date Element

## Purpose and Scope
This element identifies and records the date(s) that pertain to the creation, assembly, accumulation, and/or maintenance and use of the materials being described.  This section describes types of dates and forms of dates.

Commentary:  It may be useful or necessary for archivists to record different types of dates for the materials being described, including

**Date(s) of creation** are the dates that the documents in the unit being described were originally created (e.g., date of writing a letter, drawing a map, or painting a portrait) or the date that an event or image was captured in some material form (e.g., date that a photograph was taken, sound was originally recorded, or a film was shot).  Dates of creation refer only to the activity of creation of individual documents that make up each unit (as opposed to the "creation" of an aggregate such as a series or file).  This is the type of date recorded most often by archivists and manuscript catalogers not describing government or organizational records.

**Date(s) of record-keeping activity** are the dates during which the unit being described was created, assembled, accumulated, and/or maintained and used as a unit in the conduct of affairs by the organization or individual responsible for its provenance. They are distinct from the dates of creation of individual documents.  Although the dates of record-keeping activity may often coincide with the dates of creation, the date types differ in two ways.  First, the date(s) of record-keeping activity refer to the dates of a number of interrelated activities (including, but not limited to, creation and accumulation); and secondly, the activities pertain to the unit as a whole as opposed to individual documents.  Records may be accumulated and used for a current purpose long after they were originally created, for example, where much earlier records are assembled to support an investigation or a legal action.

When dates of creation and dates of record-keeping activity are the same, record only the former.  Dates of record-keeping activity are most often recorded by archivists working with government records, organizational archives, or other materials where it is important to account for functions and activities.

**Date(s) of publication** are recorded if the unit being described is a commercially issued or mass-produced item.  Record this date information (including dates of publishing, distributing, releasing, and issuing of items) according to rules in various chapters of AACR2 or other appropriate standards (see Appendix B).  Dates of publication are most often recorded when describing items.

**Date(s) of broadcast** are dates on which sound recordings or moving image materials were broadcast on radio or television.  Record this date information according to rules in various chapters of AACR2 or other appropriate standards (see Appendix B).  Dates of broadcast are most often recorded when describing items.

## Exclusions
**2.4.1.**  If the material being described is a reproduction, record the details about the reproduction, including the date(s) of reproduction, if known, in the Scope and Content Element (3.1.7).  If the material being described is the original and the repository wishes to provide details about the availability of copies, record that information in the Existence and Location of Copies Element (6.2).

## Sources of Information
**2.4.2.**  Take the information from any reliable source, including the internal evidence of the materials being described.

##General Rules
**2.4.3.**  Record dates of creation, record-keeping activity, publication, or broadcast as appropriate to the materials being described.

**2.4.4.**  Alternatively, if relevant and deemed necessary by the repository and if the descriptive system permits it, record multiple types of dates, labeling each clearly. <sup>[1](#footnote1)</sup>  When recording multiple date types, explain each in the Scope and Content Element (3.1).

**2.4.5.**) Record the year(s) in Western-style Arabic numerals.  If the date found in or on the unit being described is not of the Gregorian or Julian calendar, <sup>[2](#footnote2)</sup> record the date as found and follow it with the year(s) of the Gregorian or Julian calendar in parentheses. Specify the name of the calendar, such as Republican, Jewish, Chinese, in a note (see 7.1.2)
```
2628 (1968)
Note:  Dated in accordance with the Chinese calendar.

an 14 (i.e., 1805)
Note:  Dated in accordance with the French Republican calendar.
```

**2.4.6.**  Record the date(s) of the unit being described either as a range of dates or as a single date.

## Date Ranges
### Inclusive dates
**2.4.7.**  If the materials comprising or the record-keeping activity relating to the unit being described span a period of time, always record the inclusive dates, that is, the earliest and latest dates of the materials or activity in question.

`1849-1851`

**2.4.8.**  When further accruals are expected, record the inclusive dates pertaining to the holdings currently in the custody of the repository.  Record information about expected accruals in the Accruals Element (5.4).  When the accruals are received, revise the date information accordingly.
```
1979-1993
not 1979-
not 1979-(ongoing)
```

**2.4.9.**  The date(s) of a unit being described must fall within the range of dates of the unit of which it forms a part.  This rule applies to both dates of creation and dates of record-keeping activity.

```
1934-1985
Dates of record-keeping activity for a body of corporate records.

1945-1960
Dates of record-keeping activity for a series within the above.

1950-1955
Dates of record-keeping activity for a file within the above.

```

### Predominant or bulk dates
**2.4.10.**  Optionally, where the dates pertaining to the majority of the documents in the unit being described differ significantly from the inclusive dates, provide predominant or bulk dates. Specify them as such, preceded by the word “predominant” or “bulk.”  Never provide predominant or bulk dates without also providing inclusive dates.
```
1785-1960, bulk 1916-1958

1942-1998, predominant 1975-1991
```

**2.4.11.**  Optionally, if there is a significant gap in the chronological sequence of the documents in the unit being described, where providing predominant/bulk dates would be misleading, record the anomalous date(s) separated by commas. <sup>[3](#footnote3)</sup>  Explain significant chronological gaps in the materials in the Scope and Content Element (3.1).
```
1827, 1952-1978

1975, 2002
```

### Estimated date ranges
**2.4.12.**  At all levels of description, where the earliest or latest dates pertaining to the unit being described are estimates, indicate the estimated dates in a clear and consistent fashion. <sup>[4](#footnote4)</sup>
```
approximately 1952-1978

circa 1870-1879
```

### Single dates
**2.4.13.**  If the materials fall within a single year, record that date or a more specific date therein.
```
1975

1975 March-August
```

### Exact single dates
**2.4.14.**  For descriptions of a single item, record exact dates in a consistent and unambiguous fashion, preferably expressed as year-month-day. <sup>[5](#footnote5)</sup>

`1906 March 17`

### Estimated single dates
**2.4.15.**  If no date can be found on or in the material itself or determined from any other source, estimate the nearest year, decade, century or other interval as precisely as possible. Record estimated dates in a consistent fashion.
```
probably 1867

approximately 1925

before 1867

after 1867 January 5

1892 or 1893

1890s

circa August 1975
```

### No dates
**2.4.16.**  When recording date(s) for files and items, if the unit being described bears no date and the institution does not wish to or it may be misleading to record an estimated date, use "undated."  Do not use the abbreviations “n.d.” or “s.d.”

## Examples of Encoding for 2.4 Date Element

Encoding at any level of description in EAD.  Dates that a repository wishes to be computer searchable should be normalized according to ISO 8601 Representation of Dates and Times.
```
<unitdate normal="1975">1975</unitdate>

<unitdate type="inclusive" normal="1849/1851">1849-1851</unitdate>

<unitdate normal="19060317">1906 March 17</unitdate>

<unitdate type="inclusive" normal="1785/1960">1785-1960</unitdate>
<unitdate type="bulk" normal="1916/1958">bulk 1916-1958</unitdate>

<unitdate type="inclusive" normal="1870/1879">circa 1870-1879</unitdate>

<unitdate normal="1892/1893">1892 or 1893</unitdate>

<unitdate type="inclusive" normal="1862/1969" label="Dates of Creation">1862-1969</unitdate>
<unitdate type="inclusive" normal="1957-1969" label="Dates of Record-keeping Activity">1957-1969</unitdate>
```

Encoding at the highest level of description in MARC 21:
```

245    00    ‡a Project Ngoc records, ‡f 1978-1998.

245    10    ‡a Henry David Thoreau letter and engraving, ‡f 1847.

245    10    ‡a Willis H. Warner papers, ‡f 1884-1964, ‡g bulk 1920-1963.

245    10    ‡a United Farm Workers Information Fair collection, ‡f circa 1968-1972.

245    00    ‡a David Douglas Duncan photographs
260    bb    ‡c 1935-2004
```

* * *
<a name="footnote1">[1]</a>: Most MARC-based systems will allow only one date type and the repository’s ability to label dates will be very limited.  EAD and other systems are more flexible in this area.

<a name="footnote2">[2]</a>: Direction for converting dates after 1582 from the Julian calendar to the Gregorian calendar is provided in AACR2 rule 22.17A n. 16.

<a name="footnote3">[3]</a>: Repositories are encouraged to establish consistent policies and procedures regarding the maximum number of anomalous dates to record.

<a name="footnote4">[4]</a>: It is recommended, though not required, that terms reflecting estimation be spelled out rather than abbreviated, as abbreviations may not be understood by all users.

<a name="footnote5">[5]</a>: Expression of dates as all numerals is discouraged due to the differing conventions in the order of information.

