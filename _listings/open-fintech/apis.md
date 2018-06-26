---
name: Open FinTech
x-slug: open-fintech
description: International standards yield technological, economic and social advantages.
  Standards speed up the development of new applications and simplify the process
  of communication between the services. Data and service is available under the Open
  Database License (ODbL). It is an open standard and open data, every player of FinTech
  market can contribute to development and enhancement. All data is available through
  Rest API based on JSON API standard.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/open-fintech-io.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Open FinTech
created: "2018-06-26"
modified: "2018-06-26"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/open-fintech/master/_listings/open-fintech/apis.md
specificationVersion: "0.14"
apis:
- name: Open FinTech List of banks
  x-api-slug: open-fintech
  description: Returns list of banks. Each object contains general information about
    bank such as name and status, also information about bank details and related
    link to main organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/open-fintech-io.png
  humanURL: http://openfintech.io
  baseURL: https://api.openfintech.io//v1///banks
  tags: Banks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/open-fintech/master/_listings/open-fintech/banks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/open-fintech/master/_listings/open-fintech/banks-get-openapi.md
- name: Open FinTech Bank by ID
  x-api-slug: open-fintech
  description: Returns bank with specific ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/open-fintech-io.png
  humanURL: http://openfintech.io
  baseURL: https://api.openfintech.io//v1///banks/{id}
  tags: Banks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/open-fintech/master/_listings/open-fintech/banksid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/open-fintech/master/_listings/open-fintech/banksid-get-openapi.md
