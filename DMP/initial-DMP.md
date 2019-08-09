<center>
<img src="https://raw.githubusercontent.com/actris/data-management-plan/master/DMP/img/draft-logo.png" alt="draft">
<img src="https://www.actris.eu/Portals/46/Images/Logos/logo-actris_new_140.png?ver=2015-06-08-141001-817" alt="ACTRIS logo">
</center>

# Data Management plan for ACTRIS - Aerosols, Clouds, and Trace gases Research InfraStructure

# Table of contents

* [1. Introduction to ACTRIS and The ACTRIS Data Centre](#1-Introduction-to-ACTRIS-and-The-ACTRIS-Data-Centre)
  * [1.1. ACTRIS data set descriptions and ACTRIS data levels](#11-actris-data-set-descriptions-and-actris-data-levels)
* [2. Data summary for ACTRIS data centre](#2-Data-summary-for-ACTRIS-data-centre)
  * [2.1. ACTRIS In Situ data centre unit (In-Situ)](#21-actris-in-situ-data-centre-unit-in-situ)
  * [2.2. ACTRIS Aerosol remote sensing data centre unit (ARES)](#22-actris-aerosol-remote-sensing-data-centre-unit-ares)
  * [2.3. ACTRIS Cloud remote sensing data centre unit (CLU)](#23-actris-cloud-remote-sensing-data-centre-unit-clu)
  * [2.4. ACTRIS trace gases remote sensing data centre unit (GRES)](#24-actris-trace-gases-remote-sensing-data-centre-unit-gres)
  * [2.5. ACTRIS Atmospheric simulation chamber data centre unit (ASC)](#25-actris-atmospheric-simulation-chamber-data-centre-unit-asc)
  * [2.6. ACTRIS data and services (ACCESS)](#26-actris-data-and-services-access)
* [3. Data Management at the ACTRIS data centre](#3-Data-Management-at-the-ACTRIS-data-centre)
  * [Findable: Making data findable, including provisions for metadata [FAIR data]](#31-findable-making-data-findable-including-provisions-for-metadata-fair-data)
  * [Accessible: Making data openly accessible [FAIR data]](#32-accessible-making-data-openly-accessible-fair-data)
  * [Interoperable: Making data interoperable [FAIR data]](#33-interoperable-making-data-interoperable-fair-data)
  * [Reuseable: Increase data re-use (through clarifying licenses) [FAIR data]](#34-reuseable-increase-data-re-use-through-clarifying-licenses-fair-data)
* [4. Allocation of resources](#4-Allocation-of-resources)
* [5. Data security](#5-Data-security)
* [6. Ethical aspects](#6-Ethical-aspects)
* [7. Other](#7-Other)
* [8. Appendix](#8-Appendix)
  * [Appendix 1: List of ACTRIS variables and recommended methodology](#appendix-1-list-of-actris-variables-and-recommended-methodology)
  * [Appendix 2: List of ACTRIS level 3 data products](#appendix-2-list-of-actris-level-3-data-products)
  * [Appendix 3: ACTRIS In situ data centre unit (In-Situ) data life cycle](#appendix-3-actris-in-situ-data-centre-unit-in-situ-data-life-cycle)
  * [Appendix 4: ACTRIS Aerosol remote sensing data centre unit (ARES) data life cycle and workflow diagram](#appendix-4-actris-aerosol-remote-sensing-data-centre-unit-ares-data-life-cycle-and-workflow-diagram)
  * [Appendix 5: ACTRIS Cloud remote sensing data centre unit (CLU) data life cycle and workflow diagram](#appendix-5-actris-cloud-remote-sensing-data-centre-unit-clu-data-life-cycle-and-workflow-diagram)
  * [Appendix 6: ACTRIS trace gases remote sensing data centre unit (GRES) data life cycle and workflow diagram](#appendix-6-actris-trace-gases-remote-sensing-data-centre-unit-gres-data-life-cycle-and-workflow-diagram)
  * [Appendix 7: ACTRIS Atmospheric simulation chamber data centre unit (ASC) data life cycle and workflow diagram](#appendix-7-actris-atmospheric-simulation-chamber-data-centre-unit-asc-data-life-cycle-and-workflow-diagram)
  * [Appendix 8: Data lifecycle and workflow for ACCESS Data Centre Unit](#appendix-8-data-lifecycle-and-workflow-for-access-data-centre-unit)

## 1.  Introduction to The ACTRIS Data Centre and ACTRIS Data Management Plan

The Aerosol, Clouds and Trace Gases Research Infrastructure (ACTRIS) focuses on producing high-quality data for the understanding of short-lived atmospheric constituents and their interactions. These constituents have a residence time in the atmosphere from hours to weeks. The short lifetimes make their concentrations highly variable in time and space and involve processes occurring on very short timescales. These considerations separate the short-lived atmospheric constituents from long-lived greenhouse gases, and calls for a four dimensional distributed observatory. The Research Infrastructure (RI) ACTRIS is the pan-European RI that consolidates activities amongst European partners for observations of aerosols, clouds, and trace gases and for understanding of the related atmospheric processes, as well as to provide RI services to wide user groups (See the [Stakeholder Handbook](http://www.actris.eu/Portals/46/Documentation/ACTRIS%20PPP/Stakeholder%20Handbook/2018/ACTRIS%20Stakeholder%20Handbook%202018.pdf?ver=2019-03-08-140842-873) for more information). 

ACTRIS data are data from observational or exploratory National Facilities complying with the procedures established within ACTRIS.

ACTRIS observational platforms are fixed ground-based stations that produce long-term data based on a regular measurement schedule and common operation standards. These platforms perform measurements of aerosol, clouds, and reactive trace gases from the Earth surface throughout the troposphere up to the stratosphere by applying state-of-the-art remote-sensing and in situ measurement techniques under consideration of harmonized, standardized, and quality controlled instrumentation, operation procedures and data retrieval schemes. The sites are strategically located in diverse climatic regimes both within and outside Europe, and many of them contribute to one or several European and international networks, such as [EMEP](https://www.emep.int/), [NDACC](http://www.ndaccdemo.org/), or [GAW](http://www.wmo.int/pages/prog/arep/gaw/gaw_home_en.html), and are possibly partly shared with other environmental infrastructures, such as [ICOS](https://www.icos-cp.eu/), [SIOS](https://sios-svalbard.org/), [ANAEE](https://www.anaee.com/) or [eLTER](https://www.lter-europe.net/elter).

ACTRIS exploratory platforms are atmospheric simulation chambers. These chambers are among the most advanced tools for studying and quantifying atmospheric processes and are used to provide many of the parameters incorporated in air quality and climate models. Atmospheric simulation chamber data contribute to better predict the behavior of the atmosphere over all time scales through a detailed understanding of the physical and chemical processes, which affect air quality and climate change. Atmospheric simulation chambers are among the most advanced tools for studying and quantifying atmospheric processes and are used to provide many of the parameters incorporated in air quality and climate models. 

![Architecture of the ACTRIS Data Centre](https://raw.githubusercontent.com/actris/data-management-plan/master/DMP/img/section1/Exp_Obs_NF.jpg)
* Figure XX: Overview of the types of National Facilities providing data to ACTRIS Data Centre*

ACTRIS is a unique RI improving both the quality of and access to atmospheric observations, developing new methods and protocols, and harmonizing existing observations of the atmospheric variables listed in [Appendix 1](https://folk.nilu.no/~richard/actris-ri-variables/Appendix_I_ACTRIS-RI_variables_21February2018.xlsx). Appendix 1 includes an updated list of all ACTRIS variables associated to recommended measurement methodology.

### 1.1 The mission, overall goal and structure of the ACTRIS Data Centre

> The mission of the ACTRIS Data Centre is to compile, archive and provide access to well documented and traceable ACTRIS measurement data and data products, including digital tools for visualisation, data analysis and research. As a tool for science, the highest priorities for the ACTRIS DC are to maintain and increase the availability of ACTRIS data and data products relevant to climate and air quality research for all interested users.

The overall goal of the ACTRIS Data Centre (DC) is to provide scientists and other user groups with free and open access to all ACTRIS infrastructure data, complemented with access to innovative and mature data products, together with tools for quality assurance (QA), data analysis and research. ACTRIS data and products should be **f**indable, **a**ccessible, **i**nteroperable and **r**eusable (FAIR), and the data centre work towards fulfilling the [FAIR principles](https://www.force11.org/group/fairgroup/fairprinciples). The numerous measurement methodologies applied in ACTRIS result in a considerable diversity of the data collected. In accordance with these requirements, the ACTRIS DC will be organized in 6 Units, with clear links and procedures for interaction between the data centre Units, National Facilities (NFs) and topical centres (TCs). The ACTRIS DC will be coordinated by the ACCESS unit leader and all data is linked through the [ACTRIS data portal](http://actris.nilu.no/) to provide a single access point to all data and related information. The units and short names are:

* [ACTRIS data and services access unit (ACCESS)](http://actris.nilu.no/)
* [ACTRIS In situ data centre unit (In-Situ)](http://ebas.nilu.no/)
* [ACTRIS Aerosol remote sensing data centre unit (ARES)](http://access.earlinet.org/EARLINET/)
* [ACTRIS Cloud remote sensing data centre unit (CLU)](http://cloudnet.fmi.fi/)
* [ACTRIS trace gases remote sensing data centre unit (GRES)](https://en.aeris-data.fr/)
* [ACTRIS Atmospheric simulation chamber data centre unit (ASC)](https://data.eurochamp.org/)

![Architecture of the ACTRIS Data Centre](https://raw.githubusercontent.com/actris/data-management-plan/master/DMP/img/ACTRIS_data_centre_elements_phase2.jpg)
*Figure 1: Architecture of the ACTRIS Data Centre*

During the ACTRIS implementation phase (expected 2020-2024), the Central Facilities will be constructed and their services tested. The ACTRIS Central Facilities host selection was a part of ACTRIS PPP, and the following consortium is selected to host the ACTRIS Data Centre, and the various units with services to data producers and data users.

| Name of Central Facility and associated Unit                                | Hosting institution and contribution | Main activities                                                   |
|--------------------------------------------------------------|--------------------------------------|--------------------------------------------------------------------|
| ACTRIS Data Centre                                           | NILU (lead), contributions by all    | Coordinate the work and the interaction and reporting to the Head Office |                                        
| [ACTRIS data and services access unit (ACCESS)](http://actris.nilu.no/)                | NILU (lead), CNRS, MetNo, BSC        | ACTRIS web interface for data, services and tools, called “The ACTRIS Data Centre”. Main activities are discovery and access to ACTRIS data and data products, digital tools provided by the topical centres and the data centre units, documentation, access to software and tools for data production. Offer visualisation of ACTRIS data products. Data production of selected Level 3 data and synergy data products. The data centre will offer bridge to external data bases and sources.|
| [ACTRIS In-Situ data center unit (In-Situ)](http://ebas.nilu.no/)                   | NILU                                 | Data curation service for in situ data: all aerosol, cloud and trace gas in situ data. This comprises inclusion of data in the data base EBAS, archiving and documentation. Support for centralized data processing, harmonization, traceability, quality control and data product generation. Training and online tools for QA, QC. The activity enables RRT and NRT delivery.|
| [ACTRIS Aerosol remote sensing data centre unit (ARES)](http://access.earlinet.org/EARLINET/)		   | CNR (lead), CNRS					  |	Aerosol remote sensing data processing and curation. This includes centralized processing, traceability, harmonization and data versioning, quality control, data archiving in EARLINET DB, data provision and documentation. The activity enables RRT and NRT delivery. Tutorial activities. Production of level 3 data for climatological analysis and new products. |	
| [ACTRIS Cloud remote sensing data centre unit (CLU)](http://cloudnet.fmi.fi/)		   | FMI								  |	Data curation service for cloud remote sensing data. Support for centralized cloud remote sensing data processing, harmonization, automated quality control and product generation. Enables RRT and NRT delivery. Production of level 3 data for NWP model evaluation. | 
| [ACTRIS Atmospheric simulation chamber data centre unit (ASC)](https://data.eurochamp.org/) | CNRS                                 | Data curation service for atmospheric simulation chamber data. This includes standardized process for data submission, quality control, inclusion of data in the XX data base, search metadata creation and provision and archiving.|
| [ACTRIS trace gases remote sensing data centre unit (GRES)](https://en.aeris-data.fr/)    | CNRS                                 | Data curation service for reactive trace gases remote sensing data. This comprises standardized process for data submission, quality control, inclusion of data in the XX data base, metadata creation and provision and archiving. Production of level 3 data for climatological analysis, and added values products (quicklooks, links to EVDC - ESA Atmospheric Validation Data Centre).|

*Table 1: Short description of the ACTRIS DC units and the research performing organizations leading and contributing to the units.*

### 1.2 The overall goal and structure of ACTRIS Data Management Plan

The ACTRIS Data Management Plan (DMP) is the key element of the comprehensive ACTRIS data management and describes the data management life cycle in detail and the plans for the data collected, processed and/or generated. The goal of the DMP is to describe the operational ACTRIS data curation, and outline the strategy and development needed towards making ACTRIS data FAIR at ACTRIS Data Centre Level.

The ACTRIS DMP is a living online document which is set up to be a machine-actionable document that is a part of the FAIR data ecosystem. The DMP should be a hub of information on ACTRIS FAIR digital objects. The goal is to make the ACTRIS DMP accessible for all stakeholders (repository operators, funders, researchers, publishers, infrastructure providers etc.) by making it available and accessible for both humans and machines. We currently use [GitHub](https://github.com/actris/data-management-plan) as the platform for collaboration on the DMP, this enables all actors working with or within ACTRIS to directly contribute and susggest changes to the document. Furthermore, the ACTRIS Data Management Plan follow the [glossary](https://www.actris.eu/About/ACTRIS/ACTRISglossary.aspx) of terminology and definitions used in ACTRIS.

## 2. ACTRIS data and ACTRIS data levels

ACTRIS data are data from observational or exploratory National Facilities complying with the procedures established within ACTRIS. ACTRIS data comprises ACTRIS variables resulting from measurements at National Facilities that fully comply with the standard operating procedures (SOP), measurement recommendations, and quality guidelines established within ACTRIS. The ACTRIS atmospheric variables are listed in [Appendix I](https://folk.nilu.no/~richard/actris-ri-variables/Appendix_I_ACTRIS-RI_variables_21February2018.xlsx), associated to the corresponding recommended methodology. 

There are 4 levels of ACTRIS data:
 * **ACTRIS level 0 data:** Raw sensor output, either mV or physical units. Native resolution, metadata necessary for next level.
 * **ACTRIS level 1 data:** Calibrated and quality assured data with minimum level of quality control.
 * **ACTRIS level 2 data:** Approved and fully quality controlled ACTRIS data product or geophysical variable.
 * **ACTRIS level 3 data:** Elaborated ACTRIS data products derived by post-processing of ACTRIS Level 0 -1 -2 data, and data from other sources. The data can be gridded or not.
 * **ACTRIS synthesis product:** Data product from e.g. research activities, not under direct ACTRIS responsibility, but ACTRIS offer repository and access.

![Architecture of the ACTRIS Data Centre](https://raw.githubusercontent.com/actris/data-management-plan/master/DMP/img/ACTRIS_data_levels.jpg)
*Figure 1: ACTRIS data levels*

The list of ACTRIS variables are expected to increase during the progress of ACTRIS, particularly level 3 data products.

## 3. Data summary of the ACTRIS data centre

#### The purpose of the data collection/generation

Primary goal of ACTRIS is to produce high quality integrated datasets in the area of atmospheric sciences and provide services, including access to instrumented platforms, tailored for scientific and technological usage. The purpose of the data collection and generation of data products in ACTRIS is to provide open access to aerosol, cloud and trace gas in situ and remote sensing measurements of high quality, benefiting a large community of scientists involved in atmospheric science and related areas as well as policy makers, the private sector, educators and the general public. 

See the [Stakeholder Handbook](http://www.actris.eu/Portals/46/Documentation/ACTRIS%20PPP/Stakeholder%20Handbook/high_res_version.pdf?ver=2018-06-04-080105-217) for more information.

#### The relation to the objectives of the project

The primary goal of ACTRIS is to produce high quality integrated datasets in the area of atmospheric sciences and provide services, including access to instrumented platforms, tailored for scientific and technological usage. The main objectives of ACTRIS are:

* to provide information on the 4D-compositon and variability and of the physical, optical and chemical properties of short-lived atmospheric constituents, from the surface throughout the troposphere to the stratosphere, with the required level of precision, coherence and integration;
* to provide information and understanding on the atmospheric processes driving the formation, transformation and removal of short-lived atmospheric constituents;
* to provide efficient open access to ACTRIS data and services and the means to effectively use the of ACTRIS products;
* to ensure and raise the quality of data and use of up-to-date technology used in the RI and the quality of services offered to the community of users, involving partners from the private sector; and
* to promote training of operators and users and enhance linkage between research, education and innovation in the field of atmospheric science.

* *From the Stakeholder Handbook (2018)*

Management of ACTRIS data relates to measuring atmospheric composition and the ability to predict the future behavior of the atmosphere over all time scales. High quality observational data harmonized across the countries and continents facilitates this, and needs to be supported by:

* Documentation of archiving procedures and access to level 0 -> level 3 data produced by the National Facilities (NFs), Topical Centres (TCs), and Central Facilities (CFs)
* Documented and traceable processing chain of level 0 data
* Documented, traceable processing and long-term archiving and preservation of all ACTRIS level 1 to level 3 data and data products
* Access to ACTRIS data, data products, and digital tools through a single point of entry, the ACTRIS data user interface
* Documentation of data, data flow, citation service, and data attribution, including version control, data traceability, and interoperability,
* Data curation and support for campaigns and dedicated research projects and initiatives, external or internal to ACTRIS.

#### Main users of ACTRIS data and software

ACTRIS will produce data and data products essential to a wide range of communities as described in detail in the [Stakeholder Handbook](http://www.actris.eu/Portals/46/Documentation/ACTRIS%20PPP/Stakeholder%20Handbook/high_res_version.pdf?ver=2018-06-04-080105-217), section “Users” including:

* Atmospheric science research communities world-wide
  * The climate and air-quality, observational/ experimental/ modelling/ satellite communities, national and international research programmes and organisations;
* Environmental science research communities and communities from other neighboring fields: hydro-marine, bio-ecosystem, geosciences, space physics, energy, health, and food domain, to study interactions and processes in across different disciplines;
* Instrument manufacturers and sensor industries for development, testing, prototyping and demonstration;
* Operational services, National weather services, climate services for model validation, weather and climate analysis and forecasting;
* Space agencies for validation and the development of new satellite missions;
* National and regional air quality monitoring networks and environmental protection agencies for air quality assessments and validation of air pollution models;
* Policy makers and local/ regional/ national authorities for climate and air-quality related information for decision making and policy development.
* Copernicus Gas atmospheric service (ECMWF)
* Science community working on air quality, climate change and stratospheric ozone depletion issues

### 3.1 ACTRIS In situ data centre unit (In-Situ)

The In-Situ data centre unit provides data curation service for aerosol, cloud and trace gas in situ data and inclusion of data in EBAS database. This includes tools for harmonized data submission and meta data templates, inclusion of data and meta data in the data base, traceability, harmonization and data versioning, quality control, archiving, documentation and data provision. Training and online tools for QA, QC is offered. The activity enables RRT and NRT data compilation and delivery and provides tutorial activities. Furthermore, support for centralized data processing, harmonization, and data product generation, both level 2 and level 3 is offered and further implemented during the implementation phase.

#### The types and formats of data generated/collected
The ACTRIS In-situ data centre unit is supported by the [EBAS database infrastructure](http://ebas.nilu.no/ResourcesATMOS/AboutEBAS.pdf). In situ data submitted to ACTRIS need to be formatted in the EBAS NASA-Ames format (ASCII file) by the data originator, and there are exsisting [instructions and templates](https://ebas-submit.nilu.no/) for each instrument/group of instruments. [The EBAS NASA-Ames format](https://projects.nilu.no//ccc/tfmm/kjeller_2016/EBAS_Data_Format_2016-10.pdf) is based on the ASCII text NASA-Ames 1001 format, but contains additional metadata specifications ensuring proper documentation from the [EBAS-Submit documentation](https://ebas-submit.nilu.no/) website as well as tools for [file-generation](http://dev-ebas-file-generation-tool.nilu.no/) (*beta*) and [file-submission](https://ebas-submit-tool.nilu.no/).

ACTRIS in situ data is also available in the netCDF 4 format through the [EBAS Thredds Server](https://thredds.nilu.no/thredds/catalog.html), following the [CF 1.7 convention](http://cfconventions.org/Data/cf-conventions/cf-conventions-1.7/cf-conventions.html) and the [Attribute Convention for Data Discovery 1-3 (ACDD)](http://wiki.esipfed.org/index.php/Attribute_Convention_for_Data_Discovery_1-3).

#### Re-use of existing data

The ACTRIS data user interface will include access to aerosol and trace gas in situ legacy data resulting from ACTRIS pre-projects (for In-Situ [CREATE, EUSAAR, ACTRIS-FP7](https://www.actris.eu/About/ACTRIS/Heritage.aspx). These will also be included as a part of the ACTRIS In Situ data centre unit. Legacy data resulting from ACTRIS pre-projects will be available in the same format as current products.

#### The origin of the data

The origin of the data is derived from instrument raw data, either through online or offline observations.

#### The expected size of the data

| Type                          |Number of annual datasests (end 2019)                          | Number of annual datasets (min by 2025) | Number of annual datasets (max by 2025) |
|-------------------------------|----------------------------------------------------------|-----------------------------------------|-----------------------------------------|
| ACTRIS in situ aerosol data   |           60                                             |       50                                |   120                                   |
| ACTRIS in situ cloud data     |           0                                              |       35                                |   105                                   |
| ACTRIS in situ trace gas data |           27                                             |       30                                |   60		                               |

Table 1: *Number of annual datasets*

| Type                          |Data volume (end 2019)                                          | Data volume (min by 2025)                | Data volume (max by 2025) |
|-------------------------------|-----------------------------------------------------------|------------------------------------------|------------------------------------------|
| ACTRIS in situ aerosol data   |           18 000 MB                                       |       15 000 MB                          |   50 000 MB                              |
| ACTRIS in situ cloud data     |           0 MB                                            |       1 GB                               |   3 GB                                   |
| ACTRIS in situ trace gas data |           300 MB                                          |       200 MB                             |   400 MB	                              |

Table 2: *Data volume*

#### Data utility

Data utility specifically related to the DC unit (see data summary at ASC for under the "Data utility" section for an example)

#### Outline of data life cycle (workflow and workflow diagram)
Detail on the data life cycle and workflow (workflow diagrams for data production) for in situ observations can be found in [*Appendix 3: ACTRIS in situ aerosol, cloud and trace gas data lifecycle and workflow (draft)*](https://github.com/actris/data-management-plan/blob/master/DMP/initial-DMP.md#appendix-3-actris-in-situ-data-centre-unit-in-situ-data-life-cycle-and-workflow-diagram).

### 3.2 ACTRIS Aerosol remote sensing data centre unit (ARES)

The ARES data centre unit provides a data curation and data processing service for aerosol remote sensing data. This includes centralized data processing, inclusion of data and meta data in the data base, traceability, harmonization and data versioning, quality control, archiving, documentation and data provision. The activity enables RRT and NRT data compilation and delivery and provides tutorial activities. Furthermore, data product generation of level 3 data for climatological analysis and new products is offered and further implemented during the implementation phase.

Furthermore the goal is to measure the aerosol distribution and optical properties in the whole troposphere and upper stratosphere with short time resolution and to investigate its relationship with near surface processes as pollution and air quality issues and to address the challenging issue of cloud indirect effects of aerosol in the climate change.

#### The types and formats of data generated/collected

The ACTRIS ARES data centre unit is making use of EARLINET Data base infrastructure. Aerosol remote sensing data submitted to ACTRIS need to be in a specified format compliant with the centralized processing suite. ARES provides data compliant with netCDF 4 as much as possible, and following Climate Forecast (CF) 1.7 convention. 

#### Re-use of existing data
The ACTRIS data user interface will include access to aerosol remote sensing legacy data resulting from ACTRIS pre-projects (for ARES [EARLINET, EARLINET-ASOS](https://www.actris.eu/About/ACTRIS/Heritage.aspx)). These will also be included as a part of the ACTRIS ARES data centre unit. Legacy data resulting from ACTRIS pre-projects will be available in the same format as current products.

#### The origin of the data

The origin of the data is derived from instrument raw data.

#### The expected size of the data

| Type                                |Number of annual datasets (end 2019)                          | Number of annual datasets (min by 2025) | Number of annual datasets (max by 2025) |
|-------------------------------------|----------------------------------------------------------|-----------------------------------------|-----------------------------------------|
| ACTRIS aerosol remote sensing data  |           28                                             |       30                                |   70                                    |

Table 1: *Number of annual datasets*

| Type                               |Data volume (end 2019)                                          | Data volume (min by 2025)                | Data volume (max by 2025)  |
|------------------------------------|-----------------------------------------------------------|------------------------------------------|----------------------------|
| ACTRIS aerosol remote sensing data |           4 GB                                            |       2.5 TB                             |   25 TB                    |

Table 2: *Data volume*

#### Data utility

Data utility specifically related to the DC unit (see data summary at ASC for example)

#### Outline of data life cycle (workflow and workflow diagram)

Details of the data life cycle and workflow (workflow diagrams for data production) for in situ observations can be found in [Appendix 4: ACTRIS aerosol remote sensing data lifecycle and workflow (draft)](https://github.com/actris/data-management-plan/blob/master/DMP/initial-DMP.md#appendix-4-actris-aerosol-remote-sensing-data-centre-unit-ares-data-life-cycle-and-workflow-diagram).

### 3.3 ACTRIS Cloud remote sensing data centre unit (CLU)

The CLU data centre unit provides data curation and data processing service of cloud remote sensing data. This includes centralized processing, traceability, harmonization and data versioning, quality control, data provision and archiving, and documentation. The activity enables RRT and NRT data compilation and delivery, and participation in training. Furthermore, data product generation of level 3 data for forecast and climate model evaluation, climatological analysis and new products is offered and further implemented during the implementation phase. 

#### The types and formats of data generated/collected

The ACTRIS CLU data centre unit is making use of the CLOUDNET data base infrastructure. Cloud remote sensing data submitted to ACTRIS need to be in a specified format compliant with the centralized processing suite. CLU provides data compliant with netCDF 3 and netCDF4 formats as much as possible, and following CF 1.7 convention. Level 0 data submitted to ACTRIS CLU are required to be in a specified format compliant with the centralized processing suite. All further data levels are produced by the CLU processing suite.

#### Re-use of existing data

The ACTRIS data user interface will include access to cloud remote sensing legacy data resulting from ACTRIS pre-projects (for CLU [CLOUDNET](https://www.actris.eu/About/ACTRIS/Heritage.aspx)). These will also be included as a part of the ACTRIS CLU data centre unit. Legacy data resulting from ACTRIS preprojects will be available in the same format as current products.

#### The origin of the data

Data is derived from instrument raw data, coupled with thermodynamic profiles from NWP model.

#### The expected size of the data

| Type                              |Number of annual datasests (end 2019)                          | Number of annual datasets (min by 2025) | Number of annual datasets (max by 2025) |
|-----------------------------------|----------------------------------------------------------|-----------------------------------------|-----------------------------------------|
| ACTRIS cloud remote sensing data  |       11                                                 |      15                                 |   25                                    |

Table 1: *Number of annual datasets*

| Type                               |Data volume (end 2019)                                     | Data volume (min by 2025)             | Data volume (max by 2025)             |
|------------------------------------|------------------------------------------------------|---------------------------------------|---------------------------------------|
| ACTRIS cloud remote sensing data   |           15 TB                                      |       50 TB                           |   150 TB                              |

Table 2: *Data volume*

#### Data utility

Data utility specifically related to the DC unit (see data summary at ASC for example).

#### Outline of data life cycle (workflow and workflow diagram)

Details on the data life cycle and workflow (workflow diagrams for data production) for remote sensing observations can be found in [Appendix 5: ACTRIS cloud remote sensing  data lifecycle and workflow (draft)](https://github.com/actris/data-management-plan/blob/master/DMP/initial-DMP.md#appendix-5-actris-cloud-remote-sensing-data-centre-unit-clu-data-life-cycle-and-workflow-diagram).

### 3.4 ACTRIS trace gases remote sensing data centre unit (GRES)

The GRES data centre unit provides data curation service for reactive trace gases remote sensing data, **ADD: new text, see issue and comment have this consistent with the other units.**

#### Description of the ACTRIS-GRES unit
The ACTRIS trace gases remote sensing data centre unit making use of AERIS database. Reactive trace gas remote sensing data submitted to ACTRIS need to be submitted as level 2 data following the GEOMS data format (Generic Earth Observation Metadata Standard, http://www.ndsc.ncep.noaa.gov/data/formats) and the appropriate GEOMS template for FTIR, UVVIS and LIDAR measurements.

For data access and download, the level 2 and level 3 data are be converted in NetCDF4 format following the CF (Climate Forecast) conventions. 

#### The types and formats of data generated/collected
The ACTRIS trace gases remote sensing data centre unit is supported by AERIS database. All providers will submit level 2 data following the GEOMS data format (Generic Earth Observation Metadata Standard, http://www.ndsc.ncep.noaa.gov/data/formats) and following the appropriate GEOMS template for FTIR, UVVIS and LIDAR measurements. The GEOMS data format allows the necessary requirements to setup the ACTRIS data curation service for trace gas remote sensing data.

The level 2 and level 3 data will be also converted in NetCDF ([https://www.unidata.ucar.edu/software/netcdf/](https://www.unidata.ucar.edu/software/netcdf/)) version 4 format following the CF (Climate Forecast) conventions and be disseminated. The Climate and Forecast conventions are metadata conventions for earth science data. The conventions define metadata that are included in the same file as the data making the file "self-describing".

#### Re-use of existing data
The ACTRIS data user interface will include access to reactive trace gases remote sensing legacy data data resulting from ACTRIS pre-projects (for GRES…). These will also be included as a part of the ACTRIS GRES data centre unit. Legacy data resulting from ACTRIS pre-projects will be available in the same format as current products.

#### The origin of the data
The origin of the data is derived from instrument raw data, through offline observations.

#### The expected size of the data

| Type                                |Number of annual datasets (end 2019)                          | Number of annual datasets (min by 2025) | Number of annual datasets (max by 2025) |
|-------------------------------------|----------------------------------------------------------|-----------------------------------------|-----------------------------------------|
| ACTRIS-GRES FTIR                    |                  276                                 |         200                            |             300                         |
| ACTRIS-GRES UV-VIS                  |             20000                                          |          15000                            |             30000                         |
| ACTRIS-GRES LIDAR DIAL              |                  450                                    |          300                            |             500                          |

Table 1: *Number of annual datasets*

| Type                               |Data volume (end 2019)                                          | Data volume (min by 2025)                | Data volume (max by 2025)  |
|------------------------------------|-----------------------------------------------------------|------------------------------------------|----------------------------|
| ACTRIS-GRES FTIR |                    2,5 GB                                   |              12 GB                         |          18 GB               |
| ACTRIS-GRES UV-VIS  |                     1,2 GB                                   |              6 GB                         |          10 GB               |
| ACTRIS-GRES LIDAR DIAL |                     400 MB                                |              400 MB                      |          550 MB            |

Table 2: *Data volume*

#### Data utility

Data utility specifically related to the DC unit (see data summary at ASC for example)

#### Outline of data life cycle (workflow and workflow diagram)
Detail on the data life cycle and workflow (workflow diagrams for data production) for trace gases remote sensing data can be found in [Appendix 6](https://github.com/actris/data-management-plan/blob/master/DMP/initial-DMP.md#appendix-6-actris-trace-gases-remote-sensing-data-centre-unit-gres-data-life-cycle-and-workflow-diagram).

### 3.5 ACTRIS Atmospheric simulation chamber data centre unit (ASC)

The ASC data centre unit provides data curation service for data obtained from ACTRIs exploratory platforms; experiments in atmospheric simulation chambers. (This includes standardized processing for data provision, data services curation and documentation. ASC compile and provides access to detailed information on the infrastructures (i.e. simulation chambers) used for the generation of the data; this includes a technical description of the chambers (size, volume, walls, irradiation system …) and an “auxiliary mechanism” which provides the chamber-dependent parameters affecting the observations.

The ACTRIS-ASC unit is structured in three pilars:
-   The _Database of Atmospheric Simulation Chamber Studies_ (DASCS) provides access to experimental and modelled data (level 2 data), typically time-series of measured parameters, obtained from experiments in simulation chambers.
    
-   The _Library of Analytical Resources_ (LAR) provides quantitative analytical resources that include infrared spectra and mass spectra of molecules and derivatives (level 3 data).
    
-   The _Library of Advanced Data Products_ (LADP) provides different types of mature data products (level 3 data): rate constants of reactions in gas and condensed phases, quantum yields and photolysis frequencies of trace gas compounds, secondary organic aerosol (SOA) yields, mass extinction/absorption/scattering coefficients and complex refractive index of aerosols, growth factors of aerosols and modelling tools.
    
**The types and formats of data generated/collected**

The ACTRIS ASC data centre unit is making use of AERIS data infrastructure. Atmospheric simulation chambers data submitted to ACTRIS and the DASCS data base pillar have to be provided by NFs in a standard format, called “EDF format” (EUROCHAMP Data Format) which is based on an ASCII text format but contains additional metadata in a header. These data are completed with rich metadata which are available from the website and give access to a technical description of the chambers (size, volume, walls, irradiation system …), the experimental protocols used for the generation of the data, and an “auxiliary mechanism” which provides the chamberdependent parameters affecting the observations. Currently, work is being conducted with regards to providing tools for access and download of data also in the netCDF 4 format, compliant with the CF 1.7 convention. This will be implemented during ACTRIS implementation phase. 

Level 3 data provided in LAR are IR and mass spectra in JCAMP-DX format which is the standard format recommended by IUPAC for spectra. It is a 2D graphic format based on ASCII format. Metadata are attached and made available through the ACTRIS data user interface. These data are provided by NFs.

Level 3 data provided in LADP are of different types and have thus different nonharmonized formats. Most of them are provided as a unique value with metadata attached. These metadata include information on the level 2 data processing, a link to the level 2 data in the DASCS and the reference paper where this data has been published.

**Re-use of existing data**

The ACTRIS data user interface will include access to atmospheric simulation chamber legacy data resulting from ACTRIS pre-projects (for ASC [EUROCHAMP, EUROCHAMP-2](https://www.actris.eu/About/ACTRIS/Heritage.aspx)). These will also be included as a part of the ACTRIS ASC data centre unit. Legacy data resulting from ACTRIS pre-projects will be available in the same format as current products.

**The origin of the data**

Data provided by ACTRIS ASC unit are produced from experiments in simulation chambers. Data provided in DASCS and LAR pillars are generated byinstrument raw data and data processing, while data provided in LADP are produced from L2 data processing. All the data processing is performed by NFs.

**The expected size of the data**

| Type                                |Number of annual datasets (end 2019)                          | Number of annual datasets (min by 2025) | Number of annual datasets (max by 2025) |
|-------------------------------------|----------------------------------------------------------|-----------------------------------------|-------------------------------|
| ACTRIS-ASC DASCS                    |                   100                                    |          50                            |             200                 |
| ACTRIS-ASC LAR                 |                   20                                  |          10                          |             50               |
| ACTRIS-ASC LADP              |                   30                                     |          60                             |             150                |


 Table 1: _Number of annual datasets

|  Type                                |Data volume (end 2019)                          | Data volumes (min by 2025) | Data volume (max by 2025) |
|-------------------------------------|----------------------------------------------------------|-----------------------------------------|-------------------------------|
| ACTRIS-ASC DASCS                    |                  1,2 GB                                  |        1,5 GB                            |             2,4 GB                 |
| ACTRIS-ASC LAR                 |                   67 MB                                  |          76 MB                        |            120 MB               |
| ACTRIS-ASC LADP              |                   26 KB                                     |          200 KB                             |             500 KB                |

Table 2: _Data volume_

**Data utility**

Atmospheric simulation chamber data contribute to better predict the behavior of the atmosphere over all time scales through a detailed understanding of the physical and chemical processes which affect air quality and climate change. ACTRIS-ASC unit give access to different types of data and data products essential to a wide range of communities. Many of these parameters are incorporated in air quality and climate models.

-   Level 2 data provided in DASCS are of high interest for a large community of users in atmospheric science research and related areas, as well as the private sector. In particular, they are largely used for modelling activities to develop and/or validate chemical schemes of atmospheric models.
    
-   Level 3 data provided in the LAR are of high interest for a large community of users in atmospheric sciences, analytical chemistry and related areas, as well as the private sector. Indeed, quantitative chemical analysis of infrared spectra for complex mixtures requires access to standards for the calibration of instruments. However, as the chemical species formed by these processes are often very complex (and not commercially available), their spectra are not available in the “classical” databases of analytical chemistry, or are not useful due to their low resolution. To tackle this issue, the EUROCHAMP consortium has developed its own Library of infrared spectra and has made it freely available to the scientific communities.
    
-   Level 3 data products provided in the LADP are especially useful for researchers working on atmospheric observations, as well as atmospheric model development and validation. It includes products for the development of chemical mechanisms in atmospheric models (e.g. rate coefficients, photolysis frequencies, SOA yields, vapor pressures, etc.), products for the retrieval of satellite data and for radiative transfer modelling (e.g.), and tools to generate oxidation schemes which are very useful to interpret field measurements as well as laboratory studies.
    

**Outline of data life cycle (workflow and workflow diagram)**

Detail on the data life cycle and workflow (workflow diagrams for data production) for Atmospheric Simulation chamber data can be found in [Appendix 7](https://github.com/actris/data-management-plan/blob/master/DMP/initial-DMP.md#appendix-7-actris-atmospheric-simulation-chamber-data-centre-unit-asc-data-life-cycle-and-workflow-diagram).

### 3.6 ACTRIS data and services (ACCESS)

ACTRIS data and services access unit (ACCESS) is responsible for access to measurement data, services, tools and documentation, with scientific data management and support to observational and exploratory NFs. The access unit provides provision of ACTRIS web interface for data, services and digital tools as well as performing data production of and access to Level 3 data, quality control tools, and synergy data products.

The ACTRIS access web interface for data, services and tools, is called “The ACTRIS Data Centre” and the main activities are **Discovery and access** to ACTRIS data and data products, digital tools provided by the topical centres and the data centre units, documentation, software and tools for data production. **Visualisation** of ACTRIS data products. **Data production** of Level 3 data and synergy data products. The data centre also offers **bridge to external data bases and sources**.

The ACTRIS ACCESS unit provides elaborated aerosol, cloud and trace gas data products, issued of advanced multi-instrument synergistic algorithms, long term reanalysis, modelling and satellite data and sources.

The list of ACTRIS level 3 data products is detailed in the [Appendix II](https://folk.nilu.no/~richard/actris-ri-variables/Appendix_II_ACTRIS-RI_level3_variables_21February2018.xlsx), and consiste of three main categories:

	I. Production of level 3 data solely based on data from ACTRIS observational platforms

	II. Production of level 3 data and tools through multi-source data integration services, employing external ground based measurement data

	III. Production of level 3 data products involving regional and global model data

#### The types and formats of data generated/collected

The objective is that most of the level 3 data generated will be in [NetCDF data format](https://www.unidata.ucar.edu/software/netcdf/) and have metadata compliant to the [NetCDF CF Metadata Conventions](http://cfconventions.org). This format and metadata are widely used in the atmospheric science community, and is supported by a lot of standard visualization and analysis tools. Nevertheless, the collected data can come from external sources accordingly, non standard formats may also be used. In these cases, they will be rather kept in their original format.

### Re-use of existing data

The generated products and online services available from ACTRIS-preproject use existing ACTRIS L0-1-2, satellite and model data.

### The origin of the data
The origin of the data is derived from ground-based and satellite observations, retrieval algorithms and model simulations.

#### The expected size of the data

| Type                  |Number of annual datasests (end 2019)   | Number of annual datasets (min by 2025) | Number of annual datasets (max by 2025) |
|-----------------------|-----------------------------------|-----------------------------------------|-----------------------------------------|
|    GRASP/GARRLiC      |                        6          |             See SCC L1 from ARES        |    See SCC L1 from ARES                 |
|    GRASP-AOD          |                        0          |             7500                        |    7500                                 |
|    ReOBS              |                        1          |             1                           |    1                                    |

Table 2.6.1. *Number of annual datasets*

| Type              |Data volume (end 2019)                                          | Data volume (min by 2025)  | Data volume (max by 2025)  |
|-------------------|-----------------------------------------------------------|----------------------------|----------------------------|
| GRASP/GARRLiC     |                            3.2 GB                         |     TBD                    |           TBD              |
| GRASP-AOD         |                              0 GB                         |      10.5 TB               |        17.5 TB             |
| ReOBS             |                              2 GB                         |        3 GB                |                5 GB        |

Table 2.6.2. *Data volume*


##### Generated (on-demand services)

| Product                                                       | Typical dataset per day | Typical volume per day |
| ------------------------------------------------------------- | ----------------------- | ---------------------- |
| Satellite data subsets                                        | 100                     | 100 MB                 |
| Transport modelling products for assessment of source regions | ...                     |                        |
| Colocation service of data from contributing networks         | TBD                     | TBD                    |
| Model Evaluation Service                                      | 30                      | 300 MB                 |
| NWP Model Evaluation Service                                  | 120                     | 100 MB                 |

#### Data utility

Data utility specifically related to the DC unit (see data summary at ASC for example)

#### Outline of data life cycle (workflow and workflow diagram)

Detail on the data life cycle and workflow (workflow diagrams for data production) for level 3 data can be found in Detail on the data life cycle and workflow (workflow diagrams for data production) for level 3 data can be found in [Appendix 8](https://github.com/actris/data-management-plan/blob/master/DMP/initial-DMP.md#appendix-8-data-lifecycle-and-workflow-for-access-data-centre-unit)

## 4. Data Management at the ACTRIS data centre

ACTRIS data and products should be findable, accessible, interoperable and reusable (FAIR), and the data centre work towards fulfilling the FAIR principles. This chapter is describing the complete ACTRIS Data Flow from [National Facilities (NF)](https://raw.githubusercontent.com/actris/data-management-plan/master/DMP/img/section1/Exp_Obs_NF.jpg) to users that is operational now and the work and solutions that will be implemented during the implementation phase (2020-2025). The section starts with and introduction to the data management system in ACTRIS in section 4.1, including detailed description of data flow within each unit (4.1.1.-4.1.5). This is followed by sections describing detailed solutions and implementation plans making ACTRIS data and products findable (4.2), accessible (4.3), interoperable (4.4) and reusable (4.5).

### 4.1 Dataflow

#### 4.1.1 Dataflow data and services access unit (ACCESS)

![ACTRIS Data Centre elements, phase 2](https://raw.githubusercontent.com/actris/data-management-plan/master/DMP/img/section2/ACTRIS_data_centre_elements_phase2_simplified.jpg)
![ACTRIS Data Centre topical databases](https://raw.githubusercontent.com/actris/data-management-plan/master/DMP/img/section2/current_overview_topical_databases.png)
*Figure x: current_overview_topical_databases.png*

#### 4.1.2 Dataflow In situ data centre unit (In-Situ)

#### 4.1.3 Dataflow Aerosol remote sensing data centre unit (ARES)

#### 4.1.4 Dataflow Cloud remote sensing data centre unit (CLU)

#### 4.1.5 Dataflow trace gases remote sensing data centre unit (GRES)

#### 4.1.6 Dataflow Atmospheric simulation chamber data centre unit (ASC)

![ACTRIS ASC Unit:](https://raw.githubusercontent.com/actris/data-management-plan/master/DMP/img/section2/overview_ASC_unit.png)
*Figure x: current overview of ASC unit*

### 4.2 Findable: Making data findable, including provisions for metadata [FAIR data]

ACTRIS will harvest metadata from a large range of observations employing methodologies provided by multiple data centre units covering different types of data both in terms of size, time coverage and metadata. 
The ACCESS unit aims at providing discovery metadata for all ACTRIS level 2 data, using a common standard that is WIS compliant such as ISO19139 or ISO19115. Exceptions may occur in cases where the selected metadata standards do not meet the need to describe the data.

Future efforts should further develop the system shown in Figure XXX (that Richard is producing) and make it possible for the ACCESS unit to harvest all metadata from the different data centre units and collect this in a central ACTRIS metadata catalog and provide this through a commonly used protocol for Metadata harvesting like OAI-PMH or similar.

There might be instances where standards do not cover the need for describing the data at the data centre unit. In this case, one should still try to provide metadata in a way that is similar to the agreed formats and standards and at the same time push for an extension of the specified standard.

The core responsibility of metadata provisioning is at the data centre unit level and common metadata protocols and standards for each data curation unit will be implemented. The role of the ACCESS unit is to harvest metadata records for the ACTRIS metadata catalog as well as putting in place instruments for monitoring data/metadata provisioning as well as monitoring and collecting user statistics (inspections, plotting and download of data) related to the ACTRIS Data Portal and the ACTRIS metadata catalog.

Generally, ACTRIS data set names aims to be compliant with [CF (Climate and Forecast) metadata conventions](http://cfconventions.org/standard-names.html). In the case where no standard CF names are defined, an application will be sent to establish these.

ACTRIS works towards establishing traceability for all applicable variables using persistent identifiers (PIDs). This is to assure proper attribution is given to data originators adequately reflecting their contributions. Currently ACTRIS is using  digital object identifiers (DOIs) for all secondary datasets though the [Data Cite Metadata Store API](https://mds.datacite.org/).
*(Note from ASC and GRES DC : Not yet but we work on it)*

Moreover, ARES unit assigns a persistent identifier to a dataset implementing an internal PID generation system based on an alphanumerical \<prefix\>/\<suffix\> pattern. 

Currently there is no search model used by the ACCESS unit (ACTRIS data portal). Still search keywords are implemented to varying degrees on the individual data centre unit level (e.g. search keywords are used for the EBAS ISO19115 records). The ACTRIS data centre should in the future use a controlled set of vocabularies for search keywords like [Global Change Master Directory (GCMD)](https://earthdata.nasa.gov/about/gcmd/global-change-master-directory-gcmd-keywords) or similar, and semantic search will be implemented.

ASC unit has developed a user-friendly web interface which includes searching tools based on the metadata catalogue for the three pillars, DASCS, LAR and LADP. Relevant searching criteria have been defined for each pillar.

ACTRIS aiming at following the [INSPIRE](https://eur-lex.europa.eu/legal-content/EN/ALL/?uri=CELEX:32007L0002) directive for metadata formatting. Present standard(s) for metadata at the ACTRIS data and services access unit level. Must decide if data centre units should provide metadata according to a specific standards, as well as providing metadata from the ACTRIS DC to the ENVRI cluster, EOSC etc.

The ACTRIS DC aims at providing clear versioning of its data and metadata, due to the decentralised nature of the Data Centre, this varies between the different data centre units, and implementation will be done on unit level.

As a guiding principle, all data submitted to ACTRIS passing quality assurance should be uniquely identified. In case of updates, a ID-number is generated, and previous data versions should be identifiable and kept available upon request while the latest version is served through the ACTRIS data portal web-interface.

A Versioning System has been implemented at ARES directly in the RDBMS by using DML (Data Manipulation Language) triggers.
A new version of a file is produced when a user tries to modify data through a DML event. New versions will be centrally produced if new QC procedures and new processing features are released. Additionally new versions of the files will be allowed and centrally handled for fixing file bugs in particular for legacy data.

#### 4.2.1 Metadata services

ACTRIS data should be described with rich metadata. Currently metadata services are offered on data center unit level, but the aim is to offer all ACTRIS level 2 data through a centralized metadata service.

| Data center unit                  | metadata service               | end-point                                                                               |                        standard |
|--------------------------|--------------------------------|-----------------------------------------------------------------------------------------|---------------------------------|
|         In Situ          |          OAI-PMH               |  https://ebas-oai-pmh.nilu.no/oai/provider?verb=ListIdentifiers&metadataPrefix=iso19115 |       ISO 19115-2, CF-1.7,ACDD  |
|         ARES             |          ISO via Thredds server, JSON via REST API, HTTP via Apache Server|  https://login.earlinet.org:8443/thredds/catalog/earlinedbscan/catalog.html , https://150.145.73.229/earlinetservice/services/ , https://150.145.73.229/earlinet/           |       ISO 19115-2 , ECMA262-3, CF-1.7, NCML, RFC2616               |
|         CLU              |          To be defined     |  None                                                                 |       To be decided                      |
|	  ACCESS           	   | To be decided              |  None																		              |       To be decided             |
|         ASC              | CSW, geonetwork				|  [http://catalogue2.sedoo.fr/geonetwork/srv](http://catalogue2.sedoo.fr/geonetwork/srv)	(implementation on going)																			  |      ISO 19139				|
|         GRES             | CSW, geonetwork					|   [http://catalogue2.sedoo.fr/geonetwork/srv](http://catalogue2.sedoo.fr/geonetwork/srv)	(implementation on going)																					  |       ISO 19139

*Table: ACTRIS metadata services*

#### 4.2.2 Persistent Identifiers (PIDs)

ACTRIS data should be assigned PIDs that are available through the metadata.

| Data center unit                  | PID service               | Description                                                                               |                        standard |
|--------------------------|---------------------------|-------------------------------------------------------------------------------------------|---------------------------------|
|         In Situ          |                           |                                                                                           |                                 |
|         ARES             |                           |                                                                                           |                                 |
|         CLU              |          NaN              |  None                                                                                     |       To be decided             |
|	      ACCESS           | Defined by primary repository  |  None																		              |       To be decided             |
|         ASC              | To be defined					|  None																					  |       To be decided				|
|         GRES             | To be decided					|  None																					  |       To be decided				|

*Table: ACTRIS PID handlers*

#### 4.2.3 Metadata indexing in external resources

ACTRIS metadata should be registered or indexed in relevant metadata catalogs

| Metadata catalogs           | Description               | ACTRIS DC unit indexed                                                                    |
|-----------------------------|---------------------------|-------------------------------------------------------------------------------------------|
|         GISC Offenbach          |                           |                                                                                       |
|         NextGEOSS             |                           |                                                                                         |
|         WIGOS              |          NaN              |  None                                                                                      |
|	      Copernicus           | Defined by primary repository  |  None																		          |
|         re3data              | To be defined					|  None																			      |
|         EOSC             | To be decided					|  None																					      |   

*Table: ACTRIS PID handlers*

### 4.3 Accessible: Making data openly accessible [FAIR data]

As a guding principle all ACTRIS data should be readable for both humans and machines using protocols that offer no limitations to access. ACTRIS is organized as a distrbuted network of centralized repositories. The main access point to ACTRIS data will be through the [ACTRIS data portal](http://actris.nilu.no/), this will be a web portal that allows the user to search, analyse and download data produced within ACTRIS. Access to data and metadata should also be made possible by machine-to-machine interaction, enabling harvesting of metadata from the ACTRIS metadata catalog. Currently, machine-to-machine access of ACTRIS data varies between the different data repositories.

The access protocol should be clearly discribed in the metadata. If direct access is limited due to size of data or sensitive data, a email, telephone number or similar to a contact person should then be included. The access protocol must be described in a easy to understand way in the metadata, both for humans and machines.

There might also be data available through the ACTRIS data portal that is not directly ACTRIS data, but used in the interpretation of ACTRIS data.

#### 4.3.1 ACTRIS data access protocols

| DC unit                  | data format                  | Repository URL                                                                                                                                                       |           Protocol           | Authentication and authorization needed  | 
|--------------------------|------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------|------------------------------------------|
|         In Situ		   |          netCDF              |                 http://ebas.nilu.no/                                                                                                                                 |              HTTP               | No                                    | 
|         ARES     		   |          netCDF              |                 http://access.earlinet.org/                                                                                                                          |              HTTP               | Yes                                   |
|         CLU              |          netCDF              |                 http://cloudnet.fmi.fi                                                                                                                               |              HTTP               | No                                    |
|		  ACCESS (data portal)          | Defined by primary repository|  				http://actris.nilu.no/														                                                                         |               HTTP      	       | For some data                         |
|         ASC              | netCDF (data conversion by 2020)			      |  				https://data.eurochamp.org/																	                                                         |       		 HTTP		       | For some data                         |
|		  GRES             | netCDF (data conversion by 2021)			  |  				https://en.aeris-data.fr/																	                                                         |       				 FTP      | No                                     |
|		  ACCESS             | varies				  |  					http://actris.nilu.no/Content/?pageid=226809f7a0ac49538914eeafb4448afa																                                                         |       				 FTP      | No                                     |

**Table: Who and how to access the data**
*(Note from Bénédicte: Does it mean that we plan to maintain these URL and to make them available from the ACTRIS data portal? Or do we want to move them in a common “ACTRIS” URL? I think that it is something we never really discussed but maybe I missed some discussions)*

* **Type 1: ACTRIS data**
   * Data are funded and produced within the context of the ACTRIS project. Every dataset created within ACTRIS is owned by the ACTRIS partner(s) who created this dataset, and the ACTRIS data policy can be found here. A description of ACTRIS data is provided in the "ACTRIS Data management Plan". This includes access to NRT data (not for ASC DC). The ACCESS unit is currently showcasing NRT data providing quicklook images for [Near surface and cloud data](http://actris.nilu.no/Content/?pageid=844fe06802f04a83a2d6b0e8b2a59fe2) and [Aerosol profiles](http://actris.nilu.no/Content/?pageid=ae1bf05f1fa54ba8bae735a2420e6c8d).

* **Type 2: Other data available through the portal**
  * Data are archived and owned by other organisations or data providers and are hosted at other databases. Type 2 data are provided with the permission of each organisation or data provider contributing to the data archive. Each dataset of type II may have its own data policy that will supersede the ACTRIS data policy.

* **Type 3: ACTRIS level 3 data:**
  * Data are elaborated ACTRIS data products derived by post-processing of ACTRIS Level 0 -1 -2, and (and/or ?) data from other sources. The data can be gridded or not. Level 3 datasets are derived from measurement data, where the measurements are reported to the ACTRIS topic data repositories. The datasets are derived by e.g. averaging, filtering of events, interpolation of measurement data and are usually the result of analysis for special studies or processed for model experiments. The [secondary data archive](http://actris.nilu.no/Content/?pageid=226809f7a0ac49538914eeafb4448afa) stores secondary data sets to provide long term access for all users, including the possibility to issue a Digital Object Identifier (DOI). Secondary datasets are normally not updated over time.

Still, individual data centre units will also serve as access points for ACTRIS data. But that is out of scope for this document.

General guidelines for access to ACTRIS data and services are available in the current [ACTRIS access and service policy](https://www.actris.eu/Portals/46/Documentation/ACTRIS%20PPP/Deliverables/Public/WP2_D2.6_M32.pdf?ver=2018-10-29-152442-467). Conditions of use should be indicated in section 3.4, and is covered by the attached licence, unless stated otherwise.

Some data requires a username and password in order to gain access, e.g. the usage of aerosol profile data.**(If some data is kept closed, we must provide rationale for doing so. For ARES registration is open to everybody.)**
Apart from Quicklooks (simple plots of data from the [In Situ](http://ebas-nrt-showcase.nilu.no/), ARES and CLU units), Near-Real-Time (NRT) data is mostly access protected.
For all data that requires username and password, a Single-Sign-On service should be implemented, and used by all Data Centre units.

A Single-Sign-On authentication system has been implemented at ARES unit. It is based on [CAS (Central Authentication Service)](https://www.apereo.org/projects/cas) protocol and provides both authentication via username and password and via Google credentials. 

For ASC unit, all data, metadata, tools and documentation are provided with free and fully open access to all users without authentication with username and password.

In all cases where access is restricted, information on how to access the data should be available through the metadata.

If specific software tools are need to access the data, documentation about the software and how to access it should be included, preferably in the metadata. Furthermore, ACTRIS digital tools (software etc.) should be available through open access repositories like GitHub. A open source licence for software should be encouraged and applied when possible. The aformentioned guidelines are related to ACTRIS [level 2 data](#11-actris-data-set-descriptions-and-actris-data-levels). This is primarily intended as guidelines for software that is needed to access data that is available through the data centre. Software related to ACTRIS level 0 and level 1 data is out of scope for this section.

### 4.4 Interoperable: Making data interoperable [FAIR data]

As a guiding principle, ACTRIS should make sure that metadata and data use a format that is commonly used and accessible both within the research community as well as other disciplines.
Currently there are no common approach towards interoperability among the DC units.

By some of the DC units the Thredds Data Server (TDS) is used for serving data as netCDF and through OPeNDAP (EBAS, Earlinet, ASC, GRES). 

More over, ARES unit provides a [REST API](https://150.145.73.229/earlinetservice/services) for machine-to-machine communication. The API serves metadata (info, provenance, versions, quality controls, etc.) in JSON format and data (specific files or datasets previously generated) in NetCDF format. CLU unit provides a [RESTful API](http://devcloudnet.fmi.fi/api) with similar services (data and some metadata).

ACTRIS DC needs to specify what data standards the ACTRIS DC should choose, in order to facilitate interoperability. Still, work remains to see if a common solution could be agreed upon. The intricate nature of the data, might require the use of different solutions to suit the needs of each individual DC unit.

As mention in section 3.1 metadata standard and vocabularies commonly used in the atmospheric domain should be applied, unless the common solutions do not address the specific need for the DC unit.

Aerosol and cloud profile data are archived and provided by the ARES and CLU units in netCDF format. All published EARLINET and Cloudnet data are in [CF (Climate and Forecast) 1.7](http://cfconventions.org/) compliant format.

For ASC unit, format of data differ according to the database: In DASCS pillar, data are provided in a ASCII based format but work is being conducted in order to provide data also in the netCDF format. In LAR pillar, data are provided in J-DX CAMP format which is a standard format for spectra. Finally, data in LADP are provided in a ASCII based format. For more details on these formats, see section 2.5.

Implementation of new standards for data and metadata used in the context of ACTRIS should be discussed by all the DC units. This is especially important for the ACCESS unit, coordinating the access to all of the ACTRIS data. Therefore the aim should be to harmonize data and metadata as much as possible, both in terms of technical aspects related to implementation, but also making it easier for the end user to make use of the data.

Standard vocabulary might not always be used, but in all cases they should be mapped to standard vocabulary if existing by the DC ACCESS unit.

As an overarching goal, ACTRIS DC will take part in discussions that takes place in forums/groups such as ENVRI FAIR across the different environmental domains and strive to use cross-environmental standards and solutions in order to allow for inter-disciplinary interoperability.

#### 4.4.1 Implementation of vocabulary

| Data center unit         | Vocabulary name               |          Comment            |
|--------------------------|-------------------------------|-----------------------------|
|         In Situ		   | ISO19139, ISO19115-2, CF-1.7  |                             |
|         ARES     		   | ISO19115-2, netCDF-CF1.7      |                             |
|         CLU              |          netCDF-CF-1.7        |                             |
|		  ACCESS           | Defined by primary repository |                             |
|         ASC              | 		ISO19139				       |  			                 |
|		  GRES             | 		ISO19139				   |  				             |

*Table X: List of vocabularies*

### 4.5 Reuseable: Increase data re-use [FAIR data]

The guiding principle is free and open access to ACTRIS data and ACTRIS data products.

The ACTRIS DC will facilitate data re-use by providing free and open access to ACTRIS data following the ACTRIS data and access policy and the open research data initiative of the European Commission. As a result, the ACTRIS DC will implement one or multiple licences for all ACTRIS level 2 data and NRT data that is available through the ACTRIS metadata catalog. Furthermore, the ACTRIS DC might also consider issuing a licence on the use of metadata, in order to ensure the visibility of ACTRIS when large amounts of metadata is harvested by third party application/services. ACTRIS aims to implement a license from the time ACTRIS becomes an ERIC (probably end of 2020 or early 2021). Until ACTRIS has decided upon and implemented one or more licenses, the current [ACTRIS data policy](http://actris.nilu.no/Content/Documents/DataPolicy.pdf) will apply.

Several features have been implemented by ARES unit to ensure reusability and traceability. Just to mention a few: 
  * recording of files and datasets downloaded by users, as well as of research filters/keywords used; 
  * the use of a centralized and automated tool, the [Single Calculus Chain (SCC)](https://scc.imaa.cnr.it), for data processing. This allows a "traceable" reprocessing when a new version (of the data as well as of the tool) is available. More over, the processing suite could potentially be made available to others per specific processing needs.  

Similarly, the CLU unit has a centralized and automated processing chain, Cloudnet, ensuring reusability and traceability, which is also available via [open source](https://github.com/tukiains/cloudnetpy) for the community to use, evaluate and review.

In order to increase the reusability of data in ASC unit, these data are completed with rich metadata which are in open access from the website. These metadata provide detailed technical description of the chambers (size, volume, walls, irradiation system …), experimental protocols used for the generation of the data, and an “auxiliary mechanism” which provides the chamber-dependent parameters affecting the observations. This last one is very useful for modelers who aim at simulating experiments performed in simulation chambers.

Availability of data can vary between the different data centre units. As an example, in situ data is typically submitted on an annual basis, and are therefore available the subsequent year, but other data centre units may provide NRT delivery of data; in addition, there may be campaign-based data. ACTRIS legacy data should be kept available for users, but may have a different data policy to the current ACTRIS data policy. If this is the case, this information should be available in the metadata.

#### 4.5.1 Data and software usage licence

| Data center unit         |          Data licence                 |  Comment     |
|--------------------------|---------------------------------------|--------------|
|         In Situ		   |          To be decided                |              |
|         ARES     		   |          To be decided                |              |
|         CLU              |          To be decided                |              |                                                          
|		  ACCESS           | Will be defined by primary repository |              | 
|         ASC              | To be decided			               |              |
|		  GRES             | To be decided				           |              |

*Table x: Licences*

| Responsible data center unit         |          Software licence    |  Software link                                                        |
|--------------------------------------|------------------------------|-----------------------------------------------------------------------|
|         In Situ		               |       None                   |     [EBAS IO](https://git.nilu.no/ebas/ebas-io/wikis/home)            |
|         ARES     		               |       None                   |           [Single Calculus Chain](https://scc.imaa.cnr.it)            |

*Table x: Software*

**Consider adding a table giving an overview of when data is made available, level 2, NRT, campaign data and how this differs among the DC units**

Data quality assurance is provided by the data submitter and national facilities, appropriate topical centre, and the appropriate data centre unit.

ACTRIS as a Research infrastructure is in its preparation phase, and is expected to be fully operational within 2025, aiming to provide open-access to data throughout the lifetime of the infrastructure.

## 5. Allocation of resources

**Cathrine takes the lead on this section. Draft should be more like an abstract of the cost book**

### Estimate the costs for making your data FAIR. Describe how you intend to cover these costs

  Question not answered.

### Clearly identify responsibilities for data management in your project

  Question not answered.

### Describe costs and potential value of long term preservation

  Question not answered.

## 6. Data security

### Address data recovery as well as secure storage and transfer of sensitive data

  **Address data security related issues for each data centre unit.**

## 7. Ethical aspects

### To be covered in the context of the ethics review, ethics section of DoA and ethics deliverables. Include references and related technical aspects if not covered by the former

  Link this section to the [ACTRIS Ethical Guidelines](https://www.actris.eu/Portals/46/Documentation/ACTRIS%20PPP/Deliverables/Public/WP2_D2.2_M24.pdf?ver=2018-12-07-080117-913)

## 8. Appendix

### Appendix 1: List of ACTRIS variables and recommended methodology
[List of ACTRIS variables and recommended methodology](https://folk.nilu.no/~richard/actris-ri-variables/Appendix_I_ACTRIS-RI_variables_21February2018.xlsx)

*Additional information:* During ACTRIS-2, e.g. the aerosol and cloud databases will be augmented with new classification products developed through the combination of existing sensors with additional instrumentation; and products providing information about aerosol layering and typing, together with advanced products derived from long term series or special case analyses. In addition, new parameters utilizing these products will also be prepared, and standardized pre processed lidar data and NRT optical property profiles will be available.

### Appendix 2: List of ACTRIS level 3 data products
[List of ACTRIS level 3 data products](https://folk.nilu.no/~richard/actris-ri-variables/Appendix_II_ACTRIS-RI_level3_variables_21February2018.xlsx)

### Appendix 3: ACTRIS In situ data centre unit (In-Situ) data life cycle

#### Data Life Cycle Description

*More tables to be added regarding the workflow, currently this is an example draft*

![ACTRIS In situ data centre unit workflow diagram](https://folk.nilu.no/~markus/ACTRIS-DMP/20190424%20ACTRIS%20EBAS%20Data%20Flowchart.png)

#### Workflow Tasks Responsibilities


| Workflow Task ID           | Responsible for specification   | Responsible for implementation | Responsible for operation |
|----------------------------|---------------------------------|--------------------------------|---------------------------|
|         				     |                                 |                   			    |                           |
|              				 |                                 |                                |                           |
|                  			 |                                 |                                |                           |

Table: *Workflow Tasks Responsibilities*

#### Workflow Tasks Short Specification

| Workflow Task ID           | Short Specification   |
|----------------------------|-----------------------|
|         				     |                       |
|              				 |                       |
|                  			 |                       |

Table: *Workflow Tasks Short Specification*

### Appendix 4: ACTRIS Aerosol remote sensing data centre unit (ARES) data life cycle and workflow diagram
**Will also link to seperate document describing the workflow in more detail.**
![ACTRIS Aerosol remote sensing data centre unit workflow diagram](https://raw.githubusercontent.com/actris/data-management-plan/master/DMP/img/ACTRIS_Aerosol_Remote_Sensing_workflow.png)

### Appendix 5: ACTRIS Cloud remote sensing data centre unit (CLU) data life cycle and workflow diagram
**Will also link to seperate document describing the workflow in more detail.**
![ACTRIS Cloud remote sensing data centre unit workflow diagram](https://raw.githubusercontent.com/actris/data-management-plan/master/DMP/img/ACTRIS_cloud_remote_Sensing_workflow.png)

### Appendix 6: ACTRIS trace gases remote sensing data centre unit (GRES) data life cycle and workflow diagram
![ACTRIS trace gases remote sensing data centre unit workflow diagram](https://raw.githubusercontent.com/actris/data-management-plan/master/DMP/img/workflow_gres.png)

### Appendix 7: ACTRIS Atmospheric simulation chamber data centre unit (ASC) data life cycle and workflow diagram
![ACTRIS Atmospheric simulation chamber data centre unit workflow diagram](https://raw.githubusercontent.com/actris/data-management-plan/master/DMP/img/atm_simulation_chamber_workflow.png)

### Appendix 8: Data lifecycle and workflow for ACCESS Data Centre Unit
![ACTRIS ACCESS data centre unit workflow diagram](https://raw.githubusercontent.com/actris/data-management-plan/master/DMP/img/section3/DMP-DataAccess-MetNo-BSC.png)

### Appendix 9: List of all level 3 variables

Below is a list of all lev3 variables that are listed in Annex II and the checkbox indicates whether they are included in the lists below or not:

- [ ] Column Water Vapor Content
- [ ] Climatology products for ACTRIS variables @ ACTRIS National Facilities across Europe
- [x] Calculated Particle light scattering coefficients ** GRASP/GARRLiC **
- [x] Collocation service of data from contributing networks
- [ ] PM retrieval  @GAW sites
- [x] Single Scattering Albedo @ACTRIS National Facilities
- [x] Calculated particle light extinction coefficient ** GRASP/GARRLiC **
- [ ] Integrated full-range particle number size distribution
- [ ] Source apportionment of submicron organic aerosols in Europe
- [ ] Volatile Organic Compounds (VOC) source attribution across Europe
- [ ] Cloud occurence at cloud in situ observational platforms
- [x] Direct Sun/Moon Extinction Aerosol Optical Depth (column)
- [x] Spectral Downward Sky Radiances
- [x] Aerosol columnar properties (GRASP-AOD)
- [x] ReOBS  
- [x] Aerosol profile microphysical and optical properties ** GRASP/GARRLiC **
- [x] Satellite data – combined with ground based ACTRIS data
- [x] Aerosol and Gas trend assessment
- [x] Data Interpretation and Outlier Identification Tool
- [x] Optimal interpolation and Gap filling tool
- [x] Model Evaluation Service
- [x] NWP Model Evaluation Service
- [x] Transport modelling products for assessment of source regions
- [x] Alert Service for National Facilities

##### Collected (other than ACTRIS L0-1-2)

| Product          | format  | source    | description                                                                                                                                                                                                  |
| ---------------- | ------- | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| AERONET-NASA L1  | csv     | NASA/GSFC | [https://aeronet.gsfc.nasa.gov](https://aeronet.gsfc.nasa.gov)                                                                                                                                               |
| Terra+Aqua/MODIS | HDF4    | AERIS     | [https://modis.gsfc.nasa.gov](https://modis.gsfc.nasa.gov)                                                                                                                                                   |
| CALIPSO          | HDF4    | AERIS     | [https://www-calipso.larc.nasa.gov](https://www-calipso.larc.nasa.gov)                                                                                                                                       |
| CLOUDSAT         | HDF4    | AERIS     | [http://www.cloudsat.cira.colostate.edu](http://www.cloudsat.cira.colostate.edu)                                                                                                                             |
| PARASOL          | HDF5    | AERIS     | [http://www.icare.univ-lille1.fr/parasol](http://www.icare.univ-lille1.fr/parasol)                                                                                                                           |
| Aura/OMI         | HDF4    | AERIS     | [https://aura.gsfc.nasa.gov/omi](https://aura.gsfc.nasa.gov/omi.html)                                                                                                                                        |
| Terra/MISR       | HDF4    | AERIS     | [https://terra.nasa.gov/about/terra-instruments/misr](https://terra.nasa.gov/about/terra-instruments/misr)                                                                                                   |
| Metop/IASI       | BUFR    | AERIS     | [https://www.eumetsat.int/website/home/Satellites/CurrentSatellites/Metop/MetopDesign/IASI/index.html](https://www.eumetsat.int/website/home/Satellites/CurrentSatellites/Metop/MetopDesign/IASI/index.html) |
| MSG/SEVIRI       | NetCDF4 | AERIS     | [https://www.eumetsat.int/website/home/Satellites/CurrentSatellites/Meteosat/index.html](https://www.eumetsat.int/website/home/Satellites/CurrentSatellites/Meteosat/index.html)                             |
| AeroCom          | NetCDF4 | METNO     | https://aerocom.met.no/                                                                                                                                                                                                             |
| NWP Model data   | NetCDF4 | NWP Centres    |                                                                                                                                                                                                              |

##### Generated (systematic production)

| Product                                             | format               | description                                                                                                                                                                                  |
| --------------------------------------------------- | -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| GRASP/GARRLiC                                       | NetCDF-CF            | ACTRIS-2 GARRLiC Data Product Description. Link to be added                                                                                                                                  |
| GRASP-AOD                                           | NetCDF-CF            | Aerosol size distribution retrieval from optical depth                                                                                                                                       |
| ReOBS                                               | NetCDF-CF            | The ReOBS project proposes a scientific method to aggregate, qualify and harmonize about fifty geophysical variables at hourly scale over a decade, to allow multiannual and multi-variables studies combining atmospheric dynamics and thermodynamics, radiation, clouds and aerosols, from ground-based observations. |
| Aerosol and Gas trend assessment                                    | NetCDF-CF                            | Estimate of long term trends @ACTRIS sites, combining observations with models, interactive web visualization,  automated assessment report                                                                      |
| Data Interpretation and Outlier Identification Tool                 | NetCDF-CF                            | Quicklooks for time series data, compared to Copernicus Analysis and Reanalysis model products                                                                                                                   |
| **?** Optimal interpolation and Gap filling tool                    | NetCDF-CF                            | modal/data integration products which fill measurement gaps, eg in a time series, profile or field.                                                                                                              |
| Alert Service for National Facilities                               | [geoJSON](http://geojson.org/) **?** | Provide near real time update of special weather situations of interest for research activities at national facilities                                                                                           |

##### Generated (on-demand services)

Some products will be generated through on-line services, and will generate datasets available for a limited time on a web server.

| Product                                                             | format                               | description                                                                                                                                                                                                      |
| ------------------------------------------------------------------- | ------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Satellite data subsets                                              | NetCDF-CF                            | Satellite data subsets, spatially and temporally colocated with ACTRIS ground-based measurements                                                                                                                 |
| **?** Transport modelling products for assessment of source regions | NetCDF-CF                            | Backward transport modelling with FLEXPART to analyse air transirt and impact of various soucres. Develop tools to run FLEXPART operationally and automatically on a regular basis, e.g. monthly, for every site |
| Colocation service of data from contributing networks               | NetCDF-CF                            | Benchmark data products including relevant EMEP and ACTRIS data: PM and/or sulphate with  ACTRIS National Facilities  compiled in one data product                                                               |
| Model Evaluation Service                                            | NetCDF-CF                            | Automated model evaluation workflow, Evaluation reports of different complexity, NRT and reanalysis, climate models                                                                                              |
| NWP Model Evaluation Service                                        | NetCDF-CF                            | Automated model evaluation workflow, evaluation reports of different complexity for NWP models, NRT and reanalysis, NWP models                     
