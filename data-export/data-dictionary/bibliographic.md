---
title: Bibliographic
parent: Data Dictionaries
grand_parent: Data Export
has_children: false
nav_order: 2
layout: page
---

# Bibliographic Data Dictionary

This spreadsheet output from a bibliographic data export will contain the unchanged bibliographic reference information for the studies in your SyRF project (as uploaded from original systematic search).

## Data Export Examples

[Bibliographic information example](./spreadsheet_templates/bibliographic_information_example.csv)

[Bibliographic information example - Systematic Search Import Compatible format](./spreadsheet_templates/bibliographic_information_systematic-search-import-compatibility-format_example.csv)

## Column Headings

- ##### **StudyId\***

  A unique 32 digit alphanumeric identifier which SyRF uses to refer to the specific study.

  _(UUID)_

- ##### **Title**

  Title of the study.

  _(String)_

- ##### **Authors**

  List of authors of study separated by a semi-colon.

  _(String)_

- ##### **PublicationName**

  Name of the journal in which the study was published.

  _(String)_

- ##### **AlternateName**

  Alternate name of the journal in which the study was published. (Former name, abbreviation, etc)

  _(String)_

- ##### **Abstract**

  Full text of the study abstract.

  _(String)_

- ##### **Url**

  Link to full-text PDF

  _(String)_

- ##### **AuthorAddress**

  Contact information for primary author. (institutional affiliation, e-mail address)

- ##### **Year**

  Year study was published.

  _(Integer)_

- ##### **Doi**

  Unique Digital Object Identifier (DOI) assigned to study.

  _(String)_

- ##### **ReferenceType**

  Type of reference (Journal article / book chapter / conference proceedings)

  _(String)_

- ##### **Keywords**

  Keywords associated with study.

  _(String)_

- ##### **PdfRelativePath**

  Path to PDF of study from root directory.

  _(String)_

- ##### **DateTimeStudyAdded\***

  When the study reference was uploaded to the SyRF project. In the ISO 8601 format, e.g. "2019-02-26 14:53:58"

  _(DateTime)_

- ##### **SystematicSearchId\***

  A unique 32 digit alphanumeric identifier which SyRF uses to refer to the specific search.

  _(UUID)_

- ##### **SystematicSearchName\***

  Unique search name.

  _(String)_

- ##### **CustomId**
  A string input by the user at the time of upload, which can be used for reference purposes outside of SyRF. (Endnote library name, etc)

  _(String)_

**\*** Column is omitted if "SyRF systematic search import compatible format" is ticked.
