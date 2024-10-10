---
title: Genetic studies through the lens of gene networks
keywords:
- genetic studies
- gwas
- twas
- gene modules
- gene co-expression networks
- QTL
- complex traits
lang: en-US
date-meta: '2024-10-10'
author-meta:
- Marc Subirana-Granés
- Jill Hoffman
- Haoyu Zhang
- Christina Akirtava
- Sutanu Nandi
- Kevin Fotso
- Milton Pividori
header-includes: |
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta property="og:type" content="article" />
  <meta name="dc.title" content="Genetic studies through the lens of gene networks" />
  <meta name="citation_title" content="Genetic studies through the lens of gene networks" />
  <meta property="og:title" content="Genetic studies through the lens of gene networks" />
  <meta property="twitter:title" content="Genetic studies through the lens of gene networks" />
  <meta name="dc.date" content="2024-10-10" />
  <meta name="citation_publication_date" content="2024-10-10" />
  <meta property="article:published_time" content="2024-10-10" />
  <meta name="dc.modified" content="2024-10-10T16:43:30+00:00" />
  <meta property="article:modified_time" content="2024-10-10T16:43:30+00:00" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Marc Subirana-Granés" />
  <meta name="citation_author_institution" content="Department of Biomedical Informatics, University of Colorado Anschutz Medical Campus, Aurora, CO, USA" />
  <meta name="citation_author_orcid" content="0000-0003-3934-839X" />
  <meta name="twitter:creator" content="@msubirana20" />
  <meta name="citation_author" content="Jill Hoffman" />
  <meta name="citation_author_institution" content="Department of Biomedical Informatics, University of Colorado Anschutz Medical Campus, Aurora, CO, USA" />
  <meta name="citation_author_orcid" content="0000-0002-2690-2593" />
  <meta name="citation_author" content="Haoyu Zhang" />
  <meta name="citation_author_institution" content="Department of Biomedical Informatics, University of Colorado Anschutz Medical Campus, Aurora, CO, USA" />
  <meta name="citation_author_orcid" content="0009-0005-6025-0217" />
  <meta name="citation_author" content="Christina Akirtava" />
  <meta name="citation_author_institution" content="Department of Biochemistry and Molecular Genetics, RNA Bioscience Initiative, University of Colorado Anschutz Medical Campus, Aurora, CO, USA" />
  <meta name="citation_author_orcid" content="0000-0001-7587-2303" />
  <meta name="twitter:creator" content="@bio2data" />
  <meta name="citation_author" content="Sutanu Nandi" />
  <meta name="citation_author_institution" content="Department of Pharmacology, University of Colorado Anschutz Medical Campus, Aurora, CO, USA" />
  <meta name="citation_author_orcid" content="0009-0001-5887-999X" />
  <meta name="citation_author" content="Kevin Fotso" />
  <meta name="citation_author_institution" content="Office of Information Technology, University of Colorado Anschutz Medical Campus, Aurora, CO, USA" />
  <meta name="citation_author" content="Milton Pividori" />
  <meta name="citation_author_institution" content="Department of Biomedical Informatics, University of Colorado School of Medicine, Aurora, CO 80045, USA" />
  <meta name="citation_author_institution" content="Colorado Center for Personalized Medicine, University of Colorado Anschutz Medical Campus, Aurora, CO, USA" />
  <meta name="citation_author_orcid" content="0000-0002-3035-4403" />
  <meta name="twitter:creator" content="@miltondp" />
  <link rel="canonical" href="https://pivlab.github.io/annual_review_of_biomedical_data_science/" />
  <meta property="og:url" content="https://pivlab.github.io/annual_review_of_biomedical_data_science/" />
  <meta property="twitter:url" content="https://pivlab.github.io/annual_review_of_biomedical_data_science/" />
  <meta name="citation_fulltext_html_url" content="https://pivlab.github.io/annual_review_of_biomedical_data_science/" />
  <meta name="citation_pdf_url" content="https://pivlab.github.io/annual_review_of_biomedical_data_science/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://pivlab.github.io/annual_review_of_biomedical_data_science/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://pivlab.github.io/annual_review_of_biomedical_data_science/v/c2524cc88cbe2714df69644fdc4b9d3d5105b835/" />
  <meta name="manubot_html_url_versioned" content="https://pivlab.github.io/annual_review_of_biomedical_data_science/v/c2524cc88cbe2714df69644fdc4b9d3d5105b835/" />
  <meta name="manubot_pdf_url_versioned" content="https://pivlab.github.io/annual_review_of_biomedical_data_science/v/c2524cc88cbe2714df69644fdc4b9d3d5105b835/manuscript.pdf" />
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



<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.2/css/all.css">

[
<i class="fas fa-info-circle fa-lg"></i> **When citing this paper, please use the following:**<br><br>
_Subirana-Granés M, Hoffman J, Zhang H, Nandi S, Akirtava C, Fotso K, Pividori M. Genetic studies through the lens of gene networks. 2025. Annu. Rev. Biomed. Data Sci. 8. https://doi.org/10.1146/annurev-biodatasci-103123-095355_
]{.banner .lightblue}


