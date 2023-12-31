# WGS-workflows
## Resources for *Thermococcus kodakarensis* sequencing workflows
##

![Alt text](/image_bank/usegalaxy.png?raw=true ".")

Galaxy webserver is @ https://usegalaxy.org/  
You'll need to register for an account

##
### Format reference genome to fix length
Did you need to generate a custom reference genome? You can use one of these tools to reformat your custom reference genome such that each line contains 60 nt.  
From the FATSX-toolkit (http://hannonlab.cshl.edu/fastx_toolkit/).  
- **search "FASTA Width formatter"** on usegalaxy.org (recommended 60 nt width) 
- **Format FASTA to fixed length** @ https://junli.netlify.app/apps/format-fasta/

##

### Need SRA data but can't code?
search "SRA" @ usegalaxy.org and look for one of the following tools:  
- **Download and Extract Reads in FASTQ** format from NCBI SRA
- **Faster Download and Extract Reads in FASTQ** format from NCBI SRA
- **Download and Extract Reads in BAM** format from NCBI SRA

##
### Do you need to annotate a plasmid? Try pLannotate @ http://plannotate.barricklab.org/

![Alt text](/image_bank/pLannotate.png?raw=true ".")

##
### The MEME suite has a weberver @ https://meme-suite.org/meme/index.html  
**Discovery, detection, and analysis of sequence motifs**  

i.e. Do you want to know the coordinate location of all occurences of "GTAAAG" in the reference genome? Use **FIMO** from the MEME suite. But be cognizant of the p-value cutoff.  
i.e. Do you have a dataset of ChIP-seq sequences and want to discover a sequence motif (such as a protein binding site) within these sequences? Use one of the motif discovery or enrichment tools depending on your application.

![Alt text](/image_bank/meme_suite.png?raw=true ".")



