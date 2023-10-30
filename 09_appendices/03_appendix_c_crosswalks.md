# Appendix C Crosswalks

## DACS to ISAAR(CPF) to EAC(CPF)

<table border="1">
  <tbody>
    <tr>
      <td><strong>DACS</strong></td>
      <td><strong>ISAAR(CPF)</strong></td>
      <td><strong>EAC-CPF</strong></td>
    </tr>
    <tr>
      <td colspan="3"><em>Chapter 2 Identity Elements</em></td>
    </tr>
    <tr>
      <td>2.6 Name of Creator(s)</td>
      <td>5.1 Identity area</td>
      <td><code>&lt;identity&gt;</code></td>
    </tr>
    <tr>
      <td>2.7 Administrative/ Biographical History</td>
      <td>5.2.2 History</td>
      <td><code>&lt;biogHist&gt;</code></td>
    </tr>
    <tr>
      <td>2.7.13 Names</td>
      <td>5.1.2 Authorized form(s) of name</td>
      <td><code>&lt;nameEntry&gt;</code> or <code>&lt;nameEntryParallel&gt;</code> with <code>&lt;authorizedForm&gt;</code></td>
    </tr>
    <tr>
      <td>2.7.14 Family information</td>
      <td>5.2.7 Internal structure/Genealogy</td>
      <td><code>&lt;structureOrGenealogy&gt;</code></td>
    </tr>
    <tr>
      <td>2.7.15 Dates</td>
      <td>5.2.1 Dates of existence</td>
      <td><code>&lt;existDates&gt;</code></td>
    </tr>
    <tr>
      <td>2.7.16 Place of residence</td>
      <td>5.2.3 Places</td>
      <td><code>&lt;place&gt;</code> or <code>&lt;places&gt;</code></td>
    </tr>
    <tr>
      <td>2.7.17 Education</td>
      <td>5.2.2 History</td>
      <td><code>&lt;biogHist&gt;</code></td>
    </tr>
    <tr>
      <td>2.7.18 Occupation, life, and activities</td>
      <td>5.2.5 Functions, occupations, and activities</td>
      <td><code>&lt;occupation&gt;</code> or <code>&lt;occupations&gt;</code></td>
    </tr>
    <tr>
      <td>2.7.19 Other relationships</td>
      <td>5.2.8 General context</td>
      <td><code>&lt;relations&gt;</code></td>
    </tr>
    <tr>
      <td>2.7.20 Family relationships</td>
      <td>5.2.7 Internal structure/Genealogy</td>
      <td><code>&lt;cpfRelation cpfRelationType="family"&gt;</code></td>
    </tr>
    <tr>
      <td>2.7.21 Other significant information</td>
      <td>5.2.9 Other significant information</td>
      <td><code>&lt;generalContext&gt;</code></td>
    </tr>
    <tr>
    <td>2.7.22–23 Administrative history</td>
      <td>5.2.2 History</td>
      <td><code>&lt;biogHist&gt;</code></td>
    </tr>
    <tr>
      <td>2.7.24 Dates of founding and/or dissolution</td>
      <td>5.2.1 Dates of existence</td>
      <td><code>&lt;existDates&gt;</code></td>
    </tr>
    <tr>
      <td>2.7.25 Geographical areas</td>
      <td>5.2.3 Places</td>
      <td><code>&lt;place&gt;</code> or <code>&lt;places&gt;</code></td>
    </tr>
    <tr>
      <td>2.7.26 Mandate</td>
      <td>5.2.6 Mandates/Sources of authority</td>
      <td><code>&lt;mandate&gt;</code> or <code>&lt;mandates&gt;</code></td>
    </tr>
    <tr>
      <td>2.7.27 Functions</td>
      <td>5.2.5 Functions, occupations, and activities</td>
      <td><code>&lt;function&gt;</code> or <code>&lt;functions&gt;</code>, <code>&lt;occupation&gt;</code> or <code>&lt;occupations&gt;</code></td>
    </tr>
    <tr>
      <td>2.7.28 Administrative structure</td>
      <td>5.2.7 Internal structure/Genealogy</td>
      <td><code>&lt;structureOrGenealogy&gt;</code></td>
    </tr>
    <tr>
      <td>2.7.29 Predecessor and successor bodies</td>
      <td>5.2.2 History</td>
      <td><code>&lt;cpfRelation cpfRelationType="temporal-earlier"&gt;</code> or <code>"temporal-later"</code></td>
    </tr>
    <tr>
      <td>2.7.30 Amalgamations and mergers</td>
      <td>5.2.2 History</td>
      <td><code>&lt;cpfRelation cpfRelationType="[value]"&gt;</code></td>
    </tr>
    <tr>
      <td>2.7.31 Name changes</td>
      <td>5.2.2 History</td>
      <td><code>&lt;cpfRelation cpfRelationType="[value]"&gt;</code></td>
    </tr>
    <tr>
      <td>2.7.32 Names of officers</td>
      <td>5.2.2 History</td>
    </tr>
    <tr>
      <td>2.7.33 Other significant information</td>
      <td>5.2.8 General context</td>
      <td><code>&lt;generalContext&gt;</code></td>
    </tr>
    <tr>
      <td colspan="3"><em>Part II: Chapter 9 Archival Authority Records/Chapter 10 Form of the Name</em></td>
    </tr>
    <tr>
      <td>10.1 Authorized Form of the Name</td>
      <td>5.1.2 Authorized form(s) of name</td>
      <td><code>&lt;nameEntry&gt;</code> or <code>&lt;nameEntryParallel&gt;</code> with <code>&lt;authorizedForm&gt;</code></td>
    </tr>
    <tr>
      <td>10.2 Type of Entity</td>
      <td>5.1.1 Type of entity</td>
      <td><code>&lt;entityType&gt;</code></td>
    </tr>
    <tr>
      <td>10.3 Variant Forms of Names</td>
      <td>5.1.3 Parallel forms of name</td>
      <td><code>&lt;nameEntryParallel&gt;</code></td>
    </tr>
    <tr>
      <td>10.3.2 Standardized form of the name according to other rules</td>
      <td>5.1.4 Standardized forms of name according to other rules</td>
      <td><code>&lt;nameEntry&gt;</code> or <code>&lt;nameEntryParallel&gt;</code> with <code>&lt;authorizedForm&gt;</code></td>
    </tr>
    <tr>
      <td>10.3.3 Other forms of name</td>
      <td>5.1.5 Other forms of name</td>
      <td><code>&lt;nameEntry&gt;</code> or <code>&lt;nameEntryParallel&gt;</code> with <code>&lt;alternativeForm&gt;</code></td>
    </tr>
    <tr>
      <td>10.4 Identifiers for Corporate Bodies</td>
      <td>5.1.6 Identifiers for corporate bodies</td>
      <td><code>&lt;entityID&gt;</code></td>
    </tr>
    <tr>
      <td colspan="3"><em>Chapter 11 Description of the Person, Family, or Corporate Body</em></td>
    </tr>
    <tr>
      <td>11.1 Dates of Existence</td>
      <td>5.2.1 Dates of existence</td>
      <td><code>&lt;existDate&gt;</code></td>
    </tr>
    <tr>
      <td>11.2 Historical Summary</td>
      <td>5.2.2 History</td>
      <td><code>&lt;biogHist&gt;</code></td>
    </tr>
    <tr>
      <td>11.3 Places</td>
      <td>5.2.3 Places</td>
      <td><code>&lt;place&gt;</code> or <code>&lt;places&gt;</code></td>
    </tr>
    <tr>
      <td>11.4 Legal Status</td>
      <td>5.2.4 Legal Status</td>
      <td><code>&lt;legalStatus&gt;</code> or <code>&lt;legalStatuses&gt;</code></td>
    </tr>
    <tr>
      <td>11.5 Functions, Occupations, and Activities</td>
      <td>5.2.5 Functions, occupations, and activities</td>
      <td><code>&lt;function&gt;</code> or <code>&lt;functions&gt;</code>, <code>&lt;occupation&gt;</code> or <code>&lt;occupations&gt;</code></td>
    </tr>
    <tr>
      <td>11.6 Mandates/Source of Authority</td>
      <td>5.2.6 Mandates/Sources of authority</td>
      <td><code>&lt;mandate&gt;</code> or <code>&lt;mandates&gt;</code></td>
    </tr>
    <tr>
      <td>11.7 Internal Structure/Genealogy</td>
      <td>5.2.7 Internal structure/Genealogy</td>
      <td><code>&lt;structureOrGenealogy&gt;</code></td>
    </tr>
    <tr>
      <td colspan="3"><em>Chapter 12 Related Corporate Bodies, Persons, and Families</em></td>
    </tr>
    <tr>
      <td>12.1–12.2 Names/Identifiers of Related Corporate Bodies, Persons, or Families <em>and</em> Type of Related Entity</td>
      <td>5.3.1 Names/identifiers of related corporate bodies, persons or families</td>
      <td><code>&lt;cpfRelation&gt;</code> and <code>&lt;entityType&gt;</code></td>
    </tr>
    <tr>
      <td>12.3 Nature of Relationship</td>
      <td>5.3.2 Category of relationship</td>
      <td><code>&lt;cpfRelation cpfRelationType="[value]"&gt;</code></td>
    </tr>
    <tr>
      <td>12.3 Nature of Relationship</td>
      <td>5.3.3 Description of the relationship</td>
      <td><code>&lt;objectXMLWrap&gt;</code> or <code>&lt;objectBinWrap&gt;</code> or <code>&;t;RelationEntry&gt;</code></td>
    </tr>
    <tr>
      <td>12.4 Dates of the Relationship</td>
      <td>5.3.4 Dates of the relationship</td>
      <td><code>&lt;cpfRelation&gt;/&lt;date&gt;</code> or <code>&lt;dateRange&gt;</code> or <code>&lt;dateSet&gt;</code></td>
    </tr>
    <tr>
      <td colspan="3"><em>Authority Record Management</em></td>
    </tr>
    <tr>
      <td>13.1 Repository Code</td>
      <td>5.4.2 Institution identifiers</td>
      <td><code>&lt;maintenanceAgency/agencyCode</code> and/or <code>agencyName&gt;</code></td>
    </tr>
    <tr>
      <td>13.2 Authority Record Identifier</td>
      <td>5.4.1 Authority record identifier</td>
      <td><code>&lt;recordId&gt;</code></td>
    </tr>
    <tr>
      <td>13.3 Rules or Conventions</td>
      <td>5.4.3 Rules and/or conventions</td>
      <td><code>&lt;conventionDeclaration&gt;</code></td>
    </tr>
    <tr>
      <td>13.4 Status</td>
      <td>5.4.4 Status</td>
      <td><code>&lt;maintenanceStatus&gt;</code></td>
    </tr>
    <tr>
      <td>13.5 Level of Detail</td>
      <td>5.4.5 Level of detail</td>
      <td><code>&lt;localControl&gt;</code></td>
    </tr>
    <tr>
      <td>13.6 Date(s) of Authority Record Creation and Revision</td>
      <td>5.4.6 Dates of creation, revision, or deletion</td>
      <td><code>&lt;maintenanceEvent&gt;/&lt;eventDateTime&gt;</code></td>
    </tr>
    <tr>
      <td>13.7 Languages or Scripts</td>
      <td>5.4.7 Languages and scripts</td>
      <td><code>&lt;languageDeclaration&gt;</code></td>
    </tr>
    <tr>
      <td>13.8 Sources</td>
      <td>5.4.8 Sources</td>
      <td><code>&lt;sources&gt;</code></td>
    </tr>
    <tr>
      <td>13.9 Maintenance Information</td>
      <td>5.4.9 Maintenance notes</td>
      <td><code>&lt;maintenanceEvent&gt;/&lt;maintenanceDescription&gt;</code></td>
    </tr>
    <tr>
      <td colspan="3"><em>Related Archival Materials and Other Resources</em></td>
    </tr>
    <tr>
      <td>14.1 Identifiers and Titles of Related Resources</td>
      <td>6.1 Identifiers and titles of related resources</td>
      <td><code>&lt;objectXMLWrap&gt;</code> or <code>&lt;objectBinWrap&gt;</code> or <code>&lt;relationEntry&gt;</code></td>
    </tr>
    <tr>
      <td>14.2 Types of Related Resources</td>
      <td>6.2 Types of related resources</td>
      <td><code>&lt;resourceRelation xlink:role="[value]"&gt;</code></td>
    </tr>
    <tr>
      <td>14.3 Nature of Relationship to Related Resources</td>
      <td>6.3 Nature of relationships</td>
      <td><code>&lt;resourceRelation resourceRelationType=" [value]"&gt;</code></td>
    </tr>
    <tr>
      <td>14.4 Dates of Related Resources and/or Relationships</td>
      <td>6.4 Dates of related resources and/or relationships</td>
      <td><code>&lt;resourceRelation&gt;/&lt;date&gt;</code> or <code>&lt;dateRange&gt;</code> or <code>&lt;dateSet&gt;</code></td>
    </tr>
  </tbody>
