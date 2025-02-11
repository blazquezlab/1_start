# Start

Entry-point to all the repos and documents for the lab members. Here you will find the links to all the relevant scripts, workflows and guides.

## Downstream Analysis Scripts

- [`R utils`](https://github.com/blazquezlab/R-utils): a variety of R scripts for data visualization (boxplots, heatmaps, PCA, UMAP...) of **differential expression** and **alternative splicing** summary tables (TPMs and events).
- [`sashimi plots`](https://github.com/meryhidalgo/sashimiplots): terminal-based (Bash) script to generate grouped sashimi plots from a list of events and BAM files.
- [`MaxEntScan analysis`](https://github.com/blazquezlab/MaxEntScan): Instructions to get MaxEntScan scores programatically by perl scripts


## Automated Workflows

- [`Salmon & VAST-tools`](https://github.com/blazquezlab/Salmon-VAST_tools): scripts to:
  - generate and filter TPMs starting from Salmon *quant-files*
  - generate and filter event-tables starting from VAST-tools FULL_INCLUSION tables
- [`Lexogen Nextflow`](https://github.com/blazquezlab/lexogen_pipeline): Nextflow-based pipeline to QC, demultiplex, align (STAR), deduplicate and quantify (featureCounts) Illumina reads with barcodes and UMIs. It can be run eihther on a local machine (EPI2ME app) or on a cluster (SLURM).
- [`Plasmidsaurus Worflow`](https://github.com/blazquezlab/plasmidsaurus_workflow): terminal-based (Bash) script to QC, align and plot (sashimis) FASTQs from Plasmidsaurus.
- [`Plasmidsaurus Nextflow`](https://github.com/blazquezlab/plasmidsaurus_nextflow): same as the above, but Nextflow-based (i.e. EPI2ME app or SLURM).
- [`Basecalling`](https://github.com/blazquezlab/basecalling): utility scripts to basecall Nanopore FAST5s with Guppy or Dorado basecallers.
- [`VIVE Pipeline`](https://github.com/blazquezlab/vive-pipeline): Nextflow-based pipeline to process viral RNA for the VIVE Biotech project.
- [`Illumina -> Nanopore`](https://github.com/blazquezlab/illumina2nanopore): Nextflow-based pipeline to process Nanopore reads prepared with Illumina kits (Illumina adapters, UMIs, etc.).
- [`rMATS pipeline`](https://github.com/blazquezlab/rmats_pipeline): BASH based scripts to run multiple rMATS contrasts in parallel using SLURM array jobs.


## Guides

- [`Atlas`](https://github.com/blazquezlab/1-Access-to-Atlas-and-Instructions): instructions on how to use the cluster.
- [`Conda`](https://github.com/blazquezlab/conda_envs): instructions on how to create and manage Conda environments.
- [`Bind FASTQs`](https://github.com/blazquezlab/binding_FASTQs): instructions on how to bind FASTQs coming from the same sample.
- [`Download EGA`](https://github.com/blazquezlab/download_pyega): instructions on how to download files from the EGA repository using their API.
- [`Custom Reference Files`](https://github.com/blazquezlab/custom_references): intructions on how to create custom FASTA, GTF and BED files for non-standard genomes. Additionally, it includes instructions on how to create IGV `.bam` lists to visualize multiple samples at once.
- [`Adaptive Sampling Guide`](https://github.com/blazquezlab/adaptive_sampling): step-by-step guide on how to prepare an adaptive sampling experiment on the P2Solo.
