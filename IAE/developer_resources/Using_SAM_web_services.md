---
layout: dev_resources
title: Using the SAM Web Services
nav: using_SAM_web_services
---
### Using SAM Web Services 
SAM offers web services to search for both Entiy data and Exclusions data.<br>

The WSDL is available at https://gw.sam.gov/SAMWS/1.0/Entity?wsdl (https://gw.sam.gov/SAMWS/1.0/Entity?wsdl)
The Endpoint is https://gw.sam.gov/SAMWS/1.0/Entity (https://gw.sam.gov/SAMWS/1.0/Entity)

<b>Entity Managment data can be searched by:</b><br>
* DUNSNumber<br>
* CAGECode<br>
* taxpayerIdentificationNumber*<br>
* startDate & endDate<br>



*Note: TaxpayerIdentificationNumber requires elevated access. Click here [link to Accessing SAM Data] for Data Access Request instructions.<br><br>



Exclusions can be searched by:



###Testing SAM Web Services

| Web Service | Endpoint |
|---|---|
| SAM Entity Management | |
| __TEST ENDPOINT__ | https://test.sam.gov/SAMWS/1.0/Entity |
| SAM Exclusion |  |
| __TEST ENDPOINT__ | https://gw.test.sam.gov/SAMWS/1.0/ExclusionSearch |


<b>Test IDs:</b>

| ID Name | Password | Description | Examples of available data*| 
|---|---|---|---|
| SAMPublic | Contact IAETransparency@gsa.gov | The public Entity Management Web Service requires authentication | includes: name, address, some POC information |
| SAMFOUO | Contact IAETransparency@gsa.gov | For Official Use Only | Includes certain types of POC and hierarchy information. |
| SAMSensitive | Contact IAETransparency@gsa.gov | Offers more secure data including banking information and MPIN. |

*A test id is not needed for the SAM Exclusions XML web service. There is no role or authentication requirement.
 
Need more help? Click [here](sam entity management tutorial url in tech-docs) for the SAM entity web service management tutorial.

Tools available:

| Tool Name | Description |
|---|---|
| [Web Services tutorial](https://github.com/GSA/IAE-Architecture/tree/master/as-is/tech-docs/SAM) | Documents how to build an Entity Management web service. |
| [Sample XML request/response]() | Included in the web services tutorial. Various sample request and response for Entity Management. |
| [Soap UI project]() | Project ready for import into Soap UI. (http://www.soapui.org/) |
| [SAM Functional Data Dictionary](https://github.com/GSA/IAE-Architecture/blob/master/as-is/tech-docs/SAM/SAM%20Functional%20Data%20Dictionary%20v4.0.pdf) | https://github.com/GSA/IAE-Architecture/blob/master/as-is/tech-docs/SAM/SAM%20Functional%20Data%20Dictionary%20v4.0.pdf |
| [Web Services Response Schema Documentation]() | Coming Soon! |

If you have questions, please post them to [IAE Transparency Issues](https://github.com/GSA/IAE-Architecture/issues).