</table>

##  DACS to RDA

<table border="1">
  <tbody>
    <tr>
      <td><strong>DACS</strong></td>
      <td><strong>RDA</strong></td>
    </tr>
    <tr>
      <td colspan="3"><em>Part I</em></td>
    </tr>
    <tr>
      <td>2.1 Reference Code</td>
      <td>2.15 Manifestations; 2.19 Item-level (They have an archival example here.)</td>
    </tr>
    <tr>
      <td>2.2 Name and Location of Repository</td>
      <td>4.1</td>
    </tr>
    <tr>
      <td>2.3 Title</td>
      <td>2.3.2.11.4</td>
    </tr>
    <tr>
      <td>2.4 Date</td>
      <td>2.7.6.7</td>
    </tr>
    <tr>
      <td>2.5 Extent</td>
      <td>3.4.1.11</td>
    </tr>
    <tr>
      <td>2.6 Name of Creator(s)</td>
      <td>19, 20, 21, 22</td>
    </tr>
    <tr>
      <td>2.7 Administrative/Biographical History</td>
      <td>No RDA equivalent</td>
    </tr>
    <tr>
      <td>3.1 Scope and Content</td>
      <td>7.10</td>
    </tr>
    <tr>
      <td>3.2 System of Arrangement</td>
      <td>7.8</td>
    </tr>
    <tr>
      <td>4.1 Conditions Governing Access</td>
      <td>4.4</td>
    </tr>
    <tr>
      <td>4.2 Physical Access</td>
      <td>No RDA equivalent (perhaps 3.21)</td>
    </tr>
    <tr>
      <td>4.3 Technical Access</td>
      <td>3.20</td>
    </tr>
    <tr>
      <td>4.4 Conditions Governing Reproduction and Use</td>
      <td>4.5</td>
    </tr>
    <tr>
      <td>4.5 Languages and Scripts of the Material</td>
      <td>7.12; 7.13</td>
    </tr>
    <tr>
      <td>4.6 Finding Aids</td>
      <td>25.1 (related work)</td>
    </tr>
    <tr>
      <td>5.1 Custodial History</td>
      <td>2.18</td>
    </tr>
    <tr>
      <td>5.2 Immediate Source of Acquisition</td>
      <td>2.19</td>
    </tr>
    <tr>
      <td>5.3 Appraisal, Destruction, and Scheduling Information</td>
      <td>No RDA equivalent</td>
    </tr>
    <tr>
      <td>5.4 Accruals</td>
      <td>No RDA equivalent</td>
    </tr>
    <tr>
      <td>6.1 Existence and Location of Originals</td>
      <td>27.1 (related manifestations)</td>
    </tr>
    <tr>
      <td>6.2 Existence and Location of Copies</td>
      <td>27.1</td>
    </tr>
    <tr>
      <td>6.3 Related Archival Materials</td>
      <td>25.1</td>
    </tr>
    <tr>
      <td>6.4 Publication Note</td>
      <td>25.1 (related work)</td>
    </tr>
    <tr>
      <td>7.1 Notes</td>
      <td>2.21 (manifestations/items)</td>
    </tr>
    <tr>
      <td>8.1 Description Control</td>
      <td>5.7 (work)</td>
    </tr>
    <tr>
      <td colspan="2"><em>Part II</em></td>
    </tr>
    <tr>
      <td>10.1 Authorized Form of the Name</td>
      <td>8.6</td>
    </tr>
    <tr>
      <td>10.2 Type of Entity</td>
      <td>No RDA equivalent</td>
    </tr>
    <tr>
      <td>10.3 Variant Forms of Name</td>
      <td>8.7</td>
    </tr>
    <tr>
      <td>11.1 Dates of Existence</td>
      <td>9.3 (Person); 10.4 (Family); 11.4 (Corporate bodies)</td>
    </tr>
    <tr>
      <td>11.2 Historical Summary</td>
      <td>9.17 (Person); 10.9 (Family); 11.11 (Corporate body)</td>
    </tr>
    <tr>
      <td>11.3 Places</td>
      <td>9.8–9.12 (Person); 10.5 (Family); 11.3 (Corporate body)</td>
    </tr>
    <tr>
      <td>11.4 Legal Status</td>
      <td>11.7</td>
    </tr>
    <tr>
      <td>11.5 Functions, Occupations, and Activities</td>
      <td>9.15–9.16 (Person); 11.10 (Corporate body)</td>
    </tr>
    <tr>
      <td>11.6 Mandates/Sources of Authority</td>
      <td>No RDA equivalent</td>
    </tr>
    <tr>
      <td>11.7 Internal Structure/Genealogy</td>
      <td>10.9 (Family); 11.11 (Corporate body)</td>
    </tr>
    <tr>
      <td>12.1 Names/Identifiers of Related Corporate Bodies, Persons, or Families</td>
      <td>30.1 (Person); 31.1 (Families); 32.1 (Corporate body)</td>
    </tr>
    <tr>
      <td>12.2 Type of Related Entity</td>
      <td>No RDA equivalent</td>
    </tr>
    <tr>
      <td>12.3 Nature of Relationship</td>
      <td>30.2 (Person); 31.2 (Family); 32.2 (Corporate body); Appendix K, Relationship designators</td>
    </tr>
    <tr>
      <td>12.4 Dates of the Relationship</td>
      <td>No RDA equivalent</td>
    </tr>
    <tr>
      <td>13.1 Repository Code</td>
      <td>No RDA equivalent</td>
    </tr>
    <tr>
      <td>13.2 Authority Record Identifier</td>
      <td>No RDA equivalent</td>
    </tr>
    <tr>
      <td>13.3 Rules or Conventions</td>
      <td>No RDA equivalent</td>
    </tr>
    <tr>
      <td>13.4 Status</td>
      <td>8.10</td>
    </tr>
    <tr>
      <td>13.5 Level of Detail</td>
      <td>No RDA equivalent</td>
    </tr>
    <tr>
      <td>13.6 Date(s) of Authority Record Creation and Revision</td>
      <td>No RDA equivalent</td>
    </tr>
    <tr>
      <td>13.7 Languages or Scripts</td>
      <td>8.4</td>
    </tr>
    <tr>
      <td>13.8 Sources</td>
      <td>8.12</td>
    </tr>
    <tr>
      <td>13.9 Maintenance Information</td>
      <td>No RDA equivalent</td>
    </tr>
    <tr>
      <td>14.1 Identifiers and Titles of Related Resources</td>
      <td>No RDA equivalent</td>
    </tr>
    <tr>
      <td>14.2 Types of Related Resources</td>
      <td>No RDA equivalent</td>
    </tr>
    <tr>
      <td>14.3 Nature of Relationship to Related Resources</td>
      <td>Appendix I, Relationship designators</td>
    </tr>
    <tr>
      <td>14.4 Dates of Related Resources and/or Relationships</td>
      <td>No RDA equivalent</td>
    </tr>
  </tbody>
