---
layout: project
title:  "Draining the Data Swamp"
image: "klimaticScreenshot.png"
featured: false
teaser: "Turning Data Swamps into Data Lakes"
description: "Techniques for extracting rich metadata from heterogeneous scientific data repositories."
---

As scientific data repositories and file systems continue to explode in size without regard for discoverability, scientists are maddened by
their inability to locate, organize, and interpret data. To mitigate the effects of high-velocity data expansion and disorganized data
repositories, we have developed Skluma---an automated metadata extraction service that extracts rich content- and context-based metadata from
files. Such metadata include aggregate data derived from embedded structured data; named
entities and latent topics buried within free-text documents; and content encoded in images (e.g., locations
represented in a map). Skluma applies advanced methods to determine file types, dynamically prioritizes and then execute extractors, and is
able to associate contextual metadata with files based on their relationship to other files. The derived metadata, represented in JSON, represents probabilistic knowledge of each file which
may be subsequently used for discovery or organization.
Skluma's architecture uses cloud-hosted containers
among other cloud services to create and execute dynamic extraction workflows on massive numbers of files. It is designed to be both modular
and extensible---allowing users to develop their own specialized metadata extractors (in any language).
%searchable Globus Search index.
Thus far we have tested Skluma on local filesystems, remote FTP-accessible servers, and publicly-accessible
Globus endpoints. We have demonstrated the efficacy of Skluma by applying it to a scientific carbon dioxide repository containing more
than 500,000 files.


Publications

- [Skluma: A Statistical Learning Pipeline for Taming Unkempt Data Repositories](https://www.researchgate.net/publication/317352352_Skluma_A_Statistical_Learning_Pipeline_for_Taming_Unkempt_Data_Repositories). SSDBM, 2017.

