# sp-rho-GSA

No DEG's but still want to perform Gene set enrichment analysis (GSEA)/ Gene set analysis (GSA)/ Overrepresentation analysis (ORA) then it can be done using spearman's correlation. 

Step1: Find sp rho correlation in between age and cell type specific gene expression. 

Step2: Find standard error of rho correlation. 

Step3: Use estimates (i.e., beta or rho) and standard error as your input for GSA (using all the genes). 
       Ranked estimates for GSEA (using all the genes)
       and just the gene list (significant) as input and all the gene list as background genes.

Tutorial for fgsea and fgsea ORA: https://bioinformatics-core-shared-training.github.io/RNAseq_May_2020_remote/html/06_Gene_set_testing.html#fgsea
Using GSEA genesets: https://www.gsea-msigdb.org/gsea/msigdb/human/collections.jsp
We are going to try with: 
-> Hallmark genes 
-> C2.CP (canonical pathways)
-> C5.GO 
-> C5.HPO

Step4: See if there is any common geneset using all above methods

