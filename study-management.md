---
title: Study Management
has_children: true
has_toc: false
nav_order: 9
layout: page
---

**Contents**

* TOC
{:toc}

---

# Study Management

This guide covers how to manage studies in your SyRF project.

## Key Study Management Activities

The following are key activities for managing studies in your SyRF project:

1. **[Prepare files for systematic search upload](prepare-references.html)** - Start by preparing your CSV or XML files for upload, including deduplication and format requirements.

2. **[Upload systematic searches](upload-search.html)** - Use the prepared files to upload systematic searches with step-by-step guidance through the upload wizard.

3. **[Manage PDFs](manage-pdfs.html)** - Coordinate with the SyRF helpdesk to provide full-text PDF access for reviewers during screening and data extraction.

4. **[Update data for uploaded studies](manage-studies.html)** - Use Bulk Study Update to modify existing studies, add PDF paths, update custom IDs, or correct screening decisions.

5. **[Calculate Risk of Bias](calculate-risk-of-bias.html)** - Initiate risk of bias calculations and monitor assessment processes.

<!-- 6. **Monitor background processes** - Track upload progress and background processes using the monitoring tools described in [sections 3.2](#2-risk-of-bias-assessment-monitoring) and [3.3](#3-job-progress-monitoring) below.  -->

The guidance for these activities are covered in detail in dedicated sub-pages.



---

## Study Management Interface

{: .note }
> **Administrator Access Required:** Study Management features are only available to project administrators.

To access the study management interface, select a project, click the **Studies** button in the left navigation bar, then click **Study Management**

![Study Management Interface](figs/Fig_study-management-access-2.png){: style="border: 2px solid #ccc; padding:10px;"}

## Overview of Study Management Interface

Study Management interface is the central hub for managing your research data throughout the systematic review process. 

There are 3 main sections:
1. **[Systematic Searches Table](#1-systematic-searches-table)** - Your primary workspace for managing searches
2. **[Risk of Bias Monitoring](#2-risk-of-bias-assessment-monitoring)** - Monitoring Risk of Bias assessments
3. **[Job Progress Monitoring](#3-job-progress-monitoring)** - Monitor background processes


### 1. Systematic Searches Table
Your primary workspace showing all uploaded searches with:
- **Action buttons**: Upload new searches and bulk update studies
- **Bulk operations**: Select multiple searches for Risk of Bias calculations
- **Progress indicators**: Real-time status updates with clickable links to detailed progress
- **Overflow menu**: View studies, delete systematic searches, run Risk of Bias assessment for a single search, copy the ID of a search

Access guidance for [Upload Systematic Search](upload-search.html), [Bulk Study Update](manage-studies.html), and [Calculate Risk of Bias](calculate-risk-of-bias.html) at dedicated user guide sections.

The following actions are performed directly within the Systematic Searches table:

**1.1 View Studies in a Systematic Search**
{: #view-studies}

Click the icon marked in the screenshot to view studies.
![Study Management Interface](figs/Fig_view-studies-from-systematic-search-table.png){: style="border: 2px solid #ccc; padding:10px;"}


This table displays all studies currently imported into your project. You can sort, filter, and search this list. You can also view the PDFs if available.


**1.2 Delete a Systematic Search**
{: #delete-search}
> **⚠️ Warning:** This action cannot be undone. This will remove the systematic search from this project, and all screenings, annotations and outcome data for studies in this search will be lost.

Click the red delete button (trash icon) in the Actions column: 

![Study Management Interface](figs/Fig_search-delete-start.png){: style="border: 2px solid #ccc; padding:10px;"}

This will open a dialogue box for confirmation. Type the systematic search name into the text field and click Delete to complete the process:

![Study Management Interface](figs/Fig_search-delete-confirmation.png){: style="border: 2px solid #ccc; padding:10px;"}


**1.4 Copy Systematic Search ID**
{: #copy-search-id}
Click the ellipsis symbol to access the overflow menu and select the button for copying the search ID:
![Study Management Interface](figs/Fig_copy-search-id.png){: style="border: 2px solid #ccc; padding:10px;"}


### 2. Risk of Bias Assessment Monitoring
{: #2-risk-of-bias-assessment-monitoring}

Track Risk of Bias Assessment processes with detailed progress and error reporting. 

### 3. Job Progress Monitoring
{: #3-job-progress-monitoring}

The Job Progress table shows all running and completed background processes. Click the job name to view detailed progress information, or click the error count (if any) to view specific error details:

![Study Management Interface](figs/Fig_job-progress-table.png){: style="border: 2px solid #ccc; padding:10px;"}

When you click on an error count, a detailed error dialogue box opens showing specific error messages.

![Study Management Interface](figs/Fig_job-progress-table-error.png){: style="border: 2px solid #ccc; padding:10px;"}


---

**Status Indicators**
{: #status-indicators}

Understanding the status indicators in the Systematic Searches table:

*Uploading:* File transfer is currently in progress. This status is clickable and will show detailed progress information when selected.

*Received:* The file has been received and is queued for processing. Click this status to monitor the processing progress.

*Parsing:* The system is converting your data into SyRF format. This status is clickable to view parsing details.

*Complete:* The upload has successfully finished and the search is ready for use. This status is not clickable as no further action is needed.

*Error:* The upload has failed. Click this status to view detailed error information that can help troubleshoot the issue.

---

*Need help? Each subsection includes detailed troubleshooting and links to related topics.*
