<h1 id="ProductGroup">ProductGroup</h1>

Type: rdf:Class

Definition: A grouping of trade products.

Unique UN Assigned ID: UN01011922

Dictionary Entry Name: Trade_ Product Group. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="ProductGroupIncludedTradeLineItem">ProductGroupIncludedTradeLineItem</span> | [edi3:SupplyChainTradeLineItem](#SupplyChainTradeLineItem) | A supply chain trade line item which is included in this trade product group. | UN01011925 | Trade_ Product Group. Included. Supply Chain_ Trade Line Item
<span id="ProductGroupName">ProductGroupName</span> | xsd:string | The name, expressed as text, for this trade product group. | UN01011924 | Trade_ Product Group. Name. Text


<h1 id="FinancialInstitutionAddress">FinancialInstitutionAddress</h1>

Type: rdf:Class

Definition: The location at which a financial institution may be found or reached.

Unique UN Assigned ID: UN01003173

Dictionary Entry Name: Financial Institution_ Address. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="FinancialInstitutionAddressPostOfficeBox">FinancialInstitutionAddressPostOfficeBox</span> | xsd:string | The post office box, expressed as text, for this financial institution address. | UN01004892 | Financial Institution_ Address. Post Office Box. Text
<span id="FinancialInstitutionAddressBuildingNumber">FinancialInstitutionAddressBuildingNumber</span> | xsd:string | The number, expressed as text, of the building on a street for this financial institution address. | UN01003181 | Financial Institution_ Address. Building Number. Text
<span id="FinancialInstitutionAddressPostcode">FinancialInstitutionAddressPostcode</span> | xsd:token | The code specifying the postcode for this financial institution address. | UN01003182 | Financial Institution_ Address. Postcode. Code
<span id="FinancialInstitutionAddressCountrySubDivisionName">FinancialInstitutionAddressCountrySubDivisionName</span> | xsd:string | The name, expressed as text, of a country sub-division within this financial institution address. | UN01004894 | Financial Institution_ Address. Country Sub-Division Name. Text
<span id="FinancialInstitutionAddressLineFive">FinancialInstitutionAddressLineFive</span> | xsd:string | The fifth free form line, expressed as text, of this financial institution address. | UN01003179 | Financial Institution_ Address. Line Five. Text
<span id="FinancialInstitutionAddressLineOne">FinancialInstitutionAddressLineOne</span> | xsd:string | The first free form line, expressed as text, of this financial institution address. | UN01003175 | Financial Institution_ Address. Line One. Text
<span id="FinancialInstitutionAddressCountryName">FinancialInstitutionAddressCountryName</span> | xsd:string | The name, expressed as text, of the country within this financial institution address. | UN01004895 | Financial Institution_ Address. Country Name. Text
<span id="FinancialInstitutionAddressLineFour">FinancialInstitutionAddressLineFour</span> | xsd:string | The fourth free form line, expressed as text, of this financial institution address. | UN01003178 | Financial Institution_ Address. Line Four. Text
<span id="FinancialInstitutionAddressStreetName">FinancialInstitutionAddressStreetName</span> | xsd:string | The name, expressed as text, of the street or thoroughfare for this financial institution address. | UN01003180 | Financial Institution_ Address. Street Name. Text
<span id="FinancialInstitutionAddressLineTwo">FinancialInstitutionAddressLineTwo</span> | xsd:string | The second free form line, expressed as text, of this financial institution address. | UN01003176 | Financial Institution_ Address. Line Two. Text
<span id="FinancialInstitutionAddressCityID">FinancialInstitutionAddressCityID</span> | xsd:token | The unique identifier of the city for this financial institution address, such as United Nations Location Code (UNLOCODE). | UN01004893 | Financial Institution_ Address. City. Identifier
<span id="FinancialInstitutionAddressCityName">FinancialInstitutionAddressCityName</span> | xsd:string | The name, expressed as text, of the city, town or village of this financial institution address. | UN01003183 | Financial Institution_ Address. City Name. Text
<span id="FinancialInstitutionAddressDepartmentName">FinancialInstitutionAddressDepartmentName</span> | xsd:string | The name, expressed as text, of a department within this financial institution address. | UN01004891 | Financial Institution_ Address. Department Name. Text
<span id="FinancialInstitutionAddressTypeCode">FinancialInstitutionAddressTypeCode</span> | xsd:token | The code specifying the type of financial institution address. | UN01003174 | Financial Institution_ Address. Type. Code
<span id="FinancialInstitutionAddressCountrySubDivisionCode">FinancialInstitutionAddressCountrySubDivisionCode</span> | xsd:token | The unique identifier of a country sub-division for this financial institution address (Reference ISO 3166 and UN/ECE Rec 3). | UN01003184 | Financial Institution_ Address. Country Sub-Division. Identifier
<span id="FinancialInstitutionAddressCountryCode">FinancialInstitutionAddressCountryCode</span> | xsd:token | The unique identifier of a country for this financial institution address (Reference ISO 3166 and UN/ECE Rec 3). | UN01003185 | Financial Institution_ Address. Country. Identifier


<h1 id="TradeAddress">TradeAddress</h1>

Type: rdf:Class

Definition: The location at which a particular trade related organization or person may be found or reached.

Unique UN Assigned ID: UN01004533

Dictionary Entry Name: Trade_ Address. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="TradeAddressID">TradeAddressID</span> | xsd:token | A unique identifier for this trade address. | UN01004534 | Trade_ Address. Identification. Identifier
<span id="TradeAddressLineTwo">TradeAddressLineTwo</span> | xsd:string | The second free form line, expressed as text, of this trade address. | UN01004539 | Trade_ Address. Line Two. Text
<span id="CitySubDivisionText">CitySubDivisionText</span> | xsd:string | A name, expressed as text, of a sub-division of a city for this trade address, for example a district or borough. | UN01004545 | Trade_ Address. City Sub-Division Name. Text
<span id="AttentionOf">AttentionOf</span> | xsd:string | The name, expressed as text, of a person or department in the organization to whom incoming mail is marked with words such as 'for the attention of' or 'FAO' or 'ATTN' for this trade address. | UN01004550 | Trade_ Address. Attention Of. Text
<span id="BuildingName">BuildingName</span> | xsd:string | The name, expressed as text, of a building, a house or other structure on a street at this trade address. | UN01004537 | Trade_ Address. Building Name. Text
<span id="TradeAddressLineOne">TradeAddressLineOne</span> | xsd:string | The first free form line, expressed as text, of this trade address. | UN01004538 | Trade_ Address. Line One. Text
<span id="TradeAddressPostcode">TradeAddressPostcode</span> | xsd:token | A code specifying the postcode of this trade address. | UN01004535 | Trade_ Address. Postcode. Code
<span id="TradeAddressLineFive">TradeAddressLineFive</span> | xsd:string | The fifth free form line, expressed as text, of this trade address. | UN01004542 | Trade_ Address. Line Five. Text
<span id="TradeAddressLineThree">TradeAddressLineThree</span> | xsd:string | The third free form line, expressed as text, of this trade address. | UN01004540 | Trade_ Address. Line Three. Text
<span id="CareOf">CareOf</span> | xsd:string | The name, expressed as text, of a person or organization at this trade address to whom incoming mail is marked with words such as 'care of' or 'C/O'. | UN01004551 | Trade_ Address. Care Of. Text
<span id="TradeAddressCityName">TradeAddressCityName</span> | xsd:string | The name, expressed as text, of the city, town or village of this trade address. | UN01004544 | Trade_ Address. City Name. Text
<span id="TradeAddressPostOfficeBox">TradeAddressPostOfficeBox</span> | xsd:string | The unique identifier, expressed as text, of a container commonly referred to as a box, in a post office or other postal service location, assigned to a person or organization, where postal items may be kept for this trade address. | UN01004536 | Trade_ Address. Post Office Box. Text
<span id="TradeAddressCountryName">TradeAddressCountryName</span> | xsd:string | A name, expressed as text, of the country for this trade address. | UN01004547 | Trade_ Address. Country Name. Text
<span id="TradeAddressCountrySubDivisionCode">TradeAddressCountrySubDivisionCode</span> | xsd:token | A unique identifier of the country sub-division for this trade address. | UN01004548 | Trade_ Address. Country Sub-Division. Identifier
<span id="AdditionalStreetName">AdditionalStreetName</span> | xsd:string | The additional name of a street, expressed as text, for this trade address. | UN01008282 | Trade_ Address. Additional_ Street Name. Text
<span id="TradeAddressStreetName">TradeAddressStreetName</span> | xsd:string | A name, expressed as text, of a street or thoroughfare for this trade address. | UN01004543 | Trade_ Address. Street Name. Text
<span id="TradeAddressCountryCode">TradeAddressCountryCode</span> | xsd:token | The unique identifier of a country for this trade address. | UN01004546 | Trade_ Address. Country. Identifier
<span id="TradeAddressDepartmentName">TradeAddressDepartmentName</span> | xsd:string | The name, expressed as text, of a department for this trade address. | UN01006206 | Trade_ Address. Department Name. Text
<span id="TradeAddressLineFour">TradeAddressLineFour</span> | xsd:string | The fourth free form line, expressed as text, of this trade address. | UN01004541 | Trade_ Address. Line Four. Text
<span id="TradeAddressTypeCode">TradeAddressTypeCode</span> | xsd:token | A code specifying the type of this trade address, such as business address or home address. | UN01013131 | Trade_ Address. Type. Code
<span id="TradeGeographicalCoordinate">TradeGeographicalCoordinate</span> | [edi3:GeographicalCoordinate](#GeographicalCoordinate) | An identification of a set of geographical coordinates for this trade address. | UN01004553 | Trade_ Address. Geo-Coordinate Identification. Geographical Coordinate
<span id="TradeAddressCountrySubDivisionName">TradeAddressCountrySubDivisionName</span> | xsd:string | A name, expressed as text, of the sub-division of a country for this trade address. | UN01004549 | Trade_ Address. Country Sub-Division Name. Text
<span id="TradeAddressBuildingNumber">TradeAddressBuildingNumber</span> | xsd:string | The building number, expressed as text, in this trade address. | UN01006053 | Trade_ Address. Building Number. Text


<h1 id="BirthAddress">BirthAddress</h1>

Type: rdf:Class

Definition: The place of birth.

Unique UN Assigned ID: UN01003169

Dictionary Entry Name: Birth_ Address. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="BirthAddressCityName">BirthAddressCityName</span> | xsd:string | The name, expressed as text, of the city, town or village of this birth address. | UN01003171 | Birth_ Address. City Name. Text
<span id="BirthAddressCountrySubDivisionName">BirthAddressCountrySubDivisionName</span> | xsd:string | The name, expressed as text, of the sub-division of a country for this birth address. | UN01003170 | Birth_ Address. Country Sub-Division Name. Text


<h1 id="Query">Query</h1>

Type: rdf:Class

Definition: A formally raised question or request for information about this specification.

Unique UN Assigned ID: UN01000073

Dictionary Entry Name: Specification_ Query. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="QueryTypeCode">QueryTypeCode</span> | xsd:token | The code specifying the type of specification query. | UN01000075 | Specification_ Query. Type. Code
<span id="QueryContentText">QueryContentText</span> | xsd:string | The content, expressed as text, of this specification query. | UN01000076 | Specification_ Query. Content. Text


<h1 id="Product">Product</h1>

Type: rdf:Class

Definition: A reference to a product or service produced by human or mechanical effort or by a natural process for trading purposes.

Unique UN Assigned ID: UN01004027

Dictionary Entry Name: Referenced_ Product. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="ProductGlobalID">ProductGlobalID</span> | xsd:token | A unique global identifier for this referenced product. | UN01004029 | Referenced_ Product. Global_ Identification. Identifier
<span id="ProductBuyerAssignedID">ProductBuyerAssignedID</span> | xsd:token | The unique buyer assigned identifier for this referenced product. | UN01004031 | Referenced_ Product. Buyer Assigned_ Identification. Identifier
<span id="ProductName">ProductName</span> | xsd:string | A name, expressed as text, for this referenced product. | UN01004034 | Referenced_ Product. Name. Text
<span id="ProductUnitQuantity">ProductUnitQuantity</span> | xsd:decimal | A unit quantity of this referenced product. | UN01007191 | Referenced_ Product. Unit. Quantity
<span id="ProductManufacturerAssignedID">ProductManufacturerAssignedID</span> | xsd:token | A unique manufacturer assigned identifier for this referenced product. | UN01004032 | Referenced_ Product. Manufacturer Assigned_ Identification. Identifier
<span id="ProductRelationshipTypeCode">ProductRelationshipTypeCode</span> | xsd:token | A code specifying a type of relationship for this referenced product. | UN01007190 | Referenced_ Product. Relationship_ Type. Code
<span id="ProductSellerAssignedID">ProductSellerAssignedID</span> | xsd:token | The unique seller assigned identifier for this referenced product. | UN01004030 | Referenced_ Product. Seller Assigned_ Identification. Identifier
<span id="ProductID">ProductID</span> | xsd:token | A unique identifier for this referenced product. | UN01004028 | Referenced_ Product. Identification. Identifier
<span id="ProductDescription">ProductDescription</span> | xsd:string | A textual description for this referenced product. | UN01007189 | Referenced_ Product. Description. Text


<h1 id="TradeProduct">TradeProduct</h1>

Type: rdf:Class

Definition: Any tangible output or service produced by human or mechanical effort or by a natural process for trade purposes.

Unique UN Assigned ID: UN01004679

Dictionary Entry Name: Trade_ Product. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="TradeProductAdditionalDescription">TradeProductAdditionalDescription</span> | xsd:string | An additional textual description for this trade product. | UN01007253 | Trade_ Product. Additional_ Description. Text
<span id="RecyclingTypeCode">RecyclingTypeCode</span> | xsd:token | The code specifying the type of recycling for this trade product. | UN01007264 | Trade_ Product. Recycling_ Type. Code
<span id="TrackingSystemID">TrackingSystemID</span> | xsd:token | An identifier for a tracking system of this trade product. | UN01007241 | Trade_ Product. Tracking System. Identifier
<span id="TradeProductManufacturerAssignedID">TradeProductManufacturerAssignedID</span> | xsd:token | A unique manufacturer assigned identifier for this trade product. | UN01004684 | Trade_ Product. Manufacturer Assigned_ Identification. Identifier
<span id="DesignationText">DesignationText</span> | xsd:string | A designation, expressed as text, for this trade product. | UN01008537 | Trade_ Product. Designation. Text
<span id="ConciseDescription">ConciseDescription</span> | xsd:string | A concise textual description for this trade product, such as the description used on a shelf or printed on a receipt. | UN01007251 | Trade_ Product. Concise_ Description. Text
<span id="SuppliedFromCountry">SuppliedFromCountry</span> | [edi3:Country](#Country) | A country of supply for this trade product. | UN01004704 | Trade_ Product. Supplied From. Trade_ Country
<span id="TradeProductID">TradeProductID</span> | xsd:token | A unique identifier for this trade product. | UN01004680 | Trade_ Product. Identification. Identifier
<span id="UseDescription">UseDescription</span> | xsd:string | A textual description of a use of this trade product. | UN01007250 | Trade_ Product. Use_ Description. Text
<span id="IntendedUseText">IntendedUseText</span> | xsd:string | An intended use, expressed as text, for this trade product. | UN01006190 | Trade_ Product. Intended_ Use. Text
<span id="TradeProductAdditionalDocument">TradeProductAdditionalDocument</span> | [edi3:Document](#Document) | An additional referenced document for this trade product, such as a manual or a certificate. | UN01007274 | Trade_ Product. Additional_ Reference. Referenced_ Document
<span id="TradeProductNetVolume">TradeProductNetVolume</span> | xsd:decimal | A measure of a net volume for this trade product. | UN01005377 | Trade_ Product. Net Volume. Measure
<span id="TradeProductDescription">TradeProductDescription</span> | xsd:string | A textual description for this trade product. | UN01004689 | Trade_ Product. Description. Text
<span id="FinalAssemblyCountry">FinalAssemblyCountry</span> | [edi3:Country](#Country) | A final assembly country for this trade product. | UN01007271 | Trade_ Product. Final_ Assembly. Trade_ Country
<span id="InspectionDocument">InspectionDocument</span> | [edi3:Document](#Document) | A referenced inspection document for this trade product. | UN01004702 | Trade_ Product. Inspection_ Reference. Referenced_ Document
<span id="TradeTradeProductGroupID">TradeTradeProductGroupID</span> | xsd:token | A unique identifier for a product group for this trade product. | UN01005376 | Trade_ Product. Product Group. Identifier
<span id="TradeProductMaterialGoodsCharacteristic">TradeProductMaterialGoodsCharacteristic</span> | [edi3:GoodsCharacteristic](#GoodsCharacteristic) | A material goods characteristic applicable to this trade product. | UN01004695 | Trade_ Product. Applicable. Material_ Goods Characteristic
<span id="ModelName">ModelName</span> | xsd:string | The model name, expressed as text, for this trade product. | UN01008523 | Trade_ Product. Model_ Name. Text
<span id="LatestProductDataChangeFormattedDateTime">LatestProductDataChangeFormattedDateTime</span> | xsd:dateTime | The formatted date, time, date time, or other date time value of the latest change in the product data for this trade product. | UN01011529 | Trade_ Product. Formatted Latest_ Product Data Change. Date Time
<span id="EndItemTypeCode">EndItemTypeCode</span> | xsd:token | A code specifying a type of end item for this trade product. | UN01005385 | Trade_ Product. End Item_ Type. Code
<span id="TradeProductDangerousGoods">TradeProductDangerousGoods</span> | [edi3:DangerousGoods](#DangerousGoods) | Transport dangerous goods information applicable for this trade product. | UN01007280 | Trade_ Product. Applicable. Transport_ Dangerous Goods
<span id="MSDSDocument">MSDSDocument</span> | [edi3:Document](#Document) | A Material Safety Data Sheet (MSDS) document referenced for this product. | UN01007273 | Trade_ Product. MSDS_ Reference. Referenced_ Document
<span id="VariantDescription">VariantDescription</span> | xsd:string | A textual description of a variant of this trade product. | UN01007252 | Trade_ Product. Variant_ Description. Text
<span id="LegalRightsOwner">LegalRightsOwner</span> | [edi3:TradeParty](#TradeParty) | The party that owns the legal rights for this trade product. | UN01007276 | Trade_ Product. Legal Rights Owner. Trade_ Party
<span id="ContentUnitQuantity">ContentUnitQuantity</span> | xsd:decimal | The number of content units of this trade product. | UN01007266 | Trade_ Product. Content_ Unit. Quantity
<span id="IncludedProductContentUnitQuantity">IncludedProductContentUnitQuantity</span> | xsd:decimal | The number of content units of products included in this trade product. | UN01007269 | Trade_ Product. Included Product Content_ Unit. Quantity
<span id="TradeProductGrossVolume">TradeProductGrossVolume</span> | xsd:decimal | A measure of the gross volume for this trade product. | UN01005382 | Trade_ Product. Gross Volume. Measure
<span id="TradeProductTypeCode">TradeProductTypeCode</span> | xsd:token | A code specifying the type of trade product. | UN01004690 | Trade_ Product. Type. Code
<span id="UltimateCustomerAssignedExtensionID">UltimateCustomerAssignedExtensionID</span> | xsd:token | An ultimate customer assigned extension identifier for this trade product. | UN01013467 | Trade_ Product. Ultimate Customer Assigned Extension_ Identification. Identifier
<span id="PrePackagedIndicator">PrePackagedIndicator</span> | xsd:boolean | The indication of whether or not this trade product is pre-packaged. | UN01007261 | Trade_ Product. Pre-Packaged. Indicator
<span id="BrandRangeName">BrandRangeName</span> | xsd:string | The brand range name, expressed as text, for this trade product. | UN01008522 | Trade_ Product. Brand Range_ Name. Text
<span id="SerialNumberMarkedIndicator">SerialNumberMarkedIndicator</span> | xsd:boolean | The indication of whether or not this trade product is marked with a serial number. | UN01007260 | Trade_ Product. Marked_ Serial Number. Indicator
<span id="IncludedProduct">IncludedProduct</span> | [edi3:Product](#Product) | An included product referenced from this trade product. | UN01007282 | Trade_ Product. Included. Referenced_ Product
<span id="TradeProductBuyerAssignedID">TradeProductBuyerAssignedID</span> | xsd:token | The unique buyer assigned identifier for this trade product. | UN01004683 | Trade_ Product. Buyer Assigned_ Identification. Identifier
<span id="TradeProductCommonName">TradeProductCommonName</span> | xsd:string | A common name, expressed as text, for this trade product. | UN01006143 | Trade_ Product. Common_ Name. Text
<span id="CustomerAssignedID">CustomerAssignedID</span> | xsd:token | A unique customer assigned identifier for this trade product. | UN01005387 | Trade_ Product. Customer Assigned_ Identification. Identifier
<span id="InnerPackQuantity">InnerPackQuantity</span> | xsd:decimal | The number of inner packs of this trade product. | UN01007268 | Trade_ Product. Inner Pack. Quantity
<span id="Packaging">Packaging</span> | [edi3:Packaging](#Packaging) | Packaging applicable for use with this trade product. | UN01004700 | Trade_ Product. Applicable. Supply Chain_ Packaging
<span id="BrandName">BrandName</span> | xsd:string | The brand name, expressed as text, for this trade product. | UN01007255 | Trade_ Product. Brand_ Name. Text
<span id="TradeProductOriginCountry">TradeProductOriginCountry</span> | [edi3:Country](#Country) | A country of origin for this trade product. | UN01004703 | Trade_ Product. Origin. Trade_ Country
<span id="TradeProductSeasonCode">TradeProductSeasonCode</span> | xsd:token | A code specifying a season for this trade product. | UN01008538 | Trade_ Product. Season. Code
<span id="MarketingProductFeature">MarketingProductFeature</span> | [edi3:Feature](#Feature) | A marketing feature of this trade product. | UN01007279 | Trade_ Product. Marketing. Trade Product_ Feature
<span id="MarketingDescription">MarketingDescription</span> | xsd:string | A marketing description, expressed as text, for this trade product. | UN01008519 | Trade_ Product. Marketing_ Description. Text
<span id="AnnouncedLaunchCancellationFormattedDateTime">AnnouncedLaunchCancellationFormattedDateTime</span> | xsd:dateTime | The formatted date, time, date time, or other date time value of the cancellation of the announced launch of this trade product. | UN01011528 | Trade_ Product. Formatted Cancellation_ Announced Launch. Date Time
<span id="UnitTypeCode">UnitTypeCode</span> | xsd:token | A code specifying a type of unit for this trade product. | UN01007265 | Trade_ Product. Unit_ Type. Code
<span id="FromProductionLifeSpanMeasure">FromProductionLifeSpanMeasure</span> | xsd:decimal | The measure of the life span of this trade product from date of production. | UN01007244 | Trade_ Product. From Production_ Life Span. Measure
<span id="TradeProductManufacturer">TradeProductManufacturer</span> | [edi3:TradeParty](#TradeParty) | A manufacturer party for this trade product. | UN01004708 | Trade_ Product. Manufacturer. Trade_ Party
<span id="CertificationEvidenceDocument">CertificationEvidenceDocument</span> | [edi3:Document](#Document) | A referenced certification evidence document for this trade product. | UN01004701 | Trade_ Product. Certification Evidence_ Reference. Referenced_ Document
<span id="AttachedSecurityTag">AttachedSecurityTag</span> | [edi3:SecurityTag](#SecurityTag) | A tag device attached to this trade product to provide protection from a peril such as theft. | UN01007278 | Trade_ Product. Attached. Product_ Security Tag
<span id="Characteristic">Characteristic</span> | [edi3:Characteristic](#Characteristic) | A characteristic applicable to this trade product. | UN01004694 | Trade_ Product. Applicable. Product_ Characteristic
<span id="IncludedProductTypeQuantity">IncludedProductTypeQuantity</span> | xsd:decimal | The number of different product types included at the next lower level in this trade product. | UN01007270 | Trade_ Product. Included Product Type. Quantity
<span id="TradeProductMaximumDimensions">TradeProductMaximumDimensions</span> | [edi3:SpatialDimension](#SpatialDimension) | Maximum linear spatial dimensions of this trade product. | UN01004707 | Trade_ Product. Maximum_ Linear. Spatial_ Dimension
<span id="DrainedNetWeight">DrainedNetWeight</span> | xsd:decimal | The measure of the drained net weight (mass) of this trade product. | UN01007257 | Trade_ Product. Drained_ Net Weight. Measure
<span id="TradeProductGlobalID">TradeProductGlobalID</span> | xsd:token | A unique global identifier for this trade product. | UN01004681 | Trade_ Product. Global_ Identification. Identifier
<span id="PresentationBinaryFile">PresentationBinaryFile</span> | [edi3:BinaryFile](#BinaryFile) | A binary file presentation specified for this trade product. | UN01007272 | Trade_ Product. Presentation. Specified_ Binary File
<span id="TradeProductIndustryAssignedID">TradeProductIndustryAssignedID</span> | xsd:token | A unique industry assigned identifier for this product. | UN01004685 | Trade_ Product. Industry Assigned_ Identification. Identifier
<span id="BrandOwner">BrandOwner</span> | [edi3:TradeParty](#TradeParty) | The party that owns the brand of this trade product. | UN01007277 | Trade_ Product. Brand Owner. Trade_ Party
<span id="TradeProductStatusCode">TradeProductStatusCode</span> | xsd:token | A code specifying a status for this trade product. | UN01005375 | Trade_ Product. Status. Code
<span id="ColourDescription">ColourDescription</span> | xsd:string | A textual description of the colour of this trade product. | UN01007263 | Trade_ Product. Colour_ Description. Text
<span id="RegulationConformityID">RegulationConformityID</span> | xsd:token | An identifier assigned to indicate conformity with a regulation or standard for this trade product, such as "CE" which declares that the product conforms with the essential requirements of the applicable EC directives. | UN01009971 | Trade_ Product. Regulation Conformity. Identifier
<span id="InnerPackContentUnitQuantity">InnerPackContentUnitQuantity</span> | xsd:decimal | The number of content units in an inner pack of this trade product. | UN01007267 | Trade_ Product. Inner Pack Content_ Unit. Quantity
<span id="TradeProductNetWeight">TradeProductNetWeight</span> | xsd:decimal | A measure of the net weight (mass) of this trade product. | UN01004691 | Trade_ Product. Net Weight. Measure
<span id="ContentVariableMeasureIndicator">ContentVariableMeasureIndicator</span> | xsd:boolean | The indication of whether or not instances of this trade product have a content variable measure, such as weight, length or volume. | UN01011928 | Trade_ Product. Content_ Variable Measure. Indicator
<span id="PhysicalFormDescription">PhysicalFormDescription</span> | xsd:string | A textual description of the physical form of this trade product. | UN01007254 | Trade_ Product. Physical Form_ Description. Text
<span id="GlobalExtensionID">GlobalExtensionID</span> | xsd:token | A global extension identifier for this trade product, such as a prefix or a suffix. | UN01004912 | Trade_ Product. Global Extension_ Identification. Identifier
<span id="TradeName">TradeName</span> | xsd:string | A trade name, expressed as text, for this trade product. | UN01004688 | Trade_ Product. Trade_ Name. Text
<span id="ProductionDiscontinuedDateTime">ProductionDiscontinuedDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value of the discontinuation of the production of this trade product. | UN01007248 | Trade_ Product. Production Discontinued. Date Time
<span id="ModelID">ModelID</span> | xsd:token | A unique model identifier for this trade product. | UN01004686 | Trade_ Product. Model_ Identification. Identifier
<span id="ManufactureCountry">ManufactureCountry</span> | [edi3:Country](#Country) | The country of manufacture of this trade product. | UN01009048 | Trade_ Product. Manufacture. Trade_ Country
<span id="TradeProductGrossWeight">TradeProductGrossWeight</span> | xsd:decimal | A measure of the gross weight (mass) of this trade product. | UN01004692 | Trade_ Product. Gross Weight. Measure
<span id="TradeProductDimensions">TradeProductDimensions</span> | [edi3:SpatialDimension](#SpatialDimension) | Linear spatial dimensions of this trade product. | UN01004705 | Trade_ Product. Linear. Spatial_ Dimension
<span id="SeasonDescription">SeasonDescription</span> | xsd:string | A season description, expressed as text, for this trade product. | UN01008520 | Trade_ Product. Season_ Description. Text
<span id="Classification">Classification</span> | [edi3:Classification](#Classification) | A product classification designated for this trade product. | UN01004696 | Trade_ Product. Designated. Product_ Classification
<span id="VariableMeasureIndicator">VariableMeasureIndicator</span> | xsd:boolean | The indication of whether or not instances of this trade product have a variable measure, such as weight, length or volume. | UN01007258 | Trade_ Product. Variable Measure. Indicator
<span id="TradeProductName">TradeProductName</span> | xsd:string | A name, expressed as text, for this trade product. | UN01004687 | Trade_ Product. Name. Text
<span id="MarketingCampaignDocument">MarketingCampaignDocument</span> | [edi3:Document](#Document) | A referenced marketing campaign document for this trade product. | UN01007275 | Trade_ Product. Marketing Campaign_ Reference. Referenced_ Document
<span id="SubBrandName">SubBrandName</span> | xsd:string | The sub-brand name, expressed as text, for this trade product. | UN01007256 | Trade_ Product. Sub-Brand_ Name. Text
<span id="GeneticModificationExtentCode">GeneticModificationExtentCode</span> | xsd:token | The code specifying the extent of a genetic modification to this trade product. | UN01004693 | Trade_ Product. Genetic Modification Extent. Code
<span id="StorageInformation">StorageInformation</span> | [edi3:Note](#Note) | A storage information note for this trade product. | UN01009050 | Trade_ Product. Storage_ Information. Note
<span id="FromOpeningLifeSpanMeasure">FromOpeningLifeSpanMeasure</span> | xsd:decimal | The measure of the life span of this trade product from date of opening. | UN01007245 | Trade_ Product. From Opening_ Life Span. Measure
<span id="ConfigurableIndicator">ConfigurableIndicator</span> | xsd:boolean | The indication of whether or not this trade product is configurable. | UN01007259 | Trade_ Product. Configurable. Indicator
<span id="BuyerSuppliedPartsReferenceDocument">BuyerSuppliedPartsReferenceDocument</span> | [edi3:Document](#Document) | A buyer supplier parts document referenced for this trade product. | UN01012684 | Trade_ Product. Buyer Supplied Parts_ Reference. Referenced_ Document
<span id="TransportInformation">TransportInformation</span> | [edi3:Note](#Note) | A transport information note for this trade product. | UN01009051 | Trade_ Product. Transport_ Information. Note
<span id="TradeProductDisposalInstructions">TradeProductDisposalInstructions</span> | [edi3:DisposalInstructions](#DisposalInstructions) | Disposal instructions applicable to this trade product. | UN01008515 | Trade_ Product. Applicable. Disposal_ Instructions
<span id="TradeKeyword">TradeKeyword</span> | [edi3:Keyword](#Keyword) | A keyword applicable to this trade product. | UN01007281 | Trade_ Product. Applicable. Keyword
<span id="TradeProductColourCode">TradeProductColourCode</span> | xsd:token | The code specifying the colour for this trade product. | UN01007262 | Trade_ Product. Colour. Code
<span id="Certification">Certification</span> | [edi3:Certification](#Certification) | A certification applicable to this trade product. | UN01008539 | Trade_ Product. Applicable. Trade Product_ Certification
<span id="TradeProductScientificName">TradeProductScientificName</span> | xsd:string | A scientific name, expressed as text, for this trade product. | UN01006144 | Trade_ Product. Scientific_ Name. Text
<span id="TradeProductBatchID">TradeProductBatchID</span> | xsd:token | A batch identifier for this trade product. | UN01007243 | Trade_ Product. Batch_ Identification. Identifier
<span id="SecurityInformation">SecurityInformation</span> | [edi3:Note](#Note) | A security information note for this trade product. | UN01009052 | Trade_ Product. Security_ Information. Note
<span id="ConsumerAgeDescription">ConsumerAgeDescription</span> | xsd:string | A consumer age description, expressed as text, for this trade product. | UN01008517 | Trade_ Product. Consumer Age_ Description. Text
<span id="TradeProductSellerAssignedID">TradeProductSellerAssignedID</span> | xsd:token | The unique seller assigned identifier for this trade product. | UN01004682 | Trade_ Product. Seller Assigned_ Identification. Identifier
<span id="SpecifiedProductCertificate">SpecifiedProductCertificate</span> | [edi3:Certificate](#Certificate) | A product certificate specified for this trade product. | UN01013116 | Trade_ Product. Specified. Product_ Certificate
<span id="TradeProductInformationNote">TradeProductInformationNote</span> | [edi3:Note](#Note) | An information note for this trade product. | UN01007283 | Trade_ Product. Information. Note
<span id="ConsumerGenderDescription">ConsumerGenderDescription</span> | xsd:string | A consumer gender description, expressed as text, for this trade product. | UN01008518 | Trade_ Product. Consumer Gender_ Description. Text
<span id="IndividualProductInstance">IndividualProductInstance</span> | [edi3:ProductInstance](#ProductInstance) | An individual instance of this trade product. | UN01004697 | Trade_ Product. Individual. Trade_ Product Instance
<span id="FromDeliveryLifeSpanMeasure">FromDeliveryLifeSpanMeasure</span> | xsd:decimal | The measure of the life span of this trade product from date of delivery. | UN01007246 | Trade_ Product. From Delivery_ Life Span. Measure
<span id="PromotionalVariantID">PromotionalVariantID</span> | xsd:token | The promotional variant identifier for this trade product. | UN01008516 | Trade_ Product. Promotional Variant_ Identification. Identifier
<span id="TradeProductMinimumDimensions">TradeProductMinimumDimensions</span> | [edi3:SpatialDimension](#SpatialDimension) | Minimum linear spatial dimensions of this trade product. | UN01004706 | Trade_ Product. Minimum_ Linear. Spatial_ Dimension
<span id="TradeProductOriginLocation">TradeProductOriginLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | A location of origin for this trade product. | UN01006145 | Trade_ Product. Origin. Logistics_ Location
<span id="ExportIndicator">ExportIndicator</span> | xsd:boolean | The indication of whether or not this trade product is for export. | UN01013368 | Trade_ Product. Export. Indicator
<span id="SizeDescription">SizeDescription</span> | xsd:string | A size description, expressed as text, for this trade product. | UN01008521 | Trade_ Product. Size_ Description. Text
<span id="AreaDensityMeasure">AreaDensityMeasure</span> | xsd:decimal | The measure of the area density, such as paper density 100 gsm, of this trade product. | UN01007247 | Trade_ Product. Area Density. Measure
<span id="EndItemName">EndItemName</span> | xsd:string | An end item name, expressed as text, for this trade product. | UN01005386 | Trade_ Product. End Item_ Name. Text


<h1 id="Fault">Fault</h1>

Type: rdf:Class

Definition: An identified defect or fault.

Unique UN Assigned ID: UN01010065

Dictionary Entry Name: Identified_ Fault. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="IDCode">IDCode</span> | xsd:token | A code specifying an identified fault. | UN01010067 | Identified_ Fault. Identification. Code


<h1 id="FinancingRequestDocument">FinancingRequestDocument</h1>

Type: rdf:Class

Definition: The set of characteristics shared by all individual transactions grouped for this financing request document.

Unique UN Assigned ID: UN01013228

Dictionary Entry Name: Financing Request_ Document. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="IncludedAdditionalInformationNote">IncludedAdditionalInformationNote</span> | [edi3:Note](#Note) | An additional information note included for this financing request document. | UN01013244 | Financing Request_ Document. Additional Information_ Included. Note
<span id="ContractualDocumentClause">ContractualDocumentClause</span> | [edi3:Clause](#Clause) | A contractual document clause specified for this financing request document. | UN01013243 | Financing Request_ Document. Contractual. Document_ Clause
<span id="FinancingRequestDocumentCopyIndicator">FinancingRequestDocumentCopyIndicator</span> | xsd:boolean | The indication of whether or not this financing request document is a copy rather than an original. | UN01013233 | Financing Request_ Document. Copy. Indicator
<span id="FinancingRequestDocumentCurrencyCode">FinancingRequestDocumentCurrencyCode</span> | xsd:token | The code specifying the currency in this financing request document. | UN01013236 | Financing Request_ Document. Currency. Code
<span id="GroupID">GroupID</span> | xsd:token | The group identifier in this financing request document. | UN01013229 | Financing Request_ Document. Group_ Identification. Identifier
<span id="CancellationReasonText">CancellationReasonText</span> | xsd:string | A cancellation reason, expressed as text, in this financing request document. | UN01013235 | Financing Request_ Document. Cancellation Reason. Text
<span id="SpecifiedCancellationStatus">SpecifiedCancellationStatus</span> | [edi3:CancellationStatus](#CancellationStatus) | A status of a cancellation specified for this financing request document, such as accepted. | UN01013241 | Financing Request_ Document. Specified. Cancellation_ Status
<span id="SpecifiedValidationStatus">SpecifiedValidationStatus</span> | [edi3:ValidationStatus](#ValidationStatus) | The status of the validation specified for this financing request document, such as error. | UN01013242 | Financing Request_ Document. Specified. Validation_ Status
<span id="GroupedTransactionTotalAmount">GroupedTransactionTotalAmount</span> | xsd:decimal | A total monetary value of grouped transactions in this financing request document. | UN01013231 | Financing Request_ Document. Grouped Transaction_ Total. Amount
<span id="SpecifiedRequestingParty">SpecifiedRequestingParty</span> | [edi3:RequestingParty](#RequestingParty) | The requesting party specified in this financing request document. | UN01013240 | Financing Request_ Document. Specified. Requesting_ Party
<span id="SpecifiedIntermediaryCreditorFinancialInstitution">SpecifiedIntermediaryCreditorFinancialInstitution</span> | [edi3:CreditorFinancialInstitution](#CreditorFinancialInstitution) | The creditor financial institution specified as the intermediary in this financing request document. | UN01013239 | Financing Request_ Document. Intermediary_ Specified. Creditor_ Financial Institution
<span id="SpecifiedFirstAgentCreditorFinancialInstitution">SpecifiedFirstAgentCreditorFinancialInstitution</span> | [edi3:CreditorFinancialInstitution](#CreditorFinancialInstitution) | The creditor financial institution specified as the first agent in this financing request document. | UN01013238 | Financing Request_ Document. First Agent_ Specified. Creditor_ Financial Institution
<span id="FinancingRequestDocumentCreationDateTime">FinancingRequestDocumentCreationDateTime</span> | xsd:dateTime | The date, time, date time or other date time value for the creation of this financing request document. | UN01013232 | Financing Request_ Document. Creation. Date Time
<span id="AgreementInformation">AgreementInformation</span> | xsd:string | Agreement information, expressed as text, in this financing request document, such as a collection mandate. | UN01013237 | Financing Request_ Document. Agreement_ Information. Text
<span id="GroupedTransactionSpecifiedQuantity">GroupedTransactionSpecifiedQuantity</span> | xsd:decimal | The number of grouped transactions specified in this financing request document. | UN01013230 | Financing Request_ Document. Grouped Transaction_ Specified. Quantity


<h1 id="FinancingRequestResultDocument">FinancingRequestResultDocument</h1>

Type: rdf:Class

Definition: A collection of data that reports the result of a financing request.

Unique UN Assigned ID: UN01013224

Dictionary Entry Name: Financing Request Result_ Document. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="FinancingRequestResultDocumentFinancedTotalAmount">FinancingRequestResultDocumentFinancedTotalAmount</span> | xsd:decimal | A monetary value of the financed total amount in this financing request result document. | UN01013225 | Financing Request Result_ Document. Financed_ Total. Amount
<span id="SpecifiedFinancingStatus">SpecifiedFinancingStatus</span> | [edi3:FinancingStatus](#FinancingStatus) | The financing status specified in this financing request result document. | UN01013227 | Financing Request Result_ Document. Specified. Financing_ Status


<h1 id="FinancingSummaryDocument">FinancingSummaryDocument</h1>

Type: rdf:Class

Definition: A collection of financing related data that provides an overview of key points.

Unique UN Assigned ID: UN01013245

Dictionary Entry Name: Financing Summary_ Document. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="LineOfCreditFinancingFinancialAccount">LineOfCreditFinancingFinancialAccount</span> | [edi3:FinancingFinancialAccount](#FinancingFinancialAccount) | The financing financial account, used for managing the line of credit, specified for this financing summary document. | UN01013251 | Financing Summary_ Document. Line Of Credit_ Specified. Financing_ Financial Account
<span id="FinancingSummaryDocumentFinancedTotalAmount">FinancingSummaryDocumentFinancedTotalAmount</span> | xsd:decimal | A financed total monetary value in this financing summary document. | UN01013248 | Financing Summary_ Document. Financed_ Total. Amount
<span id="RelatedFinancialBooking">RelatedFinancialBooking</span> | [edi3:Booking](#Booking) | The financial booking related to this financing summary document. | UN01013250 | Financing Summary_ Document. Related. Financial_ Booking
<span id="FinancedTransactionSpecifiedQuantity">FinancedTransactionSpecifiedQuantity</span> | xsd:decimal | The number of financed transactions specified in this financing summary document. | UN01013246 | Financing Summary_ Document. Financed Transaction_ Specified. Quantity
<span id="FinancingSummaryDocumentSpecifiedCreditorFinancialAccount">FinancingSummaryDocumentSpecifiedCreditorFinancialAccount</span> | [edi3:CreditorFinancialAccount](#CreditorFinancialAccount) | The creditor financial account, used for crediting, specified for this financing summary document. | UN01013252 | Financing Summary_ Document. Specified. Creditor_ Financial Account
<span id="FinancedAppliedRate">FinancedAppliedRate</span> | xsd:decimal | The financed applied rate, expressed as a percentage, in this financing summary document. | UN01013249 | Financing Summary_ Document. Financed Applied_ Rate. Percent


<h1 id="ExchangedDocument">ExchangedDocument</h1>

Type: rdf:Class

Definition: A collection of data for a piece of written, printed or electronic matter that is exchanged between two or more parties.

Unique UN Assigned ID: UN01002487

Dictionary Entry Name: Exchanged_ Document. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="ExchangedDocumentPurposeCode">ExchangedDocumentPurposeCode</span> | xsd:token | A code specifying the purpose of this exchanged document, such as request or reminder. | UN01003561 | Exchanged_ Document. Purpose. Code
<span id="PurposeText">PurposeText</span> | xsd:string | The purpose, expressed as text, of this exchanged document. | UN01003548 | Exchanged_ Document. Purpose. Text
<span id="Agent">Agent</span> | [edi3:TradeParty](#TradeParty) | A party representing another party for this exchanged document. | UN01003588 | Exchanged_ Document. Agent. Trade_ Party
<span id="ExchangedDocumentSignatoryAuthentication">ExchangedDocumentSignatoryAuthentication</span> | [edi3:Authentication](#Authentication) | A signatory document authentication for this exchanged document. | UN01002499 | Exchanged_ Document. Signatory. Document_ Authentication
<span id="UrgencyText">UrgencyText</span> | xsd:string | An urgency, expressed as text, of this exchanged document. | UN01013352 | Exchanged_ Document. Urgency. Text
<span id="ExchangedDocumentCopyIndicator">ExchangedDocumentCopyIndicator</span> | xsd:boolean | The indication of whether or not this exchanged document is a copy. | UN01002494 | Exchanged_ Document. Copy. Indicator
<span id="ExchangedDocumentGlobalID">ExchangedDocumentGlobalID</span> | xsd:token | The unique global identifier for this exchanged document. | UN01003574 | Exchanged_ Document. Global_ Identification. Identifier
<span id="AmendmentPurposeCode">AmendmentPurposeCode</span> | xsd:token | A code specifying a purpose of an amendment to this exchanged document. | UN01003562 | Exchanged_ Document. Amendment_ Purpose. Code
<span id="CopyIssuedQuantity">CopyIssuedQuantity</span> | xsd:decimal | The number of copies issued of this exchanged document. | UN01003560 | Exchanged_ Document. Copy Issued. Quantity
<span id="ExchangedDocumentLodgementLocation">ExchangedDocumentLodgementLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | The location where this exchanged document has been lodged. | UN01003581 | Exchanged_ Document. Lodgement. Logistics_ Location
<span id="LineCount">LineCount</span> | xsd:decimal | The count of the number of lines in this exchanged document. | UN01003555 | Exchanged_ Document. Line Count. Numeric
<span id="ResponseDateTime">ResponseDateTime</span> | xsd:dateTime | A date, time, date time, or other date time value of a response of the exchanged document. | UN01005277 | Exchanged_ Document. Response. Date Time
<span id="ExchangedDocumentCustomsID">ExchangedDocumentCustomsID</span> | xsd:token | A unique identifier, for customs purposes, for this exchanged document. | UN01003572 | Exchanged_ Document. Customs_ Identification. Identifier
<span id="ExchangedDocumentIssuer">ExchangedDocumentIssuer</span> | [edi3:TradeParty](#TradeParty) | The party that issues this exchanged document. | UN01003589 | Exchanged_ Document. Issuer. Trade_ Party
<span id="ExchangedDocumentCreationDateTime">ExchangedDocumentCreationDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value of a creation of this exchanged document. | UN01012584 | Exchanged_ Document. Creation. Date Time
<span id="ExchangedDocumentVersionID">ExchangedDocumentVersionID</span> | xsd:token | The unique identifier for the version of this exchanged document. | UN01003573 | Exchanged_ Document. Version_ Identification. Identifier
<span id="ExchangedDocumentContractualClause">ExchangedDocumentContractualClause</span> | [edi3:Clause](#Clause) | A contractual clause of this exchanged document. | UN01003582 | Exchanged_ Document. Contractual. Document_ Clause
<span id="ThirdSignatoryAuthentication">ThirdSignatoryAuthentication</span> | [edi3:Authentication](#Authentication) | The third signature, also known as the second counter signature, that has been authenticated on this exchanged document indicating where appropriate the authentication party. | UN01003585 | Exchanged_ Document. Third_ Signatory. Document_ Authentication
<span id="ExchangedDocumentID">ExchangedDocumentID</span> | xsd:token | The unique identifier of this exchanged document. | UN01002488 | Exchanged_ Document. Identification. Identifier
<span id="ExchangedDocumentControlRequirementIndicator">ExchangedDocumentControlRequirementIndicator</span> | xsd:boolean | The indication of whether or not this exchanged document has specific control requirements. | UN01003550 | Exchanged_ Document. Control Requirement. Indicator
<span id="UrgencyCode">UrgencyCode</span> | xsd:token | The code specifying the urgency for this exchanged document. | UN01012960 | Exchanged_ Document. Urgency. Code
<span id="ExchangedDocumentStatusCode">ExchangedDocumentStatusCode</span> | xsd:token | The code specifying the status of this exchanged document. | UN01002492 | Exchanged_ Document. Status. Code
<span id="FirstSignatoryAuthentication">FirstSignatoryAuthentication</span> | [edi3:Authentication](#Authentication) | The first or primary signature that authenticates this exchanged document. | UN01003583 | Exchanged_ Document. First_ Signatory. Document_ Authentication
<span id="ResponseRequestTypeCode">ResponseRequestTypeCode</span> | xsd:token | A code specifying a type of response requested for this exchanged document. | UN01006746 | Exchanged_ Document. Requested_ Response Type. Code
<span id="FourthSignatoryAuthentication">FourthSignatoryAuthentication</span> | [edi3:Authentication](#Authentication) | The fourth signature, also known as the third counter signature, that has been authenticated on this exchanged document indicating where appropriate the authentication party. | UN01003586 | Exchanged_ Document. Fourth_ Signatory. Document_ Authentication
<span id="ExchangedDocumentLanguageCode">ExchangedDocumentLanguageCode</span> | xsd:token | A unique identifier for a language used in this exchanged document. | UN01003554 | Exchanged_ Document. Language. Identifier
<span id="ExchangedDocumentPreviousRevisionID">ExchangedDocumentPreviousRevisionID</span> | xsd:token | The unique identifier of the previous revision of this exchanged document. | UN01003576 | Exchanged_ Document. Previous Revision_ Identification. Identifier
<span id="OffsetProcessingStatusText">OffsetProcessingStatusText</span> | xsd:string | A status of an offset processing, expressed as text, for this exchanged document, such as the process offsetted by this document. | UN01013354 | Exchanged_ Document. Offset Processing_ Status. Text
<span id="RejectionResponseDateTime">RejectionResponseDateTime</span> | xsd:dateTime | A date, time, date time, or other date time value of a rejection response of the exchanged document. | UN01005276 | Exchanged_ Document. Rejection_ Response. Date Time
<span id="ExchangedDocumentIssueDateTime">ExchangedDocumentIssueDateTime</span> | xsd:dateTime | The date, time, date time or other date time value for the issuance of this exchanged document. | UN01002493 | Exchanged_ Document. Issue. Date Time
<span id="OriginalRequiredQuantity">OriginalRequiredQuantity</span> | xsd:decimal | The number of originals required of this exchanged document. | UN01003557 | Exchanged_ Document. Original Required. Quantity
<span id="ExchangedDocumentRevisionID">ExchangedDocumentRevisionID</span> | xsd:token | The unique identifier of the revision of this exchanged document. | UN01003575 | Exchanged_ Document. Revision_ Identification. Identifier
<span id="ExchangedDocumentIssueLocation">ExchangedDocumentIssueLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | The location where this exchanged document has been issued. | UN01003580 | Exchanged_ Document. Issue. Logistics_ Location
<span id="RecipientAssignedID">RecipientAssignedID</span> | xsd:token | A unique recipient assigned identifier for this exchanged document. | UN01003571 | Exchanged_ Document. Recipient Assigned_ Identification. Identifier
<span id="BuyerSignatoryDocumentAuthentication">BuyerSignatoryDocumentAuthentication</span> | [edi3:Authentication](#Authentication) | The buyer signature that authenticates this exchanged document. | UN01013397 | Exchanged_ Document. Buyer_ Signatory. Document_ Authentication
<span id="ExchangedDocumentItemQuantity">ExchangedDocumentItemQuantity</span> | xsd:decimal | The number of line items in this exchanged document. | UN01003568 | Exchanged_ Document. Line_ Item. Quantity
<span id="ExchangedDocumentAcceptanceDateTime">ExchangedDocumentAcceptanceDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value for the acceptance of this exchanged document. | UN01003556 | Exchanged_ Document. Acceptance. Date Time
<span id="ExchangedDocumentRemark">ExchangedDocumentRemark</span> | xsd:string | A remark, expressed as text, regarding this exchanged document. | UN01003553 | Exchanged_ Document. Remarks. Text
<span id="SubmissionDateTime">SubmissionDateTime</span> | xsd:dateTime | The date, time, date time or other date time value for the formal submission of this exchanged document to a receiver by a sender. | UN01003549 | Exchanged_ Document. Submission. Date Time
<span id="ExchangedDocumentRecipient">ExchangedDocumentRecipient</span> | [edi3:TradeParty](#TradeParty) | A trade party that receives this exchanged document. | UN01004889 | Exchanged_ Document. Recipient. Trade_ Party
<span id="ExchangedDocumentCategoryCode">ExchangedDocumentCategoryCode</span> | xsd:token | The code specifying a category for this exchanged document. | UN01004856 | Exchanged_ Document. Category. Code
<span id="ExchangedDocumentNote">ExchangedDocumentNote</span> | [edi3:Note](#Note) | A note included in this exchanged document. | UN01002497 | Exchanged_ Document. Included. Note
<span id="OriginalIssuedQuantity">OriginalIssuedQuantity</span> | xsd:decimal | The number of originals issued of this exchanged document. | UN01003559 | Exchanged_ Document. Original Issued. Quantity
<span id="SecondSignatoryAuthentication">SecondSignatoryAuthentication</span> | [edi3:Authentication](#Authentication) | The second signature, also known as the first counter signature, that has been authenticated on this exchanged document indicating where appropriate the authentication party. | UN01003584 | Exchanged_ Document. Second_ Signatory. Document_ Authentication
<span id="ExchangedDocumentInformation">ExchangedDocumentInformation</span> | xsd:string | Information, expressed as text, for this exchanged document. | UN01003563 | Exchanged_ Document. Information. Text
<span id="ExchangedDocumentSender">ExchangedDocumentSender</span> | [edi3:TradeParty](#TradeParty) | The party that sends this exchanged document. | UN01003587 | Exchanged_ Document. Sender. Trade_ Party
<span id="ExchangedDocumentEffectivePeriod">ExchangedDocumentEffectivePeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The specified period within which this exchanged document is effective. | UN01003578 | Exchanged_ Document. Effective. Specified_ Period
<span id="CopyRequiredQuantity">CopyRequiredQuantity</span> | xsd:decimal | The number of copies required of this exchanged document. | UN01003558 | Exchanged_ Document. Copy Required. Quantity
<span id="ApproverSignatoryDocumentAuthentication">ApproverSignatoryDocumentAuthentication</span> | [edi3:Authentication](#Authentication) | The approver signature that authenticates this exchanged document. | UN01013398 | Exchanged_ Document. Approver_ Signatory. Document_ Authentication
<span id="CancellationDateTime">CancellationDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value of a cancellation of the exchanged document. | UN01005275 | Exchanged_ Document. Cancellation. Date Time
<span id="RevisionDateTime">RevisionDateTime</span> | xsd:dateTime | The date, time, date time or other date time value for the revision of this exchanged document. | UN01003567 | Exchanged_ Document. Revision. Date Time
<span id="SenderAssignedID">SenderAssignedID</span> | xsd:token | A unique sender assigned identifier for this exchanged document. | UN01003570 | Exchanged_ Document. Sender Assigned_ Identification. Identifier
<span id="TraderAssignedID">TraderAssignedID</span> | xsd:token | A unique trader assigned identifier for this exchanged document. | UN01003569 | Exchanged_ Document. Trader Assigned_ Identification. Identifier
<span id="ResponseReasonCode">ResponseReasonCode</span> | xsd:token | A code specifying a response reason for this exchanged document. | UN01006698 | Exchanged_ Document. Response Reason. Code
<span id="ExchangedDocumentTypeCode">ExchangedDocumentTypeCode</span> | xsd:token | The code specifying the type of exchanged document. | UN01002491 | Exchanged_ Document. Type. Code
<span id="ExchangedDocumentReferenceDocument">ExchangedDocumentReferenceDocument</span> | [edi3:Document](#Document) | Other documents referenced by this exchanged document. | UN01002498 | Exchanged_ Document. Reference. Referenced_ Document
<span id="ExchangedDocumentDescription">ExchangedDocumentDescription</span> | xsd:string | A textual description of this exchanged document. | UN01002490 | Exchanged_ Document. Description. Text
<span id="AttachedFile">AttachedFile</span> | [edi3:BinaryFile](#BinaryFile) | A binary file attached to this exchanged document. | UN01006747 | Exchanged_ Document. Attached. Specified_ Binary File


<h1 id="DocumentLineDocument">DocumentLineDocument</h1>

Type: rdf:Class

Definition: A collection of data for a line on a piece of written, printed or electronic matter that provides information or evidence.

Unique UN Assigned ID: UN01003513

Dictionary Entry Name: Document Line_ Document. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="ParentLineID">ParentLineID</span> | xsd:token | The unique identifier of the parent line to this document line. | UN01003516 | Document Line_ Document. Parent_ Line. Identifier
<span id="DocumentLineDocumentSubordinateLineID">DocumentLineDocumentSubordinateLineID</span> | xsd:token | An identifier of a subordinate line of this document line. | UN01013361 | Document Line_ Document. Subordinate Line. Identifier
<span id="DocumentLineAcknowledgementDocument">DocumentLineAcknowledgementDocument</span> | [edi3:AcknowledgementDocument](#AcknowledgementDocument) | The acknowledgement document referenced in this document line. | UN01011478 | Document Line_ Document. Reference. Acknowledgement_ Document
<span id="LatestRevisionDateTime">LatestRevisionDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value for the latest revision of this document line. | UN01007176 | Document Line_ Document. Latest_ Revision. Date Time
<span id="StatusReasonCode">StatusReasonCode</span> | xsd:token | The code specifying the line status reason for this document line. | UN01003518 | Document Line_ Document. Line Status Reason. Code
<span id="DocumentLineDocumentLineID">DocumentLineDocumentLineID</span> | xsd:token | The unique identifier of this document line. | UN01003514 | Document Line_ Document. Line. Identifier
<span id="DocumentLineDocumentID">DocumentLineDocumentID</span> | xsd:token | The identifier of this document line document. | UN01011477 | Document Line_ Document. Identification. Identifier
<span id="DocumentLineDocumentIssueDateTime">DocumentLineDocumentIssueDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value for the issuance of this document line. | UN01012957 | Document Line_ Document. Issue. Date Time
<span id="PublicationDateTime">PublicationDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value of the publication of this document line. | UN01012959 | Document Line_ Document. Publication. Date Time
<span id="BuyerAssignedCategoryCode">BuyerAssignedCategoryCode</span> | xsd:token | The code specifying the category assigned by the buyer for this document line. | UN01013319 | Document Line_ Document. Buyer Assigned_ Category. Code
<span id="DocumentLineDocumentStatusCode">DocumentLineDocumentStatusCode</span> | xsd:token | The code specifying the status of this document line. | UN01003517 | Document Line_ Document. Line Status. Code
<span id="LineStatusReasonText">LineStatusReasonText</span> | xsd:string | A reason, expressed as text, for the line status in this document line. | UN01012958 | Document Line_ Document. Line Status Reason. Text
<span id="DocumentLineDocumentEffectivePeriod">DocumentLineDocumentEffectivePeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The period within which this document line is effective. | UN01007177 | Document Line_ Document. Effective. Specified_ Period
<span id="DocumentLineDocumentNote">DocumentLineDocumentNote</span> | [edi3:Note](#Note) | A note included in this document line. | UN01003519 | Document Line_ Document. Included. Note


<h1 id="Document">Document</h1>

Type: rdf:Class

Definition: Written, printed or electronic matter that is referenced.

Unique UN Assigned ID: UN01001569

Dictionary Entry Name: Referenced_ Document. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="DocumentLanguageCode">DocumentLanguageCode</span> | xsd:token | An identifier for a language used in this referenced document. | UN01008989 | Referenced_ Document. Language. Identifier
<span id="DocumentCategoryCode">DocumentCategoryCode</span> | xsd:token | The code specifying the category of this referenced document. | UN01004013 | Referenced_ Document. Category. Code
<span id="DocumentTypeCode">DocumentTypeCode</span> | xsd:token | The code specifying the type of referenced document. | UN01001577 | Referenced_ Document. Type. Code
<span id="DocumentStatusCode">DocumentStatusCode</span> | xsd:token | The code specifying the status for this referenced document. | UN01001573 | Referenced_ Document. Status. Code
<span id="DocumentIssueLocation">DocumentIssueLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | The logistics related location where this referenced document has been issued. | UN01004018 | Referenced_ Document. Issue. Logistics_ Location
<span id="DocumentLineID">DocumentLineID</span> | xsd:token | The unique identifier of a line in this referenced document. | UN01001575 | Referenced_ Document. Line. Identifier
<span id="DocumentRelationshipTypeCode">DocumentRelationshipTypeCode</span> | xsd:token | The code specifying the type of relationship between this referenced document and another artefact, such as a replacement of an original document. | UN01002527 | Referenced_ Document. Relationship Type. Code
<span id="ElectronicPresentationIndicator">ElectronicPresentationIndicator</span> | xsd:boolean | The indication of whether or not this referenced document is presented in an electronic format. | UN01004010 | Referenced_ Document. Electronic Presentation. Indicator
<span id="DocumentRemark">DocumentRemark</span> | xsd:string | A remark, expressed as text, regarding this referenced document. | UN01003999 | Referenced_ Document. Remarks. Text
<span id="DocumentInformation">DocumentInformation</span> | xsd:string | Information, expressed as text, for this referenced document. | UN01004008 | Referenced_ Document. Information. Text
<span id="DocumentSender">DocumentSender</span> | [edi3:TradeParty](#TradeParty) | The trade related party that sends this referenced document. | UN01010568 | Referenced_ Document. Sender. Trade_ Party
<span id="DocumentFormattedIssueDateTime">DocumentFormattedIssueDateTime</span> | xsd:dateTime | The formatted date or date time for the issuance of this referenced document. | UN01011525 | Referenced_ Document. Formatted_ Issue. Date Time
<span id="DocumentLodgementLocation">DocumentLodgementLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | The logistics related location where this referenced document has been lodged. | UN01004019 | Referenced_ Document. Lodgement. Logistics_ Location
<span id="DocumentPreviousRevisionID">DocumentPreviousRevisionID</span> | xsd:token | An identifier for a previous revision of this referenced document. | UN01009018 | Referenced_ Document. Previous Revision_ Identification. Identifier
<span id="DocumentGlobalID">DocumentGlobalID</span> | xsd:token | A unique global identifier for this referenced document. | UN01003992 | Referenced_ Document. Global_ Identification. Identifier
<span id="AcceptablePeriod">AcceptablePeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The specified period within which this referenced document may be accepted. | UN01004015 | Referenced_ Document. Acceptable. Specified_ Period
<span id="IncludedAmount">IncludedAmount</span> | xsd:decimal | A monetary value included in this referenced document. | UN01013310 | Referenced_ Document. Included. Amount
<span id="DocumentSignatoryAuthentication">DocumentSignatoryAuthentication</span> | [edi3:Authentication](#Authentication) | A signatory authentication for this referenced document. | UN01004021 | Referenced_ Document. Signatory. Document_ Authentication
<span id="DocumentURI">DocumentURI</span> | xsd:token | The unique Uniform Resource Identifier (URI) for this referenced document. | UN01001571 | Referenced_ Document. URI_ Identification. Identifier
<span id="ReferenceTypeCode">ReferenceTypeCode</span> | xsd:token | The code specifying the reference type of this referenced document. | UN01006036 | Referenced_ Document. Reference_ Type. Code
<span id="DocumentEffectivePeriod">DocumentEffectivePeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The specified period within which this referenced document is effective. | UN01004014 | Referenced_ Document. Effective. Specified_ Period
<span id="IssuerAssignedID">IssuerAssignedID</span> | xsd:token | The unique issuer assigned identifier for this referenced document. | UN01001570 | Referenced_ Document. Issuer Assigned_ Identification. Identifier
<span id="DocumentCopyIndicator">DocumentCopyIndicator</span> | xsd:boolean | The indication of whether or not the referenced document is a copy. | UN01001574 | Referenced_ Document. Copy. Indicator
<span id="DocumentProprietaryTypeText">DocumentProprietaryTypeText</span> | xsd:string | A proprietary type, expressed as text, for this referenced document. | UN01013290 | Referenced_ Document. Proprietary_ Type. Text
<span id="SpecifiedStatus">SpecifiedStatus</span> | [edi3:DocumentStatus](#DocumentStatus) | Status information specified for this referenced document. | UN01013179 | Referenced_ Document. Specified. Document_ Status
<span id="DocumentAcceptanceDateTime">DocumentAcceptanceDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value of the acceptance of this referenced document. | UN01004001 | Referenced_ Document. Acceptance. Date Time
<span id="DocumentIssuer">DocumentIssuer</span> | [edi3:TradeParty](#TradeParty) | The trade related party that issues this referenced document. | UN01004016 | Referenced_ Document. Issuer. Trade_ Party
<span id="AttachedBinaryObject">AttachedBinaryObject</span> | xsd:base64Binary | A binary object that is attached or otherwise appended to this referenced document. | UN01003996 | Referenced_ Document. Attachment. Binary Object
<span id="DocumentRevisionID">DocumentRevisionID</span> | xsd:token | A unique identifier for a revision of this referenced document. | UN01003993 | Referenced_ Document. Revision_ Identification. Identifier
<span id="AttachedBinaryFile">AttachedBinaryFile</span> | [edi3:BinaryFile](#BinaryFile) | A specified binary file attached to this referenced document. | UN01006029 | Referenced_ Document. Attached. Specified_ Binary File
<span id="DocumentID">DocumentID</span> | xsd:token | A unique identifier for this referenced document. | UN01003991 | Referenced_ Document. Identification. Identifier
<span id="DocumentReferenceDateTime">DocumentReferenceDateTime</span> | xsd:dateTime | The reference date or date time for this referenced document. | UN01013289 | Referenced_ Document. Reference. Date Time
<span id="IncludedNote">IncludedNote</span> | [edi3:Note](#Note) | A note included in this referenced document. | UN01012756 | Referenced_ Document. Included. Note
<span id="PageID">PageID</span> | xsd:token | The identifier of the page for this referenced document. | UN01012755 | Referenced_ Document. Page. Identifier
<span id="DocumentContractualClause">DocumentContractualClause</span> | [edi3:Clause](#Clause) | A contractual clause of this referenced document. | UN01004020 | Referenced_ Document. Contractual. Document_ Clause
<span id="DocumentRecipient">DocumentRecipient</span> | [edi3:TradeParty](#TradeParty) | A trade related party that receives this referenced document. | UN01004017 | Referenced_ Document. Recipient. Trade_ Party
<span id="SectionName">SectionName</span> | xsd:string | A section name, expressed as text, for this referenced document. | UN01007188 | Referenced_ Document. Section Name. Text
<span id="DocumentName">DocumentName</span> | xsd:string | A name, expressed as text, for this referenced document. | UN01003994 | Referenced_ Document. Name. Text
<span id="ReceiptDateTime">ReceiptDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value for the formal receipt of this referenced document. | UN01003995 | Referenced_ Document. Receipt. Date Time
<span id="AuthenticatedOriginalIndicator">AuthenticatedOriginalIndicator</span> | xsd:boolean | The indication of whether or not this referenced document is an authenticated original. | UN01004009 | Referenced_ Document. Authenticated Original. Indicator


<h1 id="AcknowledgementDocument">AcknowledgementDocument</h1>

Type: rdf:Class

Definition: A document exchanged between parties for a business application level acknowledgement of the receipt of information.

Unique UN Assigned ID: UN01002071

Dictionary Entry Name: Acknowledgement_ Document. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="AcknowledgementDocumentID">AcknowledgementDocumentID</span> | xsd:token | The unique identifier of this acknowledgement document. | UN01002073 | Acknowledgement_ Document. Identification. Identifier
<span id="AcknowledgementDocumentTypeCode">AcknowledgementDocumentTypeCode</span> | xsd:token | A code specifying a type of acknowledgement document. | UN01002105 | Acknowledgement_ Document. Type. Code
<span id="AcknowledgementDocumentStatusCode">AcknowledgementDocumentStatusCode</span> | xsd:token | A code specifying a status for this acknowledgement document. | UN01002112 | Acknowledgement_ Document. Status. Code
<span id="ReportSubmissionDateTime">ReportSubmissionDateTime</span> | xsd:dateTime | The date, time, date time or other date time value of the submission of the report being acknowledged by this acknowledgment document. | UN01002108 | Acknowledgement_ Document. Report_ Submission. Date Time
<span id="MultipleReferencesIndicator">MultipleReferencesIndicator</span> | xsd:boolean | The indication of whether or not this acknowledgement document has multiple references. | UN01002072 | Acknowledgement_ Document. Multiple References. Indicator
<span id="AcknowledgementDocumentCreationDateTime">AcknowledgementDocumentCreationDateTime</span> | xsd:dateTime | The date or date time value of the creation of this acknowledgement document. | UN01002111 | Acknowledgement_ Document. Creation. Date Time
<span id="AcknowledgementDocumentIssueDateTime">AcknowledgementDocumentIssueDateTime</span> | xsd:dateTime | The date, time, date time or other date time value for the issuance of this acknowledgement document. | UN01002107 | Acknowledgement_ Document. Issue. Date Time
<span id="ReportReceiptDateTime">ReportReceiptDateTime</span> | xsd:dateTime | The date, time, date time or other date time value of the receipt of the report being acknowledged by this acknowledgment document. | UN01002109 | Acknowledgement_ Document. Report_ Receipt. Date Time
<span id="AcknowledgementDocumentReasonInformationText">AcknowledgementDocumentReasonInformationText</span> | xsd:string | Reason information, expressed as text, for this acknowledgement document. | UN01002649 | Acknowledgement_ Document. Reason_ Information. Text
<span id="AcknowledgementDocumentControlRequirementIndicator">AcknowledgementDocumentControlRequirementIndicator</span> | xsd:boolean | The indication of whether or not this acknowledgement document has a control requirement. | UN01002110 | Acknowledgement_ Document. Control Requirement. Indicator
<span id="AcknowledgementStatusCode">AcknowledgementStatusCode</span> | xsd:token | A code specifying an acknowledgment status for this acknowledgement document. | UN01002113 | Acknowledgement_ Document. Acknowledgement_ Status. Code
<span id="AcknowledgementDocumentName">AcknowledgementDocumentName</span> | xsd:string | The name, expressed as text, for this acknowledgement document. | UN01002106 | Acknowledgement_ Document. Name. Text
<span id="AcknowledgementDocumentReferenceDocument">AcknowledgementDocumentReferenceDocument</span> | [edi3:Document](#Document) | A document referenced by this acknowledgement document. | UN01002650 | Acknowledgement_ Document. Reference. Referenced_ Document


<h1 id="GeographicalSurface">GeographicalSurface</h1>

Type: rdf:Class

Definition: A figure on the Earth having only two dimensions (reference ISO 19136).

Unique UN Assigned ID: UN01012199

Dictionary Entry Name: Specified_ Geographical Surface. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="GeographicalSurfacePolygon">GeographicalSurfacePolygon</span> | [edi3:Polygon](#Polygon) | The polygon included in this geographical surface. | UN01012201 | Specified_ Geographical Surface. Included. Specified_ Polygon


<h1 id="Feature">Feature</h1>

Type: rdf:Class

Definition: Distinctive or characteristic parts of a trade product.

Unique UN Assigned ID: UN01007470

Dictionary Entry Name: Trade Product_ Feature. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="MarketingMeasure">MarketingMeasure</span> | xsd:decimal | A marketing measure for this trade product feature. | UN01007476 | Trade Product_ Feature. Marketing. Measure
<span id="FeatureName">FeatureName</span> | xsd:string | A name, expressed as text, for this trade product feature. | UN01007473 | Trade Product_ Feature. Name. Text
<span id="MarketingPhrase">MarketingPhrase</span> | xsd:string | A catch phrase, expressed as text, for marketing of this trade product feature. | UN01007475 | Trade Product_ Feature. Marketing Phrase. Text
<span id="FeatureDescription">FeatureDescription</span> | xsd:string | A textual description of this trade product feature. | UN01007472 | Trade Product_ Feature. Description. Text
<span id="FeatureTypeCode">FeatureTypeCode</span> | xsd:token | The code specifying the type of trade product feature. | UN01007474 | Trade Product_ Feature. Type. Code


<h1 id="GroupedWorkItem">GroupedWorkItem</h1>

Type: rdf:Class

Definition: A grouping of related work items.

Unique UN Assigned ID: UN01000043

Dictionary Entry Name: Grouped_ Work Item. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="GroupedWorkItemRequestedActionCode">GroupedWorkItemRequestedActionCode</span> | xsd:token | A code specifying a requested action for this grouped work item. | UN01007510 | Grouped_ Work Item. Requested Action. Code
<span id="GroupedWorkItemComment">GroupedWorkItemComment</span> | xsd:string | A comment, expressed as text, for this work item group. | UN01000049 | Grouped_ Work Item. Comment. Text
<span id="GroupedWorkItemAlternativeClassificationCode">GroupedWorkItemAlternativeClassificationCode</span> | xsd:token | A code specifying an alternative classification for this work item group. | UN01000046 | Grouped_ Work Item. Alternative_ Classification. Code
<span id="GroupedWorkItemContractualLanguageCode">GroupedWorkItemContractualLanguageCode</span> | xsd:token | The code specifying the contractual language for this grouped work item. | UN01007512 | Grouped_ Work Item. Contractual Language. Code
<span id="GroupedWorkItemID">GroupedWorkItemID</span> | xsd:token | The unique identifier for this work item group. | UN01000044 | Grouped_ Work Item. Identification. Identifier
<span id="GroupedWorkItemIndexText">GroupedWorkItemIndexText</span> | xsd:string | The index, expressed as text, to be used for this grouped work item. | UN01007509 | Grouped_ Work Item. Index. Text
<span id="GroupedWorkItemItemBasicWorkItem">GroupedWorkItemItemBasicWorkItem</span> | [edi3:BasicWorkItem](#BasicWorkItem) | A basic work item within this grouped work item. | UN01007569 | Grouped_ Work Item. Item. Basic_ Work Item
<span id="GroupedWorkItemComplexDescription">GroupedWorkItemComplexDescription</span> | [edi3:ComplexDescription](#ComplexDescription) | An actual complex description for this work item group. | UN01007515 | Grouped_ Work Item. Actual. Work Item_ Complex Description
<span id="GroupedWorkItemTotalQuantity">GroupedWorkItemTotalQuantity</span> | xsd:decimal | The total quantity of this work item group. | UN01000052 | Grouped_ Work Item. Total. Quantity
<span id="GroupedWorkItemPriceListItemID">GroupedWorkItemPriceListItemID</span> | xsd:token | The identifier of a price list item for this grouped work item. | UN01007511 | Grouped_ Work Item. Price List Item_ Identification. Identifier
<span id="BinaryFile">BinaryFile</span> | [edi3:BinaryFile](#BinaryFile) | A specified binary file referenced by this grouped work item. | UN01011538 | Grouped_ Work Item. Referenced. Specified_ Binary File
<span id="ItemGroupedWorkItem">ItemGroupedWorkItem</span> | [edi3:GroupedWorkItem](#GroupedWorkItem) | A grouped work item within this grouped work item. | UN01007568 | Grouped_ Work Item. Item. Grouped_ Work Item
<span id="GroupedWorkItemChangedRecordedStatus">GroupedWorkItemChangedRecordedStatus</span> | [edi3:RecordedStatus](#RecordedStatus) | A changed recorded status for this grouped work item. | UN01007513 | Grouped_ Work Item. Changed. Recorded_ Status
<span id="GroupedWorkItemTypeCode">GroupedWorkItemTypeCode</span> | xsd:token | A code specifying the type of this work item group. | UN01000048 | Grouped_ Work Item. Type. Code
<span id="GroupedWorkItemPrimaryClassificationCode">GroupedWorkItemPrimaryClassificationCode</span> | xsd:token | A code specifying the primary classification for this work item group. | UN01000045 | Grouped_ Work Item. Primary_ Classification. Code


<h1 id="BasicWorkItem">BasicWorkItem</h1>

Type: rdf:Class

Definition: A basic item of work.

Unique UN Assigned ID: UN01000026

Dictionary Entry Name: Basic_ Work Item. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="BasicWorkItemPrimaryClassificationCode">BasicWorkItemPrimaryClassificationCode</span> | xsd:token | A code specifying the primary classification for this basic work item. | UN01000029 | Basic_ Work Item. Primary_ Classification. Code
<span id="CalculatedUnitPrice">CalculatedUnitPrice</span> | [edi3:CalculatedPrice](#CalculatedPrice) | A unit calculated price for this basic work item. | UN01000040 | Basic_ Work Item. Unit. Calculated_ Price
<span id="BasicWorkItemAlternativeClassificationCode">BasicWorkItemAlternativeClassificationCode</span> | xsd:token | A code specifying an alternative classification for this basic work item. | UN01000030 | Basic_ Work Item. Alternative_ Classification. Code
<span id="BasicWorkItemIndexText">BasicWorkItemIndexText</span> | xsd:string | The index, expressed as text, to be used for this basic work item. | UN01007488 | Basic_ Work Item. Index. Text
<span id="BasicWorkItemComment">BasicWorkItemComment</span> | xsd:string | A comment, expressed as text, for this basic work item. | UN01000032 | Basic_ Work Item. Comment. Text
<span id="BasicWorkItemComplexDescription">BasicWorkItemComplexDescription</span> | [edi3:ComplexDescription](#ComplexDescription) | An actual complex description for this basic work item. | UN01000038 | Basic_ Work Item. Actual. Work Item_ Complex Description
<span id="BasicWorkItemID">BasicWorkItemID</span> | xsd:token | The unique identifier for this basic work item. | UN01000027 | Basic_ Work Item. Identification. Identifier
<span id="BasicWorkItemTypeCode">BasicWorkItemTypeCode</span> | xsd:token | A code specifying the type of basic work item. | UN01000031 | Basic_ Work Item. Type. Code
<span id="TotalQuantityAnalysis">TotalQuantityAnalysis</span> | [edi3:QuantityAnalysis](#QuantityAnalysis) | An analysis of the total quantity for this basic work item. | UN01000039 | Basic_ Work Item. Total Quantity. Work Item_ Quantity Analysis
<span id="TotalQuantityClassificationCode">TotalQuantityClassificationCode</span> | xsd:token | The code specifying the classification of the total quantity for this basic work item. | UN01000034 | Basic_ Work Item. Total Quantity Classification. Code
<span id="BasicWorkItemReferencedBinaryFile">BasicWorkItemReferencedBinaryFile</span> | [edi3:BinaryFile](#BinaryFile) | A specified binary file referenced by this basic work item. | UN01011537 | Basic_ Work Item. Referenced. Specified_ Binary File
<span id="CalculatedTotalPrice">CalculatedTotalPrice</span> | [edi3:CalculatedPrice](#CalculatedPrice) | A total calculated price for this basic work item. | UN01000041 | Basic_ Work Item. Total. Calculated_ Price
<span id="BasicWorkItemRequestedActionCode">BasicWorkItemRequestedActionCode</span> | xsd:token | A code specifying a requested action for this basic work item. | UN01007489 | Basic_ Work Item. Requested Action. Code
<span id="BasicWorkItemPriceListItemID">BasicWorkItemPriceListItemID</span> | xsd:token | The unique identifier of a price list item for this basic work item. | UN01007490 | Basic_ Work Item. Price List Item_ Identification. Identifier
<span id="DeprecatedReferenceFileBinaryObject">DeprecatedReferenceFileBinaryObject</span> | xsd:base64Binary | A reference file binary object related to this basic work item. | UN01000037 | Basic_ Work Item. Reference File. Binary Object
<span id="RecordedChangedStatus">RecordedChangedStatus</span> | [edi3:RecordedStatus](#RecordedStatus) | A changed recorded status for this basic work item. | UN01007492 | Basic_ Work Item. Changed. Recorded_ Status
<span id="BasicWorkItemDeprecatedStatusCode">BasicWorkItemDeprecatedStatusCode</span> | xsd:token | A code specifying the status of this basic work item. | UN01000036 | Basic_ Work Item. Status. Code
<span id="ReferenceID">ReferenceID</span> | xsd:token | The unique identifier of another work item referenced by this basic work item. | UN01000028 | Basic_ Work Item. Reference_ Identification. Identifier
<span id="DeprecatedSubordinateBasicWorkItem">DeprecatedSubordinateBasicWorkItem</span> | [edi3:BasicWorkItem](#BasicWorkItem) | A subordinate work item for this basic work item. | UN01000042 | Basic_ Work Item. Subordinate. Basic_ Work Item
<span id="BasicWorkItemContractualLanguageCode">BasicWorkItemContractualLanguageCode</span> | xsd:token | The code specifying the contractual language for this basic work item. | UN01007491 | Basic_ Work Item. Contractual Language. Code
<span id="DeprecatedIndexValue">DeprecatedIndexValue</span> | xsd:string | The index value for this basic work item. | UN01000035 | Basic_ Work Item. Index. Value
<span id="BasicWorkItemItemBasicWorkItem">BasicWorkItemItemBasicWorkItem</span> | [edi3:BasicWorkItem](#BasicWorkItem) | A basic work item in this basic work item. | UN01007567 | Basic_ Work Item. Item. Basic_ Work Item


<h1 id="LineTradeTransaction">LineTradeTransaction</h1>

Type: rdf:Class

Definition: A group of trade line items, trade line agreement, trade line delivery and trade line settlement details.

Unique UN Assigned ID: UN01011824

Dictionary Entry Name: Line_ Trade Transaction. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="TradeDelivery">TradeDelivery</span> | [edi3:LineTradeDelivery](#LineTradeDelivery) | A trade delivery applicable to this line trade transaction. | UN01011826 | Line_ Trade Transaction. Applicable. Line_ Trade Delivery
<span id="LineTradeTransactionTradeProduct">LineTradeTransactionTradeProduct</span> | [edi3:TradeProduct](#TradeProduct) | A trade product included in this line trade transaction. | UN01011827 | Line_ Trade Transaction. Included. Trade_ Product


<h1 id="SupplyChainTradeTransaction">SupplyChainTradeTransaction</h1>

Type: rdf:Class

Definition: A group of supply chain trade line items, trade agreement, trade delivery and trade settlement details.

Unique UN Assigned ID: UN01004475

Dictionary Entry Name: Supply Chain_ Trade Transaction. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="LineItemQuantity">LineItemQuantity</span> | xsd:decimal | The number of line items for this supply chain trade transaction. | UN01004902 | Supply Chain_ Trade Transaction. Line Item. Quantity
<span id="SalesAgentAssignedID">SalesAgentAssignedID</span> | xsd:token | The unique identifier assigned by the sales agent to identify this supply chain trade transaction. | UN01004477 | Supply Chain_ Trade Transaction. Sales Agent Assigned_ Identification. Identifier
<span id="SupplyChainTradeTransactionReferencedDocument">SupplyChainTradeTransactionReferencedDocument</span> | [edi3:Document](#Document) | A referenced document associated with this supply chain trade transaction, such as the purchase order, invoice or packing list. | UN01004481 | Supply Chain_ Trade Transaction. Associated. Referenced_ Document
<span id="SupplyChainTradeTransactionLogisticsPackage">SupplyChainTradeTransactionLogisticsPackage</span> | [edi3:Package](#Package) | A logistics package specified for this supply chain trade transaction. | UN01004485 | Supply Chain_ Trade Transaction. Specified. Logistics_ Package
<span id="ShipmentID">ShipmentID</span> | xsd:token | An identifier, such as the Unique Consignment Reference (UCR), for the shipment which is the subject of this supply chain trade transaction. | UN01013108 | Supply Chain_ Trade Transaction. Shipment_ Identification. Identifier
<span id="SupplyChainHeaderTradeDelivery">SupplyChainHeaderTradeDelivery</span> | [edi3:HeaderTradeDelivery](#HeaderTradeDelivery) | A trade delivery header applicable to this supply chain trade transaction. | UN01011869 | Supply Chain_ Trade Transaction. Applicable. Header_ Trade Delivery
<span id="DocumentURL">DocumentURL</span> | xsd:token | The Uniform Resource Locator (URL) of the web location of the document for this supply chain trade transaction. | UN01013296 | Supply Chain_ Trade Transaction. Document_ URL. Identifier
<span id="SupplyChainTradeTransactionIssueDateTime">SupplyChainTradeTransactionIssueDateTime</span> | xsd:dateTime | The date, time, date time or other date time value for the issuance of this supply chain trade transaction. | UN01013295 | Supply Chain_ Trade Transaction. Issue. Date Time
<span id="SupplyChainTradeTransactionIncludedTradeLineItem">SupplyChainTradeTransactionIncludedTradeLineItem</span> | [edi3:SupplyChainTradeLineItem](#SupplyChainTradeLineItem) | A trade line item included in this supply chain trade transaction. | UN01004480 | Supply Chain_ Trade Transaction. Included. Supply Chain_ Trade Line Item
<span id="AssociatedFinancingRequestResultDocument">AssociatedFinancingRequestResultDocument</span> | [edi3:FinancingRequestResultDocument](#FinancingRequestResultDocument) | The financing request result document associated with this supply chain trade transaction. | UN01013298 | Supply Chain_ Trade Transaction. Associated. Financing Request Result_ Document
<span id="SupplyChainHeaderTradeSettlement">SupplyChainHeaderTradeSettlement</span> | [edi3:HeaderTradeSettlement](#HeaderTradeSettlement) | The trade settlement header applicable to this supply chain trade transaction. | UN01011870 | Supply Chain_ Trade Transaction. Applicable. Header_ Trade Settlement
<span id="SupplyChainTradeTransactionTypeCode">SupplyChainTradeTransactionTypeCode</span> | xsd:token | The code specifying the type of supply chain trade transaction. | UN01004478 | Supply Chain_ Trade Transaction. Type. Code
<span id="SupplyChainTradeTransactionInformation">SupplyChainTradeTransactionInformation</span> | xsd:string | Information, expressed as text, for this supply chain trade transaction. | UN01004479 | Supply Chain_ Trade Transaction. Information. Text
<span id="SupplyChainHeaderTradeAgreement">SupplyChainHeaderTradeAgreement</span> | [edi3:HeaderTradeAgreement](#HeaderTradeAgreement) | A trade agreement header applicable to this supply chain trade transaction, such as payment or delivery terms. | UN01011868 | Supply Chain_ Trade Transaction. Applicable. Header_ Trade Agreement
<span id="ProductGroup">ProductGroup</span> | [edi3:ProductGroup](#ProductGroup) | A product group included in this supply chain trade transaction. | UN01011867 | Supply Chain_ Trade Transaction. Included. Trade_ Product Group
<span id="SenderRecipientSequenceID">SenderRecipientSequenceID</span> | xsd:token | The sender-recipient sequence identifier for this supply chain trade transaction. | UN01013297 | Supply Chain_ Trade Transaction. Sender Recipient Sequence_ Identification. Identifier
<span id="SupplyChainTradeTransactionAssociatedDocumentLine">SupplyChainTradeTransactionAssociatedDocumentLine</span> | [edi3:DocumentLineDocument](#DocumentLineDocument) | The document line associated with this supply chain trade transaction. | UN01008819 | Supply Chain_ Trade Transaction. Associated. Document Line_ Document


<h1 id="ChemicalTreatment">ChemicalTreatment</h1>

Type: rdf:Class

Definition: A process of applying a chemical, physical, or biological agent to an object.

Unique UN Assigned ID: UN01009024

Dictionary Entry Name: Applied_ Chemical Treatment. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="ChemicalTreatmentName">ChemicalTreatmentName</span> | xsd:string | A name, expressed as text, of this applied chemical treatment. | UN01009025 | Applied_ Chemical Treatment. Name. Text
<span id="AppliedPeriod">AppliedPeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | A period during which this chemical treatment is applied. | UN01009030 | Applied_ Chemical Treatment. Applied. Specified_ Period
<span id="ApplicableTemperature">ApplicableTemperature</span> | [edi3:SpecifiedTemperature](#SpecifiedTemperature) | The specified temperature applicable for this applied chemical treatment. | UN01009031 | Applied_ Chemical Treatment. Applicable. Specified_ Temperature
<span id="ResultNote">ResultNote</span> | [edi3:Note](#Note) | The note describing the results of this applied chemical treatment. | UN01009033 | Applied_ Chemical Treatment. Result. Note
<span id="ChemicalTreatmentOccurrenceDateTime">ChemicalTreatmentOccurrenceDateTime</span> | xsd:dateTime | The date time of the occurrence of this applied chemical treatment. | UN01009027 | Applied_ Chemical Treatment. Occurrence. Date Time
<span id="MethodName">MethodName</span> | xsd:string | The name, expressed as text, of the method of this applied chemical treatment. | UN01009026 | Applied_ Chemical Treatment. Method Name. Text
<span id="UsedChemical">UsedChemical</span> | [edi3:Chemical](#Chemical) | A chemical used during this applied chemical treatment. | UN01009029 | Applied_ Chemical Treatment. Used. Distinct_ Chemical
<span id="ChemicalConcentrationMeasure">ChemicalConcentrationMeasure</span> | xsd:decimal | A measure of the chemical concentration of this applied chemical treatment. | UN01009028 | Applied_ Chemical Treatment. Chemical Concentration. Measure


<h1 id="RiskAnalysisResult">RiskAnalysisResult</h1>

Type: rdf:Class

Definition: The result of a logistics risk analysis calculation.

Unique UN Assigned ID: UN01013043

Dictionary Entry Name: Logistics_ Risk Analysis Result. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="TransportEquipmentRiskRelatedCode">TransportEquipmentRiskRelatedCode</span> | xsd:token | A code specifying a transport equipment related risk for this logistics risk analysis result. | UN01013046 | Logistics_ Risk Analysis Result. Transport Equipment Risk_ Related. Code
<span id="RiskAnalysisResultDescription">RiskAnalysisResultDescription</span> | xsd:string | The textual description of this logistics risk analysis result. | UN01013049 | Logistics_ Risk Analysis Result. Description. Text
<span id="RiskAnalysisResultLevelCode">RiskAnalysisResultLevelCode</span> | xsd:token | The code specifying the level for this logistics risk analysis result. | UN01013050 | Logistics_ Risk Analysis Result. Level. Code
<span id="ConsignmentRiskRelatedCode">ConsignmentRiskRelatedCode</span> | xsd:token | A code specifying a consignment related risk for this logistics risk analysis result. | UN01013047 | Logistics_ Risk Analysis Result. Consignment Risk_ Related. Code
<span id="RiskAnalysisResultCategoryCode">RiskAnalysisResultCategoryCode</span> | xsd:token | The code specifying the category for this logistics risk analysis result. | UN01013044 | Logistics_ Risk Analysis Result. Category. Code
<span id="PartyRiskRelatedCode">PartyRiskRelatedCode</span> | xsd:token | A code specifying a party related risk for this logistics risk analysis result. | UN01013048 | Logistics_ Risk Analysis Result. Party Risk_ Related. Code


<h1 id="Classification">Classification</h1>

Type: rdf:Class

Definition: A systematic arrangement of products in classes or categories according to established criteria.

Unique UN Assigned ID: UN01002608

Dictionary Entry Name: Product_ Classification. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="ProductClassCharacteristic">ProductClassCharacteristic</span> | [edi3:Characteristic](#Characteristic) | A product class characteristic for this product classification. | UN01007187 | Product_ Classification. Class. Product_ Characteristic
<span id="ClassificationApplicableReferencedStandard">ClassificationApplicableReferencedStandard</span> | [edi3:Standard](#Standard) | The referenced standard that is applicable to this product classification. | UN01008311 | Product_ Classification. Applicable. Referenced_ Standard
<span id="ClassificationSystemID">ClassificationSystemID</span> | xsd:token | The unique identifier of the classification system for this product classification. | UN01002609 | Product_ Classification. System. Identifier
<span id="ClassCode">ClassCode</span> | xsd:token | The code specifying the class for this product classification. | UN01002611 | Product_ Classification. Class. Code
<span id="ClassName">ClassName</span> | xsd:string | A class name, expressed as text, for this product classification. | UN01002612 | Product_ Classification. Class Name. Text
<span id="SubClassCode">SubClassCode</span> | xsd:token | The code specifying the sub class for this product classification. | UN01003977 | Product_ Classification. Sub_ Class. Code


<h1 id="Accreditation">Accreditation</h1>

Type: rdf:Class

Definition: A certified recognition that provides evidence of a level of competency in a given area, such as certifying a level of skill in a trade.

Unique UN Assigned ID: UN01010056

Dictionary Entry Name: Certified_ Accreditation. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="AccreditationExpiryDateTime">AccreditationExpiryDateTime</span> | xsd:dateTime | The date, time, date time or other date time value when this certified accreditation expires. | UN01010064 | Certified_ Accreditation. Expiry. Date Time
<span id="AuthenticationMethodCode">AuthenticationMethodCode</span> | xsd:token | A code specifying an authentication method for this certified accreditation. | UN01010063 | Certified_ Accreditation. Authentication Method. Code
<span id="AccreditationDescription">AccreditationDescription</span> | xsd:string | The textual description of this certified accreditation. | UN01010061 | Certified_ Accreditation. Description. Text
<span id="AccreditationTypeCode">AccreditationTypeCode</span> | xsd:token | The code specifying the type of this certified accreditation, such as a type of driving license. | UN01010058 | Certified_ Accreditation. Type. Code
<span id="AccreditingBodyName">AccreditingBodyName</span> | xsd:string | The name of the accrediting body, expressed as text, for this certified accreditation. | UN01010060 | Certified_ Accreditation. Accrediting Body Name. Text
<span id="ObtainedDateTime">ObtainedDateTime</span> | xsd:dateTime | The date, time, date time or other date time value when this certified accreditation was obtained. | UN01010059 | Certified_ Accreditation. Obtained. Date Time
<span id="AccreditationID">AccreditationID</span> | xsd:token | An identifier for this certified accreditation. | UN01010062 | Certified_ Accreditation. Identification. Identifier


<h1 id="EmployerIdentity">EmployerIdentity</h1>

Type: rdf:Class

Definition: Identification of a party who pays someone to do work on a regular or contractual basis.

Unique UN Assigned ID: UN01003023

Dictionary Entry Name: Employer_ Identity. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-


<h1 id="PersonIdentity">PersonIdentity</h1>

Type: rdf:Class

Definition: Identification of a person.

Unique UN Assigned ID: UN01013279

Dictionary Entry Name: Person_ Identity. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="AlienRegistrationID">AlienRegistrationID</span> | xsd:token | The alien registration identifier for this person. | UN01013284 | Person_ Identity. Alien Registration_ Identification. Identifier
<span id="PassportID">PassportID</span> | xsd:token | The passport identifier for this person. | UN01013280 | Person_ Identity. Passport_ Identification. Identifier
<span id="SocialSecurityID">SocialSecurityID</span> | xsd:token | The social security identifier for this person. | UN01013281 | Person_ Identity. Social Security_ Identification. Identifier
<span id="DriversLicenceID">DriversLicenceID</span> | xsd:token | The drivers licence identifier for this person. | UN01013283 | Person_ Identity. Drivers Licence_ Identification. Identifier
<span id="PersonIdentitySpecifiedProprietaryIdentity">PersonIdentitySpecifiedProprietaryIdentity</span> | [edi3:ProprietaryIdentity](#ProprietaryIdentity) | A proprietary Identity specified for this person. | UN01013285 | Person_ Identity. Specified. Proprietary_ Identity


<h1 id="ProprietaryIdentity">ProprietaryIdentity</h1>

Type: rdf:Class

Definition: Proprietary information which uniquely identifies a person or organization.

Unique UN Assigned ID: UN01013286

Dictionary Entry Name: Proprietary_ Identity. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="ProprietaryIdentityID">ProprietaryIdentityID</span> | xsd:token | A proprietary identifier. | UN01013287 | Proprietary_ Identity. Identification. Identifier


<h1 id="FinancialIdentity">FinancialIdentity</h1>

Type: rdf:Class

Definition: A financial identification for an organization.

Unique UN Assigned ID: UN01013217

Dictionary Entry Name: Financial_ Identity. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="FinancialIdentityBICID">FinancialIdentityBICID</span> | xsd:token | The Bank Identifier Code (BIC) as defined by ISO 9362 (Banking telecommunication messages, Bank Identifier Codes) for this financial identity. | UN01013218 | Financial_ Identity. BIC_ Identification. Identifier
<span id="BankAssignedID">BankAssignedID</span> | xsd:token | The bank assigned identifier for this financial identity. | UN01013223 | Financial_ Identity. Bank Assigned_ Identification. Identifier
<span id="AgentAssignedCustomerID">AgentAssignedCustomerID</span> | xsd:token | The agent assigned customer identifier for this financial identity. | UN01013222 | Financial_ Identity. Agent Assigned Customer_ Identification. Identifier
<span id="FinancialIdentityCHIPSUniversalID">FinancialIdentityCHIPSUniversalID</span> | xsd:token | The (United States) Clearing House Interbank Payments System (CHIPS) Universal Identification (UID) as assigned by the New York Clearing House for this financial identity. | UN01013221 | Financial_ Identity. CHIPS Universal_ Identification. Identifier
<span id="IBEI">IBEI</span> | xsd:token | The International Business Entity Identifier (IBEI) for this financial identity. | UN01013219 | Financial_ Identity. IBEI_ Identification. Identifier


<h1 id="DocumentStatus">DocumentStatus</h1>

Type: rdf:Class

Definition: The information relevant to a condition related to a document.

Unique UN Assigned ID: UN01013122

Dictionary Entry Name: Document_ Status. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="DocumentStatusReasonText">DocumentStatusReasonText</span> | xsd:string | A reason, expressed as text, for this document status. | UN01013127 | Document_ Status. Reason. Text
<span id="DocumentStatusConditionCode">DocumentStatusConditionCode</span> | xsd:token | The code specifying the condition of this document status. | UN01013125 | Document_ Status. Condition. Code
<span id="DocumentStatusValidityPeriod">DocumentStatusValidityPeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | A specified validity period for this document status. | UN01013129 | Document_ Status. Validity. Specified_ Period
<span id="DocumentStatusInformation">DocumentStatusInformation</span> | xsd:string | Information, expressed as text, for this document status. | UN01013128 | Document_ Status. Information. Text
<span id="DocumentStatusDescription">DocumentStatusDescription</span> | xsd:string | The textual description of this document status. | UN01013123 | Document_ Status. Description. Text
<span id="DocumentStatusReasonCode">DocumentStatusReasonCode</span> | xsd:token | A code specifying a reason for this document status. | UN01013126 | Document_ Status. Reason. Code


<h1 id="CancellationStatus">CancellationStatus</h1>

Type: rdf:Class

Definition: Information relevant to a condition of a cancellation.

Unique UN Assigned ID: UN01013196

Dictionary Entry Name: Cancellation_ Status. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="CancellationStatusConditionCode">CancellationStatusConditionCode</span> | xsd:token | The code specifying the condition of this cancellation status. | UN01013197 | Cancellation_ Status. Condition. Code
<span id="CancellationStatusReasonInformationText">CancellationStatusReasonInformationText</span> | xsd:string | Information, expressed as text, related to the reason for this cancellation status. | UN01013200 | Cancellation_ Status. Reason_ Information. Text
<span id="CancellationStatusReasonText">CancellationStatusReasonText</span> | xsd:string | A reason, expressed as text, for this cancellation status. | UN01013199 | Cancellation_ Status. Reason. Text


<h1 id="ValidationStatus">ValidationStatus</h1>

Type: rdf:Class

Definition: Information relevant to a condition of a validation.

Unique UN Assigned ID: UN01013305

Dictionary Entry Name: Validation_ Status. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="ValidationStatusReasonCode">ValidationStatusReasonCode</span> | xsd:token | The code specifying the reason for this validation status. | UN01013307 | Validation_ Status. Reason. Code
<span id="ValidationStatusConditionCode">ValidationStatusConditionCode</span> | xsd:token | The code specifying the condition of this validation status. | UN01013306 | Validation_ Status. Condition. Code
<span id="ValidationStatusReasonInformationText">ValidationStatusReasonInformationText</span> | xsd:string | Information, expressed as text, related to the reason for this validation status. | UN01013309 | Validation_ Status. Additional_ Reason. Text


<h1 id="LogisticsStatus">LogisticsStatus</h1>

Type: rdf:Class

Definition: The information relevant to a condition or a position related to logistics.

Unique UN Assigned ID: UN01003747

Dictionary Entry Name: Logistics_ Status. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="LogisticsStatusReasonCode">LogisticsStatusReasonCode</span> | xsd:token | A code specifying a reason for this logistics status [UNECE Recommendation 24]. | UN01003751 | Logistics_ Status. Reason. Code
<span id="ReportedDepartureEvent">ReportedDepartureEvent</span> | [edi3:Event](#Event) | A transport departure event reported for this logistics status. | UN01010094 | Logistics_ Status. Departure_ Reported. Transport_ Event
<span id="LogisticsStatusSequenceNumber">LogisticsStatusSequenceNumber</span> | xsd:decimal | The sequence number of this logistics status, such as within a status report. | UN01003753 | Logistics_ Status. Sequence. Numeric
<span id="LogisticsStatusConditionCode">LogisticsStatusConditionCode</span> | xsd:token | The code specifying this logistics status condition [UNECE Recommendation 24]. | UN01003748 | Logistics_ Status. Condition. Code
<span id="LogisticsStatusSpecifiedLocation">LogisticsStatusSpecifiedLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | A location specified for this logistics status. | UN01003755 | Logistics_ Status. Specified. Logistics_ Location
<span id="LogisticsStatusValidityPeriod">LogisticsStatusValidityPeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | A specific validity period for this logistics status. | UN01010092 | Logistics_ Status. Validity. Specified_ Period
<span id="ReportedUnloadingEvent">ReportedUnloadingEvent</span> | [edi3:Event](#Event) | A transport unloading event reported for this logistics status. | UN01010096 | Logistics_ Status. Unloading_ Reported. Transport_ Event
<span id="LogisticsStatusReasonText">LogisticsStatusReasonText</span> | xsd:string | A reason, expressed as text, for this logistics status. | UN01003752 | Logistics_ Status. Reason. Text
<span id="LogisticsStatusDescription">LogisticsStatusDescription</span> | xsd:string | The textual description of this logistics status. | UN01003750 | Logistics_ Status. Description. Text
<span id="LogisticsStatusReferenceDateTime">LogisticsStatusReferenceDateTime</span> | xsd:dateTime | The reference date, time, date time or other date time value for this logistics status. | UN01003749 | Logistics_ Status. Reference. Date Time
<span id="ReportedArrivalEvent">ReportedArrivalEvent</span> | [edi3:Event](#Event) | A transport arrival event reported for this logistics status. | UN01010093 | Logistics_ Status. Arrival_ Reported. Transport_ Event


<h1 id="RecordedStatus">RecordedStatus</h1>

Type: rdf:Class

Definition: Recorded information relevant to a condition or a position of an object.

Unique UN Assigned ID: UN01007516

Dictionary Entry Name: Recorded_ Status. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="ChangedDateTime">ChangedDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value when this recorded status changed. | UN01007519 | Recorded_ Status. Changed. Date Time
<span id="RecordedStatusConditionCode">RecordedStatusConditionCode</span> | xsd:token | The code specifying the condition for this recorded status. | UN01007517 | Recorded_ Status. Condition. Code


<h1 id="FinancingStatus">FinancingStatus</h1>

Type: rdf:Class

Definition: Information relevant to a condition of financing.

Unique UN Assigned ID: UN01013262

Dictionary Entry Name: Financing_ Status. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="FinancingStatusReasonInformationText">FinancingStatusReasonInformationText</span> | xsd:string | Information, expressed as text, related to the reason for this financing status. | UN01013266 | Financing_ Status. Reason_ Information. Text
<span id="FinancingStatusReasonText">FinancingStatusReasonText</span> | xsd:string | A reason, expressed as text, for this financing status. | UN01013265 | Financing_ Status. Reason. Text
<span id="FinancingStatusConditionCode">FinancingStatusConditionCode</span> | xsd:token | The code specifying the condition of this financing status. | UN01013263 | Financing_ Status. Condition. Code


<h1 id="DeliveryAdjustment">DeliveryAdjustment</h1>

Type: rdf:Class

Definition: A correction or modification to reflect actual delivery conditions.

Unique UN Assigned ID: UN01003498

Dictionary Entry Name: Delivery_ Adjustment. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="DeliveryAdjustmentActualQuantity">DeliveryAdjustmentActualQuantity</span> | xsd:decimal | The actual quantity added or subtracted as a result of this delivery adjustment. | UN01003502 | Delivery_ Adjustment. Actual. Quantity
<span id="DeliveryAdjustmentActualAmount">DeliveryAdjustmentActualAmount</span> | xsd:decimal | An actual monetary value added or subtracted as a result of this delivery adjustment. | UN01003501 | Delivery_ Adjustment. Actual. Amount
<span id="DeliveryAdjustmentReasonText">DeliveryAdjustmentReasonText</span> | xsd:string | A reason, expressed as text, for this delivery adjustment. | UN01003500 | Delivery_ Adjustment. Reason. Text
<span id="DeliveryAdjustmentActualDateTime">DeliveryAdjustmentActualDateTime</span> | xsd:dateTime | The actual date, time, date time, or other date time value of this delivery adjustment. | UN01003503 | Delivery_ Adjustment. Actual. Date Time


<h1 id="FinancialAdjustment">FinancialAdjustment</h1>

Type: rdf:Class

Definition: A correction or modification to reflect actual financial conditions.

Unique UN Assigned ID: UN01003594

Dictionary Entry Name: Financial_ Adjustment. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="FinancialAdjustmentActualAmount">FinancialAdjustmentActualAmount</span> | xsd:decimal | An actual monetary value added or subtracted as a result of this financial adjustment. | UN01003597 | Financial_ Adjustment. Actual. Amount
<span id="DirectionCode">DirectionCode</span> | xsd:token | The code specifying whether the financial adjustment must be subtracted or added. | UN01013212 | Financial_ Adjustment. Direction. Code
<span id="FinancialAdjustmentActualQuantity">FinancialAdjustmentActualQuantity</span> | xsd:decimal | The actual quantity added or subtracted as a result of this financial adjustment. | UN01003598 | Financial_ Adjustment. Actual. Quantity
<span id="ClaimRelatedParty">ClaimRelatedParty</span> | [edi3:TradeParty](#TradeParty) | The claim related party for this financial adjustment. | UN01009705 | Financial_ Adjustment. Claim_ Related. Trade_ Party
<span id="FinancialAdjustmentActualDateTime">FinancialAdjustmentActualDateTime</span> | xsd:dateTime | The actual date, time, date time, or other date time value of this financial adjustment. | UN01003599 | Financial_ Adjustment. Actual. Date Time
<span id="FinancialAdjustmentReasonCode">FinancialAdjustmentReasonCode</span> | xsd:token | A code specifying a reason for this financial adjustment. | UN01003595 | Financial_ Adjustment. Reason. Code
<span id="ReferenceInvoiceDocument">ReferenceInvoiceDocument</span> | [edi3:Document](#Document) | The invoice document referenced for this financial adjustment. | UN01009706 | Financial_ Adjustment. Invoice_ Reference. Referenced_ Document


<h1 id="RegulatoryProcedure">RegulatoryProcedure</h1>

Type: rdf:Class

Definition: A set of formal steps to satisfy a cross-border regulation, law or convention.

Unique UN Assigned ID: UN01006147

Dictionary Entry Name: Cross-Border_ Regulatory Procedure. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="RegulatoryProcedurePreviousReferencedDocument">RegulatoryProcedurePreviousReferencedDocument</span> | [edi3:Document](#Document) | A previous document related to this cross-border regulatory procedure. | UN01006175 | Cross-Border_ Regulatory Procedure. Previous. Referenced_ Document
<span id="RegulatoryProcedurePaymentMethodCode">RegulatoryProcedurePaymentMethodCode</span> | xsd:token | The code specifying the payment method for this cross-border regulatory procedure, such as by deferred payment method. | UN01006167 | Cross-Border_ Regulatory Procedure. Payment Method. Code
<span id="ExemptionClaimant">ExemptionClaimant</span> | [edi3:TradeParty](#TradeParty) | A party who claims an exemption from this cross-border regulatory procedure. | UN01006183 | Cross-Border_ Regulatory Procedure. Exemption Claimant. Trade_ Party
<span id="OriginCriteriaText">OriginCriteriaText</span> | xsd:string | The origin criteria, expressed as text, for this cross-border regulatory procedure. | UN01006169 | Cross-Border_ Regulatory Procedure. Origin Criteria. Text
<span id="CertificationBasisText">CertificationBasisText</span> | xsd:string | A basis for a certification, expressed as text, for this cross-border regulatory procedure. | UN01009038 | Cross-Border_ Regulatory Procedure. Certification Basis. Text
<span id="AnnualQuotaQuantity">AnnualQuotaQuantity</span> | xsd:decimal | The annual quota quantity under this cross-border regulatory procedure. | UN01006173 | Cross-Border_ Regulatory Procedure. Annual_ Quota. Quantity
<span id="RegulatoryProcedureExaminationEvent">RegulatoryProcedureExaminationEvent</span> | [edi3:Event](#Event) | An examination event for this cross-border regulatory procedure. | UN01008969 | Cross-Border_ Regulatory Procedure. Examination. Transport_ Event
<span id="TransportMovementTypeCode">TransportMovementTypeCode</span> | xsd:token | A code specifying the transport movement type, such as import, export, transit, for this cross-border regulatory procedure. | UN01008957 | Cross-Border_ Regulatory Procedure. Transport Movement_ Type. Code
<span id="RequiredCertificationTestSpecificationReport">RequiredCertificationTestSpecificationReport</span> | [edi3:TestSpecificationReport](#TestSpecificationReport) | A report of a certification test and its attributes that is required for this cross-border regulatory procedure. | UN01009040 | Cross-Border_ Regulatory Procedure. Required. Certification_ Test Specification Report
<span id="ValuationBasisAmount">ValuationBasisAmount</span> | xsd:decimal | The monetary value of the basis on which the valuation is, or will be, calculated for this cross-border regulatory procedure. | UN01006154 | Cross-Border_ Regulatory Procedure. Valuation Basis. Amount
<span id="RequiredSeal">RequiredSeal</span> | [edi3:Seal](#Seal) | A seal required by this cross-border regulatory procedure. | UN01008970 | Cross-Border_ Regulatory Procedure. Required. Logistics_ Seal
<span id="RegulatoryProcedureControlRequirementIndicator">RegulatoryProcedureControlRequirementIndicator</span> | xsd:boolean | The indication of whether or not a control is required for this cross-border regulatory procedure. | UN01006161 | Cross-Border_ Regulatory Procedure. Control Requirement. Indicator
<span id="RegulatoryProcedureApplicablePeriod">RegulatoryProcedureApplicablePeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | A period applicable to this cross-border regulatory procedure. | UN01008967 | Cross-Border_ Regulatory Procedure. Applicable. Specified_ Period
<span id="DeclarationLodgementLocation">DeclarationLodgementLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | The location at which a declaration has been lodged for this cross-border regulatory procedure. | UN01006178 | Cross-Border_ Regulatory Procedure. Declaration Lodgement. Logistics_ Location
<span id="RegulatoryProcedureAcquisitionDateTime">RegulatoryProcedureAcquisitionDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value of an acquisition for this cross-border regulatory procedure. | UN01006174 | Cross-Border_ Regulatory Procedure. Acquisition. Date Time
<span id="RegulatoryProcedureBorderClearanceInstructions">RegulatoryProcedureBorderClearanceInstructions</span> | [edi3:TransportInstructions](#TransportInstructions) | Border clearance instructions for this cross-border regulatory procedure. | UN01008971 | Cross-Border_ Regulatory Procedure. Border Clearance. Transport_ Instructions
<span id="RegulatoryProcedureTariffQuantity">RegulatoryProcedureTariffQuantity</span> | xsd:decimal | A tariff quantity for this cross-border regulatory procedure. | UN01006156 | Cross-Border_ Regulatory Procedure. Tariff. Quantity
<span id="ExportLicenceControlClassificationID">ExportLicenceControlClassificationID</span> | xsd:token | The identifier of the export licence classification for control purposes relevant to this cross-border regulatory procedure, such as per the Wassenaar agreement concerning trade in weapons and dual-use goods and technologies. | UN01008966 | Cross-Border_ Regulatory Procedure. Export Licence Control Classification. Identifier
<span id="RegulatoryProcedureReportedLogisticsStatus">RegulatoryProcedureReportedLogisticsStatus</span> | [edi3:LogisticsStatus](#LogisticsStatus) | A logistics status reported for this cross-border regulatory procedure. | UN01006182 | Cross-Border_ Regulatory Procedure. Reported. Logistics_ Status
<span id="TransactionNatureCode">TransactionNatureCode</span> | xsd:token | A code specifying the nature of a transaction for this cross-border regulatory procedure. | UN01006153 | Cross-Border_ Regulatory Procedure. Transaction Nature. Code
<span id="RegulatoryProcedureReferencedDocument">RegulatoryProcedureReferencedDocument</span> | [edi3:Document](#Document) | A document referenced by this cross-border regulatory procedure. | UN01006176 | Cross-Border_ Regulatory Procedure. Referenced. Referenced_ Document
<span id="RegulatoryProcedureTotalChargeAmount">RegulatoryProcedureTotalChargeAmount</span> | xsd:decimal | A monetary value of the total charges, including tariff and non-tariff charges, for this cross-border regulatory procedure. | UN01006164 | Cross-Border_ Regulatory Procedure. Total Charge. Amount
<span id="RegulatoryProcedureTradeTax">RegulatoryProcedureTradeTax</span> | [edi3:TradeTax](#TradeTax) | A tax, levy or duty applicable to this cross-border regulatory procedure. | UN01006177 | Cross-Border_ Regulatory Procedure. Applicable. Trade_ Tax
<span id="RegulatoryProcedureGuaranteeText">RegulatoryProcedureGuaranteeText</span> | xsd:string | The undertaking, expressed as text, given in cash, bond or as a written guarantee to ensure that an obligation will be fulfilled for this cross-border regulatory procedure. | UN01006152 | Cross-Border_ Regulatory Procedure. Guarantee. Text
<span id="RegisteredDeferredPaymentPayerID">RegisteredDeferredPaymentPayerID</span> | xsd:token | The identifier of the registered deferred payment payer for this cross-border regulatory procedure. | UN01008964 | Cross-Border_ Regulatory Procedure. Registered Deferred Payment Payer. Identifier
<span id="TransitReleaseCustomsOfficeLocation">TransitReleaseCustomsOfficeLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | A location of a specified customs office at which the goods which are subject to this cross-border regulatory procedure are released from a customs transit regime. | UN01008977 | Cross-Border_ Regulatory Procedure. Transit Release Customs Office_ Specified. Logistics_ Location
<span id="ExitCustomsOfficeLocation">ExitCustomsOfficeLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | The location of the specified customs office at which the goods which are subject to this cross-border regulatory procedure leave the customs territory of destination. | UN01008973 | Cross-Border_ Regulatory Procedure. Exit Customs Office_ Specified. Logistics_ Location
<span id="ResponsibleAgencyInvolvementCode">ResponsibleAgencyInvolvementCode</span> | xsd:token | A code specifying a responsible agency involved in this cross-border regulatory procedure. | UN01008959 | Cross-Border_ Regulatory Procedure. Responsible Agency Involvement. Code
<span id="DeclarantAssignedDeclarationID">DeclarantAssignedDeclarationID</span> | xsd:token | The declarant assigned identifier of a declaration for this cross-border regulatory procedure. | UN01006159 | Cross-Border_ Regulatory Procedure. Declarant Assigned Declaration. Identifier
<span id="TotalConsignmentValueAmount">TotalConsignmentValueAmount</span> | xsd:decimal | The total monetary value for a consignment for this cross-border regulatory procedure. | UN01006155 | Cross-Border_ Regulatory Procedure. Total Consignment Value. Amount
<span id="RegulatoryProcedureRemark">RegulatoryProcedureRemark</span> | xsd:string | A remark, expressed as text, for this cross-border regulatory procedure. | UN01006165 | Cross-Border_ Regulatory Procedure. Remark. Text
<span id="TariffAmount">TariffAmount</span> | xsd:decimal | A monetary value of a tariff for this cross-border regulatory procedure. | UN01006162 | Cross-Border_ Regulatory Procedure. Tariff. Amount
<span id="RegulatoryProcedureStatement">RegulatoryProcedureStatement</span> | [edi3:Note](#Note) | A statement note for this cross-border regulatory procedure. | UN01006180 | Cross-Border_ Regulatory Procedure. Statement. Note
<span id="EntryCustomsOfficeLocation">EntryCustomsOfficeLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | The location of the specified customs office at which the goods subject to this cross-border regulatory procedure, enter the customs territory of entry. | UN01008972 | Cross-Border_ Regulatory Procedure. Entry Customs Office_ Specified. Logistics_ Location
<span id="AppliedRequiredChemicalTreatment">AppliedRequiredChemicalTreatment</span> | [edi3:ChemicalTreatment](#ChemicalTreatment) | A chemical treatment applied as required by this cross-border regulatory procedure. | UN01009039 | Cross-Border_ Regulatory Procedure. Required. Applied_ Chemical Treatment
<span id="CrossBorderDebtorFinancialAccount">CrossBorderDebtorFinancialAccount</span> | [edi3:DebtorFinancialAccount](#DebtorFinancialAccount) | A debtor financial account specified for this cross-border regulatory procedure. | UN01006181 | Cross-Border_ Regulatory Procedure. Specified. Debtor_ Financial Account
<span id="ImmediatePayableTotalChargeAmount">ImmediatePayableTotalChargeAmount</span> | xsd:decimal | A monetary value of the total charges, including tariff and non-tariff charges, immediately payable for this cross-border regulatory procedure. | UN01008961 | Cross-Border_ Regulatory Procedure. Immediate Payable_ Total Charge. Amount
<span id="ExportCustomsOfficeLocation">ExportCustomsOfficeLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | The location of the specified customs office which is responsible for export formalities for the goods which are subject to this cross-border regulatory procedure. | UN01008975 | Cross-Border_ Regulatory Procedure. Export Customs Office_ Specified. Logistics_ Location
<span id="PerformanceDateTime">PerformanceDateTime</span> | xsd:dateTime | A date, time, date time, or other date time value on which this cross-border regulatory procedure was, or will be, performed. | UN01006158 | Cross-Border_ Regulatory Procedure. Performance. Date Time
<span id="ImportCustomsOfficeLocation">ImportCustomsOfficeLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | The location of the specified customs office which is responsible for import formalities for the goods which are subject to this cross-border regulatory procedure. | UN01008974 | Cross-Border_ Regulatory Procedure. Import Customs Office_ Specified. Logistics_ Location
<span id="TreatmentEvent">TreatmentEvent</span> | [edi3:Event](#Event) | A treatment event for this cross-border regulatory procedure. | UN01008968 | Cross-Border_ Regulatory Procedure. Treatment. Transport_ Event
<span id="QuotaID">QuotaID</span> | xsd:token | A quota identifier for this cross-border regulatory procedure. | UN01006166 | Cross-Border_ Regulatory Procedure. Quota. Identifier
<span id="ConsignmentDestinationLocation">ConsignmentDestinationLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | A consignment destination location specified for this cross-border regulatory procedure. | UN01006184 | Cross-Border_ Regulatory Procedure. Consignment Destination_ Specified. Logistics_ Location
<span id="RequestOverrideCode">RequestOverrideCode</span> | xsd:token | A code specifying a request, including a reason, to override previously submitted information for this cross-border regulatory procedure, such as due to an error condition. | UN01006150 | Cross-Border_ Regulatory Procedure. Request Override. Code
<span id="ResponsibleAgencyCode">ResponsibleAgencyCode</span> | xsd:token | The code specifying the agency responsible for this cross-border regulatory procedure. | UN01008958 | Cross-Border_ Regulatory Procedure. Responsible Agency. Code
<span id="DeprecatedCustomsProcedure">DeprecatedCustomsProcedure</span> | [edi3:CrossBorderCustomsProcedure](#CrossBorderCustomsProcedure) | A customs procedure specified for this cross-border regulatory procedure. | UN01006186 | Cross-Border_ Regulatory Procedure. Specified. Cross-Border_ Customs Procedure
<span id="TransitCustomsOfficeLocation">TransitCustomsOfficeLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | A location of a specified customs office which is responsible for transit formalities en route for the goods which are subject to this cross-border regulatory procedure. | UN01008976 | Cross-Border_ Regulatory Procedure. Transit Customs Office_ Specified. Logistics_ Location
<span id="RegulatoryProcedureApplicableCurrencyExchange">RegulatoryProcedureApplicableCurrencyExchange</span> | [edi3:CurrencyExchange](#CurrencyExchange) | The applicable currency exchange for this cross-border regulatory procedure. | UN01006185 | Cross-Border_ Regulatory Procedure. Applicable. Trade_ Currency Exchange
<span id="UsedToDateQuotaQuantity">UsedToDateQuotaQuantity</span> | xsd:decimal | The quantity of the quota used to date under this cross-border regulatory procedure. | UN01006172 | Cross-Border_ Regulatory Procedure. Used To Date_ Quota. Quantity
<span id="RegulatoryProcedureCategoryCode">RegulatoryProcedureCategoryCode</span> | xsd:token | A code specifying a category for this cross-border regulatory procedure, such as the appendices of the CITES Convention. | UN01006171 | Cross-Border_ Regulatory Procedure. Category. Code
<span id="NonTariffChargeAmount">NonTariffChargeAmount</span> | xsd:decimal | A monetary value of all non-tariff charges for this cross-border regulatory procedure. | UN01006163 | Cross-Border_ Regulatory Procedure. Non-Tariff Charge. Amount
<span id="ControlResultText">ControlResultText</span> | xsd:string | A control result, expressed as text, for this cross-border regulatory procedure. | UN01006168 | Cross-Border_ Regulatory Procedure. Control Result. Text
<span id="AmendmentReasonCode">AmendmentReasonCode</span> | xsd:token | A code specifying a reason for an amendment to this cross-border regulatory procedure. | UN01006170 | Cross-Border_ Regulatory Procedure. Amendment Reason. Code
<span id="RegulatoryProcedureTypeCode">RegulatoryProcedureTypeCode</span> | xsd:token | A code specifying a type of cross-border regulatory procedure. | UN01006148 | Cross-Border_ Regulatory Procedure. Type. Code
<span id="DeferredPaymentMethodIndicator">DeferredPaymentMethodIndicator</span> | xsd:boolean | The indication of whether or not the deferred payment method is applicable to this cross-border regulatory procedure. | UN01008963 | Cross-Border_ Regulatory Procedure. Deferred Payment Method. Indicator
<span id="RegulatoryProcedureTariffDeductionQuantity">RegulatoryProcedureTariffDeductionQuantity</span> | xsd:decimal | A quantity to be deducted from the tariff quantity for this cross-border regulatory procedure. | UN01006157 | Cross-Border_ Regulatory Procedure. Tariff Deduction. Quantity
<span id="PreviousProcedureTypeCode">PreviousProcedureTypeCode</span> | xsd:token | A code specifying a type of previous procedure for this cross-border regulatory procedure. | UN01006149 | Cross-Border_ Regulatory Procedure. Previous Procedure Type. Code
<span id="ResponsibleAgencyActionCode">ResponsibleAgencyActionCode</span> | xsd:token | A code specifying an action for a responsible agency in this cross-border regulatory procedure. | UN01008960 | Cross-Border_ Regulatory Procedure. Responsible Agency Action. Code
<span id="RegulatoryProcedureGuaranteeCode">RegulatoryProcedureGuaranteeCode</span> | xsd:token | The code specifying an undertaking given in cash, bond or as a written guarantee to ensure that an obligation will be fulfilled for this cross-border regulatory procedure. | UN01006151 | Cross-Border_ Regulatory Procedure. Guarantee. Code
<span id="GoodsStatusCode">GoodsStatusCode</span> | xsd:token | The code specifying the goods status for this cross-border regulatory procedure. | UN01008965 | Cross-Border_ Regulatory Procedure. Goods Status. Code
<span id="PaymentOfficeLocation">PaymentOfficeLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | The location of an office at which a payment relevant to this cross-border regulatory procedure is made. | UN01006179 | Cross-Border_ Regulatory Procedure. Payment Office. Logistics_ Location
<span id="ControlStartDateConfirmationIndicator">ControlStartDateConfirmationIndicator</span> | xsd:boolean | The indication of whether or not the start date of a control has been confirmed for this cross-border regulatory procedure. | UN01006160 | Cross-Border_ Regulatory Procedure. Control Start Date Confirmation. Indicator


<h1 id="InstalmentPlan">InstalmentPlan</h1>

Type: rdf:Class

Definition: A plan for paying a total sum of money by several payments made over a period of time.

Unique UN Assigned ID: UN01013277

Dictionary Entry Name: Payment_ Instalment Plan. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-


<h1 id="QuarantineInstructions">QuarantineInstructions</h1>

Type: rdf:Class

Definition: Instructions for a period of imposed isolation or detention.

Unique UN Assigned ID: UN01003988

Dictionary Entry Name: Quarantine_ Instructions. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="QuarantineInstructionsDescription">QuarantineInstructionsDescription</span> | xsd:string | The textual description of these quarantine instructions. | UN01003989 | Quarantine_ Instructions. Description. Text


<h1 id="HaulageInstructions">HaulageInstructions</h1>

Type: rdf:Class

Definition: Instructions related to the action or process of conveyance.

Unique UN Assigned ID: UN01003634

Dictionary Entry Name: Haulage_ Instructions. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="HaulageInstructionsDescription">HaulageInstructionsDescription</span> | xsd:string | The textual description of these haulage instructions. | UN01003635 | Haulage_ Instructions. Description. Text


<h1 id="HandlingInstructions">HandlingInstructions</h1>

Type: rdf:Class

Definition: Handling information of an instructive nature.

Unique UN Assigned ID: UN01003625

Dictionary Entry Name: Handling_ Instructions. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="HandlingInstructionsHandlingCode">HandlingInstructionsHandlingCode</span> | xsd:token | A code specifying these handling instructions. | UN01003626 | Handling_ Instructions. Handling. Code
<span id="MaximumStorageHumidity">MaximumStorageHumidity</span> | xsd:decimal | The measure of the maximum storage humidity applicable to these handling instructions. | UN01008431 | Handling_ Instructions. Maximum Storage Humidity_ Applicable. Measure
<span id="HandlingInstructionsMaximumStackabilityWeight">HandlingInstructionsMaximumStackabilityWeight</span> | xsd:decimal | The maximum stackability weight applicable to these handling instructions. | UN01007178 | Handling_ Instructions. Maximum Stackability Weight_ Applicable. Measure
<span id="MinimumStorageHumidity">MinimumStorageHumidity</span> | xsd:decimal | The measure of the minimum storage humidity applicable to these handling instructions. | UN01008432 | Handling_ Instructions. Minimum Storage Humidity_ Applicable. Measure
<span id="HandlingInstructionsProcedureText">HandlingInstructionsProcedureText</span> | xsd:string | A procedure, expressed as text, for these handling instructions. | UN01003629 | Handling_ Instructions. Procedure. Text
<span id="HandlingInstructionsID">HandlingInstructionsID</span> | xsd:token | The identifier of this handling instructions. | UN01012760 | Handling_ Instructions. Identification. Identifier
<span id="HandlingInstructionsDescriptionCode">HandlingInstructionsDescriptionCode</span> | xsd:token | A code specifying a description of these handling instructions. | UN01003633 | Handling_ Instructions. Description. Code
<span id="DeliveryInstructedTemperature">DeliveryInstructedTemperature</span> | [edi3:InstructedTemperature](#InstructedTemperature) | The instructed temperature for delivery applicable to these handling instructions. | UN01008433 | Handling_ Instructions. Delivery_ Applicable. Instructed_ Temperature
<span id="MarketDeliveryInstructedTemperature">MarketDeliveryInstructedTemperature</span> | [edi3:InstructedTemperature](#InstructedTemperature) | The instructed temperature for market delivery applicable to these handling instructions. | UN01008434 | Handling_ Instructions. Market Delivery_ Applicable. Instructed_ Temperature
<span id="StorageInstructedTemperature">StorageInstructedTemperature</span> | [edi3:InstructedTemperature](#InstructedTemperature) | The instructed temperature for storage applicable to these handling instructions. | UN01008435 | Handling_ Instructions. Storage_ Applicable. Instructed_ Temperature
<span id="HandlingInstructionsDescription">HandlingInstructionsDescription</span> | xsd:string | A textual description of these handling instructions. | UN01003632 | Handling_ Instructions. Description. Text
<span id="HandlingTransportSettingTemperature">HandlingTransportSettingTemperature</span> | [edi3:TransportSettingTemperature](#TransportSettingTemperature) | A transport related temperature setting applicable to these handling instructions. | UN01007180 | Handling_ Instructions. Applicable. Transport Setting_ Temperature


<h1 id="ReturnableAssetInstructions">ReturnableAssetInstructions</h1>

Type: rdf:Class

Definition: The procedures to follow for returnable assets, such as reusable packaging (pallets, crates).

Unique UN Assigned ID: UN01008860

Dictionary Entry Name: Returnable Asset_ Instructions. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="TermsAndConditionsText">TermsAndConditionsText</span> | xsd:string | A textual description of the terms and conditions for these returnable asset instructions. | UN01008862 | Returnable Asset_ Instructions. Terms And Conditions_ Description. Text
<span id="DepositValidityPeriod">DepositValidityPeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The specified period during which the deposit value specified in these returnable asset instructions is valid. | UN01008865 | Returnable Asset_ Instructions. Deposit Value_ Validity. Specified_ Period
<span id="ReturnableAssetInstructionsMaterialID">ReturnableAssetInstructionsMaterialID</span> | xsd:token | An identifier of the material to which these returnable asset instructions apply. | UN01008861 | Returnable Asset_ Instructions. Material. Identifier
<span id="TermsAndConditionsCode">TermsAndConditionsCode</span> | xsd:token | The code specifying the description of the terms and conditions for these returnable asset instructions. | UN01008863 | Returnable Asset_ Instructions. Terms And Conditions_ Description. Code


<h1 id="TemperatureSettingInstructions">TemperatureSettingInstructions</h1>

Type: rdf:Class

Definition: Temperature setting related information of an instructive nature.

Unique UN Assigned ID: UN01004489

Dictionary Entry Name: Temperature Setting_ Instructions. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="TemperatureSettingInstructionsDescription">TemperatureSettingInstructionsDescription</span> | xsd:string | A textual description of these temperature setting instructions. | UN01004491 | Temperature Setting_ Instructions. Description. Text
<span id="TemperatureSettingInstructionsProcedureText">TemperatureSettingInstructionsProcedureText</span> | xsd:string | A procedure, expressed as text, for these temperature setting instructions. | UN01004490 | Temperature Setting_ Instructions. Procedure. Text


<h1 id="TransportInstructions">TransportInstructions</h1>

Type: rdf:Class

Definition: Transport information of an instructive nature.

Unique UN Assigned ID: UN01004811

Dictionary Entry Name: Transport_ Instructions. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="TransportInstructionsDescription">TransportInstructionsDescription</span> | xsd:string | A textual description of these transport instructions. | UN01004813 | Transport_ Instructions. Description. Text


<h1 id="DeliveryInstructions">DeliveryInstructions</h1>

Type: rdf:Class

Definition: Delivery information of an instructive nature.

Unique UN Assigned ID: UN01003504

Dictionary Entry Name: Delivery_ Instructions. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="DeliveryInstructionsDescription">DeliveryInstructionsDescription</span> | xsd:string | A textual description of these delivery instructions. | UN01003511 | Delivery_ Instructions. Description. Text
<span id="HandlingText">HandlingText</span> | xsd:string | Delivery handling instructions expressed as text. | UN01003506 | Delivery_ Instructions. Handling. Text
<span id="DeliveryInstructionsHandlingCode">DeliveryInstructionsHandlingCode</span> | xsd:token | A code specifying delivery handling instructions. | UN01003505 | Delivery_ Instructions. Handling. Code


<h1 id="DisposalInstructions">DisposalInstructions</h1>

Type: rdf:Class

Definition: A set of instructions detailing how to properly dispose of a material.

Unique UN Assigned ID: UN01002451

Dictionary Entry Name: Disposal_ Instructions. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="RecyclingDescriptionCode">RecyclingDescriptionCode</span> | xsd:token | A code describing recycling in these disposal instructions. | UN01008428 | Disposal_ Instructions. Recycling_ Description. Code
<span id="DisposalInstructionsMaterialID">DisposalInstructionsMaterialID</span> | xsd:token | The identifier of the material to which these disposal instructions apply. | UN01008427 | Disposal_ Instructions. Material. Identifier
<span id="DisposalInstructionsDescription">DisposalInstructionsDescription</span> | xsd:string | A textual description of these disposal instructions. | UN01008429 | Disposal_ Instructions. Description. Text


<h1 id="Booking">Booking</h1>

Type: rdf:Class

Definition: A result of a financial transaction recorded within a financial account.

Unique UN Assigned ID: UN01013213

Dictionary Entry Name: Financial_ Booking. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="BookingActualDateTime">BookingActualDateTime</span> | xsd:dateTime | An actual date, time, date time, or other date time value of this financial booking. | UN01013214 | Financial_ Booking. Actual. Date Time
<span id="DebitDateTime">DebitDateTime</span> | xsd:dateTime | The debit date, time, date time, or other date time value of this financial booking. | UN01013216 | Financial_ Booking. Debit. Date Time


<h1 id="AccountingAccount">AccountingAccount</h1>

Type: rdf:Class

Definition: A specific trade account for recording debits and credits to general accounting, cost accounting or budget accounting.

Unique UN Assigned ID: UN01004522

Dictionary Entry Name: Trade_ Accounting Account. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="AccountingAccountTypeCode">AccountingAccountTypeCode</span> | xsd:token | The code specifying the type of trade accounting account, such as general (main), secondary, cost accounting or budget account. | UN01004525 | Trade_ Accounting Account. Type. Code
<span id="SetTriggerCode">SetTriggerCode</span> | xsd:token | A code specifying a set trigger for this trade accounting account to be used in response to a specific event or a set of events. | UN01004524 | Trade_ Accounting Account. Set Trigger. Code
<span id="AccountingAccountID">AccountingAccountID</span> | xsd:token | The unique identifier for this trade accounting account. | UN01004523 | Trade_ Accounting Account. Identification. Identifier
<span id="AccountingAccountName">AccountingAccountName</span> | xsd:string | The name, expressed as text, of this trade accounting account. | UN01004528 | Trade_ Accounting Account. Name. Text
<span id="CostReferenceDimensionPatternText">CostReferenceDimensionPatternText</span> | xsd:string | The cost reference dimension pattern, expressed as text, for this trade accounting account. | UN01006030 | Trade_ Accounting Account. Cost Reference Dimension Pattern. Text


<h1 id="GeographicalMultiPoint">GeographicalMultiPoint</h1>

Type: rdf:Class

Definition: A collection of points, on the surface of the Earth (reference ISO 19136).

Unique UN Assigned ID: UN01012183

Dictionary Entry Name: Specified_ Geographical Multi-Point. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="GeographicalMultiPointDirectPositionList">GeographicalMultiPointDirectPositionList</span> | [edi3:DirectPositionList](#DirectPositionList) | The direct position list associated with this geographical multi-point. | UN01012184 | Specified_ Geographical Multi-Point. Associated. Specified_ Direct Position List
<span id="GeographicalMultiPointGeographicalObjectCharacteristic">GeographicalMultiPointGeographicalObjectCharacteristic</span> | [edi3:GeographicalObjectCharacteristic](#GeographicalObjectCharacteristic) | The geographical object characteristic associated with this geographical multi-point. | UN01012185 | Specified_ Geographical Multi-Point. Associated. Specified_ Geographical Object Characteristic


<h1 id="PaymentMeans">PaymentMeans</h1>

Type: rdf:Class

Definition: The means by which a payment will be or has been made for trade settlement purposes.

Unique UN Assigned ID: UN01004512

Dictionary Entry Name: Trade Settlement_ Payment Means. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="PayerDebtorFinancialInstitution">PayerDebtorFinancialInstitution</span> | [edi3:DebtorFinancialInstitution](#DebtorFinancialInstitution) | The debtor financial institution of the payer party specified for this trade settlement payment means. | UN01004520 | Trade Settlement_ Payment Means. Payer_ Specified. Debtor_ Financial Institution
<span id="PayerDebtorFinancialAccount">PayerDebtorFinancialAccount</span> | [edi3:DebtorFinancialAccount](#DebtorFinancialAccount) | The debtor financial account of the payer party for this trade settlement payment means. | UN01004518 | Trade Settlement_ Payment Means. Payer_ Party. Debtor_ Financial Account
<span id="PaymentMeansInformation">PaymentMeansInformation</span> | xsd:string | Information, expressed as text, for this trade settlement payment means. | UN01004910 | Trade Settlement_ Payment Means. Information. Text
<span id="PayeeCreditorFinancialAccount">PayeeCreditorFinancialAccount</span> | [edi3:CreditorFinancialAccount](#CreditorFinancialAccount) | A creditor financial account of the payee party for this trade settlement payment means. | UN01004519 | Trade Settlement_ Payment Means. Payee_ Party. Creditor_ Financial Account
<span id="TradeSettlementPaymentMeansID">TradeSettlementPaymentMeansID</span> | xsd:token | An identifier for this trade settlement payment means. | UN01006055 | Trade Settlement_ Payment Means. Identification. Identifier
<span id="GuaranteeMethodCode">GuaranteeMethodCode</span> | xsd:token | The code specifying the method of guarantee for this trade settlement payment means. | UN01004515 | Trade Settlement_ Payment Means. Guarantee Method. Code
<span id="PaymentMeansTypeCode">PaymentMeansTypeCode</span> | xsd:token | The code specifying the type of trade settlement payment means, such as cash or check. | UN01004514 | Trade Settlement_ Payment Means. Type. Code
<span id="PaymentMeansSpecifiedCreditorFinancialAccount">PaymentMeansSpecifiedCreditorFinancialAccount</span> | [edi3:CreditorFinancialAccount](#CreditorFinancialAccount) | A creditor financial account specified for this trade settlement payment means. | UN01013300 | Trade Settlement_ Payment Means. Specified. Creditor_ Financial Account
<span id="PayeeCreditorFinancialInstitution">PayeeCreditorFinancialInstitution</span> | [edi3:CreditorFinancialInstitution](#CreditorFinancialInstitution) | The creditor financial institution of the payee party specified for this trade settlement payment means. | UN01004521 | Trade Settlement_ Payment Means. Payee_ Specified. Creditor_ Financial Institution
<span id="PaymentMeansPaymentMethodCode">PaymentMeansPaymentMethodCode</span> | xsd:token | The code specifying the method by which a payment may be made for this trade settlement payment means. | UN01004516 | Trade Settlement_ Payment Means. Payment Method. Code
<span id="PaymentMeansFinancialCard">PaymentMeansFinancialCard</span> | [edi3:FinancialCard](#FinancialCard) | A financial card applicable to this trade settlement payment means. | UN01004517 | Trade Settlement_ Payment Means. Applicable. Trade Settlement_ Financial Card


<h1 id="Project">Project</h1>

Type: rdf:Class

Definition: An endeavour carefully planned to achieve a procurement of goods, works and service.

Unique UN Assigned ID: UN01000371

Dictionary Entry Name: Procuring_ Project. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="NetBudgetAmount">NetBudgetAmount</span> | xsd:decimal | The monetary value of the net budget for this procuring project. | UN01000380 | Procuring_ Project. Net_ Budget. Amount
<span id="SubWorksTypeCode">SubWorksTypeCode</span> | xsd:token | A code specifying the type of sub works, such as land surveying or information technology consulting, for this procuring project. | UN01000376 | Procuring_ Project. Sub_ Works Type. Code
<span id="WorksTypeCode">WorksTypeCode</span> | xsd:token | A code specifying the type of work, such as surveying or consulting, for this procuring project. | UN01000375 | Procuring_ Project. Works Type. Code
<span id="ProjectID">ProjectID</span> | xsd:token | The unique identifier of this procuring project. | UN01000372 | Procuring_ Project. Identification. Identifier
<span id="ProjectName">ProjectName</span> | xsd:string | The name, expressed as text, of this procuring project. | UN01000374 | Procuring_ Project. Name. Text
<span id="ProjectTypeCode">ProjectTypeCode</span> | xsd:token | The code specifying the type of procuring project, such as goods, works and service. | UN01000377 | Procuring_ Project. Type. Code
<span id="TotalBudgetAmount">TotalBudgetAmount</span> | xsd:decimal | The monetary value of the total budget which includes net amount, taxes, and material and instalment costs for this procuring project. | UN01000379 | Procuring_ Project. Total_ Budget. Amount
<span id="ProjectDescription">ProjectDescription</span> | xsd:string | The textual description of this procuring project. | UN01000373 | Procuring_ Project. Description. Text


<h1 id="Qualification">Qualification</h1>

Type: rdf:Class

Definition: An academic achievement that is officially recognized.

Unique UN Assigned ID: UN01002516

Dictionary Entry Name: Academic_ Qualification. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="QualificationName">QualificationName</span> | xsd:string | A name, expressed as text, of this academic qualification. | UN01002517 | Academic_ Qualification. Name. Text


<h1 id="Chemical">Chemical</h1>

Type: rdf:Class

Definition: Any clearly defined substance having a defined molecular composition.

Unique UN Assigned ID: UN01002172

Dictionary Entry Name: Distinct_ Chemical. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="MolecularWeight">MolecularWeight</span> | xsd:decimal | The measure of the molecular weight (in grams) for this distinct chemical. | UN01002177 | Distinct_ Chemical. Molecular_ Weight. Measure
<span id="ChemicalTypeCode">ChemicalTypeCode</span> | xsd:token | The code specifying the type of distinct chemical. | UN01002178 | Distinct_ Chemical. Type. Code
<span id="FormulaDescription">FormulaDescription</span> | xsd:string | The textual description of the formula for this distinct chemical. | UN01002179 | Distinct_ Chemical. Formula_ Description. Text
<span id="ChemicalCommonName">ChemicalCommonName</span> | xsd:string | A common name, expressed as text, for this distinct chemical. | UN01002174 | Distinct_ Chemical. Common_ Name. Text
<span id="ChemicalFamilyName">ChemicalFamilyName</span> | xsd:string | The family name expressed as text for this distinct chemical. | UN01002176 | Distinct_ Chemical. Family_ Name. Text
<span id="ChemicalScientificName">ChemicalScientificName</span> | xsd:string | The scientific name, expressed as text, for this distinct chemical. | UN01002173 | Distinct_ Chemical. Scientific_ Name. Text


<h1 id="CreditorFinancialAccount">CreditorFinancialAccount</h1>

Type: rdf:Class

Definition: A specific business arrangement whereby credits arising from transactions are recorded.

Unique UN Assigned ID: UN01003347

Dictionary Entry Name: Creditor_ Financial Account. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="CreditorFinancialAccountProprietaryID">CreditorFinancialAccountProprietaryID</span> | xsd:token | The unique proprietary identifier for this creditor financial account. | UN01004850 | Creditor_ Financial Account. Proprietary_ Identification. Identifier
<span id="CreditorFinancialAccountTypeCode">CreditorFinancialAccountTypeCode</span> | xsd:token | The code specifying the type of creditor financial account. | UN01003352 | Creditor_ Financial Account. Type. Code
<span id="CreditorFinancialAccountIBANID">CreditorFinancialAccountIBANID</span> | xsd:token | The unique International Bank Account Number (IBAN) identifier for this creditor financial account. | UN01003348 | Creditor_ Financial Account. IBAN_ Identification. Identifier
<span id="CreditorFinancialAccountName">CreditorFinancialAccountName</span> | xsd:string | The account name, expressed as text, of this creditor financial account. | UN01003355 | Creditor_ Financial Account. Account Name. Text
<span id="CreditorFinancialAccountCurrencyCode">CreditorFinancialAccountCurrencyCode</span> | xsd:token | The code specifying the currency of this creditor financial account (Reference ISO 4217 codes). | UN01003354 | Creditor_ Financial Account. Currency. Code
<span id="CreditorFinancialAccountUPICID">CreditorFinancialAccountUPICID</span> | xsd:token | The unique Universal Payment Identification Code (UPIC) identifier used by the New York Clearing House for this creditor financial account. | UN01003350 | Creditor_ Financial Account. UPIC_ Identification. Identifier
<span id="CreditorFinancialAccountBBANID">CreditorFinancialAccountBBANID</span> | xsd:token | The unique Basic Bank Account Number (BBAN) identifier used as part of a National Account Numbering Scheme(s) for this creditor financial account. | UN01003349 | Creditor_ Financial Account. BBAN_ Identification. Identifier
<span id="CreditorFinancialAccountProprietaryTypeText">CreditorFinancialAccountProprietaryTypeText</span> | xsd:string | The proprietary type, expressed as text, of this creditor financial account, such as the nature or use of the creditor account. | UN01003353 | Creditor_ Financial Account. Proprietary_ Type. Text


<h1 id="DebtorFinancialAccount">DebtorFinancialAccount</h1>

Type: rdf:Class

Definition: A specific business arrangement whereby debits arising from transactions are recorded.

Unique UN Assigned ID: UN01003284

Dictionary Entry Name: Debtor_ Financial Account. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="DebtorFinancialAccountProprietaryTypeText">DebtorFinancialAccountProprietaryTypeText</span> | xsd:string | The proprietary type, expressed as text, of this debtor financial account, such as the nature or use of the debtor account. | UN01003290 | Debtor_ Financial Account. Proprietary_ Type. Text
<span id="DebtorFinancialAccountBBANID">DebtorFinancialAccountBBANID</span> | xsd:token | The unique Basic Bank Account Number (BBAN) identifier used as part of a National Account Numbering Scheme(s) for this debtor financial account. | UN01003286 | Debtor_ Financial Account. BBAN_ Identification. Identifier
<span id="DebtorFinancialAccountIBANID">DebtorFinancialAccountIBANID</span> | xsd:token | The unique International Bank Account Number (IBAN) identifier for this debtor financial account. | UN01003285 | Debtor_ Financial Account. IBAN_ Identification. Identifier
<span id="DebtorFinancialAccountProprietaryID">DebtorFinancialAccountProprietaryID</span> | xsd:token | The unique proprietary identifier for this debtor financial account. | UN01004851 | Debtor_ Financial Account. Proprietary_ Identification. Identifier
<span id="DeprecatedProprietaryAccountName">DeprecatedProprietaryAccountName</span> | xsd:string | The proprietary account name, expressed as text, of this debtor financial account. | UN01003288 | Debtor_ Financial Account. Proprietary_ Account Name. Text
<span id="DebtorFinancialAccountUPICID">DebtorFinancialAccountUPICID</span> | xsd:token | The unique Universal Payment Identification Code (UPIC) identifier used by the New York Clearing House for this debtor financial account. | UN01003287 | Debtor_ Financial Account. UPIC_ Identification. Identifier
<span id="DebtorFinancialAccountCurrencyCode">DebtorFinancialAccountCurrencyCode</span> | xsd:token | The code specifying the currency of this debtor financial account (Reference ISO 4217 codes). | UN01003291 | Debtor_ Financial Account. Currency. Code
<span id="DebtorFinancialAccountName">DebtorFinancialAccountName</span> | xsd:string | The account name, expressed as text, of this debtor financial account. | UN01003292 | Debtor_ Financial Account. Account Name. Text


<h1 id="FinancingFinancialAccount">FinancingFinancialAccount</h1>

Type: rdf:Class

Definition: A financial account used internally by a bank to manage the line of credit granted to financing requesting party.

Unique UN Assigned ID: UN01013253

Dictionary Entry Name: Financing_ Financial Account. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="FinancingFinancialAccountIBANID">FinancingFinancialAccountIBANID</span> | xsd:token | The unique International Bank Account Number (IBAN) identifier for this financing financial account. | UN01013254 | Financing_ Financial Account. IBAN_ Identification. Identifier
<span id="FinancingFinancialAccountProprietaryID">FinancingFinancialAccountProprietaryID</span> | xsd:token | The proprietary identifier for this financing financial account. | UN01013261 | Financing_ Financial Account. Proprietary_ Identification. Identifier
<span id="FinancingFinancialAccountName">FinancingFinancialAccountName</span> | xsd:string | The account name, expressed as text, of this financing financial account. | UN01013260 | Financing_ Financial Account. Account Name. Text
<span id="FinancingFinancialAccountProprietaryTypeText">FinancingFinancialAccountProprietaryTypeText</span> | xsd:string | The proprietary type, expressed as text, of this financing financial account, such as the nature or use. | UN01013258 | Financing_ Financial Account. Proprietary_ Type. Text
<span id="FinancingFinancialAccountTypeCode">FinancingFinancialAccountTypeCode</span> | xsd:token | The code specifying the type of financing financial account. | UN01013257 | Financing_ Financial Account. Type. Code
<span id="FinancingFinancialAccountUPICID">FinancingFinancialAccountUPICID</span> | xsd:token | The unique Universal Payment Identification Code (UPIC) identifier used by the New York Clearing House for this financing financial account. | UN01013256 | Financing_ Financial Account. UPIC_ Identification. Identifier
<span id="FinancingFinancialAccountCurrencyCode">FinancingFinancialAccountCurrencyCode</span> | xsd:token | The code specifying the currency of this financing financial account. | UN01013259 | Financing_ Financial Account. Currency. Code


<h1 id="Note">Note</h1>

Type: rdf:Class

Definition: A textual or coded description, such as a remark or additional information.

Unique UN Assigned ID: UN01002519

Dictionary Entry Name: Note. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="SubjectCode">SubjectCode</span> | xsd:token | A code specifying the subject of this note. | UN01002523 | Note. Subject. Code
<span id="NoteID">NoteID</span> | xsd:token | A unique identifier for this note. | UN01002524 | Note. Identification. Identifier
<span id="NoteContentCode">NoteContentCode</span> | xsd:token | A code specifying the content of this note. | UN01002521 | Note. Content. Code
<span id="SubjectText">SubjectText</span> | xsd:string | The subject, expressed as text, of this note. | UN01002520 | Note. Subject. Text


<h1 id="SubordinateLineTradeDelivery">SubordinateLineTradeDelivery</h1>

Type: rdf:Class

Definition: Supply chain shipping arrangements and movement of products and or services including despatch and delivery.

Unique UN Assigned ID: UN01011849

Dictionary Entry Name: Subordinate Line_ Trade Delivery. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="SubordinateLineTradeDeliveryProductUnitQuantity">SubordinateLineTradeDeliveryProductUnitQuantity</span> | xsd:decimal | The number of product units in this subordinate line trade delivery. | UN01011851 | Subordinate Line_ Trade Delivery. Product_ Unit. Quantity
<span id="SubordinateLineTradeDeliveryPackageQuantity">SubordinateLineTradeDeliveryPackageQuantity</span> | xsd:decimal | The number of packages in this subordinate line trade delivery. | UN01011850 | Subordinate Line_ Trade Delivery. Package. Quantity
<span id="SubordinateLineTradeDeliveryIncludedPackaging">SubordinateLineTradeDeliveryIncludedPackaging</span> | [edi3:Packaging](#Packaging) | Packaging included in this subordinate line trade delivery. | UN01011853 | Subordinate Line_ Trade Delivery. Included. Supply Chain_ Packaging


<h1 id="LineTradeDelivery">LineTradeDelivery</h1>

Type: rdf:Class

Definition: Shipping arrangements and movement of products and or services including despatch and delivery at a line level.

Unique UN Assigned ID: UN01011755

Dictionary Entry Name: Line_ Trade Delivery. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="LineTradeDeliveryPerPackageUnitQuantity">LineTradeDeliveryPerPackageUnitQuantity</span> | xsd:decimal | The number of units per package, at line level, in this trade delivery. | UN01011766 | Line_ Trade Delivery. Per Package_ Unit. Quantity
<span id="LineTradeDeliveryRequestedQuantity">LineTradeDeliveryRequestedQuantity</span> | xsd:decimal | The quantity, at line level, requested for this trade delivery. | UN01011758 | Line_ Trade Delivery. Requested. Quantity
<span id="LineTradeDeliveryFullyDeliveredIndicator">LineTradeDeliveryFullyDeliveredIndicator</span> | xsd:boolean | The indication, at line level, of whether or not this trade delivery is fully delivered. | UN01013004 | Line_ Trade Delivery. Fully Delivered. Indicator
<span id="UnavailableQuantity">UnavailableQuantity</span> | xsd:decimal | The quantity, at line level, unavailable for this trade delivery. | UN01013446 | Line_ Trade Delivery. Unavailable. Quantity
<span id="LineTradeDeliveryFinalDeliveryIndicator">LineTradeDeliveryFinalDeliveryIndicator</span> | xsd:boolean | The indication, at line level, of whether or not this trade delivery is the final delivery. | UN01011757 | Line_ Trade Delivery. Final Delivery. Indicator
<span id="LineTradeDeliveryModificationForecastedQuantity">LineTradeDeliveryModificationForecastedQuantity</span> | xsd:decimal | The modification of a forecasted quantity, at line level, for this trade delivery. | UN01013007 | Line_ Trade Delivery. Modification_ Forecasted. Quantity
<span id="LineTradeDeliveryGoodsReceiptNote">LineTradeDeliveryGoodsReceiptNote</span> | [edi3:Document](#Document) | The goods receipt note document, at line level, referenced for this trade delivery. | UN01013462 | Line_ Trade Delivery. Goods Receipt Note. Referenced_ Document
<span id="LineTradeDeliveryUsedTransportEquipment">LineTradeDeliveryUsedTransportEquipment</span> | [edi3:ReferencedTransportEquipment](#ReferencedTransportEquipment) | A piece of logistics transport equipment, at line level, utilized for this trade delivery. | UN01012126 | Line_ Trade Delivery. Utilized. Referenced_ Logistics_ Transport Equipment
<span id="RemainingRequestedDeliveryQuantity">RemainingRequestedDeliveryQuantity</span> | xsd:decimal | The remaining quantity, at line level, requested for this trade delivery. | UN01011759 | Line_ Trade Delivery. Remaining_ Requested. Quantity
<span id="ChargeableWeightMeasure">ChargeableWeightMeasure</span> | xsd:decimal | The measure of the chargeable weight, at line level, for this trade delivery. | UN01012997 | Line_ Trade Delivery. Chargeable Weight. Measure
<span id="LineTradeDeliveryRequestedDeliveryEvent">LineTradeDeliveryRequestedDeliveryEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | A delivery event, at line level, requested for this trade delivery. | UN01011788 | Line_ Trade Delivery. Requested_ Delivery. Supply Chain_ Event
<span id="ProjectedSupplyPlan">ProjectedSupplyPlan</span> | [edi3:SupplyPlan](#SupplyPlan) | A supply plan, at line level, projected for this trade delivery. | UN01011774 | Line_ Trade Delivery. Projected. Supply Chain_ Supply Plan
<span id="LineTradeDeliveryActualPickUpEvent">LineTradeDeliveryActualPickUpEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | The actual pick-up event, at line level, for this trade delivery. | UN01011787 | Line_ Trade Delivery. Actual_ Pick-Up. Supply Chain_ Event
<span id="ReverseBilledQuantity">ReverseBilledQuantity</span> | xsd:decimal | The reverse billed quantity, at line level, for this trade delivery. | UN01013009 | Line_ Trade Delivery. Reverse_ Billed. Quantity
<span id="LineTradeDeliveryPlannedConsignment">LineTradeDeliveryPlannedConsignment</span> | [edi3:Consignment](#Consignment) | A consignment, at line level, planned for this trade delivery. | UN01011796 | Line_ Trade Delivery. Planned. Supply Chain_ Consignment
<span id="LineTradeDeliveryFinalDestinationCountry">LineTradeDeliveryFinalDestinationCountry</span> | [edi3:Country](#Country) | The country of final destination, at line level, for line trade delivery. | UN01011781 | Line_ Trade Delivery. Final Destination. Trade_ Country
<span id="LineTradeDeliveryStatusCode">LineTradeDeliveryStatusCode</span> | xsd:token | The code specifying the status, at line level, for this trade delivery. | UN01012998 | Line_ Trade Delivery. Status. Code
<span id="LineTradeDeliveryAcceptanceEvent">LineTradeDeliveryAcceptanceEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | An acceptance delivery event, at line level, for this trade delivery. | UN01013440 | Line_ Trade Delivery. Acceptance. Supply Chain_ Event
<span id="LineTradeDeliveryPackingListDocument">LineTradeDeliveryPackingListDocument</span> | [edi3:Document](#Document) | The packing list document, at line level, referenced for this trade delivery. | UN01011938 | Line_ Trade Delivery. Packing List. Referenced_ Document
<span id="TheoreticalWeight">TheoreticalWeight</span> | xsd:decimal | The measure, at line level, of the theoretical weight of this trade delivery. | UN01011769 | Line_ Trade Delivery. Theoretical Weight. Measure
<span id="ReturnedQuantity">ReturnedQuantity</span> | xsd:decimal | The quantity, at line level, returned for this trade delivery. | UN01013443 | Line_ Trade Delivery. Returned. Quantity
<span id="LineTradeDeliveryDueInAvailableQuantity">LineTradeDeliveryDueInAvailableQuantity</span> | xsd:decimal | The due in available quantity, at line level, for this trade delivery. | UN01012999 | Line_ Trade Delivery. Due In_ Available. Quantity
<span id="DueInReturnedQuantity">DueInReturnedQuantity</span> | xsd:decimal | The due in returned quantity, at line level, for this trade delivery. | UN01013002 | Line_ Trade Delivery. Due In_ Returned. Quantity
<span id="LineTradeDeliveryDespatchAdviceDocument">LineTradeDeliveryDespatchAdviceDocument</span> | [edi3:Document](#Document) | The despatch advice document, at line level, referenced for this trade delivery. | UN01011793 | Line_ Trade Delivery. Despatch Advice. Referenced_ Document
<span id="DespatchSchedule">DespatchSchedule</span> | [edi3:Schedule](#Schedule) | A supply chain despatch schedule, at line level, for this trade delivery. | UN01013019 | Line_ Trade Delivery. Despatch. Supply Chain_ Schedule
<span id="LineTradeDeliveryPlannedDeliveryEvent">LineTradeDeliveryPlannedDeliveryEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | A delivery event, at line level, planned for this trade delivery. | UN01011789 | Line_ Trade Delivery. Planned_ Delivery. Supply Chain_ Event
<span id="CustomerInventory">CustomerInventory</span> | [edi3:SupplyChainInventory](#SupplyChainInventory) | Supply chain customer inventory, at line level, for this trade delivery. | UN01013014 | Line_ Trade Delivery. Customer. Supply Chain_ Inventory
<span id="LineDeliveryAdjustment">LineDeliveryAdjustment</span> | [edi3:DeliveryAdjustment](#DeliveryAdjustment) | A delivery adjustment, at line level, specified for this trade delivery. | UN01011775 | Line_ Trade Delivery. Specified. Delivery_ Adjustment
<span id="LineTradeDeliveryDeliveryInstructions">LineTradeDeliveryDeliveryInstructions</span> | [edi3:DeliveryInstructions](#DeliveryInstructions) | Delivery instructions, at line level, specified for this trade delivery. | UN01011782 | Line_ Trade Delivery. Specified. Delivery_ Instructions
<span id="LineTradeDeliveryRelatedConsignment">LineTradeDeliveryRelatedConsignment</span> | [edi3:Consignment](#Consignment) | A consignment, at line level, related to this line trade delivery. | UN01011777 | Line_ Trade Delivery. Related. Supply Chain_ Consignment
<span id="DestroyedQuantity">DestroyedQuantity</span> | xsd:decimal | The quantity, at line level, destroyed for this trade delivery. | UN01013444 | Line_ Trade Delivery. Destroyed. Quantity
<span id="ChargeFreeQuantity">ChargeFreeQuantity</span> | xsd:decimal | The quantity, at line level, free of charge, in this trade delivery. | UN01011763 | Line_ Trade Delivery. Charge Free. Quantity
<span id="QuantityVariationTypeCode">QuantityVariationTypeCode</span> | xsd:token | The code specifying the type of quantity variation, at line level, for this trade delivery. | UN01013449 | Line_ Trade Delivery. Quantity Variation_ Type. Code
<span id="LineTradeDeliveryActualUnloadingEvent">LineTradeDeliveryActualUnloadingEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | The actual unloading event, at line level, for this trade delivery. | UN01013457 | Line_ Trade Delivery. Actual_ Unloading. Supply Chain_ Event
<span id="CancelledQuantity">CancelledQuantity</span> | xsd:decimal | The quantity, at line level, cancelled for this trade delivery. | UN01013448 | Line_ Trade Delivery. Cancelled. Quantity
<span id="LineTradeDeliveryConfirmedPickUpEvent">LineTradeDeliveryConfirmedPickUpEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | The pick-up event, at line level, confirmed for this trade delivery. | UN01013460 | Line_ Trade Delivery. Confirmed_ Pick-Up. Supply Chain_ Event
<span id="LineTradeDeliveryInformationNote">LineTradeDeliveryInformationNote</span> | [edi3:Note](#Note) | A note with information, at line level, for this trade delivery. | UN01013012 | Line_ Trade Delivery. Information. Note
<span id="LineTradeDeliveryActualReceiptEvent">LineTradeDeliveryActualReceiptEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | The actual receipt event, at line level, for this trade delivery. | UN01011791 | Line_ Trade Delivery. Actual_ Receipt. Supply Chain_ Event
<span id="QuantityVariationReasonCode">QuantityVariationReasonCode</span> | xsd:token | The code specifying the reason for the quantity variation, at line level, for this trade delivery. | UN01013450 | Line_ Trade Delivery. Quantity Variation_ Reason. Code
<span id="LineTradeDeliveryConsumptionReportDocument">LineTradeDeliveryConsumptionReportDocument</span> | [edi3:Document](#Document) | The consumption report document, at line level, referenced from this trade delivery. | UN01011799 | Line_ Trade Delivery. Consumption Report. Referenced_ Document
<span id="GFMTransferRejectedQuantity">GFMTransferRejectedQuantity</span> | xsd:decimal | The Government Furnished Material (GFM) transfer rejected quantity, at line level, for this trade delivery. | UN01013005 | Line_ Trade Delivery. GFM Transfer_ Rejected. Quantity
<span id="LineTradeDeliveryConfirmedReleaseEvent">LineTradeDeliveryConfirmedReleaseEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | The release event, at line level, confirmed for this trade delivery. | UN01013458 | Line_ Trade Delivery. Confirmed_ Release. Supply Chain_ Event
<span id="FormattedPickUpAvailabilityDateTime">FormattedPickUpAvailabilityDateTime</span> | xsd:dateTime | The formatted date, time, date time, or other date time value, at line level, when this delivery is available for pick-up. | UN01013011 | Line_ Trade Delivery. Formatted_ Pick-Up Availability. Date Time
<span id="LineTradeDeliveryPlannedDespatchEvent">LineTradeDeliveryPlannedDespatchEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | A despatch event, at line level, planned for this trade delivery. | UN01011785 | Line_ Trade Delivery. Planned_ Despatch. Supply Chain_ Event
<span id="FormattedUltimateShipToDeliveryDateTime">FormattedUltimateShipToDeliveryDateTime</span> | xsd:dateTime | The formatted date, time, date time, or other date time value, at line level, when this trade delivery is delivered to the ultimate ship to party. | UN01011772 | Line_ Trade Delivery. Formatted_ Ultimate Ship To Delivery. Date Time
<span id="LineTradeDeliveryDueInForecastedQuantity">LineTradeDeliveryDueInForecastedQuantity</span> | xsd:decimal | The due in forecasted quantity, at line level, for this trade delivery. | UN01013000 | Line_ Trade Delivery. Due In_ Forecasted. Quantity
<span id="LineTradeDeliveryOverDeliveryAllowedIndicator">LineTradeDeliveryOverDeliveryAllowedIndicator</span> | xsd:boolean | The indication, at line level, of whether or not over delivery is allowed for this trade delivery. | UN01013008 | Line_ Trade Delivery. Over Delivery Allowed. Indicator
<span id="LatestDespatchedQuantity">LatestDespatchedQuantity</span> | xsd:decimal | The latest quantity, at line level, despatched in this trade delivery. | UN01011760 | Line_ Trade Delivery. Latest_ Despatched. Quantity
<span id="LineTradeDeliveryEconomicOrderQuantity">LineTradeDeliveryEconomicOrderQuantity</span> | xsd:decimal | The economic order quantity, at line level, for this trade delivery. | UN01013003 | Line_ Trade Delivery. Economic_ Order. Quantity
<span id="LineTradeDeliveryProductUnitQuantity">LineTradeDeliveryProductUnitQuantity</span> | xsd:decimal | The number of product units, at line level, in this trade delivery. | UN01011765 | Line_ Trade Delivery. Product_ Unit. Quantity
<span id="LineTradeDeliveryAdditionalDocument">LineTradeDeliveryAdditionalDocument</span> | [edi3:Document](#Document) | An additional document, at line level, referenced for this trade delivery. | UN01011792 | Line_ Trade Delivery. Additional. Referenced_ Document
<span id="ReceivedQuantity">ReceivedQuantity</span> | xsd:decimal | The quantity, at line level, received for this trade delivery. | UN01011942 | Line_ Trade Delivery. Received. Quantity
<span id="IndividualPackageQuantity">IndividualPackageQuantity</span> | xsd:decimal | The quantity within the individual package, at line level, for this trade delivery. | UN01013006 | Line_ Trade Delivery. Individual_ Package. Quantity
<span id="LineTradeDeliveryGrossVolume">LineTradeDeliveryGrossVolume</span> | xsd:decimal | The measure, at line level, of the gross volume of this trade delivery. | UN01011771 | Line_ Trade Delivery. Gross Volume. Measure
<span id="Supply(Replenishment)Schedule">Supply(Replenishment)Schedule</span> | [edi3:Schedule](#Schedule) | A supply (replenishment) schedule, specified at line level, for this trade delivery. | UN01013023 | Line_ Trade Delivery. Supply_ Specified. Supply Chain_ Schedule
<span id="LineTradeDeliveryConfirmedDespatchEvent">LineTradeDeliveryConfirmedDespatchEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | The despatch event, at line level, confirmed for this trade delivery. | UN01013459 | Line_ Trade Delivery. Confirmed_ Despatch. Supply Chain_ Event
<span id="LineTradeDeliveryHandlingInstructions">LineTradeDeliveryHandlingInstructions</span> | [edi3:HandlingInstructions](#HandlingInstructions) | Handling instructions, at line level, specified for this trade delivery. | UN01011783 | Line_ Trade Delivery. Specified. Handling_ Instructions
<span id="QuantityDiscrepancyNatureCode">QuantityDiscrepancyNatureCode</span> | xsd:token | The code specifying the nature of the discrepancy of the quantity, at line level, for this trade delivery. | UN01013452 | Line_ Trade Delivery. Quantity_ Discrepancy Nature. Code
<span id="AvailableQuantity">AvailableQuantity</span> | xsd:decimal | The quantity, at line level, available for this trade delivery. | UN01013445 | Line_ Trade Delivery. Available. Quantity
<span id="BilledQuantity">BilledQuantity</span> | xsd:decimal | The quantity, at line level, billed for in this trade delivery. | UN01011762 | Line_ Trade Delivery. Billed. Quantity
<span id="TurnInReceivedQuantity">TurnInReceivedQuantity</span> | xsd:decimal | The turn in quantity, at line level, received for this trade delivery. | UN01013010 | Line_ Trade Delivery. Turn In_ Received. Quantity
<span id="LineTradeDeliveryAgreedQuantity">LineTradeDeliveryAgreedQuantity</span> | xsd:decimal | The quantity, at line level, agreed for this trade delivery. | UN01011761 | Line_ Trade Delivery. Agreed. Quantity
<span id="LineTradeDeliveryGoodsOwnershipChangeDateTime">LineTradeDeliveryGoodsOwnershipChangeDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value for the goods ownership change, at line level, for this trade delivery. | UN01013454 | Line_ Trade Delivery. Goods Ownership Change. Date Time
<span id="LineTradeDeliveryShipFromParty">LineTradeDeliveryShipFromParty</span> | [edi3:TradeParty](#TradeParty) | The ship from party, at line level, for this trade delivery. | UN01011780 | Line_ Trade Delivery. Ship From. Trade_ Party
<span id="LineTradeDeliveryTransportDangerousGoods">LineTradeDeliveryTransportDangerousGoods</span> | [edi3:DangerousGoods](#DangerousGoods) | The transport dangerous goods details, at line level, applicable to this trade delivery. | UN01011798 | Line_ Trade Delivery. Applicable. Transport_ Dangerous Goods
<span id="LineTradeDeliveryShipToParty">LineTradeDeliveryShipToParty</span> | [edi3:TradeParty](#TradeParty) | The ship to party, at line level, for this trade delivery. | UN01011778 | Line_ Trade Delivery. Ship To. Trade_ Party
<span id="LineTradeDeliveryDisposalParty">LineTradeDeliveryDisposalParty</span> | [edi3:TradeParty](#TradeParty) | A disposal party, at line level, for this trade delivery. | UN01013455 | Line_ Trade Delivery. Disposal. Trade_ Party
<span id="LineTradeDeliveryPlannedShipToDeliveryEvent">LineTradeDeliveryPlannedShipToDeliveryEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | The planned ship to delivery event, at line level, for this trade delivery. | UN01013447 | Line_ Trade Delivery. Planned Ship To_ Delivery. Supply Chain_ Event
<span id="AvailableInventory">AvailableInventory</span> | [edi3:SupplyChainInventory](#SupplyChainInventory) | Inventory available, at line level, for this trade delivery. | UN01011773 | Line_ Trade Delivery. Available. Supply Chain_ Inventory
<span id="ConsumptionSchedule">ConsumptionSchedule</span> | [edi3:Schedule](#Schedule) | A supply chain consumption schedule, at line level, for this trade delivery. | UN01013017 | Line_ Trade Delivery. Consumption. Supply Chain_ Schedule
<span id="LineTradeDeliveryGrossWeight">LineTradeDeliveryGrossWeight</span> | xsd:decimal | The measure, at line level, of the gross weight (mass) of this line trade delivery. | UN01011768 | Line_ Trade Delivery. Gross Weight. Measure
<span id="LineTradeDeliveryConfirmedDeliveryEvent">LineTradeDeliveryConfirmedDeliveryEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | The confirmed delivery event, at line level, for this trade delivery. | UN01011797 | Line_ Trade Delivery. Confirmed_ Delivery. Supply Chain_ Event
<span id="RejectedQuantity">RejectedQuantity</span> | xsd:decimal | The quantity, at line level, rejected for this trade delivery. | UN01013441 | Line_ Trade Delivery. Rejected. Quantity
<span id="LineTradeDeliveryBuyerOrderDateTime">LineTradeDeliveryBuyerOrderDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value, at line level, of the buyer order for this trade delivery. | UN01013453 | Line_ Trade Delivery. Buyer_ Order. Date Time
<span id="SpecifiedSchedule">SpecifiedSchedule</span> | [edi3:Schedule](#Schedule) | A supply chain schedule, specified at line level, for this trade delivery. | UN01013022 | Line_ Trade Delivery. Specified. Supply Chain_ Schedule
<span id="ConsignmentInventory">ConsignmentInventory</span> | [edi3:SupplyChainInventory](#SupplyChainInventory) | Supply chain consignment inventory, at line level, for this trade delivery. | UN01013013 | Line_ Trade Delivery. Consignment. Supply Chain_ Inventory
<span id="LogisticsServiceProvider">LogisticsServiceProvider</span> | [edi3:TradeParty](#TradeParty) | A logistics service provider party, at line level, for this trade delivery. | UN01013015 | Line_ Trade Delivery. Logistics Service Provider. Trade_ Party
<span id="LineTradeDeliveryPlannedPickUpEvent">LineTradeDeliveryPlannedPickUpEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | The pick-up event, at line level, planned for this trade delivery. | UN01013461 | Line_ Trade Delivery. Planned_ Pick-Up. Supply Chain_ Event
<span id="LineTradeDeliveryShipmentScheduleDocument">LineTradeDeliveryShipmentScheduleDocument</span> | [edi3:Document](#Document) | The shipment schedule document referenced, at line level, for this trade delivery. | UN01013463 | Line_ Trade Delivery. Shipment Schedule. Referenced_ Document
<span id="LineTradeDeliveryUltimateShipToParty">LineTradeDeliveryUltimateShipToParty</span> | [edi3:TradeParty](#TradeParty) | The ultimate ship to party, at line level, for this trade delivery. | UN01011779 | Line_ Trade Delivery. Ultimate_ Ship To. Trade_ Party
<span id="LineTradeDeliveryID">LineTradeDeliveryID</span> | xsd:token | An identifier, at line level, for this trade delivery. | UN01013438 | Line_ Trade Delivery. Identification. Identifier
<span id="LineTradeDeliveryPartialDeliveryAllowedIndicator">LineTradeDeliveryPartialDeliveryAllowedIndicator</span> | xsd:boolean | The indication, at line level, of whether or not this trade delivery can be partially delivered. | UN01011756 | Line_ Trade Delivery. Partial Delivery Allowed. Indicator
<span id="LineTradeDeliverySubordinateID">LineTradeDeliverySubordinateID</span> | xsd:token | A subordinate identifier, at line level, for this trade delivery. | UN01013439 | Line_ Trade Delivery. Subordinate_ Identification. Identifier
<span id="UsedLogisticsLabel">UsedLogisticsLabel</span> | [edi3:Label](#Label) | A logistics label, at line level, used for this trade delivery. | UN01012670 | Line_ Trade Delivery. Used. Logistics_ Label
<span id="LineTradeDeliveryInventoryManager">LineTradeDeliveryInventoryManager</span> | [edi3:TradeParty](#TradeParty) | An inventory manager party, at line level, for this trade delivery. | UN01013016 | Line_ Trade Delivery. Inventory Manager. Trade_ Party
<span id="LineTradeDeliveryLogisticsPackage">LineTradeDeliveryLogisticsPackage</span> | [edi3:Package](#Package) | A logistics package, at line level, specified for this trade delivery. | UN01012125 | Line_ Trade Delivery. Specified. Logistics_ Package
<span id="LineTradeDeliveryNetWeight">LineTradeDeliveryNetWeight</span> | xsd:decimal | The measure, at line level, of the net weight (mass) of this trade delivery. | UN01011767 | Line_ Trade Delivery. Net Weight. Measure
<span id="OrderSchedule">OrderSchedule</span> | [edi3:Schedule](#Schedule) | A supply chain order schedule, at line level, for this trade delivery. | UN01013020 | Line_ Trade Delivery. Order. Supply Chain_ Schedule
<span id="ReceiptSchedule">ReceiptSchedule</span> | [edi3:Schedule](#Schedule) | A supply chain receipt schedule, at line level, for this trade delivery. | UN01013021 | Line_ Trade Delivery. Receipt. Supply Chain_ Schedule
<span id="LineTradeDeliveryActualDespatchEvent">LineTradeDeliveryActualDespatchEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | An actual despatch event, at line level, for this trade delivery. | UN01011786 | Line_ Trade Delivery. Actual_ Despatch. Supply Chain_ Event
<span id="LineTradeDeliveryActualDeliveryEvent">LineTradeDeliveryActualDeliveryEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | An actual delivery event, at line level, for this trade delivery. | UN01011790 | Line_ Trade Delivery. Actual_ Delivery. Supply Chain_ Event
<span id="LineTradeDeliveryDueInRequestedQuantity">LineTradeDeliveryDueInRequestedQuantity</span> | xsd:decimal | The due in requested quantity, at line level, for this trade delivery. | UN01013001 | Line_ Trade Delivery. Due In_ Requested. Quantity
<span id="OrderQuantity">OrderQuantity</span> | xsd:decimal | The quantity, at line level, ordered for this trade delivery. | UN01013442 | Line_ Trade Delivery. Order. Quantity
<span id="LineTradeDeliveryDeliveryNoteDocument">LineTradeDeliveryDeliveryNoteDocument</span> | [edi3:Document](#Document) | The delivery note document, at line level, referenced for this trade delivery. | UN01011795 | Line_ Trade Delivery. Delivery Note. Referenced_ Document
<span id="LineTradeDeliveryIncludedPackaging">LineTradeDeliveryIncludedPackaging</span> | [edi3:Packaging](#Packaging) | Packaging included, at line level, in this trade delivery. | UN01011776 | Line_ Trade Delivery. Included. Supply Chain_ Packaging
<span id="QuantityVariationReasonText">QuantityVariationReasonText</span> | xsd:string | A reason, expressed as text, for a quantity variation, at line level, for this trade delivery. | UN01013451 | Line_ Trade Delivery. Quantity Variation_ Reason. Text
<span id="LineTradeDeliveryNetVolume">LineTradeDeliveryNetVolume</span> | xsd:decimal | The measure, at line level, of the net volume of this line trade delivery. | UN01011770 | Line_ Trade Delivery. Net Volume. Measure
<span id="LineTradeDeliveryPackageQuantity">LineTradeDeliveryPackageQuantity</span> | xsd:decimal | The number of packages, at line level, in this trade delivery. | UN01011764 | Line_ Trade Delivery. Package. Quantity
<span id="LineTradeDeliveryReceivingAdviceDocument">LineTradeDeliveryReceivingAdviceDocument</span> | [edi3:Document](#Document) | A receiving advice document, at line level, referenced for this trade delivery. | UN01011794 | Line_ Trade Delivery. Receiving Advice. Referenced_ Document
<span id="DeliverySchedule">DeliverySchedule</span> | [edi3:Schedule](#Schedule) | A supply chain delivery schedule, at line level, for this trade delivery. | UN01013018 | Line_ Trade Delivery. Delivery. Supply Chain_ Schedule
<span id="LineTradeDeliveryActualLoadingEvent">LineTradeDeliveryActualLoadingEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | The actual loading event, at line level, for this trade delivery. | UN01013456 | Line_ Trade Delivery. Actual_ Loading. Supply Chain_ Event
<span id="LineTradeDeliveryDespatchedQuantity">LineTradeDeliveryDespatchedQuantity</span> | xsd:decimal | The quantity, at line level, despatched for this trade delivery. | UN01011943 | Line_ Trade Delivery. Despatched. Quantity


<h1 id="HeaderTradeDelivery">HeaderTradeDelivery</h1>

Type: rdf:Class

Definition: Shipping arrangements and movement of products and or services including despatch and delivery at a header level.

Unique UN Assigned ID: UN01011603

Dictionary Entry Name: Header_ Trade Delivery. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="HeaderTradeDeliveryPlannedConsignment">HeaderTradeDeliveryPlannedConsignment</span> | [edi3:Consignment](#Consignment) | A consignment, at header level, planned for this trade delivery. | UN01011638 | Header_ Trade Delivery. Planned. Supply Chain_ Consignment
<span id="HeaderTradeDeliveryDespatchedQuantity">HeaderTradeDeliveryDespatchedQuantity</span> | xsd:decimal | The quantity, at header level, despatched in this trade delivery. | UN01011610 | Header_ Trade Delivery. Despatched. Quantity
<span id="UltimateShipToDeliveryEvent">UltimateShipToDeliveryEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | The ultimate ship to delivery event, at header level, for this trade delivery. | UN01011640 | Header_ Trade Delivery. Ultimate Ship To_ Delivery. Supply Chain_ Event
<span id="HeaderTradeDeliveryAdditionalDocument">HeaderTradeDeliveryAdditionalDocument</span> | [edi3:Document](#Document) | An additional document, at header level, referenced for this trade delivery. | UN01011631 | Header_ Trade Delivery. Additional. Referenced_ Document
<span id="HeaderTradeDeliveryHandlingInstructions">HeaderTradeDeliveryHandlingInstructions</span> | [edi3:HandlingInstructions](#HandlingInstructions) | Handling instructions, at header level, specified for this trade delivery. | UN01013428 | Header_ Trade Delivery. Specified. Handling_ Instructions
<span id="HeaderTradeDeliveryDespatchAdviceDocument">HeaderTradeDeliveryDespatchAdviceDocument</span> | [edi3:Document](#Document) | The despatch advice document, at header level, referenced for this trade delivery. | UN01011632 | Header_ Trade Delivery. Despatch Advice. Referenced_ Document
<span id="HeaderTradeDeliveryRelatedConsignment">HeaderTradeDeliveryRelatedConsignment</span> | [edi3:Consignment](#Consignment) | A consignment, at header level, related to this trade delivery. | UN01011617 | Header_ Trade Delivery. Related. Supply Chain_ Consignment
<span id="HeaderTradeDeliveryIncludedPackaging">HeaderTradeDeliveryIncludedPackaging</span> | [edi3:Packaging](#Packaging) | Packaging, at header level, included in this trade delivery. | UN01011616 | Header_ Trade Delivery. Included. Supply Chain_ Packaging
<span id="HeaderTradeDeliveryPlannedPickUpEvent">HeaderTradeDeliveryPlannedPickUpEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | The pick-up event, at header level, planned for this trade delivery. | UN01013436 | Header_ Trade Delivery. Planned_ Pick-Up. Supply Chain_ Event
<span id="UltimateShipToDeliveryDateTime">UltimateShipToDeliveryDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value, at header level, when this trade delivery is delivered to the ultimate ship to party. | UN01013422 | Header_ Trade Delivery. Ultimate Ship To Delivery. Date Time
<span id="HeaderTradeDeliveryRequestedDespatchEvent">HeaderTradeDeliveryRequestedDespatchEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | A despatch event, at header level, requested for this trade delivery. | UN00008873 | Header_ Trade Delivery. Requested_ Despatch. Supply Chain_ Event
<span id="HeaderTradeDeliveryOverDeliveryAllowedIndicator">HeaderTradeDeliveryOverDeliveryAllowedIndicator</span> | xsd:boolean | The indication, at header level, of whether or not over delivery is allowed for this trade delivery. | UN01013421 | Header_ Trade Delivery. Over Delivery Allowed. Indicator
<span id="RemainingRequestedQuantity">RemainingRequestedQuantity</span> | xsd:decimal | The remaining quantity, at header level, requested for this trade delivery. | UN01011608 | Header_ Trade Delivery. Remaining_ Requested. Quantity
<span id="HeaderTradeDeliveryConfirmedPickUpEvent">HeaderTradeDeliveryConfirmedPickUpEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | The pick-up event, at header level, confirmed for this trade delivery. | UN01013432 | Header_ Trade Delivery. Confirmed_ Pick-Up. Supply Chain_ Event
<span id="GoodsPhysicalStateTypeText">GoodsPhysicalStateTypeText</span> | xsd:string | A type, expressed as text, for the physical state of the goods, at header level, for this trade delivery. | UN01013425 | Header_ Trade Delivery. Goods Physical State_ Type. Text
<span id="HeaderTradeDeliveryRequestedQuantity">HeaderTradeDeliveryRequestedQuantity</span> | xsd:decimal | The quantity, at header level, requested for this trade delivery. | UN01011607 | Header_ Trade Delivery. Requested. Quantity
<span id="HeaderTradeDeliveryID">HeaderTradeDeliveryID</span> | xsd:token | The identifier, at header level, for this trade delivery. | UN01011604 | Header_ Trade Delivery. Identification. Identifier
<span id="HeaderTradeDeliveryPreviousDeliveryEvent">HeaderTradeDeliveryPreviousDeliveryEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | A previous delivery event, at header level, for this trade delivery. | UN01011642 | Header_ Trade Delivery. Previous_ Delivery. Supply Chain_ Event
<span id="GoodsPhysicalStateDescriptionCode">GoodsPhysicalStateDescriptionCode</span> | xsd:token | The code specifying a description for the physical state of the goods, at header level, for this trade delivery. | UN01013426 | Header_ Trade Delivery. Goods Physical State_ Description. Code
<span id="HeaderTradeDeliveryConsumptionReportDocument">HeaderTradeDeliveryConsumptionReportDocument</span> | [edi3:Document](#Document) | The consumption report document, at header level, referenced for this trade delivery. | UN01011641 | Header_ Trade Delivery. Consumption Report. Referenced_ Document
<span id="HeaderTradeDeliveryPlannedDeliveryEvent">HeaderTradeDeliveryPlannedDeliveryEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | A delivery event, at header level, planned for this trade delivery. | UN01011627 | Header_ Trade Delivery. Planned_ Delivery. Supply Chain_ Event
<span id="HeaderTradeDeliveryGoodsOwnershipChangeDateTime">HeaderTradeDeliveryGoodsOwnershipChangeDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value, at header level, when the goods ownership of this trade delivery changed. | UN01013423 | Header_ Trade Delivery. Goods Ownership Change. Date Time
<span id="HeaderTradeDeliveryFinalDestinationCountry">HeaderTradeDeliveryFinalDestinationCountry</span> | [edi3:Country](#Country) | The country of final destination, at header level, for this header trade delivery. | UN01012124 | Header_ Trade Delivery. Final Destination. Trade_ Country
<span id="HeaderTradeDeliveryDisposalParty">HeaderTradeDeliveryDisposalParty</span> | [edi3:TradeParty](#TradeParty) | A disposal party, at header level, for this trade delivery. | UN01013429 | Header_ Trade Delivery. Disposal. Trade_ Party
<span id="HeaderTradeDeliveryDueInForecastedQuantity">HeaderTradeDeliveryDueInForecastedQuantity</span> | xsd:decimal | The due in forecasted quantity, at header level, for this trade delivery. | UN01011613 | Header_ Trade Delivery. Due In_ Forecasted. Quantity
<span id="HeaderTradeDeliveryShipToParty">HeaderTradeDeliveryShipToParty</span> | [edi3:TradeParty](#TradeParty) | The ship to party, at header level, for this trade delivery. | UN01011618 | Header_ Trade Delivery. Ship To. Trade_ Party
<span id="HeaderTradeDeliveryDueInAvailableQuantity">HeaderTradeDeliveryDueInAvailableQuantity</span> | xsd:decimal | The due in available quantity, at header level, for this trade delivery. | UN01011612 | Header_ Trade Delivery. Due In_ Available. Quantity
<span id="HeaderTradeDeliveryPartialDeliveryAllowedIndicator">HeaderTradeDeliveryPartialDeliveryAllowedIndicator</span> | xsd:boolean | The indication, at header level, of whether or not this trade delivery can be partially delivered. | UN01011605 | Header_ Trade Delivery. Partial Delivery Allowed. Indicator
<span id="HeaderTradeDeliveryInventoryManager">HeaderTradeDeliveryInventoryManager</span> | [edi3:TradeParty](#TradeParty) | An inventory manager party, at header level, for this trade delivery. | UN01011635 | Header_ Trade Delivery. Inventory Manager. Trade_ Party
<span id="HeaderTradeDeliveryShipmentScheduleDocument">HeaderTradeDeliveryShipmentScheduleDocument</span> | [edi3:Document](#Document) | The shipment schedule document, referenced at header level, for this trade delivery. | UN01011637 | Header_ Trade Delivery. Shipment Schedule. Referenced_ Document
<span id="HeaderTradeDeliveryAgreedQuantity">HeaderTradeDeliveryAgreedQuantity</span> | xsd:decimal | The quantity, at header level, agreed for this trade delivery. | UN01011609 | Header_ Trade Delivery. Agreed. Quantity
<span id="HeaderTradeDeliveryGoodsReceiptNote">HeaderTradeDeliveryGoodsReceiptNote</span> | [edi3:Document](#Document) | A goods receipt note document, at header level, referenced for this trade delivery. | UN01013433 | Header_ Trade Delivery. Goods Receipt Note. Referenced_ Document
<span id="HeaderTradeDeliveryRequestedDeliveryEvent">HeaderTradeDeliveryRequestedDeliveryEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | A delivery event, at header level, requested for this trade delivery. | UN01011626 | Header_ Trade Delivery. Requested_ Delivery. Supply Chain_ Event
<span id="HeaderTradeDeliveryActualReceiptEvent">HeaderTradeDeliveryActualReceiptEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | The actual receipt event, at header level, for this trade delivery. | UN01011629 | Header_ Trade Delivery. Actual_ Receipt. Supply Chain_ Event
<span id="HeaderTradeDeliveryPlannedShipToDeliveryEvent">HeaderTradeDeliveryPlannedShipToDeliveryEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | The planned ship to delivery event, at header level, for this trade delivery. | UN01013434 | Header_ Trade Delivery. Planned Ship To_ Delivery. Supply Chain_ Event
<span id="PlannedShipFromDeliveryEvent">PlannedShipFromDeliveryEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | The event of the planned ship from delivery, at header level, for this trade delivery. | UN01012671 | Header_ Trade Delivery. Planned Ship From_ Delivery. Supply Chain_ Event
<span id="HeaderTradeDeliveryConfirmedDespatchEvent">HeaderTradeDeliveryConfirmedDespatchEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | The despatch event, at header level, confirmed for this trade delivery. | UN01013431 | Header_ Trade Delivery. Confirmed_ Despatch. Supply Chain_ Event
<span id="HeaderTradeDeliveryPlannedDespatchEvent">HeaderTradeDeliveryPlannedDespatchEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | A despatch event, at header level, planned for this trade delivery. | UN01011622 | Header_ Trade Delivery. Planned_ Despatch. Supply Chain_ Event
<span id="HeaderTradeDeliveryInformationNote">HeaderTradeDeliveryInformationNote</span> | [edi3:Note](#Note) | A note with information, at header level, for this trade delivery. | UN01011636 | Header_ Trade Delivery. Information. Note
<span id="HeaderTradeDeliveryModificationForecastedQuantity">HeaderTradeDeliveryModificationForecastedQuantity</span> | xsd:decimal | The modification of a previously forecasted quantity, at header level, for this trade delivery. | UN01011611 | Header_ Trade Delivery. Modification_ Forecasted. Quantity
<span id="PlannedReleaseEvent">PlannedReleaseEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | The release event, at header level, planned for this trade delivery. | UN01011625 | Header_ Trade Delivery. Planned_ Release. Supply Chain_ Event
<span id="HeaderTradeDeliveryShipFromParty">HeaderTradeDeliveryShipFromParty</span> | [edi3:TradeParty](#TradeParty) | The ship from party, at header level, for this trade delivery. | UN01011620 | Header_ Trade Delivery. Ship From. Trade_ Party
<span id="HeaderTradeDeliveryActualDeliveryEvent">HeaderTradeDeliveryActualDeliveryEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | An actual delivery event, at header level, for this trade delivery. | UN01011628 | Header_ Trade Delivery. Actual_ Delivery. Supply Chain_ Event
<span id="HeaderTradeDeliveryActualDespatchEvent">HeaderTradeDeliveryActualDespatchEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | An actual despatch event, at header level, for this trade delivery. | UN01011623 | Header_ Trade Delivery. Actual_ Despatch. Supply Chain_ Event
<span id="HeaderTradeDeliveryDeliveryInstructions">HeaderTradeDeliveryDeliveryInstructions</span> | [edi3:DeliveryInstructions](#DeliveryInstructions) | Delivery instructions, at header level, specified for this trade delivery. | UN01011621 | Header_ Trade Delivery. Specified. Delivery_ Instructions
<span id="HeaderTradeDeliverySubordinateID">HeaderTradeDeliverySubordinateID</span> | xsd:token | A subordinate identifier, at header level, for this trade delivery. | UN01013418 | Header_ Trade Delivery. Subordinate_ Identification. Identifier
<span id="GoodsPhysicalStateDescriptionText">GoodsPhysicalStateDescriptionText</span> | xsd:string | A textual description for the physical state of the goods, at header level, for this trade delivery. | UN01013427 | Header_ Trade Delivery. Goods Physical State_ Description. Text
<span id="HeaderTradeDeliveryUltimateShipToParty">HeaderTradeDeliveryUltimateShipToParty</span> | [edi3:TradeParty](#TradeParty) | The ultimate ship to party, at header level, for this trade delivery. | UN01011619 | Header_ Trade Delivery. Ultimate_ Ship To. Trade_ Party
<span id="HeaderTradeDeliveryConfirmedReleaseEvent">HeaderTradeDeliveryConfirmedReleaseEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | The confirmed release event, at header level, for this trade delivery. | UN01011639 | Header_ Trade Delivery. Confirmed_ Release. Supply Chain_ Event
<span id="GoodsPhysicalStateTypeCode">GoodsPhysicalStateTypeCode</span> | xsd:token | The code specifying the type of physical state of the goods, at header level, for this trade delivery. | UN01013424 | Header_ Trade Delivery. Goods Physical State_ Type. Code
<span id="HeaderTradeDeliveryActualUnloadingEvent">HeaderTradeDeliveryActualUnloadingEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | The actual unloading event, at header level, for this trade delivery. | UN01013430 | Header_ Trade Delivery. Actual_ Unloading. Supply Chain_ Event
<span id="HeaderTradeDeliveryDueInRequestedQuantity">HeaderTradeDeliveryDueInRequestedQuantity</span> | xsd:decimal | The due in requested quantity, at header level, for this trade delivery. | UN01011614 | Header_ Trade Delivery. Due In_ Requested. Quantity
<span id="HeaderTradeDeliveryBuyerOrderDateTime">HeaderTradeDeliveryBuyerOrderDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value, at header level, of the buyer order for this trade delivery. | UN01013437 | Header_ Trade Delivery. Buyer_ Order. Date Time
<span id="HeaderTradeDeliveryAcceptanceEvent">HeaderTradeDeliveryAcceptanceEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | An acceptance delivery event, at header level, for this trade delivery. | UN01013435 | Header_ Trade Delivery. Acceptance. Supply Chain_ Event
<span id="HeaderTradeDeliveryActualLoadingEvent">HeaderTradeDeliveryActualLoadingEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | The actual loading event, at header level, for this trade delivery. | UN01011630 | Header_ Trade Delivery. Actual_ Loading. Supply Chain_ Event
<span id="PickUpAvailabilityDateTime">PickUpAvailabilityDateTime</span> | xsd:dateTime | The formatted date, time, date time, or other date time value, at header level, when this trade delivery is available for pick-up. | UN01011615 | Header_ Trade Delivery. Formatted_ Pick-Up Availability. Date Time
<span id="HeaderTradeDeliveryReceivingAdviceDocument">HeaderTradeDeliveryReceivingAdviceDocument</span> | [edi3:Document](#Document) | A receiving advice document, at header level, referenced for this trade delivery. | UN01011633 | Header_ Trade Delivery. Receiving Advice. Referenced_ Document
<span id="HeaderTradeDeliveryStatusCode">HeaderTradeDeliveryStatusCode</span> | xsd:token | The code specifying the status, at header level, for this trade delivery. | UN01013419 | Header_ Trade Delivery. Status. Code
<span id="HeaderTradeDeliveryFullyDeliveredIndicator">HeaderTradeDeliveryFullyDeliveredIndicator</span> | xsd:boolean | The indication, at header level, of whether or not this trade delivery is fully delivered. | UN01013420 | Header_ Trade Delivery. Fully Delivered. Indicator
<span id="HeaderTradeDeliveryPackingListDocument">HeaderTradeDeliveryPackingListDocument</span> | [edi3:Document](#Document) | The packing list document, at header level, referenced for this trade delivery. | UN01011937 | Header_ Trade Delivery. Packing List. Referenced_ Document
<span id="HeaderTradeDeliveryDeliveryNoteDocument">HeaderTradeDeliveryDeliveryNoteDocument</span> | [edi3:Document](#Document) | The delivery note document, at header level, referenced for this trade delivery. | UN01011634 | Header_ Trade Delivery. Delivery Note. Referenced_ Document
<span id="HeaderTradeDeliveryFinalDeliveryIndicator">HeaderTradeDeliveryFinalDeliveryIndicator</span> | xsd:boolean | The indication, at header level, of whether or not this trade delivery is the final delivery. | UN01011606 | Header_ Trade Delivery. Final Delivery. Indicator


<h1 id="Country">Country</h1>

Type: rdf:Class

Definition: The area of land that belongs to a nation together with its properties, such as population, political organization, etc., used or referenced for trade purposes.

Unique UN Assigned ID: UN01002552

Dictionary Entry Name: Trade_ Country. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="SubDivision">SubDivision</span> | [edi3:CountrySubDivision](#CountrySubDivision) | A trade country sub-division that is subordinate to this trade country, such as a state, a county, a canton, a province. | UN01002555 | Trade_ Country. Subordinate. Trade_ Country Sub-Division
<span id="CountryCode">CountryCode</span> | xsd:token | A unique identifier for this trade country. | UN01002553 | Trade_ Country. Identification. Identifier


<h1 id="Seal">Seal</h1>

Type: rdf:Class

Definition: A device used to secure an object and protect it from unauthorized entry or tampering during transport or other logistics operations.

Unique UN Assigned ID: UN01003713

Dictionary Entry Name: Logistics_ Seal. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="SealingPartyRoleCode">SealingPartyRoleCode</span> | xsd:token | The code specifying the role of the party responsible for the sealing of this logistics seal. | UN01003718 | Logistics_ Seal. Sealing Party Role. Code
<span id="SealID">SealID</span> | xsd:token | A unique identifier for this logistics seal. | UN01003714 | Logistics_ Seal. Identification. Identifier
<span id="SealTypeCode">SealTypeCode</span> | xsd:token | The code specifying the type of logistics seal. | UN01003716 | Logistics_ Seal. Type. Code
<span id="MaximumID">MaximumID</span> | xsd:token | The maximum unique identifier used for these logistics seals. | UN01003715 | Logistics_ Seal. Maximum_ Identification. Identifier
<span id="IssuingParty">IssuingParty</span> | [edi3:TradeParty](#TradeParty) | The party issuing this logistics seal. | UN01003720 | Logistics_ Seal. Issuing. Trade_ Party


<h1 id="Package">Package</h1>

Type: rdf:Class

Definition: A self-contained wrapping or container within which goods can be contained for logistics purposes, such as a box or a barrel which can be filled, partially filled or empty.

Unique UN Assigned ID: UN01003689

Dictionary Entry Name: Logistics_ Package. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="PackageID">PackageID</span> | xsd:token | The unique identifier for this logistics package. | UN01003700 | Logistics_ Package. Identification. Identifier
<span id="PackageLevelCode">PackageLevelCode</span> | xsd:token | The code specifying the level of this logistics package. | UN01003696 | Logistics_ Package. Level. Code
<span id="PackageDescription">PackageDescription</span> | xsd:string | A textual description of this logistics package. | UN01003703 | Logistics_ Package. Description. Text
<span id="PackageNominalGrossWeight">PackageNominalGrossWeight</span> | xsd:decimal | The measure of the nominal gross weight (mass) of this logistics package and its contents. | UN01003692 | Logistics_ Package. Nominal_ Gross Weight. Measure
<span id="PackageParentID">PackageParentID</span> | xsd:token | The unique parent identifier for this logistics package. | UN01003702 | Logistics_ Package. Parent_ Identification. Identifier
<span id="UsedPackaging">UsedPackaging</span> | [edi3:Packaging](#Packaging) | Supply chain packaging used for this logistics package. | UN01003709 | Logistics_ Package. Used. Supply Chain_ Packaging
<span id="PackageSeriesStartID">PackageSeriesStartID</span> | xsd:token | The unique start identifier of a series of packages within this logistics package. | UN01004898 | Logistics_ Package. Series Start_ Identification. Identifier
<span id="PackagePerPackageUnitQuantity">PackagePerPackageUnitQuantity</span> | xsd:decimal | A number of units per package in this logistics package. | UN01012961 | Logistics_ Package. Per Package_ Unit. Quantity
<span id="PackageShippingMarks">PackageShippingMarks</span> | [edi3:ShippingMarks](#ShippingMarks) | Physical shipping marks and barcode information for this logistics package. | UN01003705 | Logistics_ Package. Physical. Logistics_ Shipping Marks
<span id="PackageSequenceNumber">PackageSequenceNumber</span> | xsd:decimal | The sequence number of this logistics package. | UN01003699 | Logistics_ Package. Sequence. Numeric
<span id="LogisticsPackageTypeCode">LogisticsPackageTypeCode</span> | xsd:token | A code specifying the type of logistics package. | UN01003697 | Logistics_ Package. Type. Code
<span id="PackageInformation">PackageInformation</span> | xsd:string | Information, expressed as text, for this logistics package. | UN01003704 | Logistics_ Package. Information. Text
<span id="PackageNominalGrossVolume">PackageNominalGrossVolume</span> | xsd:decimal | The measure of the nominal gross volume of this logistics package. | UN01003695 | Logistics_ Package. Nominal_ Gross Volume. Measure
<span id="PackageTypeText">PackageTypeText</span> | xsd:string | A type, expressed as text, of this logistics package. | UN01003698 | Logistics_ Package. Type. Text
<span id="PackageDimensions">PackageDimensions</span> | [edi3:SpatialDimension](#SpatialDimension) | The linear spatial dimensions of this logistics package. | UN01003707 | Logistics_ Package. Linear. Spatial_ Dimension
<span id="PackageItemQuantity">PackageItemQuantity</span> | xsd:decimal | The number of logistics packages at this level. | UN01003690 | Logistics_ Package. Item. Quantity
<span id="PackageGrossWeight">PackageGrossWeight</span> | xsd:decimal | The measure of the gross weight (mass) of this logistics package and its contents. | UN01003691 | Logistics_ Package. Gross Weight. Measure
<span id="PackageNetWeight">PackageNetWeight</span> | xsd:decimal | The measure of the net weight of this logistics package, i.e. the weight (mass) of the contents. | UN01003693 | Logistics_ Package. Net Weight. Measure
<span id="PackageSeriesEndID">PackageSeriesEndID</span> | xsd:token | The unique identifier of the end of a series of packages within this logistics package. | UN01004899 | Logistics_ Package. Series End_ Identification. Identifier
<span id="PackageGlobalID">PackageGlobalID</span> | xsd:token | The unique global identifier for this logistics package. | UN01003701 | Logistics_ Package. Global_ Identification. Identifier
<span id="PackageReturnableIndicator">PackageReturnableIndicator</span> | xsd:boolean | The indication of whether or not this logistics package is returnable. | UN01012566 | Logistics_ Package. Returnable. Indicator
<span id="DespatchNoteDocument">DespatchNoteDocument</span> | [edi3:Document](#Document) | A despatch note associated with this logistics package. | UN01011828 | Logistics_ Package. Despatch Note_ Associated. Referenced_ Document
<span id="PackageGrossVolume">PackageGrossVolume</span> | xsd:decimal | The measure of the gross volume of this logistics package. | UN01003694 | Logistics_ Package. Gross Volume. Measure
<span id="PackageColourCode">PackageColourCode</span> | xsd:token | The code specifying the colour of this logistics package. | UN01012758 | Logistics_ Package. Colour. Code


<h1 id="ReferencedPackage">ReferencedPackage</h1>

Type: rdf:Class

Definition: A referenced self-contained wrapping or container within which goods can be contained for logistics purposes.

Unique UN Assigned ID: UN01006790

Dictionary Entry Name: Referenced_ Logistics_ Package. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="ReferencedPackageSeriesEndID">ReferencedPackageSeriesEndID</span> | xsd:token | The identifier of the end of a series of packages within this referenced logistics package. | UN01006799 | Referenced_ Logistics_ Package. Series End_ Identification. Identifier
<span id="ReferencedPackageSeriesStartID">ReferencedPackageSeriesStartID</span> | xsd:token | The identifier of the start of a series of packages within this referenced logistics package. | UN01006798 | Referenced_ Logistics_ Package. Series Start_ Identification. Identifier
<span id="ReferencedPackageInformation">ReferencedPackageInformation</span> | xsd:string | Information, expressed as text, for this referenced logistics package. | UN01013105 | Referenced_ Logistics_ Package. Information. Text
<span id="ReferencedPackageColourCode">ReferencedPackageColourCode</span> | xsd:token | The code specifying the colour of this referenced logistics package. | UN01012741 | Referenced_ Logistics_ Package. Colour. Code
<span id="ReferencedPackageGlobalID">ReferencedPackageGlobalID</span> | xsd:token | The global identifier for this referenced logistics package. | UN01006796 | Referenced_ Logistics_ Package. Global_ Identification. Identifier
<span id="ReferencedPackageNominalGrossVolume">ReferencedPackageNominalGrossVolume</span> | xsd:decimal | The measure of the nominal gross volume of this referenced logistics package. | UN01013103 | Referenced_ Logistics_ Package. Nominal_ Gross Volume. Measure
<span id="ReferencedPackageGrossWeight">ReferencedPackageGrossWeight</span> | xsd:decimal | The measure of the gross weight (mass) of this referenced logistics package and its contents. | UN01013099 | Referenced_ Logistics_ Package. Gross Weight. Measure
<span id="ReferencedPackageItemQuantity">ReferencedPackageItemQuantity</span> | xsd:decimal | The number of referenced logistics packages at this level. | UN01006791 | Referenced_ Logistics_ Package. Item. Quantity
<span id="ReferencedPackageLevelCode">ReferencedPackageLevelCode</span> | xsd:token | The code specifying the level of this referenced logistics package. | UN01006792 | Referenced_ Logistics_ Package. Level. Code
<span id="ReferencedPackagePerPackageUnitQuantity">ReferencedPackagePerPackageUnitQuantity</span> | xsd:decimal | A number of units per package in this referenced logistics package. | UN01013106 | Referenced_ Logistics_ Package. Per Package_ Unit. Quantity
<span id="ReferencedPackageTypeCode">ReferencedPackageTypeCode</span> | xsd:token | The code specifying the type of referenced logistics package. | UN01006793 | Referenced_ Logistics_ Package. Type. Code
<span id="ReferencedPackageSequenceNumber">ReferencedPackageSequenceNumber</span> | xsd:decimal | The sequence number of this referenced logistics package. | UN01006794 | Referenced_ Logistics_ Package. Sequence. Numeric
<span id="ReferencedPackageGrossVolume">ReferencedPackageGrossVolume</span> | xsd:decimal | The measure of the gross volume of this referenced logistics package. | UN01013102 | Referenced_ Logistics_ Package. Gross Volume. Measure
<span id="ReferencedPackagePhysicalShippingMarks">ReferencedPackagePhysicalShippingMarks</span> | [edi3:ShippingMarks](#ShippingMarks) | Physical logistics shipping marks in this referenced logistics package. | UN01013107 | Referenced_ Logistics_ Package. Physical. Logistics_ Shipping Marks
<span id="ReferencedPackageID">ReferencedPackageID</span> | xsd:token | The identifier for this referenced logistics package. | UN01006795 | Referenced_ Logistics_ Package. Identification. Identifier
<span id="ReferencedPackageParentID">ReferencedPackageParentID</span> | xsd:token | The parent identifier for this referenced logistics package. | UN01006797 | Referenced_ Logistics_ Package. Parent_ Identification. Identifier
<span id="ReferencedPackageDescription">ReferencedPackageDescription</span> | xsd:string | A textual description of this referenced logistics package. | UN01013104 | Referenced_ Logistics_ Package. Description. Text
<span id="ReferencedPackageTypeText">ReferencedPackageTypeText</span> | xsd:string | A type, expressed as text, of this referenced logistics package. | UN01013098 | Referenced_ Logistics_ Package. Type. Text
<span id="ReferencedPackageNetWeight">ReferencedPackageNetWeight</span> | xsd:decimal | The measure of the net weight (mass) of the contents of this referenced logistics package. | UN01013101 | Referenced_ Logistics_ Package. Net Weight. Measure


<h1 id="ContactPerson">ContactPerson</h1>

Type: rdf:Class

Definition: An individual human being in a position to give assistance or information.

Unique UN Assigned ID: UN01005145

Dictionary Entry Name: Contact_ Person. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="SpecifiedEmployerIdentity">SpecifiedEmployerIdentity</span> | [edi3:EmployerIdentity](#EmployerIdentity) | An employer identity specified for this contact person. | UN01013205 | Contact_ Person. Specified. Employer_ Identity
<span id="ContactPersonRoleText">ContactPersonRoleText</span> | xsd:string | A role, expressed as text, for this contact person. | UN01013201 | Contact_ Person. Role. Text
<span id="SpecifiedPersonIdentity">SpecifiedPersonIdentity</span> | [edi3:PersonIdentity](#PersonIdentity) | The person identity specified for this contact person. | UN01013206 | Contact_ Person. Specified. Person_ Identity
<span id="ContactPersonTelephone">ContactPersonTelephone</span> | [edi3:TelecommunicationCommunication](#TelecommunicationCommunication) | Telephone communication information for this contact person. | UN01005153 | Contact_ Person. Telephone. Telecommunication_ Communication
<span id="ContactPersonEmailAddress">ContactPersonEmailAddress</span> | [edi3:EmailCommunication](#EmailCommunication) | The email Uniform Resource Identifier (URI) communication for this contact person. | UN01005155 | Contact_ Person. Email_ URI. Email_ Communication
<span id="ContactPersonFax">ContactPersonFax</span> | [edi3:TelecommunicationCommunication](#TelecommunicationCommunication) | Facsimile communication information for this contact person. | UN01005154 | Contact_ Person. Fax. Telecommunication_ Communication
<span id="ContactPersonGivenName">ContactPersonGivenName</span> | xsd:string | The name, expressed as text, given to this contact person, usually by parents at birth. | UN01005147 | Contact_ Person. Given Name. Text
<span id="SpecifiedBirthAddress">SpecifiedBirthAddress</span> | [edi3:BirthAddress](#BirthAddress) | The birth address specified for this contact person. | UN01013204 | Contact_ Person. Specified. Birth_ Address
<span id="ContactPersonFamilyName">ContactPersonFamilyName</span> | xsd:string | The name, expressed as text, that this contact person shares with members of his/her family. | UN01005150 | Contact_ Person. Family Name. Text
<span id="ResidenceCountryCode">ResidenceCountryCode</span> | xsd:token | The identifier of the residence country of this contact person. | UN01013203 | Contact_ Person. Residence Country. Identifier
<span id="MiddleName">MiddleName</span> | xsd:string | The middle name, expressed as text, of this contact person, usually given by parents at birth. | UN01005148 | Contact_ Person. Middle Name. Text
<span id="SpecifiedTaxRegistration">SpecifiedTaxRegistration</span> | [edi3:TaxRegistration](#TaxRegistration) | A tax registration specified for this contact person. | UN01013207 | Contact_ Person. Specified. Tax_ Registration
<span id="ContactPersonBirthDateTime">ContactPersonBirthDateTime</span> | xsd:dateTime | The date, time, date time or other date time value which specifies the birth date for this contact person. | UN01012119 | Contact_ Person. Birth. Date Time


<h1 id="TransportPerson">TransportPerson</h1>

Type: rdf:Class

Definition: A transport related person, such as a member of a crew or a passenger.

Unique UN Assigned ID: UN01004815

Dictionary Entry Name: Transport_ Person. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="TransportPersonRoleText">TransportPersonRoleText</span> | xsd:string | A role, expressed as text, of this transport person. | UN01004820 | Transport_ Person. Role. Text
<span id="CrewTravelEffects">CrewTravelEffects</span> | [edi3:PersonalEffects](#PersonalEffects) | Personal effects use declared by a transport person. | UN01013147 | Transport_ Person. Declared. Specified_ Personal Effects
<span id="NationalityCountry">NationalityCountry</span> | [edi3:Country](#Country) | A country that constitutes a nationality by origin, birth, or naturalization for this transport person. | UN01004821 | Transport_ Person. Nationality. Trade_ Country
<span id="TransportPersonLanguageCode">TransportPersonLanguageCode</span> | xsd:token | A unique identifier of a language related to this transport person, such as their spoken or correspondence language. | UN01004819 | Transport_ Person. Language. Identifier
<span id="TransportPersonMobileTelephone">TransportPersonMobileTelephone</span> | [edi3:UniversalCommunication](#UniversalCommunication) | Mobile telephone communication information for this transport person. | UN01013149 | Transport_ Person. Mobile_ Telephone. Universal_ Communication
<span id="EmbarkationLocation">EmbarkationLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | An embarkation location for this transport person. | UN01013143 | Transport_ Person. Embarkation. Logistics_ Location
<span id="DisembarkationLocation">DisembarkationLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | A disembarkation location for this transport person. | UN01013144 | Transport_ Person. Disembarkation. Logistics_ Location
<span id="TransportPersonFamilyName">TransportPersonFamilyName</span> | xsd:string | A family name, expressed as text, for this transport person. | UN01013138 | Transport_ Person. Family Name. Text
<span id="TravelIdentityDocument">TravelIdentityDocument</span> | [edi3:Document](#Document) | A referenced travel identity document for this transport person. | UN01013145 | Transport_ Person. Travel Identity. Referenced_ Document
<span id="TransportPersonGivenName">TransportPersonGivenName</span> | xsd:string | A given name, expressed as text, for this transport person. | UN01013137 | Transport_ Person. Given Name. Text
<span id="BirthplaceName">BirthplaceName</span> | xsd:string | The name, expressed as text, of the place where this transport person was born. | UN01013140 | Transport_ Person. Birthplace Name. Text
<span id="TransportPersonCategoryCode">TransportPersonCategoryCode</span> | xsd:token | A code specifying a category for this transport person, such as a member of crew or passenger. | UN01013135 | Transport_ Person. Category. Code
<span id="GenderCode">GenderCode</span> | xsd:token | A code specifying the gender of this transport person. | UN01013136 | Transport_ Person. Gender. Code
<span id="TransportPersonEmailAddress">TransportPersonEmailAddress</span> | [edi3:UniversalCommunication](#UniversalCommunication) | The email URI (Uniform Resource Identifier) communication for this transport person. | UN01013150 | Transport_ Person. Email_ URI. Universal_ Communication
<span id="TransportPersonRoleCode">TransportPersonRoleCode</span> | xsd:token | A code specifying a role of this transport person. | UN01013134 | Transport_ Person. Role. Code
<span id="TransportPersonBirthDateTime">TransportPersonBirthDateTime</span> | xsd:dateTime | The birth date of this transport person. | UN01004818 | Transport_ Person. Birth. Date Time
<span id="TransportPersonName">TransportPersonName</span> | xsd:string | The name or set of names, expressed as text, by which this transport person is known. | UN01004817 | Transport_ Person. Name. Text
<span id="InTransitIndicator">InTransitIndicator</span> | xsd:boolean | The indication of whether or not this transport person is in transit. | UN01013141 | Transport_ Person. In Transit. Indicator
<span id="TravelVisaDocument">TravelVisaDocument</span> | [edi3:Document](#Document) | A referenced travel visa document for this transport person. | UN01013146 | Transport_ Person. Travel_ Visa. Referenced_ Document
<span id="TransportCertifiedAccreditation">TransportCertifiedAccreditation</span> | [edi3:Accreditation](#Accreditation) | A certified accreditation specific to this transport person. | UN01010155 | Transport_ Person. Specific. Certified_ Accreditation
<span id="TransportPersonID">TransportPersonID</span> | xsd:token | The unique identifier for this transport person. | UN01004816 | Transport_ Person. Identification. Identifier
<span id="BirthCountryCode">BirthCountryCode</span> | xsd:token | The identifier of the birth country of this transport person. | UN01013139 | Transport_ Person. Birth Country. Identifier
<span id="AttainedQualification">AttainedQualification</span> | [edi3:Qualification](#Qualification) | An academic qualification attained by this transport person. | UN01013142 | Transport_ Person. Attained. Academic_ Qualification


<h1 id="AuthoritativeSignatoryPerson">AuthoritativeSignatoryPerson</h1>

Type: rdf:Class

Definition: A person who is authorized to sign a document, such as a customs officer or other government official.

Unique UN Assigned ID: UN01002513

Dictionary Entry Name: Authoritative Signatory_ Person. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="AttainedAcademicQualification">AttainedAcademicQualification</span> | [edi3:Qualification](#Qualification) | An academic qualification attained by this authoritative signatory person. | UN01002515 | Authoritative Signatory_ Person. Attained. Academic_ Qualification


<h1 id="SupplyChainInventory">SupplyChainInventory</h1>

Type: rdf:Class

Definition: Supply chain goods and materials held in stock.

Unique UN Assigned ID: UN01004305

Dictionary Entry Name: Supply Chain_ Inventory. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="DispositionDocument">DispositionDocument</span> | [edi3:Document](#Document) | A disposition document referenced in this supply chain inventory. | UN01005304 | Supply Chain_ Inventory. Disposition. Referenced_ Document
<span id="StockQuantity">StockQuantity</span> | xsd:decimal | The quantity of stock in this supply chain inventory. | UN01004306 | Supply Chain_ Inventory. Stock. Quantity
<span id="AverageDurationDateTime">AverageDurationDateTime</span> | xsd:dateTime | The date, time, date time, or other date time of the average duration for this supply chain inventory. | UN01012964 | Supply Chain_ Inventory. Average Duration. Date Time
<span id="SupplyChainInventoryLocation">SupplyChainInventoryLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | The location specified for this supply chain inventory. | UN01004310 | Supply Chain_ Inventory. Specified. Logistics_ Location
<span id="PlannedStockQuantity">PlannedStockQuantity</span> | xsd:decimal | The planned stock quantity for this supply chain inventory. | UN01008437 | Supply Chain_ Inventory. Planned_ Stock. Quantity
<span id="AverageDemandQuantity">AverageDemandQuantity</span> | xsd:decimal | The average demand quantity for this supply chain inventory. | UN01012963 | Supply Chain_ Inventory. Average_ Demand. Quantity
<span id="MinimumStockQuantity">MinimumStockQuantity</span> | xsd:decimal | The minimum stock quantity in this CI supply chain inventory. | UN01012966 | Supply Chain_ Inventory. Minimum_ Stock. Quantity
<span id="MaximumStockQuantity">MaximumStockQuantity</span> | xsd:decimal | The maximum stock quantity in this CI supply chain inventory. | UN01012965 | Supply Chain_ Inventory. Maximum_ Stock. Quantity
<span id="PlannedStockCalculationDateTime">PlannedStockCalculationDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value of the planned stock calculation of this supply chain inventory. | UN01008436 | Supply Chain_ Inventory. Planned Stock_ Calculation. Date Time
<span id="CalculationDateTime">CalculationDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value of the calculation of this supply chain inventory. | UN01004307 | Supply Chain_ Inventory. Calculation. Date Time
<span id="SupplyChainInventoryStatusCode">SupplyChainInventoryStatusCode</span> | xsd:token | The code specifying a status for this supply chain inventory. | UN01005301 | Supply Chain_ Inventory. Status. Code
<span id="MaximumStockLevelMeasure">MaximumStockLevelMeasure</span> | xsd:decimal | The measure of the maximum stock level for this supply chain inventory. | UN01004309 | Supply Chain_ Inventory. Maximum_ Stock Level. Measure
<span id="SupplyChainInventoryRemark">SupplyChainInventoryRemark</span> | [edi3:Note](#Note) | A note containing a remark for this supply chain inventory. | UN01004311 | Supply Chain_ Inventory. Remark. Note
<span id="MinimumStockLevelMeasure">MinimumStockLevelMeasure</span> | xsd:decimal | The measure of the minimum stock level for this supply chain inventory. | UN01004308 | Supply Chain_ Inventory. Minimum_ Stock Level. Measure


<h1 id="StoresItemInventory">StoresItemInventory</h1>

Type: rdf:Class

Definition: A stores item, such as for onboard use during a journey.

Unique UN Assigned ID: UN01013189

Dictionary Entry Name: Stores Item_ Inventory. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="StoresItemInventorySequenceNumber">StoresItemInventorySequenceNumber</span> | xsd:decimal | A sequence number for this stores inventory item. | UN01013190 | Stores Item_ Inventory. Sequence. Numeric
<span id="StoresItemInventoryOnboardQuantity">StoresItemInventoryOnboardQuantity</span> | xsd:decimal | An onboard quantity for this stores inventory item. | UN01013193 | Stores Item_ Inventory. Onboard. Quantity
<span id="StoresItemInventoryTypeCode">StoresItemInventoryTypeCode</span> | xsd:token | A code specifying the type of stores inventory item. | UN01013191 | Stores Item_ Inventory. Type. Code
<span id="StoresItemInventoryDescription">StoresItemInventoryDescription</span> | xsd:string | A textual description of this stores inventory item. | UN01013192 | Stores Item_ Inventory. Description. Text


<h1 id="Cargo">Cargo</h1>

Type: rdf:Class

Definition: Information about goods being transported identifying their nature for customs, statistical or transport purposes.

Unique UN Assigned ID: UN01004757

Dictionary Entry Name: Transport_ Cargo. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="CargoTypeCode">CargoTypeCode</span> | xsd:token | The code, such as UNECE Recommendation 21 single digit codes, specifying the type of transported cargo. | UN01004758 | Transport_ Cargo. Type. Code
<span id="IdentificationText">IdentificationText</span> | xsd:string | Identification, expressed as text, of this transport cargo that is sufficient to identify it for customs, statistical or transport purposes. | UN01004759 | Transport_ Cargo. Identification. Text
<span id="StatisticalClassificationCode">StatisticalClassificationCode</span> | xsd:token | The code specifying a statistical classification for this transport cargo. | UN01004761 | Transport_ Cargo. Statistical Classification. Code


<h1 id="Organization">Organization</h1>

Type: rdf:Class

Definition: An organization set up on a legal basis as a business, government body, department, charity, or financial institution.

Unique UN Assigned ID: UN01003637

Dictionary Entry Name: Legal_ Organization. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="AuthorizedRegistration">AuthorizedRegistration</span> | [edi3:LegalRegistration](#LegalRegistration) | A legal registration authorized for this legally set up organization. | UN01003647 | Legal_ Organization. Authorized. Legal_ Registration
<span id="EstablishedDateTime">EstablishedDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value when this legally set up organization was established. | UN01003644 | Legal_ Organization. Established. Date Time
<span id="TradingName">TradingName</span> | xsd:string | The trading business name, expressed as text, of this legally set up organization. | UN01003645 | Legal_ Organization. Trading Business Name. Text
<span id="OrganizationTypeCode">OrganizationTypeCode</span> | xsd:token | A code specifying a type of legally set up organization. | UN01003643 | Legal_ Organization. Type. Code
<span id="OrganizationID">OrganizationID</span> | xsd:token | A unique identifier for this legally set up organization. | UN01003641 | Legal_ Organization. Identification. Identifier
<span id="OrganizationPostalAddress">OrganizationPostalAddress</span> | [edi3:TradeAddress](#TradeAddress) | A postal address for this legally set up organization. | UN01003646 | Legal_ Organization. Postal. Trade_ Address
<span id="OrganizationName">OrganizationName</span> | xsd:string | A name, expressed as text, of this legally set up organization. | UN01003640 | Legal_ Organization. Name. Text
<span id="BusinessTypeCode">BusinessTypeCode</span> | xsd:token | A code specifying the type of business of this legally set up organization. | UN01003638 | Legal_ Organization. Business Type. Code


<h1 id="PersonalEffects">PersonalEffects</h1>

Type: rdf:Class

Definition: Specified privately owned articles for personal use by an individual.

Unique UN Assigned ID: UN01013184

Dictionary Entry Name: Specified_ Personal Effects. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="PersonalEffectsOnboardQuantity">PersonalEffectsOnboardQuantity</span> | xsd:decimal | An onboard number of these specified personal effects. | UN01013188 | Specified_ Personal Effects. Onboard. Quantity
<span id="PersonalEffectsDescription">PersonalEffectsDescription</span> | xsd:string | A textual description of these specified personal effects. | UN01013186 | Specified_ Personal Effects. Description. Text
<span id="PersonalEffectsTypeCode">PersonalEffectsTypeCode</span> | xsd:token | A code specifying a type of specified personal effects. | UN01013187 | Specified_ Personal Effects. Type. Code


<h1 id="TransportEquipment">TransportEquipment</h1>

Type: rdf:Class

Definition: A piece of equipment used to hold, protect or secure cargo for logistics purposes.

Unique UN Assigned ID: UN01003757

Dictionary Entry Name: Logistics_ Transport Equipment. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="TransportEquipmentBondedWarehouseStorageEvent">TransportEquipmentBondedWarehouseStorageEvent</span> | [edi3:Event](#Event) | A bonded warehouse storage event specifying when and where this piece of logistics transport equipment will be, or has been, stored. | UN01003805 | Logistics_ Transport Equipment. Bonded Warehouse_ Storage. Transport_ Event
<span id="ContainedConsignmentQuantity">ContainedConsignmentQuantity</span> | xsd:decimal | The number of consignments contained in this piece of logistics transport equipment. | UN01008983 | Logistics_ Transport Equipment. Contained Consignment. Quantity
<span id="TransportEquipmentApplicableNote">TransportEquipmentApplicableNote</span> | [edi3:Note](#Note) | A note providing information applicable to this piece of logistics transport equipment. | UN01012568 | Logistics_ Transport Equipment. Applicable. Note
<span id="TransportEquipmentLoadingInstructions">TransportEquipmentLoadingInstructions</span> | [edi3:TransportInstructions](#TransportInstructions) | Loading instructions for this piece of logistics transport equipment. | UN01003791 | Logistics_ Transport Equipment. Loading. Transport_ Instructions
<span id="ReleaseRestrictionText">ReleaseRestrictionText</span> | xsd:string | The release restriction, expressed as text, for this piece of logistics transport equipment. | UN01003785 | Logistics_ Transport Equipment. Release Restriction. Text
<span id="TransportEquipmentDamageRemark">TransportEquipmentDamageRemark</span> | xsd:string | A damage remark, expressed as text, for this piece of logistics transport equipment. | UN01003777 | Logistics_ Transport Equipment. Damage Remark. Text
<span id="ContainedTransportEquipment">ContainedTransportEquipment</span> | [edi3:AssociatedTransportEquipment](#AssociatedTransportEquipment) | A piece of transport equipment contained within this piece of logistics transport equipment, such as a pallet. | UN01003799 | Logistics_ Transport Equipment. Contained. Associated_ Transport Equipment
<span id="ContainedConsignment">ContainedConsignment</span> | [edi3:Consignment](#Consignment) | A consignment contained in this piece of logistics transport equipment. | UN01003786 | Logistics_ Transport Equipment. Contained. Supply Chain_ Consignment
<span id="TransportEquipmentRelatedCommunicationEvent">TransportEquipmentRelatedCommunicationEvent</span> | [edi3:CommunicationEvent](#CommunicationEvent) | A communication event related to this piece of logistics transport equipment. | UN01013594 | Logistics_ Transport Equipment. Related. Communication_ Event
<span id="TransportEquipmentUnitQuantity">TransportEquipmentUnitQuantity</span> | xsd:decimal | The number of units of this type of logistics transport equipment. | UN01008981 | Logistics_ Transport Equipment. Unit. Quantity
<span id="HumidityPercent">HumidityPercent</span> | xsd:decimal | The percent of the humidity (moisture content) within this piece of logistics transport equipment. | UN01003766 | Logistics_ Transport Equipment. Humidity. Percent
<span id="TransportEquipmentLoadedPackageQuantity">TransportEquipmentLoadedPackageQuantity</span> | xsd:decimal | The number of packages loaded into or onto this piece of logistics transport equipment. | UN01003765 | Logistics_ Transport Equipment. Loaded Package. Quantity
<span id="TransportEquipmentLoadingSequenceNumber">TransportEquipmentLoadingSequenceNumber</span> | xsd:decimal | The sequence number differentiating this piece of logistics transport equipment from others during loading. | UN01010098 | Logistics_ Transport Equipment. Loading Sequence. Numeric
<span id="TransportEquipmentInformation">TransportEquipmentInformation</span> | xsd:string | Information, expressed as text, for this piece of logistics transport equipment. | UN01003778 | Logistics_ Transport Equipment. Information. Text
<span id="ConsolidationEvent">ConsolidationEvent</span> | [edi3:Event](#Event) | A consolidation event specifying when and where this piece of logistics transport equipment will be, or has been, stuffed. | UN01008984 | Logistics_ Transport Equipment. Consolidation. Transport_ Event
<span id="TransportEquipmentDeliveryInstructions">TransportEquipmentDeliveryInstructions</span> | [edi3:DeliveryInstructions](#DeliveryInstructions) | Delivery instructions for this piece of logistics transport equipment. | UN01003790 | Logistics_ Transport Equipment. Delivery. Delivery_ Instructions
<span id="TransportEquipmentCarrierAssignedBookingID">TransportEquipmentCarrierAssignedBookingID</span> | xsd:token | A carrier assigned booking identifier for this piece of logistics transport equipment. | UN01010099 | Logistics_ Transport Equipment. Carrier Assigned Booking_ Identification. Identifier
<span id="IOTDeviceReportingTransportEvent">IOTDeviceReportingTransportEvent</span> | [edi3:Event](#Event) | An IOT device reported transport event for this piece of logistics transport equipment. | UN01013593 | Logistics_ Transport Equipment. Reporting_ IOT Device. Transport_ Event
<span id="TransportEquipmentAffixedSeal">TransportEquipmentAffixedSeal</span> | [edi3:Seal](#Seal) | A seal affixed to this piece of logistics transport equipment. | UN01003795 | Logistics_ Transport Equipment. Affixed. Logistics_ Seal
<span id="TransportEquipmentPickUpEvent">TransportEquipmentPickUpEvent</span> | [edi3:Event](#Event) | A pick-up event specifying when and where this piece of logistics transport equipment will be, or has been, collected, i.e. picked-up by the carrier. | UN01003807 | Logistics_ Transport Equipment. Pick-Up. Transport_ Event
<span id="TransportEquipmentReturnableIndicator">TransportEquipmentReturnableIndicator</span> | xsd:boolean | The indication of whether or not this piece of logistics transport equipment is returnable. | UN01012583 | Logistics_ Transport Equipment. Returnable. Indicator
<span id="TransportServicesBuyer">TransportServicesBuyer</span> | [edi3:TradeParty](#TradeParty) | The transport services buyer party for this piece of logistics transport equipment. | UN01003810 | Logistics_ Transport Equipment. Transport Services Buyer. Trade_ Party
<span id="TransportEquipmentGrossWeight">TransportEquipmentGrossWeight</span> | xsd:decimal | The measure of the gross weight (mass) of this piece of logistics transport equipment which is the weight (mass) including loaded goods, packing and transport equipment. | UN01003759 | Logistics_ Transport Equipment. Gross Weight. Measure
<span id="LoadedConsignmentItem">LoadedConsignmentItem</span> | [edi3:ConsignmentItem](#ConsignmentItem) | A consignment item loaded onto, or into, this piece of logistics transport equipment. | UN01003787 | Logistics_ Transport Equipment. Loaded. Supply Chain_ Consignment Item
<span id="TransportEquipmentApplicableServiceCharge">TransportEquipmentApplicableServiceCharge</span> | [edi3:ServiceCharge](#ServiceCharge) | A service charge applicable to this piece of logistics transport equipment. | UN01003801 | Logistics_ Transport Equipment. Applicable. Logistics_ Service Charge
<span id="LoadedDangerousGoods">LoadedDangerousGoods</span> | [edi3:DangerousGoods](#DangerousGoods) | Dangerous goods loaded into this piece of logistics transport equipment. | UN01003794 | Logistics_ Transport Equipment. Loaded. Transport_ Dangerous Goods
<span id="ActualTransportRoute">ActualTransportRoute</span> | [edi3:Route](#Route) | An actual route for this piece of logistics transport equipment. | UN01013597 | Logistics_ Transport Equipment. Actual. Transport_ Route
<span id="HaulageArrangementCode">HaulageArrangementCode</span> | xsd:token | The code specifying the arrangement for the haulage of this piece of logistics transport equipment. | UN01003775 | Logistics_ Transport Equipment. Haulage Arrangement. Code
<span id="TransportEquipmentDeliveryEvent">TransportEquipmentDeliveryEvent</span> | [edi3:Event](#Event) | A delivery event for this piece of logistics transport equipment. | UN01010100 | Logistics_ Transport Equipment. Delivery. Transport_ Event
<span id="TransportEquipmentQuarantineInstructions">TransportEquipmentQuarantineInstructions</span> | [edi3:QuarantineInstructions](#QuarantineInstructions) | Quarantine instructions for this piece of logistics transport equipment. | UN01003788 | Logistics_ Transport Equipment. Quarantine. Quarantine_ Instructions
<span id="ScheduledTransportRoute">ScheduledTransportRoute</span> | [edi3:Route](#Route) | A scheduled or planned route for this piece of logistics transport equipment. | UN01013595 | Logistics_ Transport Equipment. Scheduled. Transport_ Route
<span id="PowerSupplyTypeText">PowerSupplyTypeText</span> | xsd:string | The type of power supply, expressed as text, for this piece of logistics transport equipment, such as diesel fuel or electricity. | UN01003781 | Logistics_ Transport Equipment. Power Supply Type. Text
<span id="CarriedTransportEquipment">CarriedTransportEquipment</span> | [edi3:AssociatedTransportEquipment](#AssociatedTransportEquipment) | A piece of transport equipment carried on this piece of logistics transport equipment, such as a container placed on a rail wagon. | UN01003798 | Logistics_ Transport Equipment. Carried. Associated_ Transport Equipment
<span id="TransportEquipmentStorageEvent">TransportEquipmentStorageEvent</span> | [edi3:Event](#Event) | A storage event specifying when and where this piece of logistics transport equipment will be, or has been, stored. | UN01003804 | Logistics_ Transport Equipment. Storage. Transport_ Event
<span id="TransportEquipmentHandlingInstructions">TransportEquipmentHandlingInstructions</span> | [edi3:HandlingInstructions](#HandlingInstructions) | Handling instructions for this piece of logistics transport equipment. | UN01003789 | Logistics_ Transport Equipment. Handling. Handling_ Instructions
<span id="ReleaseID">ReleaseID</span> | xsd:token | The release identifier for this piece of logistics transport equipment. | UN01003784 | Logistics_ Transport Equipment. Release. Identifier
<span id="TransportEquipmentCarrier">TransportEquipmentCarrier</span> | [edi3:TradeParty](#TradeParty) | A carrier party for this piece of logistics transport equipment. | UN01003812 | Logistics_ Transport Equipment. Carrier. Trade_ Party
<span id="TransportEquipmentCategoryCode">TransportEquipmentCategoryCode</span> | xsd:token | The code specifying the category for this piece of logistics transport equipment, such as container or trailer. | UN01003767 | Logistics_ Transport Equipment. Category. Code
<span id="TransportEquipmentLoadingLength">TransportEquipmentLoadingLength</span> | xsd:decimal | The measure of the loading length of this piece of logistics transport equipment. | UN01003762 | Logistics_ Transport Equipment. Loading Length. Measure
<span id="TransportEquipmentReportedStatus">TransportEquipmentReportedStatus</span> | [edi3:LogisticsStatus](#LogisticsStatus) | A status reported for this piece of logistics transport equipment. | UN01003818 | Logistics_ Transport Equipment. Reported. Logistics_ Status
<span id="FullEmptyCode">FullEmptyCode</span> | xsd:token | The code specifying the used capacity of this piece of logistics transport equipment, such as full or empty. | UN01003771 | Logistics_ Transport Equipment. Used Capacity. Code
<span id="SpecifiedTransportMeans">SpecifiedTransportMeans</span> | [edi3:LogisticsTransportMeans](#LogisticsTransportMeans) | A transport means specified for this piece of logistics transport equipment. | UN01003814 | Logistics_ Transport Equipment. Specified. Logistics_ Transport Means
<span id="TransportEquipmentDimensions">TransportEquipmentDimensions</span> | [edi3:SpatialDimension](#SpatialDimension) | The linear spatial dimensions of this piece of logistics transport equipment. | UN01003796 | Logistics_ Transport Equipment. Linear. Spatial_ Dimension
<span id="SealedIndicator">SealedIndicator</span> | xsd:boolean | The indication of whether or not this piece of logistics transport equipment is sealed. | UN01012567 | Logistics_ Transport Equipment. Sealed. Indicator
<span id="TransportEquipmentAssociatedDocument">TransportEquipmentAssociatedDocument</span> | [edi3:Document](#Document) | A referenced document associated with this piece of logistics transport equipment. | UN01011040 | Logistics_ Transport Equipment. Associated. Referenced_ Document
<span id="TransportEquipmentGrossVolume">TransportEquipmentGrossVolume</span> | xsd:decimal | The measure of the gross volume of this piece of logistics transport equipment. | UN01003764 | Logistics_ Transport Equipment. Gross Volume. Measure
<span id="TareWeight">TareWeight</span> | xsd:decimal | The measure of the tare weight (mass) of this piece of logistics transport equipment which is the weight (mass) including permanent equipment but excluding goods and loose accessories. | UN01003761 | Logistics_ Transport Equipment. Tare Weight. Measure
<span id="TransportEquipmentCharacteristicText">TransportEquipmentCharacteristicText</span> | xsd:string | The characteristic or characteristics, expressed as text, of a piece of logistics transport equipment, such as its size and type. | UN01003769 | Logistics_ Transport Equipment. Characteristic. Text
<span id="UnloadingInstructions">UnloadingInstructions</span> | [edi3:TransportInstructions](#TransportInstructions) | Unloading instructions for this piece of logistics transport equipment. | UN01003792 | Logistics_ Transport Equipment. Unloading. Transport_ Instructions
<span id="TransportEquipmentNotifiedParty">TransportEquipmentNotifiedParty</span> | [edi3:TradeParty](#TradeParty) | A party who has been or will be notified about this piece of logistics transport equipment. | UN01003813 | Logistics_ Transport Equipment. Notified. Trade_ Party
<span id="IOTDeviceReportingCommunicationPairing">IOTDeviceReportingCommunicationPairing</span> | [edi3:Pairing](#Pairing) | An IOT device reported communication pairing for this piece of logistics transport equipment. | UN01013592 | Logistics_ Transport Equipment. Reporting_ IOT Device. Communication_ Pairing
<span id="TransportEquipmentSizeTypeCode">TransportEquipmentSizeTypeCode</span> | xsd:token | The code specifying the characteristic or characteristics of this piece of logistics transport equipment, such as the ISO 6346 transport equipment size and type code. | UN01003768 | Logistics_ Transport Equipment. Characteristic. Code
<span id="TransportEquipmentAttachedMonitoringIOTDevice">TransportEquipmentAttachedMonitoringIOTDevice</span> | [edi3:IOTDevice](#IOTDevice) | An IOT device attached to this piece of logistics transport equipment. | UN01013598 | Logistics_ Transport Equipment. Attached. Monitoring_ IOT Device
<span id="TransportEquipmentOperationalStatusCode">TransportEquipmentOperationalStatusCode</span> | xsd:token | The code specifying the operational status for this piece of logistics transport equipment, such as to be repaired or to be shifted. | UN01003772 | Logistics_ Transport Equipment. Operational Status. Code
<span id="TransportMovementStatusCode">TransportMovementStatusCode</span> | xsd:token | The code specifying the transport movement status for this piece of logistics transport equipment, such as for export, for import, or for transhipment. | UN01003773 | Logistics_ Transport Equipment. Transport Movement Status. Code
<span id="LoadingRemark">LoadingRemark</span> | xsd:string | A loading remark, expressed as text, for this piece of logistics transport equipment. | UN01003776 | Logistics_ Transport Equipment. Loading Remark. Text
<span id="AirFlowMeasure">AirFlowMeasure</span> | xsd:decimal | The measure of the air flow for this piece of logistics transport equipment. | UN01008982 | Logistics_ Transport Equipment. Air Flow. Measure
<span id="TransportEquipmentSequenceNumber">TransportEquipmentSequenceNumber</span> | xsd:decimal | The sequence number differentiating this piece of logistics transport equipment from others in a set of transport equipment. | UN01003779 | Logistics_ Transport Equipment. Sequence. Numeric
<span id="PositioningEvent">PositioningEvent</span> | [edi3:Event](#Event) | A positioning event specifying when and where this piece of logistics transport equipment will be, or has been, positioned, i.e. delivered and available for pick-up. | UN01003806 | Logistics_ Transport Equipment. Positioning. Transport_ Event
<span id="TransportEquipmentLogisticsRiskAnalysisResult">TransportEquipmentLogisticsRiskAnalysisResult</span> | [edi3:RiskAnalysisResult](#RiskAnalysisResult) | A result of a logistics risk analysis calculation specified for this transport equipment. | UN01013051 | Logistics_ Transport Equipment. Specified. Logistics_ Risk Analysis Result
<span id="StowagePosition">StowagePosition</span> | xsd:token | The stowage position identifier for this piece of logistics transport equipment. | UN01013168 | Logistics_ Transport Equipment. Stowage Position. Identifier
<span id="TransportEquipmentUnloadingSequenceNumber">TransportEquipmentUnloadingSequenceNumber</span> | xsd:decimal | The sequence number differentiating this piece of logistics transport equipment from others during unloading. | UN01010097 | Logistics_ Transport Equipment. Unloading Sequence. Numeric
<span id="TransportEquipmentManufacturerParty">TransportEquipmentManufacturerParty</span> | [edi3:TradeParty](#TradeParty) | The manufacturer party specified for this piece of logistics transport equipment. | UN01013599 | Logistics_ Transport Equipment. Manufacturer. Trade_ Party
<span id="TransportEquipmentUnloadingEvent">TransportEquipmentUnloadingEvent</span> | [edi3:Event](#Event) | The unloading event for this piece of logistics transport equipment. | UN01003803 | Logistics_ Transport Equipment. Unloading. Transport_ Event
<span id="LegalStatusCode">LegalStatusCode</span> | xsd:token | The code specifying the legal status of this piece of logistics transport equipment with respect to a specific law such as the "Container Convention Code". | UN01003774 | Logistics_ Transport Equipment. Legal Status. Code
<span id="AdditionalInstructions">AdditionalInstructions</span> | [edi3:TransportInstructions](#TransportInstructions) | Additional instructions for this piece of logistics transport equipment. | UN01003793 | Logistics_ Transport Equipment. Additional. Transport_ Instructions
<span id="SealQuantity">SealQuantity</span> | xsd:decimal | The quantity of seals for this piece of logistics transport equipment. | UN01006135 | Logistics_ Transport Equipment. Seal. Quantity
<span id="TransportEquipmentAttachedTransportEquipment">TransportEquipmentAttachedTransportEquipment</span> | [edi3:AttachedTransportEquipment](#AttachedTransportEquipment) | Transport equipment attached to this piece of logistics transport equipment, such as ropes or refrigeration units. | UN01003797 | Logistics_ Transport Equipment. Attached. Attached_ Transport Equipment
<span id="PowerSupplyTypeCode">PowerSupplyTypeCode</span> | xsd:token | The code specifying the type of power supply for this piece of logistics transport equipment, such as diesel fuel or electricity. | UN01003780 | Logistics_ Transport Equipment. Power Supply Type. Code
<span id="SupplierPartyRoleCode">SupplierPartyRoleCode</span> | xsd:token | The code specifying the role of the party responsible for supplying this piece of logistics transport equipment, such as the carrier or the buyer. | UN01003770 | Logistics_ Transport Equipment. Supplier Party Role. Code
<span id="TransportEquipmentManufacturngDateTime">TransportEquipmentManufacturngDateTime</span> | xsd:dateTime | The manufacturing date, time, date time, or other date time value for this piece of logistics transport equipment. | UN01013591 | Logistics_ Transport Equipment. Manufacturing. Date Time
<span id="AccompaniedIndicator">AccompaniedIndicator</span> | xsd:boolean | The indication of whether or not this piece of logistics transport equipment is accompanied, such as by a transport means. | UN01003783 | Logistics_ Transport Equipment. Accompanied. Indicator
<span id="LoadingParty">LoadingParty</span> | [edi3:TradeParty](#TradeParty) | The party that loads this piece of logistics transport equipment. | UN01003809 | Logistics_ Transport Equipment. Loading. Trade_ Party
<span id="TransportEquipmentID">TransportEquipmentID</span> | xsd:token | The unique identifier of this piece of logistics transport equipment. | UN01003758 | Logistics_ Transport Equipment. Identification. Identifier
<span id="RequestedTransportRoute">RequestedTransportRoute</span> | [edi3:Route](#Route) | A requested route for this piece of logistics transport equipment. | UN01013596 | Logistics_ Transport Equipment. Requested. Transport_ Route
<span id="TransportEquipmentNetWeight">TransportEquipmentNetWeight</span> | xsd:decimal | The measure of the net weight (mass) of this piece of logistics transport equipment. | UN01003760 | Logistics_ Transport Equipment. Net Weight. Measure
<span id="OperatingParty">OperatingParty</span> | [edi3:TradeParty](#TradeParty) | The party that operates this piece of logistics transport equipment. | UN01003808 | Logistics_ Transport Equipment. Operating. Trade_ Party
<span id="TransportEquipmentRequiredLaneLength">TransportEquipmentRequiredLaneLength</span> | xsd:decimal | The measure of the length required in a lane for this piece of logistics transport equipment. | UN01003763 | Logistics_ Transport Equipment. Required Lane Length. Measure
<span id="TransportEquipmentTemperatureSetting">TransportEquipmentTemperatureSetting</span> | [edi3:TransportSettingTemperature](#TransportSettingTemperature) | A temperature setting for this piece of logistics transport equipment, such as storage temperature or operational temperature. | UN01003800 | Logistics_ Transport Equipment. Setting. Transport Setting_ Temperature
<span id="PowerSupplyConnectorQuantity">PowerSupplyConnectorQuantity</span> | xsd:decimal | The number of power supply connectors for this piece of logistics transport equipment. | UN01003782 | Logistics_ Transport Equipment. Power Supply Connector. Quantity
<span id="ShipperReferenceInformation">ShipperReferenceInformation</span> | xsd:string | Shipper reference information, expressed as text, for this piece of logistics transport equipment. | UN01013167 | Logistics_ Transport Equipment. Shipper Reference_ Information. Text


<h1 id="ReferencedTransportEquipment">ReferencedTransportEquipment</h1>

Type: rdf:Class

Definition: A referenced piece of equipment used to hold, protect or secure cargo for logistics purposes.

Unique UN Assigned ID: UN01004022

Dictionary Entry Name: Referenced_ Logistics_ Transport Equipment. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="ReferencedTransportEquipmentUnitQuantity">ReferencedTransportEquipmentUnitQuantity</span> | xsd:decimal | The number of units of this type of referenced logistics transport equipment. | UN01008992 | Referenced_ Logistics_ Transport Equipment. Unit. Quantity
<span id="ReferencedTransportEquipmentCategoryCode">ReferencedTransportEquipmentCategoryCode</span> | xsd:token | The code specifying the category of this referenced piece of logistics transport equipment. | UN01004024 | Referenced_ Logistics_ Transport Equipment. Category. Code
<span id="ReferencedTransportEquipmentCharacteristicText">ReferencedTransportEquipmentCharacteristicText</span> | xsd:string | The characteristics, expressed as text, of a referenced piece of logistics transport equipment, such as size and type. | UN01004026 | Referenced_ Logistics_ Transport Equipment. Characteristic. Text
<span id="ReferencedTransportEquipmentID">ReferencedTransportEquipmentID</span> | xsd:token | The unique identifier for this referenced piece of logistics transport equipment, such as a number, mark or name. | UN01004023 | Referenced_ Logistics_ Transport Equipment. Identification. Identifier
<span id="ReferencedTransportEquipmentGrossWeight">ReferencedTransportEquipmentGrossWeight</span> | xsd:decimal | The measure of the gross weight (mass) of this piece of referenced logistics transport equipment which is the weight (mass) including loaded goods, packing and transport equipment. | UN01008993 | Referenced_ Logistics_ Transport Equipment. Gross Weight. Measure
<span id="ReferencedTransportEquipmentLoadedPackageQuantity">ReferencedTransportEquipmentLoadedPackageQuantity</span> | xsd:decimal | The number of packages loaded into or onto this piece of referenced logistics transport equipment. | UN01008991 | Referenced_ Logistics_ Transport Equipment. Loaded Package. Quantity
<span id="ReferencedTransportEquipmentTemperatureSetting">ReferencedTransportEquipmentTemperatureSetting</span> | [edi3:TransportSettingTemperature](#TransportSettingTemperature) | A temperature setting for this piece of referenced logistics transport equipment, such as storage temperature or operational temperature. | UN01013181 | Referenced_ Logistics_ Transport Equipment. Setting. Transport Setting_ Temperature
<span id="ReferencedTransportEquipmentCarrierAssignedBookingID">ReferencedTransportEquipmentCarrierAssignedBookingID</span> | xsd:token | A carrier assigned booking identifier for this piece of referenced logistics transport equipment. | UN01010137 | Referenced_ Logistics_ Transport Equipment. Carrier Assigned Booking_ Identification. Identifier
<span id="ReferencedTransportEquipmentNetWeight">ReferencedTransportEquipmentNetWeight</span> | xsd:decimal | The measure of the net weight (mass) of this piece of referenced logistics transport equipment. | UN01008994 | Referenced_ Logistics_ Transport Equipment. Net Weight. Measure
<span id="ReferencedTransportEquipmentAffixedSeal">ReferencedTransportEquipmentAffixedSeal</span> | [edi3:Seal](#Seal) | A seal affixed to this piece of referenced logistics transport equipment. | UN01013180 | Referenced_ Logistics_ Transport Equipment. Affixed. Logistics_ Seal
<span id="ReferencedTransportEquipmentSizeTypeCode">ReferencedTransportEquipmentSizeTypeCode</span> | xsd:token | The code specifying the characteristics, such as size and type, of this referenced piece of logistics transport equipment. | UN01004025 | Referenced_ Logistics_ Transport Equipment. Characteristic. Code


<h1 id="AttachedTransportEquipment">AttachedTransportEquipment</h1>

Type: rdf:Class

Definition: A piece of attached transport equipment, such as a chain or a tarpaulin.

Unique UN Assigned ID: UN01003416

Dictionary Entry Name: Attached_ Transport Equipment. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="AttachedTransportEquipmentCategoryCode">AttachedTransportEquipmentCategoryCode</span> | xsd:token | A code specifying a category of this piece of attached transport equipment. | UN01003418 | Attached_ Transport Equipment. Category. Code
<span id="CharacteristicCode">CharacteristicCode</span> | xsd:token | The code specifying the characteristics, i.e. size and type, of this piece of attached transport equipment. | UN01003419 | Attached_ Transport Equipment. Characteristic. Code
<span id="AttachedTransportEquipmentCharacteristicText">AttachedTransportEquipmentCharacteristicText</span> | xsd:string | The textual description of the characteristics, i.e. size and type, of this piece of attached transport equipment. | UN01003420 | Attached_ Transport Equipment. Characteristic. Text
<span id="AttachedTransportEquipmentUnitQuantity">AttachedTransportEquipmentUnitQuantity</span> | xsd:decimal | The number of units of attached transport equipment. | UN01008955 | Attached_ Transport Equipment. Unit. Quantity


<h1 id="AssociatedTransportEquipment">AssociatedTransportEquipment</h1>

Type: rdf:Class

Definition: A piece of transport equipment that is associated with another piece of transport equipment, such as a maritime container placed on a rail wagon for transportation.

Unique UN Assigned ID: UN01004883

Dictionary Entry Name: Associated_ Transport Equipment. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="AssociatedTransportEquipmentCharacteristicText">AssociatedTransportEquipmentCharacteristicText</span> | xsd:string | The textual description of the characteristics, i.e. size and type, of this piece of associated transport equipment. | UN01003415 | Associated_ Transport Equipment. Characteristic. Text


<h1 id="Consignment">Consignment</h1>

Type: rdf:Class

Definition: A separately identifiable collection of goods items to be transported or available to be transported from one consignor to one consignee in a supply chain via one or more modes of transport where each consignment is the subject of one single transport contract.

Unique UN Assigned ID: UN01004159

Dictionary Entry Name: Supply Chain_ Consignment. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="ApplicableAllowanceCharge">ApplicableAllowanceCharge</span> | [edi3:TradeAllowanceCharge](#TradeAllowanceCharge) | An allowance or charge applicable to this supply chain consignment. | UN01004287 | Supply Chain_ Consignment. Applicable. Trade_ Allowance Charge
<span id="CargoInsuranceInstructions">CargoInsuranceInstructions</span> | xsd:string | Cargo insurance instructions, expressed as text, for this supply chain consignment. | UN01012578 | Supply Chain_ Consignment. Cargo Insurance Instructions_ Information. Text
<span id="ConsignmentNetWeight">ConsignmentNetWeight</span> | xsd:decimal | A measure of the net weight (mass) of this consignment which excludes the weight of packaging of this supply chain consignment and that of any transport equipment. | UN01004174 | Supply Chain_ Consignment. Net Weight. Measure
<span id="ConsignmentFinalDestinationCountry">ConsignmentFinalDestinationCountry</span> | [edi3:Country](#Country) | The final destination country for this supply chain consignment. | UN01004271 | Supply Chain_ Consignment. Final_ Destination. Trade_ Country
<span id="ConsignmentConsignorAssignedID">ConsignmentConsignorAssignedID</span> | xsd:token | The unique identifier assigned by the consignor to this supply chain consignment. | UN01004161 | Supply Chain_ Consignment. Consignor Assigned. Identifier
<span id="ConsignmentDeclaredValueForCustomsAmount">ConsignmentDeclaredValueForCustomsAmount</span> | xsd:decimal | The monetary value declared for customs purposes for this supply chain consignment. | UN01004188 | Supply Chain_ Consignment. Declared Value For Customs. Amount
<span id="ConsignmentGrossWeight">ConsignmentGrossWeight</span> | xsd:decimal | A measure of the gross weight (mass) of this supply chain consignment which includes the weight of packaging but which excludes the weight of any transport equipment. | UN01004173 | Supply Chain_ Consignment. Gross Weight. Measure
<span id="ConsignmentPreviousAdministrativeDocument">ConsignmentPreviousAdministrativeDocument</span> | [edi3:Document](#Document) | A previous administrative referenced document for this supply chain consignment. | UN01012580 | Supply Chain_ Consignment. Previous Administrative. Referenced_ Document
<span id="MainCarriageTransportMovement">MainCarriageTransportMovement</span> | [edi3:TransportMovement](#TransportMovement) | A main carriage logistics transport movement for this supply chain consignment. | UN01004261 | Supply Chain_ Consignment. Main Carriage. Logistics_ Transport Movement
<span id="ConsignmentChargeableWeight">ConsignmentChargeableWeight</span> | xsd:decimal | A measure of a chargeable weight of this supply chain consignment. | UN01004177 | Supply Chain_ Consignment. Chargeable Weight. Measure
<span id="ShipStoresIndicator">ShipStoresIndicator</span> | xsd:boolean | The indication of whether or not this supply chain consignment is for ship stores, such as for consumption on the means of transport. | UN01004209 | Supply Chain_ Consignment. Ship Stores. Indicator
<span id="CODAmount">CODAmount</span> | xsd:decimal | The monetary value of the COD (Cash On Delivery) amount to be collected by the carrier upon delivery of this supply chain consignment. | UN01004189 | Supply Chain_ Consignment. COD. Amount
<span id="ConsignmentLoadingInstructions">ConsignmentLoadingInstructions</span> | [edi3:TransportInstructions](#TransportInstructions) | Loading instructions for this supply chain consignment. | UN01004250 | Supply Chain_ Consignment. Loading. Transport_ Instructions
<span id="UnloadingBaseportLocation">UnloadingBaseportLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | The baseport location at which this supply chain consignment is to be unloaded from a means of transport according to the transport contract. | UN01004239 | Supply Chain_ Consignment. Unloading Baseport. Logistics_ Location
<span id="TransshipmentLocation">TransshipmentLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | A transshipment location for this supply chain consignment. | UN01004236 | Supply Chain_ Consignment. Transshipment. Logistics_ Location
<span id="TransportServicesBuyerParty">TransportServicesBuyerParty</span> | [edi3:TradeParty](#TradeParty) | The party which is the buyer of the transport services for this supply chain consignment. | UN01012665 | Supply Chain_ Consignment. Transport Services Buyer. Trade_ Party
<span id="GoodsReleaseRestrictionText">GoodsReleaseRestrictionText</span> | xsd:string | A goods release restriction, expressed as text, for this supply chain consignment. | UN01004202 | Supply Chain_ Consignment. Goods Release Restriction. Text
<span id="ConsignmentCustomsValuation">ConsignmentCustomsValuation</span> | [edi3:CustomsValuation](#CustomsValuation) | A cross-border customs valuation applicable to this supply chain consignment. | UN01009002 | Supply Chain_ Consignment. Applicable. Cross-Border_ Customs Valuation
<span id="ConsignmentDestinationCountry">ConsignmentDestinationCountry</span> | [edi3:Country](#Country) | The destination country for this supply chain consignment. | UN01004270 | Supply Chain_ Consignment. Destination. Trade_ Country
<span id="ConsignmentPackageTypeText">ConsignmentPackageTypeText</span> | xsd:string | A type of package, expressed as text, for this supply chain consignment. | UN01010142 | Supply Chain_ Consignment. Package Type. Text
<span id="LoadingInformation">LoadingInformation</span> | xsd:string | Loading information, expressed as text, for this supply chain consignment, such as advice and instructions. | UN01004207 | Supply Chain_ Consignment. Loading_ Information. Text
<span id="ExportExitDateTime">ExportExitDateTime</span> | xsd:dateTime | The date, time, date time or other date time value when this supply chain consignment will exit, or has exited from the last port, airport, or border post of the country of export. | UN01004171 | Supply Chain_ Consignment. Export Exit. Date Time
<span id="ConsignmentFOBAmount">ConsignmentFOBAmount</span> | xsd:decimal | The monetary value that has to be, or has been, paid for this supply chain consignment as calculated under FOB (Free on Board) delivery terms. | UN01004178 | Supply Chain_ Consignment. FOB. Amount
<span id="ConsignmentTransportEquipmentQuantity">ConsignmentTransportEquipmentQuantity</span> | xsd:decimal | A number of pieces of transport equipment, such as containers or similar unit load devices, in this supply chain consignment. | UN01004198 | Supply Chain_ Consignment. Transport Equipment. Quantity
<span id="ConsignmentFreightForwarderAssignedID">ConsignmentFreightForwarderAssignedID</span> | xsd:token | The unique identifier assigned by the freight forwarder to this supply chain consignment. | UN01004165 | Supply Chain_ Consignment. Freight Forwarder Assigned. Identifier
<span id="ConsignmentDeliveryParty">ConsignmentDeliveryParty</span> | [edi3:TradeParty](#TradeParty) | The party to whom this supply chain consignment will be, or has been, delivered. | UN01004220 | Supply Chain_ Consignment. Delivery. Trade_ Party
<span id="ConsignmentTradeTransaction">ConsignmentTradeTransaction</span> | [edi3:SupplyChainTradeTransaction](#SupplyChainTradeTransaction) | A trade transaction related to this supply chain consignment. | UN01004289 | Supply Chain_ Consignment. Related. Supply Chain_ Trade Transaction
<span id="FreightForwarder">FreightForwarder</span> | [edi3:TradeParty](#TradeParty) | The freight forwarder party for this supply chain consignment. | UN01004216 | Supply Chain_ Consignment. Freight Forwarder. Trade_ Party
<span id="AtArrivalTransportMovement">AtArrivalTransportMovement</span> | [edi3:TransportMovement](#TransportMovement) | The logistics transport movement for this supply chain consignment at the point when the means of transport arrives in a country or at a regional border. | UN01004265 | Supply Chain_ Consignment. At Arrival. Logistics_ Transport Movement
<span id="ConsignmentTransitCountry">ConsignmentTransitCountry</span> | [edi3:Country](#Country) | A transit country for this supply chain consignment. | UN01004269 | Supply Chain_ Consignment. Transit. Trade_ Country
<span id="ConsignmentLoadingLength">ConsignmentLoadingLength</span> | xsd:decimal | A measure of the loading length which is the length along a means of transport over which the complete width and height is needed for loading all the goods items in this supply chain consignment. | UN01004176 | Supply Chain_ Consignment. Loading Length. Measure
<span id="ConsignmentHandlingInstructions">ConsignmentHandlingInstructions</span> | [edi3:HandlingInstructions](#HandlingInstructions) | Handling instructions for this supply chain consignment, such as where or how specified packages or containers are to be loaded on a means of transport. | UN01004248 | Supply Chain_ Consignment. Handling. Handling_ Instructions
<span id="PickUpParty">PickUpParty</span> | [edi3:TradeParty](#TradeParty) | The pick-up trade party for this supply chain consignment. | UN01005289 | Supply Chain_ Consignment. Pick-Up. Trade_ Party
<span id="ConsignmentExaminationEvent">ConsignmentExaminationEvent</span> | [edi3:Event](#Event) | An examination event for this supply chain consignment. | UN01004253 | Supply Chain_ Consignment. Examination. Transport_ Event
<span id="CustomsImportAgent">CustomsImportAgent</span> | [edi3:TradeParty](#TradeParty) | The party acting as an agent for, or on behalf of, the consignee with respect to the customs import procedures for this supply chain consignment. | UN01004224 | Supply Chain_ Consignment. Customs Import Agent. Trade_ Party
<span id="ConsignmentPreCarriageTransportMovement">ConsignmentPreCarriageTransportMovement</span> | [edi3:TransportMovement](#TransportMovement) | A pre-carriage logistics transport movement for this supply chain consignment. | UN01004262 | Supply Chain_ Consignment. Pre-Carriage. Logistics_ Transport Movement
<span id="ConsignmentExportGeopoliticalRegion">ConsignmentExportGeopoliticalRegion</span> | [edi3:GeopoliticalRegion](#GeopoliticalRegion) | The geopolitical region of export for this supply chain consignment. | UN01004276 | Supply Chain_ Consignment. Export. Trade_ Geopolitical Region
<span id="LoadingLocation">LoadingLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | The logistics location where the supply chain consignment is loaded. | UN01013114 | Supply Chain_ Consignment. Loading. Logistics_ Location
<span id="ReExportCountry">ReExportCountry</span> | [edi3:Country](#Country) | A re-export country for this supply chain consignment. | UN01004274 | Supply Chain_ Consignment. Re-Export. Trade_ Country
<span id="DemurrageInformation">DemurrageInformation</span> | xsd:string | Demurrage information, expressed as text, for this supply chain consignment. | UN01004208 | Supply Chain_ Consignment. Demurrage_ Information. Text
<span id="ConsignorProvidedBorderClearanceInstructions">ConsignorProvidedBorderClearanceInstructions</span> | [edi3:TransportInstructions](#TransportInstructions) | Border clearance instructions provided by the consignor for this supply chain consignment. | UN01009003 | Supply Chain_ Consignment. Consignor Provided_ Border Clearance. Transport_ Instructions
<span id="ConsignmentOriginCountry">ConsignmentOriginCountry</span> | [edi3:Country](#Country) | A country of origin for this supply chain consignment. | UN01004268 | Supply Chain_ Consignment. Origin. Trade_ Country
<span id="LocalConsigneeAgent">LocalConsigneeAgent</span> | [edi3:TradeParty](#TradeParty) | The local party authorized to act for or on behalf of the consignee for this supply chain consignment. | UN01005288 | Supply Chain_ Consignment. Local_ Consignee Agent. Trade_ Party
<span id="ConsignmentShipToParty">ConsignmentShipToParty</span> | [edi3:TradeParty](#TradeParty) | The ship to party for this supply chain consignment. | UN01004222 | Supply Chain_ Consignment. Ship To. Trade_ Party
<span id="NilCustomsValueIndicator">NilCustomsValueIndicator</span> | xsd:boolean | The indication of whether or not this supply chain consignment has a nil value for customs. | UN01004192 | Supply Chain_ Consignment. Nil Customs Value. Indicator
<span id="RelatedBookingTypeText">RelatedBookingTypeText</span> | xsd:string | The type of booking, expressed as text, related to this supply chain consignment. | UN01013606 | Supply Chain_ Consignment. Related Booking Type. Text
<span id="ConsignmentManifestDocument">ConsignmentManifestDocument</span> | [edi3:Document](#Document) | A referenced manifest document associated to this supply chain consignment. | UN01004246 | Supply Chain_ Consignment. Manifest_ Associated. Referenced_ Document
<span id="ConsignmentDeclaredValueForCarriageAmount">ConsignmentDeclaredValueForCarriageAmount</span> | xsd:decimal | The monetary value of this supply chain consignment as declared by the shipper or his agent for the purpose of varying the carrier's level of liability from that provided in the contract of carriage, in case of loss or damage to goods or delayed delivery. | UN01006138 | Supply Chain_ Consignment. Declared Value For Carriage. Amount
<span id="ConsignmentCargoToleranceInformation">ConsignmentCargoToleranceInformation</span> | xsd:string | Cargo tolerance information, expressed as text, for this supply chain consignment. | UN01004205 | Supply Chain_ Consignment. Cargo Tolerance_ Information. Text
<span id="TotalCollectChargeAmount">TotalCollectChargeAmount</span> | xsd:decimal | The total monetary value of all freight and other service charges which are to be collected from the consignee at or after delivery for this supply chain consignment. | UN01004183 | Supply Chain_ Consignment. Total Collect Charge. Amount
<span id="TransshipmentPermittedIndicator">TransshipmentPermittedIndicator</span> | xsd:boolean | The indication of whether or not transshipment is permitted for this supply chain consignment. | UN01012579 | Supply Chain_ Consignment. Transshipment Permission. Indicator
<span id="ConsignmentRegulatoryProcedure">ConsignmentRegulatoryProcedure</span> | [edi3:RegulatoryProcedure](#RegulatoryProcedure) | A cross-border regulatory procedure applicable to this supply chain consignment. | UN01006189 | Supply Chain_ Consignment. Applicable. Cross-Border_ Regulatory Procedure
<span id="ConsignmentCarrierAcceptanceLocation">ConsignmentCarrierAcceptanceLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | The location where this supply chain consignment will be, or has been, accepted by the carrier. | UN01004235 | Supply Chain_ Consignment. Carrier Acceptance. Logistics_ Location
<span id="ConsignmentInvoicee">ConsignmentInvoicee</span> | [edi3:TradeParty](#TradeParty) | An invoicee trade party associated with this supply chain consignment. | UN01010143 | Supply Chain_ Consignment. Invoicee_ Associated. Trade_ Party
<span id="FinalDestinationLocation">FinalDestinationLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | The final destination location for this supply chain consignment. | UN01004242 | Supply Chain_ Consignment. Final Destination. Logistics_ Location
<span id="CustomsExportAgent">CustomsExportAgent</span> | [edi3:TradeParty](#TradeParty) | The party acting as an agent for, or on behalf of, the consignor with respect to the customs export procedures for this supply chain consignment. | UN01004225 | Supply Chain_ Consignment. Customs Export Agent. Trade_ Party
<span id="ConsignmentTransportPackage">ConsignmentTransportPackage</span> | [edi3:Package](#Package) | Transport packages for this supply chain consignment. | UN01004290 | Supply Chain_ Consignment. Transport. Logistics_ Package
<span id="InsurancePremiumAmount">InsurancePremiumAmount</span> | xsd:decimal | The monetary value of the insurance premium for this supply chain consignment. | UN01004180 | Supply Chain_ Consignment. Insurance Premium. Amount
<span id="Importer">Importer</span> | [edi3:TradeParty](#TradeParty) | The party who imports this supply chain consignment. | UN01004217 | Supply Chain_ Consignment. Importer. Trade_ Party
<span id="ConsignmentTotalAllowanceChargeAmount">ConsignmentTotalAllowanceChargeAmount</span> | xsd:decimal | The total monetary value of all allowances and charges for this supply chain consignment. | UN01004185 | Supply Chain_ Consignment. Total Allowance Charge. Amount
<span id="GroupingCentre">GroupingCentre</span> | [edi3:TradeParty](#TradeParty) | A grouping centre party for this supply chain consignment. | UN01004234 | Supply Chain_ Consignment. Grouping Centre. Trade_ Party
<span id="ConsignmentBondedWarehouseStorageEvent">ConsignmentBondedWarehouseStorageEvent</span> | [edi3:Event](#Event) | A bonded warehouse storage event for this supply chain consignment. | UN01004256 | Supply Chain_ Consignment. Bonded Warehouse_ Storage. Transport_ Event
<span id="ConsignmentTransportSplitDescription">ConsignmentTransportSplitDescription</span> | xsd:string | The textual description of the transport split of this supply chain consignment across different transport means or transport equipment. | UN01004206 | Supply Chain_ Consignment. Transport Split Description. Text
<span id="ConsignmentLogisticsRiskAnalysisResult">ConsignmentLogisticsRiskAnalysisResult</span> | [edi3:RiskAnalysisResult](#RiskAnalysisResult) | A result of a logistics risk analysis calculation specified for this supply chain consignment. | UN01013053 | Supply Chain_ Consignment. Specified. Logistics_ Risk Analysis Result
<span id="SupplyChainTransportEvent">SupplyChainTransportEvent</span> | [edi3:Event](#Event) | An event occurring during the transport of this supply chain consignment. | UN01004252 | Supply Chain_ Consignment. Transport. Transport_ Event
<span id="Exporter">Exporter</span> | [edi3:TradeParty](#TradeParty) | The party who exports this supply chain consignment. | UN01004218 | Supply Chain_ Consignment. Exporter. Trade_ Party
<span id="ConsignmentOriginGeopoliticalRegion">ConsignmentOriginGeopoliticalRegion</span> | [edi3:GeopoliticalRegion](#GeopoliticalRegion) | The geopolitical region of origin for this supply chain consignment. | UN01004275 | Supply Chain_ Consignment. Origin. Trade_ Geopolitical Region
<span id="ImportCountry">ImportCountry</span> | [edi3:Country](#Country) | The import country for this supply chain consignment. | UN01004272 | Supply Chain_ Consignment. Import. Trade_ Country
<span id="ConsignmentConsigneeAssignedID">ConsignmentConsigneeAssignedID</span> | xsd:token | The unique identifier assigned by the consignee to this supply chain consignment. | UN01004162 | Supply Chain_ Consignment. Consignee Assigned. Identifier
<span id="ConsignmentDevanningEvent">ConsignmentDevanningEvent</span> | [edi3:Event](#Event) | A transport devanning event for this supply chain consignment, i.e. the unloading of this consignment at the place of delivery. | UN01013195 | Supply Chain_ Consignment. Devanning. Transport_ Event
<span id="ConsignmentCustomsID">ConsignmentCustomsID</span> | xsd:token | A unique identifier, for customs purposes, for this consignment. | UN01004163 | Supply Chain_ Consignment. Customs_ Identification. Identifier
<span id="UnloadingLocation">UnloadingLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | The logistics location where the supply chain consignment is unloaded. | UN01013113 | Supply Chain_ Consignment. Unloading. Logistics_ Location
<span id="NumberOfPackages">NumberOfPackages</span> | xsd:decimal | The number of packages within this supply chain consignment. | UN01004197 | Supply Chain_ Consignment. Package. Quantity
<span id="ConsigneeAgent">ConsigneeAgent</span> | [edi3:TradeParty](#TradeParty) | The party authorized to act for or on behalf of the consignee for this supply chain consignment. | UN01004233 | Supply Chain_ Consignment. Consignee Agent. Trade_ Party
<span id="ConsignmentConsignee">ConsignmentConsignee</span> | [edi3:TradeParty](#TradeParty) | The consignee party for this supply chain consignment. | UN01004213 | Supply Chain_ Consignment. Consignee. Trade_ Party
<span id="ConsignmentDespatchParty">ConsignmentDespatchParty</span> | [edi3:TradeParty](#TradeParty) | The party from whom this supply chain consignment will be or has been despatched. | UN01004219 | Supply Chain_ Consignment. Despatch. Trade_ Party
<span id="RiskFactorCode">RiskFactorCode</span> | xsd:token | The code specifying a risk factor for this supply chain consignment. | UN01004211 | Supply Chain_ Consignment. Risk Factor. Code
<span id="ConsignmentStorageEvent">ConsignmentStorageEvent</span> | [edi3:Event](#Event) | A storage event for this supply chain consignment. | UN01004255 | Supply Chain_ Consignment. Storage. Transport_ Event
<span id="ConsignmentAssociatedParty">ConsignmentAssociatedParty</span> | [edi3:TradeParty](#TradeParty) | A trade party associated with this supply chain consignment. | UN01004901 | Supply Chain_ Consignment. Associated. Trade_ Party
<span id="IncludedConsignment">IncludedConsignment</span> | [edi3:ReferencedConsignment](#ReferencedConsignment) | A referenced consignment included in this supply chain consignment. | UN01004259 | Supply Chain_ Consignment. Included. Referenced_ Supply Chain_ Consignment
<span id="CarrierProvidedInformation">CarrierProvidedInformation</span> | xsd:string | Information, expressed as text, provided by the carrier for this supply chain consignment. | UN01004204 | Supply Chain_ Consignment. Carrier Provided_ Information. Text
<span id="CustomsTransitAgent">CustomsTransitAgent</span> | [edi3:TradeParty](#TradeParty) | The party acting as an agent for, or on behalf of, the consignor with respect to customs transit procedures for this supply chain consignment. | UN01004226 | Supply Chain_ Consignment. Customs Transit Agent. Trade_ Party
<span id="TransportEquipmentSplitGoodsIndicator">TransportEquipmentSplitGoodsIndicator</span> | xsd:boolean | The indication of whether or not the goods in this supply chain consignment are split across more than one piece of transport equipment. | UN01004210 | Supply Chain_ Consignment. Transport Equipment Split Goods. Indicator
<span id="CargoInsurance">CargoInsurance</span> | [edi3:CargoInsurance](#CargoInsurance) | The cargo insurance applicable to this supply chain consignment. | UN01004277 | Supply Chain_ Consignment. Applicable. Transport_ Cargo Insurance
<span id="ConsignmentDeliveryInstructions">ConsignmentDeliveryInstructions</span> | [edi3:DeliveryInstructions](#DeliveryInstructions) | Delivery instructions for this supply chain consignment. | UN01009004 | Supply Chain_ Consignment. Delivery. Delivery_ Instructions
<span id="ConsignmentAssociatedDocument">ConsignmentAssociatedDocument</span> | [edi3:Document](#Document) | A referenced document associated with this supply chain consignment, such as the certificate of origin or dangerous goods note. | UN01004245 | Supply Chain_ Consignment. Associated. Referenced_ Document
<span id="ConsignmentConsignor">ConsignmentConsignor</span> | [edi3:TradeParty](#TradeParty) | The consignor party for this supply chain consignment. | UN01004212 | Supply Chain_ Consignment. Consignor. Trade_ Party
<span id="WarehouseArrivalDateTime">WarehouseArrivalDateTime</span> | xsd:dateTime | The date, time, date time or other date time value of the arrival of this supply chain consignment at a warehouse. | UN01004172 | Supply Chain_ Consignment. Warehouse Arrival. Date Time
<span id="ConsignmentVanningEvent">ConsignmentVanningEvent</span> | [edi3:Event](#Event) | The vanning event for this supply chain consignment, i.e. the loading of this consignment at the place of original despatch. | UN01004257 | Supply Chain_ Consignment. Vanning. Transport_ Event
<span id="ConsignorAgent">ConsignorAgent</span> | [edi3:TradeParty](#TradeParty) | The party authorized to act for or on behalf of the consignor for this supply chain consignment. | UN01004232 | Supply Chain_ Consignment. Consignor Agent. Trade_ Party
<span id="InsuranceCurrencyExchange">InsuranceCurrencyExchange</span> | [edi3:CurrencyExchange](#CurrencyExchange) | A currency exchange applicable to an insurance charge for this supply chain consignment. | UN01004282 | Supply Chain_ Consignment. Insurance_ Applicable. Trade_ Currency Exchange
<span id="ConsignmentCarrierAssignedID">ConsignmentCarrierAssignedID</span> | xsd:token | The unique identifier assigned by the carrier to this supply chain consignment, such as a booking reference number when cargo space is reserved prior to loading. | UN01004164 | Supply Chain_ Consignment. Carrier Assigned. Identifier
<span id="ConsignmentGrossVolume">ConsignmentGrossVolume</span> | xsd:decimal | A measure of the gross volume, normally calculated by multiplying the maximum length, width and height of this supply chain consignment. | UN01004175 | Supply Chain_ Consignment. Gross Volume. Measure
<span id="IntermediateConsignee">IntermediateConsignee</span> | [edi3:TradeParty](#TradeParty) | A party that is an intermediate consignee for this supply chain consignment. | UN01004229 | Supply Chain_ Consignment. Intermediate Consignee. Trade_ Party
<span id="NilInsuranceValueIndicator">NilInsuranceValueIndicator</span> | xsd:boolean | The indication of whether or not this supply chain consignment has a nil value for insurance. | UN01004194 | Supply Chain_ Consignment. Nil Insurance Value. Indicator
<span id="TransitLocation">TransitLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | A location of transit for this supply chain consignment. | UN01004240 | Supply Chain_ Consignment. Transit. Logistics_ Location
<span id="SupplyChainHaulageInstructions">SupplyChainHaulageInstructions</span> | [edi3:HaulageInstructions](#HaulageInstructions) | Haulage instructions for this supply chain consignment. | UN01004249 | Supply Chain_ Consignment. Haulage. Haulage_ Instructions
<span id="OnCarriageTransportMovement">OnCarriageTransportMovement</span> | [edi3:TransportMovement](#TransportMovement) | An on-carriage logistics transport movement for this supply chain consignment. | UN01004263 | Supply Chain_ Consignment. On-Carriage. Logistics_ Transport Movement
<span id="TotalDisbursementAmount">TotalDisbursementAmount</span> | xsd:decimal | The monetary value of total disbursement for this supply chain consignment, such as the amount to be collected by the carrier according to the order given by the consignor. | UN01004186 | Supply Chain_ Consignment. Total Disbursement. Amount
<span id="Deconsolidator">Deconsolidator</span> | [edi3:TradeParty](#TradeParty) | The party responsible for the deconsolidation of this supply chain consignment. | UN01004231 | Supply Chain_ Consignment. Deconsolidator. Trade_ Party
<span id="ConsignmentDangerousGoods">ConsignmentDangerousGoods</span> | [edi3:DangerousGoods](#DangerousGoods) | Dangerous goods applicable to the transport of this supply chain consignment. | UN01006205 | Supply Chain_ Consignment. Applicable. Transport_ Dangerous Goods
<span id="ContainerizationIndicator">ContainerizationIndicator</span> | xsd:boolean | The indication of whether or not this supply chain consignment is to be transported in a container or containers. | UN01004195 | Supply Chain_ Consignment. Containerization. Indicator
<span id="ConsignmentDeliveryEvent">ConsignmentDeliveryEvent</span> | [edi3:Event](#Event) | The delivery event for this supply chain consignment. | UN01004251 | Supply Chain_ Consignment. Delivery. Transport_ Event
<span id="ChargeableTransportationStageQuantity">ChargeableTransportationStageQuantity</span> | xsd:decimal | The number of separately chargeable transportation stages to be covered by this supply chain consignment. | UN01004199 | Supply Chain_ Consignment. Chargeable Transportation Stage. Quantity
<span id="LoadingBaseportLocation">LoadingBaseportLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | The baseport location at which this supply chain consignment is to be loaded on a means of transport according to the transport contract. | UN01004238 | Supply Chain_ Consignment. Loading Baseport. Logistics_ Location
<span id="TotalPrepaidChargeAmount">TotalPrepaidChargeAmount</span> | xsd:decimal | The total monetary value of all freight and other service charges which have been paid in advance for this supply chain consignment. | UN01004184 | Supply Chain_ Consignment. Total Prepaid Charge. Amount
<span id="TradedParcelID">TradedParcelID</span> | xsd:token | A traded parcel identifier for this supply chain consignment. | UN01004166 | Supply Chain_ Consignment. Traded Parcel. Identifier
<span id="CustomsRequiredInvoiceDocument">CustomsRequiredInvoiceDocument</span> | [edi3:Document](#Document) | A referenced invoice document required by customs for this supply chain consignment. | UN01004244 | Supply Chain_ Consignment. Customs Required Invoice. Referenced_ Document
<span id="ConsignmentExportCountry">ConsignmentExportCountry</span> | [edi3:Country](#Country) | The export country for this supply chain consignment. | UN01004273 | Supply Chain_ Consignment. Export. Trade_ Country
<span id="ConsignmentTransportService">ConsignmentTransportService</span> | [edi3:Service](#Service) | A transport service for this supply chain consignment. | UN01004284 | Supply Chain_ Consignment. Transport. Transport_ Service
<span id="ConsignmentReportedStatus">ConsignmentReportedStatus</span> | [edi3:LogisticsStatus](#LogisticsStatus) | A logistics status reported for this supply chain consignment. | UN01004288 | Supply Chain_ Consignment. Reported. Logistics_ Status
<span id="AtDepartureTransportMovement">AtDepartureTransportMovement</span> | [edi3:TransportMovement](#TransportMovement) | The logistics transport movement for this supply chain consignment at the point when the means of transport departs a country or regional border. | UN01004266 | Supply Chain_ Consignment. At Departure. Logistics_ Transport Movement
<span id="ConsignmentInvoiceCurrencyExchange">ConsignmentInvoiceCurrencyExchange</span> | [edi3:CurrencyExchange](#CurrencyExchange) | A currency exchange applicable to the invoice for this supply chain consignment. | UN01004280 | Supply Chain_ Consignment. Invoice_ Applicable. Trade_ Currency Exchange
<span id="ConsignmentApplicableServiceCharge">ConsignmentApplicableServiceCharge</span> | [edi3:ServiceCharge](#ServiceCharge) | A logistics service charge applicable to this supply chain consignment, such as freight or insurance charges. | UN01004285 | Supply Chain_ Consignment. Applicable. Logistics_ Service Charge
<span id="SpecifiedDeliveryTerms">SpecifiedDeliveryTerms</span> | [edi3:DeliveryTerms](#DeliveryTerms) | Delivery terms specified for this supply chain consignment. | UN01004283 | Supply Chain_ Consignment. Specified. Trade_ Delivery Terms
<span id="ConsignmentInsuranceValueAmount">ConsignmentInsuranceValueAmount</span> | xsd:decimal | The monetary value of this supply chain consignment as covered by an insurance policy. | UN01004179 | Supply Chain_ Consignment. Insurance Value. Amount
<span id="ConsignmentTransportContractDocument">ConsignmentTransportContractDocument</span> | [edi3:Document](#Document) | The referenced transport contract document for this supply chain consignment, such as an airwaybill or a seawaybill. | UN01004243 | Supply Chain_ Consignment. Transport Contract. Referenced_ Document
<span id="DangerousGoodsNotifier">DangerousGoodsNotifier</span> | [edi3:TradeParty](#TradeParty) | The party responsible for providing the dangerous goods notification in accordance with the dangerous goods regulations relevant for this supply chain consignment. | UN01004228 | Supply Chain_ Consignment. Dangerous Goods Notifier. Trade_ Party
<span id="ConsignmentTotalChargeAmount">ConsignmentTotalChargeAmount</span> | xsd:decimal | The total monetary value of all freight and other service charges for this supply chain consignment. | UN01004182 | Supply Chain_ Consignment. Total Charge. Amount
<span id="ConsignorProvidedInformationText">ConsignorProvidedInformationText</span> | xsd:string | Information, expressed as text, provided by the consignor for this supply chain consignment. | UN01013607 | Supply Chain_ Consignment. Consignor Provided_ Information. Text
<span id="BorderCrossingTransportMovement">BorderCrossingTransportMovement</span> | [edi3:TransportMovement](#TransportMovement) | A border crossing logistics transport movement for this supply chain consignment. | UN01004264 | Supply Chain_ Consignment. Border Crossing. Logistics_ Transport Movement
<span id="ConsignmentPickUpEvent">ConsignmentPickUpEvent</span> | [edi3:Event](#Event) | The pick-up event for this supply chain consignment. | UN01004254 | Supply Chain_ Consignment. Pick-Up. Transport_ Event
<span id="NetVolumeMeasure">NetVolumeMeasure</span> | xsd:decimal | A measure of the net volume of this supply chain consignment item which excludes all packaging. | UN01012710 | Supply Chain_ Consignment. Net Volume. Measure
<span id="ConsignmentCarrierAcceptanceDateTime">ConsignmentCarrierAcceptanceDateTime</span> | xsd:dateTime | The date, time, date time or other date time value when this supply chain consignment will be, or has been, accepted by the carrier. | UN01004170 | Supply Chain_ Consignment. Carrier Acceptance. Date Time
<span id="ConsignmentUnloadingSequenceNumber">ConsignmentUnloadingSequenceNumber</span> | xsd:decimal | The unloading sequence number for this supply chain consignment. | UN01010141 | Supply Chain_ Consignment. Unloading Sequence. Numeric
<span id="ConsignmentCarrier">ConsignmentCarrier</span> | [edi3:TradeParty](#TradeParty) | The carrier party for this supply chain consignment. | UN01004214 | Supply Chain_ Consignment. Carrier. Trade_ Party
<span id="EstimatedServiceCharge">EstimatedServiceCharge</span> | [edi3:ServiceCharge](#ServiceCharge) | An estimated logistics service charge applicable to this supply chain consignment, such as freight or insurance charges. | UN01004286 | Supply Chain_ Consignment. Estimated_ Applicable. Logistics_ Service Charge
<span id="ConsignmentIncludedConsignmentItem">ConsignmentIncludedConsignmentItem</span> | [edi3:ConsignmentItem](#ConsignmentItem) | A consignment item included in this supply chain consignment. | UN01004258 | Supply Chain_ Consignment. Included. Supply Chain_ Consignment Item
<span id="LoadingListQuantity">LoadingListQuantity</span> | xsd:decimal | The number of loading lists, manifests or similar documents for this supply chain consignment. | UN01004200 | Supply Chain_ Consignment. Loading List. Quantity
<span id="DeliveryInformation">DeliveryInformation</span> | xsd:string | The delivery information, expressed as text, for this supply chain consignment. | UN01009001 | Supply Chain_ Consignment. Delivery_ Information. Text
<span id="ConsignmentCarrierAgent">ConsignmentCarrierAgent</span> | [edi3:TradeParty](#TradeParty) | The party acting as the agent of the carrier for this supply chain consignment. | UN01004215 | Supply Chain_ Consignment. Carrier Agent. Trade_ Party
<span id="ServiceChargeCurrencyExchange">ServiceChargeCurrencyExchange</span> | [edi3:CurrencyExchange](#CurrencyExchange) | A currency exchange applicable to a service charge for this supply chain consignment. | UN01004281 | Supply Chain_ Consignment. Service Charge_ Applicable. Trade_ Currency Exchange
<span id="SummaryDescription">SummaryDescription</span> | xsd:string | A textual summary description of this supply chain consignment. | UN01004201 | Supply Chain_ Consignment. Summary Description. Text
<span id="NatureIdentificationCargo">NatureIdentificationCargo</span> | [edi3:Cargo](#Cargo) | Transport cargo details of this supply chain consignment sufficient to identify its nature for customs, statistical or transport purposes. | UN01006140 | Supply Chain_ Consignment. Nature Identification. Transport_ Cargo
<span id="NilCarriageValueIndicator">NilCarriageValueIndicator</span> | xsd:boolean | The indication of whether or not this supply chain consignment has a nil value for carriage. | UN01004193 | Supply Chain_ Consignment. Nil Carriage Value. Indicator
<span id="ConsignmentTotalExportExitToImportEntryChargeAmount">ConsignmentTotalExportExitToImportEntryChargeAmount</span> | xsd:decimal | The monetary value of the total charge or charges of freight, insurance and other services for this supply chain consignment calculated from the export exit location to the import entry location. | UN01004187 | Supply Chain_ Consignment. Total Export Exit To Import Entry Charge. Amount
<span id="ConsignmentID">ConsignmentID</span> | xsd:token | A unique identifier for this supply chain consignment. | UN01004160 | Supply Chain_ Consignment. Identification. Identifier
<span id="AvailabilityDueDateTime">AvailabilityDueDateTime</span> | xsd:dateTime | The date, time, date time or other date time value when this supply chain consignment is due to be available. | UN01004169 | Supply Chain_ Consignment. Availability Due. Date Time
<span id="AssociatedInvoiceDiscountAmount">AssociatedInvoiceDiscountAmount</span> | xsd:decimal | A monetary value of the discount on an invoice associated with this supply chain consignment. | UN01004190 | Supply Chain_ Consignment. Associated Invoice Discount. Amount
<span id="ConsignmentSequenceNumber">ConsignmentSequenceNumber</span> | xsd:decimal | A sequence number for this supply chain consignment. | UN01004167 | Supply Chain_ Consignment. Sequence. Numeric
<span id="ConsignmentPhysicalShippingMarks">ConsignmentPhysicalShippingMarks</span> | [edi3:ShippingMarks](#ShippingMarks) | Physical logistics shipping marks and barcoding information related to this supply chain consignment. | UN01004247 | Supply Chain_ Consignment. Physical. Logistics_ Shipping Marks
<span id="ConsignmentNotifiedParty">ConsignmentNotifiedParty</span> | [edi3:TradeParty](#TradeParty) | A party who has been or will be notified about this supply chain consignment. | UN01004223 | Supply Chain_ Consignment. Notified. Trade_ Party
<span id="AssociatedInvoiceAmount">AssociatedInvoiceAmount</span> | xsd:decimal | A monetary value of an invoice associated with this supply chain consignment. | UN01004181 | Supply Chain_ Consignment. Associated Invoice. Amount
<span id="Consolidator">Consolidator</span> | [edi3:TradeParty](#TradeParty) | The party responsible for the consolidation of this supply chain consignment. | UN01004230 | Supply Chain_ Consignment. Consolidator. Trade_ Party
<span id="ConsignmentShipFromParty">ConsignmentShipFromParty</span> | [edi3:TradeParty](#TradeParty) | The ship from party for this supply chain consignment. | UN01004221 | Supply Chain_ Consignment. Ship From. Trade_ Party
<span id="ConsigneeReceiptLocation">ConsigneeReceiptLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | The location at which this supply chain consignment will be or has been received by the consignee. | UN01004237 | Supply Chain_ Consignment. Consignee Receipt. Logistics_ Location
<span id="AssociatedInvoiceDiscountPercent">AssociatedInvoiceDiscountPercent</span> | xsd:decimal | A percent that is a discount on an invoice amount associated with this supply chain consignment. | UN01004191 | Supply Chain_ Consignment. Associated Invoice Discount. Percent
<span id="ConsignmentUsedTransportEquipment">ConsignmentUsedTransportEquipment</span> | [edi3:TransportEquipment](#TransportEquipment) | Logistics transport equipment utilized for this supply chain consignment. | UN01004260 | Supply Chain_ Consignment. Utilized. Logistics_ Transport Equipment
<span id="ConsignmentDeclaredForCustomsLocation">ConsignmentDeclaredForCustomsLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | The location of this supply chain consignment as declared for customs. | UN01004241 | Supply Chain_ Consignment. Declared For Customs. Logistics_ Location
<span id="ConsignmentConsignmentItemQuantity">ConsignmentConsignmentItemQuantity</span> | xsd:decimal | The number of consignment items separately defined for transport or customs purposes within this supply chain consignment. | UN01004196 | Supply Chain_ Consignment. Consignment Item. Quantity
<span id="ConsignmentPaymentArrangementCode">ConsignmentPaymentArrangementCode</span> | xsd:token | The code specifying the payment arrangements for this supply chain consignment. | UN01006139 | Supply Chain_ Consignment. Payment Arrangement. Code
<span id="SpecifiedTransportMovement">SpecifiedTransportMovement</span> | [edi3:TransportMovement](#TransportMovement) | A logistics transport movement specified for this supply chain consignment. | UN01004267 | Supply Chain_ Consignment. Specified. Logistics_ Transport Movement
<span id="ConsignmentInformation">ConsignmentInformation</span> | xsd:string | Information, expressed as text, for this supply chain consignment. | UN01004203 | Supply Chain_ Consignment. Information. Text
<span id="ConsignmentApplicableCurrencyExchange">ConsignmentApplicableCurrencyExchange</span> | [edi3:CurrencyExchange](#CurrencyExchange) | A currency exchange applicable to this supply chain consignment. | UN01004279 | Supply Chain_ Consignment. Applicable. Trade_ Currency Exchange
<span id="ConnectingCarrier">ConnectingCarrier</span> | [edi3:TradeParty](#TradeParty) | A connecting carrier party for this supply chain consignment. | UN01004227 | Supply Chain_ Consignment. Connecting Carrier. Trade_ Party


<h1 id="ReferencedConsignment">ReferencedConsignment</h1>

Type: rdf:Class

Definition: A referenced, separately identifiable collection of goods items to be transported or available to be transported from one consignor to one consignee via one or more modes of transport where each consignment is the subject of one single transport contract.

Unique UN Assigned ID: UN01004040

Dictionary Entry Name: Referenced_ Supply Chain_ Consignment. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="ReferencedConsignmentConsignee">ReferencedConsignmentConsignee</span> | [edi3:TradeParty](#TradeParty) | The consignee party for this referenced supply chain consignment. | UN01011055 | Referenced_ Supply Chain_ Consignment. Consignee. Trade_ Party
<span id="ReferencedConsignmentFreightForwarderAssignedID">ReferencedConsignmentFreightForwarderAssignedID</span> | xsd:token | The unique identifier assigned by the freight forwarder to this referenced supply chain consignment. | UN01004045 | Referenced_ Supply Chain_ Consignment. Freight Forwarder Assigned. Identifier
<span id="ReferencedConsignmentGrossWeight">ReferencedConsignmentGrossWeight</span> | xsd:decimal | A measure of the gross weight (mass) of this referenced supply chain consignment which includes the weight of packaging but which excludes the weight of any transport equipment. | UN01011048 | Referenced_ Supply Chain_ Consignment. Gross Weight. Measure
<span id="ReferencedConsignmentConsigneeAssignedID">ReferencedConsignmentConsigneeAssignedID</span> | xsd:token | The unique identifier assigned by the consignee to this referenced supply chain consignment. | UN01004043 | Referenced_ Supply Chain_ Consignment. Consignee Assigned. Identifier
<span id="ReferencedConsignmentCarrierAcceptanceDateTime">ReferencedConsignmentCarrierAcceptanceDateTime</span> | xsd:dateTime | The date, time, date time or other date time value when this referenced supply chain consignment will be, or has been, accepted by the carrier. | UN01011052 | Referenced_ Supply Chain_ Consignment. Carrier Acceptance. Date Time
<span id="ReferencedConsignmentUsedTransportEquipment">ReferencedConsignmentUsedTransportEquipment</span> | [edi3:TransportEquipment](#TransportEquipment) | Logistics transport equipment utilized for this referenced supply chain consignment. | UN01011067 | Referenced_ Supply Chain_ Consignment. Utilized. Logistics_ Transport Equipment
<span id="ReferencedConsignmentDespatchParty">ReferencedConsignmentDespatchParty</span> | [edi3:TradeParty](#TradeParty) | The party from whom this referenced supply chain consignment will be or has been despatched. | UN01011056 | Referenced_ Supply Chain_ Consignment. Despatch. Trade_ Party
<span id="ReferencedConsignmentLogisticsRiskAnalysisResult">ReferencedConsignmentLogisticsRiskAnalysisResult</span> | [edi3:RiskAnalysisResult](#RiskAnalysisResult) | A result of a logistics risk analysis specified for this referenced supply chain consignment. | UN01013182 | Referenced_ Supply Chain_ Consignment. Specified. Logistics_ Risk Analysis Result
<span id="ReferencedConsignmentConsignorAssignedID">ReferencedConsignmentConsignorAssignedID</span> | xsd:token | The unique identifier assigned by the consignor to this referenced supply chain consignment. | UN01004042 | Referenced_ Supply Chain_ Consignment. Consignor Assigned. Identifier
<span id="WarehouseStorageEvent">WarehouseStorageEvent</span> | [edi3:Event](#Event) | A warehouse storage event for this referenced supply chain consignment. | UN01011068 | Referenced_ Supply Chain_ Consignment. Warehouse_ Storage. Transport_ Event
<span id="ReferencedConsignmentDevanningEvent">ReferencedConsignmentDevanningEvent</span> | [edi3:Event](#Event) | A transport devanning event for this referenced supply chain consignment, i.e. the unloading of this consignment at the place of delivery. | UN01013183 | Referenced_ Supply Chain_ Consignment. Devanning. Transport_ Event
<span id="ReferencedConsignmentPreCarriageTransportMovement">ReferencedConsignmentPreCarriageTransportMovement</span> | [edi3:TransportMovement](#TransportMovement) | A pre-carriage logistics transport movement for this referenced supply chain consignment. | UN01011066 | Referenced_ Supply Chain_ Consignment. Pre-Carriage. Logistics_ Transport Movement
<span id="ReferencedConsignmentRegulatoryProcedure">ReferencedConsignmentRegulatoryProcedure</span> | [edi3:RegulatoryProcedure](#RegulatoryProcedure) | A cross-border regulatory procedure applicable to this referenced supply chain consignment. | UN01011064 | Referenced_ Supply Chain_ Consignment. Applicable. Cross-Border_ Regulatory Procedure
<span id="ReferencedConsignmentCarrier">ReferencedConsignmentCarrier</span> | [edi3:TradeParty](#TradeParty) | The carrier party for this referenced supply chain consignment. | UN01011059 | Referenced_ Supply Chain_ Consignment. Carrier. Trade_ Party
<span id="ReferencedConsignmentTradeTransaction">ReferencedConsignmentTradeTransaction</span> | [edi3:SupplyChainTradeTransaction](#SupplyChainTradeTransaction) | A trade transaction related to this referenced supply chain consignment. | UN01011060 | Referenced_ Supply Chain_ Consignment. Related. Supply Chain_ Trade Transaction
<span id="ReferencedConsignmentGrossVolume">ReferencedConsignmentGrossVolume</span> | xsd:decimal | A measure of the gross volume, normally calculated by multiplying the maximum length, width and height, of this referenced supply chain consignment. | UN01011050 | Referenced_ Supply Chain_ Consignment. Gross Volume. Measure
<span id="ReferencedConsignmentTransportContractDocument">ReferencedConsignmentTransportContractDocument</span> | [edi3:Document](#Document) | The transport contract document for this referenced supply chain consignment, such as an airwaybill or a seawaybill. | UN01011065 | Referenced_ Supply Chain_ Consignment. Transport Contract. Referenced_ Document
<span id="ReferencedConsignmentCarrierAcceptanceLocation">ReferencedConsignmentCarrierAcceptanceLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | The location where this referenced supply chain consignment will be or has been accepted by the carrier. | UN01011063 | Referenced_ Supply Chain_ Consignment. Carrier Acceptance. Logistics_ Location
<span id="ReferencedConsignmentIncludedConsignmentItem">ReferencedConsignmentIncludedConsignmentItem</span> | [edi3:ReferencedConsignmentItem](#ReferencedConsignmentItem) | A referenced consignment item included in this referenced supply chain consignment. | UN01004048 | Referenced_ Supply Chain_ Consignment. Included. Referenced_ Supply Chain_ Consignment Item
<span id="ReferencedConsignmentNetWeight">ReferencedConsignmentNetWeight</span> | xsd:decimal | A measure of the net weight (mass) of this referenced consignment which excludes the weight of packaging and the weight of any transport equipment. | UN01011049 | Referenced_ Supply Chain_ Consignment. Net Weight. Measure
<span id="ReferencedConsignmentConsignmentItemQuantity">ReferencedConsignmentConsignmentItemQuantity</span> | xsd:decimal | The number of consignment items separately defined for transport or customs purposes within this referenced supply chain consignment. | UN01011051 | Referenced_ Supply Chain_ Consignment. Consignment Item. Quantity
<span id="ReferencedConsignmentCustomsID">ReferencedConsignmentCustomsID</span> | xsd:token | The identifier, for customs purposes, for this referenced supply chain consignment. | UN01011053 | Referenced_ Supply Chain_ Consignment. Customs_ Identification. Identifier
<span id="ReferencedConsignmentDeliveryParty">ReferencedConsignmentDeliveryParty</span> | [edi3:TradeParty](#TradeParty) | The party to whom this referenced supply chain consignment will be or has been delivered. | UN01011057 | Referenced_ Supply Chain_ Consignment. Delivery. Trade_ Party
<span id="ReferencedConsignmentCarrierAssignedID">ReferencedConsignmentCarrierAssignedID</span> | xsd:token | The unique identifier assigned by the carrier to this referenced supply chain consignment, such as a booking reference number when cargo space is reserved prior to loading. | UN01004044 | Referenced_ Supply Chain_ Consignment. Carrier Assigned. Identifier
<span id="ReferencedConsignmentSequenceNumber">ReferencedConsignmentSequenceNumber</span> | xsd:decimal | The sequence number for this referenced supply chain consignment. | UN01004046 | Referenced_ Supply Chain_ Consignment. Sequence. Numeric
<span id="ReferencedConsignmentVanningEvent">ReferencedConsignmentVanningEvent</span> | [edi3:Event](#Event) | The vanning event (the loading of this consignment at the place of its original despatch) for this referenced supply chain consignment. | UN01011062 | Referenced_ Supply Chain_ Consignment. Vanning. Transport_ Event
<span id="ReferencedConsignmentTransportPackage">ReferencedConsignmentTransportPackage</span> | [edi3:Package](#Package) | Transport packages for this referenced supply chain consignment. | UN01011061 | Referenced_ Supply Chain_ Consignment. Transport. Logistics_ Package
<span id="ReferencedConsignmentTransportSplitDescription">ReferencedConsignmentTransportSplitDescription</span> | xsd:string | The textual description of the transport split of this referenced supply chain consignment across different transport means or transport equipment. | UN01004047 | Referenced_ Supply Chain_ Consignment. Transport Split Description. Text
<span id="ReferencedConsignmentID">ReferencedConsignmentID</span> | xsd:token | A unique identifier for this referenced supply chain consignment. | UN01004041 | Referenced_ Supply Chain_ Consignment. Identification. Identifier
<span id="ReferencedConsignmentConsignor">ReferencedConsignmentConsignor</span> | [edi3:TradeParty](#TradeParty) | The consignor party for this referenced supply chain consignment. | UN01011054 | Referenced_ Supply Chain_ Consignment. Consignor. Trade_ Party


<h1 id="TradeSettlementPaymentMonetarySummation">TradeSettlementPaymentMonetarySummation</h1>

Type: rdf:Class

Definition: A collection of monetary amount totals specified for a trade settlement payment.

Unique UN Assigned ID: UN01011912

Dictionary Entry Name: Trade Settlement Payment_ Monetary Summation. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="TradeSettlementPaymentMonetarySummationAdjustedBalanceOutAmount">TradeSettlementPaymentMonetarySummationAdjustedBalanceOutAmount</span> | xsd:decimal | A monetary value that is an adjusted amount balanced out for this trade settlement payment monetary summation. | UN01011916 | Trade Settlement Payment_ Monetary Summation. Adjusted_ Balance Out. Amount
<span id="TradeSettlementPaymentMonetarySummationTaxTotalAmount">TradeSettlementPaymentMonetarySummationTaxTotalAmount</span> | xsd:decimal | A monetary value of the total of all tax amounts reported in this trade settlement payment monetary summation. | UN01013027 | Trade Settlement Payment_ Monetary Summation. Tax Total. Amount
<span id="TradeSettlementPaymentPaymentBalanceOut">TradeSettlementPaymentPaymentBalanceOut</span> | [edi3:PaymentBalanceOut](#PaymentBalanceOut) | A balance out applicable to this trade settlement payment monetary summation. | UN01011917 | Trade Settlement Payment_ Monetary Summation. Applicable. Payment_ Balance Out
<span id="TradeSettlementPaymentMonetarySummationPaymentTotalAmount">TradeSettlementPaymentMonetarySummationPaymentTotalAmount</span> | xsd:decimal | A monetary value of a payment total reported in this trade settlement payment monetary summation. | UN01011914 | Trade Settlement Payment_ Monetary Summation. Payment Total. Amount
<span id="TradeSettlementPaymentMonetarySummationLineTotalAmountIncludingTaxes">TradeSettlementPaymentMonetarySummationLineTotalAmountIncludingTaxes</span> | xsd:decimal | A monetary value of the line total, including taxes, being reported in this trade settlement payment monetary summation. | UN01013110 | Trade Settlement Payment_ Monetary Summation. Including Taxes_ Line Total. Amount
<span id="TradeSettlementPaymentMonetarySummationNetLineTotalAmount">TradeSettlementPaymentMonetarySummationNetLineTotalAmount</span> | xsd:decimal | A monetary value of the net total of all line amounts, including line level allowances and charges and excluding line level taxes, being reported in this trade settlement payment monetary summation. | UN01013469 | Trade Settlement Payment_ Monetary Summation. Net_ Line Total. Amount
<span id="TradeSettlementPaymentMonetarySummationGrandTotalAmount">TradeSettlementPaymentMonetarySummationGrandTotalAmount</span> | xsd:decimal | A monetary value of a grand total reported in this trade settlement payment monetary summation. | UN01013468 | Trade Settlement Payment_ Monetary Summation. Grand Total. Amount
<span id="TradeSettlementPaymentMonetarySummationBalanceOutAmount">TradeSettlementPaymentMonetarySummationBalanceOutAmount</span> | xsd:decimal | A monetary value that is an amount balanced out for this trade settlement payment monetary summation. | UN01011915 | Trade Settlement Payment_ Monetary Summation. Balance Out. Amount


<h1 id="TradeSettlementHeaderMonetarySummation">TradeSettlementHeaderMonetarySummation</h1>

Type: rdf:Class

Definition: A collection of monetary amount totals, specified at header level, for a trade settlement.

Unique UN Assigned ID: UN01011871

Dictionary Entry Name: Trade Settlement Header_ Monetary Summation. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="TradeSettlementHeaderMonetarySummationGrandTotalAmount">TradeSettlementHeaderMonetarySummationGrandTotalAmount</span> | xsd:decimal | A monetary value of the grand total of this trade settlement header monetary summation, to include addition and subtraction of individual summation amounts. | UN01011878 | Trade Settlement Header_ Monetary Summation. Grand Total. Amount
<span id="TradeSettlementHeaderMonetarySummationGrossLineTotalAmount">TradeSettlementHeaderMonetarySummationGrossLineTotalAmount</span> | xsd:decimal | A monetary value of the total of all line amounts, excluding line level allowances and charges and taxes, being reported in this trade settlement header monetary summation. | UN01011890 | Trade Settlement Header_ Monetary Summation. Gross_ Line Total. Amount
<span id="InsuranceChargeTotalAmount">InsuranceChargeTotalAmount</span> | xsd:decimal | A monetary value of the total of all insurance charges being reported in this trade settlement header monetary summation. | UN01012667 | Trade Settlement Header_ Monetary Summation. Insurance_ Charge Total. Amount
<span id="TradeSettlementHeaderMonetarySummationPaymentTotalAmount">TradeSettlementHeaderMonetarySummationPaymentTotalAmount</span> | xsd:decimal | A monetary value of a payment total reported in this header trade settlement payment monetary summation. | UN01011884 | Trade Settlement Header_ Monetary Summation. Payment Total. Amount
<span id="TradeSettlementHeaderMonetarySummationTotalRetailValueInformationAmount">TradeSettlementHeaderMonetarySummationTotalRetailValueInformationAmount</span> | xsd:decimal | A monetary value which constitutes the total retail value stated for information purposes in this trade settlement header monetary summation. | UN01011889 | Trade Settlement Header_ Monetary Summation. Total Retail Value_ Information. Amount
<span id="RoundingAmount">RoundingAmount</span> | xsd:decimal | A monetary value of a rounding amount being applied in this trade settlement header monetary summation. | UN01011877 | Trade Settlement Header_ Monetary Summation. Rounding. Amount
<span id="TradeSettlementHeaderMonetarySummationNetLineTotalAmount">TradeSettlementHeaderMonetarySummationNetLineTotalAmount</span> | xsd:decimal | A monetary value of the total of all line amounts, including line level allowances and charges and excluding line level taxes, being reported in this trade settlement header monetary summation. | UN01011891 | Trade Settlement Header_ Monetary Summation. Net_ Line Total. Amount
<span id="ProductValueExcludingTobaccoTaxInformationAmount">ProductValueExcludingTobaccoTaxInformationAmount</span> | xsd:decimal | A monetary value which constitutes the total product value, excluding tobacco tax, stated for information purposes in this trade settlement header monetary summation. | UN01011888 | Trade Settlement Header_ Monetary Summation. Product Value Excluding Tobacco Tax_ Information. Amount
<span id="RetailValueExcludingTaxInformationAmount">RetailValueExcludingTaxInformationAmount</span> | xsd:decimal | A monetary value which constitutes the retail value, excluding all duties and taxes, stated for information purposes in this trade settlement header monetary summation. | UN01011886 | Trade Settlement Header_ Monetary Summation. Retail Value Excluding Tax_ Information. Amount
<span id="TotalDiscountAmount">TotalDiscountAmount</span> | xsd:decimal | A monetary value of a total discount reported in this trade settlement header monetary summation. | UN01011881 | Trade Settlement Header_ Monetary Summation. Total Discount. Amount
<span id="TradeSettlementHeaderMonetarySummationBalanceOutAmount">TradeSettlementHeaderMonetarySummationBalanceOutAmount</span> | xsd:decimal | A monetary value that is an amount balanced out for this trade settlement header monetary summation. | UN01011893 | Trade Settlement Header_ Monetary Summation. Balance Out. Amount
<span id="TradeSettlementHeaderMonetarySummationChargeTotalAmount">TradeSettlementHeaderMonetarySummationChargeTotalAmount</span> | xsd:decimal | A monetary value of the total of all charge amounts being reported in this trade settlement header monetary summation. | UN01011873 | Trade Settlement Header_ Monetary Summation. Charge Total. Amount
<span id="TradeSettlementHeaderMonetarySummationTotalAllowanceChargeAmount">TradeSettlementHeaderMonetarySummationTotalAllowanceChargeAmount</span> | xsd:decimal | A monetary value of a total allowance and charge reported in this trade settlement header monetary summation. | UN01011882 | Trade Settlement Header_ Monetary Summation. Total Allowance Charge. Amount
<span id="TradeSettlementHeaderMonetarySummationTaxBasisTotalAmount">TradeSettlementHeaderMonetarySummationTaxBasisTotalAmount</span> | xsd:decimal | A monetary value of the total of all tax basis amounts being reported in this trade settlement monetary summation. | UN01011875 | Trade Settlement Header_ Monetary Summation. Tax Basis Total. Amount
<span id="TradeSettlementHeaderMonetarySummationDuePayableAmount">TradeSettlementHeaderMonetarySummationDuePayableAmount</span> | xsd:decimal | A monetary value that is an amount due and payable for this trade settlement header monetary summation, such as the amount due to the creditor. | UN01011883 | Trade Settlement Header_ Monetary Summation. Due Payable. Amount
<span id="TradeSettlementHeaderHeaderBalanceOut">TradeSettlementHeaderHeaderBalanceOut</span> | [edi3:HeaderBalanceOut](#HeaderBalanceOut) | A header balance out applicable to this trade settlement header monetary summation. | UN01011895 | Trade Settlement Header_ Monetary Summation. Applicable. Header_ Balance Out
<span id="TradeSettlementHeaderMonetarySummationAllowanceTotalAmount">TradeSettlementHeaderMonetarySummationAllowanceTotalAmount</span> | xsd:decimal | A monetary value of the total of all allowance amounts being reported in this trade settlement header monetary summation. | UN01011874 | Trade Settlement Header_ Monetary Summation. Allowance Total. Amount
<span id="TotalPrepaidAmount">TotalPrepaidAmount</span> | xsd:decimal | A monetary value of a prepaid total reported in this trade settlement header monetary summation. | UN01011880 | Trade Settlement Header_ Monetary Summation. Total Prepaid. Amount
<span id="LineTotalAmountExcludingTaxes">LineTotalAmountExcludingTaxes</span> | xsd:decimal | A monetary value of the total of all line amounts, excluding all duties and taxes, being reported in this trade settlement header monetary summation. | UN01012995 | Trade Settlement Header_ Monetary Summation. Excluding Taxes_ Line Total. Amount
<span id="TradeSettlementHeaderMonetarySummationTaxTotalAmount">TradeSettlementHeaderMonetarySummationTaxTotalAmount</span> | xsd:decimal | A monetary value of the total of all tax amounts being reported in this trade settlement header monetary summation. | UN01011876 | Trade Settlement Header_ Monetary Summation. Tax Total. Amount
<span id="TradeSettlementHeaderMonetarySummationLineTotalAmountIncludingTaxes">TradeSettlementHeaderMonetarySummationLineTotalAmountIncludingTaxes</span> | xsd:decimal | A monetary value of the total of all line amounts, including all duties and taxes, being reported in this trade settlement header monetary summation. | UN01012996 | Trade Settlement Header_ Monetary Summation. Including Taxes_ Line Total. Amount
<span id="TradeSettlementHeaderMonetarySummationLineTotalAmount">TradeSettlementHeaderMonetarySummationLineTotalAmount</span> | xsd:decimal | A monetary value of the line amount total being reported in this trade settlement header monetary summation. | UN01011872 | Trade Settlement Header_ Monetary Summation. Line Total. Amount
<span id="TradeSettlementHeaderMonetarySummationAdjustedBalanceOutAmount">TradeSettlementHeaderMonetarySummationAdjustedBalanceOutAmount</span> | xsd:decimal | A monetary value that is an adjusted amount balanced out for this trade settlement header monetary summation. | UN01011894 | Trade Settlement Header_ Monetary Summation. Adjusted_ Balance Out. Amount
<span id="TotalDiscountBasisAmount">TotalDiscountBasisAmount</span> | xsd:decimal | A monetary value of a total discount basis reported in this trade settlement header monetary summation. | UN01011885 | Trade Settlement Header_ Monetary Summation. Total Discount Basis. Amount
<span id="GrandTotalSpecifiedFinancialAdjustment">GrandTotalSpecifiedFinancialAdjustment</span> | [edi3:FinancialAdjustment](#FinancialAdjustment) | The financial adjustment of the grand total specified for this trade settlement header monetary summation. | UN01013299 | Trade Settlement Header_ Monetary Summation. Grand Total_ Specified. Financial_ Adjustment
<span id="TradeSettlementHeaderMonetarySummationNetIncludingTaxesLineTotalAmount">TradeSettlementHeaderMonetarySummationNetIncludingTaxesLineTotalAmount</span> | xsd:decimal | A monetary value of the total of all line amounts, including line level allowances and charges and including line level taxes, being reported in this trade settlement header monetary summation. | UN01011892 | Trade Settlement Header_ Monetary Summation. Net Including Taxes_ Line Total. Amount
<span id="TotalDepositFeeInformationAmount">TotalDepositFeeInformationAmount</span> | xsd:decimal | A monetary value of the total deposit fee stated for information purposes in this trade settlement header monetary summation. | UN01011887 | Trade Settlement Header_ Monetary Summation. Total Deposit Fee_ Information. Amount


<h1 id="TradeSettlementLineMonetarySummation">TradeSettlementLineMonetarySummation</h1>

Type: rdf:Class

Definition: A collection of monetary amount totals, specified at line level, for a trade settlement.

Unique UN Assigned ID: UN01011896

Dictionary Entry Name: Trade Settlement Line_ Monetary Summation. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="TradeSettlementLineMonetarySummationInformationAmount">TradeSettlementLineMonetarySummationInformationAmount</span> | xsd:decimal | A monetary value of an amount being reported for information in this trade settlement monetary summation. | UN01011903 | Trade Settlement Line_ Monetary Summation. Information. Amount
<span id="TradeSettlementLineMonetarySummationLineTotalAmountIncludingTaxes">TradeSettlementLineMonetarySummationLineTotalAmountIncludingTaxes</span> | xsd:decimal | A monetary value of the line total, including taxes, being reported in this trade settlement line monetary summation. | UN01013109 | Trade Settlement Line_ Monetary Summation. Including Taxes_ Line Total. Amount
<span id="TradeSettlementLineMonetarySummationNetIncludingTaxesLineTotalAmount">TradeSettlementLineMonetarySummationNetIncludingTaxesLineTotalAmount</span> | xsd:decimal | A monetary value of the total of all line amounts, including line level allowances and charges and including line level taxes, being reported in this trade settlement line monetary summation. | UN01011910 | Trade Settlement Line_ Monetary Summation. Net Including Taxes_ Line Total. Amount
<span id="TradeSettlementLineMonetarySummationTotalRetailValueInformationAmount">TradeSettlementLineMonetarySummationTotalRetailValueInformationAmount</span> | xsd:decimal | A monetary value which constitutes the total retail value stated for information purposes in this trade settlement line monetary summation. | UN01011907 | Trade Settlement Line_ Monetary Summation. Total Retail Value_ Information. Amount
<span id="TradeSettlementLineMonetarySummationGrandTotalAmount">TradeSettlementLineMonetarySummationGrandTotalAmount</span> | xsd:decimal | A monetary value of the grand total of this trade settlement line monetary summation, to include addition and subtraction of individual summation amounts. | UN01011902 | Trade Settlement Line_ Monetary Summation. Grand Total. Amount
<span id="TradeSettlementLineMonetarySummationDuePayableAmount">TradeSettlementLineMonetarySummationDuePayableAmount</span> | xsd:decimal | A monetary value that is an amount due and payable for this trade settlement line monetary summation, such as the amount due to the creditor. | UN01011905 | Trade Settlement Line_ Monetary Summation. Due Payable. Amount
<span id="TradeSettlementLineMonetarySummationPaymentTotalAmount">TradeSettlementLineMonetarySummationPaymentTotalAmount</span> | xsd:decimal | A monetary value of a payment total reported in this trade settlement line monetary summation. | UN01011906 | Trade Settlement Line_ Monetary Summation. Payment Total. Amount
<span id="TradeSettlementLineMonetarySummationTaxBasisTotalAmount">TradeSettlementLineMonetarySummationTaxBasisTotalAmount</span> | xsd:decimal | A monetary value of the total of all tax basis amounts being reported in this trade settlement line monetary summation. | UN01011900 | Trade Settlement Line_ Monetary Summation. Tax Basis Total. Amount
<span id="TradeSettlementLineMonetarySummationNetLineTotalAmount">TradeSettlementLineMonetarySummationNetLineTotalAmount</span> | xsd:decimal | A monetary value of the total of all line amounts, including line level allowances and charges and excluding line level taxes, being reported in this trade settlement line monetary summation. | UN01011909 | Trade Settlement Line_ Monetary Summation. Net_ Line Total. Amount
<span id="TradeSettlementLineMonetarySummationLineTotalAmount">TradeSettlementLineMonetarySummationLineTotalAmount</span> | xsd:decimal | A monetary value of the line amount total being reported in this trade settlement line monetary summation. | UN01011897 | Trade Settlement Line_ Monetary Summation. Line Total. Amount
<span id="TradeSettlementLineMonetarySummationTaxTotalAmount">TradeSettlementLineMonetarySummationTaxTotalAmount</span> | xsd:decimal | A monetary value of the total of all tax amounts being reported in this trade settlement line monetary summation. | UN01011901 | Trade Settlement Line_ Monetary Summation. Tax Total. Amount
<span id="TradeSettlementLineMonetarySummationTotalAllowanceChargeAmount">TradeSettlementLineMonetarySummationTotalAllowanceChargeAmount</span> | xsd:decimal | A monetary value of a total allowance and charge reported in this trade settlement line monetary summation. | UN01011904 | Trade Settlement Line_ Monetary Summation. Total Allowance Charge. Amount
<span id="TradeSettlementLineMonetarySummationAllowanceTotalAmount">TradeSettlementLineMonetarySummationAllowanceTotalAmount</span> | xsd:decimal | A monetary value of the total of all allowance amounts being reported in this trade settlement line monetary summation. | UN01011899 | Trade Settlement Line_ Monetary Summation. Allowance Total. Amount
<span id="ProductWeightLossInformationAmount">ProductWeightLossInformationAmount</span> | xsd:decimal | A monetary value of the loss of weight of a product, such as fresh goods, stated for information purposes in this trade settlement line monetary summation. | UN01011911 | Trade Settlement Line_ Monetary Summation. Product Weight Loss_ Information. Amount
<span id="TradeSettlementLineMonetarySummationChargeTotalAmount">TradeSettlementLineMonetarySummationChargeTotalAmount</span> | xsd:decimal | A monetary value of the total of all charge amounts being reported in this trade settlement line monetary summation. | UN01011898 | Trade Settlement Line_ Monetary Summation. Charge Total. Amount


<h1 id="PaymentDiscountTerms">PaymentDiscountTerms</h1>

Type: rdf:Class

Definition: Trade terms and conditions by which a discount is or can be applied to a payable amount.

Unique UN Assigned ID: UN01004617

Dictionary Entry Name: Trade_ Payment Discount Terms. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="PaymentDiscountTermsBasisPeriodMeasure">PaymentDiscountTermsBasisPeriodMeasure</span> | xsd:decimal | The measure of the basis period for these trade payment discount terms. | UN01004619 | Trade_ Payment Discount Terms. Basis Period. Measure
<span id="PaymentDiscountTermsBasisAmount">PaymentDiscountTermsBasisAmount</span> | xsd:decimal | A monetary value used as a basis to calculate the discount in these trade payment discount terms. | UN01004620 | Trade_ Payment Discount Terms. Basis. Amount
<span id="PaymentDiscountTermsCalculationPercent">PaymentDiscountTermsCalculationPercent</span> | xsd:decimal | The percent used to calculate the discount in these trade payment discount terms. | UN01004621 | Trade_ Payment Discount Terms. Calculation. Percent
<span id="PaymentDiscountTermsBasisDateTime">PaymentDiscountTermsBasisDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value used as the basis to calculate the discount in the trade payment discount terms. | UN01004618 | Trade_ Payment Discount Terms. Basis. Date Time


<h1 id="FinancialCard">FinancialCard</h1>

Type: rdf:Class

Definition: A card used to represent a financial account for a trade settlement.

Unique UN Assigned ID: UN01004493

Dictionary Entry Name: Trade Settlement_ Financial Card. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="FinancialCardTypeCode">FinancialCardTypeCode</span> | xsd:token | The code specifying the type of this trade settlement financial card, such as debit or credit. | UN01004496 | Trade Settlement_ Financial Card. Type. Code
<span id="FinancialCardDescription">FinancialCardDescription</span> | xsd:string | The textual description of this trade settlement financial card. | UN01009967 | Trade Settlement_ Financial Card. Description. Text
<span id="FinancialCardID">FinancialCardID</span> | xsd:token | The unique identifier, commonly known as the card number, of this trade settlement financial card. | UN01004495 | Trade Settlement_ Financial Card. Identification. Identifier
<span id="CardholderName">CardholderName</span> | xsd:string | The cardholder name as it appears on this trade settlement financial card. This may include both an individual authorized to use the card as well as the organization that owns the card. | UN01004497 | Trade Settlement_ Financial Card. Cardholder Name. Text
<span id="MicrochipIndicator">MicrochipIndicator</span> | xsd:boolean | The indication of whether or not this trade settlement financial card has a microchip. | UN01004494 | Trade Settlement_ Financial Card. Microchip. Indicator
<span id="VerificationNumber">VerificationNumber</span> | xsd:decimal | The unique card verification number for security purposes to help verify the card user is in actual possession of this trade settlement financial card. | UN01004499 | Trade Settlement_ Financial Card. Verification. Numeric
<span id="CreditLimitAmount">CreditLimitAmount</span> | xsd:decimal | A monetary value of the credit limit for this trade settlement financial card. | UN01006085 | Trade Settlement_ Financial Card. Credit Limit. Amount
<span id="ExpiryDate">ExpiryDate</span> | xsd:date | The date of expiry up to which this trade settlement financial card is valid. | UN01004498 | Trade Settlement_ Financial Card. Expiry. Date
<span id="IssuingCompanyName">IssuingCompanyName</span> | xsd:string | The issuing company name, expressed as text, for this trade settlement financial card. | UN01009966 | Trade Settlement_ Financial Card. Issuing Company Name. Text
<span id="ValidFromDate">ValidFromDate</span> | xsd:dateTime | The date from which this trade settlement financial card is valid. | UN01004500 | Trade Settlement_ Financial Card. Valid From. Date Time
<span id="InterestRate">InterestRate</span> | xsd:decimal | The interest rate expressed as a percentage for this trade settlement financial card. | UN01006087 | Trade Settlement_ Financial Card. Interest Rate. Percent


<h1 id="LocationParty">LocationParty</h1>

Type: rdf:Class

Definition: An individual, a group, or a body having a role related to a location.

Unique UN Assigned ID: UN01003661

Dictionary Entry Name: Location_ Party. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="LocationPartyCountryCode">LocationPartyCountryCode</span> | xsd:token | A unique country identifier for this location party. | UN01003667 | Location_ Party. Country. Identifier
<span id="LocationPartyTelephone">LocationPartyTelephone</span> | [edi3:UniversalCommunication](#UniversalCommunication) | Telephone communication information for this location party. | UN01003671 | Location_ Party. Telephone. Universal_ Communication
<span id="LocationTransportPerson">LocationTransportPerson</span> | [edi3:TransportPerson](#TransportPerson) | A transport related person specified for this location party. | UN01003668 | Location_ Party. Specified. Transport_ Person
<span id="LocationPartyPostalAddress">LocationPartyPostalAddress</span> | [edi3:TradeAddress](#TradeAddress) | A postal address for this location party. | UN01003670 | Location_ Party. Postal. Trade_ Address
<span id="LocationPartyName">LocationPartyName</span> | xsd:string | A name, expressed as text, for this location party. | UN01003664 | Location_ Party. Name. Text
<span id="LocationPartyFax">LocationPartyFax</span> | [edi3:UniversalCommunication](#UniversalCommunication) | Fax communication information for this location party. | UN01003672 | Location_ Party. Fax. Universal_ Communication
<span id="ProvidedTransportService">ProvidedTransportService</span> | [edi3:Service](#Service) | A transport service provided by this location party. | UN01003674 | Location_ Party. Provided. Transport_ Service
<span id="DefinedContact">DefinedContact</span> | [edi3:Contact](#Contact) | A trade contact defined for this location party. | UN01003669 | Location_ Party. Defined. Trade_ Contact
<span id="LocationPartyRoleCode">LocationPartyRoleCode</span> | xsd:token | A code specifying a role of this location party. | UN01003666 | Location_ Party. Role. Code
<span id="LocationPartyURI">LocationPartyURI</span> | [edi3:UniversalCommunication](#UniversalCommunication) | Uniform Resource Identifier (URI) communication information for this location party, such as a web or email address. | UN01003673 | Location_ Party. URI. Universal_ Communication


<h1 id="TradeParty">TradeParty</h1>

Type: rdf:Class

Definition: An individual, a group, or a body having a role in a trade business function.

Unique UN Assigned ID: UN01004594

Dictionary Entry Name: Trade_ Party. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="TradePartyRoleText">TradePartyRoleText</span> | xsd:string | A role, expressed as text, for this trade party. | UN01013115 | Trade_ Party. Role. Text
<span id="TradeLegalOrganization">TradeLegalOrganization</span> | [edi3:Organization](#Organization) | The legally constituted organization specified for this trade party. | UN01004601 | Trade_ Party. Specified. Legal_ Organization
<span id="TradeTaxRegistration">TradeTaxRegistration</span> | [edi3:TaxRegistration](#TaxRegistration) | A tax registration specified for this trade party. | UN01004611 | Trade_ Party. Specified. Tax_ Registration
<span id="TradeGovernmentRegistration">TradeGovernmentRegistration</span> | [edi3:GovernmentRegistration](#GovernmentRegistration) | A governmental registration specified for this trade party. | UN01011071 | Trade_ Party. Specified. Government_ Registration
<span id="TradePartyDescription">TradePartyDescription</span> | xsd:string | A textual description of this trade party. | UN01010146 | Trade_ Party. Description. Text
<span id="TradePartyGlobalID">TradePartyGlobalID</span> | xsd:token | A globally unique identifier of this trade party. | UN01004596 | Trade_ Party. Global_ Identification. Identifier
<span id="LogoBinaryFile">LogoBinaryFile</span> | [edi3:BinaryFile](#BinaryFile) | A file containing a specified binary representation of a logo associated with this trade party. | UN01006723 | Trade_ Party. Logo_ Associated. Specified_ Binary File
<span id="TradePartyLanguageCode">TradePartyLanguageCode</span> | xsd:token | A code specifying a language for this trade party. | UN01009017 | Trade_ Party. Language. Code
<span id="TradePartyTransportService">TradePartyTransportService</span> | [edi3:Service](#Service) | A transport service provided by this trade party. | UN01004608 | Trade_ Party. Provided. Transport_ Service
<span id="TradePartyName">TradePartyName</span> | xsd:string | The name, expressed as text, for this trade party. | UN01004598 | Trade_ Party. Name. Text
<span id="DUNSID">DUNSID</span> | xsd:token | The unique nine-digit Data Universal Numbering System (DUNS) identifier for this trade party. | UN01006091 | Trade_ Party. DUNS_ Identification. Identifier
<span id="OwnedCreditorFinancialAccount">OwnedCreditorFinancialAccount</span> | [edi3:CreditorFinancialAccount](#CreditorFinancialAccount) | The creditor financial account owned by this trade party. | UN01013304 | Trade_ Party. Owned. Creditor_ Financial Account
<span id="TradePartyTypeCode">TradePartyTypeCode</span> | xsd:token | A code specifying the type of trade party that is independent of its role. | UN01004597 | Trade_ Party. Type. Code
<span id="RegisteredID">RegisteredID</span> | xsd:token | A registered identifier of this trade party. | UN01013041 | Trade_ Party. Registered_ Identification. Identifier
<span id="TradePartyRoleCode">TradePartyRoleCode</span> | xsd:token | A code specifying the role of this trade party. | UN01004599 | Trade_ Party. Role. Code
<span id="TradePartyPostalAddress">TradePartyPostalAddress</span> | [edi3:TradeAddress](#TradeAddress) | The postal address for this trade party. | UN01004603 | Trade_ Party. Postal. Trade_ Address
<span id="TradePartyID">TradePartyID</span> | xsd:token | A unique identifier of this trade party. | UN01004595 | Trade_ Party. Identification. Identifier
<span id="GLNID">GLNID</span> | xsd:token | A Global Location Number (GLN) identifier for this trade party. | UN01006092 | Trade_ Party. GLN_ Identification. Identifier
<span id="DefinedContactDetails">DefinedContactDetails</span> | [edi3:Contact](#Contact) | A trade contact defined for this trade party. | UN01004602 | Trade_ Party. Defined. Trade_ Contact
<span id="TradePartyLogisticsServiceCharge">TradePartyLogisticsServiceCharge</span> | [edi3:ServiceCharge](#ServiceCharge) | A logistics service charge applicable to this trade party. | UN01009008 | Trade_ Party. Applicable. Logistics_ Service Charge
<span id="SpecifiedFinancialIdentity">SpecifiedFinancialIdentity</span> | [edi3:FinancialIdentity](#FinancialIdentity) | The financial identity specified for this trade party. | UN01013303 | Trade_ Party. Specified. Financial_ Identity
<span id="TradePartyAssociatedParty">TradePartyAssociatedParty</span> | [edi3:TradeParty](#TradeParty) | A party associated with this trade party, such as a local agent of a shipping line. | UN01004609 | Trade_ Party. Associated. Trade_ Party
<span id="TradeAuthoritativeSignatoryPerson">TradeAuthoritativeSignatoryPerson</span> | [edi3:AuthoritativeSignatoryPerson](#AuthoritativeSignatoryPerson) | A person specified to sign on behalf of this trade party. | UN01006142 | Trade_ Party. Specified. Authoritative Signatory_ Person
<span id="TradePartyLogisticsLocation">TradePartyLogisticsLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | A logistics related location or place specified for this trade party. | UN01004610 | Trade_ Party. Specified. Logistics_ Location
<span id="TradePartyTelephone">TradePartyTelephone</span> | [edi3:UniversalCommunication](#UniversalCommunication) | A telephone communication for this trade party. | UN01004604 | Trade_ Party. Telephone. Universal_ Communication
<span id="SpecifiedContactPerson">SpecifiedContactPerson</span> | [edi3:ContactPerson](#ContactPerson) | A contact person specified for this trade party. | UN01013301 | Trade_ Party. Specified. Contact_ Person
<span id="TradePartyURI">TradePartyURI</span> | [edi3:UniversalCommunication](#UniversalCommunication) | A Uniform Resource Identifier (URI) communication for this trade party, such as a web or email address. | UN01004606 | Trade_ Party. URI. Universal_ Communication
<span id="TradePartySpecifiedProprietaryIdentity">TradePartySpecifiedProprietaryIdentity</span> | [edi3:ProprietaryIdentity](#ProprietaryIdentity) | A proprietary identity specified for this trade party. | UN01013302 | Trade_ Party. Specified. Proprietary_ Identity
<span id="QualityAssuranceIndicator">QualityAssuranceIndicator</span> | xsd:boolean | The indication of whether or not this trade party is quality assured. | UN01004600 | Trade_ Party. Quality Assurance. Indicator
<span id="TradePartyLogisticsRiskAnalysisResult">TradePartyLogisticsRiskAnalysisResult</span> | [edi3:RiskAnalysisResult](#RiskAnalysisResult) | A result of a logistics risk analysis calculation specified for this trade party. | UN01013054 | Trade_ Party. Specified. Logistics_ Risk Analysis Result


<h1 id="RequestingParty">RequestingParty</h1>

Type: rdf:Class

Definition: An individual, a group, or a body having a role as a requestor.

Unique UN Assigned ID: UN01002017

Dictionary Entry Name: Requesting_ Party. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="SpecifiedLineOfCreditFinancingFinancialAccount">SpecifiedLineOfCreditFinancingFinancialAccount</span> | [edi3:FinancingFinancialAccount](#FinancingFinancialAccount) | The financing financial account, used for managing the line of credit, specified for this requesting party. | UN01013293 | Requesting_ Party. Line Of Credit_ Specified. Financing_ Financial Account
<span id="RequestingPartyTypeCode">RequestingPartyTypeCode</span> | xsd:token | The code specifying the type of requesting party. | UN01002019 | Requesting_ Party. Type. Code
<span id="SpecifiedProjectPerson">SpecifiedProjectPerson</span> | [edi3:ProjectPerson](#ProjectPerson) | The project person specified for this requesting party. | UN01002025 | Requesting_ Party. Specified. Project_ Person
<span id="ProjectOrganization">ProjectOrganization</span> | [edi3:ProjectOrganization](#ProjectOrganization) | The project organization, such as a business or government body, for this requesting party. | UN01002024 | Requesting_ Party. Specified. Project_ Organization
<span id="RequestingPartyDescription">RequestingPartyDescription</span> | xsd:string | The textual description of this requesting party. | UN01002021 | Requesting_ Party. Description. Text
<span id="RequestingPartyLanguageCode">RequestingPartyLanguageCode</span> | xsd:token | A code specifying a language for this requesting party. | UN01002023 | Requesting_ Party. Language. Code
<span id="AccessRightsCode">AccessRightsCode</span> | xsd:token | The code specifying the access rights, such as unlimited, restricted, prohibited, for this requesting party. | UN01002022 | Requesting_ Party. Access Rights. Code
<span id="RequestingPartySpecifiedProprietaryIdentity">RequestingPartySpecifiedProprietaryIdentity</span> | [edi3:ProprietaryIdentity](#ProprietaryIdentity) | A proprietary identity specified for this requesting party. | UN01013292 | Requesting_ Party. Specified. Proprietary_ Identity
<span id="RequestingPartyID">RequestingPartyID</span> | xsd:token | The unique identifier for this requesting party. | UN01002018 | Requesting_ Party. Identification. Identifier
<span id="RequestingPartySpecifiedCreditorFinancialAccount">RequestingPartySpecifiedCreditorFinancialAccount</span> | [edi3:CreditorFinancialAccount](#CreditorFinancialAccount) | The creditor financial account, used for crediting, specified for this requesting party. | UN01013294 | Requesting_ Party. Specified. Creditor_ Financial Account
<span id="RequestingPartyName">RequestingPartyName</span> | xsd:string | The name, expressed as text, for this requesting party. | UN01002020 | Requesting_ Party. Name. Text


<h1 id="MaterialComponent">MaterialComponent</h1>

Type: rdf:Class

Definition: An unused and rejected as unwanted component of transport material.

Unique UN Assigned ID: UN01013152

Dictionary Entry Name: Transport Waste_ Material Component. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="MaterialComponentTypeCode">MaterialComponentTypeCode</span> | xsd:token | A code specifying a type of transport waste material component. | UN01013153 | Transport Waste_ Material Component. Type. Code
<span id="RetainedMeasure">RetainedMeasure</span> | xsd:decimal | The measure for this retained transport waste material component. | UN01013157 | Transport Waste_ Material Component. Retained. Measure
<span id="GeneratedMeasure">GeneratedMeasure</span> | xsd:decimal | The estimated measure for this generated transport waste material component. | UN01013156 | Transport Waste_ Material Component. Estimated_ Generated. Measure
<span id="DischargedMeasure">DischargedMeasure</span> | xsd:decimal | The planned measure for this discharged transport waste material component. | UN01013158 | Transport Waste_ Material Component. Planned_ Discharged. Measure
<span id="MaterialComponentDescription">MaterialComponentDescription</span> | xsd:string | A textual description for this transport waste material component. | UN01013154 | Transport Waste_ Material Component. Description. Text
<span id="RemainingDeliveryEvent">RemainingDeliveryEvent</span> | [edi3:Event](#Event) | A delivery event for this remaining transport waste material component. | UN01013159 | Transport Waste_ Material Component. Remaining_ Delivery. Transport_ Event


<h1 id="CreditorFinancialInstitution">CreditorFinancialInstitution</h1>

Type: rdf:Class

Definition: A bank, building society, credit union, stock brokerage, or similar business of the party that receives money.

Unique UN Assigned ID: UN01002975

Dictionary Entry Name: Creditor_ Financial Institution. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="CreditorFinancialInstitutionFedwireRoutingNumberID">CreditorFinancialInstitutionFedwireRoutingNumberID</span> | xsd:token | The unique Fedwire Routing Number identifier as assigned by the American Bankers Association (ABA) for this creditor financial institution. | UN01002984 | Creditor_ Financial Institution. Fedwire Routing Number_ Identification. Identifier
<span id="CreditorFinancialInstitutionSICID">CreditorFinancialInstitutionSICID</span> | xsd:token | The unique Swiss Interbank Clearing (SIC) Code identifier for this creditor financial institution. | UN01002990 | Creditor_ Financial Institution. SIC_ Identification. Identifier
<span id="CreditorFinancialInstitutionJapanFinancialInstitutionCommonID">CreditorFinancialInstitutionJapanFinancialInstitutionCommonID</span> | xsd:token | The Japan Financial Institution Common identifier as assigned by the Japanese Bankers Association for this creditor financial institution. | UN01011472 | Creditor_ Financial Institution. Japan Financial Institution Common_ Identification. Identifier
<span id="CreditorFinancialInstitutionClearingSystemName">CreditorFinancialInstitutionClearingSystemName</span> | xsd:string | The clearing system name, expressed as text, for this creditor financial institution. | UN01002977 | Creditor_ Financial Institution. Clearing System Name. Text
<span id="CreditorFinancialInstitutionPortugueseNCCID">CreditorFinancialInstitutionPortugueseNCCID</span> | xsd:token | The unique Portuguese National Clearing Code (NCC) identifier for this creditor financial institution. | UN01002985 | Creditor_ Financial Institution. Portuguese NCC_ Identification. Identifier
<span id="CreditorFinancialInstitutionBICID">CreditorFinancialInstitutionBICID</span> | xsd:token | The unique Bank Identification Code (BIC) as defined in ISO 9362 for this creditor financial institution. | UN01002976 | Creditor_ Financial Institution. BIC. Identifier
<span id="CreditorFinancialInstitutionHongKongBankID">CreditorFinancialInstitutionHongKongBankID</span> | xsd:token | The unique Hong Kong Bank Code identifier for this creditor financial institution. | UN01002994 | Creditor_ Financial Institution. Hong Kong Bank_ Identification. Identifier
<span id="CreditorFinancialInstitutionSpanishDomesticInterbankingID">CreditorFinancialInstitutionSpanishDomesticInterbankingID</span> | xsd:token | The unique Spanish Domestic Interbanking Code identifier as assigned by the Centro de Cooperacion Interbancaria (CCI) for this creditor financial institution. | UN01002992 | Creditor_ Financial Institution. Spanish Domestic Interbanking_ Identification. Identifier
<span id="CreditorFinancialInstitutionName">CreditorFinancialInstitutionName</span> | xsd:string | The name, expressed as text, for this creditor financial institution. | UN01002999 | Creditor_ Financial Institution. Name. Text
<span id="CreditorFinancialInstitutionAustralianBSBID">CreditorFinancialInstitutionAustralianBSBID</span> | xsd:token | The unique Australian Bank State Branch (BSB) Code identifier as assigned by the Australian Payments Clearing Association (APCA) for this creditor financial institution. | UN01002995 | Creditor_ Financial Institution. Australian BSB_ Identification. Identifier
<span id="AdditionalClearingSystemID">AdditionalClearingSystemID</span> | xsd:token | An additional clearing system identifier for this creditor financial institution. | UN01013209 | Creditor_ Financial Institution. Additional_ Clearing System. Identifier
<span id="CreditorFinancialInstitutionCHIPSParticipantID">CreditorFinancialInstitutionCHIPSParticipantID</span> | xsd:token | The unique (United States) Clearing House Interbank Payment System (CHIPS) Participant Identifier (ID) as assigned by the New York Clearing House for this creditor financial institution. | UN01002982 | Creditor_ Financial Institution. CHIPS Participant_ Identification. Identifier
<span id="CreditorFinancialInstitutionGermanBankleitzahlID">CreditorFinancialInstitutionGermanBankleitzahlID</span> | xsd:token | The unique German Bankleitzahl identifier for this creditor financial institution. | UN01002991 | Creditor_ Financial Institution. German Bankleitzahl_ Identification. Identifier
<span id="CreditorFinancialInstitutionSwissBCID">CreditorFinancialInstitutionSwissBCID</span> | xsd:token | The unique Swiss Bank Code (BC) identifier for this creditor financial institution. | UN01002983 | Creditor_ Financial Institution. Swiss BC_ Identification. Identifier
<span id="CreditorFinancialInstitutionItalianDomesticID">CreditorFinancialInstitutionItalianDomesticID</span> | xsd:token | The unique Italian Domestic Identification Code identifier as assigned by the Associazione Bancaria Italiana (ABI) for this creditor financial institution. | UN01002987 | Creditor_ Financial Institution. Italian Domestic_ Identification. Identifier
<span id="CreditorFinancialInstitutionIndianFinancialSystemID">CreditorFinancialInstitutionIndianFinancialSystemID</span> | xsd:token | The unique Indian Financial System Code identifier for this creditor financial institution. | UN01002996 | Creditor_ Financial Institution. Indian Financial System_ Identification. Identifier
<span id="CreditorFinancialInstitutionSpecifiedProprietaryIdentity">CreditorFinancialInstitutionSpecifiedProprietaryIdentity</span> | [edi3:ProprietaryIdentity](#ProprietaryIdentity) | A proprietary identity specified for this creditor financial institution. | UN01013210 | Creditor_ Financial Institution. Specified. Proprietary_ Identity
<span id="CreditorFinancialInstitutionBranch">CreditorFinancialInstitutionBranch</span> | [edi3:BranchFinancialInstitution](#BranchFinancialInstitution) | The branch financial institution for this creditor financial institution. | UN01003001 | Creditor_ Financial Institution. Sub-Division. Branch_ Financial Institution
<span id="AustralianSNID">AustralianSNID</span> | xsd:token | The Australian Small Network (SN) identifier as assigned by the Australian Payments Clearing Association (APCA) for this creditor financial institution. | UN01013208 | Creditor_ Financial Institution. Australian SN_ Identification. Identifier
<span id="CreditorFinancialInstitutionRussianCentralBankID">CreditorFinancialInstitutionRussianCentralBankID</span> | xsd:token | The unique Russian Central Bank Identification Code identifier for this creditor financial institution. | UN01002986 | Creditor_ Financial Institution. Russian Central Bank_ Identification. Identifier
<span id="CreditorFinancialInstitutionAustrianBankleitzahlID">CreditorFinancialInstitutionAustrianBankleitzahlID</span> | xsd:token | The unique Austrian Bankleitzahl identifier for this creditor financial institution. | UN01002988 | Creditor_ Financial Institution. Austrian Bankleitzahl_ Identification. Identifier
<span id="CreditorFinancialInstitutionUKSortCodeID">CreditorFinancialInstitutionUKSortCodeID</span> | xsd:token | The unique United Kingdom (UK) Sort Code identifier as assigned by the UK Payment Association (APACS) for this creditor financial institution. | UN01002981 | Creditor_ Financial Institution. UK Sort Code_ Identification. Identifier
<span id="CreditorFinancialInstitutionCanadianPaymentsAssociationID">CreditorFinancialInstitutionCanadianPaymentsAssociationID</span> | xsd:token | The unique Canadian Payments Association Routing Number identifier for this creditor financial institution. | UN01002989 | Creditor_ Financial Institution. Canadian Payments Association_ Identification. Identifier
<span id="CreditorFinancialInstitutionPolishNationalClearingID">CreditorFinancialInstitutionPolishNationalClearingID</span> | xsd:token | The unique Polish National Clearing Code identifier for this creditor financial institution. | UN01002998 | Creditor_ Financial Institution. Polish National Clearing_ Identification. Identifier
<span id="CreditorFinancialInstitutionCHIPSUniversalID">CreditorFinancialInstitutionCHIPSUniversalID</span> | xsd:token | The unique (United States) Clearing House Interbank Payments System (CHIPS) Universal Identification (UID) as assigned by the New York Clearing House for this creditor financial institution. | UN01002978 | Creditor_ Financial Institution. CHIPS Universal_ Identification. Identifier
<span id="CreditorFinancialInstitutionNewZealandNCCID">CreditorFinancialInstitutionNewZealandNCCID</span> | xsd:token | The unique New Zealand National Clearing Code (NCC) identifier as assigned by the New Zealand Bankers' Association (NZBA) for this creditor financial institution. | UN01002979 | Creditor_ Financial Institution. New Zealand NCC_ Identification. Identifier
<span id="CreditorFinancialInstitutionHellenicBankID">CreditorFinancialInstitutionHellenicBankID</span> | xsd:token | The unique Hellenic Bank Identification Code identifier for this creditor financial institution. | UN01002997 | Creditor_ Financial Institution. Hellenic Bank_ Identification. Identifier
<span id="CreditorFinancialInstitutionAddress">CreditorFinancialInstitutionAddress</span> | [edi3:FinancialInstitutionAddress](#FinancialInstitutionAddress) | The location address for this creditor financial institution. | UN01003000 | Creditor_ Financial Institution. Location. Financial Institution_ Address
<span id="CreditorFinancialInstitutionIrishNSCID">CreditorFinancialInstitutionIrishNSCID</span> | xsd:token | The unique Irish National Sorting Code (NSC) identifier as assigned by the Irish Payments Services Organisation (IPSO) for this creditor financial institution. | UN01002980 | Creditor_ Financial Institution. Irish NSC_ Identification. Identifier


<h1 id="DebtorFinancialInstitution">DebtorFinancialInstitution</h1>

Type: rdf:Class

Definition: A bank, building society, credit union, stock brokerage, or similar business of the party that owes money.

Unique UN Assigned ID: UN01002840

Dictionary Entry Name: Debtor_ Financial Institution. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="DebtorFinancialInstitutionBICID">DebtorFinancialInstitutionBICID</span> | xsd:token | The unique Bank Identification Code (BIC) as defined in ISO 9362 for this debtor financial institution. | UN01002841 | Debtor_ Financial Institution. BIC. Identifier
<span id="DebtorFinancialInstitutionRussianCentralBankID">DebtorFinancialInstitutionRussianCentralBankID</span> | xsd:token | The unique Russian Central Bank Identification Code identifier for this debtor financial institution. | UN01002851 | Debtor_ Financial Institution. Russian Central Bank_ Identification. Identifier
<span id="DebtorFinancialInstitutionSouthAfricanNCCID">DebtorFinancialInstitutionSouthAfricanNCCID</span> | xsd:token | The unique South African National Clearing Code (NCC) identifier as assigned by the South African Bankers Services Company Ltd. (BankServ) for this debtor financial institution. | UN01002858 | Debtor_ Financial Institution. South African NCC_ Identification. Identifier
<span id="DebtorFinancialInstitutionHellenicBankID">DebtorFinancialInstitutionHellenicBankID</span> | xsd:token | The unique Hellenic Bank Identification Code identifier for this debtor financial institution. | UN01002862 | Debtor_ Financial Institution. Hellenic Bank_ Identification. Identifier
<span id="DebtorFinancialInstitutionBranch">DebtorFinancialInstitutionBranch</span> | [edi3:BranchFinancialInstitution](#BranchFinancialInstitution) | The branch financial institution for this debtor financial institution. | UN01002866 | Debtor_ Financial Institution. Sub-Division. Branch_ Financial Institution
<span id="DebtorFinancialInstitutionJapanFinancialInstitutionCommonID">DebtorFinancialInstitutionJapanFinancialInstitutionCommonID</span> | xsd:token | The Japan Financial Institution Common identifier as assigned by the Japanese Bankers Association for this debtor financial institution. | UN01011473 | Debtor_ Financial Institution. Japan Financial Institution Common_ Identification. Identifier
<span id="DebtorFinancialInstitutionIrishNSCID">DebtorFinancialInstitutionIrishNSCID</span> | xsd:token | The unique Irish National Sorting Code (NSC) identifier as assigned by the Irish Payments Services Organisation (IPSO) for this debtor financial institution. | UN01002845 | Debtor_ Financial Institution. Irish NSC_ Identification. Identifier
<span id="DebtorFinancialInstitutionGermanBankleitzahlID">DebtorFinancialInstitutionGermanBankleitzahlID</span> | xsd:token | The unique German Bankleitzahl identifier for this debtor financial institution. | UN01002856 | Debtor_ Financial Institution. German Bankleitzahl_ Identification. Identifier
<span id="DebtorFinancialInstitutionFedwireRoutingNumberID">DebtorFinancialInstitutionFedwireRoutingNumberID</span> | xsd:token | The unique Fedwire Routing Number identifier as assigned by the American Bankers Association (ABA) for this debtor financial institution. | UN01002849 | Debtor_ Financial Institution. Fedwire Routing Number_ Identification. Identifier
<span id="DebtorFinancialInstitutionClearingSystemName">DebtorFinancialInstitutionClearingSystemName</span> | xsd:string | The clearing system name, expressed as text, for this debtor financial institution. | UN01002842 | Debtor_ Financial Institution. Clearing System Name. Text
<span id="DebtorFinancialInstitutionPortugueseNCCID">DebtorFinancialInstitutionPortugueseNCCID</span> | xsd:token | The unique Portuguese National Clearing Code (NCC) identifier for this debtor financial institution. | UN01002850 | Debtor_ Financial Institution. Portuguese NCC_ Identification. Identifier
<span id="DebtorFinancialInstitutionAustralianBSBID">DebtorFinancialInstitutionAustralianBSBID</span> | xsd:token | The unique Australian Bank State Branch (BSB) Code identifier as assigned by the Australian Payments Clearing Association (APCA) for this debtor financial institution. | UN01002860 | Debtor_ Financial Institution. Australian BSB_ Identification. Identifier
<span id="DebtorFinancialInstitutionAddress">DebtorFinancialInstitutionAddress</span> | [edi3:FinancialInstitutionAddress](#FinancialInstitutionAddress) | The location address for this debtor financial institution. | UN01002865 | Debtor_ Financial Institution. Location. Financial Institution_ Address
<span id="DebtorFinancialInstitutionSpanishDomesticInterbankingID">DebtorFinancialInstitutionSpanishDomesticInterbankingID</span> | xsd:token | The unique Spanish Domestic Interbanking Code identifier as assigned by the Centro de Cooperacion Interbancaria (CCI) for this debtor financial institution. | UN01002857 | Debtor_ Financial Institution. Spanish Domestic Interbanking_ Identification. Identifier
<span id="DebtorFinancialInstitutionSwissBCID">DebtorFinancialInstitutionSwissBCID</span> | xsd:token | The unique Swiss Bank Code (BC) identifier for this debtor financial institution. | UN01002848 | Debtor_ Financial Institution. Swiss BC_ Identification. Identifier
<span id="DebtorFinancialInstitutionIndianFinancialSystemID">DebtorFinancialInstitutionIndianFinancialSystemID</span> | xsd:token | The unique Indian Financial System Code identifier for this debtor financial institution. | UN01002861 | Debtor_ Financial Institution. Indian Financial System_ Identification. Identifier
<span id="DebtorFinancialInstitutionNewZealandNCCID">DebtorFinancialInstitutionNewZealandNCCID</span> | xsd:token | The unique New Zealand National Clearing Code (NCC) identifier as assigned by the New Zealand Bankers' Association (NZBA) for this debtor financial institution. | UN01002844 | Debtor_ Financial Institution. New Zealand NCC_ Identification. Identifier
<span id="DebtorFinancialInstitutionUKSortCodeID">DebtorFinancialInstitutionUKSortCodeID</span> | xsd:token | The unique United Kingdom (UK) Sort Code identifier as assigned by the UK Payment Association (APACS) for this debtor financial institution. | UN01002846 | Debtor_ Financial Institution. UK Sort Code_ Identification. Identifier
<span id="DebtorFinancialInstitutionCHIPSParticipantID">DebtorFinancialInstitutionCHIPSParticipantID</span> | xsd:token | The unique (United States) Clearing House Interbank Payment System (CHIPS) Participant Identifier (ID) as assigned by the New York Clearing House for this debtor financial institution. | UN01002847 | Debtor_ Financial Institution. CHIPS Participant_ Identification. Identifier
<span id="DebtorFinancialInstitutionCHIPSUniversalID">DebtorFinancialInstitutionCHIPSUniversalID</span> | xsd:token | The unique (United States) Clearing House Interbank Payments System (CHIPS) Universal Identification (UID) as assigned by the New York Clearing House for this debtor financial institution. | UN01002843 | Debtor_ Financial Institution. CHIPS Universal_ Identification. Identifier
<span id="DebtorFinancialInstitutionPolishNationalClearingID">DebtorFinancialInstitutionPolishNationalClearingID</span> | xsd:token | The unique Polish National Clearing Code identifier for this debtor financial institution. | UN01002863 | Debtor_ Financial Institution. Polish National Clearing_ Identification. Identifier
<span id="DebtorFinancialInstitutionCanadianPaymentsAssociationID">DebtorFinancialInstitutionCanadianPaymentsAssociationID</span> | xsd:token | The unique Canadian Payments Association Routing Number identifier for this debtor financial institution. | UN01002854 | Debtor_ Financial Institution. Canadian Payments Association_ Identification. Identifier
<span id="DebtorFinancialInstitutionName">DebtorFinancialInstitutionName</span> | xsd:string | The name, expressed as text, for this debtor financial institution. | UN01002864 | Debtor_ Financial Institution. Name. Text
<span id="DebtorFinancialInstitutionAustrianBankleitzahlID">DebtorFinancialInstitutionAustrianBankleitzahlID</span> | xsd:token | The unique Austrian Bankleitzahl identifier for this debtor financial institution. | UN01002853 | Debtor_ Financial Institution. Austrian Bankleitzahl_ Identification. Identifier
<span id="DebtorFinancialInstitutionHongKongBankID">DebtorFinancialInstitutionHongKongBankID</span> | xsd:token | The unique Hong Kong Bank Code identifier for this debtor financial institution. | UN01002859 | Debtor_ Financial Institution. Hong Kong Bank_ Identification. Identifier
<span id="DebtorFinancialInstitutionItalianDomesticID">DebtorFinancialInstitutionItalianDomesticID</span> | xsd:token | The unique Italian Domestic Identification Code identifier as assigned by the Associazione Bancaria Italiana (ABI) for this debtor financial institution. | UN01002852 | Debtor_ Financial Institution. Italian Domestic_ Identification. Identifier


<h1 id="BranchFinancialInstitution">BranchFinancialInstitution</h1>

Type: rdf:Class

Definition: A sub-division of a bank, building society, credit union, stock brokerage, or similar business; established primarily to provide financial services and financial transactions.

Unique UN Assigned ID: UN01003138

Dictionary Entry Name: Branch_ Financial Institution. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="SortCode">SortCode</span> | xsd:token | The unique identifier for this branch of a financial institution. | UN01003139 | Branch_ Financial Institution. Identification. Identifier
<span id="BranchFinancialInstitutionName">BranchFinancialInstitutionName</span> | xsd:string | The name, expressed as text, for this branch of a financial institution. | UN01003140 | Branch_ Financial Institution. Name. Text


<h1 id="ComplexDescription">ComplexDescription</h1>

Type: rdf:Class

Definition: An aggregation of descriptive information consisting of different but related characteristics that together constitute a work item complex description.

Unique UN Assigned ID: UN01000067

Dictionary Entry Name: Work Item_ Complex Description. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="RespondingSpecificationAnswer">RespondingSpecificationAnswer</span> | [edi3:Response](#Response) | A responding specification response for this work item complex description. | UN01000071 | Work Item_ Complex Description. Responding. Specification_ Response
<span id="ComplexDescriptionContentText">ComplexDescriptionContentText</span> | xsd:string | Content, expressed as text, for this work item complex description. | UN01000069 | Work Item_ Complex Description. Content. Text
<span id="RequestingSpecificationQuery">RequestingSpecificationQuery</span> | [edi3:Query](#Query) | A requesting specification query for this work item complex description. | UN01000070 | Work Item_ Complex Description. Requesting. Specification_ Query
<span id="Abstract">Abstract</span> | xsd:string | A textual abstract of the content of the work item complex description. | UN01000068 | Work Item_ Complex Description. Abstract. Text
<span id="ComplexDescriptionContractualLanguageCode">ComplexDescriptionContractualLanguageCode</span> | xsd:token | The code specifying the contractual language for this work item complex description. | UN01007542 | Work Item_ Complex Description. Contractual Language. Code


<h1 id="GeopoliticalRegion">GeopoliticalRegion</h1>

Type: rdf:Class

Definition: A collection of countries and/or economies united for trade purposes.

Unique UN Assigned ID: UN01004587

Dictionary Entry Name: Trade_ Geopolitical Region. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="GeopoliticalRegionName">GeopoliticalRegionName</span> | xsd:string | The name, expressed as text, of this trade geopolitical region. | UN01004590 | Trade_ Geopolitical Region. Name. Text
<span id="IncludedCountry">IncludedCountry</span> | [edi3:Country](#Country) | A country included in this trade geopolitical region. | UN01004591 | Trade_ Geopolitical Region. Included. Trade_ Country
<span id="GeopoliticalRegionTypeCode">GeopoliticalRegionTypeCode</span> | xsd:token | The code specifying the type of trade geopolitical region. | UN01004589 | Trade_ Geopolitical Region. Type. Code


<h1 id="GeographicalMultiSurface">GeographicalMultiSurface</h1>

Type: rdf:Class

Definition: A collection of surfaces on the Earth (reference ISO 19136).

Unique UN Assigned ID: UN01012196

Dictionary Entry Name: Specified_ Geographical Multi-Surface. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="GeographicalMultiSurfacePolygon">GeographicalMultiSurfacePolygon</span> | [edi3:Polygon](#Polygon) | A polygon included in this geographical multi-surface. | UN01012198 | Specified_ Geographical Multi-Surface. Included. Specified_ Polygon


<h1 id="EmailCommunication">EmailCommunication</h1>

Type: rdf:Class

Definition: An address for the delivery of electronic mail.

Unique UN Assigned ID: UN01002838

Dictionary Entry Name: Email_ Communication. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-


<h1 id="TelecommunicationCommunication">TelecommunicationCommunication</h1>

Type: rdf:Class

Definition: Information necessary to establish an electronic telecommunication connection for the purpose of a telephone or facsimile exchange.

Unique UN Assigned ID: UN01002043

Dictionary Entry Name: Telecommunication_ Communication. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="SpecialDeviceTypeText">SpecialDeviceTypeText</span> | xsd:string | The special device type, expressed as text, for this telecommunication communication, such as a device for the hearing impaired. | UN01002293 | Telecommunication_ Communication. Special Device Type. Text
<span id="CountryNumberCode">CountryNumberCode</span> | xsd:token | The country access code for this telecommunication number. | UN01002046 | Telecommunication_ Communication. Country Number. Code
<span id="UseCode">UseCode</span> | xsd:token | The code specifying the use of this telecommunication such as for business purposes or private. | UN01002050 | Telecommunication_ Communication. Use. Code
<span id="UsagePreference">UsagePreference</span> | [edi3:SpecifiedPreference](#SpecifiedPreference) | The specified preference for the usage of this telecommunication method. | UN01002051 | Telecommunication_ Communication. Usage. Specified_ Preference
<span id="LocalNumber">LocalNumber</span> | xsd:string | The communication number, expressed as text and not including country access code or the area number code, for this telecommunication. | UN01002044 | Telecommunication_ Communication. Local Number. Text
<span id="ExtensionNumber">ExtensionNumber</span> | xsd:string | The extension number, expressed as text, assigned to this telecommunication number. | UN01002047 | Telecommunication_ Communication. Extension Number. Text
<span id="InternalAccessText">InternalAccessText</span> | xsd:string | Access information, expressed as text, for the internal access telecommunication number, such as the United States Defense Network Service number. | UN01002049 | Telecommunication_ Communication. Internal_ Access. Text
<span id="AreaNumberCode">AreaNumberCode</span> | xsd:token | The code specifying the area number for this telecommunication. | UN01002048 | Telecommunication_ Communication. Area Number. Code


<h1 id="UniversalCommunication">UniversalCommunication</h1>

Type: rdf:Class

Definition: The exchange of thoughts, messages, or information, as universally exchanged by speech, signals, writing, or behaviour between persons and/or organizations.

Unique UN Assigned ID: UN01001252

Dictionary Entry Name: Universal_ Communication. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="UniversalCommunicationCompleteNumber">UniversalCommunicationCompleteNumber</span> | xsd:string | The text string of characters that make up the complete number for this universal communication. | UN01001256 | Universal_ Communication. Complete Number. Text
<span id="ChannelCode">ChannelCode</span> | xsd:token | The code specifying the channel or manner in which a universal communication can be made, such as telephone or email. | UN01001254 | Universal_ Communication. Channel. Code


<h1 id="Context">Context</h1>

Type: rdf:Class

Definition: The scenario or setting of an exchanged document, such as its business process application context.

Unique UN Assigned ID: UN01003540

Dictionary Entry Name: Exchanged Document_ Context. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="BIM">BIM</span> | [edi3:DocumentContextParameter](#DocumentContextParameter) | A Business Information Master (BIM) context parameter specified for this exchanged document context. | UN01003543 | Exchanged Document_ Context. BIM_ Specified. Document Context_ Parameter
<span id="MessageStandard">MessageStandard</span> | [edi3:DocumentContextParameter](#DocumentContextParameter) | The message standard document context parameter specified for this exchanged document context. | UN01008332 | Exchanged Document_ Context. Message Standard_ Specified. Document Context_ Parameter
<span id="Scenario">Scenario</span> | [edi3:DocumentContextParameter](#DocumentContextParameter) | A scenario context parameter specified for this exchanged document context. | UN01003544 | Exchanged Document_ Context. Scenario_ Specified. Document Context_ Parameter
<span id="BusinessProcess">BusinessProcess</span> | [edi3:DocumentContextParameter](#DocumentContextParameter) | A business process context parameter specified for this exchanged document context. | UN01003542 | Exchanged Document_ Context. Business Process_ Specified. Document Context_ Parameter
<span id="Subset">Subset</span> | [edi3:DocumentContextParameter](#DocumentContextParameter) | A subset context parameter specified for this exchanged document context. | UN01003547 | Exchanged Document_ Context. Subset_ Specified. Document Context_ Parameter
<span id="TransactionID">TransactionID</span> | xsd:token | The identifier of a specified transaction in this exchanged document context. | UN01003541 | Exchanged Document_ Context. Specified_ Transaction. Identifier
<span id="Guideline">Guideline</span> | [edi3:DocumentContextParameter](#DocumentContextParameter) | A guideline context parameter specified for this exchanged document context. | UN01003546 | Exchanged Document_ Context. Guideline_ Specified. Document Context_ Parameter
<span id="UserSpecifiedParameter">UserSpecifiedParameter</span> | [edi3:DocumentContextParameter](#DocumentContextParameter) | A user specified document context parameter specified for this exchanged document context. | UN01012759 | Exchanged Document_ Context. User_ Specified. Document Context_ Parameter
<span id="TransactionProcessingDateTime">TransactionProcessingDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value of the processing of a transaction for this exchanged document context. | UN01012761 | Exchanged Document_ Context. Processing_ Transaction. Date Time
<span id="Application">Application</span> | [edi3:DocumentContextParameter](#DocumentContextParameter) | An application context parameter specified for this exchanged document context. | UN01003545 | Exchanged Document_ Context. Application_ Specified. Document Context_ Parameter


<h1 id="CustomsValuation">CustomsValuation</h1>

Type: rdf:Class

Definition: A cross-border trade related assessment of the worth of an object, such as its monetary value, for customs purposes.

Unique UN Assigned ID: UN01003483

Dictionary Entry Name: Cross-Border_ Customs Valuation. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="BuyerSellerRelationshipIndicator">BuyerSellerRelationshipIndicator</span> | xsd:boolean | The indication of whether or not there is a relationship between the buyer and the seller, such as a financial relationship, for this cross-border customs valuation. | UN01003492 | Cross-Border_ Customs Valuation. Buyer Seller Relationship. Indicator
<span id="ChargeApportionMethodCode">ChargeApportionMethodCode</span> | xsd:token | The code specifying the method of the apportion of charges for this cross-border customs valuation. | UN01003490 | Cross-Border_ Customs Valuation. Charge Apportion Method. Code
<span id="SalePriceConditionIndicator">SalePriceConditionIndicator</span> | xsd:boolean | The indication of whether or not there is a condition imposed on the sale price of the goods for this cross-border customs valuation. | UN01003495 | Cross-Border_ Customs Valuation. Sale Price Condition. Indicator
<span id="AddedAdjustmentAmount">AddedAdjustmentAmount</span> | xsd:decimal | The monetary value of the adjustment added for this cross-border customs valuation. | UN01003484 | Cross-Border_ Customs Valuation. Added_ Adjustment. Amount
<span id="CustomsValuationApplicableCurrencyExchange">CustomsValuationApplicableCurrencyExchange</span> | [edi3:CurrencyExchange](#CurrencyExchange) | The trade related currency exchange applicable to this cross-border customs valuation. | UN01003497 | Cross-Border_ Customs Valuation. Applicable. Trade_ Currency Exchange
<span id="CustomsValuationMethodCode">CustomsValuationMethodCode</span> | xsd:token | The code specifying the method by which this cross-border customs valuation is determined. | UN01003488 | Cross-Border_ Customs Valuation. Method. Code
<span id="OtherChargeAmount">OtherChargeAmount</span> | xsd:decimal | A monetary value added or subtracted from the total invoice price not previously taken into account for this cross-border customs valuation. | UN01003491 | Cross-Border_ Customs Valuation. Other Charge. Amount
<span id="AddedAdjustmentPercent">AddedAdjustmentPercent</span> | xsd:decimal | The adjustment added, expressed as a percentage, for this cross-border customs valuation. | UN01003486 | Cross-Border_ Customs Valuation. Added_ Adjustment. Percent
<span id="RoyaltyLicenceFeeIndicator">RoyaltyLicenceFeeIndicator</span> | xsd:boolean | The indication of whether or not there is a royalty or licence fee related to the goods for this cross-border customs valuation. | UN01003496 | Cross-Border_ Customs Valuation. Royalty License Fee. Indicator
<span id="WTOAdditionCode">WTOAdditionCode</span> | xsd:token | The code specifying any additions necessary under the World Trade Organization (WTO) Valuation Agreement used for the assessment of this cross-border customs valuation. | UN01003489 | Cross-Border_ Customs Valuation. WTO Addition. Code
<span id="CustomsValuationTypeCode">CustomsValuationTypeCode</span> | xsd:token | The code specifying the type of cross-border customs valuation. | UN01008956 | Cross-Border_ Customs Valuation. Type. Code
<span id="SaleRestrictionText">SaleRestrictionText</span> | xsd:string | A restriction, expressed as text, imposed on the sale of the goods for this cross-border customs valuation. | UN01012694 | Cross-Border_ Customs Valuation. Sale Restriction. Text
<span id="SaleRestrictionIndicator">SaleRestrictionIndicator</span> | xsd:boolean | The indication of whether or not there is any restriction imposed on the sale of the goods for this cross-border customs valuation. | UN01003494 | Cross-Border_ Customs Valuation. Sale Restriction. Indicator
<span id="BuyerSellerRelationshipPriceInfluenceIndicator">BuyerSellerRelationshipPriceInfluenceIndicator</span> | xsd:boolean | The indication of whether or not the buyer seller relationship influences the price of the goods for this cross-border customs valuation. | UN01003493 | Cross-Border_ Customs Valuation. Buyer Seller Relationship Price Influence. Indicator
<span id="DeductedAdjustmentPercent">DeductedAdjustmentPercent</span> | xsd:decimal | The adjustment deducted, expressed as a percentage, for this cross-border customs valuation. | UN01003487 | Cross-Border_ Customs Valuation. Deducted_ Adjustment. Percent


<h1 id="DeliveryTerms">DeliveryTerms</h1>

Type: rdf:Class

Definition: Conditions agreed upon between the parties with regard to the delivery of goods and or services for trade purposes.

Unique UN Assigned ID: UN01001654

Dictionary Entry Name: Trade_ Delivery Terms. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="FunctionCode">FunctionCode</span> | xsd:token | A code specifying a function of these trade delivery terms. | UN01009006 | Trade_ Delivery Terms. Function. Code
<span id="RelevantLocation">RelevantLocation</span> | [edi3:TradeLocation](#TradeLocation) | The trade location relevant for these trade delivery terms. | UN01001657 | Trade_ Delivery Terms. Relevant. Trade_ Location
<span id="DeliveryTermsDescription">DeliveryTermsDescription</span> | xsd:string | A textual description of these trade delivery terms. | UN01001656 | Trade_ Delivery Terms. Description. Text
<span id="DeliveryTermsPartialDeliveryAllowedIndicator">DeliveryTermsPartialDeliveryAllowedIndicator</span> | xsd:boolean | The indication of whether or not these trade delivery terms allow a partial delivery. | UN01012763 | Trade_ Delivery Terms. Partial Delivery Allowed. Indicator
<span id="DeliveryDiscontinuationCode">DeliveryDiscontinuationCode</span> | xsd:token | The code specifying the delivery discontinuation for this trade delivery terms. | UN01012762 | Trade_ Delivery Terms. Delivery Discontinuation. Code


<h1 id="Keyword">Keyword</h1>

Type: rdf:Class

Definition: A significant word, part of word or phrase that is used to enable indexing of or searching within a textual repository, such as a product catalogue or library.

Unique UN Assigned ID: UN01007299

Dictionary Entry Name: Keyword. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-


<h1 id="WorkItemDimension">WorkItemDimension</h1>

Type: rdf:Class

Definition: A measure of spatial extent associated with this work item, such as length, breadth, or height.

Unique UN Assigned ID: UN01000056

Dictionary Entry Name: Work Item_ Dimension. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="WorkItemDimensionTypeCode">WorkItemDimensionTypeCode</span> | xsd:token | The code specifying the type of this work item dimension. | UN01000060 | Work Item_ Dimension. Type. Code
<span id="ComponentDimension">ComponentDimension</span> | [edi3:WorkItemDimension](#WorkItemDimension) | A work item component dimension for this work item dimension. | UN01000061 | Work Item_ Dimension. Component. Work Item_ Dimension
<span id="Measure">Measure</span> | xsd:decimal | The measured value for this work item dimension. | UN01000058 | Work Item_ Dimension. Value. Measure
<span id="WorkItemDimensionContractualLanguageCode">WorkItemDimensionContractualLanguageCode</span> | xsd:token | The code specifying the contractual language for this work item dimension. | UN01007543 | Work Item_ Dimension. Contractual Language. Code
<span id="WorkItemDimensionDescription">WorkItemDimensionDescription</span> | xsd:string | The textual description of this work item dimension. | UN01000059 | Work Item_ Dimension. Description. Text


<h1 id="SpatialDimension">SpatialDimension</h1>

Type: rdf:Class

Definition: A measure of spatial extent of an object, such as the length, breadth or height of a shipping container.

Unique UN Assigned ID: UN01004075

Dictionary Entry Name: Spatial_ Dimension. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="SpatialDimensionValueMeasure">SpatialDimensionValueMeasure</span> | xsd:decimal | The measure of the value of this spatial dimension. | UN01004076 | Spatial_ Dimension. Value. Measure
<span id="Width">Width</span> | xsd:decimal | The measure of the width component of this spatial dimension. | UN01004079 | Spatial_ Dimension. Width. Measure
<span id="SpatialDimensionID">SpatialDimensionID</span> | xsd:token | The unique identifier of this spatial dimension. | UN01004082 | Spatial_ Dimension. Identification. Identifier
<span id="SpatialDimensionTypeCode">SpatialDimensionTypeCode</span> | xsd:token | The code specifying the type of spatial dimension, such as thickness, area, or volume. | UN01004077 | Spatial_ Dimension. Type. Code
<span id="SpatialDimensionDescription">SpatialDimensionDescription</span> | xsd:string | A textual description of this spatial dimension. | UN01004078 | Spatial_ Dimension. Description. Text
<span id="Diameter">Diameter</span> | xsd:decimal | The measure of the diameter component for this spatial dimension. | UN01007192 | Spatial_ Dimension. Diameter. Measure
<span id="Height">Height</span> | xsd:decimal | The measure of the height component of this spatial dimension. | UN01004081 | Spatial_ Dimension. Height. Measure


<h1 id="CurrencyExchange">CurrencyExchange</h1>

Type: rdf:Class

Definition: The conversion of one currency to another for trade purposes.

Unique UN Assigned ID: UN01004576

Dictionary Entry Name: Trade_ Currency Exchange. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="MarketID">MarketID</span> | xsd:token | The unique identifier of the currency exchange market from which the exchange rate is taken for trade purposes. | UN01004581 | Trade_ Currency Exchange. Market. Identifier
<span id="SourceCurrencyCode">SourceCurrencyCode</span> | xsd:token | The code specifying the source currency of a trade related currency conversion. | UN01004577 | Trade_ Currency Exchange. Source Currency. Code
<span id="TargetCurrencyCode">TargetCurrencyCode</span> | xsd:token | The code specifying the target currency of a trade related currency conversion. | UN01004579 | Trade_ Currency Exchange. Target Currency. Code
<span id="SourceUnitBasis">SourceUnitBasis</span> | xsd:decimal | The numeric unit basis of the source currency used in this trade related currency exchange rate calculation. | UN01004578 | Trade_ Currency Exchange. Source Unit Basis. Numeric
<span id="ConversionRate">ConversionRate</span> | xsd:decimal | The rate factor used for conversion from the source currency to the target currency for trade purposes. | UN01004582 | Trade_ Currency Exchange. Conversion. Rate
<span id="CurrencyExchangeAssociatedDocument">CurrencyExchangeAssociatedDocument</span> | [edi3:Document](#Document) | An associated document referenced for this trade related currency exchange. | UN01011919 | Trade_ Currency Exchange. Associated. Referenced_ Document
<span id="TargetUnitBasis">TargetUnitBasis</span> | xsd:decimal | The numeric unit basis of the target currency used in this trade related currency exchange rate calculation. | UN01004580 | Trade_ Currency Exchange. Target Unit Base. Numeric


<h1 id="BinaryFile">BinaryFile</h1>

Type: rdf:Class

Definition: A specified computer file or program stored in a binary format.

Unique UN Assigned ID: UN01006014

Dictionary Entry Name: Specified_ Binary File. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="AuthorName">AuthorName</span> | xsd:string | A name of an author, expressed as text, of this specified binary file. | UN01006017 | Specified_ Binary File. Author Name. Text
<span id="Size">Size</span> | xsd:decimal | The measure of the size of this specified binary file. | UN01006027 | Specified_ Binary File. Size. Measure
<span id="BinaryFileID">BinaryFileID</span> | xsd:token | A unique identifier for this specified binary file. | UN01006015 | Specified_ Binary File. Identification. Identifier
<span id="BinaryFileURI">BinaryFileURI</span> | xsd:token | The unique Uniform Resource Identifier (URI) for this specified binary file. | UN01006020 | Specified_ Binary File. URI. Identifier
<span id="EncodingCode">EncodingCode</span> | xsd:token | The code specifying the encoding of this specified binary file. | UN01006022 | Specified_ Binary File. Encoding. Code
<span id="BinaryFileDescription">BinaryFileDescription</span> | xsd:string | A textual description of this specified binary file. | UN01006026 | Specified_ Binary File. Description. Text
<span id="Title">Title</span> | xsd:string | A title, expressed as text, for this specified binary file. | UN01006016 | Specified_ Binary File. Title. Text
<span id="AccessText">AccessText</span> | xsd:string | Access information, expressed as text, for this specified binary file, such as security and download parameters. | UN01006025 | Specified_ Binary File. Access. Text
<span id="BinaryFileVersionID">BinaryFileVersionID</span> | xsd:token | The unique version identifier for this specified binary file. | UN01006018 | Specified_ Binary File. Version. Identifier
<span id="BinaryFileName">BinaryFileName</span> | xsd:string | The file name, expressed as text, of this specified binary file. | UN01006019 | Specified_ Binary File. File Name. Text
<span id="CharacterSetCode">CharacterSetCode</span> | xsd:token | The code specifying the character set for this specified binary file. | UN01006023 | Specified_ Binary File. Character Set. Code
<span id="AccessAvailabilityPeriod">AccessAvailabilityPeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The specified period when access to this binary file is available. | UN01006028 | Specified_ Binary File. Access Availability. Specified_ Period
<span id="MIMECode">MIMECode</span> | xsd:token | The code specifying the Multipurpose Internet Mail Extensions (MIME) type for this specified binary file. | UN01006021 | Specified_ Binary File. MIME. Code


<h1 id="Section">Section</h1>

Type: rdf:Class

Definition: The parts into which a label is or may be divided.

Unique UN Assigned ID: UN01012731

Dictionary Entry Name: Label_ Section. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="SectionID">SectionID</span> | xsd:token | The identifier of this label section. | UN01012732 | Label_ Section. Identification. Identifier
<span id="IncludedSegment">IncludedSegment</span> | [edi3:Segment](#Segment) | A segment included in this label section. | UN01012734 | Label_ Section. Included. Section_ Segment


<h1 id="GeographicalPoint">GeographicalPoint</h1>

Type: rdf:Class

Definition: A point on the surface of the Earth (reference ISO 19136).

Unique UN Assigned ID: UN01012180

Dictionary Entry Name: Specified_ Geographical Point. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="GeographicalPointGeographicalObjectCharacteristic">GeographicalPointGeographicalObjectCharacteristic</span> | [edi3:GeographicalObjectCharacteristic](#GeographicalObjectCharacteristic) | The geographical object characteristic associated with this geographical point. | UN01012182 | Specified_ Geographical Point. Associated. Specified_ Geographical Object Characteristic
<span id="GeographicalPointAssociatedLogisticsLocation">GeographicalPointAssociatedLogisticsLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | A logistics location associated with this specified geographical point. | UN01013626 | Specified_ Geographical Point. Associated. Logistics_ Location


<h1 id="Marketplace">Marketplace</h1>

Type: rdf:Class

Definition: An actual or virtual place where buyers and sellers interact, directly or through intermediaries, to trade goods or services.

Unique UN Assigned ID: UN01009952

Dictionary Entry Name: Specified_ Marketplace. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="Website">Website</span> | xsd:token | A website Uniform Resource Identifier (URI) for this specified marketplace. | UN01009956 | Specified_ Marketplace. Website_ URI. Identifier
<span id="SalesMethodCode">SalesMethodCode</span> | xsd:token | The code specifying a sales method, such as an auction clock or mediation, for this specified marketplace. | UN01009957 | Specified_ Marketplace. Sales Method. Code
<span id="AvailableOrderingPeriod">AvailableOrderingPeriod</span> | [edi3:AvailablePeriod](#AvailablePeriod) | An available ordering period for this specified marketplace. | UN01009958 | Specified_ Marketplace. Ordering. Available_ Period
<span id="VirtualIndicator">VirtualIndicator</span> | xsd:boolean | The indication of whether or not this specified marketplace is virtual, such as a web-based marketplace. | UN01009955 | Specified_ Marketplace. Virtual. Indicator
<span id="MarketplaceID">MarketplaceID</span> | xsd:token | The identifier for this specified marketplace. | UN01009953 | Specified_ Marketplace. Identification. Identifier


<h1 id="Authentication">Authentication</h1>

Type: rdf:Class

Definition: A proof that a document is genuine.

Unique UN Assigned ID: UN01002639

Dictionary Entry Name: Document_ Authentication. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="RepresentationTypeCode">RepresentationTypeCode</span> | xsd:token | The code specifying the type of representation of this document authentication, such as direct or indirect. | UN01003525 | Document_ Authentication. Representation Type. Code
<span id="IncludedClause">IncludedClause</span> | [edi3:Clause](#Clause) | A document clause included in this document authentication. | UN01002645 | Document_ Authentication. Included. Document_ Clause
<span id="ReferencedProvider">ReferencedProvider</span> | [edi3:ReferencedParty](#ReferencedParty) | The referenced party providing this document authentication. | UN01002642 | Document_ Authentication. Provider. Referenced_ Party
<span id="SignatoryImageBinaryObject">SignatoryImageBinaryObject</span> | xsd:base64Binary | The signatory image, expressed as a binary object, for this document authentication. | UN01012687 | Document_ Authentication. Signatory_ Image. Binary Object
<span id="LocationProvider">LocationProvider</span> | [edi3:TradeParty](#TradeParty) | The trade party providing the location for this document authentication. | UN01004886 | Document_ Authentication. Location Provider. Trade_ Party
<span id="AuthenticationInformation">AuthenticationInformation</span> | xsd:string | Information, expressed as text, for this document authentication. | UN01003522 | Document_ Authentication. Information. Text
<span id="AuthenticationCategoryCode">AuthenticationCategoryCode</span> | xsd:token | A code specifying a category for this document authentication. | UN01012809 | Document_ Authentication. Category. Code
<span id="GovernmentActionTypeCode">GovernmentActionTypeCode</span> | xsd:token | The code specifying the type of document authentication. | UN01002640 | Document_ Authentication. Type. Code
<span id="AuthenticationStatement">AuthenticationStatement</span> | xsd:string | The statement, expressed as text, for this document authentication. | UN01003523 | Document_ Authentication. Statement. Text
<span id="StatementCode">StatementCode</span> | xsd:token | The code specifying the statement for this document authentication. | UN01003524 | Document_ Authentication. Statement. Code
<span id="AuthenticationActualDateTime">AuthenticationActualDateTime</span> | xsd:dateTime | The actual date, time, date time, or other date time value of this document authentication. | UN01002641 | Document_ Authentication. Actual. Date Time
<span id="AuthenticationID">AuthenticationID</span> | xsd:token | A unique identifier for this document authentication. | UN01003520 | Document_ Authentication. Identification. Identifier
<span id="SignatoryText">SignatoryText</span> | xsd:string | The signatory, expressed as text, for this document authentication. | UN01006191 | Document_ Authentication. Signatory. Text
<span id="AuthenticationIssueLocation">AuthenticationIssueLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | The issue location for this document authentication. | UN01006141 | Document_ Authentication. Issue. Logistics_ Location


<h1 id="SupplyChainEvent">SupplyChainEvent</h1>

Type: rdf:Class

Definition: A significant occurrence or happening in a supply chain.

Unique UN Assigned ID: UN01004291

Dictionary Entry Name: Supply Chain_ Event. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="SupplyChainEventDescription">SupplyChainEventDescription</span> | xsd:string | A textual description of this supply chain event. | UN01004295 | Supply Chain_ Event. Description. Text
<span id="OccurrenceTime">OccurrenceTime</span> | xsd:dateTime | A time value of an occurrence of this supply chain event. | UN01012565 | Supply Chain_ Event. Time_ Occurrence. Date Time
<span id="SupplyChainEventDueDateTime">SupplyChainEventDueDateTime</span> | xsd:dateTime | The due date, time, date time, or other date time value of this supply chain event. | UN01013373 | Supply Chain_ Event. Due. Date Time
<span id="EarliestOccurrenceDateTime">EarliestOccurrenceDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value of the earliest occurrence of this supply chain event. | UN01009020 | Supply Chain_ Event. Earliest_ Occurrence. Date Time
<span id="SupplyChainEventFrequencyCode">SupplyChainEventFrequencyCode</span> | xsd:token | The code specifying a frequency for this supply chain event. | UN01005303 | Supply Chain_ Event. Frequency. Code
<span id="SupplyChainEventOccurrencePeriod">SupplyChainEventOccurrencePeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | A specified period of time during which this supply chain event occurs. | UN01004298 | Supply Chain_ Event. Occurrence. Specified_ Period
<span id="SupplyChainEventUnitQuantity">SupplyChainEventUnitQuantity</span> | xsd:decimal | A number of units for this supply chain event. | UN01004297 | Supply Chain_ Event. Unit. Quantity
<span id="LatestOccurrenceDateTime">LatestOccurrenceDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value of the latest occurrence of this supply chain event. | UN01009019 | Supply Chain_ Event. Latest_ Occurrence. Date Time
<span id="SupplyChainEventOccurrenceDateTime">SupplyChainEventOccurrenceDateTime</span> | xsd:dateTime | A date, time, date time, or other date time value of an occurrence of this supply chain event. | UN01004293 | Supply Chain_ Event. Occurrence. Date Time
<span id="SupplyChainEventLocation">SupplyChainEventLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | A logistics location where this supply chain event occurs. | UN01004299 | Supply Chain_ Event. Occurrence. Logistics_ Location
<span id="SupplyChainEventID">SupplyChainEventID</span> | xsd:token | The unique identifier for this supply chain event. | UN01004292 | Supply Chain_ Event. Identification. Identifier
<span id="DescriptionBinaryObject">DescriptionBinaryObject</span> | xsd:base64Binary | Binary object data, such as a photograph, describing this supply chain event. | UN01004296 | Supply Chain_ Event. Description. Binary Object


<h1 id="CommunicationEvent">CommunicationEvent</h1>

Type: rdf:Class

Definition: A significant occurrence or happening communicated by means of sending or receiving information, such as transmitting digital data by using the internet.

Unique UN Assigned ID: UN01013560

Dictionary Entry Name: Communication_ Event. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="CommunicationEventReasonCode">CommunicationEventReasonCode</span> | xsd:token | The code specifying a reason for this communication event. | UN01013566 | Communication_ Event. Reason. Code
<span id="OccurrenceLogisticsLocation">OccurrenceLogisticsLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | The logistics location where this communication event will occur or has occurred. | UN01013569 | Communication_ Event. Occurrence. Logistics_ Location
<span id="CommunicationEventOccurrenceDateTime">CommunicationEventOccurrenceDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value of an occurrence of this communication event. | UN01013562 | Communication_ Event. Occurrence. Date Time
<span id="CommunicationEventUnitQuantity">CommunicationEventUnitQuantity</span> | xsd:decimal | The number of units for this communication event. | UN01013565 | Communication_ Event. Unit. Quantity
<span id="CommunicationEventDescription">CommunicationEventDescription</span> | xsd:string | A textual description of this communication event. | UN01013564 | Communication_ Event. Description. Text
<span id="CommunicationEventAssociatedGeographicalFeature">CommunicationEventAssociatedGeographicalFeature</span> | [edi3:GeographicalFeature](#GeographicalFeature) | A geographical feature associated with this communication event. | UN01013570 | Communication_ Event. Associated. Specified_ Geographical Feature
<span id="OperationalResponsibleParty">OperationalResponsibleParty</span> | [edi3:TradeParty](#TradeParty) | The operational responsible party for this communication event. | UN01013568 | Communication_ Event. Operational_ Responsible. Trade_ Party
<span id="CommunicationEventTypeCode">CommunicationEventTypeCode</span> | xsd:token | The code specifying the type of communication event. | UN01013563 | Communication_ Event. Type. Code
<span id="CommunicationEventValueMeasure">CommunicationEventValueMeasure</span> | xsd:decimal | The measure of a value for this communication event. | UN01013567 | Communication_ Event. Value. Measure


<h1 id="ReferencedEvent">ReferencedEvent</h1>

Type: rdf:Class

Definition: A referenced significant occurrence or happening during transport.

Unique UN Assigned ID: UN01010081

Dictionary Entry Name: Referenced_ Transport_ Event. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="ReferencedEventScheduledArrivalDateTime">ReferencedEventScheduledArrivalDateTime</span> | xsd:dateTime | The date, time, date time or other date time value of the scheduled arrival related to this referenced transport event. | UN01010082 | Referenced_ Transport_ Event. Scheduled Arrival_ Related. Date Time
<span id="ReferencedEventScheduledDepartureDateTime">ReferencedEventScheduledDepartureDateTime</span> | xsd:dateTime | The date, time, date time or other date time value of the scheduled departure related to this referenced transport event. | UN01010083 | Referenced_ Transport_ Event. Scheduled Departure_ Related. Date Time
<span id="ReasonTypeCode">ReasonTypeCode</span> | xsd:token | The code specifying the reason type for this referenced transport event. | UN01010084 | Referenced_ Transport_ Event. Reason_ Type. Code


<h1 id="Event">Event</h1>

Type: rdf:Class

Definition: A significant occurrence or happening during transport.

Unique UN Assigned ID: UN01004791

Dictionary Entry Name: Transport_ Event. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="RequestedService">RequestedService</span> | [edi3:ReferencedService](#ReferencedService) | A requested service related to this transport event. | UN01010152 | Transport_ Event. Requested_ Related. Referenced Transport_ Service
<span id="ScheduledOccurrencePeriod">ScheduledOccurrencePeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The scheduled period of time specified for the occurrence of this transport event. | UN01013590 | Transport_ Event. Scheduled_ Occurrence. Specified_ Period
<span id="ConveyanceFacilityLocation">ConveyanceFacilityLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | A location of a conveyance facility related to this transport event. | UN01004809 | Transport_ Event. Conveyance Facility_ Related. Logistics_ Location
<span id="ExpectedIndicator">ExpectedIndicator</span> | xsd:boolean | The indication of whether or not this transport event is or was expected. | UN01013585 | Transport_ Event. Expected. Indicator
<span id="EventAssociatedGeographicalFeature">EventAssociatedGeographicalFeature</span> | [edi3:GeographicalFeature](#GeographicalFeature) | A geographical feature associated with this transport event. | UN01013587 | Transport_ Event. Associated. Specified_ Geographical Feature
<span id="EventPreviousAssociatedGeographicalFeature">EventPreviousAssociatedGeographicalFeature</span> | [edi3:GeographicalFeature](#GeographicalFeature) | A geographical feature previously associated with this transport event. | UN01013588 | Transport_ Event. Previous_ Associated. Specified_ Geographical Feature
<span id="DelayPeriod">DelayPeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | A specified period of time during which this transport event is delayed. | UN01004806 | Transport_ Event. Delay_ Occurrence. Specified_ Period
<span id="EventScheduledArrivalDateTime">EventScheduledArrivalDateTime</span> | xsd:dateTime | The date, time, date time or other date time value of the scheduled arrival related to this transport event. | UN01010147 | Transport_ Event. Scheduled Arrival_ Related. Date Time
<span id="RequestedOccurrenceDateTime">RequestedOccurrenceDateTime</span> | xsd:dateTime | The requested date, time, date time, or other date time value of the occurrence of this transport event. | UN01004798 | Transport_ Event. Requested_ Occurrence. Date Time
<span id="CertifyingParty">CertifyingParty</span> | [edi3:TradeParty](#TradeParty) | A certifying party for this transport event. | UN01004810 | Transport_ Event. Certifying. Trade_ Party
<span id="TransportMeansStayPeriod">TransportMeansStayPeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The specified period during which the transport means is held at a location. | UN01004805 | Transport_ Event. Transport Means Stay_ Occurrence. Specified_ Period
<span id="EventID">EventID</span> | xsd:token | The unique identifier for this transport event. | UN01004792 | Transport_ Event. Identification. Identifier
<span id="EventApplicableNote">EventApplicableNote</span> | [edi3:Note](#Note) | A note providing information applicable to this transport event. | UN01012582 | Transport_ Event. Applicable. Note
<span id="ActualDepartureDateTime">ActualDepartureDateTime</span> | xsd:dateTime | The date, time, date time or other date time value of the actual departure related to this transport event. | UN01010150 | Transport_ Event. Actual Departure_ Related. Date Time
<span id="EventTypeCode">EventTypeCode</span> | xsd:token | The code specifying the type of transport event. | UN01004793 | Transport_ Event. Type. Code
<span id="AdditionalSecurityMeasures">AdditionalSecurityMeasures</span> | [edi3:Note](#Note) | A note providing additional security measures applicable to this transport event. | UN01013133 | Transport_ Event. Additional Security Measures_ Applicable. Note
<span id="ArrivalDateTime">ArrivalDateTime</span> | xsd:dateTime | An arrival date, time, date time, or other date time value related to this transport event. | UN01004799 | Transport_ Event. Arrival_ Related. Date Time
<span id="EventUnitQuantity">EventUnitQuantity</span> | xsd:decimal | The number of units for this transport event. | UN01006146 | Transport_ Event. Unit. Quantity
<span id="EstimatedTransportMeansArrivalOccurrenceDateTime">EstimatedTransportMeansArrivalOccurrenceDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value when the arrival of a means of transport at the location of this transport event is estimated to occur. | UN01004801 | Transport_ Event. Estimated Transport Means Arrival_ Occurrence. Date Time
<span id="ActualOccurrenceDateTime">ActualOccurrenceDateTime</span> | xsd:dateTime | The actual date, time, date time, or other date time value of the occurrence of this transport event. | UN01004796 | Transport_ Event. Actual_ Occurrence. Date Time
<span id="LaycanPeriod">LaycanPeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The specified period of laycan time during which this transport event occurs. | UN01004807 | Transport_ Event. Laycan_ Occurrence. Specified_ Period
<span id="ScheduledOccurrenceDateTime">ScheduledOccurrenceDateTime</span> | xsd:dateTime | The scheduled date, time, date time, or other date time value of the occurrence of this transport event. | UN01004797 | Transport_ Event. Scheduled_ Occurrence. Date Time
<span id="ActualOccurrencePeriod">ActualOccurrencePeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The actual period of time during which this transport event occurred. | UN01013589 | Transport_ Event. Actual_ Occurrence. Specified_ Period
<span id="ActualArrivalDateTime">ActualArrivalDateTime</span> | xsd:dateTime | The date, time, date time or other date time value of the actual arrival related to this transport event. | UN01010148 | Transport_ Event. Actual Arrival_ Related. Date Time
<span id="EventScheduledDepartureDateTime">EventScheduledDepartureDateTime</span> | xsd:dateTime | The date, time, date time or other date time value of the scheduled departure related to this transport event. | UN01010149 | Transport_ Event. Scheduled Departure_ Related. Date Time
<span id="ReportedConditionTypeCode">ReportedConditionTypeCode</span> | xsd:token | The code specifying the type of reported condition for this transport event. | UN01013582 | Transport_ Event. Reported Condition_ Type. Code
<span id="EventSecurityLevelCode">EventSecurityLevelCode</span> | xsd:token | A security level code for this transport event. | UN01013132 | Transport_ Event. Security Level. Code
<span id="EventSpecifiedInstructions">EventSpecifiedInstructions</span> | [edi3:TransportInstructions](#TransportInstructions) | An instruction or a set of instructions specified for this transport event. | UN01004802 | Transport_ Event. Specified. Transport_ Instructions
<span id="StayEvent">StayEvent</span> | [edi3:ReferencedEvent](#ReferencedEvent) | A stay specified for this referenced transport event. | UN01010154 | Transport_ Event. Stay_ Specified. Referenced_ Transport_ Event
<span id="RelatedObservation">RelatedObservation</span> | [edi3:Observation](#Observation) | An observation related to this transport event. | UN01012581 | Transport_ Event. Related. Specified_ Observation
<span id="OccurrenceLocation">OccurrenceLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | The logistics location where this transport event occurs. | UN01004803 | Transport_ Event. Occurrence. Logistics_ Location
<span id="ReportingMonitoringIOTDevice">ReportingMonitoringIOTDevice</span> | [edi3:IOTDevice](#IOTDevice) | An IOT device for this transport reporting event. | UN01013586 | Transport_ Event. Reporting. Monitoring_ IOT Device
<span id="ReceivedDateTime">ReceivedDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value when information related to this transport event was received, from the perspective of the receiver. | UN01013584 | Transport_ Event. Received. Date Time
<span id="CargoFacilityLocation">CargoFacilityLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | The location of a cargo facility related to this transport event. | UN01004808 | Transport_ Event. Cargo Facility_ Related. Logistics_ Location
<span id="EstimatedOccurrenceDateTime">EstimatedOccurrenceDateTime</span> | xsd:dateTime | The estimated date, time, date time, or other date time value of the occurrence of this transport event. | UN01004795 | Transport_ Event. Estimated_ Occurrence. Date Time
<span id="DelayEvent">DelayEvent</span> | [edi3:ReferencedEvent](#ReferencedEvent) | A delay specified for this referenced transport event. | UN01010153 | Transport_ Event. Delay_ Specified. Referenced_ Transport_ Event
<span id="EventValueMeasure">EventValueMeasure</span> | xsd:decimal | The measure of a value for this transport event. | UN01013583 | Transport_ Event. Value. Measure
<span id="RelatedRoute">RelatedRoute</span> | [edi3:Route](#Route) | The route related to this transport event. | UN01010151 | Transport_ Event. Related. Transport_ Route
<span id="DepartureDateTime">DepartureDateTime</span> | xsd:dateTime | A departure date, time, date time, or other date time value related to this transport event. | UN01004800 | Transport_ Event. Departure_ Related. Date Time
<span id="EventOccurrencePeriod">EventOccurrencePeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | A specified period of time during which this transport event occurs. | UN01004804 | Transport_ Event. Occurrence. Specified_ Period


<h1 id="DocumentContextParameter">DocumentContextParameter</h1>

Type: rdf:Class

Definition: A feature that is fixed for a particular document context.

Unique UN Assigned ID: UN01004852

Dictionary Entry Name: Document Context_ Parameter. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="DocumentContextParameterValueText">DocumentContextParameterValueText</span> | xsd:string | The value, expressed as text, of this document context parameter. | UN01004854 | Document Context_ Parameter. Value. Text
<span id="Version">Version</span> | [edi3:Version](#Version) | The document version specified for this document context parameter. | UN01004855 | Document Context_ Parameter. Specified. Document_ Version


<h1 id="ControlSettingParameter">ControlSettingParameter</h1>

Type: rdf:Class

Definition: A set of measurable factors that specifies the conditions of its operation within a specific context.

Unique UN Assigned ID: UN01013502

Dictionary Entry Name: Control Setting_ Parameter. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="SpecifiedRequestedRange">SpecifiedRequestedRange</span> | [edi3:Range](#Range) | A requested range specified for this control setting parameter. | UN01013512 | Control Setting_ Parameter. Requested. Specified_ Range
<span id="ControlSettingParameterTypeCode">ControlSettingParameterTypeCode</span> | xsd:token | The code specifying a type of parameter for this control setting parameter. | UN01013504 | Control Setting_ Parameter. Type. Code
<span id="ControlSettingParameterID">ControlSettingParameterID</span> | xsd:token | The identifier of this control setting parameter. | UN01013503 | Control Setting_ Parameter. Identification. Identifier
<span id="ControlSettingParameterStatusCode">ControlSettingParameterStatusCode</span> | xsd:token | The code specifying the status of this control setting parameter. | UN01013505 | Control Setting_ Parameter. Status. Code
<span id="ControlSettingParameterName">ControlSettingParameterName</span> | xsd:string | The name, expressed as text, of this control setting parameter. | UN01013507 | Control Setting_ Parameter. Name. Text
<span id="ControlSettingParameterValueAllowedIndicator">ControlSettingParameterValueAllowedIndicator</span> | xsd:boolean | The indication of whether or not this control setting parameter value is allowed. | UN01013508 | Control Setting_ Parameter. Value Allowed. Indicator
<span id="ControlSettingParameterChangeableIndicator">ControlSettingParameterChangeableIndicator</span> | xsd:boolean | The indication whether or not this control setting parameter is changeable. | UN01013511 | Control Setting_ Parameter. Changeable. Indicator
<span id="ControlSettingParameterValueText">ControlSettingParameterValueText</span> | xsd:string | The value, expressed as text, of this control setting parameter. | UN01013509 | Control Setting_ Parameter. Value. Text
<span id="ControlSettingParameterDescription">ControlSettingParameterDescription</span> | xsd:string | A textual description of this control setting parameter. | UN01013506 | Control Setting_ Parameter. Description. Text


<h1 id="OperationalParameter">OperationalParameter</h1>

Type: rdf:Class

Definition: A set of measurable factors that specifies the conditions within which an entity operates correctly.

Unique UN Assigned ID: UN01013513

Dictionary Entry Name: Operational_ Parameter. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="OperationalParameterValueMeasure">OperationalParameterValueMeasure</span> | xsd:decimal | The measure value for this operational parameter. | UN01013521 | Operational_ Parameter. Value. Measure
<span id="DefinedRange">DefinedRange</span> | [edi3:Range](#Range) | A defined range specified for this operational parameter. | UN01013523 | Operational_ Parameter. Defined. Specified_ Range
<span id="OperationalParameterDescription">OperationalParameterDescription</span> | xsd:string | A textual description of this operational parameter. | UN01013517 | Operational_ Parameter. Description. Text
<span id="OperationalParameterStatusCode">OperationalParameterStatusCode</span> | xsd:token | The code specifying the status of this operational parameter. | UN01013516 | Operational_ Parameter. Status. Code
<span id="OperationalParameterTypeCode">OperationalParameterTypeCode</span> | xsd:token | The code specifying the type of this operational parameter. | UN01013515 | Operational_ Parameter. Type. Code
<span id="OperationalParameterValueText">OperationalParameterValueText</span> | xsd:string | The value, expressed as text, of this operational parameter. | UN01013520 | Operational_ Parameter. Value. Text
<span id="OperationalParameterName">OperationalParameterName</span> | xsd:string | The name, expressed as text, of this operational parameter. | UN01013518 | Operational_ Parameter. Name. Text
<span id="OperationalParameterChangeableIndicator">OperationalParameterChangeableIndicator</span> | xsd:boolean | The indication whether or not this operational parameter is changeable. | UN01013522 | Operational_ Parameter. Changeable. Indicator
<span id="OperationalParameterID">OperationalParameterID</span> | xsd:token | The identifier of this operational parameter. | UN01013514 | Operational_ Parameter. Identification. Identifier


<h1 id="PaymentPenaltyTerms">PaymentPenaltyTerms</h1>

Type: rdf:Class

Definition: Trade terms and conditions by which a penalty is or can be applied to a payable amount.

Unique UN Assigned ID: UN01004626

Dictionary Entry Name: Trade_ Payment Penalty Terms. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="PaymentPenaltyTermsBasisDateTime">PaymentPenaltyTermsBasisDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value used as the basis to calculate these trade payment penalty terms. | UN01004627 | Trade_ Payment Penalty Terms. Basis. Date Time
<span id="ActualPenaltyAmount">ActualPenaltyAmount</span> | xsd:decimal | A monetary value of the actual penalty in these trade payment penalty terms. | UN01004872 | Trade_ Payment Penalty Terms. Actual Penalty. Amount
<span id="PaymentPenaltyTermsBasisPeriodMeasure">PaymentPenaltyTermsBasisPeriodMeasure</span> | xsd:decimal | The measure of the period used as a basis to calculate these trade payment penalty terms. | UN01004628 | Trade_ Payment Penalty Terms. Basis Period. Measure
<span id="PaymentPenaltyTermsCalculationPercent">PaymentPenaltyTermsCalculationPercent</span> | xsd:decimal | The percent applied to calculate these trade payment penalty terms. | UN01004630 | Trade_ Payment Penalty Terms. Calculation. Percent


<h1 id="GeographicalMultiCurve">GeographicalMultiCurve</h1>

Type: rdf:Class

Definition: A collection of curves on the surface of the Earth (reference ISO 19136).

Unique UN Assigned ID: UN01012190

Dictionary Entry Name: Specified_ Geographical Multi-Curve. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="GeographicalMultiCurveGeographicalObjectCharacteristic">GeographicalMultiCurveGeographicalObjectCharacteristic</span> | [edi3:GeographicalObjectCharacteristic](#GeographicalObjectCharacteristic) | The geographical object characteristic associated with this geographical multi-curve. | UN01012192 | Specified_ Geographical Multi-Curve. Associated. Specified_ Geographical Object Characteristic
<span id="GeographicalMultiCurveGeographicalLine">GeographicalMultiCurveGeographicalLine</span> | [edi3:GeographicalLine](#GeographicalLine) | A geographical line member of this geographical multi-curve. | UN01012193 | Specified_ Geographical Multi-Curve. Member. Specified_ Geographical Line


<h1 id="LinearRing">LinearRing</h1>

Type: rdf:Class

Definition: A specified array of points which define a closed loop which is not self intersecting.

Unique UN Assigned ID: UN01010472

Dictionary Entry Name: Specified_ Linear Ring. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="SpecifiedSpecifiedGeographicalCoordinate">SpecifiedSpecifiedGeographicalCoordinate</span> | [edi3:FLUXGeographicalCoordinate](#FLUXGeographicalCoordinate) | Geographical coordinate information specified for this linear ring. | UN01011207 | Specified_ Linear Ring. Specified. FLUX_ Geographical Coordinate
<span id="LinearRingCoordinateText">LinearRingCoordinateText</span> | xsd:string | A coordinate, expressed as text, for this specified linear ring. | UN01010473 | Specified_ Linear Ring. Coordinate. Text
<span id="CoordinateDirectPosition">CoordinateDirectPosition</span> | [edi3:DirectPosition](#DirectPosition) | The specified direct position of a coordinate for this linear ring. | UN01010474 | Specified_ Linear Ring. Coordinate. Specified_ Direct Position


<h1 id="LineTradeAgreement">LineTradeAgreement</h1>

Type: rdf:Class

Definition: The contractual terms of a line trade agreement.

Unique UN Assigned ID: UN01011693

Dictionary Entry Name: Line_ Trade Agreement. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="LineTradeAgreementPriceListDocument">LineTradeAgreementPriceListDocument</span> | [edi3:Document](#Document) | The price list document referenced in this line trade agreement. | UN01011721 | Line_ Trade Agreement. Price List. Referenced_ Document
<span id="LineTradeAgreementQuotationRequestDocument">LineTradeAgreementQuotationRequestDocument</span> | [edi3:Document](#Document) | The quotation request document referenced in this line trade agreement. | UN01011716 | Line_ Trade Agreement. Quotation Request. Referenced_ Document
<span id="LineTradeAgreementSeller">LineTradeAgreementSeller</span> | [edi3:TradeParty](#TradeParty) | The seller party for this line trade agreement. | UN01011708 | Line_ Trade Agreement. Seller. Trade_ Party
<span id="LineTradeAgreementRelevantParty">LineTradeAgreementRelevantParty</span> | [edi3:TradeParty](#TradeParty) | A party relevant for this line trade agreement. | UN01013416 | Line_ Trade Agreement. Relevant. Trade_ Party
<span id="LineTradeAgreementBuyerOrderDocument">LineTradeAgreementBuyerOrderDocument</span> | [edi3:Document](#Document) | A buyer generated order document referenced in this line trade agreement. | UN01011713 | Line_ Trade Agreement. Buyer_ Order. Referenced_ Document
<span id="GuaranteedProductLifeSpanPeriod">GuaranteedProductLifeSpanPeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The guaranteed product life span specified in this line trade agreement. | UN01011738 | Line_ Trade Agreement. Guaranteed Product Life Span. Specified_ Period
<span id="ExclusivityPeriod">ExclusivityPeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The exclusivity period specified in this line trade agreement. | UN01011736 | Line_ Trade Agreement. Exclusivity. Specified_ Period
<span id="LineTradeAgreementBuyerRequisitioner">LineTradeAgreementBuyerRequisitioner</span> | [edi3:TradeParty](#TradeParty) | A party who is a buyer requisitioner in this line trade agreement. | UN01011709 | Line_ Trade Agreement. Buyer_ Requisitioner. Trade_ Party
<span id="LineTradeAgreementReferenceText">LineTradeAgreementReferenceText</span> | xsd:string | A reference, expressed as text, for this line trade agreement. | UN01011694 | Line_ Trade Agreement. Reference. Text
<span id="LineTradeAgreementID">LineTradeAgreementID</span> | xsd:token | An identifier for this line trade agreement. | UN01013412 | Line_ Trade Agreement. Identification. Identifier
<span id="ProductNetPrice">ProductNetPrice</span> | [edi3:TradePrice](#TradePrice) | A net product price in this line trade agreement. | UN01011724 | Line_ Trade Agreement. Net Price_ Product. Trade_ Price
<span id="LineTradeAgreementLetterOfCreditDocument">LineTradeAgreementLetterOfCreditDocument</span> | [edi3:Document](#Document) | The letter of credit document referenced in this line trade agreement. | UN01011744 | Line_ Trade Agreement. Letter Of Credit. Referenced_ Document
<span id="LineTradeAgreementQuotationProposalResponseDocument">LineTradeAgreementQuotationProposalResponseDocument</span> | [edi3:Document](#Document) | The quotation proposal response document referenced in this line trade agreement. | UN01011748 | Line_ Trade Agreement. Quotation Proposal Response. Referenced_ Document
<span id="LineTradeAgreementSalesConditionsDocument">LineTradeAgreementSalesConditionsDocument</span> | [edi3:Document](#Document) | A sales conditions document referenced by this line trade agreement. | UN01011726 | Line_ Trade Agreement. Sales_ Conditions. Referenced_ Document
<span id="MinimumProductOrderableQuantity">MinimumProductOrderableQuantity</span> | xsd:decimal | The minimum product orderable quantity for this line trade agreement. | UN01011702 | Line_ Trade Agreement. Minimum_ Product Orderable. Quantity
<span id="ProductEndUser">ProductEndUser</span> | [edi3:TradeParty](#TradeParty) | The party acting as the end user for the products in this line trade agreement. | UN01011710 | Line_ Trade Agreement. Product End User. Trade_ Party
<span id="RequestForQuotationResponseDocument">RequestForQuotationResponseDocument</span> | [edi3:Document](#Document) | The quotation request response document referenced in this line trade agreement. | UN01011749 | Line_ Trade Agreement. Quotation Request Response. Referenced_ Document
<span id="LineTradeAgreementUltimateCustomerOrderDocument">LineTradeAgreementUltimateCustomerOrderDocument</span> | [edi3:Document](#Document) | An ultimate customer order document referenced for this line trade agreement. | UN01012137 | Line_ Trade Agreement. Ultimate Customer_ Order. Referenced_ Document
<span id="LineTradeAgreementBuyer">LineTradeAgreementBuyer</span> | [edi3:TradeParty](#TradeParty) | The buyer party for this line trade agreement. | UN01012561 | Line_ Trade Agreement. Buyer. Trade_ Party
<span id="LineTradeAgreementCarrier">LineTradeAgreementCarrier</span> | [edi3:TradeParty](#TradeParty) | A carrier party for this line trade agreement. | UN01011731 | Line_ Trade Agreement. Carrier. Trade_ Party
<span id="LineTradeAgreementDeliveryPriorityCode">LineTradeAgreementDeliveryPriorityCode</span> | xsd:token | The code specifying the delivery priority for this line trade agreement. | UN01012560 | Line_ Trade Agreement. Delivery_ Priority. Code
<span id="LineTradeAgreementEngineeringChangeDocument">LineTradeAgreementEngineeringChangeDocument</span> | [edi3:Document](#Document) | The engineering change document referenced in this line trade agreement. | UN01011743 | Line_ Trade Agreement. Engineering Change. Referenced_ Document
<span id="ProgramMissionProject">ProgramMissionProject</span> | [edi3:MissionProject](#MissionProject) | A mission project program for this line trade agreement. | UN01013464 | Line_ Trade Agreement. Program. Mission_ Project
<span id="LineTradeAgreementPromotionalDealDocument">LineTradeAgreementPromotionalDealDocument</span> | [edi3:Document](#Document) | The promotional deal document referenced in this line trade agreement. | UN01011720 | Line_ Trade Agreement. Promotional Deal. Referenced_ Document
<span id="ResaleProductUnitOfMeasureCode">ResaleProductUnitOfMeasureCode</span> | xsd:token | The code specifying the resale product unit of measure, such as kilogram or litre, for this trade line agreement. | UN01011706 | Line_ Trade Agreement. Resale_ Product Unit Measure. Code
<span id="LineTradeAgreementImpactCode">LineTradeAgreementImpactCode</span> | xsd:token | The code specifying the impact for this line trade agreement. | UN01012988 | Line_ Trade Agreement. Impact. Code
<span id="ItemSeller">ItemSeller</span> | [edi3:TradeParty](#TradeParty) | The item seller party for this line trade agreement. | UN01011750 | Line_ Trade Agreement. Item_ Seller. Trade_ Party
<span id="OrderPrice">OrderPrice</span> | [edi3:TradePrice](#TradePrice) | An order price for a product in this line trade agreement. | UN01011753 | Line_ Trade Agreement. Order Price_ Product. Trade_ Price
<span id="LineTradeAgreementBuyerReferenceText">LineTradeAgreementBuyerReferenceText</span> | xsd:string | A buyer reference, expressed as text, for this line trade agreement. | UN01011695 | Line_ Trade Agreement. Buyer_ Reference. Text
<span id="LineTradeAgreementOriginalOrderDocument">LineTradeAgreementOriginalOrderDocument</span> | [edi3:Document](#Document) | The original order document referenced in this line trade agreement. | UN01011742 | Line_ Trade Agreement. Original_ Order. Referenced_ Document
<span id="IncrementalProductOrderableQuantity">IncrementalProductOrderableQuantity</span> | xsd:decimal | The incremental product orderable quantity for this line trade agreement. | UN01011704 | Line_ Trade Agreement. Incremental_ Product Orderable. Quantity
<span id="ProductGrossPrice">ProductGrossPrice</span> | [edi3:TradePrice](#TradePrice) | A gross product price in this line trade agreement. | UN01011723 | Line_ Trade Agreement. Gross Price_ Product. Trade_ Price
<span id="InformationUseRestrictionIndicator">InformationUseRestrictionIndicator</span> | xsd:boolean | The indication of whether or not the use of the information provided in this line trade agreement is restricted. | UN01011707 | Line_ Trade Agreement. Information Use Restriction. Indicator
<span id="OrderProductUnitOfMeasureCode">OrderProductUnitOfMeasureCode</span> | xsd:token | The code specifying the order product unit of measure, such as kilogram or litre, for this line trade agreement. | UN01011705 | Line_ Trade Agreement. Order_ Product Unit Measure. Code
<span id="LineTradeAgreementPrimeContractSeller">LineTradeAgreementPrimeContractSeller</span> | [edi3:TradeParty](#TradeParty) | The seller party acting as the prime contractor for this line trade agreement. | UN01013415 | Line_ Trade Agreement. Prime Contract_ Seller. Trade_ Party
<span id="Marketplace">Marketplace</span> | [edi3:Marketplace](#Marketplace) | A marketplace included in this line trade agreement. | UN01011752 | Line_ Trade Agreement. Included. Specified_ Marketplace
<span id="LineTradeAgreementMarketplaceOrderDocument">LineTradeAgreementMarketplaceOrderDocument</span> | [edi3:Document](#Document) | The marketplace generated order document referenced in this line trade agreement. | UN01011714 | Line_ Trade Agreement. Marketplace_ Order. Referenced_ Document
<span id="LineTradeAgreementSellerOrderDocument">LineTradeAgreementSellerOrderDocument</span> | [edi3:Document](#Document) | The seller generated order document referenced in this line trade agreement. | UN01011712 | Line_ Trade Agreement. Seller_ Order. Referenced_ Document
<span id="LineTradeAgreementProcurementParty">LineTradeAgreementProcurementParty</span> | [edi3:TradeParty](#TradeParty) | The procurement party for this line trade agreement. | UN01011729 | Line_ Trade Agreement. Procurement. Trade_ Party
<span id="LineTradeAgreementQuotationDocument">LineTradeAgreementQuotationDocument</span> | [edi3:Document](#Document) | The quotation document referenced in this line trade agreement. | UN01011715 | Line_ Trade Agreement. Quotation. Referenced_ Document
<span id="PickUpOrderFulfilmentLeadTime">PickUpOrderFulfilmentLeadTime</span> | xsd:decimal | The measure of the expected time interval between the receipt of an order and its pick-up fulfilment according to this line trade agreement. | UN01011701 | Line_ Trade Agreement. Pick-Up_ Order Fulfilment Lead Time. Measure
<span id="LineTradeAgreementRequisitionerDocument">LineTradeAgreementRequisitionerDocument</span> | [edi3:Document](#Document) | A requisitioner document referenced in this line trade agreement. | UN01011725 | Line_ Trade Agreement. Requisitioner. Referenced_ Document
<span id="SupplyInstruction">SupplyInstruction</span> | [edi3:Document](#Document) | A supply instruction document referenced in this line trade agreement. | UN01012563 | Line_ Trade Agreement. Supply Instruction. Referenced_ Document
<span id="LineTradeAgreementBuyerApprovedDateTime">LineTradeAgreementBuyerApprovedDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value of approval by the buyer for this line trade agreement. | UN01013414 | Line_ Trade Agreement. Buyer_ Approved. Date Time
<span id="LineTradeAgreementQuotationProposalDocument">LineTradeAgreementQuotationProposalDocument</span> | [edi3:Document](#Document) | The quotation proposal document referenced in this line trade agreement. | UN01011747 | Line_ Trade Agreement. Quotation Proposal. Referenced_ Document
<span id="LineTradeAgreementContractDocument">LineTradeAgreementContractDocument</span> | [edi3:Document](#Document) | A contract document referenced in this line trade agreement. | UN01011717 | Line_ Trade Agreement. Contract. Referenced_ Document
<span id="ImmediatePreviousPriceListDocument">ImmediatePreviousPriceListDocument</span> | [edi3:Document](#Document) | The immediate previous price list document referenced in this line trade agreement. | UN01011754 | Line_ Trade Agreement. Immediate Previous_ Price List. Referenced_ Document
<span id="LineTradeAgreementRevisionID">LineTradeAgreementRevisionID</span> | xsd:token | An identifier for the revision of this line trade agreement. | UN01013413 | Line_ Trade Agreement. Revision_ Identification. Identifier
<span id="ForecastTerms">ForecastTerms</span> | [edi3:ForecastTerms](#ForecastTerms) | The supply chain forecast terms applicable to this line trade agreement. | UN01012562 | Line_ Trade Agreement. Applicable. Supply Chain_ Forecast Terms
<span id="LineTradeAgreementPriorityCode">LineTradeAgreementPriorityCode</span> | xsd:token | The code specifying the priority for this line trade agreement. | UN01012989 | Line_ Trade Agreement. Priority. Code
<span id="LineTradeAgreementSellerReferenceText">LineTradeAgreementSellerReferenceText</span> | xsd:string | A seller reference, expressed as text, for this line trade agreement. | UN01012990 | Line_ Trade Agreement. Seller_ Reference. Text
<span id="MinimumOrderQuantityOrderingPeriod">MinimumOrderQuantityOrderingPeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The minimum order quantity ordering period specified in this line trade agreement. | UN01011734 | Line_ Trade Agreement. Minimum Order Quantity_ Ordering. Specified_ Period
<span id="LineTradeAgreementRequisitionDocument">LineTradeAgreementRequisitionDocument</span> | [edi3:Document](#Document) | A requisition document referenced in this line trade agreement. | UN01011718 | Line_ Trade Agreement. Requisition. Referenced_ Document
<span id="MaximumProductOrderableQuantity">MaximumProductOrderableQuantity</span> | xsd:decimal | The maximum product orderable quantity for this line trade agreement. | UN01011703 | Line_ Trade Agreement. Maximum_ Product Orderable. Quantity
<span id="MaximumOrderQuantityOrderingPeriod">MaximumOrderQuantityOrderingPeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The maximum order quantity ordering period specified in this line trade agreement. | UN01011735 | Line_ Trade Agreement. Maximum Order Quantity_ Ordering. Specified_ Period
<span id="LineTradeAgreementDemandForecastDocument">LineTradeAgreementDemandForecastDocument</span> | [edi3:Document](#Document) | A demand forecast document referenced in this line trade agreement. | UN01011719 | Line_ Trade Agreement. Demand Forecast. Referenced_ Document
<span id="SupportCentre">SupportCentre</span> | [edi3:TradeParty](#TradeParty) | The support centre party for this line trade agreement. | UN01011730 | Line_ Trade Agreement. Support Centre. Trade_ Party
<span id="DeliveryOrderFulfilmentLeadTime">DeliveryOrderFulfilmentLeadTime</span> | xsd:decimal | The measure of the expected time interval between the receipt of an order and its delivery fulfilment according to this line trade agreement. | UN01011700 | Line_ Trade Agreement. Delivery_ Order Fulfilment Lead Time. Measure
<span id="ProductReorderableIndicator">ProductReorderableIndicator</span> | xsd:boolean | The indication of whether or not the product can be reordered according to this line trade agreement. | UN01011698 | Line_ Trade Agreement. Product Reorderable. Indicator
<span id="LineTradeAgreementTargetMarketCountry">LineTradeAgreementTargetMarketCountry</span> | [edi3:Country](#Country) | A target market country for this line trade agreement. | UN01011732 | Line_ Trade Agreement. Target Market. Trade_ Country
<span id="LineTradeAgreementExportLicenceDocument">LineTradeAgreementExportLicenceDocument</span> | [edi3:Document](#Document) | The export licence document referenced in this line trade agreement. | UN01011746 | Line_ Trade Agreement. Export Licence. Referenced_ Document
<span id="LineTradeAgreementPreviousOrderDocument">LineTradeAgreementPreviousOrderDocument</span> | [edi3:Document](#Document) | The previous order document referenced in this line trade agreement. | UN01011741 | Line_ Trade Agreement. Previous_ Order. Referenced_ Document
<span id="ItemBuyer">ItemBuyer</span> | [edi3:TradeParty](#TradeParty) | The item buyer party for this line trade agreement. | UN01011751 | Line_ Trade Agreement. Item_ Buyer. Trade_ Party
<span id="LineTradeAgreementSalesReportDocument">LineTradeAgreementSalesReportDocument</span> | [edi3:Document](#Document) | The sales report document referenced in this line trade agreement. | UN01011739 | Line_ Trade Agreement. Sales Report. Referenced_ Document
<span id="LineTradeAgreementBlanketOrderDocument">LineTradeAgreementBlanketOrderDocument</span> | [edi3:Document](#Document) | The blanket order document referenced in this line trade agreement. | UN01011740 | Line_ Trade Agreement. Blanket Order. Referenced_ Document
<span id="LineTradeAgreementTradeDeliveryTerms">LineTradeAgreementTradeDeliveryTerms</span> | [edi3:DeliveryTerms](#DeliveryTerms) | The terms of delivery applicable to this line trade agreement. | UN01011711 | Line_ Trade Agreement. Applicable. Trade_ Delivery Terms
<span id="LineTradeAgreementCatalogueDocument">LineTradeAgreementCatalogueDocument</span> | [edi3:Document](#Document) | A catalogue document referenced by this line trade agreement. | UN01011727 | Line_ Trade Agreement. Catalogue. Referenced_ Document
<span id="ProductAvailabilityCode">ProductAvailabilityCode</span> | xsd:token | The code specifying the product availability according to this line trade agreement. | UN01011696 | Line_ Trade Agreement. Product Availability. Code
<span id="LineTradeAgreementImportLicenceDocument">LineTradeAgreementImportLicenceDocument</span> | [edi3:Document](#Document) | The import licence document referenced in this line trade agreement. | UN01011745 | Line_ Trade Agreement. Import Licence. Referenced_ Document
<span id="OrderingPeriod">OrderingPeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The ordering period specified in this line trade agreement. | UN01011733 | Line_ Trade Agreement. Ordering. Specified_ Period
<span id="ResalePeriod">ResalePeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The resale period specified in this line trade agreement. | UN01011737 | Line_ Trade Agreement. Resale. Specified_ Period
<span id="LineTradeAgreementCatalogueInformationProvider">LineTradeAgreementCatalogueInformationProvider</span> | [edi3:TradeParty](#TradeParty) | The party that provides catalogue information for this line trade agreement. | UN01011728 | Line_ Trade Agreement. Catalogue_ Information Provider. Trade_ Party
<span id="LineTradeAgreementEconomicOrderQuantity">LineTradeAgreementEconomicOrderQuantity</span> | xsd:decimal | The economic order quantity for this line trade agreement. | UN01012987 | Line_ Trade Agreement. Economic_ Order. Quantity
<span id="LineTradeAgreementAdditionalDocument">LineTradeAgreementAdditionalDocument</span> | [edi3:Document](#Document) | An additional document referenced in this line trade agreement. | UN01011722 | Line_ Trade Agreement. Additional. Referenced_ Document
<span id="ProductMadeToOrderIndicator">ProductMadeToOrderIndicator</span> | xsd:boolean | The indication of whether or not, according to this line trade agreement, the product is manufactured, built or customized only after receipt of order. | UN01011699 | Line_ Trade Agreement. Product Made To Order. Indicator


<h1 id="HeaderTradeAgreement">HeaderTradeAgreement</h1>

Type: rdf:Class

Definition: The contractual terms of a header trade agreement.

Unique UN Assigned ID: UN01011547

Dictionary Entry Name: Header_ Trade Agreement. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="HeaderTradeAgreementSellerReferenceText">HeaderTradeAgreementSellerReferenceText</span> | xsd:string | A seller reference, expressed as text, for this header trade agreement. | UN01013026 | Header_ Trade Agreement. Seller_ Reference. Text
<span id="BuyerTaxRepresentative">BuyerTaxRepresentative</span> | [edi3:TradeParty](#TradeParty) | The party acting as a tax representative for the buyer for this header trade agreement. | UN01011557 | Header_ Trade Agreement. Buyer_ Tax Representative. Trade_ Party
<span id="HeaderTradeAgreementBuyerReferenceText">HeaderTradeAgreementBuyerReferenceText</span> | xsd:string | A buyer reference, expressed as text, for this header trade agreement. | UN01011549 | Header_ Trade Agreement. Buyer_ Reference. Text
<span id="HeaderTradeAgreementRevisionID">HeaderTradeAgreementRevisionID</span> | xsd:token | An identifier for the revision of this header trade agreement. | UN01013409 | Header_ Trade Agreement. Revision_ Identification. Identifier
<span id="HeaderTradeAgreementDemandForecastDocument">HeaderTradeAgreementDemandForecastDocument</span> | [edi3:Document](#Document) | A demand forecast document referenced in this header trade agreement. | UN01011571 | Header_ Trade Agreement. Demand Forecast. Referenced_ Document
<span id="HeaderTradeAgreementID">HeaderTradeAgreementID</span> | xsd:token | An identifier for this header trade agreement. | UN01013408 | Header_ Trade Agreement. Identification. Identifier
<span id="HeaderTradeAgreementAdditionalDocument">HeaderTradeAgreementAdditionalDocument</span> | [edi3:Document](#Document) | An additional document referenced in this header trade agreement. | UN01011575 | Header_ Trade Agreement. Additional. Referenced_ Document
<span id="HeaderTradeAgreementBuyerOrderDocument">HeaderTradeAgreementBuyerOrderDocument</span> | [edi3:Document](#Document) | The buyer generated order document referenced in this header trade agreement. | UN01011564 | Header_ Trade Agreement. Buyer_ Order. Referenced_ Document
<span id="HeaderTradeAgreementPriceListDocument">HeaderTradeAgreementPriceListDocument</span> | [edi3:Document](#Document) | The price list document referenced in this header trade agreement. | UN01011574 | Header_ Trade Agreement. Price List. Referenced_ Document
<span id="HeaderTradeAgreementRelevantParty">HeaderTradeAgreementRelevantParty</span> | [edi3:TradeParty](#TradeParty) | A relevant party for this header trade agreement. | UN01011945 | Header_ Trade Agreement. Relevant. Trade_ Party
<span id="HeaderTradeAgreementCrossBorderRegulatoryProcedure">HeaderTradeAgreementCrossBorderRegulatoryProcedure</span> | [edi3:RegulatoryProcedure](#RegulatoryProcedure) | A cross-border regulatory procedure applicable to this header trade agreement. | UN01012123 | Header_ Trade Agreement. Applicable. Cross-Border_ Regulatory Procedure
<span id="HeaderTradeAgreementDeliveryPriorityCode">HeaderTradeAgreementDeliveryPriorityCode</span> | xsd:token | The code specifying the delivery priority for this header trade agreement. | UN01011550 | Header_ Trade Agreement. Delivery_ Priority. Code
<span id="HeaderTradeAgreementLogisticsLocation">HeaderTradeAgreementLogisticsLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | A logistics location or place applicable to this header trade agreement. | UN01011585 | Header_ Trade Agreement. Applicable. Logistics_ Location
<span id="PurchaseConditionsDocument">PurchaseConditionsDocument</span> | [edi3:Document](#Document) | A purchase conditions document referenced in this header trade agreement. | UN01011578 | Header_ Trade Agreement. Purchase_ Conditions. Referenced_ Document
<span id="SupplyInstructionDocument">SupplyInstructionDocument</span> | [edi3:Document](#Document) | A supply instruction document referenced in this header trade agreement. | UN01011572 | Header_ Trade Agreement. Supply Instruction. Referenced_ Document
<span id="QuoteReferencedWorkflowObject">QuoteReferencedWorkflowObject</span> | [edi3:WorkflowObject](#WorkflowObject) | The quote trade workflow object referenced in this header trade agreement. | UN01011602 | Header_ Trade Agreement. Quote_ Referenced. Trade_ Workflow Object
<span id="HeaderTradeAgreementQuotationProposalResponseDocument">HeaderTradeAgreementQuotationProposalResponseDocument</span> | [edi3:Document](#Document) | The quotation proposal response document referenced in this header trade agreement. | UN01011600 | Header_ Trade Agreement. Quotation Proposal Response. Referenced_ Document
<span id="HeaderTradeAgreementRequisitionDocument">HeaderTradeAgreementRequisitionDocument</span> | [edi3:Document](#Document) | A requisition document referenced in this header trade agreement. | UN01011570 | Header_ Trade Agreement. Requisition. Referenced_ Document
<span id="HeaderTradeAgreementOriginalOrderDocument">HeaderTradeAgreementOriginalOrderDocument</span> | [edi3:Document](#Document) | The original order document referenced in this header trade agreement. | UN01011594 | Header_ Trade Agreement. Original_ Order. Referenced_ Document
<span id="HeaderTradeAgreementCarrier">HeaderTradeAgreementCarrier</span> | [edi3:TradeParty](#TradeParty) | The carrier party, at header level, for this trade agreement. | UN01013407 | Header_ Trade Agreement. Carrier. Trade_ Party
<span id="ShippingPeriod">ShippingPeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The shipping period specified in this header trade agreement. | UN01011586 | Header_ Trade Agreement. Shipping. Specified_ Period
<span id="HeaderTradeAgreementLetterOfCreditDocument">HeaderTradeAgreementLetterOfCreditDocument</span> | [edi3:Document](#Document) | The letter of credit document referenced in this header trade agreement. | UN01011596 | Header_ Trade Agreement. Letter Of Credit. Referenced_ Document
<span id="SellerTaxRepresentative">SellerTaxRepresentative</span> | [edi3:TradeParty](#TradeParty) | The party acting as a tax representative for the seller for this header trade agreement. | UN01011558 | Header_ Trade Agreement. Seller_ Tax Representative. Trade_ Party
<span id="HeaderTradeAgreementSalesConditionsDocument">HeaderTradeAgreementSalesConditionsDocument</span> | [edi3:Document](#Document) | A sales conditions document referenced in this header trade agreement. | UN01011579 | Header_ Trade Agreement. Sales_ Conditions. Referenced_ Document
<span id="SalesAgent">SalesAgent</span> | [edi3:TradeParty](#TradeParty) | The agent party representing the seller for this header trade agreement. | UN01011553 | Header_ Trade Agreement. Sales Agent. Trade_ Party
<span id="HeaderTradeAgreementSellerOrderDocument">HeaderTradeAgreementSellerOrderDocument</span> | [edi3:Document](#Document) | The seller generated order document referenced in this header trade agreement. | UN01011563 | Header_ Trade Agreement. Seller_ Order. Referenced_ Document
<span id="OrderResponseDocument">OrderResponseDocument</span> | [edi3:Document](#Document) | The order response document referenced in this header trade agreement. | UN01011567 | Header_ Trade Agreement. Order Response. Referenced_ Document
<span id="HeaderProcuringProject">HeaderProcuringProject</span> | [edi3:Project](#Project) | The procuring project specified for this header trade agreement. | UN01011944 | Header_ Trade Agreement. Specified. Procuring_ Project
<span id="HeaderTradeAgreementPrimeContractSeller">HeaderTradeAgreementPrimeContractSeller</span> | [edi3:TradeParty](#TradeParty) | The seller party acting as the prime contractor for this header trade agreement. | UN01013411 | Header_ Trade Agreement. Prime Contract_ Seller. Trade_ Party
<span id="HeaderTradeAgreementBuyerRequisitioner">HeaderTradeAgreementBuyerRequisitioner</span> | [edi3:TradeParty](#TradeParty) | A party who is a buyer requisitioner in this header trade agreement. | UN01011554 | Header_ Trade Agreement. Buyer_ Requisitioner. Trade_ Party
<span id="HeaderTradeAgreementPaymentTerms">HeaderTradeAgreementPaymentTerms</span> | [edi3:PaymentTerms](#PaymentTerms) | The payment terms applicable to this header trade agreement. | UN01011561 | Header_ Trade Agreement. Applicable. Trade_ Payment Terms
<span id="CatalogueInformationReceiver">CatalogueInformationReceiver</span> | [edi3:TradeParty](#TradeParty) | The party that receives catalogue information for this header trade agreement. | UN01011582 | Header_ Trade Agreement. Catalogue_ Information Receiver. Trade_ Party
<span id="EndUser">EndUser</span> | [edi3:TradeParty](#TradeParty) | The party acting as the end user for the products in this header trade agreement. | UN01011559 | Header_ Trade Agreement. Product End User. Trade_ Party
<span id="HeaderTradeAgreementEngineeringChangeDocument">HeaderTradeAgreementEngineeringChangeDocument</span> | [edi3:Document](#Document) | The engineering change document referenced in this header trade agreement. | UN01011595 | Header_ Trade Agreement. Engineering Change. Referenced_ Document
<span id="HeaderTradeAgreementProcurementParty">HeaderTradeAgreementProcurementParty</span> | [edi3:TradeParty](#TradeParty) | The procurement party for this header trade agreement. | UN01011583 | Header_ Trade Agreement. Procurement. Trade_ Party
<span id="HeaderTradeAgreementBuyer">HeaderTradeAgreementBuyer</span> | [edi3:TradeParty](#TradeParty) | The buyer party for this header trade agreement. | UN01011552 | Header_ Trade Agreement. Buyer. Trade_ Party
<span id="HeaderTradeAgreementPriorityCode">HeaderTradeAgreementPriorityCode</span> | xsd:token | The code specifying the priority for this header trade agreement. | UN01013025 | Header_ Trade Agreement. Priority. Code
<span id="HeaderTradeAgreementMarketplaceOrderDocument">HeaderTradeAgreementMarketplaceOrderDocument</span> | [edi3:Document](#Document) | The marketplace generated order document referenced in this header trade agreement. | UN01011565 | Header_ Trade Agreement. Marketplace_ Order. Referenced_ Document
<span id="BuyerAgent">BuyerAgent</span> | [edi3:TradeParty](#TradeParty) | The buyer agent party for this header trade agreement. | UN01011577 | Header_ Trade Agreement. Buyer Agent. Trade_ Party
<span id="HeaderTradeAgreementTargetMarketCountry">HeaderTradeAgreementTargetMarketCountry</span> | [edi3:Country](#Country) | A target market country for this header trade agreement. | UN01011584 | Header_ Trade Agreement. Target Market. Trade_ Country
<span id="CatalogueSubscriptionDocument">CatalogueSubscriptionDocument</span> | [edi3:Document](#Document) | A catalogue subscription document referenced in this header trade agreement. | UN01011588 | Header_ Trade Agreement. Catalogue Subscription. Referenced_ Document
<span id="HeaderTradeAgreementReferenceText">HeaderTradeAgreementReferenceText</span> | xsd:string | A reference, expressed as text, for this header trade agreement. | UN01011548 | Header_ Trade Agreement. Reference. Text
<span id="ApplicableForecastTerms">ApplicableForecastTerms</span> | [edi3:ForecastTerms](#ForecastTerms) | The supply chain forecast terms applicable to this header trade agreement. | UN01011562 | Header_ Trade Agreement. Applicable. Supply Chain_ Forecast Terms
<span id="HeaderTradeAgreementQuotationProposalDocument">HeaderTradeAgreementQuotationProposalDocument</span> | [edi3:Document](#Document) | The quotation proposal document referenced in this header trade agreement. | UN01011599 | Header_ Trade Agreement. Quotation Proposal. Referenced_ Document
<span id="QuotationRequestResponseDocument">QuotationRequestResponseDocument</span> | [edi3:Document](#Document) | The quotation request response document referenced in this header trade agreement. | UN01011601 | Header_ Trade Agreement. Quotation Request Response. Referenced_ Document
<span id="PreviousOrderResponseDocument">PreviousOrderResponseDocument</span> | [edi3:Document](#Document) | The previous order response document referenced in this header trade agreement. | UN01011593 | Header_ Trade Agreement. Previous_ Order Response. Referenced_ Document
<span id="HeaderTradeAgreementCatalogueDocument">HeaderTradeAgreementCatalogueDocument</span> | [edi3:Document](#Document) | A catalogue document referenced in this header trade agreement. | UN01011580 | Header_ Trade Agreement. Catalogue. Referenced_ Document
<span id="HeaderTradeAgreementImpactCode">HeaderTradeAgreementImpactCode</span> | xsd:token | The code specifying the impact for this header trade agreement. | UN01013024 | Header_ Trade Agreement. Impact. Code
<span id="HeaderTradeAgreementPromotionalDealDocument">HeaderTradeAgreementPromotionalDealDocument</span> | [edi3:Document](#Document) | The promotional deal document referenced in this header trade agreement. | UN01011573 | Header_ Trade Agreement. Promotional Deal. Referenced_ Document
<span id="SellerAssignedAccountant">SellerAssignedAccountant</span> | [edi3:TradeParty](#TradeParty) | The party assigned as an accountant by the seller for this header trade agreement. | UN01011556 | Header_ Trade Agreement. Seller_ Assigned Accountant. Trade_ Party
<span id="HeaderTradeAgreementTradeDeliveryTerms">HeaderTradeAgreementTradeDeliveryTerms</span> | [edi3:DeliveryTerms](#DeliveryTerms) | The terms of delivery applicable to this header trade agreement. | UN01011560 | Header_ Trade Agreement. Applicable. Trade_ Delivery Terms
<span id="HeaderTradeAgreementImportLicenceDocument">HeaderTradeAgreementImportLicenceDocument</span> | [edi3:Document](#Document) | The import licence document referenced in this header trade agreement. | UN01011597 | Header_ Trade Agreement. Import Licence. Referenced_ Document
<span id="HeaderTradeAgreementQuotationDocument">HeaderTradeAgreementQuotationDocument</span> | [edi3:Document](#Document) | The quotation document referenced in this header trade agreement. | UN01011566 | Header_ Trade Agreement. Quotation. Referenced_ Document
<span id="HeaderTradeAgreementExportLicenceDocument">HeaderTradeAgreementExportLicenceDocument</span> | [edi3:Document](#Document) | The export licence document referenced in this header trade agreement. | UN01011598 | Header_ Trade Agreement. Export Licence. Referenced_ Document
<span id="HeaderTradeAgreementQuotationRequestDocument">HeaderTradeAgreementQuotationRequestDocument</span> | [edi3:Document](#Document) | The quotation request document referenced in this header trade agreement. | UN01011568 | Header_ Trade Agreement. Quotation Request. Referenced_ Document
<span id="HeaderTradeAgreementPreviousOrderDocument">HeaderTradeAgreementPreviousOrderDocument</span> | [edi3:Document](#Document) | The previous order document referenced in this header trade agreement. | UN01011591 | Header_ Trade Agreement. Previous_ Order. Referenced_ Document
<span id="HeaderTradeAgreementRequisitionerDocument">HeaderTradeAgreementRequisitionerDocument</span> | [edi3:Document](#Document) | A requisitioner document referenced in this header trade agreement. | UN01011576 | Header_ Trade Agreement. Requisitioner. Referenced_ Document
<span id="PricingBaseAppilicableLogisticsLocation">PricingBaseAppilicableLogisticsLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | The logistics location applicable to the pricing base for this header trade agreement. | UN01012666 | Header_ Trade Agreement. Pricing Base_ Applicable. Logistics_ Location
<span id="PreviousOrderChangeDocument">PreviousOrderChangeDocument</span> | [edi3:Document](#Document) | The previous order change document referenced in this header trade agreement. | UN01011592 | Header_ Trade Agreement. Previous_ Order Change. Referenced_ Document
<span id="HeaderTradeAgreementContractDocument">HeaderTradeAgreementContractDocument</span> | [edi3:Document](#Document) | A contract document referenced in this header trade agreement. | UN01011569 | Header_ Trade Agreement. Contract. Referenced_ Document
<span id="HeaderTradeAgreementBuyerApprovedDateTime">HeaderTradeAgreementBuyerApprovedDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value of approval by the buyer for this header trade agreement. | UN01013410 | Header_ Trade Agreement. Buyer_ Approved. Date Time
<span id="HeaderTradeAgreementCatalogueInformationProvider">HeaderTradeAgreementCatalogueInformationProvider</span> | [edi3:TradeParty](#TradeParty) | The party that provides catalogue information for this header trade agreement. | UN01011581 | Header_ Trade Agreement. Catalogue_ Information Provider. Trade_ Party
<span id="CatalogueRequestDocument">CatalogueRequestDocument</span> | [edi3:Document](#Document) | A catalogue request document referenced in this header trade agreement. | UN01011587 | Header_ Trade Agreement. Catalogue Request. Referenced_ Document
<span id="HeaderTradeAgreementBlanketOrderDocument">HeaderTradeAgreementBlanketOrderDocument</span> | [edi3:Document](#Document) | The blanket order document referenced in this header trade agreement. | UN01011590 | Header_ Trade Agreement. Blanket Order. Referenced_ Document
<span id="HeaderTradeAgreementUltimateCustomerOrderDocument">HeaderTradeAgreementUltimateCustomerOrderDocument</span> | [edi3:Document](#Document) | An ultimate customer order document referenced for this header trade agreement. | UN01012133 | Header_ Trade Agreement. Ultimate Customer_ Order. Referenced_ Document
<span id="HeaderTradeAgreementSalesReportDocument">HeaderTradeAgreementSalesReportDocument</span> | [edi3:Document](#Document) | The sales report document referenced in this header trade agreement. | UN01011589 | Header_ Trade Agreement. Sales Report. Referenced_ Document
<span id="HeaderTradeAgreementSeller">HeaderTradeAgreementSeller</span> | [edi3:TradeParty](#TradeParty) | The seller party for this header trade agreement. | UN01011551 | Header_ Trade Agreement. Seller. Trade_ Party


<h1 id="SubordinateLineTradeAgreement">SubordinateLineTradeAgreement</h1>

Type: rdf:Class

Definition: The contractual terms of a subordinate line trade agreement.

Unique UN Assigned ID: UN01011843

Dictionary Entry Name: Subordinate Line_ Trade Agreement. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="GrossPrice">GrossPrice</span> | [edi3:TradePrice](#TradePrice) | A gross product price in this subordinate line trade agreement. | UN01011847 | Subordinate Line_ Trade Agreement. Gross Price_ Product. Trade_ Price
<span id="SubordinateLineTradeAgreementSellerOrderDocument">SubordinateLineTradeAgreementSellerOrderDocument</span> | [edi3:Document](#Document) | The seller generated order document referenced in this subordinate line trade agreement. | UN01011844 | Subordinate Line_ Trade Agreement. Seller_ Order. Referenced_ Document
<span id="SubordinateLineTradeAgreementAdditionalDocument">SubordinateLineTradeAgreementAdditionalDocument</span> | [edi3:Document](#Document) | An additional document referenced in this subordinate line trade agreement. | UN01011846 | Subordinate Line_ Trade Agreement. Additional. Referenced_ Document
<span id="SubordinateLineTradeAgreementBuyerOrderDocument">SubordinateLineTradeAgreementBuyerOrderDocument</span> | [edi3:Document](#Document) | A buyer generated order document referenced in this subordinate line trade agreement. | UN01011845 | Subordinate Line_ Trade Agreement. Buyer_ Order. Referenced_ Document


<h1 id="DirectPosition">DirectPosition</h1>

Type: rdf:Class

Definition: A specified physical location described within a coordinate reference system.

Unique UN Assigned ID: UN01010466

Dictionary Entry Name: Specified_ Direct Position. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="UnitOfMeasureLabelListText">UnitOfMeasureLabelListText</span> | xsd:string | An ordered list of Unit Of Measure (UOM) labels, expressed as text, for this specified direct position. | UN01010470 | Specified_ Direct Position. UOM_ Label List. Text
<span id="DirectPositionCount">DirectPositionCount</span> | xsd:decimal | A count for this specified direct position. | UN01010471 | Specified_ Direct Position. Count. Numeric
<span id="DirectPositionCoordinateReferenceDimensionText">DirectPositionCoordinateReferenceDimensionText</span> | xsd:string | A coordinate reference dimension, expressed as text, for this specified direct position. | UN01010468 | Specified_ Direct Position. Coordinate Reference Dimension. Text
<span id="DirectPositionName">DirectPositionName</span> | xsd:string | The name, expressed as text, of the reference for this specified direct position. | UN01010467 | Specified_ Direct Position. Name. Text


<h1 id="TradeAllowanceCharge">TradeAllowanceCharge</h1>

Type: rdf:Class

Definition: A component of pricing, such as an allowance or charge for trade purposes.

Unique UN Assigned ID: UN01001631

Dictionary Entry Name: Trade_ Allowance Charge. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="TradeAllowanceChargeReasonText">TradeAllowanceChargeReasonText</span> | xsd:string | The reason, expressed as text, for this trade allowance charge. | UN01004557 | Trade_ Allowance Charge. Reason. Text
<span id="TradeAllowanceChargeBasisAmount">TradeAllowanceChargeBasisAmount</span> | xsd:decimal | The monetary value that is the basis on which this trade allowance charge is calculated. | UN01001636 | Trade_ Allowance Charge. Basis. Amount
<span id="TradeAllowanceChargeChargeIndicator">TradeAllowanceChargeChargeIndicator</span> | xsd:boolean | The indication of whether or not the trade allowance charge is a charge. | UN01001632 | Trade_ Allowance Charge. Charge. Indicator
<span id="TradeAllowanceChargeID">TradeAllowanceChargeID</span> | xsd:token | The unique identifier for this trade allowance charge. | UN01001633 | Trade_ Allowance Charge. Identification. Identifier
<span id="TradeAllowanceChargeTypeCode">TradeAllowanceChargeTypeCode</span> | xsd:token | The code specifying the type of this trade allowance charge. | UN01008859 | Trade_ Allowance Charge. Type. Code
<span id="TradeAllowanceChargeTaxCategory">TradeAllowanceChargeTaxCategory</span> | [edi3:TradeTax](#TradeTax) | A tax category of this trade allowance charge. | UN01004558 | Trade_ Allowance Charge. Category. Trade_ Tax
<span id="TradeAllowanceChargeReasonCode">TradeAllowanceChargeReasonCode</span> | xsd:token | The code specifying the reason for this trade allowance charge. | UN01004556 | Trade_ Allowance Charge. Reason. Code
<span id="TradeAllowanceChargeActualAmount">TradeAllowanceChargeActualAmount</span> | xsd:decimal | An actual monetary value of the trade allowance charge. | UN01002069 | Trade_ Allowance Charge. Actual. Amount
<span id="TradeAllowanceChargeUnitBasisAmount">TradeAllowanceChargeUnitBasisAmount</span> | xsd:decimal | The monetary value of the unit basis on which the allowance or charge is calculated. | UN01004554 | Trade_ Allowance Charge. Unit_ Basis. Amount
<span id="TradeAllowanceChargeSequenceNumber">TradeAllowanceChargeSequenceNumber</span> | xsd:decimal | The sequence number for applying this trade allowance charge. | UN01001634 | Trade_ Allowance Charge. Sequence. Numeric
<span id="TradeAllowanceChargeBasisQuantity">TradeAllowanceChargeBasisQuantity</span> | xsd:decimal | The quantity on which this trade allowance charge is based. | UN01001637 | Trade_ Allowance Charge. Basis. Quantity
<span id="TradeAllowanceChargeCalculationPercent">TradeAllowanceChargeCalculationPercent</span> | xsd:decimal | The percentage applied to calculate this trade allowance charge. | UN01001635 | Trade_ Allowance Charge. Calculation. Percent
<span id="PrepaidIndicator">PrepaidIndicator</span> | xsd:boolean | The indication of whether or not this trade allowance charge is prepaid. | UN01001638 | Trade_ Allowance Charge. Prepaid. Indicator


<h1 id="AppliedAllowanceCharge">AppliedAllowanceCharge</h1>

Type: rdf:Class

Definition: The applied allowance or charge component of pricing.

Unique UN Assigned ID: UN01000188

Dictionary Entry Name: Applied_ Allowance Charge. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="AppliedAllowanceChargeReasonCode">AppliedAllowanceChargeReasonCode</span> | xsd:token | The code specifying the reason for this applied allowance charge. | UN01000191 | Applied_ Allowance Charge. Reason. Code
<span id="AppliedAllowanceChargeDescription">AppliedAllowanceChargeDescription</span> | xsd:string | The textual description of the applied allowance charge. | UN01000190 | Applied_ Allowance Charge. Description. Text
<span id="AppliedAllowanceChargeCalculationPercent">AppliedAllowanceChargeCalculationPercent</span> | xsd:decimal | The percentage used to calculate the applied allowance charge. | UN01000192 | Applied_ Allowance Charge. Calculation. Percent
<span id="AppliedAllowanceChargeActualAmount">AppliedAllowanceChargeActualAmount</span> | xsd:decimal | The actual monetary value of the applied allowance charge. | UN01000189 | Applied_ Allowance Charge. Actual. Amount
<span id="AppliedAllowanceChargeBasisAmount">AppliedAllowanceChargeBasisAmount</span> | xsd:decimal | The monetary value that is the basis on which the applied allowance charge is calculated. | UN01000193 | Applied_ Allowance Charge. Basis. Amount
<span id="AppliedAllowanceChargeChargeIndicator">AppliedAllowanceChargeChargeIndicator</span> | xsd:boolean | The indication of whether or not the applied allowance charge is a charge. | UN01000194 | Applied_ Allowance Charge. Charge. Indicator


<h1 id="Label">Label</h1>

Type: rdf:Class

Definition: A label used for identifying goods for logistics purposes, such as a barcode, a radio frequency tag or a Vehicle Identification Number (VIN).

Unique UN Assigned ID: UN01003675

Dictionary Entry Name: Logistics_ Label. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="LabelSeriesStartID">LabelSeriesStartID</span> | xsd:token | The unique identifier of the start of a series of logistics labels. | UN01003677 | Logistics_ Label. Series Start. Identifier
<span id="LayoutTypeCode">LayoutTypeCode</span> | xsd:token | The code specifying the layout type of this logistics label. | UN01012728 | Logistics_ Label. Layout_ Type. Code
<span id="SizeCode">SizeCode</span> | xsd:token | The code specifying the size of this logistics label. | UN01012729 | Logistics_ Label. Size. Code
<span id="LabelID">LabelID</span> | xsd:token | The unique identifier of this logistics label. | UN01003676 | Logistics_ Label. Identification. Identifier
<span id="IncludedSection">IncludedSection</span> | [edi3:Section](#Section) | A section included in this logistics label. | UN01012730 | Logistics_ Label. Included. Label_ Section


<h1 id="RegisteredTax">RegisteredTax</h1>

Type: rdf:Class

Definition: A registered tax or duty system pertaining to an authority.

Unique UN Assigned ID: UN01004057

Dictionary Entry Name: Registered_ Tax. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="RegisteredTaxTypeCode">RegisteredTaxTypeCode</span> | xsd:token | The code specifying the type of registered tax. | UN01004058 | Registered_ Tax. Type. Code
<span id="RegisteredTaxCurrencyCode">RegisteredTaxCurrencyCode</span> | xsd:token | The code specifying the currency for this registered tax. | UN01004061 | Registered_ Tax. Currency. Code
<span id="RegisteredTaxDescription">RegisteredTaxDescription</span> | xsd:string | A textual description of this registered tax. | UN01004063 | Registered_ Tax. Description. Text
<span id="RegisteredTaxCustomsDutyIndicator">RegisteredTaxCustomsDutyIndicator</span> | xsd:boolean | The indication of whether or not this registered tax is a customs duty. | UN01004064 | Registered_ Tax. Customs Duty. Indicator
<span id="RegisteredTaxJurisdictionText">RegisteredTaxJurisdictionText</span> | xsd:string | A jurisdiction, expressed as text, for this registered tax. | UN01004062 | Registered_ Tax. Jurisdiction. Text
<span id="RegisteredTaxExemptionReasonText">RegisteredTaxExemptionReasonText</span> | xsd:string | A reason, expressed as text, for exemption from this registered tax. | UN01004060 | Registered_ Tax. Exemption Reason. Text


<h1 id="TradeTax">TradeTax</h1>

Type: rdf:Class

Definition: A trade related fiscal levy or duty.

Unique UN Assigned ID: UN01004709

Dictionary Entry Name: Trade_ Tax. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="TradeTaxBasisAmount">TradeTaxBasisAmount</span> | xsd:decimal | A monetary value used as the basis on which this trade related tax, levy or duty is calculated. | UN01004717 | Trade_ Tax. Basis. Amount
<span id="BuyerNonDeductibleTaxAccountingAccount">BuyerNonDeductibleTaxAccountingAccount</span> | [edi3:AccountingAccount](#AccountingAccount) | The buyer non-deductible tax specified accounting account for this trade related tax, levy or duty. | UN01009023 | Trade_ Tax. Buyer Non-Deductible Tax_ Specified. Trade_ Accounting Account
<span id="BuyerRepayableTaxAccountingAccount">BuyerRepayableTaxAccountingAccount</span> | [edi3:AccountingAccount](#AccountingAccount) | The buyer repayable tax specified accounting account for this trade related tax, levy or duty. | UN01009009 | Trade_ Tax. Buyer Repayable Tax_ Specified. Trade_ Accounting Account
<span id="SelfAssessedBasisQuantity">SelfAssessedBasisQuantity</span> | xsd:decimal | The quantity on which this trade related tax, levy or duty has been calculated on a self-assessment basis. | UN01004732 | Trade_ Tax. Self-Assessed Basis. Quantity
<span id="ServiceSupplyCountry">ServiceSupplyCountry</span> | [edi3:Country](#Country) | The country or country sub-division where a service was supplied for this trade tax. | UN01006063 | Trade_ Tax. Service Supply. Trade_ Country
<span id="TradeTaxCustomsDutyIndicator">TradeTaxCustomsDutyIndicator</span> | xsd:boolean | The indication of whether or not this trade related tax, levy or duty is a customs duty. | UN01004722 | Trade_ Tax. Customs Duty. Indicator
<span id="TradeTaxGuaranteeCode">TradeTaxGuaranteeCode</span> | xsd:token | The code specifying an undertaking given in cash, bond or as a written guarantee to ensure that an obligation will be fulfilled for this trade related tax, levy or duty. | UN01004738 | Trade_ Tax. Guarantee. Code
<span id="SellerRefundableTaxAccountingAccount">SellerRefundableTaxAccountingAccount</span> | [edi3:AccountingAccount](#AccountingAccount) | The seller refundable tax specified accounting account for this trade related tax, levy or duty. | UN01009011 | Trade_ Tax. Seller Refundable Tax_ Specified. Trade_ Accounting Account
<span id="PaymentID">PaymentID</span> | xsd:token | The unique identifier of the payment of this trade related tax, levy or duty. | UN01004728 | Trade_ Tax. Payment. Identifier
<span id="CategoryName">CategoryName</span> | xsd:string | A category name, expressed as text, of this trade related tax, levy or duty. | UN01004742 | Trade_ Tax. Category Name. Text
<span id="CalculationSequenceNumber">CalculationSequenceNumber</span> | xsd:decimal | A numeric expression of the sequence in which this trade related tax is to be or has been applied when multiple taxes are applicable per calculation, such as first "Value Added Tax (VAT)", second "Transfer". | UN01004715 | Trade_ Tax. Calculation Sequence. Numeric
<span id="TradeTaxCurrencyCode">TradeTaxCurrencyCode</span> | xsd:token | The code specifying the currency for this trade related tax, levy or duty [UNCL 6345]. | UN01004720 | Trade_ Tax. Currency. Code
<span id="ExemptionAuthorizationID">ExemptionAuthorizationID</span> | xsd:token | The unique identifier of the exemption authorization for this trade tax. | UN01004710 | Trade_ Tax. Exemption Authorization_ Identification. Identifier
<span id="TradeTaxExemptionReasonCode">TradeTaxExemptionReasonCode</span> | xsd:token | A code specifying a reason for exemption from this trade related tax, levy or duty. | UN01004723 | Trade_ Tax. Exemption Reason. Code
<span id="RegimeTypeCode">RegimeTypeCode</span> | xsd:token | The code specifying a type of regime applicable to the assessment or calculation of this trade related tax, levy or duty, such as a preferential duty rate. | UN01004735 | Trade_ Tax. Regime Type. Code
<span id="TradeTaxCategoryCode">TradeTaxCategoryCode</span> | xsd:token | The code specifying the category to which this trade related tax, levy or duty applies, such as codes for "Exempt from Tax", "Standard Rate", "Free Export Item - Tax Not Charged" [Reference United Nations Code List (UNCL) 5305]. | UN01004719 | Trade_ Tax. Category. Code
<span id="TradeTaxGuaranteeText">TradeTaxGuaranteeText</span> | xsd:string | The undertaking, expressed as text, given in cash, bond or as a written guarantee to ensure that an obligation will be fulfilled for this trade related tax, levy or duty. | UN01004739 | Trade_ Tax. Guarantee. Text
<span id="BuyerDeductibleTaxAccountingAccount">BuyerDeductibleTaxAccountingAccount</span> | [edi3:AccountingAccount](#AccountingAccount) | The buyer deductible tax specified accounting account for this trade related tax, levy or duty. | UN01009022 | Trade_ Tax. Buyer Deductible Tax_ Specified. Trade_ Accounting Account
<span id="TradeTaxTypeCode">TradeTaxTypeCode</span> | xsd:token | The code specifying the type of trade related tax, levy or duty, such as a code for a Value Added Tax (VAT) [Reference United Nations Code List (UNCL) 5153]. | UN01004712 | Trade_ Tax. Type. Code
<span id="Percent">Percent</span> | xsd:decimal | The percent of trade tax applicable, such as to an object or an activity. | UN01007284 | Trade_ Tax. Applicable. Percent
<span id="TradeTaxGrandTotalAmount">TradeTaxGrandTotalAmount</span> | xsd:decimal | A monetary value of the grand total of the basis plus tax for this trade tax. | UN01013042 | Trade_ Tax. Grand Total. Amount
<span id="TradeTaxCalculatedAmount">TradeTaxCalculatedAmount</span> | xsd:decimal | A monetary value resulting from the calculation of this trade related tax, levy or duty. | UN01004711 | Trade_ Tax. Calculated. Amount
<span id="TradeTaxTariffDeductionQuantity">TradeTaxTariffDeductionQuantity</span> | xsd:decimal | A quantity to be deducted from the tariff quantity for the calculation of this trade related tax, duty or levy. | UN01004740 | Trade_ Tax. Tariff Deduction. Quantity
<span id="RefundAmount">RefundAmount</span> | xsd:decimal | A monetary value of the refund of this trade related tax, levy or duty. | UN01004743 | Trade_ Tax. Refund. Amount
<span id="TradeTaxPaymentMethodCode">TradeTaxPaymentMethodCode</span> | xsd:token | The code specifying the payment method for this trade related tax, levy or duty. | UN01004729 | Trade_ Tax. Payment Method. Code
<span id="BasisAllowanceRate">BasisAllowanceRate</span> | xsd:decimal | The rate of the tax basis allowance (deduction or discount) used to calculate the trade related tax, levy or duty. | UN01004724 | Trade_ Tax. Tax Basis Allowance. Rate
<span id="TradeTaxUnitBasisAmount">TradeTaxUnitBasisAmount</span> | xsd:decimal | A monetary value that constitutes the per unit basis on which this trade related tax, levy or duty is calculated. | UN01004718 | Trade_ Tax. Unit_ Basis. Amount
<span id="SellerPayableTaxAccountingAccount">SellerPayableTaxAccountingAccount</span> | [edi3:AccountingAccount](#AccountingAccount) | The seller payable tax specified accounting account for this trade related tax, levy or duty. | UN01009010 | Trade_ Tax. Seller Payable Tax_ Specified. Trade_ Accounting Account
<span id="TradeTaxBasisQuantity">TradeTaxBasisQuantity</span> | xsd:decimal | The quantity used as the basis for calculating the amount of this trade related tax, levy or duty. | UN01004716 | Trade_ Tax. Basis. Quantity
<span id="ApplicableRatePercent">ApplicableRatePercent</span> | xsd:decimal | The applicable rate, expressed as a percentage, for this trade tax, levy or duty. | UN01009021 | Trade_ Tax. Rate_ Applicable. Percent
<span id="TradeTaxTaxPointDate">TradeTaxTaxPointDate</span> | xsd:date | The date of the tax point when this trade related tax, levy or duty becomes applicable. | UN01004725 | Trade_ Tax. Tax Point. Date
<span id="TaxCalculationMethodCode">TaxCalculationMethodCode</span> | xsd:token | The code specifying the method by which this trade related tax, levy or duty is calculated, such as codes for "tax calculated after line total summation", "tax calculated before line total summation", "tax back calculated based on grand total". | UN01013097 | Trade_ Tax. Calculation Method. Code
<span id="AllowanceChargeBasisAmount">AllowanceChargeBasisAmount</span> | xsd:decimal | A monetary value used as the allowance and charge basis on which this trade related tax, levy or duty is calculated. | UN01004875 | Trade_ Tax. Allowance Charge_ Basis. Amount
<span id="ExemptionIndicator">ExemptionIndicator</span> | xsd:boolean | The indication of whether or not there is an exemption from this trade tax. | UN01004876 | Trade_ Tax. Exemption. Indicator
<span id="SelfAssessedBasisAmount">SelfAssessedBasisAmount</span> | xsd:decimal | A monetary value of the amount on which this trade related tax, levy or duty has been calculated on a self-assessment basis. | UN01004733 | Trade_ Tax. Self-Assessed Basis. Amount
<span id="SelfAssessedCalculatedAmount">SelfAssessedCalculatedAmount</span> | xsd:decimal | A monetary value of the self-assessed calculated amount of this trade related tax, levy or duty. | UN01004731 | Trade_ Tax. Self-Assessed Calculated. Amount
<span id="TradeTaxExemptionReasonText">TradeTaxExemptionReasonText</span> | xsd:string | The reason, expressed as text, for exemption from this trade related tax, levy or duty. | UN01004713 | Trade_ Tax. Exemption Reason. Text
<span id="TradeTaxInformationAmount">TradeTaxInformationAmount</span> | xsd:decimal | A monetary value of an amount being reported for information for this trade related tax, levy or duty. | UN01004741 | Trade_ Tax. Information. Amount
<span id="DueDateTypeCode">DueDateTypeCode</span> | xsd:token | The code specifying a type of due date for this trade tax. | UN01006051 | Trade_ Tax. Due Date Type. Code
<span id="ApplicableLocation">ApplicableLocation</span> | [edi3:TradeLocation](#TradeLocation) | A location where this trade tax is applicable. | UN01011929 | Trade_ Tax. Place_ Applicable. Trade_ Location
<span id="DeductionAmount">DeductionAmount</span> | xsd:decimal | A monetary value of the deduction from this trade related tax, levy or duty. | UN01004730 | Trade_ Tax. Deduction. Amount
<span id="TradeTaxCalculatedRate">TradeTaxCalculatedRate</span> | xsd:decimal | The rate used to calculate the amount of this trade related tax, levy or duty. | UN01004714 | Trade_ Tax. Calculated. Rate
<span id="TradeTaxTypeText">TradeTaxTypeText</span> | xsd:string | The type, expressed as text, of this trade related tax, levy or duty. | UN01004727 | Trade_ Tax. Type. Text
<span id="TradeTaxJurisdictionText">TradeTaxJurisdictionText</span> | xsd:string | A jurisdiction, expressed as text, to which this trade related tax, levy or duty applies. | UN01004721 | Trade_ Tax. Jurisdiction. Text
<span id="TaxExemptionAuthorityID">TaxExemptionAuthorityID</span> | xsd:token | The unique tax exemption authority identifier for this trade tax. | UN01004873 | Trade_ Tax. Tax Exemption Authority_ Identification. Identifier
<span id="LineTotalBasisAmount">LineTotalBasisAmount</span> | xsd:decimal | A monetary value used as the line total basis on which this trade related tax, levy or duty is calculated. | UN01004874 | Trade_ Tax. Line Total_ Basis. Amount
<span id="RateCode">RateCode</span> | xsd:token | The code specifying the rate for this trade related tax, levy or duty. | UN01004736 | Trade_ Tax. Rate. Code


<h1 id="AppliedTax">AppliedTax</h1>

Type: rdf:Class

Definition: A total levy or payment for the support of a government that is required of persons, groups, or businesses within the domain of that government.

Unique UN Assigned ID: UN01000183

Dictionary Entry Name: Applied_ Tax. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="AppliedTaxCalculatedAmount">AppliedTaxCalculatedAmount</span> | xsd:decimal | The monetary value resulting from the calculation of the applied tax. | UN01000184 | Applied_ Tax. Calculated. Amount
<span id="AppliedTaxTaxPointDate">AppliedTaxTaxPointDate</span> | xsd:date | The date of the tax point when taxes, such as VAT, are to be applied. | UN01002070 | Applied_ Tax. Tax Point. Date
<span id="AppliedTaxCalculatedRate">AppliedTaxCalculatedRate</span> | xsd:decimal | The rate used to calculate the applied tax. | UN01000186 | Applied_ Tax. Calculated. Rate
<span id="AppliedTaxBasisAmount">AppliedTaxBasisAmount</span> | xsd:decimal | The monetary value used as the basis in calculating the applied tax. | UN01000187 | Applied_ Tax. Basis. Amount


<h1 id="Process">Process</h1>

Type: rdf:Class

Definition: A naturally occurring or designed sequence of operations or events that create, transform, or touch a product, such as manufacturing, treating, packaging, and storing.

Unique UN Assigned ID: UN01002627

Dictionary Entry Name: Product Handling_ Process. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="CompletionPeriod">CompletionPeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The specified period of completion for this product handling process. | UN01004857 | Product Handling_ Process. Completion. Specified_ Period
<span id="OperationCountry">OperationCountry</span> | [edi3:Country](#Country) | The trade country where the operation of this product handling process occurs. | UN01002631 | Product Handling_ Process. Operation. Trade_ Country
<span id="ApplicableCharacteristic">ApplicableCharacteristic</span> | [edi3:ProcessCharacteristic](#ProcessCharacteristic) | A process characteristic applicable to this product handling process. | UN01002630 | Product Handling_ Process. Applicable. Process_ Characteristic
<span id="ProcessOperator">ProcessOperator</span> | [edi3:TradeParty](#TradeParty) | A trade party who is an operator of this product handling process. | UN01003970 | Product Handling_ Process. Operator. Trade_ Party


<h1 id="BreakdownStatement">BreakdownStatement</h1>

Type: rdf:Class

Definition: A detailed statement of work, prices, and dimensions for this valuation.

Unique UN Assigned ID: UN01007545

Dictionary Entry Name: Valuation_ Breakdown Statement. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="BreakdownStatementName">BreakdownStatementName</span> | xsd:string | The name, expressed as text, for this valuation breakdown statement. | UN01007547 | Valuation_ Breakdown Statement. Name. Text
<span id="ReaderBinaryFile">ReaderBinaryFile</span> | [edi3:BinaryFile](#BinaryFile) | A specified binary file used to read this valuation breakdown statement. | UN01011935 | Valuation_ Breakdown Statement. Reader. Specified_ Binary File
<span id="DefaultLanguageCode">DefaultLanguageCode</span> | xsd:token | The code specifying the default language for this valuation breakdown statement. | UN01007552 | Valuation_ Breakdown Statement. Default_ Language. Code
<span id="BreakdownStatementContractualLanguageCode">BreakdownStatementContractualLanguageCode</span> | xsd:token | The code specifying the contractual language for this valuation breakdown statement. | UN01007557 | Valuation_ Breakdown Statement. Contractual Language. Code
<span id="DefaultCurrencyCode">DefaultCurrencyCode</span> | xsd:token | The code specifying the default currency for this valuation breakdown statement. | UN01007551 | Valuation_ Breakdown Statement. Default_ Currency. Code
<span id="BreakdownStatementID">BreakdownStatementID</span> | xsd:token | The unique identifier for this valuation breakdown statement. | UN01007546 | Valuation_ Breakdown Statement. Identification. Identifier
<span id="PriceListID">PriceListID</span> | xsd:token | The identifier of a price list for this valuation breakdown statement. | UN01007556 | Valuation_ Breakdown Statement. Price List_ Identification. Identifier
<span id="ValuationGroupedWorkItem">ValuationGroupedWorkItem</span> | [edi3:GroupedWorkItem](#GroupedWorkItem) | A grouped work item in this valuation breakdown statement. | UN01007558 | Valuation_ Breakdown Statement. Item. Grouped_ Work Item
<span id="BreakdownStatementTypeCode">BreakdownStatementTypeCode</span> | xsd:token | A code specifying the type of valuation breakdown statement. | UN01007554 | Valuation_ Breakdown Statement. Type. Code
<span id="ValuationBasicWorkItem">ValuationBasicWorkItem</span> | [edi3:BasicWorkItem](#BasicWorkItem) | A basic work item in this valuation breakdown statement. | UN01007559 | Valuation_ Breakdown Statement. Item. Basic_ Work Item
<span id="BreakdownStatementRequestedActionCode">BreakdownStatementRequestedActionCode</span> | xsd:token | A code specifying the requested action for this valuation breakdown statement. | UN01007555 | Valuation_ Breakdown Statement. Requested Action. Code
<span id="BreakdownStatementReferencedBinaryFile">BreakdownStatementReferencedBinaryFile</span> | [edi3:BinaryFile](#BinaryFile) | A specified binary file referenced by this valuation breakdown statement. | UN01011936 | Valuation_ Breakdown Statement. Referenced. Specified_ Binary File
<span id="BreakdownStatementTotalCalculatedPrice">BreakdownStatementTotalCalculatedPrice</span> | [edi3:CalculatedPrice](#CalculatedPrice) | A total calculated price for this valuation breakdown statement. | UN01007560 | Valuation_ Breakdown Statement. Total. Calculated_ Price
<span id="BreakdownStatementChangedRecordedStatus">BreakdownStatementChangedRecordedStatus</span> | [edi3:RecordedStatus](#RecordedStatus) | A changed recorded status for this valuation breakdown statement. | UN01007563 | Valuation_ Breakdown Statement. Changed. Recorded_ Status
<span id="CreationBinaryFile">CreationBinaryFile</span> | [edi3:BinaryFile](#BinaryFile) | A specified binary file used to create this valuation breakdown statement. | UN01011934 | Valuation_ Breakdown Statement. Creation. Specified_ Binary File
<span id="BreakdownStatementCreationDateTime">BreakdownStatementCreationDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value of the creation of this valuation breakdown statement. | UN01007550 | Valuation_ Breakdown Statement. Creation. Date Time
<span id="BreakdownStatementDescription">BreakdownStatementDescription</span> | xsd:string | A textual description of this valuation breakdown statement. | UN01007548 | Valuation_ Breakdown Statement. Description. Text
<span id="BreakdownStatementComment">BreakdownStatementComment</span> | xsd:string | A comment, expressed as text, for this valuation breakdown statement. | UN01007553 | Valuation_ Breakdown Statement. Comment. Text


<h1 id="ForecastTerms">ForecastTerms</h1>

Type: rdf:Class

Definition: A set of terms and conditions by which a supply chain forecast has been or will be made.

Unique UN Assigned ID: UN01004300

Dictionary Entry Name: Supply Chain_ Forecast Terms. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="ForecastTermsFrequencyCode">ForecastTermsFrequencyCode</span> | xsd:token | A code specifying a frequency in these supply chain forecast terms. | UN01004302 | Supply Chain_ Forecast Terms. Frequency. Code
<span id="ForecastTermsCommitmentLevelCode">ForecastTermsCommitmentLevelCode</span> | xsd:token | A code specifying a commitment level in these supply chain forecast terms. | UN01004304 | Supply Chain_ Forecast Terms. Commitment Level. Code
<span id="DateTypeCode">DateTypeCode</span> | xsd:token | A code specifying a type of date in these supply chain forecast terms. | UN01004303 | Supply Chain_ Forecast Terms. Date Type. Code


<h1 id="GeographicalLine">GeographicalLine</h1>

Type: rdf:Class

Definition: A connection between two points on the surface of the Earth (reference ISO 19136).

Unique UN Assigned ID: UN01012187

Dictionary Entry Name: Specified_ Geographical Line. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="GeographicalLineDirectPositionList">GeographicalLineDirectPositionList</span> | [edi3:DirectPositionList](#DirectPositionList) | The direct position list associated with this geographical line. | UN01012188 | Specified_ Geographical Line. Associated. Specified_ Direct Position List
<span id="GeographicalLineGeographicalObjectCharacteristic">GeographicalLineGeographicalObjectCharacteristic</span> | [edi3:GeographicalObjectCharacteristic](#GeographicalObjectCharacteristic) | The geographical object characteristic associated with this geographical line. | UN01012189 | Specified_ Geographical Line. Associated. Specified_ Geographical Object Characteristic


<h1 id="Version">Version</h1>

Type: rdf:Class

Definition: A specific variant of a document.

Unique UN Assigned ID: UN01003590

Dictionary Entry Name: Document_ Version. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="VersionName">VersionName</span> | xsd:string | The name, expressed as text, of this document version. | UN01003592 | Document_ Version. Name. Text
<span id="VersionID">VersionID</span> | xsd:token | The unique identifier for this document version. | UN01003591 | Document_ Version. Identification. Identifier


<h1 id="GeographicalObjectCharacteristic">GeographicalObjectCharacteristic</h1>

Type: rdf:Class

Definition: An attribute of a geographical object.

Unique UN Assigned ID: UN01012368

Dictionary Entry Name: Specified_ Geographical Object Characteristic. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="GeographicalObjectCharacteristicDescription">GeographicalObjectCharacteristicDescription</span> | xsd:string | The textual description for this geographical object characteristic. | UN01012370 | Specified_ Geographical Object Characteristic. Description. Text
<span id="RelevantGeometryTypeText">RelevantGeometryTypeText</span> | xsd:string | The type of geometry, expressed as text, relevant for this geographical object characteristic. | UN01013622 | Specified_ Geographical Object Characteristic. Relevant Geometry Type. Text
<span id="PhysicalIndicator">PhysicalIndicator</span> | xsd:boolean | The indication of whether or not this geographical object can be characterized as physical. | UN01013618 | Specified_ Geographical Object Characteristic. Physical. Indicator
<span id="GeometryCollectionIndicator">GeometryCollectionIndicator</span> | xsd:boolean | The indication of whether or not this geographical object can be characterized as a geometry collection. | UN01013617 | Specified_ Geographical Object Characteristic. Geometry Collection. Indicator
<span id="ShapeTypeText">ShapeTypeText</span> | xsd:string | The type of shape, expressed as text, such as a semi-circle, for this geographical object characteristic. | UN01013623 | Specified_ Geographical Object Characteristic. Shape Type. Text
<span id="GeographicalObjectCharacteristicName">GeographicalObjectCharacteristicName</span> | xsd:string | The name, expressed as text, for this geographical object characteristic. | UN01012372 | Specified_ Geographical Object Characteristic. Name. Text
<span id="DescriptionReferenceText">DescriptionReferenceText</span> | xsd:string | The description reference, expressed as text, for this geographical object characteristic. | UN01012371 | Specified_ Geographical Object Characteristic. Description Reference. Text


<h1 id="TaxRegistration">TaxRegistration</h1>

Type: rdf:Class

Definition: Registration with a specific tax authority.

Unique UN Assigned ID: UN01004486

Dictionary Entry Name: Tax_ Registration. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="TaxRegistrationID">TaxRegistrationID</span> | xsd:token | The unique identifier for this tax registration. | UN01004487 | Tax_ Registration. Identification. Identifier
<span id="TaxRegisteredTax">TaxRegisteredTax</span> | [edi3:RegisteredTax](#RegisteredTax) | The registered tax associated with this tax registration. | UN01004488 | Tax_ Registration. Associated. Registered_ Tax


<h1 id="LegalRegistration">LegalRegistration</h1>

Type: rdf:Class

Definition: The recording of items or details for a specific legal purpose.

Unique UN Assigned ID: UN01003648

Dictionary Entry Name: Legal_ Registration. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="LegalRegistrationID">LegalRegistrationID</span> | xsd:token | A unique identifier for this legal registration. | UN01003651 | Legal_ Registration. Identification. Identifier
<span id="LegalRegistrationLastRegisteredYear">LegalRegistrationLastRegisteredYear</span> | xsd:dateTime | The last year in which this legal registration was registered. | UN01003656 | Legal_ Registration. Last Registered Year. Date Time
<span id="LegalRegistrationCountryCode">LegalRegistrationCountryCode</span> | xsd:token | An identifier of the country in which this legal registration is valid. | UN01003654 | Legal_ Registration. Country. Identifier


<h1 id="GovernmentRegistration">GovernmentRegistration</h1>

Type: rdf:Class

Definition: The recording of items or details for a governmental purpose.

Unique UN Assigned ID: UN01011028

Dictionary Entry Name: Government_ Registration. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="GovernmentRegistrationID">GovernmentRegistrationID</span> | xsd:token | An identifier for this government registration. | UN01011029 | Government_ Registration. Identification. Identifier
<span id="GovernmentRegistrationCountryCode">GovernmentRegistrationCountryCode</span> | xsd:token | The identifier of the country for this government registration. | UN01011036 | Government_ Registration. Country. Identifier
<span id="GovernmentRegistrationTypeCode">GovernmentRegistrationTypeCode</span> | xsd:token | A code specifying a type of government registration. | UN01011031 | Government_ Registration. Type. Code
<span id="GovernmentRegistrationVersionID">GovernmentRegistrationVersionID</span> | xsd:token | The identifier of the version of this government registration. | UN01011030 | Government_ Registration. Version. Identifier
<span id="GovernmentRegistrationCategoryCode">GovernmentRegistrationCategoryCode</span> | xsd:token | A code specifying a category of this government registration. | UN01011032 | Government_ Registration. Category. Code
<span id="GovernmentRegistrationCountrySubDivisionCode">GovernmentRegistrationCountrySubDivisionCode</span> | xsd:token | The identifier of the country sub-division for this registration. | UN01011037 | Government_ Registration. Country Sub-Division. Identifier
<span id="GovernmentRegistrationValidityPeriod">GovernmentRegistrationValidityPeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The period of time during which this government registration is valid. | UN01011038 | Government_ Registration. Validity. Specified_ Period
<span id="LicenceID">LicenceID</span> | xsd:token | The identifier of a licence for this government registration. | UN01011033 | Government_ Registration. Licence. Identifier
<span id="RecordedDate">RecordedDate</span> | xsd:date | The date that this government registration was recorded. | UN01011034 | Government_ Registration. Recorded. Date


<h1 id="SpecifiedGeographicalCoordinate">SpecifiedGeographicalCoordinate</h1>

Type: rdf:Class

Definition: The latitude and longitude of a specified place, by which its relative situation on the globe is known. The height above the sea level constitutes a third coordinate.

Unique UN Assigned ID: UN01002026

Dictionary Entry Name: Specified_ Geographical Coordinate. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="SpecifiedGeographicalCoordinateLongitude">SpecifiedGeographicalCoordinateLongitude</span> | xsd:decimal | The measure of the longitude as an angular distance east or west from the Greenwich meridian to the meridian of a specific place for this specified geographical coordinate. (Reference ISO 6709). | UN01002029 | Specified_ Geographical Coordinate. Longitude. Measure
<span id="SpecifiedGeographicalCoordinateLatitudeDirectionIndicator">SpecifiedGeographicalCoordinateLatitudeDirectionIndicator</span> | xsd:boolean | The indication of whether the latitude compass direction from the Equator meridian to the meridian of a specific place for this specified geographical coordinate is North (+) or South (-).  (Reference ISO 6709). | UN01002030 | Specified_ Geographical Coordinate. Latitude Direction. Indicator
<span id="SpecifiedGeographicalCoordinateLatitude">SpecifiedGeographicalCoordinateLatitude</span> | xsd:decimal | The measure of the latitude as an angular distance north or south from the Equator meridian to the meridian of a specific place for this specified geographical coordinate. (Reference ISO 6709). | UN01002028 | Specified_ Geographical Coordinate. Latitude. Measure
<span id="SpecifiedGeographicalCoordinateSystemID">SpecifiedGeographicalCoordinateSystemID</span> | xsd:token | The unique identifier of the system used for measuring this specified geographical coordinate. | UN01002032 | Specified_ Geographical Coordinate. System. Identifier
<span id="SpecifiedGeographicalCoordinateAltitude">SpecifiedGeographicalCoordinateAltitude</span> | xsd:decimal | The measure of the altitude that reflects the vertical elevation of an object above a surface for this specified geographical coordinate (Reference ISO 6709). | UN01002027 | Specified_ Geographical Coordinate. Altitude. Measure


<h1 id="GeographicalCoordinate">GeographicalCoordinate</h1>

Type: rdf:Class

Definition: A set of geographical coordinates of a specific point such as the longitude, latitude and altitude.

Unique UN Assigned ID: UN01003616

Dictionary Entry Name: Geographical Coordinate. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="TimeZoneText">TimeZoneText</span> | xsd:string | The time zone, expressed as text, for this geographical coordinate. | UN01013610 | Geographical Coordinate. Time Zone. Text
<span id="GeographicalCoordinateSystemID">GeographicalCoordinateSystemID</span> | xsd:token | The unique identifier of the reference system used for measuring a geographical coordinate. | UN01003622 | Geographical Coordinate. System. Identifier
<span id="AltimetricSystemID">AltimetricSystemID</span> | xsd:token | The unique identifier of the system used for measuring the altitude. | UN01003624 | Geographical Coordinate. Altimetric System. Identifier
<span id="TimeZoneDateTime">TimeZoneDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value for the time zone of this geographical coordinate. | UN01013465 | Geographical Coordinate. Time Zone. Date Time
<span id="GeographicalCoordinateLatitudeDirectionIndicator">GeographicalCoordinateLatitudeDirectionIndicator</span> | xsd:boolean | The indication of whether the latitude compass direction from the Equator meridian to the meridian of a specific place is North (+) or South (-)  (Reference ISO 6709). | UN01003620 | Geographical Coordinate. Latitude Direction. Indicator
<span id="GeographicalCoordinateLongitudeDirectionIndicator">GeographicalCoordinateLongitudeDirectionIndicator</span> | xsd:boolean | The indication of whether the longitude as a compass direction from the Greenwich meridian to the meridian of a specific place is East (+) or West (-) for this geographical coordinate (Reference ISO 6709). | UN01003621 | Geographical Coordinate. Longitude Direction. Indicator
<span id="GeographicalCoordinateID">GeographicalCoordinateID</span> | xsd:token | The unique identifier for this geographical coordinate. | UN01003623 | Geographical Coordinate. Identification. Identifier
<span id="GeographicalCoordinateUsedGeographicalCoordinateSourceSystem">GeographicalCoordinateUsedGeographicalCoordinateSourceSystem</span> | [edi3:CoordinateSourceSystem](#CoordinateSourceSystem) | The geographical coordinate source system used for this geographical coordinate. | UN01013614 | Geographical Coordinate. Used. Geographical_ Coordinate Source System
<span id="GeographicalCoordinateAltitude">GeographicalCoordinateAltitude</span> | xsd:decimal | The measure of the altitude that reflects the vertical elevation of an object above a surface for this geographical coordinate (Reference ISO 6709). | UN01003617 | Geographical Coordinate. Altitude. Measure
<span id="AlternativeSourceSystemID">AlternativeSourceSystemID</span> | xsd:token | An alternative source system identifier for this geographical coordinate. | UN01013612 | Geographical Coordinate. Alternative Source System. Identifier
<span id="GeographicalCoordinateLongitude">GeographicalCoordinateLongitude</span> | xsd:decimal | The measure of the longitude as an angular distance east or west from the Greenwich meridian to the meridian of a specific place (Reference ISO 6709). | UN01003619 | Geographical Coordinate. Longitude. Measure
<span id="TimeZoneCode">TimeZoneCode</span> | xsd:token | The code specifying the time zone of this geographical coordinate. | UN01013466 | Geographical Coordinate. Time Zone. Code
<span id="GeographicalCoordinateLatitude">GeographicalCoordinateLatitude</span> | xsd:decimal | The measure of the latitude as an angular distance north or south from the Equator meridian to the meridian of a specific place for this geographical coordinate (Reference ISO 6709). | UN01003618 | Geographical Coordinate. Latitude. Measure
<span id="GeographicalCoordinateAcquisitionDateTime">GeographicalCoordinateAcquisitionDateTime</span> | xsd:dateTime | The date, time, date time or other date time value of the acquisition of this geographical coordinate. | UN01013611 | Geographical Coordinate. Acquisition. Date Time


<h1 id="Production">Production</h1>

Type: rdf:Class

Definition: The making or manufacturing of goods, such as from components or raw materials.

Unique UN Assigned ID: UN01012676

Dictionary Entry Name: Goods_ Production. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="ManufacturingProcessDescription">ManufacturingProcessDescription</span> | xsd:string | A textual description of the manufacturing process for this goods production. | UN01012678 | Goods_ Production. Manufacturing Process_ Description. Text


<h1 id="TransportMovement">TransportMovement</h1>

Type: rdf:Class

Definition: The conveyance (physical carriage) of goods or other objects used for logistics transport purposes.

Unique UN Assigned ID: UN01003837

Dictionary Entry Name: Logistics_ Transport Movement. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="TerminalOperatorAssignedID">TerminalOperatorAssignedID</span> | xsd:token | A unique identifier for this logistics transport movement as assigned by a terminal operator. | UN01003844 | Logistics_ Transport Movement. Terminal Operator Assigned_ Identification. Identifier
<span id="CrewQuantity">CrewQuantity</span> | xsd:decimal | The number of crew members for this logistics transport movement. | UN01003850 | Logistics_ Transport Movement. Crew. Quantity
<span id="CrewNationalityCountry">CrewNationalityCountry</span> | [edi3:Country](#Country) | Crew nationality details for this logistics transport movement. | UN01010127 | Logistics_ Transport Movement. Crew Nationality. Trade_ Country
<span id="ISPSDocument">ISPSDocument</span> | [edi3:Document](#Document) | The International Ship and Port facility Security code (ISPS) document related to this transport movement. | UN01010128 | Logistics_ Transport Movement. ISPS_ Related. Referenced_ Document
<span id="StageCode">StageCode</span> | xsd:token | The code specifying the stage of this logistics transport movement. | UN01003838 | Logistics_ Transport Movement. Stage. Code
<span id="OnboardInventory">OnboardInventory</span> | [edi3:StoresItemInventory](#StoresItemInventory) | A stores inventory item held onboard for this logistics transport movement. | UN01013176 | Logistics_ Transport Movement. Onboard. Stores Item_ Inventory
<span id="ConsortiumCarrier">ConsortiumCarrier</span> | [edi3:TradeParty](#TradeParty) | A consortium carrier party for this logistics transport movement. | UN01003864 | Logistics_ Transport Movement. Consortium_ Carrier. Trade_ Party
<span id="TransportMovementID">TransportMovementID</span> | xsd:token | The unique identifier for this logistics transport movement, such as a voyage number, flight number, or trip number. | UN01003841 | Logistics_ Transport Movement. Identification. Identifier
<span id="TransportMovementTransportEquipmentQuantity">TransportMovementTransportEquipmentQuantity</span> | xsd:decimal | The number of pieces of transport equipment for this logistics transport movement. | UN01003851 | Logistics_ Transport Movement. Transport Equipment. Quantity
<span id="TransportMovementUnloadingEvent">TransportMovementUnloadingEvent</span> | [edi3:Event](#Event) | The unloading event during which goods will be or have been unloaded from the means of transport used for this logistics transport movement. | UN01003857 | Logistics_ Transport Movement. Unloading. Transport_ Event
<span id="TransportMovementTransportContractDocument">TransportMovementTransportContractDocument</span> | [edi3:Document](#Document) | A transport contract document related to this logistics transport movement. | UN01008986 | Logistics_ Transport Movement. Transport Contract_ Related. Referenced_ Document
<span id="ArrivalEvent">ArrivalEvent</span> | [edi3:Event](#Event) | An arrival event for this logistics transport movement. | UN01003858 | Logistics_ Transport Movement. Arrival. Transport_ Event
<span id="TransportMovementLoadingEvent">TransportMovementLoadingEvent</span> | [edi3:Event](#Event) | The loading event during which goods will be or have been loaded into or onto the means of transport used for this logistics transport movement. | UN01003856 | Logistics_ Transport Movement. Loading. Transport_ Event
<span id="TransportMovementLogisticsRiskAnalysisResult">TransportMovementLogisticsRiskAnalysisResult</span> | [edi3:RiskAnalysisResult](#RiskAnalysisResult) | A result of a logistics risk analysis calculation specified for this transport movement. | UN01013052 | Logistics_ Transport Movement. Specified. Logistics_ Risk Analysis Result
<span id="UnloadingInspectionInstructions">UnloadingInspectionInstructions</span> | [edi3:TransportInstructions](#TransportInstructions) | Unloading inspection instructions specified for this logistics transport movement. | UN01003881 | Logistics_ Transport Movement. Unloading Inspection_ Specified. Transport_ Instructions
<span id="TransportMovementCarrier">TransportMovementCarrier</span> | [edi3:TradeParty](#TradeParty) | A carrier party for this logistics transport movement. | UN01003863 | Logistics_ Transport Movement. Carrier. Trade_ Party
<span id="LoadingInspectionParty">LoadingInspectionParty</span> | [edi3:TradeParty](#TradeParty) | The loading inspection party for this logistics transport movement. | UN01003870 | Logistics_ Transport Movement. Loading_ Inspection. Trade_ Party
<span id="TradedParcelQuantity">TradedParcelQuantity</span> | xsd:decimal | The number of traded parcels of cargo being transported in this logistics transport movement. | UN01003852 | Logistics_ Transport Movement. Traded Parcel. Quantity
<span id="SailingAdviceNotifiedParty">SailingAdviceNotifiedParty</span> | [edi3:TradeParty](#TradeParty) | A party to be notified of the sailing advice for this logistics transport movement. | UN01003875 | Logistics_ Transport Movement. Sailing Advice_ Notified. Trade_ Party
<span id="ManifestOnboardIndicator">ManifestOnboardIndicator</span> | xsd:boolean | The indication of whether or not the manifest for this logistics transport movement is onboard. | UN01010122 | Logistics_ Transport Movement. Manifest Onboard. Indicator
<span id="PassengerQuantity">PassengerQuantity</span> | xsd:decimal | The number of passengers for this logistics transport movement. | UN01003849 | Logistics_ Transport Movement. Passenger. Quantity
<span id="ModeText">ModeText</span> | xsd:string | The mode, expressed as text, of this logistics transport movement. | UN01003840 | Logistics_ Transport Movement. Mode. Text
<span id="TransportMovementSpecialInstructions">TransportMovementSpecialInstructions</span> | [edi3:TransportInstructions](#TransportInstructions) | Special transport instructions specified for this logistics transport movement. | UN01003880 | Logistics_ Transport Movement. Special_ Specified. Transport_ Instructions
<span id="Stevedore">Stevedore</span> | [edi3:TradeParty](#TradeParty) | A stevedore party for this logistics transport movement. | UN01003872 | Logistics_ Transport Movement. Stevedore. Trade_ Party
<span id="TradingConsolidatorAssignedID">TradingConsolidatorAssignedID</span> | xsd:token | The unique identifier for this logistics transport movement as assigned by the trading consolidator. | UN01003843 | Logistics_ Transport Movement. Trading Consolidator Assigned_ Identification. Identifier
<span id="CommodityConsolidatorAgent">CommodityConsolidatorAgent</span> | [edi3:TradeParty](#TradeParty) | The commodity consolidator agent party for this logistics transport movement. | UN01003868 | Logistics_ Transport Movement. Commodity Consolidator Agent. Trade_ Party
<span id="CallEvent">CallEvent</span> | [edi3:Event](#Event) | A call event for this logistics transport movement. | UN01010123 | Logistics_ Transport Movement. Call. Transport_ Event
<span id="ServiceText">ServiceText</span> | xsd:string | The service, expressed as text, of this logistics transport movement. | UN01012752 | Logistics_ Transport Movement. Service. Text
<span id="AssociatedConvoy">AssociatedConvoy</span> | [edi3:Convoy](#Convoy) | The convoy associated with this logistics transport movement. | UN01010124 | Logistics_ Transport Movement. Associated. Logistics_ Convoy
<span id="SpecifiedCalculatedEmission">SpecifiedCalculatedEmission</span> | [edi3:Emission](#Emission) | A calculated emission specified for this logistics transport movement. | UN01010129 | Logistics_ Transport Movement. Specified. Calculated_ Emission
<span id="CycleText">CycleText</span> | xsd:string | The cycle, as expressed as text, of this logistics transport movement, such as twice a day. | UN01012754 | Logistics_ Transport Movement. Cycle. Text
<span id="TransportMovementApplicableServiceCharge">TransportMovementApplicableServiceCharge</span> | [edi3:ServiceCharge](#ServiceCharge) | A service charge, such as a freight charge, applicable to this logistics transport movement. | UN01003862 | Logistics_ Transport Movement. Applicable. Logistics_ Service Charge
<span id="PassengerListDocument">PassengerListDocument</span> | [edi3:Document](#Document) | The passenger list document related to this logistics transport movement. | UN01010136 | Logistics_ Transport Movement. Passenger List_ Related. Referenced_ Document
<span id="CarriedInactiveTransportMeans">CarriedInactiveTransportMeans</span> | [edi3:TransportMeans](#TransportMeans) | Details of transport means inactively carried during the transport movement, such as trucks on a Roll-On/Roll-Off (RORO) ferry. | UN01010133 | Logistics_ Transport Movement. Carried Inactive. Referenced_ Transport Means
<span id="FirstArrivalEvent">FirstArrivalEvent</span> | [edi3:Event](#Event) | The first arrival event for this logistics transport movement. | UN01003859 | Logistics_ Transport Movement. First_ Arrival. Transport_ Event
<span id="CarriedGoodsCharacteristic">CarriedGoodsCharacteristic</span> | [edi3:GoodsCharacteristic](#GoodsCharacteristic) | Material characteristics of goods carried during this logistics transport movement. | UN01010131 | Logistics_ Transport Movement. Carried. Material_ Goods Characteristic
<span id="ShipToShipEvent">ShipToShipEvent</span> | [edi3:Event](#Event) | A ship to ship event for this logistics transport movement. | UN01013178 | Logistics_ Transport Movement. Ship To Ship. Transport_ Event
<span id="Event">Event</span> | [edi3:Event](#Event) | A transport event specified for this logistics transport movement. | UN01012569 | Logistics_ Transport Movement. Specified. Transport_ Event
<span id="CrewPerson">CrewPerson</span> | [edi3:TransportPerson](#TransportPerson) | A person who is a member of the crew of the means of transport used for this logistics transport movement. | UN01003855 | Logistics_ Transport Movement. Crew. Transport_ Person
<span id="SailingAdviceNotificationInformation">SailingAdviceNotificationInformation</span> | xsd:string | Sailing advice notification information, expressed as text, for this logistics transport movement. | UN01003853 | Logistics_ Transport Movement. Sailing Advice Notification_ Information. Text
<span id="BorderCrossingEvent">BorderCrossingEvent</span> | [edi3:Event](#Event) | A border crossing event for this logistics transport movement. | UN01010125 | Logistics_ Transport Movement. Border Crossing. Transport_ Event
<span id="ReportedSecurityInformation">ReportedSecurityInformation</span> | xsd:string | Reported security information, expressed as text, for this logistics transport movement. | UN01013172 | Logistics_ Transport Movement. Reported Security_ Information. Text
<span id="ScheduledID">ScheduledID</span> | xsd:token | A unique identifier for this logistics transport movement, such as a voyage number, flight number, or trip number, as stated in a schedule. | UN01003842 | Logistics_ Transport Movement. Scheduled_ Identification. Identifier
<span id="ModeCode">ModeCode</span> | xsd:token | The code specifying the mode, such as by air, sea, rail, road or inland waterway, for this logistics transport movement. | UN01003839 | Logistics_ Transport Movement. Mode. Code
<span id="ConsignmentQuantity">ConsignmentQuantity</span> | xsd:decimal | The number of consignments in this logistics transport movement. | UN01006136 | Logistics_ Transport Movement. Consignment. Quantity
<span id="PilotageExemptionID">PilotageExemptionID</span> | xsd:token | The identifier of a pilotage exemption for this logistics transport movement. | UN01010119 | Logistics_ Transport Movement. Pilotage Exemption. Identifier
<span id="CargoDescription">CargoDescription</span> | xsd:string | The textual description of the cargo for this logistics transport movement. | UN01010120 | Logistics_ Transport Movement. Cargo Description. Text
<span id="TerminalOperator">TerminalOperator</span> | [edi3:TradeParty](#TradeParty) | A terminal operator party for this logistics transport movement. | UN01003866 | Logistics_ Transport Movement. Terminal Operator. Trade_ Party
<span id="CallPurposeCode">CallPurposeCode</span> | xsd:token | A code specifying a call purpose for this logistics transport movement. | UN01013173 | Logistics_ Transport Movement. Call Purpose. Code
<span id="CrewListDocument">CrewListDocument</span> | [edi3:Document](#Document) | The crew list document related to this logistics transport movement. | UN01010135 | Logistics_ Transport Movement. Crew List_ Related. Referenced_ Document
<span id="ExcessTransportService">ExcessTransportService</span> | [edi3:Service](#Service) | An excess transport service for this logistics transport movement. | UN01008988 | Logistics_ Transport Movement. Excess Transport. Transport_ Service
<span id="BorderCrossingDateTime">BorderCrossingDateTime</span> | xsd:dateTime | A date, time, date time or other date time value when this logistics transport movement crosses a border. | UN01003847 | Logistics_ Transport Movement. Border Crossing. Date Time
<span id="DangerousGoodsIndicator">DangerousGoodsIndicator</span> | xsd:boolean | The indication of whether or not dangerous goods are carried for this logistics transport movement. | UN01010121 | Logistics_ Transport Movement. Dangerous Goods. Indicator
<span id="TransportMovementPackageQuantity">TransportMovementPackageQuantity</span> | xsd:decimal | The number of packages in this logistics transport movement. | UN01006137 | Logistics_ Transport Movement. Package. Quantity
<span id="LoadingInspectionInstructions">LoadingInspectionInstructions</span> | [edi3:TransportInstructions](#TransportInstructions) | Loading inspection instructions specified for this logistics transport movement. | UN01003882 | Logistics_ Transport Movement. Loading Inspection_ Specified. Transport_ Instructions
<span id="NVOCCCarrier">NVOCCCarrier</span> | [edi3:TradeParty](#TradeParty) | A Non-Vessel Operating Common Carrier (NVOCC) carrier party for this logistics transport movement. | UN01003865 | Logistics_ Transport Movement. NVOCC_ Carrier. Trade_ Party
<span id="TransportMovementTypeText">TransportMovementTypeText</span> | xsd:string | The type, as expressed as text, of the logistics transport movement. | UN01012753 | Logistics_ Transport Movement. Type. Text
<span id="UsedTransportMeans">UsedTransportMeans</span> | [edi3:LogisticsTransportMeans](#LogisticsTransportMeans) | The means of transport used for this logistics transport movement. | UN01003861 | Logistics_ Transport Movement. Used. Logistics_ Transport Means
<span id="TransportMovementSpecifiedInstructions">TransportMovementSpecifiedInstructions</span> | [edi3:HandlingInstructions](#HandlingInstructions) | Handling instructions specified for this logistics transport movement. | UN01010132 | Logistics_ Transport Movement. Specified. Handling_ Instructions
<span id="TransportMovementInformation">TransportMovementInformation</span> | xsd:string | Information, expressed as text, for this logistics transport movement. | UN01006193 | Logistics_ Transport Movement. Information. Text
<span id="TransitDirectionCode">TransitDirectionCode</span> | xsd:token | The code specifying the transit direction of this logistics transport movement. | UN01003848 | Logistics_ Transport Movement. Transit Direction. Code
<span id="UnloadingInspectionParty">UnloadingInspectionParty</span> | [edi3:TradeParty](#TradeParty) | The inspection party for the unloading of this logistics transport movement. | UN01003871 | Logistics_ Transport Movement. Unloading_ Inspection. Trade_ Party
<span id="CommodityConsolidator">CommodityConsolidator</span> | [edi3:TradeParty](#TradeParty) | The commodity consolidator party for this logistics transport movement. | UN01003867 | Logistics_ Transport Movement. Commodity Consolidator. Trade_ Party
<span id="TransportMovementCarrierAgent">TransportMovementCarrierAgent</span> | [edi3:TradeParty](#TradeParty) | The carrier agent trade party for this logistics transport movement. | UN01010130 | Logistics_ Transport Movement. Carrier Agent. Trade_ Party
<span id="InspectionParty">InspectionParty</span> | [edi3:TradeParty](#TradeParty) | An inspection party for this logistics transport movement. | UN01003869 | Logistics_ Transport Movement. Inspection. Trade_ Party
<span id="StayID">StayID</span> | xsd:token | The unique identifier of a stay in a port, airport or other place of service for this logistics transport movement. | UN01003845 | Logistics_ Transport Movement. Stay. Identifier
<span id="DocumentaryInstructionsNotifiedParty">DocumentaryInstructionsNotifiedParty</span> | [edi3:TradeParty](#TradeParty) | A party to be notified of the documentary instructions for this logistics transport movement. | UN01003874 | Logistics_ Transport Movement. Documentary Instructions_ Notified. Trade_ Party
<span id="LiftingInstructions">LiftingInstructions</span> | [edi3:Document](#Document) | A referenced lifting instructions document related to this logistics transport movement. | UN01003878 | Logistics_ Transport Movement. Lifting Instructions_ Related. Referenced_ Document
<span id="ServiceCode">ServiceCode</span> | xsd:token | The code specifying the service of this logistics transport movement, such as regular, milk run or spot service. | UN01012751 | Logistics_ Transport Movement. Service. Code
<span id="ClosingDateTime">ClosingDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value by which cargo should be loaded onto the means of transport for the departure of this logistics transport movement. | UN01003846 | Logistics_ Transport Movement. Closing. Date Time
<span id="Master">Master</span> | [edi3:TransportPerson](#TransportPerson) | The person legally responsible for the operation of the means of transport used for this logistics transport movement. | UN01003854 | Logistics_ Transport Movement. Master_ Responsible. Transport_ Person
<span id="TransportMovementNotifiedParty">TransportMovementNotifiedParty</span> | [edi3:TradeParty](#TradeParty) | A party to be notified about this logistics transport movement. | UN01003873 | Logistics_ Transport Movement. Notified. Trade_ Party
<span id="TransportMovementManifestDocument">TransportMovementManifestDocument</span> | [edi3:Document](#Document) | A referenced manifest document related to this transport movement. | UN01003879 | Logistics_ Transport Movement. Manifest_ Related. Referenced_ Document
<span id="CrewPersonalEffects">CrewPersonalEffects</span> | [edi3:PersonalEffects](#PersonalEffects) | Personal effects of an individual member of the crew for this logistics transport movement. | UN01013175 | Logistics_ Transport Movement. Crew. Specified_ Personal Effects
<span id="TransportMovementName">TransportMovementName</span> | xsd:string | The name, expressed as text, for this logistics transport movement. | UN01013604 | Logistics_ Transport Movement. Name. Text
<span id="OnboardPerson">OnboardPerson</span> | [edi3:TransportPerson](#TransportPerson) | A person onboard this logistics transport movement. | UN01013174 | Logistics_ Transport Movement. Onboard. Transport_ Person
<span id="TransportMeansSecurityOfficerPerson">TransportMeansSecurityOfficerPerson</span> | [edi3:TransportPerson](#TransportPerson) | The officer responsible for the security of the means of transport used for this logistics transport movement. | UN01010134 | Logistics_ Transport Movement. Transport Means Security Officer. Transport_ Person
<span id="ItineraryRoute">ItineraryRoute</span> | [edi3:Route](#Route) | A route in the itinerary of this logistics transport movement. | UN01003877 | Logistics_ Transport Movement. Itinerary. Transport_ Route
<span id="ReportedWasteMaterial">ReportedWasteMaterial</span> | [edi3:TransportWasteMaterial](#TransportWasteMaterial) | Waste material reported for this logistics transport movement. | UN01013177 | Logistics_ Transport Movement. Reported. Transport Waste_ Material
<span id="PassengerNationalityCountry">PassengerNationalityCountry</span> | [edi3:Country](#Country) | Passenger nationality details for this logistics transport movement. | UN01010126 | Logistics_ Transport Movement. Passenger Nationality. Trade_ Country
<span id="DepartureEvent">DepartureEvent</span> | [edi3:Event](#Event) | A departure event during this logistics transport movement. | UN01003860 | Logistics_ Transport Movement. Departure. Transport_ Event
<span id="ApplicableRegulatoryProcedure">ApplicableRegulatoryProcedure</span> | [edi3:RegulatoryProcedure](#RegulatoryProcedure) | A cross-border regulatory procedure applicable to this logistics transport movement. | UN01006187 | Logistics_ Transport Movement. Applicable. Cross-Border_ Regulatory Procedure


<h1 id="Convoy">Convoy</h1>

Type: rdf:Class

Definition: A number of means of transport following each other with a common logistics purpose.

Unique UN Assigned ID: UN01010068

Dictionary Entry Name: Logistics_ Convoy. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="OverallLength">OverallLength</span> | xsd:decimal | The overall length measure of this logistics convoy. | UN01010070 | Logistics_ Convoy. Overall_ Length. Measure
<span id="PowerActiveTransportMeans">PowerActiveTransportMeans</span> | [edi3:LogisticsTransportMeans](#LogisticsTransportMeans) | A means of transport actively powering this logistics convoy. | UN01010072 | Logistics_ Convoy. Power Active. Logistics_ Transport Means
<span id="MaximumWidth">MaximumWidth</span> | xsd:decimal | The maximum width measure for this logistics convoy. | UN01010071 | Logistics_ Convoy. Maximum_ Width. Measure
<span id="NumberOfTransportMeans">NumberOfTransportMeans</span> | xsd:decimal | The number of means of transport in this logistics convoy. | UN01010069 | Logistics_ Convoy. Transport Means. Quantity


<h1 id="Polygon">Polygon</h1>

Type: rdf:Class

Definition: A planar surface, defined by one exterior boundary and zero or more interior boundaries. Each interior boundary defines a hole in the polygon.

Unique UN Assigned ID: UN01010475

Dictionary Entry Name: Specified_ Polygon. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="InteriorLinearRing">InteriorLinearRing</span> | [edi3:LinearRing](#LinearRing) | An interior linear ring specified for this polygon. | UN01010476 | Specified_ Polygon. Interior. Specified_ Linear Ring
<span id="ExteriorLinearRing">ExteriorLinearRing</span> | [edi3:LinearRing](#LinearRing) | The exterior linear specified ring for this polygon. | UN01010477 | Specified_ Polygon. Exterior. Specified_ Linear Ring
<span id="PolygonAssociatedLogisticsLocation">PolygonAssociatedLogisticsLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | A logistics location associated with this specified polygon. | UN01013627 | Specified_ Polygon. Associated. Logistics_ Location


<h1 id="HeaderBalanceOut">HeaderBalanceOut</h1>

Type: rdf:Class

Definition: Offset header information to ensure that debits and credits are equal for a transaction.

Unique UN Assigned ID: UN01011539

Dictionary Entry Name: Header_ Balance Out. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="HeaderBalanceOutReasonCode">HeaderBalanceOutReasonCode</span> | xsd:token | The code specifying the reason for this header balance out. | UN01011542 | Header_ Balance Out. Reason. Code
<span id="HeaderBalanceOutReasonDescription">HeaderBalanceOutReasonDescription</span> | xsd:string | A textual description of the reason for this header balance out. | UN01011543 | Header_ Balance Out. Reason Description. Text
<span id="HeaderBalanceOutCalculatedAmount">HeaderBalanceOutCalculatedAmount</span> | xsd:decimal | A monetary value calculated for this header balance out. | UN01011545 | Header_ Balance Out. Calculated. Amount
<span id="BreakdownBalanceOut">BreakdownBalanceOut</span> | [edi3:HeaderBalanceOut](#HeaderBalanceOut) | A balance out breakdown of this header balance out. | UN01011546 | Header_ Balance Out. Breakdown. Header_ Balance Out
<span id="HeaderBalanceOutOccurrenceDateTime">HeaderBalanceOutOccurrenceDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value of an occurrence of this header balance out. | UN01011544 | Header_ Balance Out. Occurrence. Date Time
<span id="HeaderBalanceOutDescription">HeaderBalanceOutDescription</span> | xsd:string | A textual description of this header balance out. | UN01011541 | Header_ Balance Out. Description. Text


<h1 id="PaymentBalanceOut">PaymentBalanceOut</h1>

Type: rdf:Class

Definition: Offset information to ensure that debits and credits are equal for a transaction.

Unique UN Assigned ID: UN01011829

Dictionary Entry Name: Payment_ Balance Out. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="PaymentBalanceOutID">PaymentBalanceOutID</span> | xsd:token | The identifier for this payment balance out. | UN01011830 | Payment_ Balance Out. Identification. Identifier
<span id="PaymentBalanceOutDescription">PaymentBalanceOutDescription</span> | xsd:string | A textual description of this payment balance out. | UN01011831 | Payment_ Balance Out. Description. Text
<span id="PaymentBalanceOutCalculatedAmount">PaymentBalanceOutCalculatedAmount</span> | xsd:decimal | A monetary value calculated for this payment balance out. | UN01011835 | Payment_ Balance Out. Calculated. Amount
<span id="PaymentBalanceOutReasonCode">PaymentBalanceOutReasonCode</span> | xsd:token | The code specifying the reason for this payment balance out. | UN01011832 | Payment_ Balance Out. Reason. Code
<span id="PaymentBalanceOutReasonDescription">PaymentBalanceOutReasonDescription</span> | xsd:string | A textual description of the reason for this payment balance out. | UN01011833 | Payment_ Balance Out. Reason Description. Text


<h1 id="Route">Route</h1>

Type: rdf:Class

Definition: A way or course taken from one location to another for the purpose of transporting cargo and or passengers.

Unique UN Assigned ID: UN01004822

Dictionary Entry Name: Transport_ Route. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="RouteStatusCode">RouteStatusCode</span> | xsd:token | The code specifying a status for a transport route, such as planned or actual. | UN01011530 | Transport_ Route. Status. Code
<span id="FrequencyTypeCode">FrequencyTypeCode</span> | xsd:token | The code specifying the type of frequency for this transport route, such as weekly, bi-monthly or daily. | UN01004828 | Transport_ Route. Frequency Type. Code
<span id="ItineraryStopEvent">ItineraryStopEvent</span> | [edi3:Event](#Event) | An itinerary stop event for this transport route, such as a port call in a vessel schedule. | UN01004829 | Transport_ Route. Itinerary Stop. Transport_ Event
<span id="RouteSecurityLevelCode">RouteSecurityLevelCode</span> | xsd:token | A code specifying a security level for this transport route. | UN01013151 | Transport_ Route. Security Level. Code
<span id="DeparturePointText">DeparturePointText</span> | xsd:string | A departure point, expressed as text, for this transport route. | UN01004825 | Transport_ Route. Departure Point. Text
<span id="MapBinaryObject">MapBinaryObject</span> | xsd:base64Binary | Binary object data that is the map of this transport route. | UN01004826 | Transport_ Route. Map. Binary Object
<span id="TransportSpecifiedPeriod">TransportSpecifiedPeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The specified period during which this transport route is scheduled. | UN01004831 | Transport_ Route. Scheduled. Specified_ Period
<span id="RouteDescription">RouteDescription</span> | xsd:string | The textual description of this transport route. | UN01004824 | Transport_ Route. Description. Text
<span id="RouteTypeText">RouteTypeText</span> | xsd:string | A type, expressed as text for this transport route. | UN01013605 | Transport_ Route. Type. Text
<span id="TransportMeansText">TransportMeansText</span> | xsd:string | A means of transport, expressed as text, for this transport route. | UN01004827 | Transport_ Route. Transport Means. Text
<span id="FrequencyEffectivePeriod">FrequencyEffectivePeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | A specified period of time for which a frequency is effective for this transport route. | UN01004832 | Transport_ Route. Frequency Effective. Specified_ Period


<h1 id="CountrySubDivision">CountrySubDivision</h1>

Type: rdf:Class

Definition: A political or physical area or region within the political boundaries of a country used or referenced for trade purposes.

Unique UN Assigned ID: UN01002561

Dictionary Entry Name: Trade_ Country Sub-Division. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="SuperordinateCountrySubDivision">SuperordinateCountrySubDivision</span> | [edi3:CountrySubDivision](#CountrySubDivision) | A superordinate country sub-division for this trade country sub-division. | UN01002566 | Trade_ Country Sub-Division. Superordinate. Trade_ Country Sub-Division
<span id="CountrySubDivisionName">CountrySubDivisionName</span> | xsd:string | A name, expressed as text, of this trade country sub-division. | UN01002563 | Trade_ Country Sub-Division. Name. Text
<span id="AuthorizedActivityParty">AuthorizedActivityParty</span> | [edi3:TradeParty](#TradeParty) | A party that is authorized to perform an activity in this trade country sub-division. | UN01004575 | Trade_ Country Sub-Division. Activity_ Authorized. Trade_ Party
<span id="SubordinateCountrySubDivision">SubordinateCountrySubDivision</span> | [edi3:CountrySubDivision](#CountrySubDivision) | A subordinate country sub-division within this trade country sub-division. | UN01002567 | Trade_ Country Sub-Division. Subordinate. Trade_ Country Sub-Division
<span id="FunctionTypeCode">FunctionTypeCode</span> | xsd:token | The code specifying the function type of this trade country sub-division. | UN01002565 | Trade_ Country Sub-Division. Function_ Type. Code
<span id="HierarchicalLevelCode">HierarchicalLevelCode</span> | xsd:token | The code specifying the hierarchical level of this trade country sub-division. | UN01002564 | Trade_ Country Sub-Division. Hierarchical Level. Code


<h1 id="GoodsCharacteristic">GoodsCharacteristic</h1>

Type: rdf:Class

Definition: A distinctive feature of a material contained within physical goods.

Unique UN Assigned ID: UN01003884

Dictionary Entry Name: Material_ Goods Characteristic. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="GoodsCharacteristicTypeCode">GoodsCharacteristicTypeCode</span> | xsd:token | The code specifying the type of material goods characteristic. | UN01003886 | Material_ Goods Characteristic. Type. Code
<span id="ConstituentPercent">ConstituentPercent</span> | xsd:decimal | The percentage presence of the material within the goods for this material goods characteristic. | UN01003887 | Material_ Goods Characteristic. Proportional_ Constituent. Percent
<span id="AbsolutePresenceVolume">AbsolutePresenceVolume</span> | xsd:decimal | The volume measure of the absolute presence of this material goods characteristic. | UN01003889 | Material_ Goods Characteristic. Absolute Presence_ Volume. Measure
<span id="GoodsCharacteristicDescription">GoodsCharacteristicDescription</span> | xsd:string | A textual description of this material goods characteristic. | UN01003885 | Material_ Goods Characteristic. Description. Text


<h1 id="Circle">Circle</h1>

Type: rdf:Class

Definition: A planar surface specified as one completely round flat shape in the mathematical sense.

Unique UN Assigned ID: UN01013577

Dictionary Entry Name: Specified_ Circle. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="CircleGeographicalObjectCharacteristic">CircleGeographicalObjectCharacteristic</span> | [edi3:GeographicalObjectCharacteristic](#GeographicalObjectCharacteristic) | The geographical object characteristic associated with this specified circle. | UN01013580 | Specified_ Circle. Associated. Specified_ Geographical Object Characteristic
<span id="RadiusMeasure">RadiusMeasure</span> | xsd:decimal | The measure of the radius for this specified circle. | UN01013578 | Specified_ Circle. Radius. Measure
<span id="CircleAssociatedLogisticsLocation">CircleAssociatedLogisticsLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | A logistics location associated with this specified circle. | UN01013581 | Specified_ Circle. Associated. Logistics_ Location


<h1 id="TestSpecificationReport">TestSpecificationReport</h1>

Type: rdf:Class

Definition: A report that specifies a certification test and its attributes.

Unique UN Assigned ID: UN01009034

Dictionary Entry Name: Certification_ Test Specification Report. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="ResultText">ResultText</span> | xsd:string | A result, expressed as text, reported in this certification test specification report. | UN01009036 | Certification_ Test Specification Report. Result. Text
<span id="StandardName">StandardName</span> | xsd:string | The name, expressed as text, of the standard applicable for this certification test specification report. | UN01009037 | Certification_ Test Specification Report. Standard Name. Text


<h1 id="Characteristic">Characteristic</h1>

Type: rdf:Class

Definition: A prominent attribute or aspect of a product.

Unique UN Assigned ID: UN01003971

Dictionary Entry Name: Product_ Characteristic. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="CharacteristicValueMeasure">CharacteristicValueMeasure</span> | xsd:decimal | A measure of a value for this product characteristic. | UN01003975 | Product_ Characteristic. Value. Measure
<span id="CharacteristicValueCode">CharacteristicValueCode</span> | xsd:token | The code specifying the value of this product characteristic. | UN01008304 | Product_ Characteristic. Value. Code
<span id="ValueBinaryFile">ValueBinaryFile</span> | [edi3:BinaryFile](#BinaryFile) | The value for this product characteristic expressed in a binary file. | UN01008307 | Product_ Characteristic. Value. Specified_ Binary File
<span id="ApplicableCondition">ApplicableCondition</span> | [edi3:Condition](#Condition) | A condition applicable to this product characteristic. | UN01008308 | Product_ Characteristic. Applicable. Product Characteristic_ Condition
<span id="MeasurementMethodCode">MeasurementMethodCode</span> | xsd:token | A code specifying a measurement method for this product characteristic. | UN01003976 | Product_ Characteristic. Measurement Method. Code
<span id="ContentTypeCode">ContentTypeCode</span> | xsd:token | A code specifying the content type of this product characteristic. | UN01011085 | Product_ Characteristic. Content_ Type. Code
<span id="CharacteristicTypeCode">CharacteristicTypeCode</span> | xsd:token | A code specifying a type of product characteristic. | UN01003973 | Product_ Characteristic. Type. Code
<span id="CharacteristicValueText">CharacteristicValueText</span> | xsd:string | A value, expressed as text, for this product characteristic. | UN01004900 | Product_ Characteristic. Value. Text
<span id="ValueDateTime">ValueDateTime</span> | xsd:dateTime | The value for this product characteristic expressed as a date, time, date time, or other date time value. | UN01008305 | Product_ Characteristic. Value. Date Time
<span id="CharacteristicDescription">CharacteristicDescription</span> | xsd:string | A textual description of this product characteristic. | UN01003974 | Product_ Characteristic. Description. Text
<span id="ValueIndicator">ValueIndicator</span> | xsd:boolean | The value for this product characteristic expressed as an indicator. | UN01008306 | Product_ Characteristic. Value. Indicator
<span id="CharacteristicApplicableReferencedStandard">CharacteristicApplicableReferencedStandard</span> | [edi3:Standard](#Standard) | The referenced standard that is applicable to this product characteristic. | UN01008309 | Product_ Characteristic. Applicable. Referenced_ Standard


<h1 id="AvailablePeriod">AvailablePeriod</h1>

Type: rdf:Class

Definition: A specific period of time such as the length of time between two known date/time points, from a start date onwards, or up to an end date for which something is available.

Unique UN Assigned ID: UN01005108

Dictionary Entry Name: Available_ Period. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="AvailablePeriodStartDateTime">AvailablePeriodStartDateTime</span> | xsd:dateTime | The date, time, date time or other date time value for the start of this available period of time. | UN01005109 | Available_ Period. Start. Date Time
<span id="AvailablePeriodDescription">AvailablePeriodDescription</span> | xsd:string | The textual description of this available period. | UN01005111 | Available_ Period. Description. Text


<h1 id="SpecifiedPeriod">SpecifiedPeriod</h1>

Type: rdf:Class

Definition: A specified period of time.

Unique UN Assigned ID: UN01001270

Dictionary Entry Name: Specified_ Period. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="OpenIndicator">OpenIndicator</span> | xsd:boolean | The indication of whether or not an entity is open during this specified period. | UN01001277 | Specified_ Period. Open. Indicator
<span id="SpecifiedPeriodStartDateTime">SpecifiedPeriodStartDateTime</span> | xsd:dateTime | The date, time, date time or other date time value for the start of this specified period of time. | UN01001274 | Specified_ Period. Start. Date Time
<span id="SpecifiedPeriodSequenceNumber">SpecifiedPeriodSequenceNumber</span> | xsd:decimal | A sequence number for this specified period. | UN01004084 | Specified_ Period. Sequence. Numeric
<span id="SpecifiedPeriodEndDateTime">SpecifiedPeriodEndDateTime</span> | xsd:dateTime | The date, time, date time or other date time value for the end of this specified period of time. | UN01001275 | Specified_ Period. End. Date Time
<span id="DurationMeasure">DurationMeasure</span> | xsd:decimal | A measure of the length of time for this specified time period such as hours, days, weeks, months, years. | UN01001271 | Specified_ Period. Duration. Measure
<span id="SpecifiedPeriodID">SpecifiedPeriodID</span> | xsd:token | The unique identifier of this specified period. | UN01001279 | Specified_ Period. Identification. Identifier
<span id="ContinuousIndicator">ContinuousIndicator</span> | xsd:boolean | The indication of whether or not this specified period is continuous. | UN01004086 | Specified_ Period. Continuous. Indicator
<span id="SpecifiedPeriodDescription">SpecifiedPeriodDescription</span> | xsd:string | A textual description of this specified period of time. | UN01001273 | Specified_ Period. Description. Text
<span id="SpecifiedPeriodPurposeCode">SpecifiedPeriodPurposeCode</span> | xsd:token | The code specifying the purpose of this specified period. | UN01009047 | Specified_ Period. Purpose. Code
<span id="SpecifiedPeriodName">SpecifiedPeriodName</span> | xsd:string | A name, expressed as text, of this specified period. | UN01004083 | Specified_ Period. Name. Text
<span id="InclusiveIndicator">InclusiveIndicator</span> | xsd:boolean | The indication of whether or not the start and end dates are included in this specified period. | UN01001272 | Specified_ Period. Inclusive. Indicator
<span id="StartDateFlexibilityCode">StartDateFlexibilityCode</span> | xsd:token | The code specifying the flexibility of the start date of this specified period. | UN01004085 | Specified_ Period. Start Date Flexibility. Code
<span id="SpecifiedPeriodSeasonCode">SpecifiedPeriodSeasonCode</span> | xsd:token | The code specifying the season for this specified period. | UN01001278 | Specified_ Period. Season. Code


<h1 id="SupplyChainTradeLineItem">SupplyChainTradeLineItem</h1>

Type: rdf:Class

Definition: A collection of information specific to an item being used or reported on for supply chain trade purposes.

Unique UN Assigned ID: UN01004417

Dictionary Entry Name: Supply Chain_ Trade Line Item. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="SpecifiedGoodsProduction">SpecifiedGoodsProduction</span> | [edi3:Production](#Production) | A production of goods specified for this supply chain trade line Item. | UN01012685 | Supply Chain_ Trade Line Item. Specified. Goods_ Production
<span id="SupplyChainTradeLineItemID">SupplyChainTradeLineItemID</span> | xsd:token | The unique identifier for this supply chain trade line item. | UN01004418 | Supply Chain_ Trade Line Item. Identification. Identifier
<span id="TypeExtensionCode">TypeExtensionCode</span> | xsd:token | The code used as an extension to the type code for further specifying a type of supply chain trade line item. | UN01004422 | Supply Chain_ Trade Line Item. Type Extension. Code
<span id="SupplyChainTradeLineItemTypeCode">SupplyChainTradeLineItemTypeCode</span> | xsd:token | The code specifying the type of supply chain trade line item. | UN01004421 | Supply Chain_ Trade Line Item. Type. Code
<span id="SubstituteProduct">SubstituteProduct</span> | [edi3:Product](#Product) | A referenced substitute product applicable for this supply chain trade line item. | UN01007230 | Supply Chain_ Trade Line Item. Substitute_ Applicable. Referenced_ Product
<span id="InvoiceReferencedDocument">InvoiceReferencedDocument</span> | [edi3:Document](#Document) | An invoice document associated to this supply chain trade line item. | UN01013311 | Supply Chain_ Trade Line Item. Invoice_ Associated. Referenced_ Document
<span id="SupplyChainTradeLineItemReferencedDocument">SupplyChainTradeLineItemReferencedDocument</span> | [edi3:Document](#Document) | A document referenced for this supply chain trade line item. | UN01011126 | Supply Chain_ Trade Line Item. Reference. Referenced_ Document
<span id="SupplyChainLineTradeAgreement">SupplyChainLineTradeAgreement</span> | [edi3:LineTradeAgreement](#LineTradeAgreement) | The line trade agreement specified for this supply chain trade line item. | UN01011862 | Supply Chain_ Trade Line Item. Specified. Line_ Trade Agreement
<span id="BarcodeID">BarcodeID</span> | xsd:token | A unique barcode identifier for this supply chain trade line item. | UN01004420 | Supply Chain_ Trade Line Item. Barcode_ Identification. Identifier
<span id="AssertedAuthentication">AssertedAuthentication</span> | [edi3:Authentication](#Authentication) | A document authentication asserted for this supply chain trade line item. | UN01004426 | Supply Chain_ Trade Line Item. Asserted. Document_ Authentication
<span id="SupplyChainTradeLineItemLogisticsPackage">SupplyChainTradeLineItemLogisticsPackage</span> | [edi3:Package](#Package) | A physical logistics package for this supply chain trade line item. | UN01005348 | Supply Chain_ Trade Line Item. Physical. Logistics_ Package
<span id="SupplyChainTradeLineItemAssociatedDocumentLine">SupplyChainTradeLineItemAssociatedDocumentLine</span> | [edi3:DocumentLineDocument](#DocumentLineDocument) | The document line associated with this trade line item. | UN01004427 | Supply Chain_ Trade Line Item. Associated. Document Line_ Document
<span id="SupplyChainTradeLineItemTransportEquipment">SupplyChainTradeLineItemTransportEquipment</span> | [edi3:TransportEquipment](#TransportEquipment) | A piece of transport equipment associated with this supply chain trade line item. | UN01004425 | Supply Chain_ Trade Line Item. Associated. Logistics_ Transport Equipment
<span id="AdditionalID">AdditionalID</span> | xsd:token | An additional unique identifier for this supply chain trade line item. | UN01004419 | Supply Chain_ Trade Line Item. Additional_ Identification. Identifier
<span id="SupplyChainTradeLineItemTradeProduct">SupplyChainTradeLineItemTradeProduct</span> | [edi3:TradeProduct](#TradeProduct) | A product specified for this supply chain trade line item. | UN01004431 | Supply Chain_ Trade Line Item. Specified. Trade_ Product
<span id="SupplyChainSupplyChainSupplyChainTradeLineItemReferencedLogisticsPackage">SupplyChainSupplyChainSupplyChainTradeLineItemReferencedLogisticsPackage</span> | [edi3:ReferencedPackage](#ReferencedPackage) | A physical logistics package referenced for this supply chain trade line item. | UN01011865 | Supply Chain_ Trade Line Item. Physical. Referenced_ Logistics_ Package
<span id="SupplyChainSupplyChainSupplyChainTradeLineItemReferencedLogisticsPackage">SupplyChainSupplyChainSupplyChainTradeLineItemReferencedLogisticsPackage</span> | [edi3:Package](#Package) | A logistics package referenced in this supply chain trade line item. | UN01012984 | Supply Chain_ Trade Line Item. Referenced. Logistics_ Package
<span id="SupplyChainTradeLineItemSequenceNumber">SupplyChainTradeLineItemSequenceNumber</span> | xsd:decimal | A sequence number for this supply chain trade line item. | UN01009005 | Supply Chain_ Trade Line Item. Sequence. Numeric
<span id="SubstitutedProduct">SubstitutedProduct</span> | [edi3:Product](#Product) | A referenced product substituted for this supply chain trade line item. | UN01006722 | Supply Chain_ Trade Line Item. Substituted. Referenced_ Product
<span id="IncludedWithinConsignmentItem">IncludedWithinConsignmentItem</span> | [edi3:ConsignmentItem](#ConsignmentItem) | The consignment item within which this supply chain trade line item is included. | UN01004423 | Supply Chain_ Trade Line Item. Included Within. Supply Chain_ Consignment Item
<span id="ComponentProduct">ComponentProduct</span> | [edi3:Product](#Product) | A referenced component product applicable for this supply chain trade line item. | UN01007234 | Supply Chain_ Trade Line Item. Component_ Applicable. Referenced_ Product
<span id="SupplyChainLineTradeSettlement">SupplyChainLineTradeSettlement</span> | [edi3:LineTradeSettlement](#LineTradeSettlement) | A line trade settlement specified for this supply chain trade line item. | UN01011864 | Supply Chain_ Trade Line Item. Specified. Line_ Trade Settlement
<span id="ComplementaryProduct">ComplementaryProduct</span> | [edi3:Product](#Product) | A referenced complementary product applicable for this supply chain trade line item. | UN01007232 | Supply Chain_ Trade Line Item. Complementary_ Applicable. Referenced_ Product
<span id="SupplyChainLineTradeDelivery">SupplyChainLineTradeDelivery</span> | [edi3:LineTradeDelivery](#LineTradeDelivery) | The line trade delivery specified for this supply chain trade line item. | UN01011863 | Supply Chain_ Trade Line Item. Specified. Line_ Trade Delivery
<span id="IncludedSubordinateTradeLineItem">IncludedSubordinateTradeLineItem</span> | [edi3:SubordinateTradeLineItem](#SubordinateTradeLineItem) | A subordinate trade line item included in this supply chain trade line item. | UN01011866 | Supply Chain_ Trade Line Item. Included. Subordinate_ Trade Line Item
<span id="AdditionalProduct">AdditionalProduct</span> | [edi3:Product](#Product) | A referenced product additionally applicable with this supply chain trade line item. | UN01007233 | Supply Chain_ Trade Line Item. Additional_ Applicable. Referenced_ Product
<span id="AccessoryProduct">AccessoryProduct</span> | [edi3:Product](#Product) | A referenced accessory product applicable for this supply chain trade line item. | UN01007231 | Supply Chain_ Trade Line Item. Accessory_ Applicable. Referenced_ Product
<span id="SupplyChainTradeLineItemDescriptionCode">SupplyChainTradeLineItemDescriptionCode</span> | xsd:token | The code specifying a description of this supply chain trade line item. | UN01011941 | Supply Chain_ Trade Line Item. Description. Code
<span id="RequiredProduct">RequiredProduct</span> | [edi3:Product](#Product) | A required product applicable for this supply chain trade line item. | UN01008770 | Supply Chain_ Trade Line Item. Required_ Applicable. Referenced_ Product
<span id="SpecifiedRequisitionerTradeProduct">SpecifiedRequisitionerTradeProduct</span> | [edi3:TradeProduct](#TradeProduct) | The product specified by the requisitioner for this supply chain trade line item. | UN01013381 | Supply Chain_ Trade Line Item. Requisitioner_ Specified. Trade_ Product


<h1 id="SubordinateTradeLineItem">SubordinateTradeLineItem</h1>

Type: rdf:Class

Definition: A collection of information specific to a subordinate item being used or reported on for trade purposes.

Unique UN Assigned ID: UN01004098

Dictionary Entry Name: Subordinate_ Trade Line Item. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="SubordinateSubordinateLineTradeDelivery">SubordinateSubordinateLineTradeDelivery</span> | [edi3:SubordinateLineTradeDelivery](#SubordinateLineTradeDelivery) | The delivery specified for this subordinate trade line item. | UN01011857 | Subordinate_ Trade Line Item. Specified. Subordinate Line_ Trade Delivery
<span id="ApplicableProduct">ApplicableProduct</span> | [edi3:TradeProduct](#TradeProduct) | A product applicable for this subordinate trade line item. | UN01010015 | Subordinate_ Trade Line Item. Applicable. Trade_ Product
<span id="SubordinateReferencedProduct">SubordinateReferencedProduct</span> | [edi3:Product](#Product) | The referenced product specified for this subordinate trade line item. | UN01004102 | Subordinate_ Trade Line Item. Specified. Referenced_ Product
<span id="SubordinateTradeLineItemID">SubordinateTradeLineItemID</span> | xsd:token | A unique identifier for this subordinate trade line item. | UN01004099 | Subordinate_ Trade Line Item. Identification. Identifier
<span id="SubordinateSubordinateLineTradeAgreement">SubordinateSubordinateLineTradeAgreement</span> | [edi3:SubordinateLineTradeAgreement](#SubordinateLineTradeAgreement) | The trade agreement specified for this subordinate trade line item. | UN01011856 | Subordinate_ Trade Line Item. Specified. Subordinate Line_ Trade Agreement


<h1 id="Range">Range</h1>

Type: rdf:Class

Definition: A row, line or series, commonly used to express the difference between lowest and highest values.

Unique UN Assigned ID: UN01013524

Dictionary Entry Name: Specified_ Range. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="StartID">StartID</span> | xsd:token | The identifier of the start of this specified range. | UN01013526 | Specified_ Range. Start. Identifier
<span id="RangeTypeCode">RangeTypeCode</span> | xsd:token | The code specifying a type of this specified range. | UN01013525 | Specified_ Range. Type. Code
<span id="MaximumValueMeasure">MaximumValueMeasure</span> | xsd:decimal | The measure of the maximum value for this specified range. | UN01013529 | Specified_ Range. Maximum Value. Measure
<span id="TotalItemQuantity">TotalItemQuantity</span> | xsd:decimal | The total number of items in this specified range. | UN01013530 | Specified_ Range. Total Item. Quantity
<span id="MinimumValueMeasure">MinimumValueMeasure</span> | xsd:decimal | The measure of the minimum value for this specified range. | UN01013528 | Specified_ Range. Minimum Value. Measure


<h1 id="Certification">Certification</h1>

Type: rdf:Class

Definition: The process of certifying that a certain product has passed performance and quality assurance tests, or qualification requirements stipulated in regulations.

Unique UN Assigned ID: UN01008292

Dictionary Entry Name: Trade Product_ Certification. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="ResponsibleAgencyText">ResponsibleAgencyText</span> | xsd:string | The agency, expressed as text, responsible for this trade product certification. | UN01008294 | Trade Product_ Certification. Responsible Agency. Text
<span id="StandardText">StandardText</span> | xsd:string | The standard, expressed as text, for this trade product certification. | UN01008296 | Trade Product_ Certification. Standard. Text
<span id="AssertionText">AssertionText</span> | xsd:string | An assertion, expressed as text, for this trade product certification, such as that this product is free from peanuts. | UN01008295 | Trade Product_ Certification. Assertion. Text


<h1 id="InstalmentPayment">InstalmentPayment</h1>

Type: rdf:Class

Definition: A discharge of obligations in respect of funds or securities, transferred through one of several payments, between two or more parties.

Unique UN Assigned ID: UN01013272

Dictionary Entry Name: Instalment_ Payment. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="SpecifiedFinancingRequestResultDocument">SpecifiedFinancingRequestResultDocument</span> | [edi3:FinancingRequestResultDocument](#FinancingRequestResultDocument) | The financing request result document specified for this instalment payment. | UN01013276 | Instalment_ Payment. Specified. Financing Request Result_ Document
<span id="InstalmentPaymentDueDateTime">InstalmentPaymentDueDateTime</span> | xsd:dateTime | The due date for this instalment payment. | UN01013275 | Instalment_ Payment. Due. Date Time
<span id="SequenceID">SequenceID</span> | xsd:token | The sequence identifier for this instalment payment. | UN01013273 | Instalment_ Payment. Sequence. Identifier


<h1 id="AdvancePayment">AdvancePayment</h1>

Type: rdf:Class

Definition: A prepaid discharge of obligations in respect of funds or securities transferred between two or more parties.

Unique UN Assigned ID: UN01001295

Dictionary Entry Name: Advance_ Payment. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="AdvancePaymentPaidAmount">AdvancePaymentPaidAmount</span> | xsd:decimal | The monetary value of the funds or securities paid in this advance payment. | UN01001296 | Advance_ Payment. Paid. Amount
<span id="AdvancePaymentIncludedTax">AdvancePaymentIncludedTax</span> | [edi3:TradeTax](#TradeTax) | A tax included in this advance payment. | UN01012134 | Advance_ Payment. Included. Trade_ Tax


<h1 id="TradeSettlementPayment">TradeSettlementPayment</h1>

Type: rdf:Class

Definition: The specific discharge obligations in respect of funds or securities transferred between two or more parties as part of a trade settlement.

Unique UN Assigned ID: UN01008866

Dictionary Entry Name: Trade Settlement_ Payment. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="EndToEndID">EndToEndID</span> | xsd:token | The unique identifier for the end-to-end processing of this trade settlement payment, such as an identifier assigned by an initiating party to unambiguously identify the transaction. | UN01008867 | Trade Settlement_ Payment. End-To-End_ Identification. Identifier
<span id="SpecifiedPaymentTradeSettlement">SpecifiedPaymentTradeSettlement</span> | [edi3:PaymentTradeSettlement](#PaymentTradeSettlement) | A trade settlement payment specified for this trade settlement payment. | UN01011918 | Trade Settlement_ Payment. Specified. Payment_ Trade Settlement
<span id="InstructionID">InstructionID</span> | xsd:token | The unique identifier of the instruction for this trade settlement payment. | UN01008868 | Trade Settlement_ Payment. Instruction. Identifier
<span id="RequestedExecutionDateTime">RequestedExecutionDateTime</span> | xsd:dateTime | The date, time, date time or other date time value of the requested execution of this trade settlement payment. | UN01008869 | Trade Settlement_ Payment. Requested Execution. Date Time


<h1 id="LineTradeSettlement">LineTradeSettlement</h1>

Type: rdf:Class

Definition: The information, at a line level, that enables the reconciliation of a financial transaction with the item(s) that the financial transaction is intended to settle, for example a commercial invoice.

Unique UN Assigned ID: UN01011800

Dictionary Entry Name: Line_ Trade Settlement. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="LineTradeSettlementPayerReferenceText">LineTradeSettlementPayerReferenceText</span> | xsd:string | The payer reference, expressed as text, for this line trade settlement. | UN01011803 | Line_ Trade Settlement. Payer_ Reference. Text
<span id="LineTradeSettlementPaymentReferenceText">LineTradeSettlementPaymentReferenceText</span> | xsd:string | A payment reference, expressed as text, for this line trade settlement. | UN01011801 | Line_ Trade Settlement. Payment Reference. Text
<span id="ReferencedLineTradeTransaction">ReferencedLineTradeTransaction</span> | [edi3:LineTradeTransaction](#LineTradeTransaction) | A trade transaction referenced in this line trade settlement. | UN01011823 | Line_ Trade Settlement. Referenced. Line_ Trade Transaction
<span id="DocumentLine">DocumentLine</span> | [edi3:DocumentLineDocument](#DocumentLineDocument) | A document line associated with this line trade settlement. | UN01011821 | Line_ Trade Settlement. Associated. Document Line_ Document
<span id="LineTradeSettlementAccountsReceivable">LineTradeSettlementAccountsReceivable</span> | [edi3:AccountingAccount](#AccountingAccount) | A receivable accounting account specified for this line trade settlement. | UN01011817 | Line_ Trade Settlement. Receivable_ Specified. Trade_ Accounting Account
<span id="LineTradeSettlementLogisticsServiceCharge">LineTradeSettlementLogisticsServiceCharge</span> | [edi3:ServiceCharge](#ServiceCharge) | A logistics service charge specified for this line trade settlement. | UN01011810 | Line_ Trade Settlement. Specified. Logistics_ Service Charge
<span id="LineTradeSettlementAllowanceCharge">LineTradeSettlementAllowanceCharge</span> | [edi3:TradeAllowanceCharge](#TradeAllowanceCharge) | An allowance or charge specified for this line trade settlement. | UN01011808 | Line_ Trade Settlement. Specified. Trade_ Allowance Charge
<span id="LineTradeSettlementDiscountIndicator">LineTradeSettlementDiscountIndicator</span> | xsd:boolean | The indication of whether or not a discount applies to the item in this line trade settlement. | UN01011940 | Line_ Trade Settlement. Discount. Indicator
<span id="LineTradeSettlementPurchaseAccountingAccount">LineTradeSettlementPurchaseAccountingAccount</span> | [edi3:AccountingAccount](#AccountingAccount) | A purchase accounting account specified for this line trade settlement. | UN01011818 | Line_ Trade Settlement. Purchase_ Specified. Trade_ Accounting Account
<span id="LineTradeSettlementInvoiceDateTime">LineTradeSettlementInvoiceDateTime</span> | xsd:dateTime | The date, time, date time or other date time value of the invoice in this line trade settlement. | UN01013111 | Line_ Trade Settlement. Invoice. Date Time
<span id="LineTradeSettlementSalesAccountingAccount">LineTradeSettlementSalesAccountingAccount</span> | [edi3:AccountingAccount](#AccountingAccount) | A sales accounting account specified for this line trade settlement. | UN01011819 | Line_ Trade Settlement. Sales_ Specified. Trade_ Accounting Account
<span id="LineTradeSettlementTradeTax">LineTradeSettlementTradeTax</span> | [edi3:TradeTax](#TradeTax) | A tax applicable to this line trade settlement. | UN01011806 | Line_ Trade Settlement. Applicable. Trade_ Tax
<span id="LineTradeSettlementAdditionalDocument">LineTradeSettlementAdditionalDocument</span> | [edi3:Document](#Document) | An additional document referenced in this line trade settlement. | UN01011815 | Line_ Trade Settlement. Additional. Referenced_ Document
<span id="LineTradeSettlementSubtotalCalculatedTax">LineTradeSettlementSubtotalCalculatedTax</span> | [edi3:TradeTax](#TradeTax) | A tax subtotal calculated for this line trade settlement. | UN01011809 | Line_ Trade Settlement. Subtotal_ Calculated. Trade_ Tax
<span id="LineTradeSettlementBillingPeriod">LineTradeSettlementBillingPeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | A billing period specified for this line trade settlement. | UN01011807 | Line_ Trade Settlement. Billing. Specified_ Period
<span id="LineTradeSettlementInvoicee">LineTradeSettlementInvoicee</span> | [edi3:TradeParty](#TradeParty) | The party to whom an invoice is issued for this line trade settlement. | UN01011804 | Line_ Trade Settlement. Invoicee. Trade_ Party
<span id="LineTradeSettlementPayer">LineTradeSettlementPayer</span> | [edi3:TradeParty](#TradeParty) | The payer party for this line trade settlement. | UN01011805 | Line_ Trade Settlement. Payer. Trade_ Party
<span id="LineTradeSettlementPriceCurrencyCode">LineTradeSettlementPriceCurrencyCode</span> | xsd:token | The code specifying the price currency for this line trade settlement. | UN01013472 | Line_ Trade Settlement. Price_ Currency. Code
<span id="LineTradeSettlementFinancialAdjustment">LineTradeSettlementFinancialAdjustment</span> | [edi3:FinancialAdjustment](#FinancialAdjustment) | A financial adjustment specified for this line trade settlement. | UN01011813 | Line_ Trade Settlement. Specified. Financial_ Adjustment
<span id="LineTradeSettlementAssociatedDocument">LineTradeSettlementAssociatedDocument</span> | [edi3:Document](#Document) | A document associated with this line trade settlement. | UN01011822 | Line_ Trade Settlement. Associated. Referenced_ Document
<span id="LineTradeSettlementInvoiceDocument">LineTradeSettlementInvoiceDocument</span> | [edi3:Document](#Document) | An invoice document referenced in this line trade settlement. | UN01011814 | Line_ Trade Settlement. Invoice. Referenced_ Document
<span id="LineTradeSettlementMonetarySummation">LineTradeSettlementMonetarySummation</span> | [edi3:TradeSettlementLineMonetarySummation](#TradeSettlementLineMonetarySummation) | The monetary summation totals specified for this line trade settlement. | UN01011812 | Line_ Trade Settlement. Specified. Trade Settlement Line_ Monetary Summation
<span id="LineTradeSettlementInvoiceIssuerReferenceText">LineTradeSettlementInvoiceIssuerReferenceText</span> | xsd:string | The invoice issuer reference, expressed as text, for this line settlement. | UN01011802 | Line_ Trade Settlement. Invoice Issuer_ Reference. Text
<span id="LineTradeSettlementAccountsPayable">LineTradeSettlementAccountsPayable</span> | [edi3:AccountingAccount](#AccountingAccount) | A payable accounting account specified for this line trade settlement. | UN01011816 | Line_ Trade Settlement. Payable_ Specified. Trade_ Accounting Account
<span id="LineTradeSettlementTotalAdjustmentAmount">LineTradeSettlementTotalAdjustmentAmount</span> | xsd:decimal | The monetary value of the total adjustment for this line trade settlement. | UN01011939 | Line_ Trade Settlement. Total_ Adjustment. Amount
<span id="LineTradeSettlementFinancialCard">LineTradeSettlementFinancialCard</span> | [edi3:FinancialCard](#FinancialCard) | A financial card specified in this line trade settlement. | UN01011820 | Line_ Trade Settlement. Specified. Trade Settlement_ Financial Card
<span id="LineTradeSettlementPaymentAmount">LineTradeSettlementPaymentAmount</span> | xsd:decimal | A monetary value of a payment for this line trade settlement. | UN01013471 | Line_ Trade Settlement. Payment. Amount


<h1 id="SubordinateLineTradeSettlement">SubordinateLineTradeSettlement</h1>

Type: rdf:Class

Definition: The information, at a subordinate line level, that enables the reconciliation of a financial transaction with the item(s) that the financial transaction is intended to settle, for example a commercial invoice.

Unique UN Assigned ID: UN01011854

Dictionary Entry Name: Subordinate Line_ Trade Settlement. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-


<h1 id="PaymentTradeSettlement">PaymentTradeSettlement</h1>

Type: rdf:Class

Definition: The information that enables the reconciliation of a payment with the item(s) that the payment is intended to settle, for example a commercial invoice.

Unique UN Assigned ID: UN01003261

Dictionary Entry Name: Payment_ Trade Settlement. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="PaymentTradeSettlementPaymentCurrencyExchange">PaymentTradeSettlementPaymentCurrencyExchange</span> | [edi3:CurrencyExchange](#CurrencyExchange) | The currency exchange applicable to this payment trade settlement. | UN01011839 | Payment_ Trade Settlement. Payment_ Applicable. Trade_ Currency Exchange
<span id="PaymentMonetarySummation">PaymentMonetarySummation</span> | [edi3:TradeSettlementPaymentMonetarySummation](#TradeSettlementPaymentMonetarySummation) | The monetary summation totals specified for this payment trade settlement. | UN01011840 | Payment_ Trade Settlement. Specified. Trade Settlement Payment_ Monetary Summation
<span id="PaymentTradeSettlementSpecifiedPaymentMeans">PaymentTradeSettlementSpecifiedPaymentMeans</span> | [edi3:PaymentMeans](#PaymentMeans) | The payment means specified for this payment trade settlement. | UN01011841 | Payment_ Trade Settlement. Specified. Trade Settlement_ Payment Means
<span id="PaymentTradeSettlementAdditionalDescription">PaymentTradeSettlementAdditionalDescription</span> | xsd:string | The description, expressed as text, of additional information supplied to enable the matching of an entry with the items that the payment is intended to settle. | UN01003272 | Payment_ Trade Settlement. Additional_ Description. Text
<span id="PaymentTradeSettlementPayee">PaymentTradeSettlementPayee</span> | [edi3:TradeParty](#TradeParty) | The payee party for this payment trade settlement. | UN01011837 | Payment_ Trade Settlement. Payee. Trade_ Party
<span id="PaymentTradeSettlementPayer">PaymentTradeSettlementPayer</span> | [edi3:TradeParty](#TradeParty) | The payer party for this payment trade settlement. | UN01011838 | Payment_ Trade Settlement. Payer. Trade_ Party
<span id="ApplicableTax">ApplicableTax</span> | [edi3:TradeTax](#TradeTax) | The tax applicable to this payment trade settlement. | UN01011842 | Payment_ Trade Settlement. Applicable. Trade_ Tax


<h1 id="HeaderTradeSettlement">HeaderTradeSettlement</h1>

Type: rdf:Class

Definition: The information, at a header level, that enables the reconciliation of a financial transaction, with the item(s) that the financial transaction is intended to settle, such as a commercial invoice.

Unique UN Assigned ID: UN01011643

Dictionary Entry Name: Header_ Trade Settlement. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="CreditorReferenceIssuerID">CreditorReferenceIssuerID</span> | xsd:token | An identifier of the creditor reference issuer for this header trade settlement. | UN01011647 | Header_ Trade Settlement. Creditor Reference Issuer. Identifier
<span id="PaymentMeans">PaymentMeans</span> | [edi3:PaymentMeans](#PaymentMeans) | A payment means specified for this header trade settlement. | UN01011671 | Header_ Trade Settlement. Specified. Trade Settlement_ Payment Means
<span id="ScheduledPaymentDateTime">ScheduledPaymentDateTime</span> | xsd:dateTime | The date, time, date time or other date time value of the scheduled payment of this header trade settlement. | UN01012136 | Header_ Trade Settlement. Scheduled_ Payment. Date Time
<span id="HeaderTradeSettlementInvoicee">HeaderTradeSettlementInvoicee</span> | [edi3:TradeParty](#TradeParty) | The party to whom an invoice is issued for this header trade settlement. | UN01011663 | Header_ Trade Settlement. Invoicee. Trade_ Party
<span id="TaxCurrencyCode">TaxCurrencyCode</span> | xsd:token | The code specifying the tax currency for this header trade settlement. | UN01011650 | Header_ Trade Settlement. Tax_ Currency. Code
<span id="HeaderTradeSettlementPaymentReferenceText">HeaderTradeSettlementPaymentReferenceText</span> | xsd:string | A payment reference, expressed as text, for this header trade settlement. | UN01011649 | Header_ Trade Settlement. Payment Reference. Text
<span id="HeaderTradeSettlementLetterOfCreditDocument">HeaderTradeSettlementLetterOfCreditDocument</span> | [edi3:Document](#Document) | The letter of credit document referenced in this header trade settlement. | UN01011682 | Header_ Trade Settlement. Letter Of Credit. Referenced_ Document
<span id="RequestedFinancingAmount">RequestedFinancingAmount</span> | xsd:decimal | A financing monetary value requested for this header trade settlement. | UN01013267 | Header_ Trade Settlement. Requested_ Financing. Amount
<span id="HeaderAdvancePayment">HeaderAdvancePayment</span> | [edi3:AdvancePayment](#AdvancePayment) | An advance payment specified in this header trade settlement. | UN01011691 | Header_ Trade Settlement. Specified. Advance_ Payment
<span id="HeaderTradeSettlementSubtotalCalculatedTax">HeaderTradeSettlementSubtotalCalculatedTax</span> | [edi3:TradeTax](#TradeTax) | A tax subtotal calculated for this header trade settlement. | UN01011675 | Header_ Trade Settlement. Subtotal_ Calculated. Trade_ Tax
<span id="NextInvoiceDateTime">NextInvoiceDateTime</span> | xsd:dateTime | A date, time, date time or other date time value of a next invoice or invoices in this header trade settlement. | UN01011659 | Header_ Trade Settlement. Next_ Invoice. Date Time
<span id="ProFormaInvoiceDocument">ProFormaInvoiceDocument</span> | [edi3:Document](#Document) | The pro-forma invoice document referenced by this header trade settlement. | UN01011681 | Header_ Trade Settlement. Pro-Forma Invoice. Referenced_ Document
<span id="HeaderPaymentInstalmentPlan">HeaderPaymentInstalmentPlan</span> | [edi3:InstalmentPlan](#InstalmentPlan) | The payment instalment plan specified for this header trade settlement. | UN01013271 | Header_ Trade Settlement. Specified. Payment_ Instalment Plan
<span id="HeaderTradeSettlementRelevantParty">HeaderTradeSettlementRelevantParty</span> | [edi3:TradeParty](#TradeParty) | A relevant party for this header trade settlement. | UN01013473 | Header_ Trade Settlement. Relevant. Trade_ Party
<span id="CreditorReferenceID">CreditorReferenceID</span> | xsd:token | The identifier of the creditor reference for this header trade settlement, such as a specific identifier assigned by the creditor to reference the financial transaction. | UN01011648 | Header_ Trade Settlement. Creditor Reference. Identifier
<span id="HeaderTradeSettlementInvoiceIssuerReferenceText">HeaderTradeSettlementInvoiceIssuerReferenceText</span> | xsd:string | The invoice issuer reference, expressed as text, for this header trade settlement. | UN01011655 | Header_ Trade Settlement. Invoice Issuer_ Reference. Text
<span id="HeaderTradeSettlementTradeTax">HeaderTradeSettlementTradeTax</span> | [edi3:TradeTax](#TradeTax) | A tax applicable to this header trade settlement. | UN01011672 | Header_ Trade Settlement. Applicable. Trade_ Tax
<span id="HeaderTradeSettlementInvoiceDateTime">HeaderTradeSettlementInvoiceDateTime</span> | xsd:dateTime | The date, time, date time or other date time value of the invoice in this header trade settlement. | UN01011658 | Header_ Trade Settlement. Invoice. Date Time
<span id="QuotationCurrencyCode">QuotationCurrencyCode</span> | xsd:token | The code specifying the quotation currency for this header trade settlement. | UN01011657 | Header_ Trade Settlement. Quotation_ Currency. Code
<span id="CreditorReferenceTypeText">CreditorReferenceTypeText</span> | xsd:string | A creditor reference type, expressed as text, for this header trade settlement. | UN01011646 | Header_ Trade Settlement. Creditor Reference Type. Text
<span id="HeaderTradeSettlementPaymentCurrencyExchange">HeaderTradeSettlementPaymentCurrencyExchange</span> | [edi3:CurrencyExchange](#CurrencyExchange) | The currency exchange applicable to the payment in this header trade settlement. | UN01011670 | Header_ Trade Settlement. Payment_ Applicable. Trade_ Currency Exchange
<span id="CreditReasonText">CreditReasonText</span> | xsd:string | A textual description of the reason for a credit being given in this header trade settlement. | UN01011661 | Header_ Trade Settlement. Credit Reason. Text
<span id="HeaderTradeSettlementDescription">HeaderTradeSettlementDescription</span> | xsd:string | A textual description of this header trade settlement. | UN01012991 | Header_ Trade Settlement. Description. Text
<span id="CreditNoteAmount">CreditNoteAmount</span> | xsd:decimal | A monetary value of the credit note for this header trade settlement. | UN01013270 | Header_ Trade Settlement. Credit Note. Amount
<span id="FactoringListDocument">FactoringListDocument</span> | [edi3:Document](#Document) | A factoring list document referenced in this header trade settlement. | UN01011684 | Header_ Trade Settlement. Factoring List. Referenced_ Document
<span id="HeaderTradeSettlementInvoiceDocument">HeaderTradeSettlementInvoiceDocument</span> | [edi3:Document](#Document) | An invoice document referenced by this header trade settlement. | UN01011680 | Header_ Trade Settlement. Invoice. Referenced_ Document
<span id="HeaderTradeSettlementPaymentCurrencyCode">HeaderTradeSettlementPaymentCurrencyCode</span> | xsd:token | The code specifying the payment currency for this header trade settlement. | UN01011654 | Header_ Trade Settlement. Payment_ Currency. Code
<span id="HeaderTradeSettlementInvoiceCurrencyExchange">HeaderTradeSettlementInvoiceCurrencyExchange</span> | [edi3:CurrencyExchange](#CurrencyExchange) | The currency exchange applicable to the invoice in this header trade settlement. | UN01011668 | Header_ Trade Settlement. Invoice_ Applicable. Trade_ Currency Exchange
<span id="HeaderTradeSettlementFinancialCard">HeaderTradeSettlementFinancialCard</span> | [edi3:FinancialCard](#FinancialCard) | A financial card specified in this header trade settlement. | UN01011689 | Header_ Trade Settlement. Specified. Trade Settlement_ Financial Card
<span id="DebitNoteAmount">DebitNoteAmount</span> | xsd:decimal | A monetary value of the debit note for this header trade settlement. | UN01013269 | Header_ Trade Settlement. Debit Note. Amount
<span id="HeaderTradeSettlementPayerReferenceText">HeaderTradeSettlementPayerReferenceText</span> | xsd:string | The payer reference, expressed as text, for this header trade settlement. | UN01011656 | Header_ Trade Settlement. Payer_ Reference. Text
<span id="FactoringAgreementDocument">FactoringAgreementDocument</span> | [edi3:Document](#Document) | A factoring agreement document referenced in this header trade settlement. | UN01011683 | Header_ Trade Settlement. Factoring Agreement. Referenced_ Document
<span id="HeaderTradeSettlementPaymentAmount">HeaderTradeSettlementPaymentAmount</span> | xsd:decimal | A monetary value of a payment for this header trade settlement. | UN01013470 | Header_ Trade Settlement. Payment. Amount
<span id="HeaderTradeSettlementSalesAccountingAccount">HeaderTradeSettlementSalesAccountingAccount</span> | [edi3:AccountingAccount](#AccountingAccount) | A sales accounting account specified for this header trade settlement. | UN01011688 | Header_ Trade Settlement. Sales_ Specified. Trade_ Accounting Account
<span id="HeaderTradeSettlementAccountsReceivable">HeaderTradeSettlementAccountsReceivable</span> | [edi3:AccountingAccount](#AccountingAccount) | A receivable accounting account specified for this header trade settlement. | UN01011686 | Header_ Trade Settlement. Receivable_ Specified. Trade_ Accounting Account
<span id="QuotationCurrencyExchange">QuotationCurrencyExchange</span> | [edi3:CurrencyExchange](#CurrencyExchange) | The currency exchange applicable to the quotation currency in this header trade settlement. | UN01011690 | Header_ Trade Settlement. Quotation_ Applicable. Trade_ Currency Exchange
<span id="HeaderTradeSettlementDiscountIndicator">HeaderTradeSettlementDiscountIndicator</span> | xsd:boolean | The indication of whether or not this header trade settlement includes a discount amount. | UN01012992 | Header_ Trade Settlement. Discount. Indicator
<span id="OrderCurrencyExchange">OrderCurrencyExchange</span> | [edi3:CurrencyExchange](#CurrencyExchange) | The currency exchange applicable to the order currency in this header trade settlement. | UN01011667 | Header_ Trade Settlement. Order_ Applicable. Trade_ Currency Exchange
<span id="HeaderTradeSettlementPurchaseAccountingAccount">HeaderTradeSettlementPurchaseAccountingAccount</span> | [edi3:AccountingAccount](#AccountingAccount) | A purchase accounting account specified for this header trade settlement. | UN01011687 | Header_ Trade Settlement. Purchase_ Specified. Trade_ Accounting Account
<span id="UltimatePayee">UltimatePayee</span> | [edi3:TradeParty](#TradeParty) | An ultimate payee party in this header trade settlement. | UN01011692 | Header_ Trade Settlement. Ultimate_ Payee. Trade_ Party
<span id="HeaderTradeSettlementClosingBookDueDateTime">HeaderTradeSettlementClosingBookDueDateTime</span> | xsd:dateTime | The date, time, date time or other date time value when the book closing is due for this header trade settlement. | UN01012135 | Header_ Trade Settlement. Closing Book_ Due. Date Time
<span id="HeaderTradeSettlementAllowanceCharge">HeaderTradeSettlementAllowanceCharge</span> | [edi3:TradeAllowanceCharge](#TradeAllowanceCharge) | An allowance or charge specified for this header trade settlement. | UN01011674 | Header_ Trade Settlement. Specified. Trade_ Allowance Charge
<span id="HeaderTradeSettlementBillingPeriod">HeaderTradeSettlementBillingPeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | A billing period specified for this header trade settlement. | UN01011673 | Header_ Trade Settlement. Billing. Specified_ Period
<span id="RequestedFinancingRate">RequestedFinancingRate</span> | xsd:decimal | The financing rate, expressed as a percentage, requested for this header trade settlement. | UN01013268 | Header_ Trade Settlement. Requested_ Financing Rate. Percent
<span id="HeaderTradeSettlementPaymentTerms">HeaderTradeSettlementPaymentTerms</span> | [edi3:PaymentTerms](#PaymentTerms) | Payment terms specified for this header trade settlement. | UN01011677 | Header_ Trade Settlement. Specified. Trade_ Payment Terms
<span id="HeaderTradeSettlementAccountsPayable">HeaderTradeSettlementAccountsPayable</span> | [edi3:AccountingAccount](#AccountingAccount) | A payable accounting account specified for this header trade settlement. | UN01011685 | Header_ Trade Settlement. Payable_ Specified. Trade_ Accounting Account
<span id="HeaderTradeSettlementPriceCurrencyCode">HeaderTradeSettlementPriceCurrencyCode</span> | xsd:token | The code specifying the price currency for this header trade settlement. | UN01011653 | Header_ Trade Settlement. Price_ Currency. Code
<span id="HeaderTradeSettlementTotalAdjustmentAmount">HeaderTradeSettlementTotalAdjustmentAmount</span> | xsd:decimal | A monetary value of the total adjustment for this header trade settlement. | UN01012994 | Header_ Trade Settlement. Total_ Adjustment. Amount
<span id="PriceCurrencyExchange">PriceCurrencyExchange</span> | [edi3:CurrencyExchange](#CurrencyExchange) | The currency exchange applicable to the price in this header trade settlement. | UN01011669 | Header_ Trade Settlement. Price_ Applicable. Trade_ Currency Exchange
<span id="HeaderTradeSettlementMonetarySummation">HeaderTradeSettlementMonetarySummation</span> | [edi3:TradeSettlementHeaderMonetarySummation](#TradeSettlementHeaderMonetarySummation) | The monetary summation totals specified for this header trade settlement. | UN01011678 | Header_ Trade Settlement. Specified. Trade Settlement Header_ Monetary Summation
<span id="HeaderTradeSettlementTotalInvoiceAmount">HeaderTradeSettlementTotalInvoiceAmount</span> | xsd:decimal | A monetary value of the total invoice on which this header trade settlement is calculated. | UN01012993 | Header_ Trade Settlement. Total Invoice. Amount
<span id="CreditorReferenceTypeCode">CreditorReferenceTypeCode</span> | xsd:token | A code specifying the creditor reference type for this header trade settlement. | UN01011645 | Header_ Trade Settlement. Creditor Reference Type. Code
<span id="HeaderTradeSettlementFinancialAdjustment">HeaderTradeSettlementFinancialAdjustment</span> | [edi3:FinancialAdjustment](#FinancialAdjustment) | A financial adjustment specified for this header trade settlement. | UN01011679 | Header_ Trade Settlement. Specified. Financial_ Adjustment
<span id="HeaderTradeSettlementLogisticsServiceCharge">HeaderTradeSettlementLogisticsServiceCharge</span> | [edi3:ServiceCharge](#ServiceCharge) | A logistics service charge specified for this header trade settlement. | UN01011676 | Header_ Trade Settlement. Specified. Logistics_ Service Charge
<span id="HeaderTradeSettlementDuePayableAmount">HeaderTradeSettlementDuePayableAmount</span> | xsd:decimal | A monetary value that is an exact amount due and payable for this header trade settlement, such as the amount due to the creditor. | UN01011644 | Header_ Trade Settlement. Due Payable. Amount
<span id="OrderCurrencyCode">OrderCurrencyCode</span> | xsd:token | The code specifying the currency of the order for this header trade settlement. | UN01011651 | Header_ Trade Settlement. Order_ Currency. Code
<span id="InvoiceCurrencyCode">InvoiceCurrencyCode</span> | xsd:token | The code specifying the invoice currency for this header trade settlement. | UN01011652 | Header_ Trade Settlement. Invoice_ Currency. Code
<span id="Invoicer">Invoicer</span> | [edi3:TradeParty](#TradeParty) | The party issuing the invoice for this header trade settlement. | UN01011662 | Header_ Trade Settlement. Invoicer. Trade_ Party
<span id="HeaderTradeSettlementPayer">HeaderTradeSettlementPayer</span> | [edi3:TradeParty](#TradeParty) | The payer party for this header trade settlement. | UN01011665 | Header_ Trade Settlement. Payer. Trade_ Party
<span id="HeaderTradeSettlementPayee">HeaderTradeSettlementPayee</span> | [edi3:TradeParty](#TradeParty) | A payee party for this header trade settlement. | UN01011664 | Header_ Trade Settlement. Payee. Trade_ Party
<span id="CreditReasonCode">CreditReasonCode</span> | xsd:token | The code specifying the reason for a credit being given in this header trade settlement. | UN01011660 | Header_ Trade Settlement. Credit Reason. Code


<h1 id="ReferencePrice">ReferencePrice</h1>

Type: rdf:Class

Definition: A reference to a sum of money for which something is or may be bought or sold.

Unique UN Assigned ID: UN01007304

Dictionary Entry Name: Reference_ Price. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="ReferencePriceChargeAmount">ReferencePriceChargeAmount</span> | xsd:decimal | The monetary value of a charged reference price. | UN01007305 | Reference_ Price. Charge. Amount
<span id="ReferencePriceBasisQuantity">ReferencePriceBasisQuantity</span> | xsd:decimal | A quantity on which the reference price is based. | UN01007306 | Reference_ Price. Basis. Quantity
<span id="ComparisonMethodCode">ComparisonMethodCode</span> | xsd:token | The code specifying the comparison method for this reference price. | UN01008503 | Reference_ Price. Comparison Method. Code


<h1 id="TradePrice">TradePrice</h1>

Type: rdf:Class

Definition: A sum of money for which something is or may be bought or sold for trade purposes.

Unique UN Assigned ID: UN01001676

Dictionary Entry Name: Trade_ Price. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="TradePriceTypeText">TradePriceTypeText</span> | xsd:string | A type, expressed as text, for this trade price. | UN01013365 | Trade_ Price. Type. Text
<span id="MaximumQuantity">MaximumQuantity</span> | xsd:decimal | The maximum quantity in a range for which the trade price applies. | UN01004644 | Trade_ Price. Maximum. Quantity
<span id="TradePriceChargeAmount">TradePriceChargeAmount</span> | xsd:decimal | A monetary value of the trade price charge. | UN01001679 | Trade_ Price. Charge. Amount
<span id="TradePriceAssociatedDocument">TradePriceAssociatedDocument</span> | [edi3:Document](#Document) | An associated document referenced for this trade price. | UN01011921 | Trade_ Price. Associated. Referenced_ Document
<span id="UnitAmount">UnitAmount</span> | xsd:decimal | A monetary value of the unit of this trade price. | UN01004645 | Trade_ Price. Unit. Amount
<span id="ChangeReasonText">ChangeReasonText</span> | xsd:string | A reason, expressed as text, for a change of this trade price. | UN01004646 | Trade_ Price. Change Reason. Text
<span id="TradeComparisonPrice">TradeComparisonPrice</span> | [edi3:ReferencePrice](#ReferencePrice) | A price that provides a trade comparison with this trade price. | UN01011920 | Trade_ Price. Trade_ Comparison. Reference_ Price
<span id="TradePriceAppliedAllowanceCharge">TradePriceAppliedAllowanceCharge</span> | [edi3:TradeAllowanceCharge](#TradeAllowanceCharge) | An allowance or charge applied to the trade price. | UN01001682 | Trade_ Price. Applied. Trade_ Allowance Charge
<span id="DeliveryLocation">DeliveryLocation</span> | [edi3:TradeLocation](#TradeLocation) | A delivery location for this trade price. | UN01007237 | Trade_ Price. Delivery. Trade_ Location
<span id="TradePriceIncludedTax">TradePriceIncludedTax</span> | [edi3:TradeTax](#TradeTax) | A tax included in this trade price. | UN01004649 | Trade_ Price. Included. Trade_ Tax
<span id="TradePriceTypeCode">TradePriceTypeCode</span> | xsd:token | The code specifying the type of trade price. | UN01001678 | Trade_ Price. Type. Code
<span id="OrderUnitConversionFactor">OrderUnitConversionFactor</span> | xsd:decimal | The value used as the factor to convert the order unit into the price unit for this trade price. | UN01004647 | Trade_ Price. Order_ Unit Conversion Factor. Numeric
<span id="TradePriceBasisQuantity">TradePriceBasisQuantity</span> | xsd:decimal | The quantity on which the trade price is based. | UN01001680 | Trade_ Price. Basis. Quantity
<span id="TradePriceValidityPeriod">TradePriceValidityPeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | A specified period for which this trade price is valid. | UN01004648 | Trade_ Price. Validity. Specified_ Period


<h1 id="CalculatedPrice">CalculatedPrice</h1>

Type: rdf:Class

Definition: Information related to a calculated price.

Unique UN Assigned ID: UN01000179

Dictionary Entry Name: Calculated_ Price. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="CalculatedPriceTypeCode">CalculatedPriceTypeCode</span> | xsd:token | A code specifying the type of calculated price. | UN01000180 | Calculated_ Price. Type. Code
<span id="CalculatedPriceAppliedAllowanceCharge">CalculatedPriceAppliedAllowanceCharge</span> | [edi3:AppliedAllowanceCharge](#AppliedAllowanceCharge) | Applied allowance charge information related to this calculated price. | UN01000182 | Calculated_ Price. Related. Applied_ Allowance Charge


<h1 id="SupplyPlan">SupplyPlan</h1>

Type: rdf:Class

Definition: Specification of the delivery time and quantity bucket in a supply chain demand forecast or delivery schedule.

Unique UN Assigned ID: UN01004324

Dictionary Entry Name: Supply Chain_ Supply Plan. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="SynchronizationQuantity">SynchronizationQuantity</span> | xsd:decimal | The value specifying the quantity for a synchronization of this supply chain supply plan. | UN01005311 | Supply Chain_ Supply Plan. Synchronization. Quantity
<span id="SupplyPlanConfirmedDeliveryEvent">SupplyPlanConfirmedDeliveryEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | A confirmed delivery event in this supply chain supply plan. | UN01006702 | Supply Chain_ Supply Plan. Confirmed_ Delivery. Supply Chain_ Event
<span id="SupplyPlanContractDocument">SupplyPlanContractDocument</span> | [edi3:Document](#Document) | A referenced contract document for this supply chain supply plan. | UN01011860 | Supply Chain_ Supply Plan. Contract. Referenced_ Document
<span id="SynchronizationDateTime">SynchronizationDateTime</span> | xsd:dateTime | A date, time, date time, or other date time value of a synchronization of the supply chain supply plan. | UN01005310 | Supply Chain_ Supply Plan. Synchronization. Date Time
<span id="MinusToleranceQuantity">MinusToleranceQuantity</span> | xsd:decimal | The minus tolerance quantity from the planned or requested quantity in this supply chain supply plan. | UN01006699 | Supply Chain_ Supply Plan. Minus_ Tolerance. Quantity
<span id="SupplyPlanApplicablePeriod">SupplyPlanApplicablePeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The period applicable for this supply chain supply plan. | UN01011859 | Supply Chain_ Supply Plan. Applicable. Specified_ Period
<span id="PlannedQuantity">PlannedQuantity</span> | xsd:decimal | The planned quantity in this supply chain supply plan. | UN01004326 | Supply Chain_ Supply Plan. Planned. Quantity
<span id="SupplyPlanDeliveryNoteDocument">SupplyPlanDeliveryNoteDocument</span> | [edi3:Document](#Document) | A delivery note document referenced by this supply chain supply plan. | UN01011861 | Supply Chain_ Supply Plan. Delivery Note. Referenced_ Document
<span id="ScheduledDeliveryEvent">ScheduledDeliveryEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | A scheduled delivery event in this supply chain supply plan. | UN01006701 | Supply Chain_ Supply Plan. Scheduled_ Delivery. Supply Chain_ Event
<span id="SupplyPlanDeliveryEvent">SupplyPlanDeliveryEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | A delivery event for this supply chain supply plan. | UN01004330 | Supply Chain_ Supply Plan. Delivery. Supply Chain_ Event
<span id="PlusToleranceQuantity">PlusToleranceQuantity</span> | xsd:decimal | The plus tolerance quantity from the planned or requested quantity in this supply chain supply plan. | UN01006700 | Supply Chain_ Supply Plan. Plus_ Tolerance. Quantity
<span id="SupplyPlanShipToParty">SupplyPlanShipToParty</span> | [edi3:TradeParty](#TradeParty) | The ship to trade party for this supply chain supply plan. | UN01006704 | Supply Chain_ Supply Plan. Ship To. Trade_ Party
<span id="SupplyPlanActualQuantity">SupplyPlanActualQuantity</span> | xsd:decimal | The actual quantity in this supply chain supply plan. | UN01004327 | Supply Chain_ Supply Plan. Actual. Quantity
<span id="SupplyPlanCommitmentLevelCode">SupplyPlanCommitmentLevelCode</span> | xsd:token | The code specifying the commitment level for this supply chain supply plan, such as fabrication or raw material. | UN01004325 | Supply Chain_ Supply Plan. Commitment Level. Code
<span id="ToleranceQuantity">ToleranceQuantity</span> | xsd:decimal | The quantity of tolerance from the planned quantity in this supply chain supply plan. | UN01004328 | Supply Chain_ Supply Plan. Tolerance. Quantity


<h1 id="Observation">Observation</h1>

Type: rdf:Class

Definition: A specified act or instance of viewing or noting a fact or occurrence for some scientific or other special purpose.

Unique UN Assigned ID: UN01012570

Dictionary Entry Name: Specified_ Observation. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="ObservationDescription">ObservationDescription</span> | xsd:string | The textual description for this specified observation. | UN01012572 | Specified_ Observation. Description. Text
<span id="ObservationApplicableNote">ObservationApplicableNote</span> | [edi3:Note](#Note) | A note providing information applicable to this specified observation. | UN01012574 | Specified_ Observation. Applicable. Note
<span id="ObservationID">ObservationID</span> | xsd:token | The identifier for this specified observation. | UN01012571 | Specified_ Observation. Identification. Identifier


<h1 id="Packaging">Packaging</h1>

Type: rdf:Class

Definition: Any material with which supply chain goods are packaged, such as a box or bubble wrap.

Unique UN Assigned ID: UN01004312

Dictionary Entry Name: Supply Chain_ Packaging. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="PackagingInstructionCode">PackagingInstructionCode</span> | xsd:token | A code specifying an instruction for this supply chain packaging. | UN01005307 | Supply Chain_ Packaging. Instruction. Code
<span id="PackagingConditionCode">PackagingConditionCode</span> | xsd:token | A code specifying the condition of this supply chain packaging. | UN01004316 | Supply Chain_ Packaging. Condition. Code
<span id="ContentLayerQuantity">ContentLayerQuantity</span> | xsd:decimal | The number of content layers that are or may be packaged with this supply chain packaging, such as the number of layers of product on a pallet. | UN01008489 | Supply Chain_ Packaging. Content Layer. Quantity
<span id="PackagingMaximumStackabilityWeight">PackagingMaximumStackabilityWeight</span> | xsd:decimal | The measure of the maximum stackability weight of this supply chain packaging. | UN01006750 | Supply Chain_ Packaging. Maximum Stackability_ Weight. Measure
<span id="AdditionalInstructionIndicator">AdditionalInstructionIndicator</span> | xsd:boolean | The indication of whether or not there is an additional instruction for this supply chain packaging. | UN01012709 | Supply Chain_ Packaging. Additional_ Instruction. Indicator
<span id="PackagingDimensions">PackagingDimensions</span> | [edi3:SpatialDimension](#SpatialDimension) | The linear spatial dimensions of this supply chain packaging. | UN01004320 | Supply Chain_ Packaging. Linear. Spatial_ Dimension
<span id="SupplyChainReturnableAssetInstructions">SupplyChainReturnableAssetInstructions</span> | [edi3:ReturnableAssetInstructions](#ReturnableAssetInstructions) | Returnable asset instructions for this supply chain packaging. | UN01008492 | Supply Chain_ Packaging. Applicable. Returnable Asset_ Instructions
<span id="PackagingReturnableIndicator">PackagingReturnableIndicator</span> | xsd:boolean | The indication of whether or not this supply chain packaging is returnable. | UN01006751 | Supply Chain_ Packaging. Returnable. Indicator
<span id="TotalUnitQuantity">TotalUnitQuantity</span> | xsd:decimal | A total number of units contained in this supply chain packaging. | UN01007195 | Supply Chain_ Packaging. Total Unit. Quantity
<span id="PackagingTypeCode">PackagingTypeCode</span> | xsd:token | The code specifying the type of supply chain packaging. | UN01004313 | Supply Chain_ Packaging. Type. Code
<span id="PackagingWeight">PackagingWeight</span> | xsd:decimal | A measure of the weight of this supply chain packaging. | UN01004319 | Supply Chain_ Packaging. Weight. Measure
<span id="PackagingDescription">PackagingDescription</span> | xsd:string | A textual description of this supply chain packaging. | UN01004315 | Supply Chain_ Packaging. Description. Text
<span id="AdditionalInstructionCode">AdditionalInstructionCode</span> | xsd:token | A code specifying an additional instruction for this supply chain packaging. | UN01012708 | Supply Chain_ Packaging. Additional_ Instruction. Code
<span id="LayerTotalUnitQuantity">LayerTotalUnitQuantity</span> | xsd:decimal | The total number of units in a layer of this supply chain packaging. | UN01007196 | Supply Chain_ Packaging. Layer_ Total Unit. Quantity
<span id="PackagingMaximumStackabilityQuantity">PackagingMaximumStackabilityQuantity</span> | xsd:decimal | The number of units of this type of supply chain packaging which can be stacked on top of each other. | UN01006749 | Supply Chain_ Packaging. Maximum Stackability. Quantity
<span id="DisposalMethodCode">DisposalMethodCode</span> | xsd:token | A code specifying the disposal method of this supply chain packaging. | UN01004317 | Supply Chain_ Packaging. Disposal Method. Code
<span id="Marking">Marking</span> | [edi3:Marking](#Marking) | A marking specified for this supply chain packaging, such as an inscription, stamp or label to indicate date, ownership, quality, manufacture or origin. | UN01004323 | Supply Chain_ Packaging. Specified. Packaging_ Marking
<span id="PackagingMaximumDimensions">PackagingMaximumDimensions</span> | [edi3:SpatialDimension](#SpatialDimension) | The maximum linear spatial dimensions of this supply chain packaging. | UN01004322 | Supply Chain_ Packaging. Maximum_ Linear. Spatial_ Dimension
<span id="PackagingTypeText">PackagingTypeText</span> | xsd:string | The type, expressed as text, of supply chain packaging. | UN01004314 | Supply Chain_ Packaging. Type. Text
<span id="GoodsCharacteristic">GoodsCharacteristic</span> | [edi3:GoodsCharacteristic](#GoodsCharacteristic) | Material goods characteristic applicable to this supply chain packaging. | UN01008490 | Supply Chain_ Packaging. Applicable. Material_ Goods Characteristic
<span id="CustomerFacingTotalUnitQuantity">CustomerFacingTotalUnitQuantity</span> | xsd:decimal | The total number of units of this supply chain packaging facing the customer, such as would be seen when this packaging is placed on a retail shelf. | UN01007194 | Supply Chain_ Packaging. Customer Facing_ Total Unit. Quantity
<span id="PackagingMinimumDimensions">PackagingMinimumDimensions</span> | [edi3:SpatialDimension](#SpatialDimension) | The minimum linear spatial dimensions of this supply chain packaging. | UN01004321 | Supply Chain_ Packaging. Minimum_ Linear. Spatial_ Dimension


<h1 id="Certificate">Certificate</h1>

Type: rdf:Class

Definition: A collection of data for a piece of written, printed or electronic matter that provides information or evidence about the product.

Unique UN Assigned ID: UN01012483

Dictionary Entry Name: Product_ Certificate. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="IssuingPartyID">IssuingPartyID</span> | xsd:token | The identifier for the party issuing this product certificate. | UN01012493 | Product_ Certificate. Issuing_ Party. Identifier
<span id="ActualEffectiveDateTime">ActualEffectiveDateTime</span> | xsd:dateTime | The actual effective date, time, date time or other date time value for this product certificate. | UN01012490 | Product_ Certificate. Actual Effective. Date Time
<span id="CertificateIssueDateTime">CertificateIssueDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value when this product certificate was issued. | UN01012485 | Product_ Certificate. Issue. Date Time
<span id="RequestedEffectiveDateTime">RequestedEffectiveDateTime</span> | xsd:dateTime | The requested effective date, time, date time or other date time value for this product certificate. | UN01012489 | Product_ Certificate. Requested Effective. Date Time
<span id="CertificateDescription">CertificateDescription</span> | xsd:string | A textual description of this product certificate. | UN01012491 | Product_ Certificate. Description. Text
<span id="CertificateID">CertificateID</span> | xsd:token | The identifier for this product certificate. | UN01012484 | Product_ Certificate. Identification. Identifier
<span id="CertificateTypeCode">CertificateTypeCode</span> | xsd:token | A code specifying the type of product certificate. | UN01012488 | Product_ Certificate. Type. Code
<span id="ApplicableObjectCode">ApplicableObjectCode</span> | xsd:token | A code specifying an object, such as item, animal, person or organization applicable for this product certificate. | UN01012492 | Product_ Certificate. Applicable_ Object. Code
<span id="CertificateExpiryDateTime">CertificateExpiryDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value when this product certificate expires. | UN01012486 | Product_ Certificate. Expiry. Date Time
<span id="IssueReasonCode">IssueReasonCode</span> | xsd:token | The code specifying the reason why this product certificate was issued. | UN01012487 | Product_ Certificate. Issue Reason. Code


<h1 id="Sensor">Sensor</h1>

Type: rdf:Class

Definition: An object which can detect and measure physical properties and which can record, indicate and transmit such measurements.

Unique UN Assigned ID: UN01013539

Dictionary Entry Name: Monitoring_ Sensor. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="SensorOwnerParty">SensorOwnerParty</span> | [edi3:TradeParty](#TradeParty) | The owner party of this monitoring sensor. | UN01013545 | Monitoring_ Sensor. Owner. Trade_ Party
<span id="SensorPositionCode">SensorPositionCode</span> | xsd:token | The code specifying a position of this monitoring sensor. | UN01013542 | Monitoring_ Sensor. Position. Code
<span id="SensorManufacturerParty">SensorManufacturerParty</span> | [edi3:TradeParty](#TradeParty) | The manufacturer party for this monitoring sensor. | UN01013546 | Monitoring_ Sensor. Manufacturer. Trade_ Party
<span id="SensorID">SensorID</span> | xsd:token | An identifier of this monitoring sensor. | UN01013540 | Monitoring_ Sensor. Identification. Identifier
<span id="SensorRemainingBatteryChargePercent">SensorRemainingBatteryChargePercent</span> | xsd:decimal | The percentage of the remaining battery charge of this monitoring sensor. | UN01013544 | Monitoring_ Sensor. Remaining Battery Charge. Percent
<span id="ReportedScheduledCalibratedMeasurement">ReportedScheduledCalibratedMeasurement</span> | [edi3:CalibratedMeasurement](#CalibratedMeasurement) | A scheduled calibrated measurement reported for this monitoring sensor. | UN01013552 | Monitoring_ Sensor. Scheduled_ Reported. Calibrated_ Measurement
<span id="DefinedControlSettingParameter">DefinedControlSettingParameter</span> | [edi3:ControlSettingParameter](#ControlSettingParameter) | A control setting parameter defined for this monitoring sensor. | UN01013547 | Monitoring_ Sensor. Defined. Control Setting_ Parameter
<span id="DefinedOperationalParameter">DefinedOperationalParameter</span> | [edi3:OperationalParameter](#OperationalParameter) | An operational parameter defined for this monitoring sensor. | UN01013548 | Monitoring_ Sensor. Defined. Operational_ Parameter
<span id="SensorGrantedProductCertificate">SensorGrantedProductCertificate</span> | [edi3:Certificate](#Certificate) | A product certificate granted for this monitoring sensor. | UN01013549 | Monitoring_ Sensor. Granted. Product_ Certificate
<span id="SensorTypeCode">SensorTypeCode</span> | xsd:token | The code specifying a type of monitoring sensor. | UN01013541 | Monitoring_ Sensor. Type. Code
<span id="ReportedActualCalibratedMeasurement">ReportedActualCalibratedMeasurement</span> | [edi3:CalibratedMeasurement](#CalibratedMeasurement) | An actual calibrated measurement reported for this monitoring sensor. | UN01013551 | Monitoring_ Sensor. Actual_ Reported. Calibrated_ Measurement
<span id="PrecisionCalibratedMeasurement">PrecisionCalibratedMeasurement</span> | [edi3:CalibratedMeasurement](#CalibratedMeasurement) | A calibrated measurement of precision for this monitoring sensor. | UN01013550 | Monitoring_ Sensor. Precision. Calibrated_ Measurement


<h1 id="IOTDevice">IOTDevice</h1>

Type: rdf:Class

Definition: An IOT (Internet of Things) piece of mechanical or electronic equipment which can collect, report and autonomously transmit digital data.

Unique UN Assigned ID: UN01013475

Dictionary Entry Name: Monitoring_ IOT Device. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="IOTDeviceTypeCode">IOTDeviceTypeCode</span> | xsd:token | The code specifying the type of monitoring IOT device. | UN01013477 | Monitoring_ IOT Device. Type. Code
<span id="IOTDevicePositionCode">IOTDevicePositionCode</span> | xsd:token | The code specifying the position of this monitoring IOT device. | UN01013480 | Monitoring_ IOT Device. Position. Code
<span id="CommunicationCapabilityCode">CommunicationCapabilityCode</span> | xsd:token | The code specifying the communication capability of this monitoring IOT device. | UN01013479 | Monitoring_ IOT Device. Communication Capability. Code
<span id="LatestReceivedSignalDateTime">LatestReceivedSignalDateTime</span> | xsd:dateTime | The date, time, date time or other date time value of the latest received signal for this monitoring IOT device, from the perspective of the receiver. | UN01013483 | Monitoring_ IOT Device. Latest Received_ Signal. Date Time
<span id="LatestReceivedGeographicalCoordinate">LatestReceivedGeographicalCoordinate</span> | [edi3:GeographicalCoordinate](#GeographicalCoordinate) | The latest geographical coordinates received by this monitoring IOT device, from the perspective of the receiver. | UN01013496 | Monitoring_ IOT Device. Latest_ Received. Geographical Coordinate
<span id="IOTDeviceGrantedProductCertificate">IOTDeviceGrantedProductCertificate</span> | [edi3:Certificate](#Certificate) | A product certificate granted for this monitoring IOT device. | UN01013485 | Monitoring_ IOT Device. Granted. Product_ Certificate
<span id="IOTDeviceRemainingBatteryChargePercent">IOTDeviceRemainingBatteryChargePercent</span> | xsd:decimal | The percentage of the remaining battery charge of this monitoring IOT device. | UN01013482 | Monitoring_ IOT Device. Remaining Battery Charge. Percent
<span id="OEMInterfaceEquipment">OEMInterfaceEquipment</span> | [edi3:Equipment](#Equipment) | An interface between an OEM (Original Equipment Manufacturer) equipment and this monitoring IOT device. | UN01013490 | Monitoring_ IOT Device. Interface. OEM_ Equipment
<span id="EmbeddedSensor">EmbeddedSensor</span> | [edi3:Sensor](#Sensor) | An embedded sensor of this monitoring IOT device. | UN01013494 | Monitoring_ IOT Device. Embedded. Monitoring_ Sensor
<span id="IOTDeviceOwnerParty">IOTDeviceOwnerParty</span> | [edi3:TradeParty](#TradeParty) | The owner party of this monitoring IOT device. | UN01013487 | Monitoring_ IOT Device. Owner. Trade_ Party
<span id="RemoteSensor">RemoteSensor</span> | [edi3:Sensor](#Sensor) | A remote sensor of this monitoring IOT device. | UN01013495 | Monitoring_ IOT Device. Remote. Monitoring_ Sensor
<span id="PowerSourceTypeCode">PowerSourceTypeCode</span> | xsd:token | The code specifying a type of power source for this monitoring IOT device. | UN01013481 | Monitoring_ IOT Device. Power Source Type. Code
<span id="IOTDeviceOperationalStatusCode">IOTDeviceOperationalStatusCode</span> | xsd:token | The code specifying the operational status, such as broken, stolen, unpaired, inactive of this monitoring IOT device. | UN01013478 | Monitoring_ IOT Device. Operational_ Status. Code
<span id="ReportedTransportEvent">ReportedTransportEvent</span> | [edi3:Event](#Event) | A transport event reported by this monitoring IOT device. | UN01013493 | Monitoring_ IOT Device. Reported. Transport_ Event
<span id="ProviderParty">ProviderParty</span> | [edi3:TradeParty](#TradeParty) | The provider party for this monitoring IOT device. | UN01013489 | Monitoring_ IOT Device. Provider. Trade_ Party
<span id="IOTDeviceManufacturerParty">IOTDeviceManufacturerParty</span> | [edi3:TradeParty](#TradeParty) | The manufacturer party of this monitoring IOT device. | UN01013486 | Monitoring_ IOT Device. Manufacturer. Trade_ Party
<span id="AttachedAssetID">AttachedAssetID</span> | xsd:token | The identifier for the asset, such as a container, to which this monitoring IOT device is attached. | UN01013484 | Monitoring_ IOT Device. Attached Asset_ Identification. Identifier
<span id="OperatorParty">OperatorParty</span> | [edi3:TradeParty](#TradeParty) | The operator party, such as terminal operator, service provider, network operator of this monitoring IOT device. | UN01013488 | Monitoring_ IOT Device. Operator. Trade_ Party
<span id="ReportingSensorCommunicationPairing">ReportingSensorCommunicationPairing</span> | [edi3:Pairing](#Pairing) | A sensor communication pairing reported for this monitoring IOT device. | UN01013491 | Monitoring_ IOT Device. Reporting_ Sensor. Communication_ Pairing
<span id="IOTDeviceID">IOTDeviceID</span> | xsd:token | An identifier for this monitoring IOT device. | UN01013476 | Monitoring_ IOT Device. Identification. Identifier


<h1 id="Measurement">Measurement</h1>

Type: rdf:Class

Definition: An amount, size, or extent as established by measuring.

Unique UN Assigned ID: UN01003890

Dictionary Entry Name: Measurement. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="MeasurementTypeCode">MeasurementTypeCode</span> | xsd:token | A code specifying a type of measurement. | UN01003895 | Measurement. Type. Code
<span id="MeasurementDescription">MeasurementDescription</span> | xsd:string | A textual description of this measurement. | UN01003896 | Measurement. Description. Text
<span id="ActualMeasure">ActualMeasure</span> | xsd:decimal | An actual measure for this measurement. | UN01003892 | Measurement. Actual. Measure
<span id="MethodText">MethodText</span> | xsd:string | A measurement method expressed as text. | UN01003893 | Measurement. Method. Text
<span id="ConditionMeasure">ConditionMeasure</span> | xsd:decimal | A measure of a condition for this measurement. | UN01003894 | Measurement. Condition. Measure


<h1 id="CalibratedMeasurement">CalibratedMeasurement</h1>

Type: rdf:Class

Definition: A measurement established by a device which is tested to a calibration standard of known accuracy.

Unique UN Assigned ID: UN01013531

Dictionary Entry Name: Calibrated_ Measurement. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="CalibratedMeasurementValueCode">CalibratedMeasurementValueCode</span> | xsd:token | The code specifying a value for this calibrated measurement. | UN01013535 | Calibrated_ Measurement. Value. Code
<span id="CalibratedMeasurementToleranceMeasure">CalibratedMeasurementToleranceMeasure</span> | xsd:decimal | The measure of the tolerance of this calibrated measurement. | UN01013537 | Calibrated_ Measurement. Tolerance. Measure
<span id="CalibratedMeasurementID">CalibratedMeasurementID</span> | xsd:token | The identifier for this calibrated measurement. | UN01013532 | Calibrated_ Measurement. Identification. Identifier
<span id="CalibratedMeasurementVersionID">CalibratedMeasurementVersionID</span> | xsd:token | The identifier of a version of this calibrated measurement. | UN01013533 | Calibrated_ Measurement. Version. Identifier
<span id="QuantificationTypeCode">QuantificationTypeCode</span> | xsd:token | The code specifying a quantification type for this calibrated measurement, such as measured, calculated, or estimated. | UN01013534 | Calibrated_ Measurement. Quantification Type. Code
<span id="TolerancePercent">TolerancePercent</span> | xsd:decimal | The percent of tolerance of this calibrated measurement. | UN01013538 | Calibrated_ Measurement. Tolerance. Percent


<h1 id="InstructedTemperature">InstructedTemperature</h1>

Type: rdf:Class

Definition: Temperature settings instructed for storage or movement of goods.

Unique UN Assigned ID: UN01008871

Dictionary Entry Name: Instructed_ Temperature. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="InstructedTemperatureMinimumValue">InstructedTemperatureMinimumValue</span> | xsd:decimal | The measure of the minimum value of this instructed temperature. | UN01008873 | Instructed_ Temperature. Minimum_ Value. Measure


<h1 id="TransportSettingTemperature">TransportSettingTemperature</h1>

Type: rdf:Class

Definition: Temperature settings for a transport movement, such as a required storage temperature range.

Unique UN Assigned ID: UN01004746

Dictionary Entry Name: Transport Setting_ Temperature. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="TransportSettingTemperatureValue">TransportSettingTemperatureValue</span> | xsd:decimal | The measure of the value of this transport setting temperature, such as a temperature value of ten degrees Celsius. | UN01004747 | Transport Setting_ Temperature. Value. Measure
<span id="TransportSettingTemperatureMinimumValue">TransportSettingTemperatureMinimumValue</span> | xsd:decimal | The measure of the lowest value of this transport setting temperature, such as a minimum temperature value of four degrees Celsius. | UN01004748 | Transport Setting_ Temperature. Minimum_ Value. Measure
<span id="Instructions">Instructions</span> | [edi3:TemperatureSettingInstructions](#TemperatureSettingInstructions) | Informational instructions for achieving, maintaining, using or responding to this transport setting temperature. | UN01004751 | Transport Setting_ Temperature. Information. Temperature Setting_ Instructions
<span id="TransportSettingTemperatureMaximumValue">TransportSettingTemperatureMaximumValue</span> | xsd:decimal | The measure of the highest value of this transport setting temperature, such as a maximum temperature value of fourteen degrees Celsius. | UN01004749 | Transport Setting_ Temperature. Maximum_ Value. Measure


<h1 id="SpecifiedTemperature">SpecifiedTemperature</h1>

Type: rdf:Class

Definition: A specified temperature value or range of values.

Unique UN Assigned ID: UN01009043

Dictionary Entry Name: Specified_ Temperature. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="SpecifiedTemperatureMinimumValue">SpecifiedTemperatureMinimumValue</span> | xsd:decimal | The measure of the lowest value of a range for this specified temperature, such as a minimum temperature value of four degrees Celsius. | UN01009045 | Specified_ Temperature. Minimum_ Value. Measure
<span id="SpecifiedTemperatureMaximumValue">SpecifiedTemperatureMaximumValue</span> | xsd:decimal | The measure of the highest value of a range for this specified temperature, such as a maximum temperature value of fourteen degrees Celsius. | UN01009046 | Specified_ Temperature. Maximum_ Value. Measure


<h1 id="Emission">Emission</h1>

Type: rdf:Class

Definition: A calculation of the pollution (including noise, heat, and radiation etc.) discharged into the environment by a residential, commercial, or industrial facility or by a means of transport, such as a vessel, aircraft or truck.

Unique UN Assigned ID: UN01010051

Dictionary Entry Name: Calculated_ Emission. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="PollutionMeasure">PollutionMeasure</span> | xsd:decimal | A measure of the pollution calculated for this emission. | UN01010055 | Calculated_ Emission. Pollution. Measure
<span id="EmissionWeight">EmissionWeight</span> | xsd:decimal | A weight for which this calculated emission is measured. | UN01010054 | Calculated_ Emission. Weight. Measure
<span id="AffectedDistanceMeasure">AffectedDistanceMeasure</span> | xsd:decimal | The affected distance over which this calculated emission is measured. | UN01010053 | Calculated_ Emission. Affected_ Distance. Measure


<h1 id="Standard">Standard</h1>

Type: rdf:Class

Definition: A referenced norm or requirement that establishes uniform criteria, methods, processes and practices, such as in engineering or technical areas.

Unique UN Assigned ID: UN01008540

Dictionary Entry Name: Referenced_ Standard. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="StandardURI">StandardURI</span> | xsd:token | The Uniform Resource Identifier (URI) for this referenced standard. | UN01008544 | Referenced_ Standard. URI. Identifier
<span id="PartID">PartID</span> | xsd:token | The identifier of a part of this referenced standard, such as a section or topic. | UN01008545 | Referenced_ Standard. Part_ Identification. Identifier
<span id="ElementVersionID">ElementVersionID</span> | xsd:token | The identifier of the version of a specific element within the referenced standard, such as the version of a data element. | UN01008543 | Referenced_ Standard. Element Version. Identifier
<span id="AgencyID">AgencyID</span> | xsd:token | The identifier of the agency for this referenced standard. | UN01008546 | Referenced_ Standard. Agency. Identifier
<span id="StandardVersionID">StandardVersionID</span> | xsd:token | The identifier of the version of this referenced standard. | UN01008542 | Referenced_ Standard. Version. Identifier


<h1 id="PaymentTerms">PaymentTerms</h1>

Type: rdf:Class

Definition: Terms and conditions by which payment has been or will be made for trade purposes.

Unique UN Assigned ID: UN01001672

Dictionary Entry Name: Trade_ Payment Terms. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="PaymentTermsInstructionCode">PaymentTermsInstructionCode</span> | xsd:token | A code specifying an instruction for these trade payment terms. | UN01005363 | Trade_ Payment Terms. Instruction. Code
<span id="PartialPaymentPercent">PartialPaymentPercent</span> | xsd:decimal | A partial payment, expressed as a percent, in these trade payment terms. | UN01006047 | Trade_ Payment Terms. Partial Payment. Percent
<span id="PaymentTermsDescription">PaymentTermsDescription</span> | xsd:string | A textual description of these trade payment terms. | UN01004631 | Trade_ Payment Terms. Description. Text
<span id="SettlementPeriodMeasure">SettlementPeriodMeasure</span> | xsd:decimal | The measure of the number of settlement periods from this trade payment term time reference to the latest payment date, such as 30 days, 3 months. | UN01001675 | Trade_ Payment Terms. Settlement Period. Measure
<span id="PaymentTermsID">PaymentTermsID</span> | xsd:token | The unique identifier of these trade payment terms. | UN01001673 | Trade_ Payment Terms. Identification. Identifier
<span id="PaymentTermsDueDateTime">PaymentTermsDueDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value of the due date specified by these trade payment terms. | UN01012587 | Trade_ Payment Terms. Due. Date Time
<span id="DirectDebitMandateID">DirectDebitMandateID</span> | xsd:token | An identifier of a direct debit mandate in these trade payment terms. | UN01006046 | Trade_ Payment Terms. Direct Debit Mandate_ Identification. Identifier
<span id="PaymentPenaltyTerms">PaymentPenaltyTerms</span> | [edi3:PaymentPenaltyTerms](#PaymentPenaltyTerms) | Trade payment penalty terms applicable to these trade payment terms. | UN01004639 | Trade_ Payment Terms. Applicable. Trade_ Payment Penalty Terms
<span id="InstructionTypeCode">InstructionTypeCode</span> | xsd:token | A code specifying a type of instruction for these trade payment terms. | UN01004638 | Trade_ Payment Terms. Instruction_ Type. Code
<span id="TradePaymentMeansID">TradePaymentMeansID</span> | xsd:token | An identifier of a payment means in these trade payment terms. | UN01006048 | Trade_ Payment Terms. Payment Means_ Identification. Identifier
<span id="PaymentDiscountTerms">PaymentDiscountTerms</span> | [edi3:PaymentDiscountTerms](#PaymentDiscountTerms) | Trade payment discount terms applicable to these trade payment terms. | UN01004640 | Trade_ Payment Terms. Applicable. Trade_ Payment Discount Terms
<span id="PaymentTermsPayee">PaymentTermsPayee</span> | [edi3:TradeParty](#TradeParty) | A payee party in these trade payment terms. | UN01009067 | Trade_ Payment Terms. Payee. Trade_ Party
<span id="FromEventCode">FromEventCode</span> | xsd:token | The code specifying the event from which these trade payment terms are offered for a length of time. | UN01001674 | Trade_ Payment Terms. From Event. Code
<span id="DeprecatedDueDateDateTime">DeprecatedDueDateDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value for a due date specified by these trade payment terms. | UN01004632 | Trade_ Payment Terms. Due Date. Date Time
<span id="PaymentTermsTypeCode">PaymentTermsTypeCode</span> | xsd:token | A code specifying the type of trade payment terms. | UN01004634 | Trade_ Payment Terms. Type. Code


<h1 id="GeographicalFeature">GeographicalFeature</h1>

Type: rdf:Class

Definition: Representation of real world phenomenon associated with a location relative to the Earth, such as cities, buildings, roads, rivers, forests and lakes.

Unique UN Assigned ID: UN01012168

Dictionary Entry Name: Specified_ Geographical Feature. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="GeographicalFeatureName">GeographicalFeatureName</span> | xsd:string | The name, expressed as text, of this specified geographical feature. | UN01012170 | Specified_ Geographical Feature. Name. Text
<span id="CollectionIndicator">CollectionIndicator</span> | xsd:boolean | The indication of whether or not this specified geographical feature is a collection of features. | UN01013616 | Specified_ Geographical Feature. Collection. Indicator
<span id="GeographicalFeatureUsedCSEngineeringCoordinateReferenceSystem">GeographicalFeatureUsedCSEngineeringCoordinateReferenceSystem</span> | [edi3:CSEngineeringCoordinateReferenceSystem](#CSEngineeringCoordinateReferenceSystem) | The CS (Coordinate System) engineering coordinate reference system used for this specified geographical feature. | UN01013619 | Specified_ Geographical Feature. Used. CS Engineering_ Coordinate Reference System
<span id="GeographicalFeatureGeographicalLine">GeographicalFeatureGeographicalLine</span> | [edi3:GeographicalLine](#GeographicalLine) | The geographical line included in this geographical feature. | UN01012173 | Specified_ Geographical Feature. Included. Specified_ Geographical Line
<span id="GeographicalFeatureUsedGeographicalCoordinateSourceSystem">GeographicalFeatureUsedGeographicalCoordinateSourceSystem</span> | [edi3:CoordinateSourceSystem](#CoordinateSourceSystem) | The geographical coordinate source system used for this specified geographical feature. | UN01013620 | Specified_ Geographical Feature. Used. Geographical_ Coordinate Source System
<span id="IncludedCircle">IncludedCircle</span> | [edi3:Circle](#Circle) | A circle included in this specified geographical feature. | UN01013621 | Specified_ Geographical Feature. Included. Specified_ Circle
<span id="GeographicalMultiCurve">GeographicalMultiCurve</span> | [edi3:GeographicalMultiCurve](#GeographicalMultiCurve) | The geographical multi-curve included in this geographical feature. | UN01012176 | Specified_ Geographical Feature. Included. Specified_ Geographical Multi-Curve
<span id="GeographicalFeaturePolygon">GeographicalFeaturePolygon</span> | [edi3:Polygon](#Polygon) | The polygon included in this geographical feature. | UN01012178 | Specified_ Geographical Feature. Included. Specified_ Polygon
<span id="GeographicalFeatureID">GeographicalFeatureID</span> | xsd:token | The identifier for this specified geographical feature. | UN01013615 | Specified_ Geographical Feature. Identification. Identifier
<span id="GeographicalGrid">GeographicalGrid</span> | [edi3:GeographicalGrid](#GeographicalGrid) | The geographical grid included in this geographical feature. | UN01012179 | Specified_ Geographical Feature. Included. Specified_ Geographical Grid
<span id="GeographicalSurface">GeographicalSurface</span> | [edi3:GeographicalSurface](#GeographicalSurface) | The geographical surface included in this geographical feature. | UN01012174 | Specified_ Geographical Feature. Included. Specified_ Geographical Surface
<span id="GeographicalFeatureGeographicalPoint">GeographicalFeatureGeographicalPoint</span> | [edi3:GeographicalPoint](#GeographicalPoint) | The geographical point included in this geographical feature. | UN01012172 | Specified_ Geographical Feature. Included. Specified_ Geographical Point
<span id="GeographicalFeatureDescription">GeographicalFeatureDescription</span> | xsd:string | The textual description of this specified geographical feature. | UN01012169 | Specified_ Geographical Feature. Description. Text
<span id="GeographicalMultiPoint">GeographicalMultiPoint</span> | [edi3:GeographicalMultiPoint](#GeographicalMultiPoint) | The geographical multi-point included in this geographical feature. | UN01012175 | Specified_ Geographical Feature. Included. Specified_ Geographical Multi-Point
<span id="GeographicalMultiSurface">GeographicalMultiSurface</span> | [edi3:GeographicalMultiSurface](#GeographicalMultiSurface) | The geographical multi-surface included in this geographical feature. | UN01012177 | Specified_ Geographical Feature. Included. Specified_ Geographical Multi-Surface


<h1 id="Segment">Segment</h1>

Type: rdf:Class

Definition: The parts into which a segment is or may be divided.

Unique UN Assigned ID: UN01012735

Dictionary Entry Name: Section_ Segment. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="SegmentID">SegmentID</span> | xsd:token | The identifier of this section segment. | UN01012736 | Section_ Segment. Identification. Identifier
<span id="ImageBinaryObject">ImageBinaryObject</span> | xsd:base64Binary | The image, expressed as a binary object, for this section segment. | UN01012739 | Section_ Segment. Image. Binary Object
<span id="SegmentInformationText">SegmentInformationText</span> | xsd:string | Information, expressed as text, in this section segment. | UN01012738 | Section_ Segment. Information. Text


<h1 id="ReferencedConsignmentItem">ReferencedConsignmentItem</h1>

Type: rdf:Class

Definition: A reference to an item within a supply chain consignment of goods separately identified for transport and customs purposes.

Unique UN Assigned ID: UN01004035

Dictionary Entry Name: Referenced_ Supply Chain_ Consignment Item. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="ReferencedConsignmentItemCargoNatureIdentification">ReferencedConsignmentItemCargoNatureIdentification</span> | [edi3:Cargo](#Cargo) | Transport cargo details of this referenced supply chain consignment item sufficient to identify its nature for customs, statistical or transport purposes. | UN01011045 | Referenced_ Supply Chain_ Consignment Item. Nature Identification. Transport_ Cargo
<span id="ReferencedConsignmentItemSequenceNumber">ReferencedConsignmentItemSequenceNumber</span> | xsd:decimal | The sequence number for this referenced supply chain consignment item. | UN01004036 | Referenced_ Supply Chain_ Consignment Item. Sequence. Numeric
<span id="ReferencedConsignmentItemTradeLineItem">ReferencedConsignmentItemTradeLineItem</span> | [edi3:SupplyChainTradeLineItem](#SupplyChainTradeLineItem) | A trade line item included in this referenced supply chain consignment item. | UN01011044 | Referenced_ Supply Chain_ Consignment Item. Included. Supply Chain_ Trade Line Item
<span id="ReferencedConsignmentItemTradeLineItemQuantity">ReferencedConsignmentItemTradeLineItemQuantity</span> | xsd:decimal | The number of trade line items in this referenced supply chain consignment item. | UN01011042 | Referenced_ Supply Chain_ Consignment Item. Trade Line Item. Quantity
<span id="ReferencedConsignmentItemGoodsTypeCode">ReferencedConsignmentItemGoodsTypeCode</span> | xsd:token | The code specifying the type of referenced supply chain consignment item. | UN01004037 | Referenced_ Supply Chain_ Consignment Item. Type. Code
<span id="ReferencedConsignmentItemTransportPackage">ReferencedConsignmentItemTransportPackage</span> | [edi3:Package](#Package) | A transport package for this referenced supply chain consignment item. | UN01011043 | Referenced_ Supply Chain_ Consignment Item. Transport. Logistics_ Package
<span id="ReferencedConsignmentItemAssociatedTransportEquipment">ReferencedConsignmentItemAssociatedTransportEquipment</span> | [edi3:ReferencedTransportEquipment](#ReferencedTransportEquipment) | A piece of transport equipment associated with this referenced supply chain consignment item. | UN01011047 | Referenced_ Supply Chain_ Consignment Item. Associated. Referenced_ Logistics_ Transport Equipment
<span id="ReferencedConsignmentItemTransportDangerousGoods">ReferencedConsignmentItemTransportDangerousGoods</span> | [edi3:DangerousGoods](#DangerousGoods) | Dangerous goods transport details applicable to this referenced supply chain consignment item. | UN01011531 | Referenced_ Supply Chain_ Consignment Item. Applicable. Transport_ Dangerous Goods
<span id="ReferencedConsignmentItemGoodsTypeExtensionCode">ReferencedConsignmentItemGoodsTypeExtensionCode</span> | xsd:token | The code used as an extension to the type code for further specifying the type of referenced supply chain consignment item. | UN01004038 | Referenced_ Supply Chain_ Consignment Item. Type Extension. Code
<span id="ReferencedConsignmentItemAssociatedDocument">ReferencedConsignmentItemAssociatedDocument</span> | [edi3:Document](#Document) | A referenced document associated with this referenced supply chain consignment item. | UN01004039 | Referenced_ Supply Chain_ Consignment Item. Associated. Referenced_ Document


<h1 id="ConsignmentItem">ConsignmentItem</h1>

Type: rdf:Class

Definition: An item within a supply chain consignment of goods separately identified for transport and customs purposes.

Unique UN Assigned ID: UN01004103

Dictionary Entry Name: Supply Chain_ Consignment Item. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="ConsignmentItemApplicableNote">ConsignmentItemApplicableNote</span> | [edi3:Note](#Note) | A note providing information applicable to this supply chain consignment item. | UN01012577 | Supply Chain_ Consignment Item. Applicable. Note
<span id="ConsignmentItemHandlingInstructions">ConsignmentItemHandlingInstructions</span> | [edi3:HandlingInstructions](#HandlingInstructions) | Handling instructions for this supply chain consignment item. | UN01004132 | Supply Chain_ Consignment Item. Handling. Handling_ Instructions
<span id="ConsignmentItemDestinationCountry">ConsignmentItemDestinationCountry</span> | [edi3:Country](#Country) | The destination country for this supply chain consignment item. | UN01004141 | Supply Chain_ Consignment Item. Destination. Trade_ Country
<span id="ConsignmentItemCrossBorderRegulatoryProcedure">ConsignmentItemCrossBorderRegulatoryProcedure</span> | [edi3:RegulatoryProcedure](#RegulatoryProcedure) | A cross-border regulatory procedure applicable to this supply chain consignment item. | UN01006188 | Supply Chain_ Consignment Item. Applicable. Cross-Border_ Regulatory Procedure
<span id="ServiceCharge">ServiceCharge</span> | [edi3:ServiceCharge](#ServiceCharge) | A logistics service charge applicable to this supply chain consignment item. | UN01004154 | Supply Chain_ Consignment Item. Applicable. Logistics_ Service Charge
<span id="ConsignmentItemOriginGeopoliticalRegion">ConsignmentItemOriginGeopoliticalRegion</span> | [edi3:GeopoliticalRegion](#GeopoliticalRegion) | The geopolitical region of origin for this supply chain consignment item. | UN01004137 | Supply Chain_ Consignment Item. Origin. Trade_ Geopolitical Region
<span id="ConsignmentItemNetWeight">ConsignmentItemNetWeight</span> | xsd:decimal | A measure of the net weight (mass) of this supply chain consignment item which excludes all packaging. | UN01004122 | Supply Chain_ Consignment Item. Net Weight. Measure
<span id="ConsignmentItemDamageRemark">ConsignmentItemDamageRemark</span> | xsd:string | Damage remarks, expressed as text, for this supply chain consignment item. | UN01004127 | Supply Chain_ Consignment Item. Damage Remarks. Text
<span id="ConsignmentItemInsuranceValueAmount">ConsignmentItemInsuranceValueAmount</span> | xsd:decimal | The monetary value of this supply chain consignment item as covered by an insurance policy. | UN01004117 | Supply Chain_ Consignment Item. Insurance Value. Amount
<span id="ConsignmentItemCargoToleranceInformation">ConsignmentItemCargoToleranceInformation</span> | xsd:string | Cargo tolerance information, expressed as text, for this supply chain consignment item. | UN01004129 | Supply Chain_ Consignment Item. Cargo Tolerance_ Information. Text
<span id="SecondTypeExtensionCode">SecondTypeExtensionCode</span> | xsd:token | The code used as a second extension to the type code for further specifying the type of supply chain consignment item. | UN01004109 | Supply Chain_ Consignment Item. Second_ Type Extension. Code
<span id="ConsignmentItemDeliveryEvent">ConsignmentItemDeliveryEvent</span> | [edi3:Event](#Event) | The delivery event for this supply chain consignment item. | UN01004156 | Supply Chain_ Consignment Item. Delivery. Transport_ Event
<span id="ConsignmentItemFOBAmount">ConsignmentItemFOBAmount</span> | xsd:decimal | The monetary value for this supply chain consignment item as calculated under FOB (Free On Board) delivery terms. | UN01004116 | Supply Chain_ Consignment Item. FOB. Amount
<span id="ConsignmentItemDeclaredValueForCustomsAmount">ConsignmentItemDeclaredValueForCustomsAmount</span> | xsd:decimal | The monetary value of this supply chain consignment item as declared for customs purposes. | UN01004113 | Supply Chain_ Consignment Item. Declared Value For Customs. Amount
<span id="ConsignmentItemTransportPackage">ConsignmentItemTransportPackage</span> | [edi3:Package](#Package) | A transport package for this supply chain consignment item. | UN01004152 | Supply Chain_ Consignment Item. Transport. Logistics_ Package
<span id="ConsignmentItemBorderClearanceInstructions">ConsignmentItemBorderClearanceInstructions</span> | [edi3:TransportInstructions](#TransportInstructions) | Border clearance instructions for this supply chain consignment item. | UN01009000 | Supply Chain_ Consignment Item. Border Clearance. Transport_ Instructions
<span id="ConsignmentItemShippingMarks">ConsignmentItemShippingMarks</span> | [edi3:ShippingMarks](#ShippingMarks) | Physical logistics shipping marks and barcode information for this supply chain consignment item. | UN01004135 | Supply Chain_ Consignment Item. Physical. Logistics_ Shipping Marks
<span id="ConsignmentItemTransportDangerousGoods">ConsignmentItemTransportDangerousGoods</span> | [edi3:DangerousGoods](#DangerousGoods) | Dangerous goods transport details applicable to this supply chain consignment item. | UN01004131 | Supply Chain_ Consignment Item. Applicable. Transport_ Dangerous Goods
<span id="ConsignmentItemDespatchParty">ConsignmentItemDespatchParty</span> | [edi3:TradeParty](#TradeParty) | The party from whom this supply chain consignment item will be or has been despatched. | UN01004147 | Supply Chain_ Consignment Item. Despatch. Trade_ Party
<span id="ConsignmentItemGrossWeight">ConsignmentItemGrossWeight</span> | xsd:decimal | A measure of the gross weight (mass) of this supply chain consignment item which includes packaging but excludes any transport equipment. | UN01004121 | Supply Chain_ Consignment Item. Gross Weight. Measure
<span id="ImportTypeCode">ImportTypeCode</span> | xsd:token | The code specifying the import type of supply chain consignment item. | UN01004112 | Supply Chain_ Consignment Item. Import_ Type. Code
<span id="ConsignmentItemPackageTypeText">ConsignmentItemPackageTypeText</span> | xsd:string | A package type, expressed as text, for this supply chain consignment item. | UN01010140 | Supply Chain_ Consignment Item. Package Type. Text
<span id="ConsignmentItemDeclaredValueForCarriageAmount">ConsignmentItemDeclaredValueForCarriageAmount</span> | xsd:decimal | The monetary value of this supply chain consignment item as declared by the shipper or his agent for the purpose of varying the carrier's level of liability from that provided in the contract of carriage, in case of loss or damage to goods or delayed delivery. | UN01004114 | Supply Chain_ Consignment Item. Declared Value For Carriage. Amount
<span id="NationalTypeExtensionCode">NationalTypeExtensionCode</span> | xsd:token | The code used as a national extension to the type code for further specifying the type of supply chain consignment item. | UN01004110 | Supply Chain_ Consignment Item. National_ Type Extension. Code
<span id="InvoiceAmount">InvoiceAmount</span> | xsd:decimal | A monetary value for an invoice for this supply chain consignment item. | UN01004118 | Supply Chain_ Consignment Item. Invoice. Amount
<span id="FirstTypeExtensionCode">FirstTypeExtensionCode</span> | xsd:token | The code used as a first extension to the type code for further specifying the type of supply chain consignment item. | UN01004108 | Supply Chain_ Consignment Item. First_ Type Extension. Code
<span id="ConsignmentItemCustomsValuation">ConsignmentItemCustomsValuation</span> | [edi3:CustomsValuation](#CustomsValuation) | A customs valuation applicable to this supply chain consignment item. | UN01008998 | Supply Chain_ Consignment Item. Applicable. Cross-Border_ Customs Valuation
<span id="ConsignmentItemPreviousAdministrativeDocument">ConsignmentItemPreviousAdministrativeDocument</span> | [edi3:Document](#Document) | A previous administrative referenced document for this supply chain consignment item. | UN01012576 | Supply Chain_ Consignment Item. Previous Administrative. Referenced_ Document
<span id="ConsignmentItemDimensions">ConsignmentItemDimensions</span> | [edi3:SpatialDimension](#SpatialDimension) | The linear spatial dimensions of this supply chain consignment item. | UN01004136 | Supply Chain_ Consignment Item. Linear. Spatial_ Dimension
<span id="ConsignmentItemQuarantineInstructions">ConsignmentItemQuarantineInstructions</span> | [edi3:QuarantineInstructions](#QuarantineInstructions) | Quarantine instructions for this supply chain consignment item. | UN01004133 | Supply Chain_ Consignment Item. Quarantine. Quarantine_ Instructions
<span id="ConsignmentItemCargoNatureIdentification">ConsignmentItemCargoNatureIdentification</span> | [edi3:Cargo](#Cargo) | Transport cargo details of this supply chain consignment item sufficient to identify its nature for customs, statistical or transport purposes. | UN01004130 | Supply Chain_ Consignment Item. Nature Identification. Transport_ Cargo
<span id="ConsignmentItemTotalExportExitToImportEntryChargeAmount">ConsignmentItemTotalExportExitToImportEntryChargeAmount</span> | xsd:decimal | The monetary value of the total charge or charges of freight, insurance and other services for this supply chain consignment item calculated from the export exit location to the import entry location. | UN01004120 | Supply Chain_ Consignment Item. Total Export Exit To Import Entry Charge. Amount
<span id="ConsignmentItemGoodsTypeExtensionCode">ConsignmentItemGoodsTypeExtensionCode</span> | xsd:token | The code used as an extension to the type code for further specifying the type of supply chain consignment item. | UN01004107 | Supply Chain_ Consignment Item. Type Extension. Code
<span id="ConsignmentItemAssociatedTransportEquipment">ConsignmentItemAssociatedTransportEquipment</span> | [edi3:ReferencedTransportEquipment](#ReferencedTransportEquipment) | A referenced piece of transport equipment associated with this supply chain consignment item. | UN01004145 | Supply Chain_ Consignment Item. Associated. Referenced_ Logistics_ Transport Equipment
<span id="ImportationCountry">ImportationCountry</span> | [edi3:Country](#Country) | The importation country for this supply chain consignment item. | UN01004142 | Supply Chain_ Consignment Item. Importation. Trade_ Country
<span id="ConsignmentItemExportCountry">ConsignmentItemExportCountry</span> | [edi3:Country](#Country) | The export country for this supply chain consignment item. | UN01004140 | Supply Chain_ Consignment Item. Export. Trade_ Country
<span id="ConsignmentItemTradeLineItemQuantity">ConsignmentItemTradeLineItemQuantity</span> | xsd:decimal | The number of trade line items in this supply chain consignment item. | UN01011069 | Supply Chain_ Consignment Item. Trade Line Item. Quantity
<span id="ConsignmentItemDeclaredForCustomsLocation">ConsignmentItemDeclaredForCustomsLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | The location of this supply chain consignment item as declared for customs. | UN01004144 | Supply Chain_ Consignment Item. Declared For Customs. Logistics_ Location
<span id="ConsignmentItemGrossVolume">ConsignmentItemGrossVolume</span> | xsd:decimal | A measure of the gross volume, normally calculated by multiplying the maximum length, width and height of this supply chain consignment item. | UN01004124 | Supply Chain_ Consignment Item. Gross Volume. Measure
<span id="ConsignmentItemTransportContractDocument">ConsignmentItemTransportContractDocument</span> | [edi3:Document](#Document) | A transport contract document for this supply chain consignment item. | UN01008997 | Supply Chain_ Consignment Item. Transport Contract. Referenced_ Document
<span id="ConsignmentItemVanningEvent">ConsignmentItemVanningEvent</span> | [edi3:Event](#Event) | The vanning event for this supply chain consignment item, i.e. the loading of this consignment item at the place of original despatch. | UN01004158 | Supply Chain_ Consignment Item. Vanning. Transport_ Event
<span id="ConsignmentItemChargeableWeight">ConsignmentItemChargeableWeight</span> | xsd:decimal | A measure of the supply chain consignment item weight on which charges are to be based. | UN01004123 | Supply Chain_ Consignment Item. Chargeable Weight. Measure
<span id="TransportTemperatureSetting">TransportTemperatureSetting</span> | [edi3:TransportSettingTemperature](#TransportSettingTemperature) | The transport temperature setting for this supply chain consignment item. | UN01004134 | Supply Chain_ Consignment Item. Transport. Transport Setting_ Temperature
<span id="ConsignmentItemSpecialInstructions">ConsignmentItemSpecialInstructions</span> | xsd:string | Special instructions, expressed as text, for this supply chain consignment item. | UN01004125 | Supply Chain_ Consignment Item. Special Instructions. Text
<span id="ExportTypeCode">ExportTypeCode</span> | xsd:token | The code specifying the export type of supply chain consignment item. | UN01004111 | Supply Chain_ Consignment Item. Export_ Type. Code
<span id="ConsignmentItemDeliveryInstructions">ConsignmentItemDeliveryInstructions</span> | xsd:string | Delivery instructions, expressed as text, for this supply chain consignment item. | UN01004126 | Supply Chain_ Consignment Item. Delivery Instructions. Text
<span id="ConsignmentItemAssociatedDocument">ConsignmentItemAssociatedDocument</span> | [edi3:Document](#Document) | A referenced document associated with this supply chain consignment item. | UN01004149 | Supply Chain_ Consignment Item. Associated. Referenced_ Document
<span id="ConsignmentItemLoadingLength">ConsignmentItemLoadingLength</span> | xsd:decimal | The measure of the loading length of this supply chain consignment item. | UN01008996 | Supply Chain_ Consignment Item. Loading Length. Measure
<span id="ConsignmentItemSequenceNumber">ConsignmentItemSequenceNumber</span> | xsd:decimal | The sequence number for this supply chain consignment item. | UN01004105 | Supply Chain_ Consignment Item. Sequence. Numeric
<span id="ConsignmentItemManufacturer">ConsignmentItemManufacturer</span> | [edi3:TradeParty](#TradeParty) | The party which manufactured this supply chain consignment item. | UN01004146 | Supply Chain_ Consignment Item. Manufacturer. Trade_ Party
<span id="ConsignmentItemDeliveryParty">ConsignmentItemDeliveryParty</span> | [edi3:TradeParty](#TradeParty) | The party to whom this supply chain consignment item will be or has been delivered. | UN01004148 | Supply Chain_ Consignment Item. Delivery. Trade_ Party
<span id="ConsignmentItemPackageQuantity">ConsignmentItemPackageQuantity</span> | xsd:decimal | The package quantity for this supply chain consignment item. | UN01010139 | Supply Chain_ Consignment Item. Package. Quantity
<span id="ConsignmentItemInformation">ConsignmentItemInformation</span> | xsd:string | Information, expressed as text, for this supply chain consignment item. | UN01004128 | Supply Chain_ Consignment Item. Information. Text
<span id="ConsignmentItemID">ConsignmentItemID</span> | xsd:token | A unique identifier for this supply chain consignment item. | UN01004104 | Supply Chain_ Consignment Item. Identification. Identifier
<span id="ConsignmentItemGoodsTypeCode">ConsignmentItemGoodsTypeCode</span> | xsd:token | The code specifying the type of supply chain consignment item. | UN01004106 | Supply Chain_ Consignment Item. Type. Code
<span id="TransportMeans">TransportMeans</span> | [edi3:LogisticsTransportMeans](#LogisticsTransportMeans) | The means of transport applicable to this supply chain consignment item. | UN01004150 | Supply Chain_ Consignment Item. Applicable. Logistics_ Transport Means
<span id="ConsignmentItemTradeLineItem">ConsignmentItemTradeLineItem</span> | [edi3:SupplyChainTradeLineItem](#SupplyChainTradeLineItem) | A trade line item included in this supply chain consignment item. | UN01004153 | Supply Chain_ Consignment Item. Included. Supply Chain_ Trade Line Item
<span id="ConsignmentItemReportedLogisticsStatus">ConsignmentItemReportedLogisticsStatus</span> | [edi3:LogisticsStatus](#LogisticsStatus) | A logistics status reported for this supply chain consignment item. | UN01004155 | Supply Chain_ Consignment Item. Reported. Logistics_ Status
<span id="ConsignmentItemTariffQuantity">ConsignmentItemTariffQuantity</span> | xsd:decimal | The tariff quantity in this supply chain consignment item. | UN01009962 | Supply Chain_ Consignment Item. Tariff. Quantity
<span id="ConsignmentItemExportGeopoliticalRegion">ConsignmentItemExportGeopoliticalRegion</span> | [edi3:GeopoliticalRegion](#GeopoliticalRegion) | The geopolitical region of export for this supply chain consignment item. | UN01004138 | Supply Chain_ Consignment Item. Export. Trade_ Geopolitical Region
<span id="DeclaredValueForStatisticsAmount">DeclaredValueForStatisticsAmount</span> | xsd:decimal | The monetary value of this supply chain consignment item as declared for statistical purposes. | UN01004115 | Supply Chain_ Consignment Item. Declared Value For Statistics. Amount
<span id="ConsignmentItemExaminationEvent">ConsignmentItemExaminationEvent</span> | [edi3:Event](#Event) | An examination event for this supply chain consignment item. | UN01004157 | Supply Chain_ Consignment Item. Examination. Transport_ Event
<span id="ConsignmentItemTotalChargeAmount">ConsignmentItemTotalChargeAmount</span> | xsd:decimal | The monetary value of all freight and other service charges for this supply chain consignment item. | UN01004119 | Supply Chain_ Consignment Item. Total Charge. Amount
<span id="ConsignmentItemTransitCountry">ConsignmentItemTransitCountry</span> | [edi3:Country](#Country) | A transit country for this supply chain consignment item. | UN01004143 | Supply Chain_ Consignment Item. Transit. Trade_ Country
<span id="ConsignmentItemPickUpEvent">ConsignmentItemPickUpEvent</span> | [edi3:Event](#Event) | A pick-up transport event for this supply chain consignment item. | UN01008999 | Supply Chain_ Consignment Item. Pick-Up. Transport_ Event
<span id="ConsignmentItemGlobalID">ConsignmentItemGlobalID</span> | xsd:token | A global identifier for this supply chain consignment item. | UN01012575 | Supply Chain_ Consignment Item. Global_ Identification. Identifier


<h1 id="ServiceCharge">ServiceCharge</h1>

Type: rdf:Class

Definition: A charge made for a logistics related service.

Unique UN Assigned ID: UN01003721

Dictionary Entry Name: Logistics_ Service Charge. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="AppliedAmount">AppliedAmount</span> | xsd:decimal | A monetary value applied to this logistics service charge. | UN01003730 | Logistics_ Service Charge. Applied. Amount
<span id="ServiceChargeSpecifiedPaymentMeans">ServiceChargeSpecifiedPaymentMeans</span> | [edi3:PaymentMeans](#PaymentMeans) | The trade settlement payment means specified for this logistics service charge. | UN01008980 | Logistics_ Service Charge. Specified. Trade Settlement_ Payment Means
<span id="AppliedFromLocation">AppliedFromLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | The start location from which this logistics service charge should be applied. | UN01003737 | Logistics_ Service Charge. Applied From. Logistics_ Location
<span id="CalculationBasisText">CalculationBasisText</span> | xsd:string | The basis, expressed as text, on which this logistics service charge is to be calculated, such as by volume or per unit. | UN01003734 | Logistics_ Service Charge. Calculation Basis. Text
<span id="ChargeCategoryCode">ChargeCategoryCode</span> | xsd:token | The code specifying the category of charge for this logistics service charge. | UN01003727 | Logistics_ Service Charge. Charge_ Category. Code
<span id="AllowanceChargeText">AllowanceChargeText</span> | xsd:string | The allowance or charge, expressed as text, for this logistics service charge. | UN01003731 | Logistics_ Service Charge. Allowance Charge. Text
<span id="PaymentPlace">PaymentPlace</span> | [edi3:LogisticsLocation](#LogisticsLocation) | The location of the place of payment of this logistics service charge. | UN01003736 | Logistics_ Service Charge. Payment Place. Logistics_ Location
<span id="CalculationBasisCode">CalculationBasisCode</span> | xsd:token | The code specifying a basis on which this logistics service charge is to be calculated, such as by volume or per unit. | UN01003733 | Logistics_ Service Charge. Calculation Basis. Code
<span id="TariffClassCode">TariffClassCode</span> | xsd:token | The code specifying the tariff class for this logistics service charge which represents an entry in a table of fixed charges [Reference United Nations Code List (UNCL) 5243]. | UN01003725 | Logistics_ Service Charge. Tariff Class. Code
<span id="DisbursementAmount">DisbursementAmount</span> | xsd:decimal | A monetary value of a disbursement for this logistics service charge. | UN01003729 | Logistics_ Service Charge. Disbursement. Amount
<span id="ServiceCategoryCode">ServiceCategoryCode</span> | xsd:token | The code specifying the category of service for this logistics service charge. | UN01003728 | Logistics_ Service Charge. Service_ Category. Code
<span id="AppliedToLocation">AppliedToLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | The end location at which this logistics service charge is no longer to be applied. | UN01003738 | Logistics_ Service Charge. Applied To. Logistics_ Location
<span id="ServiceChargeDescription">ServiceChargeDescription</span> | xsd:string | A textual description of this logistics service charge. | UN01003723 | Logistics_ Service Charge. Description. Text
<span id="ServiceChargePaymentArrangementCode">ServiceChargePaymentArrangementCode</span> | xsd:token | The code specifying the payment arrangement for this logistics service charge [Reference United Nations Code List (UNCL) 4237]. | UN01003724 | Logistics_ Service Charge. Payment Arrangement. Code
<span id="PayingPartyRoleCode">PayingPartyRoleCode</span> | xsd:token | The code specifying the role of the party responsible for paying this logistics service charge. | UN01003732 | Logistics_ Service Charge. Paying Party Role. Code
<span id="FreightInvoiceTypeCode">FreightInvoiceTypeCode</span> | xsd:token | A code specifying a type of freight invoice of this logistics service charge. | UN01005280 | Logistics_ Service Charge. Freight Invoice_ Type. Code
<span id="ServiceChargeCategoryCode">ServiceChargeCategoryCode</span> | xsd:token | The code specifying the category of this logistics service charge [Reference United Nations Code List (UNCL) 5237]. | UN01003726 | Logistics_ Service Charge. Category. Code
<span id="TransportPaymentMethodCode">TransportPaymentMethodCode</span> | xsd:token | The code specifying the transport payment method for this logistics service charge. | UN01003735 | Logistics_ Service Charge. Transport Payment Method. Code
<span id="ServiceChargeID">ServiceChargeID</span> | xsd:token | The unique identifier for this logistics service charge. | UN01003722 | Logistics_ Service Charge. Identification. Identifier


<h1 id="SecurityTag">SecurityTag</h1>

Type: rdf:Class

Definition: A product tag device to provide protection from a peril such as theft.

Unique UN Assigned ID: UN01007301

Dictionary Entry Name: Product_ Security Tag. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="SecurityTagTypeCode">SecurityTagTypeCode</span> | xsd:token | The code specifying the type of this product security tag. | UN01007302 | Product_ Security Tag. Type. Code


<h1 id="Declaration">Declaration</h1>

Type: rdf:Class

Definition: A collection of data for a piece of written, printed or electronic matter that is exchanged between two parties as a formal declaration.

Unique UN Assigned ID: UN01011006

Dictionary Entry Name: Exchanged_ Declaration. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="StatisticalValueAmount">StatisticalValueAmount</span> | xsd:decimal | The monetary value specified for statistical purposes in this exchanged declaration. | UN01011016 | Exchanged_ Declaration. Statistical Value_ Specified. Amount
<span id="Declarant">Declarant</span> | [edi3:TradeParty](#TradeParty) | The trade party acting as the declarant for this exchanged declaration. | UN01011020 | Exchanged_ Declaration. Declarant. Trade_ Party
<span id="DeclarantAgent">DeclarantAgent</span> | [edi3:TradeParty](#TradeParty) | The trade party acting as an agent for the declarant for this exchanged declaration. | UN01011021 | Exchanged_ Declaration. Declarant Agent. Trade_ Party
<span id="ExchangedCrossBorderCustomsValuation">ExchangedCrossBorderCustomsValuation</span> | [edi3:CustomsValuation](#CustomsValuation) | Customs valuation information applicable to this exchanged declaration. | UN01011023 | Exchanged_ Declaration. Applicable. Cross-Border_ Customs Valuation
<span id="DeclarationGrossWeight">DeclarationGrossWeight</span> | xsd:decimal | The gross weight measure specified in this exchanged declaration. | UN01011009 | Exchanged_ Declaration. Gross Weight_ Specified. Measure
<span id="AdditionalStatement">AdditionalStatement</span> | [edi3:Note](#Note) | An additional statement note for this exchanged declaration. | UN01011026 | Exchanged_ Declaration. Additional_ Statement. Note
<span id="ProcedureCode">ProcedureCode</span> | xsd:token | A code specifying a procedure for this exchanged declaration. | UN01011014 | Exchanged_ Declaration. Procedure. Code
<span id="DeclarationReferencedDocument">DeclarationReferencedDocument</span> | [edi3:Document](#Document) | A referenced document associated with this exchanged declaration. | UN01011027 | Exchanged_ Declaration. Associated. Referenced_ Document
<span id="TotalPackageQuantity">TotalPackageQuantity</span> | xsd:decimal | The total package quantity specified in this exchanged declaration. | UN01011010 | Exchanged_ Declaration. Total Package_ Specified. Quantity
<span id="DeclarationFormattedIssueDateTime">DeclarationFormattedIssueDateTime</span> | xsd:dateTime | The date, time, date time or other date time value for the issuance of this exchanged declaration. | UN01011008 | Exchanged_ Declaration. Issue. Date Time
<span id="DeclarationTotalInvoiceAmount">DeclarationTotalInvoiceAmount</span> | xsd:decimal | The total invoice monetary value specified in this exchanged declaration. | UN01011017 | Exchanged_ Declaration. Total Invoice_ Specified. Amount
<span id="DeclarationID">DeclarationID</span> | xsd:token | An identifier for this exchanged declaration. | UN01011007 | Exchanged_ Declaration. Identification. Identifier
<span id="FormattedJurisdictionEntryDateTime">FormattedJurisdictionEntryDateTime</span> | xsd:dateTime | The date, time, date time or other date time value when the items which are a subject of this exchanged declaration enter a jurisdiction, such as the actual date of arrival of a means of transport. | UN01011011 | Exchanged_ Declaration. Jurisdiction Entry. Date Time
<span id="DeclarationVersionID">DeclarationVersionID</span> | xsd:token | The identifier for the version of this exchanged declaration. | UN01011012 | Exchanged_ Declaration. Version. Identifier
<span id="SpecificCircumstanceCode">SpecificCircumstanceCode</span> | xsd:token | The code specifying a specific circumstance in this exchanged declaration. | UN01011019 | Exchanged_ Declaration. Specific Circumstance. Code
<span id="CurrencyExchangeRate">CurrencyExchangeRate</span> | xsd:decimal | The rate of currency exchange in this exchanged declaration. | UN01011018 | Exchanged_ Declaration. Currency Exchange. Rate
<span id="DeclarationPreviousReferencedDocument">DeclarationPreviousReferencedDocument</span> | [edi3:Document](#Document) | A previous document referenced for this exchanged declaration. | UN01011024 | Exchanged_ Declaration. Previous. Referenced_ Document
<span id="DeclarationTypeCode">DeclarationTypeCode</span> | xsd:token | The code specifying the type of this exchanged declaration. | UN01011013 | Exchanged_ Declaration. Type. Code
<span id="SubmissionLogisticsLocation">SubmissionLogisticsLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | The submission location for this exchanged declaration. | UN01011022 | Exchanged_ Declaration. Submission. Logistics_ Location
<span id="AssociatedPrincipalParty">AssociatedPrincipalParty</span> | [edi3:TradeParty](#TradeParty) | A principal trade party associated with this exchanged declaration. | UN01011025 | Exchanged_ Declaration. Principal_ Associated. Trade_ Party


<h1 id="DangerousGoods">DangerousGoods</h1>

Type: rdf:Class

Definition: Goods which may contain a substance which poses risks to people and/or the environment during transportation which is regulated by dangerous goods regulations.

Unique UN Assigned ID: UN01004762

Dictionary Entry Name: Transport_ Dangerous Goods. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="PollutantIndicator">PollutantIndicator</span> | xsd:boolean | The indication of whether or not these transported dangerous goods have a pollutant content. | UN01004784 | Transport_ Dangerous Goods. Pollutant. Indicator
<span id="LowerPartOrangeHazardPlacardID">LowerPartOrangeHazardPlacardID</span> | xsd:token | The unique lower part of the orange hazard placard identifier for these transported dangerous goods. | UN01004772 | Transport_ Dangerous Goods. Lower Part Orange Hazard Placard. Identifier
<span id="TREMID">TREMID</span> | xsd:token | The unique TRansport EMergency (TREM) card identifier for these transported dangerous goods. | UN01004770 | Transport_ Dangerous Goods. TREM. Identifier
<span id="HazardTypeCode">HazardTypeCode</span> | xsd:token | A code specifying the type of hazard for these transported dangerous goods. | UN01004779 | Transport_ Dangerous Goods. Hazard Type. Code
<span id="RegulatoryAuthorityName">RegulatoryAuthorityName</span> | xsd:string | The name, expressed as text, for the regulatory authority for these transported dangerous goods. | UN01004764 | Transport_ Dangerous Goods. Regulatory Authority Name. Text
<span id="ReportableQuantity">ReportableQuantity</span> | xsd:decimal | The reportable quantity for these transported dangerous goods. | UN01006210 | Transport_ Dangerous Goods. Reportable. Quantity
<span id="SupplementaryInformation">SupplementaryInformation</span> | xsd:string | Supplementary information, expressed as text, concerning the transport of these dangerous goods. | UN01006208 | Transport_ Dangerous Goods. Supplementary_ Information. Text
<span id="DangerousGoodsGrossWeight">DangerousGoodsGrossWeight</span> | xsd:decimal | The measure of the weight (mass) of these transported dangerous goods including packaging but excluding the transport equipment. | UN01004778 | Transport_ Dangerous Goods. Gross Weight. Measure
<span id="ExplosiveCargoNetWeight">ExplosiveCargoNetWeight</span> | xsd:decimal | The measure of the explosive cargo weight applicable to these transported dangerous goods. | UN01004787 | Transport_ Dangerous Goods. Explosive Cargo_ Net Weight. Measure
<span id="DangerousGoodsMarkingText">DangerousGoodsMarkingText</span> | xsd:string | Marking, expressed as text, for these transported dangerous goods. | UN01004775 | Transport_ Dangerous Goods. Marking. Text
<span id="ExplosiveCompatibilityGroupCode">ExplosiveCompatibilityGroupCode</span> | xsd:token | The code specifying the explosive compatibility group for these transported dangerous goods. | UN01006209 | Transport_ Dangerous Goods. Explosive_ Compatibility Group. Code
<span id="ControlTemperature">ControlTemperature</span> | [edi3:Measurement](#Measurement) | The measurement of the control temperature of these transported dangerous goods. | UN01006222 | Transport_ Dangerous Goods. Control Temperature. Measurement
<span id="MFAGID">MFAGID</span> | xsd:token | The unique Medical First Aid Guide (MFAG) identifier for these transported dangerous goods. | UN01004773 | Transport_ Dangerous Goods. MFAG. Identifier
<span id="PackingInstructionTypeCode">PackingInstructionTypeCode</span> | xsd:token | The code specifying a type of packing instruction for these transported dangerous goods. | UN01004776 | Transport_ Dangerous Goods. Packing Instruction Type. Code
<span id="OverpackInformation">OverpackInformation</span> | xsd:string | Overpack information, expressed as text, for these transported dangerous goods. | UN01006218 | Transport_ Dangerous Goods. Overpack_ Information. Text
<span id="PackagingDangerLevelCode">PackagingDangerLevelCode</span> | xsd:token | The code specifying the level of danger that the packaging of these dangerous goods must cover for transport purposes. | UN01004774 | Transport_ Dangerous Goods. Packaging Danger Level. Code
<span id="UpperPartOrangeHazardPlacardID">UpperPartOrangeHazardPlacardID</span> | xsd:token | The unique upper part of the orange hazard placard identifier for these transported dangerous goods. | UN01004771 | Transport_ Dangerous Goods. Upper Part Orange Hazard Placard. Identifier
<span id="EMSID">EMSID</span> | xsd:token | The unique transport emergency procedure (EMS) identifier applicable for these transported dangerous goods. | UN01004769 | Transport_ Dangerous Goods. EMS. Identifier
<span id="EmergencyTemperature">EmergencyTemperature</span> | [edi3:Measurement](#Measurement) | The measurement of the emergency temperature of these transported dangerous goods. | UN01006223 | Transport_ Dangerous Goods. Emergency Temperature. Measurement
<span id="HazardCategoryCode">HazardCategoryCode</span> | xsd:token | The code specifying the hazard category for these transported dangerous goods. | UN01006213 | Transport_ Dangerous Goods. Hazard_ Category. Code
<span id="DangerousGoodsGrossVolume">DangerousGoodsGrossVolume</span> | xsd:decimal | The measure of the gross volume, normally calculated by multiplying the maximum length, width and height dimensions of these transported dangerous goods. | UN01004783 | Transport_ Dangerous Goods. Gross Volume. Measure
<span id="PollutantLevelCode">PollutantLevelCode</span> | xsd:token | The code specifying the level of pollution of these transported dangerous goods. | UN01004777 | Transport_ Dangerous Goods. Pollutant Level. Code
<span id="UNDGID">UNDGID</span> | xsd:token | The code specifying the unique United Nations Dangerous Goods (UNDG) number assigned to these transported dangerous goods. | UN01004763 | Transport_ Dangerous Goods. UNDG Identification. Code
<span id="DangerousGoodsLogisticsPackage">DangerousGoodsLogisticsPackage</span> | [edi3:Package](#Package) | A logistics package specified for these transported dangerous goods. | UN01013055 | Transport_ Dangerous Goods. Specified. Logistics_ Package
<span id="DangerousGoodsNetWeight">DangerousGoodsNetWeight</span> | xsd:decimal | The measure of the net weight (mass) of these transported dangerous goods. | UN01004786 | Transport_ Dangerous Goods. Net Weight. Measure
<span id="AuthorizationInformation">AuthorizationInformation</span> | xsd:string | Authorization information, expressed as text, for these transported dangerous goods. | UN01006215 | Transport_ Dangerous Goods. Authorization_ Information. Text
<span id="RegulationCode">RegulationCode</span> | xsd:token | The code specifying a regulation applicable to these transported dangerous goods. | UN01004765 | Transport_ Dangerous Goods. Regulation. Code
<span id="SpecialProvisionID">SpecialProvisionID</span> | xsd:token | The unique identifier of the special provision for these transported dangerous goods. | UN01006212 | Transport_ Dangerous Goods. Special Provision. Identifier
<span id="TechnicalName">TechnicalName</span> | xsd:string | A technical name, expressed as text, for these transported dangerous goods. | UN01004767 | Transport_ Dangerous Goods. Technical Name. Text
<span id="AllPackedInOneInformation">AllPackedInOneInformation</span> | xsd:string | All packed in one information, expressed as text, for these transported dangerous goods. | UN01006216 | Transport_ Dangerous Goods. All Packed In One_ Information. Text
<span id="IMDGSegregationGroupCode">IMDGSegregationGroupCode</span> | xsd:token | The code specifying the IMDG (International Maritime Dangerous Goods regulation) segregation group for these transported dangerous goods. | UN01006214 | Transport_ Dangerous Goods. IMDG Segregation Group. Code
<span id="HazardClassVersionID">HazardClassVersionID</span> | xsd:token | The unique identifier of the version of a hazard class for these transported dangerous goods. | UN01004782 | Transport_ Dangerous Goods. Hazard Class Version. Identifier
<span id="TransportExpertContact">TransportExpertContact</span> | [edi3:Contact](#Contact) | The expert to be contacted for details about the transport of these dangerous goods. | UN01004788 | Transport_ Dangerous Goods. Transport Expert. Trade_ Contact
<span id="TransportPackageTypeCode">TransportPackageTypeCode</span> | xsd:token | The code specifying the package type for the transported dangerous goods. | UN01009012 | Transport_ Dangerous Goods. Package Type. Code
<span id="TunnelRestrictionCode">TunnelRestrictionCode</span> | xsd:token | The code specifying the tunnel restriction for these transported dangerous goods. | UN01006211 | Transport_ Dangerous Goods. Tunnel Restriction. Code
<span id="DangerousGoodsTransportEquipment">DangerousGoodsTransportEquipment</span> | [edi3:ReferencedTransportEquipment](#ReferencedTransportEquipment) | Referenced transport equipment associated with the dangerous goods. | UN01009014 | Transport_ Dangerous Goods. Associated. Referenced_ Logistics_ Transport Equipment
<span id="ProperShippingName">ProperShippingName</span> | xsd:string | The proper shipping name, expressed as text, for these transported dangerous goods. | UN01006207 | Transport_ Dangerous Goods. Proper Shipping Name. Text
<span id="HazardClassificationID">HazardClassificationID</span> | xsd:token | The unique identifier of a hazard class applicable to these transported dangerous goods as defined by the relevant governing regulation authority. | UN01004780 | Transport_ Dangerous Goods. Hazard Classification. Identifier
<span id="RegulationName">RegulationName</span> | xsd:string | A name, expressed as text, for a regulation of these transported dangerous goods. | UN01004766 | Transport_ Dangerous Goods. Regulation Name. Text
<span id="FlashpointTemperature">FlashpointTemperature</span> | [edi3:Measurement](#Measurement) | A measurement of the flashpoint temperature of these transported dangerous goods. | UN01004790 | Transport_ Dangerous Goods. Flashpoint Temperature. Measurement
<span id="DangerousGoodsHandlingInstructions">DangerousGoodsHandlingInstructions</span> | [edi3:HandlingInstructions](#HandlingInstructions) | Handling instructions for the transported dangerous goods. | UN01009013 | Transport_ Dangerous Goods. Handling. Handling_ Instructions
<span id="QValueNumber">QValueNumber</span> | xsd:decimal | The number of the Q-Value for these transported dangerous goods. | UN01006217 | Transport_ Dangerous Goods. Q-Value. Numeric
<span id="MarinePollutantIndicator">MarinePollutantIndicator</span> | xsd:boolean | The indication of whether or not these transported dangerous goods have a marine pollutant content. | UN01004785 | Transport_ Dangerous Goods. Marine_ Pollutant. Indicator
<span id="AircraftLimitationInformation">AircraftLimitationInformation</span> | xsd:string | Aircraft limitation information, expressed as text, for these transported dangerous goods. | UN01006219 | Transport_ Dangerous Goods. Aircraft Limitation_ Information. Text
<span id="EmergencyContact">EmergencyContact</span> | [edi3:Contact](#Contact) | The person or department to be contacted in the event of any emergency related to these transported dangerous goods. | UN01004789 | Transport_ Dangerous Goods. Emergency. Trade_ Contact
<span id="ShipperDeclarationInformation">ShipperDeclarationInformation</span> | xsd:string | Shipper declaration information, expressed as text, for these transported dangerous goods. | UN01006221 | Transport_ Dangerous Goods. Shipper Declaration_ Information. Text
<span id="LimitedQuantityCode">LimitedQuantityCode</span> | xsd:token | A code specifying facilitations for transport of limited quantities of these transported dangerous goods. | UN01008331 | Transport_ Dangerous Goods. Limited Quantity. Code
<span id="TransportRadioactiveMaterial">TransportRadioactiveMaterial</span> | [edi3:RadioactiveMaterial](#RadioactiveMaterial) | The radioactive material transported as dangerous goods. | UN01006224 | Transport_ Dangerous Goods. Radioactive. Radioactive_ Material
<span id="AdditionalHazardClassificationID">AdditionalHazardClassificationID</span> | xsd:token | The unique identifier of an additional hazard class applicable to these transported dangerous goods. | UN01004781 | Transport_ Dangerous Goods. Additional_ Hazard Classification. Identifier
<span id="ComplianceDeclarationInformation">ComplianceDeclarationInformation</span> | xsd:string | Compliance declaration information, expressed as text, for these transported dangerous goods. | UN01006220 | Transport_ Dangerous Goods. Compliance Declaration_ Information. Text


<h1 id="QuantityAnalysis">QuantityAnalysis</h1>

Type: rdf:Class

Definition: The quantity analysis for this work item.

Unique UN Assigned ID: UN01000015

Dictionary Entry Name: Work Item_ Quantity Analysis. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="ActualQuantityDimension">ActualQuantityDimension</span> | [edi3:WorkItemDimension](#WorkItemDimension) | A work item dimension of the actual quantity in this work item quantity analysis. | UN01000024 | Work Item_ Quantity Analysis. Actual Quantity. Work Item_ Dimension
<span id="QuantityAnalysisPrimaryClassificationCode">QuantityAnalysisPrimaryClassificationCode</span> | xsd:token | A code specifying a primary classification value for this work item quantity analysis. | UN01000022 | Work Item_ Quantity Analysis. Primary_ Classification. Code
<span id="QuantityAnalysisContractualLanguageCode">QuantityAnalysisContractualLanguageCode</span> | xsd:token | The code specifying the contractual language for this work item quantity analysis. | UN01007570 | Work Item_ Quantity Analysis. Contractual Language. Code
<span id="QuantityAnalysisAlternativeClassificationCode">QuantityAnalysisAlternativeClassificationCode</span> | xsd:token | A code specifying an alternative classification value for this work item quantity analysis. | UN01000023 | Work Item_ Quantity Analysis. Alternative_ Classification. Code
<span id="QuantityAnalysisTypeCode">QuantityAnalysisTypeCode</span> | xsd:token | The code specifying the type of work item quantity analysis. | UN01000021 | Work Item_ Quantity Analysis. Type. Code
<span id="QuantityAnalysisActualQuantity">QuantityAnalysisActualQuantity</span> | xsd:decimal | The actual quantity for this work item quantity analysis. | UN01000017 | Work Item_ Quantity Analysis. Actual. Quantity
<span id="QuantityAnalysisDeprecatedStatusCode">QuantityAnalysisDeprecatedStatusCode</span> | xsd:token | The code specifying the status of this work item quantity analysis, such as partial, approved, not approved. | UN01000020 | Work Item_ Quantity Analysis. Status. Code
<span id="QuantityAnalysisID">QuantityAnalysisID</span> | xsd:token | The unique identifier for this work item quantity analysis. | UN01000016 | Work Item_ Quantity Analysis. Identification. Identifier
<span id="QuantityAnalysisDescription">QuantityAnalysisDescription</span> | xsd:string | The textual description of this work item quantity analysis. | UN01000018 | Work Item_ Quantity Analysis. Description. Text
<span id="QuantityAnalysisChangedRecordedStatus">QuantityAnalysisChangedRecordedStatus</span> | [edi3:RecordedStatus](#RecordedStatus) | A changed recorded status for this work item quantity analysis. | UN01007544 | Work Item_ Quantity Analysis. Changed. Recorded_ Status
<span id="ActualQuantityPercent">ActualQuantityPercent</span> | xsd:decimal | The percentage of a total quantity that the actual quantity of this work item quantity analysis represents. | UN01000019 | Work Item_ Quantity Analysis. Actual Quantity. Percent


<h1 id="CoordinateSourceSystem">CoordinateSourceSystem</h1>

Type: rdf:Class

Definition: Properties defining a geographical coordinate source system used in different places around the world to identify locations on the earth.

Unique UN Assigned ID: UN01013571

Dictionary Entry Name: Geographical_ Coordinate Source System. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="CoordinateSourceSystemToleranceMeasure">CoordinateSourceSystemToleranceMeasure</span> | xsd:decimal | The measure of the tolerance of this geographical coordinate source system. | UN01013574 | Geographical_ Coordinate Source System. Tolerance. Measure
<span id="SignalSourceAvailableQuantity">SignalSourceAvailableQuantity</span> | xsd:decimal | The quantity of signal source available for this geographical coordinate source system. | UN01013576 | Geographical_ Coordinate Source System. Signal Source Available. Quantity
<span id="CoordinateSourceSystemTypeCode">CoordinateSourceSystemTypeCode</span> | xsd:token | The code specifying a type of source for this geographical coordinate source system. | UN01013573 | Geographical_ Coordinate Source System. Source_ Type. Code
<span id="CoordinateSourceSystemID">CoordinateSourceSystemID</span> | xsd:token | The identifier for this geographical coordinate source system. | UN01013572 | Geographical_ Coordinate Source System. Identification. Identifier


<h1 id="Pairing">Pairing</h1>

Type: rdf:Class

Definition: The process by which two potentially communicating entities are linked.

Unique UN Assigned ID: UN01013497

Dictionary Entry Name: Communication_ Pairing. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="TargetEntityID">TargetEntityID</span> | xsd:token | The identifier of the target entity for this communication pairing. | UN01013500 | Communication_ Pairing. Target Entity. Identifier
<span id="PairingMethodCode">PairingMethodCode</span> | xsd:token | The code specifying the method of this communication pairing. | UN01013499 | Communication_ Pairing. Method. Code
<span id="PairedIndicator">PairedIndicator</span> | xsd:boolean | The indication of whether or not the entity is paired in this communication pairing. | UN01013498 | Communication_ Pairing. Paired. Indicator


<h1 id="Condition">Condition</h1>

Type: rdf:Class

Definition: A state that applies to a product characteristic.

Unique UN Assigned ID: UN01008312

Dictionary Entry Name: Product Characteristic_ Condition. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="ConditionName">ConditionName</span> | xsd:string | A name, expressed as text, for this product characteristic condition. | UN01008314 | Product Characteristic_ Condition. Name. Text


<h1 id="ShippingMarks">ShippingMarks</h1>

Type: rdf:Class

Definition: Physical markings or labels on individual packages or transport units for logistics purposes.

Unique UN Assigned ID: UN01003741

Dictionary Entry Name: Logistics_ Shipping Marks. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="MarkingInstructionCode">MarkingInstructionCode</span> | xsd:token | A code specifying a marking instruction for these logistics shipping marks. | UN01003743 | Logistics_ Shipping Marks. Marking Instruction. Code
<span id="RFIDLabel">RFIDLabel</span> | [edi3:Label](#Label) | A Radio Frequency Identification (RFID) label that is a part of these logistics shipping marks. | UN01003745 | Logistics_ Shipping Marks. RFID. Logistics_ Label
<span id="VINLabel">VINLabel</span> | [edi3:Label](#Label) | A Vehicle Identification Number (VIN) label that is a part of these logistics shipping marks. | UN01003746 | Logistics_ Shipping Marks. VIN. Logistics_ Label
<span id="ShippingMarksMarkingText">ShippingMarksMarkingText</span> | xsd:string | Marking, expressed as text, for these logistics shipping marks. | UN01003742 | Logistics_ Shipping Marks. Marking. Text


<h1 id="ReferencedService">ReferencedService</h1>

Type: rdf:Class

Definition: A referenced service associated with a specified event during transport movement.

Unique UN Assigned ID: UN01010074

Dictionary Entry Name: Referenced Transport_ Service. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="ContractID">ContractID</span> | xsd:token | The contract identifier of this referenced transport service. | UN01010076 | Referenced Transport_ Service. Contract_ Identification. Identifier
<span id="ReferencedServiceID">ReferencedServiceID</span> | xsd:token | An identifier of this referenced transport service. | UN01010075 | Referenced Transport_ Service. Identification. Identifier
<span id="ReferencedServiceCategoryTypeCode">ReferencedServiceCategoryTypeCode</span> | xsd:token | A code specifying the category type of this referenced transport service. | UN01010077 | Referenced Transport_ Service. Category_ Type. Code


<h1 id="Service">Service</h1>

Type: rdf:Class

Definition: A service associated with a transport movement.

Unique UN Assigned ID: UN01004837

Dictionary Entry Name: Transport_ Service. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="ServicePriorityCode">ServicePriorityCode</span> | xsd:token | The code specifying the priority of this transport service. | UN01004844 | Transport_ Service. Priority. Code
<span id="ResponsibleParty">ResponsibleParty</span> | [edi3:TradeParty](#TradeParty) | A trade party responsible for this transport service. | UN01010158 | Transport_ Service. Responsible. Trade_ Party
<span id="ServiceURI">ServiceURI</span> | [edi3:UniversalCommunication](#UniversalCommunication) | The Uniform Resource Identifier (URI) communication for this transport service, such as its website or email address. | UN01004849 | Transport_ Service. URI. Universal_ Communication
<span id="ServiceChargeAmount">ServiceChargeAmount</span> | xsd:decimal | The monetary value of the charge for this transport service. | UN01004841 | Transport_ Service. Charge. Amount
<span id="ServiceRequester">ServiceRequester</span> | [edi3:TradeParty](#TradeParty) | A trade party requesting this transport service. | UN01010157 | Transport_ Service. Requester. Trade_ Party
<span id="ConditionTypeCode">ConditionTypeCode</span> | xsd:token | A code specifying a type of condition for this transport service, such as a contract or carriage condition. | UN01004842 | Transport_ Service. Condition_ Type. Code
<span id="ServiceEffectivePeriod">ServiceEffectivePeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The specified period during which this transport service is effective. | UN01004848 | Transport_ Service. Effective. Specified_ Period
<span id="ServiceName">ServiceName</span> | xsd:string | The name, expressed as text, of this transport service. | UN01004840 | Transport_ Service. Name. Text
<span id="ServiceCategoryTypeCode">ServiceCategoryTypeCode</span> | xsd:token | A code specifying a type of category for this transport service. | UN01004843 | Transport_ Service. Category_ Type. Code
<span id="ServiceDescription">ServiceDescription</span> | xsd:string | The textual description of this transport service. | UN01004839 | Transport_ Service. Description. Text
<span id="ServiceID">ServiceID</span> | xsd:token | The unique identifier of this transport service. | UN01004838 | Transport_ Service. Identification. Identifier
<span id="SpecifiedRoute">SpecifiedRoute</span> | [edi3:Route](#Route) | A transport route specified for this transport service. | UN01004847 | Transport_ Service. Specified. Transport_ Route
<span id="ServiceInformationText">ServiceInformationText</span> | xsd:string | Information, expressed as text, for this transport service. | UN01004846 | Transport_ Service. Information. Text
<span id="ServiceRequirementCode">ServiceRequirementCode</span> | xsd:token | A code specifying a service requirement for this transport service. | UN01004845 | Transport_ Service. Service Requirement. Code


<h1 id="RadioactiveMaterial">RadioactiveMaterial</h1>

Type: rdf:Class

Definition: Material capable of undergoing spontaneous nuclear decay involving emission of ionizing radiation in the form of particles or gamma rays.

Unique UN Assigned ID: UN01006194

Dictionary Entry Name: Radioactive_ Material. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="LowDispersibleInformation">LowDispersibleInformation</span> | xsd:string | Information, expressed as text, describing the low dispersion properties of this radioactive material. | UN01006199 | Radioactive_ Material. Low Dispersible_ Information. Text
<span id="RadioactiveMaterialTypeCode">RadioactiveMaterialTypeCode</span> | xsd:token | The code specifying the type of this radioactive material. | UN01006196 | Radioactive_ Material. Type. Code
<span id="TransportIndexNumber">TransportIndexNumber</span> | xsd:decimal | The transport index number of this radioactive material. | UN01006200 | Radioactive_ Material. Transport_ Index. Numeric
<span id="CriticalitySafetyIndexNumber">CriticalitySafetyIndexNumber</span> | xsd:decimal | The criticality safety index number of this radioactive material. | UN01006201 | Radioactive_ Material. Criticality Safety_ Index. Numeric
<span id="SpecialFormInformation">SpecialFormInformation</span> | xsd:string | Information, expressed as text, describing the special form for this radioactive material. | UN01006198 | Radioactive_ Material. Special Form_ Information. Text
<span id="FissileExceptionIndicator">FissileExceptionIndicator</span> | xsd:boolean | The indication of whether or not this radioactive material is a fissile exception. | UN01006202 | Radioactive_ Material. Fissile_ Exception. Indicator
<span id="RadionuclideName">RadionuclideName</span> | xsd:string | The name of the radionuclide, expressed as text, of this radioactive material. | UN01006195 | Radioactive_ Material. Radionuclide_ Name. Text


<h1 id="TransportWasteMaterial">TransportWasteMaterial</h1>

Type: rdf:Class

Definition: Any materials unused and rejected as unwanted during a transport movement.

Unique UN Assigned ID: UN01013160

Dictionary Entry Name: Transport Waste_ Material. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="NextDeliveryEvent">NextDeliveryEvent</span> | [edi3:Event](#Event) | A next delivery event for this transport waste material. | UN01013163 | Transport Waste_ Material. Next_ Delivery. Transport_ Event
<span id="IncludedWasteMaterialComponent">IncludedWasteMaterialComponent</span> | [edi3:MaterialComponent](#MaterialComponent) | A material component included in this transport waste. | UN01013165 | Transport Waste_ Material. Included. Transport Waste_ Material Component
<span id="CompleteDeliveryIndicator">CompleteDeliveryIndicator</span> | xsd:boolean | The indication of whether or not a transport waste material delivery is complete. | UN01013161 | Transport Waste_ Material. Complete Delivery. Indicator
<span id="ReceptionFacilityContact">ReceptionFacilityContact</span> | [edi3:Contact](#Contact) | A reception facility contact for this transport waste material. | UN01013164 | Transport Waste_ Material. Reception_ Facility. Trade_ Contact


<h1 id="Marking">Marking</h1>

Type: rdf:Class

Definition: An inscription, stamp or label on packaging, such as to indicate date, ownership, quality, manufacture or origin.

Unique UN Assigned ID: UN01003919

Dictionary Entry Name: Packaging_ Marking. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="ContentDateTime">ContentDateTime</span> | xsd:dateTime | The date, time, date time or other date time value for the content of this packaging marking. | UN01003922 | Packaging_ Marking. Content. Date Time
<span id="AutomaticDataCaptureMethodTypeCode">AutomaticDataCaptureMethodTypeCode</span> | xsd:token | A code specifying an automatic data capture method type for this packaging marking. | UN01008443 | Packaging_ Marking. Automatic Data Capture Method_ Type. Code
<span id="MarkingTypeCode">MarkingTypeCode</span> | xsd:token | A code specifying a type of packaging marking. | UN01003920 | Packaging_ Marking. Type. Code
<span id="MarkingContentCode">MarkingContentCode</span> | xsd:token | Content, expressed as a code, of this packaging marking. | UN01008444 | Packaging_ Marking. Content. Code
<span id="BarcodeTypeCode">BarcodeTypeCode</span> | xsd:token | A code specifying a type of barcode for this packaging marking. | UN01007183 | Packaging_ Marking. Barcode_ Type. Code
<span id="ContentAmount">ContentAmount</span> | xsd:decimal | Content, expressed as a monetary amount, for this packaging marking. | UN01007182 | Packaging_ Marking. Content. Amount


<h1 id="CargoInsurance">CargoInsurance</h1>

Type: rdf:Class

Definition: Insurance coverage for cargo during transport movements.

Unique UN Assigned ID: UN01004752

Dictionary Entry Name: Transport_ Cargo Insurance. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="CoverageCode">CoverageCode</span> | xsd:token | The code specifying the coverage of this transport cargo insurance. | UN01004753 | Transport_ Cargo Insurance. Coverage. Code
<span id="ContractGeneralConditionsText">ContractGeneralConditionsText</span> | xsd:string | The contract general conditions, expressed as text, for this transport cargo insurance. | UN01004755 | Transport_ Cargo Insurance. Contract General Conditions. Text
<span id="CoverageDescription">CoverageDescription</span> | xsd:string | The textual description of the coverage of this transport cargo insurance. | UN01004754 | Transport_ Cargo Insurance. Coverage Description. Text


<h1 id="LogisticsTransportMeans">LogisticsTransportMeans</h1>

Type: rdf:Class

Definition: The devices used to convey goods or other objects from place to place during logistics cargo movements.

Unique UN Assigned ID: UN01003819

Dictionary Entry Name: Logistics_ Transport Means. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="LogisticsTransportMeansManufacturerParty">LogisticsTransportMeansManufacturerParty</span> | [edi3:TradeParty](#TradeParty) | The manufacturer party for this logistics means of transport. | UN01013603 | Logistics_ Transport Means. Manufacturer. Trade_ Party
<span id="ServiceProvider">ServiceProvider</span> | [edi3:TradeParty](#TradeParty) | A trade party providing services for this logistics means of transport. | UN01010111 | Logistics_ Transport Means. Service Provider. Trade_ Party
<span id="LogisticsTransportMeansTypeCode">LogisticsTransportMeansTypeCode</span> | xsd:token | The code specifying the type of logistics means of transport (Reference UNECE Recommendation 28). | UN01003820 | Logistics_ Transport Means. Type. Code
<span id="LogisticsTransportMeansSequenceNumber">LogisticsTransportMeansSequenceNumber</span> | xsd:decimal | The sequence number differentiating this logistics transport means from others. | UN01010101 | Logistics_ Transport Means. Sequence. Numeric
<span id="ForwardDraughtLevelMeasure">ForwardDraughtLevelMeasure</span> | xsd:decimal | The draught level measured at the fore end of this transport means. | UN01010105 | Logistics_ Transport Means. Forward_ Draught Level. Measure
<span id="LogisticsTransportMeansDriverAccompaniedIndicator">LogisticsTransportMeansDriverAccompaniedIndicator</span> | xsd:boolean | The indication of whether or not this logistics means of transport is accompanied by a driver. | UN01010102 | Logistics_ Transport Means. Driver Accompanied. Indicator
<span id="OwnerAgent">OwnerAgent</span> | [edi3:TradeParty](#TradeParty) | The owner agent trade party for this logistics means of transport. | UN01010116 | Logistics_ Transport Means. Owner Agent. Trade_ Party
<span id="LogisticsTransportMeansGrossWeight">LogisticsTransportMeansGrossWeight</span> | xsd:decimal | The measure of the gross weight (mass) of this logistics means of transport including cargo, such as the measure of the overall size of a vessel determined in accordance with the provisions of the International Convention on Tonnage Measurement of Ships, 1969. | UN01003824 | Logistics_ Transport Means. Gross Weight. Measure
<span id="ConferenceCode">ConferenceCode</span> | xsd:token | The code specifying the conference for this logistics means of transport. | UN01010103 | Logistics_ Transport Means. Conference. Code
<span id="CargoGrossWeight">CargoGrossWeight</span> | xsd:decimal | The measure of the total gross weight (mass) of all cargo loaded onto this logistics means of transport, including packaging but excluding any associated transport equipment. | UN01003828 | Logistics_ Transport Means. Cargo Gross Weight. Measure
<span id="LogisticsTransportMeansApplicableServiceCharge">LogisticsTransportMeansApplicableServiceCharge</span> | [edi3:ServiceCharge](#ServiceCharge) | A service charge, such as a freight charge, applicable to this logistics means of transport. | UN01003832 | Logistics_ Transport Means. Applicable. Logistics_ Service Charge
<span id="CertifiedCalculatedEmission">CertifiedCalculatedEmission</span> | [edi3:Emission](#Emission) | A certified level of pollution calculated for an emission from this logistics transport means. | UN01010115 | Logistics_ Transport Means. Certified. Calculated_ Emission
<span id="ISSCIssuingAuthorityParty">ISSCIssuingAuthorityParty</span> | [edi3:TradeParty](#TradeParty) | The trade party authorized to issue the International Ship Security Certificate (ISSC) for this logistics means of transport. | UN01010117 | Logistics_ Transport Means. ISSC Issuing Authority. Trade_ Party
<span id="OperatorNationalityCountry">OperatorNationalityCountry</span> | [edi3:Country](#Country) | The country of nationality of the operator of this logistics means of transport. | UN01003833 | Logistics_ Transport Means. Operator Nationality. Trade_ Country
<span id="Owner">Owner</span> | [edi3:TradeParty](#TradeParty) | The party owning this logistics means of transport. | UN01003836 | Logistics_ Transport Means. Owner. Trade_ Party
<span id="ManoeuvringSpeed">ManoeuvringSpeed</span> | xsd:decimal | The manoeuvring speed measured for this logistics means of transport. | UN01010104 | Logistics_ Transport Means. Manoeuvring_ Speed. Measure
<span id="TareWeightMeasure">TareWeightMeasure</span> | xsd:decimal | The measure of the tare weight (mass) of this logistics means of transport which is the weight (mass) including permanent equipment but excluding goods and loose accessories. | UN01013600 | Logistics_ Transport Means. Tare Weight. Measure
<span id="ApprovedSecurityPlanOnboardIndicator">ApprovedSecurityPlanOnboardIndicator</span> | xsd:boolean | The indication of whether or not there is an approved security plan onboard this logistics transport means. | UN01013169 | Logistics_ Transport Means. Approved Security Plan Onboard. Indicator
<span id="SpecifiedFault">SpecifiedFault</span> | [edi3:Fault](#Fault) | An identified defect specified for this logistics means of transport. | UN01010118 | Logistics_ Transport Means. Specified. Identified_ Fault
<span id="WasteReportingExemptionIndicator">WasteReportingExemptionIndicator</span> | xsd:boolean | The indication of whether or not there is a waste reporting exemption for this logistics means of transport. | UN01010107 | Logistics_ Transport Means. Waste Reporting Exemption. Indicator
<span id="AftDraughtLevelMeasure">AftDraughtLevelMeasure</span> | xsd:decimal | The draught level measured at the aft end of this transport means. | UN01010106 | Logistics_ Transport Means. Aft_ Draught Level. Measure
<span id="LoadedCargoMeasure">LoadedCargoMeasure</span> | xsd:decimal | The measure of the cargo loaded onto this logistics means of transport, such as the number of barrels of oil or other quantity of breakbulk cargo. | UN01003830 | Logistics_ Transport Means. Loaded Cargo. Measure
<span id="LogisticsTransportMeansTypeText">LogisticsTransportMeansTypeText</span> | xsd:string | The type, expressed as text, of this logistics means of transport. | UN01003821 | Logistics_ Transport Means. Type. Text
<span id="LogisticsTransportMeansNetWeight">LogisticsTransportMeansNetWeight</span> | xsd:decimal | The measure of the net weight (mass) of this logistics means of transport, such as the net tonnage of a vessel determined in accordance with the provisions of the International Convention on Tonnage Measurement of Ships, 1969. | UN01003825 | Logistics_ Transport Means. Net Weight. Measure
<span id="CompanySecurityOfficer">CompanySecurityOfficer</span> | [edi3:TransportPerson](#TransportPerson) | A person who is a company security officer for this logistics transport means. | UN01013171 | Logistics_ Transport Means. Company Security Officer. Transport_ Person
<span id="SpecifiedHandlingInstructions">SpecifiedHandlingInstructions</span> | [edi3:HandlingInstructions](#HandlingInstructions) | Handling instructions specified for this logistics means of transport. | UN01010112 | Logistics_ Transport Means. Specified. Handling_ Instructions
<span id="ISPSSecurityLevelCode">ISPSSecurityLevelCode</span> | xsd:token | The code specifying the International Ship and Port facility Security (ISPS) level assigned to this logistics means of transport. | UN01010109 | Logistics_ Transport Means. ISPS Security Level. Code
<span id="LogisticsTransportMeansAttachedTransportEquipment">LogisticsTransportMeansAttachedTransportEquipment</span> | [edi3:TransportEquipment](#TransportEquipment) | A piece of logistics transport equipment attached to this logistics means of transport. | UN01003831 | Logistics_ Transport Means. Attached. Logistics_ Transport Equipment
<span id="LogisticsTransportMeansManufacturngDateTime">LogisticsTransportMeansManufacturngDateTime</span> | xsd:dateTime | The manufacturing date, time, date time, or other date time value for this logistics means of transport. | UN01013601 | Logistics_ Transport Means. Manufacturing. Date Time
<span id="RequiredTransportService">RequiredTransportService</span> | [edi3:Service](#Service) | A transport service required for this logistics means of transport. | UN01010113 | Logistics_ Transport Means. Required. Transport_ Service
<span id="LogisticsTransportMeansLength">LogisticsTransportMeansLength</span> | xsd:decimal | The measure of the length of this logistics means of transport. | UN01003826 | Logistics_ Transport Means. Length. Measure
<span id="LogisticsTransportMeansName">LogisticsTransportMeansName</span> | xsd:string | The name, expressed as text, of this logistics means of transport. | UN01003823 | Logistics_ Transport Means. Name. Text
<span id="RegistrationEvent">RegistrationEvent</span> | [edi3:Event](#Event) | A registration event of this logistics transport means. | UN01010114 | Logistics_ Transport Means. Registration. Transport_ Event
<span id="SpecifiedSpatialDimension">SpecifiedSpatialDimension</span> | [edi3:SpatialDimension](#SpatialDimension) | Spatial dimensions specified for this logistics means of transport. | UN01010110 | Logistics_ Transport Means. Specified. Spatial_ Dimension
<span id="ISSCDocument">ISSCDocument</span> | [edi3:Document](#Document) | The referenced ISSC (International Ship Security Certificate) document for this logistics transport means. | UN01013170 | Logistics_ Transport Means. ISSC. Referenced_ Document
<span id="HelipadIndicator">HelipadIndicator</span> | xsd:boolean | The indication of whether or not there is a helipad on this logistics means of transport. | UN01010108 | Logistics_ Transport Means. Helipad. Indicator
<span id="RegistrationCountry">RegistrationCountry</span> | [edi3:Country](#Country) | The country of registration of this logistics means of transport. | UN01003834 | Logistics_ Transport Means. Registration. Trade_ Country
<span id="DraughtLevelMeasure">DraughtLevelMeasure</span> | xsd:decimal | The measure of the draught level of this logistics means of transport. | UN01003827 | Logistics_ Transport Means. Draught Level. Measure
<span id="LogisticsTransportMeansID">LogisticsTransportMeansID</span> | xsd:token | An identifier of this logistics means of transport, such as the International Maritime Organization number of a vessel. | UN01003822 | Logistics_ Transport Means. Identification. Identifier
<span id="LogisticsTransportMeansAttachedMonitoringIOTDevice">LogisticsTransportMeansAttachedMonitoringIOTDevice</span> | [edi3:IOTDevice](#IOTDevice) | An IOT device attached to this logistics transport means. | UN01013602 | Logistics_ Transport Means. Attached. Monitoring_ IOT Device
<span id="LogisticsTransportMeansOperator">LogisticsTransportMeansOperator</span> | [edi3:TradeParty](#TradeParty) | The party operating this logistics means of transport. | UN01003835 | Logistics_ Transport Means. Operator. Trade_ Party


<h1 id="TransportMeans">TransportMeans</h1>

Type: rdf:Class

Definition: Reference to a device or method used to convey people, goods, or other objects from place to place.

Unique UN Assigned ID: UN01004049

Dictionary Entry Name: Referenced_ Transport Means. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="TransportMeansDriverAccompaniedIndicator">TransportMeansDriverAccompaniedIndicator</span> | xsd:boolean | The indication of whether or not this referenced means of transport is accompanied by a driver. | UN01010138 | Referenced_ Transport Means. Driver Accompanied. Indicator
<span id="TransportMeansID">TransportMeansID</span> | xsd:token | An identifier of this referenced transport means, such as the International Maritime Organization number for a vessel. | UN01004052 | Referenced_ Transport Means. Identification. Identifier
<span id="TransportMeansName">TransportMeansName</span> | xsd:string | The name, expressed as text, of this referenced transport means, such as the vessel name. | UN01004053 | Referenced_ Transport Means. Name. Text
<span id="TransportMeansTypeCode">TransportMeansTypeCode</span> | xsd:token | The code specifying the type of referenced transport means [Reference UNECE Recommendation 28]. | UN01004050 | Referenced_ Transport Means. Type. Code


<h1 id="ProductInstance">ProductInstance</h1>

Type: rdf:Class

Definition: An individual trade product or batch of similar trade products produced by human or mechanical effort or by a natural process.

Unique UN Assigned ID: UN01004651

Dictionary Entry Name: Trade_ Product Instance. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="SupplierAssignedSerialID">SupplierAssignedSerialID</span> | xsd:token | The unique supplier assigned serial identifier for this trade product instance. | UN01004659 | Trade_ Product Instance. Supplier Assigned Serial_ Identification. Identifier
<span id="ProductionEvent">ProductionEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | The production event for this trade product instance. | UN01004674 | Trade_ Product Instance. Production. Supply Chain_ Event
<span id="GlobalSerialID">GlobalSerialID</span> | xsd:token | The unique global serial identifier for this trade product instance. | UN01004655 | Trade_ Product Instance. Global Serial_ Identification. Identifier
<span id="RegistrationID">RegistrationID</span> | xsd:token | A unique registration identifier, such as a vehicle licence plate identification, for this trade product instance. | UN01007239 | Trade_ Product Instance. Registration_ Identification. Identifier
<span id="KanbanID">KanbanID</span> | xsd:token | The unique kanban identifier for this trade product instance. | UN01004657 | Trade_ Product Instance. Kanban_ Identification. Identifier
<span id="ProductInstanceOriginLocation">ProductInstanceOriginLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | A location of origin for this supply chain product instance. | UN01004665 | Trade_ Product Instance. Origin. Logistics_ Location
<span id="TradeProductCharacteristic">TradeProductCharacteristic</span> | [edi3:Characteristic](#Characteristic) | A product characteristic applicable to this trade product instance. | UN01011926 | Trade_ Product Instance. Applicable. Product_ Characteristic
<span id="BestBeforeDateTime">BestBeforeDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value before which it is best to consume the items contained in this trade product instance. | UN01004662 | Trade_ Product Instance. Best Before. Date Time
<span id="ProductInstanceMaterialGoodsCharacteristic">ProductInstanceMaterialGoodsCharacteristic</span> | [edi3:GoodsCharacteristic](#GoodsCharacteristic) | A distinguishing material feature applicable to this trade product instance. | UN01007240 | Trade_ Product Instance. Applicable. Material_ Goods Characteristic
<span id="ProductInstanceExpiryDateTime">ProductInstanceExpiryDateTime</span> | xsd:dateTime | The date, time, date time, or other date time value of expiry of the items contained in the trade product instance. | UN01004663 | Trade_ Product Instance. Expiry. Date Time
<span id="ProductInstanceActualQuantity">ProductInstanceActualQuantity</span> | xsd:decimal | The actual quantity of items in this trade product instance. | UN01004661 | Trade_ Product Instance. Actual. Quantity
<span id="ProductInstanceInspectionEvent">ProductInstanceInspectionEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | The inspection event for this trade product instance. | UN01004676 | Trade_ Product Instance. Inspection. Supply Chain_ Event
<span id="LotID">LotID</span> | xsd:token | The unique lot identifier for this trade product instance. | UN01004658 | Trade_ Product Instance. Lot_ Identification. Identifier
<span id="ProductInstanceBatchID">ProductInstanceBatchID</span> | xsd:token | The unique batch identifier for this trade product instance. | UN01004656 | Trade_ Product Instance. Batch_ Identification. Identifier
<span id="PackagingEvent">PackagingEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | The packaging event for this trade product instance. | UN01004677 | Trade_ Product Instance. Packaging. Supply Chain_ Event
<span id="SerialID">SerialID</span> | xsd:token | A unique serial identifier for this trade product instance. | UN01005370 | Trade_ Product Instance. Serial_ Identification. Identifier
<span id="TradeProductHandlingProcess">TradeProductHandlingProcess</span> | [edi3:Process](#Process) | A product handling process applied to this trade product instance, such as manufacturing or storage. | UN01004667 | Trade_ Product Instance. Applied. Product Handling_ Process


<h1 id="Contact">Contact</h1>

Type: rdf:Class

Definition: A person or a department that acts as a point of contact with another person or department in a trading relationship.

Unique UN Assigned ID: UN01001640

Dictionary Entry Name: Trade_ Contact. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="ContactTelephone">ContactTelephone</span> | [edi3:UniversalCommunication](#UniversalCommunication) | Telephone communication information for this trade contact. | UN01004564 | Trade_ Contact. Telephone. Universal_ Communication
<span id="InstantMessaging">InstantMessaging</span> | [edi3:UniversalCommunication](#UniversalCommunication) | Instant messaging communication information for this trade contact. | UN01004572 | Trade_ Contact. Instant Messaging. Universal_ Communication
<span id="Telex">Telex</span> | [edi3:UniversalCommunication](#UniversalCommunication) | Telegraphy (Telex) communication information for this trade contact. | UN01004570 | Trade_ Contact. Telex. Universal_ Communication
<span id="ContactDepartmentName">ContactDepartmentName</span> | xsd:string | The name, expressed as text, of the department to which this trade contact belongs within an organization. | UN01001643 | Trade_ Contact. Department Name. Text
<span id="ContactNote">ContactNote</span> | [edi3:Note](#Note) | A note specified for this trade contact. | UN01004573 | Trade_ Contact. Specified. Note
<span id="DirectTelephone">DirectTelephone</span> | [edi3:UniversalCommunication](#UniversalCommunication) | The direct telephone communication information for this trade contact. | UN01004565 | Trade_ Contact. Direct_ Telephone. Universal_ Communication
<span id="PersonID">PersonID</span> | xsd:token | A unique identifier for this trade contact person. | UN01004563 | Trade_ Contact. Person_ Identification. Identifier
<span id="Person">Person</span> | [edi3:ContactPerson](#ContactPerson) | The contact person specified for this trade contact. | UN01008317 | Trade_ Contact. Specified. Contact_ Person
<span id="VOIP">VOIP</span> | [edi3:UniversalCommunication](#UniversalCommunication) | Voice Over Internet Protocol (VOIP) communication information for this trade contact. | UN01004571 | Trade_ Contact. VOIP. Universal_ Communication
<span id="ContactFax">ContactFax</span> | [edi3:UniversalCommunication](#UniversalCommunication) | Fax communication information for this trade contact. | UN01004567 | Trade_ Contact. Fax. Universal_ Communication
<span id="JobTitle">JobTitle</span> | xsd:string | The job title, position or designation, expressed as text, of this trade contact within an organization, such as Director, Software Engineer, Purchasing Manager. | UN01004561 | Trade_ Contact. Job Title. Text
<span id="ResponsibilityText">ResponsibilityText</span> | xsd:string | A responsibility, expressed as text, of this trade contact. | UN01004562 | Trade_ Contact. Responsibility. Text
<span id="ContactID">ContactID</span> | xsd:token | The unique identifier for this trade contact. | UN01001641 | Trade_ Contact. Identification. Identifier
<span id="PersonName">PersonName</span> | xsd:string | The name, expressed as text, of this trade contact person. | UN01001642 | Trade_ Contact. Person Name. Text
<span id="ContactTypeCode">ContactTypeCode</span> | xsd:token | The code specifying the type of trade contact. | UN01001644 | Trade_ Contact. Type. Code
<span id="AuthorizedPersonName">AuthorizedPersonName</span> | xsd:string | The name, expressed as text, of the authorized person for this trade contact. | UN01013395 | Trade_ Contact. Authorized_ Person Name. Text
<span id="ContactMobileTelephone">ContactMobileTelephone</span> | [edi3:UniversalCommunication](#UniversalCommunication) | The mobile telephone communication information for this trade contact. | UN01004566 | Trade_ Contact. Mobile_ Telephone. Universal_ Communication


<h1 id="WorkflowObject">WorkflowObject</h1>

Type: rdf:Class

Definition: An object used in the management of the status changes in a business process.

Unique UN Assigned ID: UN01011930

Dictionary Entry Name: Trade_ Workflow Object. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="PreviousStatusCode">PreviousStatusCode</span> | xsd:token | The code specifying the previous status of this trade workflow object. | UN01011933 | Trade_ Workflow Object. Previous_ Status. Code
<span id="WorkflowObjectID">WorkflowObjectID</span> | xsd:token | The identifier of this trade workflow object. | UN01011931 | Trade_ Workflow Object. Identification. Identifier


<h1 id="Response">Response</h1>

Type: rdf:Class

Definition: A response to a specification query.

Unique UN Assigned ID: UN01000077

Dictionary Entry Name: Specification_ Response. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="ResponseContractualLanguageCode">ResponseContractualLanguageCode</span> | xsd:token | The code specifying the contractual language for this specification response. | UN01007521 | Specification_ Response. Contractual Language. Code
<span id="ResponseContentText">ResponseContentText</span> | xsd:string | The content, expressed as text, of this specification response. | UN01000081 | Specification_ Response. Content. Text
<span id="ResponseID">ResponseID</span> | xsd:token | The unique identifier for this specification response. | UN01000078 | Specification_ Response. Identification. Identifier
<span id="QueryID">QueryID</span> | xsd:token | The unique identifier for the query to which this response refers. | UN01000079 | Specification_ Response. Query_ Identification. Identifier


<h1 id="Equipment">Equipment</h1>

Type: rdf:Class

Definition: Hardware or software typically marketed by a company other than the original manufacturer.

Unique UN Assigned ID: UN01013553

Dictionary Entry Name: OEM_ Equipment. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="EquipmentID">EquipmentID</span> | xsd:token | An identifier of this OEM equipment. | UN01013554 | OEM_ Equipment. Identification. Identifier
<span id="PollingRateMeasure">PollingRateMeasure</span> | xsd:decimal | The measure of the polling rate for this OEM equipment. | UN01013557 | OEM_ Equipment. Polling Rate. Measure
<span id="ApplicablePhysicalCharacteristic">ApplicablePhysicalCharacteristic</span> | [edi3:PhysicalCharacteristic](#PhysicalCharacteristic) | A physical characteristic applicable to this OEM equipment. | UN01013558 | OEM_ Equipment. Applicable. Physical_ Characteristic
<span id="PollingCapabilityIndicator">PollingCapabilityIndicator</span> | xsd:boolean | The indication of whether or not this OEM equipment has a polling capability. | UN01013556 | OEM_ Equipment. Polling Capability. Indicator
<span id="EquipmentTypeCode">EquipmentTypeCode</span> | xsd:token | A code specifying a type of OEM equipment. | UN01013555 | OEM_ Equipment. Type. Code


<h1 id="DirectPositionList">DirectPositionList</h1>

Type: rdf:Class

Definition: The specified list of coordinates for a physical location, expressed as a sequence of direct positions.

Unique UN Assigned ID: UN01012471

Dictionary Entry Name: Specified_ Direct Position List. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="UOMLabelListText">UOMLabelListText</span> | xsd:string | An ordered list of Unit Of Measure (UOM) labels, expressed as text, for this specified direct position list. | UN01012476 | Specified_ Direct Position List. UOM_ Label List. Text
<span id="DirectPositionListAxisLabelListText">DirectPositionListAxisLabelListText</span> | xsd:string | An ordered list of axis labels, expressed as text, for this specified direct position list. | UN01012475 | Specified_ Direct Position List. Axis_ Label List. Text
<span id="DirectPositionListCoordinateText">DirectPositionListCoordinateText</span> | xsd:string | The coordinate, expressed as text, for this specified direct position list. | UN01012472 | Specified_ Direct Position List. Coordinate. Text
<span id="DirectPositionListName">DirectPositionListName</span> | xsd:string | The name, expressed as text, of this specified direct position list. | UN01012473 | Specified_ Direct Position List. Name. Text
<span id="DirectPositionListCount">DirectPositionListCount</span> | xsd:decimal | A count for this specified direct position list. | UN01012477 | Specified_ Direct Position List. Count. Numeric


<h1 id="Schedule">Schedule</h1>

Type: rdf:Class

Definition: A series of planned activities or things to be done in this supply chain.

Unique UN Assigned ID: UN01012978

Dictionary Entry Name: Supply Chain_ Schedule. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="ScheduleDescription">ScheduleDescription</span> | xsd:string | A textual description of this supply chain schedule. | UN01012979 | Supply Chain_ Schedule. Description. Text
<span id="ScheduleID">ScheduleID</span> | xsd:token | An identifier of this supply chain schedule. | UN01012980 | Supply Chain_ Schedule. Identification. Identifier
<span id="ScheduleOccurrenceDateTime">ScheduleOccurrenceDateTime</span> | xsd:dateTime | A date, time, date time, or other date time of an occurrence in this supply chain schedule. | UN01012981 | Supply Chain_ Schedule. Occurrence. Date Time
<span id="ScheduleTypeCode">ScheduleTypeCode</span> | xsd:token | A code specifying the type of supply chain schedule. | UN01012982 | Supply Chain_ Schedule. Type. Code


<h1 id="Clause">Clause</h1>

Type: rdf:Class

Definition: A distinct article or provision in a document, which requires compliance.

Unique UN Assigned ID: UN01002646

Dictionary Entry Name: Document_ Clause. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="ClauseID">ClauseID</span> | xsd:token | The unique identifier of this document clause. | UN01002647 | Document_ Clause. Identification. Identifier
<span id="URL">URL</span> | xsd:token | The Uniform Resource Locator (URL) for this document clause. | UN01013211 | Document_ Clause. URL. Identifier
<span id="AssociatedPeriod">AssociatedPeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | A period of time associated with this document clause. | UN01009042 | Document_ Clause. Associated. Specified_ Period
<span id="ClauseContentText">ClauseContentText</span> | xsd:string | Content, expressed as text, of this document clause. | UN01002648 | Document_ Clause. Content. Text


<h1 id="RegulatedGoods">RegulatedGoods</h1>

Type: rdf:Class

Definition: Articles of trade or commerce which are subject to, or controlled by a rule, regulation, or law at a particular point during their logistics lifecycle.

Unique UN Assigned ID: UN01003711

Dictionary Entry Name: Logistics_ Regulated Goods. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-


<h1 id="SubordinateSubordinateLocation">SubordinateSubordinateLocation</h1>

Type: rdf:Class

Definition: A physical location or place which is a subordinate location of a subordinate location.

Unique UN Assigned ID: UN01004087

Dictionary Entry Name: Subordinate Subordinate_ Location. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="SubordinateSubordinateLocationName">SubordinateSubordinateLocationName</span> | xsd:string | The name, expressed as text, of this subordinate of a subordinate location. | UN01004089 | Subordinate Subordinate_ Location. Name. Text
<span id="SubordinateSubordinateLocationTypeCode">SubordinateSubordinateLocationTypeCode</span> | xsd:token | The code specifying the type of subordinate of a subordinate location. | UN01004090 | Subordinate Subordinate_ Location. Type. Code
<span id="SubordinateSubordinateLocationID">SubordinateSubordinateLocationID</span> | xsd:token | The unique identifier for this subordinate of a subordinate location, such as a United Nations Location Code (UNLOCODE) or GS1 Global Location Number (GLN). | UN01004088 | Subordinate Subordinate_ Location. Identification. Identifier


<h1 id="SubordinateLocation">SubordinateLocation</h1>

Type: rdf:Class

Definition: A physical location or place which is a subordinate location of a location.

Unique UN Assigned ID: UN01004092

Dictionary Entry Name: Subordinate_ Location. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="SubordinateLocationSubordinateLocation">SubordinateLocationSubordinateLocation</span> | [edi3:SubordinateSubordinateLocation](#SubordinateSubordinateLocation) | The location subordinate to this subordinate location. | UN01004097 | Subordinate_ Location. Subordinate. Subordinate Subordinate_ Location
<span id="SubordinateLocationID">SubordinateLocationID</span> | xsd:token | The unique identifier for this subordinate location, such as a United Nations Location Code (UNLOCODE) or GS1 Global Location Number (GLN). | UN01004093 | Subordinate_ Location. Identification. Identifier
<span id="SubordinateLocationName">SubordinateLocationName</span> | xsd:string | The name, expressed as text, of this subordinate location. | UN01004094 | Subordinate_ Location. Name. Text
<span id="SubordinateLocationPhysicalGeographicalCoordinate">SubordinateLocationPhysicalGeographicalCoordinate</span> | [edi3:GeographicalCoordinate](#GeographicalCoordinate) | Physical geographical coordinate information for this subordinate location. | UN01004096 | Subordinate_ Location. Physical. Geographical Coordinate


<h1 id="TradeLocation">TradeLocation</h1>

Type: rdf:Class

Definition: A physical location or place used or referenced for trade purposes.

Unique UN Assigned ID: UN01001658

Dictionary Entry Name: Trade_ Location. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="TradeLocationName">TradeLocationName</span> | xsd:string | The name, expressed as text, of this location used or referenced in trade. | UN01001662 | Trade_ Location. Name. Text
<span id="TradeLocationCountryName">TradeLocationCountryName</span> | xsd:string | The name, expressed as text, of a country location used or referenced in trade. | UN01001660 | Trade_ Location. Country Name. Text
<span id="TradeLocationCountryCode">TradeLocationCountryCode</span> | xsd:token | The unique identifier of a country location used or referenced in trade. | UN01001659 | Trade_ Location. Country. Identifier


<h1 id="TransportServiceLocation">TransportServiceLocation</h1>

Type: rdf:Class

Definition: A location where a transport service takes place.

Unique UN Assigned ID: UN01010086

Dictionary Entry Name: Transport Service_ Location. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="TransportServiceLocationName">TransportServiceLocationName</span> | xsd:string | A name, expressed as text, of this transport service location. | UN01010088 | Transport Service_ Location. Name. Text
<span id="TransportServiceLocationTypeCode">TransportServiceLocationTypeCode</span> | xsd:token | A code specifying the type of transport service location. | UN01010089 | Transport Service_ Location. Type. Code


<h1 id="LogisticsLocation">LogisticsLocation</h1>

Type: rdf:Class

Definition: A logistics related physical location or place.

Unique UN Assigned ID: UN01003679

Dictionary Entry Name: Logistics_ Location. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="LogisticsLocationSubordinateLocation">LogisticsLocationSubordinateLocation</span> | [edi3:SubordinateLocation](#SubordinateLocation) | A location subordinate to this logistics related location. | UN01003687 | Logistics_ Location. Subordinate. Subordinate_ Location
<span id="StayPeriod">StayPeriod</span> | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | A period of stay at this logistics location. | UN01013166 | Logistics_ Location. Stay. Specified_ Period
<span id="LogisticsLocationCountryName">LogisticsLocationCountryName</span> | xsd:string | The country name, expressed as text, of this logistics location. | UN01004896 | Logistics_ Location. Country Name. Text
<span id="LogisticsLocationDescription">LogisticsLocationDescription</span> | xsd:string | A textual description of this logistics related location. | UN01003683 | Logistics_ Location. Description. Text
<span id="LogisticsLocationPostalAddress">LogisticsLocationPostalAddress</span> | [edi3:TradeAddress](#TradeAddress) | The postal trade address information for this logistics related location. | UN01003686 | Logistics_ Location. Postal. Trade_ Address
<span id="GeographicalCoordinates">GeographicalCoordinates</span> | [edi3:GeographicalCoordinate](#GeographicalCoordinate) | Geographical coordinate information for this logistics related location. | UN01003685 | Logistics_ Location. Physical. Geographical Coordinate
<span id="LogisticsLocationAssociatedGeographicalFeature">LogisticsLocationAssociatedGeographicalFeature</span> | [edi3:GeographicalFeature](#GeographicalFeature) | A geographical feature associated with this logistics location. | UN01013608 | Logistics_ Location. Associated. Specified_ Geographical Feature
<span id="LogisticsLocationName">LogisticsLocationName</span> | xsd:string | A name, expressed as text, of this logistics related location. | UN01003681 | Logistics_ Location. Name. Text
<span id="LogisticsLocationPreviousAssociatedGeographicalFeature">LogisticsLocationPreviousAssociatedGeographicalFeature</span> | [edi3:GeographicalFeature](#GeographicalFeature) | A geographical feature previously associated with this logistics location. | UN01013609 | Logistics_ Location. Previous_ Associated. Specified_ Geographical Feature
<span id="LogisticsLocationInspectionEvent">LogisticsLocationInspectionEvent</span> | [edi3:SupplyChainEvent](#SupplyChainEvent) | A supply chain inspection event at this logistics location. | UN01013121 | Logistics_ Location. Inspection. Supply Chain_ Event
<span id="LogisticsLocationID">LogisticsLocationID</span> | xsd:token | A unique identifier for this logistics related location, such as a United Nations Location Code (UNLOCODE) or GS1 Global Location Number (GLN). | UN01003680 | Logistics_ Location. Identification. Identifier
<span id="CountrySubDivisionID">CountrySubDivisionID</span> | xsd:token | The identifier of the country sub-division for this logistics related location. | UN01013369 | Logistics_ Location. Country Sub-Division. Identifier
<span id="ServicingParty">ServicingParty</span> | [edi3:LocationParty](#LocationParty) | A servicing party specified for this logistics related location. | UN01003688 | Logistics_ Location. Servicing_ Specified. Location_ Party
<span id="LogisticsLocationTypeCode">LogisticsLocationTypeCode</span> | xsd:token | A code specifying the type of this logistics related location. | UN01003682 | Logistics_ Location. Type. Code


<h1 id="GeographicalGrid">GeographicalGrid</h1>

Type: rdf:Class

Definition: The combination of the latitude and longitude forming a graticule, used for specifying the position of any location on the surface of the Earth, without consideration of altitude or depth (reference ISO 19136).

Unique UN Assigned ID: UN01012202

Dictionary Entry Name: Specified_ Geographical Grid. Details

Properties: 

Name | Type | Definition | Unique UN Assigned ID | Dictionary Entry Name
-|-|-|-|-
<span id="OffsetVectorNumber">OffsetVectorNumber</span> | xsd:decimal | The offset vector, expressed as a number, which indicates the offset of cells along each axis for this geographical grid. | UN01012205 | Specified_ Geographical Grid. Offset Vector. Numeric
<span id="GeographicalGridAssociatedLogisticsLocation">GeographicalGridAssociatedLogisticsLocation</span> | [edi3:LogisticsLocation](#LogisticsLocation) | A logistics location associated with this specified geographical grid. | UN01013624 | Specified_ Geographical Grid. Associated. Logistics_ Location
<span id="GeographicalGridID">GeographicalGridID</span> | xsd:token | An identifier for this geographical grid. | UN01012204 | Specified_ Geographical Grid. Identification. Identifier
<span id="AxisName">AxisName</span> | xsd:string | An axis name, expressed as text, for this geographical grid. | UN01012209 | Specified_ Geographical Grid. Axis_ Name. Text
<span id="HighLimitText">HighLimitText</span> | xsd:string | The tuple of elements, expressed as text, indicating the high limit of this geographical grid specifying the diagonally opposing corner of each axis. | UN01012207 | Specified_ Geographical Grid. High_ Limit. Text
<span id="GeographicalGridGeographicalObjectCharacteristic">GeographicalGridGeographicalObjectCharacteristic</span> | [edi3:GeographicalObjectCharacteristic](#GeographicalObjectCharacteristic) | The geographical object characteristic associated with this geographical grid. | UN01012211 | Specified_ Geographical Grid. Associated. Specified_ Geographical Object Characteristic
<span id="CellText">CellText</span> | xsd:string | The cell value, expressed as text, for this geographical grid. | UN01012203 | Specified_ Geographical Grid. Cell. Text
<span id="DimensionNumber">DimensionNumber</span> | xsd:decimal | The dimension, expressed as a number, of this geographical grid. | UN01012208 | Specified_ Geographical Grid. Dimension. Numeric
<span id="LowLimitText">LowLimitText</span> | xsd:string | The tuple of elements, expressed as text, indicating the low limit of this geographical grid specifying the offset of each axis. | UN01012206 | Specified_ Geographical Grid. Low_ Limit. Text


