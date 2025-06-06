# Guide to preparing supplementary metadata for leaf-level gas exchange data
Supplementary metadata tables should be provided to explain codes used in data tables used to describe samples and experimental variables. Supplementary metadata tables or text should also record additional experimental detail not recorded in the methods metadata template. 

Here are some typical examples of how to present these metadata. Tables should be included in data packages as .csv files.

Guidance on variable names and descriptions should be taken from other ESS-DIVE data formats where available, for example, the [Sample ID and Metadata Reporting Format](https://github.com/ess-dive-workspace/essdive-sample-id-metadata) and the [Reporting Format for location metadata](https://github.com/ess-dive-workspace/essdive-location-metadata). 

### Species information example
**Metadata variable**|**Format**|**Description**|**Example**
-----|-----|-----|-----
speciesCode|Free text|Code used to identify species in data tables|JUOC
species |Free text|Full species name and subspecies if applicable|*Juniperus occidentalis*
genotype|Free text|Identified genotype or mutant| 
citation|Free text|Reference for species authority|Hook.

### Additional metadata tables or text
The requirement for methods supplement tables or text documents will depend on the experimental setup. Where available and appropriate consider including the following information in a gas exchange data package: biome, ecosystem type, climate, local seasonality, timing of measurements relative to the growing season, data time zone and relationship with solar noon, environmental conditions at time of measurement, soil type, canopy exposure, canopy height and depth, terrain, aspect, seed provenance, genetic or cultivar details, pot size, leaf age classes, instrument configuration and measurement scripts.
