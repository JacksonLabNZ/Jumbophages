# Jumbophages
Data and analysis scripts from Malone *et al.*, 2020:

Malone LM, Warring SL, Jackson SA, Warnecke C, Gardner PP, Gumy LF, Fineran PC* (2020) A nucleus-forming jumbophage evades CRISPR-Cas DNA targeting but is vulnerable to type III RNA-based immunity. **Nature Microbiology**, 5:48-55.

Spacer-protospacer matches identified by GASSST (target_search.sh) - these files are provided (Search_Results*) - were processed using Jumbo_project_Spacer_hit_analysis_Workflow_type(IE/IF or III).R then the outputs were merged and analysed using Jumbo_project_Spacer_hit_analysis_Workflow_all.R

Note: the spacer-target searches were run with the target database genomes subsetted into > or < 150 kb. The output data were subsequently merged and analysed as > or < 200 kb phage genomes.
