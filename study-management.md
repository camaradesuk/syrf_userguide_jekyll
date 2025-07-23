---
title: Study Management
has_children: true
nav_order: 9
layout: page
---

# Study Management

This guide covers how to manage Systematic Searches in your SyRF project. In Study Management page project administrators can upload, organise, monitor, and update study references throughout the systematic review process.

## What is Study Management?

In SyRF, Systematic Searches are organised groups of references from your database searches.

The Study Management interface provides tools to:

- Upload systematic searches
- Bulk update existing study data
- Run Risk of Bias assessments
- Manage PDF file associations
- Monitor upload and processing progress
- Delete systematic searches 

## Accessing Study Management

{: .note }
> **Administrator Access Required:** Study Management features are only available to project administrators.

After selecting a project,
click on **Studies** button on the left navigation bar → then click on **Study Management** button to access the administrative interface.

todo: add screenshot

## The Study Management Interface

The Study Management page contains three main sections:

### 1. Systematic Searches Table
Your primary workspace showing all uploaded searches with:
- **Action buttons**: Upload new searches and bulk update studies
- **Bulk operations**: Select multiple searches for Risk of Bias calculations
- **Progress indicators**: Real-time status updates with clickable links to detailed progress
- **Overflow menu** View studies, delete Systematic Searches, run Risk of Bias assessment for a single search, copy the ID of a search



### 2. Risk of Bias Assessment Monitoring
Track risk of bias assessment processes with detailed progress and error reporting.

### 3. Job Progress Monitoring  
Real-time tracking of background processes including Systematic Serach Uploads, Bulk Study Updates with comprehensive error details.


## Quick Guide

Choose your starting point based on your current situation:

> **Prepare files for Systematic Search Upload**
>
> Start with  [Preparing References](prepare-references.html). Learn file preparation, deduplication, and format requirements.

> **Upload Systematic Sesrches with the prepared files**
> 
> Read [Systematic Search Upload Process](upload-search.html) for step-by-step instructions on how to upload systematic searches using a CSV or an XML file.

> **If you need to add PDFs later?**
>
> Check [PDF Management](manage-pdfs.html) to learn how you can link full-text PDFs to studies to give reviewers access to full text during screening and data extraction. 

> **If you need to update existing data**
>
> Use [Managing Studies Post-Upload](manage-studies.html) to modify existing studies that had been uploaded. This feature is useful for add or correc PDFRelativePath information, add or correct CustomID values and  Upload or modify screening decisions made outside of SyRF or correct existing screening decisions.

> **Calculate Risk of Bias**
>
> See [Risk of Bias Assessment](risk-of-bias-assessment.html) for details. DO WE NEED A PAGE??

> **Monitor the background processes**
>
> Review [Monitoring Upload Progress](monitoring-upload-progress.html). DO WE NEED A PAGE??

## Status Indicators Guide

Understanding the status indicators in the Study Management interface:

| Status | Meaning | Clickable? | Next Action |
|--------|---------|------------|-------------|
| `Uploading` | File transfer in progress | ✅ Yes | Click to view detailed progress |
| `Received` | File received, queued for processing | ✅ Yes | Click to monitor processing |
| `Parsing` | Converting data into SyRF format | ✅ Yes | Click for parsing details |
| `Complete` | Upload successfully finished | ❌ No | Search is ready for use |
| `Error` | Upload failed | ✅ Yes ??? | Click to view error details |

## Video Guide

<br/>

<div class="youtube-wrapper">
    <iframe src="https://www.youtube.com/embed/e6blmlaPrNA?list=PLT9yacSnQZW85roKzVqoC11OiXm9pob-4"
            title="SyRF Guide: Uploading a Systematic Search"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            allowfullscreen>
    </iframe>
</div>

---



*Need help? Each subsection includes detailed troubleshooting and links to related topics.*
