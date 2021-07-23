#!/bin/bash 
#BSUB -J jobname
#BSUB -e log/output.err
#BSUB -o log/output.out
#BSUB -q zhaolabgpu
#BSUB -n 36


# write by hanwei
# 20210720


source alphafold.config

# run the alphafold2
python /share/apps/alphfold/alphafold/docker/run_docker.py --fasta_paths=input.fasta --max_template_date=2021-07-20 --preset=casp14
