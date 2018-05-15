# gene_sets

Autosomal protein-coding gene sets, with chromosomal coordinates of the longest or canonical transcript (hg19). All gene names have been standardized using the HGNC-approved symbols and gene sets are restricted to protein-coding genes (defined by HGNC locus group).

1. protein_coding_genes.bed -- all protein coding genes. Total of 17,695 genes.
2. mendelian_genes.bed -- all Mendelian disorder genes in OMIM with the following criteria: (1) disorder is Mendelian and fully penetrant, therefore excluding susceptibility phenotypes and (2) molecular basis of the Mendelian disorder is known (i.e., phenotype mapping key = 3). Total of 3,466 genes.
3. lof_genes.bed -- all loss-of-function intolerant genes, as defined by ExAC's pLI score > 0.9. Total of 2,978 genes.

4. Mendelian disorder gene sets for specific traits, created from mining OMIM for phentoype-specific clinical keywords and restricting to entries satisfying the same criteria (1) and (2) as described above, and with the following additional criteria: (3) gene-phenotype association description does not contain “genome-wide association study” or other GWAS synonyms unless: the description also contains any of the terms “missense”, “nonsense”, “nonsynonymous”, or “frameshift”; or the gene contains at least one pathogenic or likely pathogenic allele in the ClinVar database. 


