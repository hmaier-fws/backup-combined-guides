# mdJSON vs. mdEditor files

File management in mdEditor involves consistent and proper handling and storage of mdEditor derived formats of metadata. These files are essential for long-term access to metadata beyond a single work session.

## How mdEditor Stores Information

mdEditor stores information on your local computer in your internet browser's[ localStorage](https://en.wikipedia.org/wiki/Web\_storage) cache (not the normal file cache). This means that if you use a different internet browser (Edge vs Google)  to access mdEditor, it will not show the metadata records from your original browser. It also means that clearing your browser's cache generally will not delete your mdEditor records. However, depending on your browser's settings, clearing your browser cache may still delete your mdEditor data (e.g., in Chrome, checking the "c_ookies and other site data_" option will clear your mdEditor data).

{% hint style="danger" %}
**Warning**: In mdEditor settings, you can clear your storage cache. Doing so will remove all of the information currently loaded in mdEditor. Reasons you might want to clear your storage cache is due to too much information stored in the cache, or as a way to debug a problem with mdEditor. **It is very important that you back up your records before clearing the mdEditor cache to avoid losing your data.** Consult the [Export](../metadata-standards-reference/exporting.md) or Settings section of this manual to learn more.
{% endhint %}

## mdEditor File Format

[JSON](https://en.wikipedia.org/wiki/JSON) (JavaScript Object Notation) is an open-standard file format with file extension .json. The underlying format of the metadata from mdEditor is mdJSON, which was created specifically for mdEditor and is a sort of dialect of JSON.  There are two types of mdJSON files.

1. mdJSON files are the format that is published from mdEditor and made available to metadata catalogs like ScienceBase and data.gov. Their default file name is _**md\_metadata.json**_.
2. mdEditor.json files are the files used by mdEditor. They contain extra information, such as settings, that tell mdEditor how to operate. Their default file name is _**mdeditor-timestamp.json**_.

mdJSON files can be exported and imported via mdEditor's built-in [**Export** ](broken-reference)and [**Import**](broken-reference) functionality. The Export functionality allows you to back up and share your records between browsers. The Import functionality lets you load records into mdEditor, either from previously-saved mdEditor session, exported from another browser, or downloaded from ScienceBase.

{% hint style="info" %}
JSON = JavaScript Object Notation, an open source file format. mdEditor produces mdJSON. ScienceBase has their own JSON format, called sbJSON.
{% endhint %}

### What mdJSON files are required?

The Alaska Regional Data Repository houses mdEditor files created from using Export All or Export Selected.

![](<../../.gitbook/assets/image (73).png>)

**Plain mdJSON,** which are produced by using Export mdJSON, are files that may be translated into other metadata standards or published externally. These files do not contain the extra information used by mdEditor.

{% hint style="warning" %}
Typically, the Export mdJSON function is NOT used when creating a metadata file for the a RDR archive folder.
{% endhint %}

![](<../../.gitbook/assets/image (33).png>)



## mdEditor File Management Strategies

### (1) Work on a project-by-project basis.

To keep file size manageable, it is recommended that you work on one project (and its related products and contacts) at a time. You should group said project, products, and contacts together using the same scheme that your LCC uses to organize data.

1. Save each project and affiliated products together as a set. To do this, select ???Export??? from the top menu, then select the appropriate records (i.e., the target project and its affiliated products) and then click ???Export Selected."
2. Save the resulting mdEditor JSON file to your hard drive in a working folder. There should be a separate mdEditor JSON file for each project and all of its products.

### (2) Leave information in mdEditor between work sessions.

It is recommended that you leave your contacts in mdEditor between work sessions so that they will be available the next time you need to create metadata records. You can also export your contacts independently of your records for use between browsers.

You can also set up a metadata directory so you can always find the metadata file. This directory can be any folder on your local computer that is easily accessible and will not be deleted. &#x20;

{% hint style="info" %}
Remember that the Regional Data Repository contains an master contacts list in the top level contacts folder and approved mdEditor.json files are stored there as well.
{% endhint %}

### (3) Export your contacts with your records.

When exporting products or projects, you should also export your entire contact list. If you do not export your contact list, and you later import a record that contains a contact not loaded in mdEditor, you may receive an error and have to re-create and re-enter the contact for that record.

{% hint style="danger" %}
If contacts records are re-created, it results in another mdEditor identifier being created for a contact, resulting in duplicate contacts. mdEditor does not know that this is an existing contact. You should maintain a single list of your contacts. Having duplicate copies of the same contact is not desirable. It can create confusion as you edit and manage your metadata records and introduce unnecessary errors.

This is why we have a master contacts file in the RDR!
{% endhint %}

### (4) Export frequently to backup your records.

Maintain an ???Export All??? JSON file each time you finish a work session in mdEditor (or switch browsers, URLs, etc.). This is the most efficient way to backup your records. For more information, consult [Export](../metadata-standards-reference/exporting.md).

It is particularly important that you export your records for backup before using mdEditor's **Clear Storage Cache** functionality (clearing the storage cache will delete any records or data you have entered in mdEditor). Exporting ensures that your data is secure even after clearing the storage cache. Not exporting your data before clearing your cache will result in a permanent loss of records. Consult the [Settings](broken-reference) section of this manual to learn more.







&#x20;
