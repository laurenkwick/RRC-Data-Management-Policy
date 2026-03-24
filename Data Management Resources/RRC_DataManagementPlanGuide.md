# **Data Management Plan (DMP) Guide**

### About this document
The Rice Rivers Center (RRC) is working to build infrastructure that illuminates the relationship between 
field station activities, publications, and data sets. Often times, these components of a research project are
tracked and managed separately and the connecting link between them is lost over time. At Rice, we are
working to implement new data management protocols like project registration, Data Management Plans, and
data archiving requirements to track these project components and provide visibility at the field station-level. 

One of the major drivers for implementing these new data management protocols is to ensure that RRC-affiliated
data are [FAIR](https://www.go-fair.org/fair-principles/). FAIR data are **F**indable, **A**ccessible, **I**nteroperable, 
and **R**eusable. Research data becomes FAIR when it is made publicly available with rich and contextual 
metadata. RRC requires research data that is collected at RRC or with RRC support to be deposited in a public
data repository within 1 year of publication. The process of depositing data is made easier if you complete a Data
Management Plan (DMP) as the information in your plan can be reused to populate downstream metadata. To assist in 
the development of a DMP for your project, this document provides guidance and examples for the DMP template 
found within the project registration form. 

As with the other data management protocols that are being rolled out, we welcome any and all feedback 
related to this document. You are encouraged to contact the [RRC Data Manager](https://ricerivers.vcu.edu/directory/lauren-wick.html)
directly with feedback, questions, and/or concerns. 

## **Data Management Plan Template**

The sections below breakdown the DMP topics into smaller questions. 

### 1. Data and Materials Produced

Describe the types of data, physical samples or collections, software, curriculum materials, and other
materials to be produced in the course of the project.

**Guidance:**

* Describe the data that will be generated from the research. If you know how your data tables will be set up, 
describe the parameters that will be recorded. 
  * Include full names of variables, variable definitions, units of measurement, codes used for missing data,
  and important contextual information like date and place of collection. 
* What types of data will you collect? (e.g. tabular data, survey data, software, audio data, visual
data, physical samples)
* How will you capture or create the data? (e.g. manual samples, data loggers, model simulation, etc.)
* If you will be using existing data, state this and include how you will obtain it.
* How will the data be processed? (e.g. GIS software, programming languages used, etc.)
* What quality assurance and quality control measures will you employ? 
  * Check out the [Cleaning Data and Quality Control Resource](https://edirepository.org/resources/cleaning-data-and-quality-control) 
  from EDI, which covers QAQC processes including value checking and data flagging.


### 2. Standards, Formats, and Metadata

Describe the standards to be used for all the data types anticipated, including data or file format and
metadata.

**Guidance:**

* Which file formats will you use for you data and why? (e.g. .csv, .txt, .tif) 
  * Using open formats ensures the long-term usability of data and are recommended for 
  sharing and archiving. 
* What metadata standards will you use and why? (e.g., Dublin Core, Ecological Metadata Language, etc.)
  * For a full list of metadata standards, check out the [Metadata Standards Catalog](https://rdamsc.bath.ac.uk/).
  * Check if your selected data repository requires a specific metadata standard for depositing your data.
* What contextual details should you include in your metadata to make it meaningful?
* What file naming conventions will you use to manage your data and folders? 
  * Names of files and variables should be constructed from entirely alphanumerics and underscores
  for the sake of machine readability. Spaces and symbols can be inconsistently represented across computational
  applications. (Source: [EDI](https://edirepository.org/resources/cleaning-data-and-quality-control))
  * Check out these resources: [File Naming Convention Worksheet](https://authors.library.caltech.edu/records/mmnpf-cez11) and
   [VCU Organizing and Documenting your Data](https://guides.library.vcu.edu/data/organize)
* How do you intend to manage multiple versions of your files? 
  * Track software changes using GitHub. 
  * Utilize Google's [versioning for non-native files](https://support.google.com/drive/answer/2409045?hl=en&visit_id=639099575811208680-617229695&rd=1).
  Make sure you mark "[Keep Forever](https://instructionaldesignthatworks.com/2023/08/21/manage-file-versions-in-google-drive/)" on your file's previous versions so that Google does not delete them. 

### 3. Roles and Responsibilities

Describe the roles and responsibilities of all parties with respect to the management of the data.

**Guidance:**

* Who are the personnel responsible for carrying out the DMP. Name specific people and their title if
possible. 
* How often will the DMP be reviewed and/or updated during the project? Who is responsible for 
performing this review?
* Which role(s) will assume responsibility for carrying out the DMP if personnel change occur?
* Is any training required to complete specific data collection, analysis, or management tasks?

### 4. Policies for Data Sharing and Public Access

Describe the policies for data sharing, public access, and re-use, including re-distribution by others and 
the production of derivatives. Where appropriate, include provisions for protection of privacy, 
confidentiality, security, intellectual property rights, and other rights. 

**Guidance:**

* How will you make the data available?
* When will you make the data available?
* How long will the original data creator retain the right to use the data before making them publicly
available?
  * Currently, RRC is encouraging researchers/data creators to publish data within a year of relevant publications.
* Are there ethical and privacy issues? Will any permission restrictions need to be placed on the data?
  * Review VCU's [Data Classification Standard Policy](https://itgovernance.vcu.edu/security/) to evaluate whether your
  data is Category I (Confidential and Regulated), Category II (Sensitive), or Category III (Public). Category
  III data can be made public without prior approval.
* Who is likely to be interested in the data? (e.g., researchers, educators, governmental organizations, community groups, etc.)
* What are the intended or foreseeable uses of the data? (e.g., research, applications, educational material, etc.)
* How do you wish to be acknowledged if your data is reused in the future?
  * What license will the data be released under? Check out EDI's [Licensing Data Guide](https://edirepository.org/resources/licensing-data).

### 5. Archiving, Storage, and Preservation

Describe plans for archiving data, metadata, samples, software, and other research products. Consider
which data will be deposited for long-term access and where.

**Guidance:**

* Which archive, repository, or database have you identified as a place to deposit data?
  * Check out the [RRC Data Repository Comparison Chart](https://laurenkwick.github.io/RRC-Data-Management-Policy/Data%20Management%20Resources/RRC_DataRepositoryComparisonChart.html) and
  and [VCU Research Data Management Guidelines](https://guides.library.vcu.edu/data/sharing) for help with
  making this decision. 
* Who is the long-term data owner?
  * In other words, once the data is published who should be the point of contact for future questions about the 
  data set.
* What procedures or requirements does your intended long-term repository have in place for
preservation and backup?
  * Most repositories outline their preservation, backup, and succession plans in their documentation. Examples: 
  [figshare data storage](https://info.figshare.com/user-guide/how-is-my-data-stored-is-it-secure/) and 
  [EDI data preservation](https://edirepository.org/about/data-sustainability).
* Which data will be preserved for the long-term?
* What transformations will be necessary to prepare data for preservation and sharing?
* What metadata and/or documentation will be submitted alongside the data in order to make the
data reusable?
  * Review metadata requirements of your selected repository as well as [FAIR data standards](https://www.go-fair.org/fair-principles/) to ensure
  your published data will be reusable. 

## **Acknowledgements**

This document references content from VCU CHS' [Data Management Plan Guidelines and Templates](https://intranet.chs.vcu.edu/media/chs-intranet/sponsored-programs/documents/DataManagementPlanGuidanceandTemplate_accessible.docx),
and NC State's [Drafting Your DMP Guide](https://www.lib.ncsu.edu/do/data-management/elements-of-a-dmp#TypesOfData). 
Additional resources from [GO FAIR](https://www.go-fair.org/), the [Environmental Data Initiative](https://edirepository.org/), [Figshare](https://figshare.com/), 
[VCU Library](https://www.library.vcu.edu/), [Research Data Alliance](https://www.rd-alliance.org/), and
[California Institute of Technology](https://www.caltech.edu/) are noted throughout the document with direct references to their content.


