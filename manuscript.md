---
title: Manuscript Title
keywords:
- markdown
- publishing
- manubot
lang: en-US
date-meta: '2024-09-27'
author-meta:
- John Doe
- Jane Roe
header-includes: |
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta property="og:type" content="article" />
  <meta name="dc.title" content="Manuscript Title" />
  <meta name="citation_title" content="Manuscript Title" />
  <meta property="og:title" content="Manuscript Title" />
  <meta property="twitter:title" content="Manuscript Title" />
  <meta name="dc.date" content="2024-09-27" />
  <meta name="citation_publication_date" content="2024-09-27" />
  <meta property="article:published_time" content="2024-09-27" />
  <meta name="dc.modified" content="2024-09-27T15:52:51+00:00" />
  <meta property="article:modified_time" content="2024-09-27T15:52:51+00:00" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="John Doe" />
  <meta name="citation_author_institution" content="Department of Something, University of Whatever" />
  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />
  <meta name="twitter:creator" content="@johndoe" />
  <meta name="citation_author" content="Jane Roe" />
  <meta name="citation_author_institution" content="Department of Something, University of Whatever" />
  <meta name="citation_author_institution" content="Department of Whatever, University of Something" />
  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />
  <link rel="canonical" href="https://pivlab.github.io/annual_review_of_biomedical_data_science/" />
  <meta property="og:url" content="https://pivlab.github.io/annual_review_of_biomedical_data_science/" />
  <meta property="twitter:url" content="https://pivlab.github.io/annual_review_of_biomedical_data_science/" />
  <meta name="citation_fulltext_html_url" content="https://pivlab.github.io/annual_review_of_biomedical_data_science/" />
  <meta name="citation_pdf_url" content="https://pivlab.github.io/annual_review_of_biomedical_data_science/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://pivlab.github.io/annual_review_of_biomedical_data_science/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://pivlab.github.io/annual_review_of_biomedical_data_science/v/8791f3f5252090e925ae4ea699c6a24e4ea52f9b/" />
  <meta name="manubot_html_url_versioned" content="https://pivlab.github.io/annual_review_of_biomedical_data_science/v/8791f3f5252090e925ae4ea699c6a24e4ea52f9b/" />
  <meta name="manubot_pdf_url_versioned" content="https://pivlab.github.io/annual_review_of_biomedical_data_science/v/8791f3f5252090e925ae4ea699c6a24e4ea52f9b/manuscript.pdf" />
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
([permalink](https://pivlab.github.io/annual_review_of_biomedical_data_science/v/8791f3f5252090e925ae4ea699c6a24e4ea52f9b/))
was automatically generated
from [pivlab/annual_review_of_biomedical_data_science@8791f3f](https://github.com/pivlab/annual_review_of_biomedical_data_science/tree/8791f3f5252090e925ae4ea699c6a24e4ea52f9b)
on September 27, 2024.
</em></small>



## Authors



+ **John Doe**
  <br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [johndoe](https://github.com/johndoe)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [johndoe](https://twitter.com/johndoe)
    · ![Mastodon icon](images/mastodon.svg){.inline_icon width=16 height=16}
    [\@johndoe@mastodon.social](https://mastodon.social/@johndoe)
    <br>
  <small>
     Department of Something, University of Whatever
     · Funded by Grant XXXXXXXX
  </small>

+ **Jane Roe**
  ^[✉](#correspondence)^<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [janeroe](https://github.com/janeroe)
    <br>
  <small>
     Department of Something, University of Whatever; Department of Whatever, University of Something
  </small>


::: {#correspondence}
✉ — Correspondence possible via [GitHub Issues](https://github.com/pivlab/annual_review_of_biomedical_data_science/issues)
or email to
Jane Roe \<jane.roe@whatever.edu\>.


:::


## Abstract {.page_break_before}

This is a very cool paper about something.
We are doing this and that.
And this are the conclusions.
And this is in **boldface**.


## Introduction

Understanding the genetics of complex traits remains a formidable challenge, primarily addressed through Genome-Wide Association Studies (GWAS) that identify variant-trait associations without providing a mechanistic understanding of how these variants influence phenotypes.
A significant limitation of GWAS is that most associated variants reside in non-coding regions of the genome, underscoring the critical role of gene regulation in generating diverse phenotypes from identical DNA sequences.
To bridge this gap, Transcriptome-Wide Association Studies (TWAS) have been developed to link genetic variants to gene expression (eQTLs) or alternative splicing (sQTLs) and subsequently to specific traits or phenotypes.
However, TWAS and similar approaches typically focus on single variants or individual genes, thereby overlooking the intricate gene-gene interactions that are pivotal according to modern theories such as the omnigenic model of genetic architecture for complex traits.
Capturing these interactions necessitates more sophisticated methodologies.
Traditional approaches involve pathways or gene sets, which rely on predefined groups of functionally related genes but are constrained by existing knowledge.
Alternatively, QTL analyses like trans-eQTLs and sQTLs explore distal genetic relationships and splicing variations, respectively.
Another promising avenue is the construction of gene regulatory networks based on co-expression patterns, introducing the concept of gene modules.
These gene modules are often identified using unsupervised learning techniques applied to diverse and heterogeneous datasets, enabling the modeling of both linear and nonlinear relationships within the data.
Such methods transcend basic differential expression analyses by capturing higher-order connections between genes.
Tools like MAGMA and the more recent PhenoPLIER exemplify this integrative approach by combining variant-trait associations from GWAS or variant-gene expression-trait associations from TWAS with groups of functionally related genes, thereby enhancing the reliability of gene modules by mitigating false positives through additional layers of evidence.
Furthermore, these gene modules can be refined using quantitative omnigenic models that incorporate transcription factors (TFs) to better elucidate gene-gene interactions and potentially include aspects of alternative splicing.
Ongoing research continues to explore and develop novel methods that more effectively link expression patterns with genetic variation, aiming to provide a more comprehensive mechanistic understanding of the genetic basis of complex traits.


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>

