---
description: Updated January 2022
---

# Metadata Records

### <mark style="color:blue;">Main Tab</mark>

#### Basic Information

| Field  | Project                                                                                    |  Product                                                                                   |
| ------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| Title  | Required                                                                                   | Required                                                                                   |
| Status | Required; must be one of '**completed**', '**onGoing**', '**proposed'**, or '**accepted**' | Required; must be one of '**completed**', '**onGoing**', '**proposed**', or '**accepted**' |

#### **Resource Types**

| Field         | Project                         | Product                                                                                                                               |
| ------------- | ------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| Resource Type | Required; must be '**project**' | Required; must not be '**project**' or '**product'**. Choose a more specific product type (e.g. '**tabularDataset**', '**document**') |

#### Point of Contact

See guidance for required and best practice selections for the "Role" field in the Point of Contact section. Each role is required to have an associated contact person under the Contact field.

| Role               | Project                      | Product                      | Notes                                                                                           |
| ------------------ | ---------------------------- | ---------------------------- | ----------------------------------------------------------------------------------------------- |
| **owner**          | Required                     | Best Practice                | Use this role for Data Trustee                                                                  |
| **pointOfContact** | Required                     | Required                     | Use this role for Data Steward. Can also be used to identify an organizational point of contact |
| **custodian**      | Required                     | Required                     | Use this role for Data Custodian                                                                |
| **originator**     |                              | Required                     | Use this role for Data Originator/Producer                                                      |
| **administrator**  | Best Practice                | Best Practice                |                                                                                                 |
| **contributor**    | Best Practice, if applicable | Best Practice, if applicable | Role used to identify partner organizations                                                     |

#### Citation&#x20;

| Field                        | Project                                                                                                                                  |  Product                                                                                                                                                                                        |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Title                        | Required (auto-populated)                                                                                                                | Required (auto-populated)                                                                                                                                                                       |
| Dates/Date Type              | Required: one of '**creation**' or '**dateUpdated**'                                                                                     | <p>Required: '<strong>creation</strong>', '<strong>lastUpdated</strong>' (if applicable);<br>Best Practice, if applicable: '<strong>published</strong>', '<strong>acquisition</strong>'<br></p> |
| Responsible Parties/Role     | <p>Required: '<strong>publisher</strong>'<br>Best Practice: '<strong>principalInvestigator</strong>', '<strong>contributor</strong>'</p> | <p>Required: '<strong>publisher</strong>'<br>Best Practice: '<strong>contributor</strong>'</p>                                                                                                  |
| Responsible Parties/Contacts | Required                                                                                                                                 | Required                                                                                                                                                                                        |
| Online Resource/Name         | Best Practice, if applicable                                                                                                             |                                                                                                                                                                                                 |
| Online Resource/URI          | Best Practice, if applicable                                                                                                             |                                                                                                                                                                                                 |
| Identifier/Identifier        | Best Practice, if applicable: a Digital Object Identifier (DOI)                                                                          | Best Practice, for published papers: a Digital Object Identifier (DOI)                                                                                                                          |
| Identifier/Namespace         | Best Practice, if applicable: '**DOI**'                                                                                                  | Best Practice, for published papers: '**DOI**'                                                                                                                                                  |

#### Description

| Field    | Project  | Product  |
| -------- | -------- | -------- |
| Abstract | Required | Required |

#### Time Period

| Field      | Project                 | Product                 |
| ---------- | ----------------------- | ----------------------- |
| Start Date | Required                | Required                |
| End Date   | Required, if applicable | Required, if applicable |

### <mark style="color:blue;">Metadata Tab</mark>

#### Basic Information

| Field           | Project                                      |  Product                                     |
| --------------- | -------------------------------------------- | -------------------------------------------- |
| Metadata Status | Required                                     | Required                                     |
| Date            | Required: '**creation**' or '**lastUpdate**' | Required: '**creation**' or '**lastUpdate**' |

#### Metadata Contact

See guidance for required and best practice selections for the "Role" field in the Metadata Point of Contact section. Each role is required to have an associated contact person under the Contact field.

| Role               | Project       | Product       |
| ------------------ | ------------- | ------------- |
| **author**         | Required      | Required      |
| **pointOfContact** | Required      | Required      |
| **publisher**      | Best Practice | Best Practice |

### <mark style="color:blue;">Keywords Tab</mark>

The following are required and best practice keyword thesauri. At least one keyword is required from each thesaurus used.

| Keyword Thesaurus         | Project       |  Product      |
| ------------------------- | ------------- | ------------- |
| **GCMD Science Keywords** | Required      | Required      |
| **ISO Topic Category**    | Best Practice | Best Practice |

### <mark style="color:blue;">Taxonomy Tab</mark>

If applicable, taxa associated with the project must be identified using the Integrated Taxonomic Information System (ITIS) taxonomic system.

### <mark style="color:blue;">Extent Tab</mark>

If applicable, it is best practice to describe extent with at least one of the following fields:

| Field                          | Project       | Product       |
| ------------------------------ | ------------- | ------------- |
| Extent Description             | Best Practice | Best Practice |
| Geographic Extent/Bounding Box | Best Practice | Best Practice |
| Geographic Extent/Features     | Best Practice | Best Practice |
| Geographic Extent/Description  | Best Practice | Best Practice |

### <mark style="color:blue;">Distribution Tab</mark>

#### Distributors

| Field                                       | Project |  Product                                                    |
| ------------------------------------------- | ------- | ----------------------------------------------------------- |
| Role                                        |         | Required: '**distributor**'                                 |
| Contacts                                    |         | Required, must be an organization rather than an individual |
| Transfer Option/Transfer Size               |         | Best Practice                                               |
| Transfer Option/Online Transfer/Name        |         | Best Practice                                               |
| Transfer Option/Online Transfer/URI         | ****    | Required                                                    |
| Transfer Option/Online Transfer/Description |         | Best Practice                                               |
| Transfer Option/Online Transfer/Function    |         | Best Practice                                               |

### <mark style="color:blue;">Constraints Tab</mark>

If sections in the constraint tab are left blank, open access to data products is assumed.

| Field           | Project |  Product                               |
| --------------- | ------- | -------------------------------------- |
| Constraint Type |         | Required if constraints not left blank |

#### Legal

| Field              | Project |  Product                     |
| ------------------ | ------- | ---------------------------- |
| Access Constraints |         | Required, **** if applicable |
| Use Constraints    |         | Required, if applicable      |
| Other Constraints  |         | Required, if applicable      |

#### Security

| Field          | Project |  Product                |
| -------------- | ------- | ----------------------- |
| Classification |         | Required, if applicable |

### <mark style="color:blue;">Associations Tab</mark>

If an association exists, basic record information that is required from the Main tab must be filled out for the associated resource in addition to Association Type.

| Field            | Project                                      | Product                 |
| ---------------- | -------------------------------------------- | ----------------------- |
| Association Type | Required, if applicable: '**parentProject**' | Required, if applicable |

### <mark style="color:blue;">Dictionaries Tab</mark>

If a data product is a tabular dataset, it must have a data dictionary associated with it. See [Dictionary Records](dictionary-records.md) for more information.
