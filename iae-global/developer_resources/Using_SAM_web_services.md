---
layout: dev_resources
title: Using the SAM Data Extract
nav: using_SAM_data_extract
---
### SAM Web Services Documentation

Version 1.0 
 
A note on version:  With this last round of updates to the documentation we have baselined both our documentation and extract/web service releases. We have baselined to v1.0.  
 
UPDATE: re-posted  SAMWebServiceMappingsv1.0 on 5/19/2014 - no changes except to the names of the actual excel files from v5.1 to v1.0
 
All SAM extract files and web service WSDLs are now at v1.0. 
We have not made any major changes either the file layouts or the web service request/response structure or WSDLs since the intital rollout in May, 2013. 
We will use a standad 1.x.x (Major, Minor, Revision) for versioning going forward
 
SAMWebServiceMappingsv1.0 (attached below) has all of the documentation updates. Please look at the first tab, "Change Log" to review the changes in the documenation.
Quick Guide to get started using SAM Web Services:

The SAM test environment is completely separate from the SAM production environment so separate IDs are needed.  We have created generic IDs with independent passwords that are completely separate from production credentials. The data, above public access, is masked but usable for testing in the environment.

Here is what you need to get started:
Web Service Name | Endpoint / WSDL
---|---
SAM Entity Management XML | https://gw.test.sam.gov/SAMWS/1.0/Entity or

https://test.sam.gov/SAMWS/1.0/Entity

https://gw.sam.gov/SAMWS/1.0/Entity?wsdl 

SAM Exclusion XML | https://gw.test.sam.gov/SAMWS/1.0/ExclusionSearch

https://gw.sam.gov/SAMWS/1.0/ExclusionSearch?wsdl
