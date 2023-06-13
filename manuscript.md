---
title: The Open Pediatric Cancer Project
keywords:
- pediatric cancer
- reproducibility
- open science
- classification
- somatic variation
lang: en-US
date-meta: '2023-06-13'
author-meta:
- Eric Wafula
- Krutika S. Gaonkar
- Run Jin
- Komal S. Rathi
- Yuankun Zhu
- Bailey K. Farrow
- Daniel P. Miller
- Mariarita Santi
- Adam A. Kraya
- Xiaoyan Huang
- Bo Zhang
- Brian M. Ennis
- Ryan J. Corbett
- Sharon J. Diskin
- Nicholas Van Kuren
- Noel Coleman
- Christopher Blackden
- Jennifer L. Mason
- Saksham Phul
- Miguel A. Brown
- Adam C. Resnick
- Jo Lynne Rokita^
header-includes: |-
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta name="dc.title" content="The Open Pediatric Cancer Project" />
  <meta name="citation_title" content="The Open Pediatric Cancer Project" />
  <meta property="og:title" content="The Open Pediatric Cancer Project" />
  <meta property="twitter:title" content="The Open Pediatric Cancer Project" />
  <meta name="dc.date" content="2023-06-13" />
  <meta name="citation_publication_date" content="2023-06-13" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Eric Wafula" />
  <meta name="citation_author_institution" content="Department of Bioinformatics and Health Informatics, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_orcid" content="0000-0001-8073-3797" />
  <meta name="citation_author" content="Krutika S. Gaonkar" />
  <meta name="citation_author_institution" content="Center for Data-Driven Discovery in Biomedicine, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_institution" content="Division of Neurosurgery, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_institution" content="Department of Bioinformatics and Health Informatics, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_orcid" content="0000-0003-0838-2405" />
  <meta name="twitter:creator" content="@aggokittu" />
  <meta name="citation_author" content="Run Jin" />
  <meta name="citation_author_institution" content="Center for Data-Driven Discovery in Biomedicine, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_institution" content="Division of Neurosurgery, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_orcid" content="0000-0002-8958-9266" />
  <meta name="twitter:creator" content="@runjin" />
  <meta name="citation_author" content="Komal S. Rathi" />
  <meta name="citation_author_institution" content="Center for Data-Driven Discovery in Biomedicine, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_institution" content="Department of Bioinformatics and Health Informatics, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_orcid" content="0000-0001-5534-6904" />
  <meta name="twitter:creator" content="@komalsrathi" />
  <meta name="citation_author" content="Yuankun Zhu" />
  <meta name="citation_author_institution" content="Center for Data-Driven Discovery in Biomedicine, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_institution" content="Division of Neurosurgery, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_orcid" content="0000-0002-2455-9525" />
  <meta name="twitter:creator" content="@zhuyuankun" />
  <meta name="citation_author" content="Bailey K. Farrow" />
  <meta name="citation_author_institution" content="Center for Data-Driven Discovery in Biomedicine, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_institution" content="Division of Neurosurgery, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_orcid" content="0000-0001-6727-6333" />
  <meta name="citation_author" content="Daniel P. Miller" />
  <meta name="citation_author_institution" content="Center for Data-Driven Discovery in Biomedicine, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_institution" content="Division of Neurosurgery, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_orcid" content="0000-0002-2032-4358" />
  <meta name="citation_author" content="Mariarita Santi" />
  <meta name="citation_author_institution" content="Department of Pathology and Laboratory Medicine, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_institution" content="Department of Pathology and Laboratory Medicine, University of Pennsylvania Perelman School of Medicine, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_orcid" content="0000-0002-6728-3450" />
  <meta name="citation_author" content="Adam A. Kraya" />
  <meta name="citation_author_institution" content="Center for Data-Driven Discovery in Biomedicine, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_institution" content="Division of Neurosurgery, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_orcid" content="0000-0002-8526-5694" />
  <meta name="citation_author" content="Xiaoyan Huang" />
  <meta name="citation_author_institution" content="Center for Data-Driven Discovery in Biomedicine, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_institution" content="Division of Neurosurgery, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_orcid" content="0000-0001-7267-4512" />
  <meta name="citation_author" content="Bo Zhang" />
  <meta name="citation_author_institution" content="Center for Data-Driven Discovery in Biomedicine, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_institution" content="Division of Neurosurgery, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_orcid" content="0000-0002-0743-5379" />
  <meta name="citation_author" content="Brian M. Ennis" />
  <meta name="citation_author_institution" content="Center for Data-Driven Discovery in Biomedicine, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_institution" content="Division of Neurosurgery, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_orcid" content="0000-0002-2653-5009" />
  <meta name="citation_author" content="Ryan J. Corbett" />
  <meta name="citation_author_institution" content="Center for Data-Driven Discovery in Biomedicine, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_institution" content="Division of Neurosurgery, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_orcid" content="0000-0002-3478-0784" />
  <meta name="citation_author" content="Sharon J. Diskin" />
  <meta name="citation_author_institution" content="Division of Oncology, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_institution" content="Department of Pediatrics, University of Pennsylvania, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_orcid" content="0000-0002-7200-8939" />
  <meta name="twitter:creator" content="@sjdiskin" />
  <meta name="citation_author" content="Nicholas Van Kuren" />
  <meta name="citation_author_institution" content="Center for Data-Driven Discovery in Biomedicine, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_institution" content="Division of Neurosurgery, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_orcid" content="0000-0002-7414-9516" />
  <meta name="citation_author" content="Noel Coleman" />
  <meta name="citation_author_institution" content="Center for Data-Driven Discovery in Biomedicine, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_institution" content="Division of Neurosurgery, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_orcid" content="0000-0001-6454-1285" />
  <meta name="citation_author" content="Christopher Blackden" />
  <meta name="citation_author_institution" content="Center for Data-Driven Discovery in Biomedicine, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_institution" content="Division of Neurosurgery, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author" content="Jennifer L. Mason" />
  <meta name="citation_author_institution" content="Center for Data-Driven Discovery in Biomedicine, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_institution" content="Division of Neurosurgery, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="twitter:creator" content="@jenn0307" />
  <meta name="citation_author" content="Saksham Phul" />
  <meta name="citation_author_institution" content="Center for Data-Driven Discovery in Biomedicine, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_institution" content="Division of Neurosurgery, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_orcid" content="0000-0002-2771-2572" />
  <meta name="twitter:creator" content="@migbro" />
  <meta name="citation_author" content="Miguel A. Brown" />
  <meta name="citation_author_institution" content="Center for Data-Driven Discovery in Biomedicine, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_institution" content="Division of Neurosurgery, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_orcid" content="0000-0001-6782-1442" />
  <meta name="twitter:creator" content="@migbro" />
  <meta name="citation_author" content="Adam C. Resnick" />
  <meta name="citation_author_institution" content="Center for Data-Driven Discovery in Biomedicine, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_institution" content="Division of Neurosurgery, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_orcid" content="0000-0003-0436-4189" />
  <meta name="twitter:creator" content="@adamcresnick" />
  <meta name="citation_author" content="Jo Lynne Rokita^" />
  <meta name="citation_author_institution" content="Center for Data-Driven Discovery in Biomedicine, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_institution" content="Division of Neurosurgery, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_institution" content="Department of Bioinformatics and Health Informatics, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_orcid" content="0000-0003-2171-3627" />
  <meta name="twitter:creator" content="@jolynnerokita" />
  <link rel="canonical" href="https://d3b-center.github.io/OpenPedCan-methods/" />
  <meta property="og:url" content="https://d3b-center.github.io/OpenPedCan-methods/" />
  <meta property="twitter:url" content="https://d3b-center.github.io/OpenPedCan-methods/" />
  <meta name="citation_fulltext_html_url" content="https://d3b-center.github.io/OpenPedCan-methods/" />
  <meta name="citation_pdf_url" content="https://d3b-center.github.io/OpenPedCan-methods/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://d3b-center.github.io/OpenPedCan-methods/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://d3b-center.github.io/OpenPedCan-methods/v/4718374200b2c101a255edda327d4e3f77e6e878/" />
  <meta name="manubot_html_url_versioned" content="https://d3b-center.github.io/OpenPedCan-methods/v/4718374200b2c101a255edda327d4e3f77e6e878/" />
  <meta name="manubot_pdf_url_versioned" content="https://d3b-center.github.io/OpenPedCan-methods/v/4718374200b2c101a255edda327d4e3f77e6e878/manuscript.pdf" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />
  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />
  <meta name="theme-color" content="#ad1457" />
  <!-- end Manubot generated metadata -->
