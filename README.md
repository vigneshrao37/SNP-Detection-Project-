# SNP-Detection-Project-

Motivation:

Many  bacterial  organisms  can  live  and  grow  in  our  bodysome  of  which  are pathogenic  (i.e.  cause  disease) andcan  be  treated  withantibioticmedication. Howeverextended use of an antibioticmedicationcan encouragetheselection of genetic mutations in the pathogenic bacteria that enable them to resist against the antibiotic. In other words,as we claim victory over the pathogenic bacteria, nature is givingthem a chance to come back through evolution. For us to fight back, we need to better understand the mutations, genes and pathways that are involved in their defense mechanism. Otherwise their come back, can be the beginning of our demiseas a specie.Whether that’s good or not, letusleave itto the aliens to decide.

Problem:

Biologists have evolved the bacterium Escherichia coliK-12 MG1655 model strain under sublethal  concentrations  of  an  antibiotic  for  hundredsofgenerations.  They  have sequenced the bacteria and given us sixpairsof FASTQ files(link),three of which relate to the treatment group (evolved under antibiotic usage). The other three relate to the control group (evolved  under  normal  conditions).They  want  us  to  analyze  this  sequencing  data.  First,  we need  to  provide single  nucleotide  polymorphisms  (SNPs)that  are observedin  the  treatment group only. Second, we need to provide a  list of genes that are impacted most by  the SNPs. Third, we are asked to reportthe biological pathways that are impacted most by the SNPs. They will use thiskeyinformation to come up with biologically valid theories that would explain the mechanism of resistance in the bacteria to be validated with further experiments.

Approach:

Download  the  FASTQ  files  and  use  the  tools  introduced  during  the  discussion session (e.g. fastqc, trimmomatic, samtools, bowtie2) to perform the analysis we are asked to do.
