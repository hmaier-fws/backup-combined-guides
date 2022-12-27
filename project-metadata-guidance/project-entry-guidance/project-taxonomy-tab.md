# Project Taxonomy Tab

Taxonomny is similar to Keywards and provides another way to improve search and discovery of the metadata within a metadata catalog. mdEditor Taxonomy automatically pulls in taxonomic information from ITIS ([Integrated Taxonomic Information System](https://www.itis.gov/)).

{% hint style="info" %}
Please note that this functionality in mdEditor is not intended to explore ITIS. It is a tool to add known taxonomic information to your metadata. If you want to explore ITIS, visit itis.gov to find detailed information.
{% endhint %}

**Taxonomy is required in cases where a species is the subject of the project or data asset.** The minimum requirements for valid Taxonomy Collection are a Taxonomic System plus one or more Taxonomic Classifications. To some extent, relevent taxonomy is up to the best judgement of the metadata author who can access the connection of the project to a specific species or other taxonomic group. For example, if a bear model was used to rank habitat for a prioritization product, but the final output is not relevant to bears any longer, then you probably do not need to add bear species in taxonomy.

{% hint style="info" %}
If you have existing species names in the keywords section, you do not need to delete them. Taxonomy is entered in a separate section from keywords in mdJSON.
{% endhint %}

## Taxonomic Systems

### ITIS (Required, if applicable)

ITIS stands for Integrated Taxonomic Information System, which is maintained by a [partnership](https://www.itis.gov/organ.html) of federal agencies. Search for the relevent authoritative taxonomy to the level known (Kingdom to subspecies). Each ITIS Taxonomy Collection requires at least one Taxonomic Classification.

## How to Add a Taxonomic System

(1) Click "Add Collection"

![](<../../.gitbook/assets/image (99).png>)

(2) From here, you can click "Add Taxa from ITIS" (from the right) directly without needing to choose the taxonomic system. This will be filled in for you automatically once you have added items from ITIS.

![](<../../.gitbook/assets/image (12).png>)

(3) Enter your search terms in the search box. You can type in a common name, scientific name, or TSN (Taxonomic Serial Number) assigned by ITIS. You can type in any level of taxonomy, not just species name (e.g., you can type in an order or class or genus). You can specify by Kingdom, if you like.

{% hint style="info" %}
If you haven’t used the search in a while (or ever) the ITIS API service might be asleep so it will take more time to load, but it should work more quickly after that.
{% endhint %}

{% hint style="info" %}
The status of the taxonomic classification is denoted in parentheses() after the TSN. ITIS may consider a classification "invalid" if the species was reclassified, for example. It is up to you whether you want to add invalid ITIS classifications to your metadata.
{% endhint %}

![](<../../.gitbook/assets/image (51).png>)

(4) Click "Add" for the search results that you would like included in your record and then click "Import Taxa." A message of successful import should appear at the bottom of your screen.

{% hint style="info" %}
&#x20;mdEditor will not to create duplicate entries of the same taxa if the same species is accidentally imported multiple times.
{% endhint %}

![](<../../.gitbook/assets/image (5).png>)

(5) Click "Back to Collection." You will see that it has added a taxonomic hierarchy and a Title to Taxonomic System (if you hadn’t already added one by hand). This completes the minimum requirements for taxonomy.

{% hint style="info" %}
You can click on any level of the taxonomic hierarchy to collapse the entries below that level.
{% endhint %}

![](<../../.gitbook/assets/image (55).png>)

(6) You can add additional information regarding the taxonomic information, if desired.

**Observers** can be added from your contacts if staff worked in the field or lab to identify species.

**General Scope** is a description of the range of taxa considered in the dataset or collection.

**Identification Procedure** should include a description of the methods used for taxonomic identification.

**Identification Completeness** should detail information regarding completeness and uncertainty of the identifications.

**Voucher** would be filling in with information about specimens you submitted to a museum or a storage facility where specimens are stored.  The museum or storage facility should be entered as a Contact. ([See Contact Entry Guidance](../contact-entry-guidance/)).

![Classification Blank entry boxes for General Scope, Identification procedure, and Completeness ](<../../.gitbook/assets/image (16).png>)

![Example voucher entry](<../../.gitbook/assets/image (39).png>)

<img src="../../.gitbook/assets/image (57).png" alt="" data-size="line">