</table>

## ISAD(G) to DACS

<table border="1">
  <tbody>
    <tr>
      <td><strong>ISAD(G)</strong></td>
      <td><strong>DACS</strong></td>
    </tr>
    <tr>
      <td colspan="2"><em>3.1 Identity Statement Area</em></td>
    </tr>
    <tr>
      <td>3.1.1 Reference code(s)</td>
      <td>2.1 Reference Code</td>
    </tr>
    <tr>
      <td>3.1.2 Title</td>
      <td>2.3 Title</td>
    </tr>
    <tr>
      <td>3.1.3 Dates</td>
      <td>2.4 Date</td>
    </tr>
    <tr>
      <td>3.1.4 Level of description</td>
      <td>1 Levels of Description</td>
    </tr>
    <tr>
      <td>3.1.5 Extent and medium of the unit</td>
      <td>2.5 Extent</td>
    </tr>
    <tr>
    <td colspan="2"><em>3.2 Context Area</em></td>
    </tr>
    <tr>
      <td>3.2.1 Name of creator</td>
      <td>2.6, Part II Describing Creators</td>
    </tr>
    <tr>
      <td>3.2.2 Administrative/ Biographical history</td>
      <td>2.7, 11.2 Administrative/Biographical History</td>
    </tr>
    <tr>
      <td>3.2.3 Archival history</td>
      <td>5.1 Custodial History</td>
    </tr>
    <tr>
      <td>3.2.4 Immediate source of acquisition</td>
      <td>5.2 Immediate Source of Acquisition</td>
    </tr>
    <tr>
      <td colspan="2"><em>3.3 Context and Structure Area</em></td>
    </tr>
    <tr>
      <td>3.3.1 Scope and content</td>
      <td>3.1 Scope and content</td>
    </tr>
    <tr>
      <td>3.3.2 Appraisal, destruction and scheduling</td>
      <td>5.3 Appraisal, Destruction, and Scheduling Information</td>
    </tr>
    <tr>
      <td>3.3.3 Accruals</td>
      <td>5.4 Accruals</td>
    </tr>
    <tr>
      <td>3.3.4 System of arrangement</td>
      <td>3.2 System of Arrangement</td>
    </tr>
    <tr>
      <td colspan="2"><em>3.4 Conditions of Access and Use Area</em></td>
    </tr>
    <tr>
      <td>3.4.1 Conditions governing access</td>
      <td>4.1 Conditions Governing Access</td>
    </tr>
    <tr>
      <td>3.4.2 Conditions governing reproduction</td>
      <td>4.4 Conditions Governing Reproduction and Use</td>
    </tr>
    <tr>
      <td>3.4.3 Language/scripts of material</td>
      <td>4.5 Languages and Scripts of the Material</td>
    </tr>
    <tr>
      <td>3.4.4 Physical characteristics and technical requirements</td>
      <td>4.2 Physical Access/4.3 Technical Access</td>
    </tr>
    <tr>
      <td>3.4.5 Finding aids</td>
      <td>4.6 Finding Aids</td>
    </tr>
    <tr>
      <td colspan="2"><em>3.5 Allied Materials Area</em></td>
    </tr>
    <tr>
      <td>3.5.1 Existence and location of originals</td>
      <td>6.1 Existence and Location of Originals</td>
    </tr>
    <tr>
      <td>3.5.2 Existence and location of copies</td>
      <td>6.2 Existence and Location of Copies</td>
    </tr>
    <tr>
      <td>3.5.3 Related units of description</td>
      <td>6.3 Related Archival Materials</td>
    </tr>
    <tr>
      <td>3.5.4 Publication note</td>
      <td>6.4 Publication Note</td>
    </tr>
    <tr>
      <td colspan="2"><em>3.6 Notes Area</em></td>
    </tr>
    <tr>
      <td>3.6.1 Note</td>
      <td>7 Notes</td>
    </tr>
    <tr>
      <td colspan="2"><em>3.7 Description Control Area</em></td>
    </tr>
    <tr>
      <td>3.7.1 Archivist's note</td>
      <td>8.1.5 Archivist and date</td>
    </tr>
    <tr>
      <td>3.7.2 Rules or conventions</td>
      <td>8.1.4 Rules or conventions</td>
    </tr>
    <tr>
      <td>3.7.3 Date(s) of descriptions</td>
      <td>8.1.5 Archivist and date</td>
    </tr>
  </tbody>
