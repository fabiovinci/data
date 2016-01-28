
# Spatial Representation Type

**Purpose**

The method used to spatially represent geographic information.

**Test method**

Test if a spatialRepresentationType value is used from an appropriate codelist. The values of MD_SpatialRepresentationTypeCode in the scope of the INSPIRE Directive are: vector, grid or tin.

Grab the resource and check the spatial representation. Validate if it matches the advertised representation.

    <gmd:spatialRepresentationType>
      <gmd:MD_SpatialRepresentationTypeCode
         codeList="http://standards.iso.org/ittf/PubliclyAvailableStandards/ISO_19139_Schemas/resources/codelist/gmxCodelists.xml#MD_SpatialRepresentationTypeCode"
         codeListValue="vector" />
    </gmd:spatialRepresentationType>

**Reference(s)**	 

* [IR IOP AMD](./README.md#ref_IR_IOP_AMD), Art 13 - 6

**Test type:** Automated

**Notes**

**Contextual XPath references**

The namespace prefixes used as described in [README.md](./README.md#namespaces).

Abbreviation                                   |  XPath expression (relative to gmd:MD_Metadata)
-----------------------------------------------| -------------------------------------------------------------------------
<a name="codeList"></a> codeList   | gmd:identificationInfo/gmd:MD_DataIdentification/gmd:spatialRepresentationType/gmd:MD_SpatialRepresentationTypeCode@codeList
<a name="codeListValue"></a> codeListValue   | gmd:identificationInfo/gmd:MD_DataIdentification/gmd:spatialRepresentationType/gmd:MD_SpatialRepresentationTypeCode@codeListValue
