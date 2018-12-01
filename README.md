# Analysis tools for split-seq

## Requirements

Requires python 3.

Additional software needed:

- [STAR](https://github.com/alexdobin/STAR)
- [samtools](https://github.com/samtools/samtools)

To install all dependencies, try running `install_dependencies.sh`, which installs dependencies to `~/split_seq_reqs/`.

To install the package: run `pip install -e .` (might need sudo).

## Running the pipeline

To see all options, run `split-seq -h`.

To run the entire pipeline on a given dataset:

`split-seq all <fastq-1> <fastq-2> <output-dir> --genome-dir <genome dir with STAR index> --gtf_file <path to gtf file>`

## References
