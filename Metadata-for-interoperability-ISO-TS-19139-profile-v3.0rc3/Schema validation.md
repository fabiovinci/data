# Schema validation

**Purpose**: Performs a schema validation of the document.

**Test method**

Document shall pass schema validation without errors, using one of the following XML schema definitions:

To Validate XML against ISO AP 1.0:
* http://schemas.opengis.net/csw/2.0.2/profiles/apiso/1.0.0/apiso.xsd

To Validate XML against ISO 19139 version 2005-DIS with GML 3.2.0:
* http://schemas.opengis.net/iso/19139/20060504/gmd/gmd.xsd

To Validate XML against ISO/TS 19139:2007 with GML 3.2.1:
* http://standards.iso.org/ittf/PubliclyAvailableStandards/ISO_19139_Schemas/gmd/gmd.xsd or
http://schemas.opengis.net/iso/19139/20070417/gmd/gmd.xsd

**References**	 

* [TG MD](README.md#ref_TG_MD) 2.1.2
* [TG_DS_TMPL](./README.md#ref_TG_DS_TMPL), TG requirement 3

**Test type:** Automated

**Notes**

## Contextual XPath references

The namespace prefixes used as described in [README.md](README.md#namespaces).

Abbreviation                                               |  XPath expression
---------------------------------------------------------- | -------------------------------------------------------------------------