<small><em>
This manuscript
([permalink](https://pivlab.github.io/annual_review_of_biomedical_data_science/v/c2524cc88cbe2714df69644fdc4b9d3d5105b835/))
was automatically generated
from [pivlab/annual_review_of_biomedical_data_science@c2524cc](https://github.com/pivlab/annual_review_of_biomedical_data_science/tree/c2524cc88cbe2714df69644fdc4b9d3d5105b835)
on October 10, 2024.
</em></small>



## Authors



+ **Marc Subirana-Granés**
  <br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0003-3934-839X](https://orcid.org/0000-0003-3934-839X)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [msubirana](https://github.com/msubirana)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [msubirana20](https://twitter.com/msubirana20)
    <br>
  <small>
     Department of Biomedical Informatics, University of Colorado Anschutz Medical Campus, Aurora, CO, USA
  </small>

+ **Jill Hoffman**
  <br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0002-2690-2593](https://orcid.org/0000-0002-2690-2593)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [jillhoffman](https://github.com/jillhoffman)
    <br>
  <small>
     Department of Biomedical Informatics, University of Colorado Anschutz Medical Campus, Aurora, CO, USA
  </small>

+ **Haoyu Zhang**
  <br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0009-0005-6025-0217](https://orcid.org/0009-0005-6025-0217)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [haoyu-zc](https://github.com/haoyu-zc)
    <br>
  <small>
     Department of Biomedical Informatics, University of Colorado Anschutz Medical Campus, Aurora, CO, USA
  </small>

+ **Christina Akirtava**
  <br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0001-7587-2303](https://orcid.org/0000-0001-7587-2303)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [bio2data](https://github.com/bio2data)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [bio2data](https://twitter.com/bio2data)
    <br>
  <small>
     Department of Biochemistry and Molecular Genetics, RNA Bioscience Initiative, University of Colorado Anschutz Medical Campus, Aurora, CO, USA
  </small>

+ **Sutanu Nandi**
  <br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0009-0001-5887-999X](https://orcid.org/0009-0001-5887-999X)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [snandi-DS](https://github.com/snandi-DS)
    <br>
  <small>
     Department of Pharmacology, University of Colorado Anschutz Medical Campus, Aurora, CO, USA
  </small>

+ **Kevin Fotso**
  <br>
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [kf-cuanschutz](https://github.com/kf-cuanschutz)
    <br>
  <small>
     Office of Information Technology, University of Colorado Anschutz Medical Campus, Aurora, CO, USA
  </small>

+ **Milton Pividori**
  ^[✉](#correspondence)^<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0002-3035-4403](https://orcid.org/0000-0002-3035-4403)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [miltondp](https://github.com/miltondp)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [miltondp](https://twitter.com/miltondp)
    · ![Mastodon icon](images/mastodon.svg){.inline_icon width=16 height=16}
    [\@miltondp@genomic.social](https://genomic.social/@miltondp)
    <br>
  <small>
     Department of Biomedical Informatics, University of Colorado School of Medicine, Aurora, CO 80045, USA; Colorado Center for Personalized Medicine, University of Colorado Anschutz Medical Campus, Aurora, CO, USA
     · Funded by The National Human Genome Research Institute (K99/R00 HG011898); The Eunice Kennedy Shriver National Institute of Child Health and Human Development (R01 HD109765)
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
Understanding the genetics of complex traits remains a formidable challenge.
Genome-Wide Association Studies (GWAS) have been instrumental in advancing our understanding of the genetics behind complex traits.
By scanning the genomes of large populations, GWAS identify associations between genetic variants and traits, providing valuable insights into the genetic architecture of diseases and other phenotypic traits.
This approach has been particularly successful in identifying thousands of variant-trait associations, shedding light on potential genetic factors involved in a wide range of conditions.
However, a significant limitation of GWAS is that most associated variants reside in non-coding regions of the genome, underscoring the critical role of gene regulation in generating diverse phenotypes from identical DNA sequences.


To bridge this gap, various methods have been developed to enhance the interpretation of GWAS findings.
One such approach is MAGMA, which assigns variants to genes based on physical proximity without considering gene expression data.
However, it has been shown that the closest gene to a variant is not necessarily the gene influenced by that variant, revealing the limitations of proximity-based methods.
Transcriptome-Wide Association Studies (TWAS) overcome this limitation by linking genetic variants to gene expression (eQTLs).
TWAS has evolved into a more general framework to test other molecular phenotypes (molQTLs).

Despite their advancements, TWAS and similar approaches typically focus on single variants or individual genes, thereby overlooking the intricate gene–gene interactions that are pivotal according to modern theories such as the omnigenic model of genetic architecture for complex traits.
Capturing these interactions necessitates more sophisticated methodologies.
One effective approach involves leveraging gene modules based on co-expression patterns.
Machine learning methods, such as decomposition techniques and autoencoders, have demonstrated superior performance in identifying these co-expression modules by capturing latent patterns in high-dimensional datasets.
However, the reliance on co-expression alone can lead to false positives, limiting the accuracy of these modules.

To mitigate this, integrating additional data sources is essential.
For instance, PhenoPLIER exemplifies an integrative approach by combining genetic variant-trait associations from GWAS and variant-gene expression-trait associations from TWAS with groups of functionally related genes.
This integration strengthens the reliability of gene modules by cross-validating co-expression patterns with genetic evidence, thus reducing the likelihood of false positives and enhancing the biological relevance of the results.


In this review, we explore how integrating gene modeling machine learning frameworks with genetic and multi-omics data enhances our understanding of the molecular mechanisms underlying complex traits and diseases, effectively approaching genetic studies through the lens of gene networks.


## Single variant / single gene approaches 

![
**Major approaches based on single variant/single gene strategies to understand the genetic basis of complex traits**.
GWAS identifies associations between DNA variants and traits.
All the other approaches test how different molecular mechanisms might mediate variant-trait associations from GWAS.
TWAS uses variants linked to changes in gene expression (i.e., expression quantitative trait loci or eQTLs).
PWAS links protein functionality to traits via protein QTLs (pQTLs).
HAWAS maps histone modifications to traits using hQTLs, while MWAS explores DNA methylation patterns in relation to traits through mQTLs.
](images/fig1.svg "single variant/single gene strategies"){#fig:fig1 width="100%"}

### From genetic variants to traits: genome-wide association study

In a simple trait, a single gene can be responsible for the disease (monogenic), for example in the case of Sickle Cell Anemia and Huntington's disease.
However, most traits are not so simplistic and are the result of many mutations across the genome (polygenic).
Even monogenic traits can sometimes be influenced by the polygenic background [@doi:10.1038/s41467-020-17374-3].
Genome-wide association studies (GWAS) examine the relationship between specific genetic variants and phenotypes by comparing allele frequencies in individuals of similar ancestry with distinct phenotypic traits (**Figure {@fig:fig1}**).
Both causal and non-causal variants are found to be significant and due to the phenomena of linkage disequilibrium, the results of GWAS are often grouped into risk loci.
These loci represent clusters of variants that demonstrate significant associations, although not every variant may be causal [@doi:10.1186/s13059-022-02697-9].

Since the first GWAS on age-related macular degeneration (AMD) in 2005, the GWAS catalog rapidly expanded, containing SNP-trait associations across >5,000 human traits [@doi:10.1093/nar/gkac1010].
These studies have successfully identified risk loci for a variety of traits such as type 2 diabetes, auto-immune disease, schizophrenia, major depressive disorder, and many more [@doi:10.1038/s41576-019-0127-1; @doi:10.1016/j.ajhg.2017.06.005].
As GWAS participants increase, more loci are able to be identified.
For example, a study investigating insomnia with a sample size of >1M identified 202 risk loci [@doi:10.1038/s41588-018-0333-3], compared to earlier studies with a sample size of ~110,00, which were only able to identify 3 risk loci [@doi:10.1038/ng.3888].
Beyond the identification of risk loci, GWAS have also led to the discovery of novel biological mechanisms in Crohn’s disease [@doi:10.1038/ng1954; @doi:10.1038/nature13044], rheumatoid arthritis [@doi:10.1038/s41588-022-01213-w], and more.

Although GWAS have identified numerous genetic variants associated with complex traits, translating these findings into biological insights remains challenging [@doi:10.1038/s41576-019-0127-1].
For example, genes can have epistatic interactions where a secondary loci affects a primary loci.
The peripheral effects of the secondary loci are often too small to be picked up through GWAS alone [@doi:10.1016/j.tig.2011.05.007].
Furthermore, any significant GWAS variants are located in non-coding regions, making it difficult to identify the specific genes that drive trait associations [@doi:10.1093/hmg/ddac198].
A simple strategy to link GWAS-associated variants with a gene is by physical proximity, which typically selects the closest gene to the most significant SNP at each locus.
Approaches like MAGMA [@doi:10.1371/journal.pcbi.1004219] are based on proximity to compute a gene-trait association.
However, SNPs can have distal effects on the expression of the target gene [@doi:10.1126/science.aaz1776; @doi:10.1126/science.1222794; @doi:10.1038/nature13138; @doi:10.1073/pnas.112212199].


Recent approaches combine multi-omics data from various cell types and tissues with GWAS to identify potential mechanisms of SNPs and the associated gene through molecular quantitative trait loci (molQTLs) [@doi:10.1016/j.molmed.2019.10.004] (Figure {@fig:fig1}).
For example, an expression quantitative trait loci (eQTL) is a genetic region associated with the expression levels of a nearby or distant gene [@doi:10.1016/j.jgg.2023.05.003].
eQTL studies estimate that the majority of heritability is explained by the combination of multiple weak *trans*-eQTLs [@doi:10.1038/s41588-021-00913-z].

In the next section, we briefly review computational approaches that test different molecular phenotypes via QTLs to link variants with genes.
Both GWAS and QTL studies have been penalized by their large multiple testing burden, causing the need to adopt a high level of significance.
This results in GWAS being underpowered to detect all heritability explained by SNPs [@doi:10.1038/s41576-019-0127-1].

### From GWAS to gene: transcriptome-wide association studies 

Transcriptome-wide association studies (TWAS) integrate GWAS with gene expression data (**Figure {@fig:fig1}**) from eQTL analysis, to prioritize genes whose expression across different tissues is influenced by GWAS variants [@doi:10.3389/fgene.2021.713230; @doi:10.1038/s41588-019-0385-z].
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

PWAS complements GWAS and TWAS by aggregating genetic variations in protein-coding regions to assess their combined impact on protein function and phenotype (**Figure {@fig:fig1}**) [@doi:10.1186/s13059-020-02089-x].
Unlike GWAS, which focuses on individual variants, PWAS evaluates the cumulative effects of multiple coding variants, reducing the scale of multiple testing, detecting complex inheritance patterns, and offering deeper insights into potential disease links.
PWAS employs the FIRM machine learning model to evaluate how variants—such as missense, nonsense, and frameshift mutations—affect protein function by assigning impairment scores [@doi:10.1186/s13059-020-02089-x].
The aggregate effects of these variants on each gene are then assessed, followed by statistical tests to identify significant associations between gene scores and phenotypes.
For example, PWAS confirmed the association of *MUTYH* with colorectal cancer using UK Biobank data, even when no individual variant reached genome-wide significance in GWAS, highlighting its ability to uncover functional associations missed by other methods.
However, PWAS relies on high-quality proteomic data, may miss non-coding variant associations, and is computationally intensive.

Epigenome-wide association studies (EWAS) encompass methodologies such methylome-wide association studies (MWAS) (**Figure {@fig:fig1}**) and histone acetylome-wide association studies (HAWAS) (**Figure {@fig:fig1}**), based on haQTLs and mQLTs respectability, which focus on specific types of epigenetic modifications to reveal their roles in gene regulation and disease etiology  [@doi:10.1186/s13148-021-01200-8].
MWAS targets DNA methylation patterns, identifying loci where methylation changes are linked to particular traits or diseases.
For instance, a study by Shen et al. demonstrated a causal relationship between DNA methylation and depression, indicating that epigenetic modifications may mediate genetic risk for psychiatric disorders [@doi:10.1186/s13073-022-01039-5].
HAWAS focuses on histone acetylation modifications, which are crucial for regulating chromatin structure and gene expression.
Del Rosario et al.conducted a HAWAS identifying over 2,000 differentially acetylated loci in immune cells from Mycobacterium tuberculosis-infected individuals, linking these changes to gene expression and potassium channel genes like *KCNJ15* in modulating apoptosis and Mtb clearance.
haQTL analysis further revealed variants associated with immune phenotypes, complementing GWAS findings and enhancing understanding of disease mechanisms  [@doi:10.1038/s41564-021-01049-w].
The tissue-specific nature of epigenetic modifications, alongside the capacity to capture cellular plasticity and environmental influences, enhances our insight into the effects of genetic variants across distinct tissues, temporal cellular states, and gene-environment interactions [@doi:10.3390/cells9112424; @doi:10.1016/j.placenta.2007.09.011].
Despite the advancements facilitated by single variant and single gene methodologies, a common thread persists: the focus remains on one gene at a time.
The underlying expectation is that identifying a gene linked to a trait will directly unveil the biological mechanisms driving disease processes.
While this has been successful in certain monogenic disorders, complex traits often involve intricate interactions among multiple genes and environmental factors.
Consequently, the one-gene-at-a-time paradigm may oversimplify the multifaceted nature of these traits.
In light of these considerations, it becomes imperative to reevaluate our approaches to dissecting the genetic architecture of complex traits.
This necessitates a shift towards methodologies that can capture the polygenic and network-based interactions inherent in complex diseases.


## From single genes to gene networks: the omnigenic model for complex traits

### Omnigenic model as a framework for deciphering genetic architecture of traits

![
**Schematic of the omnigenic model**.
Schematic representation of the biological networks and associated phenotypes in an omnigenic context.
Nodes represent individual genes, while edges indicate functional relationships between the nodes, such as transcription factor (TF) binding, splicing events, post-translational modifications (PTMs), gene co-expression, non-coding RNA (ncRNA), and protein-protein interactions (PPIs).
The size of the arrows connecting phenotypes indicates the magnitude of their effect, with thicker arrows representing larger phenotypic influences.
iological networks are indicated by shaded regions, where genes might play a role in different networks.
Genes are categorized as “core” (diamonds) if they have a direct effect on the phenotype, or as “peripheral” (circles) if they have an indirect effect on the phenotype by moduling core genes.
Phenotypes are linked to their relevant biological networks, highlighting the interplay between different systems and their contribution to phenotypic outcomes.
](images/fig2.svg "Omnigenic model"){#fig:fig2 width="100%"}

In the early 20th century, a significant debate arose between Mendelian geneticists and biometricians concerning the inheritance of complex traits.
Mendelians emphasized single gene traits with discrete inheritance patterns, while biometricians argued that such models could not account for the continuous phenotypic variation observed in populations.
This conflict highlighted a fundamental question: how can discrete genetic factors produce continuous phenotypic variation? [@doi:10.1016/j.cell.2017.05.038; @doi:10.1073/pnas.2005634117].
The disagreement was resolved by R.A. Fisher in 1918, who introduced the infinitesimal model, demonstrating that if many genes influence a trait, their combined effects can generate continuous phenotypic distributions [@doi:10.1017/S0080456800012163].
Despite the success of Fisher’s infinitesimal model, the actual number of genes involved in complex traits and the magnitude of their effects remained uncertain for much of the 20th century.
Translating genotypes into phenotypes proved challenging due to the complexity of the genetic mechanisms driving trait variation.
In this context, GWAS brought a new perspective for identifying specific genetic variants with functional effects on complex traits.
Over a decade of GWAS has led to several unexpected findings:
The strongest GWAS associations exhibit modest effect sizes on disease risk, collectively accounting for only a minor fraction of the predicted heritability (missing heritability) [@doi:10.1038/nature08494].
It is now understood that much of this missing heritability arises from a vast number of common variants with small effects that remain undetected in current sample sizes [@doi:10.1371/journal.pgen.1008222].
A surprising uniform distribution of these small-effect significant variants exists throughout the genome, including non-coding regions, with a notable concentration in regulatory elements such as enhancers and promoters [@doi:10.1038/nature08185; @doi:10.1146/annurev-biodatasci-122120-110102].
For instance, it is estimated that 71%–100% of 1-MB windows in the genome contribute to heritability for schizophrenia [@doi:10.1038/ng.3431].
Trait variation is influenced by the broader genome, not only by genes with direct biological links to specific phenotypes.
However, the idea that nearly all genomic variants could exert direct additive effects on a given phenotype is biologically unlikely [@doi:10.1016/j.cell.2017.05.038].
In response to these unexpected findings, Boyle et al. proposed the omnigenic model  [@doi:10.1016/j.cell.2017.05.038], a conceptual framework in which the genetic architecture of complex traits could be explained by highly interconnected gene regulatory networks.
The omnigenic model reframes the earlier infinitesimal model by distinguishing between “core” genes, which have a direct biological role in the disease or trait, and “peripheral” genes, which influence core genes and thus indirectly affect the disease or trait through regulatory networks [@doi:10.1016/j.cell.2017.05.038].
The omnigenic model, unlike the traditional infinitesimal model, offers a mechanistic rationale for complex traits architecture based on molecular and cellular biology, understanding the molecular pathways that connect genetic variation to phenotypic traits (**Figure {@fig:fig2}**).

The key proposals of this model are: 1) nearly all genes expressed in cells relevant to the trait have the potential to impact the regulation of core genes 2) that for typical traits, nearly all heritability is attributable to variation near peripheral genes.
Consequently, while core genes function as the primary drivers of disease, it is the cumulative effects of numerous peripheral gene variants that determine polygenic risk [@doi:10.1016/j.cell.2019.04.014].
This framework provides a possible explanation for several previously identified problems, including widespread pleiotropy (the ability of a single gene to affect multiple traits), polygenicity (the involvement of many genes in the manifestation of a single trait), the bias effect size where small-effect variants can collectively account for a large portion of heritability, and the uniform distribution of these effects across the genome.

### Success stories of the omnigenic model

Since the introduction of the omnigenic model, numerous studies have adopted it as a framework to deepen our understanding of the genetic architecture of complex traits and the molecular mechanisms that drive them.

In schizophrenia, the application of the omnigenic model has revealed specific core gene sets associated with the disorder.
Notably, the *TCF4* gene set maintained its significant impact even after excluding SNPs within the *TCF4* gene itself.
This finding suggests that peripheral genes within the set contribute to the development of schizophrenia.
Additionally, the observed systematic floor effect across polygenic scores aligns with the model's prediction that most genes expressed in relevant cells contribute to heritability, thereby highlighting the model's potential in explaining the broad genetic contributions to complex psychiatric conditions [@doi:10.1038/s41386-019-0410-z].

Li et al. (2024) identified a significantly connected subgraph formed by cancer-affected coding genes and ncRNAs by focusing on connectivity as a key topological feature.
This approach highlighted the essential role of ncRNAs in linking fragmented cancer-affected genes, consistent with the omnigenic framework's premise that peripheral genes, including non-coding elements, contribute to complex traits such as cancer.
Importantly, the inclusion of ncRNAs enhanced the identification of cancer-related pathways, indicating that a comprehensive network model encompassing ncRNAs is more effective in characterizing disease relationships than models concentrating solely on coding genes [@doi:10.3390/e26080640].

Empirical support for the omnigenic theory extends beyond human diseases.
Sundell et al. demonstrated this concept in European black poplars, showing that both core and peripheral genes play a crucial role in predicting phenotypes.
While core genes are indeed important, the information they provide must be complemented by other genes to ensure accurate phenotype predictions.
Furthermore, peripheral genes were found to carry significant biological information contributing to robust predictions [@doi:10.1186/s12864-020-06809-2].

### Limitations of the omnigenic model: from a theoretical to a practical approach

In essence, the omnigenic model proposes a specific mechanism: that the genetic architecture of complex traits is intrinsically interconnected, involving a multitude of genes that contribute to phenotypic variation both directly (core genes) and indirectly (peripheral genes).
This framework facilitates an understanding of the highly polygenic and often subtle genetic effects on complex traits, shifting the focus from individual genes to gene networks.
While this proves successful in some fields the model exhibits certain limitations and has faced several criticisms.

One major concern is the lack of clear, quantitative methods for identifying peripheral genes or estimating their contribution to heritability.
While the model suggests that most genetic effects arise from peripheral genes, it remains unclear how to statistically define and measure these effects [@doi:10.1016/j.cell.2018.05.051][@doi:10.20900/jpbs.20170014(S2)].
Interestingly, research suggests that most heritability in complex traits is controlled by *trans* effects rather than *cis* effects, despite their small effect sizes [@doi:10.1016/j.cell.2019.04.014].
This paradox can be explained by natural selection acting most strongly against variants with large effects, limiting the contribution of directly biologically important genes to heritability [@doi:10.1016/j.cell.2019.04.014].
Thus, understanding *trans* effects, where a variant at one locus influences genes at distant loci is crucial for identifying and quantifying peripheral genes and their contribution to core traits.
However, detecting and quantifying *trans* effects remains a significant challenge due to their weak individual effects.
The omnigenic model postulates that nearly all genes expressed in cells relevant to a given trait have the potential to influence the regulation of core genes.
However, Yengo et al., in their recent GWAS on height, challenge this view.
They introduced the first "saturated" GWAS, where further increases in sample size are unlikely to yield additional genetic insights unless participant diversity or variant inclusion is expanded.
Their findings revealed that only a subset of genomic regions (~20%) seem to contribute to height determination in individuals of European ancestry.
This suggests that, at least for height, not all genes play a role in the trait as predicted by the omnigenic model [@doi:10.1038/s41586-022-05275-y].
Furthermore, the omnigenic model has been criticized for their binary classification of genes into core and peripheral, which might oversimplify biological systems and potentially underestimate their true complexity [@doi:10.1016/j.cell.2018.05.051].
It also fails to account for gene-environment interactions, which play a crucial role in shaping complex traits [@doi:10.1371/journal.pgen.1008519].
Additionally, while the model provides a conceptual framework, it remains unclear how to translate it into a practical statistical model [@doi:10.1101/2024.02.01.578486].
As George E. P. Box remarked, "all models are wrong, but some are useful." While we acknowledge that the omnigenic model simplifies the inherent complexity of biological systems and may not universally apply to all traits, we maintain that it remains a valuable framework for elucidating genetic architectures.
The model effectively bridges quantitative and molecular genetics offering comprehensive mechanistic insights with predictions on quantitative variation.
Moreover, the omnigenic model has been instrumental in shifting the focus from single gene analyses to network-based models.
Recognizing the necessity of translating this model into practical applications, machine learning-derived gene modules, which use this concept to infer gene-gene networks, offer a promising way to ground these theoretical ideas into  practical approaches.


# From gene networks to machine learning derived gene modules: hands-on strategies for inferring gene-gene interactions

![
**Computational methods for machine learning derived gene module detection.**.
**a)**.
Real biological network, where nodes represent genes and edges denote the relationships between them.
It captures all possible patterns that can link genes.
Some of these relationships are gene co-expression patterns, which transcriptomics can capture, such as (1), (3) and (4).
Other patterns, such as protein-protein interactions (2), are not captured by transcriptomics and are thus not reflected in the co-expression analysis.
**b).** Different approaches for capturing machine learning-derived gene modules.
In this example, transcriptome data is used as input, but other data types such as methylomics, proteomics, and metabolomics can also be applied.
The first row illustrates the PLIER method, which uses non-negative matrix factorization and prior knowledge to align gene modules with known biological pathways.
This approach generates interpretable gene modules but only captures linear relationships.
The second row shows a vanilla VAE, which can capture both linear and nonlinear patterns but does not integrate prior knowledge, resulting in less interpretable gene modules.
The third row highlights interpretable VAEs, which incorporate prior knowledge into its decoder, achieving a balance between capturing complex relationships and maintaining biological interpretability.
](images/fig3.svg "Omnigenic model"){#fig:fig3 width="100%"}

## From single gene analysis to gene module discovery with machine learning approaches

High-throughput technologies, particularly genome-wide gene expression profiling tools such as RNA sequencing (RNA-seq), have fundamentally transformed the landscape of molecular biology.
Unlike traditional gene-by-gene approaches, RNA-seq offers a comprehensive view of the transcriptomic landscape [@doi:10.1038/s41598-022-23985-1].
These advancements, alongside conceptual frameworks like the omnigenic model, have facilitated a paradigm shift from a single gene perspective to a module-based approach, wherein groups of genes rather than individual genes are essential for elucidating the complexities of biological networks [@doi:10.1016/j.copbio.2008.07.011].

Gene modules, a key type of biological network, consist of nodes (genes) and edges that reflect coexpression relationships between them (**Figure {@fig:fig3}a)**).
These modules, formed by genes with coordinated expression patterns under specific biological conditions, not only reveal coexpression but could also provide valuable insights into regulatory mechanisms, gene functions, and the pathways involved in traits and diseases [@doi:10.1371/journal.pone.0247671].

Numerous approaches have been proposed for module detection in gene expression data.
Machine learning (ML) techniques are particularly proficient at addressing common challenges in omics data, such as data sparsity and high dimensionality [@doi:10.1038/s41540-023-00312-6].
ML methods can compress correlations into lower-dimensional representations, facilitating the processing of large datasets to identify intricate coexpression patterns.
Additionally, ML approaches are capable of integrating various types of omics data enhancing the detection of gene modules, providing a more comprehensive understanding of biological networks [@doi:10.1038/s41540-023-00312-6].

In this context, unsupervised ML approaches have gained significant popularity [@doi:10.1126/scitranslmed.aag3101].
These methods facilitate the discovery of patterns and structures within the data without requiring prior knowledge of the system, allowing for the inference of novel findings and hypotheses.
This capability is particularly advantageous for gene module inference, which aims to identify groups of coexpressed and potentially co-regulated genes that contribute to similar biological functions [@doi:10.1038/s41467-018-03424-4].


The most common approach in unsupervised ML is clustering, with methods such as WGCNA, which has been widely used since the first gene expression datasets became available and remains one of the most popular tools today [@doi:10.1038/s41467-018-03424-4].
However, these methodologies typically rely on traditional correlation measures (e.g., the Pearson correlation coefficient), which are limited to capturing linear associations between continuous data.
Newer approaches, such as the Clustermatch Correlation Coefficient (CCC), have been developed to quantify both linear and non-linear correlations in complex gene expression datasets, providing a more flexible means of detecting intricate relationships that are not apparent through linear models alone [@doi:10.1016/j.cels.2024.08.005].

In this section, given their successful applications, we will focus on decomposition approaches like Principal Component Analysis (PCA), and deep learning methods for inferring gene modules, highlighting their effectiveness in uncovering complex gene interactions and enhancing our understanding of biological networks (**Figure {@fig:fig3}b)**).
However, we acknowledge that utilizing transcriptional data alone is insufficient for fully comprehending the intricate system of biological networks; it serves as an initial step toward a more comprehensive understanding.

### Decomposition methods

Decomposition methods reduce complex, high-dimensional gene expression data into simpler components, revealing underlying patterns and structures that aid in interpreting large-scale datasets.
These methods outperform other unsupervised machine learning approaches in recovering gene modules by effectively capturing local co-expression effects present in only a subset of biological samples, while also allowing genes to be assigned to multiple modules [@doi:10.1038/s41467-018-03424-4].

Simple models like PCA have traditionally been used to reduce dimensionality in gene expression data, offering a basic understanding of co-expressed genes [@doi:10.1088/1478-3975/acce8d].
However, these models often lack the ability to incorporate prior biological knowledge, which limits their interpretability and biological relevance.
To overcome these limitations, more sophisticated semi-supervised approaches such as the Pathway-Level Information Extractor (PLIER) [@doi:10.1038/s41592-019-0456-1], or  GenomicSuperSignature [@doi:10.1038/s41467-022-31411-3] have been developed.
These methodologies combine unsupervised approaches (decomposition methodologies) with supervised approaches to infer gene modules and annotate them with prior biological knowledge.

GenomicSuperSignature employs PCA to identify gene modules applying prior knowledge for biological annotation after module discovery.
This flexibility allows it to adapt to novel datasets and provides computational efficiency, even with large datasets.
However, the lack of prior knowledge integration during training can result in modules that are less biologically interpretable compared to those from PLIER-based methods [@doi:10.1038/s41467-022-31411-3].

The Pathway-Level Information Extractor (PLIER) (**Figure {@fig:fig3}b**) is a semi-supervised framework based on non-negative matrix factorization.
During training, it reduces high-dimensional gene expression data into a smaller set of latent variables (LVs) while aligning some of them to known pathway or gene set annotations.
These LVs are designed to capture the greatest variance in the data, where a fraction of the LVs represent known mechanisms (i.e., aligned with prior knowledge/pathways) while others capture potential technical artifacts or novel patterns.
By incorporating prior pathway/gene set information, PLIER generates interpretable latent representations.
Importantly, PLIER retains some gene modules that are not aligned with pathways, allowing researchers to distinguish LVs that represent either known patterns, technical artifacts or potential novel biological insights [@doi:10.1371/journal.pgen.1008519].

PLIER has been used to integrate large-scale gene expression data using transfer learning across multiple cell types and conditions [@doi:10.1016/j.cels.2019.04.003].
By leveraging large datasets like recount2 [@doi:https://doi.org/10.1038/nbt.3838], it enhances the accuracy of inferred gene modules by identifying patterns consistent across diverse data.
This application addresses the limitation of small datasets, such as those for rare diseases, by training a PLIER model on a large public data compendium and applying it to smaller datasets, resulting in models that align well with biological factors.
This approach improves the interpretability and reliability of gene expression patterns, particularly in complex experimental contexts.
PLIER can be used in specific cohort contexts, focusing on dissecting traits within smaller, more homogenous datasets.
Nandi et al. (2024) demonstrated its utility on the Human Trisome Project (HTP) [@url:https://www.trisome.org/], identifying gene modules that mediate the effect of karyotype on body mass index in Down syndrome, highlighting key regulators such as *GPX1* and *MCL1*.
This allows it to capture condition-specific regulatory mechanisms, but at the expense of broader generalizability, making it a powerful tool for understanding unique biological processes within specialized groups.
PLIER, initially designed for human gene expression data, has been successfully adapted for use in other species, demonstrating its versatility across different biological contexts.
By applying the framework to model organisms, researchers can infer gene modules in species beyond humans, expanding the utility of PLIER for comparative studies and translational research.
One such adaptation is MousiPLIER, which tailors the PLIER framework for use in mouse models, a widely used system in biomedical research [@doi:10.1523/ENEURO.0313-23.2024].

### Deep learning methods: autoencoders

In contrast to linear methods, non-linear models such as deep learning (DL) approaches excel at capturing complex patterns in data.
This strength has been demonstrated in various fields, including predicting gene expression directly from sequence data [@doi:10.1038/s41588-018-0160-6; @doi:10.1016/j.celrep.2020.107663; @doi:10.1016/j.crmeth.2023.100580].

DL models are also highly effective in unsupervised settings such as inferring gene modules.
Specifically, DL methods like autoencoders [@arxiv:1312.6114], which utilize neural networks to learn compressed representations, can capture both linear and nonlinear patterns between genes.
This makes autoencoders particularly suited for uncovering gene modules and efficiently handling high-dimensional datasets.
For instance, variational autoencoders (VAEs) (**Figure {@fig:fig3}b)**) enhance this process by encoding data into a continuous latent space, enabling dimensionality reduction and the generation of new data.
 However, this increased power to capture more general patterns has a major tradeoff: interpretability.
To overcome this, interpretable VAE models like the Pathway Module VAE (pmVAE) [@doi:10.1101/2021.01.28.428664], expiMap [@doi:10.1038/s41556-022-01072-x], and VEGA [@doi:10.1038/s41467-021-26017-0] integrate biological pathway information into the decoder, which improves interpretability, thus making these approaches function as linear dimensionality reduction methods.
(**Figure {@fig:fig3}b)**).

From now on, we refer to a gene module as a pattern extracted by any unsupervised approach (such as PLIER, GenomicSuperSignature, VAE, clustering, etc.) applied to gene expression data, which could be a latent variable or other types of gene cluster.


## A gene module perspective for genetic studies

![
**An integrative, gene module-based approach for genetic studies.**
Each panel shows a component of the PhenoPLIER framework [@doi:10.1038/s41467-023-41057-4].
**a)** First, latent variables (LVs) or gene modules are learned from transcriptome data using the PLIER matrix factorization method.
PLIER generates matrix $\mathbf{Z}$, which has gene weights for each module, and matrix $\mathbf{B}$, which has the samples in the latent space.
**b)** Schematic of gene-trait associations from TWAS and gene-drug scores from LINCS L1000 being projected into the latent space for a joint analysis.
**c)** Schematic of a gene module-based drug reporposing framework, where the projection of TWAS and LINCS L1000 data is used to compute a drug-disease score.
**d)** Schematic of a regression model that tests whether genes that belong to a module (using a column of $\mathbf{Z}$) tend to be more strongly associated with a trait (using $p$-values from TWAS).
**e)** (top) Example of a gene module identified as LV246 analyzed in [@doi:10.1038/s41467-023-41057-4].
*DGAT2* and *ACACA*, found in a CRISPR screen to be linked to lipid metabolism and potential core genes, were among the top 15 genes in this module.
Using metadata from the top samples for LV246 from $\mathbf{B}$, the module was found to be expressed mainly in adipose tissue, and liver and astrocyes were part of the top 10 cell types and tissues.
Using the regression model depicted in d), this module was significantly associated with high cholesterol, tryglycerides, LDL cholesterol, cholesterol lowering medication, Alzheimer's disease and dementia in the discovery cohort (UK Biobank), and high cholesterol and memory loss in the replication cohort (eMERGE).
(bottom) The $p$-values and colocalization probability from gene-trait associations from TWAS for a subset of the top 1% genes in LV246 ($y$-axis) and traits significantly associated with LV246 ($x$-axis).
It can be seen that *DGAT2* and *ACACA* (in boldface), although strongly linked to lipid metabolism, are weakly associated with these lipid-relevant traits.
](images/fig4.svg "An integrative, gene module-based approach for genetic studies"){#fig:fig4 width="100%"}

All the previously described approaches provide valuable and orthogonal information to better understand the molecular basis of human complex traits, including different molecular mechanisms through variant-trait, variant-gene, gene-trait and gene-gene information.
All of them have limitations and offer a partial view of the complex molecular interplay underlying pathophysiological processes.
In this section, we describe a gene module-based approach aimed at identifying patterns shared across these data sources.
The underlying hypothesis of this approach is that biologically meaningful, disease-relevant gene-gene links will be revealed when different yet incomplete data modalities are integrated.
In particular, we show examples on how the integration of gene modules with gene-trait associations and gene-drug data highlight core genes, disease-relevant molecular processes and drug’s mechanisms of action.

The PhenoPLIER framework [@doi:10.1038/s41467-023-41057-4] is a recent computational framework that implements this gene module-based approach.**
PhenoPLIER can integrate gene modules extracted from any transcriptome data with gene-trait associations from TWAS and drug-induced transcriptional profiles (**Figure @fig4**).
The approach integrates different molecular data sources by using a latent space derived from transcriptome data where each latent variable (LV) is a gene module (**Figure @{fig4}a)**).
Then, different data modalities are integrated into this common latent space for a joint analysis, which was shown to detect important genes missed by standard methods, capture relevant trait clusters and predict drug-disease links more accurately than state-of-the-art drug repurposing approaches.
An advantage of PhenoPLIER is interpretability: it uses gene module models from PLIER (**Figure @{fig4}a)**), which provides not only information about which genes belong to a module but also what are the top samples where those genes are expressed.
If present, by looking at the metadata of the RNA-seq datasets, it is possible to infer if those samples represent consistent conditions such as tissues, cell types, or other more complex contexts.

