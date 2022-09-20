---

[comment]: # Do not change the layout
layout: project

[comment]: # Project title
title: "ProxyStore"

[comment]: # The image should be added to images/projects/
image: "proxystore.png"

[comment]: # List of project members.
people: ["Greg Pauloski", "Valerie Hayot-Sasson", "Kyle Chard", "Ian Foster"]

[comment]: # List of project tags. Remove all that do not apply
hashtags: [
    "Cloud and Edge Computing",
    "Compute Frameworks",
]

[comment]: # GitHub link or blank if not applicable
github: "https://github.com/proxystore"

[comment]: # Website/homepage/docs or blank if not applicable
website: "https://proxystore.readthedocs.io/en/latest/"

[comment]: # One-line teaser/description for front page/project page
teaser: "A data fabric for high-performance, multi-site workloads facilited by transparent object proxies."

[comment]: # Set to false if the project is no longer maintained
active: true

---

ProxyStore provides a unique interface to object stores through transparent object proxies that is designed to simplify the use of object stores for transferring large objects in distributed applications.
ProxyStore is backed by a suite of object storage backends including shared file systems, Redis, and KeyDB and custom backends that enable multi-site workloads and fast intra-site communication via RDMA.

ProxyStore’s goals are to:
- **Improve productivity.** ProxyStore enables easy decoupling of communication from the rest of the code, allowing developers to focus on functionality and performance.
- **Improve compatibility.** Consumers of data can be agnostic to the communication method because object proxies handle the communication behind the scenes.
- **Improve performance.** Transport methods and object stores can be changed at runtime to optimal choices for the given data without the consumers being aware of the change.


#### Publications
<!-- List the full citations for each paper here with links to where to find it. -->
Available soon.

#### Funding and Acknowledgements
<!-- List any funding sources or other acknowledgements here otherwise remove -->
Available soon.
