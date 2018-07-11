# awesome-cancer-variant-databases
A community-maintained repository of cancer clinical knowledge bases and databases focused on cancer and normal variants. [Contributions welcome](https://github.com/seandavi/awesome-cancer-variant-databases/blob/master/CONTRIBUTE.md]).

Also see our [bioRxiv manuscript, *Resources For Interpreting Variants In Precision Genomic Oncology Applications*](https://doi.org/10.1101/144766) and [Frontiers in Oncology Publication](https://doi.org/10.3389/fonc.2017.00214)

## Clinically-focused databases

- [CanDL](https://candl.osu.edu/) - an expert-curated database of potentially actionable driver mutations for molecular pathologists and laboratory directors to facilitate literature-based annotation of genomic testing of tumors. [web app, Download]
- [Cancer Genome Interpreter](https://www.cancergenomeinterpreter.org/) - designed to support the identification of tumor alterations that drive the disease and detect those that may be therapeutically actionable. CGI relies on existing knowledge collected from several resources and on computational methods that annotate the alterations in a tumor according to distinct levels of evidence. [web app, API]
- [CiViC](https://civic.genome.wustl.edu/#/home) - CIViC is an open access, open source, community-driven web resource for Clinical Interpretation of Variants in Cancer. [web app, API, Download]
- [DGIdb](http://dgidb.genome.wustl.edu/) - Mining the druggable genome for personalized medicine. [web app, API, Download]
- [Database of Curated Mutations (DOCM)](http://docm.genome.wustl.edu/) - DoCM, the Database of Curated Mutations, is a highly curated database of known, disease-causing mutations that provides easily explorable variant lists with direct links to source citations for easy verification. [web app, API, Download]
- [JAX Lab Clinical Knowledge Base](https://ckb.jax.org/) - The Jackson Laboratory Clinical Knowledgebase (CKB) is a semi-automated/manually curated database of gene/variant annotations, therapy knowledge, diagnostic/prognostic information, and clinical trials related to oncology. [web app]
- [MyCancerGenome](https://www.mycancergenome.org/) - My Cancer Genome is a personalized cancer medicine knowledge resource for physicians, patients, caregivers and researchers.  My Cancer Genome gives up-to-date information on what mutations make cancers grow and related therapeutic implications, including available clinical trials. [web app, API, Download, *may require licensing*]
- [OncoKB](http://oncokb.org/) - OncoKB, a comprehensive and curated precision oncology knowledge base, offers oncologists detailed, evidence-based information about individual somatic mutations and structural alterations present in patient tumors with the goal of supporting optimal treatment decisions. [web app, API, Download]
- [PharmGKB](https://next.pharmgkb.org/) - PharmGKB is a comprehensive resource that curates knowledge about the impact
of genetic variation on drug response for clinicians and researchers. [web app, Download]
- [Precision Medicine KnowledgeBase (PMKB)](https://pmkb.weill.cornell.edu/) - PMKB is organized to provide information about clinical cancer variants and interpretations in a structured way, as well as allowing users to submit and edit existing entries for continued growth of the knowledgebase. All changes are reviewed by cancer pathologists. [web app, Download]

## Catalogs

- [EpiTAD](https://gerkelab.shinyapps.io/EpiTAD/) - Compare genomic structures (e.g. topologically associating domains) and annotations across multiple databases and platforms in an interactive platform. [web app]
- [Oncotator](http://portals.broadinstitute.org/oncotator/) - Oncotator is a tool to annotate point mutations and indels with functional data relevant to cancer researchers. Annotations include gene names, functional consequence (e.g. Missense), PolyPhen-2 predictions, and cancer-specific annotations from resources such as COSMIC, Tumorscape, and published MutSig results. [web app, API, Download]
- [SNPinfo](https://snpinfo.niehs.nih.gov/) - Several tools that comprehensively utilize computational functional estimates, experimental and epidemiological information together with recent genome wide association study (GWAS) results and linkage disequilibrium (LD) information to prioritize SNPs for further genetic mapping studies. [web app]
- [VarSome](https://varsome.com) - Large, online aggregation database of variants. VarSome is a knowledge base and aggregator for human genomic variants. We were frustrated with the amount of time it takes to look up variants in a number of public databases, and we decided to act. The result is a comprehensive resource that will save you both time and effort when looking up variant information. [example API query](https://api.varsome.com/lookup/15-73027478-T-C)

### Somatic

- [COSMIC: Catalogue of Somatic Mutations in Cancer](http://cancer.sanger.ac.uk/cancergenome/projects/cosmic/) [web app, Download]
- [ISB Cancer Genomics Cloud Pilot Bigquery Table for TCGA](https://bigquery.cloud.google.com/welcome/isb-cgc) [Web database, export as csv, json, etc.]

### Germline

- [dbSNP](http://www.ncbi.nlm.nih.gov/SNP/) - [Web app, API, Download]
- [GnomAD](http://gnomad.broadinstitute.org/) - The Genome Aggregation Database (gnomAD) is a resource developed by an international coalition of investigators, with the goal of aggregating and harmonizing both exome and genome sequencing data from a wide variety of large-scale sequencing projects, and making summary data available for the wider scientific community. The data set provided on this website spans 123,136 exome sequences and 15,496 whole-genome sequences from unrelated individuals sequenced as part of various disease-specific and population genetic studies. [Web app, Download]
- [Kaviar](http://db.systemsbiology.net/kaviar/) - Kaviar (~Known VARiants) is a compilation of SNVs, indels, and complex variants observed in humans, designed to facilitate testing for the novelty and frequency of observed variants. Kaviar contains 162 million SNV sites (including 25M not in dbSNP) and incorporates data from 35 projects encompassing 77,781 individuals (13.2K whole genome, 64.6K exome). - [web app, API, Download]
- [Exome Aggregation Consortium](http://exac.broadinstitute.org/) - [Web app, API, Download]
- [1000 Genomes](http://www.1000genomes.org) - [Web app, API, Download]
- [ClinVar](http://www.ncbi.nlm.nih.gov/clinvar/) - [Web app, Download]
- [Exome Sequencing Project](http://evs.gs.washington.edu/EVS/) - [Web app, Download]
- [Genome of the Netherlands](http://www.nlgenome.nl/)
- [UK10K](http://www.uk10k.org/)
- [GEUVADIS: Genetic European Variation in Health and Disease](http://www.geuvadis.org/web/geuvadis/home)
- [SweGen](https://swefreq.nbis.se/#/) - [Web app, API, Download]

## Annotation tools and software

- [PCGR](https://github.com/sigven/pcgr) - The Personal Cancer Genome Reporter (PCGR) is a stand-alone software package for functional annotation and translation of individual cancer genomes for precision oncology. It interprets both somatic SNVs/InDels and copy number aberrations. The software extends basic gene and variant annotations from the Ensembl’s Variant Effect Predictor (VEP) with oncology-relevant, up-to-date annotations retrieved flexibly through vcfanno, and produces interactive HTML reports intended for clinical interpretation. - [Software tool]

## Variant Effect Prediction tools and databases

- [ANNOVAR](http://annovar.openbioinformatics.org/en/latest/) - Functionally annotates genetic variants across several databases for gene/region/filter-based annotation, along with other functionalities. [Software tool, web app at [wANNOVAR](http://wannovar.wglab.org/index.php)]
- [fannsdb](http://bbglab.irbbarcelona.org/fannsdb/) - Combines ConDEL and TransFIC annotations. FannsDB is a database for Functional ANnotations for Non Synonymous SNVs which contains precalculated scores for several predictors. [Web app, Download]
- [dbNSFP](https://sites.google.com/site/jpopgen/dbNSFP) - [Download]
- [myvariant.info](http://myvariant.info/) - [Web app, API]
- [PolyPhen-2](http://genetics.bwh.harvard.edu/pph2) - [Software tool, Download]
- [SIFT](http://sift.jcvi.org)
- [MutationAssessor](http://mutationassessor.org)
- [MutationTaster](http://www.mutationtaster.org)
- [PROVEAN](http://provean.jcvi.org/index.php)
- [CADD](http://cadd.gs.washington.edu)
- [GERP++](http://mendel.stanford.edu/SidowLab/downloads/gerp/index.html)
- [PhyloP and PhastCons](http://compgen.cshl.edu/phast/index.php)
- [nsSNPAnalyzer](http://snpanalyzer.uthsc.edu/)
- [SnpEff](http://snpeff.sourceforge.net/) - Variant annotation and effect prediction tool that annotates and predicts the effects of variants on genes (such as amino acid changes). [Software tool]
- [SNPs&GO](http://snps-and-go.biocomp.unibo.it/snps-and-go)
- [SNAP2](https://rostlab.org/services/snap2web/)
- [SNPs3D](http://www.snps3d.org/)
- [MutPred2](http://mutpred.mutdb.org/)
- [AUTO-MUTE](http://binf2.gmu.edu/automute/)
- [Panther](http://www.pantherdb.org/tools/csnpScoreForm.jsp)
- [stSNP](http://ilyinlab.org/StSNP/)
- [Condel](http://bg.upf.edu/fannsdb/) - a weighted average of multiple methods 
- [CoVEC](https://sourceforge.net/projects/covec/files)
- [CAROL](http://www.sanger.ac.uk/science/tools/carol)
- [CHASM](http://wiki.chasmsoftware.org/index.php/Main_Page)
- [CanDrA](http://bioinformatics.mdanderson.org/main/CanDrA\#CanDrA) - 96 structural, evolutionary and gene features 
- [Variant Effect Predictor](http://useast.ensembl.org/info/docs/tools/vep/index.html) - Determines the effect of your variants (SNPs, insertions, deletions, CNVs or structural variants) on genes, transcripts, and protein sequence, as well as regulatory regions. [Web app, software tool, API]