In PhenoPLIER, this latent transcriptional space is described by 987 gene modules derived from recount2 [@doi:10.1038/nbt.3838; @doi:10.1016/j.cels.2019.04.003] (Figure @{fig4}a), a large and highly heterogeneous expression compendia.
Given the heterogeneity of the dataset, these gene modules can capture genes expressed across different contexts such as tissues, cell types (across differentiation stages), different disease states or stimuli.
These contexts can be extracted from sample metadata.
PhenoPLIER incorporates gene-trait associations computed with the PrediXcan family of TWAS methods [@doi:10.1038/ng.3367; @doi:10.1038/s41467-018-03621-1; @doi:10.1371/journal.pgen.1007889] on two different cohorts: the UK Biobank [@doi:10.1038/s41586-018-0579-z; @doi:10.1126/sciadv.aba2083] as discovery, and the Electronic Medical Records and Genomics (eMERGE) network phase III [@doi:10.1038/gim.2013.72; @doi:10.1101/2021.10.21.21265225] as replication.
Gene-trait associations are then projected into the latent space (**Figure @{fig4}b)**) where cluster analysis on traits was performed and expected and stable groupings of traits were detected, such as asthma and allergies, heel bone-densitometry measurements, hematological assays on red blood cells, physical measures, keratometry measurements, assays on white blood cells and platelets, skin and hair color traits, autoimmune disorders, and cardiovascular diseases.
The cardiovascular grouping also included other cardiovascular-related traits such as hand-grip strength [@doi:10.1016/S0140-6736(14)62000-6], and environmental/behavioral factors such as physical activity and diet.
The PhenoPLIER approach also proposed a methodology based on interpretable classifiers to detect which gene modules are driving the different clusters.
For example, gene modules associated with the red blood cells cluster were 1) well-aligned to pathways related to early progenitors of the erythrocytes lineage, 2) predominantly expressed in early differentiation stages of erythropoiesis and 3) strongly associated with different assays on red blood cells from TWAS.
Other gene modules were associated with the keratometry measures grouping and expressed in corneal endothelial cells, and the grouping with autoimmune disorders was driven by gene modules expressed in T cells.
These results show that shared patterns exist between prior knowledge (pathways), gene expression, and gene-trait associations from TWAS.

