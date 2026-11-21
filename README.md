## SIT_ISP.Rprog - Repository for R code used for ISP project for SIT Undergraduate Climate Change and the Arctic Fall 2026. 

# ISP_Main Main Markdown
Purpose: Home base for ISP data analysis
- Read in data and make preliminary edits
- Preliminary visualizations
- Data processing tracking

Environment Objects Created
- bugs_raw
- bugs
- env_raw
- env
- na_summary

# Markdowns

### PERMANOVA analysis and supporting materials
Purpose: 
- PERMANOVA analysis for each depth
- betadisper/permutest() dispersion test for each depth
- pairwise comparisons for each stream combination at each depth
- p-value matrix visualization
- Bray-Curtis heatmap visualization

Necessary Environment Objects:
- bugs: ISP main markdown

Environment Objects Created:
- many (none relevant for future analysis)


### Species richness analysis
Purpose: 
- Species richness, shannon, and simpson diversity metrics for each stream/depth combination
- Supporting box plots
- Mixed Effects models 
    - test whether richness varies with temperature nonlinearly
    - test whether that temperature relationship differs by depth
    - visualize fitted temperature richness curves with uncertainty

Necessary Environment Objects
- bugs: ISP main markdown

Environment Objects Created
- diversity_df
- diversity_long

### CCA analysis and supporting materials
Purpose: 
- Run CCA comparing community composition and all env vars
- Run CCA comparing community composition across depth
- Supporting CCA plots

Necessary Environment Objects
- bugs: ISP main markdown

Environment Objects Created
- bugs_agg
- cca_dat
- comm2
- richness_long

### Species composition plots
Purpose: 
- create average sample abundance bar chart
- create abundance and relative abundance heat maps

Necessary Environment Objects
- bugs: ISP main markdown

Environment Objects Created
- bugs_long
- bugs_long_prop