</table>

## DACS to EAD 2002, EAD3, and MARC

<table border="1">
  <tbody>
    <tr>
      <td><strong>DACS</strong></td>
      <td><strong>EAD 2002</strong></td>
      <td><strong>EAD3 (draft)</strong></td>
      <td><strong>MARC</strong></td>
    </tr>
    <tr>
      <td><em>1 Level of Description</em></td>
      <td><code>&lt;archdesc&gt;</code> and <code>&lt;c&gt;</code> level attribute</td>
      <td><code>&lt;archdesc&gt;</code> and <code>&lt;c&gt;</code> level attribute</td>
      <td><code>351$c</code></td>
    </tr>
    <tr>
      <td colspan="3"><em>2 Identity Elements</em></td>
    </tr>
    <tr>
      <td>2.1.3 Local identifier</td>
      <td><code>&lt;unitid&gt;</code></td>
      <td><code>&lt;unitid&gt;</code></td>
      <td><code>099</code>, <code>090</code></td>
    </tr>
    <tr>
      <td>2.1.4 Repository identifier</td>
      <td><code>&lt;unitid&gt;</code> repositorycode attribute</td>
      <td><code>&lt;unitid&gt;</code> repositorycode attribute</td>
      <td><code>040$a</code></td>
    </tr>
    <tr>
      <td>2.1.5 Country identifier</td>
      <td><code>&lt;unitid&gt;</code> countrycode attribute</td>
      <td><code>&lt;unitid&gt;</code> countrycode attribute</td>
      <td>The MARC21 format does not contain a straightforward mapping for this DACS subelement value.</td>
    </tr>
    <tr>
      <td>2.2 Name and Location of Repository</td>
      <td><code>&lt;repository&gt;</code></td>
      <td><code>&lt;repository&gt;</code> or <code>&lt;relation&gt;</code></td>
      <td><code>852</code>, <code>524</code> (if the preferred citation indicates both the name and location of the repository)</td>
    </tr>
    <tr>
      <td>2.3 Title</td>
      <td><code>&lt;unittitle&gt;</code></td>
      <td><code>&lt;unittitle&gt;</code></td>
      <td><code>245$a</code></td>
    </tr>
    <tr>
      <td>2.4 Date</td>
      <td><code>&lt;unitdate&gt;</code></td>
      <td><code>&lt;unitdate&gt;</code> or <code>&lt;unitdatestructured&gt;</code></td>
      <td><code>264 _0 $c</code></td>
    </tr>
    <tr>
      <td>2.5 Extent</td>
      <td><code>&lt;physdesc&gt;</code> and subelements <code>&lt;extent&gt;</code>, <code>&lt;dimensions&gt;</code>, <code>&lt;genreform&gt;</code>, <code>&lt;physfacet&gt;</code></td>
      <td><code>&lt;physdesc&gt;</code> (text or basic formatting elements) or <code>&lt;physdescstructured&gt;</code> and subelements <code>&lt;quantity&gt;</code>, <code>&lt;unittype&gt;</code>, <code>&lt;physfacet&gt;</code> and <code>&lt;dimensions&gt;</code></td>
      <td><code>300$a</code> and potentially other subfields</td>
    </tr>
    <tr>
      <td>2.6 Name of Creator(s)</td>
      <td><code>&lt;origination&gt;</code></td>
      <td><code>&lt;origination&gt;</code> or <code>&lt;relation&gt;</code> (if using &lt;relation&gt;, specify appropriate @arcrole, e.g. http://purl.org/dc/elements/1.1/creator)</td>
      <td><code>100</code>, <code>110</code>, or <code>111</code>; <code>700</code>, <code>710</code>, or <code>711</code> for names in addition to that of the predominant creator</td>
    </tr>
    <tr>
      <td>2.7 Admininstrative/Biographical History</td>
      <td><code>&lt;bioghist&gt;</code></td>
      <td><code>&lt;bioghist&gt;</code></td>
      <td><code>545</code></td>
    </tr>
    <tr>
      <td colspan="3"><em>3 Content and Structure Elements</em></td>
    </tr>
    <tr>
      <td>3.1 Scope and Content</td>
      <td><code>&lt;scopecontent&gt;</code></td>
      <td><code>&lt;scopecontent&gt;</code></td>
      <td><code>520</code></td>
    </tr>
    <tr>
      <td>3.2 System of Arrangement</td>
      <td><code>&lt;arrangement&gt;</code></td>
      <td><code>&lt;arrangement&gt;</code></td>
      <td><code>351</code></td>
    </tr>
    <tr>
      <td colspan="3"><em>4 Access Elements</em></td>
    </tr>
    <tr>
      <td>4.1 Conditions Governing Access</td>
      <td><code>&lt;accessrestrict&gt;</code></td>
      <td><code>&lt;accessrestrict&gt;</code></td>
      <td><code>506</code></td>
    </tr>
    <tr>
      <td>4.2 Physical Access</td>
      <td><code>&lt;accessrestrict&gt;</code>, <code>&lt;phystech&gt;</code>, <code>&lt;physloc&gt;</code></td>
      <td><code>&lt;accessrestrict&gt;</code>, <code>&lt;phystech&gt;</code>, <code>&lt;physloc&gt;</code></td>
      <td><code>340</code>, <code>506</code></td>
    </tr>
    <tr>
      <td>4.3 Technical Access</td>
      <td><code>&lt;phystech&gt;</code></td>
      <td><code>&lt;phystech&gt;</code></td>
      <td><code>340</code>, <code>538</code></td>
    </tr>
    <tr>
      <td>4.4 Conditions Governing Reproduction and Use</td>
      <td><code>&lt;userestrict&gt;</code></td>
      <td><code>&lt;userestrict&gt;</code></td>
      <td><code>540</code></td>
    </tr>
    <tr>
      <td>4.5 Languages and Scripts of the Material</td>
      <td><code>&lt;langmaterial&gt;</code></td>
      <td><code>&lt;langmaterial&gt;</code></td>
      <td><code>546</code></td>
    </tr>
    <tr>
      <td>4.6 Finding Aids</td>
      <td><code>&lt;otherfindaid&gt;</code></td>
      <td><code>&lt;recordid&gt;</code> instanceurl attribute, <code>&lt;representation&gt;</code>, <code>&lt;otherfindaid&gt;</code>, or <code>&lt;relation&gt;</code></td>
      <td><code>555</code></td>
    </tr>
    <tr>
      <td colspan="3"><em>5 Acquisition and Appraisal Elements</em></td>
    </tr>
    <tr>
      <td>5.1 Custodial History</td>
      <td><code>&lt;custodhist&gt;</code></td>
      <td><code>&lt;custodhist&gt; or <code>&lt;relation&gt;</code></code></td>
      <td><code>561</code></td>
    </tr>
    <tr>
      <td>5.2 Immediate Source of Acquisition</td>
      <td><code>&lt;acqinfo&gt;</code></td>
      <td><code>&lt;acqinfo&gt;</code> or <code>&lt;relation&gt;</code></td>
      <td><code>541</code></td>
    </tr>
    <tr>
      <td>5.3 Appraisal, Destruction, and Scheduling Information</td>
      <td><code>&lt;appraisal&gt;</code></td>
      <td><code>&lt;appraisal&gt;</code></td>
      <td><code>583</code></td>
    </tr>
    <tr>
      <td>5.4 Accruals</td>
      <td><code>&lt;accruals&gt;</code></td>
      <td><code>&lt;accruals&gt;</code></td>
      <td><code>584</code></td>
    </tr>
    <tr>
      <td colspan="3"><em>6 Related Materials Elements</em></td>
    </tr>
    <tr>
      <td>6.1 Existence and Location of Originals</td>
      <td><code>&lt;originalsloc&gt;</code></td>
      <td><code>&lt;originalsloc&gt; or <code>&lt;relation&gt;</code></code></td>
      <td><code>535</code></td>
    </tr>
    <tr>
      <td>6.2 Existence and Location of Copies</td>
      <td><code>&lt;altformavail&gt;</code></td>
      <td><code>&lt;altformavail&gt; or <code>&lt;relation&gt;</code></code></td>
      <td><code>530</code>, <code>533</code></td>
    </tr>
    <tr>
      <td>6.3 Related Archival Materials</td>
      <td><code>&lt;relatedmaterial&gt;</code> or <code>&lt;separatedmaterial&gt;</code></td>
      <td><code>&lt;relatedmaterial&gt;</code>, <code>&lt;separatedmaterial&gt;</code>, or <code>&lt;relation&gt;</code></td>
      <td><code>544</code></td>
    </tr>
    <tr>
      <td>6.4 Publication Note</td>
      <td><code>&lt;bibliography&gt;&lt;p&gt;</code> or <code>&lt;bibliography&gt;&lt;bibref&gt;</code></td>
      <td><code>&lt;bibliography&gt;&lt;p&gt;</code>, <code>&lt;bibliography&gt;&lt;bibref&gt;</code>, or <code>&lt;relation&gt;</code></td>
      <td><code>581</code></td>
    </tr>
    <tr>
      <td><em>7 Notes</em><sup>1</sup></td>
      <td><code>&lt;odd&gt;</code>, <code>&lt;note&gt;</code></td>
      <td><code>&lt;controlnote&gt;</code>, <code>&lt;didnote&gt;</code>, <code>&lt;descriptivenote&gt;</code>, <code>&lt;footnote&gt;</code>, <code>&lt;odd&gt;</code></td>
      <td><code>500</code></td>
    </tr>
    <tr>
      <td><em>8 Description Control</em></td>
      <td><code>&lt;processinfo&gt;</code></td>
      <td><code>&lt;processinfo&gt;</code></td>
      <td><code>583</code></td>
    </tr>
    <tr>
      <td>8.1.4 Rules or conventions</td>
      <td><code>&lt;descrules&gt;</code></td>
      <td><code>&lt;conventiondeclaration&gt;</code> or <code>&lt;localtypedeclaration&gt;</code></td>
      <td><code>040$e</code></td>
    </tr>
    <tr>
      <td>8.1.5 Archivist and date</td>
      <td><code>&lt;processinfo&gt;&lt;p&gt;&lt;date&gt;</code></td>
      <td><code>&lt;processinfo&gt;&lt;p&gt;&lt;date&gt;</code></td>
      <td><code>583</code></td>
    </tr>
  </tbody>
</table>

## DACS to ISAD(G)

<table border="1">
  <tbody>
    <tr>
      <td><strong>DACS</strong></td>
      <td><strong>ISAD(G)</strong></td>
    </tr>
    <tr>
      <td><em>1 Levels of Description</em></td>
      <td>3.1.4 Level of description</td>
    </tr>
    <tr>
      <td colspan="2"><em>2 Identity Elements</em></td>
    </tr>
    <tr>
      <td>2.1 Reference Code</td>
      <td>3.1.1 Reference code(s)</td>
    </tr>
    <tr>
      <td>2.3 Title</td>
      <td>3.1.2 Title</td>
    </tr>
    <tr>
      <td>2.4 Date</td>
      <td>3.1.3 Dates</td>
    </tr>
    <tr>
      <td>2.5 Extent</td>
      <td>3.1.5 Extent and medium of the unit</td>
    </tr>
    <tr>
      <td>2.6 Name of Creator(s)</td>
      <td>3.2.1 Name of creator</td>
    </tr>
    <tr>
      <td>2.7 Administrative/Biographical History</td>
      <td>3.2.2 Administrative/Biographical history</td>
    </tr>
    <tr>
      <td colspan="2"><em>3 Content and Structure Elements</em></td>
    </tr>
    <tr>
      <td>3.1 Scope and Content</td>
      <td>3.3.1 Scope and content</td>
    </tr>
    <tr>
      <td>3.2 System of Arrangement</td>
      <td>3.3.4 System of arrangement</td>
    </tr>
    <tr>
      <td colspan="2"><em>4 Access Elements</em></td>
    </tr>
    <tr>
      <td>4.1 Conditions Governing Access</td>
      <td>3.4.1 Conditions governing access</td>
    </tr>
    <tr>
      <td>4.2 Physical Access</td>
      <td>3.4.4 Physical characteristics and technical requirements</td>
    </tr>
    <tr>
      <td>4.3 Technical Access</td>
      <td>3.4.4 Physical char. and technical req.</td>
    </tr>
    <tr>
      <td>4.4 Conditions Governing Reproduction and Use</td>
      <td>3.4.2 Conditions governing reproduction</td>
    </tr>
    <tr>
      <td>4.5 Languages and Scripts of the Material</td>
      <td>3.4.3 Language/scripts of material</td>
    </tr>
    <tr>
      <td>4.6 Finding Aids</td>
      <td>3.4.5 Finding aids</td>
    </tr>
    <tr>
      <td colspan="2"><em>5 Acquisition and Appraisal Elements</em></td>
    </tr>
    <tr>
      <td>5.1 Custodial History</td>
      <td>3.2.3 Archival history</td>
    </tr>
    <tr>
      <td>5.2 Immediate Source of Acquisition</td>
      <td>3.2.4 Immediate source of acquisition</td>
    </tr>
    <tr>
      <td>5.3 Appraisal, Destruction, and Scheduling Information</td>
      <td>3.3.2 Appraisal, destruction, scheduling</td>
    </tr>
    <tr>
      <td>5.4 Accruals</td>
      <td>3.3.3 Accruals</td>
    </tr>
    <tr>
      <td colspan="2"><em>6 Related Materials Elements</em></td>
    </tr>
    <tr>
      <td>6.1 Existence and Location of Originals</td>
      <td>3.5.1 Existence and location of originals</td>
    </tr>
    <tr>
      <td>6.2 Existence and Location of Copies</td>
      <td>3.5.2 Existence and location of copies</td>
    </tr>
    <tr>
      <td>6.3 Related Archival Materials</td>
      <td>3.5.3 Related units of description</td>
    </tr>
    <tr>
      <td>6.4 Publication Note</td>
      <td>3.5.4 Publication note</td>
    </tr>
    <tr>
      <td><em>7 Notes</em></td>
      <td>3.6.1 Note</td>
    </tr>
    <tr>
      <td><em>8 Description Control</em></td>
      <td>3.7.1 Archivist’s note</td>
    </tr>
    <tr>
      <td>8.1.4 Rules or conventions</td>
      <td>3.7.2 Rules or conventions</td>
    </tr>
    <tr>
      <td>8.1.5 Archivist and date</td>
      <td>3.7.3 Date(s) of descriptions</td>
    </tr>
    <tr>
      <td><em>Part II: Introduction to Describing Creators</em></td>
      <td>3.2.1 Name of creator</td>
    </tr>
    <tr>
      <td><em>10 Form of the Name</em></td>
      <td>3.2.2 Administrative/Biographical history</td>
    </tr>
    <tr>
      <td><em>11 Description of the Person, Family, or Corporate Body</em></td>
      <td></td>
    </tr>
    <tr>
      <td><em>12 Related Corporate Bodies, Persons, and Families</em></td>
      <td></td>
    </tr>
    <tr>
      <td><em>13 Authority Record Management</em></td>
      <td></td>
    </tr>
    <tr>
      <td><em>14 Related Archival Materials and Other Resources</em></td>
      <td></td>
    </tr>
  </tbody>
</table>

* * *

[1] Notes should only be encoded using the more generic <odd> and <note> elements (EAD) or 500 field (MARC 21) when they do not correspond to a more specific EAD element or MARC 21 field.