In PhenoPLIER, information about gene-drug links is incorporated from transcriptional responses to small molecule perturbations profiled in LINCS L1000 [@doi:10.1016/j.cell.2017.10.049].
This information was integrated with gene-trait associations to build a gene module-based drug repurposing framework with the purpose of assessing how substituting LVs for single genes predicted known treatment-disease relationships better (**Figure @{fig4}c))**).
Based on an established drug repurposing strategy that matches reversed transcriptome patterns between genes and drug-induced perturbations [@doi:10.1126/scitranslmed.300264; @doi:10.1126/scitranslmed.3001318], in PhenoPLIER the authors adapted an existing drug repurposing framework [@doi:10.1038/nn.4618] that uses single gene information from TWAS to gene modules.
Then, these two approaches, the single gene-based and gene module-based one, were compared using a manually-curated gold standard set of drug-disease medical indications [@doi:10.7554/elife.26726; @doi:10.5281/zenodo.47664] for 322 drugs across 53 diseases to evaluate the prediction performance.
The gene module-based approach outperformed the single gene-based one with an area under the curve of 0.63 vs 0.57, and average precision of 0.86 vs 0.64.
Although the performance difference in this task was not large, the authors noted that the gene module-based approach represents a compressed version of the entire set of single gene-based results, and the higher performance implied that the low-dimensional latent space used (which necessarily misses some information) captured biologically meaningful gene-gene patterns.
Additionally, since gene modules represent interpretable features, the authors found that lipid-related gene modules expressed in adipose tissue and liver were among the top modules contributing to the prediction of high cholesterol and Nicotinic acid (Niacin, which can treat lipid disorders), potentially resembling known mechanisms of action of Niacin such as decreasing the production of low-density lipoproteins (LDL) either by modulating triglyceride synthesis in hepatocytes or by inhibiting adipocyte triglyceride lipolysis [@doi:10.1016/j.amjcard.2008.02.029].

