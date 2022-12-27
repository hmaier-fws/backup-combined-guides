# Metadata Creation Workflow

The following is a suggested workflow for metadata creation (or revision and updating). Click on any link here to get more information about the step.

## Step 1: Gather the information needed for your metadata entries

Have information about your projects and products on hand before you begin creating metadata records. This information includes start and end dates, project abstracts or product summaries, QA/QC procedures or other protocol documents, or a DOI (digital object identifier).&#x20;

{% hint style="success" %}
Guidance for obtaining a DOI (digital object identifier) is given in the [AK-Region Interim Data Management User Guide](https://ak-region-dst.gitbook.io/alaska-region-interim-data-management-user-guide/).
{% endhint %}

If you are writing metadata for a product, tidy your data products using the best practices guidance provided in the [AK-Region Interim Data Management User Guide](https://ak-region-dst.gitbook.io/alaska-region-interim-data-management-user-guide/).&#x20;

## Step 2: Open mdEditor and check Settings

The direct link to mdEditor is [https://go.mdeditor.org](https://go.mdeditor.org/). Bookmark this link in your browser for future reference.

The first time you open mdEditor, check your settings. The one to consider changing now is to set AutoSave to ON. The AutoSave option will write all changes to local storage as soon as you exit a data entry field. Changes must be manually saved if the Auto-Save feature is turned off. AutoSave allows you to save less frequently, but it makes it harder to undo changes that you make to your records. Once you leave the record, the record is saved and changes can no longer be cancelled.

![](broken-reference)

## Step 3: Import the metadata file from your project's archive fold

If you are updating an existing metadata record, you should import the mdEditor mdJSON file from the project's folder in the Regional Data Repository. Learn how to import files into mdEditor on the [Import ](broken-reference)page.&#x20;

The metadata file will either be in the incoming folder or the metadata folder in your project's archive folder, depending if the metadata has previously been approved or not. It will still be in the incoming folder if it has not been approved by your Data Manager. It will be in the metadata folder if your Data Manager has already reviewed and approved it.&#x20;

{% hint style="success" %}
If you are starting a new project metadata record and completed the machine-readable DMP, then a mdJSON initiated metadata record has been created for you in your incoming folder.
{% endhint %}

## Step 4: Import the Contacts file from the Regional Data Repository Folder

Learn how to import files into mdEditor on the [Import ](broken-reference)page.&#x20;

Contacts must be loaded into mdEditor before they can be used in the creation of metadata records. The contact folder is located in the contacts file on the [Regional Data Repository.](../alaska-data-management-101/alaska-region-data-repository.md) Consult the [contacts ](contacts.md)section for information on the contacts record and adding new contacts.

## Step 5: Consider making a template record and using the Copy Record function

If you are making many project and product records with similar information, like Points of Contact, it might be efficient to make a template metadata record and use the [Copy Record](mdeditor-101/untitled-1.md) function to avoid re-entering the same information repeatedly.&#x20;

{% hint style="danger" %}
If you do copy a record, be sure to check that a new record ID in the copy is created and to thoroughly review the copied record to be sure that all information in relevant to the new record.&#x20;
{% endhint %}

## Step 6: Write (or revise or update) metadata

Follow [project entry guidance](broken-reference), [product entry guidance](broken-reference) or [dictionary entry guidance](broken-reference) depending on what type of metadata you are writing.&#x20;

## Step 7: Create Associations

Associations link project metadata with product metadata. With both the project and product metadata loaded into mdEditor, associations can be established [from the project to the product](broken-reference) or [from the product to the project](broken-reference).

{% hint style="info" %}
If you used the machine-readable DMP template, associations between the project and its products listed are already created in your initiated metadata records!
{% endhint %}

## Step 8 : Export the file to your project's incoming folder for review or backup

[Export](broken-reference) the project, product, and data dictionary records as a single file to the incoming folder in the project's archive folder on the Regional Data Repository using **Export All**. Rename this file "project\_name.json." For example, MBMWA\_011\_YKDNestPlot.json would be the metadata record for the YK Delta nest plot survey project conducted by the Waterfowl Program in MBM (it was the 11th project archive record created by the program).&#x20;

{% hint style="danger" %}
Even if your metadata file is not ready for review, export it to the incoming folder after every session and import it back into mdEditor at the beginning of a new session. It serves as a backup to your metadata files.
{% endhint %}

This metadata file will be moved from your incoming folder to the metadata folder of the project by the data custodian after review.

## Step 9: Data Custodian reviews metadata and product

The Data Custodian may ask you to revise the metadata and you would import the metadata from the incoming folder to continue working on it (see Step 4). When the metadata file is approved, the Data Custodian will move the metadata file and associated products from the incoming folder and into the appropriate location(s) in the archive folder.
