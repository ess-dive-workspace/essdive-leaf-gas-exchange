# ESS-DIVE Leaf-Level Gas Exchange Data and Metadata Reporting Format v1.1.0

This documentation contains guidance for the content and format of leaf-level gas exchange data and metadata. The reporting format comprises defined variable names and units for data tables, a methods metadata template, and instrument details template and guidance on inclusion of other related data and metadata.   

## About the Leaf-Level Gas Exchange Data and Metadata Reporting Format

The ESS-DIVE leaf-level gas exchange data and metadata reporting format has been developed to meet the needs of researchers for a unified reporting format. This initial effort covers the most common variables and provides templates for metadata reporting. Additional reporting requirements have been developed for seven common data types: 
* Survey
* Response of photosynthesis to intercellular CO&#8322; concentration (ACi curves)
* Photosynthetic parameters derived from ACi curves
* Vcmax from one point
* Response of photosynthesis to irradiance (AQ curves)
* Photosynthetic parameters derived from AQ curves
* Dark adapted respiration

For a full description of the reporting format, refer to Ely et al (2021). A reporting format for leaf-level gas exchange data and metadata. Ecological Informatics. https://doi.org/10.1016/j.ecoinf.2021.101232 

## Getting started: links to instructions and templates

Instructions for how to use this reporting format:
- [Leaf-level gas exchange reporting format instructions](instructions.md) 

Other documents to get started:
- [Methods metadata template](templates/methodsMetadataTemplate.xlsx): Download spreadsheet template for recording experiment and methods metadata. 
- [Instrument details template](templates/instrumentDetailsTemplate.xlsx): Download spreadsheet template to record instrument details. 

---
## Updates in v1.1.0
This update includes restructuring of the GitHub repository, updated Instructions, suggested file naming conventions, addition of standard data dictionaries, and inclusion of additional required variables for the Survey datatype. 

Details are as follows:
- The GitHub file structure has been reorganized to remove the “docs” folder and display all informational content in the home directory. Files have been renamed using a numbering system that corresponds with steps in the Instructions. 
- The Instructions have been rewritten to align with the guide and definition documents. 
- Metadata template file names have been adjusted to meet ESS-DIVE requirements.
- Suggested file naming conventions have been added to the Instructions and Guides documents.
- For the Survey data type, Tair and VPDleaf have been added as Required Variables. 
- Data dictionary (dd) files have been added to Templates for methods metadata, instrument details, LI-COR 6400 output, LI-COR 6800 output and the reporting format defined variables. 

## How to contribute 

This leaf-level gas exchange data reporting format is evolving and growing to meet the needs of researchers. Feedback and new contributions are welcome, and can be made by submitting an [issue or feedback](https://github.com/ess-dive-workspace/essdive-leaf-gas-exchange/issues/new/choose).  

The issue templates we use are modeled from that provided by Darwin Core:
Darwin Core maintenance group, Biodiversity Information Standards (TDWG) (2014). Darwin Core. Zenodo. https://doi.org/10.5281/zenodo.592792

## Copyright information

The leaf-level gas exchange data and metadata reporting format is licensed under the Creative Commons Attribution 4.0 International (CCby4).

## Funding and acknowledgements

Funding for the development of ESS-DIVE's leaf-level gas exchange data and metadata reporting format was provided by the US Department of Energy (DOE), Biological and Environmental Research Program, Earth and Environmental Systems Sciences Division, Data Management.

The format was developed with input and feedback of over 80 subject experts, including data collectors, data scientists, data users (empiricists and modelers), and instrument manufacturers. Thank you all. 

For further description of the reporting format, and the development process, refer to:

Ely K.S. et al (2021). A reporting format for leaf-level gas exchange data and metadata. Ecological Informatics. Volume 61.  [https://doi.org/10.1016/j.ecoinf.2021.101232](https://doi.org/10.1016/j.ecoinf.2021.101232)

## Recommended citation

Ely K.S., Rogers A, Crystal-Ornelas R (2020). ESS-DIVE reporting format for leaf-level gas exchange data and metadata. Environmental Systems Science Data Infrastructure for a Virtual Ecosystem (ESS-DIVE), ESS-DIVE repository. Dataset. [https://data.ess-dive.lbl.gov/datasets/doi:10.15485/1659484](https://data.ess-dive.lbl.gov/datasets/doi:10.15485/1659484)
