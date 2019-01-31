# ACTRIS Research Infrastructure initial outline of DMP

## Introduction to ACTRIS Data Centre

ACTRIS-2 (Aerosols, Clouds, and Trace gases Research InfraStructure) Integrating Activity (IA) addresses
the scope of integrating state-of-the-art European ground-based stations for long-term observations of
aerosols, clouds and short lived gases. ACTRIS-2 is a unique research infrastructure improving the quality
of atmospheric observations, developing new methods and protocols, and harmonizing existing
observations of the atmospheric variables listed in Appendix I.

The overall goal of the ACTRIS Data Centre is to provide scientists and other user groups with free and
open access to all ACTRIS infrastructure data, complemented with access to innovative and mature data
products, together with tools for quality assurance (QA), data analysis and research following the [FAIR principles](https://www.force11.org/group/fairgroup/fairprinciples).

The numerous measurement methodologies applied in ACTRIS result in a considerable diversity of the
data collected. In accordance with these requirements, the ACTRIS Data Centre currently consists of five topical
data repositories archiving the measurement data, which are all linked through the ACTRIS data portal to
provide a single access point to all data:

* ACTRIS In situ data centre unit (In-Situ): http://ebas.nilu.no/
* ACTRIS Aerosol remote sensing data centre unit (ARES): http://access.earlinet.org/EARLINET/
* ACTRIS Cloud remote sensing data centre unit (CLU): http://cloudnet.fmi.fi/
* ACTRIS trace gases remote sensing data centre unit (GRES): 
* ACTRIS Atmospheric simulation chamber data centre unit (ASC): https://data.eurochamp.org/

In addition, AERIS contributes with the production and provision of satellite data that complements the
ACTRIS ground-based data: http://www.icare.univ-lille1.fr/catalogue.

## ACTRIS data set descriptions and ACTRIS data levels

ACTRIS data sets are atmospheric variables listed in Appendix I, measured with the corresponding
recommended methodology. ACTRIS data - comprises ACTRIS variables resulting from measurements
that fully comply with the [standard operating procedures (SOP), measurement recommendations, and
quality guidelines](http://actris.nilu.no/Content/?pageid=2bedb8fc3d5a42a4b6d96d5fb8dfcd3b) established within ACTRIS.

There are 3 levels of ACTRIS data:
  * **ACTRIS level 0 data:** Raw sensor output, either mV or physical units. Native resolution, metadata necessary for next level.
  * **ACTRIS level 1 data:** Calibrated and quality assured data with minimum level of quality control.
  * **ACTRIS level 2 data:** Approved and fully quality controlled ACTRIS data product or geophysical variable.
  * **ACTRIS level 3 data:** Elaborated ACTRIS data products derived by post-processing of ACTRIS Level 0 -1 -2 data, and data from other sources. The data can be gridded or not.
  * **ACTRIS synthesis product:** Data product from e.g. research activities, not under direct ACTRIS responsibility, but ACTRIS offer repository and access.

The list of variables are expected to increase during the progress of ACTRIS, particularly level 3 data products. During ACTRIS-2, e.g. the aerosol and cloud databases will be augmented with new classification products developed through the combination of existing sensors with additional instrumentation; and products providing information about aerosol layering and typing, together with advanced products derived from long term series or special case analyses. In addition, new parameters utilising these products will also be prepared, and standardized pre processed lidar data and NRT optical property profiles will be available. 

## 1. Data summary for the different data centre units

### Data summary of the ACTRIS In situ data centre unit (In-Situ)

* State the purpose of the data collection/generation
* Explain the relation to the objectives of the project
* Specify the types and formats of data generated/collected
* Specify if existing data is being re-used (if any)
* Specify the origin of the data
* State the expected size of the data (if known)
* Outline the data utility: to whom will it be useful
* Outline of workflow and workflow diagram

### Data summary of the ACTRIS Aerosol remote sensing data centre unit (ARES)

* State the purpose of the data collection/generation
* Explain the relation to the objectives of the project
* Specify the types and formats of data generated/collected
* Specify if existing data is being re-used (if any)
* Specify the origin of the data
* State the expected size of the data (if known)
* Outline the data utility: to whom will it be useful
* Outline of workflow and workflow diagram

### Data summary of the ACTRIS Cloud remote sensing data centre unit (CLU)

* State the purpose of the data collection/generation
* Explain the relation to the objectives of the project
* Specify the types and formats of data generated/collected
* Specify if existing data is being re-used (if any)
* Specify the origin of the data
* State the expected size of the data (if known)
* Outline the data utility: to whom will it be useful
* Outline of workflow and workflow diagram

### Data summary of the ACTRIS trace gases remote sensing data centre unit (GRES)

* State the purpose of the data collection/generation
* Explain the relation to the objectives of the project
* Specify the types and formats of data generated/collected
* Specify if existing data is being re-used (if any)
* Specify the origin of the data
* State the expected size of the data (if known)
* Outline the data utility: to whom will it be useful
* Outline of workflow and workflow diagram

### Data summary of the ACTRIS Atmospheric simulation chamber data centre unit (ASC) 

* State the purpose of the data collection/generation
* Explain the relation to the objectives of the project
* Specify the types and formats of data generated/collected
* Specify if existing data is being re-used (if any)
* Specify the origin of the data
* State the expected size of the data (if known)
* Outline the data utility: to whom will it be useful
* Outline of workflow and workflow diagram

### Data summary of the data products providers (level 3 data/abbreviation missing)

* State the purpose of the data collection/generation
* Explain the relation to the objectives of the project
* Specify the types and formats of data generated/collected
* Specify if existing data is being re-used (if any)
* Specify the origin of the data
* State the expected size of the data (if known)
* Outline the data utility: to whom will it be useful
* Outline of workflow and workflow diagram

## 2. Data Management at the ACTRIS data and services access unit (ACCESS)

### 2.1 Findable: Making data findable, including provisions for metadata [FAIR data]

#### Outline the discoverability of data (metadata provision)

  Present the discoverability of the data at ACTRIS data and services access unit (ACCESS) level.

#### Outline the identifiability of data and refer to standard identification mechanism. Do you make use of persistent and unique identifiers such as Digital Object Identifiers?

  Present the identification mechanisms from each individual data centre unit -> ACCESS unit.

#### Outline naming conventions used

  Present naming conventions at both the data centre unit level and the ACCESS level.

#### Outline the approach towards search keyword

  Approach towards search keywords at the ACTRIS data and services access unit level. E.g. mapping of keywords in relation to the metadata standards (iso19115/iso19139)?

#### Outline the approach for clear versioning

  Question not answered.

#### Specify standards for metadata creation (if any). If there are no standards in your discipline describe what metadata will be created and how

   ACTRIS aiming at following the [INSPIRE](https://eur-lex.europa.eu/legal-content/EN/ALL/?uri=CELEX:32007L0002) directive for metadata formatting. Present standard(s) for metadata at the ACTRIS data and services access unit level. Must decide if data centre units should provide metadata according to a specific standards, as well as providing metadata from the ACTRIS DC to the ENVRI cluster, EOSC etc.

### 2.2 Accessible: Making data openly accessible [FAIR data]

#### Specify which data will be made openly available? If some data is kept closed provide rationale for doing so

  Specify data access policy at the ACCESS unit level and possibly link this section to the existing access policy document: Deliverable 2.6:ACTRIS access and service policy

#### Specify how the data will be made available

  Specify data availability at the ACCESS unit level.

#### Specify what methods or software tools are needed to access the data? Is documentation about the software needed to access the data included? Is it possible to include the relevant software (e.g. in open source code)?

  Specify for each individual data centre unit and for the ACTRIS ACCESS unit, or only at the ACCESS unit level?

#### Specify where the data and associated metadata, documentation and code are deposited

  Specify technical details related to the ACCESS unit.

#### Specify how access will be provided in case there are any restrictions

  Question not answered.

### 2.3 Interoperable: Making data interoperable [FAIR data]

#### Assess the interoperability of your data. Specify what data and metadata vocabularies, standards or methodologies you will follow to facilitate interoperability. 

  Present data and metadata standards. E.g. NetCDF/CF and iso19115/iso19113.

#### Specify whether you will be using standard vocabulary for all data types present in your data set, to allow inter-disciplinary interoperability? If not, will you provide mapping to more commonly used ontologies?

  Standard vocabulary will not always be used, but in all cases these will be mapped to standard vocabulary where exisitng at the DC ACCESS unit.

### 2.4 Reuseable: Increase data re-use (through clarifying licenses) [FAIR data]

#### Specify how the data will be licenced to permit the widest reuse possible

  The main principle of ACTRIS, and also ACTRIS PPP, is to have as open data policy as possible, without compromising the protection of personal and confidential data. The ACTRIS PPP data policy described here affects data collected and produced within the framework of ACTRIS PPP. It does not affect other ACTRIS data.
  Link this section to the existing data policy document: Deliverable 2.3: ACTRIS data policy

#### Specify when the data will be made available for re-use. If applicable, specify why and for what period a data embargo is needed 

  Question not answered.

#### Specify whether the data produced and/or used in the project is useable by third parties, in particular after the end of the project? If the re-use of some data is restricted, explain why

  Question not answered.

#### Describe data quality assurance processes

  Question not answered.

#### Specify the length of time for which the data will remain re-usable

  Question not answered.

### 3. Allocation of resources

#### Estimate the costs for making your data FAIR. Describe how you intend to cover these costs

  Question not answered.

#### Clearly identify responsibilities for data management in your project

  Question not answered.

### Describe costs and potential value of long term preservation

  Question not answered.

### 4. Data security

#### Address data recovery as well as secure storage and transfer of sensitive data 

  Question not answered.

### 5. Ethical aspects

#### To be covered in the context of the ethics review, ethics section of DoA and ethics deliverables. Include references and related technical aspects if not covered by the former 

  Link this section to the [ACTRIS Ethical Guidelines](https://www.actris.eu/Portals/46/Documentation/ACTRIS%20PPP/Deliverables/Public/WP2_D2.2_M24.pdf?ver=2018-12-07-080117-913)

### 6. Other

#### Refer to other national/funder/sectorial/departmental procedures for data management that you are using (if any) 

  Question not answered.

### 7. Appendix

#### Appendix I: List of ACTRIS variables and recommended methodology

#### Appendix II: Data lifecycle/workflow for data centre unit x 




-------------------------------------------------
> Initial outline of the Data Management Plan created using DMPonline
