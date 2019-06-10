# usdot-jpo-ode-workzone-data-exchange

Workzone Data Exchange Validator is a validation service that checks JSON data against the [WZDx v1.1 specification](https://github.com/usdot-jpo-ode/jpo-wzdx/blob/master/full-spec/full-spec.md).  This project uses [ReVAL (Django Data Ingest)](https://github.com/18F/django-data-ingest) to perform JSON Schema validation.

Please note that WZDx v1.1 specification is written in XML, therefore, the [JSON schema](https://github.com/18F/usdot-jpo-ode-workzone-data-exchange/blob/master/schema.json) provided here is derived from the XML version.  More specifically, it was derived from the [WZDx_final01.xsd file](https://github.com/usdot-jpo-ode/jpo-wzdx/blob/master/sample-files/WZDx_final01.xsd).