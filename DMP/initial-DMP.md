# ACTRIS Research Infrastructure initial outline of DMP

## 1. Introduction to ACTRIS and The ACTRIS Data Centre

The Research Infrastructure (RI) ACTRIS – Aerosols, Clouds, and Trace Gases is the pan-European RI that consolidates activities amongst European partners for observations of aerosols, clouds, and trace gases and for understanding of the related atmospheric processes, as well as to provide RI services to wide user groups. ACTRIS is a unique research infrastructure improving the quality of atmospheric observations, developing new methods and protocols, and harmonizing existing observations of the atmospheric variables listed in Appendix 1.

ACTRIS (Aerosols, Clouds, and Trace gases Research Infrastructure) was adopted to the ESFRI roadmap in 2016. During the ongoing preparation phase (2017-2019), ACTRIS shall achieve maturity at organizational, operational, and strategic levels. The preparation phase is supported by the European Commission (ACTRIS Preparatory Phase Project, PPP) and partner countries and organizations at the national level. The ACTRIS Central Facilities (CFs) host selection will be an essential outcome of ACTRIS PPP.
During the implementation phase (expected 2020-2024), the CFs are constructed and their services are tested. ACTRIS operations will start step-by-step by ramping up the service provision. After the necessary legal preparations, ACTRIS shall become a legal entity (ERIC, European Research Infrastructure Consortium) funded by the Member countries. The target is to launch ACTRIS ERIC in the beginning of 2021. It is foreseen that ACTRIS will be fully operational by 2025.

