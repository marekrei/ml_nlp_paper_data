ML and NLP paper data
=======================

This repository contains the data crawled and processed for the post series on [ML and NLP publications](https://www.marekrei.com/blog/ml-and-nlp-publications-in-2019/).

The project was created by [Marek Rei](https://www.marekrei.com/) ([@MarekRei](https://twitter.com/MarekRei)). The country annotation was contributed by [Jonas Pfeiffer](https://pfeiffer.ai/) ([@PfeiffJo](https://twitter.com/PfeiffJo)) and [Andrew Caines](https://www.cl.cam.ac.uk/~apc38/) ([@cainesap](https://twitter.com/cainesap)).


Conference proceedings
--------------------------

The *papers* directory contains json files for each of the crawled conferences. Take a look inside to see the available metadata.


Country annotation
--------------------------

*annotated_orgs.tsv* contains the following columns in tab-separated format:

* id
* org_name - the name of the organization, as crawled
* paper_count - the number of papers that matched that name, after initial processing
* is_org - manually annotated field, indicating whether this is an actual organization or crawling noise
* canonical_org_name - a canonical name for this organization, to match together different versions
* country - manually annotated country name for each organization
* example1 - an example paper where this organization was crawled from
* example2 - another example
* example3 - another example


License
-------------------------

This dataset is made available under the CC BY-NC 4.0 license.

