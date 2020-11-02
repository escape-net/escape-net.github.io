---
layout: default
title: Importing data tables from the joint database into SAS
parent: Jupyter Notebook
nav_order: 4
---

**Importing data tables from the joint database into SAS**
{: .label .label-red}

To import data tables from the joint database and into a SAS notebook, the user must first export the data from within the BC\|GENOME browsers.

To do so, click on the desired dataset (can also be a subset of datasets) and select "Export tools" as pictured below.

![export1](/figs/export1.png)

Choose "text - Plaintext data"

![export2](/figs/export2.png)

and select the desired Converter options. Lastly click "Export Data".

![export3](/figs/export3.png)

Finally, the exported dataset can be imported into a SAS notebook as pictured below.

![import1](/figs/import1.png)


The exported data files can be found under **bcos_results/jobid\*/filename.txt\***

**jobid\*** can be found in BC\|GENOME under "DATA MANAGEMENT" and "RESULTS ARCHIVE "

![jobiddsd](/figs/jobid.png)

**filename.txt\*** can be found by clicking on the desired jobid folder.

![filename](/figs/filename.png)
