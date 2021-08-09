# Spatial transcriptomics analysis of Medulloblastoma PDX models
For sharing scripts on analyses of 
MedulloBlastoma patient-derived xenograft (MB-PDX) of 
Visium spatial RNA-seq between Palbociclib treated & control samples.

## Installation
Need to install requirements.txt.

## Quick Index

    docs/ -> Contains project documentation.
    
        index.md -> Index which describes each script in scripts/ in terms of 
                    INPUT/OUTPUT, and brief description of function.
                    
    figure_components/ -> Contains the outputted components which are used to 
                            create the paper figures. Is grouped according to 
                            the figure. You can see index.md for which script
                            generates what figure components by checking the 
                            script OUTPUT description. 
                    
    scripts/ -> Contains the scripts described in docs/index.md.
                Scripts are grouped into folders relating to order & analysis
                performed.

        X1_QC_SpeciesClassify/ -> Contains scripts related to spot QC & 
                                           classifying spots by human/mouse/mix.

        X2_DEAnalysis/ -> Contains scripts related to the DE analysis between
                            Palbo treated & control samples pseudobulked by 
                            human/mix/mouse spots. 
                            Also includes subsequent GSEA analyses. 

                 

