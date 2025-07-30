---
title: Bulk Update Studies
parent: Study Management
nav_order: 5
layout: page
---

**Contents**

* TOC
{:toc}

---

# Managing Studies Post-Upload
## Using the Bulk Study Update Feature

This powerful feature allows Project Administrators to modify data for *existing* studies in bulk *after* they have been uploaded. It's useful for:

* Adding or correcting `PDFRelativePath` information (e.g., for the two-stage PDF workflow).
* Adding or correcting `CustomID` values.
* Uploading or modifying screening decisions made outside of SyRF (or correcting existing ones).

### How to Access Bulk Update

Navigate to **Studies** -> **Study Management**.
Click on the "Bulk Study Update" button to start the process.  


![Bulk Update](/figs/Fig_Bulk-Study-Update-Button.png){: style="border: 2px solid #ccc; padding:10px;"}

"Bulk Update Study References" dialog will be opened. 


![Screenshot showing location of Bulk Study Update option](figs/Fig_Bulk-Study-Update.png)


## 1. Preparing Your Update File (CSV)

### 1.1 Create a CSV File
You'll need a new CSV file specifically for the update.

### 1.2 Required `studyId` Column
This file **must** include a column named exactly `studyId`. Each row should contain the unique SyRF `studyId` of a study you wish to update.
* **How to get `studyId`s:** The easiest way is to export your current study data from SyRF. Go to `Data Export` -> `Bibliographic`. **Untick** the option "SyRF systematic search import compatible format". Click `DOWNLOAD DATA`. The exported CSV file will contain the `studyId` column along with other bibliographic data.

### 1.3 Include Only Columns to Update
Besides `studyId`, your update file should *only* contain columns for the data you intend to change. For example:
* `pdfRelativePath`
* `customId`
* Columns for screening decisions (e.g., `Screener_Alice_TitleAbstract`, `Screener_Bob_FullText`).
* **Important:** Remove all other bibliographic columns (`Title`, `Authors`, `Year`, etc.) from the file you exported to get the `studyId`s. Only keep `studyId` and the columns you are actively updating.

### 1.4 Enter Update Values
* **For `pdfRelativePath` or `customId`:** Enter the new value in the corresponding cell for each `studyId` you want to modify.
    > **Warning:** Providing an empty/blank cell for `pdfRelativePath` or `customId` in the update file *will erase* any existing value for that field in SyRF for that study. Only include rows and provide values for studies you intend to change.
* **For Screening Decisions:**
    * Use column names you can recognise (you'll map them later).
    * Use `1` for inclusion and `0` for exclusion.
    * **Note:** Blank cells in screening decision columns are *ignored* during the update; they will *not* erase existing decisions. However, providing a `1` or `0` will *overwrite* any previous decision made by the *same mapped user* for the *same study* across ***any*** screening stage.

## 2. Upload and Mapping Process

### 2.1 Choose File
In the "Bulk study update" dialog, select your prepared CSV update file.

### 2.2 Column Mapping
SyRF will display the columns it detected in your CSV. Review this list carefully. If unexpected columns appear, cancel the upload, correct your CSV file, and try again.
If you included screening decision columns, you **must** map each one to the corresponding **Project Member** and the relevant **Screening Stage** (e.g., Title/Abstract, Full Text).

![Screenshot of column mapping for screening decisions in Bulk Update](figs/Fig_Bulk-Study-Update-Screening.png)

### 2.3 Review and Confirm Upload
A final confirmation screen summarizes the detected columns and the screening decision mappings you've made.
**Read the warnings on this page very carefully before proceeding.**

> **Critical Warnings for Bulk Update:**
>
> * **Irreversible Action:** Bulk updates **cannot be undone**. Changes made are permanent. Double-check your update file and mappings.
> * **Overwriting Data (`pdfRelativePath`, `customId`):** Any data present in your update file for these columns *will overwrite* the current data in SyRF for the specified `studyId`.
> * **Erasing Data (`pdfRelativePath`, `customId`):** Providing a *blank cell* for these columns in your update file *will permanently delete* any existing data for that field in SyRF.
> * **Screening Decisions:** Decisions (`1` or `0`) in your update file *will overwrite* existing decisions made by the *same user* for the *same study* and *same stage*. Blank cells in screening columns are *ignored* and do not erase existing decisions.

If everything is correct, confirm the upload.

![Screenshot of the final confirmation page for Bulk Update](figs/Fig_Bulk-Study-Update-Confirmation.png)



---

## Related Pages

* **[Preparing References](prepare-references.html)** - How to prepare your reference files
* **[Upload Search](upload-search.html)** - How to upload your systematic search
* **[Managing PDFs](manage-pdfs.html)** - How to add and manage PDF files
* **[View Studies](study-management.html#view-studies)** - See your uploaded studies in the project
