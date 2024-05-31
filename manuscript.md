---
title: The Open Pediatric Cancer (OpenPedCan) Project
keywords:
- pediatric cancer
- reproducibility
- open science
- multi-omics
lang: en-US
date-meta: '2024-05-31'
author-meta:
- Eric Wafula
- Zhuangzhuang Geng
- Sangeeta Shukla
- Aditya Lahiri
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
- Chuwei Zhong
- Brian M. Ennis
- Ryan J. Corbett
- Sharon J. Diskin
- Nicholas Van Kuren
- Matthew R. Lueder
- Noel Coleman
- Christopher Blackden
- Jennifer L. Mason
- Saksham Phul
- Miguel A. Brown
- Alex Sickler
- Kelsey Keith
- Dave Hill
- Asif T Chinwalla
- Yuanchao Zhang
- Adam C. Resnick
- Alvin Farrel
- Deanne Taylor
- Jo Lynne Rokita^
header-includes: |
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta property="og:type" content="article" />
  <meta name="dc.title" content="The Open Pediatric Cancer (OpenPedCan) Project" />
  <meta name="citation_title" content="The Open Pediatric Cancer (OpenPedCan) Project" />
  <meta property="og:title" content="The Open Pediatric Cancer (OpenPedCan) Project" />
  <meta property="twitter:title" content="The Open Pediatric Cancer (OpenPedCan) Project" />
  <meta name="dc.date" content="2024-05-31" />
  <meta name="citation_publication_date" content="2024-05-31" />
  <meta property="article:published_time" content="2024-05-31" />
  <meta name="dc.modified" content="2024-05-31T18:41:36+00:00" />
  <meta property="article:modified_time" content="2024-05-31T18:41:36+00:00" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Eric Wafula" />
  <meta name="citation_author_institution" content="Department of Bioinformatics and Health Informatics, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_orcid" content="0000-0001-8073-3797" />
  <meta name="citation_author" content="Zhuangzhuang Geng" />
  <meta name="citation_author_institution" content="Center for Data-Driven Discovery in Biomedicine, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_institution" content="Division of Neurosurgery, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_orcid" content="0009-0007-6883-0691" />
  <meta name="citation_author" content="Sangeeta Shukla" />
  <meta name="citation_author_institution" content="Department of Bioinformatics and Health Informatics, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_orcid" content="0000-0002-3727-9602" />
  <meta name="citation_author" content="Aditya Lahiri" />
  <meta name="citation_author_institution" content="Department of Bioinformatics and Health Informatics, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_orcid" content="0000-0001-9352-1312" />
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
  <meta name="citation_author" content="Chuwei Zhong" />
  <meta name="citation_author_institution" content="Center for Data-Driven Discovery in Biomedicine, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_institution" content="Division of Neurosurgery, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_orcid" content="0000-0003-2406-2735" />
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
  <meta name="citation_author" content="Matthew R. Lueder" />
  <meta name="citation_author_institution" content="Center for Data-Driven Discovery in Biomedicine, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_institution" content="Division of Neurosurgery, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_institution" content="Department of Pathology and Laboratory Medicine, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_orcid" content="0009-0002-7370-102X" />
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
  <meta name="citation_author" content="Alex Sickler" />
  <meta name="citation_author_institution" content="Center for Data-Driven Discovery in Biomedicine, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_institution" content="Division of Neurosurgery, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_orcid" content="0000-0001-7830-7537" />
  <meta name="citation_author" content="Kelsey Keith" />
  <meta name="citation_author_institution" content="Department of Biomedical and Health Informatics, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_orcid" content="0000-0002-7451-5117" />
  <meta name="citation_author" content="Dave Hill" />
  <meta name="citation_author_institution" content="Department of Biomedical and Health Informatics, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_orcid" content="0000-0002-1337-1789" />
  <meta name="citation_author" content="Asif T Chinwalla" />
  <meta name="citation_author_institution" content="Department of Biomedical and Health Informatics, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_orcid" content="0000-0001-7831-3996" />
  <meta name="citation_author" content="Yuanchao Zhang" />
  <meta name="citation_author_institution" content="Department of Biomedical and Health Informatics, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author" content="Adam C. Resnick" />
  <meta name="citation_author_institution" content="Center for Data-Driven Discovery in Biomedicine, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_institution" content="Division of Neurosurgery, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_orcid" content="0000-0003-0436-4189" />
  <meta name="twitter:creator" content="@adamcresnick" />
  <meta name="citation_author" content="Alvin Farrel" />
  <meta name="citation_author_institution" content="Department of Biomedical and Health Informatics, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_institution" content="Division of Oncology, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_institution" content="Center for Childhood Cancer Research, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_orcid" content="0000-0003-1087-9840" />
  <meta name="citation_author" content="Deanne Taylor" />
  <meta name="citation_author_institution" content="Department of Bioinformatics and Health Informatics, Children&#39;s Hospital of Philadelphia, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_institution" content="Department of Pediatrics, University of Pennsylvania Perelman Medical School, Philadelphia, PA, 19104, USA" />
  <meta name="citation_author_orcid" content="0000-0002-3302-4610" />
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
  <link rel="alternate" type="text/html" href="https://d3b-center.github.io/OpenPedCan-methods/v/6b9a252228a7e7da2eea0506617fea08ffe08229/" />
  <meta name="manubot_html_url_versioned" content="https://d3b-center.github.io/OpenPedCan-methods/v/6b9a252228a7e7da2eea0506617fea08ffe08229/" />
  <meta name="manubot_pdf_url_versioned" content="https://d3b-center.github.io/OpenPedCan-methods/v/6b9a252228a7e7da2eea0506617fea08ffe08229/manuscript.pdf" />
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
([permalink](https://d3b-center.github.io/OpenPedCan-methods/v/6b9a252228a7e7da2eea0506617fea08ffe08229/))
was automatically generated
from [d3b-center/OpenPedCan-methods@6b9a252](https://github.com/d3b-center/OpenPedCan-methods/tree/6b9a252228a7e7da2eea0506617fea08ffe08229)
on 2024-05-31.
</em></small>

# Authors



+ **Eric Wafula**<br>
    ![ORCID icon](images/orcid.png){.inline_icon}
    [0000-0001-8073-3797](https://orcid.org/0000-0001-8073-3797)
  <br>
  <small>
     Department of Bioinformatics and Health Informatics, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA
  </small>

+ **Zhuangzhuang Geng**<br>
    ![ORCID icon](images/orcid.png){.inline_icon}
    [0009-0007-6883-0691](https://orcid.org/0009-0007-6883-0691)
  <br>
  <small>
     Center for Data-Driven Discovery in Biomedicine, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA; Division of Neurosurgery, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA
  </small>

+ **Sangeeta Shukla**<br>
    ![ORCID icon](images/orcid.png){.inline_icon}
    [0000-0002-3727-9602](https://orcid.org/0000-0002-3727-9602)
  <br>
  <small>
     Department of Bioinformatics and Health Informatics, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA
  </small>

+ **Aditya Lahiri**<br>
    ![ORCID icon](images/orcid.png){.inline_icon}
    [0000-0001-9352-1312](https://orcid.org/0000-0001-9352-1312)
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

+ **Chuwei Zhong**<br>
    ![ORCID icon](images/orcid.png){.inline_icon}
    [0000-0003-2406-2735](https://orcid.org/0000-0003-2406-2735)
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

+ **Matthew R. Lueder**<br>
    ![ORCID icon](images/orcid.png){.inline_icon}
    [0009-0002-7370-102X](https://orcid.org/0009-0002-7370-102X)
  <br>
  <small>
     Center for Data-Driven Discovery in Biomedicine, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA; Division of Neurosurgery, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA; Department of Pathology and Laboratory Medicine, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA
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

+ **Alex Sickler**<br>
    ![ORCID icon](images/orcid.png){.inline_icon}
    [0000-0001-7830-7537](https://orcid.org/0000-0001-7830-7537)
  <br>
  <small>
     Center for Data-Driven Discovery in Biomedicine, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA; Division of Neurosurgery, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA
  </small>

+ **Kelsey Keith**<br>
    ![ORCID icon](images/orcid.png){.inline_icon}
    [0000-0002-7451-5117](https://orcid.org/0000-0002-7451-5117)
  <br>
  <small>
     Department of Biomedical and Health Informatics, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA
  </small>

+ **Dave Hill**<br>
    ![ORCID icon](images/orcid.png){.inline_icon}
    [0000-0002-1337-1789](https://orcid.org/0000-0002-1337-1789)
  <br>
  <small>
     Department of Biomedical and Health Informatics, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA
  </small>

+ **Asif T Chinwalla**<br>
    ![ORCID icon](images/orcid.png){.inline_icon}
    [0000-0001-7831-3996](https://orcid.org/0000-0001-7831-3996)
  <br>
  <small>
     Department of Biomedical and Health Informatics, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA
  </small>

+ **Yuanchao Zhang**<br>
  <br>
  <small>
     Department of Biomedical and Health Informatics, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA
  </small>

+ **Adam C. Resnick**<br>
    ![ORCID icon](images/orcid.png){.inline_icon}
    [0000-0003-0436-4189](https://orcid.org/0000-0003-0436-4189)
  <br>
  <small>
     Center for Data-Driven Discovery in Biomedicine, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA; Division of Neurosurgery, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA
     · Funded by Children's Brain Tumor Network; NIH 3P30 CA016520-44S5, U2C HL138346-03, U24 CA220457-03; NCI/NIH Contract No. 75N91019D00024, Task Order No. 75N91020F00003; Children’s Hospital of Philadelphia Division of Neurosurgery
  </small>

+ **Alvin Farrel**<br>
    ![ORCID icon](images/orcid.png){.inline_icon}
    [0000-0003-1087-9840](https://orcid.org/0000-0003-1087-9840)
  <br>
  <small>
     Department of Biomedical and Health Informatics, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA; Division of Oncology, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA; Center for Childhood Cancer Research, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA
     · Funded by NCI/NIH Contract No. 75N91019D00024, Task Order No. 75N91020F00003
  </small>

+ **Deanne Taylor**<br>
    ![ORCID icon](images/orcid.png){.inline_icon}
    [0000-0002-3302-4610](https://orcid.org/0000-0002-3302-4610)
  <br>
  <small>
     Department of Bioinformatics and Health Informatics, Children's Hospital of Philadelphia, Philadelphia, PA, 19104, USA; Department of Pediatrics, University of Pennsylvania Perelman Medical School, Philadelphia, PA, 19104, USA
     · Funded by NCI/NIH Contract No. 75N91019D00024, Task Order No. 75N91020F00003
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

✉Correspondence: Jo Lynne Rokita <rokita@chop.edu>


<!-- The title of the article, which should include an accurate, clear and concise description of the reported work, avoiding abbreviations; and the full names, institutional addresses, e-mail addresses for all authors. The corresponding author should also be indicated. It is suitable, should the authors of the work prefer, to designate authorship as a Consortium or Project. In such a case, a contact author must still be provided, and a complete author list/institutions/emails/etc should be included in the Authors' Contribution section. -->




## Abstract
<!-- 250 words maximum for abstract. Abstract must be structured into separate sections: 1). Background; 2). Findings; 3). Conclusions. -->

### Background 
<!-- A presentation of the interest or relevance of these data for the broader community -->

### Findings
<!-- A very brief preview of the data type(s) produced, the methods used, and information relevant to data validation -->

### Conclusions
<!-- A short summary of the potential uses of these data and implications for the field. -->




## Keywords
Pediatric cancer, open science, reproducibility, multi-omics



## Data Description

<!-- A brief statement providing background and purpose for collection of these data should be presented for readers without specialist knowledge in that area. A clear, concise, description of the data, the protocol(s) for data collection, data curation and quality control, as well as potential uses should then follow. -->

The Open Pediatric Cancer (OpenPedCan) project at the Children’s Hospital of Philadelphia is an open analysis effort in which we harmonize pediatric cancer data from multiple sources, perform downstream cancer analyses on these data, and provide them on PedcBioPortal and v2.1 of NCI's [Pediatric Molecular Targets Platform (MTP)](https://moleculartargets.ccdi.cancer.gov/). 
We harmonized, aggregated, and analyzed data from multiple pediatric and adult data sources.
Building on the work of OpenPBTA, OPC contains additional data from the following studies:
OpenPedCan currently include the following datasets, described more fully below:

- OpenPBTA
- TARGET
- Kids First Neuroblastoma (X01)
- Kids First PBTA (X01)
- Chordoma Foundation
- PPTC
- Maris
- MI-ONCOSEQ Study
- DGD (CHOP P30 Panel)
- GTEx
- TCGA
- CPTAC PBTA
- CPTAC GBM
- HOPE proteomics

**Open Pediatric Brain Tumor Atlas (OpenPBTA)**
In September of 2018, the [Children's Brain Tumor Network (CBTN)](https://cbtn.org/) released the [Pediatric Brain Tumor Atlas (PBTA)](https://cbtn.org/pediatric-brain-tumor-atlas/), a genomic dataset (whole genome sequencing, whole exome sequencing, RNA sequencing, proteomic, and clinical data) for nearly 1,000 tumors, available from the [Gabriella Miller Kids First Portal](https://kidsfirstdrc.org/).
In September of 2019, the Open Pediatric Brain Tumor Atlas (OpenPBTA) Project was launched.
OpenPBTA was a global open science initiative to comprehensively define the molecular landscape of tumors of 943 patients from the CBTN and the PNOC003 DIPG clinical trial from the [Pediatric Pacific Neuro-oncology Consortium](http://www.pnoc.us/) through real-time, collaborative analyses and [collaborative manuscript writing](https://github.com/AlexsLemonade/OpenPBTA-manuscript/) on GitHub, now published in [_Cell Genomics_](10.1016/j.xgen.2023.100340).
Additional PBTA data has been, and will be continually added to, OpenPedCan.

**Therapeutically Applicable Research to Generate Effective Treatments [(TARGET)](https://www.ncbi.nlm.nih.gov/projects/gap/cgi-bin/study.cgi?study_id=phs000218.v23.p8)**
The Therapeutically Applicable Research to Generate Effective Treatments (TARGET) Initiative is an NCI-funded collection of disease-specific projects that seeks to identify the genomic changes of pediatric cancers. 
The overall goal is to collect genomic data to accelerate the development of more effective therapies.
OpenPedCan analyses include the seven diseases present in the TARGET dataset: Acute Lymphoblastic Leukemia (ALL), Acute Myeloid Leukemia (AML), Clear cell sarcoma of the kidney, Neuroblastoma, Osteosarcoma, Rhabdoid tumor, and Wilm’s Tumor.

**Gabriella Miller Kids First [(Neuroblastoma)](https://www.ncbi.nlm.nih.gov/projects/gap/cgi-bin/study.cgi?study_id=phs001436.v1.p1) and [PBTA](https://www.ncbi.nlm.nih.gov/projects/gap/cgi-bin/study.cgi?study_id=phs002517.v2.p2)**
The Gabriella Miller Kids First Pediatric Research Program (Kids First) is a large-scale effort to accelerate research and gene discovery in pediatric cancers and structural birth defects.
The program includes whole genome sequencing (WGS) from patients with pediatric cancers and structural birth defects and their families.
OpenPedCan analyses include Neuroblastoma and PBTA data from the Kids First projects.

**[Chordoma Foundation](@https://www.chordomafoundation.org)**
The Chordoma Foundation seeks to advance research and improve healthcare for patients diagnosed with chordoma.

**Pediatric Preclinical Testing Consortium [(PPTC)](@https://ctep.cancer.gov/MajorInitiatives/Pediatric_PIVOT_Program.htm])**
The National Cancer Institute's (NCI) former PPTC,  now the [Pediatric Preclinical in Vivo Testing (PIVOT) Program](https://preclinicalpivot.org/about-pivot/), molecularly and pharmacologically characterizes cell-derived and patient-derived xenograft (PDX) models. 
OpenPedCan includes re-harmonized RNA-Seq data for 244 models from the initial PPTC study [@doi:10.1016/j.celrep.2019.09.071]. 

**MI-ONCOSEQ Study [@https://www.pathology.med.umich.edu/mctp/mi-oncoseq-study]**
These clinical sequencing data from the University of Michigan were donated to CBTN and added to the PBTA cohort.

**DGD [(CHOP P30 Panel)](https://www.chop.edu/cancer-panels)**
CHOP's [Division of Genome Diagnostics](https://www.chop.edu/centers-programs/division-genomic-diagnostics) has partnered with CCDI to add somatic panel sequencing data to OpenPedCan and the Molecular Targets Platform.

**The Genotype-Tissue Expression [(GTEx)](https://gtexportal.org/home/)**
GTEx project is an ongoing effort to build a comprehensive public data resource and tissue bank to study tissue-specific gene expression, regulation and their relationship with genetic variants.
Samples were collected from 54 non-diseased tissue sites across nearly 1000 individuals, primarily for molecular assays including WGS, WXS, and RNA-Seq.
OpenPedCan project includes 17,382 GTEx RNA-Seq samples from GTEx v8 release, which span across 31 GTEx groups in the v12 release.

**The Cancer Genome Atlas Program [(TCGA)](https://www.ncbi.nlm.nih.gov/projects/gap/cgi-bin/study.cgi?study_id=phs000178.v11.p8)**
TCGA is a landmark cancer genomics program that molecularly characterized over 20,000 primary cancer and matched normal samples spanning 33 cancer types.
It is a joint effort between NCI and the National Human Genome Research Institute.
OpenPedCan project includes 10,414 TCGA RNA-Seq samples (716 normal and 9698 tumor) from [33 cancer types](https://github.com/d3b-center/OpenPedCan-analysis/blob/dev/analyses/molecular-subtyping-integrate/results/tcga_cancer_groups.tsv).

**Clinical Proteomic Tumor Analysis Consortium (CPTAC) PBTA proteomics study** 
The CPTAC pediatric pan-brain tumor study [@doi:10.1016/j.cell.2020.10.044] contains 218 tumors profiled by proteogenomics and are included in OPC.

**CPTAC adult GBM proteomics study** 
This CPTAC adult GBM study [@doi:10.1016/j.ccell.2021.01.006] contains 99 tumors profiled by proteogenomics and are included in OPC.

**Project HOPE proteomics study**
Project HOPE is an adolescent and young adult high-grade glioma study (in preparation for publication) that contains 90 tumors profiled by proteogenomics and are included in OPC.

OpenPedCan operates on a pull request model to accept contributions from community participants.
The maintainers have set up continuous integration software via GitHub Actions to confirm the reproducibility of analyses within the project’s Docker container.

We maintained a data release folder on Amazon S3, downloadable directly from S3 or our open-access CAVATICA project, with merged files for each analysis.
As we produced new results, identified data issues, or added additional data, we created new data releases in a versioned manner.

The project maintainers includes scientists from the [Center for Data-Driven Discovery in Biomedicine](https://d3b.center/) and [Department of Biomedical and Health Informatics](https://www.research.chop.edu/department-of-biomedical-and-health-informatics) at the Children's Hospital of Philadelphia.

## Context

Creation of this dataset had multiple motivations.
First, we sought to harmonize, summarize, and contextualize pediatric cancer genomics data among normal tissues (GTEx) and adult cancer tissues (TCGA) to enable the creation of the National Cancer Institute's Molecular Targets Platform (MTP) at https://moleculartargets.ccdi.cancer.gov/.
Next, we created this resource for broad community use to promote rapid reuse and accelerate the discovery of additional mechanisms contributing to the pathogenesis of pediatric cancers.

<!-- Please state what motivated you to produced this data, and give some background on the area of research to relate the work to previous studies and help understand its utility and potential for reuse. -->

## Methods
<!-- This section can potentially be further broken up into subheadings a) Sampling strategy and b) Steps. Related methods can also be grouped under corresponding subheadings. This section should provide enough detail to allow other researchers to interpret and repeat the study. In addition to including the design of the study, it needs to provide detail on the type of reagents, instrumentation and kits used (including any identifiers such as RRIDs).

Please include and cite the URLs (or DOIs if snapshots have been archived in a repository such as Zenodo or GigaDB) to any publically available bioinformatics tools that are used in the production of the data, including the exact version used. If you are using new bioinformatics tools that you have developed for production or processing of the data described here, this may be suitable for submission as a Technical Note. We strongly encourage the use of workflow management systems such as Galaxy and container systems such as Docker, to save the details of the methods to encourage reproducibility as well as conciseness. Our GigaDB repository can also be used to archive data, workflows and snapshots of the code with an accompanying DOI. We also offer integration with Code Ocean, a cloud-based computational reproducibility platform.

For any article that presents software, in addition to making the source code available, we encourage submission to Code Ocean, a cloud-based computational reproducibility platform. Code Ocean supports any open-source programming language (as well as MATLAB and Stata). Authors should upload their code and data, specifying the appropriate languages and dependencies within the computational environment, to create a “compute capsule” that reproduces the results.

Once the code is published on Code Ocean, you will be issued DOI, which should be used to cite the compute capsule in the software section and any other relevant reference in the paper. Readers will then be able to view and verify the article’s results without needing to download or install anything. To submit, sign up to CodeOcean.
-->

### Method Details

#### Nucleic acids extraction and library preparation
For the PBTA X01 cohort, libraries were prepped using the Illumina TruSeq Strand-Specific Protocol to pull out poly-adenylated transcripts.

**cDNA Library Construction**
Total RNA was quantified using the Quant-iT™ RiboGreen® RNA Assay Kit and normalized to 5ng/ul.
Following plating, 2 uL of ERCC controls (using a 1:1000 dilution) were spiked into each sample.
An aliquot of 325 ng for each sample was transferred into library preparation.
The resultant 400bp cDNA went through dual-indexed library preparation: ‘A’ base addition, adapter ligation using P7 adapters, and PCR enrichment using P5 adapters.
After enrichment, the libraries were quantified using Quant-iT PicoGreen (1:200 dilution).
Samples were normalized to 5 ng/uL.
The sample set was pooled and quantified using the KAPA Library Quantification Kit for Illumina Sequencing Platforms.

**miRNA Extraction and Library Preparation**
Total RNA for CBTN samples was extracted as described in OpenPBTA [@doi:10.1016/j.xgen.2023.100340] and prepared according to the HTG Edge Seq protocol for the extracted RNA miRNA Whole transcriptome assay (WTA). 
15ng of RNA were mixed in 25ul of lysis buffer, which were then loaded onto a 96-well plate.
Human Fetal Brain Total RNA (Takara Bio USA, #636526) and Human Brain Total RNA (Ambion, Inc., Austin, TX, USA) were used as controls.
The plate was loaded into the HTG EdgeSeq processor along with the miRNA WTA assay reagent pack. 
Samples were processed for 18-20 hours, then were barcoded and amplified using a unique forward and reverse primer combination. 
PCR settings used for barcoding and amplification were 95C for 4 min, 16 cycles of (95C for 15 sec, 56C for 45 sec, 68C for 45 sec), and 68C for 10 min. 
Barcoded and amplified samples were cleaned using AMPure magnetic beads (Ampure XP,Cat# A63881). 
Libraries were quantified using the KAPA Biosystem assay qPCR kit (Kapa Biosystems Cat#KK4824) and CT values were used to determine the pM concentration of each library. 

#### Data generation
**PBTA X01 Illumina Sequencing**
Pooled libraries were normalized to 2nM and denatured using 0.1 N NaOH prior to sequencing.
Flowcell cluster amplification and sequencing were performed according to the manufacturer’s protocols using the NovaSeq 6000.
Each run was a 151bp paired-end with an eight-base index barcode read.
Data was analyzed using the Broad Picard Pipeline which includes de-multiplexing and data aggregation.

**PBTA miRNA Sequencing**
Libraries were pooled, denatured, and loaded onto sequencing cartridge. 
Libraries were sequenced using an Illumina Nextseq 500 per manufacturer guidelines.
FASTQ files were generated from raw sequencing data using Illumina BaseSpace and analyzed with the HTG EdgeSeq Parser software v5.4.0.7543 to generate an excel file containing quantification of 2083 miRNAs per sample. 
Any sample that did not pass the quality control set by the HTG REVEAL software version 2.0.1 (Tuscon, AR, USA) was excluded from the analysis.

#### DNA WGS Alignment
Please refer to the OpenPBTA manuscript for details [@doi:10.1016/j.xgen.2023.100340].

#### Quality Control of Sequencing Data
Please refer to the OpenPBTA manuscript for details [@doi:10.1016/j.xgen.2023.100340].
We also ran `somalier relate` [@doi:10.1186/s13073-020-00761-2] to identify potential mismatched samples.
We required that at least 20M total reads with 50% of RNA-Seq reads mapped to the human reference for samples to be included in analysis. 
We required at least 20X coverage for tumor DNA samples to be included in this analysis.

##### SNP calling for B-allele Frequency (BAF) generation
Please refer to the OpenPBTA manuscript for details [@doi:10.1016/j.xgen.2023.100340].

#### Somatic Mutation and INDEL Calling
For matched tumor/normal samples, we used the same mutation calling methods as described in OpenPBTA manuscript for details [@doi:10.1016/j.xgen.2023.100340].
For tumor only samples, we ran Mutect2 from GATK v4.2.2.0 using the following [workflow](https://github.com/kids-first/kf-tumor-workflow/tree/v0.3.0-beta).

##### VCF annotation and MAF creation
Somatic variants were annotated by the Ensembl Variant Effect Predictor (VEP v105) [@doi:10.1186/s13059-016-0974-4].
From tumor only variant calls, we removed variants with `alt_depth == 0` or `t_depth < 4`.

##### Consensus SNV Calling (tumor/normal only)
We adopted the consensus SNV calling method described in OpenPBTA manuscript with adjustment [@doi:10.1016/j.xgen.2023.100340]. 
For SNV calling, we combined four consensus SNV calling algorithms: Strelka2[@doi:10.1038/s41592-018-0051-x], Mutect2[@doi:10.1101/861054], Lancet[@doi:10.1038/s42003-018-0023-9], and VarDict[@doi: 10.1093/nar/gkw227].

Strelka2 outputs multi-nucleotide polymorphisms (MNPs) as consecutive single-nucleotide polymorphisms.
In order preserve MNPs, we gather MNP calls from the other caller inputs, and search for evidence supporting these consecutive SNP calls as MNP candidates.
Once found, the Strelka2 SNP calls supporting a MNP are converted to a single MNP call.
This is done to preserve the predicted gene model as accurately as possible in our consensus calls.
Consensus SNV from all four callers were collected and by default, calls that were detected in at least two calling algorithms or marked with "HotSpotAllele" were retained. 

For all SNVs, potential non-hotspot germline variants were removed if they had a normal depth <= 7 and gnomAD allele frequency > 0.001.
Final results were saved in MAF format.

#### Somatic Copy Number Variant (CNV) Calling
We called copy number variants for tumor/normal samples using Control-FREEC [@doi:10/ckt4vz; @doi:10/c6bcps] and CNVkit [@doi:10.1371/journal.pcbi.1004873] as described in the OpenPBTA manuscript [@doi:10.1016/j.xgen.2023.100340].
We used GATK [@doi:10.1101/gr.107524.110] to call CNVs for matched tumor/normal WGS samples when there were at least 30 male and 30 female normals from the same sequencing platform available for panel of normal creation.
For tumor only samples, we used Control-FREEC with the following modifications.
Instead of the b-allele frequency germline input file, we used the `dbSNP_v153_ucsc-compatible.converted.vt.decomp.norm.common_snps.vcf.gz` [dbSNP common snps file](s3://kids-first-seq-data/pipeline_references/dbSNP_v153_ucsc-compatible.converted.vt.decomp.norm.common_snps.vcf.gz) and to avoid hard-to-call regions, utilized the `hg38_canonical_150.mappability` [mappability file](s3://kids-first-seq-data/pipeline_references/hg38_canonical_150.mappability).
Both are also linked in the public [Kids First references CAVATICA project](https://cavatica.sbgenomics.com/u/kfdrc-harmonization/kf-references).
The Control-FREEC tumor only workflow can be found [here](https://github.com/kids-first/kf-tumor-workflow/blob/v0.3.0-beta/workflows/kfdrc_controlfreec_tumor_only_wf.cwl).

##### Consensus CNV Calling (WGS samples only)
We adopted the consensus CNV calling described in OpenPBTA manuscript [@doi:10.1016/j.xgen.2023.100340] with minor adjustments. 
For each caller and sample with WGS performed, we called CNVs based on consensus among Control-FREEC [@doi:10/ckt4vz; @doi:10/c6bcps], CNVkit [@doi:10.1371/journal.pcbi.1004873], and GATK [@doi:
10.1101/gr.107524.110]. 
Sample and consensus caller files with more than 2,500 CNVs were removed to de-noise and increase data quality, based on cutoffs used in GISTIC [@https://doi.org/10.1186/gb-2011-12-4-r41]. 
For each sample, we included the following regions in the final consensus set: 1) regions with reciprocal overlap of 50% or more between at least two of the callers; 2) smaller CNV regions in which more than 90% of regions were covered by another caller. 
For GATK, if a panel of normal was not able to be created (required 30 male and 30 female with the same sequencing platform), consensus was run for that tumor using Control-FREEC, CNVkit, and MantaSV. 
We defined copy number as NA for any regions that had a neutral call for the samples included in the consensus file. 
We merged CNV regions within 10,000 bp of each other with the same direction of gain or loss into single region. 

Any CNVs that overlapped 50% or more with immunoglobulin, telomeric, centromeric, segment duplicated regions, or that were shorter than 3000 bp were filtered out.
The CNVKit calls for WXS samples were appended to the consensus CNV file.

#### Somatic Structural Variant Calling (WGS samples only)
Please refer to the OpenPBTA manuscript for details [@doi:10.1016/j.xgen.2023.100340].

#### Methylation Analysis
##### Methylation array preprocessing
We preprocessed raw Illumina 450K and EPIC 850K Infinium Human Methylation Bead Array intensities using the array preprocessing methods implemented in the `minfi Bioconductor package` [@doi:10.1093/bioinformatics/btw691].
We utilized either `preprocessFunnorm` when an array dataset had both tumor and normal samples or multiple OpenPedcan-defined `cancer_groups` and `preprocessQuantile` when an array dataset had only tumor samples from a single OpenPedcan-defined `cancer_group` to estimate usable methylation measurements (`beta-values` and `m-values`) and copy number (`cn-values`).
Some Illumina Infinium array probes targeting CpG loci contain single-nucleotide polymorphisms (SNPs) near or within the probe [@doi:10.1038/bjc.2013.496], which could affect DNA methylation measurements [@doi:10.1186/s12864-015-2202-0].
As the minfi preprocessing workflow recommends, we dropped probes containing common SNPs in dbSNP (minor allele frequency > 1%) at the CpG interrogation or the single nucleotide extensions.

Details of methylation array preprocessing are available in the [OpenPedCan methylation-preprocessing module](https://github.com/PediatricOpenTargets/OpenPedCan-analysis/tree/dev/analyses/methylation-preprocessing).

##### Methylation beta-values summaries
We comprehensively summarized gene-level and isoform-level metrics for the methylation `beta-values` estimated by array preprocessing to provide insight into the variations in overall genomic DNA methylation levels observed across different pediatric tumors by computing CpG probe-level summary metrics in each cancer group within a cohort, including 1) `beta-values quantiles`, 2) `gene expression (TPM) and methylation (beta-values) correlation`, 3) `TPM median expression`, and 4) `transcript representation` - a proxy for percent isoform expression in a gene.
In addition, each CpG probe was annotated with a gene feature to identify the genomic regions likely involved in regulating gene expression.

Details of the analysis are available in the [OpenPedCan methylation-summary module](https://github.com/PediatricOpenTargets/OpenPedCan-analysis/tree/dev/analyses/methylation-summary).

##### Methylation sample classification
The Clinical Methylation Unit Laboratory of Pathology at the National Cancer Institute Center for Cancer Research ran the [DKFZ brain classifier version 12.6](https://www.molecularneuropathology.org/mnp/classifiers/11), a comprehensive DNA methylation-based classification of CNS tumors across all entities and age groups [@doi:10.1038/nature26000] and/or the Bethesda Brain tumor classifier v2.0 (NIH_v2) and the combo reporter pipeline v2.0 on docker container trust1/bethesda:latest.
Unprocessed IDAT-files from the [Children's Brain Tumor Network (CBTN)](https://cbtn.org/) `Infinium Human Methylation EPIC (850k) BeadChip arrays` were used as input and the following information was compiled into the `histologies.tsv` file: `dkfz_v12_methylation_subclass` (predicted methylation subtype), `dkfz_v12_methylation_subclass_score` (classification score), `dkfz_v12_methylation_mgmt_status` (_MGMT_ methylation status), `dkfz_v12_methylation_mgmt_estimated` (estimated _MGMT_ methylation fraction), `NIH_v2_methylation_Superfamily`, `NIH_v2_methylation_Superfamily_mean_score`, `NIH_v2_methylation_Superfamily_Consistency_score`, `NIH_v2_methylation_Class`, `NIH_v2_methylation_Class_mean_score`, `NIH_v2_methylation_Class_consistency_score`, `NIH_v2_methylation_Superfamily_match`, and `NIH_v2_methylation_Class_match`. 

#### Gene Expression
The [`tumor-normal-differential-expression`](https://github.com/PediatricOpenTargets/OpenPedCan-analysis/tree/dev/analyses/tumor-normal-differential-expression) module performs differential expression analyses for all sets of Disease (`cancer_group`) and Dataset (`cohort`) across all genes found in the `gene-expression-rsem-tpm-collapsed.rds` table.
The purpose of this analysis is to highlight the correlation and understand the variability in gene expression in different cancer conditions across different histological tissues.
For OpenPedCan v12 data release, this module performs expression analysis over 102 cancer groups across 52 histological tissues for all 54,346 genes found in the dataset.
This analysis was performed on the Children's Hospital of Philadelphia HPC and was configured to use 96G of RAM per CPU, with one task (one iteration of expression analysis for each set of tissue and cancer group) per CPU (total 102x52=5304 CPUs) using the [R/DESeq2](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-014-0550-8) package.
Please refer to script `run-tumor-normal-differential-expression.sh` in the module for additional details on Slurm processing configuration.
The same analysis can also be performed on CAVATICA, but requires further optimization.
The module describes the steps for CAVATICA set up, and scripts to publish an application on the portal.
The required data files are also available publicly on CAVATICA under the [Open Pediatric Cancer (OpenPedCan) Open Access](https://cavatica.sbgenomics.com/u/cavatica/opentarget/files/#q?path=v12).
Refer to the module for detailed description and scripts.

##### Abundance Estimation
Among the data sources used for OpenPedCan, GTEx and TCGA used GENCODE v26 and v36, respectively.
Therefore, the gene symbols had to be harmonized to GENCODE v39 for compatibility with the rest of the dataset.
The liftover process was done via a [custom script](https://github.com/d3b-center/D3b-DGD-Collaboration/blob/main/scripts/update_gene_symbols.py). 
The script first constructs an object detailing the gene symbol changes from the [HGNC symbol database](https://https://ftp.ebi.ac.uk/pub/databases/genenames/hgnc/archive/monthly/tsv/hgnc_complete_set_2021-06-01.txt). 
Using the symbol-change object, the script updates any columns containing gene symbols.
This liftover process was used on GTEx RNA-Seq, TCGA RNA-Seq, DGD fusions, and DNA hotspot files.

Additionally, the gene expression matrices had some instances where multiple Ensembl gene identifiers mapped to the same gene symbol.
This was dealt with by filtering the expression matrix to only genes with [FPKM/TPM] > 0 and then selecting the instance of the gene symbol with the maximum mean [FPKM/TPM/Expected_count] value across samples.
This enabled many downstream modules that require RNA-seq data have gene symbols as unique gene identifiers.
Refer to [collapse-rnaseq](https://github.com/PediatricOpenTargets/OpenPedCan-analysis/tree/dev/analyses/collapse-rnaseq) module for scripts and details.

##### Gene Expression Summary Statistics
We generated RNA-Seq gene expression (TPM) summary statistics for independent tumor samples from the combined OpenPedCan gene expression matrices, including cancers from pediatric cohorts (`PBTA`, `GMKF`, and `TARGET`) and adult cancers from the `TCGA` cohort.
We grouped selected samples into two groups containing samples from a cancer group in either each cohort or all cohorts, and calculated `TPM means`, `standard deviations`, `gene-wise z-scores`, `group-wise z-scores`, and `ranks` for each group as described in the [OpenPedCan rna-seq-expression-summary-stats module](https://github.com/PediatricOpenTargets/OpenPedCan-analysis/tree/dev/analyses/rna-seq-expression-summary-stats) in detail.
The resulting `gene-wise` and `group-wise` summary statistics tables were annotated with `EFO` and `MONDO` disease codes associated with the cancer groups.

##### Gene fusion detection
<!-- TODO: needs update -->

#### CPTAC PBTA, CPTAC GBM, and HOPE proteogenomics
The following methods are the general proteomics approaches used for the CPTAC PBTA [@doi:10.1016/j.cell.2020.10.044], CPTAC GBM [@doi:10.1016/j.ccell.2021.01.006], and HOPE (pre-publication, correspondence with Dr. Pei Wang) studies. 
For specific descriptions of sample preparation, mass spectrometry instrumentation and approaches, and data generation, processing, or analysis please refer to the relevant publications.

##### TMT-11 Labeling and Phosphopeptide Enrichment
Proteome and phosphoproteome analysis of brain cancer samples in the CPTAC PBTA (pediatric), CPTAC GBM (adult), and HOPE (adolescent and young adult, AYA) cohort studies were structured as TMT11-plex experiments. 
Tumor samples were digested with LysC and trypsin. 
Digested peptides were labeled with TMT11-plex reagent and prepared for phosphopeptide enrichment. 
For each dataset, a common reference sample was compiled from representative samples within the cohort. 
Phosphopeptides were enriched using Immobilized Metal Affinity Chromatography (IMAC) with Fe3+-NTA-agarose bead kits.

##### Liquid Chromatography with Tandem Mass Spectrometry (LC-MS/MS) Analysis
To reduce sample complexity, peptide samples were separated by high pH reversed phase HPLC fractionation. 
For CPTAC PBTA a total of 96 fractions were consolidated into 12 final fractions for LC-MS/MS analysis. 
For CPTAC GBM and HOPE cohorts a total of 96 fractions were consolidated into 24 fractions. 
For CPTAC PBTA, global proteome mass spectrometry analyses were performed on an Orbitrap Fusion Tribrid Mass Spectrometer and phosphoproteome analyses were performed on an Orbitrap Fusion Lumos Tribrid Mass Spectrometer. 
For CPTAC GBM and HOPE studies, mass spectrometry analysis was performed using an Orbitrap Fusion Lumos Mass Spectrometer. 

##### Protein Identification
The CPTAC PBTA spectra data were analyzed with MSFragger version 20190628 [@doi:10.1038/nmeth.4256] searching against a CPTAC harmonized RefSeq-based sequence database containing 41,457 proteins mapped to the human reference genome (GRCh38/hg38) obtained via the UCSC Table Browser on June 29, 2018, with the addition of 13 proteins encoded in the human mitochondrial genome, 264 common laboratory contaminant proteins, and an equal number of decoy sequences. 
The CPTAC GBM and HOPE spectra data were analyzed with MS-GF+ v9881 [@doi:10.1093/bioinformatics/btv437; @doi:10.1038/ncomms6277; @doi:10.1186/1471-2164-15-S1-S9] searching against the RefSeq human protein sequence database downloaded on June 29, 2018 (hg38; 41,734 proteins), combined with 264 contaminants, and a decoy database composed of the forward and reversed protein sequences. 

##### Protein Quantification and Data Analysis
Relative protein (gene) abundance was calculated as the ratio of sample abundance to reference abundance using the summed reporter ion intensities from peptides mapped to the respective gene. 
For phosphoproteomic datasets, data were not summarized by protein but left at the phosphopeptide level. 
Global normalization was performed on the gene-level abundance matrix (log2 ratio) for global proteomic and on the site-level abundance matrix (log2 ratio) for phosphoproteomic data. 
The median, log2 relative protein or peptide abundance for each sample was calculated and used to normalize each sample to achieve a common median of 0. 
To identify TMT outliers, inter-TMT t-tests were performed for each individual protein or phosphopeptide. 
Batch effects were checked using the log2 relative protein or phosphopeptide abundance and corrected using the Combat algorithm [@doi:10.1038/nbt1240]. 
Imputation was performed after batch effect correction for proteins or phosphopeptides with a missing rate < 50%. 
For the phosphopeptide datasets, 440 markers associated with cold-regulated ischemia genes were filtered and removed.


### QUANTIFICATION AND STATISTICAL ANALYSIS

##### Focal Copy Number Calling (`focal-cn-file-preparation` analysis module)
Please refer to the OpenPBTA manuscript for details on assignment of copy number status values to CNV segments, cytobands, and genes [@doi:10.1016/j.xgen.2023.100340].
We applied criteria to resolve instances of multiple conflicting status calls for the same gene and sample, which are described in detail in the [focal-cn-file-preparation](https://github.com/PediatricOpenTargets/OpenPedCan-analysis/tree/dev/analyses/focal-cn-file-preparation) module.
Briefly, we prioritized 1) non-neutral status calls, 2) calls made from dominant segments with respect to gene overlap, and 3) amplification and deep deletion status calls over gain and loss calls, respectively, when selecting a dominant status call per gene and sample.
These methods resolved >99% of duplicated gene-level status calls.    

##### Gene Set Variation Analysis (`gene-set-enrichment-analysis` analysis module)
Please refer to the OpenPBTA manuscript for details [@doi:10.1016/j.xgen.2023.100340].


##### Fusion prioritization (`fusion_filtering` analysis module)

The [`fusion_filtering`](https://github.com/PediatricOpenTargets/OpenPedCan-analysis/tree/dev/analyses/fusion_filtering) module filters artifacts and annotates fusion calls, with prioritization for oncogenic fusions, for the fusion calls from STAR-Fusion and Arriba.
After artifact filtering, fusions were prioritized and annotated as "putative oncogenic fusions" when at least one gene was a known kinase, oncogene, tumor suppressor, curated transcription factor, on the COSMIC Cancer Gene Census List, or observed in TCGA.
Fusions were retained in this module if they were called by both callers, recurrent or specific to a cancer group, or annotated as a putative oncogenic fusion.
Please refer to the module linked above for more detailed documentation and scripts.

##### Splicing quantification

To detect alternative splicing events, we utilized rMATS turbo (v. 4.1.0) with Ensembl/GENCODE v39 GFF annotations using the [Kids First RNA-Seq workflow](https://github.com/kids-first/kf-rnaseq-workflow/blob/master/workflow/rmats_wf.cwl).
We used `--variable-read-length` and `-t paired` options and applied an additional filter to include only splicing events with total junction read counts greater than 10.


#### Mutational Signatures (`mutational-signatures` analysis module)


### Tumor Mutation Burden [TMB] (`tmb-calculation` analysis module)

Recent clinical studies have associated high TMB with improved patient response rates and survival benefit from immune checkpoint inhibitors [@doi.org/10.1002/gcc.22733].

The [Tumor Mutation Burden (TMB) `tmb-calculation`](https://github.com/PediatricOpenTargets/OpenPedCan-analysis/tree/dev/analyses/tmb-calculation) module was adapted from the [`snv-callers` module](https://github.com/AlexsLemonade/OpenPBTA-analysis/tree/master/analyses/snv-callers) of the OpenPBTA project [@doi:10.1016/j.xgen.2023.100340].
Here, we use mutations in the `snv-consensus-plus-hotspots.maf.tsv.gz` file which is generated using [Kids First DRC Consensus Calling Workflow](https://github.com/kids-first/kf-somatic-workflow/blob/master/docs/kfdrc-consensus-calling.md) and is included in the OpenPedCan data download.
The consensus MAF contains SNVs or MNVs called in at least 2 of the 4 callers (Mutect2, Strelka2, Lancet, and Vardict) plus hotspot mutations if called in 1 of the 4 callers.
We calculated TMB for tumor samples sequenced  with either WGS or WXS.
Briefly, we split the SNV consensus MAF into SNVs and multinucleotide variants (MNVs).
We split the MNV subset into SNV calls, merged those back with the SNVs subset, and then removed sample-specific redundant calls.
The resulting merged and non-redundant SNV consensus calls were used as input for the TMB calculation.
We tallied only nonsynonymous variants with classifications of high/moderate consequence ("Missense_Mutation", "Frame_Shift_Del", "In_Frame_Ins", "Frame_Shift_Ins", "Splice_Site", "Nonsense_Mutation", "In_Frame_Del", "Nonstop_Mutation", and "Translation_Start_Site") for the numerator.

**All mutation TMB**

For WGS samples, we calculated the size of the genome covered as the intersection of Strelka2 and Mutect2's effectively surveyed areas, regions common to all variant callers, and used this as the denominator.
`WGS_all_mutations_TMB = (total # mutations in consensus MAF) / intersection_strelka_mutect_vardict_genome_size`
For WXS samples, we used the size of the WXS bed region file as the denominator.
`WXS_all_mutations_TMB = (total # mutations in consensus MAF)) / wxs_genome_size`

**Coding only TMB**

We generated coding only TMB from the consensus MAF as well.
We calculated the intersection for Strelka2 and Mutect2 surveyed regions using the coding sequence ranges in the GENCODE v39 gtf supplied in the OpenPedCan data download.
We removed SNVs outside of these coding sequences prior to implementing the TMB calculation below:
`WGS_coding_only_TMB = (total # coding mutations in consensus MAF) / intersection_wgs_strelka_mutect_vardict_CDS_genome_size`
For WXS samples, we intersected each WXS bed region file with the GENCODE v39 coding sequence, sum only variants within this region for the numerator, and calculate the size of this region as the denominator.
`WXS_coding_only_TMB = (total # coding mutations in consensus MAF) / intersection_wxs_CDS_genome_size`

Finally, we include an option (`nonsynfilter_focr`) to use specific nonsynonymous mutation variant classifications recommended from the [TMB Harmonization Project](https://friendsofcancerresearch.org/tmb/).


#### Clinical Data Harmonization

##### WHO Classification of Disease Types


##### Molecular Subtyping
Here, we build upon the molecular subtyping performed in OpenPBTA [@doi:10.1016/j.xgen.2023.100340].

**High-grade gliomas.**
<!-- TODO: needs update - DHG, IHG -->

High-grade gliomas (HGG) were categorized based on a combination of clinical information, molecular features, and DNA methylation data. 
H3 K28-altered diffuse midline gliomas (DMG) were classified based on the presence of a p.K28M or p.K28I mutation in _H3F3A_, _HIST1H3B_, _HIST1H3C_, or _HIST2H3C_, or a high-confidence DKFZ methylation score (>=0.8) in the appropriate subclass. 
Oligodendroglioma, IDH-mutant tumors were classified based on high-confidence "O_IDH" methylation classifications, and oligosarcoma, IDH-mutant tumors were defined as those with high-confidence "OLIGOSARC_IDH" methylation classifications. 
Pleomorphic xanthoastrocytomas (PXA) were classified using the following criteria: 1) methylation subtype is high-confidence "PXA" or `pathology_free_text_diagnosis` contains "pleomorphic xanthoastrocytoma" or "pxa", and 2) tumor contains a BRAF V600E mutation and a _CDKN2A_ or _CDKN2B_ homozygous deletion. 
Methylation classifications were used in classifying the following subtypes: 

1. DHG, H3 G35 ("DHG_G34" and "GBM_G34" classifications)
2. HGG, IDH ("A_IDH_HG" and "GBM_IDH" classifications)
3. HGG, H3 wild type (methylation classification contains "GBM_MES", "GBM_RTK", "HGG_", "HGAP", "AAP", or "ped_")

A new high-grade glioma entity called infant-type hemispheric gliomas (IHGs), characterized by distinct gene fusions enriched in receptor tyrosine kinase (RTK) genes including _ALK_, _NTRK1/2/3_, _ROS1_ or _MET_, was identified in 2021 [@doi: 10.1038/s41467-019-12187-5].
To identify IHG tumors, first, tumors which were classified as "IHG" by the DKFZ methylation classifier or diagnosed as "infant type hemispheric glioma" from `pathology_free_text_diagnosis` were selected [@doi:10.1038/nature26000].
Then, the corresponding tumor RNA-seq data were utilized to seek the evidence for RTK gene fusion.
Based on the specific RTK gene fusion present in the samples, IHGs were further classified as "IHG, ALK-altered", "IHG, NTRK-altered", "IHG, ROS1-altered", or "IHG, MET-altered".
If no fusion was observed, the samples were identified as "IHG, To be classified".


**Atypical teratoid rhabdoid tumors.**

Atypical teratoid rhabdoid tumors (ATRT) tumors were categorized into three subtypes: "ATRT, MYC", "ATRT, SHH", and "ATRT, TYR" [@doi:10.1093/neuonc/noz235].
In OpenPedCan, the molecular subtyping of ATRT was based solely on the DNA methylation data.
Briefly, ATRT samples with a high confidence DKFZ methylation subclass score (>= 0.8) were selected and subtypes were assigned based on the DKFZ methylation subclass [@doi10.1038/nature26000].
Samples with low confidence DKFZ methylation subclass scores (< 0.8) were identified as "ATRT, To be classified".

**Neuroblastoma tumors.**

Neuroblastoma (NBL) tumors with a pathology diagnosis of neuroblastoma, ganglioneuroblastoma, or ganglioneuroma were subtyped based on their MYCN copy number status as either "NBL, MYCN amplified" or "NBL, MYCN non-amplified".
If `pathology_free_text_diagnosis` was "NBL, MYCN non-amplified" and the genetic data suggested MYCN amplification, the samples were subtyped as "NBL, MYCN amplified".
On the other hand, if `pathology_free_text_diagnosis` was "NBL, MYCN amplified" and the genetic data suggested MYCN non-amplification, the RNA-Seq gene expression level of _MYCN_ was used as a prediction indicator.
In those cases, samples with _MYCN_ gene expression above or below the cutoff (TPM >= 140.83 based on visual inspection of MYCN CNV status) were subtyped as "NBL, MYCN amplified" and "NBL, MYCN non-amplified", respectively.
_MYCN_ gene expression was also used to subtype samples without DNA sequencing data.
If a sample did not fit none of these situations, it was denoted as "NBL, To be classified". 

**Craniopharyngiomas**

In addition to molecular criteria established in OpenPBTA [@doi:10.1016/j.xgen.2023.100340], craniopharyngiomas (CRANIO) are now subtyped using DNA methylation classifiers. 
Craniopharyngiomas with a high-confidence methylation subclass containing "CPH_PAP" were classified as papillary (CRANIO, PAP), and those with high-confidence methylation subclass containing "CPH_ADM" were classified as adamantinomatous (CRANIO, ADAM), respectively. 

**Ependymomas**

Ependymomas (EPN) are subtyped using the following criteria: 

1. Any spinal tumor with _MYCN_ amplification or with a high-confidence "EPN, SP-MYCN" methylation classification was subtyped as EPN, spinal and MYCN-amplified (SP-MYCN).
2. EPN tumors containing one or more gene fusions of _YAP1::MAMLD1_, _YAP1::MAML2_, or _YAP1::FAM118B_, or else had a high-confidence "EPN, ST YAP1" methylation classification were subtyped as EPN, ST YAP1.
3. EPN tumors containing one or more gene fusions of _ZFTA::RELA_ or _ZFTA::MAML2_, or else had a high-confidence "EPN, ST ZFTA" methylation classification were subtyped as EPN, ST ZFTA. 
This reflects an update to WHO classifications that now characterizes this subtype based on _ZFTA_ fusions rather than _RELA_ fusions. 
4. EPN tumors with 1) chromosome 1q gain and _TKTL1_ over-expression, or 2) _EZHIP_ over-expression, or 3) posterior fossa anatomical location and a histone H3 K28 mutation in _H3F3A_, _HIST1H3B_, _HIST1H3C_, or _HIST2H3C_, or 4) a high-confidence "EPN, PF A" methylation classification were subtyped as posterior fossa group A ependymomas (EPN, PF A). 
5. Tumors with 1) chr 6p or 6q loss and _GPBP1_ or _IFT46_ over-expression, or 2) a high-confidence "EPN, PF B" methylation classification were subtyped as posterior fossa group B ependymomas (EPN, PF B).
6. EPN tumors with a high-confidence "EPN, MPE" methylation classification were subtyped as myxopapillary ependymomas (EPN, MPE).
7. EPN tumors with a high-confidence "EPN, PF SE" methylation classification were subtyped as posterior fossa subependymomas (EPN, PF SE).
8. EPN tumors with a high-confidence "EPN, SP SE" methylation classification were subtyped as spinal subependymomas (EPN, SP SE).
9. EPN tumors with a high-confidence "EPN, SP" methylation classification were subtyped as spinal ependymomas (EPN, SP).
10. All other EPN tumors were classified as "EPN, To be classified".

**Low-grade gliomas**

In addition to subtyping methods described in OpenPBTA [@doi:10.1016/j.xgen.2023.100340], high-confidence methylation classifications are now used in classifying the following low-grade glioma (LGG) subtypes: 

1. LGG, other MAPK-altered (methylation subclass "PA_MID" or "PLNTY")
2. LGG, FGFR-altered (methylation subclass "PA_INF_FGFR")
3. LGG, IDH-altered (methylation subclass "A_IDH_LG")
4. LGG, MYB/MYBL1 fusion (methylation subclass "AG_MYB" or "LGG_MYB")
5. LGG, MAPK-altered (methylation subclass "LGG, MAPK")
6. LGG, BRAF- and MAPK-altered (methylation subclass "LGG, BRAF/MAPK")
7. SEGA, to be classified (methylation subclass "SEGA, To be classified")

**Medulloblastoma**

Medulloblastomas (MB) are now subtyped using high-confidence methylation classifications in addition to MedulloClassifier [@doi:10.1371/journal.pcbi.1008263] as follows:

1. MB tumors with methylation classification that contains "MB_SHH" are subtyped as SHH-activated medulloblastoma (MB, SHH)
2. MB tumors with "MB_G34_I", "MB_G34_II", "MB_G34_III", and "MB_G334_IV" methylation classifications are subtyped as medulloblastoma group 3 (MB, group 3)
3. MB tumors with "MB_G34_V", "MB_G34_VI", "MB_G34_VII", and "MB_G334_VIII" methylation classifications are subtyped as medulloblastoma group 4 (MB, group 4)
4. MB tumors with "MB_WNT" methylation classification are subtyped as WNT-activated MB (MB, WNT)
5. MB tumors with "MB_MYO" methylation classification are subtyped as medulloblastomas with myogenic differentiation (MB, MYO)

**Pineoblastomas**

Pineoblastomas (PB) are classified as follows using high-confidence methylation classifications:

1. Pineoblastoma, MYC/FOXR2-activated ("PB_FOXR2" methylation classification)
2. Pineoblastoma, RB1-altered ("PB_RB1" methylation classification)
3. Pineoblastoma, group 1 ("PB_GRP1A" and "PB_GRP1B" methylation classifications) 
4. Pineoblastoma, group 2 ("PB_GRP2" methylation classification)
5. All other pineoblastomas were classified as "PB, To be classified"

**non-MB, non-ATRT Embryonal Tumors**

Updates were made to non-MB, non-ATRT embryonal tumor subtyping as follows: 

1. Embryonal tumors with multilayered rosettes and C19MC-altered (ETMR, C19MC-altered) were classified based on 1) high-confidence "ETMR_C19MC" methylation classification or 2) _TTYH1_ gene fusion and either chromosome 19 amplification or _LIN28A_ over-expression. 
2. ETMR, not otherwise specified (NOS) were classified based on _LIN28A_ over-expression and no _TTYH1_ gene fusion. 


#### TP53 Alteration Annotation (`tp53_nf1_score` analysis module)
Please refer to the OpenPBTA manuscript for details [@doi:10.1016/j.xgen.2023.100340].

#### Prediction of participants' genetic sex
Please refer to the OpenPBTA manuscript for details [@doi:10.1016/j.xgen.2023.100340].

#### Selection of independent samples (`independent-samples` analysis module)
For analyses that require all input biospecimens to be independent, we use the OpenPedCan-analysis [independent-samples](https://github.com/PediatricOpenTargets/OpenPedCan-analysis/tree/d397339d567ddeff17e7a8cdca892f6a9dd2a0ba/analyses/independent-samples) module to select only one biospecimen from each input participant.
For each input participant of an analysis, the independent biospecimen is selected based on the analysis-specific filters and preferences for the biospecimen metadata, such as experimental strategy, cancer group, and tumor descriptor.


## Availability of source code and requirements

Project name: The Open Pediatric Cancer (OpenPedCan) Project
Project home page: https://github.com/d3b-center/OpenPedCan-analysis
Operating system(s): Platform independent
Programming languages: R, Python, bash
Other requirements: CAVATICA, Docker image at pgc-images.sbgenomics.com/d3b-bixu/openpedcanverse:latest
License: CC-BY 4.0

Primary analyses were performed using Gabriella Miller Kids First pipelines and are listed in the methods section.
Analysis modules were developed within [https://github.com/AlexsLemonade/OpenPBTA-analysis](https://github.com/AlexsLemonade/OpenPBTA-analysis) [@doi:10.1016/j.xgen.2023.100340], modified based on OpenPBTA, or newly created and can be found within the [https://github.com/d3b-center/OpenPedCan-analysis](https://github.com/d3b-center/OpenPedCan-analysis) publicly available repository.

Software versions are documented in **Table XX**.



## Data Availability

<!-- GigaScience requires authors to deposit the dataset(s) supporting the results reported in submitted manuscripts in a publicly-accessible data repository such as GigaDB (see GigaDB database terms of use for complete details). This section should be included when supporting data are available and must include the name of the repository and the permanent identifier or accession number and persistent hyperlinks for the datasets (if appropriate). The following format is recommended:

"The dataset(s) supporting the results of this article is(are) available in the [repository name] repository, [cite unique persistent identifier]."

Following the Joint Declaration of Data Citation Principles, where appropriate we ask that the data sets be cited where it is first mentioned in the manuscript, and included in the reference list. If a DOI has been issued to a dataset please always cite it using the DOI rather than the less stable URL the DOI resolves to (e.g., http://dx.doi.org/10.5524/100044 rather than http://gigadb.org/dataset/100044). For more see:

A list of available scientific research data repositories can be found in res3data and FAIRsharing.

A Data availability statement is required for all papers, and the code snapshots should be cited here. -->

### Datasets
The datasets supporting this study are available as follows:
The TARGET dataset is available in dbGAP under phs000218.v23.p8 [@dbgap:phs000218.v23.p8].
The GMKF Neuroblastoma dataset is available in dbGAP under phs001436.v1.p1[@dbgap:phs001436.v1.p1].
The Pediatric Brain Tumor Atlas data (PBTA), containing the subcohorts OpenPBTA, Kids First PBTA (X01), Chordoma Foundation, MI-ONCOSEQ Study, PNOC, and DGD is available in dbGAP under phs002517.v2.p2 [@dbgap:phs002517.v2.p2] or in the Kids First Portal (kidsfirstdrc.org).
The raw Genotype-Tissue Expression (GTEx) dataset is available in dbGAP under phs000424.v9.p2 and publicly available at https://gtexportal.org/home/.
The Cancer Genome Atlas (TCGA) dataset is available in dbGAP under phs000178.v11.p8 [@dbgap:phs000178.v11.p8].

Merged summary files for the latest release of OpenPedCan are openly accessible in [CAVATICA](https://cavatica.sbgenomics.com/u/cavatica/opentarget) or via `download-data.sh` script in the [https://github.com/d3b-center/OpenPedCan-analysis](https://github.com/d3b-center/OpenPedCan-analysis) repository.
Cancer group summary data from release v11 are visible within the NCI's pediatric [Molecular Targets Platform](https://moleculartargets.ccdi.cancer.gov/). 
Cohort, cancer group, and individual data are visible within [PedcBioPortal](https://pedcbioportal.kidsfirstdrc.org/study/summary?id=openpedcan_v15)




## Acknowledgments
We are incredibly grateful to each patient and family for donating tissue and associated metadata and clinical data to their respective consortia.


## Author Contributions

|Author|Contributions|
|---|---|
|Eric Wafula|Formal analysis, Software|
|Zhuangzhuang Geng|Data curation, Formal analysis, Investigation, Methodology, Software, Writing – Original draft|
|Sangeeta Shukla|Data curation, Formal analysis, Investigation, Methodology, Software, Writing – Original draft, Writing - Review and editing|
|Aditya Lahiri|Data curation, Formal analysis, Investigation, Methodology, Software, Writing – Original draft, Writing - Review and editing|
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
|Chuwei Zhong|Formal analysis|
|Brian M. Ennis|Data curation, Formal analysis|
|Ryan J. Corbett|Formal analysis|
|Sharon J. Diskin|Investigation, Supervision, Validation, Funding acquisition, Writing - Review and editing|
|Nicholas Van Kuren|Data curation, Software|
|Matthew R. Lueder|Data curation|
|Noel Coleman|Data curation|
|Christopher Blackden|Resources|
|Jennifer L. Mason|Supervision|
|Saksham Phul|Data curation, Methodology, Formal analysis|
|Miguel A. Brown|Data curation, Methodology, Formal analysis|
|Alex Sickler|Methodology, Formal analysis|
|Kelsey Keith|Software, Writing - original draft, API, Formal Analysis, Data Curation, Visualization|
|Dave Hill|Software, Writing - original draft, API, Data Curation|
|Asif T Chinwalla|Project Administration, Supervision, Methodology, Investigation, Validation, API|
|Yuanchao Zhang|API, Software, Formal Analysis, Writing - original draft|
|Adam C. Resnick|Conceptualization, Funding acquisition, Resources, Supervision|
|Alvin Farrel|Supervision, Investigation, Visualization, Methodology, Funding acquisition|
|Deanne Taylor|Conceptualization, Data curation, Formal analysis, Funding acquisition, Investigation, Methodology, Software, Supervision, Writing – Original draft, Writing - Review and editing|
|Jo Lynne Rokita^|Conceptualization, Data curation, Formal analysis, Funding acquisition, Investigation, Methodology, Software, Supervision, Writing – Original draft, Writing - Review and editing|


## Declarations of Interest
The authors declare no conflicts.

## Figure Titles and Legends



## Table Titles and Legends




## List of Abbreviations

<!-- If abbreviations are used in the text they should be defined in the text at first use, and a list of abbreviations should be provided in alphabetical order. -->

## Supplemental Information Titles and Legends



## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>

