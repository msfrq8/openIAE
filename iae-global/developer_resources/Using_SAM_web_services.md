---
layout: dev_resources
title: Using the SAM Web Services
nav: using_SAM_web_services
---
### Using SAM Web Services 
SAM offers web services to search for Entiy data and Excluded Party data.<br>
Entity Managment data can be searched by:<br>
DUNSNumber<br>
CAGECode<br>
taxpayerIdentificationNumber*<br>
startDate & endDate<br>
*Note: TaxpayerIdentificationNumber requires elevated access<br><br>
Exclusions can be searched by:



Here is what you need to get started:

| Web Service Name | Endpoint / WSDL |
|---|---|
| SAM Entity Management | https://gw.sam.gov/SAMWS/1.0/Entity?wsdl |
| __TEST ENDPOINT__ | https://test.sam.gov/SAMWS/1.0/Entity |
| __WSDL FILE__ | https://github.com/GSA/IAE-Architecture/blob/master/as-is/tech-docs/SAM/SAMWSDLsv1.0/Entity.wsdl |
| SAM Exclusion | https://gw.sam.gov/SAMWS/1.0/ExclusionSearch?wsdl |
| __TEST ENDPOINT__ | https://gw.test.sam.gov/SAMWS/1.0/ExclusionSearch |
| __WSDL FILE__ | https://github.com/GSA/IAE-Architecture/blob/master/as-is/tech-docs/SAM/SAMWSDLsv1.0/ExclusionSearch.wsdl |

Test IDs:

| ID Name | Password | Description | Examples of available data*| 
|---|---|---|---|
| SAMPublic | Contact pamela.miller@gsa.gov | EM XML at the public level requires authentication. | includes: name, address, some POC information |
| SAMFOUO | Contact pamela.miller@gsa.gov | For Official Use Only | includes certain types of POC and hierarchy information. |
| SAMSensitive | Contact pamela.miller@gsa.gov | more secure data including banking information and MPIN. |

*A test id is not needed for the SAM Exclusions XML web service. There is no role or authentication requirement.
 
Need more help? Click [here](sam entity management tutorial url in tech-docs) for the SAM entity web service management tutorial.

Tools available:

| Tool Name | Location | Description |
|---|---|---|
| Web Services tutorial | https://github.com/GSA/IAE-Architecture/tree/master/as-is/tech-docs/SAM | Documents how to build an Entity Management web service. |
| Sample XML request/response | https://interact.gsa.gov | Included in the web services tutorial. Various sample request and response for Entity Management. |
| Soap UI project | https://interact.gsa.gov | Project ready for import into Soap UI. (http://www.soapui.org/) |
| SAM Functional Data Dictionary | https://github.com/GSA/IAE-Architecture/blob/master/as-is/tech-docs/SAM/SAM%20Functional%20Data%20Dictionary%20v4.0.pdf |  |
| Web Services Response Schema Documentation |  | Coming Soon! |

If you have questions, please post them to [IAE Transparency Issues](https://github.com/GSA/IAE-Architecture/issues).