- name: Open FinTech List of countries
  x-api-slug: open-fintech
  description: Returns all available countries.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/open-fintech-io.png
  humanURL: http://openfintech.io
  baseURL: https://api.openfintech.io//v1///countries
  tags: Countries
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/open-fintech/master/_listings/open-fintech/countries-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/open-fintech/master/_listings/open-fintech/countries-get-openapi.md
- name: Open FinTech Country by ID
  x-api-slug: open-fintech
  description: Returns country with specific ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/open-fintech-io.png
  humanURL: http://openfintech.io
  baseURL: https://api.openfintech.io//v1///countries/{id}
  tags: Countries
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/open-fintech/master/_listings/open-fintech/countriesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/open-fintech/master/_listings/open-fintech/countriesid-get-openapi.md
- name: Open FinTech List of currencies
  x-api-slug: open-fintech
  description: Returns all available currencies.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/open-fintech-io.png
  humanURL: http://openfintech.io
  baseURL: https://api.openfintech.io//v1///currencies
  tags: Currencies
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/open-fintech/master/_listings/open-fintech/currencies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/open-fintech/master/_listings/open-fintech/currencies-get-openapi.md
- name: Open FinTech Currency by ID
  x-api-slug: open-fintech
  description: Returns currency with specific ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/open-fintech-io.png
  humanURL: http://openfintech.io
  baseURL: https://api.openfintech.io//v1///currencies/{id}
  tags: Currencies
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/open-fintech/master/_listings/open-fintech/currenciesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/open-fintech/master/_listings/open-fintech/currenciesid-get-openapi.md
- name: Open FinTech List of exchangers
  x-api-slug: open-fintech
  description: |-
    Returns list of exchange markets. Each object contains general information about exchanger such as name and status, also information about rates export and related link to main organization.<br>
    Rates export standards is represented by:
    * [estandards](http://estandards.info)
    * [jsons](http://jsons.info)
    * ratex - our internal standard
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/open-fintech-io.png
  humanURL: http://openfintech.io
  baseURL: https://api.openfintech.io//v1///exchangers
  tags: Exchangers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/open-fintech/master/_listings/open-fintech/exchangers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/open-fintech/master/_listings/open-fintech/exchangers-get-openapi.md
- name: Open FinTech Exchanger by ID
  x-api-slug: open-fintech
  description: Returns exchanger with specific ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/open-fintech-io.png
  humanURL: http://openfintech.io
  baseURL: https://api.openfintech.io//v1///exchangers/{id}
  tags: Exchangers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/open-fintech/master/_listings/open-fintech/exchangersid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/open-fintech/master/_listings/open-fintech/exchangersid-get-openapi.md
- name: Open FinTech List of merchant industries
  x-api-slug: open-fintech
  description: Returns all available merchant fields of activity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/open-fintech-io.png
  humanURL: http://openfintech.io
  baseURL: https://api.openfintech.io//v1///merchant-industries
  tags: Merchant-industries
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/open-fintech/master/_listings/open-fintech/merchantindustries-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/open-fintech/master/_listings/open-fintech/merchantindustries-get-openapi.md
- name: Open FinTech Merchant industry by ID
  x-api-slug: open-fintech
  description: Returns merchant industry with specific ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/open-fintech-io.png
  humanURL: http://openfintech.io
  baseURL: https://api.openfintech.io//v1///merchant-industries/{id}
  tags: Merchant-industries
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/open-fintech/master/_listings/open-fintech/merchantindustriesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/open-fintech/master/_listings/open-fintech/merchantindustriesid-get-openapi.md
- name: Open FinTech List of organizations
  x-api-slug: open-fintech
  description: This endpoint retrievs the list of organizations present in the system.
    The data displays general, public information, without reference to the type of
    activity (for example - name, address, contacts, etc.).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/open-fintech-io.png
  humanURL: http://openfintech.io
  baseURL: https://api.openfintech.io//v1///organizations
  tags: Organizations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/open-fintech/master/_listings/open-fintech/organizations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/open-fintech/master/_listings/open-fintech/organizations-get-openapi.md
- name: Open FinTech Organization by ID
  x-api-slug: open-fintech
  description: Returns organization with specific ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/open-fintech-io.png
  humanURL: http://openfintech.io
  baseURL: https://api.openfintech.io//v1///organizations/{id}
  tags: Organizations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/open-fintech/master/_listings/open-fintech/organizationsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/open-fintech/master/_listings/open-fintech/organizationsid-get-openapi.md
- name: Open FinTech List of payment methods
  x-api-slug: open-fintech
  description: Returns list of payment methods. Each object contains information about
    payment method such as name and category, also related link to payment method
    issuer (which processing it).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/open-fintech-io.png
  humanURL: http://openfintech.io
  baseURL: https://api.openfintech.io//v1///payment-methods
  tags: Payment-methods
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/open-fintech/master/_listings/open-fintech/paymentmethods-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/open-fintech/master/_listings/open-fintech/paymentmethods-get-openapi.md
- name: Open FinTech Payment method by ID
  x-api-slug: open-fintech
  description: Returns payment method with specific ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/open-fintech-io.png
  humanURL: http://openfintech.io
  baseURL: https://api.openfintech.io//v1///payment-methods/{id}
  tags: Payment-methods
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/open-fintech/master/_listings/open-fintech/paymentmethodsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/open-fintech/master/_listings/open-fintech/paymentmethodsid-get-openapi.md
- name: Open FinTech List of payment providers
  x-api-slug: open-fintech
  description: 'A payment service provider (PSP) offers shops online services for
    accepting electronic payments by a variety of payment methods.<br> Endpoint returns
    list of PSPs. Each object contains: name, type, supported features and sales channels,
    also related link to available payment methods and main organization.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/open-fintech-io.png
  humanURL: http://openfintech.io
  baseURL: https://api.openfintech.io//v1///payment-providers
  tags: Payment-providers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/open-fintech/master/_listings/open-fintech/paymentproviders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/open-fintech/master/_listings/open-fintech/paymentproviders-get-openapi.md
- name: Open FinTech Payment provider by ID
  x-api-slug: open-fintech
  description: Returns payment provider with specific ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/open-fintech-io.png
  humanURL: http://openfintech.io
  baseURL: https://api.openfintech.io//v1///payment-providers/{id}
  tags: Payment-providers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/open-fintech/master/_listings/open-fintech/paymentprovidersid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/open-fintech/master/_listings/open-fintech/paymentprovidersid-get-openapi.md
- name: Open FinTech
  x-api-slug: open-fintech
  description: International standards yield technological, economic and social advantages.
    Standards speed up the development of new applications and simplify the process
    of communication between the services. Data and service is available under the
    Open Database License (ODbL). It is an open standard and open data, every player
    of FinTech market can contribute to development and enhancement. All data is available
    through Rest API based on JSON API standard.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/open-fintech-io.png
  humanURL: http://openfintech.io
  baseURL: https://api.openfintech.io//v1/
  tags: Open FinTech
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/open-fintech/master/_listings/open-fintech/openapi.md
x-common:
- type: x-developer
  url: https://docs.openfintech.io/
- type: x-getting-started
  url: https://docs.openfintech.io/#section/Get-Started
- type: x-github
  url: https://github.com/openfintechio
- type: x-website
  url: http://openfintech.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---