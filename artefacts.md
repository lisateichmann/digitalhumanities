# Digital Humanities Artifacts

# GAZETTEERS

# CURATORIAL STATEMENT

Extracting and mapping toponyms in fiction or non-fiction – especially historical texts – can be a challenging task. Place names might change over time, differ from language to language and also depend on text genre and period. Gazetteers are a useful resource for research in spatial humanities. Not only do they provide an academically well curated list of toponyms, but also serve as the basis of a mapping project. 
This entry aims at compiling some available, open source gazetteers for different languages (such as English and German) and tools to apply to a dataset such as a text corpus. Each artifact can ideally be used by someone who endeavors to extract and map place names in a given text.

# CURATED ARTIFACTS

## German Toponym Gazetteer

![barbaresigazetteer](https://user-images.githubusercontent.com/28898995/31368966-157d6dba-ad4f-11e7-89b6-eaad54bfe700.png)

* Artifact Type: gazetteer
* Source URL: https://github.com/adbar/toponyms
* Permissions: open source, CC BY-SA 4.0 license
* Creator and Affiliation: Adrien Barbaresi (Austrian Academy of Sciences, Austria)
* Tags: advanced prototype

Database of German toponyms compiled semi-automatically from Wikidata API and Geonames and Python code for the extraction of place names. The Gazzetteer includes both contemporary and historical spatial data to identify and extract toponyms in newspaper texts from "Die Fackel" (1899-1936). The registers consist of four toponym lists:
* 1. makro (45 entries) 
* 2. states (213 entries)
* 4. regions (1015 entries)
* 5. cities (6546 entries)
As opposed to NER and AI methods to extract place names from textual data, this gazetteer represents a highly curated dataset with the geographical focus on Europe. The accompanying Python script enables the extraction and disambiguation of place names from text. The output data can then be visualized with a mapping tool or GIS software.


## MoEML Gazetteer of Early Modern London

[! screenshot] (images/....jpg)

* Artifact Type: gazetteer
* Source URL: https://mapoflondon.uvic.ca/gazetteer_a.htm
* Permissions: Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)
* Creator and Affiliation: Janelle Jenstad et.al. (University of Victoria, Canada), Tye Landels-Gruenewald (Queen's University, Canada), et.al.
* Tags: advanced

MoEML is a gazetteer of 6500 London place names and has been created to map the English book trade by mining and geocoding the imprint lines of books printed in London between 1475 and 1640. As Jenstad et.al. [2017] mention, NER software did not proof to be feasible in extracting toponyms due to ambiguation issues. The extracted locations from the imprint line were then matched and manually compiled to the MoEML database. The XML/TEI conform dataset has six columns:
* 1. Variant Toponym
* 2. Authority Name
* 3. @xml:id
* 4. Agas Map Reference
* 5. Other Variant Names and Spellings
* 6. Location Type
The toponym data is tailored to include all possible variants of a place name which makes it searchable for a specific toponym, even if the spelling has changed over time. This gazetteer is therefore especially useful for historic data.

## TileMill

[! screenshot] (images/....jpg)

* Artifact Type: tool
* Source URL: https://tilemill-project.github.io/tilemill/
* Permissions: open source (BSD 3)
* Creator and Affiliation: Development Seed and Mapbox
* Tags: tool used

TileMill is an open source map design studio. It also features an interactive map and the possibility to export into a variety of formats and GIS programs. Furthermore, it is open for development within the open source community on github and includes an extensive documentation. It is a web based application and the installation and use of a GIS and graphics editor are necessary in order to work with TileMill. The application's site provides detailed instructions and explanations for the use of GIS and spatial data.
A possible use of this tool is to extract place names from text with a gazetteer and then visualize the data with TileMill. 

## Related Keywords: Mapping, Literary Geography, Spatial Humanities, Toponyms

## Related Materials
 * AAC – Austrian Academy Corpus (2007). AAC–FACKEL, Online
Version: “Die Fackel. Herausgeber: Karl Kraus, Wien 1899-
1936”. http://www.aac.ac.at/fackel
* Jenstad, J., ed. The Map of Early Modern London (MoEML). Available
at: http://mapoflondon.u vic.ca/ [Accessed 20 March
2017].

## Works Cited
* Barbaresi, Adrien. "Toponyms as Entry Points into a Digital Edition: Mapping The Torch (1899-1936)," in Digital Humanities 2017 conference abstracts, Montreal, Canada, August 8-11, 2017. https://dh2017.adho.org/abstracts/209/209.pdf
* Jenstad, Janelle Auriol; Landels-Gruenewald, Tye; Takeda, Joseph. "Mapping the STC with MoEML and DEEP," in Digital Humanities 2017 conference abstracts, Montreal, Canada, August 8-11, 2017. https://dh2017.adho.org/abstracts/461/461.pdf


