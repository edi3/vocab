<h1 id="ProductGroup">ProductGroup</h1>

Type: rdf:Class

Description: A grouping of trade products.

Properties: 

name | type | description
-|-|-
ProductGroupIncludedTradeLineItem | [edi3:SupplyChainTradeLineItem](#SupplyChainTradeLineItem) | A supply chain trade line item which is included in this trade product group.
ProductGroupName | xsd:string | The name, expressed as text, for this trade product group.


<h1 id="FinancialInstitutionAddress">FinancialInstitutionAddress</h1>

Type: rdf:Class

Description: The location at which a financial institution may be found or reached.

Properties: 

name | type | description
-|-|-
FinancialInstitutionAddressPostOfficeBox | xsd:string | The post office box, expressed as text, for this financial institution address.
FinancialInstitutionAddressBuildingNumber | xsd:string | The number, expressed as text, of the building on a street for this financial institution address.
FinancialInstitutionAddressPostcode | xsd:token | The code specifying the postcode for this financial institution address.
FinancialInstitutionAddressCountrySubDivisionName | xsd:string | The name, expressed as text, of a country sub-division within this financial institution address.
FinancialInstitutionAddressLineFive | xsd:string | The fifth free form line, expressed as text, of this financial institution address.
FinancialInstitutionAddressLineOne | xsd:string | The first free form line, expressed as text, of this financial institution address.
FinancialInstitutionAddressCountryName | xsd:string | The name, expressed as text, of the country within this financial institution address.
FinancialInstitutionAddressLineFour | xsd:string | The fourth free form line, expressed as text, of this financial institution address.
FinancialInstitutionAddressStreetName | xsd:string | The name, expressed as text, of the street or thoroughfare for this financial institution address.
FinancialInstitutionAddressLineTwo | xsd:string | The second free form line, expressed as text, of this financial institution address.
FinancialInstitutionAddressCityID | xsd:token | The unique identifier of the city for this financial institution address, such as United Nations Location Code (UNLOCODE).
FinancialInstitutionAddressCityName | xsd:string | The name, expressed as text, of the city, town or village of this financial institution address.
FinancialInstitutionAddressDepartmentName | xsd:string | The name, expressed as text, of a department within this financial institution address.
FinancialInstitutionAddressTypeCode | xsd:token | The code specifying the type of financial institution address.
FinancialInstitutionAddressCountrySubDivisionCode | xsd:token | The unique identifier of a country sub-division for this financial institution address (Reference ISO 3166 and UN/ECE Rec 3).
FinancialInstitutionAddressCountryCode | xsd:token | The unique identifier of a country for this financial institution address (Reference ISO 3166 and UN/ECE Rec 3).


<h1 id="TradeAddress">TradeAddress</h1>

Type: rdf:Class

Description: The location at which a particular trade related organization or person may be found or reached.

Properties: 

name | type | description
-|-|-
TradeAddressID | xsd:token | A unique identifier for this trade address.
TradeAddressLineTwo | xsd:string | The second free form line, expressed as text, of this trade address.
CitySubDivisionText | xsd:string | A name, expressed as text, of a sub-division of a city for this trade address, for example a district or borough.
AttentionOf | xsd:string | The name, expressed as text, of a person or department in the organization to whom incoming mail is marked with words such as 'for the attention of' or 'FAO' or 'ATTN' for this trade address.
GeographicalCoordinate | [edi3:GeographicalCoordinate](#GeographicalCoordinate) | An identification of a set of geographical coordinates for this trade address.
BuildingName | xsd:string | The name, expressed as text, of a building, a house or other structure on a street at this trade address.
TradeAddressLineOne | xsd:string | The first free form line, expressed as text, of this trade address.
TradeAddressPostcode | xsd:token | A code specifying the postcode of this trade address.
TradeAddressLineFive | xsd:string | The fifth free form line, expressed as text, of this trade address.
TradeAddressLineThree | xsd:string | The third free form line, expressed as text, of this trade address.
CareOf | xsd:string | The name, expressed as text, of a person or organization at this trade address to whom incoming mail is marked with words such as 'care of' or 'C/O'.
TradeAddressCityName | xsd:string | The name, expressed as text, of the city, town or village of this trade address.
TradeAddressPostOfficeBox | xsd:string | The unique identifier, expressed as text, of a container commonly referred to as a box, in a post office or other postal service location, assigned to a person or organization, where postal items may be kept for this trade address.
TradeAddressCountryName | xsd:string | A name, expressed as text, of the country for this trade address.
TradeAddressCountrySubDivisionCode | xsd:token | A unique identifier of the country sub-division for this trade address.
AdditionalStreetName | xsd:string | The additional name of a street, expressed as text, for this trade address.
TradeAddressStreetName | xsd:string | A name, expressed as text, of a street or thoroughfare for this trade address.
TradeAddressCountryCode | xsd:token | The unique identifier of a country for this trade address.
TradeAddressDepartmentName | xsd:string | The name, expressed as text, of a department for this trade address.
TradeAddressLineFour | xsd:string | The fourth free form line, expressed as text, of this trade address.
TradeAddressTypeCode | xsd:token | A code specifying the type of this trade address, such as business address or home address.
TradeAddressCountrySubDivisionName | xsd:string | A name, expressed as text, of the sub-division of a country for this trade address.
TradeAddressBuildingNumber | xsd:string | The building number, expressed as text, in this trade address.


<h1 id="BirthAddress">BirthAddress</h1>

Type: rdf:Class

Description: The place of birth.

Properties: 

name | type | description
-|-|-
BirthAddressCityName | xsd:string | The name, expressed as text, of the city, town or village of this birth address.
BirthAddressCountrySubDivisionName | xsd:string | The name, expressed as text, of the sub-division of a country for this birth address.


<h1 id="Query">Query</h1>

Type: rdf:Class

Description: A formally raised question or request for information about this specification.

Properties: 

name | type | description
-|-|-
QueryTypeCode | xsd:token | The code specifying the type of specification query.
QueryContentText | xsd:string | The content, expressed as text, of this specification query.


<h1 id="TradeProduct">TradeProduct</h1>

Type: rdf:Class

Description: Any tangible output or service produced by human or mechanical effort or by a natural process for trade purposes.

Properties: 

name | type | description
-|-|-
TradeProductAdditionalDescription | xsd:string | An additional textual description for this trade product.
RecyclingTypeCode | xsd:token | The code specifying the type of recycling for this trade product.
TrackingSystemID | xsd:token | An identifier for a tracking system of this trade product.
TradeProductManufacturerAssignedID | xsd:token | A unique manufacturer assigned identifier for this trade product.
DesignationText | xsd:string | A designation, expressed as text, for this trade product.
ConciseDescription | xsd:string | A concise textual description for this trade product, such as the description used on a shelf or printed on a receipt.
SuppliedFromCountry | [edi3:Country](#Country) | A country of supply for this trade product.
TradeProductID | xsd:token | A unique identifier for this trade product.
UseDescription | xsd:string | A textual description of a use of this trade product.
IntendedUseText | xsd:string | An intended use, expressed as text, for this trade product.
TradeProductAdditionalDocument | [edi3:Document](#Document) | An additional referenced document for this trade product, such as a manual or a certificate.
TradeProductNetVolume | xsd:decimal | A measure of a net volume for this trade product.
TradeProductDescription | xsd:string | A textual description for this trade product.
FinalAssemblyCountry | [edi3:Country](#Country) | A final assembly country for this trade product.
InspectionDocument | [edi3:Document](#Document) | A referenced inspection document for this trade product.
TradeTradeProductGroupID | xsd:token | A unique identifier for a product group for this trade product.
TradeProductMaterialGoodsCharacteristic | [edi3:GoodsCharacteristic](#GoodsCharacteristic) | A material goods characteristic applicable to this trade product.
ModelName | xsd:string | The model name, expressed as text, for this trade product.
LatestProductDataChangeFormattedDateTime | xsd:dateTime | The formatted date, time, date time, or other date time value of the latest change in the product data for this trade product.
EndItemTypeCode | xsd:token | A code specifying a type of end item for this trade product.
TradeProductDangerousGoods | [edi3:DangerousGoods](#DangerousGoods) | Transport dangerous goods information applicable for this trade product.
MSDSDocument | [edi3:Document](#Document) | A Material Safety Data Sheet (MSDS) document referenced for this product.
VariantDescription | xsd:string | A textual description of a variant of this trade product.
LegalRightsOwner | [edi3:TradeParty](#TradeParty) | The party that owns the legal rights for this trade product.
ContentUnitQuantity | xsd:decimal | The number of content units of this trade product.
IncludedProductContentUnitQuantity | xsd:decimal | The number of content units of products included in this trade product.
TradeProductGrossVolume | xsd:decimal | A measure of the gross volume for this trade product.
TradeProductTypeCode | xsd:token | A code specifying the type of trade product.
UltimateCustomerAssignedExtensionID | xsd:token | An ultimate customer assigned extension identifier for this trade product.
PrePackagedIndicator | xsd:boolean | The indication of whether or not this trade product is pre-packaged.
BrandRangeName | xsd:string | The brand range name, expressed as text, for this trade product.
SerialNumberMarkedIndicator | xsd:boolean | The indication of whether or not this trade product is marked with a serial number.
IncludedProduct | [edi3:Product](#Product) | An included product referenced from this trade product.
TradeProductBuyerAssignedID | xsd:token | The unique buyer assigned identifier for this trade product.
TradeProductCommonName | xsd:string | A common name, expressed as text, for this trade product.
CustomerAssignedID | xsd:token | A unique customer assigned identifier for this trade product.
InnerPackQuantity | xsd:decimal | The number of inner packs of this trade product.
Packaging | [edi3:Packaging](#Packaging) | Packaging applicable for use with this trade product.
BrandName | xsd:string | The brand name, expressed as text, for this trade product.
TradeProductOriginCountry | [edi3:Country](#Country) | A country of origin for this trade product.
TradeProductSeasonCode | xsd:token | A code specifying a season for this trade product.
MarketingProductFeature | [edi3:Feature](#Feature) | A marketing feature of this trade product.
MarketingDescription | xsd:string | A marketing description, expressed as text, for this trade product.
AnnouncedLaunchCancellationFormattedDateTime | xsd:dateTime | The formatted date, time, date time, or other date time value of the cancellation of the announced launch of this trade product.
UnitTypeCode | xsd:token | A code specifying a type of unit for this trade product.
FromProductionLifeSpanMeasure | xsd:decimal | The measure of the life span of this trade product from date of production.
TradeProductManufacturer | [edi3:TradeParty](#TradeParty) | A manufacturer party for this trade product.
CertificationEvidenceDocument | [edi3:Document](#Document) | A referenced certification evidence document for this trade product.
Keyword | [edi3:Keyword](#Keyword) | A keyword applicable to this trade product.
AttachedSecurityTag | [edi3:SecurityTag](#SecurityTag) | A tag device attached to this trade product to provide protection from a peril such as theft.
Characteristic | [edi3:Characteristic](#Characteristic) | A characteristic applicable to this trade product.
IncludedProductTypeQuantity | xsd:decimal | The number of different product types included at the next lower level in this trade product.
TradeProductMaximumDimensions | [edi3:SpatialDimension](#SpatialDimension) | Maximum linear spatial dimensions of this trade product.
DrainedNetWeight | xsd:decimal | The measure of the drained net weight (mass) of this trade product.
TradeProductGlobalID | xsd:token | A unique global identifier for this trade product.
PresentationBinaryFile | [edi3:BinaryFile](#BinaryFile) | A binary file presentation specified for this trade product.
TradeProductIndustryAssignedID | xsd:token | A unique industry assigned identifier for this product.
BrandOwner | [edi3:TradeParty](#TradeParty) | The party that owns the brand of this trade product.
TradeProductStatusCode | xsd:token | A code specifying a status for this trade product.
ColourDescription | xsd:string | A textual description of the colour of this trade product.
RegulationConformityID | xsd:token | An identifier assigned to indicate conformity with a regulation or standard for this trade product, such as "CE" which declares that the product conforms with the essential requirements of the applicable EC directives.
InnerPackContentUnitQuantity | xsd:decimal | The number of content units in an inner pack of this trade product.
TradeProductNetWeight | xsd:decimal | A measure of the net weight (mass) of this trade product.
ContentVariableMeasureIndicator | xsd:boolean | The indication of whether or not instances of this trade product have a content variable measure, such as weight, length or volume.
PhysicalFormDescription | xsd:string | A textual description of the physical form of this trade product.
GlobalExtensionID | xsd:token | A global extension identifier for this trade product, such as a prefix or a suffix.
TradeName | xsd:string | A trade name, expressed as text, for this trade product.
ProductionDiscontinuedDateTime | xsd:dateTime | The date, time, date time, or other date time value of the discontinuation of the production of this trade product.
ModelID | xsd:token | A unique model identifier for this trade product.
ManufactureCountry | [edi3:Country](#Country) | The country of manufacture of this trade product.
TradeProductGrossWeight | xsd:decimal | A measure of the gross weight (mass) of this trade product.
TradeProductDimensions | [edi3:SpatialDimension](#SpatialDimension) | Linear spatial dimensions of this trade product.
SeasonDescription | xsd:string | A season description, expressed as text, for this trade product.
Classification | [edi3:Classification](#Classification) | A product classification designated for this trade product.
VariableMeasureIndicator | xsd:boolean | The indication of whether or not instances of this trade product have a variable measure, such as weight, length or volume.
TradeProductName | xsd:string | A name, expressed as text, for this trade product.
MarketingCampaignDocument | [edi3:Document](#Document) | A referenced marketing campaign document for this trade product.
SubBrandName | xsd:string | The sub-brand name, expressed as text, for this trade product.
GeneticModificationExtentCode | xsd:token | The code specifying the extent of a genetic modification to this trade product.
StorageInformation | [edi3:Note](#Note) | A storage information note for this trade product.
FromOpeningLifeSpanMeasure | xsd:decimal | The measure of the life span of this trade product from date of opening.
ConfigurableIndicator | xsd:boolean | The indication of whether or not this trade product is configurable.
BuyerSuppliedPartsReferenceDocument | [edi3:Document](#Document) | A buyer supplier parts document referenced for this trade product.
TransportInformation | [edi3:Note](#Note) | A transport information note for this trade product.
TradeProductDisposalInstructions | [edi3:DisposalInstructions](#DisposalInstructions) | Disposal instructions applicable to this trade product.
TradeProductColourCode | xsd:token | The code specifying the colour for this trade product.
Certification | [edi3:Certification](#Certification) | A certification applicable to this trade product.
TradeProductScientificName | xsd:string | A scientific name, expressed as text, for this trade product.
TradeProductBatchID | xsd:token | A batch identifier for this trade product.
SecurityInformation | [edi3:Note](#Note) | A security information note for this trade product.
ConsumerAgeDescription | xsd:string | A consumer age description, expressed as text, for this trade product.
TradeProductSellerAssignedID | xsd:token | The unique seller assigned identifier for this trade product.
SpecifiedProductCertificate | [edi3:Certificate](#Certificate) | A product certificate specified for this trade product.
TradeProductInformationNote | [edi3:Note](#Note) | An information note for this trade product.
ConsumerGenderDescription | xsd:string | A consumer gender description, expressed as text, for this trade product.
IndividualProductInstance | [edi3:ProductInstance](#ProductInstance) | An individual instance of this trade product.
FromDeliveryLifeSpanMeasure | xsd:decimal | The measure of the life span of this trade product from date of delivery.
PromotionalVariantID | xsd:token | The promotional variant identifier for this trade product.
TradeProductMinimumDimensions | [edi3:SpatialDimension](#SpatialDimension) | Minimum linear spatial dimensions of this trade product.
TradeProductOriginLocation | [edi3:LogisticsLocation](#LogisticsLocation) | A location of origin for this trade product.
ExportIndicator | xsd:boolean | The indication of whether or not this trade product is for export.
SizeDescription | xsd:string | A size description, expressed as text, for this trade product.
AreaDensityMeasure | xsd:decimal | The measure of the area density, such as paper density 100 gsm, of this trade product.
EndItemName | xsd:string | An end item name, expressed as text, for this trade product.


<h1 id="Product">Product</h1>

Type: rdf:Class

Description: A reference to a product or service produced by human or mechanical effort or by a natural process for trading purposes.

Properties: 

name | type | description
-|-|-
ProductGlobalID | xsd:token | A unique global identifier for this referenced product.
ProductBuyerAssignedID | xsd:token | The unique buyer assigned identifier for this referenced product.
ProductName | xsd:string | A name, expressed as text, for this referenced product.
ProductUnitQuantity | xsd:decimal | A unit quantity of this referenced product.
ProductManufacturerAssignedID | xsd:token | A unique manufacturer assigned identifier for this referenced product.
ProductRelationshipTypeCode | xsd:token | A code specifying a type of relationship for this referenced product.
ProductSellerAssignedID | xsd:token | The unique seller assigned identifier for this referenced product.
ProductID | xsd:token | A unique identifier for this referenced product.
ProductDescription | xsd:string | A textual description for this referenced product.


<h1 id="Fault">Fault</h1>

Type: rdf:Class

Description: An identified defect or fault.

Properties: 

name | type | description
-|-|-
IDCode | xsd:token | A code specifying an identified fault.


<h1 id="Document">Document</h1>

Type: rdf:Class

Description: Written, printed or electronic matter that is referenced.

Properties: 

name | type | description
-|-|-
DocumentLanguageCode | xsd:token | An identifier for a language used in this referenced document.
DocumentCategoryCode | xsd:token | The code specifying the category of this referenced document.
DocumentTypeCode | xsd:token | The code specifying the type of referenced document.
DocumentStatusCode | xsd:token | The code specifying the status for this referenced document.
DocumentIssueLocation | [edi3:LogisticsLocation](#LogisticsLocation) | The logistics related location where this referenced document has been issued.
DocumentLineID | xsd:token | The unique identifier of a line in this referenced document.
DocumentRelationshipTypeCode | xsd:token | The code specifying the type of relationship between this referenced document and another artefact, such as a replacement of an original document.
ElectronicPresentationIndicator | xsd:boolean | The indication of whether or not this referenced document is presented in an electronic format.
DocumentRemark | xsd:string | A remark, expressed as text, regarding this referenced document.
DocumentInformation | xsd:string | Information, expressed as text, for this referenced document.
DocumentSender | [edi3:TradeParty](#TradeParty) | The trade related party that sends this referenced document.
DocumentFormattedIssueDateTime | xsd:dateTime | The formatted date or date time for the issuance of this referenced document.
DocumentLodgementLocation | [edi3:LogisticsLocation](#LogisticsLocation) | The logistics related location where this referenced document has been lodged.
DocumentPreviousRevisionID | xsd:token | An identifier for a previous revision of this referenced document.
DocumentGlobalID | xsd:token | A unique global identifier for this referenced document.
AcceptablePeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The specified period within which this referenced document may be accepted.
IncludedAmount | xsd:decimal | A monetary value included in this referenced document.
DocumentSignatoryAuthentication | [edi3:Authentication](#Authentication) | A signatory authentication for this referenced document.
DocumentURI | xsd:token | The unique Uniform Resource Identifier (URI) for this referenced document.
ReferenceTypeCode | xsd:token | The code specifying the reference type of this referenced document.
DocumentEffectivePeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The specified period within which this referenced document is effective.
IssuerAssignedID | xsd:token | The unique issuer assigned identifier for this referenced document.
DocumentCopyIndicator | xsd:boolean | The indication of whether or not the referenced document is a copy.
DocumentProprietaryTypeText | xsd:string | A proprietary type, expressed as text, for this referenced document.
SpecifiedStatus | [edi3:DocumentStatus](#DocumentStatus) | Status information specified for this referenced document.
DocumentAcceptanceDateTime | xsd:dateTime | The date, time, date time, or other date time value of the acceptance of this referenced document.
DocumentIssuer | [edi3:TradeParty](#TradeParty) | The trade related party that issues this referenced document.
AttachedBinaryObject | xsd:base64Binary | A binary object that is attached or otherwise appended to this referenced document.
DocumentRevisionID | xsd:token | A unique identifier for a revision of this referenced document.
AttachedBinaryFile | [edi3:BinaryFile](#BinaryFile) | A specified binary file attached to this referenced document.
DocumentID | xsd:token | A unique identifier for this referenced document.
DocumentReferenceDateTime | xsd:dateTime | The reference date or date time for this referenced document.
IncludedNote | [edi3:Note](#Note) | A note included in this referenced document.
PageID | xsd:token | The identifier of the page for this referenced document.
DocumentContractualClause | [edi3:Clause](#Clause) | A contractual clause of this referenced document.
DocumentRecipient | [edi3:TradeParty](#TradeParty) | A trade related party that receives this referenced document.
SectionName | xsd:string | A section name, expressed as text, for this referenced document.
DocumentName | xsd:string | A name, expressed as text, for this referenced document.
ReceiptDateTime | xsd:dateTime | The date, time, date time, or other date time value for the formal receipt of this referenced document.
AuthenticatedOriginalIndicator | xsd:boolean | The indication of whether or not this referenced document is an authenticated original.


<h1 id="DocumentLineDocument">DocumentLineDocument</h1>

Type: rdf:Class

Description: A collection of data for a line on a piece of written, printed or electronic matter that provides information or evidence.

Properties: 

name | type | description
-|-|-
ParentLineID | xsd:token | The unique identifier of the parent line to this document line.
DocumentLineDocumentSubordinateLineID | xsd:token | An identifier of a subordinate line of this document line.
LatestRevisionDateTime | xsd:dateTime | The date, time, date time, or other date time value for the latest revision of this document line.
StatusReasonCode | xsd:token | The code specifying the line status reason for this document line.
DocumentLineDocumentLineID | xsd:token | The unique identifier of this document line.
DocumentLineDocumentID | xsd:token | The identifier of this document line document.
DocumentLineDocumentIssueDateTime | xsd:dateTime | The date, time, date time, or other date time value for the issuance of this document line.
PublicationDateTime | xsd:dateTime | The date, time, date time, or other date time value of the publication of this document line.
BuyerAssignedCategoryCode | xsd:token | The code specifying the category assigned by the buyer for this document line.
DocumentLineDocumentStatusCode | xsd:token | The code specifying the status of this document line.
LineStatusReasonText | xsd:string | A reason, expressed as text, for the line status in this document line.
AcknowledgementDocument | [edi3:AcknowledgementDocument](#AcknowledgementDocument) | The acknowledgement document referenced in this document line.
DocumentLineDocumentEffectivePeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The period within which this document line is effective.
DocumentLineDocumentNote | [edi3:Note](#Note) | A note included in this document line.


<h1 id="AcknowledgementDocument">AcknowledgementDocument</h1>

Type: rdf:Class

Description: A document exchanged between parties for a business application level acknowledgement of the receipt of information.

Properties: 

name | type | description
-|-|-
AcknowledgementDocumentID | xsd:token | The unique identifier of this acknowledgement document.
AcknowledgementDocumentTypeCode | xsd:token | A code specifying a type of acknowledgement document.
AcknowledgementDocumentStatusCode | xsd:token | A code specifying a status for this acknowledgement document.
ReportSubmissionDateTime | xsd:dateTime | The date, time, date time or other date time value of the submission of the report being acknowledged by this acknowledgment document.
MultipleReferencesIndicator | xsd:boolean | The indication of whether or not this acknowledgement document has multiple references.
AcknowledgementDocumentCreationDateTime | xsd:dateTime | The date or date time value of the creation of this acknowledgement document.
AcknowledgementDocumentIssueDateTime | xsd:dateTime | The date, time, date time or other date time value for the issuance of this acknowledgement document.
ReportReceiptDateTime | xsd:dateTime | The date, time, date time or other date time value of the receipt of the report being acknowledged by this acknowledgment document.
AcknowledgementDocumentReasonInformationText | xsd:string | Reason information, expressed as text, for this acknowledgement document.
AcknowledgementDocumentControlRequirementIndicator | xsd:boolean | The indication of whether or not this acknowledgement document has a control requirement.
AcknowledgementStatusCode | xsd:token | A code specifying an acknowledgment status for this acknowledgement document.
AcknowledgementDocumentName | xsd:string | The name, expressed as text, for this acknowledgement document.
AcknowledgementDocumentReferenceDocument | [edi3:Document](#Document) | A document referenced by this acknowledgement document.


<h1 id="FinancingRequestResultDocument">FinancingRequestResultDocument</h1>

Type: rdf:Class

Description: A collection of data that reports the result of a financing request.

Properties: 

name | type | description
-|-|-
FinancingRequestResultDocumentFinancedTotalAmount | xsd:decimal | A monetary value of the financed total amount in this financing request result document.
SpecifiedFinancingStatus | [edi3:FinancingStatus](#FinancingStatus) | The financing status specified in this financing request result document.


<h1 id="ExchangedDocument">ExchangedDocument</h1>

Type: rdf:Class

Description: A collection of data for a piece of written, printed or electronic matter that is exchanged between two or more parties.

Properties: 

name | type | description
-|-|-
ExchangedDocumentPurposeCode | xsd:token | A code specifying the purpose of this exchanged document, such as request or reminder.
PurposeText | xsd:string | The purpose, expressed as text, of this exchanged document.
Agent | [edi3:TradeParty](#TradeParty) | A party representing another party for this exchanged document.
ExchangedDocumentSignatoryAuthentication | [edi3:Authentication](#Authentication) | A signatory document authentication for this exchanged document.
UrgencyText | xsd:string | An urgency, expressed as text, of this exchanged document.
ExchangedDocumentCopyIndicator | xsd:boolean | The indication of whether or not this exchanged document is a copy.
ExchangedDocumentGlobalID | xsd:token | The unique global identifier for this exchanged document.
AmendmentPurposeCode | xsd:token | A code specifying a purpose of an amendment to this exchanged document.
CopyIssuedQuantity | xsd:decimal | The number of copies issued of this exchanged document.
ExchangedDocumentLodgementLocation | [edi3:LogisticsLocation](#LogisticsLocation) | The location where this exchanged document has been lodged.
LineCount | xsd:decimal | The count of the number of lines in this exchanged document.
ResponseDateTime | xsd:dateTime | A date, time, date time, or other date time value of a response of the exchanged document.
ExchangedDocumentCustomsID | xsd:token | A unique identifier, for customs purposes, for this exchanged document.
ExchangedDocumentIssuer | [edi3:TradeParty](#TradeParty) | The party that issues this exchanged document.
ExchangedDocumentCreationDateTime | xsd:dateTime | The date, time, date time, or other date time value of a creation of this exchanged document.
ExchangedDocumentVersionID | xsd:token | The unique identifier for the version of this exchanged document.
ExchangedDocumentContractualClause | [edi3:Clause](#Clause) | A contractual clause of this exchanged document.
ThirdSignatoryAuthentication | [edi3:Authentication](#Authentication) | The third signature, also known as the second counter signature, that has been authenticated on this exchanged document indicating where appropriate the authentication party.
ExchangedDocumentID | xsd:token | The unique identifier of this exchanged document.
ExchangedDocumentControlRequirementIndicator | xsd:boolean | The indication of whether or not this exchanged document has specific control requirements.
UrgencyCode | xsd:token | The code specifying the urgency for this exchanged document.
ExchangedDocumentStatusCode | xsd:token | The code specifying the status of this exchanged document.
FirstSignatoryAuthentication | [edi3:Authentication](#Authentication) | The first or primary signature that authenticates this exchanged document.
ResponseRequestTypeCode | xsd:token | A code specifying a type of response requested for this exchanged document.
FourthSignatoryAuthentication | [edi3:Authentication](#Authentication) | The fourth signature, also known as the third counter signature, that has been authenticated on this exchanged document indicating where appropriate the authentication party.
ExchangedDocumentLanguageCode | xsd:token | A unique identifier for a language used in this exchanged document.
ExchangedDocumentPreviousRevisionID | xsd:token | The unique identifier of the previous revision of this exchanged document.
OffsetProcessingStatusText | xsd:string | A status of an offset processing, expressed as text, for this exchanged document, such as the process offsetted by this document.
RejectionResponseDateTime | xsd:dateTime | A date, time, date time, or other date time value of a rejection response of the exchanged document.
ExchangedDocumentIssueDateTime | xsd:dateTime | The date, time, date time or other date time value for the issuance of this exchanged document.
OriginalRequiredQuantity | xsd:decimal | The number of originals required of this exchanged document.
ExchangedDocumentRevisionID | xsd:token | The unique identifier of the revision of this exchanged document.
ExchangedDocumentIssueLocation | [edi3:LogisticsLocation](#LogisticsLocation) | The location where this exchanged document has been issued.
RecipientAssignedID | xsd:token | A unique recipient assigned identifier for this exchanged document.
BuyerSignatoryDocumentAuthentication | [edi3:Authentication](#Authentication) | The buyer signature that authenticates this exchanged document.
ExchangedDocumentItemQuantity | xsd:decimal | The number of line items in this exchanged document.
ExchangedDocumentAcceptanceDateTime | xsd:dateTime | The date, time, date time, or other date time value for the acceptance of this exchanged document.
ExchangedDocumentRemark | xsd:string | A remark, expressed as text, regarding this exchanged document.
SubmissionDateTime | xsd:dateTime | The date, time, date time or other date time value for the formal submission of this exchanged document to a receiver by a sender.
ExchangedDocumentRecipient | [edi3:TradeParty](#TradeParty) | A trade party that receives this exchanged document.
ExchangedDocumentCategoryCode | xsd:token | The code specifying a category for this exchanged document.
ExchangedDocumentNote | [edi3:Note](#Note) | A note included in this exchanged document.
OriginalIssuedQuantity | xsd:decimal | The number of originals issued of this exchanged document.
SecondSignatoryAuthentication | [edi3:Authentication](#Authentication) | The second signature, also known as the first counter signature, that has been authenticated on this exchanged document indicating where appropriate the authentication party.
ExchangedDocumentInformation | xsd:string | Information, expressed as text, for this exchanged document.
ExchangedDocumentSender | [edi3:TradeParty](#TradeParty) | The party that sends this exchanged document.
ExchangedDocumentEffectivePeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The specified period within which this exchanged document is effective.
CopyRequiredQuantity | xsd:decimal | The number of copies required of this exchanged document.
ApproverSignatoryDocumentAuthentication | [edi3:Authentication](#Authentication) | The approver signature that authenticates this exchanged document.
CancellationDateTime | xsd:dateTime | The date, time, date time, or other date time value of a cancellation of the exchanged document.
RevisionDateTime | xsd:dateTime | The date, time, date time or other date time value for the revision of this exchanged document.
SenderAssignedID | xsd:token | A unique sender assigned identifier for this exchanged document.
TraderAssignedID | xsd:token | A unique trader assigned identifier for this exchanged document.
ResponseReasonCode | xsd:token | A code specifying a response reason for this exchanged document.
ExchangedDocumentTypeCode | xsd:token | The code specifying the type of exchanged document.
ExchangedDocumentReferenceDocument | [edi3:Document](#Document) | Other documents referenced by this exchanged document.
ExchangedDocumentDescription | xsd:string | A textual description of this exchanged document.
AttachedFile | [edi3:BinaryFile](#BinaryFile) | A binary file attached to this exchanged document.


<h1 id="FinancingRequestDocument">FinancingRequestDocument</h1>

Type: rdf:Class

Description: The set of characteristics shared by all individual transactions grouped for this financing request document.

Properties: 

name | type | description
-|-|-
IncludedAdditionalInformationNote | [edi3:Note](#Note) | An additional information note included for this financing request document.
ContractualDocumentClause | [edi3:Clause](#Clause) | A contractual document clause specified for this financing request document.
FinancingRequestDocumentCopyIndicator | xsd:boolean | The indication of whether or not this financing request document is a copy rather than an original.
FinancingRequestDocumentCurrencyCode | xsd:token | The code specifying the currency in this financing request document.
GroupID | xsd:token | The group identifier in this financing request document.
CancellationReasonText | xsd:string | A cancellation reason, expressed as text, in this financing request document.
SpecifiedCancellationStatus | [edi3:CancellationStatus](#CancellationStatus) | A status of a cancellation specified for this financing request document, such as accepted.
SpecifiedValidationStatus | [edi3:ValidationStatus](#ValidationStatus) | The status of the validation specified for this financing request document, such as error.
GroupedTransactionTotalAmount | xsd:decimal | A total monetary value of grouped transactions in this financing request document.
SpecifiedRequestingParty | [edi3:RequestingParty](#RequestingParty) | The requesting party specified in this financing request document.
SpecifiedIntermediaryCreditorFinancialInstitution | [edi3:CreditorFinancialInstitution](#CreditorFinancialInstitution) | The creditor financial institution specified as the intermediary in this financing request document.
SpecifiedFirstAgentCreditorFinancialInstitution | [edi3:CreditorFinancialInstitution](#CreditorFinancialInstitution) | The creditor financial institution specified as the first agent in this financing request document.
FinancingRequestDocumentCreationDateTime | xsd:dateTime | The date, time, date time or other date time value for the creation of this financing request document.
AgreementInformation | xsd:string | Agreement information, expressed as text, in this financing request document, such as a collection mandate.
GroupedTransactionSpecifiedQuantity | xsd:decimal | The number of grouped transactions specified in this financing request document.


<h1 id="FinancingSummaryDocument">FinancingSummaryDocument</h1>

Type: rdf:Class

Description: A collection of financing related data that provides an overview of key points.

Properties: 

name | type | description
-|-|-
LineOfCreditFinancingFinancialAccount | [edi3:FinancingFinancialAccount](#FinancingFinancialAccount) | The financing financial account, used for managing the line of credit, specified for this financing summary document.
FinancingSummaryDocumentFinancedTotalAmount | xsd:decimal | A financed total monetary value in this financing summary document.
RelatedFinancialBooking | [edi3:Booking](#Booking) | The financial booking related to this financing summary document.
FinancedTransactionSpecifiedQuantity | xsd:decimal | The number of financed transactions specified in this financing summary document.
FinancingSummaryDocumentSpecifiedCreditorFinancialAccount | [edi3:CreditorFinancialAccount](#CreditorFinancialAccount) | The creditor financial account, used for crediting, specified for this financing summary document.
FinancedAppliedRate | xsd:decimal | The financed applied rate, expressed as a percentage, in this financing summary document.


<h1 id="GeographicalSurface">GeographicalSurface</h1>

Type: rdf:Class

Description: A figure on the Earth having only two dimensions (reference ISO 19136).

Properties: 

name | type | description
-|-|-
GeographicalSurfacePolygon | [edi3:Polygon](#Polygon) | The polygon included in this geographical surface.


<h1 id="Feature">Feature</h1>

Type: rdf:Class

Description: Distinctive or characteristic parts of a trade product.

Properties: 

name | type | description
-|-|-
MarketingMeasure | xsd:decimal | A marketing measure for this trade product feature.
FeatureName | xsd:string | A name, expressed as text, for this trade product feature.
MarketingPhrase | xsd:string | A catch phrase, expressed as text, for marketing of this trade product feature.
FeatureDescription | xsd:string | A textual description of this trade product feature.
FeatureTypeCode | xsd:token | The code specifying the type of trade product feature.


<h1 id="GroupedWorkItem">GroupedWorkItem</h1>

Type: rdf:Class

Description: A grouping of related work items.

Properties: 

name | type | description
-|-|-
GroupedWorkItemRequestedActionCode | xsd:token | A code specifying a requested action for this grouped work item.
GroupedWorkItemComment | xsd:string | A comment, expressed as text, for this work item group.
GroupedWorkItemAlternativeClassificationCode | xsd:token | A code specifying an alternative classification for this work item group.
GroupedWorkItemContractualLanguageCode | xsd:token | The code specifying the contractual language for this grouped work item.
GroupedWorkItemID | xsd:token | The unique identifier for this work item group.
GroupedWorkItemIndexText | xsd:string | The index, expressed as text, to be used for this grouped work item.
GroupedWorkItemItemBasicWorkItem | [edi3:BasicWorkItem](#BasicWorkItem) | A basic work item within this grouped work item.
GroupedWorkItemComplexDescription | [edi3:ComplexDescription](#ComplexDescription) | An actual complex description for this work item group.
GroupedWorkItemTotalQuantity | xsd:decimal | The total quantity of this work item group.
GroupedWorkItemPriceListItemID | xsd:token | The identifier of a price list item for this grouped work item.
BinaryFile | [edi3:BinaryFile](#BinaryFile) | A specified binary file referenced by this grouped work item.
ItemGroupedWorkItem | [edi3:GroupedWorkItem](#GroupedWorkItem) | A grouped work item within this grouped work item.
GroupedWorkItemChangedRecordedStatus | [edi3:RecordedStatus](#RecordedStatus) | A changed recorded status for this grouped work item.
GroupedWorkItemTypeCode | xsd:token | A code specifying the type of this work item group.
GroupedWorkItemPrimaryClassificationCode | xsd:token | A code specifying the primary classification for this work item group.


<h1 id="BasicWorkItem">BasicWorkItem</h1>

Type: rdf:Class

Description: A basic item of work.

Properties: 

name | type | description
-|-|-
BasicWorkItemPrimaryClassificationCode | xsd:token | A code specifying the primary classification for this basic work item.
CalculatedUnitPrice | [edi3:CalculatedPrice](#CalculatedPrice) | A unit calculated price for this basic work item.
BasicWorkItemAlternativeClassificationCode | xsd:token | A code specifying an alternative classification for this basic work item.
BasicWorkItemIndexText | xsd:string | The index, expressed as text, to be used for this basic work item.
BasicWorkItemComment | xsd:string | A comment, expressed as text, for this basic work item.
BasicWorkItemComplexDescription | [edi3:ComplexDescription](#ComplexDescription) | An actual complex description for this basic work item.
BasicWorkItemID | xsd:token | The unique identifier for this basic work item.
BasicWorkItemTypeCode | xsd:token | A code specifying the type of basic work item.
TotalQuantityAnalysis | [edi3:QuantityAnalysis](#QuantityAnalysis) | An analysis of the total quantity for this basic work item.
TotalQuantityClassificationCode | xsd:token | The code specifying the classification of the total quantity for this basic work item.
BasicWorkItemReferencedBinaryFile | [edi3:BinaryFile](#BinaryFile) | A specified binary file referenced by this basic work item.
CalculatedTotalPrice | [edi3:CalculatedPrice](#CalculatedPrice) | A total calculated price for this basic work item.
BasicWorkItemRequestedActionCode | xsd:token | A code specifying a requested action for this basic work item.
BasicWorkItemPriceListItemID | xsd:token | The unique identifier of a price list item for this basic work item.
DeprecatedReferenceFileBinaryObject | xsd:base64Binary | A reference file binary object related to this basic work item.
RecordedChangedStatus | [edi3:RecordedStatus](#RecordedStatus) | A changed recorded status for this basic work item.
BasicWorkItemDeprecatedStatusCode | xsd:token | A code specifying the status of this basic work item.
ReferenceID | xsd:token | The unique identifier of another work item referenced by this basic work item.
DeprecatedSubordinateBasicWorkItem | [edi3:BasicWorkItem](#BasicWorkItem) | A subordinate work item for this basic work item.
BasicWorkItemContractualLanguageCode | xsd:token | The code specifying the contractual language for this basic work item.
DeprecatedIndexValue | xsd:string | The index value for this basic work item.
BasicWorkItemItemBasicWorkItem | [edi3:BasicWorkItem](#BasicWorkItem) | A basic work item in this basic work item.


<h1 id="LineTradeTransaction">LineTradeTransaction</h1>

Type: rdf:Class

Description: A group of trade line items, trade line agreement, trade line delivery and trade line settlement details.

Properties: 

name | type | description
-|-|-
TradeDelivery | [edi3:LineTradeDelivery](#LineTradeDelivery) | A trade delivery applicable to this line trade transaction.
LineTradeTransactionTradeProduct | [edi3:TradeProduct](#TradeProduct) | A trade product included in this line trade transaction.


<h1 id="SupplyChainTradeTransaction">SupplyChainTradeTransaction</h1>

Type: rdf:Class

Description: A group of supply chain trade line items, trade agreement, trade delivery and trade settlement details.

Properties: 

name | type | description
-|-|-
LineItemQuantity | xsd:decimal | The number of line items for this supply chain trade transaction.
SalesAgentAssignedID | xsd:token | The unique identifier assigned by the sales agent to identify this supply chain trade transaction.
SupplyChainTradeTransactionReferencedDocument | [edi3:Document](#Document) | A referenced document associated with this supply chain trade transaction, such as the purchase order, invoice or packing list.
SupplyChainTradeTransactionLogisticsPackage | [edi3:Package](#Package) | A logistics package specified for this supply chain trade transaction.
HeaderTradeSettlement | [edi3:HeaderTradeSettlement](#HeaderTradeSettlement) | The trade settlement header applicable to this supply chain trade transaction.
ShipmentID | xsd:token | An identifier, such as the Unique Consignment Reference (UCR), for the shipment which is the subject of this supply chain trade transaction.
DocumentURL | xsd:token | The Uniform Resource Locator (URL) of the web location of the document for this supply chain trade transaction.
SupplyChainTradeTransactionIssueDateTime | xsd:dateTime | The date, time, date time or other date time value for the issuance of this supply chain trade transaction.
SupplyChainTradeTransactionIncludedTradeLineItem | [edi3:SupplyChainTradeLineItem](#SupplyChainTradeLineItem) | A trade line item included in this supply chain trade transaction.
AssociatedFinancingRequestResultDocument | [edi3:FinancingRequestResultDocument](#FinancingRequestResultDocument) | The financing request result document associated with this supply chain trade transaction.
HeaderTradeDelivery | [edi3:HeaderTradeDelivery](#HeaderTradeDelivery) | A trade delivery header applicable to this supply chain trade transaction.
SupplyChainTradeTransactionTypeCode | xsd:token | The code specifying the type of supply chain trade transaction.
SupplyChainTradeTransactionInformation | xsd:string | Information, expressed as text, for this supply chain trade transaction.
HeaderTradeAgreement | [edi3:HeaderTradeAgreement](#HeaderTradeAgreement) | A trade agreement header applicable to this supply chain trade transaction, such as payment or delivery terms.
ProductGroup | [edi3:ProductGroup](#ProductGroup) | A product group included in this supply chain trade transaction.
SenderRecipientSequenceID | xsd:token | The sender-recipient sequence identifier for this supply chain trade transaction.
SupplyChainTradeTransactionAssociatedDocumentLine | [edi3:DocumentLineDocument](#DocumentLineDocument) | The document line associated with this supply chain trade transaction.


<h1 id="ChemicalTreatment">ChemicalTreatment</h1>

Type: rdf:Class

Description: A process of applying a chemical, physical, or biological agent to an object.

Properties: 

name | type | description
-|-|-
ChemicalTreatmentName | xsd:string | A name, expressed as text, of this applied chemical treatment.
AppliedPeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | A period during which this chemical treatment is applied.
ApplicableTemperature | [edi3:SpecifiedTemperature](#SpecifiedTemperature) | The specified temperature applicable for this applied chemical treatment.
ResultNote | [edi3:Note](#Note) | The note describing the results of this applied chemical treatment.
ChemicalTreatmentOccurrenceDateTime | xsd:dateTime | The date time of the occurrence of this applied chemical treatment.
MethodName | xsd:string | The name, expressed as text, of the method of this applied chemical treatment.
UsedChemical | [edi3:Chemical](#Chemical) | A chemical used during this applied chemical treatment.
ChemicalConcentrationMeasure | xsd:decimal | A measure of the chemical concentration of this applied chemical treatment.


<h1 id="RiskAnalysisResult">RiskAnalysisResult</h1>

Type: rdf:Class

Description: The result of a logistics risk analysis calculation.

Properties: 

name | type | description
-|-|-
TransportEquipmentRiskRelatedCode | xsd:token | A code specifying a transport equipment related risk for this logistics risk analysis result.
RiskAnalysisResultDescription | xsd:string | The textual description of this logistics risk analysis result.
RiskAnalysisResultLevelCode | xsd:token | The code specifying the level for this logistics risk analysis result.
ConsignmentRiskRelatedCode | xsd:token | A code specifying a consignment related risk for this logistics risk analysis result.
RiskAnalysisResultCategoryCode | xsd:token | The code specifying the category for this logistics risk analysis result.
PartyRiskRelatedCode | xsd:token | A code specifying a party related risk for this logistics risk analysis result.


<h1 id="Classification">Classification</h1>

Type: rdf:Class

Description: A systematic arrangement of products in classes or categories according to established criteria.

Properties: 

name | type | description
-|-|-
ProductClassCharacteristic | [edi3:Characteristic](#Characteristic) | A product class characteristic for this product classification.
ClassificationApplicableReferencedStandard | [edi3:Standard](#Standard) | The referenced standard that is applicable to this product classification.
ClassificationSystemID | xsd:token | The unique identifier of the classification system for this product classification.
ClassCode | xsd:token | The code specifying the class for this product classification.
ClassName | xsd:string | A class name, expressed as text, for this product classification.
SubClassCode | xsd:token | The code specifying the sub class for this product classification.


<h1 id="Accreditation">Accreditation</h1>

Type: rdf:Class

Description: A certified recognition that provides evidence of a level of competency in a given area, such as certifying a level of skill in a trade.

Properties: 

name | type | description
-|-|-
AccreditationExpiryDateTime | xsd:dateTime | The date, time, date time or other date time value when this certified accreditation expires.
AuthenticationMethodCode | xsd:token | A code specifying an authentication method for this certified accreditation.
AccreditationDescription | xsd:string | The textual description of this certified accreditation.
AccreditationTypeCode | xsd:token | The code specifying the type of this certified accreditation, such as a type of driving license.
AccreditingBodyName | xsd:string | The name of the accrediting body, expressed as text, for this certified accreditation.
ObtainedDateTime | xsd:dateTime | The date, time, date time or other date time value when this certified accreditation was obtained.
AccreditationID | xsd:token | An identifier for this certified accreditation.


<h1 id="FinancialIdentity">FinancialIdentity</h1>

Type: rdf:Class

Description: A financial identification for an organization.

Properties: 

name | type | description
-|-|-
FinancialIdentityBICID | xsd:token | The Bank Identifier Code (BIC) as defined by ISO 9362 (Banking telecommunication messages, Bank Identifier Codes) for this financial identity.
BankAssignedID | xsd:token | The bank assigned identifier for this financial identity.
AgentAssignedCustomerID | xsd:token | The agent assigned customer identifier for this financial identity.
FinancialIdentityCHIPSUniversalID | xsd:token | The (United States) Clearing House Interbank Payments System (CHIPS) Universal Identification (UID) as assigned by the New York Clearing House for this financial identity.
IBEI | xsd:token | The International Business Entity Identifier (IBEI) for this financial identity.


<h1 id="EmployerIdentity">EmployerIdentity</h1>

Type: rdf:Class

Description: Identification of a party who pays someone to do work on a regular or contractual basis.

Properties: 

name | type | description
-|-|-


<h1 id="PersonIdentity">PersonIdentity</h1>

Type: rdf:Class

Description: Identification of a person.

Properties: 

name | type | description
-|-|-
AlienRegistrationID | xsd:token | The alien registration identifier for this person.
PassportID | xsd:token | The passport identifier for this person.
SocialSecurityID | xsd:token | The social security identifier for this person.
DriversLicenceID | xsd:token | The drivers licence identifier for this person.
PersonIdentitySpecifiedProprietaryIdentity | [edi3:ProprietaryIdentity](#ProprietaryIdentity) | A proprietary Identity specified for this person.


<h1 id="ProprietaryIdentity">ProprietaryIdentity</h1>

Type: rdf:Class

Description: Proprietary information which uniquely identifies a person or organization.

Properties: 

name | type | description
-|-|-
ProprietaryIdentityID | xsd:token | A proprietary identifier.


<h1 id="ValidationStatus">ValidationStatus</h1>

Type: rdf:Class

Description: Information relevant to a condition of a validation.

Properties: 

name | type | description
-|-|-
ValidationStatusReasonCode | xsd:token | The code specifying the reason for this validation status.
ValidationStatusConditionCode | xsd:token | The code specifying the condition of this validation status.
ValidationStatusReasonInformationText | xsd:string | Information, expressed as text, related to the reason for this validation status.


<h1 id="DocumentStatus">DocumentStatus</h1>

Type: rdf:Class

Description: The information relevant to a condition related to a document.

Properties: 

name | type | description
-|-|-
DocumentStatusReasonText | xsd:string | A reason, expressed as text, for this document status.
DocumentStatusConditionCode | xsd:token | The code specifying the condition of this document status.
DocumentStatusValidityPeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | A specified validity period for this document status.
DocumentStatusInformation | xsd:string | Information, expressed as text, for this document status.
DocumentStatusDescription | xsd:string | The textual description of this document status.
DocumentStatusReasonCode | xsd:token | A code specifying a reason for this document status.


<h1 id="CancellationStatus">CancellationStatus</h1>

Type: rdf:Class

Description: Information relevant to a condition of a cancellation.

Properties: 

name | type | description
-|-|-
CancellationStatusConditionCode | xsd:token | The code specifying the condition of this cancellation status.
CancellationStatusReasonInformationText | xsd:string | Information, expressed as text, related to the reason for this cancellation status.
CancellationStatusReasonText | xsd:string | A reason, expressed as text, for this cancellation status.


<h1 id="FinancingStatus">FinancingStatus</h1>

Type: rdf:Class

Description: Information relevant to a condition of financing.

Properties: 

name | type | description
-|-|-
FinancingStatusReasonInformationText | xsd:string | Information, expressed as text, related to the reason for this financing status.
FinancingStatusReasonText | xsd:string | A reason, expressed as text, for this financing status.
FinancingStatusConditionCode | xsd:token | The code specifying the condition of this financing status.


<h1 id="RecordedStatus">RecordedStatus</h1>

Type: rdf:Class

Description: Recorded information relevant to a condition or a position of an object.

Properties: 

name | type | description
-|-|-
ChangedDateTime | xsd:dateTime | The date, time, date time, or other date time value when this recorded status changed.
RecordedStatusConditionCode | xsd:token | The code specifying the condition for this recorded status.


<h1 id="LogisticsStatus">LogisticsStatus</h1>

Type: rdf:Class

Description: The information relevant to a condition or a position related to logistics.

Properties: 

name | type | description
-|-|-
LogisticsStatusReasonCode | xsd:token | A code specifying a reason for this logistics status [UNECE Recommendation 24].
ReportedDepartureEvent | [edi3:Event](#Event) | A transport departure event reported for this logistics status.
LogisticsStatusSequenceNumber | xsd:decimal | The sequence number of this logistics status, such as within a status report.
LogisticsStatusConditionCode | xsd:token | The code specifying this logistics status condition [UNECE Recommendation 24].
LogisticsStatusSpecifiedLocation | [edi3:LogisticsLocation](#LogisticsLocation) | A location specified for this logistics status.
LogisticsStatusValidityPeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | A specific validity period for this logistics status.
ReportedUnloadingEvent | [edi3:Event](#Event) | A transport unloading event reported for this logistics status.
LogisticsStatusReasonText | xsd:string | A reason, expressed as text, for this logistics status.
LogisticsStatusDescription | xsd:string | The textual description of this logistics status.
LogisticsStatusReferenceDateTime | xsd:dateTime | The reference date, time, date time or other date time value for this logistics status.
ReportedArrivalEvent | [edi3:Event](#Event) | A transport arrival event reported for this logistics status.


<h1 id="DeliveryAdjustment">DeliveryAdjustment</h1>

Type: rdf:Class

Description: A correction or modification to reflect actual delivery conditions.

Properties: 

name | type | description
-|-|-
DeliveryAdjustmentActualQuantity | xsd:decimal | The actual quantity added or subtracted as a result of this delivery adjustment.
DeliveryAdjustmentActualAmount | xsd:decimal | An actual monetary value added or subtracted as a result of this delivery adjustment.
DeliveryAdjustmentReasonText | xsd:string | A reason, expressed as text, for this delivery adjustment.
DeliveryAdjustmentActualDateTime | xsd:dateTime | The actual date, time, date time, or other date time value of this delivery adjustment.


<h1 id="FinancialAdjustment">FinancialAdjustment</h1>

Type: rdf:Class

Description: A correction or modification to reflect actual financial conditions.

Properties: 

name | type | description
-|-|-
FinancialAdjustmentActualAmount | xsd:decimal | An actual monetary value added or subtracted as a result of this financial adjustment.
DirectionCode | xsd:token | The code specifying whether the financial adjustment must be subtracted or added.
FinancialAdjustmentActualQuantity | xsd:decimal | The actual quantity added or subtracted as a result of this financial adjustment.
ClaimRelatedParty | [edi3:TradeParty](#TradeParty) | The claim related party for this financial adjustment.
FinancialAdjustmentActualDateTime | xsd:dateTime | The actual date, time, date time, or other date time value of this financial adjustment.
FinancialAdjustmentReasonCode | xsd:token | A code specifying a reason for this financial adjustment.
ReferenceInvoiceDocument | [edi3:Document](#Document) | The invoice document referenced for this financial adjustment.


<h1 id="RegulatoryProcedure">RegulatoryProcedure</h1>

Type: rdf:Class

Description: A set of formal steps to satisfy a cross-border regulation, law or convention.

Properties: 

name | type | description
-|-|-
RegulatoryProcedurePreviousReferencedDocument | [edi3:Document](#Document) | A previous document related to this cross-border regulatory procedure.
RegulatoryProcedurePaymentMethodCode | xsd:token | The code specifying the payment method for this cross-border regulatory procedure, such as by deferred payment method.
ExemptionClaimant | [edi3:TradeParty](#TradeParty) | A party who claims an exemption from this cross-border regulatory procedure.
OriginCriteriaText | xsd:string | The origin criteria, expressed as text, for this cross-border regulatory procedure.
CertificationBasisText | xsd:string | A basis for a certification, expressed as text, for this cross-border regulatory procedure.
AnnualQuotaQuantity | xsd:decimal | The annual quota quantity under this cross-border regulatory procedure.
RegulatoryProcedureExaminationEvent | [edi3:Event](#Event) | An examination event for this cross-border regulatory procedure.
TransportMovementTypeCode | xsd:token | A code specifying the transport movement type, such as import, export, transit, for this cross-border regulatory procedure.
RequiredCertificationTestSpecificationReport | [edi3:TestSpecificationReport](#TestSpecificationReport) | A report of a certification test and its attributes that is required for this cross-border regulatory procedure.
ValuationBasisAmount | xsd:decimal | The monetary value of the basis on which the valuation is, or will be, calculated for this cross-border regulatory procedure.
RequiredSeal | [edi3:Seal](#Seal) | A seal required by this cross-border regulatory procedure.
RegulatoryProcedureControlRequirementIndicator | xsd:boolean | The indication of whether or not a control is required for this cross-border regulatory procedure.
RegulatoryProcedureApplicablePeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | A period applicable to this cross-border regulatory procedure.
DeclarationLodgementLocation | [edi3:LogisticsLocation](#LogisticsLocation) | The location at which a declaration has been lodged for this cross-border regulatory procedure.
RegulatoryProcedureAcquisitionDateTime | xsd:dateTime | The date, time, date time, or other date time value of an acquisition for this cross-border regulatory procedure.
RegulatoryProcedureBorderClearanceInstructions | [edi3:TransportInstructions](#TransportInstructions) | Border clearance instructions for this cross-border regulatory procedure.
RegulatoryProcedureTariffQuantity | xsd:decimal | A tariff quantity for this cross-border regulatory procedure.
ExportLicenceControlClassificationID | xsd:token | The identifier of the export licence classification for control purposes relevant to this cross-border regulatory procedure, such as per the Wassenaar agreement concerning trade in weapons and dual-use goods and technologies.
RegulatoryProcedureReportedLogisticsStatus | [edi3:LogisticsStatus](#LogisticsStatus) | A logistics status reported for this cross-border regulatory procedure.
TransactionNatureCode | xsd:token | A code specifying the nature of a transaction for this cross-border regulatory procedure.
RegulatoryProcedureReferencedDocument | [edi3:Document](#Document) | A document referenced by this cross-border regulatory procedure.
RegulatoryProcedureTotalChargeAmount | xsd:decimal | A monetary value of the total charges, including tariff and non-tariff charges, for this cross-border regulatory procedure.
RegulatoryProcedureTradeTax | [edi3:TradeTax](#TradeTax) | A tax, levy or duty applicable to this cross-border regulatory procedure.
RegulatoryProcedureGuaranteeText | xsd:string | The undertaking, expressed as text, given in cash, bond or as a written guarantee to ensure that an obligation will be fulfilled for this cross-border regulatory procedure.
RegisteredDeferredPaymentPayerID | xsd:token | The identifier of the registered deferred payment payer for this cross-border regulatory procedure.
TransitReleaseCustomsOfficeLocation | [edi3:LogisticsLocation](#LogisticsLocation) | A location of a specified customs office at which the goods which are subject to this cross-border regulatory procedure are released from a customs transit regime.
ExitCustomsOfficeLocation | [edi3:LogisticsLocation](#LogisticsLocation) | The location of the specified customs office at which the goods which are subject to this cross-border regulatory procedure leave the customs territory of destination.
ResponsibleAgencyInvolvementCode | xsd:token | A code specifying a responsible agency involved in this cross-border regulatory procedure.
DeclarantAssignedDeclarationID | xsd:token | The declarant assigned identifier of a declaration for this cross-border regulatory procedure.
TotalConsignmentValueAmount | xsd:decimal | The total monetary value for a consignment for this cross-border regulatory procedure.
RegulatoryProcedureRemark | xsd:string | A remark, expressed as text, for this cross-border regulatory procedure.
TariffAmount | xsd:decimal | A monetary value of a tariff for this cross-border regulatory procedure.
RegulatoryProcedureStatement | [edi3:Note](#Note) | A statement note for this cross-border regulatory procedure.
EntryCustomsOfficeLocation | [edi3:LogisticsLocation](#LogisticsLocation) | The location of the specified customs office at which the goods subject to this cross-border regulatory procedure, enter the customs territory of entry.
AppliedRequiredChemicalTreatment | [edi3:ChemicalTreatment](#ChemicalTreatment) | A chemical treatment applied as required by this cross-border regulatory procedure.
ImmediatePayableTotalChargeAmount | xsd:decimal | A monetary value of the total charges, including tariff and non-tariff charges, immediately payable for this cross-border regulatory procedure.
ExportCustomsOfficeLocation | [edi3:LogisticsLocation](#LogisticsLocation) | The location of the specified customs office which is responsible for export formalities for the goods which are subject to this cross-border regulatory procedure.
PerformanceDateTime | xsd:dateTime | A date, time, date time, or other date time value on which this cross-border regulatory procedure was, or will be, performed.
ImportCustomsOfficeLocation | [edi3:LogisticsLocation](#LogisticsLocation) | The location of the specified customs office which is responsible for import formalities for the goods which are subject to this cross-border regulatory procedure.
TreatmentEvent | [edi3:Event](#Event) | A treatment event for this cross-border regulatory procedure.
QuotaID | xsd:token | A quota identifier for this cross-border regulatory procedure.
ConsignmentDestinationLocation | [edi3:LogisticsLocation](#LogisticsLocation) | A consignment destination location specified for this cross-border regulatory procedure.
RequestOverrideCode | xsd:token | A code specifying a request, including a reason, to override previously submitted information for this cross-border regulatory procedure, such as due to an error condition.
ResponsibleAgencyCode | xsd:token | The code specifying the agency responsible for this cross-border regulatory procedure.
DeprecatedCustomsProcedure | [edi3:CrossBorderCustomsProcedure](#CrossBorderCustomsProcedure) | A customs procedure specified for this cross-border regulatory procedure.
TransitCustomsOfficeLocation | [edi3:LogisticsLocation](#LogisticsLocation) | A location of a specified customs office which is responsible for transit formalities en route for the goods which are subject to this cross-border regulatory procedure.
RegulatoryProcedureApplicableCurrencyExchange | [edi3:CurrencyExchange](#CurrencyExchange) | The applicable currency exchange for this cross-border regulatory procedure.
UsedToDateQuotaQuantity | xsd:decimal | The quantity of the quota used to date under this cross-border regulatory procedure.
RegulatoryProcedureCategoryCode | xsd:token | A code specifying a category for this cross-border regulatory procedure, such as the appendices of the CITES Convention.
NonTariffChargeAmount | xsd:decimal | A monetary value of all non-tariff charges for this cross-border regulatory procedure.
ControlResultText | xsd:string | A control result, expressed as text, for this cross-border regulatory procedure.
AmendmentReasonCode | xsd:token | A code specifying a reason for an amendment to this cross-border regulatory procedure.
RegulatoryProcedureTypeCode | xsd:token | A code specifying a type of cross-border regulatory procedure.
DeferredPaymentMethodIndicator | xsd:boolean | The indication of whether or not the deferred payment method is applicable to this cross-border regulatory procedure.
RegulatoryProcedureTariffDeductionQuantity | xsd:decimal | A quantity to be deducted from the tariff quantity for this cross-border regulatory procedure.
PreviousProcedureTypeCode | xsd:token | A code specifying a type of previous procedure for this cross-border regulatory procedure.
ResponsibleAgencyActionCode | xsd:token | A code specifying an action for a responsible agency in this cross-border regulatory procedure.
RegulatoryProcedureGuaranteeCode | xsd:token | The code specifying an undertaking given in cash, bond or as a written guarantee to ensure that an obligation will be fulfilled for this cross-border regulatory procedure.
GoodsStatusCode | xsd:token | The code specifying the goods status for this cross-border regulatory procedure.
PaymentOfficeLocation | [edi3:LogisticsLocation](#LogisticsLocation) | The location of an office at which a payment relevant to this cross-border regulatory procedure is made.
DebtorFinancialAccount | [edi3:DebtorFinancialAccount](#DebtorFinancialAccount) | A debtor financial account specified for this cross-border regulatory procedure.
ControlStartDateConfirmationIndicator | xsd:boolean | The indication of whether or not the start date of a control has been confirmed for this cross-border regulatory procedure.


<h1 id="InstalmentPlan">InstalmentPlan</h1>

Type: rdf:Class

Description: A plan for paying a total sum of money by several payments made over a period of time.

Properties: 

name | type | description
-|-|-


<h1 id="ReturnableAssetInstructions">ReturnableAssetInstructions</h1>

Type: rdf:Class

Description: The procedures to follow for returnable assets, such as reusable packaging (pallets, crates).

Properties: 

name | type | description
-|-|-
TermsAndConditionsText | xsd:string | A textual description of the terms and conditions for these returnable asset instructions.
DepositValidityPeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The specified period during which the deposit value specified in these returnable asset instructions is valid.
ReturnableAssetInstructionsMaterialID | xsd:token | An identifier of the material to which these returnable asset instructions apply.
TermsAndConditionsCode | xsd:token | The code specifying the description of the terms and conditions for these returnable asset instructions.


<h1 id="HandlingInstructions">HandlingInstructions</h1>

Type: rdf:Class

Description: Handling information of an instructive nature.

Properties: 

name | type | description
-|-|-
HandlingInstructionsHandlingCode | xsd:token | A code specifying these handling instructions.
MaximumStorageHumidity | xsd:decimal | The measure of the maximum storage humidity applicable to these handling instructions.
HandlingInstructionsMaximumStackabilityWeight | xsd:decimal | The maximum stackability weight applicable to these handling instructions.
MinimumStorageHumidity | xsd:decimal | The measure of the minimum storage humidity applicable to these handling instructions.
HandlingInstructionsProcedureText | xsd:string | A procedure, expressed as text, for these handling instructions.
HandlingInstructionsID | xsd:token | The identifier of this handling instructions.
TransportSettingTemperature | [edi3:TransportSettingTemperature](#TransportSettingTemperature) | A transport related temperature setting applicable to these handling instructions.
HandlingInstructionsDescriptionCode | xsd:token | A code specifying a description of these handling instructions.
DeliveryInstructedTemperature | [edi3:InstructedTemperature](#InstructedTemperature) | The instructed temperature for delivery applicable to these handling instructions.
MarketDeliveryInstructedTemperature | [edi3:InstructedTemperature](#InstructedTemperature) | The instructed temperature for market delivery applicable to these handling instructions.
StorageInstructedTemperature | [edi3:InstructedTemperature](#InstructedTemperature) | The instructed temperature for storage applicable to these handling instructions.
HandlingInstructionsDescription | xsd:string | A textual description of these handling instructions.


<h1 id="QuarantineInstructions">QuarantineInstructions</h1>

Type: rdf:Class

Description: Instructions for a period of imposed isolation or detention.

Properties: 

name | type | description
-|-|-
QuarantineInstructionsDescription | xsd:string | The textual description of these quarantine instructions.


<h1 id="DeliveryInstructions">DeliveryInstructions</h1>

Type: rdf:Class

Description: Delivery information of an instructive nature.

Properties: 

name | type | description
-|-|-
DeliveryInstructionsDescription | xsd:string | A textual description of these delivery instructions.
HandlingText | xsd:string | Delivery handling instructions expressed as text.
DeliveryInstructionsHandlingCode | xsd:token | A code specifying delivery handling instructions.


<h1 id="TemperatureSettingInstructions">TemperatureSettingInstructions</h1>

Type: rdf:Class

Description: Temperature setting related information of an instructive nature.

Properties: 

name | type | description
-|-|-
TemperatureSettingInstructionsDescription | xsd:string | A textual description of these temperature setting instructions.
TemperatureSettingInstructionsProcedureText | xsd:string | A procedure, expressed as text, for these temperature setting instructions.


<h1 id="TransportInstructions">TransportInstructions</h1>

Type: rdf:Class

Description: Transport information of an instructive nature.

Properties: 

name | type | description
-|-|-
TransportInstructionsDescription | xsd:string | A textual description of these transport instructions.


<h1 id="HaulageInstructions">HaulageInstructions</h1>

Type: rdf:Class

Description: Instructions related to the action or process of conveyance.

Properties: 

name | type | description
-|-|-
HaulageInstructionsDescription | xsd:string | The textual description of these haulage instructions.


<h1 id="DisposalInstructions">DisposalInstructions</h1>

Type: rdf:Class

Description: A set of instructions detailing how to properly dispose of a material.

Properties: 

name | type | description
-|-|-
RecyclingDescriptionCode | xsd:token | A code describing recycling in these disposal instructions.
DisposalInstructionsMaterialID | xsd:token | The identifier of the material to which these disposal instructions apply.
DisposalInstructionsDescription | xsd:string | A textual description of these disposal instructions.


<h1 id="Booking">Booking</h1>

Type: rdf:Class

Description: A result of a financial transaction recorded within a financial account.

Properties: 

name | type | description
-|-|-
BookingActualDateTime | xsd:dateTime | An actual date, time, date time, or other date time value of this financial booking.
DebitDateTime | xsd:dateTime | The debit date, time, date time, or other date time value of this financial booking.


<h1 id="AccountingAccount">AccountingAccount</h1>

Type: rdf:Class

Description: A specific trade account for recording debits and credits to general accounting, cost accounting or budget accounting.

Properties: 

name | type | description
-|-|-
AccountingAccountTypeCode | xsd:token | The code specifying the type of trade accounting account, such as general (main), secondary, cost accounting or budget account.
SetTriggerCode | xsd:token | A code specifying a set trigger for this trade accounting account to be used in response to a specific event or a set of events.
AccountingAccountID | xsd:token | The unique identifier for this trade accounting account.
AccountingAccountName | xsd:string | The name, expressed as text, of this trade accounting account.
CostReferenceDimensionPatternText | xsd:string | The cost reference dimension pattern, expressed as text, for this trade accounting account.


<h1 id="GeographicalMultiPoint">GeographicalMultiPoint</h1>

Type: rdf:Class

Description: A collection of points, on the surface of the Earth (reference ISO 19136).

Properties: 

name | type | description
-|-|-
GeographicalMultiPointDirectPositionList | [edi3:DirectPositionList](#DirectPositionList) | The direct position list associated with this geographical multi-point.
GeographicalMultiPointGeographicalObjectCharacteristic | [edi3:GeographicalObjectCharacteristic](#GeographicalObjectCharacteristic) | The geographical object characteristic associated with this geographical multi-point.


<h1 id="PaymentMeans">PaymentMeans</h1>

Type: rdf:Class

Description: The means by which a payment will be or has been made for trade settlement purposes.

Properties: 

name | type | description
-|-|-
PayerDebtorFinancialInstitution | [edi3:DebtorFinancialInstitution](#DebtorFinancialInstitution) | The debtor financial institution of the payer party specified for this trade settlement payment means.
PayerDebtorFinancialAccount | [edi3:DebtorFinancialAccount](#DebtorFinancialAccount) | The debtor financial account of the payer party for this trade settlement payment means.
PaymentMeansInformation | xsd:string | Information, expressed as text, for this trade settlement payment means.
PayeeCreditorFinancialAccount | [edi3:CreditorFinancialAccount](#CreditorFinancialAccount) | A creditor financial account of the payee party for this trade settlement payment means.
TradeSettlementPaymentMeansID | xsd:token | An identifier for this trade settlement payment means.
GuaranteeMethodCode | xsd:token | The code specifying the method of guarantee for this trade settlement payment means.
PaymentMeansTypeCode | xsd:token | The code specifying the type of trade settlement payment means, such as cash or check.
PaymentMeansSpecifiedCreditorFinancialAccount | [edi3:CreditorFinancialAccount](#CreditorFinancialAccount) | A creditor financial account specified for this trade settlement payment means.
PayeeCreditorFinancialInstitution | [edi3:CreditorFinancialInstitution](#CreditorFinancialInstitution) | The creditor financial institution of the payee party specified for this trade settlement payment means.
PaymentMeansPaymentMethodCode | xsd:token | The code specifying the method by which a payment may be made for this trade settlement payment means.
PaymentMeansFinancialCard | [edi3:FinancialCard](#FinancialCard) | A financial card applicable to this trade settlement payment means.


<h1 id="Project">Project</h1>

Type: rdf:Class

Description: An endeavour carefully planned to achieve a procurement of goods, works and service.

Properties: 

name | type | description
-|-|-
NetBudgetAmount | xsd:decimal | The monetary value of the net budget for this procuring project.
SubWorksTypeCode | xsd:token | A code specifying the type of sub works, such as land surveying or information technology consulting, for this procuring project.
WorksTypeCode | xsd:token | A code specifying the type of work, such as surveying or consulting, for this procuring project.
ProjectID | xsd:token | The unique identifier of this procuring project.
ProjectName | xsd:string | The name, expressed as text, of this procuring project.
ProjectTypeCode | xsd:token | The code specifying the type of procuring project, such as goods, works and service.
TotalBudgetAmount | xsd:decimal | The monetary value of the total budget which includes net amount, taxes, and material and instalment costs for this procuring project.
ProjectDescription | xsd:string | The textual description of this procuring project.


<h1 id="Qualification">Qualification</h1>

Type: rdf:Class

Description: An academic achievement that is officially recognized.

Properties: 

name | type | description
-|-|-
QualificationName | xsd:string | A name, expressed as text, of this academic qualification.


<h1 id="Chemical">Chemical</h1>

Type: rdf:Class

Description: Any clearly defined substance having a defined molecular composition.

Properties: 

name | type | description
-|-|-
MolecularWeight | xsd:decimal | The measure of the molecular weight (in grams) for this distinct chemical.
ChemicalTypeCode | xsd:token | The code specifying the type of distinct chemical.
FormulaDescription | xsd:string | The textual description of the formula for this distinct chemical.
ChemicalCommonName | xsd:string | A common name, expressed as text, for this distinct chemical.
ChemicalFamilyName | xsd:string | The family name expressed as text for this distinct chemical.
ChemicalScientificName | xsd:string | The scientific name, expressed as text, for this distinct chemical.


<h1 id="CreditorFinancialAccount">CreditorFinancialAccount</h1>

Type: rdf:Class

Description: A specific business arrangement whereby credits arising from transactions are recorded.

Properties: 

name | type | description
-|-|-
CreditorFinancialAccountProprietaryID | xsd:token | The unique proprietary identifier for this creditor financial account.
CreditorFinancialAccountTypeCode | xsd:token | The code specifying the type of creditor financial account.
CreditorFinancialAccountIBANID | xsd:token | The unique International Bank Account Number (IBAN) identifier for this creditor financial account.
CreditorFinancialAccountName | xsd:string | The account name, expressed as text, of this creditor financial account.
CreditorFinancialAccountCurrencyCode | xsd:token | The code specifying the currency of this creditor financial account (Reference ISO 4217 codes).
CreditorFinancialAccountUPICID | xsd:token | The unique Universal Payment Identification Code (UPIC) identifier used by the New York Clearing House for this creditor financial account.
CreditorFinancialAccountBBANID | xsd:token | The unique Basic Bank Account Number (BBAN) identifier used as part of a National Account Numbering Scheme(s) for this creditor financial account.
CreditorFinancialAccountProprietaryTypeText | xsd:string | The proprietary type, expressed as text, of this creditor financial account, such as the nature or use of the creditor account.


<h1 id="DebtorFinancialAccount">DebtorFinancialAccount</h1>

Type: rdf:Class

Description: A specific business arrangement whereby debits arising from transactions are recorded.

Properties: 

name | type | description
-|-|-
DebtorFinancialAccountProprietaryTypeText | xsd:string | The proprietary type, expressed as text, of this debtor financial account, such as the nature or use of the debtor account.
DebtorFinancialAccountBBANID | xsd:token | The unique Basic Bank Account Number (BBAN) identifier used as part of a National Account Numbering Scheme(s) for this debtor financial account.
DebtorFinancialAccountIBANID | xsd:token | The unique International Bank Account Number (IBAN) identifier for this debtor financial account.
DebtorFinancialAccountProprietaryID | xsd:token | The unique proprietary identifier for this debtor financial account.
DeprecatedProprietaryAccountName | xsd:string | The proprietary account name, expressed as text, of this debtor financial account.
DebtorFinancialAccountUPICID | xsd:token | The unique Universal Payment Identification Code (UPIC) identifier used by the New York Clearing House for this debtor financial account.
DebtorFinancialAccountCurrencyCode | xsd:token | The code specifying the currency of this debtor financial account (Reference ISO 4217 codes).
DebtorFinancialAccountName | xsd:string | The account name, expressed as text, of this debtor financial account.


<h1 id="FinancingFinancialAccount">FinancingFinancialAccount</h1>

Type: rdf:Class

Description: A financial account used internally by a bank to manage the line of credit granted to financing requesting party.

Properties: 

name | type | description
-|-|-
FinancingFinancialAccountIBANID | xsd:token | The unique International Bank Account Number (IBAN) identifier for this financing financial account.
FinancingFinancialAccountProprietaryID | xsd:token | The proprietary identifier for this financing financial account.
FinancingFinancialAccountName | xsd:string | The account name, expressed as text, of this financing financial account.
FinancingFinancialAccountProprietaryTypeText | xsd:string | The proprietary type, expressed as text, of this financing financial account, such as the nature or use.
FinancingFinancialAccountTypeCode | xsd:token | The code specifying the type of financing financial account.
FinancingFinancialAccountUPICID | xsd:token | The unique Universal Payment Identification Code (UPIC) identifier used by the New York Clearing House for this financing financial account.
FinancingFinancialAccountCurrencyCode | xsd:token | The code specifying the currency of this financing financial account.


<h1 id="Note">Note</h1>

Type: rdf:Class

Description: A textual or coded description, such as a remark or additional information.

Properties: 

name | type | description
-|-|-
SubjectCode | xsd:token | A code specifying the subject of this note.
NoteID | xsd:token | A unique identifier for this note.
NoteContentCode | xsd:token | A code specifying the content of this note.
SubjectText | xsd:string | The subject, expressed as text, of this note.


<h1 id="HeaderTradeDelivery">HeaderTradeDelivery</h1>

Type: rdf:Class

Description: Shipping arrangements and movement of products and or services including despatch and delivery at a header level.

Properties: 

name | type | description
-|-|-
HeaderTradeDeliveryPlannedConsignment | [edi3:Consignment](#Consignment) | A consignment, at header level, planned for this trade delivery.
HeaderTradeDeliveryDespatchedQuantity | xsd:decimal | The quantity, at header level, despatched in this trade delivery.
UltimateShipToDeliveryEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | The ultimate ship to delivery event, at header level, for this trade delivery.
HeaderTradeDeliveryAdditionalDocument | [edi3:Document](#Document) | An additional document, at header level, referenced for this trade delivery.
HeaderTradeDeliveryHandlingInstructions | [edi3:HandlingInstructions](#HandlingInstructions) | Handling instructions, at header level, specified for this trade delivery.
HeaderTradeDeliveryDespatchAdviceDocument | [edi3:Document](#Document) | The despatch advice document, at header level, referenced for this trade delivery.
HeaderTradeDeliveryRelatedConsignment | [edi3:Consignment](#Consignment) | A consignment, at header level, related to this trade delivery.
HeaderTradeDeliveryIncludedPackaging | [edi3:Packaging](#Packaging) | Packaging, at header level, included in this trade delivery.
HeaderTradeDeliveryPlannedPickUpEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | The pick-up event, at header level, planned for this trade delivery.
UltimateShipToDeliveryDateTime | xsd:dateTime | The date, time, date time, or other date time value, at header level, when this trade delivery is delivered to the ultimate ship to party.
HeaderTradeDeliveryRequestedDespatchEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | A despatch event, at header level, requested for this trade delivery.
HeaderTradeDeliveryOverDeliveryAllowedIndicator | xsd:boolean | The indication, at header level, of whether or not over delivery is allowed for this trade delivery.
RemainingRequestedQuantity | xsd:decimal | The remaining quantity, at header level, requested for this trade delivery.
HeaderTradeDeliveryConfirmedPickUpEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | The pick-up event, at header level, confirmed for this trade delivery.
GoodsPhysicalStateTypeText | xsd:string | A type, expressed as text, for the physical state of the goods, at header level, for this trade delivery.
HeaderTradeDeliveryRequestedQuantity | xsd:decimal | The quantity, at header level, requested for this trade delivery.
HeaderTradeDeliveryID | xsd:token | The identifier, at header level, for this trade delivery.
HeaderTradeDeliveryPreviousDeliveryEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | A previous delivery event, at header level, for this trade delivery.
GoodsPhysicalStateDescriptionCode | xsd:token | The code specifying a description for the physical state of the goods, at header level, for this trade delivery.
HeaderTradeDeliveryConsumptionReportDocument | [edi3:Document](#Document) | The consumption report document, at header level, referenced for this trade delivery.
HeaderTradeDeliveryPlannedDeliveryEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | A delivery event, at header level, planned for this trade delivery.
HeaderTradeDeliveryGoodsOwnershipChangeDateTime | xsd:dateTime | The date, time, date time, or other date time value, at header level, when the goods ownership of this trade delivery changed.
HeaderTradeDeliveryFinalDestinationCountry | [edi3:Country](#Country) | The country of final destination, at header level, for this header trade delivery.
HeaderTradeDeliveryDisposalParty | [edi3:TradeParty](#TradeParty) | A disposal party, at header level, for this trade delivery.
HeaderTradeDeliveryDueInForecastedQuantity | xsd:decimal | The due in forecasted quantity, at header level, for this trade delivery.
HeaderTradeDeliveryShipToParty | [edi3:TradeParty](#TradeParty) | The ship to party, at header level, for this trade delivery.
HeaderTradeDeliveryDueInAvailableQuantity | xsd:decimal | The due in available quantity, at header level, for this trade delivery.
HeaderTradeDeliveryPartialDeliveryAllowedIndicator | xsd:boolean | The indication, at header level, of whether or not this trade delivery can be partially delivered.
HeaderTradeDeliveryInventoryManager | [edi3:TradeParty](#TradeParty) | An inventory manager party, at header level, for this trade delivery.
HeaderTradeDeliveryShipmentScheduleDocument | [edi3:Document](#Document) | The shipment schedule document, referenced at header level, for this trade delivery.
HeaderTradeDeliveryAgreedQuantity | xsd:decimal | The quantity, at header level, agreed for this trade delivery.
HeaderTradeDeliveryGoodsReceiptNote | [edi3:Document](#Document) | A goods receipt note document, at header level, referenced for this trade delivery.
HeaderTradeDeliveryRequestedDeliveryEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | A delivery event, at header level, requested for this trade delivery.
HeaderTradeDeliveryActualReceiptEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | The actual receipt event, at header level, for this trade delivery.
HeaderTradeDeliveryPlannedShipToDeliveryEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | The planned ship to delivery event, at header level, for this trade delivery.
PlannedShipFromDeliveryEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | The event of the planned ship from delivery, at header level, for this trade delivery.
HeaderTradeDeliveryConfirmedDespatchEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | The despatch event, at header level, confirmed for this trade delivery.
HeaderTradeDeliveryPlannedDespatchEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | A despatch event, at header level, planned for this trade delivery.
HeaderTradeDeliveryInformationNote | [edi3:Note](#Note) | A note with information, at header level, for this trade delivery.
HeaderTradeDeliveryModificationForecastedQuantity | xsd:decimal | The modification of a previously forecasted quantity, at header level, for this trade delivery.
PlannedReleaseEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | The release event, at header level, planned for this trade delivery.
HeaderTradeDeliveryShipFromParty | [edi3:TradeParty](#TradeParty) | The ship from party, at header level, for this trade delivery.
HeaderTradeDeliveryActualDeliveryEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | An actual delivery event, at header level, for this trade delivery.
HeaderTradeDeliveryActualDespatchEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | An actual despatch event, at header level, for this trade delivery.
HeaderTradeDeliveryDeliveryInstructions | [edi3:DeliveryInstructions](#DeliveryInstructions) | Delivery instructions, at header level, specified for this trade delivery.
HeaderTradeDeliverySubordinateID | xsd:token | A subordinate identifier, at header level, for this trade delivery.
GoodsPhysicalStateDescriptionText | xsd:string | A textual description for the physical state of the goods, at header level, for this trade delivery.
HeaderTradeDeliveryUltimateShipToParty | [edi3:TradeParty](#TradeParty) | The ultimate ship to party, at header level, for this trade delivery.
HeaderTradeDeliveryConfirmedReleaseEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | The confirmed release event, at header level, for this trade delivery.
GoodsPhysicalStateTypeCode | xsd:token | The code specifying the type of physical state of the goods, at header level, for this trade delivery.
HeaderTradeDeliveryActualUnloadingEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | The actual unloading event, at header level, for this trade delivery.
HeaderTradeDeliveryDueInRequestedQuantity | xsd:decimal | The due in requested quantity, at header level, for this trade delivery.
HeaderTradeDeliveryBuyerOrderDateTime | xsd:dateTime | The date, time, date time, or other date time value, at header level, of the buyer order for this trade delivery.
HeaderTradeDeliveryAcceptanceEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | An acceptance delivery event, at header level, for this trade delivery.
HeaderTradeDeliveryActualLoadingEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | The actual loading event, at header level, for this trade delivery.
PickUpAvailabilityDateTime | xsd:dateTime | The formatted date, time, date time, or other date time value, at header level, when this trade delivery is available for pick-up.
HeaderTradeDeliveryReceivingAdviceDocument | [edi3:Document](#Document) | A receiving advice document, at header level, referenced for this trade delivery.
HeaderTradeDeliveryStatusCode | xsd:token | The code specifying the status, at header level, for this trade delivery.
HeaderTradeDeliveryFullyDeliveredIndicator | xsd:boolean | The indication, at header level, of whether or not this trade delivery is fully delivered.
HeaderTradeDeliveryPackingListDocument | [edi3:Document](#Document) | The packing list document, at header level, referenced for this trade delivery.
HeaderTradeDeliveryDeliveryNoteDocument | [edi3:Document](#Document) | The delivery note document, at header level, referenced for this trade delivery.
HeaderTradeDeliveryFinalDeliveryIndicator | xsd:boolean | The indication, at header level, of whether or not this trade delivery is the final delivery.


<h1 id="SubordinateLineTradeDelivery">SubordinateLineTradeDelivery</h1>

Type: rdf:Class

Description: Supply chain shipping arrangements and movement of products and or services including despatch and delivery.

Properties: 

name | type | description
-|-|-
SubordinateLineTradeDeliveryProductUnitQuantity | xsd:decimal | The number of product units in this subordinate line trade delivery.
SubordinateLineTradeDeliveryPackageQuantity | xsd:decimal | The number of packages in this subordinate line trade delivery.
SubordinateLineTradeDeliveryIncludedPackaging | [edi3:Packaging](#Packaging) | Packaging included in this subordinate line trade delivery.


<h1 id="LineTradeDelivery">LineTradeDelivery</h1>

Type: rdf:Class

Description: Shipping arrangements and movement of products and or services including despatch and delivery at a line level.

Properties: 

name | type | description
-|-|-
LineTradeDeliveryPerPackageUnitQuantity | xsd:decimal | The number of units per package, at line level, in this trade delivery.
LineTradeDeliveryRequestedQuantity | xsd:decimal | The quantity, at line level, requested for this trade delivery.
LineTradeDeliveryFullyDeliveredIndicator | xsd:boolean | The indication, at line level, of whether or not this trade delivery is fully delivered.
UnavailableQuantity | xsd:decimal | The quantity, at line level, unavailable for this trade delivery.
LineTradeDeliveryFinalDeliveryIndicator | xsd:boolean | The indication, at line level, of whether or not this trade delivery is the final delivery.
LineTradeDeliveryModificationForecastedQuantity | xsd:decimal | The modification of a forecasted quantity, at line level, for this trade delivery.
LineTradeDeliveryGoodsReceiptNote | [edi3:Document](#Document) | The goods receipt note document, at line level, referenced for this trade delivery.
LineTradeDeliveryUsedTransportEquipment | [edi3:ReferencedTransportEquipment](#ReferencedTransportEquipment) | A piece of logistics transport equipment, at line level, utilized for this trade delivery.
RemainingRequestedDeliveryQuantity | xsd:decimal | The remaining quantity, at line level, requested for this trade delivery.
ChargeableWeightMeasure | xsd:decimal | The measure of the chargeable weight, at line level, for this trade delivery.
LineTradeDeliveryRequestedDeliveryEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | A delivery event, at line level, requested for this trade delivery.
ProjectedSupplyPlan | [edi3:SupplyPlan](#SupplyPlan) | A supply plan, at line level, projected for this trade delivery.
LineTradeDeliveryActualPickUpEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | The actual pick-up event, at line level, for this trade delivery.
ReverseBilledQuantity | xsd:decimal | The reverse billed quantity, at line level, for this trade delivery.
LineTradeDeliveryPlannedConsignment | [edi3:Consignment](#Consignment) | A consignment, at line level, planned for this trade delivery.
LineTradeDeliveryFinalDestinationCountry | [edi3:Country](#Country) | The country of final destination, at line level, for line trade delivery.
LineTradeDeliveryStatusCode | xsd:token | The code specifying the status, at line level, for this trade delivery.
LineTradeDeliveryAcceptanceEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | An acceptance delivery event, at line level, for this trade delivery.
LineTradeDeliveryPackingListDocument | [edi3:Document](#Document) | The packing list document, at line level, referenced for this trade delivery.
TheoreticalWeight | xsd:decimal | The measure, at line level, of the theoretical weight of this trade delivery.
ReturnedQuantity | xsd:decimal | The quantity, at line level, returned for this trade delivery.
LineTradeDeliveryDueInAvailableQuantity | xsd:decimal | The due in available quantity, at line level, for this trade delivery.
DueInReturnedQuantity | xsd:decimal | The due in returned quantity, at line level, for this trade delivery.
LineTradeDeliveryDespatchAdviceDocument | [edi3:Document](#Document) | The despatch advice document, at line level, referenced for this trade delivery.
DespatchSchedule | [edi3:Schedule](#Schedule) | A supply chain despatch schedule, at line level, for this trade delivery.
LineTradeDeliveryPlannedDeliveryEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | A delivery event, at line level, planned for this trade delivery.
CustomerInventory | [edi3:SupplyChainInventory](#SupplyChainInventory) | Supply chain customer inventory, at line level, for this trade delivery.
LineTradeDeliveryDeliveryInstructions | [edi3:DeliveryInstructions](#DeliveryInstructions) | Delivery instructions, at line level, specified for this trade delivery.
LineTradeDeliveryRelatedConsignment | [edi3:Consignment](#Consignment) | A consignment, at line level, related to this line trade delivery.
DestroyedQuantity | xsd:decimal | The quantity, at line level, destroyed for this trade delivery.
ChargeFreeQuantity | xsd:decimal | The quantity, at line level, free of charge, in this trade delivery.
QuantityVariationTypeCode | xsd:token | The code specifying the type of quantity variation, at line level, for this trade delivery.
LineTradeDeliveryActualUnloadingEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | The actual unloading event, at line level, for this trade delivery.
CancelledQuantity | xsd:decimal | The quantity, at line level, cancelled for this trade delivery.
LineTradeDeliveryConfirmedPickUpEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | The pick-up event, at line level, confirmed for this trade delivery.
LineTradeDeliveryInformationNote | [edi3:Note](#Note) | A note with information, at line level, for this trade delivery.
LineTradeDeliveryActualReceiptEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | The actual receipt event, at line level, for this trade delivery.
QuantityVariationReasonCode | xsd:token | The code specifying the reason for the quantity variation, at line level, for this trade delivery.
LineTradeDeliveryConsumptionReportDocument | [edi3:Document](#Document) | The consumption report document, at line level, referenced from this trade delivery.
GFMTransferRejectedQuantity | xsd:decimal | The Government Furnished Material (GFM) transfer rejected quantity, at line level, for this trade delivery.
LineTradeDeliveryConfirmedReleaseEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | The release event, at line level, confirmed for this trade delivery.
FormattedPickUpAvailabilityDateTime | xsd:dateTime | The formatted date, time, date time, or other date time value, at line level, when this delivery is available for pick-up.
LineTradeDeliveryPlannedDespatchEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | A despatch event, at line level, planned for this trade delivery.
FormattedUltimateShipToDeliveryDateTime | xsd:dateTime | The formatted date, time, date time, or other date time value, at line level, when this trade delivery is delivered to the ultimate ship to party.
LineTradeDeliveryDueInForecastedQuantity | xsd:decimal | The due in forecasted quantity, at line level, for this trade delivery.
LineTradeDeliveryOverDeliveryAllowedIndicator | xsd:boolean | The indication, at line level, of whether or not over delivery is allowed for this trade delivery.
LatestDespatchedQuantity | xsd:decimal | The latest quantity, at line level, despatched in this trade delivery.
LineTradeDeliveryEconomicOrderQuantity | xsd:decimal | The economic order quantity, at line level, for this trade delivery.
LineTradeDeliveryProductUnitQuantity | xsd:decimal | The number of product units, at line level, in this trade delivery.
LineTradeDeliveryAdditionalDocument | [edi3:Document](#Document) | An additional document, at line level, referenced for this trade delivery.
ReceivedQuantity | xsd:decimal | The quantity, at line level, received for this trade delivery.
IndividualPackageQuantity | xsd:decimal | The quantity within the individual package, at line level, for this trade delivery.
LineTradeDeliveryGrossVolume | xsd:decimal | The measure, at line level, of the gross volume of this trade delivery.
Supply(Replenishment)Schedule | [edi3:Schedule](#Schedule) | A supply (replenishment) schedule, specified at line level, for this trade delivery.
LineTradeDeliveryConfirmedDespatchEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | The despatch event, at line level, confirmed for this trade delivery.
LineTradeDeliveryHandlingInstructions | [edi3:HandlingInstructions](#HandlingInstructions) | Handling instructions, at line level, specified for this trade delivery.
QuantityDiscrepancyNatureCode | xsd:token | The code specifying the nature of the discrepancy of the quantity, at line level, for this trade delivery.
AvailableQuantity | xsd:decimal | The quantity, at line level, available for this trade delivery.
BilledQuantity | xsd:decimal | The quantity, at line level, billed for in this trade delivery.
TurnInReceivedQuantity | xsd:decimal | The turn in quantity, at line level, received for this trade delivery.
LineTradeDeliveryAgreedQuantity | xsd:decimal | The quantity, at line level, agreed for this trade delivery.
LineTradeDeliveryGoodsOwnershipChangeDateTime | xsd:dateTime | The date, time, date time, or other date time value for the goods ownership change, at line level, for this trade delivery.
LineTradeDeliveryShipFromParty | [edi3:TradeParty](#TradeParty) | The ship from party, at line level, for this trade delivery.
LineTradeDeliveryTransportDangerousGoods | [edi3:DangerousGoods](#DangerousGoods) | The transport dangerous goods details, at line level, applicable to this trade delivery.
LineTradeDeliveryShipToParty | [edi3:TradeParty](#TradeParty) | The ship to party, at line level, for this trade delivery.
LineTradeDeliveryDisposalParty | [edi3:TradeParty](#TradeParty) | A disposal party, at line level, for this trade delivery.
LineTradeDeliveryPlannedShipToDeliveryEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | The planned ship to delivery event, at line level, for this trade delivery.
AvailableInventory | [edi3:SupplyChainInventory](#SupplyChainInventory) | Inventory available, at line level, for this trade delivery.
ConsumptionSchedule | [edi3:Schedule](#Schedule) | A supply chain consumption schedule, at line level, for this trade delivery.
LineTradeDeliveryGrossWeight | xsd:decimal | The measure, at line level, of the gross weight (mass) of this line trade delivery.
LineTradeDeliveryConfirmedDeliveryEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | The confirmed delivery event, at line level, for this trade delivery.
RejectedQuantity | xsd:decimal | The quantity, at line level, rejected for this trade delivery.
LineTradeDeliveryBuyerOrderDateTime | xsd:dateTime | The date, time, date time, or other date time value, at line level, of the buyer order for this trade delivery.
SpecifiedSchedule | [edi3:Schedule](#Schedule) | A supply chain schedule, specified at line level, for this trade delivery.
ConsignmentInventory | [edi3:SupplyChainInventory](#SupplyChainInventory) | Supply chain consignment inventory, at line level, for this trade delivery.
LogisticsServiceProvider | [edi3:TradeParty](#TradeParty) | A logistics service provider party, at line level, for this trade delivery.
LineTradeDeliveryPlannedPickUpEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | The pick-up event, at line level, planned for this trade delivery.
LineTradeDeliveryShipmentScheduleDocument | [edi3:Document](#Document) | The shipment schedule document referenced, at line level, for this trade delivery.
LineTradeDeliveryUltimateShipToParty | [edi3:TradeParty](#TradeParty) | The ultimate ship to party, at line level, for this trade delivery.
LineTradeDeliveryID | xsd:token | An identifier, at line level, for this trade delivery.
LineTradeDeliveryPartialDeliveryAllowedIndicator | xsd:boolean | The indication, at line level, of whether or not this trade delivery can be partially delivered.
LineTradeDeliverySubordinateID | xsd:token | A subordinate identifier, at line level, for this trade delivery.
UsedLogisticsLabel | [edi3:Label](#Label) | A logistics label, at line level, used for this trade delivery.
LineTradeDeliveryInventoryManager | [edi3:TradeParty](#TradeParty) | An inventory manager party, at line level, for this trade delivery.
LineTradeDeliveryLogisticsPackage | [edi3:Package](#Package) | A logistics package, at line level, specified for this trade delivery.
LineTradeDeliveryNetWeight | xsd:decimal | The measure, at line level, of the net weight (mass) of this trade delivery.
OrderSchedule | [edi3:Schedule](#Schedule) | A supply chain order schedule, at line level, for this trade delivery.
ReceiptSchedule | [edi3:Schedule](#Schedule) | A supply chain receipt schedule, at line level, for this trade delivery.
LineTradeDeliveryActualDespatchEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | An actual despatch event, at line level, for this trade delivery.
LineTradeDeliveryActualDeliveryEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | An actual delivery event, at line level, for this trade delivery.
LineTradeDeliveryDueInRequestedQuantity | xsd:decimal | The due in requested quantity, at line level, for this trade delivery.
OrderQuantity | xsd:decimal | The quantity, at line level, ordered for this trade delivery.
LineTradeDeliveryDeliveryNoteDocument | [edi3:Document](#Document) | The delivery note document, at line level, referenced for this trade delivery.
LineTradeDeliveryIncludedPackaging | [edi3:Packaging](#Packaging) | Packaging included, at line level, in this trade delivery.
DeliveryAdjustment | [edi3:DeliveryAdjustment](#DeliveryAdjustment) | A delivery adjustment, at line level, specified for this trade delivery.
QuantityVariationReasonText | xsd:string | A reason, expressed as text, for a quantity variation, at line level, for this trade delivery.
LineTradeDeliveryNetVolume | xsd:decimal | The measure, at line level, of the net volume of this line trade delivery.
LineTradeDeliveryPackageQuantity | xsd:decimal | The number of packages, at line level, in this trade delivery.
LineTradeDeliveryReceivingAdviceDocument | [edi3:Document](#Document) | A receiving advice document, at line level, referenced for this trade delivery.
DeliverySchedule | [edi3:Schedule](#Schedule) | A supply chain delivery schedule, at line level, for this trade delivery.
LineTradeDeliveryActualLoadingEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | The actual loading event, at line level, for this trade delivery.
LineTradeDeliveryDespatchedQuantity | xsd:decimal | The quantity, at line level, despatched for this trade delivery.


<h1 id="Country">Country</h1>

Type: rdf:Class

Description: The area of land that belongs to a nation together with its properties, such as population, political organization, etc., used or referenced for trade purposes.

Properties: 

name | type | description
-|-|-
SubDivision | [edi3:CountrySubDivision](#CountrySubDivision) | A trade country sub-division that is subordinate to this trade country, such as a state, a county, a canton, a province.
CountryCode | xsd:token | A unique identifier for this trade country.


<h1 id="Seal">Seal</h1>

Type: rdf:Class

Description: A device used to secure an object and protect it from unauthorized entry or tampering during transport or other logistics operations.

Properties: 

name | type | description
-|-|-
SealingPartyRoleCode | xsd:token | The code specifying the role of the party responsible for the sealing of this logistics seal.
SealID | xsd:token | A unique identifier for this logistics seal.
SealTypeCode | xsd:token | The code specifying the type of logistics seal.
MaximumID | xsd:token | The maximum unique identifier used for these logistics seals.
IssuingParty | [edi3:TradeParty](#TradeParty) | The party issuing this logistics seal.


<h1 id="Package">Package</h1>

Type: rdf:Class

Description: A self-contained wrapping or container within which goods can be contained for logistics purposes, such as a box or a barrel which can be filled, partially filled or empty.

Properties: 

name | type | description
-|-|-
PackageID | xsd:token | The unique identifier for this logistics package.
PackageLevelCode | xsd:token | The code specifying the level of this logistics package.
PackageDescription | xsd:string | A textual description of this logistics package.
PackageNominalGrossWeight | xsd:decimal | The measure of the nominal gross weight (mass) of this logistics package and its contents.
PackageParentID | xsd:token | The unique parent identifier for this logistics package.
UsedPackaging | [edi3:Packaging](#Packaging) | Supply chain packaging used for this logistics package.
PackageSeriesStartID | xsd:token | The unique start identifier of a series of packages within this logistics package.
PackagePerPackageUnitQuantity | xsd:decimal | A number of units per package in this logistics package.
PackageShippingMarks | [edi3:ShippingMarks](#ShippingMarks) | Physical shipping marks and barcode information for this logistics package.
PackageSequenceNumber | xsd:decimal | The sequence number of this logistics package.
LogisticsPackageTypeCode | xsd:token | A code specifying the type of logistics package.
PackageInformation | xsd:string | Information, expressed as text, for this logistics package.
PackageNominalGrossVolume | xsd:decimal | The measure of the nominal gross volume of this logistics package.
PackageTypeText | xsd:string | A type, expressed as text, of this logistics package.
PackageDimensions | [edi3:SpatialDimension](#SpatialDimension) | The linear spatial dimensions of this logistics package.
PackageItemQuantity | xsd:decimal | The number of logistics packages at this level.
PackageGrossWeight | xsd:decimal | The measure of the gross weight (mass) of this logistics package and its contents.
PackageNetWeight | xsd:decimal | The measure of the net weight of this logistics package, i.e. the weight (mass) of the contents.
PackageSeriesEndID | xsd:token | The unique identifier of the end of a series of packages within this logistics package.
PackageGlobalID | xsd:token | The unique global identifier for this logistics package.
PackageReturnableIndicator | xsd:boolean | The indication of whether or not this logistics package is returnable.
DespatchNoteDocument | [edi3:Document](#Document) | A despatch note associated with this logistics package.
PackageGrossVolume | xsd:decimal | The measure of the gross volume of this logistics package.
PackageColourCode | xsd:token | The code specifying the colour of this logistics package.


<h1 id="ReferencedPackage">ReferencedPackage</h1>

Type: rdf:Class

Description: A referenced self-contained wrapping or container within which goods can be contained for logistics purposes.

Properties: 

name | type | description
-|-|-
ReferencedPackageSeriesEndID | xsd:token | The identifier of the end of a series of packages within this referenced logistics package.
ReferencedPackageSeriesStartID | xsd:token | The identifier of the start of a series of packages within this referenced logistics package.
ReferencedPackageInformation | xsd:string | Information, expressed as text, for this referenced logistics package.
ReferencedPackageColourCode | xsd:token | The code specifying the colour of this referenced logistics package.
ReferencedPackageGlobalID | xsd:token | The global identifier for this referenced logistics package.
ReferencedPackageNominalGrossVolume | xsd:decimal | The measure of the nominal gross volume of this referenced logistics package.
ReferencedPackageGrossWeight | xsd:decimal | The measure of the gross weight (mass) of this referenced logistics package and its contents.
ReferencedPackageItemQuantity | xsd:decimal | The number of referenced logistics packages at this level.
ReferencedPackageLevelCode | xsd:token | The code specifying the level of this referenced logistics package.
ReferencedPackagePerPackageUnitQuantity | xsd:decimal | A number of units per package in this referenced logistics package.
ReferencedPackageTypeCode | xsd:token | The code specifying the type of referenced logistics package.
ReferencedPackageSequenceNumber | xsd:decimal | The sequence number of this referenced logistics package.
ReferencedPackageGrossVolume | xsd:decimal | The measure of the gross volume of this referenced logistics package.
ReferencedPackagePhysicalShippingMarks | [edi3:ShippingMarks](#ShippingMarks) | Physical logistics shipping marks in this referenced logistics package.
ReferencedPackageID | xsd:token | The identifier for this referenced logistics package.
ReferencedPackageParentID | xsd:token | The parent identifier for this referenced logistics package.
ReferencedPackageDescription | xsd:string | A textual description of this referenced logistics package.
ReferencedPackageTypeText | xsd:string | A type, expressed as text, of this referenced logistics package.
ReferencedPackageNetWeight | xsd:decimal | The measure of the net weight (mass) of the contents of this referenced logistics package.


<h1 id="TransportPerson">TransportPerson</h1>

Type: rdf:Class

Description: A transport related person, such as a member of a crew or a passenger.

Properties: 

name | type | description
-|-|-
TransportPersonRoleText | xsd:string | A role, expressed as text, of this transport person.
CrewTravelEffects | [edi3:PersonalEffects](#PersonalEffects) | Personal effects use declared by a transport person.
NationalityCountry | [edi3:Country](#Country) | A country that constitutes a nationality by origin, birth, or naturalization for this transport person.
TransportPersonLanguageCode | xsd:token | A unique identifier of a language related to this transport person, such as their spoken or correspondence language.
TransportPersonMobileTelephone | [edi3:UniversalCommunication](#UniversalCommunication) | Mobile telephone communication information for this transport person.
EmbarkationLocation | [edi3:LogisticsLocation](#LogisticsLocation) | An embarkation location for this transport person.
DisembarkationLocation | [edi3:LogisticsLocation](#LogisticsLocation) | A disembarkation location for this transport person.
TransportPersonFamilyName | xsd:string | A family name, expressed as text, for this transport person.
TravelIdentityDocument | [edi3:Document](#Document) | A referenced travel identity document for this transport person.
TransportPersonGivenName | xsd:string | A given name, expressed as text, for this transport person.
BirthplaceName | xsd:string | The name, expressed as text, of the place where this transport person was born.
TransportPersonCategoryCode | xsd:token | A code specifying a category for this transport person, such as a member of crew or passenger.
CertifiedAccreditation | [edi3:Accreditation](#Accreditation) | A certified accreditation specific to this transport person.
GenderCode | xsd:token | A code specifying the gender of this transport person.
TransportPersonEmailAddress | [edi3:UniversalCommunication](#UniversalCommunication) | The email URI (Uniform Resource Identifier) communication for this transport person.
TransportPersonRoleCode | xsd:token | A code specifying a role of this transport person.
TransportPersonBirthDateTime | xsd:dateTime | The birth date of this transport person.
TransportPersonName | xsd:string | The name or set of names, expressed as text, by which this transport person is known.
InTransitIndicator | xsd:boolean | The indication of whether or not this transport person is in transit.
TravelVisaDocument | [edi3:Document](#Document) | A referenced travel visa document for this transport person.
TransportPersonID | xsd:token | The unique identifier for this transport person.
BirthCountryCode | xsd:token | The identifier of the birth country of this transport person.
AttainedQualification | [edi3:Qualification](#Qualification) | An academic qualification attained by this transport person.


<h1 id="ContactPerson">ContactPerson</h1>

Type: rdf:Class

Description: An individual human being in a position to give assistance or information.

Properties: 

name | type | description
-|-|-
SpecifiedEmployerIdentity | [edi3:EmployerIdentity](#EmployerIdentity) | An employer identity specified for this contact person.
ContactPersonRoleText | xsd:string | A role, expressed as text, for this contact person.
SpecifiedPersonIdentity | [edi3:PersonIdentity](#PersonIdentity) | The person identity specified for this contact person.
ContactPersonTelephone | [edi3:TelecommunicationCommunication](#TelecommunicationCommunication) | Telephone communication information for this contact person.
ContactPersonEmailAddress | [edi3:EmailCommunication](#EmailCommunication) | The email Uniform Resource Identifier (URI) communication for this contact person.
ContactPersonFax | [edi3:TelecommunicationCommunication](#TelecommunicationCommunication) | Facsimile communication information for this contact person.
ContactPersonGivenName | xsd:string | The name, expressed as text, given to this contact person, usually by parents at birth.
SpecifiedBirthAddress | [edi3:BirthAddress](#BirthAddress) | The birth address specified for this contact person.
ContactPersonFamilyName | xsd:string | The name, expressed as text, that this contact person shares with members of his/her family.
ResidenceCountryCode | xsd:token | The identifier of the residence country of this contact person.
MiddleName | xsd:string | The middle name, expressed as text, of this contact person, usually given by parents at birth.
SpecifiedTaxRegistration | [edi3:TaxRegistration](#TaxRegistration) | A tax registration specified for this contact person.
ContactPersonBirthDateTime | xsd:dateTime | The date, time, date time or other date time value which specifies the birth date for this contact person.


<h1 id="AuthoritativeSignatoryPerson">AuthoritativeSignatoryPerson</h1>

Type: rdf:Class

Description: A person who is authorized to sign a document, such as a customs officer or other government official.

Properties: 

name | type | description
-|-|-
AttainedAcademicQualification | [edi3:Qualification](#Qualification) | An academic qualification attained by this authoritative signatory person.


<h1 id="SupplyChainInventory">SupplyChainInventory</h1>

Type: rdf:Class

Description: Supply chain goods and materials held in stock.

Properties: 

name | type | description
-|-|-
DispositionDocument | [edi3:Document](#Document) | A disposition document referenced in this supply chain inventory.
StockQuantity | xsd:decimal | The quantity of stock in this supply chain inventory.
AverageDurationDateTime | xsd:dateTime | The date, time, date time, or other date time of the average duration for this supply chain inventory.
SupplyChainInventoryLocation | [edi3:LogisticsLocation](#LogisticsLocation) | The location specified for this supply chain inventory.
PlannedStockQuantity | xsd:decimal | The planned stock quantity for this supply chain inventory.
AverageDemandQuantity | xsd:decimal | The average demand quantity for this supply chain inventory.
MinimumStockQuantity | xsd:decimal | The minimum stock quantity in this CI supply chain inventory.
MaximumStockQuantity | xsd:decimal | The maximum stock quantity in this CI supply chain inventory.
PlannedStockCalculationDateTime | xsd:dateTime | The date, time, date time, or other date time value of the planned stock calculation of this supply chain inventory.
CalculationDateTime | xsd:dateTime | The date, time, date time, or other date time value of the calculation of this supply chain inventory.
SupplyChainInventoryStatusCode | xsd:token | The code specifying a status for this supply chain inventory.
MaximumStockLevelMeasure | xsd:decimal | The measure of the maximum stock level for this supply chain inventory.
SupplyChainInventoryRemark | [edi3:Note](#Note) | A note containing a remark for this supply chain inventory.
MinimumStockLevelMeasure | xsd:decimal | The measure of the minimum stock level for this supply chain inventory.


<h1 id="StoresItemInventory">StoresItemInventory</h1>

Type: rdf:Class

Description: A stores item, such as for onboard use during a journey.

Properties: 

name | type | description
-|-|-
StoresItemInventorySequenceNumber | xsd:decimal | A sequence number for this stores inventory item.
StoresItemInventoryOnboardQuantity | xsd:decimal | An onboard quantity for this stores inventory item.
StoresItemInventoryTypeCode | xsd:token | A code specifying the type of stores inventory item.
StoresItemInventoryDescription | xsd:string | A textual description of this stores inventory item.


<h1 id="Cargo">Cargo</h1>

Type: rdf:Class

Description: Information about goods being transported identifying their nature for customs, statistical or transport purposes.

Properties: 

name | type | description
-|-|-
CargoTypeCode | xsd:token | The code, such as UNECE Recommendation 21 single digit codes, specifying the type of transported cargo.
IdentificationText | xsd:string | Identification, expressed as text, of this transport cargo that is sufficient to identify it for customs, statistical or transport purposes.
StatisticalClassificationCode | xsd:token | The code specifying a statistical classification for this transport cargo.


<h1 id="Organization">Organization</h1>

Type: rdf:Class

Description: An organization set up on a legal basis as a business, government body, department, charity, or financial institution.

Properties: 

name | type | description
-|-|-
AuthorizedRegistration | [edi3:LegalRegistration](#LegalRegistration) | A legal registration authorized for this legally set up organization.
EstablishedDateTime | xsd:dateTime | The date, time, date time, or other date time value when this legally set up organization was established.
TradingName | xsd:string | The trading business name, expressed as text, of this legally set up organization.
OrganizationTypeCode | xsd:token | A code specifying a type of legally set up organization.
OrganizationID | xsd:token | A unique identifier for this legally set up organization.
OrganizationPostalAddress | [edi3:TradeAddress](#TradeAddress) | A postal address for this legally set up organization.
OrganizationName | xsd:string | A name, expressed as text, of this legally set up organization.
BusinessTypeCode | xsd:token | A code specifying the type of business of this legally set up organization.


<h1 id="PersonalEffects">PersonalEffects</h1>

Type: rdf:Class

Description: Specified privately owned articles for personal use by an individual.

Properties: 

name | type | description
-|-|-
PersonalEffectsOnboardQuantity | xsd:decimal | An onboard number of these specified personal effects.
PersonalEffectsDescription | xsd:string | A textual description of these specified personal effects.
PersonalEffectsTypeCode | xsd:token | A code specifying a type of specified personal effects.


<h1 id="ReferencedTransportEquipment">ReferencedTransportEquipment</h1>

Type: rdf:Class

Description: A referenced piece of equipment used to hold, protect or secure cargo for logistics purposes.

Properties: 

name | type | description
-|-|-
ReferencedTransportEquipmentUnitQuantity | xsd:decimal | The number of units of this type of referenced logistics transport equipment.
ReferencedTransportEquipmentCategoryCode | xsd:token | The code specifying the category of this referenced piece of logistics transport equipment.
ReferencedTransportEquipmentCharacteristicText | xsd:string | The characteristics, expressed as text, of a referenced piece of logistics transport equipment, such as size and type.
ReferencedTransportEquipmentID | xsd:token | The unique identifier for this referenced piece of logistics transport equipment, such as a number, mark or name.
ReferencedTransportEquipmentGrossWeight | xsd:decimal | The measure of the gross weight (mass) of this piece of referenced logistics transport equipment which is the weight (mass) including loaded goods, packing and transport equipment.
ReferencedTransportEquipmentLoadedPackageQuantity | xsd:decimal | The number of packages loaded into or onto this piece of referenced logistics transport equipment.
ReferencedTransportEquipmentTemperatureSetting | [edi3:TransportSettingTemperature](#TransportSettingTemperature) | A temperature setting for this piece of referenced logistics transport equipment, such as storage temperature or operational temperature.
ReferencedTransportEquipmentCarrierAssignedBookingID | xsd:token | A carrier assigned booking identifier for this piece of referenced logistics transport equipment.
ReferencedTransportEquipmentNetWeight | xsd:decimal | The measure of the net weight (mass) of this piece of referenced logistics transport equipment.
ReferencedTransportEquipmentAffixedSeal | [edi3:Seal](#Seal) | A seal affixed to this piece of referenced logistics transport equipment.
ReferencedTransportEquipmentSizeTypeCode | xsd:token | The code specifying the characteristics, such as size and type, of this referenced piece of logistics transport equipment.


<h1 id="TransportEquipment">TransportEquipment</h1>

Type: rdf:Class

Description: A piece of equipment used to hold, protect or secure cargo for logistics purposes.

Properties: 

name | type | description
-|-|-
TransportEquipmentBondedWarehouseStorageEvent | [edi3:Event](#Event) | A bonded warehouse storage event specifying when and where this piece of logistics transport equipment will be, or has been, stored.
ContainedConsignmentQuantity | xsd:decimal | The number of consignments contained in this piece of logistics transport equipment.
TransportEquipmentApplicableNote | [edi3:Note](#Note) | A note providing information applicable to this piece of logistics transport equipment.
TransportEquipmentLoadingInstructions | [edi3:TransportInstructions](#TransportInstructions) | Loading instructions for this piece of logistics transport equipment.
ReleaseRestrictionText | xsd:string | The release restriction, expressed as text, for this piece of logistics transport equipment.
TransportEquipmentDamageRemark | xsd:string | A damage remark, expressed as text, for this piece of logistics transport equipment.
ContainedTransportEquipment | [edi3:AssociatedTransportEquipment](#AssociatedTransportEquipment) | A piece of transport equipment contained within this piece of logistics transport equipment, such as a pallet.
ContainedConsignment | [edi3:Consignment](#Consignment) | A consignment contained in this piece of logistics transport equipment.
TransportEquipmentRelatedCommunicationEvent | [edi3:CommunicationEvent](#CommunicationEvent) | A communication event related to this piece of logistics transport equipment.
TransportEquipmentUnitQuantity | xsd:decimal | The number of units of this type of logistics transport equipment.
HumidityPercent | xsd:decimal | The percent of the humidity (moisture content) within this piece of logistics transport equipment.
TransportEquipmentLoadedPackageQuantity | xsd:decimal | The number of packages loaded into or onto this piece of logistics transport equipment.
TransportEquipmentLoadingSequenceNumber | xsd:decimal | The sequence number differentiating this piece of logistics transport equipment from others during loading.
TransportEquipmentInformation | xsd:string | Information, expressed as text, for this piece of logistics transport equipment.
ConsolidationEvent | [edi3:Event](#Event) | A consolidation event specifying when and where this piece of logistics transport equipment will be, or has been, stuffed.
TransportEquipmentDeliveryInstructions | [edi3:DeliveryInstructions](#DeliveryInstructions) | Delivery instructions for this piece of logistics transport equipment.
TransportEquipmentCarrierAssignedBookingID | xsd:token | A carrier assigned booking identifier for this piece of logistics transport equipment.
IOTDeviceReportingTransportEvent | [edi3:Event](#Event) | An IOT device reported transport event for this piece of logistics transport equipment.
TransportEquipmentAffixedSeal | [edi3:Seal](#Seal) | A seal affixed to this piece of logistics transport equipment.
TransportEquipmentPickUpEvent | [edi3:Event](#Event) | A pick-up event specifying when and where this piece of logistics transport equipment will be, or has been, collected, i.e. picked-up by the carrier.
TransportEquipmentReturnableIndicator | xsd:boolean | The indication of whether or not this piece of logistics transport equipment is returnable.
TransportServicesBuyer | [edi3:TradeParty](#TradeParty) | The transport services buyer party for this piece of logistics transport equipment.
TransportEquipmentGrossWeight | xsd:decimal | The measure of the gross weight (mass) of this piece of logistics transport equipment which is the weight (mass) including loaded goods, packing and transport equipment.
LoadedConsignmentItem | [edi3:ConsignmentItem](#ConsignmentItem) | A consignment item loaded onto, or into, this piece of logistics transport equipment.
TransportEquipmentApplicableServiceCharge | [edi3:ServiceCharge](#ServiceCharge) | A service charge applicable to this piece of logistics transport equipment.
LoadedDangerousGoods | [edi3:DangerousGoods](#DangerousGoods) | Dangerous goods loaded into this piece of logistics transport equipment.
ActualTransportRoute | [edi3:Route](#Route) | An actual route for this piece of logistics transport equipment.
HaulageArrangementCode | xsd:token | The code specifying the arrangement for the haulage of this piece of logistics transport equipment.
TransportEquipmentDeliveryEvent | [edi3:Event](#Event) | A delivery event for this piece of logistics transport equipment.
TransportEquipmentQuarantineInstructions | [edi3:QuarantineInstructions](#QuarantineInstructions) | Quarantine instructions for this piece of logistics transport equipment.
ScheduledTransportRoute | [edi3:Route](#Route) | A scheduled or planned route for this piece of logistics transport equipment.
PowerSupplyTypeText | xsd:string | The type of power supply, expressed as text, for this piece of logistics transport equipment, such as diesel fuel or electricity.
CarriedTransportEquipment | [edi3:AssociatedTransportEquipment](#AssociatedTransportEquipment) | A piece of transport equipment carried on this piece of logistics transport equipment, such as a container placed on a rail wagon.
TransportEquipmentStorageEvent | [edi3:Event](#Event) | A storage event specifying when and where this piece of logistics transport equipment will be, or has been, stored.
TransportEquipmentHandlingInstructions | [edi3:HandlingInstructions](#HandlingInstructions) | Handling instructions for this piece of logistics transport equipment.
ReleaseID | xsd:token | The release identifier for this piece of logistics transport equipment.
TransportEquipmentCarrier | [edi3:TradeParty](#TradeParty) | A carrier party for this piece of logistics transport equipment.
TransportEquipmentCategoryCode | xsd:token | The code specifying the category for this piece of logistics transport equipment, such as container or trailer.
TransportEquipmentLoadingLength | xsd:decimal | The measure of the loading length of this piece of logistics transport equipment.
TransportEquipmentReportedStatus | [edi3:LogisticsStatus](#LogisticsStatus) | A status reported for this piece of logistics transport equipment.
FullEmptyCode | xsd:token | The code specifying the used capacity of this piece of logistics transport equipment, such as full or empty.
SpecifiedTransportMeans | [edi3:LogisticsTransportMeans](#LogisticsTransportMeans) | A transport means specified for this piece of logistics transport equipment.
TransportEquipmentDimensions | [edi3:SpatialDimension](#SpatialDimension) | The linear spatial dimensions of this piece of logistics transport equipment.
SealedIndicator | xsd:boolean | The indication of whether or not this piece of logistics transport equipment is sealed.
TransportEquipmentAssociatedDocument | [edi3:Document](#Document) | A referenced document associated with this piece of logistics transport equipment.
TransportEquipmentGrossVolume | xsd:decimal | The measure of the gross volume of this piece of logistics transport equipment.
TareWeight | xsd:decimal | The measure of the tare weight (mass) of this piece of logistics transport equipment which is the weight (mass) including permanent equipment but excluding goods and loose accessories.
TransportEquipmentCharacteristicText | xsd:string | The characteristic or characteristics, expressed as text, of a piece of logistics transport equipment, such as its size and type.
UnloadingInstructions | [edi3:TransportInstructions](#TransportInstructions) | Unloading instructions for this piece of logistics transport equipment.
TransportEquipmentNotifiedParty | [edi3:TradeParty](#TradeParty) | A party who has been or will be notified about this piece of logistics transport equipment.
IOTDeviceReportingCommunicationPairing | [edi3:Pairing](#Pairing) | An IOT device reported communication pairing for this piece of logistics transport equipment.
TransportEquipmentSizeTypeCode | xsd:token | The code specifying the characteristic or characteristics of this piece of logistics transport equipment, such as the ISO 6346 transport equipment size and type code.
TransportEquipmentAttachedMonitoringIOTDevice | [edi3:IOTDevice](#IOTDevice) | An IOT device attached to this piece of logistics transport equipment.
TransportEquipmentOperationalStatusCode | xsd:token | The code specifying the operational status for this piece of logistics transport equipment, such as to be repaired or to be shifted.
TransportMovementStatusCode | xsd:token | The code specifying the transport movement status for this piece of logistics transport equipment, such as for export, for import, or for transhipment.
LoadingRemark | xsd:string | A loading remark, expressed as text, for this piece of logistics transport equipment.
AirFlowMeasure | xsd:decimal | The measure of the air flow for this piece of logistics transport equipment.
TransportEquipmentSequenceNumber | xsd:decimal | The sequence number differentiating this piece of logistics transport equipment from others in a set of transport equipment.
PositioningEvent | [edi3:Event](#Event) | A positioning event specifying when and where this piece of logistics transport equipment will be, or has been, positioned, i.e. delivered and available for pick-up.
TransportEquipmentLogisticsRiskAnalysisResult | [edi3:RiskAnalysisResult](#RiskAnalysisResult) | A result of a logistics risk analysis calculation specified for this transport equipment.
StowagePosition | xsd:token | The stowage position identifier for this piece of logistics transport equipment.
TransportEquipmentUnloadingSequenceNumber | xsd:decimal | The sequence number differentiating this piece of logistics transport equipment from others during unloading.
TransportEquipmentManufacturerParty | [edi3:TradeParty](#TradeParty) | The manufacturer party specified for this piece of logistics transport equipment.
TransportEquipmentUnloadingEvent | [edi3:Event](#Event) | The unloading event for this piece of logistics transport equipment.
LegalStatusCode | xsd:token | The code specifying the legal status of this piece of logistics transport equipment with respect to a specific law such as the "Container Convention Code".
AdditionalInstructions | [edi3:TransportInstructions](#TransportInstructions) | Additional instructions for this piece of logistics transport equipment.
SealQuantity | xsd:decimal | The quantity of seals for this piece of logistics transport equipment.
TransportEquipmentAttachedTransportEquipment | [edi3:AttachedTransportEquipment](#AttachedTransportEquipment) | Transport equipment attached to this piece of logistics transport equipment, such as ropes or refrigeration units.
PowerSupplyTypeCode | xsd:token | The code specifying the type of power supply for this piece of logistics transport equipment, such as diesel fuel or electricity.
SupplierPartyRoleCode | xsd:token | The code specifying the role of the party responsible for supplying this piece of logistics transport equipment, such as the carrier or the buyer.
TransportEquipmentManufacturngDateTime | xsd:dateTime | The manufacturing date, time, date time, or other date time value for this piece of logistics transport equipment.
AccompaniedIndicator | xsd:boolean | The indication of whether or not this piece of logistics transport equipment is accompanied, such as by a transport means.
LoadingParty | [edi3:TradeParty](#TradeParty) | The party that loads this piece of logistics transport equipment.
TransportEquipmentID | xsd:token | The unique identifier of this piece of logistics transport equipment.
RequestedTransportRoute | [edi3:Route](#Route) | A requested route for this piece of logistics transport equipment.
TransportEquipmentNetWeight | xsd:decimal | The measure of the net weight (mass) of this piece of logistics transport equipment.
OperatingParty | [edi3:TradeParty](#TradeParty) | The party that operates this piece of logistics transport equipment.
TransportEquipmentRequiredLaneLength | xsd:decimal | The measure of the length required in a lane for this piece of logistics transport equipment.
TransportEquipmentTemperatureSetting | [edi3:TransportSettingTemperature](#TransportSettingTemperature) | A temperature setting for this piece of logistics transport equipment, such as storage temperature or operational temperature.
PowerSupplyConnectorQuantity | xsd:decimal | The number of power supply connectors for this piece of logistics transport equipment.
ShipperReferenceInformation | xsd:string | Shipper reference information, expressed as text, for this piece of logistics transport equipment.


<h1 id="AssociatedTransportEquipment">AssociatedTransportEquipment</h1>

Type: rdf:Class

Description: A piece of transport equipment that is associated with another piece of transport equipment, such as a maritime container placed on a rail wagon for transportation.

Properties: 

name | type | description
-|-|-
AssociatedTransportEquipmentCharacteristicText | xsd:string | The textual description of the characteristics, i.e. size and type, of this piece of associated transport equipment.


<h1 id="AttachedTransportEquipment">AttachedTransportEquipment</h1>

Type: rdf:Class

Description: A piece of attached transport equipment, such as a chain or a tarpaulin.

Properties: 

name | type | description
-|-|-
AttachedTransportEquipmentCategoryCode | xsd:token | A code specifying a category of this piece of attached transport equipment.
CharacteristicCode | xsd:token | The code specifying the characteristics, i.e. size and type, of this piece of attached transport equipment.
AttachedTransportEquipmentCharacteristicText | xsd:string | The textual description of the characteristics, i.e. size and type, of this piece of attached transport equipment.
AttachedTransportEquipmentUnitQuantity | xsd:decimal | The number of units of attached transport equipment.


<h1 id="Consignment">Consignment</h1>

Type: rdf:Class

Description: A separately identifiable collection of goods items to be transported or available to be transported from one consignor to one consignee in a supply chain via one or more modes of transport where each consignment is the subject of one single transport contract.

Properties: 

name | type | description
-|-|-
ApplicableAllowanceCharge | [edi3:TradeAllowanceCharge](#TradeAllowanceCharge) | An allowance or charge applicable to this supply chain consignment.
CargoInsuranceInstructions | xsd:string | Cargo insurance instructions, expressed as text, for this supply chain consignment.
ConsignmentNetWeight | xsd:decimal | A measure of the net weight (mass) of this consignment which excludes the weight of packaging of this supply chain consignment and that of any transport equipment.
ConsignmentFinalDestinationCountry | [edi3:Country](#Country) | The final destination country for this supply chain consignment.
ConsignmentConsignorAssignedID | xsd:token | The unique identifier assigned by the consignor to this supply chain consignment.
ConsignmentDeclaredValueForCustomsAmount | xsd:decimal | The monetary value declared for customs purposes for this supply chain consignment.
ConsignmentGrossWeight | xsd:decimal | A measure of the gross weight (mass) of this supply chain consignment which includes the weight of packaging but which excludes the weight of any transport equipment.
ConsignmentPreviousAdministrativeDocument | [edi3:Document](#Document) | A previous administrative referenced document for this supply chain consignment.
MainCarriageTransportMovement | [edi3:TransportMovement](#TransportMovement) | A main carriage logistics transport movement for this supply chain consignment.
ConsignmentChargeableWeight | xsd:decimal | A measure of a chargeable weight of this supply chain consignment.
ShipStoresIndicator | xsd:boolean | The indication of whether or not this supply chain consignment is for ship stores, such as for consumption on the means of transport.
CODAmount | xsd:decimal | The monetary value of the COD (Cash On Delivery) amount to be collected by the carrier upon delivery of this supply chain consignment.
ConsignmentLoadingInstructions | [edi3:TransportInstructions](#TransportInstructions) | Loading instructions for this supply chain consignment.
UnloadingBaseportLocation | [edi3:LogisticsLocation](#LogisticsLocation) | The baseport location at which this supply chain consignment is to be unloaded from a means of transport according to the transport contract.
TransshipmentLocation | [edi3:LogisticsLocation](#LogisticsLocation) | A transshipment location for this supply chain consignment.
TransportServicesBuyerParty | [edi3:TradeParty](#TradeParty) | The party which is the buyer of the transport services for this supply chain consignment.
GoodsReleaseRestrictionText | xsd:string | A goods release restriction, expressed as text, for this supply chain consignment.
ConsignmentCustomsValuation | [edi3:CustomsValuation](#CustomsValuation) | A cross-border customs valuation applicable to this supply chain consignment.
ConsignmentDestinationCountry | [edi3:Country](#Country) | The destination country for this supply chain consignment.
ConsignmentPackageTypeText | xsd:string | A type of package, expressed as text, for this supply chain consignment.
LoadingInformation | xsd:string | Loading information, expressed as text, for this supply chain consignment, such as advice and instructions.
ExportExitDateTime | xsd:dateTime | The date, time, date time or other date time value when this supply chain consignment will exit, or has exited from the last port, airport, or border post of the country of export.
ConsignmentFOBAmount | xsd:decimal | The monetary value that has to be, or has been, paid for this supply chain consignment as calculated under FOB (Free on Board) delivery terms.
ConsignmentTransportEquipmentQuantity | xsd:decimal | A number of pieces of transport equipment, such as containers or similar unit load devices, in this supply chain consignment.
ConsignmentFreightForwarderAssignedID | xsd:token | The unique identifier assigned by the freight forwarder to this supply chain consignment.
ConsignmentDeliveryParty | [edi3:TradeParty](#TradeParty) | The party to whom this supply chain consignment will be, or has been, delivered.
ConsignmentTradeTransaction | [edi3:SupplyChainTradeTransaction](#SupplyChainTradeTransaction) | A trade transaction related to this supply chain consignment.
FreightForwarder | [edi3:TradeParty](#TradeParty) | The freight forwarder party for this supply chain consignment.
AtArrivalTransportMovement | [edi3:TransportMovement](#TransportMovement) | The logistics transport movement for this supply chain consignment at the point when the means of transport arrives in a country or at a regional border.
ConsignmentTransitCountry | [edi3:Country](#Country) | A transit country for this supply chain consignment.
ConsignmentLoadingLength | xsd:decimal | A measure of the loading length which is the length along a means of transport over which the complete width and height is needed for loading all the goods items in this supply chain consignment.
ConsignmentHandlingInstructions | [edi3:HandlingInstructions](#HandlingInstructions) | Handling instructions for this supply chain consignment, such as where or how specified packages or containers are to be loaded on a means of transport.
PickUpParty | [edi3:TradeParty](#TradeParty) | The pick-up trade party for this supply chain consignment.
ConsignmentExaminationEvent | [edi3:Event](#Event) | An examination event for this supply chain consignment.
CustomsImportAgent | [edi3:TradeParty](#TradeParty) | The party acting as an agent for, or on behalf of, the consignee with respect to the customs import procedures for this supply chain consignment.
ConsignmentPreCarriageTransportMovement | [edi3:TransportMovement](#TransportMovement) | A pre-carriage logistics transport movement for this supply chain consignment.
ConsignmentExportGeopoliticalRegion | [edi3:GeopoliticalRegion](#GeopoliticalRegion) | The geopolitical region of export for this supply chain consignment.
LoadingLocation | [edi3:LogisticsLocation](#LogisticsLocation) | The logistics location where the supply chain consignment is loaded.
ReExportCountry | [edi3:Country](#Country) | A re-export country for this supply chain consignment.
DemurrageInformation | xsd:string | Demurrage information, expressed as text, for this supply chain consignment.
ConsignorProvidedBorderClearanceInstructions | [edi3:TransportInstructions](#TransportInstructions) | Border clearance instructions provided by the consignor for this supply chain consignment.
ConsignmentOriginCountry | [edi3:Country](#Country) | A country of origin for this supply chain consignment.
LocalConsigneeAgent | [edi3:TradeParty](#TradeParty) | The local party authorized to act for or on behalf of the consignee for this supply chain consignment.
ConsignmentShipToParty | [edi3:TradeParty](#TradeParty) | The ship to party for this supply chain consignment.
NilCustomsValueIndicator | xsd:boolean | The indication of whether or not this supply chain consignment has a nil value for customs.
RelatedBookingTypeText | xsd:string | The type of booking, expressed as text, related to this supply chain consignment.
ConsignmentManifestDocument | [edi3:Document](#Document) | A referenced manifest document associated to this supply chain consignment.
ConsignmentDeclaredValueForCarriageAmount | xsd:decimal | The monetary value of this supply chain consignment as declared by the shipper or his agent for the purpose of varying the carrier's level of liability from that provided in the contract of carriage, in case of loss or damage to goods or delayed delivery.
ConsignmentCargoToleranceInformation | xsd:string | Cargo tolerance information, expressed as text, for this supply chain consignment.
TotalCollectChargeAmount | xsd:decimal | The total monetary value of all freight and other service charges which are to be collected from the consignee at or after delivery for this supply chain consignment.
TransshipmentPermittedIndicator | xsd:boolean | The indication of whether or not transshipment is permitted for this supply chain consignment.
ConsignmentRegulatoryProcedure | [edi3:RegulatoryProcedure](#RegulatoryProcedure) | A cross-border regulatory procedure applicable to this supply chain consignment.
ConsignmentCarrierAcceptanceLocation | [edi3:LogisticsLocation](#LogisticsLocation) | The location where this supply chain consignment will be, or has been, accepted by the carrier.
ConsignmentInvoicee | [edi3:TradeParty](#TradeParty) | An invoicee trade party associated with this supply chain consignment.
FinalDestinationLocation | [edi3:LogisticsLocation](#LogisticsLocation) | The final destination location for this supply chain consignment.
CustomsExportAgent | [edi3:TradeParty](#TradeParty) | The party acting as an agent for, or on behalf of, the consignor with respect to the customs export procedures for this supply chain consignment.
ConsignmentTransportPackage | [edi3:Package](#Package) | Transport packages for this supply chain consignment.
InsurancePremiumAmount | xsd:decimal | The monetary value of the insurance premium for this supply chain consignment.
Importer | [edi3:TradeParty](#TradeParty) | The party who imports this supply chain consignment.
ConsignmentTotalAllowanceChargeAmount | xsd:decimal | The total monetary value of all allowances and charges for this supply chain consignment.
GroupingCentre | [edi3:TradeParty](#TradeParty) | A grouping centre party for this supply chain consignment.
ConsignmentBondedWarehouseStorageEvent | [edi3:Event](#Event) | A bonded warehouse storage event for this supply chain consignment.
ConsignmentTransportSplitDescription | xsd:string | The textual description of the transport split of this supply chain consignment across different transport means or transport equipment.
ConsignmentLogisticsRiskAnalysisResult | [edi3:RiskAnalysisResult](#RiskAnalysisResult) | A result of a logistics risk analysis calculation specified for this supply chain consignment.
Exporter | [edi3:TradeParty](#TradeParty) | The party who exports this supply chain consignment.
ConsignmentOriginGeopoliticalRegion | [edi3:GeopoliticalRegion](#GeopoliticalRegion) | The geopolitical region of origin for this supply chain consignment.
ImportCountry | [edi3:Country](#Country) | The import country for this supply chain consignment.
ConsignmentConsigneeAssignedID | xsd:token | The unique identifier assigned by the consignee to this supply chain consignment.
ConsignmentDevanningEvent | [edi3:Event](#Event) | A transport devanning event for this supply chain consignment, i.e. the unloading of this consignment at the place of delivery.
ConsignmentCustomsID | xsd:token | A unique identifier, for customs purposes, for this consignment.
UnloadingLocation | [edi3:LogisticsLocation](#LogisticsLocation) | The logistics location where the supply chain consignment is unloaded.
NumberOfPackages | xsd:decimal | The number of packages within this supply chain consignment.
ConsigneeAgent | [edi3:TradeParty](#TradeParty) | The party authorized to act for or on behalf of the consignee for this supply chain consignment.
ConsignmentConsignee | [edi3:TradeParty](#TradeParty) | The consignee party for this supply chain consignment.
ConsignmentDespatchParty | [edi3:TradeParty](#TradeParty) | The party from whom this supply chain consignment will be or has been despatched.
RiskFactorCode | xsd:token | The code specifying a risk factor for this supply chain consignment.
ConsignmentStorageEvent | [edi3:Event](#Event) | A storage event for this supply chain consignment.
ConsignmentAssociatedParty | [edi3:TradeParty](#TradeParty) | A trade party associated with this supply chain consignment.
IncludedConsignment | [edi3:ReferencedConsignment](#ReferencedConsignment) | A referenced consignment included in this supply chain consignment.
CarrierProvidedInformation | xsd:string | Information, expressed as text, provided by the carrier for this supply chain consignment.
CustomsTransitAgent | [edi3:TradeParty](#TradeParty) | The party acting as an agent for, or on behalf of, the consignor with respect to customs transit procedures for this supply chain consignment.
TransportEquipmentSplitGoodsIndicator | xsd:boolean | The indication of whether or not the goods in this supply chain consignment are split across more than one piece of transport equipment.
CargoInsurance | [edi3:CargoInsurance](#CargoInsurance) | The cargo insurance applicable to this supply chain consignment.
ConsignmentDeliveryInstructions | [edi3:DeliveryInstructions](#DeliveryInstructions) | Delivery instructions for this supply chain consignment.
ConsignmentAssociatedDocument | [edi3:Document](#Document) | A referenced document associated with this supply chain consignment, such as the certificate of origin or dangerous goods note.
ConsignmentConsignor | [edi3:TradeParty](#TradeParty) | The consignor party for this supply chain consignment.
WarehouseArrivalDateTime | xsd:dateTime | The date, time, date time or other date time value of the arrival of this supply chain consignment at a warehouse.
ConsignmentVanningEvent | [edi3:Event](#Event) | The vanning event for this supply chain consignment, i.e. the loading of this consignment at the place of original despatch.
ConsignorAgent | [edi3:TradeParty](#TradeParty) | The party authorized to act for or on behalf of the consignor for this supply chain consignment.
InsuranceCurrencyExchange | [edi3:CurrencyExchange](#CurrencyExchange) | A currency exchange applicable to an insurance charge for this supply chain consignment.
ConsignmentCarrierAssignedID | xsd:token | The unique identifier assigned by the carrier to this supply chain consignment, such as a booking reference number when cargo space is reserved prior to loading.
ConsignmentGrossVolume | xsd:decimal | A measure of the gross volume, normally calculated by multiplying the maximum length, width and height of this supply chain consignment.
IntermediateConsignee | [edi3:TradeParty](#TradeParty) | A party that is an intermediate consignee for this supply chain consignment.
NilInsuranceValueIndicator | xsd:boolean | The indication of whether or not this supply chain consignment has a nil value for insurance.
TransitLocation | [edi3:LogisticsLocation](#LogisticsLocation) | A location of transit for this supply chain consignment.
OnCarriageTransportMovement | [edi3:TransportMovement](#TransportMovement) | An on-carriage logistics transport movement for this supply chain consignment.
TotalDisbursementAmount | xsd:decimal | The monetary value of total disbursement for this supply chain consignment, such as the amount to be collected by the carrier according to the order given by the consignor.
Deconsolidator | [edi3:TradeParty](#TradeParty) | The party responsible for the deconsolidation of this supply chain consignment.
ConsignmentDangerousGoods | [edi3:DangerousGoods](#DangerousGoods) | Dangerous goods applicable to the transport of this supply chain consignment.
ContainerizationIndicator | xsd:boolean | The indication of whether or not this supply chain consignment is to be transported in a container or containers.
ConsignmentDeliveryEvent | [edi3:Event](#Event) | The delivery event for this supply chain consignment.
ChargeableTransportationStageQuantity | xsd:decimal | The number of separately chargeable transportation stages to be covered by this supply chain consignment.
LoadingBaseportLocation | [edi3:LogisticsLocation](#LogisticsLocation) | The baseport location at which this supply chain consignment is to be loaded on a means of transport according to the transport contract.
TotalPrepaidChargeAmount | xsd:decimal | The total monetary value of all freight and other service charges which have been paid in advance for this supply chain consignment.
TradedParcelID | xsd:token | A traded parcel identifier for this supply chain consignment.
CustomsRequiredInvoiceDocument | [edi3:Document](#Document) | A referenced invoice document required by customs for this supply chain consignment.
ConsignmentExportCountry | [edi3:Country](#Country) | The export country for this supply chain consignment.
ConsignmentTransportService | [edi3:Service](#Service) | A transport service for this supply chain consignment.
ConsignmentReportedStatus | [edi3:LogisticsStatus](#LogisticsStatus) | A logistics status reported for this supply chain consignment.
AtDepartureTransportMovement | [edi3:TransportMovement](#TransportMovement) | The logistics transport movement for this supply chain consignment at the point when the means of transport departs a country or regional border.
ConsignmentInvoiceCurrencyExchange | [edi3:CurrencyExchange](#CurrencyExchange) | A currency exchange applicable to the invoice for this supply chain consignment.
ConsignmentApplicableServiceCharge | [edi3:ServiceCharge](#ServiceCharge) | A logistics service charge applicable to this supply chain consignment, such as freight or insurance charges.
SpecifiedDeliveryTerms | [edi3:DeliveryTerms](#DeliveryTerms) | Delivery terms specified for this supply chain consignment.
ConsignmentInsuranceValueAmount | xsd:decimal | The monetary value of this supply chain consignment as covered by an insurance policy.
ConsignmentTransportContractDocument | [edi3:Document](#Document) | The referenced transport contract document for this supply chain consignment, such as an airwaybill or a seawaybill.
DangerousGoodsNotifier | [edi3:TradeParty](#TradeParty) | The party responsible for providing the dangerous goods notification in accordance with the dangerous goods regulations relevant for this supply chain consignment.
ConsignmentTotalChargeAmount | xsd:decimal | The total monetary value of all freight and other service charges for this supply chain consignment.
ConsignorProvidedInformationText | xsd:string | Information, expressed as text, provided by the consignor for this supply chain consignment.
BorderCrossingTransportMovement | [edi3:TransportMovement](#TransportMovement) | A border crossing logistics transport movement for this supply chain consignment.
ConsignmentPickUpEvent | [edi3:Event](#Event) | The pick-up event for this supply chain consignment.
TransportEvent | [edi3:Event](#Event) | An event occurring during the transport of this supply chain consignment.
NetVolumeMeasure | xsd:decimal | A measure of the net volume of this supply chain consignment item which excludes all packaging.
ConsignmentCarrierAcceptanceDateTime | xsd:dateTime | The date, time, date time or other date time value when this supply chain consignment will be, or has been, accepted by the carrier.
ConsignmentUnloadingSequenceNumber | xsd:decimal | The unloading sequence number for this supply chain consignment.
ConsignmentCarrier | [edi3:TradeParty](#TradeParty) | The carrier party for this supply chain consignment.
EstimatedServiceCharge | [edi3:ServiceCharge](#ServiceCharge) | An estimated logistics service charge applicable to this supply chain consignment, such as freight or insurance charges.
ConsignmentIncludedConsignmentItem | [edi3:ConsignmentItem](#ConsignmentItem) | A consignment item included in this supply chain consignment.
LoadingListQuantity | xsd:decimal | The number of loading lists, manifests or similar documents for this supply chain consignment.
DeliveryInformation | xsd:string | The delivery information, expressed as text, for this supply chain consignment.
ConsignmentCarrierAgent | [edi3:TradeParty](#TradeParty) | The party acting as the agent of the carrier for this supply chain consignment.
ServiceChargeCurrencyExchange | [edi3:CurrencyExchange](#CurrencyExchange) | A currency exchange applicable to a service charge for this supply chain consignment.
SummaryDescription | xsd:string | A textual summary description of this supply chain consignment.
NatureIdentificationCargo | [edi3:Cargo](#Cargo) | Transport cargo details of this supply chain consignment sufficient to identify its nature for customs, statistical or transport purposes.
NilCarriageValueIndicator | xsd:boolean | The indication of whether or not this supply chain consignment has a nil value for carriage.
ConsignmentTotalExportExitToImportEntryChargeAmount | xsd:decimal | The monetary value of the total charge or charges of freight, insurance and other services for this supply chain consignment calculated from the export exit location to the import entry location.
ConsignmentID | xsd:token | A unique identifier for this supply chain consignment.
AvailabilityDueDateTime | xsd:dateTime | The date, time, date time or other date time value when this supply chain consignment is due to be available.
AssociatedInvoiceDiscountAmount | xsd:decimal | A monetary value of the discount on an invoice associated with this supply chain consignment.
ConsignmentSequenceNumber | xsd:decimal | A sequence number for this supply chain consignment.
ConsignmentPhysicalShippingMarks | [edi3:ShippingMarks](#ShippingMarks) | Physical logistics shipping marks and barcoding information related to this supply chain consignment.
ConsignmentNotifiedParty | [edi3:TradeParty](#TradeParty) | A party who has been or will be notified about this supply chain consignment.
AssociatedInvoiceAmount | xsd:decimal | A monetary value of an invoice associated with this supply chain consignment.
Consolidator | [edi3:TradeParty](#TradeParty) | The party responsible for the consolidation of this supply chain consignment.
ConsignmentShipFromParty | [edi3:TradeParty](#TradeParty) | The ship from party for this supply chain consignment.
ConsigneeReceiptLocation | [edi3:LogisticsLocation](#LogisticsLocation) | The location at which this supply chain consignment will be or has been received by the consignee.
AssociatedInvoiceDiscountPercent | xsd:decimal | A percent that is a discount on an invoice amount associated with this supply chain consignment.
ConsignmentUsedTransportEquipment | [edi3:TransportEquipment](#TransportEquipment) | Logistics transport equipment utilized for this supply chain consignment.
ConsignmentDeclaredForCustomsLocation | [edi3:LogisticsLocation](#LogisticsLocation) | The location of this supply chain consignment as declared for customs.
ConsignmentConsignmentItemQuantity | xsd:decimal | The number of consignment items separately defined for transport or customs purposes within this supply chain consignment.
ConsignmentPaymentArrangementCode | xsd:token | The code specifying the payment arrangements for this supply chain consignment.
SpecifiedTransportMovement | [edi3:TransportMovement](#TransportMovement) | A logistics transport movement specified for this supply chain consignment.
ConsignmentInformation | xsd:string | Information, expressed as text, for this supply chain consignment.
HaulageInstructions | [edi3:HaulageInstructions](#HaulageInstructions) | Haulage instructions for this supply chain consignment.
ConsignmentApplicableCurrencyExchange | [edi3:CurrencyExchange](#CurrencyExchange) | A currency exchange applicable to this supply chain consignment.
ConnectingCarrier | [edi3:TradeParty](#TradeParty) | A connecting carrier party for this supply chain consignment.


<h1 id="ReferencedConsignment">ReferencedConsignment</h1>

Type: rdf:Class

Description: A referenced, separately identifiable collection of goods items to be transported or available to be transported from one consignor to one consignee via one or more modes of transport where each consignment is the subject of one single transport contract.

Properties: 

name | type | description
-|-|-
ReferencedConsignmentConsignee | [edi3:TradeParty](#TradeParty) | The consignee party for this referenced supply chain consignment.
ReferencedConsignmentFreightForwarderAssignedID | xsd:token | The unique identifier assigned by the freight forwarder to this referenced supply chain consignment.
ReferencedConsignmentGrossWeight | xsd:decimal | A measure of the gross weight (mass) of this referenced supply chain consignment which includes the weight of packaging but which excludes the weight of any transport equipment.
ReferencedConsignmentConsigneeAssignedID | xsd:token | The unique identifier assigned by the consignee to this referenced supply chain consignment.
ReferencedConsignmentCarrierAcceptanceDateTime | xsd:dateTime | The date, time, date time or other date time value when this referenced supply chain consignment will be, or has been, accepted by the carrier.
ReferencedConsignmentUsedTransportEquipment | [edi3:TransportEquipment](#TransportEquipment) | Logistics transport equipment utilized for this referenced supply chain consignment.
ReferencedConsignmentDespatchParty | [edi3:TradeParty](#TradeParty) | The party from whom this referenced supply chain consignment will be or has been despatched.
ReferencedConsignmentLogisticsRiskAnalysisResult | [edi3:RiskAnalysisResult](#RiskAnalysisResult) | A result of a logistics risk analysis specified for this referenced supply chain consignment.
ReferencedConsignmentConsignorAssignedID | xsd:token | The unique identifier assigned by the consignor to this referenced supply chain consignment.
WarehouseStorageEvent | [edi3:Event](#Event) | A warehouse storage event for this referenced supply chain consignment.
ReferencedConsignmentDevanningEvent | [edi3:Event](#Event) | A transport devanning event for this referenced supply chain consignment, i.e. the unloading of this consignment at the place of delivery.
ReferencedConsignmentPreCarriageTransportMovement | [edi3:TransportMovement](#TransportMovement) | A pre-carriage logistics transport movement for this referenced supply chain consignment.
ReferencedConsignmentRegulatoryProcedure | [edi3:RegulatoryProcedure](#RegulatoryProcedure) | A cross-border regulatory procedure applicable to this referenced supply chain consignment.
ReferencedConsignmentCarrier | [edi3:TradeParty](#TradeParty) | The carrier party for this referenced supply chain consignment.
ReferencedConsignmentTradeTransaction | [edi3:SupplyChainTradeTransaction](#SupplyChainTradeTransaction) | A trade transaction related to this referenced supply chain consignment.
ReferencedConsignmentGrossVolume | xsd:decimal | A measure of the gross volume, normally calculated by multiplying the maximum length, width and height, of this referenced supply chain consignment.
ReferencedConsignmentTransportContractDocument | [edi3:Document](#Document) | The transport contract document for this referenced supply chain consignment, such as an airwaybill or a seawaybill.
ReferencedConsignmentCarrierAcceptanceLocation | [edi3:LogisticsLocation](#LogisticsLocation) | The location where this referenced supply chain consignment will be or has been accepted by the carrier.
ReferencedConsignmentIncludedConsignmentItem | [edi3:ReferencedConsignmentItem](#ReferencedConsignmentItem) | A referenced consignment item included in this referenced supply chain consignment.
ReferencedConsignmentNetWeight | xsd:decimal | A measure of the net weight (mass) of this referenced consignment which excludes the weight of packaging and the weight of any transport equipment.
ReferencedConsignmentConsignmentItemQuantity | xsd:decimal | The number of consignment items separately defined for transport or customs purposes within this referenced supply chain consignment.
ReferencedConsignmentCustomsID | xsd:token | The identifier, for customs purposes, for this referenced supply chain consignment.
ReferencedConsignmentDeliveryParty | [edi3:TradeParty](#TradeParty) | The party to whom this referenced supply chain consignment will be or has been delivered.
ReferencedConsignmentCarrierAssignedID | xsd:token | The unique identifier assigned by the carrier to this referenced supply chain consignment, such as a booking reference number when cargo space is reserved prior to loading.
ReferencedConsignmentSequenceNumber | xsd:decimal | The sequence number for this referenced supply chain consignment.
ReferencedConsignmentVanningEvent | [edi3:Event](#Event) | The vanning event (the loading of this consignment at the place of its original despatch) for this referenced supply chain consignment.
ReferencedConsignmentTransportPackage | [edi3:Package](#Package) | Transport packages for this referenced supply chain consignment.
ReferencedConsignmentTransportSplitDescription | xsd:string | The textual description of the transport split of this referenced supply chain consignment across different transport means or transport equipment.
ReferencedConsignmentID | xsd:token | A unique identifier for this referenced supply chain consignment.
ReferencedConsignmentConsignor | [edi3:TradeParty](#TradeParty) | The consignor party for this referenced supply chain consignment.


<h1 id="TradeSettlementPaymentMonetarySummation">TradeSettlementPaymentMonetarySummation</h1>

Type: rdf:Class

Description: A collection of monetary amount totals specified for a trade settlement payment.

Properties: 

name | type | description
-|-|-
EquivalentTransferTotalAmount | xsd:decimal | A monetary value transferred as an equivalent amount in the credit transfer payment in this trade settlement payment monetary summation, such as the amount transferred between debtor and creditor, before deduction of charges, expressed in the currency of the debtor's account, and transferred into a different currency.
TradeSettlementPaymentMonetarySummationAdjustedBalanceOutAmount | xsd:decimal | A monetary value that is an adjusted amount balanced out for this trade settlement payment monetary summation.
TradeSettlementPaymentMonetarySummationTaxTotalAmount | xsd:decimal | A monetary value of the total of all tax amounts reported in this trade settlement payment monetary summation.
TradeSettlementPaymentMonetarySummationPaymentTotalAmount | xsd:decimal | A monetary value of a payment total reported in this trade settlement payment monetary summation.
TradeSettlementPaymentMonetarySummationLineTotalAmountIncludingTaxes | xsd:decimal | A monetary value of the line total, including taxes, being reported in this trade settlement payment monetary summation.
TradeSettlementPaymentMonetarySummationNetLineTotalAmount | xsd:decimal | A monetary value of the net total of all line amounts, including line level allowances and charges and excluding line level taxes, being reported in this trade settlement payment monetary summation.
TradeSettlementPaymentMonetarySummationGrandTotalAmount | xsd:decimal | A monetary value of a grand total reported in this trade settlement payment monetary summation.
TradeSettlementPaymentMonetarySummationBalanceOutAmount | xsd:decimal | A monetary value that is an amount balanced out for this trade settlement payment monetary summation.


<h1 id="TradeSettlementLineMonetarySummation">TradeSettlementLineMonetarySummation</h1>

Type: rdf:Class

Description: A collection of monetary amount totals, specified at line level, for a trade settlement.

Properties: 

name | type | description
-|-|-
TradeSettlementLineMonetarySummationInformationAmount | xsd:decimal | A monetary value of an amount being reported for information in this trade settlement monetary summation.
TradeSettlementLineMonetarySummationLineTotalAmountIncludingTaxes | xsd:decimal | A monetary value of the line total, including taxes, being reported in this trade settlement line monetary summation.
TradeSettlementLineMonetarySummationNetIncludingTaxesLineTotalAmount | xsd:decimal | A monetary value of the total of all line amounts, including line level allowances and charges and including line level taxes, being reported in this trade settlement line monetary summation.
TradeSettlementLineMonetarySummationTotalRetailValueInformationAmount | xsd:decimal | A monetary value which constitutes the total retail value stated for information purposes in this trade settlement line monetary summation.
TradeSettlementLineMonetarySummationGrandTotalAmount | xsd:decimal | A monetary value of the grand total of this trade settlement line monetary summation, to include addition and subtraction of individual summation amounts.
TradeSettlementLineMonetarySummationDuePayableAmount | xsd:decimal | A monetary value that is an amount due and payable for this trade settlement line monetary summation, such as the amount due to the creditor.
TradeSettlementLineMonetarySummationPaymentTotalAmount | xsd:decimal | A monetary value of a payment total reported in this trade settlement line monetary summation.
TradeSettlementLineMonetarySummationTaxBasisTotalAmount | xsd:decimal | A monetary value of the total of all tax basis amounts being reported in this trade settlement line monetary summation.
TradeSettlementLineMonetarySummationNetLineTotalAmount | xsd:decimal | A monetary value of the total of all line amounts, including line level allowances and charges and excluding line level taxes, being reported in this trade settlement line monetary summation.
TradeSettlementLineMonetarySummationLineTotalAmount | xsd:decimal | A monetary value of the line amount total being reported in this trade settlement line monetary summation.
TradeSettlementLineMonetarySummationTaxTotalAmount | xsd:decimal | A monetary value of the total of all tax amounts being reported in this trade settlement line monetary summation.
TradeSettlementLineMonetarySummationTotalAllowanceChargeAmount | xsd:decimal | A monetary value of a total allowance and charge reported in this trade settlement line monetary summation.
TradeSettlementLineMonetarySummationAllowanceTotalAmount | xsd:decimal | A monetary value of the total of all allowance amounts being reported in this trade settlement line monetary summation.
ProductWeightLossInformationAmount | xsd:decimal | A monetary value of the loss of weight of a product, such as fresh goods, stated for information purposes in this trade settlement line monetary summation.
TradeSettlementLineMonetarySummationChargeTotalAmount | xsd:decimal | A monetary value of the total of all charge amounts being reported in this trade settlement line monetary summation.


<h1 id="TradeSettlementHeaderMonetarySummation">TradeSettlementHeaderMonetarySummation</h1>

Type: rdf:Class

Description: A collection of monetary amount totals, specified at header level, for a trade settlement.

Properties: 

name | type | description
-|-|-
TradeSettlementHeaderMonetarySummationGrandTotalAmount | xsd:decimal | A monetary value of the grand total of this trade settlement header monetary summation, to include addition and subtraction of individual summation amounts.
TradeSettlementHeaderMonetarySummationGrossLineTotalAmount | xsd:decimal | A monetary value of the total of all line amounts, excluding line level allowances and charges and taxes, being reported in this trade settlement header monetary summation.
InsuranceChargeTotalAmount | xsd:decimal | A monetary value of the total of all insurance charges being reported in this trade settlement header monetary summation.
TradeSettlementHeaderMonetarySummationPaymentTotalAmount | xsd:decimal | A monetary value of a payment total reported in this header trade settlement payment monetary summation.
TradeSettlementHeaderMonetarySummationTotalRetailValueInformationAmount | xsd:decimal | A monetary value which constitutes the total retail value stated for information purposes in this trade settlement header monetary summation.
RoundingAmount | xsd:decimal | A monetary value of a rounding amount being applied in this trade settlement header monetary summation.
TradeSettlementHeaderMonetarySummationNetLineTotalAmount | xsd:decimal | A monetary value of the total of all line amounts, including line level allowances and charges and excluding line level taxes, being reported in this trade settlement header monetary summation.
ProductValueExcludingTobaccoTaxInformationAmount | xsd:decimal | A monetary value which constitutes the total product value, excluding tobacco tax, stated for information purposes in this trade settlement header monetary summation.
RetailValueExcludingTaxInformationAmount | xsd:decimal | A monetary value which constitutes the retail value, excluding all duties and taxes, stated for information purposes in this trade settlement header monetary summation.
TotalDiscountAmount | xsd:decimal | A monetary value of a total discount reported in this trade settlement header monetary summation.
HeaderBalanceOut | [edi3:HeaderBalanceOut](#HeaderBalanceOut) | A header balance out applicable to this trade settlement header monetary summation.
TradeSettlementHeaderMonetarySummationBalanceOutAmount | xsd:decimal | A monetary value that is an amount balanced out for this trade settlement header monetary summation.
TradeSettlementHeaderMonetarySummationChargeTotalAmount | xsd:decimal | A monetary value of the total of all charge amounts being reported in this trade settlement header monetary summation.
TradeSettlementHeaderMonetarySummationTotalAllowanceChargeAmount | xsd:decimal | A monetary value of a total allowance and charge reported in this trade settlement header monetary summation.
TradeSettlementHeaderMonetarySummationTaxBasisTotalAmount | xsd:decimal | A monetary value of the total of all tax basis amounts being reported in this trade settlement monetary summation.
TradeSettlementHeaderMonetarySummationDuePayableAmount | xsd:decimal | A monetary value that is an amount due and payable for this trade settlement header monetary summation, such as the amount due to the creditor.
TradeSettlementHeaderMonetarySummationAllowanceTotalAmount | xsd:decimal | A monetary value of the total of all allowance amounts being reported in this trade settlement header monetary summation.
TotalPrepaidAmount | xsd:decimal | A monetary value of a prepaid total reported in this trade settlement header monetary summation.
LineTotalAmountExcludingTaxes | xsd:decimal | A monetary value of the total of all line amounts, excluding all duties and taxes, being reported in this trade settlement header monetary summation.
TradeSettlementHeaderMonetarySummationTaxTotalAmount | xsd:decimal | A monetary value of the total of all tax amounts being reported in this trade settlement header monetary summation.
TradeSettlementHeaderMonetarySummationLineTotalAmountIncludingTaxes | xsd:decimal | A monetary value of the total of all line amounts, including all duties and taxes, being reported in this trade settlement header monetary summation.
TradeSettlementHeaderMonetarySummationLineTotalAmount | xsd:decimal | A monetary value of the line amount total being reported in this trade settlement header monetary summation.
TradeSettlementHeaderMonetarySummationAdjustedBalanceOutAmount | xsd:decimal | A monetary value that is an adjusted amount balanced out for this trade settlement header monetary summation.
TotalDiscountBasisAmount | xsd:decimal | A monetary value of a total discount basis reported in this trade settlement header monetary summation.
GrandTotalSpecifiedFinancialAdjustment | [edi3:FinancialAdjustment](#FinancialAdjustment) | The financial adjustment of the grand total specified for this trade settlement header monetary summation.
TradeSettlementHeaderMonetarySummationNetIncludingTaxesLineTotalAmount | xsd:decimal | A monetary value of the total of all line amounts, including line level allowances and charges and including line level taxes, being reported in this trade settlement header monetary summation.
TotalDepositFeeInformationAmount | xsd:decimal | A monetary value of the total deposit fee stated for information purposes in this trade settlement header monetary summation.


<h1 id="PaymentDiscountTerms">PaymentDiscountTerms</h1>

Type: rdf:Class

Description: Trade terms and conditions by which a discount is or can be applied to a payable amount.

Properties: 

name | type | description
-|-|-
PaymentDiscountTermsBasisPeriodMeasure | xsd:decimal | The measure of the basis period for these trade payment discount terms.
PaymentDiscountTermsBasisAmount | xsd:decimal | A monetary value used as a basis to calculate the discount in these trade payment discount terms.
PaymentDiscountTermsCalculationPercent | xsd:decimal | The percent used to calculate the discount in these trade payment discount terms.
PaymentDiscountTermsBasisDateTime | xsd:dateTime | The date, time, date time, or other date time value used as the basis to calculate the discount in the trade payment discount terms.


<h1 id="FinancialCard">FinancialCard</h1>

Type: rdf:Class

Description: A card used to represent a financial account for a trade settlement.

Properties: 

name | type | description
-|-|-
FinancialCardTypeCode | xsd:token | The code specifying the type of this trade settlement financial card, such as debit or credit.
FinancialCardDescription | xsd:string | The textual description of this trade settlement financial card.
FinancialCardID | xsd:token | The unique identifier, commonly known as the card number, of this trade settlement financial card.
CardholderName | xsd:string | The cardholder name as it appears on this trade settlement financial card. This may include both an individual authorized to use the card as well as the organization that owns the card.
MicrochipIndicator | xsd:boolean | The indication of whether or not this trade settlement financial card has a microchip.
VerificationNumber | xsd:decimal | The unique card verification number for security purposes to help verify the card user is in actual possession of this trade settlement financial card.
CreditLimitAmount | xsd:decimal | A monetary value of the credit limit for this trade settlement financial card.
ExpiryDate | xsd:date | The date of expiry up to which this trade settlement financial card is valid.
IssuingCompanyName | xsd:string | The issuing company name, expressed as text, for this trade settlement financial card.
ValidFromDate | xsd:dateTime | The date from which this trade settlement financial card is valid.
InterestRate | xsd:decimal | The interest rate expressed as a percentage for this trade settlement financial card.


<h1 id="TradeParty">TradeParty</h1>

Type: rdf:Class

Description: An individual, a group, or a body having a role in a trade business function.

Properties: 

name | type | description
-|-|-
TradePartyRoleText | xsd:string | A role, expressed as text, for this trade party.
TradePartyDescription | xsd:string | A textual description of this trade party.
TradePartyGlobalID | xsd:token | A globally unique identifier of this trade party.
LogoBinaryFile | [edi3:BinaryFile](#BinaryFile) | A file containing a specified binary representation of a logo associated with this trade party.
TradePartyLanguageCode | xsd:token | A code specifying a language for this trade party.
TradePartyTransportService | [edi3:Service](#Service) | A transport service provided by this trade party.
TradePartyName | xsd:string | The name, expressed as text, for this trade party.
DUNSID | xsd:token | The unique nine-digit Data Universal Numbering System (DUNS) identifier for this trade party.
OwnedCreditorFinancialAccount | [edi3:CreditorFinancialAccount](#CreditorFinancialAccount) | The creditor financial account owned by this trade party.
TradePartyTypeCode | xsd:token | A code specifying the type of trade party that is independent of its role.
RegisteredID | xsd:token | A registered identifier of this trade party.
TradePartyRoleCode | xsd:token | A code specifying the role of this trade party.
GovernmentRegistration | [edi3:GovernmentRegistration](#GovernmentRegistration) | A governmental registration specified for this trade party.
TradePartyPostalAddress | [edi3:TradeAddress](#TradeAddress) | The postal address for this trade party.
LegalOrganization | [edi3:Organization](#Organization) | The legally constituted organization specified for this trade party.
TradePartyID | xsd:token | A unique identifier of this trade party.
GLNID | xsd:token | A Global Location Number (GLN) identifier for this trade party.
TaxRegistration | [edi3:TaxRegistration](#TaxRegistration) | A tax registration specified for this trade party.
DefinedContactDetails | [edi3:Contact](#Contact) | A trade contact defined for this trade party.
TradePartyLogisticsServiceCharge | [edi3:ServiceCharge](#ServiceCharge) | A logistics service charge applicable to this trade party.
SpecifiedFinancialIdentity | [edi3:FinancialIdentity](#FinancialIdentity) | The financial identity specified for this trade party.
TradePartyAssociatedParty | [edi3:TradeParty](#TradeParty) | A party associated with this trade party, such as a local agent of a shipping line.
AuthoritativeSignatoryPerson | [edi3:AuthoritativeSignatoryPerson](#AuthoritativeSignatoryPerson) | A person specified to sign on behalf of this trade party.
TradePartyLogisticsLocation | [edi3:LogisticsLocation](#LogisticsLocation) | A logistics related location or place specified for this trade party.
TradePartyTelephone | [edi3:UniversalCommunication](#UniversalCommunication) | A telephone communication for this trade party.
SpecifiedContactPerson | [edi3:ContactPerson](#ContactPerson) | A contact person specified for this trade party.
TradePartyURI | [edi3:UniversalCommunication](#UniversalCommunication) | A Uniform Resource Identifier (URI) communication for this trade party, such as a web or email address.
TradePartySpecifiedProprietaryIdentity | [edi3:ProprietaryIdentity](#ProprietaryIdentity) | A proprietary identity specified for this trade party.
QualityAssuranceIndicator | xsd:boolean | The indication of whether or not this trade party is quality assured.
TradePartyLogisticsRiskAnalysisResult | [edi3:RiskAnalysisResult](#RiskAnalysisResult) | A result of a logistics risk analysis calculation specified for this trade party.


<h1 id="LocationParty">LocationParty</h1>

Type: rdf:Class

Description: An individual, a group, or a body having a role related to a location.

Properties: 

name | type | description
-|-|-
LocationPartyCountryCode | xsd:token | A unique country identifier for this location party.
LocationPartyTelephone | [edi3:UniversalCommunication](#UniversalCommunication) | Telephone communication information for this location party.
LocationPartyPostalAddress | [edi3:TradeAddress](#TradeAddress) | A postal address for this location party.
LocationPartyName | xsd:string | A name, expressed as text, for this location party.
TransportPerson | [edi3:TransportPerson](#TransportPerson) | A transport related person specified for this location party.
LocationPartyFax | [edi3:UniversalCommunication](#UniversalCommunication) | Fax communication information for this location party.
ProvidedTransportService | [edi3:Service](#Service) | A transport service provided by this location party.
DefinedContact | [edi3:Contact](#Contact) | A trade contact defined for this location party.
LocationPartyRoleCode | xsd:token | A code specifying a role of this location party.
LocationPartyURI | [edi3:UniversalCommunication](#UniversalCommunication) | Uniform Resource Identifier (URI) communication information for this location party, such as a web or email address.


<h1 id="RequestingParty">RequestingParty</h1>

Type: rdf:Class

Description: An individual, a group, or a body having a role as a requestor.

Properties: 

name | type | description
-|-|-
SpecifiedLineOfCreditFinancingFinancialAccount | [edi3:FinancingFinancialAccount](#FinancingFinancialAccount) | The financing financial account, used for managing the line of credit, specified for this requesting party.
RequestingPartyTypeCode | xsd:token | The code specifying the type of requesting party.
SpecifiedProjectPerson | [edi3:ProjectPerson](#ProjectPerson) | The project person specified for this requesting party.
ProjectOrganization | [edi3:ProjectOrganization](#ProjectOrganization) | The project organization, such as a business or government body, for this requesting party.
RequestingPartyDescription | xsd:string | The textual description of this requesting party.
RequestingPartyLanguageCode | xsd:token | A code specifying a language for this requesting party.
AccessRightsCode | xsd:token | The code specifying the access rights, such as unlimited, restricted, prohibited, for this requesting party.
RequestingPartySpecifiedProprietaryIdentity | [edi3:ProprietaryIdentity](#ProprietaryIdentity) | A proprietary identity specified for this requesting party.
RequestingPartyID | xsd:token | The unique identifier for this requesting party.
RequestingPartySpecifiedCreditorFinancialAccount | [edi3:CreditorFinancialAccount](#CreditorFinancialAccount) | The creditor financial account, used for crediting, specified for this requesting party.
RequestingPartyName | xsd:string | The name, expressed as text, for this requesting party.


<h1 id="MaterialComponent">MaterialComponent</h1>

Type: rdf:Class

Description: An unused and rejected as unwanted component of transport material.

Properties: 

name | type | description
-|-|-
MaterialComponentTypeCode | xsd:token | A code specifying a type of transport waste material component.
RetainedMeasure | xsd:decimal | The measure for this retained transport waste material component.
GeneratedMeasure | xsd:decimal | The estimated measure for this generated transport waste material component.
DischargedMeasure | xsd:decimal | The planned measure for this discharged transport waste material component.
MaterialComponentDescription | xsd:string | A textual description for this transport waste material component.
RemainingDeliveryEvent | [edi3:Event](#Event) | A delivery event for this remaining transport waste material component.


<h1 id="CreditorFinancialInstitution">CreditorFinancialInstitution</h1>

Type: rdf:Class

Description: A bank, building society, credit union, stock brokerage, or similar business of the party that receives money.

Properties: 

name | type | description
-|-|-
CreditorFinancialInstitutionFedwireRoutingNumberID | xsd:token | The unique Fedwire Routing Number identifier as assigned by the American Bankers Association (ABA) for this creditor financial institution.
CreditorFinancialInstitutionSICID | xsd:token | The unique Swiss Interbank Clearing (SIC) Code identifier for this creditor financial institution.
CreditorFinancialInstitutionJapanFinancialInstitutionCommonID | xsd:token | The Japan Financial Institution Common identifier as assigned by the Japanese Bankers Association for this creditor financial institution.
CreditorFinancialInstitutionClearingSystemName | xsd:string | The clearing system name, expressed as text, for this creditor financial institution.
CreditorFinancialInstitutionPortugueseNCCID | xsd:token | The unique Portuguese National Clearing Code (NCC) identifier for this creditor financial institution.
CreditorFinancialInstitutionBICID | xsd:token | The unique Bank Identification Code (BIC) as defined in ISO 9362 for this creditor financial institution.
CreditorFinancialInstitutionHongKongBankID | xsd:token | The unique Hong Kong Bank Code identifier for this creditor financial institution.
CreditorFinancialInstitutionSpanishDomesticInterbankingID | xsd:token | The unique Spanish Domestic Interbanking Code identifier as assigned by the Centro de Cooperacion Interbancaria (CCI) for this creditor financial institution.
CreditorFinancialInstitutionName | xsd:string | The name, expressed as text, for this creditor financial institution.
CreditorFinancialInstitutionAustralianBSBID | xsd:token | The unique Australian Bank State Branch (BSB) Code identifier as assigned by the Australian Payments Clearing Association (APCA) for this creditor financial institution.
AdditionalClearingSystemID | xsd:token | An additional clearing system identifier for this creditor financial institution.
CreditorFinancialInstitutionCHIPSParticipantID | xsd:token | The unique (United States) Clearing House Interbank Payment System (CHIPS) Participant Identifier (ID) as assigned by the New York Clearing House for this creditor financial institution.
CreditorFinancialInstitutionGermanBankleitzahlID | xsd:token | The unique German Bankleitzahl identifier for this creditor financial institution.
CreditorFinancialInstitutionSwissBCID | xsd:token | The unique Swiss Bank Code (BC) identifier for this creditor financial institution.
CreditorFinancialInstitutionItalianDomesticID | xsd:token | The unique Italian Domestic Identification Code identifier as assigned by the Associazione Bancaria Italiana (ABI) for this creditor financial institution.
CreditorFinancialInstitutionIndianFinancialSystemID | xsd:token | The unique Indian Financial System Code identifier for this creditor financial institution.
CreditorFinancialInstitutionSpecifiedProprietaryIdentity | [edi3:ProprietaryIdentity](#ProprietaryIdentity) | A proprietary identity specified for this creditor financial institution.
CreditorFinancialInstitutionBranch | [edi3:BranchFinancialInstitution](#BranchFinancialInstitution) | The branch financial institution for this creditor financial institution.
AustralianSNID | xsd:token | The Australian Small Network (SN) identifier as assigned by the Australian Payments Clearing Association (APCA) for this creditor financial institution.
CreditorFinancialInstitutionRussianCentralBankID | xsd:token | The unique Russian Central Bank Identification Code identifier for this creditor financial institution.
CreditorFinancialInstitutionAustrianBankleitzahlID | xsd:token | The unique Austrian Bankleitzahl identifier for this creditor financial institution.
CreditorFinancialInstitutionUKSortCodeID | xsd:token | The unique United Kingdom (UK) Sort Code identifier as assigned by the UK Payment Association (APACS) for this creditor financial institution.
CreditorFinancialInstitutionCanadianPaymentsAssociationID | xsd:token | The unique Canadian Payments Association Routing Number identifier for this creditor financial institution.
CreditorFinancialInstitutionPolishNationalClearingID | xsd:token | The unique Polish National Clearing Code identifier for this creditor financial institution.
CreditorFinancialInstitutionCHIPSUniversalID | xsd:token | The unique (United States) Clearing House Interbank Payments System (CHIPS) Universal Identification (UID) as assigned by the New York Clearing House for this creditor financial institution.
CreditorFinancialInstitutionNewZealandNCCID | xsd:token | The unique New Zealand National Clearing Code (NCC) identifier as assigned by the New Zealand Bankers' Association (NZBA) for this creditor financial institution.
CreditorFinancialInstitutionHellenicBankID | xsd:token | The unique Hellenic Bank Identification Code identifier for this creditor financial institution.
CreditorFinancialInstitutionAddress | [edi3:FinancialInstitutionAddress](#FinancialInstitutionAddress) | The location address for this creditor financial institution.
CreditorFinancialInstitutionIrishNSCID | xsd:token | The unique Irish National Sorting Code (NSC) identifier as assigned by the Irish Payments Services Organisation (IPSO) for this creditor financial institution.


<h1 id="BranchFinancialInstitution">BranchFinancialInstitution</h1>

Type: rdf:Class

Description: A sub-division of a bank, building society, credit union, stock brokerage, or similar business; established primarily to provide financial services and financial transactions.

Properties: 

name | type | description
-|-|-
SortCode | xsd:token | The unique identifier for this branch of a financial institution.
BranchFinancialInstitutionName | xsd:string | The name, expressed as text, for this branch of a financial institution.


<h1 id="DebtorFinancialInstitution">DebtorFinancialInstitution</h1>

Type: rdf:Class

Description: A bank, building society, credit union, stock brokerage, or similar business of the party that owes money.

Properties: 

name | type | description
-|-|-
DebtorFinancialInstitutionBICID | xsd:token | The unique Bank Identification Code (BIC) as defined in ISO 9362 for this debtor financial institution.
DebtorFinancialInstitutionRussianCentralBankID | xsd:token | The unique Russian Central Bank Identification Code identifier for this debtor financial institution.
DebtorFinancialInstitutionSouthAfricanNCCID | xsd:token | The unique South African National Clearing Code (NCC) identifier as assigned by the South African Bankers Services Company Ltd. (BankServ) for this debtor financial institution.
DebtorFinancialInstitutionHellenicBankID | xsd:token | The unique Hellenic Bank Identification Code identifier for this debtor financial institution.
DebtorFinancialInstitutionBranch | [edi3:BranchFinancialInstitution](#BranchFinancialInstitution) | The branch financial institution for this debtor financial institution.
DebtorFinancialInstitutionJapanFinancialInstitutionCommonID | xsd:token | The Japan Financial Institution Common identifier as assigned by the Japanese Bankers Association for this debtor financial institution.
DebtorFinancialInstitutionIrishNSCID | xsd:token | The unique Irish National Sorting Code (NSC) identifier as assigned by the Irish Payments Services Organisation (IPSO) for this debtor financial institution.
DebtorFinancialInstitutionGermanBankleitzahlID | xsd:token | The unique German Bankleitzahl identifier for this debtor financial institution.
DebtorFinancialInstitutionFedwireRoutingNumberID | xsd:token | The unique Fedwire Routing Number identifier as assigned by the American Bankers Association (ABA) for this debtor financial institution.
DebtorFinancialInstitutionClearingSystemName | xsd:string | The clearing system name, expressed as text, for this debtor financial institution.
DebtorFinancialInstitutionPortugueseNCCID | xsd:token | The unique Portuguese National Clearing Code (NCC) identifier for this debtor financial institution.
DebtorFinancialInstitutionAustralianBSBID | xsd:token | The unique Australian Bank State Branch (BSB) Code identifier as assigned by the Australian Payments Clearing Association (APCA) for this debtor financial institution.
DebtorFinancialInstitutionAddress | [edi3:FinancialInstitutionAddress](#FinancialInstitutionAddress) | The location address for this debtor financial institution.
DebtorFinancialInstitutionSpanishDomesticInterbankingID | xsd:token | The unique Spanish Domestic Interbanking Code identifier as assigned by the Centro de Cooperacion Interbancaria (CCI) for this debtor financial institution.
DebtorFinancialInstitutionSwissBCID | xsd:token | The unique Swiss Bank Code (BC) identifier for this debtor financial institution.
DebtorFinancialInstitutionIndianFinancialSystemID | xsd:token | The unique Indian Financial System Code identifier for this debtor financial institution.
DebtorFinancialInstitutionNewZealandNCCID | xsd:token | The unique New Zealand National Clearing Code (NCC) identifier as assigned by the New Zealand Bankers' Association (NZBA) for this debtor financial institution.
DebtorFinancialInstitutionUKSortCodeID | xsd:token | The unique United Kingdom (UK) Sort Code identifier as assigned by the UK Payment Association (APACS) for this debtor financial institution.
DebtorFinancialInstitutionCHIPSParticipantID | xsd:token | The unique (United States) Clearing House Interbank Payment System (CHIPS) Participant Identifier (ID) as assigned by the New York Clearing House for this debtor financial institution.
DebtorFinancialInstitutionCHIPSUniversalID | xsd:token | The unique (United States) Clearing House Interbank Payments System (CHIPS) Universal Identification (UID) as assigned by the New York Clearing House for this debtor financial institution.
DebtorFinancialInstitutionPolishNationalClearingID | xsd:token | The unique Polish National Clearing Code identifier for this debtor financial institution.
DebtorFinancialInstitutionCanadianPaymentsAssociationID | xsd:token | The unique Canadian Payments Association Routing Number identifier for this debtor financial institution.
DebtorFinancialInstitutionName | xsd:string | The name, expressed as text, for this debtor financial institution.
DebtorFinancialInstitutionAustrianBankleitzahlID | xsd:token | The unique Austrian Bankleitzahl identifier for this debtor financial institution.
DebtorFinancialInstitutionHongKongBankID | xsd:token | The unique Hong Kong Bank Code identifier for this debtor financial institution.
DebtorFinancialInstitutionItalianDomesticID | xsd:token | The unique Italian Domestic Identification Code identifier as assigned by the Associazione Bancaria Italiana (ABI) for this debtor financial institution.


<h1 id="ComplexDescription">ComplexDescription</h1>

Type: rdf:Class

Description: An aggregation of descriptive information consisting of different but related characteristics that together constitute a work item complex description.

Properties: 

name | type | description
-|-|-
RespondingSpecificationAnswer | [edi3:Response](#Response) | A responding specification response for this work item complex description.
ComplexDescriptionContentText | xsd:string | Content, expressed as text, for this work item complex description.
RequestingSpecificationQuery | [edi3:Query](#Query) | A requesting specification query for this work item complex description.
Abstract | xsd:string | A textual abstract of the content of the work item complex description.
ComplexDescriptionContractualLanguageCode | xsd:token | The code specifying the contractual language for this work item complex description.


<h1 id="GeopoliticalRegion">GeopoliticalRegion</h1>

Type: rdf:Class

Description: A collection of countries and/or economies united for trade purposes.

Properties: 

name | type | description
-|-|-
GeopoliticalRegionName | xsd:string | The name, expressed as text, of this trade geopolitical region.
IncludedCountry | [edi3:Country](#Country) | A country included in this trade geopolitical region.
GeopoliticalRegionTypeCode | xsd:token | The code specifying the type of trade geopolitical region.


<h1 id="GeographicalMultiSurface">GeographicalMultiSurface</h1>

Type: rdf:Class

Description: A collection of surfaces on the Earth (reference ISO 19136).

Properties: 

name | type | description
-|-|-
GeographicalMultiSurfacePolygon | [edi3:Polygon](#Polygon) | A polygon included in this geographical multi-surface.


<h1 id="EmailCommunication">EmailCommunication</h1>

Type: rdf:Class

Description: An address for the delivery of electronic mail.

Properties: 

name | type | description
-|-|-


<h1 id="TelecommunicationCommunication">TelecommunicationCommunication</h1>

Type: rdf:Class

Description: Information necessary to establish an electronic telecommunication connection for the purpose of a telephone or facsimile exchange.

Properties: 

name | type | description
-|-|-
SpecialDeviceTypeText | xsd:string | The special device type, expressed as text, for this telecommunication communication, such as a device for the hearing impaired.
CountryNumberCode | xsd:token | The country access code for this telecommunication number.
UseCode | xsd:token | The code specifying the use of this telecommunication such as for business purposes or private.
UsagePreference | [edi3:SpecifiedPreference](#SpecifiedPreference) | The specified preference for the usage of this telecommunication method.
LocalNumber | xsd:string | The communication number, expressed as text and not including country access code or the area number code, for this telecommunication.
ExtensionNumber | xsd:string | The extension number, expressed as text, assigned to this telecommunication number.
InternalAccessText | xsd:string | Access information, expressed as text, for the internal access telecommunication number, such as the United States Defense Network Service number.
AreaNumberCode | xsd:token | The code specifying the area number for this telecommunication.


<h1 id="UniversalCommunication">UniversalCommunication</h1>

Type: rdf:Class

Description: The exchange of thoughts, messages, or information, as universally exchanged by speech, signals, writing, or behaviour between persons and/or organizations.

Properties: 

name | type | description
-|-|-
UniversalCommunicationCompleteNumber | xsd:string | The text string of characters that make up the complete number for this universal communication.
ChannelCode | xsd:token | The code specifying the channel or manner in which a universal communication can be made, such as telephone or email.


<h1 id="Context">Context</h1>

Type: rdf:Class

Description: The scenario or setting of an exchanged document, such as its business process application context.

Properties: 

name | type | description
-|-|-
BIM | [edi3:DocumentContextParameter](#DocumentContextParameter) | A Business Information Master (BIM) context parameter specified for this exchanged document context.
MessageStandard | [edi3:DocumentContextParameter](#DocumentContextParameter) | The message standard document context parameter specified for this exchanged document context.
Scenario | [edi3:DocumentContextParameter](#DocumentContextParameter) | A scenario context parameter specified for this exchanged document context.
BusinessProcess | [edi3:DocumentContextParameter](#DocumentContextParameter) | A business process context parameter specified for this exchanged document context.
Subset | [edi3:DocumentContextParameter](#DocumentContextParameter) | A subset context parameter specified for this exchanged document context.
TransactionID | xsd:token | The identifier of a specified transaction in this exchanged document context.
Guideline | [edi3:DocumentContextParameter](#DocumentContextParameter) | A guideline context parameter specified for this exchanged document context.
UserSpecifiedParameter | [edi3:DocumentContextParameter](#DocumentContextParameter) | A user specified document context parameter specified for this exchanged document context.
TransactionProcessingDateTime | xsd:dateTime | The date, time, date time, or other date time value of the processing of a transaction for this exchanged document context.
Application | [edi3:DocumentContextParameter](#DocumentContextParameter) | An application context parameter specified for this exchanged document context.


<h1 id="CustomsValuation">CustomsValuation</h1>

Type: rdf:Class

Description: A cross-border trade related assessment of the worth of an object, such as its monetary value, for customs purposes.

Properties: 

name | type | description
-|-|-
BuyerSellerRelationshipIndicator | xsd:boolean | The indication of whether or not there is a relationship between the buyer and the seller, such as a financial relationship, for this cross-border customs valuation.
ChargeApportionMethodCode | xsd:token | The code specifying the method of the apportion of charges for this cross-border customs valuation.
SalePriceConditionIndicator | xsd:boolean | The indication of whether or not there is a condition imposed on the sale price of the goods for this cross-border customs valuation.
AddedAdjustmentAmount | xsd:decimal | The monetary value of the adjustment added for this cross-border customs valuation.
CustomsValuationApplicableCurrencyExchange | [edi3:CurrencyExchange](#CurrencyExchange) | The trade related currency exchange applicable to this cross-border customs valuation.
CustomsValuationMethodCode | xsd:token | The code specifying the method by which this cross-border customs valuation is determined.
OtherChargeAmount | xsd:decimal | A monetary value added or subtracted from the total invoice price not previously taken into account for this cross-border customs valuation.
AddedAdjustmentPercent | xsd:decimal | The adjustment added, expressed as a percentage, for this cross-border customs valuation.
RoyaltyLicenceFeeIndicator | xsd:boolean | The indication of whether or not there is a royalty or licence fee related to the goods for this cross-border customs valuation.
WTOAdditionCode | xsd:token | The code specifying any additions necessary under the World Trade Organization (WTO) Valuation Agreement used for the assessment of this cross-border customs valuation.
CustomsValuationTypeCode | xsd:token | The code specifying the type of cross-border customs valuation.
SaleRestrictionText | xsd:string | A restriction, expressed as text, imposed on the sale of the goods for this cross-border customs valuation.
SaleRestrictionIndicator | xsd:boolean | The indication of whether or not there is any restriction imposed on the sale of the goods for this cross-border customs valuation.
BuyerSellerRelationshipPriceInfluenceIndicator | xsd:boolean | The indication of whether or not the buyer seller relationship influences the price of the goods for this cross-border customs valuation.
DeductedAdjustmentPercent | xsd:decimal | The adjustment deducted, expressed as a percentage, for this cross-border customs valuation.


<h1 id="DeliveryTerms">DeliveryTerms</h1>

Type: rdf:Class

Description: Conditions agreed upon between the parties with regard to the delivery of goods and or services for trade purposes.

Properties: 

name | type | description
-|-|-
FunctionCode | xsd:token | A code specifying a function of these trade delivery terms.
RelevantLocation | [edi3:TradeLocation](#TradeLocation) | The trade location relevant for these trade delivery terms.
DeliveryTermsDescription | xsd:string | A textual description of these trade delivery terms.
DeliveryTermsPartialDeliveryAllowedIndicator | xsd:boolean | The indication of whether or not these trade delivery terms allow a partial delivery.
DeliveryDiscontinuationCode | xsd:token | The code specifying the delivery discontinuation for this trade delivery terms.


<h1 id="Keyword">Keyword</h1>

Type: rdf:Class

Description: A significant word, part of word or phrase that is used to enable indexing of or searching within a textual repository, such as a product catalogue or library.

Properties: 

name | type | description
-|-|-


<h1 id="SpatialDimension">SpatialDimension</h1>

Type: rdf:Class

Description: A measure of spatial extent of an object, such as the length, breadth or height of a shipping container.

Properties: 

name | type | description
-|-|-
SpatialDimensionValueMeasure | xsd:decimal | The measure of the value of this spatial dimension.
Width | xsd:decimal | The measure of the width component of this spatial dimension.
SpatialDimensionID | xsd:token | The unique identifier of this spatial dimension.
SpatialDimensionTypeCode | xsd:token | The code specifying the type of spatial dimension, such as thickness, area, or volume.
SpatialDimensionDescription | xsd:string | A textual description of this spatial dimension.
Diameter | xsd:decimal | The measure of the diameter component for this spatial dimension.
Height | xsd:decimal | The measure of the height component of this spatial dimension.


<h1 id="WorkItemDimension">WorkItemDimension</h1>

Type: rdf:Class

Description: A measure of spatial extent associated with this work item, such as length, breadth, or height.

Properties: 

name | type | description
-|-|-
WorkItemDimensionTypeCode | xsd:token | The code specifying the type of this work item dimension.
ComponentDimension | [edi3:WorkItemDimension](#WorkItemDimension) | A work item component dimension for this work item dimension.
Measure | xsd:decimal | The measured value for this work item dimension.
WorkItemDimensionContractualLanguageCode | xsd:token | The code specifying the contractual language for this work item dimension.
WorkItemDimensionDescription | xsd:string | The textual description of this work item dimension.


<h1 id="CurrencyExchange">CurrencyExchange</h1>

Type: rdf:Class

Description: The conversion of one currency to another for trade purposes.

Properties: 

name | type | description
-|-|-
MarketID | xsd:token | The unique identifier of the currency exchange market from which the exchange rate is taken for trade purposes.
SourceCurrencyCode | xsd:token | The code specifying the source currency of a trade related currency conversion.
TargetCurrencyCode | xsd:token | The code specifying the target currency of a trade related currency conversion.
SourceUnitBasis | xsd:decimal | The numeric unit basis of the source currency used in this trade related currency exchange rate calculation.
ConversionRate | xsd:decimal | The rate factor used for conversion from the source currency to the target currency for trade purposes.
CurrencyExchangeAssociatedDocument | [edi3:Document](#Document) | An associated document referenced for this trade related currency exchange.
TargetUnitBasis | xsd:decimal | The numeric unit basis of the target currency used in this trade related currency exchange rate calculation.


<h1 id="BinaryFile">BinaryFile</h1>

Type: rdf:Class

Description: A specified computer file or program stored in a binary format.

Properties: 

name | type | description
-|-|-
AuthorName | xsd:string | A name of an author, expressed as text, of this specified binary file.
Size | xsd:decimal | The measure of the size of this specified binary file.
BinaryFileID | xsd:token | A unique identifier for this specified binary file.
BinaryFileURI | xsd:token | The unique Uniform Resource Identifier (URI) for this specified binary file.
EncodingCode | xsd:token | The code specifying the encoding of this specified binary file.
BinaryFileDescription | xsd:string | A textual description of this specified binary file.
Title | xsd:string | A title, expressed as text, for this specified binary file.
AccessText | xsd:string | Access information, expressed as text, for this specified binary file, such as security and download parameters.
BinaryFileVersionID | xsd:token | The unique version identifier for this specified binary file.
BinaryFileName | xsd:string | The file name, expressed as text, of this specified binary file.
CharacterSetCode | xsd:token | The code specifying the character set for this specified binary file.
AccessAvailabilityPeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The specified period when access to this binary file is available.
MIMECode | xsd:token | The code specifying the Multipurpose Internet Mail Extensions (MIME) type for this specified binary file.


<h1 id="Section">Section</h1>

Type: rdf:Class

Description: The parts into which a label is or may be divided.

Properties: 

name | type | description
-|-|-
SectionID | xsd:token | The identifier of this label section.
IncludedSegment | [edi3:Segment](#Segment) | A segment included in this label section.


<h1 id="GeographicalPoint">GeographicalPoint</h1>

Type: rdf:Class

Description: A point on the surface of the Earth (reference ISO 19136).

Properties: 

name | type | description
-|-|-
GeographicalPointGeographicalObjectCharacteristic | [edi3:GeographicalObjectCharacteristic](#GeographicalObjectCharacteristic) | The geographical object characteristic associated with this geographical point.
GeographicalPointAssociatedLogisticsLocation | [edi3:LogisticsLocation](#LogisticsLocation) | A logistics location associated with this specified geographical point.


<h1 id="Marketplace">Marketplace</h1>

Type: rdf:Class

Description: An actual or virtual place where buyers and sellers interact, directly or through intermediaries, to trade goods or services.

Properties: 

name | type | description
-|-|-
Website | xsd:token | A website Uniform Resource Identifier (URI) for this specified marketplace.
SalesMethodCode | xsd:token | The code specifying a sales method, such as an auction clock or mediation, for this specified marketplace.
AvailableOrderingPeriod | [edi3:AvailablePeriod](#AvailablePeriod) | An available ordering period for this specified marketplace.
VirtualIndicator | xsd:boolean | The indication of whether or not this specified marketplace is virtual, such as a web-based marketplace.
MarketplaceID | xsd:token | The identifier for this specified marketplace.


<h1 id="Authentication">Authentication</h1>

Type: rdf:Class

Description: A proof that a document is genuine.

Properties: 

name | type | description
-|-|-
RepresentationTypeCode | xsd:token | The code specifying the type of representation of this document authentication, such as direct or indirect.
IncludedClause | [edi3:Clause](#Clause) | A document clause included in this document authentication.
ReferencedProvider | [edi3:ReferencedParty](#ReferencedParty) | The referenced party providing this document authentication.
SignatoryImageBinaryObject | xsd:base64Binary | The signatory image, expressed as a binary object, for this document authentication.
LocationProvider | [edi3:TradeParty](#TradeParty) | The trade party providing the location for this document authentication.
AuthenticationInformation | xsd:string | Information, expressed as text, for this document authentication.
AuthenticationCategoryCode | xsd:token | A code specifying a category for this document authentication.
GovernmentActionTypeCode | xsd:token | The code specifying the type of document authentication.
AuthenticationStatement | xsd:string | The statement, expressed as text, for this document authentication.
StatementCode | xsd:token | The code specifying the statement for this document authentication.
AuthenticationActualDateTime | xsd:dateTime | The actual date, time, date time, or other date time value of this document authentication.
AuthenticationID | xsd:token | A unique identifier for this document authentication.
SignatoryText | xsd:string | The signatory, expressed as text, for this document authentication.
AuthenticationIssueLocation | [edi3:LogisticsLocation](#LogisticsLocation) | The issue location for this document authentication.


<h1 id="Event">Event</h1>

Type: rdf:Class

Description: A significant occurrence or happening during transport.

Properties: 

name | type | description
-|-|-
RequestedService | [edi3:ReferencedService](#ReferencedService) | A requested service related to this transport event.
ScheduledOccurrencePeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The scheduled period of time specified for the occurrence of this transport event.
ConveyanceFacilityLocation | [edi3:LogisticsLocation](#LogisticsLocation) | A location of a conveyance facility related to this transport event.
ExpectedIndicator | xsd:boolean | The indication of whether or not this transport event is or was expected.
EventAssociatedGeographicalFeature | [edi3:GeographicalFeature](#GeographicalFeature) | A geographical feature associated with this transport event.
EventPreviousAssociatedGeographicalFeature | [edi3:GeographicalFeature](#GeographicalFeature) | A geographical feature previously associated with this transport event.
DelayPeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | A specified period of time during which this transport event is delayed.
EventScheduledArrivalDateTime | xsd:dateTime | The date, time, date time or other date time value of the scheduled arrival related to this transport event.
RequestedOccurrenceDateTime | xsd:dateTime | The requested date, time, date time, or other date time value of the occurrence of this transport event.
CertifyingParty | [edi3:TradeParty](#TradeParty) | A certifying party for this transport event.
TransportMeansStayPeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The specified period during which the transport means is held at a location.
EventID | xsd:token | The unique identifier for this transport event.
EventApplicableNote | [edi3:Note](#Note) | A note providing information applicable to this transport event.
ActualDepartureDateTime | xsd:dateTime | The date, time, date time or other date time value of the actual departure related to this transport event.
EventTypeCode | xsd:token | The code specifying the type of transport event.
AdditionalSecurityMeasures | [edi3:Note](#Note) | A note providing additional security measures applicable to this transport event.
ArrivalDateTime | xsd:dateTime | An arrival date, time, date time, or other date time value related to this transport event.
EventUnitQuantity | xsd:decimal | The number of units for this transport event.
EstimatedTransportMeansArrivalOccurrenceDateTime | xsd:dateTime | The date, time, date time, or other date time value when the arrival of a means of transport at the location of this transport event is estimated to occur.
ActualOccurrenceDateTime | xsd:dateTime | The actual date, time, date time, or other date time value of the occurrence of this transport event.
LaycanPeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The specified period of laycan time during which this transport event occurs.
ScheduledOccurrenceDateTime | xsd:dateTime | The scheduled date, time, date time, or other date time value of the occurrence of this transport event.
ActualOccurrencePeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The actual period of time during which this transport event occurred.
ActualArrivalDateTime | xsd:dateTime | The date, time, date time or other date time value of the actual arrival related to this transport event.
EventScheduledDepartureDateTime | xsd:dateTime | The date, time, date time or other date time value of the scheduled departure related to this transport event.
ReportedConditionTypeCode | xsd:token | The code specifying the type of reported condition for this transport event.
EventSecurityLevelCode | xsd:token | A security level code for this transport event.
EventSpecifiedInstructions | [edi3:TransportInstructions](#TransportInstructions) | An instruction or a set of instructions specified for this transport event.
StayEvent | [edi3:ReferencedEvent](#ReferencedEvent) | A stay specified for this referenced transport event.
RelatedObservation | [edi3:Observation](#Observation) | An observation related to this transport event.
OccurrenceLocation | [edi3:LogisticsLocation](#LogisticsLocation) | The logistics location where this transport event occurs.
ReportingMonitoringIOTDevice | [edi3:IOTDevice](#IOTDevice) | An IOT device for this transport reporting event.
ReceivedDateTime | xsd:dateTime | The date, time, date time, or other date time value when information related to this transport event was received, from the perspective of the receiver.
CargoFacilityLocation | [edi3:LogisticsLocation](#LogisticsLocation) | The location of a cargo facility related to this transport event.
EstimatedOccurrenceDateTime | xsd:dateTime | The estimated date, time, date time, or other date time value of the occurrence of this transport event.
DelayEvent | [edi3:ReferencedEvent](#ReferencedEvent) | A delay specified for this referenced transport event.
EventValueMeasure | xsd:decimal | The measure of a value for this transport event.
RelatedRoute | [edi3:Route](#Route) | The route related to this transport event.
DepartureDateTime | xsd:dateTime | A departure date, time, date time, or other date time value related to this transport event.
EventOccurrencePeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | A specified period of time during which this transport event occurs.


<h1 id="CommunicationEvent">CommunicationEvent</h1>

Type: rdf:Class

Description: A significant occurrence or happening communicated by means of sending or receiving information, such as transmitting digital data by using the internet.

Properties: 

name | type | description
-|-|-
CommunicationEventReasonCode | xsd:token | The code specifying a reason for this communication event.
OccurrenceLogisticsLocation | [edi3:LogisticsLocation](#LogisticsLocation) | The logistics location where this communication event will occur or has occurred.
CommunicationEventOccurrenceDateTime | xsd:dateTime | The date, time, date time, or other date time value of an occurrence of this communication event.
CommunicationEventUnitQuantity | xsd:decimal | The number of units for this communication event.
CommunicationEventDescription | xsd:string | A textual description of this communication event.
CommunicationEventAssociatedGeographicalFeature | [edi3:GeographicalFeature](#GeographicalFeature) | A geographical feature associated with this communication event.
OperationalResponsibleParty | [edi3:TradeParty](#TradeParty) | The operational responsible party for this communication event.
CommunicationEventTypeCode | xsd:token | The code specifying the type of communication event.
CommunicationEventValueMeasure | xsd:decimal | The measure of a value for this communication event.


<h1 id="SupplyChainEvent">SupplyChainEvent</h1>

Type: rdf:Class

Description: A significant occurrence or happening in a supply chain.

Properties: 

name | type | description
-|-|-
SupplyChainEventDescription | xsd:string | A textual description of this supply chain event.
OccurrenceTime | xsd:dateTime | A time value of an occurrence of this supply chain event.
SupplyChainEventDueDateTime | xsd:dateTime | The due date, time, date time, or other date time value of this supply chain event.
EarliestOccurrenceDateTime | xsd:dateTime | The date, time, date time, or other date time value of the earliest occurrence of this supply chain event.
SupplyChainEventFrequencyCode | xsd:token | The code specifying a frequency for this supply chain event.
SupplyChainEventOccurrencePeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | A specified period of time during which this supply chain event occurs.
SupplyChainEventUnitQuantity | xsd:decimal | A number of units for this supply chain event.
LatestOccurrenceDateTime | xsd:dateTime | The date, time, date time, or other date time value of the latest occurrence of this supply chain event.
SupplyChainEventOccurrenceDateTime | xsd:dateTime | A date, time, date time, or other date time value of an occurrence of this supply chain event.
SupplyChainEventLocation | [edi3:LogisticsLocation](#LogisticsLocation) | A logistics location where this supply chain event occurs.
SupplyChainEventID | xsd:token | The unique identifier for this supply chain event.
DescriptionBinaryObject | xsd:base64Binary | Binary object data, such as a photograph, describing this supply chain event.


<h1 id="ReferencedEvent">ReferencedEvent</h1>

Type: rdf:Class

Description: A referenced significant occurrence or happening during transport.

Properties: 

name | type | description
-|-|-
ReferencedEventScheduledArrivalDateTime | xsd:dateTime | The date, time, date time or other date time value of the scheduled arrival related to this referenced transport event.
ReferencedEventScheduledDepartureDateTime | xsd:dateTime | The date, time, date time or other date time value of the scheduled departure related to this referenced transport event.
ReasonTypeCode | xsd:token | The code specifying the reason type for this referenced transport event.


<h1 id="ControlSettingParameter">ControlSettingParameter</h1>

Type: rdf:Class

Description: A set of measurable factors that specifies the conditions of its operation within a specific context.

Properties: 

name | type | description
-|-|-
SpecifiedRequestedRange | [edi3:Range](#Range) | A requested range specified for this control setting parameter.
ControlSettingParameterTypeCode | xsd:token | The code specifying a type of parameter for this control setting parameter.
ControlSettingParameterID | xsd:token | The identifier of this control setting parameter.
ControlSettingParameterStatusCode | xsd:token | The code specifying the status of this control setting parameter.
ControlSettingParameterName | xsd:string | The name, expressed as text, of this control setting parameter.
ControlSettingParameterValueAllowedIndicator | xsd:boolean | The indication of whether or not this control setting parameter value is allowed.
ControlSettingParameterChangeableIndicator | xsd:boolean | The indication whether or not this control setting parameter is changeable.
ControlSettingParameterValueText | xsd:string | The value, expressed as text, of this control setting parameter.
ControlSettingParameterDescription | xsd:string | A textual description of this control setting parameter.


<h1 id="DocumentContextParameter">DocumentContextParameter</h1>

Type: rdf:Class

Description: A feature that is fixed for a particular document context.

Properties: 

name | type | description
-|-|-
DocumentContextParameterValueText | xsd:string | The value, expressed as text, of this document context parameter.
Version | [edi3:Version](#Version) | The document version specified for this document context parameter.


<h1 id="OperationalParameter">OperationalParameter</h1>

Type: rdf:Class

Description: A set of measurable factors that specifies the conditions within which an entity operates correctly.

Properties: 

name | type | description
-|-|-
OperationalParameterValueMeasure | xsd:decimal | The measure value for this operational parameter.
DefinedRange | [edi3:Range](#Range) | A defined range specified for this operational parameter.
OperationalParameterDescription | xsd:string | A textual description of this operational parameter.
OperationalParameterStatusCode | xsd:token | The code specifying the status of this operational parameter.
OperationalParameterTypeCode | xsd:token | The code specifying the type of this operational parameter.
OperationalParameterValueText | xsd:string | The value, expressed as text, of this operational parameter.
OperationalParameterName | xsd:string | The name, expressed as text, of this operational parameter.
OperationalParameterChangeableIndicator | xsd:boolean | The indication whether or not this operational parameter is changeable.
OperationalParameterID | xsd:token | The identifier of this operational parameter.


<h1 id="PaymentPenaltyTerms">PaymentPenaltyTerms</h1>

Type: rdf:Class

Description: Trade terms and conditions by which a penalty is or can be applied to a payable amount.

Properties: 

name | type | description
-|-|-
PaymentPenaltyTermsBasisDateTime | xsd:dateTime | The date, time, date time, or other date time value used as the basis to calculate these trade payment penalty terms.
ActualPenaltyAmount | xsd:decimal | A monetary value of the actual penalty in these trade payment penalty terms.
PaymentPenaltyTermsBasisPeriodMeasure | xsd:decimal | The measure of the period used as a basis to calculate these trade payment penalty terms.
PaymentPenaltyTermsCalculationPercent | xsd:decimal | The percent applied to calculate these trade payment penalty terms.


<h1 id="GeographicalMultiCurve">GeographicalMultiCurve</h1>

Type: rdf:Class

Description: A collection of curves on the surface of the Earth (reference ISO 19136).

Properties: 

name | type | description
-|-|-
GeographicalMultiCurveGeographicalObjectCharacteristic | [edi3:GeographicalObjectCharacteristic](#GeographicalObjectCharacteristic) | The geographical object characteristic associated with this geographical multi-curve.
GeographicalMultiCurveGeographicalLine | [edi3:GeographicalLine](#GeographicalLine) | A geographical line member of this geographical multi-curve.


<h1 id="LinearRing">LinearRing</h1>

Type: rdf:Class

Description: A specified array of points which define a closed loop which is not self intersecting.

Properties: 

name | type | description
-|-|-
SpecifiedGeographicalCoordinate | [edi3:FLUXGeographicalCoordinate](#FLUXGeographicalCoordinate) | Geographical coordinate information specified for this linear ring.
LinearRingCoordinateText | xsd:string | A coordinate, expressed as text, for this specified linear ring.
CoordinateDirectPosition | [edi3:DirectPosition](#DirectPosition) | The specified direct position of a coordinate for this linear ring.


<h1 id="SubordinateLineTradeAgreement">SubordinateLineTradeAgreement</h1>

Type: rdf:Class

Description: The contractual terms of a subordinate line trade agreement.

Properties: 

name | type | description
-|-|-
GrossPrice | [edi3:TradePrice](#TradePrice) | A gross product price in this subordinate line trade agreement.
SubordinateLineTradeAgreementSellerOrderDocument | [edi3:Document](#Document) | The seller generated order document referenced in this subordinate line trade agreement.
SubordinateLineTradeAgreementAdditionalDocument | [edi3:Document](#Document) | An additional document referenced in this subordinate line trade agreement.
SubordinateLineTradeAgreementBuyerOrderDocument | [edi3:Document](#Document) | A buyer generated order document referenced in this subordinate line trade agreement.


<h1 id="HeaderTradeAgreement">HeaderTradeAgreement</h1>

Type: rdf:Class

Description: The contractual terms of a header trade agreement.

Properties: 

name | type | description
-|-|-
HeaderTradeAgreementSellerReferenceText | xsd:string | A seller reference, expressed as text, for this header trade agreement.
BuyerTaxRepresentative | [edi3:TradeParty](#TradeParty) | The party acting as a tax representative for the buyer for this header trade agreement.
HeaderTradeAgreementBuyerReferenceText | xsd:string | A buyer reference, expressed as text, for this header trade agreement.
HeaderTradeAgreementRevisionID | xsd:token | An identifier for the revision of this header trade agreement.
HeaderTradeAgreementDemandForecastDocument | [edi3:Document](#Document) | A demand forecast document referenced in this header trade agreement.
HeaderTradeAgreementID | xsd:token | An identifier for this header trade agreement.
HeaderTradeAgreementAdditionalDocument | [edi3:Document](#Document) | An additional document referenced in this header trade agreement.
HeaderTradeAgreementBuyerOrderDocument | [edi3:Document](#Document) | The buyer generated order document referenced in this header trade agreement.
HeaderTradeAgreementPriceListDocument | [edi3:Document](#Document) | The price list document referenced in this header trade agreement.
HeaderTradeAgreementRelevantParty | [edi3:TradeParty](#TradeParty) | A relevant party for this header trade agreement.
HeaderTradeAgreementCrossBorderRegulatoryProcedure | [edi3:RegulatoryProcedure](#RegulatoryProcedure) | A cross-border regulatory procedure applicable to this header trade agreement.
HeaderTradeAgreementDeliveryPriorityCode | xsd:token | The code specifying the delivery priority for this header trade agreement.
HeaderTradeAgreementLogisticsLocation | [edi3:LogisticsLocation](#LogisticsLocation) | A logistics location or place applicable to this header trade agreement.
PurchaseConditionsDocument | [edi3:Document](#Document) | A purchase conditions document referenced in this header trade agreement.
SupplyInstructionDocument | [edi3:Document](#Document) | A supply instruction document referenced in this header trade agreement.
QuoteReferencedWorkflowObject | [edi3:WorkflowObject](#WorkflowObject) | The quote trade workflow object referenced in this header trade agreement.
HeaderTradeAgreementQuotationProposalResponseDocument | [edi3:Document](#Document) | The quotation proposal response document referenced in this header trade agreement.
HeaderTradeAgreementRequisitionDocument | [edi3:Document](#Document) | A requisition document referenced in this header trade agreement.
HeaderTradeAgreementOriginalOrderDocument | [edi3:Document](#Document) | The original order document referenced in this header trade agreement.
HeaderTradeAgreementCarrier | [edi3:TradeParty](#TradeParty) | The carrier party, at header level, for this trade agreement.
ShippingPeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The shipping period specified in this header trade agreement.
HeaderTradeAgreementLetterOfCreditDocument | [edi3:Document](#Document) | The letter of credit document referenced in this header trade agreement.
SellerTaxRepresentative | [edi3:TradeParty](#TradeParty) | The party acting as a tax representative for the seller for this header trade agreement.
HeaderTradeAgreementSalesConditionsDocument | [edi3:Document](#Document) | A sales conditions document referenced in this header trade agreement.
SalesAgent | [edi3:TradeParty](#TradeParty) | The agent party representing the seller for this header trade agreement.
HeaderTradeAgreementSellerOrderDocument | [edi3:Document](#Document) | The seller generated order document referenced in this header trade agreement.
OrderResponseDocument | [edi3:Document](#Document) | The order response document referenced in this header trade agreement.
HeaderTradeAgreementPrimeContractSeller | [edi3:TradeParty](#TradeParty) | The seller party acting as the prime contractor for this header trade agreement.
HeaderTradeAgreementBuyerRequisitioner | [edi3:TradeParty](#TradeParty) | A party who is a buyer requisitioner in this header trade agreement.
HeaderTradeAgreementPaymentTerms | [edi3:PaymentTerms](#PaymentTerms) | The payment terms applicable to this header trade agreement.
CatalogueInformationReceiver | [edi3:TradeParty](#TradeParty) | The party that receives catalogue information for this header trade agreement.
EndUser | [edi3:TradeParty](#TradeParty) | The party acting as the end user for the products in this header trade agreement.
HeaderTradeAgreementEngineeringChangeDocument | [edi3:Document](#Document) | The engineering change document referenced in this header trade agreement.
HeaderTradeAgreementProcurementParty | [edi3:TradeParty](#TradeParty) | The procurement party for this header trade agreement.
HeaderTradeAgreementBuyer | [edi3:TradeParty](#TradeParty) | The buyer party for this header trade agreement.
HeaderTradeAgreementPriorityCode | xsd:token | The code specifying the priority for this header trade agreement.
HeaderTradeAgreementMarketplaceOrderDocument | [edi3:Document](#Document) | The marketplace generated order document referenced in this header trade agreement.
BuyerAgent | [edi3:TradeParty](#TradeParty) | The buyer agent party for this header trade agreement.
HeaderTradeAgreementTargetMarketCountry | [edi3:Country](#Country) | A target market country for this header trade agreement.
CatalogueSubscriptionDocument | [edi3:Document](#Document) | A catalogue subscription document referenced in this header trade agreement.
HeaderTradeAgreementReferenceText | xsd:string | A reference, expressed as text, for this header trade agreement.
ApplicableForecastTerms | [edi3:ForecastTerms](#ForecastTerms) | The supply chain forecast terms applicable to this header trade agreement.
HeaderTradeAgreementQuotationProposalDocument | [edi3:Document](#Document) | The quotation proposal document referenced in this header trade agreement.
QuotationRequestResponseDocument | [edi3:Document](#Document) | The quotation request response document referenced in this header trade agreement.
PreviousOrderResponseDocument | [edi3:Document](#Document) | The previous order response document referenced in this header trade agreement.
HeaderTradeAgreementCatalogueDocument | [edi3:Document](#Document) | A catalogue document referenced in this header trade agreement.
HeaderTradeAgreementImpactCode | xsd:token | The code specifying the impact for this header trade agreement.
HeaderTradeAgreementPromotionalDealDocument | [edi3:Document](#Document) | The promotional deal document referenced in this header trade agreement.
SellerAssignedAccountant | [edi3:TradeParty](#TradeParty) | The party assigned as an accountant by the seller for this header trade agreement.
HeaderTradeAgreementTradeDeliveryTerms | [edi3:DeliveryTerms](#DeliveryTerms) | The terms of delivery applicable to this header trade agreement.
HeaderTradeAgreementImportLicenceDocument | [edi3:Document](#Document) | The import licence document referenced in this header trade agreement.
HeaderTradeAgreementQuotationDocument | [edi3:Document](#Document) | The quotation document referenced in this header trade agreement.
HeaderTradeAgreementExportLicenceDocument | [edi3:Document](#Document) | The export licence document referenced in this header trade agreement.
HeaderTradeAgreementQuotationRequestDocument | [edi3:Document](#Document) | The quotation request document referenced in this header trade agreement.
HeaderTradeAgreementPreviousOrderDocument | [edi3:Document](#Document) | The previous order document referenced in this header trade agreement.
ProcuringProject | [edi3:Project](#Project) | The procuring project specified for this header trade agreement.
HeaderTradeAgreementRequisitionerDocument | [edi3:Document](#Document) | A requisitioner document referenced in this header trade agreement.
PricingBaseAppilicableLogisticsLocation | [edi3:LogisticsLocation](#LogisticsLocation) | The logistics location applicable to the pricing base for this header trade agreement.
PreviousOrderChangeDocument | [edi3:Document](#Document) | The previous order change document referenced in this header trade agreement.
HeaderTradeAgreementContractDocument | [edi3:Document](#Document) | A contract document referenced in this header trade agreement.
HeaderTradeAgreementBuyerApprovedDateTime | xsd:dateTime | The date, time, date time, or other date time value of approval by the buyer for this header trade agreement.
HeaderTradeAgreementCatalogueInformationProvider | [edi3:TradeParty](#TradeParty) | The party that provides catalogue information for this header trade agreement.
CatalogueRequestDocument | [edi3:Document](#Document) | A catalogue request document referenced in this header trade agreement.
HeaderTradeAgreementBlanketOrderDocument | [edi3:Document](#Document) | The blanket order document referenced in this header trade agreement.
HeaderTradeAgreementUltimateCustomerOrderDocument | [edi3:Document](#Document) | An ultimate customer order document referenced for this header trade agreement.
HeaderTradeAgreementSalesReportDocument | [edi3:Document](#Document) | The sales report document referenced in this header trade agreement.
HeaderTradeAgreementSeller | [edi3:TradeParty](#TradeParty) | The seller party for this header trade agreement.


<h1 id="LineTradeAgreement">LineTradeAgreement</h1>

Type: rdf:Class

Description: The contractual terms of a line trade agreement.

Properties: 

name | type | description
-|-|-
LineTradeAgreementPriceListDocument | [edi3:Document](#Document) | The price list document referenced in this line trade agreement.
LineTradeAgreementQuotationRequestDocument | [edi3:Document](#Document) | The quotation request document referenced in this line trade agreement.
LineTradeAgreementSeller | [edi3:TradeParty](#TradeParty) | The seller party for this line trade agreement.
LineTradeAgreementRelevantParty | [edi3:TradeParty](#TradeParty) | A party relevant for this line trade agreement.
LineTradeAgreementBuyerOrderDocument | [edi3:Document](#Document) | A buyer generated order document referenced in this line trade agreement.
GuaranteedProductLifeSpanPeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The guaranteed product life span specified in this line trade agreement.
ExclusivityPeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The exclusivity period specified in this line trade agreement.
LineTradeAgreementBuyerRequisitioner | [edi3:TradeParty](#TradeParty) | A party who is a buyer requisitioner in this line trade agreement.
LineTradeAgreementReferenceText | xsd:string | A reference, expressed as text, for this line trade agreement.
LineTradeAgreementID | xsd:token | An identifier for this line trade agreement.
ProductNetPrice | [edi3:TradePrice](#TradePrice) | A net product price in this line trade agreement.
LineTradeAgreementLetterOfCreditDocument | [edi3:Document](#Document) | The letter of credit document referenced in this line trade agreement.
LineTradeAgreementQuotationProposalResponseDocument | [edi3:Document](#Document) | The quotation proposal response document referenced in this line trade agreement.
LineTradeAgreementSalesConditionsDocument | [edi3:Document](#Document) | A sales conditions document referenced by this line trade agreement.
MinimumProductOrderableQuantity | xsd:decimal | The minimum product orderable quantity for this line trade agreement.
ProductEndUser | [edi3:TradeParty](#TradeParty) | The party acting as the end user for the products in this line trade agreement.
RequestForQuotationResponseDocument | [edi3:Document](#Document) | The quotation request response document referenced in this line trade agreement.
LineTradeAgreementUltimateCustomerOrderDocument | [edi3:Document](#Document) | An ultimate customer order document referenced for this line trade agreement.
LineTradeAgreementBuyer | [edi3:TradeParty](#TradeParty) | The buyer party for this line trade agreement.
LineTradeAgreementCarrier | [edi3:TradeParty](#TradeParty) | A carrier party for this line trade agreement.
LineTradeAgreementDeliveryPriorityCode | xsd:token | The code specifying the delivery priority for this line trade agreement.
LineTradeAgreementEngineeringChangeDocument | [edi3:Document](#Document) | The engineering change document referenced in this line trade agreement.
ProgramMissionProject | [edi3:MissionProject](#MissionProject) | A mission project program for this line trade agreement.
LineTradeAgreementPromotionalDealDocument | [edi3:Document](#Document) | The promotional deal document referenced in this line trade agreement.
ResaleProductUnitOfMeasureCode | xsd:token | The code specifying the resale product unit of measure, such as kilogram or litre, for this trade line agreement.
LineTradeAgreementImpactCode | xsd:token | The code specifying the impact for this line trade agreement.
ItemSeller | [edi3:TradeParty](#TradeParty) | The item seller party for this line trade agreement.
OrderPrice | [edi3:TradePrice](#TradePrice) | An order price for a product in this line trade agreement.
LineTradeAgreementBuyerReferenceText | xsd:string | A buyer reference, expressed as text, for this line trade agreement.
LineTradeAgreementOriginalOrderDocument | [edi3:Document](#Document) | The original order document referenced in this line trade agreement.
IncrementalProductOrderableQuantity | xsd:decimal | The incremental product orderable quantity for this line trade agreement.
ProductGrossPrice | [edi3:TradePrice](#TradePrice) | A gross product price in this line trade agreement.
InformationUseRestrictionIndicator | xsd:boolean | The indication of whether or not the use of the information provided in this line trade agreement is restricted.
OrderProductUnitOfMeasureCode | xsd:token | The code specifying the order product unit of measure, such as kilogram or litre, for this line trade agreement.
LineTradeAgreementPrimeContractSeller | [edi3:TradeParty](#TradeParty) | The seller party acting as the prime contractor for this line trade agreement.
Marketplace | [edi3:Marketplace](#Marketplace) | A marketplace included in this line trade agreement.
LineTradeAgreementMarketplaceOrderDocument | [edi3:Document](#Document) | The marketplace generated order document referenced in this line trade agreement.
LineTradeAgreementSellerOrderDocument | [edi3:Document](#Document) | The seller generated order document referenced in this line trade agreement.
LineTradeAgreementProcurementParty | [edi3:TradeParty](#TradeParty) | The procurement party for this line trade agreement.
LineTradeAgreementQuotationDocument | [edi3:Document](#Document) | The quotation document referenced in this line trade agreement.
PickUpOrderFulfilmentLeadTime | xsd:decimal | The measure of the expected time interval between the receipt of an order and its pick-up fulfilment according to this line trade agreement.
LineTradeAgreementRequisitionerDocument | [edi3:Document](#Document) | A requisitioner document referenced in this line trade agreement.
SupplyInstruction | [edi3:Document](#Document) | A supply instruction document referenced in this line trade agreement.
LineTradeAgreementBuyerApprovedDateTime | xsd:dateTime | The date, time, date time, or other date time value of approval by the buyer for this line trade agreement.
LineTradeAgreementQuotationProposalDocument | [edi3:Document](#Document) | The quotation proposal document referenced in this line trade agreement.
LineTradeAgreementContractDocument | [edi3:Document](#Document) | A contract document referenced in this line trade agreement.
ImmediatePreviousPriceListDocument | [edi3:Document](#Document) | The immediate previous price list document referenced in this line trade agreement.
LineTradeAgreementRevisionID | xsd:token | An identifier for the revision of this line trade agreement.
ForecastTerms | [edi3:ForecastTerms](#ForecastTerms) | The supply chain forecast terms applicable to this line trade agreement.
LineTradeAgreementPriorityCode | xsd:token | The code specifying the priority for this line trade agreement.
LineTradeAgreementSellerReferenceText | xsd:string | A seller reference, expressed as text, for this line trade agreement.
MinimumOrderQuantityOrderingPeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The minimum order quantity ordering period specified in this line trade agreement.
LineTradeAgreementRequisitionDocument | [edi3:Document](#Document) | A requisition document referenced in this line trade agreement.
MaximumProductOrderableQuantity | xsd:decimal | The maximum product orderable quantity for this line trade agreement.
MaximumOrderQuantityOrderingPeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The maximum order quantity ordering period specified in this line trade agreement.
LineTradeAgreementDemandForecastDocument | [edi3:Document](#Document) | A demand forecast document referenced in this line trade agreement.
SupportCentre | [edi3:TradeParty](#TradeParty) | The support centre party for this line trade agreement.
DeliveryOrderFulfilmentLeadTime | xsd:decimal | The measure of the expected time interval between the receipt of an order and its delivery fulfilment according to this line trade agreement.
ProductReorderableIndicator | xsd:boolean | The indication of whether or not the product can be reordered according to this line trade agreement.
LineTradeAgreementTargetMarketCountry | [edi3:Country](#Country) | A target market country for this line trade agreement.
LineTradeAgreementExportLicenceDocument | [edi3:Document](#Document) | The export licence document referenced in this line trade agreement.
LineTradeAgreementPreviousOrderDocument | [edi3:Document](#Document) | The previous order document referenced in this line trade agreement.
ItemBuyer | [edi3:TradeParty](#TradeParty) | The item buyer party for this line trade agreement.
LineTradeAgreementSalesReportDocument | [edi3:Document](#Document) | The sales report document referenced in this line trade agreement.
LineTradeAgreementBlanketOrderDocument | [edi3:Document](#Document) | The blanket order document referenced in this line trade agreement.
LineTradeAgreementTradeDeliveryTerms | [edi3:DeliveryTerms](#DeliveryTerms) | The terms of delivery applicable to this line trade agreement.
LineTradeAgreementCatalogueDocument | [edi3:Document](#Document) | A catalogue document referenced by this line trade agreement.
ProductAvailabilityCode | xsd:token | The code specifying the product availability according to this line trade agreement.
LineTradeAgreementImportLicenceDocument | [edi3:Document](#Document) | The import licence document referenced in this line trade agreement.
OrderingPeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The ordering period specified in this line trade agreement.
ResalePeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The resale period specified in this line trade agreement.
LineTradeAgreementCatalogueInformationProvider | [edi3:TradeParty](#TradeParty) | The party that provides catalogue information for this line trade agreement.
LineTradeAgreementEconomicOrderQuantity | xsd:decimal | The economic order quantity for this line trade agreement.
LineTradeAgreementAdditionalDocument | [edi3:Document](#Document) | An additional document referenced in this line trade agreement.
ProductMadeToOrderIndicator | xsd:boolean | The indication of whether or not, according to this line trade agreement, the product is manufactured, built or customized only after receipt of order.


<h1 id="DirectPosition">DirectPosition</h1>

Type: rdf:Class

Description: A specified physical location described within a coordinate reference system.

Properties: 

name | type | description
-|-|-
UnitOfMeasureLabelListText | xsd:string | An ordered list of Unit Of Measure (UOM) labels, expressed as text, for this specified direct position.
DirectPositionCount | xsd:decimal | A count for this specified direct position.
DirectPositionCoordinateReferenceDimensionText | xsd:string | A coordinate reference dimension, expressed as text, for this specified direct position.
DirectPositionName | xsd:string | The name, expressed as text, of the reference for this specified direct position.


<h1 id="AppliedAllowanceCharge">AppliedAllowanceCharge</h1>

Type: rdf:Class

Description: The applied allowance or charge component of pricing.

Properties: 

name | type | description
-|-|-
AppliedAllowanceChargeReasonCode | xsd:token | The code specifying the reason for this applied allowance charge.
AppliedAllowanceChargeDescription | xsd:string | The textual description of the applied allowance charge.
AppliedAllowanceChargeCalculationPercent | xsd:decimal | The percentage used to calculate the applied allowance charge.
AppliedAllowanceChargeActualAmount | xsd:decimal | The actual monetary value of the applied allowance charge.
AppliedAllowanceChargeBasisAmount | xsd:decimal | The monetary value that is the basis on which the applied allowance charge is calculated.
AppliedAllowanceChargeChargeIndicator | xsd:boolean | The indication of whether or not the applied allowance charge is a charge.


<h1 id="TradeAllowanceCharge">TradeAllowanceCharge</h1>

Type: rdf:Class

Description: A component of pricing, such as an allowance or charge for trade purposes.

Properties: 

name | type | description
-|-|-
TradeAllowanceChargeReasonText | xsd:string | The reason, expressed as text, for this trade allowance charge.
TradeAllowanceChargeBasisAmount | xsd:decimal | The monetary value that is the basis on which this trade allowance charge is calculated.
TradeAllowanceChargeChargeIndicator | xsd:boolean | The indication of whether or not the trade allowance charge is a charge.
TradeAllowanceChargeID | xsd:token | The unique identifier for this trade allowance charge.
TradeAllowanceChargeTypeCode | xsd:token | The code specifying the type of this trade allowance charge.
TradeAllowanceChargeTaxCategory | [edi3:TradeTax](#TradeTax) | A tax category of this trade allowance charge.
TradeAllowanceChargeReasonCode | xsd:token | The code specifying the reason for this trade allowance charge.
TradeAllowanceChargeActualAmount | xsd:decimal | An actual monetary value of the trade allowance charge.
TradeAllowanceChargeUnitBasisAmount | xsd:decimal | The monetary value of the unit basis on which the allowance or charge is calculated.
TradeAllowanceChargeSequenceNumber | xsd:decimal | The sequence number for applying this trade allowance charge.
TradeAllowanceChargeBasisQuantity | xsd:decimal | The quantity on which this trade allowance charge is based.
TradeAllowanceChargeCalculationPercent | xsd:decimal | The percentage applied to calculate this trade allowance charge.
PrepaidIndicator | xsd:boolean | The indication of whether or not this trade allowance charge is prepaid.


<h1 id="Label">Label</h1>

Type: rdf:Class

Description: A label used for identifying goods for logistics purposes, such as a barcode, a radio frequency tag or a Vehicle Identification Number (VIN).

Properties: 

name | type | description
-|-|-
LabelSeriesStartID | xsd:token | The unique identifier of the start of a series of logistics labels.
LayoutTypeCode | xsd:token | The code specifying the layout type of this logistics label.
SizeCode | xsd:token | The code specifying the size of this logistics label.
LabelID | xsd:token | The unique identifier of this logistics label.
IncludedSection | [edi3:Section](#Section) | A section included in this logistics label.


<h1 id="TradeTax">TradeTax</h1>

Type: rdf:Class

Description: A trade related fiscal levy or duty.

Properties: 

name | type | description
-|-|-
BuyerNonDeductibleTaxAccountingAccount | [edi3:AccountingAccount](#AccountingAccount) | The buyer non-deductible tax specified accounting account for this trade related tax, levy or duty.
BuyerRepayableTaxAccountingAccount | [edi3:AccountingAccount](#AccountingAccount) | The buyer repayable tax specified accounting account for this trade related tax, levy or duty.
SelfAssessedBasisQuantity | xsd:decimal | The quantity on which this trade related tax, levy or duty has been calculated on a self-assessment basis.
ServiceSupplyCountry | [edi3:Country](#Country) | The country or country sub-division where a service was supplied for this trade tax.
TradeTaxCustomsDutyIndicator | xsd:boolean | The indication of whether or not this trade related tax, levy or duty is a customs duty.
TradeTaxGuaranteeCode | xsd:token | The code specifying an undertaking given in cash, bond or as a written guarantee to ensure that an obligation will be fulfilled for this trade related tax, levy or duty.
SellerRefundableTaxAccountingAccount | [edi3:AccountingAccount](#AccountingAccount) | The seller refundable tax specified accounting account for this trade related tax, levy or duty.
PaymentID | xsd:token | The unique identifier of the payment of this trade related tax, levy or duty.
CategoryName | xsd:string | A category name, expressed as text, of this trade related tax, levy or duty.
CalculationSequenceNumber | xsd:decimal | A numeric expression of the sequence in which this trade related tax is to be or has been applied when multiple taxes are applicable per calculation, such as first "Value Added Tax (VAT)", second "Transfer".
TradeTaxCurrencyCode | xsd:token | The code specifying the currency for this trade related tax, levy or duty [UNCL 6345].
ExemptionAuthorizationID | xsd:token | The unique identifier of the exemption authorization for this trade tax.
TradeTaxExemptionReasonCode | xsd:token | A code specifying a reason for exemption from this trade related tax, levy or duty.
RegimeTypeCode | xsd:token | The code specifying a type of regime applicable to the assessment or calculation of this trade related tax, levy or duty, such as a preferential duty rate.
TradeTaxCategoryCode | xsd:token | The code specifying the category to which this trade related tax, levy or duty applies, such as codes for "Exempt from Tax", "Standard Rate", "Free Export Item - Tax Not Charged" [Reference United Nations Code List (UNCL) 5305].
TradeTaxGuaranteeText | xsd:string | The undertaking, expressed as text, given in cash, bond or as a written guarantee to ensure that an obligation will be fulfilled for this trade related tax, levy or duty.
BuyerDeductibleTaxAccountingAccount | [edi3:AccountingAccount](#AccountingAccount) | The buyer deductible tax specified accounting account for this trade related tax, levy or duty.
TradeTaxTypeCode | xsd:token | The code specifying the type of trade related tax, levy or duty, such as a code for a Value Added Tax (VAT) [Reference United Nations Code List (UNCL) 5153].
Percent | xsd:decimal | The percent of trade tax applicable, such as to an object or an activity.
TradeTaxGrandTotalAmount | xsd:decimal | A monetary value of the grand total of the basis plus tax for this trade tax.
TradeTaxCalculatedAmount | xsd:decimal | A monetary value resulting from the calculation of this trade related tax, levy or duty.
TradeTaxTariffDeductionQuantity | xsd:decimal | A quantity to be deducted from the tariff quantity for the calculation of this trade related tax, duty or levy.
RefundAmount | xsd:decimal | A monetary value of the refund of this trade related tax, levy or duty.
TradeTaxPaymentMethodCode | xsd:token | The code specifying the payment method for this trade related tax, levy or duty.
BasisAllowanceRate | xsd:decimal | The rate of the tax basis allowance (deduction or discount) used to calculate the trade related tax, levy or duty.
TradeTaxUnitBasisAmount | xsd:decimal | A monetary value that constitutes the per unit basis on which this trade related tax, levy or duty is calculated.
SellerPayableTaxAccountingAccount | [edi3:AccountingAccount](#AccountingAccount) | The seller payable tax specified accounting account for this trade related tax, levy or duty.
TradeTaxBasisQuantity | xsd:decimal | The quantity used as the basis for calculating the amount of this trade related tax, levy or duty.
ApplicableRatePercent | xsd:decimal | The applicable rate, expressed as a percentage, for this trade tax, levy or duty.
TradeAccountingAccount | [edi3:AccountingAccount](#AccountingAccount) | A specified accounting account for this trade related tax, levy or duty.
TradeTaxTaxPointDate | xsd:date | The date of the tax point when this trade related tax, levy or duty becomes applicable.
TaxCalculationMethodCode | xsd:token | The code specifying the method by which this trade related tax, levy or duty is calculated, such as codes for "tax calculated after line total summation", "tax calculated before line total summation", "tax back calculated based on grand total".
AllowanceChargeBasisAmount | xsd:decimal | A monetary value used as the allowance and charge basis on which this trade related tax, levy or duty is calculated.
ExemptionIndicator | xsd:boolean | The indication of whether or not there is an exemption from this trade tax.
SelfAssessedBasisAmount | xsd:decimal | A monetary value of the amount on which this trade related tax, levy or duty has been calculated on a self-assessment basis.
SelfAssessedCalculatedAmount | xsd:decimal | A monetary value of the self-assessed calculated amount of this trade related tax, levy or duty.
TradeTaxExemptionReasonText | xsd:string | The reason, expressed as text, for exemption from this trade related tax, levy or duty.
TradeTaxInformationAmount | xsd:decimal | A monetary value of an amount being reported for information for this trade related tax, levy or duty.
DueDateTypeCode | xsd:token | The code specifying a type of due date for this trade tax.
ApplicableLocation | [edi3:TradeLocation](#TradeLocation) | A location where this trade tax is applicable.
DeductionAmount | xsd:decimal | A monetary value of the deduction from this trade related tax, levy or duty.
TradeTaxCalculatedRate | xsd:decimal | The rate used to calculate the amount of this trade related tax, levy or duty.
TradeTaxTypeText | xsd:string | The type, expressed as text, of this trade related tax, levy or duty.
TradeTaxJurisdictionText | xsd:string | A jurisdiction, expressed as text, to which this trade related tax, levy or duty applies.
TaxExemptionAuthorityID | xsd:token | The unique tax exemption authority identifier for this trade tax.
LineTotalBasisAmount | xsd:decimal | A monetary value used as the line total basis on which this trade related tax, levy or duty is calculated.
RateCode | xsd:token | The code specifying the rate for this trade related tax, levy or duty.


<h1 id="AppliedTax">AppliedTax</h1>

Type: rdf:Class

Description: A total levy or payment for the support of a government that is required of persons, groups, or businesses within the domain of that government.

Properties: 

name | type | description
-|-|-
AppliedTaxCalculatedAmount | xsd:decimal | The monetary value resulting from the calculation of the applied tax.
AppliedTaxTaxPointDate | xsd:date | The date of the tax point when taxes, such as VAT, are to be applied.
AppliedTaxCalculatedRate | xsd:decimal | The rate used to calculate the applied tax.
AppliedTaxBasisAmount | xsd:decimal | The monetary value used as the basis in calculating the applied tax.


<h1 id="RegisteredTax">RegisteredTax</h1>

Type: rdf:Class

Description: A registered tax or duty system pertaining to an authority.

Properties: 

name | type | description
-|-|-
RegisteredTaxTypeCode | xsd:token | The code specifying the type of registered tax.
RegisteredTaxCurrencyCode | xsd:token | The code specifying the currency for this registered tax.
RegisteredTaxDescription | xsd:string | A textual description of this registered tax.
RegisteredTaxCustomsDutyIndicator | xsd:boolean | The indication of whether or not this registered tax is a customs duty.
RegisteredTaxJurisdictionText | xsd:string | A jurisdiction, expressed as text, for this registered tax.
RegisteredTaxExemptionReasonText | xsd:string | A reason, expressed as text, for exemption from this registered tax.


<h1 id="Process">Process</h1>

Type: rdf:Class

Description: A naturally occurring or designed sequence of operations or events that create, transform, or touch a product, such as manufacturing, treating, packaging, and storing.

Properties: 

name | type | description
-|-|-
CompletionPeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The specified period of completion for this product handling process.
OperationCountry | [edi3:Country](#Country) | The trade country where the operation of this product handling process occurs.
ApplicableCharacteristic | [edi3:ProcessCharacteristic](#ProcessCharacteristic) | A process characteristic applicable to this product handling process.
ProcessOperator | [edi3:TradeParty](#TradeParty) | A trade party who is an operator of this product handling process.


<h1 id="BreakdownStatement">BreakdownStatement</h1>

Type: rdf:Class

Description: A detailed statement of work, prices, and dimensions for this valuation.

Properties: 

name | type | description
-|-|-
BreakdownStatementName | xsd:string | The name, expressed as text, for this valuation breakdown statement.
ReaderBinaryFile | [edi3:BinaryFile](#BinaryFile) | A specified binary file used to read this valuation breakdown statement.
DefaultLanguageCode | xsd:token | The code specifying the default language for this valuation breakdown statement.
BreakdownStatementContractualLanguageCode | xsd:token | The code specifying the contractual language for this valuation breakdown statement.
DefaultCurrencyCode | xsd:token | The code specifying the default currency for this valuation breakdown statement.
BreakdownStatementID | xsd:token | The unique identifier for this valuation breakdown statement.
PriceListID | xsd:token | The identifier of a price list for this valuation breakdown statement.
GroupedWorkItem | [edi3:GroupedWorkItem](#GroupedWorkItem) | A grouped work item in this valuation breakdown statement.
BasicWorkItem | [edi3:BasicWorkItem](#BasicWorkItem) | A basic work item in this valuation breakdown statement.
BreakdownStatementTypeCode | xsd:token | A code specifying the type of valuation breakdown statement.
BreakdownStatementRequestedActionCode | xsd:token | A code specifying the requested action for this valuation breakdown statement.
BreakdownStatementReferencedBinaryFile | [edi3:BinaryFile](#BinaryFile) | A specified binary file referenced by this valuation breakdown statement.
BreakdownStatementTotalCalculatedPrice | [edi3:CalculatedPrice](#CalculatedPrice) | A total calculated price for this valuation breakdown statement.
BreakdownStatementChangedRecordedStatus | [edi3:RecordedStatus](#RecordedStatus) | A changed recorded status for this valuation breakdown statement.
CreationBinaryFile | [edi3:BinaryFile](#BinaryFile) | A specified binary file used to create this valuation breakdown statement.
BreakdownStatementCreationDateTime | xsd:dateTime | The date, time, date time, or other date time value of the creation of this valuation breakdown statement.
BreakdownStatementDescription | xsd:string | A textual description of this valuation breakdown statement.
BreakdownStatementComment | xsd:string | A comment, expressed as text, for this valuation breakdown statement.


<h1 id="ForecastTerms">ForecastTerms</h1>

Type: rdf:Class

Description: A set of terms and conditions by which a supply chain forecast has been or will be made.

Properties: 

name | type | description
-|-|-
ForecastTermsFrequencyCode | xsd:token | A code specifying a frequency in these supply chain forecast terms.
ForecastTermsCommitmentLevelCode | xsd:token | A code specifying a commitment level in these supply chain forecast terms.
DateTypeCode | xsd:token | A code specifying a type of date in these supply chain forecast terms.


<h1 id="GeographicalLine">GeographicalLine</h1>

Type: rdf:Class

Description: A connection between two points on the surface of the Earth (reference ISO 19136).

Properties: 

name | type | description
-|-|-
GeographicalLineDirectPositionList | [edi3:DirectPositionList](#DirectPositionList) | The direct position list associated with this geographical line.
GeographicalLineGeographicalObjectCharacteristic | [edi3:GeographicalObjectCharacteristic](#GeographicalObjectCharacteristic) | The geographical object characteristic associated with this geographical line.


<h1 id="Version">Version</h1>

Type: rdf:Class

Description: A specific variant of a document.

Properties: 

name | type | description
-|-|-
VersionName | xsd:string | The name, expressed as text, of this document version.
VersionID | xsd:token | The unique identifier for this document version.


<h1 id="GeographicalObjectCharacteristic">GeographicalObjectCharacteristic</h1>

Type: rdf:Class

Description: An attribute of a geographical object.

Properties: 

name | type | description
-|-|-
GeographicalObjectCharacteristicDescription | xsd:string | The textual description for this geographical object characteristic.
RelevantGeometryTypeText | xsd:string | The type of geometry, expressed as text, relevant for this geographical object characteristic.
PhysicalIndicator | xsd:boolean | The indication of whether or not this geographical object can be characterized as physical.
GeometryCollectionIndicator | xsd:boolean | The indication of whether or not this geographical object can be characterized as a geometry collection.
ShapeTypeText | xsd:string | The type of shape, expressed as text, such as a semi-circle, for this geographical object characteristic.
GeographicalObjectCharacteristicName | xsd:string | The name, expressed as text, for this geographical object characteristic.
DescriptionReferenceText | xsd:string | The description reference, expressed as text, for this geographical object characteristic.


<h1 id="LegalRegistration">LegalRegistration</h1>

Type: rdf:Class

Description: The recording of items or details for a specific legal purpose.

Properties: 

name | type | description
-|-|-
LegalRegistrationID | xsd:token | A unique identifier for this legal registration.
LegalRegistrationLastRegisteredYear | xsd:dateTime | The last year in which this legal registration was registered.
LegalRegistrationCountryCode | xsd:token | An identifier of the country in which this legal registration is valid.


<h1 id="TaxRegistration">TaxRegistration</h1>

Type: rdf:Class

Description: Registration with a specific tax authority.

Properties: 

name | type | description
-|-|-
TaxRegistrationID | xsd:token | The unique identifier for this tax registration.
RegisteredTax | [edi3:RegisteredTax](#RegisteredTax) | The registered tax associated with this tax registration.


<h1 id="GovernmentRegistration">GovernmentRegistration</h1>

Type: rdf:Class

Description: The recording of items or details for a governmental purpose.

Properties: 

name | type | description
-|-|-
GovernmentRegistrationID | xsd:token | An identifier for this government registration.
GovernmentRegistrationCountryCode | xsd:token | The identifier of the country for this government registration.
GovernmentRegistrationTypeCode | xsd:token | A code specifying a type of government registration.
GovernmentRegistrationVersionID | xsd:token | The identifier of the version of this government registration.
GovernmentRegistrationCategoryCode | xsd:token | A code specifying a category of this government registration.
GovernmentRegistrationCountrySubDivisionCode | xsd:token | The identifier of the country sub-division for this registration.
GovernmentRegistrationValidityPeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The period of time during which this government registration is valid.
LicenceID | xsd:token | The identifier of a licence for this government registration.
RecordedDate | xsd:date | The date that this government registration was recorded.


<h1 id="GeographicalCoordinate">GeographicalCoordinate</h1>

Type: rdf:Class

Description: A set of geographical coordinates of a specific point such as the longitude, latitude and altitude.

Properties: 

name | type | description
-|-|-
TimeZoneText | xsd:string | The time zone, expressed as text, for this geographical coordinate.
GeographicalCoordinateSystemID | xsd:token | The unique identifier of the reference system used for measuring a geographical coordinate.
AltimetricSystemID | xsd:token | The unique identifier of the system used for measuring the altitude.
TimeZoneDateTime | xsd:dateTime | The date, time, date time, or other date time value for the time zone of this geographical coordinate.
GeographicalCoordinateLatitudeDirectionIndicator | xsd:boolean | The indication of whether the latitude compass direction from the Equator meridian to the meridian of a specific place is North (+) or South (-)  (Reference ISO 6709).
GeographicalCoordinateLongitudeDirectionIndicator | xsd:boolean | The indication of whether the longitude as a compass direction from the Greenwich meridian to the meridian of a specific place is East (+) or West (-) for this geographical coordinate (Reference ISO 6709).
GeographicalCoordinateID | xsd:token | The unique identifier for this geographical coordinate.
GeographicalCoordinateUsedGeographicalCoordinateSourceSystem | [edi3:CoordinateSourceSystem](#CoordinateSourceSystem) | The geographical coordinate source system used for this geographical coordinate.
GeographicalCoordinateAltitude | xsd:decimal | The measure of the altitude that reflects the vertical elevation of an object above a surface for this geographical coordinate (Reference ISO 6709).
AlternativeSourceSystemID | xsd:token | An alternative source system identifier for this geographical coordinate.
GeographicalCoordinateLongitude | xsd:decimal | The measure of the longitude as an angular distance east or west from the Greenwich meridian to the meridian of a specific place (Reference ISO 6709).
TimeZoneCode | xsd:token | The code specifying the time zone of this geographical coordinate.
GeographicalCoordinateLatitude | xsd:decimal | The measure of the latitude as an angular distance north or south from the Equator meridian to the meridian of a specific place for this geographical coordinate (Reference ISO 6709).
GeographicalCoordinateAcquisitionDateTime | xsd:dateTime | The date, time, date time or other date time value of the acquisition of this geographical coordinate.


<h1 id="SpecifiedGeographicalCoordinate">SpecifiedGeographicalCoordinate</h1>

Type: rdf:Class

Description: The latitude and longitude of a specified place, by which its relative situation on the globe is known. The height above the sea level constitutes a third coordinate.

Properties: 

name | type | description
-|-|-
SpecifiedGeographicalCoordinateLongitude | xsd:decimal | The measure of the longitude as an angular distance east or west from the Greenwich meridian to the meridian of a specific place for this specified geographical coordinate. (Reference ISO 6709).
SpecifiedGeographicalCoordinateLatitudeDirectionIndicator | xsd:boolean | The indication of whether the latitude compass direction from the Equator meridian to the meridian of a specific place for this specified geographical coordinate is North (+) or South (-).  (Reference ISO 6709).
SpecifiedGeographicalCoordinateLatitude | xsd:decimal | The measure of the latitude as an angular distance north or south from the Equator meridian to the meridian of a specific place for this specified geographical coordinate. (Reference ISO 6709).
SpecifiedGeographicalCoordinateSystemID | xsd:token | The unique identifier of the system used for measuring this specified geographical coordinate.
SpecifiedGeographicalCoordinateAltitude | xsd:decimal | The measure of the altitude that reflects the vertical elevation of an object above a surface for this specified geographical coordinate (Reference ISO 6709).


<h1 id="Production">Production</h1>

Type: rdf:Class

Description: The making or manufacturing of goods, such as from components or raw materials.

Properties: 

name | type | description
-|-|-
ManufacturingProcessDescription | xsd:string | A textual description of the manufacturing process for this goods production.


<h1 id="TransportMovement">TransportMovement</h1>

Type: rdf:Class

Description: The conveyance (physical carriage) of goods or other objects used for logistics transport purposes.

Properties: 

name | type | description
-|-|-
TerminalOperatorAssignedID | xsd:token | A unique identifier for this logistics transport movement as assigned by a terminal operator.
CrewQuantity | xsd:decimal | The number of crew members for this logistics transport movement.
CrewNationalityCountry | [edi3:Country](#Country) | Crew nationality details for this logistics transport movement.
ISPSDocument | [edi3:Document](#Document) | The International Ship and Port facility Security code (ISPS) document related to this transport movement.
StageCode | xsd:token | The code specifying the stage of this logistics transport movement.
OnboardInventory | [edi3:StoresItemInventory](#StoresItemInventory) | A stores inventory item held onboard for this logistics transport movement.
ConsortiumCarrier | [edi3:TradeParty](#TradeParty) | A consortium carrier party for this logistics transport movement.
TransportMovementID | xsd:token | The unique identifier for this logistics transport movement, such as a voyage number, flight number, or trip number.
TransportMovementTransportEquipmentQuantity | xsd:decimal | The number of pieces of transport equipment for this logistics transport movement.
TransportMovementUnloadingEvent | [edi3:Event](#Event) | The unloading event during which goods will be or have been unloaded from the means of transport used for this logistics transport movement.
TransportMovementTransportContractDocument | [edi3:Document](#Document) | A transport contract document related to this logistics transport movement.
ArrivalEvent | [edi3:Event](#Event) | An arrival event for this logistics transport movement.
TransportMovementLoadingEvent | [edi3:Event](#Event) | The loading event during which goods will be or have been loaded into or onto the means of transport used for this logistics transport movement.
TransportMovementLogisticsRiskAnalysisResult | [edi3:RiskAnalysisResult](#RiskAnalysisResult) | A result of a logistics risk analysis calculation specified for this transport movement.
UnloadingInspectionInstructions | [edi3:TransportInstructions](#TransportInstructions) | Unloading inspection instructions specified for this logistics transport movement.
TransportMovementCarrier | [edi3:TradeParty](#TradeParty) | A carrier party for this logistics transport movement.
LoadingInspectionParty | [edi3:TradeParty](#TradeParty) | The loading inspection party for this logistics transport movement.
TradedParcelQuantity | xsd:decimal | The number of traded parcels of cargo being transported in this logistics transport movement.
SailingAdviceNotifiedParty | [edi3:TradeParty](#TradeParty) | A party to be notified of the sailing advice for this logistics transport movement.
ManifestOnboardIndicator | xsd:boolean | The indication of whether or not the manifest for this logistics transport movement is onboard.
PassengerQuantity | xsd:decimal | The number of passengers for this logistics transport movement.
ModeText | xsd:string | The mode, expressed as text, of this logistics transport movement.
TransportMovementSpecialInstructions | [edi3:TransportInstructions](#TransportInstructions) | Special transport instructions specified for this logistics transport movement.
Stevedore | [edi3:TradeParty](#TradeParty) | A stevedore party for this logistics transport movement.
TradingConsolidatorAssignedID | xsd:token | The unique identifier for this logistics transport movement as assigned by the trading consolidator.
CommodityConsolidatorAgent | [edi3:TradeParty](#TradeParty) | The commodity consolidator agent party for this logistics transport movement.
CallEvent | [edi3:Event](#Event) | A call event for this logistics transport movement.
ServiceText | xsd:string | The service, expressed as text, of this logistics transport movement.
AssociatedConvoy | [edi3:Convoy](#Convoy) | The convoy associated with this logistics transport movement.
SpecifiedCalculatedEmission | [edi3:Emission](#Emission) | A calculated emission specified for this logistics transport movement.
CycleText | xsd:string | The cycle, as expressed as text, of this logistics transport movement, such as twice a day.
TransportMovementApplicableServiceCharge | [edi3:ServiceCharge](#ServiceCharge) | A service charge, such as a freight charge, applicable to this logistics transport movement.
PassengerListDocument | [edi3:Document](#Document) | The passenger list document related to this logistics transport movement.
CarriedInactiveTransportMeans | [edi3:TransportMeans](#TransportMeans) | Details of transport means inactively carried during the transport movement, such as trucks on a Roll-On/Roll-Off (RORO) ferry.
FirstArrivalEvent | [edi3:Event](#Event) | The first arrival event for this logistics transport movement.
CarriedGoodsCharacteristic | [edi3:GoodsCharacteristic](#GoodsCharacteristic) | Material characteristics of goods carried during this logistics transport movement.
ShipToShipEvent | [edi3:Event](#Event) | A ship to ship event for this logistics transport movement.
Event | [edi3:Event](#Event) | A transport event specified for this logistics transport movement.
CrewPerson | [edi3:TransportPerson](#TransportPerson) | A person who is a member of the crew of the means of transport used for this logistics transport movement.
SailingAdviceNotificationInformation | xsd:string | Sailing advice notification information, expressed as text, for this logistics transport movement.
BorderCrossingEvent | [edi3:Event](#Event) | A border crossing event for this logistics transport movement.
ReportedSecurityInformation | xsd:string | Reported security information, expressed as text, for this logistics transport movement.
ScheduledID | xsd:token | A unique identifier for this logistics transport movement, such as a voyage number, flight number, or trip number, as stated in a schedule.
ModeCode | xsd:token | The code specifying the mode, such as by air, sea, rail, road or inland waterway, for this logistics transport movement.
ConsignmentQuantity | xsd:decimal | The number of consignments in this logistics transport movement.
PilotageExemptionID | xsd:token | The identifier of a pilotage exemption for this logistics transport movement.
CargoDescription | xsd:string | The textual description of the cargo for this logistics transport movement.
TerminalOperator | [edi3:TradeParty](#TradeParty) | A terminal operator party for this logistics transport movement.
CallPurposeCode | xsd:token | A code specifying a call purpose for this logistics transport movement.
CrewListDocument | [edi3:Document](#Document) | The crew list document related to this logistics transport movement.
ExcessTransportService | [edi3:Service](#Service) | An excess transport service for this logistics transport movement.
BorderCrossingDateTime | xsd:dateTime | A date, time, date time or other date time value when this logistics transport movement crosses a border.
DangerousGoodsIndicator | xsd:boolean | The indication of whether or not dangerous goods are carried for this logistics transport movement.
TransportMovementPackageQuantity | xsd:decimal | The number of packages in this logistics transport movement.
LoadingInspectionInstructions | [edi3:TransportInstructions](#TransportInstructions) | Loading inspection instructions specified for this logistics transport movement.
NVOCCCarrier | [edi3:TradeParty](#TradeParty) | A Non-Vessel Operating Common Carrier (NVOCC) carrier party for this logistics transport movement.
TransportMovementTypeText | xsd:string | The type, as expressed as text, of the logistics transport movement.
UsedTransportMeans | [edi3:LogisticsTransportMeans](#LogisticsTransportMeans) | The means of transport used for this logistics transport movement.
TransportMovementSpecifiedInstructions | [edi3:HandlingInstructions](#HandlingInstructions) | Handling instructions specified for this logistics transport movement.
TransportMovementInformation | xsd:string | Information, expressed as text, for this logistics transport movement.
TransitDirectionCode | xsd:token | The code specifying the transit direction of this logistics transport movement.
UnloadingInspectionParty | [edi3:TradeParty](#TradeParty) | The inspection party for the unloading of this logistics transport movement.
CommodityConsolidator | [edi3:TradeParty](#TradeParty) | The commodity consolidator party for this logistics transport movement.
TransportMovementCarrierAgent | [edi3:TradeParty](#TradeParty) | The carrier agent trade party for this logistics transport movement.
InspectionParty | [edi3:TradeParty](#TradeParty) | An inspection party for this logistics transport movement.
StayID | xsd:token | The unique identifier of a stay in a port, airport or other place of service for this logistics transport movement.
DocumentaryInstructionsNotifiedParty | [edi3:TradeParty](#TradeParty) | A party to be notified of the documentary instructions for this logistics transport movement.
LiftingInstructions | [edi3:Document](#Document) | A referenced lifting instructions document related to this logistics transport movement.
ServiceCode | xsd:token | The code specifying the service of this logistics transport movement, such as regular, milk run or spot service.
ClosingDateTime | xsd:dateTime | The date, time, date time, or other date time value by which cargo should be loaded onto the means of transport for the departure of this logistics transport movement.
Master | [edi3:TransportPerson](#TransportPerson) | The person legally responsible for the operation of the means of transport used for this logistics transport movement.
TransportMovementNotifiedParty | [edi3:TradeParty](#TradeParty) | A party to be notified about this logistics transport movement.
TransportMovementManifestDocument | [edi3:Document](#Document) | A referenced manifest document related to this transport movement.
CrewPersonalEffects | [edi3:PersonalEffects](#PersonalEffects) | Personal effects of an individual member of the crew for this logistics transport movement.
TransportMovementName | xsd:string | The name, expressed as text, for this logistics transport movement.
OnboardPerson | [edi3:TransportPerson](#TransportPerson) | A person onboard this logistics transport movement.
TransportMeansSecurityOfficerPerson | [edi3:TransportPerson](#TransportPerson) | The officer responsible for the security of the means of transport used for this logistics transport movement.
ItineraryRoute | [edi3:Route](#Route) | A route in the itinerary of this logistics transport movement.
ReportedWasteMaterial | [edi3:TransportWasteMaterial](#TransportWasteMaterial) | Waste material reported for this logistics transport movement.
PassengerNationalityCountry | [edi3:Country](#Country) | Passenger nationality details for this logistics transport movement.
DepartureEvent | [edi3:Event](#Event) | A departure event during this logistics transport movement.
ApplicableRegulatoryProcedure | [edi3:RegulatoryProcedure](#RegulatoryProcedure) | A cross-border regulatory procedure applicable to this logistics transport movement.


<h1 id="Convoy">Convoy</h1>

Type: rdf:Class

Description: A number of means of transport following each other with a common logistics purpose.

Properties: 

name | type | description
-|-|-
OverallLength | xsd:decimal | The overall length measure of this logistics convoy.
PowerActiveTransportMeans | [edi3:LogisticsTransportMeans](#LogisticsTransportMeans) | A means of transport actively powering this logistics convoy.
MaximumWidth | xsd:decimal | The maximum width measure for this logistics convoy.
NumberOfTransportMeans | xsd:decimal | The number of means of transport in this logistics convoy.


<h1 id="Polygon">Polygon</h1>

Type: rdf:Class

Description: A planar surface, defined by one exterior boundary and zero or more interior boundaries. Each interior boundary defines a hole in the polygon.

Properties: 

name | type | description
-|-|-
InteriorLinearRing | [edi3:LinearRing](#LinearRing) | An interior linear ring specified for this polygon.
ExteriorLinearRing | [edi3:LinearRing](#LinearRing) | The exterior linear specified ring for this polygon.
PolygonAssociatedLogisticsLocation | [edi3:LogisticsLocation](#LogisticsLocation) | A logistics location associated with this specified polygon.


<h1 id="PaymentBalanceOut">PaymentBalanceOut</h1>

Type: rdf:Class

Description: Offset information to ensure that debits and credits are equal for a transaction.

Properties: 

name | type | description
-|-|-
PaymentBalanceOutID | xsd:token | The identifier for this payment balance out.
PaymentBalanceOutDescription | xsd:string | A textual description of this payment balance out.
PaymentBalanceOutCalculatedAmount | xsd:decimal | A monetary value calculated for this payment balance out.
PaymentBalanceOutReasonCode | xsd:token | The code specifying the reason for this payment balance out.
PaymentBalanceOutReasonDescription | xsd:string | A textual description of the reason for this payment balance out.


<h1 id="HeaderBalanceOut">HeaderBalanceOut</h1>

Type: rdf:Class

Description: Offset header information to ensure that debits and credits are equal for a transaction.

Properties: 

name | type | description
-|-|-
HeaderBalanceOutReasonCode | xsd:token | The code specifying the reason for this header balance out.
HeaderBalanceOutReasonDescription | xsd:string | A textual description of the reason for this header balance out.
HeaderBalanceOutCalculatedAmount | xsd:decimal | A monetary value calculated for this header balance out.
BreakdownBalanceOut | [edi3:HeaderBalanceOut](#HeaderBalanceOut) | A balance out breakdown of this header balance out.
HeaderBalanceOutOccurrenceDateTime | xsd:dateTime | The date, time, date time, or other date time value of an occurrence of this header balance out.
HeaderBalanceOutDescription | xsd:string | A textual description of this header balance out.


<h1 id="Route">Route</h1>

Type: rdf:Class

Description: A way or course taken from one location to another for the purpose of transporting cargo and or passengers.

Properties: 

name | type | description
-|-|-
RouteStatusCode | xsd:token | The code specifying a status for a transport route, such as planned or actual.
SpecifiedPeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The specified period during which this transport route is scheduled.
FrequencyTypeCode | xsd:token | The code specifying the type of frequency for this transport route, such as weekly, bi-monthly or daily.
ItineraryStopEvent | [edi3:Event](#Event) | An itinerary stop event for this transport route, such as a port call in a vessel schedule.
RouteSecurityLevelCode | xsd:token | A code specifying a security level for this transport route.
DeparturePointText | xsd:string | A departure point, expressed as text, for this transport route.
MapBinaryObject | xsd:base64Binary | Binary object data that is the map of this transport route.
RouteDescription | xsd:string | The textual description of this transport route.
RouteTypeText | xsd:string | A type, expressed as text for this transport route.
TransportMeansText | xsd:string | A means of transport, expressed as text, for this transport route.
FrequencyEffectivePeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | A specified period of time for which a frequency is effective for this transport route.


<h1 id="CountrySubDivision">CountrySubDivision</h1>

Type: rdf:Class

Description: A political or physical area or region within the political boundaries of a country used or referenced for trade purposes.

Properties: 

name | type | description
-|-|-
SuperordinateCountrySubDivision | [edi3:CountrySubDivision](#CountrySubDivision) | A superordinate country sub-division for this trade country sub-division.
CountrySubDivisionName | xsd:string | A name, expressed as text, of this trade country sub-division.
AuthorizedActivityParty | [edi3:TradeParty](#TradeParty) | A party that is authorized to perform an activity in this trade country sub-division.
SubordinateCountrySubDivision | [edi3:CountrySubDivision](#CountrySubDivision) | A subordinate country sub-division within this trade country sub-division.
FunctionTypeCode | xsd:token | The code specifying the function type of this trade country sub-division.
HierarchicalLevelCode | xsd:token | The code specifying the hierarchical level of this trade country sub-division.


<h1 id="GoodsCharacteristic">GoodsCharacteristic</h1>

Type: rdf:Class

Description: A distinctive feature of a material contained within physical goods.

Properties: 

name | type | description
-|-|-
GoodsCharacteristicTypeCode | xsd:token | The code specifying the type of material goods characteristic.
ConstituentPercent | xsd:decimal | The percentage presence of the material within the goods for this material goods characteristic.
AbsolutePresenceVolume | xsd:decimal | The volume measure of the absolute presence of this material goods characteristic.
GoodsCharacteristicDescription | xsd:string | A textual description of this material goods characteristic.


<h1 id="Circle">Circle</h1>

Type: rdf:Class

Description: A planar surface specified as one completely round flat shape in the mathematical sense.

Properties: 

name | type | description
-|-|-
CircleGeographicalObjectCharacteristic | [edi3:GeographicalObjectCharacteristic](#GeographicalObjectCharacteristic) | The geographical object characteristic associated with this specified circle.
RadiusMeasure | xsd:decimal | The measure of the radius for this specified circle.
CircleAssociatedLogisticsLocation | [edi3:LogisticsLocation](#LogisticsLocation) | A logistics location associated with this specified circle.


<h1 id="TestSpecificationReport">TestSpecificationReport</h1>

Type: rdf:Class

Description: A report that specifies a certification test and its attributes.

Properties: 

name | type | description
-|-|-
ResultText | xsd:string | A result, expressed as text, reported in this certification test specification report.
StandardName | xsd:string | The name, expressed as text, of the standard applicable for this certification test specification report.


<h1 id="Characteristic">Characteristic</h1>

Type: rdf:Class

Description: A prominent attribute or aspect of a product.

Properties: 

name | type | description
-|-|-
CharacteristicValueMeasure | xsd:decimal | A measure of a value for this product characteristic.
CharacteristicValueCode | xsd:token | The code specifying the value of this product characteristic.
ValueBinaryFile | [edi3:BinaryFile](#BinaryFile) | The value for this product characteristic expressed in a binary file.
ApplicableCondition | [edi3:Condition](#Condition) | A condition applicable to this product characteristic.
MeasurementMethodCode | xsd:token | A code specifying a measurement method for this product characteristic.
ContentTypeCode | xsd:token | A code specifying the content type of this product characteristic.
CharacteristicTypeCode | xsd:token | A code specifying a type of product characteristic.
CharacteristicValueText | xsd:string | A value, expressed as text, for this product characteristic.
ValueDateTime | xsd:dateTime | The value for this product characteristic expressed as a date, time, date time, or other date time value.
CharacteristicDescription | xsd:string | A textual description of this product characteristic.
ValueIndicator | xsd:boolean | The value for this product characteristic expressed as an indicator.
CharacteristicApplicableReferencedStandard | [edi3:Standard](#Standard) | The referenced standard that is applicable to this product characteristic.


<h1 id="AvailablePeriod">AvailablePeriod</h1>

Type: rdf:Class

Description: A specific period of time such as the length of time between two known date/time points, from a start date onwards, or up to an end date for which something is available.

Properties: 

name | type | description
-|-|-
AvailablePeriodStartDateTime | xsd:dateTime | The date, time, date time or other date time value for the start of this available period of time.
AvailablePeriodDescription | xsd:string | The textual description of this available period.


<h1 id="SpecifiedPeriod">SpecifiedPeriod</h1>

Type: rdf:Class

Description: A specified period of time.

Properties: 

name | type | description
-|-|-
OpenIndicator | xsd:boolean | The indication of whether or not an entity is open during this specified period.
SpecifiedPeriodStartDateTime | xsd:dateTime | The date, time, date time or other date time value for the start of this specified period of time.
SpecifiedPeriodSequenceNumber | xsd:decimal | A sequence number for this specified period.
SpecifiedPeriodEndDateTime | xsd:dateTime | The date, time, date time or other date time value for the end of this specified period of time.
DurationMeasure | xsd:decimal | A measure of the length of time for this specified time period such as hours, days, weeks, months, years.
SpecifiedPeriodID | xsd:token | The unique identifier of this specified period.
ContinuousIndicator | xsd:boolean | The indication of whether or not this specified period is continuous.
SpecifiedPeriodDescription | xsd:string | A textual description of this specified period of time.
SpecifiedPeriodPurposeCode | xsd:token | The code specifying the purpose of this specified period.
SpecifiedPeriodName | xsd:string | A name, expressed as text, of this specified period.
InclusiveIndicator | xsd:boolean | The indication of whether or not the start and end dates are included in this specified period.
StartDateFlexibilityCode | xsd:token | The code specifying the flexibility of the start date of this specified period.
SpecifiedPeriodSeasonCode | xsd:token | The code specifying the season for this specified period.


<h1 id="SubordinateTradeLineItem">SubordinateTradeLineItem</h1>

Type: rdf:Class

Description: A collection of information specific to a subordinate item being used or reported on for trade purposes.

Properties: 

name | type | description
-|-|-
ReferencedProduct | [edi3:Product](#Product) | The referenced product specified for this subordinate trade line item.
SubordinateLineTradeDelivery | [edi3:SubordinateLineTradeDelivery](#SubordinateLineTradeDelivery) | The delivery specified for this subordinate trade line item.
SubordinateLineTradeSettlement | [edi3:SubordinateLineTradeSettlement](#SubordinateLineTradeSettlement) | A trade settlement specified for this subordinate trade line item.
ApplicableProduct | [edi3:TradeProduct](#TradeProduct) | A product applicable for this subordinate trade line item.
SubordinateTradeLineItemID | xsd:token | A unique identifier for this subordinate trade line item.


<h1 id="SupplyChainTradeLineItem">SupplyChainTradeLineItem</h1>

Type: rdf:Class

Description: A collection of information specific to an item being used or reported on for supply chain trade purposes.

Properties: 

name | type | description
-|-|-
SpecifiedGoodsProduction | [edi3:Production](#Production) | A production of goods specified for this supply chain trade line Item.
SupplyChainTradeLineItemID | xsd:token | The unique identifier for this supply chain trade line item.
TypeExtensionCode | xsd:token | The code used as an extension to the type code for further specifying a type of supply chain trade line item.
SupplyChainTradeLineItemTypeCode | xsd:token | The code specifying the type of supply chain trade line item.
SubstituteProduct | [edi3:Product](#Product) | A referenced substitute product applicable for this supply chain trade line item.
InvoiceReferencedDocument | [edi3:Document](#Document) | An invoice document associated to this supply chain trade line item.
SupplyChainTradeLineItemReferencedDocument | [edi3:Document](#Document) | A document referenced for this supply chain trade line item.
LineTradeDelivery | [edi3:LineTradeDelivery](#LineTradeDelivery) | The line trade delivery specified for this supply chain trade line item.
BarcodeID | xsd:token | A unique barcode identifier for this supply chain trade line item.
AssertedAuthentication | [edi3:Authentication](#Authentication) | A document authentication asserted for this supply chain trade line item.
SupplyChainTradeLineItemLogisticsPackage | [edi3:Package](#Package) | A physical logistics package for this supply chain trade line item.
LineTradeSettlement | [edi3:LineTradeSettlement](#LineTradeSettlement) | A line trade settlement specified for this supply chain trade line item.
SupplyChainTradeLineItemAssociatedDocumentLine | [edi3:DocumentLineDocument](#DocumentLineDocument) | The document line associated with this trade line item.
LineTradeAgreement | [edi3:LineTradeAgreement](#LineTradeAgreement) | The line trade agreement specified for this supply chain trade line item.
SupplyChainTradeLineItemTransportEquipment | [edi3:TransportEquipment](#TransportEquipment) | A piece of transport equipment associated with this supply chain trade line item.
AdditionalID | xsd:token | An additional unique identifier for this supply chain trade line item.
SupplyChainTradeLineItemTradeProduct | [edi3:TradeProduct](#TradeProduct) | A product specified for this supply chain trade line item.
SupplyChainSupplyChainSupplyChainTradeLineItemReferencedLogisticsPackage | [edi3:Package](#Package) | A logistics package referenced in this supply chain trade line item.
SupplyChainSupplyChainSupplyChainTradeLineItemReferencedLogisticsPackage | [edi3:ReferencedPackage](#ReferencedPackage) | A physical logistics package referenced for this supply chain trade line item.
SupplyChainTradeLineItemSequenceNumber | xsd:decimal | A sequence number for this supply chain trade line item.
SubstitutedProduct | [edi3:Product](#Product) | A referenced product substituted for this supply chain trade line item.
IncludedWithinConsignmentItem | [edi3:ConsignmentItem](#ConsignmentItem) | The consignment item within which this supply chain trade line item is included.
ComponentProduct | [edi3:Product](#Product) | A referenced component product applicable for this supply chain trade line item.
ComplementaryProduct | [edi3:Product](#Product) | A referenced complementary product applicable for this supply chain trade line item.
IncludedSubordinateTradeLineItem | [edi3:SubordinateTradeLineItem](#SubordinateTradeLineItem) | A subordinate trade line item included in this supply chain trade line item.
AdditionalProduct | [edi3:Product](#Product) | A referenced product additionally applicable with this supply chain trade line item.
AccessoryProduct | [edi3:Product](#Product) | A referenced accessory product applicable for this supply chain trade line item.
SupplyChainTradeLineItemDescriptionCode | xsd:token | The code specifying a description of this supply chain trade line item.
RequiredProduct | [edi3:Product](#Product) | A required product applicable for this supply chain trade line item.
SpecifiedRequisitionerTradeProduct | [edi3:TradeProduct](#TradeProduct) | The product specified by the requisitioner for this supply chain trade line item.


<h1 id="Range">Range</h1>

Type: rdf:Class

Description: A row, line or series, commonly used to express the difference between lowest and highest values.

Properties: 

name | type | description
-|-|-
StartID | xsd:token | The identifier of the start of this specified range.
RangeTypeCode | xsd:token | The code specifying a type of this specified range.
MaximumValueMeasure | xsd:decimal | The measure of the maximum value for this specified range.
TotalItemQuantity | xsd:decimal | The total number of items in this specified range.
MinimumValueMeasure | xsd:decimal | The measure of the minimum value for this specified range.


<h1 id="Certification">Certification</h1>

Type: rdf:Class

Description: The process of certifying that a certain product has passed performance and quality assurance tests, or qualification requirements stipulated in regulations.

Properties: 

name | type | description
-|-|-
ResponsibleAgencyText | xsd:string | The agency, expressed as text, responsible for this trade product certification.
StandardText | xsd:string | The standard, expressed as text, for this trade product certification.
AssertionText | xsd:string | An assertion, expressed as text, for this trade product certification, such as that this product is free from peanuts.


<h1 id="InstalmentPayment">InstalmentPayment</h1>

Type: rdf:Class

Description: A discharge of obligations in respect of funds or securities, transferred through one of several payments, between two or more parties.

Properties: 

name | type | description
-|-|-
SpecifiedFinancingRequestResultDocument | [edi3:FinancingRequestResultDocument](#FinancingRequestResultDocument) | The financing request result document specified for this instalment payment.
InstalmentPaymentDueDateTime | xsd:dateTime | The due date for this instalment payment.
SequenceID | xsd:token | The sequence identifier for this instalment payment.


<h1 id="TradeSettlementPayment">TradeSettlementPayment</h1>

Type: rdf:Class

Description: The specific discharge obligations in respect of funds or securities transferred between two or more parties as part of a trade settlement.

Properties: 

name | type | description
-|-|-
EndToEndID | xsd:token | The unique identifier for the end-to-end processing of this trade settlement payment, such as an identifier assigned by an initiating party to unambiguously identify the transaction.
SpecifiedPaymentTradeSettlement | [edi3:PaymentTradeSettlement](#PaymentTradeSettlement) | A trade settlement payment specified for this trade settlement payment.
InstructionID | xsd:token | The unique identifier of the instruction for this trade settlement payment.
RequestedExecutionDateTime | xsd:dateTime | The date, time, date time or other date time value of the requested execution of this trade settlement payment.


<h1 id="AdvancePayment">AdvancePayment</h1>

Type: rdf:Class

Description: A prepaid discharge of obligations in respect of funds or securities transferred between two or more parties.

Properties: 

name | type | description
-|-|-
AdvancePaymentPaidAmount | xsd:decimal | The monetary value of the funds or securities paid in this advance payment.
AdvancePaymentIncludedTax | [edi3:TradeTax](#TradeTax) | A tax included in this advance payment.


<h1 id="PaymentTradeSettlement">PaymentTradeSettlement</h1>

Type: rdf:Class

Description: The information that enables the reconciliation of a payment with the item(s) that the payment is intended to settle, for example a commercial invoice.

Properties: 

name | type | description
-|-|-
PaymentTradeSettlementPaymentCurrencyExchange | [edi3:CurrencyExchange](#CurrencyExchange) | The currency exchange applicable to this payment trade settlement.
PaymentMonetarySummation | [edi3:TradeSettlementPaymentMonetarySummation](#TradeSettlementPaymentMonetarySummation) | The monetary summation totals specified for this payment trade settlement.
PaymentTradeSettlementSpecifiedPaymentMeans | [edi3:PaymentMeans](#PaymentMeans) | The payment means specified for this payment trade settlement.
PaymentTradeSettlementAdditionalDescription | xsd:string | The description, expressed as text, of additional information supplied to enable the matching of an entry with the items that the payment is intended to settle.
PaymentTradeSettlementPayee | [edi3:TradeParty](#TradeParty) | The payee party for this payment trade settlement.
PaymentTradeSettlementPayer | [edi3:TradeParty](#TradeParty) | The payer party for this payment trade settlement.
ApplicableTax | [edi3:TradeTax](#TradeTax) | The tax applicable to this payment trade settlement.


<h1 id="LineTradeSettlement">LineTradeSettlement</h1>

Type: rdf:Class

Description: The information, at a line level, that enables the reconciliation of a financial transaction with the item(s) that the financial transaction is intended to settle, for example a commercial invoice.

Properties: 

name | type | description
-|-|-
LineTradeSettlementPayerReferenceText | xsd:string | The payer reference, expressed as text, for this line trade settlement.
LineTradeSettlementPaymentReferenceText | xsd:string | A payment reference, expressed as text, for this line trade settlement.
ReferencedLineTradeTransaction | [edi3:LineTradeTransaction](#LineTradeTransaction) | A trade transaction referenced in this line trade settlement.
DocumentLine | [edi3:DocumentLineDocument](#DocumentLineDocument) | A document line associated with this line trade settlement.
LineTradeSettlementAccountsReceivable | [edi3:AccountingAccount](#AccountingAccount) | A receivable accounting account specified for this line trade settlement.
LineTradeSettlementLogisticsServiceCharge | [edi3:ServiceCharge](#ServiceCharge) | A logistics service charge specified for this line trade settlement.
LineTradeSettlementAllowanceCharge | [edi3:TradeAllowanceCharge](#TradeAllowanceCharge) | An allowance or charge specified for this line trade settlement.
LineTradeSettlementDiscountIndicator | xsd:boolean | The indication of whether or not a discount applies to the item in this line trade settlement.
LineTradeSettlementPurchaseAccountingAccount | [edi3:AccountingAccount](#AccountingAccount) | A purchase accounting account specified for this line trade settlement.
LineTradeSettlementInvoiceDateTime | xsd:dateTime | The date, time, date time or other date time value of the invoice in this line trade settlement.
LineTradeSettlementSalesAccountingAccount | [edi3:AccountingAccount](#AccountingAccount) | A sales accounting account specified for this line trade settlement.
LineTradeSettlementTradeTax | [edi3:TradeTax](#TradeTax) | A tax applicable to this line trade settlement.
LineTradeSettlementAdditionalDocument | [edi3:Document](#Document) | An additional document referenced in this line trade settlement.
LineTradeSettlementSubtotalCalculatedTax | [edi3:TradeTax](#TradeTax) | A tax subtotal calculated for this line trade settlement.
LineTradeSettlementBillingPeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | A billing period specified for this line trade settlement.
LineTradeSettlementInvoicee | [edi3:TradeParty](#TradeParty) | The party to whom an invoice is issued for this line trade settlement.
LineTradeSettlementPayer | [edi3:TradeParty](#TradeParty) | The payer party for this line trade settlement.
LineTradeSettlementPriceCurrencyCode | xsd:token | The code specifying the price currency for this line trade settlement.
LineTradeSettlementFinancialAdjustment | [edi3:FinancialAdjustment](#FinancialAdjustment) | A financial adjustment specified for this line trade settlement.
LineTradeSettlementAssociatedDocument | [edi3:Document](#Document) | A document associated with this line trade settlement.
LineTradeSettlementInvoiceDocument | [edi3:Document](#Document) | An invoice document referenced in this line trade settlement.
LineTradeSettlementMonetarySummation | [edi3:TradeSettlementLineMonetarySummation](#TradeSettlementLineMonetarySummation) | The monetary summation totals specified for this line trade settlement.
LineTradeSettlementInvoiceIssuerReferenceText | xsd:string | The invoice issuer reference, expressed as text, for this line settlement.
LineTradeSettlementAccountsPayable | [edi3:AccountingAccount](#AccountingAccount) | A payable accounting account specified for this line trade settlement.
LineTradeSettlementTotalAdjustmentAmount | xsd:decimal | The monetary value of the total adjustment for this line trade settlement.
LineTradeSettlementFinancialCard | [edi3:FinancialCard](#FinancialCard) | A financial card specified in this line trade settlement.
LineTradeSettlementPaymentAmount | xsd:decimal | A monetary value of a payment for this line trade settlement.


<h1 id="SubordinateLineTradeSettlement">SubordinateLineTradeSettlement</h1>

Type: rdf:Class

Description: The information, at a subordinate line level, that enables the reconciliation of a financial transaction with the item(s) that the financial transaction is intended to settle, for example a commercial invoice.

Properties: 

name | type | description
-|-|-


<h1 id="HeaderTradeSettlement">HeaderTradeSettlement</h1>

Type: rdf:Class

Description: The information, at a header level, that enables the reconciliation of a financial transaction, with the item(s) that the financial transaction is intended to settle, such as a commercial invoice.

Properties: 

name | type | description
-|-|-
CreditorReferenceIssuerID | xsd:token | An identifier of the creditor reference issuer for this header trade settlement.
PaymentMeans | [edi3:PaymentMeans](#PaymentMeans) | A payment means specified for this header trade settlement.
ScheduledPaymentDateTime | xsd:dateTime | The date, time, date time or other date time value of the scheduled payment of this header trade settlement.
HeaderTradeSettlementInvoicee | [edi3:TradeParty](#TradeParty) | The party to whom an invoice is issued for this header trade settlement.
TaxCurrencyCode | xsd:token | The code specifying the tax currency for this header trade settlement.
HeaderTradeSettlementPaymentReferenceText | xsd:string | A payment reference, expressed as text, for this header trade settlement.
HeaderTradeSettlementLetterOfCreditDocument | [edi3:Document](#Document) | The letter of credit document referenced in this header trade settlement.
RequestedFinancingAmount | xsd:decimal | A financing monetary value requested for this header trade settlement.
HeaderTradeSettlementSubtotalCalculatedTax | [edi3:TradeTax](#TradeTax) | A tax subtotal calculated for this header trade settlement.
NextInvoiceDateTime | xsd:dateTime | A date, time, date time or other date time value of a next invoice or invoices in this header trade settlement.
ProFormaInvoiceDocument | [edi3:Document](#Document) | The pro-forma invoice document referenced by this header trade settlement.
HeaderTradeSettlementRelevantParty | [edi3:TradeParty](#TradeParty) | A relevant party for this header trade settlement.
CreditorReferenceID | xsd:token | The identifier of the creditor reference for this header trade settlement, such as a specific identifier assigned by the creditor to reference the financial transaction.
HeaderTradeSettlementInvoiceIssuerReferenceText | xsd:string | The invoice issuer reference, expressed as text, for this header trade settlement.
HeaderTradeSettlementTradeTax | [edi3:TradeTax](#TradeTax) | A tax applicable to this header trade settlement.
HeaderTradeSettlementInvoiceDateTime | xsd:dateTime | The date, time, date time or other date time value of the invoice in this header trade settlement.
QuotationCurrencyCode | xsd:token | The code specifying the quotation currency for this header trade settlement.
CreditorReferenceTypeText | xsd:string | A creditor reference type, expressed as text, for this header trade settlement.
HeaderTradeSettlementPaymentCurrencyExchange | [edi3:CurrencyExchange](#CurrencyExchange) | The currency exchange applicable to the payment in this header trade settlement.
CreditReasonText | xsd:string | A textual description of the reason for a credit being given in this header trade settlement.
HeaderTradeSettlementDescription | xsd:string | A textual description of this header trade settlement.
CreditNoteAmount | xsd:decimal | A monetary value of the credit note for this header trade settlement.
FactoringListDocument | [edi3:Document](#Document) | A factoring list document referenced in this header trade settlement.
PaymentInstalmentPlan | [edi3:InstalmentPlan](#InstalmentPlan) | The payment instalment plan specified for this header trade settlement.
HeaderTradeSettlementInvoiceDocument | [edi3:Document](#Document) | An invoice document referenced by this header trade settlement.
HeaderTradeSettlementPaymentCurrencyCode | xsd:token | The code specifying the payment currency for this header trade settlement.
HeaderTradeSettlementInvoiceCurrencyExchange | [edi3:CurrencyExchange](#CurrencyExchange) | The currency exchange applicable to the invoice in this header trade settlement.
HeaderTradeSettlementFinancialCard | [edi3:FinancialCard](#FinancialCard) | A financial card specified in this header trade settlement.
DebitNoteAmount | xsd:decimal | A monetary value of the debit note for this header trade settlement.
HeaderTradeSettlementPayerReferenceText | xsd:string | The payer reference, expressed as text, for this header trade settlement.
FactoringAgreementDocument | [edi3:Document](#Document) | A factoring agreement document referenced in this header trade settlement.
HeaderTradeSettlementPaymentAmount | xsd:decimal | A monetary value of a payment for this header trade settlement.
HeaderTradeSettlementSalesAccountingAccount | [edi3:AccountingAccount](#AccountingAccount) | A sales accounting account specified for this header trade settlement.
HeaderTradeSettlementAccountsReceivable | [edi3:AccountingAccount](#AccountingAccount) | A receivable accounting account specified for this header trade settlement.
QuotationCurrencyExchange | [edi3:CurrencyExchange](#CurrencyExchange) | The currency exchange applicable to the quotation currency in this header trade settlement.
HeaderTradeSettlementDiscountIndicator | xsd:boolean | The indication of whether or not this header trade settlement includes a discount amount.
OrderCurrencyExchange | [edi3:CurrencyExchange](#CurrencyExchange) | The currency exchange applicable to the order currency in this header trade settlement.
HeaderTradeSettlementPurchaseAccountingAccount | [edi3:AccountingAccount](#AccountingAccount) | A purchase accounting account specified for this header trade settlement.
UltimatePayee | [edi3:TradeParty](#TradeParty) | An ultimate payee party in this header trade settlement.
HeaderTradeSettlementClosingBookDueDateTime | xsd:dateTime | The date, time, date time or other date time value when the book closing is due for this header trade settlement.
HeaderTradeSettlementAllowanceCharge | [edi3:TradeAllowanceCharge](#TradeAllowanceCharge) | An allowance or charge specified for this header trade settlement.
HeaderTradeSettlementBillingPeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | A billing period specified for this header trade settlement.
RequestedFinancingRate | xsd:decimal | The financing rate, expressed as a percentage, requested for this header trade settlement.
HeaderTradeSettlementPaymentTerms | [edi3:PaymentTerms](#PaymentTerms) | Payment terms specified for this header trade settlement.
HeaderTradeSettlementAccountsPayable | [edi3:AccountingAccount](#AccountingAccount) | A payable accounting account specified for this header trade settlement.
HeaderTradeSettlementPriceCurrencyCode | xsd:token | The code specifying the price currency for this header trade settlement.
HeaderTradeSettlementTotalAdjustmentAmount | xsd:decimal | A monetary value of the total adjustment for this header trade settlement.
PriceCurrencyExchange | [edi3:CurrencyExchange](#CurrencyExchange) | The currency exchange applicable to the price in this header trade settlement.
HeaderTradeSettlementMonetarySummation | [edi3:TradeSettlementHeaderMonetarySummation](#TradeSettlementHeaderMonetarySummation) | The monetary summation totals specified for this header trade settlement.
HeaderTradeSettlementTotalInvoiceAmount | xsd:decimal | A monetary value of the total invoice on which this header trade settlement is calculated.
CreditorReferenceTypeCode | xsd:token | A code specifying the creditor reference type for this header trade settlement.
HeaderTradeSettlementFinancialAdjustment | [edi3:FinancialAdjustment](#FinancialAdjustment) | A financial adjustment specified for this header trade settlement.
HeaderTradeSettlementLogisticsServiceCharge | [edi3:ServiceCharge](#ServiceCharge) | A logistics service charge specified for this header trade settlement.
HeaderTradeSettlementDuePayableAmount | xsd:decimal | A monetary value that is an exact amount due and payable for this header trade settlement, such as the amount due to the creditor.
OrderCurrencyCode | xsd:token | The code specifying the currency of the order for this header trade settlement.
AdvancePayment | [edi3:AdvancePayment](#AdvancePayment) | An advance payment specified in this header trade settlement.
InvoiceCurrencyCode | xsd:token | The code specifying the invoice currency for this header trade settlement.
Invoicer | [edi3:TradeParty](#TradeParty) | The party issuing the invoice for this header trade settlement.
HeaderTradeSettlementPayer | [edi3:TradeParty](#TradeParty) | The payer party for this header trade settlement.
HeaderTradeSettlementPayee | [edi3:TradeParty](#TradeParty) | A payee party for this header trade settlement.
CreditReasonCode | xsd:token | The code specifying the reason for a credit being given in this header trade settlement.


<h1 id="ReferencePrice">ReferencePrice</h1>

Type: rdf:Class

Description: A reference to a sum of money for which something is or may be bought or sold.

Properties: 

name | type | description
-|-|-
ReferencePriceChargeAmount | xsd:decimal | The monetary value of a charged reference price.
ReferencePriceBasisQuantity | xsd:decimal | A quantity on which the reference price is based.
ComparisonMethodCode | xsd:token | The code specifying the comparison method for this reference price.


<h1 id="CalculatedPrice">CalculatedPrice</h1>

Type: rdf:Class

Description: Information related to a calculated price.

Properties: 

name | type | description
-|-|-
CalculatedPriceTypeCode | xsd:token | A code specifying the type of calculated price.
CalculatedPriceAppliedAllowanceCharge | [edi3:AppliedAllowanceCharge](#AppliedAllowanceCharge) | Applied allowance charge information related to this calculated price.


<h1 id="TradePrice">TradePrice</h1>

Type: rdf:Class

Description: A sum of money for which something is or may be bought or sold for trade purposes.

Properties: 

name | type | description
-|-|-
TradePriceTypeText | xsd:string | A type, expressed as text, for this trade price.
MaximumQuantity | xsd:decimal | The maximum quantity in a range for which the trade price applies.
TradePriceChargeAmount | xsd:decimal | A monetary value of the trade price charge.
TradePriceAssociatedDocument | [edi3:Document](#Document) | An associated document referenced for this trade price.
UnitAmount | xsd:decimal | A monetary value of the unit of this trade price.
ChangeReasonText | xsd:string | A reason, expressed as text, for a change of this trade price.
TradeComparisonPrice | [edi3:ReferencePrice](#ReferencePrice) | A price that provides a trade comparison with this trade price.
TradePriceAppliedAllowanceCharge | [edi3:TradeAllowanceCharge](#TradeAllowanceCharge) | An allowance or charge applied to the trade price.
DeliveryLocation | [edi3:TradeLocation](#TradeLocation) | A delivery location for this trade price.
TradePriceIncludedTax | [edi3:TradeTax](#TradeTax) | A tax included in this trade price.
TradePriceTypeCode | xsd:token | The code specifying the type of trade price.
OrderUnitConversionFactor | xsd:decimal | The value used as the factor to convert the order unit into the price unit for this trade price.
TradePriceBasisQuantity | xsd:decimal | The quantity on which the trade price is based.
TradePriceValidityPeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | A specified period for which this trade price is valid.


<h1 id="SupplyPlan">SupplyPlan</h1>

Type: rdf:Class

Description: Specification of the delivery time and quantity bucket in a supply chain demand forecast or delivery schedule.

Properties: 

name | type | description
-|-|-
SynchronizationQuantity | xsd:decimal | The value specifying the quantity for a synchronization of this supply chain supply plan.
SupplyPlanConfirmedDeliveryEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | A confirmed delivery event in this supply chain supply plan.
SupplyPlanContractDocument | [edi3:Document](#Document) | A referenced contract document for this supply chain supply plan.
SynchronizationDateTime | xsd:dateTime | A date, time, date time, or other date time value of a synchronization of the supply chain supply plan.
MinusToleranceQuantity | xsd:decimal | The minus tolerance quantity from the planned or requested quantity in this supply chain supply plan.
SupplyPlanApplicablePeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The period applicable for this supply chain supply plan.
PlannedQuantity | xsd:decimal | The planned quantity in this supply chain supply plan.
SupplyPlanDeliveryNoteDocument | [edi3:Document](#Document) | A delivery note document referenced by this supply chain supply plan.
ScheduledDeliveryEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | A scheduled delivery event in this supply chain supply plan.
SupplyPlanDeliveryEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | A delivery event for this supply chain supply plan.
PlusToleranceQuantity | xsd:decimal | The plus tolerance quantity from the planned or requested quantity in this supply chain supply plan.
SupplyPlanShipToParty | [edi3:TradeParty](#TradeParty) | The ship to trade party for this supply chain supply plan.
SupplyPlanActualQuantity | xsd:decimal | The actual quantity in this supply chain supply plan.
SupplyPlanCommitmentLevelCode | xsd:token | The code specifying the commitment level for this supply chain supply plan, such as fabrication or raw material.
ToleranceQuantity | xsd:decimal | The quantity of tolerance from the planned quantity in this supply chain supply plan.


<h1 id="Observation">Observation</h1>

Type: rdf:Class

Description: A specified act or instance of viewing or noting a fact or occurrence for some scientific or other special purpose.

Properties: 

name | type | description
-|-|-
ObservationDescription | xsd:string | The textual description for this specified observation.
ObservationApplicableNote | [edi3:Note](#Note) | A note providing information applicable to this specified observation.
ObservationID | xsd:token | The identifier for this specified observation.


<h1 id="Packaging">Packaging</h1>

Type: rdf:Class

Description: Any material with which supply chain goods are packaged, such as a box or bubble wrap.

Properties: 

name | type | description
-|-|-
PackagingInstructionCode | xsd:token | A code specifying an instruction for this supply chain packaging.
PackagingConditionCode | xsd:token | A code specifying the condition of this supply chain packaging.
ContentLayerQuantity | xsd:decimal | The number of content layers that are or may be packaged with this supply chain packaging, such as the number of layers of product on a pallet.
PackagingMaximumStackabilityWeight | xsd:decimal | The measure of the maximum stackability weight of this supply chain packaging.
AdditionalInstructionIndicator | xsd:boolean | The indication of whether or not there is an additional instruction for this supply chain packaging.
PackagingDimensions | [edi3:SpatialDimension](#SpatialDimension) | The linear spatial dimensions of this supply chain packaging.
PackagingReturnableIndicator | xsd:boolean | The indication of whether or not this supply chain packaging is returnable.
TotalUnitQuantity | xsd:decimal | A total number of units contained in this supply chain packaging.
PackagingTypeCode | xsd:token | The code specifying the type of supply chain packaging.
ReturnableAssetInstructions | [edi3:ReturnableAssetInstructions](#ReturnableAssetInstructions) | Returnable asset instructions for this supply chain packaging.
PackagingWeight | xsd:decimal | A measure of the weight of this supply chain packaging.
PackagingDescription | xsd:string | A textual description of this supply chain packaging.
AdditionalInstructionCode | xsd:token | A code specifying an additional instruction for this supply chain packaging.
LayerTotalUnitQuantity | xsd:decimal | The total number of units in a layer of this supply chain packaging.
PackagingMaximumStackabilityQuantity | xsd:decimal | The number of units of this type of supply chain packaging which can be stacked on top of each other.
DisposalMethodCode | xsd:token | A code specifying the disposal method of this supply chain packaging.
Marking | [edi3:Marking](#Marking) | A marking specified for this supply chain packaging, such as an inscription, stamp or label to indicate date, ownership, quality, manufacture or origin.
PackagingMaximumDimensions | [edi3:SpatialDimension](#SpatialDimension) | The maximum linear spatial dimensions of this supply chain packaging.
PackagingTypeText | xsd:string | The type, expressed as text, of supply chain packaging.
GoodsCharacteristic | [edi3:GoodsCharacteristic](#GoodsCharacteristic) | Material goods characteristic applicable to this supply chain packaging.
CustomerFacingTotalUnitQuantity | xsd:decimal | The total number of units of this supply chain packaging facing the customer, such as would be seen when this packaging is placed on a retail shelf.
PackagingMinimumDimensions | [edi3:SpatialDimension](#SpatialDimension) | The minimum linear spatial dimensions of this supply chain packaging.


<h1 id="Certificate">Certificate</h1>

Type: rdf:Class

Description: A collection of data for a piece of written, printed or electronic matter that provides information or evidence about the product.

Properties: 

name | type | description
-|-|-
IssuingPartyID | xsd:token | The identifier for the party issuing this product certificate.
ActualEffectiveDateTime | xsd:dateTime | The actual effective date, time, date time or other date time value for this product certificate.
CertificateIssueDateTime | xsd:dateTime | The date, time, date time, or other date time value when this product certificate was issued.
RequestedEffectiveDateTime | xsd:dateTime | The requested effective date, time, date time or other date time value for this product certificate.
CertificateDescription | xsd:string | A textual description of this product certificate.
CertificateID | xsd:token | The identifier for this product certificate.
CertificateTypeCode | xsd:token | A code specifying the type of product certificate.
ApplicableObjectCode | xsd:token | A code specifying an object, such as item, animal, person or organization applicable for this product certificate.
CertificateExpiryDateTime | xsd:dateTime | The date, time, date time, or other date time value when this product certificate expires.
IssueReasonCode | xsd:token | The code specifying the reason why this product certificate was issued.


<h1 id="Sensor">Sensor</h1>

Type: rdf:Class

Description: An object which can detect and measure physical properties and which can record, indicate and transmit such measurements.

Properties: 

name | type | description
-|-|-
SensorOwnerParty | [edi3:TradeParty](#TradeParty) | The owner party of this monitoring sensor.
SensorPositionCode | xsd:token | The code specifying a position of this monitoring sensor.
SensorManufacturerParty | [edi3:TradeParty](#TradeParty) | The manufacturer party for this monitoring sensor.
SensorID | xsd:token | An identifier of this monitoring sensor.
SensorRemainingBatteryChargePercent | xsd:decimal | The percentage of the remaining battery charge of this monitoring sensor.
ReportedScheduledCalibratedMeasurement | [edi3:CalibratedMeasurement](#CalibratedMeasurement) | A scheduled calibrated measurement reported for this monitoring sensor.
DefinedControlSettingParameter | [edi3:ControlSettingParameter](#ControlSettingParameter) | A control setting parameter defined for this monitoring sensor.
DefinedOperationalParameter | [edi3:OperationalParameter](#OperationalParameter) | An operational parameter defined for this monitoring sensor.
SensorGrantedProductCertificate | [edi3:Certificate](#Certificate) | A product certificate granted for this monitoring sensor.
SensorTypeCode | xsd:token | The code specifying a type of monitoring sensor.
ReportedActualCalibratedMeasurement | [edi3:CalibratedMeasurement](#CalibratedMeasurement) | An actual calibrated measurement reported for this monitoring sensor.
PrecisionCalibratedMeasurement | [edi3:CalibratedMeasurement](#CalibratedMeasurement) | A calibrated measurement of precision for this monitoring sensor.


<h1 id="IOTDevice">IOTDevice</h1>

Type: rdf:Class

Description: An IOT (Internet of Things) piece of mechanical or electronic equipment which can collect, report and autonomously transmit digital data.

Properties: 

name | type | description
-|-|-
IOTDeviceTypeCode | xsd:token | The code specifying the type of monitoring IOT device.
IOTDevicePositionCode | xsd:token | The code specifying the position of this monitoring IOT device.
CommunicationCapabilityCode | xsd:token | The code specifying the communication capability of this monitoring IOT device.
LatestReceivedSignalDateTime | xsd:dateTime | The date, time, date time or other date time value of the latest received signal for this monitoring IOT device, from the perspective of the receiver.
LatestReceivedGeographicalCoordinate | [edi3:GeographicalCoordinate](#GeographicalCoordinate) | The latest geographical coordinates received by this monitoring IOT device, from the perspective of the receiver.
IOTDeviceGrantedProductCertificate | [edi3:Certificate](#Certificate) | A product certificate granted for this monitoring IOT device.
IOTDeviceRemainingBatteryChargePercent | xsd:decimal | The percentage of the remaining battery charge of this monitoring IOT device.
OEMInterfaceEquipment | [edi3:Equipment](#Equipment) | An interface between an OEM (Original Equipment Manufacturer) equipment and this monitoring IOT device.
EmbeddedSensor | [edi3:Sensor](#Sensor) | An embedded sensor of this monitoring IOT device.
IOTDeviceOwnerParty | [edi3:TradeParty](#TradeParty) | The owner party of this monitoring IOT device.
RemoteSensor | [edi3:Sensor](#Sensor) | A remote sensor of this monitoring IOT device.
PowerSourceTypeCode | xsd:token | The code specifying a type of power source for this monitoring IOT device.
IOTDeviceOperationalStatusCode | xsd:token | The code specifying the operational status, such as broken, stolen, unpaired, inactive of this monitoring IOT device.
ReportedTransportEvent | [edi3:Event](#Event) | A transport event reported by this monitoring IOT device.
ProviderParty | [edi3:TradeParty](#TradeParty) | The provider party for this monitoring IOT device.
IOTDeviceManufacturerParty | [edi3:TradeParty](#TradeParty) | The manufacturer party of this monitoring IOT device.
AttachedAssetID | xsd:token | The identifier for the asset, such as a container, to which this monitoring IOT device is attached.
OperatorParty | [edi3:TradeParty](#TradeParty) | The operator party, such as terminal operator, service provider, network operator of this monitoring IOT device.
ReportingSensorCommunicationPairing | [edi3:Pairing](#Pairing) | A sensor communication pairing reported for this monitoring IOT device.
IOTDeviceID | xsd:token | An identifier for this monitoring IOT device.


<h1 id="CalibratedMeasurement">CalibratedMeasurement</h1>

Type: rdf:Class

Description: A measurement established by a device which is tested to a calibration standard of known accuracy.

Properties: 

name | type | description
-|-|-
CalibratedMeasurementValueCode | xsd:token | The code specifying a value for this calibrated measurement.
CalibratedMeasurementToleranceMeasure | xsd:decimal | The measure of the tolerance of this calibrated measurement.
CalibratedMeasurementID | xsd:token | The identifier for this calibrated measurement.
CalibratedMeasurementVersionID | xsd:token | The identifier of a version of this calibrated measurement.
QuantificationTypeCode | xsd:token | The code specifying a quantification type for this calibrated measurement, such as measured, calculated, or estimated.
TolerancePercent | xsd:decimal | The percent of tolerance of this calibrated measurement.


<h1 id="Measurement">Measurement</h1>

Type: rdf:Class

Description: An amount, size, or extent as established by measuring.

Properties: 

name | type | description
-|-|-
MeasurementTypeCode | xsd:token | A code specifying a type of measurement.
MeasurementDescription | xsd:string | A textual description of this measurement.
ActualMeasure | xsd:decimal | An actual measure for this measurement.
MethodText | xsd:string | A measurement method expressed as text.
ConditionMeasure | xsd:decimal | A measure of a condition for this measurement.


<h1 id="TransportSettingTemperature">TransportSettingTemperature</h1>

Type: rdf:Class

Description: Temperature settings for a transport movement, such as a required storage temperature range.

Properties: 

name | type | description
-|-|-
TransportSettingTemperatureValue | xsd:decimal | The measure of the value of this transport setting temperature, such as a temperature value of ten degrees Celsius.
TransportSettingTemperatureMinimumValue | xsd:decimal | The measure of the lowest value of this transport setting temperature, such as a minimum temperature value of four degrees Celsius.
Instructions | [edi3:TemperatureSettingInstructions](#TemperatureSettingInstructions) | Informational instructions for achieving, maintaining, using or responding to this transport setting temperature.
TransportSettingTemperatureMaximumValue | xsd:decimal | The measure of the highest value of this transport setting temperature, such as a maximum temperature value of fourteen degrees Celsius.


<h1 id="InstructedTemperature">InstructedTemperature</h1>

Type: rdf:Class

Description: Temperature settings instructed for storage or movement of goods.

Properties: 

name | type | description
-|-|-
InstructedTemperatureMinimumValue | xsd:decimal | The measure of the minimum value of this instructed temperature.


<h1 id="SpecifiedTemperature">SpecifiedTemperature</h1>

Type: rdf:Class

Description: A specified temperature value or range of values.

Properties: 

name | type | description
-|-|-
SpecifiedTemperatureMinimumValue | xsd:decimal | The measure of the lowest value of a range for this specified temperature, such as a minimum temperature value of four degrees Celsius.
SpecifiedTemperatureMaximumValue | xsd:decimal | The measure of the highest value of a range for this specified temperature, such as a maximum temperature value of fourteen degrees Celsius.


<h1 id="Emission">Emission</h1>

Type: rdf:Class

Description: A calculation of the pollution (including noise, heat, and radiation etc.) discharged into the environment by a residential, commercial, or industrial facility or by a means of transport, such as a vessel, aircraft or truck.

Properties: 

name | type | description
-|-|-
PollutionMeasure | xsd:decimal | A measure of the pollution calculated for this emission.
EmissionWeight | xsd:decimal | A weight for which this calculated emission is measured.
AffectedDistanceMeasure | xsd:decimal | The affected distance over which this calculated emission is measured.


<h1 id="Standard">Standard</h1>

Type: rdf:Class

Description: A referenced norm or requirement that establishes uniform criteria, methods, processes and practices, such as in engineering or technical areas.

Properties: 

name | type | description
-|-|-
StandardURI | xsd:token | The Uniform Resource Identifier (URI) for this referenced standard.
PartID | xsd:token | The identifier of a part of this referenced standard, such as a section or topic.
ElementVersionID | xsd:token | The identifier of the version of a specific element within the referenced standard, such as the version of a data element.
AgencyID | xsd:token | The identifier of the agency for this referenced standard.
StandardVersionID | xsd:token | The identifier of the version of this referenced standard.


<h1 id="PaymentTerms">PaymentTerms</h1>

Type: rdf:Class

Description: Terms and conditions by which payment has been or will be made for trade purposes.

Properties: 

name | type | description
-|-|-
PaymentTermsInstructionCode | xsd:token | A code specifying an instruction for these trade payment terms.
PartialPaymentPercent | xsd:decimal | A partial payment, expressed as a percent, in these trade payment terms.
PaymentTermsDescription | xsd:string | A textual description of these trade payment terms.
SettlementPeriodMeasure | xsd:decimal | The measure of the number of settlement periods from this trade payment term time reference to the latest payment date, such as 30 days, 3 months.
PaymentTermsID | xsd:token | The unique identifier of these trade payment terms.
PaymentTermsDueDateTime | xsd:dateTime | The date, time, date time, or other date time value of the due date specified by these trade payment terms.
DirectDebitMandateID | xsd:token | An identifier of a direct debit mandate in these trade payment terms.
PaymentPenaltyTerms | [edi3:PaymentPenaltyTerms](#PaymentPenaltyTerms) | Trade payment penalty terms applicable to these trade payment terms.
InstructionTypeCode | xsd:token | A code specifying a type of instruction for these trade payment terms.
TradePaymentMeansID | xsd:token | An identifier of a payment means in these trade payment terms.
PaymentDiscountTerms | [edi3:PaymentDiscountTerms](#PaymentDiscountTerms) | Trade payment discount terms applicable to these trade payment terms.
PaymentTermsPayee | [edi3:TradeParty](#TradeParty) | A payee party in these trade payment terms.
FromEventCode | xsd:token | The code specifying the event from which these trade payment terms are offered for a length of time.
DeprecatedDueDateDateTime | xsd:dateTime | The date, time, date time, or other date time value for a due date specified by these trade payment terms.
PaymentTermsTypeCode | xsd:token | A code specifying the type of trade payment terms.


<h1 id="GeographicalFeature">GeographicalFeature</h1>

Type: rdf:Class

Description: Representation of real world phenomenon associated with a location relative to the Earth, such as cities, buildings, roads, rivers, forests and lakes.

Properties: 

name | type | description
-|-|-
GeographicalFeatureName | xsd:string | The name, expressed as text, of this specified geographical feature.
CollectionIndicator | xsd:boolean | The indication of whether or not this specified geographical feature is a collection of features.
GeographicalFeatureUsedCSEngineeringCoordinateReferenceSystem | [edi3:CSEngineeringCoordinateReferenceSystem](#CSEngineeringCoordinateReferenceSystem) | The CS (Coordinate System) engineering coordinate reference system used for this specified geographical feature.
GeographicalFeatureGeographicalLine | [edi3:GeographicalLine](#GeographicalLine) | The geographical line included in this geographical feature.
GeographicalFeatureUsedGeographicalCoordinateSourceSystem | [edi3:CoordinateSourceSystem](#CoordinateSourceSystem) | The geographical coordinate source system used for this specified geographical feature.
IncludedCircle | [edi3:Circle](#Circle) | A circle included in this specified geographical feature.
GeographicalMultiCurve | [edi3:GeographicalMultiCurve](#GeographicalMultiCurve) | The geographical multi-curve included in this geographical feature.
GeographicalFeaturePolygon | [edi3:Polygon](#Polygon) | The polygon included in this geographical feature.
GeographicalFeatureID | xsd:token | The identifier for this specified geographical feature.
GeographicalGrid | [edi3:GeographicalGrid](#GeographicalGrid) | The geographical grid included in this geographical feature.
GeographicalSurface | [edi3:GeographicalSurface](#GeographicalSurface) | The geographical surface included in this geographical feature.
GeographicalFeatureGeographicalPoint | [edi3:GeographicalPoint](#GeographicalPoint) | The geographical point included in this geographical feature.
GeographicalFeatureDescription | xsd:string | The textual description of this specified geographical feature.
GeographicalMultiPoint | [edi3:GeographicalMultiPoint](#GeographicalMultiPoint) | The geographical multi-point included in this geographical feature.
GeographicalMultiSurface | [edi3:GeographicalMultiSurface](#GeographicalMultiSurface) | The geographical multi-surface included in this geographical feature.


<h1 id="Segment">Segment</h1>

Type: rdf:Class

Description: The parts into which a segment is or may be divided.

Properties: 

name | type | description
-|-|-
SegmentID | xsd:token | The identifier of this section segment.
ImageBinaryObject | xsd:base64Binary | The image, expressed as a binary object, for this section segment.
SegmentInformationText | xsd:string | Information, expressed as text, in this section segment.


<h1 id="ConsignmentItem">ConsignmentItem</h1>

Type: rdf:Class

Description: An item within a supply chain consignment of goods separately identified for transport and customs purposes.

Properties: 

name | type | description
-|-|-
ConsignmentItemApplicableNote | [edi3:Note](#Note) | A note providing information applicable to this supply chain consignment item.
ConsignmentItemHandlingInstructions | [edi3:HandlingInstructions](#HandlingInstructions) | Handling instructions for this supply chain consignment item.
ConsignmentItemDestinationCountry | [edi3:Country](#Country) | The destination country for this supply chain consignment item.
ConsignmentItemCrossBorderRegulatoryProcedure | [edi3:RegulatoryProcedure](#RegulatoryProcedure) | A cross-border regulatory procedure applicable to this supply chain consignment item.
ServiceCharge | [edi3:ServiceCharge](#ServiceCharge) | A logistics service charge applicable to this supply chain consignment item.
ConsignmentItemOriginGeopoliticalRegion | [edi3:GeopoliticalRegion](#GeopoliticalRegion) | The geopolitical region of origin for this supply chain consignment item.
ConsignmentItemNetWeight | xsd:decimal | A measure of the net weight (mass) of this supply chain consignment item which excludes all packaging.
ConsignmentItemDamageRemark | xsd:string | Damage remarks, expressed as text, for this supply chain consignment item.
ConsignmentItemInsuranceValueAmount | xsd:decimal | The monetary value of this supply chain consignment item as covered by an insurance policy.
ConsignmentItemCargoToleranceInformation | xsd:string | Cargo tolerance information, expressed as text, for this supply chain consignment item.
SecondTypeExtensionCode | xsd:token | The code used as a second extension to the type code for further specifying the type of supply chain consignment item.
ConsignmentItemDeliveryEvent | [edi3:Event](#Event) | The delivery event for this supply chain consignment item.
ConsignmentItemFOBAmount | xsd:decimal | The monetary value for this supply chain consignment item as calculated under FOB (Free On Board) delivery terms.
ConsignmentItemDeclaredValueForCustomsAmount | xsd:decimal | The monetary value of this supply chain consignment item as declared for customs purposes.
ConsignmentItemTransportPackage | [edi3:Package](#Package) | A transport package for this supply chain consignment item.
ConsignmentItemBorderClearanceInstructions | [edi3:TransportInstructions](#TransportInstructions) | Border clearance instructions for this supply chain consignment item.
ConsignmentItemShippingMarks | [edi3:ShippingMarks](#ShippingMarks) | Physical logistics shipping marks and barcode information for this supply chain consignment item.
ConsignmentItemTransportDangerousGoods | [edi3:DangerousGoods](#DangerousGoods) | Dangerous goods transport details applicable to this supply chain consignment item.
ConsignmentItemDespatchParty | [edi3:TradeParty](#TradeParty) | The party from whom this supply chain consignment item will be or has been despatched.
ConsignmentItemGrossWeight | xsd:decimal | A measure of the gross weight (mass) of this supply chain consignment item which includes packaging but excludes any transport equipment.
ImportTypeCode | xsd:token | The code specifying the import type of supply chain consignment item.
ConsignmentItemPackageTypeText | xsd:string | A package type, expressed as text, for this supply chain consignment item.
ConsignmentItemDeclaredValueForCarriageAmount | xsd:decimal | The monetary value of this supply chain consignment item as declared by the shipper or his agent for the purpose of varying the carrier's level of liability from that provided in the contract of carriage, in case of loss or damage to goods or delayed delivery.
NationalTypeExtensionCode | xsd:token | The code used as a national extension to the type code for further specifying the type of supply chain consignment item.
InvoiceAmount | xsd:decimal | A monetary value for an invoice for this supply chain consignment item.
FirstTypeExtensionCode | xsd:token | The code used as a first extension to the type code for further specifying the type of supply chain consignment item.
ConsignmentItemCustomsValuation | [edi3:CustomsValuation](#CustomsValuation) | A customs valuation applicable to this supply chain consignment item.
ConsignmentItemPreviousAdministrativeDocument | [edi3:Document](#Document) | A previous administrative referenced document for this supply chain consignment item.
ConsignmentItemDimensions | [edi3:SpatialDimension](#SpatialDimension) | The linear spatial dimensions of this supply chain consignment item.
ConsignmentItemQuarantineInstructions | [edi3:QuarantineInstructions](#QuarantineInstructions) | Quarantine instructions for this supply chain consignment item.
ConsignmentItemCargoNatureIdentification | [edi3:Cargo](#Cargo) | Transport cargo details of this supply chain consignment item sufficient to identify its nature for customs, statistical or transport purposes.
ConsignmentItemTotalExportExitToImportEntryChargeAmount | xsd:decimal | The monetary value of the total charge or charges of freight, insurance and other services for this supply chain consignment item calculated from the export exit location to the import entry location.
ConsignmentItemGoodsTypeExtensionCode | xsd:token | The code used as an extension to the type code for further specifying the type of supply chain consignment item.
ConsignmentItemAssociatedTransportEquipment | [edi3:ReferencedTransportEquipment](#ReferencedTransportEquipment) | A referenced piece of transport equipment associated with this supply chain consignment item.
ImportationCountry | [edi3:Country](#Country) | The importation country for this supply chain consignment item.
ConsignmentItemExportCountry | [edi3:Country](#Country) | The export country for this supply chain consignment item.
ConsignmentItemTradeLineItemQuantity | xsd:decimal | The number of trade line items in this supply chain consignment item.
ConsignmentItemDeclaredForCustomsLocation | [edi3:LogisticsLocation](#LogisticsLocation) | The location of this supply chain consignment item as declared for customs.
ConsignmentItemGrossVolume | xsd:decimal | A measure of the gross volume, normally calculated by multiplying the maximum length, width and height of this supply chain consignment item.
ConsignmentItemTransportContractDocument | [edi3:Document](#Document) | A transport contract document for this supply chain consignment item.
ConsignmentItemVanningEvent | [edi3:Event](#Event) | The vanning event for this supply chain consignment item, i.e. the loading of this consignment item at the place of original despatch.
ConsignmentItemChargeableWeight | xsd:decimal | A measure of the supply chain consignment item weight on which charges are to be based.
TransportTemperatureSetting | [edi3:TransportSettingTemperature](#TransportSettingTemperature) | The transport temperature setting for this supply chain consignment item.
ConsignmentItemSpecialInstructions | xsd:string | Special instructions, expressed as text, for this supply chain consignment item.
ExportTypeCode | xsd:token | The code specifying the export type of supply chain consignment item.
ConsignmentItemDeliveryInstructions | xsd:string | Delivery instructions, expressed as text, for this supply chain consignment item.
ConsignmentItemAssociatedDocument | [edi3:Document](#Document) | A referenced document associated with this supply chain consignment item.
ConsignmentItemLoadingLength | xsd:decimal | The measure of the loading length of this supply chain consignment item.
ConsignmentItemSequenceNumber | xsd:decimal | The sequence number for this supply chain consignment item.
ConsignmentItemManufacturer | [edi3:TradeParty](#TradeParty) | The party which manufactured this supply chain consignment item.
ConsignmentItemDeliveryParty | [edi3:TradeParty](#TradeParty) | The party to whom this supply chain consignment item will be or has been delivered.
ConsignmentItemPackageQuantity | xsd:decimal | The package quantity for this supply chain consignment item.
ConsignmentItemInformation | xsd:string | Information, expressed as text, for this supply chain consignment item.
ConsignmentItemID | xsd:token | A unique identifier for this supply chain consignment item.
ConsignmentItemGoodsTypeCode | xsd:token | The code specifying the type of supply chain consignment item.
TransportMeans | [edi3:LogisticsTransportMeans](#LogisticsTransportMeans) | The means of transport applicable to this supply chain consignment item.
ConsignmentItemTradeLineItem | [edi3:SupplyChainTradeLineItem](#SupplyChainTradeLineItem) | A trade line item included in this supply chain consignment item.
ConsignmentItemReportedLogisticsStatus | [edi3:LogisticsStatus](#LogisticsStatus) | A logistics status reported for this supply chain consignment item.
ConsignmentItemTariffQuantity | xsd:decimal | The tariff quantity in this supply chain consignment item.
ConsignmentItemExportGeopoliticalRegion | [edi3:GeopoliticalRegion](#GeopoliticalRegion) | The geopolitical region of export for this supply chain consignment item.
DeclaredValueForStatisticsAmount | xsd:decimal | The monetary value of this supply chain consignment item as declared for statistical purposes.
ConsignmentItemExaminationEvent | [edi3:Event](#Event) | An examination event for this supply chain consignment item.
ConsignmentItemTotalChargeAmount | xsd:decimal | The monetary value of all freight and other service charges for this supply chain consignment item.
ConsignmentItemTransitCountry | [edi3:Country](#Country) | A transit country for this supply chain consignment item.
ConsignmentItemPickUpEvent | [edi3:Event](#Event) | A pick-up transport event for this supply chain consignment item.
ConsignmentItemGlobalID | xsd:token | A global identifier for this supply chain consignment item.


<h1 id="ReferencedConsignmentItem">ReferencedConsignmentItem</h1>

Type: rdf:Class

Description: A reference to an item within a supply chain consignment of goods separately identified for transport and customs purposes.

Properties: 

name | type | description
-|-|-
ReferencedConsignmentItemCargoNatureIdentification | [edi3:Cargo](#Cargo) | Transport cargo details of this referenced supply chain consignment item sufficient to identify its nature for customs, statistical or transport purposes.
ReferencedConsignmentItemSequenceNumber | xsd:decimal | The sequence number for this referenced supply chain consignment item.
ReferencedConsignmentItemTradeLineItem | [edi3:SupplyChainTradeLineItem](#SupplyChainTradeLineItem) | A trade line item included in this referenced supply chain consignment item.
ReferencedConsignmentItemTradeLineItemQuantity | xsd:decimal | The number of trade line items in this referenced supply chain consignment item.
ReferencedConsignmentItemGoodsTypeCode | xsd:token | The code specifying the type of referenced supply chain consignment item.
ReferencedConsignmentItemTransportPackage | [edi3:Package](#Package) | A transport package for this referenced supply chain consignment item.
ReferencedConsignmentItemAssociatedTransportEquipment | [edi3:ReferencedTransportEquipment](#ReferencedTransportEquipment) | A piece of transport equipment associated with this referenced supply chain consignment item.
ReferencedConsignmentItemTransportDangerousGoods | [edi3:DangerousGoods](#DangerousGoods) | Dangerous goods transport details applicable to this referenced supply chain consignment item.
ReferencedConsignmentItemGoodsTypeExtensionCode | xsd:token | The code used as an extension to the type code for further specifying the type of referenced supply chain consignment item.
ReferencedConsignmentItemAssociatedDocument | [edi3:Document](#Document) | A referenced document associated with this referenced supply chain consignment item.


<h1 id="ServiceCharge">ServiceCharge</h1>

Type: rdf:Class

Description: A charge made for a logistics related service.

Properties: 

name | type | description
-|-|-
AppliedAmount | xsd:decimal | A monetary value applied to this logistics service charge.
ServiceChargeSpecifiedPaymentMeans | [edi3:PaymentMeans](#PaymentMeans) | The trade settlement payment means specified for this logistics service charge.
AppliedFromLocation | [edi3:LogisticsLocation](#LogisticsLocation) | The start location from which this logistics service charge should be applied.
CalculationBasisText | xsd:string | The basis, expressed as text, on which this logistics service charge is to be calculated, such as by volume or per unit.
ChargeCategoryCode | xsd:token | The code specifying the category of charge for this logistics service charge.
AllowanceChargeText | xsd:string | The allowance or charge, expressed as text, for this logistics service charge.
PaymentPlace | [edi3:LogisticsLocation](#LogisticsLocation) | The location of the place of payment of this logistics service charge.
CalculationBasisCode | xsd:token | The code specifying a basis on which this logistics service charge is to be calculated, such as by volume or per unit.
TariffClassCode | xsd:token | The code specifying the tariff class for this logistics service charge which represents an entry in a table of fixed charges [Reference United Nations Code List (UNCL) 5243].
DisbursementAmount | xsd:decimal | A monetary value of a disbursement for this logistics service charge.
ServiceCategoryCode | xsd:token | The code specifying the category of service for this logistics service charge.
AppliedToLocation | [edi3:LogisticsLocation](#LogisticsLocation) | The end location at which this logistics service charge is no longer to be applied.
ServiceChargeDescription | xsd:string | A textual description of this logistics service charge.
ServiceChargePaymentArrangementCode | xsd:token | The code specifying the payment arrangement for this logistics service charge [Reference United Nations Code List (UNCL) 4237].
PayingPartyRoleCode | xsd:token | The code specifying the role of the party responsible for paying this logistics service charge.
FreightInvoiceTypeCode | xsd:token | A code specifying a type of freight invoice of this logistics service charge.
ServiceChargeCategoryCode | xsd:token | The code specifying the category of this logistics service charge [Reference United Nations Code List (UNCL) 5237].
TransportPaymentMethodCode | xsd:token | The code specifying the transport payment method for this logistics service charge.
ServiceChargeID | xsd:token | The unique identifier for this logistics service charge.


<h1 id="SecurityTag">SecurityTag</h1>

Type: rdf:Class

Description: A product tag device to provide protection from a peril such as theft.

Properties: 

name | type | description
-|-|-
SecurityTagTypeCode | xsd:token | The code specifying the type of this product security tag.


<h1 id="Declaration">Declaration</h1>

Type: rdf:Class

Description: A collection of data for a piece of written, printed or electronic matter that is exchanged between two parties as a formal declaration.

Properties: 

name | type | description
-|-|-
StatisticalValueAmount | xsd:decimal | The monetary value specified for statistical purposes in this exchanged declaration.
Declarant | [edi3:TradeParty](#TradeParty) | The trade party acting as the declarant for this exchanged declaration.
DeclarantAgent | [edi3:TradeParty](#TradeParty) | The trade party acting as an agent for the declarant for this exchanged declaration.
DeclarationGrossWeight | xsd:decimal | The gross weight measure specified in this exchanged declaration.
AdditionalStatement | [edi3:Note](#Note) | An additional statement note for this exchanged declaration.
ProcedureCode | xsd:token | A code specifying a procedure for this exchanged declaration.
DeclarationReferencedDocument | [edi3:Document](#Document) | A referenced document associated with this exchanged declaration.
TotalPackageQuantity | xsd:decimal | The total package quantity specified in this exchanged declaration.
DeclarationFormattedIssueDateTime | xsd:dateTime | The date, time, date time or other date time value for the issuance of this exchanged declaration.
DeclarationTotalInvoiceAmount | xsd:decimal | The total invoice monetary value specified in this exchanged declaration.
DeclarationID | xsd:token | An identifier for this exchanged declaration.
FormattedJurisdictionEntryDateTime | xsd:dateTime | The date, time, date time or other date time value when the items which are a subject of this exchanged declaration enter a jurisdiction, such as the actual date of arrival of a means of transport.
DeclarationVersionID | xsd:token | The identifier for the version of this exchanged declaration.
CrossBorderCustomsValuation | [edi3:CustomsValuation](#CustomsValuation) | Customs valuation information applicable to this exchanged declaration.
SpecificCircumstanceCode | xsd:token | The code specifying a specific circumstance in this exchanged declaration.
CurrencyExchangeRate | xsd:decimal | The rate of currency exchange in this exchanged declaration.
DeclarationPreviousReferencedDocument | [edi3:Document](#Document) | A previous document referenced for this exchanged declaration.
DeclarationTypeCode | xsd:token | The code specifying the type of this exchanged declaration.
SubmissionLogisticsLocation | [edi3:LogisticsLocation](#LogisticsLocation) | The submission location for this exchanged declaration.
AssociatedPrincipalParty | [edi3:TradeParty](#TradeParty) | A principal trade party associated with this exchanged declaration.


<h1 id="DangerousGoods">DangerousGoods</h1>

Type: rdf:Class

Description: Goods which may contain a substance which poses risks to people and/or the environment during transportation which is regulated by dangerous goods regulations.

Properties: 

name | type | description
-|-|-
PollutantIndicator | xsd:boolean | The indication of whether or not these transported dangerous goods have a pollutant content.
LowerPartOrangeHazardPlacardID | xsd:token | The unique lower part of the orange hazard placard identifier for these transported dangerous goods.
TREMID | xsd:token | The unique TRansport EMergency (TREM) card identifier for these transported dangerous goods.
HazardTypeCode | xsd:token | A code specifying the type of hazard for these transported dangerous goods.
RegulatoryAuthorityName | xsd:string | The name, expressed as text, for the regulatory authority for these transported dangerous goods.
ReportableQuantity | xsd:decimal | The reportable quantity for these transported dangerous goods.
SupplementaryInformation | xsd:string | Supplementary information, expressed as text, concerning the transport of these dangerous goods.
DangerousGoodsGrossWeight | xsd:decimal | The measure of the weight (mass) of these transported dangerous goods including packaging but excluding the transport equipment.
ExplosiveCargoNetWeight | xsd:decimal | The measure of the explosive cargo weight applicable to these transported dangerous goods.
DangerousGoodsMarkingText | xsd:string | Marking, expressed as text, for these transported dangerous goods.
ExplosiveCompatibilityGroupCode | xsd:token | The code specifying the explosive compatibility group for these transported dangerous goods.
ControlTemperature | [edi3:Measurement](#Measurement) | The measurement of the control temperature of these transported dangerous goods.
MFAGID | xsd:token | The unique Medical First Aid Guide (MFAG) identifier for these transported dangerous goods.
PackingInstructionTypeCode | xsd:token | The code specifying a type of packing instruction for these transported dangerous goods.
OverpackInformation | xsd:string | Overpack information, expressed as text, for these transported dangerous goods.
PackagingDangerLevelCode | xsd:token | The code specifying the level of danger that the packaging of these dangerous goods must cover for transport purposes.
UpperPartOrangeHazardPlacardID | xsd:token | The unique upper part of the orange hazard placard identifier for these transported dangerous goods.
EMSID | xsd:token | The unique transport emergency procedure (EMS) identifier applicable for these transported dangerous goods.
EmergencyTemperature | [edi3:Measurement](#Measurement) | The measurement of the emergency temperature of these transported dangerous goods.
HazardCategoryCode | xsd:token | The code specifying the hazard category for these transported dangerous goods.
DangerousGoodsGrossVolume | xsd:decimal | The measure of the gross volume, normally calculated by multiplying the maximum length, width and height dimensions of these transported dangerous goods.
PollutantLevelCode | xsd:token | The code specifying the level of pollution of these transported dangerous goods.
UNDGID | xsd:token | The code specifying the unique United Nations Dangerous Goods (UNDG) number assigned to these transported dangerous goods.
DangerousGoodsLogisticsPackage | [edi3:Package](#Package) | A logistics package specified for these transported dangerous goods.
DangerousGoodsNetWeight | xsd:decimal | The measure of the net weight (mass) of these transported dangerous goods.
AuthorizationInformation | xsd:string | Authorization information, expressed as text, for these transported dangerous goods.
RegulationCode | xsd:token | The code specifying a regulation applicable to these transported dangerous goods.
SpecialProvisionID | xsd:token | The unique identifier of the special provision for these transported dangerous goods.
TechnicalName | xsd:string | A technical name, expressed as text, for these transported dangerous goods.
AllPackedInOneInformation | xsd:string | All packed in one information, expressed as text, for these transported dangerous goods.
IMDGSegregationGroupCode | xsd:token | The code specifying the IMDG (International Maritime Dangerous Goods regulation) segregation group for these transported dangerous goods.
HazardClassVersionID | xsd:token | The unique identifier of the version of a hazard class for these transported dangerous goods.
TransportExpertContact | [edi3:Contact](#Contact) | The expert to be contacted for details about the transport of these dangerous goods.
TransportPackageTypeCode | xsd:token | The code specifying the package type for the transported dangerous goods.
TunnelRestrictionCode | xsd:token | The code specifying the tunnel restriction for these transported dangerous goods.
DangerousGoodsTransportEquipment | [edi3:ReferencedTransportEquipment](#ReferencedTransportEquipment) | Referenced transport equipment associated with the dangerous goods.
ProperShippingName | xsd:string | The proper shipping name, expressed as text, for these transported dangerous goods.
RadioactiveMaterial | [edi3:RadioactiveMaterial](#RadioactiveMaterial) | The radioactive material transported as dangerous goods.
HazardClassificationID | xsd:token | The unique identifier of a hazard class applicable to these transported dangerous goods as defined by the relevant governing regulation authority.
RegulationName | xsd:string | A name, expressed as text, for a regulation of these transported dangerous goods.
FlashpointTemperature | [edi3:Measurement](#Measurement) | A measurement of the flashpoint temperature of these transported dangerous goods.
DangerousGoodsHandlingInstructions | [edi3:HandlingInstructions](#HandlingInstructions) | Handling instructions for the transported dangerous goods.
QValueNumber | xsd:decimal | The number of the Q-Value for these transported dangerous goods.
MarinePollutantIndicator | xsd:boolean | The indication of whether or not these transported dangerous goods have a marine pollutant content.
AircraftLimitationInformation | xsd:string | Aircraft limitation information, expressed as text, for these transported dangerous goods.
EmergencyContact | [edi3:Contact](#Contact) | The person or department to be contacted in the event of any emergency related to these transported dangerous goods.
ShipperDeclarationInformation | xsd:string | Shipper declaration information, expressed as text, for these transported dangerous goods.
LimitedQuantityCode | xsd:token | A code specifying facilitations for transport of limited quantities of these transported dangerous goods.
AdditionalHazardClassificationID | xsd:token | The unique identifier of an additional hazard class applicable to these transported dangerous goods.
ComplianceDeclarationInformation | xsd:string | Compliance declaration information, expressed as text, for these transported dangerous goods.


<h1 id="QuantityAnalysis">QuantityAnalysis</h1>

Type: rdf:Class

Description: The quantity analysis for this work item.

Properties: 

name | type | description
-|-|-
ActualQuantityDimension | [edi3:WorkItemDimension](#WorkItemDimension) | A work item dimension of the actual quantity in this work item quantity analysis.
QuantityAnalysisPrimaryClassificationCode | xsd:token | A code specifying a primary classification value for this work item quantity analysis.
QuantityAnalysisContractualLanguageCode | xsd:token | The code specifying the contractual language for this work item quantity analysis.
QuantityAnalysisAlternativeClassificationCode | xsd:token | A code specifying an alternative classification value for this work item quantity analysis.
QuantityAnalysisTypeCode | xsd:token | The code specifying the type of work item quantity analysis.
QuantityAnalysisActualQuantity | xsd:decimal | The actual quantity for this work item quantity analysis.
QuantityAnalysisDeprecatedStatusCode | xsd:token | The code specifying the status of this work item quantity analysis, such as partial, approved, not approved.
QuantityAnalysisID | xsd:token | The unique identifier for this work item quantity analysis.
QuantityAnalysisDescription | xsd:string | The textual description of this work item quantity analysis.
QuantityAnalysisChangedRecordedStatus | [edi3:RecordedStatus](#RecordedStatus) | A changed recorded status for this work item quantity analysis.
ActualQuantityPercent | xsd:decimal | The percentage of a total quantity that the actual quantity of this work item quantity analysis represents.


<h1 id="CoordinateSourceSystem">CoordinateSourceSystem</h1>

Type: rdf:Class

Description: Properties defining a geographical coordinate source system used in different places around the world to identify locations on the earth.

Properties: 

name | type | description
-|-|-
CoordinateSourceSystemToleranceMeasure | xsd:decimal | The measure of the tolerance of this geographical coordinate source system.
SignalSourceAvailableQuantity | xsd:decimal | The quantity of signal source available for this geographical coordinate source system.
CoordinateSourceSystemTypeCode | xsd:token | The code specifying a type of source for this geographical coordinate source system.
CoordinateSourceSystemID | xsd:token | The identifier for this geographical coordinate source system.


<h1 id="Pairing">Pairing</h1>

Type: rdf:Class

Description: The process by which two potentially communicating entities are linked.

Properties: 

name | type | description
-|-|-
TargetEntityID | xsd:token | The identifier of the target entity for this communication pairing.
PairingMethodCode | xsd:token | The code specifying the method of this communication pairing.
PairedIndicator | xsd:boolean | The indication of whether or not the entity is paired in this communication pairing.


<h1 id="Condition">Condition</h1>

Type: rdf:Class

Description: A state that applies to a product characteristic.

Properties: 

name | type | description
-|-|-
ConditionName | xsd:string | A name, expressed as text, for this product characteristic condition.


<h1 id="ShippingMarks">ShippingMarks</h1>

Type: rdf:Class

Description: Physical markings or labels on individual packages or transport units for logistics purposes.

Properties: 

name | type | description
-|-|-
MarkingInstructionCode | xsd:token | A code specifying a marking instruction for these logistics shipping marks.
RFIDLabel | [edi3:Label](#Label) | A Radio Frequency Identification (RFID) label that is a part of these logistics shipping marks.
VINLabel | [edi3:Label](#Label) | A Vehicle Identification Number (VIN) label that is a part of these logistics shipping marks.
ShippingMarksMarkingText | xsd:string | Marking, expressed as text, for these logistics shipping marks.


<h1 id="Service">Service</h1>

Type: rdf:Class

Description: A service associated with a transport movement.

Properties: 

name | type | description
-|-|-
ServicePriorityCode | xsd:token | The code specifying the priority of this transport service.
ResponsibleParty | [edi3:TradeParty](#TradeParty) | A trade party responsible for this transport service.
ServiceURI | [edi3:UniversalCommunication](#UniversalCommunication) | The Uniform Resource Identifier (URI) communication for this transport service, such as its website or email address.
ServiceChargeAmount | xsd:decimal | The monetary value of the charge for this transport service.
ServiceRequester | [edi3:TradeParty](#TradeParty) | A trade party requesting this transport service.
ConditionTypeCode | xsd:token | A code specifying a type of condition for this transport service, such as a contract or carriage condition.
ServiceEffectivePeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | The specified period during which this transport service is effective.
ServiceName | xsd:string | The name, expressed as text, of this transport service.
ServiceCategoryTypeCode | xsd:token | A code specifying a type of category for this transport service.
ServiceDescription | xsd:string | The textual description of this transport service.
ServiceID | xsd:token | The unique identifier of this transport service.
SpecifiedRoute | [edi3:Route](#Route) | A transport route specified for this transport service.
ServiceInformationText | xsd:string | Information, expressed as text, for this transport service.
ServiceRequirementCode | xsd:token | A code specifying a service requirement for this transport service.


<h1 id="ReferencedService">ReferencedService</h1>

Type: rdf:Class

Description: A referenced service associated with a specified event during transport movement.

Properties: 

name | type | description
-|-|-
ContractID | xsd:token | The contract identifier of this referenced transport service.
ReferencedServiceID | xsd:token | An identifier of this referenced transport service.
ReferencedServiceCategoryTypeCode | xsd:token | A code specifying the category type of this referenced transport service.


<h1 id="TransportWasteMaterial">TransportWasteMaterial</h1>

Type: rdf:Class

Description: Any materials unused and rejected as unwanted during a transport movement.

Properties: 

name | type | description
-|-|-
NextDeliveryEvent | [edi3:Event](#Event) | A next delivery event for this transport waste material.
IncludedWasteMaterialComponent | [edi3:MaterialComponent](#MaterialComponent) | A material component included in this transport waste.
CompleteDeliveryIndicator | xsd:boolean | The indication of whether or not a transport waste material delivery is complete.
ReceptionFacilityContact | [edi3:Contact](#Contact) | A reception facility contact for this transport waste material.


<h1 id="RadioactiveMaterial">RadioactiveMaterial</h1>

Type: rdf:Class

Description: Material capable of undergoing spontaneous nuclear decay involving emission of ionizing radiation in the form of particles or gamma rays.

Properties: 

name | type | description
-|-|-
LowDispersibleInformation | xsd:string | Information, expressed as text, describing the low dispersion properties of this radioactive material.
RadioactiveMaterialTypeCode | xsd:token | The code specifying the type of this radioactive material.
TransportIndexNumber | xsd:decimal | The transport index number of this radioactive material.
CriticalitySafetyIndexNumber | xsd:decimal | The criticality safety index number of this radioactive material.
SpecialFormInformation | xsd:string | Information, expressed as text, describing the special form for this radioactive material.
FissileExceptionIndicator | xsd:boolean | The indication of whether or not this radioactive material is a fissile exception.
RadionuclideName | xsd:string | The name of the radionuclide, expressed as text, of this radioactive material.


<h1 id="Marking">Marking</h1>

Type: rdf:Class

Description: An inscription, stamp or label on packaging, such as to indicate date, ownership, quality, manufacture or origin.

Properties: 

name | type | description
-|-|-
ContentDateTime | xsd:dateTime | The date, time, date time or other date time value for the content of this packaging marking.
AutomaticDataCaptureMethodTypeCode | xsd:token | A code specifying an automatic data capture method type for this packaging marking.
MarkingTypeCode | xsd:token | A code specifying a type of packaging marking.
MarkingContentCode | xsd:token | Content, expressed as a code, of this packaging marking.
BarcodeTypeCode | xsd:token | A code specifying a type of barcode for this packaging marking.
ContentAmount | xsd:decimal | Content, expressed as a monetary amount, for this packaging marking.


<h1 id="CargoInsurance">CargoInsurance</h1>

Type: rdf:Class

Description: Insurance coverage for cargo during transport movements.

Properties: 

name | type | description
-|-|-
CoverageCode | xsd:token | The code specifying the coverage of this transport cargo insurance.
ContractGeneralConditionsText | xsd:string | The contract general conditions, expressed as text, for this transport cargo insurance.
CoverageDescription | xsd:string | The textual description of the coverage of this transport cargo insurance.


<h1 id="TransportMeans">TransportMeans</h1>

Type: rdf:Class

Description: Reference to a device or method used to convey people, goods, or other objects from place to place.

Properties: 

name | type | description
-|-|-
TransportMeansDriverAccompaniedIndicator | xsd:boolean | The indication of whether or not this referenced means of transport is accompanied by a driver.
TransportMeansID | xsd:token | An identifier of this referenced transport means, such as the International Maritime Organization number for a vessel.
TransportMeansName | xsd:string | The name, expressed as text, of this referenced transport means, such as the vessel name.
TransportMeansTypeCode | xsd:token | The code specifying the type of referenced transport means [Reference UNECE Recommendation 28].


<h1 id="LogisticsTransportMeans">LogisticsTransportMeans</h1>

Type: rdf:Class

Description: The devices used to convey goods or other objects from place to place during logistics cargo movements.

Properties: 

name | type | description
-|-|-
LogisticsTransportMeansManufacturerParty | [edi3:TradeParty](#TradeParty) | The manufacturer party for this logistics means of transport.
ServiceProvider | [edi3:TradeParty](#TradeParty) | A trade party providing services for this logistics means of transport.
LogisticsTransportMeansTypeCode | xsd:token | The code specifying the type of logistics means of transport (Reference UNECE Recommendation 28).
LogisticsTransportMeansSequenceNumber | xsd:decimal | The sequence number differentiating this logistics transport means from others.
ForwardDraughtLevelMeasure | xsd:decimal | The draught level measured at the fore end of this transport means.
LogisticsTransportMeansDriverAccompaniedIndicator | xsd:boolean | The indication of whether or not this logistics means of transport is accompanied by a driver.
OwnerAgent | [edi3:TradeParty](#TradeParty) | The owner agent trade party for this logistics means of transport.
LogisticsTransportMeansGrossWeight | xsd:decimal | The measure of the gross weight (mass) of this logistics means of transport including cargo, such as the measure of the overall size of a vessel determined in accordance with the provisions of the International Convention on Tonnage Measurement of Ships, 1969.
ConferenceCode | xsd:token | The code specifying the conference for this logistics means of transport.
CargoGrossWeight | xsd:decimal | The measure of the total gross weight (mass) of all cargo loaded onto this logistics means of transport, including packaging but excluding any associated transport equipment.
LogisticsTransportMeansApplicableServiceCharge | [edi3:ServiceCharge](#ServiceCharge) | A service charge, such as a freight charge, applicable to this logistics means of transport.
CertifiedCalculatedEmission | [edi3:Emission](#Emission) | A certified level of pollution calculated for an emission from this logistics transport means.
ISSCIssuingAuthorityParty | [edi3:TradeParty](#TradeParty) | The trade party authorized to issue the International Ship Security Certificate (ISSC) for this logistics means of transport.
OperatorNationalityCountry | [edi3:Country](#Country) | The country of nationality of the operator of this logistics means of transport.
Owner | [edi3:TradeParty](#TradeParty) | The party owning this logistics means of transport.
ManoeuvringSpeed | xsd:decimal | The manoeuvring speed measured for this logistics means of transport.
TareWeightMeasure | xsd:decimal | The measure of the tare weight (mass) of this logistics means of transport which is the weight (mass) including permanent equipment but excluding goods and loose accessories.
ApprovedSecurityPlanOnboardIndicator | xsd:boolean | The indication of whether or not there is an approved security plan onboard this logistics transport means.
SpecifiedFault | [edi3:Fault](#Fault) | An identified defect specified for this logistics means of transport.
WasteReportingExemptionIndicator | xsd:boolean | The indication of whether or not there is a waste reporting exemption for this logistics means of transport.
AftDraughtLevelMeasure | xsd:decimal | The draught level measured at the aft end of this transport means.
LoadedCargoMeasure | xsd:decimal | The measure of the cargo loaded onto this logistics means of transport, such as the number of barrels of oil or other quantity of breakbulk cargo.
LogisticsTransportMeansTypeText | xsd:string | The type, expressed as text, of this logistics means of transport.
LogisticsTransportMeansNetWeight | xsd:decimal | The measure of the net weight (mass) of this logistics means of transport, such as the net tonnage of a vessel determined in accordance with the provisions of the International Convention on Tonnage Measurement of Ships, 1969.
CompanySecurityOfficer | [edi3:TransportPerson](#TransportPerson) | A person who is a company security officer for this logistics transport means.
SpecifiedHandlingInstructions | [edi3:HandlingInstructions](#HandlingInstructions) | Handling instructions specified for this logistics means of transport.
ISPSSecurityLevelCode | xsd:token | The code specifying the International Ship and Port facility Security (ISPS) level assigned to this logistics means of transport.
LogisticsTransportMeansAttachedTransportEquipment | [edi3:TransportEquipment](#TransportEquipment) | A piece of logistics transport equipment attached to this logistics means of transport.
LogisticsTransportMeansManufacturngDateTime | xsd:dateTime | The manufacturing date, time, date time, or other date time value for this logistics means of transport.
RequiredTransportService | [edi3:Service](#Service) | A transport service required for this logistics means of transport.
LogisticsTransportMeansLength | xsd:decimal | The measure of the length of this logistics means of transport.
LogisticsTransportMeansName | xsd:string | The name, expressed as text, of this logistics means of transport.
RegistrationEvent | [edi3:Event](#Event) | A registration event of this logistics transport means.
SpecifiedSpatialDimension | [edi3:SpatialDimension](#SpatialDimension) | Spatial dimensions specified for this logistics means of transport.
ISSCDocument | [edi3:Document](#Document) | The referenced ISSC (International Ship Security Certificate) document for this logistics transport means.
HelipadIndicator | xsd:boolean | The indication of whether or not there is a helipad on this logistics means of transport.
RegistrationCountry | [edi3:Country](#Country) | The country of registration of this logistics means of transport.
DraughtLevelMeasure | xsd:decimal | The measure of the draught level of this logistics means of transport.
LogisticsTransportMeansID | xsd:token | An identifier of this logistics means of transport, such as the International Maritime Organization number of a vessel.
LogisticsTransportMeansAttachedMonitoringIOTDevice | [edi3:IOTDevice](#IOTDevice) | An IOT device attached to this logistics transport means.
LogisticsTransportMeansOperator | [edi3:TradeParty](#TradeParty) | The party operating this logistics means of transport.


<h1 id="ProductInstance">ProductInstance</h1>

Type: rdf:Class

Description: An individual trade product or batch of similar trade products produced by human or mechanical effort or by a natural process.

Properties: 

name | type | description
-|-|-
SupplierAssignedSerialID | xsd:token | The unique supplier assigned serial identifier for this trade product instance.
ProductionEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | The production event for this trade product instance.
GlobalSerialID | xsd:token | The unique global serial identifier for this trade product instance.
RegistrationID | xsd:token | A unique registration identifier, such as a vehicle licence plate identification, for this trade product instance.
KanbanID | xsd:token | The unique kanban identifier for this trade product instance.
ProductHandlingProcess | [edi3:Process](#Process) | A product handling process applied to this trade product instance, such as manufacturing or storage.
ProductInstanceOriginLocation | [edi3:LogisticsLocation](#LogisticsLocation) | A location of origin for this supply chain product instance.
BestBeforeDateTime | xsd:dateTime | The date, time, date time, or other date time value before which it is best to consume the items contained in this trade product instance.
ProductInstanceMaterialGoodsCharacteristic | [edi3:GoodsCharacteristic](#GoodsCharacteristic) | A distinguishing material feature applicable to this trade product instance.
ProductInstanceExpiryDateTime | xsd:dateTime | The date, time, date time, or other date time value of expiry of the items contained in the trade product instance.
ProductInstanceActualQuantity | xsd:decimal | The actual quantity of items in this trade product instance.
ProductInstanceInspectionEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | The inspection event for this trade product instance.
LotID | xsd:token | The unique lot identifier for this trade product instance.
ProductCharacteristic | [edi3:Characteristic](#Characteristic) | A product characteristic applicable to this trade product instance.
ProductInstanceBatchID | xsd:token | The unique batch identifier for this trade product instance.
PackagingEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | The packaging event for this trade product instance.
SerialID | xsd:token | A unique serial identifier for this trade product instance.


<h1 id="Contact">Contact</h1>

Type: rdf:Class

Description: A person or a department that acts as a point of contact with another person or department in a trading relationship.

Properties: 

name | type | description
-|-|-
ContactTelephone | [edi3:UniversalCommunication](#UniversalCommunication) | Telephone communication information for this trade contact.
InstantMessaging | [edi3:UniversalCommunication](#UniversalCommunication) | Instant messaging communication information for this trade contact.
Telex | [edi3:UniversalCommunication](#UniversalCommunication) | Telegraphy (Telex) communication information for this trade contact.
ContactDepartmentName | xsd:string | The name, expressed as text, of the department to which this trade contact belongs within an organization.
ContactNote | [edi3:Note](#Note) | A note specified for this trade contact.
DirectTelephone | [edi3:UniversalCommunication](#UniversalCommunication) | The direct telephone communication information for this trade contact.
PersonID | xsd:token | A unique identifier for this trade contact person.
Person | [edi3:ContactPerson](#ContactPerson) | The contact person specified for this trade contact.
VOIP | [edi3:UniversalCommunication](#UniversalCommunication) | Voice Over Internet Protocol (VOIP) communication information for this trade contact.
ContactFax | [edi3:UniversalCommunication](#UniversalCommunication) | Fax communication information for this trade contact.
JobTitle | xsd:string | The job title, position or designation, expressed as text, of this trade contact within an organization, such as Director, Software Engineer, Purchasing Manager.
ResponsibilityText | xsd:string | A responsibility, expressed as text, of this trade contact.
ContactID | xsd:token | The unique identifier for this trade contact.
PersonName | xsd:string | The name, expressed as text, of this trade contact person.
ContactTypeCode | xsd:token | The code specifying the type of trade contact.
AuthorizedPersonName | xsd:string | The name, expressed as text, of the authorized person for this trade contact.
ContactMobileTelephone | [edi3:UniversalCommunication](#UniversalCommunication) | The mobile telephone communication information for this trade contact.


<h1 id="WorkflowObject">WorkflowObject</h1>

Type: rdf:Class

Description: An object used in the management of the status changes in a business process.

Properties: 

name | type | description
-|-|-
PreviousStatusCode | xsd:token | The code specifying the previous status of this trade workflow object.
WorkflowObjectID | xsd:token | The identifier of this trade workflow object.


<h1 id="Response">Response</h1>

Type: rdf:Class

Description: A response to a specification query.

Properties: 

name | type | description
-|-|-
ResponseContractualLanguageCode | xsd:token | The code specifying the contractual language for this specification response.
ResponseContentText | xsd:string | The content, expressed as text, of this specification response.
ResponseID | xsd:token | The unique identifier for this specification response.
QueryID | xsd:token | The unique identifier for the query to which this response refers.


<h1 id="Equipment">Equipment</h1>

Type: rdf:Class

Description: Hardware or software typically marketed by a company other than the original manufacturer.

Properties: 

name | type | description
-|-|-
EquipmentID | xsd:token | An identifier of this OEM equipment.
PollingRateMeasure | xsd:decimal | The measure of the polling rate for this OEM equipment.
ApplicablePhysicalCharacteristic | [edi3:PhysicalCharacteristic](#PhysicalCharacteristic) | A physical characteristic applicable to this OEM equipment.
PollingCapabilityIndicator | xsd:boolean | The indication of whether or not this OEM equipment has a polling capability.
EquipmentTypeCode | xsd:token | A code specifying a type of OEM equipment.


<h1 id="DirectPositionList">DirectPositionList</h1>

Type: rdf:Class

Description: The specified list of coordinates for a physical location, expressed as a sequence of direct positions.

Properties: 

name | type | description
-|-|-
UOMLabelListText | xsd:string | An ordered list of Unit Of Measure (UOM) labels, expressed as text, for this specified direct position list.
DirectPositionListAxisLabelListText | xsd:string | An ordered list of axis labels, expressed as text, for this specified direct position list.
DirectPositionListCoordinateText | xsd:string | The coordinate, expressed as text, for this specified direct position list.
DirectPositionListName | xsd:string | The name, expressed as text, of this specified direct position list.
DirectPositionListCount | xsd:decimal | A count for this specified direct position list.


<h1 id="Schedule">Schedule</h1>

Type: rdf:Class

Description: A series of planned activities or things to be done in this supply chain.

Properties: 

name | type | description
-|-|-
ScheduleDescription | xsd:string | A textual description of this supply chain schedule.
ScheduleID | xsd:token | An identifier of this supply chain schedule.
ScheduleOccurrenceDateTime | xsd:dateTime | A date, time, date time, or other date time of an occurrence in this supply chain schedule.
ScheduleTypeCode | xsd:token | A code specifying the type of supply chain schedule.


<h1 id="Clause">Clause</h1>

Type: rdf:Class

Description: A distinct article or provision in a document, which requires compliance.

Properties: 

name | type | description
-|-|-
ClauseID | xsd:token | The unique identifier of this document clause.
URL | xsd:token | The Uniform Resource Locator (URL) for this document clause.
AssociatedPeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | A period of time associated with this document clause.
ClauseContentText | xsd:string | Content, expressed as text, of this document clause.


<h1 id="RegulatedGoods">RegulatedGoods</h1>

Type: rdf:Class

Description: Articles of trade or commerce which are subject to, or controlled by a rule, regulation, or law at a particular point during their logistics lifecycle.

Properties: 

name | type | description
-|-|-


<h1 id="LogisticsLocation">LogisticsLocation</h1>

Type: rdf:Class

Description: A logistics related physical location or place.

Properties: 

name | type | description
-|-|-
LogisticsLocationSubordinateLocation | [edi3:SubordinateLocation](#SubordinateLocation) | A location subordinate to this logistics related location.
StayPeriod | [edi3:SpecifiedPeriod](#SpecifiedPeriod) | A period of stay at this logistics location.
LogisticsLocationCountryName | xsd:string | The country name, expressed as text, of this logistics location.
LogisticsLocationDescription | xsd:string | A textual description of this logistics related location.
LogisticsLocationPostalAddress | [edi3:TradeAddress](#TradeAddress) | The postal trade address information for this logistics related location.
GeographicalCoordinates | [edi3:GeographicalCoordinate](#GeographicalCoordinate) | Geographical coordinate information for this logistics related location.
LogisticsLocationAssociatedGeographicalFeature | [edi3:GeographicalFeature](#GeographicalFeature) | A geographical feature associated with this logistics location.
LogisticsLocationName | xsd:string | A name, expressed as text, of this logistics related location.
LogisticsLocationPreviousAssociatedGeographicalFeature | [edi3:GeographicalFeature](#GeographicalFeature) | A geographical feature previously associated with this logistics location.
LogisticsLocationInspectionEvent | [edi3:SupplyChainEvent](#SupplyChainEvent) | A supply chain inspection event at this logistics location.
LogisticsLocationID | xsd:token | A unique identifier for this logistics related location, such as a United Nations Location Code (UNLOCODE) or GS1 Global Location Number (GLN).
CountrySubDivisionID | xsd:token | The identifier of the country sub-division for this logistics related location.
ServicingParty | [edi3:LocationParty](#LocationParty) | A servicing party specified for this logistics related location.
LogisticsLocationTypeCode | xsd:token | A code specifying the type of this logistics related location.


<h1 id="SubordinateSubordinateLocation">SubordinateSubordinateLocation</h1>

Type: rdf:Class

Description: A physical location or place which is a subordinate location of a subordinate location.

Properties: 

name | type | description
-|-|-
SubordinateSubordinateLocationName | xsd:string | The name, expressed as text, of this subordinate of a subordinate location.
SubordinateSubordinateLocationTypeCode | xsd:token | The code specifying the type of subordinate of a subordinate location.
SubordinateSubordinateLocationID | xsd:token | The unique identifier for this subordinate of a subordinate location, such as a United Nations Location Code (UNLOCODE) or GS1 Global Location Number (GLN).


<h1 id="SubordinateLocation">SubordinateLocation</h1>

Type: rdf:Class

Description: A physical location or place which is a subordinate location of a location.

Properties: 

name | type | description
-|-|-
SubordinateLocationSubordinateLocation | [edi3:SubordinateSubordinateLocation](#SubordinateSubordinateLocation) | The location subordinate to this subordinate location.
SubordinateLocationID | xsd:token | The unique identifier for this subordinate location, such as a United Nations Location Code (UNLOCODE) or GS1 Global Location Number (GLN).
SubordinateLocationName | xsd:string | The name, expressed as text, of this subordinate location.
SubordinateLocationPhysicalGeographicalCoordinate | [edi3:GeographicalCoordinate](#GeographicalCoordinate) | Physical geographical coordinate information for this subordinate location.


<h1 id="TradeLocation">TradeLocation</h1>

Type: rdf:Class

Description: A physical location or place used or referenced for trade purposes.

Properties: 

name | type | description
-|-|-
TradeLocationName | xsd:string | The name, expressed as text, of this location used or referenced in trade.
TradeLocationCountryName | xsd:string | The name, expressed as text, of a country location used or referenced in trade.
TradeLocationCountryCode | xsd:token | The unique identifier of a country location used or referenced in trade.


<h1 id="TransportServiceLocation">TransportServiceLocation</h1>

Type: rdf:Class

Description: A location where a transport service takes place.

Properties: 

name | type | description
-|-|-
TransportServiceLocationName | xsd:string | A name, expressed as text, of this transport service location.
TransportServiceLocationTypeCode | xsd:token | A code specifying the type of transport service location.


<h1 id="GeographicalGrid">GeographicalGrid</h1>

Type: rdf:Class

Description: The combination of the latitude and longitude forming a graticule, used for specifying the position of any location on the surface of the Earth, without consideration of altitude or depth (reference ISO 19136).

Properties: 

name | type | description
-|-|-
OffsetVectorNumber | xsd:decimal | The offset vector, expressed as a number, which indicates the offset of cells along each axis for this geographical grid.
GeographicalGridAssociatedLogisticsLocation | [edi3:LogisticsLocation](#LogisticsLocation) | A logistics location associated with this specified geographical grid.
GeographicalGridID | xsd:token | An identifier for this geographical grid.
AxisName | xsd:string | An axis name, expressed as text, for this geographical grid.
HighLimitText | xsd:string | The tuple of elements, expressed as text, indicating the high limit of this geographical grid specifying the diagonally opposing corner of each axis.
GeographicalGridGeographicalObjectCharacteristic | [edi3:GeographicalObjectCharacteristic](#GeographicalObjectCharacteristic) | The geographical object characteristic associated with this geographical grid.
CellText | xsd:string | The cell value, expressed as text, for this geographical grid.
DimensionNumber | xsd:decimal | The dimension, expressed as a number, of this geographical grid.
LowLimitText | xsd:string | The tuple of elements, expressed as text, indicating the low limit of this geographical grid specifying the offset of each axis.