The PhenoPLIER framework is also able to compute an association between a gene module and a trait by integrating single gene TWAS results (**Figure @{fig4}d)**).
The association is computed using a regression model that tests whether genes that strongly belong to a module (using a column in matrix Z in (**Figure @{fig4}a)**) are also strongly associated with the trait (using a row in the yellow TWAS matrix in **Figure @{fig4}b)**.
For validation, the study conducted a CRISPR Cas9 screen in the HepG2 (liver) cell line to identify genes associated with lipid regulation, and found a high-confidence lipid-increasing gene set that included genes *DGAT2* and *ACACA*, which fit the definition of core genes.
The gene module identified as LV246 (**Figure @{fig4}e)**) was the module most strongly enriched with this lipid-increasing gene set, containing *DGAT2* and *ACACA* among the top 15 genes most strongly connected with the module.
LV246 was found to be 1) aligned with lipid metabolism pathways, 2) expressed in adipose tissue, liver, astrocytes, among others, and 3) significantly associated with lipid-related traits in the discovery cohort (UK Biobank; **Figure @{fig4}e)**) and replication cohort (eMERGE), such as high cholesterol, triglycerides, LDL cholesterol and cholesterol lowering medications in the UK Biobank, and high cholesterol (hyperlipidemia, phecode 272.11) in eMERGE.
Although a direct link between lipids and *DGAT2* and *ACACA* was found by the CRISPR screening, the authors noted that these genes lack strong TWAS associations with any of these lipid-related traits (**Figure @{fig4}e)**, bottom).
The GWAS Catalog shows that genetic variants in *DGAT2* were found to be associated with cholesterol levels [@url:https://www.ebi.ac.uk/gwas/genes/DGAT2], but *ACACA* lacks any association with these phenotypes [@url:https://www.ebi.ac.uk/gwas/genes/ACACA].
A potential explanation provided by the study says that, based on the omnigenic model, *DGAT2* and *ACACA* could represent core genes, and most of the other genes in LV246 might be peripheral genes that potentially *trans* regulate them.
This example suggests that strong GWAS hits could represent either peripheral or core genes, and that some core genes might be missed by GWAS alone.

Additionally, another interesting trait association in module LV246 was with Alzheimer’s disease (AD) and dementia in the UK Biobank, and memory loss (phecode 292.3) in eMERGE, which tends to worsen as AD progresses [@doi:10.31887/DCNS.2013.15.4/hjahn].
The association with AD is relevant since this module was also found to be expressed to some degree in astrocytes, and has *APOE* as one of the top genes (**Figure @{fig4}e)**, bottom).
*APOE*, the gene most strongly associated with late-onset AD [@doi:10.1126/scitranslmed.aaz4564], encodes apolipoprotein E (ApoE), which is involved in lipid transport in the brain [@doi:10.1186/s13024-022-00574-4], a mechanism that, when dysregulated, may play an important role in AD pathogenesis.
From TWAS alone, it can be seen that *APOE* is strongly associated and colocalized with the same traits as LV246 (**Figure @{fig4}e)**, bottom).
However, a recent systematic survey across clinical trials that evaluate ApoE-targeted drugs for AD found modest to no efficacy in the treatment for this disease [@doi:10.1212/WNL.00000000002048].
Although there is strong evidence that *APOE* is a causal gene for AD, it still remains to be determined whether it represents a core gene or plays a more peripheral role.
A gene module-based approach might help prioritize core genes that remain elusive when using standard single-gene strategies.

