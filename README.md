Timeline: 

* `convert2annovar.pl -format rsid m6Asnp.txt -dbsnpfile ~/hpc/hg19_avsnp150.txt > snnplist.avinput`
* `bcftools view -i ID==@m6Asnp.txt ~/hpc/db/dbSNP153/hg38/dbSNP153.GRCh38p12b.vcf.gz -Oz -o m6A.vcf.gz`
* extract/pull SNPs from vcf files with rs ID by the above example script to extact m6A-SNPs 
* 2020/01/01: Dr. Kai Wang (kaichop@gmail.com) shared index script with me: [index_annovar.pl](index_annovar.pl)


Annotation Database: 

* SPIDEX 1.0 - Deep Genomics : (Xiong et al, Science 2015) Machine-learning prediction on how genetic variants affect RNA splicing. Genetic annotation file can be [downloaded here](https://urldefense.proofpoint.com/v2/url?u=http-3A__www.openbioinformatics.org_annovar_download_IlvUMvrpPT_hg19-5Fspidex.zip&d=DwIBAg&c=KNVzINr6WAqWApikNSnyDeOu0ck0iFwcrMz92MxUhIs&r=Mmfn7ace985CUWMMPhoR7-I6qZDPAtf2RzYymUiomes&m=dWbMrcrTn8Uhbk4EfDiAGPCRWOzvaNSGfCAzQswt4lk&s=vhkYdQvmuJO3vkrSPXXQYogFEEBKfT3TgLcwZIf1vms&e=)
