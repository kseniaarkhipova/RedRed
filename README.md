# RedRed: Reducing Redundancy script using iterative approach

Script allows cluster DNA sequences in accordance to nucleotide homology. It especially suits for clustering sequences of viral genomes (as assume possible circularity of genome) and big datasets, as allows work in batches to fit memory limits.

## Dependencies
Python 3.5.2

MUMMER 3.23 http://mummer.sourceforge.net
## Usage
    RedRed --fna dna_sequences_to_cluster.fasta

## Output

RedRed outputs two files: 

*File 1. Fasta file with representative sequences of individual clusters
*File 2. File with clusters information; first name in each row is a name of representative, which was included in File 1 