Another approach to compute an association between gene modules and traits is MAGMA gene-set analysis [@doi:10.1371/journal.pcbi.1004219].
Actually, the regression model used by PhenoPLIER is based on MAGMA.
The difference is that PhenoPLIER uses gene-trait association from the PrediXcan family of TWAS methods, while MAGMA does not incorporate eQTL data and it uses a proximity-based approach in linking variants with genes.
Another difference is that MAGMA allows to perform conditional and interaction gene-set analysis to account for correlated gene modules, and the approach was found to be useful in detecting novel pathways in the context of blood pressure [@doi:10.1038/s41467-018-06022-6].
The use of eQTL data by TWAS, however, might fit better the gene regulatory network assumptions of the omnigenic model than proximity-based approaches like MAGMA.

Approaches based on gene modules have the potential to go beyond prior knowledge and capture patterns that might be unique to different disease datasets.
First, although a gene module can be aligned to a pathway, this does not mean that it is restricted to prior knowledge as in standard pathway analyses.
Being aligned with pathways means that a module resembles a known mechanism, and this helps in interpretability and also in separating from other patterns that might be related to technical noise but the module could capture other genes as well that are not part of the pathway but potentially also involved the function.
Second, gene modules can also be extracted from very large, heterogeneous datasets such as recount2, or more specific ones such as the Human Trisome Project, which includes gene expression from people with Down Syndrome (DS).
Approaches such as PLIER and PhenoPLIER have been fundamental to extract DS-specific gene modules related to obesity, a common co-occurring condition The omni-PLIER framework, combining the PLIER model with the omnigenic approach, uncovers molecular mechanisms linking Down syndrome (DS) and obesity, identifying key latent variables with top genes such as GPX1 and MCL1, which mediate the relationship between trisomy 21 and body mass index (BMI), offering insights into DS-specific and general obesity-related processes. `[CITE Sutanu’s paper]`{.yellow}.

