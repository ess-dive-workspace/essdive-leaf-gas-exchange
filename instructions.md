# Leaf-level gas exchange reporting format instructions

These Instructions are intended to step through the various components of a dataset. They refer to numbered Guide documents, and provided templates and data description files (in [templates](templates)). The order of completion is not important. A dataset containing leaf-level gas exchange data should include:

1. Data table(s). Assemble data tables, using the [defined variableNames and variableUnits](1a_definedVariables.md). If the data is a described data type, then the data table must include the required variables for that [data type](3b_dataTypesProtocols.md). Data tables may also include additional variables, and indicators of uncertainty if appropriate. It is recommended that data files are given unique, descriptive names that include relevant information such as date, place, experiment and/or species, and the data type. e.g. 2024_Abisko_ACi.csv, SOYFace_2009_survey.csv.

2. Complete instrument output. See [2_instrumentOutputGuide.md](2_instrumentOutputGuide.md) for further details.

3. Methods metadata. Following the [methods metadata guide](3a_methodsMetadataGuide), fill in the [Methods metadata template](/templates/gas_exchange_methods_template.xlsx), ensuring that [required protocols](3b_dataTypesProtocols.md) for each data type are described.

4. Instrument details. Fill in the [Instrument details template](/templates/instrument_details_template.xlsx). See [4_instrumentDetailsGuide.md](4_instrumentDetailsGuide.md) for further details.

5. Supplementary metadata. See [supplementary metadata guide](5_supplementaryMetadataGuide.md) for further information. Supplemental metadata would include information such as definition of codes used to describe sample characteristics in data tables (e.g. species, treatments), or location details.

6. For submission to ESS-DIVE, datasets should include csv data dictionary files (found here in [templates](/templates), and a [file level metadata file (FLMD)](https://github.com/ess-dive-workspace/essdive-file-level-metadata). Within the FLMD file, the standard for each leaf-level gas exchange related file should be **"ESS-DIVE Leaf-Level Gas Exchange v1"**. ESS-DIVE dataset submissions also require a keyword in the dataset metadata to identify the reporting format. Please add the keyword **"ESS-DIVE Leaf-Level Gas Exchange Reporting Format"** to this field.

### Additional information
Inclusion of additional related datasets with gas exchange data is encouraged. This can include measurements made inline, such as fluorescence or isotopic measurements, or subsequent analysis of chemical composition or physical properties. Related data should be linked by using common sample identifiers.

Defined variables should be used where available. For variables not yet covered by this reporting format documentation, data contributors should use machine readable variable names that are in common use.

The [instrumentOutputTranslation.md](instrumentOutputTranslation.md) is provided as a tool to understand equivalencies of outputs between different instrument models. 

We will continue to work with the ESS researchers to improve data and metadata reporting formats for leaf-level gas exchange data. Please contribute by submitting [issues](https://github.com/ess-dive-workspace/essdive-leaf-gas-exchange/issues/new/choose), using our issue templates, or contact ess-dive-support@lbl.gov to provide any feedback on the process of formatting data, specific metadata fields or controlled vocabulary terms.

### Use of this format with other ESS-DIVE reporting formats
The [ESS-DIVE collection of reporting formats](https://github.com/ess-dive-workspace) includes formats for different measurement types and also for file and metadata structures. The collection is designed to be modular, so use of multiple reporting formats will be required to correctly format a dataset. As such, the content of this Leaf-level gas exchange data and metadata reporting format is limited to guidance specific to gas exchange data.

For ESS-DIVE datasets, file formats should follow those presented in the [csv file](https://github.com/ess-dive-workspace/essdive-csv-structure) and [file level metadata](https://github.com/ess-dive-workspace/essdive-file-level-metadata) reporting format documentation. The [ESS-DIVE Reporting Format for Comma-separated Values (CSV) File Structure](https://github.com/ess-dive-workspace/essdive-csv-structure) includes guidance for many general data types, including missing values, temporal and spatial data. Supplementary data should follow the relevant data format, where available, such as the [ESS-DIVE Sample ID and Metadata Reporting Format](https://github.com/ess-dive-workspace/essdive-sample-id-metadata).

Refer to the [ESS-DIVE Workspace](https://github.com/ess-dive-workspace) for a complete list of available reporting formats.
