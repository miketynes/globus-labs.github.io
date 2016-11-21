---
layout: project
title:  "Klimatic"
image: "extraction.png"
featured: false
teaser: "We are creating a searchable index of disparate geospatial data."
description: "Architecting a solution to crawl, index, integrate, and distribute geo-spatial data at scale."
---

New sensors, simulation models, and observational programs 
are producing a veritable deluge of high quality
geospatial data. However, these data are often hard for researchers 
to access, being stored in independent silos that are
distributed across many locations (e.g., consortium registries,
institutional repositories, and personal computers), accessible
via different protocols, represented in different formats (e.g.,
NetCDF, CSV) and types (e.g., vector, raster), and are in
general, difficult to discover, integrate, and use. These
challenges are none more evident than in environmental and
climate science. Here, vast collections of data are stored in
dark, heterogeneous repositories distributed worldwide.

We aspire to make these large quantities of geospatial
data accessible by creating the virtual data lake, a cached
subset of a data lake paired with additional metadata for
non-cached datasets. A data lake is “a centralized repository
containing virtually inexhaustible amounts of raw (or minimally 
curated) data that is readily made available anytime to
anyone authorized to perform analytical activities”. Such
a system allows for the local caching of raw data in a stan-
dardized format, making integration and distribution more
efficient at query-time. A geospatial data lake should allow
for the straightforward alignment of spatial and time-based
variables, and be able to manage and integrate heterogeneous
data formats. Given the huge quantity of geospatial data, we
extend the data lake model to encompass a metadata index
of all processed data and the use of our virtual lake as a
cache for popular raw data. This approach allows for the
tracking of less popular datasets without giving up valuable
performance and space availability for oft-accessed data.

To explore these ideas, we have prototyped Klimatic, a
system for the automated collection, indexing, integration,
and distribution of big geospatial data. Although there is
prior research in both geospatial metadata extraction and
data lakes, to the best of our knowledge this is the first
example of a centralized, searchable index across disparate
web-accessible resources, combined with a virtual lake cache
for raw data. We adopt a scalable crawling and metadata
extraction model, using a dynamic pool of Docker contain-
ers to discover and process files. Thus, we pave the way
for creation of a scalable system that has the capacity to scour
an increasing number of available resources for geospatial
data. To further reduce usage barriers, Klimatic supports the
integration of heterogeneous datasets (in both file type and
format) to match users’ queries, while also ensuring data
integrity.

Publications

- [Klimatic: A Virtual Data Lake for Harvesting and Distribution of Geospatial Data](http://conferences.computer.org/pdswdiscs/2016/papers/5216a031.pdf). 1st Joint International Workshop on Parallel Data Storage & Data Intensive Scalable Computing Systems (PDSW-DISCS), 2016. 

