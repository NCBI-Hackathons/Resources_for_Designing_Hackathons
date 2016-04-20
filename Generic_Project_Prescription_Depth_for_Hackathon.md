Topics/Datasets and Personnel (Team leads) -- Groups may change based on lead and participant interest

1. RNAseq for Every Biologist - *Overall scope.  Make a product where users can upload their data and compare it to background datasets*

        1. Mapping all NCBI human RNAseq data with HISAT, BLAST mapper (subset), srprism and maybe rails -- Proposed title: Homogenous mapping of 50,101 RNAseq runs to the human genome 

            1. Scan through samples for quality 

                1. Eliminate crap

                2. Soft mask when necessary

                    1. Design a heuristic

                    2. What about second pass?

            2. Automatically take in new files and integrate

            3. Potential IO problems -- ask someone from storage to sit in.

                3. Push into SRA format

                4. HISAT --mm (shares the index across processes)

            4. Trying out Lior Pachter’s new tool?  

        2. Automated Pipeline to build .nif (normalized interchange format) files -- Proposed title: Building a pipeline for automated upload and comparison of RNAseq expression data; establishing a standard format for this process

            5. Possibly similar to a GEO Matrix file

                5. The idea is to be able to make a volcano plot

                6. Data structures for rows and columns can be arbitrarily complex

                    3. Would this work to move as one file.  

                        1. Illumina uses .ini to put data in blocks

                            1. And this makes it compressable.

            6. This would be a pipeline biologists can run on the cloud.  

            7. Dumps to R and compares with controls from below project

            8. Even if not a normalized format, just a wig comparer   

            9. PhiX controls

            10. Comparing to splign data

        3. Subproject: Large Scale Metadata Normalization and Sequence Acquisition.

                7. Proposed title: Metadata Normalization for RNAseq Analysis.  

                8. Dividing cell types from biosample .xml to come up with baseline sets.  

                9. Personnel: Two members of the translational genomics superteam, one member of the RNAseq team 

NOTE: Scanning over library prep metadata to determine which subsets from 1.1.2 will not work for the gene-specific comparison table

FUTURE PROJECT: Clustering data profiles based on principal component isoform expression (with elimination of PC1)

1. Translational Genomics 

    1. Designing a variant centered NGS scanner for rapid analysis 

        4. Pipeline to scan for ClinVar variants from DNAseq, RNAseq, or .vcfs  

            11. Jumping off last year’s RNAseq project

                10. Working with RNAseq mapping folks

                    4. Starting with multiple myeloma genome data (DNAseq)

                        2. Can also scan Multiple Myeloma exon sets

                    5. Then HISAT team data

                11. Scanning RNAseq data for dbvar-like structural variants 

                12. Dealing with alts.  

                13. Tophat fusion?

    2. Multiple myeloma Pharmacogenomics -- Proposed title: Molecular Matching in Myeloma: Combining RNA-Seq Data with Drug Response Profiles

        5. [Prospective prediction of combinatorial performance]

        6. Single agent - genomic interaction prediction

            12. Feature correlations of drug response or resistance

                14. Clustering program to compare 2K drugs to expression in and variance of 30K genes

                    6. DO EXPRESSION DIFFERENCES, ISOFORM DIFFERENCES OR POINT MUTATIONS CLUSTER WITH SENSITIVITY TO CHEMICAL CLASSES?

                    7. Chemical clustering?

                    8. Transcript clustering

            13. Drug class searchability

                15. Tagging

            14. RNAseq data analysis 

                16. Crossing with GEO and pre-GEO data

                17. Add patient filter

            15. Making the system modular for later refinement

                18. Other data types

        7. Data

            16. (60) Cell lines (all before drug response)

                19. RNAseq

                    9. Expression

                    10. Isoform Specificity

                        3. (Use the SEQR Mapper)

                    11. Call variants from RNAseq data

                        4. Start with this [https://github.com/DCGenomics/hackathon_v001_rnaseq](https://github.com/DCGenomics/hackathon_v001_rnaseq)

                            2. Just fork this repo onto theirs

                20. Variant Data

                    12. (ClinVar scanner)

                21. cGH data (only baseline)

                22. Drug response data

        8. Prior examples of approaches

            17. [https://www.broadinstitute.org/software/cprg/?q=node/11](https://www.broadinstitute.org/software/cprg/?q=node/11)

                23. Referenced Nature paper

            18. [https://www.broadinstitute.org/mmgp/hom](https://www.broadinstitute.org/mmgp/home)

            19. dbGaP -- Pipelining the way this is done with the above team

                24. Proposed title: Automated Genome Selection from Complex Phenotypic Data in dbGaP

                25. Initializing dbGaP analysis in Amazon and Google Cloud

                26. Reads + SNPChips

                27. Creating indices for new genomes and remapping

                28. Using GRU and Specifically, phs000748

 

2. Democratizing Genomics - Ben Busby

    3. VM for NCBI Online Workshop -- Proposed title: Building an Educational Environment to Teach Genomic Mapping and Ultrafast BLAST; .sam Format Comparison

        9. Can compare vdbBLAST with mapping (HISAT and BLASTmapper) and come out with a score or scores. (sam comparer?)

            20. Compare scores for different alignments and parameters 

                29. For lists of genes

            21. Benchmark this, such that if used correctly, total cost will come in well under $100.  

                30. * By accepting this credit, you are acknowledging that NCBI is in no way responsible for any overage charges,  

    4. Proposed title: Using SEQR (PSSM BLAST) to map RNAseq and DNAseq Datasets - Team Organized; has google group

        10. Making SEQR work on the command line and with NGS Output!  

        11. Check for differences if time 

            22. Domain comparison?

            23. Trinity feed-in?

            24. Enrichment

        12. Verification by splice junction analysis -- potential software test

3. Product testing

The section leads will be responsible for writing tests for the other two sections

Test parameters for RNAseq

User comes with RNAseq data

This will come from things that we know are represented in the metadata space.

This will come from pre-generated toy examples made from NCBI experiments  

Makes normalized reads

Uploads and compares with appropriate samples from standard db.  

Test parameters for Translational Genomics

Test parameters for BLAST/Virtual Machines 

Project management utilities

Trello

Docs

Coders Crowd

Docker Images

Github issues

Gitter chat (for groups of up to 25)

Preparing this for publication

Need writers!

and an organizer

	

