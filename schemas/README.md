# Data Schemas

The schema docs listed here are to be used in the KYC Testing scenarios

## National Identity Schema

This record should match as close as possible to the standards and conventions in use by the DHA in the issuance of the types
of identification documents listed below:

* National Identity Document (Book and Card)
* Temporary Identity Document
* Birth Certificates
* Passports.

**Note:**  

While the schema attribute names may not be in strict accordance to internationally recognised standards, their primary use will
be in the South African context, and thus by adhering to existing local conventions, it is assumed that this will ease adoption and 
integration.

## Proof-of-Residence Schema

The Proof-of-Residence record is a aggregate record comprised of attributes from a number of other schema and may be represented as 
follows:

* Issuing Organization Name - Legal or Common Name ( see **Organisation**)
* Address - Presented as one of the acceptable forms of Address Schema
* Date Of Issue - Date as present on the statement. (https://en.wikipedia.org/wiki/ISO_8601)


The source schema for these attributes is listed below. 

### Address Schema

A physical location on earth, for the purposes of describing ones **Place-of-Residence**, can be expresed in any of the following ways:

* Physical Address (https://schema.org/address)
* Postal Address (https://schema.org/PostalAddress)
* GeoCoordinates (https://schema.org/GeoCoordinates)
* GeoHash (https://en.wikipedia.org/wiki/Geohash)

### Organization Schema

The following schema defines a complete Organization record, although only select attributes will be used in the presentation of a 
_Proof-of-Residence_ credential.

* Organization (https://schema.org/Organization)

