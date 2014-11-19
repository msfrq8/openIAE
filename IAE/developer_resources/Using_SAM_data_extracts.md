---
layout: dev_resources
title: Using SAM Data Extracts
nav: using_SAM_data_extract
---
### Using SAM Data Extracts
SAM hosts extract files for both Entity Management and Exclusions Data. You can get these files from two sources:<br>
1. SFTP - [Click here](https://github.com/GSA/IAE-Architecture/blob/master/as-is/tech-docs/SAM/Guide%20to%20Downloading%20SAM%20Extracts%20via%20SFTP%20Site.pdf?raw=true) for How to Download SAM Extracts from the SFTP server<br>
2. SAM.gov webiste. Go to SAM.gov under the "Data Access" area. <br>

SAM Extract files are available at three access levels:<br>
1. Public (includes name, address, Point of Contact information, etc.)<br>
2. For Official Use Only (FOUO) (includes certain types of Point of Contact Information and Federal Hierarchy information)<br>
3. Sensitive (includes banking information and MPIN)

If you require either FOUO or Sensitive levels of access you will need to add a role to your SAM account. To do that (link needed) click here for instructions.


Tools available:

| Tool Name | Description |
|---|---|
| [SAM Extract Mappings v1.0](https://github.com/GSA/IAE-Architecture/tree/master/as-is/tech-docs/SAM/SAMWebServicesExtractsMappingsv1.0) | Description of field mappings, data types, etc. |
| [Database load scripts for extracts](https://github.com/SiloSmashers/iae-global/blob/gh-pages/iae-global/developer_resources/SAM%20Master%20Extract%20Mapping%20v5.1%20FOUO%20File%20Layout.xlsx?raw=true) | Use this script when you are setting up your database to consume SAM Extracts. |
| [Guide to SFTP Download](https://github.com/GSA/IAE-Architecture/blob/master/as-is/tech-docs/SAM/Guide%20to%20Downloading%20SAM%20Extracts%20via%20SFTP%20Site.pdf?raw=true) | Instruction guide on how to download SAM extract files.|
| <a href="https://github.com/GSA/IAE-Architecture/tree/master/as-is/tech-docs/SAM/Sample%20Extract%20Files" target="_blank">Sample Files</a> | Sample files at all data access levels |
| [SAM Functional Data Dictionary](https://github.com/GSA/IAE-Architecture/blob/master/as-is/tech-docs/SAM/SAM%20Functional%20Data%20Dictionary%20v4.0.pdf?raw=true) |   |
|---|---|
| [Exclusions Extract User Guide](https://github.com/GSA/IAE-Architecture/blob/master/as-is/tech-docs/SAM/SAM_Exclusions_Extract_User_Guide.pdf?raw=true)|SAM Exclusions Extract contains a list of all currently open exclusions in SAM|


If you have questions, please post them to this site's [Repo Issues](https://github.com/GSA/IAE-Architecture/issues).
