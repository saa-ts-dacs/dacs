# Changelog

## Versioning System

The versioning system for DACS borrows from standard practices in software versioning. It combines two common forms of software versioning: semantic versioning and chronological versioning.

Each version of DACS is written as **DACS** followed by a series of numbers, for instance **DACS 2019.0.2**. The numbers are incremented in accordance to the type of change being made. Changes can be classified as **major, minor, or bug fixes.**

The first number represents **the year of a major update** to DACS. SAA defines a major change as one that changes the application or interpretation of the standard so much as to make previously compliant use of the standard suddenly non-compliant. Examples may include:

* Adding a new element (required or optional)
* Making significant alterations to how an element is used (going from required to optional or
optional to required) or how an element is defined to the point it would impact practical use
* Would the change make the answer to the question “Does this change how people
use/educate/write about it?” be “yes?”
* Creating a new appendix
* Significant revision to preambles, principles, appendices

The second number also represents a **major change**, in the event of two major changes in the same calendar year. In most cases, this number will remain zero.

The third number represents a **minor change**. SAA defines a minor change as one that does not affect the application or interpretation of the standard and would not result in a user’s current application of the standard being non-compliant. Examples may include:
* Updating links in an appendix or standard
* Updating crosswalks based on changes to adjacent/companion standards
* Making suggestions for use/providing use case examples
* Changes made to file structure on GitHub

The fourth number represents a **"bug" fix**. Examples of this include:
* Correcting a typo
* Correcting a grammatical error
* Correcting an error in Markdown

In other words, the structure of DACS version naming is **DACS Year.Major.Minor.Bug**

To learn more about semantic versioning, visit https://semver.org/

In order to view the files that correspond to each version, go to the [Releases page](https://github.com/saa-ts-dacs/dacs/releases) and click on the tag-shaped icon on the left-hand side of the version you would like to view. The version numbers on the releases page match what is found in the changelog, but may not be in the same order.

## What is a changelog?

A changelog is a form of documentation traditionally used in versioned software. It keeps a chronological record of all of the changes made in each version of a project. Below, you will find short descriptions of each change that was made to DACS, deliniated by a unique version number. The oldest changes are at the bottom of the document, the most recent changes are at the top.

The changelog is to be updated with each new subsequent change made to DACS and given a new version number and release.

## DACS Versions

### DACS 2022.0.3.2
* Fix formatting error caused by extraneous space character.
  
### DACS 2022.0.3.1
* Updates example in DACS 6.2.3

### DACS 2022.0.2.1
* Replaces examples containing descriptions of violent acts 
* Harmonizes language between parts I and II
* Fixes a markup bug in Appendix C

### DACS 2022.0.1.1
Bug fix release to fix broken link on Levels of Description page and the Revision flowchart rendering.

### DACS 2022.0.1

Replaced example in 3.1.5.

### DACS 2022

Major change to allow "not before" or "not after" dates in 11.1 Dates of Existence.

### DACS 2021.0.0.2

Bug fix to correct minor ommissions related to the addition of the new rights statement element.

### DACS 2021.0.0.1

Bug fix release to add Rights Statements for Archival Description element to chapter contents pages.

### DACS 2021

Added new required Rights Statements for Archival Description element. Repositories should use this element to declare the conditions under which they are making the archival description itself available for use and reuse..

### DACS 2019.0.4.1

Corrected a broken URL link in Chapter 11.

### DACS 2019.0.4

Restructure chapters 10-14 in Part II so that examples are separated into their own files rather than added to the last rule of each chapter.

### DACS 2019.0.3.1

Corrects errors in encoding for crosswalk tables formatting.

### DACS 2019.0.3

* Introduces the new DACS website.
* Fixes to filenames of appendices.
* Adds bullets and links to chapter title appendices for better structure and formatting in the web version of DACS.

### DACS 2019.0.2

* Introduces new versioning system to DACS.
* Introduces the changelog.

### DACS 2019.0.1

* Files have been renamed so they will order correctly when using the bash find to cat commands. This makes it one command to combine all the markdown, and a second to reformat in html, pdf, etc.
* Adds tables of contents with relative links at the top, and for each chapter based on the 2nd edition PDF.

### DACS 2019

This update changes the Preface and the Statement of Principles in order to better align both with current archival theory and practice as well as the International Council on Archives (ICA) draft data model for archival description, Records in Contexts (RiC).2 The preface revision is not hugely substantive but rather a reorganization and update of existing information. The revision to the Statement of Principles is total.

There are two primary and equally important justifications for the revisions. First, the revision is proposed following a deep analysis of the current Statement of Principles (hereafter referred to as current principles) and the extent to which it represents archival values, theory and practice, and is teachable and clear. Second is the release of Records in Contexts and the desire by the technical subcommittee to bring DACS in better alignment with its underlying concepts and structure and, in turn, current archival theory that undergirds RiC.

### DACS 2015.0.2.1

Minor corrections to Appendix B.

### DACS 2015.0.2

Complete overhaul and update of appendix:

* New standards added, superseded ones removed.
* Links added to existing citations.
* Full bibliographic citations from modern (i.e. online) standards removed.
* Version details removed, as they change frequently.
* Categories, subcategories, and standards alphabetized.

### DACS 2015.0.1.2

Updated text to remove reference to Part III, which was eliminated during the DACS revision in 2013.

### DACS 2015.0.1.1

Authorized by 2016 change request to remove mention of the DACS companion website since TS-DACS decided to focus on educational offerings rather than creating the website. A few references to the website were missed at that time. Deleted a reference to the website in the Digital Records section and changed the entry about Appendix D in the What's New in DACS table.

### DACS 2015.0.1

Removes reference of companion website from Preface.

### DACS 2015.0.0.2

Adds missing chapter title to Chapter 14.

### DACS 2015.0.0.1

Migration of DACS to GitHub.

### DACS 2015

The revisions are as follows:

* Commentary bullet 2 in 2.3.3 was changed to “When the repository is responsible for assembling a collection, provide, as part of the devised title, the institution’s name as the collector.” The revision changed “do not provide” to “provide” creating an affirmative burden for institution’s to identify themselves as the collector when they are responsible for the creation of a collection.

* 2.3.6 was changed to ““If the name of the creator, assembler, or collector is not known, do not record a name. In such cases, devise the nature of the archival materials for the title as instructed in rules 2.3.18-2.3.20 and 2.3.22.” This revision removed the phrase “or if the repository has assembled the materials” from the rule.


### DACS 2013

Major update to DACS. For full information on changes made and the process with which these changes were made, see https://drive.google.com/file/d/0Bz6WyYWOjAasUTFvYjNuMk42Ri1OTjFrbkxyck9iRC1kdXdB/view

Changes include:

* Major structural changes
* Removal of Part III
* Clarifications and corrections as suggested by feedback

### DACS 2004.0.2

This version of DACS includes an index, which was previously not a feature of the document.

### DACS 2004.0.1

This update of DACS adds an endorsement by the SAA.

### DACS 2004

This is the original version of DACS, first released in 2004.
