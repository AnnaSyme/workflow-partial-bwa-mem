# workflow-partial-bwa-mem

These workflows are part of a set designed to work for RAD-seq data on the Galaxy platform, using the tools from the Stacks program. 

Galaxy Australia: https://usegalaxy.org.au/

Stacks: http://catchenlab.life.illinois.edu/stacks/

This workflow is part of the reference-guided stacks workflow, https://workflowhub.eu/workflows/347

Inputs
* demultiplexed reads in fastq format, may be output from the QC workflow. Files are in a collection. 
* reference genome in fasta format

Outputs
* A set of filtered bam files, ready for the next part of the stacks workflow (e.g. gstacks). 
* Statistics on the bam files. 

