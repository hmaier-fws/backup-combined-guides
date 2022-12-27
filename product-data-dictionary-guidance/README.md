# Product Data Dictionary Guidance

The Product Data Dictionary Guidance section will cover how to create a Dictionary record for a one or more products.

Data dictionaries define the characteristics of attributes that make up an entity. A single data dictionary can describe the attributes of a single table or a collection of tables, like a database.&#x20;

{% hint style="info" %}
An **Entity** defines the structure of a discrete data object, such as a table. An **Attribute** is a unit of information describing a variable (column in a table). A **Domain** is a list of permissible values used to constrain an attribute's value. A **Domain Item** is a single permissible value for an attribute.
{% endhint %}

Like Contacts, mdEditor Dictioanry records are created separately from Product records. A Dictionary record is linked to a Product record in the [Product Dictionaries Tab](../product-metadata-guidance/product-dictionaries-tab.md)**.** Dictionaries can reused and linked to mulitple products.

{% hint style="warning" %}
A data dictionary is required for a tabular dataset (a single table or a database). This includes shapefile attributes.
{% endhint %}

## Edit a Data Dictionary

### Import an Existing Data Dictionary

If you are updating an existing metadata record, you should import the mdEditor mdJSON file from the project's folder in the Regional Data Repository. Learn how to import files into mdEditor on the [Import ](broken-reference)page.&#x20;

### Create a New Data Dictionary

1. Create a new Dictionary record by clicking the plus (**+**) sign by **Dictionaries** in the left-hand menu.
2. Give the dictionary a **Title**. Meaningful titles help link a data dictionary to its product(s). Choose "tabularDataset" as the **Dictionary Subject.** Click Save.
3. Fill out the metadata information for the following tabs.
   * Dictionary Main Tab
   * Dictionary Citation Tab
   * Dictionary Domains Tab
   * Dictionary Entities Tab
4. Associate the dictionary with applicable product(s) in the Product Dictionaries Tab.

{% hint style="info" %}
The **** [**mdJSONdictio R package**](https://hdvincelette.github.io/mdJSONdictio/) **** is available to help build and translate mdEditor Dictionary records. This tool utilizes a [tabular data dictionary template](https://hdvincelette.github.io/mdJSONdictio/articles/02\_Dictionary\_Template.html) which can serve as a human-readable reference while creating Dictionary records. The mdJSONdictio function`build.mdJSON()`can also translate these tabular data dictionaries to mdJSON, which can be subsequently imported to mdEditor as Dictionary records with data table attributes already defined. To learn more, see [Introduction to mdJSONdictio](https://hdvincelette.github.io/mdJSONdictio/articles/01\_Intro\_mdJSONdictio.html) and the associated articles.
{% endhint %}
