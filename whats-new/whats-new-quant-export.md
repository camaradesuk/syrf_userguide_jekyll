---
title: "2nd Nov 2023: Quantitative Data Export Updates"
has_children: false
nav_order: 2
parent: What's New!
layout: page
permalink: whats-new/02-11-2023-quant-data
---

# Quantitative Data Export & Other Updates

We have further updated SyRF's data export functionality.
The following updates are of particular note to project administrators:

### New feature: Quantitative Data Export

[Quantitative Data Export](../data-export/quantitative.html) is now available.

### New field: DateTimeOfScreening(s)

New fields have been added for each screening data export:

- ["DateTimeOfScreening" (long format)](../data-export/data-dictionary/screening-long.html#datetimeofscreening)
- ["DateTimeOfScreenings" (wide format)](../data-export/data-dictionary/screening-wide.html#datetimeofscreenings).

This represents the date the screening was made by a given user.

### New field: DateTimeAnnotated

New field "DateTimeAnnotated" has been added for each annotation data export:

- [Annotation (long format)](../data-export/data-dictionary/annotation-long.html#datetimeannotated)
- [Annotation (wide format)](../data-export/data-dictionary/annotation-wide.html#datetimeannotated)

This represents the date the annotation was made by a given user.

### Consistent ISO date formats

Dates in all file exports are now given in ISO format (International Standards Organisation).

N.B.: Local Excel settings may impact how this is displayed.

[Explore all Data Dictionaries for available exports here](../data-export/data-dictionary/data-dictionary.html).

### Improved data export documentation

[The data export documentation](../data-export/) in the help guide has been significantly improved and now includes guidance on the changes above as well as detailed data dictionaries defining all fields present in the data exports.
