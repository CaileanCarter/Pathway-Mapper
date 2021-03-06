[![Total alerts](https://img.shields.io/lgtm/alerts/g/CaileanCarter/Pathway-Mapper.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/CaileanCarter/Pathway-Mapper/alerts/)
[![Language grade: Python](https://img.shields.io/lgtm/grade/python/g/CaileanCarter/Pathway-Mapper.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/CaileanCarter/Pathway-Mapper/context:python)
# Enrichment Plot

Plot metabolic pathway presence/absence from Roary and BioCyc enrichment table data. 

Roary allows for fast analysis of genes present and absent in a collection of prokaryote genomes. To assign these genes to pathways, BioCyc's SMartTable system is used (required by the user to generate using an organism database, or multiple, of their choice). Firstly, a tidied list of genes from Roary's text output is required.



## Input arguments

Short flag | Long flag | Argument | Description
--- | --- | --- | --- 
 | | | Roary file path| File path for Roary gene presence/absence data (positional argument)
`-s` | `--SmartTable` | file path | File or folder path for SmartTables generated from Roary data for organism databases of your choice
`-a` | `--accessory` | bool | Show accessory pathways only
`-c` | `--core` | bool | Print core pathways
 | | `--score` | float |Assign cutoff score for whether a pathway or core of accessory
 | | `--output` | str|  Output pathway frequency to an Excel file
 
