# hpc-gatk4

This repo replaces the script previously located at `/scratch/work/cgsb/scripts/variant_calling/gatk4`

### Instructions for use
After building your `nextflow.config` file and loading the nextflow module (ex: `module load nextflow/20.11.0-edge`), use the following command to call the script directly from this repo, where the `-r` parameter specifies the version of the script you would like to run.

`nextflow run gencorefacility/hpc-gatk4 -c nextflow.config -r v1.1`

`v1.0` is the original version of the script which was previously located at `/scratch/work/cgsb/scripts/variant_calling/gatk4`. Use this version to reproduce a previous analysis or analyze new data using the same pipeline.

`v1.1` is an updated version of the script which uses an updated version of GATK4 (4.2.4.1). 
