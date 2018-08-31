swagger: "2.0"
x-collection-name: Open FinTech
x-complete: 1
info:
  title: Open FinTech
  description: openfintech-io-is-an-open-database-that-comprises-of-standardized-primary-data-for-fintech-industry--it-contains-such-information-as-geolocation-data-countries-cities-regions-organizations-currencies-national-digital-virtual-crypto-banks-digital-exchangers-payment-providers-psp-payment-methods-etc-it-is-created-for-communication-of-crossintegrated-microservices-on-one-language--this-is-achieved-through-standardization-of-entity-identifiers-that-are-used-to-exchange-information-among-different-services-
  version: "2017-08-24"
host: api.openfintech.io
basePath: /v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /banks:
    get:
      summary: List of banks
      description: Returns list of banks. Each object contains general information
        about bank such as name and status, also information about bank details and
        related link to main organization.
      operationId: banks.get
      x-api-path-slug: banks-get
      parameters:
      - in: query
        name: filter[sort_code]
        description: Filtering by banks code
      - in: query
        name: filter[status]
        description: Filtration by status
      - in: query
        name: No Name
      - in: query
        name: sort
        description: Sort params:| ASC | DESC ||-----|------|| name | -name || code
          | -code || status | -status || sort_code | -sort_code |
      responses:
        200:
          description: OK
      tags:
      - Banks
  /banks/{id}:
    get:
      summary: Bank by ID
      description: Returns bank with specific ID.
      operationId: banks.id.get
      x-api-path-slug: banksid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Banks
  /countries:
    get:
      summary: List of countries
      description: Returns all available countries.
      operationId: countries.get
      x-api-path-slug: countries-get
      parameters:
      - in: query
        name: filter[region]
        description: Filtration by region
      - in: query
        name: filter[sub_region]
        description: Filtration by sub region
      - in: query
        name: No Name
      - in: query
        name: sort
        description: Sort params:| ASC | DESC ||-----|------|| name | -name || area
          | -area || population | -population || region | -region || sub_region |
          -sub_region |
      responses:
        200:
          description: OK
      tags:
      - Countries
  /countries/{id}:
    get:
      summary: Country by ID
      description: Returns country with specific ID.
      operationId: countries.id.get
      x-api-path-slug: countriesid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Countries
  /currencies:
    get:
      summary: List of currencies
      description: Returns all available currencies.
      operationId: currencies.get
      x-api-path-slug: currencies-get
      parameters:
      - in: query
        name: filter[category]
        description: Filtration by category
      - in: query
        name: filter[code_estandards_alpha]
        description: Filtering by estandards code
      - in: query
        name: filter[code_iso_alpha3]
        description: Filtering by ISO code
      - in: query
        name: filter[code_iso_numeric3]
        description: Filtering by ISO number
      - in: query
        name: filter[currency_type]
        description: Filtration by currency type
      - in: query
        name: filter[search]
        description: Full text search with name, code, type, code_iso_alpha3, code_jsons_alpha,
          code_estandards_alpha, category
      - in: query
        name: No Name
      - in: query
        name: sort
        description: Sort params:| ASC | DESC ||-----|------|| name | -name || type
          | -type || category | -category || code | -code || code_iso_alpha3 | -code_iso_alpha3
          || code_iso_numeric3 | -code_iso_numeric3 || code_estandards_alpha | -code_estandards_alpha
          |
      responses:
        200:
          description: OK
      tags:
      - Currencies
  /currencies/{id}:
    get:
      summary: Currency by ID
      description: Returns currency with specific ID.
      operationId: currencies.id.get
      x-api-path-slug: currenciesid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Currencies
  /exchangers:
    get:
      summary: List of exchangers
      description: |-
        Returns list of exchange markets. Each object contains general information about exchanger such as name and status, also information about rates export and related link to main organization.<br>
        Rates export standards is represented by:
        * [estandards](http://estandards.info)
        * [jsons](http://jsons.info)
        * ratex - our internal standard
      operationId: exchangers.get
      x-api-path-slug: exchangers-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: sort
        description: Sort params:| ASC | DESC ||-----|------|| name | -name || status
          | -status || wmid | -wmid || rate_type | -rate_type || rates_export_standard
          | -rates_export_standard |
      responses:
        200:
          description: OK
      tags:
      - Exchangers
  /exchangers/{id}:
    get:
      summary: Exchanger by ID
      description: Returns exchanger with specific ID.
      operationId: exchangers.id.get
      x-api-path-slug: exchangersid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Exchangers
  /merchant-industries:
    get:
      summary: List of merchant industries
      description: Returns all available merchant fields of activity.
      operationId: merchant_industries.get
      x-api-path-slug: merchantindustries-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Merchant-industries
  /merchant-industries/{id}:
    get:
      summary: Merchant industry by ID
      description: Returns merchant industry with specific ID.
      operationId: merchant_industries.id.get
      x-api-path-slug: merchantindustriesid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Merchant-industries
  /organizations:
    get:
      summary: List of organizations
      description: This endpoint retrievs the list of organizations present in the
        system. The data displays general, public information, without reference to
        the type of activity (for example - name, address, contacts, etc.).
      operationId: organizations.get
      x-api-path-slug: organizations-get
      parameters:
      - in: query
        name: filter[industries]
        description: Filtering by industries
      - in: query
        name: filter[search]
        description: Full text search with id, name, code
      - in: query
        name: No Name
      - in: query
        name: sort
        description: Sort params:| ASC | DESC ||-----|------|| name | -name || code
          | -code || status | -status || description | -description |
      responses:
        200:
          description: OK
      tags:
      - Organizations
  /organizations/{id}:
    get:
      summary: Organization by ID
      description: Returns organization with specific ID.
      operationId: organizations.id.get
      x-api-path-slug: organizationsid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Organizations
  /payment-methods:
    get:
      summary: List of payment methods
      description: Returns list of payment methods. Each object contains information
        about payment method such as name and category, also related link to payment
        method issuer (which processing it).
      operationId: payment_methods.get
      x-api-path-slug: paymentmethods-get
      parameters:
      - in: query
        name: filter[category]
        description: Filtering by category
      - in: query
        name: filter[processor_name]
        description: Filtering by processor_name
      - in: query
        name: filter[search]
        description: Full text search with id, name, code, category
      - in: query
        name: No Name
      - in: query
        name: sort
        description: Sort params:| ASC | DESC ||-----|------|| name | -name || code
          | -code || processor_name | -processor_name || category | -category |
      responses:
        200:
          description: OK
      tags:
      - Payment-methods
  /payment-methods/{id}:
    get:
      summary: Payment method by ID
      description: Returns payment method with specific ID.
      operationId: payment_methods.id.get
      x-api-path-slug: paymentmethodsid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Payment-methods
  /payment-providers:
    get:
      summary: List of payment providers
      description: 'A payment service provider (PSP) offers shops online services
        for accepting electronic payments by a variety of payment methods.<br> Endpoint
        returns list of PSPs. Each object contains: name, type, supported features
        and sales channels, also related link to available payment methods and main
        organization.'
      operationId: payment_providers.get
      x-api-path-slug: paymentproviders-get
      parameters:
      - in: query
        name: filter[features]
        description: Filtering by features
      - in: query
        name: filter[sales_channels]
        description: Filtering by sales channels
      - in: query
        name: filter[search]
        description: Full text search with id, code, name
      - in: query
        name: filter[types]
        description: Filtering by types
      - in: query
        name: No Name
      - in: query
        name: sort
        description: Sort params:| ASC | DESC ||-----|------|| name | -name || code
          | -code |
      responses:
        200:
          description: OK
      tags:
      - Payment-providers
  /payment-providers/{id}:
    get:
      summary: Payment provider by ID
      description: Returns payment provider with specific ID.
      operationId: payment_providers.id.get
      x-api-path-slug: paymentprovidersid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Payment-providers