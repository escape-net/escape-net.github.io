---
layout: default
title: Secure transfer of transformed cohort data
parent: Database
nav_order: 3
---

This document describes how to securely transfer transformed cohort data to RegionH for upload into the joint database.

1. Before sending your data please make sure that the data has been properly transformed to the ESCAPE-NET format and fill in the data transformation quality control checklist. See [qc checklist for case cohorts](/texts/EscN QC checklist case v13112019.docx) and [qc checklist for longitudinal cohorts](/texts/EscN QC checklist longitudinal vMB_SK14062019.docx).

2. When the transformation is done and you are ready to upload, please follow the steps below to securely transfer data.
    1. Create an encrypted 7z folder with the .csv files for each table. If you have any doubts about this step, see [How to Create Encrypted Zip or 7z Archives on Any Operating System](https://www.howtogeek.com/203590/how-to-create-secure-encrypted-zip-or-7z-archives-on-any-operating-system/).
    2. Contact data manager and you will get a user account on a SFTP server, allowing you to move the data securely.
    3. To connect to the server you will need to download a SFTP client software. Please refer to [WinSCP](https://winscp.net/eng/download.php) for Windows users and [FileZilla](https://filezilla-project.org/) for Mac or Linux users.

3. Data manager will control the received data and move it to the secure environment, hosting the joint database and upload the data into the database.
