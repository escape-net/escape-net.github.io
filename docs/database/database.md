---
layout: default
title: Database
nav_order: 3
has_children: true
permalink: /docs/database
---

**Joint database**
{: .label .label-red}

Both the WP2 and WP3 teams have been collaborating to build a secure data management and analysis platform where only authorized users of the ESCAPE-NET project are allowed to use data without risk of either unauthorized changes or unauthorized utilization of the shared data resources.

The ESCAPE-NET database BC\|GENOME and the surrounding analysis environment (Jupyter Notebook) is located on a private "secure cloud" server hosted on [Computerome](http://www.computerome.dtu.dk/), the Danish National Supercomputer for Life Sciences. The server is accessed through a [Linux Virtual Delivery Agent (VDA)](https://docs.citrix.com/en-us/linux-virtual-delivery-agent/current-release.html) that provides access to a virtual desktop (CentOS 7). The BC\|GENOME graphical user interface and the Jupyter environments are accessed through the web browser on the secure virtual desktop. The server is network isolated, meaning that data can only get in or out of the server by the help of the data manager and dedicated Computerome personnel. Data management functionalities are restricted inside the virtual desktop: This means users are not able to download result files, graphs and metadata derived from research data without control of the BC\|GENOME administrators and data manager.
