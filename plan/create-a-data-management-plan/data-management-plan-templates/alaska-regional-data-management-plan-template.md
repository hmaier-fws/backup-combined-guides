# Alaska Regional Data Management Plan Template

The Alaska region offers a fillable form Microsoft Word DMP template for region-wide use.  The most recent version can be found [on ServCat](https://doi.org/10.7944/P9XUYMQT).  The form must be completed in the desktop version of Word to enable its full functionality.

### Benefits of using the regional DMP template

This template is designed to meet the requirements of the Service National DMP template. Your entries from this form will be fed to the National DMP for you, thus eliminating double entry. Note that fields with asterisks(\*) are required by the Region and encompass what is required by the National DMP template.&#x20;

Additionally, this template can be used to initiate your project and project metadata records in mdEditor. Your data manager will run a script to translate your inputs from this template into a mdEditor file. This automation eliminates the need to re-enter the same information from the DMP into your metadata.&#x20;

## **Regional Template Guidance**

### Section 1: Project Details

The first section collects basic project information and includes:

* **Program Name:** Choose the primary program name that the project falls under from the dropdown list, then select other programs involved with the project. While hidden, the default region is the USFWS Alaska Region.
* **Cost Center:** Choose the primary cost center from the dropdown list, then select other applicable cost centers. Please let your data manager know if there are any discrepancies to this list.&#x20;
* **Project Title:** Enter a descriptive yet succinct title.  Include species, time frame, geography, season, method or purpose, as appropriate.&#x20;
* **Start and End Dates:** Enter a start date and end date from the calendar pick tools, or enter them with using the YYYY-MM-DD format. Project start date is generally when the project is approved, funded, or when work actually begins.  End date is the date that a final product (i.e., report) is completed or funding ends, and may be an estimated date. If the project is a long-term monitoring effort, check the ongoing box rather than selecting an end date. &#x20;
* **Abstract:** Enter a description of the project into the text box. This can be copy and pasted from a proposal or investigation plan. &#x20;
* **Keywords:** Enter 4 or 5 keywords separated by commas in the text box.  Keywords may be location, species, survey method, or biological event of interest. For example: Eastern rednot, Maine, migration, stopover sites
* **Unique Project Identifier or Tracking Number:** Enter the project identifier(s) into the text box, if present. This can be a funding agreement number, contract number, or any other identifier that can link your data products to the project effort. If the project is a National Wildlife Refuge System (NWRS) initiative, enter the PRIMR ID. Internal projects may not have any project tracking identifiers.&#x20;
* **Spatial Extent:** Enter a brief text description and/or the URL location of the project spatial extent, if available. The URL may reference a shapefile, geoJSON, KML, geopackage, geoTIFF, or other. Spatial features should be provided in latitude and longitude coordinates (WGS84). Extent files must be on a shared server location, not a local computer, and file paths must include the full server name instead of the mapped drive letter (i.e., "\\\ifw7ro-file.fws.doi.net\datamgt\extents\ simplified\_refuge\KenaiNWR.geojson" instead of "D:\extents\ simplified\_refuge\KenaiNWR.geojson"). Simplified refuge boundaries can be found [in the RDR](file://ifw7ro-file.fws.doi.net/datamgt/extents-json/simplified\_refuge\_boundaries\_AlaskaRegion/). Other simplified boundaries can be created and shared upon request.

### Section 2: Project Personnel

Section 2 collects project staff information and includes:&#x20;

* **Primary Project Contact:** This is a FWS staff person who is responsible for the management of the project and associated data products. This person should be knowledgeable of the data products. This role may be filled by the project manager or primary investigator for the project. This person will be listed as a 'point of contact' in the metadata.
* **Data Steward:** This person is responsible for ensuring that collected data is tidy, clean, complete, quality controlled and assured, and appropriately documented with metadata. This may be the field crew leader or the project manager and may be same person as the Primary Project Contact. This person should be highly knowledgeable regarding the project and its data products. This person will also be a 'point of contact' in the metadata.
* **Data Custodian:** This is the person responsible for the long-term management of authoritative data deliverables and associated metadata in the RDR. This is likely your program or regional data manager or maybe the project manager. This person will be 'custodian' in the metadata.
* **Data Trustee:** This is the person responsible for ensuring that your project team has the resource allocations needed to fulfill all aspects of the project and data lifecycle. This is also likely the person who approved or renewed your project, like your program manager or field office supervisor. This person will be the 'owner' in the metadata.

The form provides additional space to add other project staff and/or collaborators. Use the plus (+) button (see blue arrow below) to add more contact entry rows (note: you must have your cursor inside of the table in order for the plus sign to be visible). This allows you to give credit to those who may not have key data management role responsibilities but contributed time or resources toward your project. Their names will also appear in the metadata with their corresponding roles.

![Contacts entry table from the regional DMP template. Note the blue arrow indicating the plus (+) button to add additional rows to the table.](<../../../.gitbook/assets/image (101).png>)

The [Service Data Management Handbook](https://www.fws.gov/policy/274fw1.html#\_3dy6vkm) provides additional guidance on these key roles and responsibilities.

### Section 3: Metadata & Data Standards

Check the box to indicate that your project and data projects will be documented with metadata that meets national, regional, and programmatic standards (_super easy!_). Don't worry; the metadata creation guidance in this guide will ensure that your metadata meets open data and all these other standards. &#x20;

Alternatively, if you would like to use another metadata standard, check the 'Other' box and select an option from the dropdown list. Be aware that this option does not have metadata validation support in mdEditor.

This section ends with a reminder that data collection must follow Service-wide standards. This guide provides a brief review of common Service-approved data standards and links to the full list.

### Section 4: Data Sharing, Security, and Preservation

**Short-term storage, backup, and security**:  The primary causes of data loss are human error and hardware corruption; therefore, it is critically important that short-term data storage is backed up and secure. Identify here where the short-term, primary working project and data files will be located. This is NOT the Regional Data Repository (RDR) and is NOT your computer hard drive. This is a shared digital storage location with a backup and recovery protocol in place.  Good options include OneDrive, Teams file folders, or a network drive. If there are internet connectivity concerns, working files may be stored on your computer hard drive for ease of use or on an additional external hard drive as a back-up, but must also be maintained in an accessible Service location.

{% hint style="warning" %}
We highly recommend mirroring the RDR files top-level folder structure for your short-term storage since it will provide continuity across storage platforms. In this way, anyone can find items within other project, data, and metadata file folders.
{% endhint %}

Also indicate how frequently the primary, short-term storage location backup is done during the project. Choose from a drop-down list of options, or choose "other" and describe the backup frequency in the input box.  Be sure to implement this!

If there are any data access restrictions that should apply to the short-term file storage, please detail those restrictions at the bottom of this section.&#x20;

**Regional Data Repository:** The Regional Data Repository (RDR) was set up as an organized, read-only, long-term storage for authoritative preservation of project data and products for the Alaska region. From the RDR, copies of data and metadata may be shared, as appropriate, to other federal or external repositories and catalogs. Enter the URL location of the Regional Data Repository for your project, if one already exists. If one does not currently exist, enter an abbreviated project title that you would like to use for your RDR folder. Check the box to confirm if you will be using the RDR as the authoritative long-term storage location for your project data assets.

**Public Data Sharing Repositories:** A copy of the data and metadata may be shared with other federal or external catalogs or repositories. List those desired publicly accessible options here. Use the plus (+) to add additional rows to the table.

Note that Refuge staff are required to preserve data assets in ServCat.

![Public Data Sharing Repositories table from the regional DMP template. The blue arrow indicates the plus (+) button for adding additional rows to the table.  ](<../../../.gitbook/assets/image (76).png>)

{% hint style="info" %}
Because the Service does not currently have officially approved repositories, the RDR serves as an authoritative staging and secure preservation location for regional project, data assets, products, and associated metadata that are readily available for distribution to other catalogs and repositories, as appropriate.
{% endhint %}

### Section 5: Records Schedule and Disposition

Permanent electronic records must be transferred to the National Archive according to the records schedules. The most relevant records disposition schedules for biological data collection are presented as dropdown options. Choose the records schedule that best classifies your data type, then visit the[ Combined USFWS Disposition Manual (2006)](https://www.fws.gov/policy/a1283fw2.html) web link to select the record type and find your disposition schedule. Use the plus (+) button to add rows, if more than one record type applies.

{% hint style="warning" %}
Disposition Schedules are under review in 2022, and a new USFWS Disposition Manual will be forthcoming.
{% endhint %}

{% hint style="success" %}
Feel free to contact the Alaska Regional Records Expert Kyle Cahill (kyle\_cahill@fws.gov or (907)-786-3351) for assistance.
{% endhint %}

### Data Products

Complete a Digital Data Product and Physical Sample table for each data product that you expect to produce during your project. Note: the Physical Sample table is optional and for your own use. Data products may include tables, shapefiles, computer code, or reports. To add a table, click on the plus (+) button in in the lower right corner of the table.

{% hint style="info" %}
If using the regional machine-readable DMP template, the initiated metadata records will contain these project and product associations.
{% endhint %}

![Digital Data Product table can be duplicated by clicking on the plus (+) button indicated by the blue arrow.](<../../../.gitbook/assets/image (89).png>)

#### Digital Data Table

A data table should be completed for each digital data type (i.e., table, database, model, geospatial layer, or photo/video collection). The following are the DMP fields for digital data:

* **Product Title:** Enter the name or title of the data product.
* **Location URL:** Enter the location of the data resource. This is likely the short-term storage location of the file.&#x20;
* **Product History:** Check a box to indicate whether the data is a new product or a pre-existing data product. If metadata for the data product already exists, provide the URL for the location of the metadata.
* **Resource Type and Format:** Select the resource type for the data product from the drop-down list and then choose the appropriate data format from the next drop-down list of options.  If the format is not listed, choose 'other' and enter the format type in the input box. Refer to guidance on common open format types.
* **Description:** Describe the data product, including information on purpose of data and key attributes of the data collected.
* **Data Originators:** Indicate the name and email of the person(s) who collected the data. This may or may not be a point of contact listed above for the project team.  Use the blue plus (+) button to add additional entries.

![Add additional data producers by clicking the blue plus (+) button.](<../../../.gitbook/assets/image (50).png>)

* **Quality Assurances:** Briefly list the procedures and methods used to help prevent errors during data collection. These procedures may be detailed in project methods documents.
* **Quality Controls:**  Briefly list the procedures and methods used to review and ensure data is free of errors after collection. These procedures may be detailed in project methods documents.
* **Resource Requirements:** Briefly describe the resources needed, such as hardware, software, equipment, staff with specialized skills, or financial commitments, needed to maintain, store, and access this data product. Also, include the size of the storage space needed with units (i.e., MB, GB, TB, PB).
* &#x20;**Metadata Author:** Enter the name and email address for the person responsible for writing the metadata for the data product.
* **Data Restrictions:** Choose from the drop-down list to indicate whether the data is restricted.  In the majority of cases, data is open-access or unrestricted. If data restrictions apply, provide a brief justification.  _Note that restricted data still requires metadata_.
* **Supplemental Materials:** List any other products or supplementary materials with storage location needed to understand this data product. This may include relational diagrams, computer code, models, or pre-existing datasets from which this product was derived.
* **Spatial Extent:**  If the product spatial extent is the same as the project spatial extent, check the box. If the spatial extent is different, include the URL location of a extent file for the data product in the spatial extent description.

#### Physical Samples

Physical samples include any tangible items that will be collected in association with the project.  The collected items often include biological specimens such as feathers or fur, blood, feces, or carcasses. For example, deceased butterflies from a laboratory colony, fish scales for aging, feathers from bird surveys, hit-by-car carcasses, or mounts for outreach may constitute physical collections. Associating these physical samples with their data and parent project creates rich metadata and contributes to an inventory of the physical samples. The following are fields for the DMP physical samples:

* **Collection Name:** Enter a descriptive name or title for the physical sample collection.
* **Description:** Enter a description of the physical samples in the text box including the purpose  of the collected samples (e.g., blood collected for genetic research).
* **Labeling Standards:** Briefly describe how the samples were labeled, including the meaning of any codes or abbreviations used. &#x20;
* **Quality Assurance and Quality Control Procedures:** Briefly describe in the text box the quality procedures and methods used to collect and compile the data from the samples. Citations/links to technical reports, publications, and existing protocols may be included.
* **Storage Location and Conditions:** Identify the location of the physical samples and the conditions in which the samples must be stored.
* **Chain of Custody:** Briefly describe the chain of custody, controls, or transfer procedure of the physical samples.
* **Fate After Analysis:** Briefly describe the long-term storage or disposition plan for the physical samples.&#x20;
* **Data Products Derived:** Provide the name or description of data products that resulted from the collection of these physical samples.&#x20;