The overall goal of the ACTRIS Data Centre is to provide scientists and other user groups with free and open access to all ACTRIS infrastructure data, complemented with access to innovative and mature data
products, together with tools for quality assurance (QA), data analysis and research following the [FAIR principles](https://www.force11.org/group/fairgroup/fairprinciples).
The numerous measurement methodologies applied in ACTRIS result in a considerable diversity of the data collected. In accordance with these requirements, the ACTRIS Data Centre currently consists of five topical data repositories archiving the measurement data, which are all linked through the [ACTRIS data portal](http://actris.nilu.no/) to provide a single access point to all data and related information:

* [ACTRIS In situ data centre unit (In-Situ)](http://ebas.nilu.no/)
* [ACTRIS Aerosol remote sensing data centre unit (ARES)](http://access.earlinet.org/EARLINET/)
* [ACTRIS Cloud remote sensing data centre unit (CLU)](http://cloudnet.fmi.fi/)
* ACTRIS trace gases remote sensing data centre unit (GRES) 
* [ACTRIS Atmospheric simulation chamber data centre unit (ASC)](https://data.eurochamp.org/)

In addition, AERIS contributes with the production and provision of satellite data that complements the ACTRIS ground-based data: http://www.icare.univ-lille1.fr/catalogue.

![Architecture of the ACTRIS Data Centre](https://raw.githubusercontent.com/actris/data-management-plan/master/DMP/img/ACTRIS_data_centre_elements_phase2.jpg)
*Figure 1: Architecture of the ACTRIS Data Centre*

**Add figure from application**

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

## 2. Data summary for the different data centre units

### 2.1.Data summary of the ACTRIS In situ data centre unit (In-Situ)

#### The purpose of the data collection/generation

The purpose of the data collection and generation of data products is to provide open access to aerosol, cloud and trace gas in situ measurements of high quality, benefiting scientists and policy makers, as well as the private sector, educators and the general public. See the [Stakeholder Handbook](http://www.actris.eu/Portals/46/Documentation/ACTRIS%20PPP/Stakeholder%20Handbook/high_res_version.pdf?ver=2018-06-04-080105-217) for more information.

#### The relation to the objectives of the project

Data management of ACTRIS in situ data relates to the ability to predict the future behaviour of the atmosphere over all time scales. High quality observation data facilitates this and needs to be supported by:
  * Long-term archiving and preservation of ACTRIS level 1 to level 3 data and data products
  * Access to ACTRIS data, data products, and digital tools through a single point of entry, the ACTRIS data user interface
  * Documentation of data, data flow, citation service, and data attribution, including version control, data traceability, and interoperability,
  * Data curation and support for campaigns and dedicated research projects and initiatives, external or internal to ACTRIS.

#### The types and formats of data generated/collected
The ACTRIS In situ data centre unit is supported by the [EBAS database infrastructure](http://ebas.nilu.no/ResourcesATMOS/AboutEBAS.pdf). Data submitted to EBAS need to be formatted in the EBAS NASA-Ames format by the data provider, and there is exsisting instructions and template for each instrument/group of instruments. [The EBAS NASA-Ames format](https://projects.nilu.no//ccc/tfmm/kjeller_2016/EBAS_Data_Format_2016-10.pdf) is based on the ASCII text NASA-Ames 1001 format, but contains additional metadata specifications ensuring proper documentation from the [EBAS-Submit documentation](https://ebas-submit.nilu.no/) website as well as tools for [file-generation](http://dev-ebas-file-generation-tool.nilu.no/) (*beta*) and [file-submission](https://ebas-submit-tool.nilu.no/).

#### Re-use of existing data

The ACTRIS data user interface will include access to ACTRIS In situ legacy data resulting from ACTRIS pre-projects.

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
Detail on the data life cycle and workflow (workflow diagrams for data production) for In situ observations can be found in [*Appendix 3: ACTRIS in situ aerosol, cloud and trace gas data lifecycle and workflow (draft)*](https://github.com/actris/data-management-plan/blob/master/DMP/initial-DMP.md#appendix-3-actris-in-situ-aerosol-cloud-and-trace-gas-data-lifecycle-and-workflow-draft).

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
<table border="0" cellspacing="0"><colgroup width="731"></colgroup> <colgroup width="388"></colgroup> <colgroup width="177"></colgroup> <colgroup width="165"></colgroup> <colgroup width="141"></colgroup> <colgroup width="115"></colgroup> <colgroup width="199"></colgroup> <colgroup width="97"></colgroup> <colgroup width="144"></colgroup> <colgroup width="147"></colgroup> <colgroup width="209"></colgroup> <colgroup width="181"></colgroup> <colgroup width="172"></colgroup> <colgroup width="168"></colgroup> <colgroup width="188"></colgroup> <colgroup width="68"></colgroup> <colgroup span="4" width="67"></colgroup> <colgroup width="63"></colgroup> <colgroup width="67"></colgroup> <colgroup width="65"></colgroup> <colgroup span="2" width="67"></colgroup> <colgroup width="63"></colgroup> <colgroup span="2" width="59"></colgroup> <colgroup span="6" width="67"></colgroup> <colgroup span="2" width="60"></colgroup> <colgroup width="53"></colgroup> <colgroup width="68"></colgroup> <colgroup width="57"></colgroup> <colgroup span="2" width="63"></colgroup> <colgroup width="68"></colgroup> <colgroup span="2" width="63"></colgroup> <colgroup width="69"></colgroup> <colgroup width="63"></colgroup> <colgroup width="79"></colgroup> <colgroup width="63"></colgroup> <colgroup span="3" width="59"></colgroup> <colgroup width="53"></colgroup> <colgroup span="3" width="56"></colgroup> <colgroup width="57"></colgroup> <colgroup span="5" width="63"></colgroup> <colgroup width="88"></colgroup> <colgroup width="81"></colgroup>
<tbody>
<tr>
<td rowspan="4" align="left" valign="top" bgcolor="#006666" height="92"><strong><span style="color: #ffffff; font-size: x-large;">Annex I: Catalog with ACTRIS L1-L2 data from observational NF</span></strong></td>
<td colspan="4" align="left" valign="middle" bgcolor="#FFFFFF"><strong><span style="color: #000000; font-family: Cambria;">Colour codes for measurement techniques</span></strong></td>
<td align="left" valign="middle" bgcolor="#FFFFFF"><strong><span style="color: #000000; font-family: Cambria;">&nbsp;</span></strong></td>
<td align="left" valign="middle" bgcolor="#FFFFFF"><strong><span style="color: #000000; font-family: Cambria;">&nbsp;</span></strong></td>
<td align="left" valign="middle" bgcolor="#FFFFFF"><strong><span style="color: #000000; font-family: Cambria;">&nbsp;</span></strong></td>
<td align="left" valign="middle" bgcolor="#FFFFFF"><strong><span style="color: #000000; font-family: Cambria;">&nbsp;</span></strong></td>
<td align="center" valign="middle" bgcolor="#FFFFFF"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#FFFFFF"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td colspan="7" align="left" valign="middle" bgcolor="#FFFFFF"><span style="color: #000000;">Variable produced from a single measurement technique </span></td>
<td align="left" valign="middle" bgcolor="#FFFFFF"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="middle" bgcolor="#FFFFFF"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="middle" bgcolor="#FFFFFF"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#FFFFFF"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td colspan="9" align="left" valign="middle" bgcolor="#FFFFFF"><span style="color: #000000;">Variable produced from synergy of measurement techniques </span></td>
<td align="left" valign="middle" bgcolor="#FFFFFF"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="middle" bgcolor="#FFFFFF"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom">&nbsp;</td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td colspan="9" align="left" valign="middle" bgcolor="#FFFFFF"><span style="color: #000000;">Variable produced from synergy of measurement techniques where combinations are possible</span></td>
<td align="left" valign="middle" bgcolor="#FFFFFF"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="middle" bgcolor="#FFFFFF"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom">&nbsp;</td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="21"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="center" valign="middle" bgcolor="#D9D9D9" height="21"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#D9D9D9"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#D9D9D9"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#D9D9D9"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#D9D9D9"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#D9D9D9"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#D9D9D9">&nbsp;</td>
<td align="center" valign="bottom" bgcolor="#D9D9D9"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#D9D9D9"><span style="color: #000000;">&nbsp;</span></td>
<td colspan="16" align="center" valign="middle" bgcolor="#D9D9D9"><strong>Measurement techniques<br />(should be consistent with the NF concept and TC concepts)</strong></td>
<td colspan="16" align="center" valign="middle" bgcolor="#D9D9D9"><strong>Measurement techniques<br />(should be consistent with the NF concept and TC concepts)</strong></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">&nbsp;</span></td>
<td colspan="8" align="center" valign="middle" bgcolor="#D9D9D9"><strong>Measurement techniques<br />(should be consistent with the NF concept and TC concepts)</strong></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><strong>&nbsp;</strong></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><strong>&nbsp;</strong></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><strong>&nbsp;</strong></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><strong>&nbsp;</strong></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><strong>&nbsp;</strong></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><strong>Model </strong></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="center" valign="middle" bgcolor="#D9D9D9" height="221"><strong><span style="color: #000000;">ACTRIS variable</span></strong></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><strong><span style="color: #000000;">Comment</span></strong></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><strong><span style="color: #000000;">NF requirements Mandatory - M<br /> Specializing - S<br />Optimum - O <br /> </span></strong></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><strong><span style="color: #000000;">wave 1/wave 2</span></strong></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><strong><span style="color: #000000;">Data level (L0, L1, L2)</span></strong></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><strong>Remote/in situ</strong></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><strong>Matrix: Aerosol/<br />Cloud/<br />trace gas</strong></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><strong>Associated Topical Centre </strong></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><strong><span style="color: #000000;">Data producer <br />L1, L2 </span></strong></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><strong><span style="color: #000000;">RRT-O= operational in RRT now<br /> RRT-S = scheduled from 2020</span></strong></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><strong><span style="color: #000000;"><br />Ambition to lead the ACTRIS data curation service</span></strong></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><strong><span style="color: #000000;">Access to L1, L2 (open, password, on request, restricted)<br /></span></strong></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><strong>Recommended time resolution</strong></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><strong>Higher timeres. available</strong></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><strong>Approx. height resolution for remote sensing data</strong></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">High-power aerosol lidar</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">Automatic sun/sky/lunar photometer</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">Automatic low-power aerosol lidar</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9">Integrating Nephelometer</td>
<td align="center" valign="middle" bgcolor="#D9D9D9">Mobility Particle <br />Size Spectrometer</td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">Aerodynamic &amp; Optical Particle Size Spectrometer</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">Absorption Photometer</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">Condensation Particle <br />Counter</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">Scanning PSM, (N)AIS, N-MPSS</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">Particle Size Magnifier (PSM)</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">Cloud Condensation Nuclei Counter</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">Filter sampling</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">Thermal-optical analyser</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">Offline filter-based<br />IC, GC-MS, HPLC-MS, LC/MS</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">Aerosol Mass Spectrometer</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">X-Ray Fluorescence, Particle Induced X-ray Emission </span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">FTIR </span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">UVVIS - ZS</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">UVVIS- MAXDOAS</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">On-line GC-FID</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">On-line GC-MS</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">On-line GC-FID/MS</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">On-line GC-Medusa</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">On-line PTR-MS</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9">On-line Hantzsch</td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">Off-line traps: ads-tubes</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">Off-line traps: DNPH-cartridge-HPLC</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">Off-line steel canister</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">Off-line glass flask</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9">NO-O3 chemiluminescence</td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">Potentially other measurement technique supported by the TC</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">Cavity Attenuated Phase Shift Spectroscopy (CAPS)</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">CI-APi-TOF </span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">Cloud radar</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">Doppler cloud radar</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;"> Lidar/ceilometer</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">Radiosonde</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">Microwave radiometer</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">Drop-counting raingauge</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">Disdrometer</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">Integrating Cloud Probe</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">Cloud Droplet Probe </span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">Cloud Ice Probe</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">Aerosol Particle Sampler</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">Bulk collectors</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">INP instrument</span></td>
<td align="center" valign="middle" bgcolor="#D9D9D9"><span style="color: #000000;">NWP model input required</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="center" valign="middle" bgcolor="#F2F2F2" height="23"><strong><span style="color: #000000;">Aerosol remote sensing </span></strong></td>
<td align="left" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><strong>&nbsp;</strong></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><strong>&nbsp;</strong></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><strong>&nbsp;</strong></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #006100;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #006100;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2">&nbsp;</td>
<td align="center" valign="bottom" bgcolor="#F2F2F2">&nbsp;</td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #9c6500;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #9c6500;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="23">Attenuated backscatter profile</td>
<td align="left" valign="top"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle">M</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">L1, L2</td>
<td align="center" valign="bottom">remote</td>
<td align="center" valign="bottom">aerosol</td>
<td align="center" valign="bottom">CARS</td>
<td align="center" valign="middle">DC</td>
<td align="center" valign="bottom">NRT-S</td>
<td align="center" valign="bottom">IMAA/CNR</td>
<td align="center" valign="middle">open</td>
<td align="center" valign="bottom">1h, 5/week</td>
<td align="center" valign="bottom">around 1h, but also at native raw resolutino (typ 1 m)</td>
<td align="center" valign="middle">60 m</td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
</tr>
<tr>
<td align="left" valign="bottom" height="23">Volume depolarization profile</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">M</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">L1, L2</td>
<td align="center" valign="bottom">remote</td>
<td align="center" valign="bottom">aerosol</td>
<td align="center" valign="bottom">CARS</td>
<td align="center" valign="middle">DC</td>
<td align="center" valign="bottom">NRT-S</td>
<td align="center" valign="bottom">IMAA/CNR</td>
<td align="center" valign="middle">open</td>
<td align="center" valign="bottom">1h, 5/week</td>
<td align="center" valign="bottom">around 1h, but also at native raw resolutino (typ 1 m)</td>
<td align="center" valign="middle">60 m</td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="23">Particle backscatter coefficient profile</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">M</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">L1, L2</td>
<td align="center" valign="bottom">remote</td>
<td align="center" valign="bottom">aerosol</td>
<td align="center" valign="bottom">CARS</td>
<td align="center" valign="middle">DC</td>
<td align="center" valign="bottom">NRT-S</td>
<td align="center" valign="bottom">IMAA/CNR</td>
<td align="center" valign="middle">open</td>
<td align="center" valign="bottom">1h, 5/week</td>
<td align="center" valign="bottom">&nbsp;</td>
<td align="center" valign="middle">60 m</td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="23">Particle extinction coefficient profile</td>
<td align="left" valign="middle">&nbsp;</td>
<td align="center" valign="middle">M</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">L1, L2</td>
<td align="center" valign="bottom">remote</td>
<td align="center" valign="bottom">aerosol</td>
<td align="center" valign="bottom">CARS</td>
<td align="center" valign="middle">DC</td>
<td align="center" valign="bottom">NRT-S</td>
<td align="center" valign="bottom">IMAA/CNR</td>
<td align="center" valign="middle">open</td>
<td align="center" valign="bottom">1h, 5/week</td>
<td align="center" valign="bottom">&nbsp;</td>
<td align="center" valign="middle">60 m</td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="23">Lidar ratio profile</td>
<td align="left" valign="middle">&nbsp;</td>
<td align="center" valign="middle">M</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">L1, L2</td>
<td align="center" valign="bottom">remote</td>
<td align="center" valign="bottom">aerosol</td>
<td align="center" valign="bottom">CARS</td>
<td align="center" valign="middle">DC</td>
<td align="center" valign="bottom">NRT-S</td>
<td align="center" valign="bottom">IMAA/CNR</td>
<td align="center" valign="middle">open</td>
<td align="center" valign="bottom">1h, 5/week</td>
<td align="center" valign="bottom">&nbsp;</td>
<td align="center" valign="middle">60 m</td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="23">&Aring;ngstr&ouml;m exponent profile</td>
<td align="left" valign="middle">&nbsp;</td>
<td align="center" valign="middle">O</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">L1, L2</td>
<td align="center" valign="bottom">remote</td>
<td align="center" valign="bottom">aerosol</td>
<td align="center" valign="bottom">CARS</td>
<td align="center" valign="middle">DC</td>
<td align="center" valign="bottom">NRT-S</td>
<td align="center" valign="bottom">IMAA/CNR</td>
<td align="center" valign="middle">open</td>
<td align="center" valign="bottom">1h, 5/week</td>
<td align="center" valign="bottom">&nbsp;</td>
<td align="center" valign="middle">60 m</td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="23">Backscatter-related &Aring;ngstr&ouml;m exponent profile</td>
<td align="left" valign="middle">&nbsp;</td>
<td align="center" valign="middle">O</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">L1, L2</td>
<td align="center" valign="bottom">remote</td>
<td align="center" valign="bottom">aerosol</td>
<td align="center" valign="bottom">CARS</td>
<td align="center" valign="middle">DC</td>
<td align="center" valign="bottom">NRT-S</td>
<td align="center" valign="bottom">IMAA/CNR</td>
<td align="center" valign="middle">open</td>
<td align="center" valign="bottom">1h, 5/week</td>
<td align="center" valign="bottom">&nbsp;</td>
<td align="center" valign="middle">60 m</td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="23">Particle depolarization ratio profile</td>
<td align="left" valign="middle">&nbsp;</td>
<td align="center" valign="middle">M</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">L1, L2</td>
<td align="center" valign="bottom">remote</td>
<td align="center" valign="bottom">aerosol</td>
<td align="center" valign="bottom">CARS</td>
<td align="center" valign="middle">DC</td>
<td align="center" valign="bottom">NRT-S</td>
<td align="center" valign="bottom">IMAA/CNR</td>
<td align="center" valign="middle">open</td>
<td align="center" valign="bottom">1h, 5/week</td>
<td align="center" valign="bottom">&nbsp;</td>
<td align="center" valign="middle">60 m</td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="23">Particle layer geometrical properties (height and thickness)</td>
<td align="left" valign="middle">&nbsp;</td>
<td align="center" valign="middle">M</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">L1, L2</td>
<td align="center" valign="bottom">remote</td>
<td align="center" valign="bottom">aerosol</td>
<td align="center" valign="bottom">CARS</td>
<td align="center" valign="middle">DC</td>
<td align="center" valign="bottom">NRT-S</td>
<td align="center" valign="bottom">IMAA/CNR</td>
<td align="center" valign="middle">open</td>
<td align="center" valign="bottom">1h, 5/week</td>
<td align="center" valign="bottom">around 1h, but also at native raw resolutino (typ 1 m)</td>
<td align="center" valign="middle">60 m</td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="23">Particle layer optical properties (extinction, backscatter, lidar ratio, &Aring;ngstr&ouml;m exponent, depolarization ratio, optical depth)</td>
<td align="left" valign="middle">&nbsp;</td>
<td align="center" valign="middle">M</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">L1, L2</td>
<td align="center" valign="bottom">remote</td>
<td align="center" valign="bottom">aerosol</td>
<td align="center" valign="bottom">CARS</td>
<td align="center" valign="middle">DC</td>
<td align="center" valign="bottom">NRT-S</td>
<td align="center" valign="bottom">IMAA/CNR</td>
<td align="center" valign="middle">open</td>
<td align="center" valign="bottom">1h, 5/week</td>
<td align="center" valign="bottom">&nbsp;</td>
<td align="center" valign="middle">60 m</td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="middle" height="23"><span style="color: #000000;">Column integrated exctinction</span></td>
<td align="left" valign="middle">Comparable to aerosol optical depth</td>
<td align="center" valign="middle">M</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">L1, L2</td>
<td align="center" valign="bottom">remote</td>
<td align="center" valign="bottom">aerosol</td>
<td align="center" valign="bottom">CARS</td>
<td align="center" valign="middle">DC</td>
<td align="center" valign="bottom">NRT-S</td>
<td align="center" valign="bottom">IMAA/CNR</td>
<td align="center" valign="middle">open</td>
<td align="center" valign="bottom">1h, 5/week</td>
<td align="center" valign="bottom">&nbsp;</td>
<td align="center" valign="middle">60 m</td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="23"><span style="color: #000000;">Planetary boundary layer height</span></td>
<td align="left" valign="middle">&nbsp;</td>
<td align="center" valign="middle">O</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">L1, L2</td>
<td align="center" valign="bottom">remote</td>
<td align="center" valign="bottom">aerosol</td>
<td align="center" valign="bottom">CARS</td>
<td align="center" valign="middle">DC</td>
<td align="center" valign="bottom">NRT-S</td>
<td align="center" valign="bottom">IMAA/CNR</td>
<td align="center" valign="middle">open</td>
<td align="center" valign="bottom">1h, 5/week</td>
<td align="center" valign="bottom">around 1h, but also at native raw resolutino (typ 1 m)</td>
<td align="center" valign="middle">60 m</td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="top" height="23"><span style="color: #000000;">Spectral Downward Sky Radiances </span></td>
<td align="left" valign="top"><span style="color: #000000;">Almucantar, Principal Planes, Hybrid, Polarization Principal Planes: AERONET-ACTRIS algorithm - AERONET-EUROPE and associated sites only</span></td>
<td align="center" valign="middle">M</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">L1</td>
<td align="center" valign="bottom">remote</td>
<td align="center" valign="bottom">aerosol</td>
<td align="center" valign="bottom">CARS</td>
<td align="center" valign="middle">TC</td>
<td align="center" valign="middle">NRT-O</td>
<td align="center" valign="bottom">CNRS</td>
<td align="center" valign="middle">open</td>
<td align="center" valign="bottom">1h</td>
<td align="center" valign="bottom">1h</td>
<td align="center" valign="middle">NA</td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #0000ff;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="top" height="23"><span style="color: #000000;">Direct Sun/Moon Extinction Aerosol Optical Depth (column)</span></td>
<td align="left" valign="top"><span style="color: #000000;">AERONET-ACTRIS algorithm - AERONET-EUROPE and associated sites only - Daytime + Nightime when available</span></td>
<td align="center" valign="middle">M</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">L1</td>
<td align="center" valign="bottom">remote</td>
<td align="center" valign="bottom">aerosol</td>
<td align="center" valign="bottom">CARS</td>
<td align="center" valign="middle">TC</td>
<td align="center" valign="middle">NRT-O</td>
<td align="center" valign="bottom">CNRS</td>
<td align="center" valign="middle">open</td>
<td align="center" valign="bottom">15min</td>
<td align="center" valign="bottom">15min</td>
<td align="center" valign="middle">NA</td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="top" height="23"><span style="color: #000000;">Aerosol columnar properties </span></td>
<td align="left" valign="top"><span style="color: #000000;">Spectral refractive indexes, spectral extinction/absorption AOD, single scattering albedo, spectral lidar ratio, Angstr&ouml;m exponent, volume size distribution, spherical fraction: Synergy &amp; single - GARRLiC / GRASP-AOD Algorithm &ndash; Daytime + Nightime when available</span></td>
<td align="center" valign="middle">M</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">L2</td>
<td align="center" valign="bottom">remote</td>
<td align="center" valign="bottom">aerosol</td>
<td align="center" valign="bottom">CARS</td>
<td align="center" valign="middle">DC</td>
<td align="center" valign="bottom">NRT-S</td>
<td align="center" valign="bottom">AERIS</td>
<td align="center" valign="middle">open</td>
<td align="center" valign="middle">1h</td>
<td align="center" valign="middle">1h</td>
<td align="center" valign="middle">NA</td>
<td align="center" valign="middle" bgcolor="#31869B"><span style="color: #31869b;">2</span></td>
<td align="center" valign="middle" bgcolor="#31869B"><span style="color: #31869b;">2</span></td>
<td align="center" valign="middle" bgcolor="#31869B"><span style="color: #31869b;">2</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="left" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="top" height="23"><span style="color: #000000;">Aerosol profile microphysical and optical properties </span></td>
<td align="left" valign="top"><span style="color: #000000;">Aerosol Volume Centration, Spectral Extinction AOD, Spectral Absorption AOD, Spectral Extinction coefficient, Spectral backscatter coefficient , Spectral Single Scattering Albedo, Spectral LiDAR ratio, Spectral Aerosol linear depolarization ratio, Extinction Ansgtr&ouml;m Exponent , Backscatter Ansgtr&ouml;m Exponent, Aerosol Phase Matrix: Synergy products -GARRLiC Algorithm &ndash; Daytime</span></td>
<td align="center" valign="middle">M</td>
<td align="center" valign="middle">&nbsp;</td>
<td align="center" valign="middle">L2</td>
<td align="center" valign="bottom">remote</td>
<td align="center" valign="bottom">aerosol</td>
<td align="center" valign="bottom">CARS</td>
<td align="center" valign="middle">DC</td>
<td align="center" valign="bottom">NRT-S</td>
<td align="center" valign="bottom">AERIS</td>
<td align="center" valign="middle">open</td>
<td align="center" valign="middle">1h, 5/week</td>
<td align="center" valign="middle">input Lidar resolution</td>
<td align="center" valign="middle">GARRLIC Resolution</td>
<td align="center" valign="middle" bgcolor="#31869B"><span style="color: #31869b;">2</span></td>
<td align="center" valign="middle" bgcolor="#31869B"><span style="color: #31869b;">2</span></td>
<td align="center" valign="middle" bgcolor="#31869B"><span style="color: #31869b;">2</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #0000ff;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="center" valign="middle" bgcolor="#F2F2F2" height="23"><strong><span style="color: #000000;">Aerosol in situ </span></strong></td>
<td align="left" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="23"><span style="color: #000000;">Particle light scattering and backscattering coefficients </span></td>
<td align="left" valign="bottom"><span style="color: #000000;">multi-wavelength</span></td>
<td align="center" valign="middle"><span style="color: #000000;">M</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L0, L1, L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">in situ</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">aerosol</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CAIS</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NF</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NRT-O</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NILU</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">1h</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="23"><span style="color: #000000;">Particle number size distribution - mobility diameter</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">0.01 - 0.8 &micro;m</span></td>
<td align="center" valign="middle"><span style="color: #000000;">M</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L0, L1, L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">in situ</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">aerosol</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CAIS</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NF</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NRT-O</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NILU</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">1h</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="23"><span style="color: #000000;">Particle number size distribution - optical and aerodynamic diameter</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">0.7 - 10 &micro;m</span></td>
<td align="center" valign="middle"><span style="color: #000000;">S</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L0, L1, L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">in situ</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">aerosol</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CAIS</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NF</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NRT-S</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NILU</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">1h</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="23"><span style="color: #000000;">Particle light absorption coefficient and equivalent black carbon concentration</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">M</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L0, L1, L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">in situ</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">aerosol</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CAIS</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NF</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NRT-O</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NILU</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">1h</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="23"><span style="color: #000000;">Particle number concentration</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&gt; 0.01 &micro;m</span></td>
<td align="center" valign="middle"><span style="color: #000000;">S</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L0, L1, L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">in situ</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">aerosol</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CAIS</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NF</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NRT-S</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NILU</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">1h</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="23"><span style="color: #000000;">Nanoparticle number size distribution</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">0.001 - 0.02 &micro;m</span></td>
<td align="center" valign="middle"><span style="color: #000000;">S</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L0, L1, L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">in situ</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">aerosol</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CAIS</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NF</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NRT-S</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NILU</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">1h</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="23"><span style="color: #000000;">Nanoparticle number concentration</span></td>
<td align="left" valign="bottom"><span style="color: #000000;"> &gt; 0.001 &micro;m</span></td>
<td align="center" valign="middle"><span style="color: #000000;">S</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L0 ,L1, L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">in situ</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">aerosol</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CAIS</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NF</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NRT-S</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NILU</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">1h</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="middle" height="23"><span style="color: #000000;">Cloud condensation nuclei number concentration</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">at various supersaturations</span></td>
<td align="center" valign="middle"><span style="color: #000000;">S</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L0, L1, L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">in situ</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">aerosol</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CAIS</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NF</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NRT-S</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NILU</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">1h</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="23"><span style="color: #000000;">Mass concentration of particulate organic and elemental carbon</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">S</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">in situ</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">aerosol</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CAIS</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NF</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NILU</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">&lt;48h - 2/week</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="23"><span style="color: #000000;">Mass concentration of particulate organic tracers</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">S</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">in situ</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">aerosol</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CAIS</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NF</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NILU</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">&lt;48h - 2/week</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="23"><span style="color: #000000;">Mass concentration of non-refractory particulate organics and inorganics</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">S</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">in situ</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">aerosol</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CAIS</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NF/TC</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-S</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NILU</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">1h</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="23"><span style="color: #000000;">Mass concentration of particulate elements</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">S</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L1, L2</span></td>
<td align="center" valign="bottom">in situ</td>
<td align="center" valign="bottom">aerosol</td>
<td align="center" valign="bottom"><span style="color: #000000;">CAIS</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NF</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NILU</span></td>
<td align="center" valign="middle">open</td>
<td align="center" valign="bottom">&lt;48h - 2/week</td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #ff0000;">&nbsp;</span></td>
</tr>
<tr>
<td align="center" valign="middle" bgcolor="#F2F2F2" height="23"><strong><span style="color: #000000;">Trace gases remote sensing </span></strong></td>
<td align="left" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">-</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="middle" height="23"><span style="color: #000000;">Ozone partial columns</span></td>
<td align="left" valign="top"><span style="color: #000000;">Almost continuous during day-time, weather permitting</span></td>
<td rowspan="10" align="center" valign="middle"><span style="color: #000000;">To be decided later</span></td>
<td align="center" valign="middle"><span style="color: #000000;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">remote</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">trace gas</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">RTGRSC</span></td>
<td rowspan="10" align="center" valign="middle"><span style="color: #000000;">To be decided later</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-O</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">AERIS</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">1h</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">5 to 8 km</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="middle" height="23"><span style="color: #000000;">Ozone column</span></td>
<td align="left" valign="top"><span style="color: #000000;">UVVIS -ZS measures at sunrise and sunset?</span></td>
<td align="center" valign="middle"><span style="color: #000000;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">remote</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">trace gas</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">RTGRSC</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-O</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">AERIS</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">1h - 2/day</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="middle" height="23"><span style="color: #000000;">Formaldehyde column</span></td>
<td align="left" valign="top"><span style="color: #000000;">NF data produser FTIR; TC data producer UVVIS-MAXDOAS</span></td>
<td align="center" valign="middle"><span style="color: #000000;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">remote</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">trace gas</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">RTGRSC</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-O</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">AERIS</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">1h</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="middle" height="23"><span style="color: #000000;">Formaldehyde lower tropospheric profile</span></td>
<td align="left" valign="top"><span style="color: #000000;">Almost continuous during day-time</span></td>
<td align="center" valign="middle"><span style="color: #000000;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">remote</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">trace gas</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">RTGRSC</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-O</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">AERIS</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">1h</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NA</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="middle" height="23"><span style="color: #000000;">NO2 column </span></td>
<td align="left" valign="top"><span style="color: #000000;">NF data produser for FTIR. UVVIS - ZS measures at sunrise and sunset?</span></td>
<td align="center" valign="middle"><span style="color: #000000;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">remote</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">trace gas</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">RTGRSC</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-O</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">AERIS</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">1h - 2/day</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="middle" height="23"><span style="color: #000000;">NO2 lower tropospheric profile</span></td>
<td align="left" valign="top"><span style="color: #000000;">Almost continuous during day-time</span></td>
<td align="center" valign="middle"><span style="color: #000000;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">remote</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">trace gas</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">RTGRSC</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-O</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">AERIS</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">1h</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NA</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="middle" height="23"><span style="color: #000000;">NH3 column</span></td>
<td align="left" valign="top"><span style="color: #000000;">Almost continuous during day-time, weather permitting</span></td>
<td align="center" valign="middle"><span style="color: #000000;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">remote</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">trace gas</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">RTGRSC</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-O</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">AERIS</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">1h</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="middle" height="23"><span style="color: #000000;">C2H6 column </span></td>
<td align="left" valign="top"><span style="color: #000000;">Almost continuous during day-time, weather permitting</span></td>
<td align="center" valign="middle"><span style="color: #000000;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">remote</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">trace gas</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">RTGRSC</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-O</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">AERIS</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">1h</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="middle" height="23"><span style="color: #000000;">SO2 lower tropospheric profile</span></td>
<td align="left" valign="top"><span style="color: #000000;">Almost continuous during day-time</span></td>
<td align="center" valign="middle"><span style="color: #000000;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">remote</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">trace gas</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">RTGRSC</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-O</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">AERIS</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">1h</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NA</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="middle" height="23"><span style="color: #000000;">SO2 column</span></td>
<td align="left" valign="top"><span style="color: #000000;">Almost continuous during day-time</span></td>
<td align="center" valign="middle"><span style="color: #000000;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">remote</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">trace gas</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">RTGRSC</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-O</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">AERIS</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">1h</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="center" valign="middle" bgcolor="#F2F2F2" height="23"><strong><span style="color: #000000;">Trace gases in situ</span></strong></td>
<td align="left" valign="top" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="23"><span style="color: #000000;">NMHCs</span></td>
<td align="left" valign="top"><span style="color: #000000;">NMHCs (C2-C9, detailed list available). Time resolution depends on sampling frequency, typical maximum 1/hour. M*: At least 6 different VOCs (NMHCs, OVOCs, terpenes) have to be measured at an NF, can be partly NMHCs.</span></td>
<td align="center" valign="middle"><span style="color: #000000;">M*, O</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L0, L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">in situ</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">trace gas</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CGas-SiM</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NF</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-S</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NILU</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">1 h-2/week</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="23"><span style="color: #000000;">OVOCs</span></td>
<td align="left" valign="top"><span style="color: #000000;">Oxidised volatile organic compounds (detailed list available). Time resolution depends on sampling frequency, typical maximum 1/hour, less for PTR-MS. M*: At least 6 different VOCs (NMHCs, OVOCs, terpenes) have to be measured at an NF, can be partly OVOCs.</span></td>
<td align="center" valign="middle"><span style="color: #000000;">M*, O</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L0, L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">in situ</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">trace gas</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CGas-SiM</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NF</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-S</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NILU</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">4 h-2/week</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="23"><span style="color: #000000;">Terpenes</span></td>
<td align="left" valign="top"><span style="color: #000000;">Monoterpenes (detailed list available), Time resolution depends on sampling frequency, typical maximum 1/hour, M*: At least 6 different VOCs (NMHCs, OVOCs, terpenes) have to be measured at an NF, can be partly terpenes.</span></td>
<td align="center" valign="middle"><span style="color: #000000;">M*, O</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L0, L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">in situ</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">trace gas</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CGas-SiM</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NF</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NILU</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">1 h-2/week</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="23"><span style="color: #000000;">NO</span></td>
<td align="left" valign="top"><span style="color: #000000;">Needs to be accomplished by water vapour and ozone measurements, ideally also global radiation or J(NO2)</span></td>
<td align="center" valign="middle"><span style="color: #000000;">M</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L0, L1, L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">in situ</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">trace gas</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CGas-SiM</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NF/TC</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-S</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NILU</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">1h</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #e46c0a;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="23"><span style="color: #000000;">NO2</span></td>
<td align="left" valign="top"><span style="color: #000000;">Needs to be accomplished by water vapour and ozone measurements, ideally also global radiation or J(NO2)</span></td>
<td align="center" valign="middle"><span style="color: #000000;">M</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L0, L1, L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">in situ</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">trace gas</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CGas-SiM</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NF/TC</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-S</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NILU</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">1h</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="23"><span style="color: #000000;">Condensable vapors </span></td>
<td align="left" valign="top"><span style="color: #000000;">Sulfuric acid, highly oxygenated molecules (HOM)</span></td>
<td align="center" valign="middle"><span style="color: #000000;">O*, S</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">in situ</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">trace gas</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CGas-SiM</span></td>
<td align="center" valign="middle"><span style="color: #000000;">NF/TC</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-S</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NILU</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">10 min</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="center" valign="middle" bgcolor="#F2F2F2" height="23"><strong><span style="color: #000000;">Cloud profile variables</span></strong></td>
<td align="left" valign="top" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="23"><span style="color: #000000;">Cloud/aerosol target classification</span></td>
<td align="left" valign="top"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">M</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">remote</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">cloud</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CCRES</span></td>
<td align="center" valign="middle"><span style="color: #000000;">DC</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-O</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">FMI</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">30s</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">N</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">60m</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="23"><span style="color: #000000;">Drizzle drop size distribution</span></td>
<td align="left" valign="top"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">M</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">remote</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">cloud</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CCRES</span></td>
<td align="center" valign="middle"><span style="color: #000000;">DC</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-O</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">FMI</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">30s</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">N</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">60m</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="23"><span style="color: #000000;">Drizzle water content</span></td>
<td align="left" valign="top"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">M</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">remote</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">cloud</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CCRES</span></td>
<td align="center" valign="middle"><span style="color: #000000;">DC</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-O</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">FMI</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">30s</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">N</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">60m</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="23"><span style="color: #000000;">Drizzle water flux</span></td>
<td align="left" valign="top"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">M</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">remote</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">cloud</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CCRES</span></td>
<td align="center" valign="middle"><span style="color: #000000;">DC</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-O</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">FMI</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">30s</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">N</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">60m</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="23"><span style="color: #000000;">Ice water content</span></td>
<td align="left" valign="top"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">M</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">remote</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">cloud</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CCRES</span></td>
<td align="center" valign="middle"><span style="color: #000000;">DC</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-O</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">FMI</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">30s</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">N</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">60m</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="23"><span style="color: #000000;">Liquid water content</span></td>
<td align="left" valign="top"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">M</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">remote</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">cloud</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CCRES</span></td>
<td align="center" valign="middle"><span style="color: #000000;">DC</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-O</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">FMI</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">30s</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">N</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">60m</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#31859C"><span style="color: #31859c;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="bottom" height="23"><span style="color: #000000;">Liquid water path</span></td>
<td align="left" valign="top"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">M</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L1,L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">remote</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">cloud</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CCRES</span></td>
<td align="center" valign="middle"><span style="color: #000000;">DC</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-O</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">FMI</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">30s</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="middle" height="23"><span style="color: #000000;">Temperature profile</span></td>
<td align="left" valign="top"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">O</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L1,L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">remote</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">cloud</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CCRES</span></td>
<td align="center" valign="middle"><span style="color: #000000;">DC</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-O</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">FMI</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">30s</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">N</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">variable</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="middle" height="23"><span style="color: #000000;">Relative humidity profile</span></td>
<td align="left" valign="top"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">O</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L1,L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">remote</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">cloud</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CCRES</span></td>
<td align="center" valign="middle"><span style="color: #000000;">DC</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-O</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">FMI</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">30s</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">N</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">variable</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="middle" height="23"><span style="color: #000000;">Integrated water vapor path</span></td>
<td align="left" valign="top"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">O</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L1,L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">remote</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">cloud</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CCRES</span></td>
<td align="center" valign="middle"><span style="color: #000000;">DC</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-O</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">FMI</span></td>
<td align="center" valign="middle"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">30s</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom">-</td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="center" valign="bottom" bgcolor="#93CDDD"><span style="color: #93cddd;">1.5</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="center" valign="bottom" bgcolor="#F2F2F2" height="24"><strong><span style="color: #000000;">Cloud in situ variables </span></strong></td>
<td align="left" valign="top" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="bottom" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle" bgcolor="#F2F2F2"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#F2F2F2"><strong><span style="color: #000000;">&nbsp;</span></strong></td>
</tr>
<tr>
<td align="left" valign="middle" height="20"><span style="color: #000000;">Liquid Water Content</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">only during cloud periods</span></td>
<td align="center" valign="middle"><span style="color: #000000;">M</span></td>
<td align="center" valign="middle"><span style="color: #000000;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L0, L1, L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">in situ</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">cloud</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CIS</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NF</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-S</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NILU?</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">1 min</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="middle" height="20"><span style="color: #000000;">Droplet effective diameter</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">only during cloud periods</span></td>
<td align="center" valign="middle"><span style="color: #000000;">M</span></td>
<td align="center" valign="middle"><span style="color: #000000;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L0, L1, L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">in situ</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">cloud</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CIS</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NF</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-S</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NILU?</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">1 min</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="middle" height="20"><span style="color: #000000;">Droplet number concentration</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">only during cloud periods</span></td>
<td align="center" valign="middle"><span style="color: #000000;">S</span></td>
<td align="center" valign="middle"><span style="color: #000000;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L0, L1, L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">in situ</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">cloud</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CIS</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NF</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-S</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NILU?</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">1 min</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="middle" height="20"><span style="color: #000000;">Droplet size distribution</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">only during cloud periods</span></td>
<td align="center" valign="middle"><span style="color: #000000;">S</span></td>
<td align="center" valign="middle"><span style="color: #000000;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L0, L1, L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">in situ</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">cloud</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CIS</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NF</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-S</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NILU?</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">1 min</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="middle" height="20"><span style="color: #000000;">Interstitial aerosol number concentration</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">only during cloud periods</span></td>
<td align="center" valign="middle"><span style="color: #000000;">S</span></td>
<td align="center" valign="middle"><span style="color: #000000;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L0, L1, L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">in situ</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">cloud</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CIS</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NF</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-S</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NILU?</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">1 Min</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="middle" height="20"><span style="color: #000000;">Interstitial aerosol size distribution</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">only during cloud periods</span></td>
<td align="center" valign="middle"><span style="color: #000000;">S</span></td>
<td align="center" valign="middle"><span style="color: #000000;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L0, L1, L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">in situ</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">cloud</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CIS</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NF</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-S</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NILU?</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">20 min</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">N</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="middle" height="20"><span style="color: #000000;">Total aerosol number concentration</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">both within and outside clouds</span></td>
<td align="center" valign="middle"><span style="color: #000000;">S</span></td>
<td align="center" valign="middle"><span style="color: #000000;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L0, L1, L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">in situ</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">cloud</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CIS</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NF</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-S</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NILU?</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">1 Min</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="middle" height="20"><span style="color: #000000;">Total aerosol size distribution</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">both within and outside clouds</span></td>
<td align="center" valign="middle"><span style="color: #000000;">S</span></td>
<td align="center" valign="middle"><span style="color: #000000;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L0, L1, L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">in situ</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">cloud</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CIS</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NF</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-S</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NILU?</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">20 min</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">N</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="middle" height="20"><span style="color: #000000;">Cloud residuals number concentration</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">optional during cloud periods</span></td>
<td align="center" valign="middle"><span style="color: #000000;">O</span></td>
<td align="center" valign="middle"><span style="color: #000000;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L0, L1, L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">in situ</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">cloud</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CIS</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NF</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-S</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NILU?</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">10 min</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="middle" height="20"><span style="color: #000000;">Cloud residuals composition</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">optional during cloud periods</span></td>
<td align="center" valign="middle"><span style="color: #000000;">O</span></td>
<td align="center" valign="middle"><span style="color: #000000;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L1, L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">in situ</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">cloud</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CIS</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NF</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-S</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NILU?</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">1 h</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">partly</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="middle" height="20"><span style="color: #000000;">Ice particle number concentration</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">only during mixed-phase cloud periods</span></td>
<td align="center" valign="middle"><span style="color: #000000;">S</span></td>
<td align="center" valign="middle"><span style="color: #000000;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L0, L1, L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">in situ</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">cloud</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CIS</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NF</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-S</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NILU?</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">1 min</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="middle" height="20"><span style="color: #000000;">Ice particle size distribution</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">only during mixed-phase cloud periods</span></td>
<td align="center" valign="middle"><span style="color: #000000;">S</span></td>
<td align="center" valign="middle"><span style="color: #000000;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L0, L1, L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">in situ</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">cloud</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CIS</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NF</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-S</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NILU?</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">10 min</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="middle" height="20"><span style="color: #000000;">Ice nucleating particle number concentration</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">both within and outside clouds</span></td>
<td align="center" valign="middle"><span style="color: #000000;">S</span></td>
<td align="center" valign="middle"><span style="color: #000000;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L0, L1, L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">in situ</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">cloud</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CIS</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NF</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-S</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NILU?</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">1 h</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">Y</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="middle" height="20"><span style="color: #000000;">Ice nucleating particle temperature spectrum</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">both within and outside clouds</span></td>
<td align="center" valign="middle"><span style="color: #000000;">S</span></td>
<td align="center" valign="middle"><span style="color: #000000;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L1, L2</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">in situ</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">cloud</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CIS</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NF</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-S</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NILU?</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">&lt;= 24 h</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">partly</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">-</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
</tr>
<tr>
<td align="left" valign="middle" height="20"><span style="color: #000000;">Bulk cloud water chemical composition</span></td>
<td align="left" valign="bottom"><span style="color: #000000;">only during cloud periods, time resolutions can vary between NFs</span></td>
<td align="center" valign="middle"><span style="color: #000000;">S</span></td>
<td align="center" valign="middle"><span style="color: #000000;">2</span></td>
<td align="center" valign="middle"><span style="color: #000000;">L1</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">in situ</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">cloud</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">CIS</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NF</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NRT-S</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">NILU?</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">open</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">&lt;= 24 h</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">partly</span></td>
<td align="center" valign="bottom"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="bottom" bgcolor="#215968"><span style="color: #215968;">1</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="center" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
<td align="left" valign="middle"><span style="color: #000000;">&nbsp;</span></td>
</tr>
</tbody>
</table>

### Appendix 2: List of ACTRIS level 3 data products
https://folk.nilu.no/~richard/actris-ri-variables/Appendix_II_ACTRIS-RI_level3_variables_21February2018.xlsx

### Appendix 3: ACTRIS In situ data centre unit (In-Situ) data life cycle and workflow diagram
![ACTRIS In situ data centre unit workflow diagram](https://folk.nilu.no/~richard/actris-ri-variables/ACTRIS_surface_insitu_workflow.jpg)

### Appendix 4: ACTRIS Aerosol remote sensing data centre unit (ARES) data life cycle and workflow diagram
![ACTRIS Aerosol remote sensing data centre unit workflow diagram](https://raw.githubusercontent.com/actris/data-management-plan/master/DMP/img/ACTRIS_Aerosol_Remote_Sensing_workflow.jpg)

### Appendix 5: ACTRIS Cloud remote sensing data centre unit (CLU) data life cycle and workflow diagram
![ACTRIS Cloud remote sensing data centre unit workflow diagram](https://raw.githubusercontent.com/actris/data-management-plan/master/DMP/img/ACTRIS_cloud_remote_Sensing_workflow.png)

### Appendix 6: ACTRIS trace gases remote sensing data centre unit (GRES) data life cycle and workflow diagram
![ACTRIS trace gases remote sensing data centre unit workflow diagram](https://raw.githubusercontent.com/actris/data-management-plan/master/DMP/img/workflow_gres.png)

### Appendix 7: ACTRIS Atmospheric simulation chamber data centre unit (ASC) data life cycle and workflow diagram
![ACTRIS Atmospheric simulation chamber data centre unit workflow diagram](https://raw.githubusercontent.com/actris/data-management-plan/master/DMP/img/atm_simulation_chamber_workflow.png)

### Appendix 8: Data lifecycle and workflow for ACCESS Data Centre Unit

