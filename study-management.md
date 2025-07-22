---
title: Study Management
has_children: true
nav_order: 9
layout: page
---

# Study Management

This comprehensive guide covers everything you need to manage Systematic Searches in your SyRF project. Study Management is where project administrators upload, organize, monitor, and maintain study references throughout the systematic review process.

## What is Study Management?

In SyRF, Systematic Searches are organized groups of references from your database searches (PubMed, Embase, Scopus, etc.).

The Study Management interface provides tools to:

- Upload new systematic searches
- Monitor upload and processing progress
- Update existing study data in bulk
- Calculate Risk of Bias assessments
- Manage PDF file associations
- Delete systematic searches when needed

## Accessing Study Management

{: .note }
> **Administrator Access Required:** Study Management features are only available to project administrators.

Navigate to **Studies** → **Study Management** in your project to access the administrative interface.

todo: add screenshot

## The Study Management Interface

The Study Management page contains four main sections:

### 1. Systematic Searches Table
Your primary workspace showing all uploaded searches with:
- **Action buttons**: Upload new searches and bulk update studies
- **Search list**: View all systematic searches with status, study counts, and actions
- **Bulk operations**: Select multiple searches for Risk of Bias calculations
- **Progress indicators**: Real-time status updates with clickable links to detailed progress

For each systematic search, manage viewing, deletion, Risk of Bias calculations, and ID copying.

### 2. Risk of Bias Assessment Monitoring
Track automated bias assessment jobs with detailed progress and error reporting.

### 3. Job Progress Monitoring  
Real-time tracking of background processes including Systematic Serach Uploads, Bulk Study Updates with comprehensive error details.



## Complete Workflow Overview

```
Prepare Files → Upload Search → Monitor Progress → Manage Studies → Calculate Risk of Bias
      ↓              ↓              ↓              ↓                    ↓
[File prep]    [Upload dialog] [Job tracking]  [Bulk updates]    [ROB assessment]
```

## Core Topics Covered

* **[Preparing References](prepare-references.html):** File preparation, deduplication, and format requirements  
* **[Uploading Systematic Searches](upload-search.html):** Step-by-step upload process and dialog navigation
* **[Monitoring Upload Progress](monitoring-upload-progress.html):** Understanding status indicators and job tracking
* **[Managing Studies Post-Upload](manage-studies.html):** Bulk Study updates, corrections, and study modifications
* **[Managing PDF Files](manage-pdfs.html):** Linking studies to full-text PDFs and file organization
* **[Viewing and Browsing Studies](view-studies.html):** Navigate uploaded studies and use search/filter tools
* **[Risk of Bias Assessment](risk-of-bias-assessment.html):** Automated bias calculation and results management

Multiple systematic searches can be managed within a single project, allowing you to handle results from different search strategies, database updates, or iterative search refinements.

## Quick Start Guide

Choose your starting point based on your current situation:

> **💡 New to SyRF uploads?** 
> Start with [Preparing References](prepare-references.html) to learn file preparation, deduplication, and format requirements

> **📂 Files ready to upload?** 
> Jump to [Upload Process](upload-search.html) for step-by-step instructions

> **📄 Need to add PDFs later?** 
> Check [PDF Management](manage-pdfs.html) for file linking procedures  

> **✏️ Updating existing data?** 
> Use [Managing Studies Post-Upload](manage-studies.html) for bulk updates

> **🔍 Want to assess study quality?**
> See [Risk of Bias Assessment](risk-of-bias-assessment.html) for automated calculations

> **❌ Having upload issues?**
> Review [Monitoring Upload Progress](monitoring-upload-progress.html) for troubleshooting

## Status Indicators Guide

Understanding the status indicators in the Study Management interface:

| Status | Meaning | Clickable? | Next Action |
|--------|---------|------------|-------------|
| `Uploading` | File transfer in progress | ✅ Yes | Click to view detailed progress |
| `Received` | File received, queued for processing | ✅ Yes | Click to monitor processing |
| `Parsing` | Converting data into SyRF format | ✅ Yes | Click for parsing details |
| `Complete` | Upload successfully finished | ❌ No | Search is ready for use |
| `Error` | Upload failed | ✅ Yes | Click to view error details |

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

## Navigation Guide

Use the left navigation menu to access detailed guides for each aspect of study management. Each subsection provides comprehensive instructions, best practices, and troubleshooting tips.

**Start with the basics:**
1. [Getting Started](getting-started-study-management.html) - Core concepts and terminology
2. [Preparing References](prepare-references.html) - File preparation and formatting

**Upload and monitor:**
3. [Uploading Systematic Searches](upload-search.html) - Step-by-step upload process  
4. [Monitoring Upload Progress](monitoring-upload-progress.html) - Track and troubleshoot uploads

**Manage and maintain:**
5. [Managing Studies Post-Upload](manage-studies.html) - Bulk updates and corrections
6. [Managing PDF Files](manage-pdfs.html) - Link studies to full-text documents
7. [Viewing and Browsing Studies](view-studies.html) - Navigate and search your studies

**Advanced features:**
8. [Risk of Bias Assessment](risk-of-bias-assessment.html) - Automated quality assessment

## Common Workflows

**First-time upload workflow:**
Prepare Files → Upload → Monitor → Verify → Add PDFs → Calculate ROB

**Ongoing maintenance workflow:**  
Review Studies → Bulk Update → Monitor Jobs → Recalculate ROB

**Troubleshooting workflow:**
Check Status → Click Error Details → Review File Format → Re-prepare → Re-upload

---

*Need help? Each subsection includes detailed troubleshooting and links to related topics.*
