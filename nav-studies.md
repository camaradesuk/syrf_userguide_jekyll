---
title: Studies
parent: Project
has_children: false
nav_order: 3
layout: page
---

# Studies

**Contents**

* TOC
{:toc}

---

## All Studies
{: .note }
> **Available to all users:** The following features are available to all users.

Under the 'All Studies' tab, you can see the bibliographic data of all the studies uploaded to a project. You can sort studies by different columns, filter them using the search box, and access detailed information for each study.

### Features Available in All Studies
- **Sorting:** Click column headers to sort by title, authors, year, etc.
- **Filtering:** Use the search box to find specific studies
- **Study Details:** Click on a study to view its complete information

---

## Study Management
{: .note }
> **Administrator Access Required:** The following features are only available to project administrators. 

This page has three main sections;
- Systematic Searches
- Risk of Bias Assessment
- Job Progress Tracking

## Systematic Searches
In this section you can:
- Upload a new Systematic Search
- Update studies using a CSV file
- Start Risk of Bias assessment on your searches
- View studies related to a search
- Delete a search
- Copy a search ID

In the Systematic Searches table you can see the statuses of the Systematic Search upload processes:

**Status Indicators:**
- `Uploading` - Initial file transfer in progress
- `Processing` - File validation and data extraction
- `Parsing` - Converting data into SyRF format
- `Complete` - Upload successfully finished
- `Error` - Upload failed (see error details below)

Clickable statuses (indicated with an animation) will direct you to the Job Progress table at the bottom of the page, which provides:
- Detailed progress information
- Status updates
- Error messages
- Time stamps for each operation



&nbsp;

### How to upload a systematic search
To start the upload click the "Upload New Systematic Search" button and follow the instructions in the dialog box.
Read more about [Systematic Search formats here]({{ site.baseurl }}{% link systematic-search.md %}).

![Search Upload](/figs/Fig_Search_Upload.png){: style="border: 2px solid #ccc; padding:10px;"}

&nbsp;

### How to update studies
The Bulk Study Update feature's button is located near the "Upload New Systematic Search" button. 
Click the button and follow the instruction in the dialog box.
Read more about [Updating studies]({{ site.baseurl }}{% link manage-studies.md %}).

![Bulk Update](/figs/Fig_Bulk-Study-Update-Button.png){: style="border: 2px solid #ccc; padding:10px;"}

&nbsp;

### How to start Risk of Bias assessment 

To start a Risk of Bias assessment on a search use the checkboxes in the first column. You can select a single search, multiple searches or you can select all the searches . When you make a selection you will see a button with a text that shows the number of selected studies. e.g. "2 selected". Click on the button to get access to run risk of bias assessment.


![Risk Of Bias 3](/figs/Fig_Risk-Of-Bias-3.png){: style="border: 2px solid #ccc; padding:10px;"}


![Risk Of Bias 1](/figs/Fig_Risk-Of-Bias-1.png){: style="border: 2px solid #ccc; padding:10px;"}


Now click on the "Calculate Risk of Bias for Selected" to start the process.
![Risk Of Bias 2](/figs/Fig_Risk-Of-Bias-2.png){: style="border: 2px solid #ccc; padding:10px;"}


Alternatively, you can use the ellipsis menu at the end of each row to start the risk of bias calculation.
![Risk Of Bias 4](/figs/Fig_Risk-Of-Bias-4.png){: style="border: 2px solid #ccc; padding:10px;"}


&nbsp;

### How to delete a systematic search
To delete a systematic search from your project:
1. Locate the search in the Systematic Searches table
2. Click the red delete button (trash icon) in the Actions column, next to the View Studies button
3. Confirm the deletion when prompted

> **⚠️ Warning:** This action cannot be undone. This will remove the systematic search from this project and all screenings, annotations and outcome data for studies in this search will be lost.

&nbsp;

### How to view all the studies in a systematic search
To view all studies in a specific systematic search:
1. Navigate to the "Systematic Searches" tab
2. Find the search you want to examine
3. Click the "View Studies" button in the Actions column
4. This will filter the All Studies view to show only studies from this search

### How to copy a systematic search's ID
To copy a search ID:
1. Locate the search in the Systematic Searches table
2. Click the three dots (⋮) in the Actions column
3. Select "Copy search ID" from the menu
4. The ID is now copied to your clipboard for use in other operations

---

The following sections allow you to monitor the progress of Risk of Bias assessment, Systematic Search Upload and Bulk Study Update.
## Risk of Bias Assessment
This table allows you to monitor the status of the Risk of Bias assessment processes. You can view the details of the errors if the process has errored. 

## Job Progress Tracking
The Job Progress section provides:
- Real-time status of ongoing background processes
- Detailed error messages 
- Historical record of completed jobs

---

## Next Steps
After managing your studies, you may want to:
- [Start Screening](screening.html) - Begin reviewing studies
- [Manage PDFs](manage-pdfs.html) - Add or update PDF links
- [Manage Studies](manage-studies.html) - Make bulk updates or corrections

## Related Pages
- [Upload Process](upload-search.html) - How to upload systematic searches
- [Managing Studies](manage-studies.html) - Post-upload management
- [Data Export](data-export.html) - Exporting study data

