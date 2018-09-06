
Introduction
- Overview

Data types, operations, process model, formal metadata and extension capabilities
-Purpose (interchange, HL7 2.0 is old and awful, doesn’t have semantic capabilities)

- Epic 2016 has some read endpoints

 https://intorca-staging.providence.org/Interconnect-OCLAB/DeveloperView/Main.aspx?clientid=1
-Previous version, DSTU2, used by Cerner, etc.

http://fhir.cerner.com/millennium/dstu2/
https://intorca-staging.providence.org/Interconnect-OCLAB/DeveloperView/Main.aspx?clientid=1
https://datahandbook.epic.com/Search/Index?SearchWord=fhir&type=5&def=0
- Current version, STU3

-Approaching stability (some resources at L5 maturity)

- Future version, ST4 (release Q4 2017, published Q3 2018)

 

Content
- Resources https://www.hl7.org/fhir/resourceguide.html

- Structural types https://www.hl7.org/fhir/bundle.html

- REST extensions https://www.hl7.org/fhir/http.html

Status codes
OperationOutcome
Content-type, caching
Interactions
Searching, pagination
Operation extensions https://www.hl7.org/fhir/operations.html
- Metadata

Profiles, tags, security labels https://www.hl7.org/fhir/resource-operations.html#meta-add
-  Codes & Lookups

https://www.hl7.org/fhir/valueset-operations.html#expand
- Ids, versions https://www.hl7.org/fhir/datatypes.html#Identifier

- Security – OIDC, Oauth, SMART, HEART

https://www.hl7.org/fhir/security.html
http://docs.smarthealthit.org/authorization/scopes-and-launch-context/
https://openid.net/wg/heart/
- HATEOAS via https://www.hl7.org/fhir/capabilitystatement.html

- Extensions

Adding attributes, adding modifiers https://www.hl7.org/fhir/extensibility.html
Adding operations https://www.hl7.org/fhir/operationdefinition.html
- Reference implementation https://github.com/jamesagnew/hapi-fhir

 
