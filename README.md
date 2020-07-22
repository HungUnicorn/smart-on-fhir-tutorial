# smart-on-fhir-tutorial
SMART on FHIR developer tutorial

Use Cerner's SMART on FHIR skeleton to show EPIC's SMART launch. After some logins, you can see the information that's belongs to the logined patient.

## What is SMART on FHIR?
SMART (Substitutable Medical Applications and Reusable Technologies) is a standard that provides a flow for how EHR systems and their applications authenticate and integrate.

FHIR (Fast Healthcare Interoperability Resource) is a standard that provides a set of data models for structuring and accessing medical data.

- ref: http://hl7.org/fhir/smart-app-launch/index.html
- ref: The original paper: https://academic.oup.com/jamia/article/23/5/899/2379865

## Endpoint
### Health
https://hungunicorn.github.io/smart-on-fhir-tutorial/example-smart-app/health.html

### Cerner
This endpint shows after login, you can see the logined patient info of Cerner.
https://hungunicorn.github.io/smart-on-fhir-tutorial/example-smart-app/launch-patient.html?iss=https://fhir-myrecord.sandboxcerner.com/dstu2/0b8a0111-e8e6-4c26-a91c-5069cbc6b1ca

#### Test patient
Username/password: wilma_smart/Cerner01

### Epic
This endpint shows after login, you can see the logined patient info of Epic
https://hungunicorn.github.io/smart-on-fhir-tutorial/example-smart-app/launch-epic-patient.html?iss=https://apporchard.epic.com/interconnect-aocurprd-oauth/api/FHIR/DSTU2

## Developement note
Cener’s documentation is free to access without an account. The sandbox for playing/testing requires an account to login and it's free to create and doesn’t ask for credit card info. In contrast, reading Epic documentation requires an account to login and the sandbox requires credit card information.
