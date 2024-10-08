---
title: Genetic studies through the lens of gene-gene networks
keywords:
- markdown
- publishing
- manubot
lang: en-US
date-meta: '2024-10-08'
author-meta:
- Marc Subirana-Granés
- Milton Pividori
header-includes: |
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta property="og:type" content="article" />
  <meta name="dc.title" content="Genetic studies through the lens of gene-gene networks" />
  <meta name="citation_title" content="Genetic studies through the lens of gene-gene networks" />
  <meta property="og:title" content="Genetic studies through the lens of gene-gene networks" />
  <meta property="twitter:title" content="Genetic studies through the lens of gene-gene networks" />
  <meta name="dc.date" content="2024-10-08" />
  <meta name="citation_publication_date" content="2024-10-08" />
  <meta property="article:published_time" content="2024-10-08" />
  <meta name="dc.modified" content="2024-10-08T18:02:18+00:00" />
  <meta property="article:modified_time" content="2024-10-08T18:02:18+00:00" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Marc Subirana-Granés" />
  <meta name="citation_author_institution" content="Department of Something, University of Whatever" />
  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />
  <meta name="twitter:creator" content="@johndoe" />
  <meta name="citation_author" content="Milton Pividori" />
  <meta name="citation_author_institution" content="Department of Something, University of Whatever" />
  <meta name="citation_author_institution" content="Department of Whatever, University of Something" />
  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />
  <link rel="canonical" href="https://pivlab.github.io/annual_review_of_biomedical_data_science/" />
  <meta property="og:url" content="https://pivlab.github.io/annual_review_of_biomedical_data_science/" />
  <meta property="twitter:url" content="https://pivlab.github.io/annual_review_of_biomedical_data_science/" />
  <meta name="citation_fulltext_html_url" content="https://pivlab.github.io/annual_review_of_biomedical_data_science/" />
  <meta name="citation_pdf_url" content="https://pivlab.github.io/annual_review_of_biomedical_data_science/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://pivlab.github.io/annual_review_of_biomedical_data_science/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://pivlab.github.io/annual_review_of_biomedical_data_science/v/b59472a6fa8e8cb091af2cc532aceb6ca8a8bb11/" />
  <meta name="manubot_html_url_versioned" content="https://pivlab.github.io/annual_review_of_biomedical_data_science/v/b59472a6fa8e8cb091af2cc532aceb6ca8a8bb11/" />
  <meta name="manubot_pdf_url_versioned" content="https://pivlab.github.io/annual_review_of_biomedical_data_science/v/b59472a6fa8e8cb091af2cc532aceb6ca8a8bb11/manuscript.pdf" />
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
([permalink](https://pivlab.github.io/annual_review_of_biomedical_data_science/v/b59472a6fa8e8cb091af2cc532aceb6ca8a8bb11/))
was automatically generated
from [pivlab/annual_review_of_biomedical_data_science@b59472a](https://github.com/pivlab/annual_review_of_biomedical_data_science/tree/b59472a6fa8e8cb091af2cc532aceb6ca8a8bb11)
on October 8, 2024.
</em></small>



## Authors



+ **Marc Subirana-Granés**
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

+ **Milton Pividori**
  ^[✉](#correspondence)^<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [miltondp](https://github.com/miltondp)
    <br>
  <small>
     Department of Something, University of Whatever; Department of Whatever, University of Something
  </small>


::: {#correspondence}
✉ — Correspondence possible via [GitHub Issues](https://github.com/pivlab/annual_review_of_biomedical_data_science/issues)
or email to
Milton Pividori \<milton.pividori@cuanschutz.edu\>.


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


## Single-variant / single-gene approaches 

![
**Major approaches based on single-variant/single-gene strategies to understand the genetic basis of complex traits**.
From left to right GWAS, TWAS, PWAS, HAWAS and MWAS.
](images/fig1.svg "Single-variant/single-gene strategies"){#fig:fig1 width="100%"}

Understanding the genetic underpinnings of complex traits and diseases has been a pivotal pursuit in the field of human genetics.
Early endeavors predominantly utilized genome-wide association studies (GWAS), which have been instrumental in identifying a foundational map of genomic regions linked to traits, offering valuable insights into the heritable components of complex diseases.

Building upon GWAS findings, efforts have been made to link these associated variants to specific genes, operating under the premise that variation in a single gene can elucidate disease-relevant biology.
Techniques such as Transcriptome-Wide Association Studies (TWAS) have emerged, integrating GWAS data with gene expression profiles to pinpoint genes whose expression levels correlate with phenotypic variation.
These approaches have advanced our understanding by moving from variant-level associations to functional gene-level insights.

### From genetic variants to traits: genome-wide association study (GWAS)

In a simple trait, a single gene can be responsible for the disease, for example in the case of Sickle Cell Anemia and Huntington's disease.
However, most traits are not so simplistic and are the result of many mutations across the genome.
Even these monogenic traits are impacted by the polygenic background [@doi:10.1038/s41467-020-17374-3].
Genome-wide association studies (GWAS) examine the relationship between genetic variants and specific phenotypes by comparing allele frequencies in individuals of similar ancestry with distinct phenotypic traits (**Figure {@fig:fig1}**).
The statistical associations are typically assessed using linear regression for continuous traits and logistic regression for binary traits.
It is crucial to control for covariates such as age, sex, population structure, and ancestry to minimize confounding effects [@doi:10.1038/s43586-021-00056-9; @doi:10.1186/s13059-022-02697-9].
As many variants are found to be significant and due to the phenomena of linkage disequilibrium between causal and non-causal variants, the results of GWAS are often grouped into risk loci.
These loci represent clusters of variants that demonstrate significant associations, although not every variant may be causal.
Since the first GWAS or age-related macular degeneration (AMD) in 2005, the GWAS catalog rapidly expanded, containing ~400,000 curated SNP-trait associations from >45,000 published GWAS across >5,000 human traits [@doi:10.1093/nar/gkac1010].
These studies have successfully identified risk loci for a variety of traits and diseases such as type 2 diabetes, auto-immune disease, schizophrenia, major depressive disorder, and more [@doi:10.1038/s41576-019-0127-1; @doi:10.1016/j.ajhg.2017.06.005].
 As GWAS participants increase, more loci are able to be identified.
For example, a study investigating insomnia with a sample size of >1M identified 202 risk loci [@doi:10.1038/s41588-018-0333-3], compared to earlier studies with a sample size of ~110,00, which were only able to identify 3 risk loci [@doi:10.1038/ng.3888].
The increased sample sizes allows for identification of more common variants as well as rare and low-frequency variants [@doi:10.1038/s41576-019-0127-1].
Beyond the identification of risk loci, GWAS has also led to the discovery of novel biological mechanisms.
In Crohn’s disease, a novel SNP was identified through GWAS in the gene *ATG16L1* (rs2241880) [@doi:10.1038/ng1954].
This SNP causes a missense mutation that enhances caspase-3-mediated cleavage of *ATG16L1* and diminished autophagy.
As a result, intracellular bacterial clearance is impaired causing a chronic inflammatory state [@doi:10.1038/nature13044].
A potential clinical application of GWAS involves quantifying a patient's risk for a specific disease based on relevant SNPs represented by a polygenic risk score (PRS) [@doi:10.1186/s13073-020-00742-5].
PRS’s can eventually be combined with current risk prediction models that include clinical, biochemical, and lifestyle features.
However, due to the majority of GWAS participants being from European ancestry, PRS has shown to not be generalizable to other groups.

Although GWAS have identified numerous genetic variants associated with complex traits, translating these findings into biological insights remains challenging [@doi:10.1038/s41576-019-0127-1].
Many significant GWAS variants are located in non-coding regions, making it difficult to identify the specific genes that drive trait associations [@doi:10.1093/hmg/ddac198].
A simple strategy to link GWAS-associated variants with a gene is by physical proximity, which typically selects the closest gene to the most significant SNP at each locus.
However, SNPs can have distal effects on the expression of the target gene [@doi:10.1126/science.aaz1776].
Genes can also have epistatic interactions, a secondary loci affecting a primary loci.
The peripheral effect of the secondary loci are often too small to be picked up through GWAS alone [@doi:10.1016/j.tig.2011.05.007]

Recent approaches combine multi-omics data from various cell types and tissues with GWAS to identify potential mechanisms of SNPs and the associated gene through molecular quantitative trait loci (moQTLs) [@doi:10.1016/j.molmed.2019.10.004] (**Figure {@fig:fig1}**).
An expression quantitative trait loci (eQTL) is a genetic region where variants are associated with the expression levels of a nearby or distant gene [@doi:10.1016/j.jgg.2023.05.003].
eQTL studies estimate that most causal genes linked to GWAS loci are not the proximal ones [@doi:10.1016/j.ajhg.2021.07.003].
They have also allowed for insight on epistatic interactions.
A large eQTL study was able to detect epistatic interactions, showing that many primary loci affecting gene expression were also modified by secondary eQTLs [@doi:10.1016/j.tig.2011.05.007].
Splicing quantitative trait loci (sQTLs) are another major causal mechanism in GWAS loci, but are complex to interpret due to the production of unknown isoforms [@doi:10.1038/s41467-022-32358-1].
To overcome this, LeafCutter [@doi:10.1038/s41588-017-0004-9] maps variable splicing events, alleviating the need for transcript annotations.
how this moqtls other mechanisms

Both GWAS and QTL studies have been penalized by their large multiple testing burden, causing the need to adopt a high level of significance.
This results in GWAS being underpowered to detect all heritability explained by SNPs [@doi:10.1038/s41576-019-0127-1].
A strategy to combat this limitation is reducing the number of tests performed by focusing on gene co-expression modules or other prioritized genes [ttps://doi.org/10.1038/s41576-019-0127-1].

There are many strategies for leveraging GWAS data to identify gene sets related to a trait such as MAGMA [@doi:10.1371/journal.pcbi.1004219] and FLAGS [@doi:10.1534/genetics.115.185009].
FLAGS uses predefined gene sets from prior knowledge while MAGMA is able to infer its own gene sets by first correlating genes with phenotypes and other genes.
Both methods then statistically associate these modules with specific phenotypes.
These tools are able to include trans-interactions, which TWAS misses, however by looking at the effect of SNPs on a gene set, specific SNP gene connections are lost [@doi:10.1093/hmg/ddz253].

### From GWAS to gene: transcriptome-wide association studies (TWAS)

Transcriptome-wide association studies (TWAS) address this gap by integrating GWAS data with gene expression data (**Figure {@fig:fig1}**), typically derived from eQTL studies, to prioritize genes whose expression across different tissues is influenced by GWAS variants [@doi:10.3389/fgene.2021.713230; @doi:10.1038/s41588-019-0385-z].
By leveraging predicted gene expression levels, TWAS provides a mechanistic link between genetic variants and traits, allowing researchers to move beyond associations with individual SNPs to identify putatively causal genes [@doi:10.1038/s41588-019-0385-z].
Since TWAS models the genetic regulation of gene expression, the approach allows researchers to impute expression levels in GWAS cohorts where expression data may not be available.
A key advantage of TWAS over GWAS lies in its ability to increase interpretability by providing a gene-trait association: TWAS connects trait-associated SNPs (which are mostly non-coding) to genes, which are biologically functional units.

Several TWAS approaches have been introduced [@doi:10.1038/s42003-023-05279-y], including PrediXcan [@doi:10.1038/ng.3367], FUSION [@doi:10.1038/ng.3506] and TIGAR [@doi:10.1016/j.ajhg.2019.05.018].
However, all of them implement a similar framework that consists in three steps: 1) model training, 2) gene expression imputation, and 3) gene-trait association.
For example, during 1), PrediXcan, builds one expression prediction model per gene and tissue using penalized linear regression with ElasticNet to model sparse genetic architectures.
These models contain weights for each SNP used as predictor for a gene expression in a tissue.
Given genotype data in a cohort without measured gene expression, during 2), the SNPs weights from the models can be used to impute tissue-specific gene expression for individuals.
During 3), a gene-tissue-trait association is computed by correlating the tissue-specific imputed gene expression with the trait of interest.
Most methods (such as Summary-PrediXcan [@doi:10.1038/s41467-018-03621-1] or S-PrediXcan), however, offer a shortcut by computing a gene-tissue-trait association directly from GWAS summary statistics without the need of individual-level data.
This process, however, requires the user to select a tissue of interest, which might not be straightforward [@doi:10.1038/s41588-019-0385-z].
To address this limitation, approaches such as MultiXcan [@doi:10.1371/journal.pgen.1007889] or UTMOST [@doi:10.1038/s41588-019-0345-7] combine information across tissues to generate a gene-trait association.
These multi-tissue approaches are generally more powerful than single-tissue ones, although they do not provide a direction of effect (i.e., whether a higher or lower predicted expression is associated with a higher or lower disease risk).

### Going beyond TWAS

The flexibility of this 3-step framework can also be used to test whether other molecular phenotypes might mediate the association between GWAS variants and a trait of interest.
In addition to integrating eQTLs, the framework has been implemented also with splicing QTLs (sQTLs), protein QTLs (pQTLs), histone acetylation QTLs (haQTLs) and methylation QTLs (mQTLs).

### Mapping protein function to disease: protein-wide association studies (PWAS)

PWAS complements GWAS and TWAS by aggregating genetic variations in protein-coding regions to assess their combined impact on protein function and phenotypes (**Figure {@fig:fig1}**) [@doi:10.1186/s13059-020-02089-x].
While GWAS focuses on individual variant associations, PWAS emphasizes the broader functional consequences of coding variants, providing a more comprehensive view of potential links to disease.
By aggregating multiple variants of a gene, PWAS reduces the multiple testing burden and reveals complex inheritance patterns, such as dominant and recessive traits.
PWAS shares a methodology with GWAS, using genotype, phenotype, and covariate data, but extends this approach by evaluating the cumulative impact of multiple variants on protein function.

To evaluate how genetic variants—such as missense, nonsense, and frameshift mutations—affect protein function, PWAS uses the FIRM machine learning model to assign impairment scores [@doi:10.1186/s13059-020-02089-x].
Genes are then evaluated for dominant and recessive inheritance patterns, followed by statistical tests to determine significant associations between gene-level scores and phenotypes.
For example, using PWAS with the UK Biobank confirmed the association of *MUTYH* with colorectal cancer, even though no individual variant reached genome-wide significance in GWAS  [@doi:10.1186/s13059-020-02089-x].
This demonstrates PWAS’s ability to uncover functional associations missed by other methods.
Similarly, PWAS identified associations in genes like *HLA-DQA2* and *PSMB9* in asthma, highlighting its utility in exploring the genetic components of complex diseases.
[@doi:10.1101/2024.01.20.23300645].
However, PWAS relies heavily on high-quality proteomic data and may overlook associations driven by non-coding variants.
It is also computationally intensive, and future efforts may focus on incorporating rare variants and more diverse data.

### Enhancing genetic studies with epigenetic data: Epigenome-wide association studies (EWAS) 

Epigenome-wide association studies (EWAS) offer another valuable approach to understanding complex traits, specifically by exploring single-variant and single-gene relationships within the epigenetic context.
Unlike GWAS, which primarily investigate genetic variants, EWAS focuses on epigenetic markers such as DNA methylation and histone modifications to uncover their roles in gene regulation and disease etiology [@doi:10.1186/s13148-021-01200-8].
Within the EWAS framework, methylome-wide association studies (MWAS) (**Figure {@fig:fig1}**) and histone acetylome-wide association studies (HAWAS) (**Figure {@fig:fig1}**), based on haQTLs and mQLTs respectability, represent specialized methodologies targeting specific types of epigenetic modifications .
MWAS concentrates on DNA methylation patterns, enabling the identification of methylation changes at individual loci associated with particular traits or diseases.
For instance, a MWAS conducted by Shen et al.
provided evidence for a causal relationship between DNAm and depression, suggesting that epigenetic modifications may mediate the genetic risk for depression, exemplifying the effectiveness of EWAS in uncovering the biological mechanisms that link genetic predisposition to psychiatric disorders [@doi:10.1186/s13073-022-01039-5].
HAWAS focuses on histone acetylation modifications, which are crucial for regulating chromatin structure and gene expression.
Sun et al.
conducted a HAWAS on autism spectrum disorder (ASD) and identified thousands of differential acetylation loci in the brains of individuals with ASD, indicating that histone acetylation plays a significant role in ASD pathogenesis [@doi:10.1016/j.cell.2016.10.031].

The tissue-specific nature of epigenetic modifications, alongside the capacity to capture cellular plasticity and environmental influences, enhances our insight into the effects of genetic variants across distinct tissues, temporal cellular states, and gene-environment interactions.
This understanding contributes to a more detailed knowledge of the molecular mechanisms and regulatory dynamics underlying complex diseases, thereby supplementing the findings from GWAS [@doi:10.3390/cells9112424; @doi:10.1016/j.placenta.2007.09.011].

### Single-gene approaches are not enough 

Despite the advancements facilitated by single-variant and single-gene methodologies, a common thread persists: the focus remains on one gene at a time.
The underlying expectation is that identifying a gene linked to a trait will directly unveil the biological mechanisms driving disease processes.
While this has been successful in certain monogenic disorders, complex traits often involve intricate interactions among multiple genes and environmental factors.
Consequently, the one-gene-at-a-time paradigm may oversimplify the multifaceted nature of these traits.
In light of these considerations, it becomes imperative to reevaluate our approaches to dissecting the genetic architecture of complex traits.
This necessitates a shift towards methodologies that can capture the polygenic and network-based interactions inherent in complex diseases.



## From single genes to gene networks: the omnigenic model for complex traits {.page_break_before}


## From gene networks to machine learning derived gene modules: hands-on strategies for inferring gene-gene interactions {.page_break_before}


## A gene module perspective for genetic studies {.page_break_before}


## Future perspectives {.page_break_before}


## Conclusions {.page_break_before}


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>

