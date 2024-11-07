# Assignment_solutions
# Create environment with dependencies

Install a conda environment with nextflow, nf-core and singularity

```console
$: conda create -n rnaseq -c bioconda nf-core nextflow singularity
```

Activate the environment

```console
conda activate rnaseq
```
Run the bioinformatic analysis (you need to work in an HPC environment provided with slurm)
```console
$: sbatch rnaseq.sbatch
```

To perform statistical analysis go to `02-deg_analysis` and follow the steps in `results_report_statistical_analysis.Rmd`.
