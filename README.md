<a href="https://www.bradfordresearch.nhs.uk/our-research-teams/connected-bradford/">
  <img align="left" alt="ConnectedBradford" width="55px" src="https://github.com/ShoreRob1/Images/blob/main/CB%20logo%201.png?raw=true" />
</a>

# cb_cdm_bri_omop
OMOP version of the Bradford Royal Infirmary EPR system , formatted to omop cdm version 5.3
Here you can find a summary of the dataset(s), data dictionaries and helpful code.

# cb_cdm_bri_omop

Contains the scripts and documentation for the Bradford Royal Informary - Electronic Patient Records (EPR) 

It contains approximately 900,000 patients. The dataset has been fully anonymised, but can link to other FDM's.

Build date 03/02/2025 - data up to 11/12/2023


# omop cdm 5.3 
The cdm is made up of a number of tables following the cdm 5.3 format, with 929,268 individuals in teh person table, and all associated data.

The dates relevant for the latest build are: 02/03/2016	to 11/12/2023

### Standard cdm tables included in this dataset


* care_site 
* concept
* concept_ancestor
* concept_class
* concept_relationship
* concept_synonym
* condition_occurrence
* domain
* drug_exposures
* drug_strength
* location
* measurement
* observation
* observation_period
* person
* procedure_occurrence
* provider
* relationship
* visit_detail
* visit_occurrence
* vocabulary

Please note: This data has not been validated using the Achilles tool (https://github.com/OHDSI/Achilles) as it is an in progress load, taking place daily , there may be orphaned records occuring through the load process

For more information on this dataset please refer to the docs folder. 

There is no identifiable information (such as names, date of birth, address,) available to the Connected Yorkshire project so patient confidentiality and privacy will be protected.