A disadvantage of the PhenoPLIER approach is that gene modules are generated by an algorithm, and as such, they could represent artifacts or be aligned with technical noise.
Interpretable methods such as PLIER and some VAE models that help segregate technical noise from relevant biology are key in solving this problem.
Another limitation is the potential difficulty in determining the contexts in which a gene module is expressed.
In the example of LV256 and lipid-related traits, the module was also found to be expressed, with different degrees, in tumor samples, skin, skeletal muscle and other contexts that might be hard to interpret.
The interpretability advantage is also limited by the quality of the RNA-seq metadata.
Additionally, compared with GWAS and TWAS, where the unit is an objective molecular entity (a SNP or gene in a particular chromosome and position), a gene module not only might or might not exist, but the algorithm could fail to capture all gene modules relevant for a particular study, which could bias any downstream analysis.
Finally, a gene module, equivalent to a gene co-expression network, represents a set of correlated genes’ expression in some conditions, but it does not provide information about gene-gene links (it’s not directed) and could include many false positives [@doi:10.1038/s41576-023-00618-5].
Future approaches should also incorporate other data modalities to refine a gene module such as transcription factor binding data or chromatin accessibility.

Although there are several limitations when we only correlate gene pairs across RNA-seq samples [@doi:10.1038/s41576-023-00618-5], integrating gene networks with other data modalities have the potential to identify disease-relevant molecular mechanisms [@doi:10.1371/journal.pgen.1008519].
Here we described an approach that integrates gene modules with other data sources such as gene-trait and gene-drug information.
The underlying hypothesis of this approach is that biologically meaningful gene-gene links will be captured when different data modalities that at least partially capture these links are integrated.
In our examples, these data modalities are gene modules from transcriptome data, single gene-trait associations and single gene-drug links via drug-induced transcriptional profiles.
We also showed that if the unsupervised approach used to extract a gene module is also interpretable (i.e., provides information about the specific contexts such as cell types or tissues that explain why those genes were grouped together), the data integration approach also sheds light on potential context-specific transcriptional mechanisms.


## Future perspectives {.page_break_before}


## Conclusions {.page_break_before}


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>

