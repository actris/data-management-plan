# ACTRIS Research Infrastructure initial outline of DMP

# Table of contents

* [1. Introduction to ACTRIS and The ACTRIS Data Centre](#1-Introduction-to-ACTRIS-and-The-ACTRIS-Data-Centre)
  * [1.1. ACTRIS data set descriptions and ACTRIS data levels](#11-actris-data-set-descriptions-and-actris-data-levels)
* [2. Data summary for ACTRIS data centre](#2-Data-summary-for-ACTRIS-data-centre)
  * [2.1. Data summary of the ACTRIS In situ data centre unit (In-Situ)](#21data-summary-of-the-actris-in-situ-data-centre-unit-in-situ)
  * [2.2. Data summary of the ACTRIS Aerosol remote sensing data centre unit (ARES)](#22-data-summary-of-the-actris-aerosol-remote-sensing-data-centre-unit-ares)
  * [2.3. Data summary of the ACTRIS Cloud remote sensing data centre unit (CLU)](#23-data-summary-of-the-actris-cloud-remote-sensing-data-centre-unit-clu)
  * [2.4. Data summary of the ACTRIS trace gases remote sensing data centre unit (GRES)](#24-data-summary-of-the-actris-trace-gases-remote-sensing-data-centre-unit-gres)
  * [2.5. Data summary of the ACTRIS Atmospheric simulation chamber data centre unit (ASC)](#25-data-summary-of-the-actris-atmospheric-simulation-chamber-data-centre-unit-asc)
  * [2.6. Data summary of the data products providers (level 3 data/abbreviation missing)](#26-data-summary-of-the-data-products-providers-level-3-dataabbreviation-missing)
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

**Describe briefly data management for each data center unit. (Could we move this up to section 2 and include this as a part of the data summary for the data center units)**

Data management is handled by the individual data center unit:

* ACTRIS In situ data centre unit for all aerosol, cloud and trace gas in situ data
* ACTRIS Aerosol remote sensing data centre unit
* ACTRIS Cloud remote sensing data centre unit
* ACTRIS Trace gases remote sensing data centre unit
* ACTRIS Atmospheric simulation chamber data centre unit. 

Access to quality controlled data from the data center units above is provided by the ACTRIS data and service access unit (ACCESS). The ACCESS unit is not only responsible for access to measurement data, but also services, tools and providing documentation, all which is based on metadata provided by the data center units. Currently there are 3 data center units providing metadata (including details on how to access measurement data), this includes data from the Cloudnet (Cloud remote sensing) database, Earlient (Aerosol remote sensing) database and the EBAS (aerosol, cloud and trace gas in situ data) database. The metadata is used as input to the current ACTRIS metadata catalog providing access to data throught the [ACTRIS data portal](http://actris.nilu.no/). Primary datasets are regularly updated through the metadata catalogue, typically every night or on a weekly basis, through various procedures, so potentially new data added to the topical databases are available through the portal the following day. 

Furthermore the ACCESS unit is showcasing NRT data providing quicklook images for the following:

* [near surface and cloud data](http://actris.nilu.no/Content/?pageid=844fe06802f04a83a2d6b0e8b2a59fe2)
* [aerosol profiles](http://actris.nilu.no/Content/?pageid=ae1bf05f1fa54ba8bae735a2420e6c8d)

ACTRIS level 3 data are elaborated ACTRIS data products derived by post-processing of ACTRIS Level 0 -1 -2, and data from other sources. The data can be gridded or not. Level 3 datasets are derived from measurement data, where the measurements are reported to the ACTRIS topic data repositories. The datasets are derived by e.g. averaging, filtering of events, interpolation of measurement data and are usually the a result of analysis for special studies or processed for model experiments. The [secondary data archive](http://actris.nilu.no/Content/?pageid=226809f7a0ac49538914eeafb4448afa) stores secondary data sets to provide long term access for all users, including the possibility to issue a Digital Object Identifier (DOI). Secondary datasets are normally not updated over time.

![Core structure of the ACTRIS Data Centre](https://raw.githubusercontent.com/actris/data-management-plan/master/DMP/img/architecture_actris_data_portal.png)

*Figure x: Overview of the core structure of the ACTRIS Data Centre (uppder panel) and technical solution of the meta data transfer and access of data through the ACTRIS data portal (lower panel).*



**ACCESS unit takes the lead on this section**
### 3.1. Findable: Making data findable, including provisions for metadata [FAIR data]

ACTRIS will collect data and metadata from a large range of observations provided by multiple data center units covering different types of data both in terms of size, time coverage and metadata. The ACCESS unit should provide discovery metadata for all ACTRIS data, using a common standard that is WIS compliant such as ISO19139 or ISO19115.

Future efforts should make it possible for the ACCESS unit to harvest all metadata from the different data center units and collect this in the a central ACTRIS metadata catalog and provide this through a commonly used protocol for Metadata harvesting like OAI-PMH or similar.

There migh be instances where standards does not cover the need for describing the data at the data center unit. In this case, one should still try to provide metadata in a way that is similar to the agreed formats and standards and at the same time push for an extension of the specified standard.

The core responsibility of metadata provisioning is at the data center unit level. The role of the ACCESS unit is to harvest metadata records for the ACTRIS metadata catalog as well as putting in place instruments for monitoring data/metadata provisioning as well as collecting user statistics (inspections, plotting and download of data) related to the ACTRIS Data Portal and the ACTRIS metadata catalog.

Generally, ACTRIS data set names aims to be compliant with [CF (Climate and Forecast) metadata conventions](http://cfconventions.org/standard-names.html). In the case where no standard CF names are defined, an application will be sent to establish these.

ACTRIS works towards establishing traceability for all applicable variables using persistent identifiers (PIDs). This is to assure proper attribution is given to data originators adequately reflecting their contributions. Currently ACTRIS is using  digital object identifiers (DOIs) for all secondary datasets though the [Data Cite Metadata Store API](https://mds.datacite.org/).

Currently there is no search model used by the ACCESS unit (ACTRIS data portal). Still search keywords are implemented to varying degrees on the individual data center unit level (e.g. search keywords are used for the EBAS ISO19115 records). The ACTRIS data center should in the future use a controlled set of vocabularies for search keywords like [Global Change Master Directory (GCMD)](https://earthdata.nasa.gov/about/gcmd/global-change-master-directory-gcmd-keywords) or similar.

ACTRIS aiming at following the [INSPIRE](https://eur-lex.europa.eu/legal-content/EN/ALL/?uri=CELEX:32007L0002) directive for metadata formatting. Present standard(s) for metadata at the ACTRIS data and services access unit level. Must decide if data centre units should provide metadata according to a specific standards, as well as providing metadata from the ACTRIS DC to the ENVRI cluster, EOSC etc.

The ACTRIS DC aims at providing clear versioning of its data and metadata, due to the decentralised nature of the Data Centre, this varies between the different data centre units.

As a guiding principle, all data submitted to ACTRIS passing quality assurance should be uniquely identified. In case of updates, a ID-number is generated, and previous data versions should be identifiable and kept available upon request while the latest version is served through the ACTRIS data portal web-interface.

### 3.2. Accessible: Making data openly accessible [FAIR data]

The main access point to ACTRIS data will be through the [ACTRIS data portal](http://actris.nilu.no/), this will be a web portal that allows the user to search, analyse and download data produced within ACTRIS. Access to data and metadata should also be made possible by machine-to-machine interaction, enabling harvesting of metadata from the ACTRIS metadata catalog, for example setting up a ACTRIS OAI-PMH server.

The guiding principle is free and open access to data abd data products.

There might also be data available through the actris data portal that is not directly actris data, but used in the interpretation of ACTRIS data.

**The following types of data is provided:**

* **Type 1: The ACTRIS data**
   * Data are funded and produced within the context of the ACTRIS project. Every dataset created within ACTRIS is owned by the ACTRIS partner(s) who created this dataset, and the ACTRIS data policy can be found here. A description of ACTRIS data is provided in the "ACTRIS Data management Plan".
    
* **Type 2: Other data available through the portal**
  * Data are archived and owned by other organisations or data providers and are hosted at other databases. Type 2 data are provided with the permission of each organisation or data provider contributing to the data archive. Each dataset of type II may have its own data policy that will supersede the ACTRIS data policy.

Still individual data center units will also serve as access points for ACTRIS data. But that is out of scope for this document.

General guidelines for access to ACTRIS data and services are available in the current [ACTRIS access and service policy](https://www.actris.eu/Portals/46/Documentation/ACTRIS%20PPP/Deliverables/Public/WP2_D2.6_M32.pdf?ver=2018-10-29-152442-467). Conditions of use should be indicated in section 3.4, and is covered by the attached licence, unless stated otherwise. 

Some data requires a username and password in order to gain access, e.g. the usage of aerosol profile data.**(If some data is kept closed, we must provide rationale for doing so)**
Apart from [Quiklooks (simple plots of data from the In Situ and CLU unit)](http://ebas-nrt-showcase.nilu.no/), Near-Real-Time (NRT) data is mostly access protected.
For all data that requires username and password, a Single-Sign-On service should be implemented, and used by all Data Centre units. 
In all cases where access is restricted, information on how to access the data should be available through the metadata.

If specific software tools are need to access the data, documentation about the software and how to access it should be included, preferably in the metadata. Furthermore, ACTRIS digital tools (software etc.) should be available through open access repositories like GitHub. A open source licence for software should be encouraged and applied when possible. The aformentioned guidelines are related to ACTRIS [level 2 data](#11-actris-data-set-descriptions-and-actris-data-levels). This is primarily intended as guidelines for software that is needed to access data that is available through the data center. Software related to ACTRIS level 0 and level 1 data is out of scope for this section. 

### 3.3. Interoperable: Making data interoperable [FAIR data]

Making data interoperable is the guiding principle of the ACTRIS DC. The ACTRIS DC handles a large variety of data and there is currently no common approach towards interoperability.

By some of the DC units the Thredds Data Server (TDS) is used for serving data as netCDF and through OPeNDAP (EBAS, Earlinet, others?). ACTRIS DC needs to specify what data standards the ACTRIS DC should choose, in order to facilitate interoperability. Still, work remains to see if a common solution could be agreed upon. The intricate nature of the data, might require the use of different solutions to suit the needs of each individual DC unit.

As mention in section 3.1 metadata standard and vocabularies commonly used in the atmospheric domain should be applied, unless the common solutions do not address the specific need for the DC unit.

Implementation of new standards for data and metadata used in the context of ACTRIS should be discussed by all the DC units. This is especially important for the ACCESS unit, coordinating the access to all of the ACTRIS data. Therefore the aim should be to harmonize data and metadata as much as possible, both in terms of technical aspects related to implementation, but also making it easier for the end user to make use of the data. 

Standard vocabulary might not always be used, but in all cases they should be mapped to standard vocabulary if existing by the DC ACCESS unit. 

As an overarching goal, ACTRIS DC will take part in discussions that takes place in forums/groups such as ENVRI FAIR across the different environmental domains and strive to use cross-environmental standards and solutions in order to allow for inter-disciplinary interoperability.

### 3.4. Reuseable: Increase data re-use [FAIR data]

The ACTRIS DC will facilitate data re-use by providing free and open access to ACTRIS data following the ACTRIS data and access policy and the open research data initiative of the European Commission. As a result, the ACTRIS DC will implement one or multiple licences for all ACTRIS level 2 data and NRT data that is available through the ACTRIS metadata catalog. Furthermore, the ACTRIS DC might also consider issuing a licence on the use of metadata, in order to ensure the visibility of ACTRIS when large amounts of metadata is harvested by third party application/services. ACTRIS aims to implement a license from the time ACTRIS becomes an ERIC (probably end of 2020 or early 2021). Until ACTRIS has decided upon and implemented one or more licenses, the current [ACTRIS data policy](http://actris.nilu.no/Content/Documents/DataPolicy.pdf) will apply.

Availability of data might vary between the different data center units. As an example, In situ data is typically submitted on an annual basis, and are therefore available the subsequent year, but this might vary for other data center units, there might be campaigns, or the delivery of NRT data that is available at a more frequent basis. ACTRIS legacy data should also be kept available for the users, but the data might follow a different data policy then the current ACTRIS data policy. If this is the case, this information should be available in the metadata.

**Consider adding a table giving an overview of when data is made available, level 2, NRT, campaign data and how this differs among the DC units**

Data quality assurance is provided by the data submitter and national facilities, the topical centers as well as by each individual data center unit. 

ACTRIS as an Research infrastructure is in its preparation phase, and is expected to be fully operational within 2025. The project will aim at providing open-access to data throughout the lifetime of the infrastructure.

## 4. Allocation of resources

**Cathrine takes the lead on this section. Draft should be more like an abstract of the cost book**

### Estimate the costs for making your data FAIR. Describe how you intend to cover these costs

  Question not answered.

### Clearly identify responsibilities for data management in your project

  Question not answered.

### Describe costs and potential value of long term preservation

  Question not answered.

## 5. Data security

### Address data recovery as well as secure storage and transfer of sensitive data 

  **Address data security related issues for each data centre unit.**

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

*More tables to be added regarding the workflow, currently this is an example draft*

![ACTRIS In situ data centre unit workflow diagram](https://folk.nilu.no/~richard/actris-ri-variables/ACTRIS_surface_insitu_workflow.jpg)

#### Workflow Tasks Responsibilities

<table style="height: 254px;" width="826"> <tbody> <tr> <th style="width: 206.25px;">&nbsp;</th> <th style="width: 206.25px;" colspan="3">&nbsp;Responsible for</th> </tr> <tr> <th style="width: 206.25px;">&nbsp;Workflow Task ID</th> <th style="width: 206.25px;">&nbsp;Specification</th> <th style="width: 206.25px;">&nbsp;Implementation</th> <th style="width: 206.25px;">&nbsp;Operation</th> </tr> <tr> <td style="width: 206.25px;">&nbsp;</td> <td style="width: 206.25px;">&nbsp;</td> <td style="width: 206.25px;">&nbsp;</td> <td style="width: 206.25px;">&nbsp;</td> </tr> <tr> <td style="width: 206.25px;">&nbsp;</td> <td style="width: 206.25px;">&nbsp;</td> <td style="width: 206.25px;">&nbsp;</td> <td style="width: 206.25px;">&nbsp;</td> </tr> </tbody> </table> 

#### Workflow Tasks Short Specification 

<table style="height: 254px; width: 826px;"> <tbody> <tr> <th style="width: 16.1667px;">&nbsp;Workflow Task ID</th> <th style="width: 395.833px;">&nbsp;Short Specification</th> </tr> <tr> <td style="width: 16.1667px;">&nbsp;</td> <td style="width: 395.833px;">&nbsp;</td> </tr> <tr> <td style="width: 16.1667px;">&nbsp;</td> <td style="width: 395.833px;">&nbsp;</td> </tr> </tbody> </table>

### Appendix 4: ACTRIS Aerosol remote sensing data centre unit (ARES) data life cycle and workflow diagram
**Will also link to seperate document describing the workflow in more detail.**
![ACTRIS Aerosol remote sensing data centre unit workflow diagram](https://raw.githubusercontent.com/actris/data-management-plan/master/DMP/img/ACTRIS_Aerosol_Remote_Sensing_workflow.jpg)

### Appendix 5: ACTRIS Cloud remote sensing data centre unit (CLU) data life cycle and workflow diagram
**Will also link to seperate document describing the workflow in more detail.**
![ACTRIS Cloud remote sensing data centre unit workflow diagram](https://raw.githubusercontent.com/actris/data-management-plan/master/DMP/img/ACTRIS_cloud_remote_Sensing_workflow.png)

### Appendix 6: ACTRIS trace gases remote sensing data centre unit (GRES) data life cycle and workflow diagram
![ACTRIS trace gases remote sensing data centre unit workflow diagram](https://raw.githubusercontent.com/actris/data-management-plan/master/DMP/img/workflow_gres.png)

### Appendix 7: ACTRIS Atmospheric simulation chamber data centre unit (ASC) data life cycle and workflow diagram
![ACTRIS Atmospheric simulation chamber data centre unit workflow diagram](https://raw.githubusercontent.com/actris/data-management-plan/master/DMP/img/atm_simulation_chamber_workflow.png)

### Appendix 8: Data lifecycle and workflow for ACCESS Data Centre Unit