bibliography:
- content/manual-references.json
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
manubot-clear-requests-cache: false
...






<small><em>
This manuscript
([permalink](https://d3b-center.github.io/OpenPedCan-methods/v/4718374200b2c101a255edda327d4e3f77e6e878/))
was automatically generated
from [d3b-center/OpenPedCan-methods@4718374](https://github.com/d3b-center/OpenPedCan-methods/tree/4718374200b2c101a255edda327d4e3f77e6e878)
on June 13, 2023.
</em></small>

## Authors



+ **Eric Wafula**<br>
    ![ORCID icon](images/orcid.png){.inline_icon}
    [0000-0001-8073-3797](https://orcid.org/0000-0001-8073-3797)
  <br>
  <small>
     Department of Bioinformatics and Health Informatics, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA
  </small>

+ **Krutika S. Gaonkar**<br>
    ![ORCID icon](images/orcid.png){.inline_icon}
    [0000-0003-0838-2405](https://orcid.org/0000-0003-0838-2405)
  <br>
  <small>
     Center for Data-Driven Discovery in Biomedicine, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA; Division of Neurosurgery, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA; Department of Bioinformatics and Health Informatics, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA
  </small>

+ **Run Jin**<br>
    ![ORCID icon](images/orcid.png){.inline_icon}
    [0000-0002-8958-9266](https://orcid.org/0000-0002-8958-9266)
  <br>
  <small>
     Center for Data-Driven Discovery in Biomedicine, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA; Division of Neurosurgery, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA
  </small>

+ **Komal S. Rathi**<br>
    ![ORCID icon](images/orcid.png){.inline_icon}
    [0000-0001-5534-6904](https://orcid.org/0000-0001-5534-6904)
  <br>
  <small>
     Center for Data-Driven Discovery in Biomedicine, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA; Department of Bioinformatics and Health Informatics, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA
  </small>

+ **Yuankun Zhu**<br>
    ![ORCID icon](images/orcid.png){.inline_icon}
    [0000-0002-2455-9525](https://orcid.org/0000-0002-2455-9525)
  <br>
  <small>
     Center for Data-Driven Discovery in Biomedicine, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA; Division of Neurosurgery, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA
  </small>

+ **Bailey K. Farrow**<br>
    ![ORCID icon](images/orcid.png){.inline_icon}
    [0000-0001-6727-6333](https://orcid.org/0000-0001-6727-6333)
  <br>
  <small>
     Center for Data-Driven Discovery in Biomedicine, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA; Division of Neurosurgery, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA
  </small>

+ **Daniel P. Miller**<br>
    ![ORCID icon](images/orcid.png){.inline_icon}
    [0000-0002-2032-4358](https://orcid.org/0000-0002-2032-4358)
  <br>
  <small>
     Center for Data-Driven Discovery in Biomedicine, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA; Division of Neurosurgery, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA
  </small>

+ **Mariarita Santi**<br>
    ![ORCID icon](images/orcid.png){.inline_icon}
    [0000-0002-6728-3450](https://orcid.org/0000-0002-6728-3450)
  <br>
  <small>
     Department of Pathology and Laboratory Medicine, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA; Department of Pathology and Laboratory Medicine, University of Pennsylvania Perelman School of Medicine, Philadelphia, PA, 19104, USA
  </small>

+ **Adam A. Kraya**<br>
    ![ORCID icon](images/orcid.png){.inline_icon}
    [0000-0002-8526-5694](https://orcid.org/0000-0002-8526-5694)
  <br>
  <small>
     Center for Data-Driven Discovery in Biomedicine, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA; Division of Neurosurgery, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA
  </small>

+ **Xiaoyan Huang**<br>
    ![ORCID icon](images/orcid.png){.inline_icon}
    [0000-0001-7267-4512](https://orcid.org/0000-0001-7267-4512)
  <br>
  <small>
     Center for Data-Driven Discovery in Biomedicine, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA; Division of Neurosurgery, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA
  </small>

+ **Bo Zhang**<br>
    ![ORCID icon](images/orcid.png){.inline_icon}
    [0000-0002-0743-5379](https://orcid.org/0000-0002-0743-5379)
  <br>
  <small>
     Center for Data-Driven Discovery in Biomedicine, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA; Division of Neurosurgery, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA
  </small>

+ **Brian M. Ennis**<br>
    ![ORCID icon](images/orcid.png){.inline_icon}
    [0000-0002-2653-5009](https://orcid.org/0000-0002-2653-5009)
  <br>
  <small>
     Center for Data-Driven Discovery in Biomedicine, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA; Division of Neurosurgery, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA
  </small>

+ **Ryan J. Corbett**<br>
    ![ORCID icon](images/orcid.png){.inline_icon}
    [0000-0002-3478-0784](https://orcid.org/0000-0002-3478-0784)
  <br>
  <small>
     Center for Data-Driven Discovery in Biomedicine, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA; Division of Neurosurgery, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA
  </small>

+ **Sharon J. Diskin**<br>
    ![ORCID icon](images/orcid.png){.inline_icon}
    [0000-0002-7200-8939](https://orcid.org/0000-0002-7200-8939)
  <br>
  <small>
     Division of Oncology, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA; Department of Pediatrics, University of Pennsylvania, Philadelphia, PA, 19104, USA
  </small>

+ **Nicholas Van Kuren**<br>
    ![ORCID icon](images/orcid.png){.inline_icon}
    [0000-0002-7414-9516](https://orcid.org/0000-0002-7414-9516)
  <br>
  <small>
     Center for Data-Driven Discovery in Biomedicine, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA; Division of Neurosurgery, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA
  </small>

+ **Noel Coleman**<br>
    ![ORCID icon](images/orcid.png){.inline_icon}
    [0000-0001-6454-1285](https://orcid.org/0000-0001-6454-1285)
  <br>
  <small>
     Center for Data-Driven Discovery in Biomedicine, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA; Division of Neurosurgery, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA
  </small>

+ **Christopher Blackden**<br>
  <br>
  <small>
     Center for Data-Driven Discovery in Biomedicine, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA; Division of Neurosurgery, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA
  </small>

+ **Jennifer L. Mason**<br>
  <br>
  <small>
     Center for Data-Driven Discovery in Biomedicine, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA; Division of Neurosurgery, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA
  </small>

+ **Saksham Phul**<br>
    ![ORCID icon](images/orcid.png){.inline_icon}
    [0000-0002-2771-2572](https://orcid.org/0000-0002-2771-2572)
  <br>
  <small>
     Center for Data-Driven Discovery in Biomedicine, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA; Division of Neurosurgery, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA
  </small>

+ **Miguel A. Brown**<br>
    ![ORCID icon](images/orcid.png){.inline_icon}
    [0000-0001-6782-1442](https://orcid.org/0000-0001-6782-1442)
  <br>
  <small>
     Center for Data-Driven Discovery in Biomedicine, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA; Division of Neurosurgery, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA
  </small>

+ **Adam C. Resnick**<br>
    ![ORCID icon](images/orcid.png){.inline_icon}
    [0000-0003-0436-4189](https://orcid.org/0000-0003-0436-4189)
  <br>
  <small>
     Center for Data-Driven Discovery in Biomedicine, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA; Division of Neurosurgery, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA
     · Funded by Children's Brain Tumor Network; NIH 3P30 CA016520-44S5, U2C HL138346-03, U24 CA220457-03; NCI/NIH Contract No. 75N91019D00024, Task Order No. 75N91020F00003; Children’s Hospital of Philadelphia Division of Neurosurgery
  </small>

+ **Jo Lynne Rokita^**
    ^[✉](#correspondence)^<br>
    ![ORCID icon](images/orcid.png){.inline_icon}
    [0000-0003-2171-3627](https://orcid.org/0000-0003-2171-3627)
  <br>
  <small>
     Center for Data-Driven Discovery in Biomedicine, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA; Division of Neurosurgery, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA; Department of Bioinformatics and Health Informatics, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA
     · Funded by NCI/NIH Contract No. 75N91019D00024, Task Order No. 75N91020F00003
  </small>


## Contact information

^Lead Contact: Jo Lynne Rokita <rokita@chop.edu>

✉Correspondence: Jo Lynne Rokita <rokita@chop.edu>

<!-- Cell Genomics author instructions: https://marlin-prod.literatumonline.com/pb-assets/journals/research/cell-genomics/cell-genomics_IfA.pdf -->

## In Brief
<!-- aka the eTOC blurb. A short summary that describes the context and significance of the findings for the broader readership in 80 words or less. -->


## Highlights
<!-- Highlights are bullet points that convey the core findings of your paper. You may include up to four highlights. The length of each highlight cannot exceed 85 characters (including spaces).-->




## Summary
<!-- The summary is a single paragraph no longer than 150 words. An effective summary includes the following elements: (1) a brief background of the question that avoids statements about how a process is not well understood; (2) a description of the results and approaches/model systems framed in the context of their conceptual interest; and (3) an indication of the broader significance of the work. We discourage novelty claims (e.g., use of the word “novel”) because they are overused, tend not to add meaning, and are difficult to verify. Please do not include references in the summary. CURRENT WORD COUNT 148 -->


## Keywords
<!-- We encourage you to include up to ten keywords with your paper. These keywords will be associated with your paper on Cell Press platforms and on PubMed. These keywords should be listed in the manuscript after the summary, separated by commas. -->



## Introduction



## Results




## Discussion




## Acknowledgments



## Author Contributions

|Author|Contributions|
|---|---|
|Eric Wafula|Formal analysis, Software|
|Krutika S. Gaonkar|Data curation, Formal analysis, Investigation, Methodology, Software, Writing – Original draft, Writing - Review and editing|
|Run Jin|Data curation, Formal analysis, Visualization, Writing – Original draft, Writing - Review and editing|
|Komal S. Rathi|Formal analysis, Investigation, Methodology, Writing – Original draft|
|Yuankun Zhu|Data curation, Formal analysis, Investigation, Methodology, Supervision|
|Bailey K. Farrow|Data curation, Software|
|Daniel P. Miller|Formal analysis|
|Mariarita Santi|Investigation, Validation, Writing - Review and editing|
|Adam A. Kraya|Methodology|
|Xiaoyan Huang|Formal analysis|
|Bo Zhang|Data curation, Formal analysis|
|Brian M. Ennis|Data curation, Formal analysis|
|Ryan J. Corbett|Formal analysis|
|Sharon J. Diskin|Investigation, Supervision, Validation, Funding acquisition, Writing - Review and editing|
|Nicholas Van Kuren|Data curation, Software|
|Noel Coleman|Data curation|
|Christopher Blackden|Resources|
|Jennifer L. Mason|Supervision|
|Saksham Phul|Data curation, Methodology, Formal analysis|
|Miguel A. Brown|Data curation, Methodology, Formal analysis|
|Adam C. Resnick|Conceptualization, Funding acquisition, Resources, Supervision|
|Jo Lynne Rokita^|Conceptualization, Data curation, Formal analysis, Funding acquisition, Investigation, Methodology, Software, Supervision, Writing – Original draft, Writing - Review and editing|


## Declarations of Interest


## Figure Titles and Legends



## Table Titles and Legends




## OPENPEDCAN METHODS

### RESOURCE AVAILABILITY

#### Lead contact

Requests for access to OpenPedCan raw data and/or specimens may be directed to, and will be fulfilled by Jo Lynne Rokita (rokita@chop.edu).

#### Materials availability

This study did not create new, unique reagents.

#### Data and code availability

Merged summary files for OpenPedCan v12 are openly accessible in [CAVATICA](https://cavatica.sbgenomics.com/u/cavatica/opentarget) or via download script in the [https://github.com/PediatricOpenTargets/OpenPedCan-analysis](https://github.com/PediatricOpenTargets/OpenPedCan-analysis) repository.
Cancer group summary data are visible within the NCI's pediatric [Molecular Targets Platform](https://moleculartargets.ccdi.cancer.gov/) and cohort, cancer group, and individual data are visible within [PedcBioPortal](https://pedcbioportal.kidsfirstdrc.org/study/summary?id=openpedcan_v12)

OpenPedCan analysis modules were developed within OpenPBTA [@doi:10.1016/j.xgen.2023.100340], modified based on OpenPBTA, or newly created and can be found within the following publicly available repositories.
OpenPBTA module analyses can be found at [https://github.com/AlexsLemonade/OpenPBTA-analysis](https://github.com/AlexsLemonade/OpenPBTA-analysis).
OpenPedCan module analyses can be found at [https://github.com/PediatricOpenTargets/OpenPedCan-analysis](https://github.com/PediatricOpenTargets/OpenPedCan-analysis).
OpenPedCan api code can be found at [https://github.com/PediatricOpenTargets/OpenPedCan-api](https://github.com/PediatricOpenTargets/OpenPedCan-api).

Software versions are documented in **Table XX**.

#### Data releases


### EXPERIMENTAL MODEL AND STUDY PARTICIPANT DETAILS
<!-- TODO: add description of all studies here -->



### METHOD DETAILS

#### Nucleic acids extraction and library preparation
<!-- TODO: add by study here, or refer to publication -->


#### Data generation
<!-- TODO: add by study here, or refer to publication -->


#### DNA WGS Alignment
Please refer to the OpenPBTA manuscript for details [@doi:10.1016/j.xgen.2023.100340].

#### Quality Control of Sequencing Data
Please refer to the OpenPBTA manuscript for details [@doi:10.1016/j.xgen.2023.100340].


##### SNP calling for B-allele Frequency (BAF) generation
Please refer to the OpenPBTA manuscript for details [@doi:10.1016/j.xgen.2023.100340].


#### Somatic Mutation Calling

##### SNV and indel calling
Please refer to the OpenPBTA manuscript for details [@doi:10.1016/j.xgen.2023.100340].


##### VCF annotation and MAF creation
<!-- TODO: update VEP version -->


##### Gather SNV and INDEL Hotspots
<!-- TODO: needs update -->


##### Consensus SNV Calling
<!-- TODO: needs update -->


#### Somatic Copy Number Variant Calling (WGS samples only)
<!-- TODO: needs update -->

##### Consensus CNV Calling
<!-- TODO: needs update -->


#### Somatic Structural Variant Calling (WGS samples only)
Please refer to the OpenPBTA manuscript for details [@doi:10.1016/j.xgen.2023.100340].


#### Methylation Analysis
<!-- include QC, b-value/m-value calculations, packages, dkfz classification -->


#### Gene Expression

##### Abundance Estimation
<!-- TODO: needs update -->


##### Gene Expression Matrices with Unique HUGO Symbols
<!-- TODO: needs update, include liftover for TCGA/GTEX -->


##### Gene fusion detection
<!-- TODO: needs update -->


### QUANTIFICATION AND STATISTICAL ANALYSIS

##### Focal Copy Number Calling (`focal-cn-file-preparation` analysis module)
Please refer to the OpenPBTA manuscript for details on assignment of copy number status values to CNV segments, cytobands, and genes [@doi:10.1016/j.xgen.2023.100340]. 
We applied criteria to resolve instances of multiple conflicting status calls for the same gene and sample, which are described in detail in the [focal-cn-file-preparation](https://github.com/PediatricOpenTargets/OpenPedCan-analysis/tree/dev/analyses/focal-cn-file-preparation) module. 
Briefly, we prioritized 1) non-neutral status calls, 2) calls made from dominant segments with respect to gene overlap, and 3) amplification and deep deletion status calls over gain and loss calls, respectively, when selecting a dominant status call per gene and sample. 
These methods resolved >99% of duplicated gene-level status calls.    


##### Gene Set Variation Analysis (`gene-set-enrichment-analysis` analysis module)
Please refer to the OpenPBTA manuscript for details [@doi:10.1016/j.xgen.2023.100340].



##### Fusion prioritization (`fusion_filtering` analysis module)




#### Mutational Signatures (`mutational-signatures` analysis module)



### Tumor Mutation Burden (`snv-callers` analysis module)



#### Clinical Data Harmonization

##### WHO Classification of Disease Types


##### Molecular Subtyping
Here, we build upon the molecular subtyping performed in OpenPBTA [@doi:10.1016/j.xgen.2023.100340].

High-grade gliomas..
<!-- TODO: needs update - DHG, IHG -->

Atypical teratoid rhabdoid tumors..


Neuroblastoma tumors...


###### Integration of brain tumor methylation classifications 


#### TP53 Alteration Annotation (`tp53_nf1_score` analysis module)
Please refer to the OpenPBTA manuscript for details [@doi:10.1016/j.xgen.2023.100340].


#### Prediction of participants' genetic sex
Please refer to the OpenPBTA manuscript for details [@doi:10.1016/j.xgen.2023.100340].


#### Selection of independent samples (`independent-samples` analysis module)

For analyses that require all input biospecimens to be independent, we use the OpenPedCan-analysis [independent-samples](https://github.com/PediatricOpenTargets/OpenPedCan-analysis/tree/d397339d567ddeff17e7a8cdca892f6a9dd2a0ba/analyses/independent-samples) module to select only one biospecimen from each input participant.
For each input participant of an analysis, the independent biospecimen is selected based on the analysis-specific filters and preferences for the biospecimen metadata, such as experimental strategy, cancer group, and tumor descriptor.



## Supplemental Information Titles and Legends



## Consortia


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>
