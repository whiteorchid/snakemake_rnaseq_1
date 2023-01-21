# snakemake_rnaseq_1
This is the record of process that to setup/write and use snakemake workflow to analysis RNAseq data, both upstream and downstream differential expression analysis and plots.


# 

The very basic compenent is the Snakefile in the workflow directory, define the tasks to run; the envs directory under the workflow can include each of the tools, say, if use conda environment, can define the channels and the tools name(plus the version), then when run the snakemake, the tools will be installed automatically. 

.
├── config
│   ├── config.yaml
│   └── config.ymal.bak
└── workflow
    ├── envs
    │   ├── fastp.yaml
    │   └── kallisto.yaml
    └── Snakefile
