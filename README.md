# Data and Jupyter/IPython notebooks to examine enriched transcripts in the SCN via Meta-analysis
### These notebooks constitute the meta-analysis carried out in Brown et al 2017:

### Laurence A. Brown, John Williams, Lewis Taylor, Ross J. Thomson, Patrick M. Nolan, Russell G. Foster, Stuart N. Peirson; Meta-analysis of transcriptomic datasets identifies genes enriched in the mammalian circadian pacemaker,  Nucleic Acids Research, Volume 45, Issue 17, 29 September 2017, Pages 9860–9873, https://doi.org/10.1093/nar/gkx714

The analysis uses the Python programming language, version 2.7.11, as well a a number of more specific packages. These are all found as part of the Anaconda Python environment produced by Contiuum Analytics This is BSD licenced and cross platform. (https://www.continuum.io/downloads)
>all required python packages:
>pandas  0.17.0
>numpy   1.9.3
>bokeh   0.10.0
>scipy   0.16.0

are installed by default in anaconda2 4.0.0 and beyond
(environment can be recreated using 'conda create included NAR.yml file)

![workflow](/IPython_notebooks/Workflow.png)

To repeat the analysis:
- unpack the copies of the Altanalyze output 
- run all 'Hedges g' calculations (A1-5)
- index these files (B1) 
- then finally run the REM meta-analysis (B2), followed by the vizualisation (C) if required

 ## See INDEX.ipynb for index of notebook files 
  A1_430AV2_Hedges_g.ipynb
  A2_430V2_Hedges_g.ipynb
  A3_MoEx_Hedges_g.ipynb
  A4_MoGene_Hedges_g.ipynb
  A5_RNA_Seq_Hedges_g.ipynb
  B1_indexing_Hedgesgs_symbol.ipynb
  B2_REM_Meta_Analysis.ipynb
  C1_Viz_table_colouring_for_Volcano.ipynb
  C2_Viz_Plot_plus_table.ipynb

-----------------------------------------------------------------------------------------------------------

Add interactive figure

