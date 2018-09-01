---
name: Standard Chartered
x-slug: standard-chartered
description: Standard Chartered PLC is a British multinational banking and financial
  services company headquartered in London, England. It operates a network of more
  than 1,200 branches and outlets (including subsidiaries, associates and joint ventures)
  across more than 70 countries and employs around 87,000 people. It is a universal
  bank with operations in consumer, corporate and institutional banking, and treasury
  services. Despite its UK base, it does not conduct retail banking in the UK, and
  around 90% of its profits come from Asia, Africa and the Middle East.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/standard-charter.png
x-kinRank: "7"
x-alexaRank: "4658"
tags: Standard Chartered
created: "2018-08-31"
modified: "2018-08-31"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/standard-chartered/master/_listings/standard-chartered/apis.md
specificationVersion: "0.14"
apis:
- name: Standard Chartered - Accounts
  x-api-slug: cibservices2bapiv1banksscbaccountsaccountidviewidaccount-get
  description: The ???GetAccountBalance??? API upon successful user authentication
    and entitlement checks will return the various types of ???Account Balances???
    applicable for the specified Account Number.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/standard-charter.png
  humanURL: https://developer.sc.com
  baseURL: https://developer.sc.com//
  tags: Financial Services, UK Banks, General Data, Relative Data, Banking
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/standard-chartered/master/_listings/standard-chartered/cibservices2bapiv1banksscbaccountsaccountidviewidaccount-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/standard-chartered/master/_listings/standard-chartered/cibservices2bapiv1banksscbaccountsaccountidviewidaccount-get-openapi.md
- name: Standard Chartered - Finds all support transaction types for a given account
  x-api-slug: cibservices2bapiv1banksscbaccountsaccountidviewidtransactionrequesttypes-get
  description: The ???GetTransactionTypes??? API upon successful user authentication
    and entitlement checks will return the supported transaction types for the specified
    account
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/standard-charter.png
  humanURL: https://developer.sc.com
  baseURL: https://developer.sc.com//
  tags: Financial Services, UK Banks, General Data, Relative Data, Banking
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/standard-chartered/master/_listings/standard-chartered/cibservices2bapiv1banksscbaccountsaccountidviewidtransactionrequesttypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/standard-chartered/master/_listings/standard-chartered/cibservices2bapiv1banksscbaccountsaccountidviewidtransactionrequesttypes-get-openapi.md
- name: Standard Chartered - Account Details & Balances
  x-api-slug: cibservices2bapiv1banksscbaccountsviewidaccounts-get
  description: List available bank accounts
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/standard-charter.png
  humanURL: https://developer.sc.com
  baseURL: https://developer.sc.com//
  tags: Financial Services, UK Banks, General Data, Relative Data, Banking
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/standard-chartered/master/_listings/standard-chartered/cibservices2bapiv1banksscbaccountsviewidaccounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/standard-chartered/master/_listings/standard-chartered/cibservices2bapiv1banksscbaccountsviewidaccounts-get-openapi.md
- name: Standard Chartered - Bank Code Inquiry
  x-api-slug: cibservices2bapiv1banksscbreferencedefaultbranches-post
  description: The ???GetBankCode??? API returns list of Bank Codes for the specified
    combination of ???Country???, ???City??? and ???Bank??? combination. The data
    will contain the ???Bank Code(s)??? as well as the address for the Bank & Branch.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/standard-charter.png
  humanURL: https://developer.sc.com
  baseURL: https://developer.sc.com//
  tags: Financial Services, UK Banks, General Data, Relative Data, Banking
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/standard-chartered/master/_listings/standard-chartered/cibservices2bapiv1banksscbreferencedefaultbranches-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/standard-chartered/master/_listings/standard-chartered/cibservices2bapiv1banksscbreferencedefaultbranches-post-openapi.md
- name: Standard Chartered - Holiday Calendar Inquiry (Country)
  x-api-slug: cibservices2bapiv1banksscbreferencedefaultholidaycalendarcountrycountry-get
  description: |-
    The ???GetHolidayCalendar??? API returns list of holidays applicable for the specified combination of:
    <ul><li>Country</li><li>Date Range</li></lu>
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/standard-charter.png
  humanURL: https://developer.sc.com
  baseURL: https://developer.sc.com//
  tags: Financial Services, UK Banks, General Data, Relative Data, Banking
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/standard-chartered/master/_listings/standard-chartered/cibservices2bapiv1banksscbreferencedefaultholidaycalendarcountrycountry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/standard-chartered/master/_listings/standard-chartered/cibservices2bapiv1banksscbreferencedefaultholidaycalendarcountrycountry-get-openapi.md
- name: Standard Chartered - Holiday Calendar Inquiry (Currency)
  x-api-slug: cibservices2bapiv1banksscbreferencedefaultholidaycalendarcurrencycurrency-get
  description: |-
    The ???GetHolidayCalendar??? API returns list of holidays applicable for the specified combination of:
    <ul><li>Currency</li><li>Date Range</li></lu>
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/standard-charter.png
  humanURL: https://developer.sc.com
  baseURL: https://developer.sc.com//
  tags: Financial Services, UK Banks, General Data, Relative Data, Banking
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/standard-chartered/master/_listings/standard-chartered/cibservices2bapiv1banksscbreferencedefaultholidaycalendarcurrencycurrency-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/standard-chartered/master/_listings/standard-chartered/cibservices2bapiv1banksscbreferencedefaultholidaycalendarcurrencycurrency-get-openapi.md
- name: Standard Chartered - Retrieve trade finance customer profile
  x-api-slug: cibservices2bapiv1tradecountrycodecustomeridprofile-get
  description: Retrieve trade finance customer profile
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/standard-charter.png
  humanURL: https://developer.sc.com
  baseURL: https://developer.sc.com//
  tags: Financial Services, UK Banks, General Data, Relative Data, Banking
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/standard-chartered/master/_listings/standard-chartered/cibservices2bapiv1tradecountrycodecustomeridprofile-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/standard-chartered/master/_listings/standard-chartered/cibservices2bapiv1tradecountrycodecustomeridprofile-get-openapi.md
- name: Standard Chartered - Retrieve trade finance limit details
  x-api-slug: cibservices2bapiv1tradecountrycodecustomeridlimits-get
  description: Retrieve trade finance limit details
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/standard-charter.png
  humanURL: https://developer.sc.com
  baseURL: https://developer.sc.com//
  tags: Financial Services, UK Banks, General Data, Relative Data, Banking
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/standard-chartered/master/_listings/standard-chartered/cibservices2bapiv1tradecountrycodecustomeridlimits-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/standard-chartered/master/_listings/standard-chartered/cibservices2bapiv1tradecountrycodecustomeridlimits-get-openapi.md
- name: Standard Chartered - Retrieve all trade finance transaction status for the
    current date (localised to tz)
  x-api-slug: cibservices2bapiv1tradecountrycodecustomeridtransactions-get
  description: Retrieve all trade finance transaction status for the current date
    (localised to tz)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/standard-charter.png
  humanURL: https://developer.sc.com
  baseURL: https://developer.sc.com//
  tags: Financial Services, UK Banks, General Data, Relative Data, Banking
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/standard-chartered/master/_listings/standard-chartered/cibservices2bapiv1tradecountrycodecustomeridtransactions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/standard-chartered/master/_listings/standard-chartered/cibservices2bapiv1tradecountrycodecustomeridtransactions-get-openapi.md
- name: Standard Chartered - Retrieve trade finance transaction status for specific
    transaction reference Id
  x-api-slug: cibservices2bapiv1tradecountrycodecustomeridtransactiontransactionid-get
  description: Retrieve trade finance transaction status for specific transaction
    reference Id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/standard-charter.png
  humanURL: https://developer.sc.com
  baseURL: https://developer.sc.com//
  tags: Financial Services, UK Banks, General Data, Relative Data, Banking
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/standard-chartered/master/_listings/standard-chartered/cibservices2bapiv1tradecountrycodecustomeridtransactiontransactionid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/standard-chartered/master/_listings/standard-chartered/cibservices2bapiv1tradecountrycodecustomeridtransactiontransactionid-get-openapi.md
x-common:
- type: x-accessibility
  url: https://developer.sc.com/cib/#/accessibility
- type: x-api-gallery
  url: http://stack.exchange.api.gallery.streamdata.io
- type: x-api-stack
  url: http://standard.chartered.stack.network
- type: x-applications
  url: https://developer.sc.com/cib/#/showcases
- type: x-crunchbase
  url: https://crunchbase.com/organization/standard-chartered-bank
- type: x-documentation
  url: https://developer.sc.com/cib/#/api-documentation/3
- type: x-privacy-policy
  url: https://developer.sc.com/cib/#/privacy
- type: x-terms-of-service
  url: https://developer.sc.com/cib/#/legal-notice
- type: x-twitter
  url: https://twitter.com/StanChart
- type: x-website
  url: https://developer.sc.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---