# nanopore-oral-genomes
This repository contains supplemental data files for the publication "Using nanopore sequencing to obtain complete genomes from saliva samples" by Jonathon L. Baker, PhD. If you use this data, please cite this GitHub repository (or the publication, when that goes live).

-The "G6-polypolish-assemblies" folder contains reassemblies of JB001 and JB003 using metaFlye and Polypolish for comparison with the current NCBI versions (GenBank accession numbers: CP072208 and CP076102) which were assembled using Unicycler, metaFlye, Trycycler, Medaka, and Pilon, and then manually corrected.

-The "TM7c-JB-assemblies" contains the draft assemblies of TM7c-JB from various stages of assembly process:  metaFlye, Unicycler, Trycycler, Pilon, and Medaka.  These can be compared to the NCBI assembly of TM7c-JB, which is GenBank accession number CP090820.1.

-The "draft-assemblies" folder contains the draft assemblies of Actinomyces graevenitzii JCVI-JB-Ag28, Lachnospiraceae HMT-096 JCVI-JB-L28, Rothia mucilaginosa JCVI-JB-Rm28, and Ruminococcaceae HMT-075 JCVI-JBR28-chr1.  Ruminococcaceae HMT-075 JCVI-JBR28-chr1 is likely to be highly accurate, but was not deposited to NCBI because it is only one chromosome of what is almost certainly a multi-chromosome genome.  The other three draft assemblies had poor coverage of Illumina reads for polishing, and therefore are likely to retain many errors for the ONT seqeuncing.

-The "pangenomes" folder contains the data tables of the pangenome information for Actinomyces, Atopobiaceae, Mogibacterium, Rothia, and Saccharibacteria (only complete genomes were considered in these analyses.
