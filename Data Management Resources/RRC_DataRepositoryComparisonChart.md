# Data Repository Comparison Chart

### About this document
The Rice Rivers Center (RRC) is working to build infrastructure that illuminates the relationship between 
field station activities, publications, and data sets. Often times, these components of a research project are
tracked and managed separately and the connecting link between them is lost over time. At Rice, we are
working to implement new data management protocols like project registration, Data Management Plans, and
data archiving requirements to track these project components and provide visibility at the field station-level. 

One of the major drivers for implementing these new data management protocols is to ensure that RRC-affiliated
data are [FAIR](https://www.go-fair.org/fair-principles/). FAIR data are **F**indable, **A**ccessible, **I**nteroperable, 
and **R**eusable. By depositing your final research data sets into an established research data repository, along
with rich, contextual metadata, you are likely to have produced FAIR data! In an effort to be FAIR, RRC is
requiring data collected at RRC or with RRC support to be made public within one year of publication (unless an
exception has been made and approved via the Project Registration Form). To support your efforts, this document 
has been created to provide guidance on the different research data repositories and their corresponding requirements. 

As with the other data management protocols that are being rolled out, we welcome any and all feedback 
related to this document. You are encouraged to contact the [RRC Data Manager](https://ricerivers.vcu.edu/directory/lauren-wick.html)
directly with feedback, questions, and/or concerns. 

### Where can I deposit my research data products?
You have the option to deposit data to various research data repositories for long term preservation and 
discoverability, ranging from broad research domains to specific niches. RRC recommends that you consider
the different options for depositing your data early on in your project, ideally when you are 
developing your Data Management Plan (DMP).

The table below is a starting point for choosing a data repository for archiving your data. This is not a 
comprehensive list of all data repositories out there, but a starting point that covers some of the most
common options. The [re3data project](https://www.re3data.org/) (Registry of Research Data Repositories) is a global registry of 
research data repositories across various disciplines. To explore data repositories by subject, use their 
[graphical web tool](https://www.re3data.org/browse/by-subject/). 


| Repository Name | Metadata Requirements | Domain | Data Formats Accepted | Data Size Restrictions | Storage Costs |
|-----------------|-----------------------|--------|-----------------------|------------------------|---------------|
| [Environmental Data Initiative](https://edirepository.org/) | Metadata is submitted in the Ecological Metadata Language (EML) | All ecological and environmental data, irrespective of origin. | Non-proprietary and non-binary format (e.g. .csv, .txt). Some exceptions allowed. | Soft limit of 500MB and hard limit of 100GB per data package. | Free |
| [Dryad](https://datadryad.org/) | Required fields: journal name, title, author(s), abstract, research domain, keywords. | All research domains. | Most file types are supported, but non-proprietary files are preferred. | Individual files should not exceed 10GB. | [Priced per dataset size](https://datadryad.org/help/requirements/costs). |
| [Figshare](https://figshare.com/) | Required fields: item title, item type, author(s), categories, keywords, description, and license. | All research domains. | Almost all file types are supported. | All figshare accounts are provided with 20GB of storage. Individual files cannot exceed 20GB. | Free up to 20GB per figshare account. [Plans are available for increased storage capacity](https://info.figshare.com/figshare-plus/). |
| [Zenodo](https://zenodo.org/) | Required fields: title, publication date, creators, and description. | All research domains. | Most file types are supported, but non-proprietary formats are preferred. | 50GB per record with a maximum of 100 files. | Free up to 50GB per record. A free one-time 200GB request is allowed. |
| [PANGAEA](https://www.pangaea.de/) | Required fields: title, author(s), abstract, license, and parameters. | Georeferenced data from earth system research. | Focus on tabular data. Data should be formatted as TAB-delimited text files in UTF-8 encoding or open spreadsheet file formats (MS Excel). | Individual files must be less than 15GB. Limit of 20 files per submission. | Free but they accept a contribution for projects with funding for publication costs. |


### Metadata standards and FAIR data

Metadata standards often drive the query logic behind these data repositories. It's important to consider
this when you are choosing your data repository. Think about how different requirements might make it easier, 
or more difficult, for your data to be discovered and accessed. 

While submitting to any of the above repositories often checks off the **F**indable and **A**ccessible points of the
FAIR data standards, you also need to ensure that you are providing rich and contextual metadata alongside
your data to ensure that it is also **I**nteroperable and **R**eusable. While some of the data repositories above have
more relaxed metadata requirements, simply submitting your data with the minimum requirements won't 
necessarily make them FAIR. It is recommended to go beyond the minimum metadata requirements when depositing
your data to enhance discoverability and ensure reusability. 

While EDI's Ecological Metadata Language is detailed and complex, they provide metadata generation tools
that can make it easier to meet their requirements. For a great example of EML metadata, check out Ariel Johnson's 
data set from the Forest Resilience Threshold Experiment (DOI https://doi.org/10.6073/pasta/8d563ea4ea39c03368487b2b34aa6987)
(Full metadata [here](https://portal.edirepository.org/nis/metadataviewer?packageid=edi.1844.1))




