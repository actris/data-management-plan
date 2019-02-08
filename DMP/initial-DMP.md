# ACTRIS Research Infrastructure initial outline of DMP

# Table of Contents
* [1. Introduction to ACTRIS and The ACTRIS Data Centre](#1-Introduction-to-ACTRIS-and-The-ACTRIS-Data-Centre)
  * [1.1. ACTRIS data set descriptions and ACTRIS data levels](#1-1-ACTRIS-data-set-descriptions-and-ACTRIS-data-levels)
* [2. Data summary for ACTRIS data centre](#2-Data-summary-for-ACTRIS-data-centre)
  * [2.1. Data summary of the ACTRIS In situ data centre unit (In-Situ)](#in-situ-summary)
  * [2.2. Data summary of the ACTRIS Aerosol remote sensing data centre unit (ARES)](#ares-summary)
  * [2.3. Data summary of the ACTRIS Cloud remote sensing data centre unit (CLU)](#clu-summary)
  * [2.4. Data summary of the ACTRIS trace gases remote sensing data centre unit (GRES)](#gres-summary)
  * [2.5. Data summary of the ACTRIS Atmospheric simulation chamber data centre unit (ASC)](#asc-summary)
  * [2.6. Data summary of the data products providers (level 3 data/abbreviation missing)](#level3-summary)
* [3. Data Management at the ACTRIS data centre](#3-Data-Management-at-the-ACTRIS-data-centre)
  * [Findable: Making data findable, including provisions for metadata [FAIR data]](#findable)
  * [Accessible: Making data openly accessible [FAIR data]](#accessible)
  * [Interoperable: Making data interoperable [FAIR data]](#interoperable)
  * [Reuseable: Increase data re-use (through clarifying licenses) [FAIR data]](#reusable)
* [4. Allocation of resources](#4-Allocation-of-resources)
* [5. Data security](#5-Data-security)
* [6. Ethical aspects](#6-Ethical-aspects)
* [7. Other](#7-Other)
* [8. Appendix](#8-Appendix)
  * [Appendix 1: List of ACTRIS variables and recommended methodology](#Appendix-1-List-of-ACTRIS-variables-and-recommended-methodology)
  * [Appendix 2: List of ACTRIS level 3 data products](#Appendix-2-List-of-ACTRIS-level-3-data-products)
  * [Appendix 3: ACTRIS In situ data centre unit (In-Situ) data life cycle](#Appendix-3-ACTRIS-In-situ-data-centre-unit-In-Situ-data-life-cycle)
  * [Appendix 4: ACTRIS Aerosol remote sensing data centre unit (ARES) data life cycle and workflow diagram](#Appendix-4-ACTRIS-Aerosol-remote-sensing-data-centre-unit-data-life-cycle-and-workflow-diagram)
  * [Appendix 5: ACTRIS Cloud remote sensing data centre unit (CLU) data life cycle and workflow diagram](#Appendix-5-ACTRIS-Cloud-remote-sensing-data-centre-unit-data-life-cycle-and-workflow-diagram)
  * [Appendix 6: ACTRIS trace gases remote sensing data centre unit (GRES) data life cycle and workflow diagram](#Appendix-6-ACTRIS-trace-gases-remote-sensing-data-centre-unit-data-life-cycle-and-workflow-diagram)
  * [Appendix 7: ACTRIS Atmospheric simulation chamber data centre unit (ASC) data life cycle and workflow diagram](#Appendix-7-ACTRIS-Atmospheric-simulation-chamber-data-centre-unit-data-life-cycle-and-workflow-diagram)
  * [Appendix 8: Data lifecycle and workflow for ACCESS Data Centre Unit](#Appendix-8-Data-lifecycle-and-workflow-for-ACCESS-Data-Centre-Unit)

## 1. Introduction to ACTRIS and The ACTRIS Data Centre

The Research Infrastructure (RI) ACTRIS – Aerosols, Clouds, and Trace Gases is the pan-European RI that consolidates activities amongst European partners for observations of aerosols, clouds, and trace gases and for understanding of the related atmospheric processes, as well as to provide RI services to wide user groups. ACTRIS is a unique research infrastructure improving the quality of atmospheric observations, developing new methods and protocols, and harmonizing existing observations of the atmospheric variables listed in Appendix 1.

The overall goal of the ACTRIS Data Centre is to provide scientists and other user groups with free and open access to all ACTRIS infrastructure data, complemented with access to innovative and mature data products, together with tools for quality assurance (QA), data analysis and research, following the [FAIR principles](https://www.force11.org/group/fairgroup/fairprinciples). The numerous measurement methodologies applied in ACTRIS result in a considerable diversity of the data collected. In accordance with these requirements, the ACTRIS Data Centre will be organized in 6 Units, with clear links and procedures for interaction between the data center Units, National Facilities (NFs) and topical centres (TCs). The ACTRIS DC will be coordinated by the ACCESS unit leader and all data is linked through the [ACTRIS data portal](http://actris.nilu.no/) to provide a single access point to all data and related information. The units are:

* [ACTRIS In situ data centre unit (In-Situ)](http://ebas.nilu.no/)
* [ACTRIS Aerosol remote sensing data centre unit (ARES)](http://access.earlinet.org/EARLINET/)
* [ACTRIS Cloud remote sensing data centre unit (CLU)](http://cloudnet.fmi.fi/)
* ACTRIS trace gases remote sensing data centre unit (GRES) 
* [ACTRIS Atmospheric simulation chamber data centre unit (ASC)](https://data.eurochamp.org/)

![Architecture of the ACTRIS Data Centre](https://raw.githubusercontent.com/actris/data-management-plan/master/DMP/img/ACTRIS_data_centre_elements_phase2.jpg)
*Figure 1: Architecture of the ACTRIS Data Centre*

During the ACTRIS implementation phase (expected 2020-2024), the Central Facilities are constructed and their services are tested. ACTRIS operations will start step-by-step by ramping up the service provision. After the necessary legal preparations, ACTRIS shall become a legal entity (ERIC, European Research Infrastructure Consortium) funded by the Member countries. The target is to launch ACTRIS ERIC in the beginning of 2021. It is foreseen that ACTRIS will be fully operational by 2025. The ACTRIS Central Facilities host selection was a part of ACTRIS PPP, and the following consortium is selected to host the ACTRIS Data Center, and the various units with services to data producers and data users.

<table width="100%" cellspacing="0" cellpadding="7">
<tbody>
<tr valign="top">
<td width="17%" height="70">
<p lang="nb-NO" align="justify"><span lang="en-GB"><strong>Name of Central Facility Unit</strong></span></p>
</td>
<td width="16%">
<p lang="nb-NO" align="justify"><span lang="en-GB"><strong>Hosting institution and contribution</strong></span></p>
</td>
<td width="67%">
<p lang="nb-NO" align="justify"><span lang="en-GB"><strong>Main activities</strong></span></p>
</td>
</tr>
<tr valign="top">
<td width="17%" height="48">
<p lang="nb-NO" align="justify"><span lang="en-GB">ACTRIS Data Centre</span></p>
</td>
<td width="16%">
<p lang="nb-NO" align="justify"><span lang="en-GB">Lead NILU, contributions by all.</span></p>
</td>
<td width="67%">
<p lang="en-GB" align="justify"><br /><br /></p>
<p lang="nb-NO" align="justify"><span lang="en-GB">Coordinate the work and the interaction and reporting to the Head Office</span></p>
</td>
</tr>
<tr valign="top">
<td width="17%" height="20">
<p align="justify"><span lang="en-GB">ACTRIS data and services access unit (ACCESS)</span></p>
<p lang="en-GB" align="justify">&nbsp;</p>
</td>
<td width="16%">
<p lang="nb-NO" align="justify"><span style="color: #000000;"><span lang="en-GB"><strong>NILU (lead)</strong></span></span><span style="color: #000000;"><span lang="en-GB"> CNRS </span></span><span lang="en-GB">MetNo, </span><span style="color: #000000;"><span lang="en-GB">BSC</span></span></p>
</td>
<td width="67%">
<p lang="nb-NO" align="justify"><span style="color: #000000;"><span lang="en-GB">ACTRIS web interface for data, services and tools, called &ldquo;</span></span><span style="color: #000000;"><span lang="en-GB"><em>The ACTRIS Data Centre</em></span></span><span style="color: #000000;"><span lang="en-GB">&rdquo;. </span></span><span lang="en-GB">Main activities are </span><span lang="en-GB"><strong>Discovery and access </strong></span><span lang="en-GB">to</span> <span lang="en-GB">ACTRIS data and data products, digital tools provided by the topic centres and the data centre units, documentation, software and tools for data production. </span><span lang="en-GB"><strong>Visualisation </strong></span><span lang="en-GB">of</span> <span lang="en-GB">ACTRIS data products. </span><span lang="en-GB"><strong>Data production </strong></span><span lang="en-GB">of selected</span> <span lang="en-GB">Level 3 data and synergy data products. The data centre will offer </span><span lang="en-GB"><strong>bridge to external data bases and sources</strong></span><span lang="en-GB">.</span></p>
</td>
</tr>
<tr valign="top">
<td width="17%" height="100">
<p align="justify"><span lang="en-GB">ACTRIS In situ data centre unit (In-Situ)</span></p>
</td>
<td width="16%">
<p lang="nb-NO" align="justify"><span style="color: #000000;"><span lang="en-GB"><strong>NILU</strong></span></span></p>
</td>
<td width="67%">
<p lang="nb-NO" align="justify"><span lang="en-GB">Data curation service for In situ data: all aerosol, cloud and trace gas in situ data. This comprises inclusion of data in the data base EBAS, archiving and documentation. Support for centralized data processing, harmonization, traceability, quality control and product generation. Training and online tools for QA, QC. The activity enables RRT and NRT delivery.</span></p>
</td>
</tr>
<tr valign="top">
<td width="17%" height="54">
<p align="justify"><span lang="en-GB">ACTRIS Aerosol remote sensing data centre unit (ARES)</span></p>
</td>
<td width="16%">
<p lang="nb-NO" align="justify"><span lang="en-GB"><strong>CNR (Lead)</strong></span><span lang="en-GB"> CNRS</span></p>
<p lang="en-GB" align="justify">&nbsp;</p>
</td>
<td width="67%">
<p lang="nb-NO" align="justify"><span lang="en-GB">Aerosol remote sensing data processing and curation. This includes centralized processing, traceability, harmonization and data versioning, quality control, data provision and archiving, and documentation. The activity enables RRT and NRT delivery. Tutorial activities. Production of level 3 data for climatological analysis and new products</span></p>
</td>
</tr>
<tr valign="top">
<td width="17%" height="80">
<p align="justify"><span lang="en-GB">ACTRIS Cloud remote sensing data centre unit (CLU)</span></p>
</td>
<td width="16%">
<p lang="nb-NO" align="justify"><span lang="en-GB"><strong>FMI</strong></span></p>
</td>
<td width="67%">
<p lang="nb-NO" align="justify"><span lang="en-GB">Data curation service for cloud remote sensing data. Support for centralized cloud remote sensing data processing, harmonization, automated quality control and product generation. Enables RRT and NRT delivery. Production of level 3 data for NWP model evaluation</span></p>
</td>
</tr>
<tr valign="top">
<td width="17%">
<p align="justify"><span lang="en-GB">ACTRIS Atmospheric simulation chamber data centre unit (ASC)</span></p>
</td>
<td width="16%">
<p lang="nb-NO" align="justify"><span lang="en-GB"><strong>CNRS</strong></span></p>
</td>
<td width="67%">
<p lang="nb-NO" align="justify"><span lang="en-GB">Atmospheric simulation chamber data services curation, provision, standardized process for data submission</span></p>
</td>
</tr>
<tr valign="top">
<td bgcolor="#ffffff" width="17%">
<p align="justify"><span style="color: #000000;"><span lang="en-GB">ACTRIS trace gases remote sensing data centre unit</span></span></p>
<p align="justify"><span style="color: #000000;"><span lang="en-GB">(GRES)</span></span></p>
</td>
<td bgcolor="#ffffff" width="16%">
<p lang="nb-NO" align="justify"><span style="color: #000000;"><span lang="en-GB"><strong>CNRS</strong></span></span></p>
</td>
<td bgcolor="#ffffff" width="67%">
<p align="justify"><span style="color: #000000;"><span lang="en-GB">Data curation service for reactive trace gases remote sensing data. This comprises standardized process for data submission, quality control, inclusion of data in the data base, search metadata creation and provision and archiving.</span></span></p>
<p lang="nb-NO" align="justify"><span style="color: #000000;"><span lang="en-GB">Production of level 3 data for climatological analysis, and added values products (quicklooks, links to EVDC - ESA Atmospheric Validation Data Centre).</span></span></p>
</td>
</tr>
</tbody>
</table>

### 1.1. ACTRIS data set descriptions and ACTRIS data levels

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

## 2. Data summary for ACTRIS data centre

**Move general content here from data centre unit text**

### 2.1.Data summary of the ACTRIS In situ data centre unit (In-Situ)

#### The purpose of the data collection/generation

The purpose of the data collection and generation of data products is to provide open access to aerosol, cloud and trace gas in situ measurements of high quality, benefiting scientists and policy makers, as well as the private sector, educators and the general public. See the [Stakeholder Handbook](http://www.actris.eu/Portals/46/Documentation/ACTRIS%20PPP/Stakeholder%20Handbook/high_res_version.pdf?ver=2018-06-04-080105-217) for more information.

#### The relation to the objectives of the project

Data management of ACTRIS in situ data relates to the ability to predict the future behaviour of the atmosphere over all time scales. High quality observation data facilitates this and needs to be supported by:
  * Documentation of archiving procedures and access to level 0 data
  * Long-term archiving and preservation of ACTRIS level 1 to level 3 data and data products
  * Access to ACTRIS data, data products, and digital tools through a single point of entry, the ACTRIS data user interface
  * Documentation of data, data flow, citation service, and data attribution, including version control, data traceability, and interoperability,
  * Data curation and support for campaigns and dedicated research projects and initiatives, external or internal to ACTRIS.

#### The types and formats of data generated/collected
The ACTRIS In situ data centre unit is supported by the [EBAS database infrastructure](http://ebas.nilu.no/ResourcesATMOS/AboutEBAS.pdf). Data submitted to EBAS need to be formatted in the EBAS NASA-Ames format by the data provider, and there is exsisting instructions and template for each instrument/group of instruments. [The EBAS NASA-Ames format](https://projects.nilu.no//ccc/tfmm/kjeller_2016/EBAS_Data_Format_2016-10.pdf) is based on the ASCII text NASA-Ames 1001 format, but contains additional metadata specifications ensuring proper documentation from the [EBAS-Submit documentation](https://ebas-submit.nilu.no/) website as well as tools for [file-generation](http://dev-ebas-file-generation-tool.nilu.no/) (*beta*) and [file-submission](https://ebas-submit-tool.nilu.no/).

#### Re-use of existing data

The ACTRIS data user interface will include access to ACTRIS In situ data and legacy data resulting from ACTRIS pre-projects.

#### The origin of the data

The origin of the data is derived from instrument raw data, either through online or offline observations.

#### The expected size of the data

<table width="604" cellspacing="0" cellpadding="7"> <tbody> <tr> <td rowspan="3" width="100" height="26"> <p class="western" lang="en-GB" align="center">&nbsp;</p> </td> <td colspan="3" width="225"> <p class="western" align="center"><span lang="en-GB"><strong>Number of annual data sets</strong></span></p> </td> <td colspan="3" width="235"> <p class="western" align="center"><span lang="en-GB"><strong>Data volume</strong></span></p> </td> </tr> <tr> <td rowspan="2" width="66"> <p class="western" align="center"><span lang="en-GB"><strong>Now</strong></span></p> </td> <td colspan="2" width="145"> <p class="western" align="center"><span lang="en-GB"><strong>by 2025</strong></span></p> </td> <td rowspan="2" width="69"> <p class="western" align="center"><span lang="en-GB"><strong>Now</strong></span></p> </td> <td colspan="2" width="152"> <p class="western" align="center"><span lang="en-GB"><strong>by 2025</strong></span></p> </td> </tr> <tr> <td width="66"> <p class="western" align="center"><span lang="en-GB"><strong>Min.</strong></span></p> </td> <td width="66"> <p class="western" align="center"><span lang="en-GB"><strong>Max.</strong></span></p> </td> <td width="69"> <p class="western" align="center"><span lang="en-GB"><strong>Min.</strong></span></p> </td> <td width="69"> <p class="western" align="center"><span lang="en-GB"><strong>Max.</strong></span></p> </td> </tr> <tr> <td width="100"> <p class="western" align="left"><span lang="en-GB">ACTRIS in situ aerosol data</span></p> </td> <td width="66"> <p class="western" align="center"><span style="color: #000000;"><span lang="en-GB">60</span></span></p> </td> <td width="66"> <p class="western" align="center"><span style="color: #000000;"><span lang="en-GB">50</span></span></p> </td> <td width="66"> <p class="western" align="center"><span style="color: #000000;"><span lang="en-GB">120</span></span></p> </td> <td width="69"> <p class="western" align="center"><span style="color: #000000;"><span lang="en-GB">18&nbsp;000 MB</span></span></p> </td> <td width="69"> <p class="western" align="center"><span style="color: #000000;"><span lang="en-GB">15&nbsp;000 MB</span></span></p> </td> <td width="69"> <p class="western" align="center"><span style="color: #000000;"><span lang="en-GB">50&nbsp;000 MB</span></span></p> </td> </tr> <tr> <td width="100"> <p class="western" align="left"><span lang="en-GB">ACTRIS in situ cloud data</span></p> </td> <td width="66"> <p class="western" align="center"><span style="color: #000000;"><span lang="en-GB">0</span></span></p> </td> <td width="66"> <p class="western" align="center"><span style="color: #000000;"><span lang="en-GB">35</span></span></p> </td> <td width="66"> <p class="western" align="center"><span style="color: #000000;"><span lang="en-GB">105</span></span></p> </td> <td width="69"> <p class="western" align="center"><span style="color: #000000;"><span lang="en-GB">0</span></span></p> </td> <td width="69"> <p class="western" align="center"><span style="color: #000000;"><span lang="en-GB">1 GB</span></span></p> </td> <td width="69"> <p class="western" align="center"><span style="color: #000000;"><span lang="en-GB">3 GB</span></span></p> </td> </tr> <tr> <td width="100"> <p class="western" align="left"><span lang="en-GB">ACTRIS in situ trace gas data</span></p> </td> <td width="66"> <p class="western" align="center"><span style="color: #000000;"><span lang="en-GB">27</span></span></p> </td> <td width="66"> <p class="western" align="center"><span style="color: #000000;"><span lang="en-GB">30</span></span></p> </td> <td width="66"> <p class="western" align="center"><span style="color: #000000;"><span lang="en-GB">60</span></span></p> </td> <td width="69"> <p class="western" align="center"><span style="color: #000000;"><span lang="en-GB">300 MB</span></span></p> </td> <td width="69"> <p class="western" align="center"><span style="color: #000000;"><span lang="en-GB">200 MB</span></span></p> </td> <td width="69"> <p class="western" align="center"><span style="color: #000000;"><span lang="en-GB">400 MB</span></span></p> </td> </tr> </tbody> </table>
*Table 1: Expected size of the data coming from the in situ data center unit*

#### Data utility: to whom will it be useful

ACTRIS will produce data and data products essential to a wide range of communities, including:

  * Atmospheric science research communities world-wide (climate and air-quality, observational/ experimental/ modelling/ satellite communities, national and international research programmes and organisations); 
  * Environmental science research communities and communities from other neighbouring fields: hydro-marine, bio-ecosystem, geosciences, space physics, energy, health, and food domain, to study interactions and processes in across different disciplines;
  * Instrument manufacturers and sensor industries for development, testing, prototyping and demonstration;
  * Operational services, National weather services, climate services for model validation, weather and climate analysis and forecasting;
  * Space agencies for validation and the development of new satellite missions; 
  * National and regional air quality monitoring networks and environmental protection agencies for air quality assessments and validation of air pollution
models; 
  * Policy makers and local/ regional/ national authorities for climate and air-quality related information for decision making and policy development.

#### Outline of data life cycle (workflow and workflow diagram)
Detail on the data life cycle and workflow (workflow diagrams for data production) for In situ observations can be found in [*Appendix 3: ACTRIS in situ aerosol, cloud and trace gas data lifecycle and workflow (draft)*](https://github.com/actris/data-management-plan/blob/master/DMP/initial-DMP.md#appendix-3-actris-in-situ-data-centre-unit-in-situ-data-life-cycle-and-workflow-diagram).

### 2.2. Data summary of the ACTRIS Aerosol remote sensing data centre unit (ARES)

* State the purpose of the data collection/generation
* Explain the relation to the objectives of the project
* Specify the types and formats of data generated/collected
* Specify if existing data is being re-used (if any)
* Specify the origin of the data
* State the expected size of the data (if known)
* Outline the data utility: to whom will it be useful
* Outline of workflow and workflow diagram

### 2.3. Data summary of the ACTRIS Cloud remote sensing data centre unit (CLU)

* State the purpose of the data collection/generation
* Explain the relation to the objectives of the project
* Specify the types and formats of data generated/collected
* Specify if existing data is being re-used (if any)
* Specify the origin of the data
* State the expected size of the data (if known)
* Outline the data utility: to whom will it be useful
* Outline of workflow and workflow diagram

### 2.4. Data summary of the ACTRIS trace gases remote sensing data centre unit (GRES)

* State the purpose of the data collection/generation
* Explain the relation to the objectives of the project
* Specify the types and formats of data generated/collected
* Specify if existing data is being re-used (if any)
* Specify the origin of the data
* State the expected size of the data (if known)
* Outline the data utility: to whom will it be useful
* Outline of workflow and workflow diagram

### 2.5. Data summary of the ACTRIS Atmospheric simulation chamber data centre unit (ASC) 

* State the purpose of the data collection/generation
* Explain the relation to the objectives of the project
* Specify the types and formats of data generated/collected
* Specify if existing data is being re-used (if any)
* Specify the origin of the data
* State the expected size of the data (if known)
* Outline the data utility: to whom will it be useful
* Outline of workflow and workflow diagram

### 2.6. Data summary of the data products providers (level 3 data/abbreviation missing)

* State the purpose of the data collection/generation
* Explain the relation to the objectives of the project
* Specify the types and formats of data generated/collected
* Specify if existing data is being re-used (if any)
* Specify the origin of the data
* State the expected size of the data (if known)
* Outline the data utility: to whom will it be useful
* Outline of workflow and workflow diagram

## 3. Data Management at the ACTRIS data centre
**Remove references to ACCESS**
### 3.1. Findable: Making data findable, including provisions for metadata [FAIR data]

#### Outline the discoverability of data (metadata provision)

  Present the discoverability of the data at ACTRIS data and services access unit (ACCESS) level.
  **mentioning of data resides at each data centre unit (maybe under i)**
#### Outline the identifiability of data and refer to standard identification mechanism. Do you make use of persistent and unique identifiers such as Digital Object Identifiers?

  Present the identification mechanisms from each individual data centre unit -> ACCESS unit.

#### Outline naming conventions used

  Present naming conventions at both the data centre unit level and the ACCESS level.

#### Outline the approach towards search keyword

  Approach towards search keywords at the ACTRIS data and services access unit level. E.g. mapping of keywords in relation to the metadata standards (iso19115/iso19139)?

#### Outline the approach for clear versioning

  Discuss both on ACCESS and unit level.

#### Specify standards for metadata creation (if any). If there are no standards in your discipline describe what metadata will be created and how

   ACTRIS aiming at following the [INSPIRE](https://eur-lex.europa.eu/legal-content/EN/ALL/?uri=CELEX:32007L0002) directive for metadata formatting. Present standard(s) for metadata at the ACTRIS data and services access unit level. Must decide if data centre units should provide metadata according to a specific standards, as well as providing metadata from the ACTRIS DC to the ENVRI cluster, EOSC etc.

### 3.2. Accessible: Making data openly accessible [FAIR data]

#### Specify which data will be made openly available? If some data is kept closed provide rationale for doing so

  Specify data access policy at the ACCESS unit level and possibly link this section to the existing access policy document: Deliverable 2.6:ACTRIS access and service policy

#### Specify how the data will be made available

  Specify data availability at the ACCESS unit level. Mention hosting at each unit, formats, interfaces ++.

#### Specify what methods or software tools are needed to access the data? Is documentation about the software needed to access the data included? Is it possible to include the relevant software (e.g. in open source code)?

  Specify for each individual data centre unit and for the ACTRIS ACCESS unit, or only at the ACCESS unit level?

#### Specify where the data and associated metadata, documentation and code are deposited

  Specify technical details related to the ACCESS unit.

#### Specify how access will be provided in case there are any restrictions

  Question not answered.

### 3.3. Interoperable: Making data interoperable [FAIR data]

#### Assess the interoperability of your data. Specify what data and metadata vocabularies, standards or methodologies you will follow to facilitate interoperability. 

  Present data and metadata standards. E.g. NetCDF/CF and iso19115/iso19113.

#### Specify whether you will be using standard vocabulary for all data types present in your data set, to allow inter-disciplinary interoperability? If not, will you provide mapping to more commonly used ontologies?

  Standard vocabulary will not always be used, but in all cases these will be mapped to standard vocabulary where exisitng at the DC ACCESS unit.

### 3.4. Reuseable: Increase data re-use (through clarifying licenses) [FAIR data]

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

## 4. Allocation of resources

### Estimate the costs for making your data FAIR. Describe how you intend to cover these costs

  Question not answered. Draft should be provided by Cathrine.

### Clearly identify responsibilities for data management in your project

  Question not answered.

### Describe costs and potential value of long term preservation

  Question not answered.

## 5. Data security

### Address data recovery as well as secure storage and transfer of sensitive data 

  Question not answered.

## 6. Ethical aspects

### To be covered in the context of the ethics review, ethics section of DoA and ethics deliverables. Include references and related technical aspects if not covered by the former 

  Link this section to the [ACTRIS Ethical Guidelines](https://www.actris.eu/Portals/46/Documentation/ACTRIS%20PPP/Deliverables/Public/WP2_D2.2_M24.pdf?ver=2018-12-07-080117-913)

## 7. Other

### Refer to other national/funder/sectorial/departmental procedures for data management that you are using (if any) 

  Question not answered.

## 8. Appendix

### Appendix 1: List of ACTRIS variables and recommended methodology
[List of ACTRIS variables and recommended methodology](https://folk.nilu.no/~richard/actris-ri-variables/Appendix_I_ACTRIS-RI_variables_21February2018.xlsx)

### Appendix 2: List of ACTRIS level 3 data products
[List of ACTRIS level 3 data products](https://folk.nilu.no/~richard/actris-ri-variables/Appendix_II_ACTRIS-RI_level3_variables_21February2018.xlsx)

### Appendix 3: ACTRIS In situ data centre unit (In-Situ) data life cycle

#### Data Life Cycle Description

**More tables to be added regarding the workflow, currently this is an example draft**

![ACTRIS In situ data centre unit workflow diagram](https://folk.nilu.no/~richard/actris-ri-variables/ACTRIS_surface_insitu_workflow.jpg)

#### Workflow Tasks Responsibilities

<table style="height: 254px;" width="826"> <tbody> <tr> <th style="width: 206.25px;">&nbsp;</th> <th style="width: 206.25px;" colspan="3">&nbsp;Responsible for</th> </tr> <tr> <th style="width: 206.25px;">&nbsp;Workflow Task ID</th> <th style="width: 206.25px;">&nbsp;Specification</th> <th style="width: 206.25px;">&nbsp;Implementation</th> <th style="width: 206.25px;">&nbsp;Operation</th> </tr> <tr> <td style="width: 206.25px;">&nbsp;</td> <td style="width: 206.25px;">&nbsp;</td> <td style="width: 206.25px;">&nbsp;</td> <td style="width: 206.25px;">&nbsp;</td> </tr> <tr> <td style="width: 206.25px;">&nbsp;</td> <td style="width: 206.25px;">&nbsp;</td> <td style="width: 206.25px;">&nbsp;</td> <td style="width: 206.25px;">&nbsp;</td> </tr> </tbody> </table> 

#### Workflow Tasks Short Specification 

<table style="height: 254px; width: 826px;"> <tbody> <tr> <th style="width: 16.1667px;">&nbsp;Workflow Task ID</th> <th style="width: 395.833px;">&nbsp;Short Specification</th> </tr> <tr> <td style="width: 16.1667px;">&nbsp;</td> <td style="width: 395.833px;">&nbsp;</td> </tr> <tr> <td style="width: 16.1667px;">&nbsp;</td> <td style="width: 395.833px;">&nbsp;</td> </tr> </tbody> </table>

### Appendix 4: ACTRIS Aerosol remote sensing data centre unit (ARES) data life cycle and workflow diagram
![ACTRIS Aerosol remote sensing data centre unit workflow diagram](https://raw.githubusercontent.com/actris/data-management-plan/master/DMP/img/ACTRIS_Aerosol_Remote_Sensing_workflow.jpg)

### Appendix 5: ACTRIS Cloud remote sensing data centre unit (CLU) data life cycle and workflow diagram
![ACTRIS Cloud remote sensing data centre unit workflow diagram](https://raw.githubusercontent.com/actris/data-management-plan/master/DMP/img/ACTRIS_cloud_remote_Sensing_workflow.png)

### Appendix 6: ACTRIS trace gases remote sensing data centre unit (GRES) data life cycle and workflow diagram
![ACTRIS trace gases remote sensing data centre unit workflow diagram](https://raw.githubusercontent.com/actris/data-management-plan/master/DMP/img/workflow_gres.png)

### Appendix 7: ACTRIS Atmospheric simulation chamber data centre unit (ASC) data life cycle and workflow diagram
![ACTRIS Atmospheric simulation chamber data centre unit workflow diagram](https://raw.githubusercontent.com/actris/data-management-plan/master/DMP/img/atm_simulation_chamber_workflow.png)

### Appendix 8: Data lifecycle and workflow for ACCESS Data Centre Unit

