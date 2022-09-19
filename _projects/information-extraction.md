---

layout: project

title: "Scientific Language Modeling and Information Extraction"

image: "info-extraction.png"

people: ["Zhi Hong", "Aswathy Ajith", "Greg Pauloski", "Eamon Duede", "Kyle Chard", "Ian Foster"]

tags: [
    "Machine Learning",
    "Materials Science"
]

teaser: "Data mining from literature with a foundational science-focused language model"

active: true

---

<!--
Add your project description below according to these guidelines.

 - Use Markdown syntax everywhere, not HTML!
 - Use active voice ("we")
 - Limit the intro paragraph to 3 sentences or less.
 - Keep the overall length under 3 paragraphs.
 - Bullet points are helpful for quickly understanding key points.
 - Add figures and additional links if relevant.

An example first paragraph:

 1. Sentence giving overall context, hinting at the problem we solve.
      "Most humans don't like to read long paragraphs and writing short
      ones takes thought."
 2. An explanation of how we fix it.
      "We made a simple template that you can follow for how to write one."
 3. A statement of impact.
      "Any Globus Labs member need only edit this template to make their
      science more accessible."
-->

Scientific articles have long been the primary means of disseminating scientific
discoveries. Valuable data and potentially ground-breaking insights have been collected 
and buried deep in the mountain of scientific publications over the centuries.
We strive to answer interesting and important questions in science by extracting
facts from publications and, in the process, have built a foundational large language
model for science.

Our previous works have focused on designing application-specific models and pipelines, which
has produced a polymer extraction model that outperformed a leading chemical extraction
toolkit by up to 50%, as measured by F1 score, as well as a druglike molecule extraction model
that found 3,591 molecules from COVID-19-related medical research that had not been previously
considered by Argonne’s computational screening research team.

Large Language Models (LLMs) has become of core of many NLP solutions in recent years
due to their flexibility and performance advantages over traditional machine learning methods.
Most publicly available pretrained LLMs are pretrained on general English
corpora such as news reports, wiki pages, and blogs, while scientific texts are usually neglected.
We have pretrained on the ScholarBERT and ScholarBERT-XL models on a corpus of 75 million
of scientific publications. Preliminary experimental results showed their strengths in identifying
disciplines corresponding to scientific named entities compared to general LLMs or domain-specific
LLMs.

#### Publications
<!-- List the full citations for each paper here with links to where to find it. -->
- Zhi Hong, J. Gregory Pauloski, Aswathy Ajith, Eamon Duede, Kyle Chard, and Ian Foster "[Accelerating Computational Social Science with ScholarBERT.](https://www.ic2s2.org/program)" 8th International Conference on Computational Social Science, 2022.
- Zhi Hong, Aswathy Ajith, Gregory Pauloski, Eamon Duede, Carl Malamud, Roger Magoulas, Kyle Chard, and Ian Foster. ”[ScholarBERT: Bigger is Not Always Better.](https://arxiv.org/abs/2205.11342)” arXiv preprint arXiv:2205.11342 (2022
- Zhi Hong, Logan Ward, Kyle Chard, Ben Blaiszik, and Ian Foster. "[Challenges and Advances in Information Extraction From Scientific Literature: A Review.](https://link.springer.com/article/10.1007/s11837-021-04902-9)" Accepted to The Journal of The Minerals, Metals \& Materials Society (JOM). 2021.
- Zhi Hong, J. Gregory Pauloski, Logan Ward, Kyle Chard, Ben Blaiszik, and Ian Foster. "[Models and Processes to Extract Drug-like Molecules from Natural Language Text.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8435623/)" Frontiers in Molecular Biosciences: 826. 2021.
- Zhi Hong, Roselyne Tchoua, Kyle Chard, Ian Foster, "[SciNER: Extracting Named Entities from Scientific Literature.](https://link.springer.com/chapter/10.1007/978-3-030-50417-5_23)". International Conference on Computational Science, 308-321. 2020.
- Tchoua, Roselyne, Zhi Hong, Debra Audus, Shrayesh Patel, Logan Ward, Kyle Chard, Juan De Pablo, and Ian Foster. "[Developing databases for polymer informatics.](https://meetings.aps.org/Meeting/MAR20/Session/G34.7)" Bulletin of the American Physical Society 65 (2020).

#### Funding and Acknowledgements
<!-- List any funding sources or other acknowledgements here otherwise remove -->
This work was performed under award 70NANB19H005 from U.S. Department of Commerce, 
National Institute of Standards and Technology as part of the Center for 
Hierarchical Materials Design (CHiMaD); by the U.S. Department of Energy under 
contract DE-AC02-06CH11357; and by U.S. National Science Foundation awards DGE-2022023 
and OAC-2106661. This research used resources of the University of Chicago Research Computing Center and
the Argonne Leadership Computing Facility, a DOE Office of Science User Facility supported under Contract DE-AC02-06CH11357.
