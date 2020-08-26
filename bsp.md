<h1 id="ProductGroup">ProductGroup</h1>

Type: rdf:Class

Comments: A grouping of trade products.

Properties: 

Name | Type 
-|-
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="NameText">NameText</span> | xsd:string


<h1 id="Address">Address</h1>

Type: rdf:Class

Comments: <br/>The place of birth.<br/>The location at which a particular trade related organization or person may be found or reached.<br/>The location at which a financial institution may be found or reached.<br/>

Properties: 

Name | Type 
-|-
<span id="CountrySubDivisionIdentifier">CountrySubDivisionIdentifier</span> | xsd:token
<span id="PostcodeCode">PostcodeCode</span> | xsd:token
<span id="LineFiveText">LineFiveText</span> | xsd:string
<span id="CountryCountryIdentifier">CountryCountryIdentifier</span> | xsd:token
<span id="LineFourText">LineFourText</span> | xsd:string
<span id="CityNameText">CityNameText</span> | xsd:string
<span id="PostOfficeBoxText">PostOfficeBoxText</span> | xsd:string
<span id="LineOneText">LineOneText</span> | xsd:string
<span id="BuildingNameText">BuildingNameText</span> | xsd:string
<span id="TypeCode">TypeCode</span> | xsd:token
<span id="CountrySubDivisionNameText">CountrySubDivisionNameText</span> | xsd:string
<span id="CityIdentifier">CityIdentifier</span> | xsd:token
<span id="TypeAddressTypeCode">TypeAddressTypeCode</span> | xsd:token
<span id="StreetNameText">StreetNameText</span> | xsd:string
<span id="AttentionOfText">AttentionOfText</span> | xsd:string
<span id="CountryNameText">CountryNameText</span> | xsd:string
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="GeoCoordinateIdentificationGeographicalCoordinate">GeoCoordinateIdentificationGeographicalCoordinate</span> | [edi3:GeographicalCoordinate](#GeographicalCoordinate)
<span id="CountryIdentifier">CountryIdentifier</span> | xsd:token
<span id="CareOfText">CareOfText</span> | xsd:string
<span id="DepartmentNameText">DepartmentNameText</span> | xsd:string
<span id="CitySubDivisionNameText">CitySubDivisionNameText</span> | xsd:string
<span id="LineThreeText">LineThreeText</span> | xsd:string
<span id="BuildingNumberText">BuildingNumberText</span> | xsd:string
<span id="LineTwoText">LineTwoText</span> | xsd:string


<h1 id="Query">Query</h1>

Type: rdf:Class

Comments: A formally raised question or request for information about this specification.

Properties: 

Name | Type 
-|-
<span id="ContractualLanguageCode">ContractualLanguageCode</span> | xsd:token
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="ContentText">ContentText</span> | xsd:string


<h1 id="Product">Product</h1>

Type: rdf:Class

Comments: <br/>A reference to a product or service produced by human or mechanical effort or by a natural process for trading purposes.<br/>Any tangible output or service produced by human or mechanical effort or by a natural process for trade purposes.<br/>

Properties: 

Name | Type 
-|-
<span id="UseDescriptionText">UseDescriptionText</span> | xsd:string
<span id="MaximumLinearSpatialDimension">MaximumLinearSpatialDimension</span> | [edi3:Dimension](#Dimension)
<span id="RecyclingTypeCode">RecyclingTypeCode</span> | xsd:token
<span id="StatusCode">StatusCode</span> | xsd:token
<span id="AdditionalDescriptionText">AdditionalDescriptionText</span> | xsd:string
<span id="ModelNameText">ModelNameText</span> | xsd:string
<span id="DesignationText">DesignationText</span> | xsd:string
<span id="SeasonDescriptionText">SeasonDescriptionText</span> | xsd:string
<span id="FinalAssemblyTradeCountry">FinalAssemblyTradeCountry</span> | [edi3:Country](#Country)
<span id="PromotionalVariantIdentificationIdentifier">PromotionalVariantIdentificationIdentifier</span> | xsd:token
<span id="IntendedUseText">IntendedUseText</span> | xsd:string
<span id="AttachedProductSecurityTag">AttachedProductSecurityTag</span> | [edi3:SecurityTag](#SecurityTag)
<span id="ApplicableDisposalInstructions">ApplicableDisposalInstructions</span> | [edi3:Instructions](#Instructions)
<span id="DrainedNetWeightMeasure">DrainedNetWeightMeasure</span> | xsd:decimal
<span id="ApplicableTransportDangerousGoods">ApplicableTransportDangerousGoods</span> | [edi3:DangerousGoods](#DangerousGoods)
<span id="FromDeliveryLifeSpanDurationUnitMeasure">FromDeliveryLifeSpanDurationUnitMeasure</span> | xsd:decimal
<span id="MarketingDescriptionText">MarketingDescriptionText</span> | xsd:string
<span id="UnitQuantity">UnitQuantity</span> | xsd:decimal
<span id="GlobalIdentificationIdentifier">GlobalIdentificationIdentifier</span> | xsd:token
<span id="CommonNameText">CommonNameText</span> | xsd:string
<span id="PresentationSpecifiedBinaryFile">PresentationSpecifiedBinaryFile</span> | [edi3:BinaryFile](#BinaryFile)
<span id="SellerAssignedIdentificationIdentifier">SellerAssignedIdentificationIdentifier</span> | xsd:token
<span id="EndItemTypeCode">EndItemTypeCode</span> | xsd:token
<span id="ProductGroupIdentifier">ProductGroupIdentifier</span> | xsd:token
<span id="TypeCode">TypeCode</span> | xsd:token
<span id="ContentUnitQuantity">ContentUnitQuantity</span> | xsd:decimal
<span id="IncludedProductContentUnitQuantity">IncludedProductContentUnitQuantity</span> | xsd:decimal
<span id="BrandOwnerTradeParty">BrandOwnerTradeParty</span> | [edi3:Party](#Party)
<span id="PrePackagedIndicator">PrePackagedIndicator</span> | xsd:boolean
<span id="TransportInformationNote">TransportInformationNote</span> | [edi3:Note](#Note)
<span id="CustomerAssignedIdentificationIdentifier">CustomerAssignedIdentificationIdentifier</span> | xsd:token
<span id="MarkedSerialNumberIndicator">MarkedSerialNumberIndicator</span> | xsd:boolean
<span id="LinearSpatialDimension">LinearSpatialDimension</span> | [edi3:Dimension](#Dimension)
<span id="InspectionReferenceReferencedDocument">InspectionReferenceReferencedDocument</span> | [edi3:Document](#Document)
<span id="IncludedReferencedProduct">IncludedReferencedProduct</span> | [edi3:Product](#Product)
<span id="InnerPackQuantity">InnerPackQuantity</span> | xsd:decimal
<span id="CertificationEvidenceReferenceReferencedDocument">CertificationEvidenceReferenceReferencedDocument</span> | [edi3:Document](#Document)
<span id="FromOpeningLifeSpanDurationUnitMeasure">FromOpeningLifeSpanDurationUnitMeasure</span> | xsd:decimal
<span id="GrossWeightMeasure">GrossWeightMeasure</span> | xsd:decimal
<span id="OriginLogisticsLocation">OriginLogisticsLocation</span> | [edi3:Location](#Location)
<span id="UnitTypeCode">UnitTypeCode</span> | xsd:token
<span id="ManufactureTradeCountry">ManufactureTradeCountry</span> | [edi3:Country](#Country)
<span id="NetWeightMeasure">NetWeightMeasure</span> | xsd:decimal
<span id="RelationshipTypeCode">RelationshipTypeCode</span> | xsd:token
<span id="StorageInformationNote">StorageInformationNote</span> | [edi3:Note](#Note)
<span id="BrandRangeNameText">BrandRangeNameText</span> | xsd:string
<span id="GlobalExtensionIdentificationIdentifier">GlobalExtensionIdentificationIdentifier</span> | xsd:token
<span id="IncludedProductTypeQuantity">IncludedProductTypeQuantity</span> | xsd:decimal
<span id="BrandNameText">BrandNameText</span> | xsd:string
<span id="TrackingSystemIdentifier">TrackingSystemIdentifier</span> | xsd:token
<span id="ManufacturerTradeParty">ManufacturerTradeParty</span> | [edi3:Party](#Party)
<span id="RegulationConformityIdentifier">RegulationConformityIdentifier</span> | xsd:token
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="FunctionDescriptionText">FunctionDescriptionText</span> | xsd:string
<span id="MarketingTradeProductFeature">MarketingTradeProductFeature</span> | [edi3:Feature](#Feature)
<span id="InnerPackContentUnitQuantity">InnerPackContentUnitQuantity</span> | xsd:decimal
<span id="BatchIdentificationIdentifier">BatchIdentificationIdentifier</span> | xsd:token
<span id="InformationNote">InformationNote</span> | [edi3:Note](#Note)
<span id="ContentVariableMeasureIndicator">ContentVariableMeasureIndicator</span> | xsd:boolean
<span id="ConsumerGenderDescriptionText">ConsumerGenderDescriptionText</span> | xsd:string
<span id="VariantDescriptionText">VariantDescriptionText</span> | xsd:string
<span id="SeasonCode">SeasonCode</span> | xsd:token
<span id="ProductionDiscontinuedDateTime">ProductionDiscontinuedDateTime</span> | xsd:dateTime
<span id="ApplicableTradeProductCertification">ApplicableTradeProductCertification</span> | [edi3:Certification](#Certification)
<span id="MinimumLinearSpatialDimension">MinimumLinearSpatialDimension</span> | [edi3:Dimension](#Dimension)
<span id="ApplicableProductCharacteristic">ApplicableProductCharacteristic</span> | [edi3:Characteristic](#Characteristic)
<span id="PhysicalFormDescriptionText">PhysicalFormDescriptionText</span> | xsd:string
<span id="FromProductionLifeSpanDurationUnitMeasure">FromProductionLifeSpanDurationUnitMeasure</span> | xsd:decimal
<span id="LegalRightsOwnerTradeParty">LegalRightsOwnerTradeParty</span> | [edi3:Party](#Party)
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="VariableMeasureIndicator">VariableMeasureIndicator</span> | xsd:boolean
<span id="AdditionalReferenceReferencedDocument">AdditionalReferenceReferencedDocument</span> | [edi3:Document](#Document)
<span id="SuppliedFromTradeCountry">SuppliedFromTradeCountry</span> | [edi3:Country](#Country)
<span id="EndItemNameText">EndItemNameText</span> | xsd:string
<span id="ConciseDescriptionText">ConciseDescriptionText</span> | xsd:string
<span id="ManufacturerAssignedIdentificationIdentifier">ManufacturerAssignedIdentificationIdentifier</span> | xsd:token
<span id="GeneticModificationExtentCode">GeneticModificationExtentCode</span> | xsd:token
<span id="FormattedLatestProductDataChangeFormattedDateTime">FormattedLatestProductDataChangeFormattedDateTime</span> | xsd:dateTime
<span id="NameText">NameText</span> | xsd:string
<span id="DesignatedProductClassification">DesignatedProductClassification</span> | [edi3:Classification](#Classification)
<span id="OriginTradeCountry">OriginTradeCountry</span> | [edi3:Country](#Country)
<span id="ColourCode">ColourCode</span> | xsd:token
<span id="SecurityInformationNote">SecurityInformationNote</span> | [edi3:Note](#Note)
<span id="MarketingCampaignReferenceReferencedDocument">MarketingCampaignReferenceReferencedDocument</span> | [edi3:Document](#Document)
<span id="ConfigurableIndicator">ConfigurableIndicator</span> | xsd:boolean
<span id="ModelIdentificationIdentifier">ModelIdentificationIdentifier</span> | xsd:token
<span id="NetVolumeMeasure">NetVolumeMeasure</span> | xsd:decimal
<span id="BuyerAssignedIdentificationIdentifier">BuyerAssignedIdentificationIdentifier</span> | xsd:token
<span id="ConsumerAgeDescriptionText">ConsumerAgeDescriptionText</span> | xsd:string
<span id="FormattedCancellationAnnouncedLaunchFormattedDateTime">FormattedCancellationAnnouncedLaunchFormattedDateTime</span> | xsd:dateTime
<span id="ApplicableKeyword">ApplicableKeyword</span> | [edi3:Keyword](#Keyword)
<span id="BuyerSuppliedPartsReferenceReferencedDocument">BuyerSuppliedPartsReferenceReferencedDocument</span> | [edi3:Document](#Document)
<span id="ApplicableSupplyChainPackaging">ApplicableSupplyChainPackaging</span> | [edi3:Packaging](#Packaging)
<span id="ColourDescriptionText">ColourDescriptionText</span> | xsd:string
<span id="SpecifiedProductCertificate">SpecifiedProductCertificate</span> | [edi3:Certificate](#Certificate)
<span id="IndustryAssignedIdentificationIdentifier">IndustryAssignedIdentificationIdentifier</span> | xsd:token
<span id="MSDSReferenceReferencedDocument">MSDSReferenceReferencedDocument</span> | [edi3:Document](#Document)
<span id="ScientificNameText">ScientificNameText</span> | xsd:string
<span id="ApplicableMaterialGoodsCharacteristic">ApplicableMaterialGoodsCharacteristic</span> | [edi3:GoodsCharacteristic](#GoodsCharacteristic)
<span id="ExportIndicator">ExportIndicator</span> | xsd:boolean
<span id="UltimateCustomerAssignedExtensionIdentificationIdentifier">UltimateCustomerAssignedExtensionIdentificationIdentifier</span> | xsd:token
<span id="SubBrandNameText">SubBrandNameText</span> | xsd:string
<span id="IndividualTradeProductInstance">IndividualTradeProductInstance</span> | [edi3:ProductInstance](#ProductInstance)
<span id="AreaDensityMeasure">AreaDensityMeasure</span> | xsd:decimal
<span id="TradeNameText">TradeNameText</span> | xsd:string
<span id="GrossVolumeMeasure">GrossVolumeMeasure</span> | xsd:decimal


<h1 id="Fault">Fault</h1>

Type: rdf:Class

Comments: An identified defect or fault.

Properties: 

Name | Type 
-|-
<span id="IdentificationCode">IdentificationCode</span> | xsd:token


<h1 id="GeographicalSurface">GeographicalSurface</h1>

Type: rdf:Class

Comments: A figure on the Earth having only two dimensions (reference ISO 19136).

Properties: 

Name | Type 
-|-
<span id="AssociatedSpecifiedGeographicalObjectCharacteristic">AssociatedSpecifiedGeographicalObjectCharacteristic</span> | [edi3:GeographicalObjectCharacteristic](#GeographicalObjectCharacteristic)


<h1 id="Document">Document</h1>

Type: rdf:Class

Comments: <br/>A collection of financing related data that provides an overview of key points.<br/>A collection of data for a piece of written, printed or electronic matter that is exchanged between two or more parties.<br/>Written, printed or electronic matter that is referenced.<br/>A collection of data for a line on a piece of written, printed or electronic matter that provides information or evidence.<br/>A collection of data that reports the result of a financing request.<br/>The set of characteristics shared by all individual transactions grouped for this financing request document.<br/>A document exchanged between parties for a business application level acknowledgement of the receipt of information.<br/>

Properties: 

Name | Type 
-|-
<span id="FinancedTotalAmount">FinancedTotalAmount</span> | xsd:decimal
<span id="ReferenceFormattedDateTime">ReferenceFormattedDateTime</span> | xsd:dateTime
<span id="SectionNameText">SectionNameText</span> | xsd:string
<span id="CurrencyCurrencyCode">CurrencyCurrencyCode</span> | xsd:token
<span id="FinancedRatePercent">FinancedRatePercent</span> | xsd:decimal
<span id="PurposeText">PurposeText</span> | xsd:string
<span id="CreationFormattedDateTime">CreationFormattedDateTime</span> | xsd:dateTime
<span id="CreationDateTime">CreationDateTime</span> | xsd:dateTime
<span id="LineItemQuantity">LineItemQuantity</span> | xsd:decimal
<span id="UrgencyText">UrgencyText</span> | xsd:string
<span id="FourthSignatoryDocumentAuthentication">FourthSignatoryDocumentAuthentication</span> | [edi3:Authentication](#Authentication)
<span id="ElectronicPresentationIndicator">ElectronicPresentationIndicator</span> | xsd:boolean
<span id="ReasonInformationText">ReasonInformationText</span> | xsd:string
<span id="AuthorizationText">AuthorizationText</span> | xsd:string
<span id="AmendmentPurposeCode">AmendmentPurposeCode</span> | xsd:token
<span id="InformationText">InformationText</span> | xsd:string
<span id="CopyIssuedQuantity">CopyIssuedQuantity</span> | xsd:decimal
<span id="PageIdentifier">PageIdentifier</span> | xsd:token
<span id="IssuerTradeParty">IssuerTradeParty</span> | [edi3:Party](#Party)
<span id="GlobalIdentificationIdentifier">GlobalIdentificationIdentifier</span> | xsd:token
<span id="FirstAgentSpecifiedCreditorFinancialInstitution">FirstAgentSpecifiedCreditorFinancialInstitution</span> | [edi3:FinancialInstitution](#FinancialInstitution)
<span id="CustomsIdentificationIdentifier">CustomsIdentificationIdentifier</span> | xsd:token
<span id="AcceptedTransactionOriginalTotalAmount">AcceptedTransactionOriginalTotalAmount</span> | xsd:decimal
<span id="ThirdSignatoryDocumentAuthentication">ThirdSignatoryDocumentAuthentication</span> | [edi3:Authentication](#Authentication)
<span id="ReferenceReferencedDocument">ReferenceReferencedDocument</span> | [edi3:Document](#Document)
<span id="AcceptanceDateTime">AcceptanceDateTime</span> | xsd:dateTime
<span id="ResponseDateTime">ResponseDateTime</span> | xsd:dateTime
<span id="ContractualDocumentClause">ContractualDocumentClause</span> | [edi3:Clause](#Clause)
<span id="PreviousRevisionIdentificationIdentifier">PreviousRevisionIdentificationIdentifier</span> | xsd:token
<span id="AgreementInformationText">AgreementInformationText</span> | xsd:string
<span id="TraderAssignedIdentificationIdentifier">TraderAssignedIdentificationIdentifier</span> | xsd:token
<span id="ReferenceTypeReferenceCode">ReferenceTypeReferenceCode</span> | xsd:token
<span id="RecipientAssignedIdentificationIdentifier">RecipientAssignedIdentificationIdentifier</span> | xsd:token
<span id="LodgementLogisticsLocation">LodgementLogisticsLocation</span> | [edi3:Location](#Location)
<span id="IncludedAmount">IncludedAmount</span> | xsd:decimal
<span id="UrgencyCode">UrgencyCode</span> | xsd:token
<span id="FinancedAppliedRatePercent">FinancedAppliedRatePercent</span> | xsd:decimal
<span id="LineStatusLineStatusCode">LineStatusLineStatusCode</span> | xsd:token
<span id="LatestRevisionDateTime">LatestRevisionDateTime</span> | xsd:dateTime
<span id="RelatedFinancialBooking">RelatedFinancialBooking</span> | [edi3:Booking](#Booking)
<span id="CategoryCode">CategoryCode</span> | xsd:token
<span id="StatusDocumentStatusCode">StatusDocumentStatusCode</span> | xsd:token
<span id="OffsetProcessingStatusText">OffsetProcessingStatusText</span> | xsd:string
<span id="RejectionResponseDateTime">RejectionResponseDateTime</span> | xsd:dateTime
<span id="OriginalRequiredQuantity">OriginalRequiredQuantity</span> | xsd:decimal
<span id="TypeDocumentCode">TypeDocumentCode</span> | xsd:token
<span id="CancellationReasonText">CancellationReasonText</span> | xsd:string
<span id="LineIdentifier">LineIdentifier</span> | xsd:token
<span id="GroupIdentificationIdentifier">GroupIdentificationIdentifier</span> | xsd:token
<span id="FirstSignatoryDocumentAuthentication">FirstSignatoryDocumentAuthentication</span> | [edi3:Authentication](#Authentication)
<span id="SpecifiedCancellationStatus">SpecifiedCancellationStatus</span> | [edi3:Status](#Status)
<span id="IssuerAssignedIdentificationIdentifier">IssuerAssignedIdentificationIdentifier</span> | xsd:token
<span id="RemarksText">RemarksText</span> | xsd:string
<span id="AttachmentBinaryObject">AttachmentBinaryObject</span> | xsd:base64Binary
<span id="SpecifiedValidationStatus">SpecifiedValidationStatus</span> | [edi3:Status](#Status)
<span id="PurposeMessageFunctionCode">PurposeMessageFunctionCode</span> | xsd:token
<span id="GroupedTransactionTotalAmount">GroupedTransactionTotalAmount</span> | xsd:decimal
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="SubordinateLineIdentifier">SubordinateLineIdentifier</span> | xsd:token
<span id="SpecifiedRequestingParty">SpecifiedRequestingParty</span> | [edi3:Party](#Party)
<span id="FinancedTransactionSpecifiedQuantity">FinancedTransactionSpecifiedQuantity</span> | xsd:decimal
<span id="RequestedResponseTypeCode">RequestedResponseTypeCode</span> | xsd:token
<span id="RevisionIdentificationIdentifier">RevisionIdentificationIdentifier</span> | xsd:token
<span id="AdditionalInformationIncludedNote">AdditionalInformationIncludedNote</span> | [edi3:Note](#Note)
<span id="ReportSubmissionDateTime">ReportSubmissionDateTime</span> | xsd:dateTime
<span id="SignatoryDocumentAuthentication">SignatoryDocumentAuthentication</span> | [edi3:Authentication](#Authentication)
<span id="MultipleReferencesIndicator">MultipleReferencesIndicator</span> | xsd:boolean
<span id="LineCountNumeric">LineCountNumeric</span> | xsd:decimal
<span id="PublicationDateTime">PublicationDateTime</span> | xsd:dateTime
<span id="EffectiveSpecifiedPeriod">EffectiveSpecifiedPeriod</span> | [edi3:Period](#Period)
<span id="BuyerAssignedCategoryCode">BuyerAssignedCategoryCode</span> | xsd:token
<span id="RelationshipTypeReferenceCode">RelationshipTypeReferenceCode</span> | xsd:token
<span id="VersionIdentificationIdentifier">VersionIdentificationIdentifier</span> | xsd:token
<span id="SpecifiedDocumentStatus">SpecifiedDocumentStatus</span> | [edi3:Status](#Status)
<span id="ItemIdentificationIdentifier">ItemIdentificationIdentifier</span> | xsd:token
<span id="FormattedIssueFormattedDateTime">FormattedIssueFormattedDateTime</span> | xsd:dateTime
<span id="BuyerSignatoryDocumentAuthentication">BuyerSignatoryDocumentAuthentication</span> | [edi3:Authentication](#Authentication)
<span id="AcceptableSpecifiedPeriod">AcceptableSpecifiedPeriod</span> | [edi3:Period](#Period)
<span id="AgentTradeParty">AgentTradeParty</span> | [edi3:Party](#Party)
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="SpecifiedFinancingStatus">SpecifiedFinancingStatus</span> | [edi3:Status](#Status)
<span id="URIIdentificationIdentifier">URIIdentificationIdentifier</span> | xsd:token
<span id="SecondSignatoryDocumentAuthentication">SecondSignatoryDocumentAuthentication</span> | [edi3:Authentication](#Authentication)
<span id="ParentLineIdentifier">ParentLineIdentifier</span> | xsd:token
<span id="LineStatusReasonCode">LineStatusReasonCode</span> | xsd:token
<span id="SubmissionDateTime">SubmissionDateTime</span> | xsd:dateTime
<span id="CopyIndicator">CopyIndicator</span> | xsd:boolean
<span id="NameText">NameText</span> | xsd:string
<span id="ControlRequirementIndicator">ControlRequirementIndicator</span> | xsd:boolean
<span id="OriginalIssuedQuantity">OriginalIssuedQuantity</span> | xsd:decimal
<span id="AcknowledgementStatusAcknowledgementCode">AcknowledgementStatusAcknowledgementCode</span> | xsd:token
<span id="StatusStatusCode">StatusStatusCode</span> | xsd:token
<span id="ReportReceiptDateTime">ReportReceiptDateTime</span> | xsd:dateTime
<span id="IntermediarySpecifiedCreditorFinancialInstitution">IntermediarySpecifiedCreditorFinancialInstitution</span> | [edi3:FinancialInstitution](#FinancialInstitution)
<span id="RecipientTradeParty">RecipientTradeParty</span> | [edi3:Party](#Party)
<span id="LineStatusReasonText">LineStatusReasonText</span> | xsd:string
<span id="CopyRequiredQuantity">CopyRequiredQuantity</span> | xsd:decimal
<span id="LanguageIdentifier">LanguageIdentifier</span> | xsd:token
<span id="SpecifiedCreditorFinancialAccount">SpecifiedCreditorFinancialAccount</span> | [edi3:FinancialAccount](#FinancialAccount)
<span id="IssueDateTime">IssueDateTime</span> | xsd:dateTime
<span id="IssueLogisticsLocation">IssueLogisticsLocation</span> | [edi3:Location](#Location)
<span id="AttachedSpecifiedBinaryFile">AttachedSpecifiedBinaryFile</span> | [edi3:BinaryFile](#BinaryFile)
<span id="ApproverSignatoryDocumentAuthentication">ApproverSignatoryDocumentAuthentication</span> | [edi3:Authentication](#Authentication)
<span id="IncludedNote">IncludedNote</span> | [edi3:Note](#Note)
<span id="CancellationDateTime">CancellationDateTime</span> | xsd:dateTime
<span id="RevisionDateTime">RevisionDateTime</span> | xsd:dateTime
<span id="UUIDLineIdentifier">UUIDLineIdentifier</span> | xsd:token
<span id="SenderTradeParty">SenderTradeParty</span> | [edi3:Party](#Party)
<span id="ResponseReasonCode">ResponseReasonCode</span> | xsd:token
<span id="ProprietaryTypeText">ProprietaryTypeText</span> | xsd:string
<span id="GroupedTransactionSpecifiedQuantity">GroupedTransactionSpecifiedQuantity</span> | xsd:decimal
<span id="ReferenceAcknowledgementDocument">ReferenceAcknowledgementDocument</span> | [edi3:Document](#Document)
<span id="ReceiptDateTime">ReceiptDateTime</span> | xsd:dateTime
<span id="AuthenticatedOriginalIndicator">AuthenticatedOriginalIndicator</span> | xsd:boolean
<span id="SenderAssignedIdentificationIdentifier">SenderAssignedIdentificationIdentifier</span> | xsd:token
<span id="LineOfCreditSpecifiedFinancingFinancialAccount">LineOfCreditSpecifiedFinancingFinancialAccount</span> | [edi3:FinancialAccount](#FinancialAccount)


<h1 id="Feature">Feature</h1>

Type: rdf:Class

Comments: Distinctive or characteristic parts of a trade product.

Properties: 

Name | Type 
-|-
<span id="TypeCode">TypeCode</span> | xsd:token
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="MarketingMeasure">MarketingMeasure</span> | xsd:decimal
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="NameText">NameText</span> | xsd:string


<h1 id="WorkItem">WorkItem</h1>

Type: rdf:Class

Comments: <br/>A basic item of work.<br/>A grouping of related work items.<br/>

Properties: 

Name | Type 
-|-
<span id="SubordinateBasicWorkItem">SubordinateBasicWorkItem</span> | [edi3:WorkItem](#WorkItem)
<span id="UnitCalculatedPrice">UnitCalculatedPrice</span> | [edi3:Price](#Price)
<span id="TypeCode">TypeCode</span> | xsd:token
<span id="TotalQuantityWorkItemQuantityAnalysis">TotalQuantityWorkItemQuantityAnalysis</span> | [edi3:QuantityAnalysis](#QuantityAnalysis)
<span id="IndexValue">IndexValue</span> | xsd:string
<span id="ItemBasicWorkItem">ItemBasicWorkItem</span> | [edi3:WorkItem](#WorkItem)
<span id="TotalQuantityClassificationCode">TotalQuantityClassificationCode</span> | xsd:token
<span id="CommentText">CommentText</span> | xsd:string
<span id="ContractualLanguageCode">ContractualLanguageCode</span> | xsd:token
<span id="ReferenceFileBinaryObject">ReferenceFileBinaryObject</span> | xsd:base64Binary
<span id="ReferencedSpecifiedBinaryFile">ReferencedSpecifiedBinaryFile</span> | [edi3:BinaryFile](#BinaryFile)
<span id="PrimaryClassificationCode">PrimaryClassificationCode</span> | xsd:token
<span id="PriceListItemIdentificationIdentifier">PriceListItemIdentificationIdentifier</span> | xsd:token
<span id="AlternativeClassificationCode">AlternativeClassificationCode</span> | xsd:token
<span id="ActualWorkItemComplexDescription">ActualWorkItemComplexDescription</span> | [edi3:ComplexDescription](#ComplexDescription)
<span id="RequestedActionCode">RequestedActionCode</span> | xsd:token
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="TotalQuantity">TotalQuantity</span> | xsd:decimal
<span id="TotalCalculatedPrice">TotalCalculatedPrice</span> | [edi3:Price](#Price)
<span id="ChangedRecordedStatus">ChangedRecordedStatus</span> | [edi3:Status](#Status)
<span id="ItemGroupedWorkItem">ItemGroupedWorkItem</span> | [edi3:WorkItem](#WorkItem)
<span id="ReferenceIdentificationIdentifier">ReferenceIdentificationIdentifier</span> | xsd:token
<span id="IndexText">IndexText</span> | xsd:string


<h1 id="ChemicalTreatment">ChemicalTreatment</h1>

Type: rdf:Class

Comments: A process of applying a chemical, physical, or biological agent to an object.

Properties: 

Name | Type 
-|-
<span id="ApplicableSpecifiedTemperature">ApplicableSpecifiedTemperature</span> | [edi3:Temperature](#Temperature)
<span id="AppliedSpecifiedPeriod">AppliedSpecifiedPeriod</span> | [edi3:Period](#Period)
<span id="OccurrenceDateTime">OccurrenceDateTime</span> | xsd:dateTime
<span id="UsedDistinctChemical">UsedDistinctChemical</span> | [edi3:Chemical](#Chemical)
<span id="ResultNote">ResultNote</span> | [edi3:Note](#Note)
<span id="NameText">NameText</span> | xsd:string
<span id="ChemicalConcentrationMeasure">ChemicalConcentrationMeasure</span> | xsd:decimal
<span id="MethodNameText">MethodNameText</span> | xsd:string


<h1 id="TradeTransaction">TradeTransaction</h1>

Type: rdf:Class

Comments: <br/>A group of supply chain trade line items, trade agreement, trade delivery and trade settlement details.<br/>A group of trade line items, trade line agreement, trade line delivery and trade line settlement details.<br/>

Properties: 

Name | Type 
-|-
<span id="IssueFormattedDateTime">IssueFormattedDateTime</span> | xsd:dateTime
<span id="LineItemQuantity">LineItemQuantity</span> | xsd:decimal
<span id="InformationText">InformationText</span> | xsd:string
<span id="IncludedTradeProductGroup">IncludedTradeProductGroup</span> | [edi3:ProductGroup](#ProductGroup)
<span id="SpecifiedLogisticsPackage">SpecifiedLogisticsPackage</span> | [edi3:Package](#Package)
<span id="AssociatedReferencedDocument">AssociatedReferencedDocument</span> | [edi3:Document](#Document)
<span id="ApplicableHeaderTradeSettlement">ApplicableHeaderTradeSettlement</span> | [edi3:TradeSettlement](#TradeSettlement)
<span id="TypeCode">TypeCode</span> | xsd:token
<span id="AssociatedDocumentLineDocument">AssociatedDocumentLineDocument</span> | [edi3:Document](#Document)
<span id="IncludedTradeProduct">IncludedTradeProduct</span> | [edi3:Product](#Product)
<span id="ApplicableHeaderTradeDelivery">ApplicableHeaderTradeDelivery</span> | [edi3:TradeDelivery](#TradeDelivery)
<span id="DocumentURLIdentifier">DocumentURLIdentifier</span> | xsd:token
<span id="ShipmentIdentificationIdentifier">ShipmentIdentificationIdentifier</span> | xsd:token
<span id="AssociatedFinancingRequestResultDocument">AssociatedFinancingRequestResultDocument</span> | [edi3:Document](#Document)
<span id="SalesAgentAssignedIdentificationIdentifier">SalesAgentAssignedIdentificationIdentifier</span> | xsd:token
<span id="SenderRecipientSequenceIdentificationIdentifier">SenderRecipientSequenceIdentificationIdentifier</span> | xsd:token
<span id="IncludedSupplyChainTradeLineItem">IncludedSupplyChainTradeLineItem</span> | [edi3:TradeLineItem](#TradeLineItem)
<span id="ApplicableLineTradeDelivery">ApplicableLineTradeDelivery</span> | [edi3:TradeDelivery](#TradeDelivery)
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="ApplicableHeaderTradeAgreement">ApplicableHeaderTradeAgreement</span> | [edi3:TradeAgreement](#TradeAgreement)


<h1 id="RiskAnalysisResult">RiskAnalysisResult</h1>

Type: rdf:Class

Comments: The result of a logistics risk analysis calculation.

Properties: 

Name | Type 
-|-
<span id="TransportEquipmentRiskRelatedCode">TransportEquipmentRiskRelatedCode</span> | xsd:token
<span id="CategoryCode">CategoryCode</span> | xsd:token
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="ConsignmentRiskRelatedCode">ConsignmentRiskRelatedCode</span> | xsd:token
<span id="PartyRiskRelatedCode">PartyRiskRelatedCode</span> | xsd:token
<span id="LevelCode">LevelCode</span> | xsd:token


<h1 id="Classification">Classification</h1>

Type: rdf:Class

Comments: A systematic arrangement of products in classes or categories according to established criteria.

Properties: 

Name | Type 
-|-
<span id="ClassNameText">ClassNameText</span> | xsd:string
<span id="SystemIdentifier">SystemIdentifier</span> | xsd:token
<span id="ClassCode">ClassCode</span> | xsd:token
<span id="SubClassCode">SubClassCode</span> | xsd:token
<span id="ClassProductCharacteristic">ClassProductCharacteristic</span> | [edi3:Characteristic](#Characteristic)
<span id="SystemNameText">SystemNameText</span> | xsd:string


<h1 id="Accreditation">Accreditation</h1>

Type: rdf:Class

Comments: A certified recognition that provides evidence of a level of competency in a given area, such as certifying a level of skill in a trade.

Properties: 

Name | Type 
-|-
<span id="TypeCode">TypeCode</span> | xsd:token
<span id="ExpiryFormattedDateTime">ExpiryFormattedDateTime</span> | xsd:dateTime
<span id="AuthenticationMethodCode">AuthenticationMethodCode</span> | xsd:token
<span id="CategoryCode">CategoryCode</span> | xsd:token
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="ObtainedFormattedDateTime">ObtainedFormattedDateTime</span> | xsd:dateTime


<h1 id="Identity">Identity</h1>

Type: rdf:Class

Comments: <br/>Identification of a person.<br/>Identification of a party who pays someone to do work on a regular or contractual basis.<br/>Proprietary information which uniquely identifies a person or organization.<br/>A financial identification for an organization.<br/>

Properties: 

Name | Type 
-|-
<span id="SpecifiedProprietaryIdentity">SpecifiedProprietaryIdentity</span> | [edi3:Identity](#Identity)
<span id="BEIIdentificationIdentifier">BEIIdentificationIdentifier</span> | xsd:token
<span id="SocialSecurityIdentificationIdentifier">SocialSecurityIdentificationIdentifier</span> | xsd:token
<span id="PassportIdentificationIdentifier">PassportIdentificationIdentifier</span> | xsd:token
<span id="IdentityCardIdentificationIdentifier">IdentityCardIdentificationIdentifier</span> | xsd:token
<span id="BICIdentificationIdentifier">BICIdentificationIdentifier</span> | xsd:token
<span id="CHIPSUniversalIdentificationIdentifier">CHIPSUniversalIdentificationIdentifier</span> | xsd:token
<span id="DriversLicenceIdentificationIdentifier">DriversLicenceIdentificationIdentifier</span> | xsd:token
<span id="AgentAssignedCustomerIdentificationIdentifier">AgentAssignedCustomerIdentificationIdentifier</span> | xsd:token
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="IBEIIdentificationIdentifier">IBEIIdentificationIdentifier</span> | xsd:token
<span id="BankAssignedIdentificationIdentifier">BankAssignedIdentificationIdentifier</span> | xsd:token
<span id="AlienRegistrationIdentificationIdentifier">AlienRegistrationIdentificationIdentifier</span> | xsd:token


<h1 id="Status">Status</h1>

Type: rdf:Class

Comments: <br/>Information relevant to a condition of financing.<br/>The information relevant to a condition or a position related to logistics.<br/>The information relevant to a condition related to a document.<br/>Recorded information relevant to a condition or a position of an object.<br/>Information relevant to a condition of a validation.<br/>Information relevant to a condition of a cancellation.<br/>

Properties: 

Name | Type 
-|-
<span id="DepartureReportedTransportEvent">DepartureReportedTransportEvent</span> | [edi3:Event](#Event)
<span id="ReasonLogisticsStatusCode">ReasonLogisticsStatusCode</span> | xsd:token
<span id="ReasonInformationText">ReasonInformationText</span> | xsd:string
<span id="InformationText">InformationText</span> | xsd:string
<span id="ValiditySpecifiedPeriod">ValiditySpecifiedPeriod</span> | [edi3:Period](#Period)
<span id="AdditionalReasonText">AdditionalReasonText</span> | xsd:string
<span id="ConditionDocumentStatusCode">ConditionDocumentStatusCode</span> | xsd:token
<span id="ReasonText">ReasonText</span> | xsd:string
<span id="ConditionValidationDocumentStatusCode">ConditionValidationDocumentStatusCode</span> | xsd:token
<span id="ChangerNameText">ChangerNameText</span> | xsd:string
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="LoadingReportedTransportEvent">LoadingReportedTransportEvent</span> | [edi3:Event](#Event)
<span id="ConditionCode">ConditionCode</span> | xsd:token
<span id="SequenceNumeric">SequenceNumeric</span> | xsd:decimal
<span id="ReferenceDateTime">ReferenceDateTime</span> | xsd:dateTime
<span id="ConditionFinancingStatusCode">ConditionFinancingStatusCode</span> | xsd:token
<span id="SpecifiedLogisticsLocation">SpecifiedLogisticsLocation</span> | [edi3:Location](#Location)
<span id="ConditionCancellationDocumentStatusCode">ConditionCancellationDocumentStatusCode</span> | xsd:token
<span id="ChangedDateTime">ChangedDateTime</span> | xsd:dateTime
<span id="ReasonFinancingStatusReasonCode">ReasonFinancingStatusReasonCode</span> | xsd:token
<span id="ConditionLogisticsStatusCode">ConditionLogisticsStatusCode</span> | xsd:token
<span id="ArrivalReportedTransportEvent">ArrivalReportedTransportEvent</span> | [edi3:Event](#Event)
<span id="ReasonCode">ReasonCode</span> | xsd:token


<h1 id="Adjustment">Adjustment</h1>

Type: rdf:Class

Comments: <br/>A correction or modification to reflect actual financial conditions.<br/>A correction or modification to reflect actual delivery conditions.<br/>

Properties: 

Name | Type 
-|-
<span id="ActualQuantity">ActualQuantity</span> | xsd:decimal
<span id="ReasonText">ReasonText</span> | xsd:string
<span id="ActualAmount">ActualAmount</span> | xsd:decimal
<span id="DirectionAccountingDebitCreditStatusCode">DirectionAccountingDebitCreditStatusCode</span> | xsd:token
<span id="InvoiceReferenceReferencedDocument">InvoiceReferenceReferencedDocument</span> | [edi3:Document](#Document)
<span id="ClaimRelatedTradeParty">ClaimRelatedTradeParty</span> | [edi3:Party](#Party)
<span id="ReasonAdjustmentReasonCode">ReasonAdjustmentReasonCode</span> | xsd:token
<span id="ReasonCode">ReasonCode</span> | xsd:token


<h1 id="InstalmentPlan">InstalmentPlan</h1>

Type: rdf:Class

Comments: A plan for paying a total sum of money by several payments made over a period of time.

Properties: 

Name | Type 
-|-


<h1 id="RegulatoryProcedure">RegulatoryProcedure</h1>

Type: rdf:Class

Comments: A set of formal steps to satisfy a cross-border regulation, law or convention.

Properties: 

Name | Type 
-|-
<span id="CertificationBasisText">CertificationBasisText</span> | xsd:string
<span id="ExitCustomsOfficeSpecifiedLogisticsLocation">ExitCustomsOfficeSpecifiedLogisticsLocation</span> | [edi3:Location](#Location)
<span id="AnnualQuotaQuantity">AnnualQuotaQuantity</span> | xsd:decimal
<span id="EntryCustomsOfficeSpecifiedLogisticsLocation">EntryCustomsOfficeSpecifiedLogisticsLocation</span> | [edi3:Location](#Location)
<span id="RequiredCertificationTestSpecificationReport">RequiredCertificationTestSpecificationReport</span> | [edi3:TestSpecificationReport](#TestSpecificationReport)
<span id="ValuationBasisAmount">ValuationBasisAmount</span> | xsd:decimal
<span id="TariffQuantity">TariffQuantity</span> | xsd:decimal
<span id="ApplicableTradeTax">ApplicableTradeTax</span> | [edi3:Tax](#Tax)
<span id="ExportLicenceControlClassificationIdentifier">ExportLicenceControlClassificationIdentifier</span> | xsd:token
<span id="DeclarationLodgementLogisticsLocation">DeclarationLodgementLogisticsLocation</span> | [edi3:Location](#Location)
<span id="ApplicableTradeCurrencyExchange">ApplicableTradeCurrencyExchange</span> | [edi3:CurrencyExchange](#CurrencyExchange)
<span id="TypeCode">TypeCode</span> | xsd:token
<span id="DeclarantAssignedDeclarationIdentifier">DeclarantAssignedDeclarationIdentifier</span> | xsd:token
<span id="ExportCustomsOfficeSpecifiedLogisticsLocation">ExportCustomsOfficeSpecifiedLogisticsLocation</span> | [edi3:Location](#Location)
<span id="PaymentMethodPaymentMethodCode">PaymentMethodPaymentMethodCode</span> | xsd:token
<span id="TransitReleaseCustomsOfficeSpecifiedLogisticsLocation">TransitReleaseCustomsOfficeSpecifiedLogisticsLocation</span> | [edi3:Location](#Location)
<span id="GuaranteeCode">GuaranteeCode</span> | xsd:token
<span id="PaymentOfficeLogisticsLocation">PaymentOfficeLogisticsLocation</span> | [edi3:Location](#Location)
<span id="ReportedLogisticsStatus">ReportedLogisticsStatus</span> | [edi3:Status](#Status)
<span id="TransactionNatureCode">TransactionNatureCode</span> | xsd:token
<span id="RemarkText">RemarkText</span> | xsd:string
<span id="RequiredLogisticsSeal">RequiredLogisticsSeal</span> | [edi3:Seal](#Seal)
<span id="ConsignmentDestinationSpecifiedLogisticsLocation">ConsignmentDestinationSpecifiedLogisticsLocation</span> | [edi3:Location](#Location)
<span id="TotalChargeAmount">TotalChargeAmount</span> | xsd:decimal
<span id="CategoryCode">CategoryCode</span> | xsd:token
<span id="ResponsibleAgencyActionGovernmentActionCode">ResponsibleAgencyActionGovernmentActionCode</span> | xsd:token
<span id="ApplicableSpecifiedPeriod">ApplicableSpecifiedPeriod</span> | [edi3:Period](#Period)
<span id="RequiredAppliedChemicalTreatment">RequiredAppliedChemicalTreatment</span> | [edi3:ChemicalTreatment](#ChemicalTreatment)
<span id="ResponsibleAgencyInvolvementResponsibleGovernmentAgencyInvolvementCode">ResponsibleAgencyInvolvementResponsibleGovernmentAgencyInvolvementCode</span> | xsd:token
<span id="QuotaIdentifier">QuotaIdentifier</span> | xsd:token
<span id="TotalConsignmentValueAmount">TotalConsignmentValueAmount</span> | xsd:decimal
<span id="BorderClearanceTransportInstructions">BorderClearanceTransportInstructions</span> | [edi3:Instructions](#Instructions)
<span id="TariffAmount">TariffAmount</span> | xsd:decimal
<span id="ImmediatePayableTotalChargeAmount">ImmediatePayableTotalChargeAmount</span> | xsd:decimal
<span id="ExemptionClaimantTradeParty">ExemptionClaimantTradeParty</span> | [edi3:Party](#Party)
<span id="StatementNote">StatementNote</span> | [edi3:Note](#Note)
<span id="PerformanceDateTime">PerformanceDateTime</span> | xsd:dateTime
<span id="DeferredPayableTotalChargeAmount">DeferredPayableTotalChargeAmount</span> | xsd:decimal
<span id="TariffDeductionQuantity">TariffDeductionQuantity</span> | xsd:decimal
<span id="TransportMovementTypeTransportMovementTypeCode">TransportMovementTypeTransportMovementTypeCode</span> | xsd:token
<span id="ResponsibleAgencyResponsibleGovernmentAgencyCode">ResponsibleAgencyResponsibleGovernmentAgencyCode</span> | xsd:token
<span id="GuaranteeText">GuaranteeText</span> | xsd:string
<span id="TreatmentTransportEvent">TreatmentTransportEvent</span> | [edi3:Event](#Event)
<span id="RequestOverrideCode">RequestOverrideCode</span> | xsd:token
<span id="ControlRequirementIndicator">ControlRequirementIndicator</span> | xsd:boolean
<span id="PreviousReferencedDocument">PreviousReferencedDocument</span> | [edi3:Document](#Document)
<span id="ImportCustomsOfficeSpecifiedLogisticsLocation">ImportCustomsOfficeSpecifiedLogisticsLocation</span> | [edi3:Location](#Location)
<span id="ReferencedReferencedDocument">ReferencedReferencedDocument</span> | [edi3:Document](#Document)
<span id="UsedToDateQuotaQuantity">UsedToDateQuotaQuantity</span> | xsd:decimal
<span id="RegisteredDeferredPaymentPayerIdentifier">RegisteredDeferredPaymentPayerIdentifier</span> | xsd:token
<span id="AcquisitionDateTime">AcquisitionDateTime</span> | xsd:dateTime
<span id="NonTariffChargeAmount">NonTariffChargeAmount</span> | xsd:decimal
<span id="ControlResultText">ControlResultText</span> | xsd:string
<span id="AmendmentReasonCode">AmendmentReasonCode</span> | xsd:token
<span id="SpecifiedCrossBorderCustomsProcedure">SpecifiedCrossBorderCustomsProcedure</span> | [edi3:CustomsProcedure](#CustomsProcedure)
<span id="DeferredPaymentMethodIndicator">DeferredPaymentMethodIndicator</span> | xsd:boolean
<span id="ExaminationTransportEvent">ExaminationTransportEvent</span> | [edi3:Event](#Event)
<span id="TransitCustomsOfficeSpecifiedLogisticsLocation">TransitCustomsOfficeSpecifiedLogisticsLocation</span> | [edi3:Location](#Location)
<span id="PreviousProcedureTypeCode">PreviousProcedureTypeCode</span> | xsd:token
<span id="SpecifiedDebtorFinancialAccount">SpecifiedDebtorFinancialAccount</span> | [edi3:FinancialAccount](#FinancialAccount)
<span id="GoodsStatusCode">GoodsStatusCode</span> | xsd:token
<span id="ControlStartDateConfirmationIndicator">ControlStartDateConfirmationIndicator</span> | xsd:boolean


<h1 id="Instructions">Instructions</h1>

Type: rdf:Class

Comments: <br/>The procedures to follow for returnable assets, such as reusable packaging (pallets, crates).<br/>Instructions for a period of imposed isolation or detention.<br/>Temperature setting related information of an instructive nature.<br/>Transport information of an instructive nature.<br/>A set of instructions detailing how to properly dispose of a material.<br/>Delivery information of an instructive nature.<br/>Instructions related to the action or process of conveyance.<br/>Handling information of an instructive nature.<br/>

Properties: 

Name | Type 
-|-
<span id="ApplicableTransportSettingTemperature">ApplicableTransportSettingTemperature</span> | [edi3:Temperature](#Temperature)
<span id="DepositValueSpecifiedAmount">DepositValueSpecifiedAmount</span> | xsd:decimal
<span id="HandlingCode">HandlingCode</span> | xsd:token
<span id="RecyclingProcedureText">RecyclingProcedureText</span> | xsd:string
<span id="RecyclingDescriptionCode">RecyclingDescriptionCode</span> | xsd:token
<span id="MaximumStackabilityWeightApplicableWeightUnitMeasure">MaximumStackabilityWeightApplicableWeightUnitMeasure</span> | xsd:decimal
<span id="MaximumStorageHumidityApplicableMeasure">MaximumStorageHumidityApplicableMeasure</span> | xsd:decimal
<span id="DepositValueValiditySpecifiedPeriod">DepositValueValiditySpecifiedPeriod</span> | [edi3:Period](#Period)
<span id="MarketDeliveryApplicableInstructedTemperature">MarketDeliveryApplicableInstructedTemperature</span> | [edi3:Temperature](#Temperature)
<span id="MaterialIdentifier">MaterialIdentifier</span> | xsd:token
<span id="TermsAndConditionsDescriptionText">TermsAndConditionsDescriptionText</span> | xsd:string
<span id="DeliveryApplicableInstructedTemperature">DeliveryApplicableInstructedTemperature</span> | [edi3:Temperature](#Temperature)
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="StorageApplicableInstructedTemperature">StorageApplicableInstructedTemperature</span> | [edi3:Temperature](#Temperature)
<span id="ProcedureText">ProcedureText</span> | xsd:string
<span id="MaximumStackabilityApplicableQuantity">MaximumStackabilityApplicableQuantity</span> | xsd:decimal
<span id="HandlingText">HandlingText</span> | xsd:string
<span id="MinimumStorageHumidityApplicableMeasure">MinimumStorageHumidityApplicableMeasure</span> | xsd:decimal
<span id="TermsAndConditionsDescriptionCode">TermsAndConditionsDescriptionCode</span> | xsd:token


<h1 id="Booking">Booking</h1>

Type: rdf:Class

Comments: A result of a financial transaction recorded within a financial account.

Properties: 

Name | Type 
-|-
<span id="ActualFormattedDateTime">ActualFormattedDateTime</span> | xsd:dateTime
<span id="CreditFormattedDateTime">CreditFormattedDateTime</span> | xsd:dateTime


<h1 id="AccountingAccount">AccountingAccount</h1>

Type: rdf:Class

Comments: A specific trade account for recording debits and credits to general accounting, cost accounting or budget accounting.

Properties: 

Name | Type 
-|-
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="NameText">NameText</span> | xsd:string
<span id="CostReferenceDimensionPatternText">CostReferenceDimensionPatternText</span> | xsd:string
<span id="TypeAccountingAccountTypeCode">TypeAccountingAccountTypeCode</span> | xsd:token
<span id="AmountTypeAccountingAmountTypeCode">AmountTypeAccountingAmountTypeCode</span> | xsd:token


<h1 id="GeographicalMultiPoint">GeographicalMultiPoint</h1>

Type: rdf:Class

Comments: A collection of points, on the surface of the Earth (reference ISO 19136).

Properties: 

Name | Type 
-|-
<span id="MemberSpecifiedGeographicalPoint">MemberSpecifiedGeographicalPoint</span> | [edi3:GeographicalPoint](#GeographicalPoint)
<span id="AssociatedSpecifiedGeographicalObjectCharacteristic">AssociatedSpecifiedGeographicalObjectCharacteristic</span> | [edi3:GeographicalObjectCharacteristic](#GeographicalObjectCharacteristic)


<h1 id="PaymentMeans">PaymentMeans</h1>

Type: rdf:Class

Comments: The means by which a payment will be or has been made for trade settlement purposes.

Properties: 

Name | Type 
-|-
<span id="InformationText">InformationText</span> | xsd:string
<span id="PaymentMethodCode">PaymentMethodCode</span> | xsd:token
<span id="PayeePartyCreditorFinancialAccount">PayeePartyCreditorFinancialAccount</span> | [edi3:FinancialAccount](#FinancialAccount)
<span id="GuaranteeMethodPaymentGuaranteeMeansCode">GuaranteeMethodPaymentGuaranteeMeansCode</span> | xsd:token
<span id="PayerSpecifiedDebtorFinancialInstitution">PayerSpecifiedDebtorFinancialInstitution</span> | [edi3:FinancialInstitution](#FinancialInstitution)
<span id="PayerPartyDebtorFinancialAccount">PayerPartyDebtorFinancialAccount</span> | [edi3:FinancialAccount](#FinancialAccount)
<span id="PayeeSpecifiedCreditorFinancialInstitution">PayeeSpecifiedCreditorFinancialInstitution</span> | [edi3:FinancialInstitution](#FinancialInstitution)
<span id="PaymentChannelPaymentMeansChannelCode">PaymentChannelPaymentMeansChannelCode</span> | xsd:token
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="SpecifiedCreditorFinancialAccount">SpecifiedCreditorFinancialAccount</span> | [edi3:FinancialAccount](#FinancialAccount)
<span id="ApplicableTradeSettlementFinancialCard">ApplicableTradeSettlementFinancialCard</span> | [edi3:FinancialCard](#FinancialCard)


<h1 id="Project">Project</h1>

Type: rdf:Class

Comments: An endeavour carefully planned to achieve a procurement of goods, works and service.

Properties: 

Name | Type 
-|-
<span id="NetBudgetAmount">NetBudgetAmount</span> | xsd:decimal
<span id="SubWorksTypeCode">SubWorksTypeCode</span> | xsd:token
<span id="WorksTypeCode">WorksTypeCode</span> | xsd:token
<span id="TypeCode">TypeCode</span> | xsd:token
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="TotalBudgetAmount">TotalBudgetAmount</span> | xsd:decimal
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="NameText">NameText</span> | xsd:string


<h1 id="Qualification">Qualification</h1>

Type: rdf:Class

Comments: An academic achievement that is officially recognized.

Properties: 

Name | Type 
-|-
<span id="AbbreviatedNameText">AbbreviatedNameText</span> | xsd:string


<h1 id="Chemical">Chemical</h1>

Type: rdf:Class

Comments: Any clearly defined substance having a defined molecular composition.

Properties: 

Name | Type 
-|-
<span id="CommonNameText">CommonNameText</span> | xsd:string
<span id="TypeCode">TypeCode</span> | xsd:token
<span id="FormulaDescriptionText">FormulaDescriptionText</span> | xsd:string
<span id="MolecularWeightMeasure">MolecularWeightMeasure</span> | xsd:decimal
<span id="SynonymNameText">SynonymNameText</span> | xsd:string
<span id="ScientificNameText">ScientificNameText</span> | xsd:string


<h1 id="FinancialAccount">FinancialAccount</h1>

Type: rdf:Class

Comments: <br/>A specific business arrangement whereby debits arising from transactions are recorded.<br/>A specific business arrangement whereby credits arising from transactions are recorded.<br/>A financial account used internally by a bank to manage the line of credit granted to financing requesting party.<br/>

Properties: 

Name | Type 
-|-
<span id="CurrencyCurrencyCode">CurrencyCurrencyCode</span> | xsd:token
<span id="ProprietaryAccountNameText">ProprietaryAccountNameText</span> | xsd:string
<span id="UPICIdentificationIdentifier">UPICIdentificationIdentifier</span> | xsd:token
<span id="IBANIdentificationIdentifier">IBANIdentificationIdentifier</span> | xsd:token
<span id="TypeCode">TypeCode</span> | xsd:token
<span id="TypeCashAccountTypeCode">TypeCashAccountTypeCode</span> | xsd:token
<span id="BBANIdentificationIdentifier">BBANIdentificationIdentifier</span> | xsd:token
<span id="ProprietaryIdentificationIdentifier">ProprietaryIdentificationIdentifier</span> | xsd:token
<span id="AccountNameText">AccountNameText</span> | xsd:string
<span id="ProprietaryTypeText">ProprietaryTypeText</span> | xsd:string


<h1 id="Note">Note</h1>

Type: rdf:Class

Comments: A textual or coded description, such as a remark or additional information.

Properties: 

Name | Type 
-|-
<span id="SubjectCode">SubjectCode</span> | xsd:token
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="ContentText">ContentText</span> | xsd:string
<span id="SubjectText">SubjectText</span> | xsd:string


<h1 id="TradeDelivery">TradeDelivery</h1>

Type: rdf:Class

Comments: <br/>Shipping arrangements and movement of products and or services including despatch and delivery at a line level.<br/>Shipping arrangements and movement of products and or services including despatch and delivery at a header level.<br/>Supply chain shipping arrangements and movement of products and or services including despatch and delivery.<br/>

Properties: 

Name | Type 
-|-
<span id="FormattedPickUpAvailabilityFormattedDateTime">FormattedPickUpAvailabilityFormattedDateTime</span> | xsd:dateTime
<span id="PerPackageUnitQuantity">PerPackageUnitQuantity</span> | xsd:decimal
<span id="NetWeightWeightUnitMeasure">NetWeightWeightUnitMeasure</span> | xsd:decimal
<span id="UnavailableQuantity">UnavailableQuantity</span> | xsd:decimal
<span id="StatusCode">StatusCode</span> | xsd:token
<span id="DueInForecastedQuantity">DueInForecastedQuantity</span> | xsd:decimal
<span id="FinalDeliveryIndicator">FinalDeliveryIndicator</span> | xsd:boolean
<span id="ConfirmedDespatchSupplyChainEvent">ConfirmedDespatchSupplyChainEvent</span> | [edi3:Event](#Event)
<span id="DisposalTradeParty">DisposalTradeParty</span> | [edi3:Party](#Party)
<span id="DeliveryNoteReferencedDocument">DeliveryNoteReferencedDocument</span> | [edi3:Document](#Document)
<span id="ConsumptionSupplyChainSchedule">ConsumptionSupplyChainSchedule</span> | [edi3:Schedule](#Schedule)
<span id="ModificationForecastedQuantity">ModificationForecastedQuantity</span> | xsd:decimal
<span id="GoodsOwnershipChangeFormattedDateTime">GoodsOwnershipChangeFormattedDateTime</span> | xsd:dateTime
<span id="ReverseBilledQuantity">ReverseBilledQuantity</span> | xsd:decimal
<span id="RequestedDeliverySupplyChainEvent">RequestedDeliverySupplyChainEvent</span> | [edi3:Event](#Event)
<span id="DueInAvailableQuantity">DueInAvailableQuantity</span> | xsd:decimal
<span id="ReturnedQuantity">ReturnedQuantity</span> | xsd:decimal
<span id="RemainingRequestedQuantity">RemainingRequestedQuantity</span> | xsd:decimal
<span id="ApplicableTransportDangerousGoods">ApplicableTransportDangerousGoods</span> | [edi3:DangerousGoods](#DangerousGoods)
<span id="DespatchAdviceReferencedDocument">DespatchAdviceReferencedDocument</span> | [edi3:Document](#Document)
<span id="DueInReturnedQuantity">DueInReturnedQuantity</span> | xsd:decimal
<span id="SpecifiedLogisticsPackage">SpecifiedLogisticsPackage</span> | [edi3:Package](#Package)
<span id="GoodsPhysicalStateTypeText">GoodsPhysicalStateTypeText</span> | xsd:string
<span id="AvailableSupplyChainInventory">AvailableSupplyChainInventory</span> | [edi3:Inventory](#Inventory)
<span id="RequestedDespatchSupplyChainEvent">RequestedDespatchSupplyChainEvent</span> | [edi3:Event](#Event)
<span id="GoodsPhysicalStateDescriptionCode">GoodsPhysicalStateDescriptionCode</span> | xsd:token
<span id="EconomicOrderQuantity">EconomicOrderQuantity</span> | xsd:decimal
<span id="RequestedQuantity">RequestedQuantity</span> | xsd:decimal
<span id="DeliverySupplyChainSchedule">DeliverySupplyChainSchedule</span> | [edi3:Schedule](#Schedule)
<span id="SpecifiedDeliveryAdjustment">SpecifiedDeliveryAdjustment</span> | [edi3:Adjustment](#Adjustment)
<span id="PlannedReleaseSupplyChainEvent">PlannedReleaseSupplyChainEvent</span> | [edi3:Event](#Event)
<span id="ConsignmentSupplyChainInventory">ConsignmentSupplyChainInventory</span> | [edi3:Inventory](#Inventory)
<span id="GrossWeightWeightUnitMeasure">GrossWeightWeightUnitMeasure</span> | xsd:decimal
<span id="UltimateShipToDeliveryFormattedDateTime">UltimateShipToDeliveryFormattedDateTime</span> | xsd:dateTime
<span id="DestroyedQuantity">DestroyedQuantity</span> | xsd:decimal
<span id="PlannedPickUpSupplyChainEvent">PlannedPickUpSupplyChainEvent</span> | [edi3:Event](#Event)
<span id="ChargeFreeQuantity">ChargeFreeQuantity</span> | xsd:decimal
<span id="QuantityVariationTypeCode">QuantityVariationTypeCode</span> | xsd:token
<span id="UltimateShipToTradeParty">UltimateShipToTradeParty</span> | [edi3:Party](#Party)
<span id="CancelledQuantity">CancelledQuantity</span> | xsd:decimal
<span id="AcceptanceSupplyChainEvent">AcceptanceSupplyChainEvent</span> | [edi3:Event](#Event)
<span id="QuantityVariationReasonCode">QuantityVariationReasonCode</span> | xsd:token
<span id="SpecifiedDeliveryInstructions">SpecifiedDeliveryInstructions</span> | [edi3:Instructions](#Instructions)
<span id="GFMTransferRejectedQuantity">GFMTransferRejectedQuantity</span> | xsd:decimal
<span id="FormattedPickUpAvailabilityDateTime">FormattedPickUpAvailabilityDateTime</span> | xsd:dateTime
<span id="PlannedDeliverySupplyChainEvent">PlannedDeliverySupplyChainEvent</span> | [edi3:Event](#Event)
<span id="RelatedSupplyChainConsignment">RelatedSupplyChainConsignment</span> | [edi3:Consignment](#Consignment)
<span id="NetVolumeVolumeUnitMeasure">NetVolumeVolumeUnitMeasure</span> | xsd:decimal
<span id="BuyerOrderFormattedDateTime">BuyerOrderFormattedDateTime</span> | xsd:dateTime
<span id="ReceiptSupplyChainSchedule">ReceiptSupplyChainSchedule</span> | [edi3:Schedule](#Schedule)
<span id="ShipToTradeParty">ShipToTradeParty</span> | [edi3:Party](#Party)
<span id="LatestDespatchedQuantity">LatestDespatchedQuantity</span> | xsd:decimal
<span id="ProjectedSupplyChainSupplyPlan">ProjectedSupplyChainSupplyPlan</span> | [edi3:SupplyPlan](#SupplyPlan)
<span id="InventoryManagerTradeParty">InventoryManagerTradeParty</span> | [edi3:Party](#Party)
<span id="ReceivedQuantity">ReceivedQuantity</span> | xsd:decimal
<span id="IndividualPackageQuantity">IndividualPackageQuantity</span> | xsd:decimal
<span id="FinalDestinationTradeCountry">FinalDestinationTradeCountry</span> | [edi3:Country](#Country)
<span id="QuantityDiscrepancyNatureCode">QuantityDiscrepancyNatureCode</span> | xsd:token
<span id="ShipFromTradeParty">ShipFromTradeParty</span> | [edi3:Party](#Party)
<span id="SupplySpecifiedSupplyChainSchedule">SupplySpecifiedSupplyChainSchedule</span> | [edi3:Schedule](#Schedule)
<span id="CustomerSupplyChainInventory">CustomerSupplyChainInventory</span> | [edi3:Inventory](#Inventory)
<span id="PlannedShipFromDeliverySupplyChainEvent">PlannedShipFromDeliverySupplyChainEvent</span> | [edi3:Event](#Event)
<span id="TheoreticalWeightWeightUnitMeasure">TheoreticalWeightWeightUnitMeasure</span> | xsd:decimal
<span id="IncludedSupplyChainPackaging">IncludedSupplyChainPackaging</span> | [edi3:Packaging](#Packaging)
<span id="AvailableQuantity">AvailableQuantity</span> | xsd:decimal
<span id="ActualDespatchSupplyChainEvent">ActualDespatchSupplyChainEvent</span> | [edi3:Event](#Event)
<span id="ConsumptionReportReferencedDocument">ConsumptionReportReferencedDocument</span> | [edi3:Document](#Document)
<span id="BilledQuantity">BilledQuantity</span> | xsd:decimal
<span id="TurnInReceivedQuantity">TurnInReceivedQuantity</span> | xsd:decimal
<span id="PlannedSupplyChainConsignment">PlannedSupplyChainConsignment</span> | [edi3:Consignment](#Consignment)
<span id="GoodsReceiptNoteReferencedDocument">GoodsReceiptNoteReferencedDocument</span> | [edi3:Document](#Document)
<span id="InformationNote">InformationNote</span> | [edi3:Note](#Note)
<span id="PackageQuantity">PackageQuantity</span> | xsd:decimal
<span id="PlannedDespatchSupplyChainEvent">PlannedDespatchSupplyChainEvent</span> | [edi3:Event](#Event)
<span id="SpecifiedHandlingInstructions">SpecifiedHandlingInstructions</span> | [edi3:Instructions](#Instructions)
<span id="ReceivingAdviceReferencedDocument">ReceivingAdviceReferencedDocument</span> | [edi3:Document](#Document)
<span id="PreviousDeliverySupplyChainEvent">PreviousDeliverySupplyChainEvent</span> | [edi3:Event](#Event)
<span id="PartialDeliveryAllowedIndicator">PartialDeliveryAllowedIndicator</span> | xsd:boolean
<span id="LogisticsServiceProviderTradeParty">LogisticsServiceProviderTradeParty</span> | [edi3:Party](#Party)
<span id="UltimateShipToDeliverySupplyChainEvent">UltimateShipToDeliverySupplyChainEvent</span> | [edi3:Event](#Event)
<span id="ProductUnitQuantity">ProductUnitQuantity</span> | xsd:decimal
<span id="FormattedUltimateShipToDeliveryFormattedDateTime">FormattedUltimateShipToDeliveryFormattedDateTime</span> | xsd:dateTime
<span id="GoodsPhysicalStateDescriptionText">GoodsPhysicalStateDescriptionText</span> | xsd:string
<span id="ConfirmedPickUpSupplyChainEvent">ConfirmedPickUpSupplyChainEvent</span> | [edi3:Event](#Event)
<span id="ActualUnloadingSupplyChainEvent">ActualUnloadingSupplyChainEvent</span> | [edi3:Event](#Event)
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="DespatchSupplyChainSchedule">DespatchSupplyChainSchedule</span> | [edi3:Schedule](#Schedule)
<span id="RejectedQuantity">RejectedQuantity</span> | xsd:decimal
<span id="FullyDeliveredIndicator">FullyDeliveredIndicator</span> | xsd:boolean
<span id="ActualReceiptSupplyChainEvent">ActualReceiptSupplyChainEvent</span> | [edi3:Event](#Event)
<span id="GrossVolumeVolumeUnitMeasure">GrossVolumeVolumeUnitMeasure</span> | xsd:decimal
<span id="DueInRequestedQuantity">DueInRequestedQuantity</span> | xsd:decimal
<span id="GoodsPhysicalStateTypeCode">GoodsPhysicalStateTypeCode</span> | xsd:token
<span id="UtilizedReferencedLogisticsTransportEquipment">UtilizedReferencedLogisticsTransportEquipment</span> | [edi3:TransportEquipment](#TransportEquipment)
<span id="ChargeableWeightWeightUnitMeasure">ChargeableWeightWeightUnitMeasure</span> | xsd:decimal
<span id="AdditionalReferencedDocument">AdditionalReferencedDocument</span> | [edi3:Document](#Document)
<span id="UsedLogisticsLabel">UsedLogisticsLabel</span> | [edi3:Label](#Label)
<span id="PlannedShipToDeliverySupplyChainEvent">PlannedShipToDeliverySupplyChainEvent</span> | [edi3:Event](#Event)
<span id="ActualDeliverySupplyChainEvent">ActualDeliverySupplyChainEvent</span> | [edi3:Event](#Event)
<span id="ActualPickUpSupplyChainEvent">ActualPickUpSupplyChainEvent</span> | [edi3:Event](#Event)
<span id="DespatchedQuantity">DespatchedQuantity</span> | xsd:decimal
<span id="OrderSupplyChainSchedule">OrderSupplyChainSchedule</span> | [edi3:Schedule](#Schedule)
<span id="OrderQuantity">OrderQuantity</span> | xsd:decimal
<span id="AgreedQuantity">AgreedQuantity</span> | xsd:decimal
<span id="ShipmentScheduleReferencedDocument">ShipmentScheduleReferencedDocument</span> | [edi3:Document](#Document)
<span id="QuantityVariationReasonText">QuantityVariationReasonText</span> | xsd:string
<span id="SubordinateIdentificationIdentifier">SubordinateIdentificationIdentifier</span> | xsd:token
<span id="OverDeliveryAllowedIndicator">OverDeliveryAllowedIndicator</span> | xsd:boolean
<span id="ConfirmedReleaseSupplyChainEvent">ConfirmedReleaseSupplyChainEvent</span> | [edi3:Event](#Event)
<span id="ConfirmedDeliverySupplyChainEvent">ConfirmedDeliverySupplyChainEvent</span> | [edi3:Event](#Event)
<span id="SpecifiedSupplyChainSchedule">SpecifiedSupplyChainSchedule</span> | [edi3:Schedule](#Schedule)
<span id="PackingListReferencedDocument">PackingListReferencedDocument</span> | [edi3:Document](#Document)


<h1 id="Country">Country</h1>

Type: rdf:Class

Comments: The area of land that belongs to a nation together with its properties, such as population, political organization, etc., used or referenced for trade purposes.

Properties: 

Name | Type 
-|-
<span id="NameText">NameText</span> | xsd:string
<span id="IdentificationCountryIdentifier">IdentificationCountryIdentifier</span> | xsd:token


<h1 id="Seal">Seal</h1>

Type: rdf:Class

Comments: A device used to secure an object and protect it from unauthorized entry or tampering during transport or other logistics operations.

Properties: 

Name | Type 
-|-
<span id="TypeSealTypeCode">TypeSealTypeCode</span> | xsd:token
<span id="SealingPartyRoleSealingPartyRoleCode">SealingPartyRoleSealingPartyRoleCode</span> | xsd:token
<span id="MaximumIdentificationIdentifier">MaximumIdentificationIdentifier</span> | xsd:token
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="IssuingTradeParty">IssuingTradeParty</span> | [edi3:Party](#Party)


<h1 id="Package">Package</h1>

Type: rdf:Class

Comments: <br/>A self-contained wrapping or container within which goods can be contained for logistics purposes, such as a box or a barrel which can be filled, partially filled or empty.<br/>A referenced self-contained wrapping or container within which goods can be contained for logistics purposes.<br/>

Properties: 

Name | Type 
-|-
<span id="PerPackageUnitQuantity">PerPackageUnitQuantity</span> | xsd:decimal
<span id="NetWeightWeightUnitMeasure">NetWeightWeightUnitMeasure</span> | xsd:decimal
<span id="TypePackageTypeCode">TypePackageTypeCode</span> | xsd:token
<span id="InformationText">InformationText</span> | xsd:string
<span id="NominalGrossVolumeVolumeUnitMeasure">NominalGrossVolumeVolumeUnitMeasure</span> | xsd:decimal
<span id="GlobalIdentificationIdentifier">GlobalIdentificationIdentifier</span> | xsd:token
<span id="DespatchNoteAssociatedReferencedDocument">DespatchNoteAssociatedReferencedDocument</span> | [edi3:Document](#Document)
<span id="TypeText">TypeText</span> | xsd:string
<span id="GrossWeightWeightUnitMeasure">GrossWeightWeightUnitMeasure</span> | xsd:decimal
<span id="LinearSpatialDimension">LinearSpatialDimension</span> | [edi3:Dimension](#Dimension)
<span id="ReturnableIndicator">ReturnableIndicator</span> | xsd:boolean
<span id="ItemQuantity">ItemQuantity</span> | xsd:decimal
<span id="GrossWeightMeasure">GrossWeightMeasure</span> | xsd:decimal
<span id="NetWeightMeasure">NetWeightMeasure</span> | xsd:decimal
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="UsedSupplyChainPackaging">UsedSupplyChainPackaging</span> | [edi3:Packaging](#Packaging)
<span id="SequenceNumeric">SequenceNumeric</span> | xsd:decimal
<span id="IncludedSupplyChainTradeLineItem">IncludedSupplyChainTradeLineItem</span> | [edi3:TradeLineItem](#TradeLineItem)
<span id="NominalGrossVolumeMeasure">NominalGrossVolumeMeasure</span> | xsd:decimal
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="GrossVolumeVolumeUnitMeasure">GrossVolumeVolumeUnitMeasure</span> | xsd:decimal
<span id="ParentIdentificationIdentifier">ParentIdentificationIdentifier</span> | xsd:token
<span id="SeriesEndIdentificationIdentifier">SeriesEndIdentificationIdentifier</span> | xsd:token
<span id="ColourCode">ColourCode</span> | xsd:token
<span id="PhysicalLogisticsShippingMarks">PhysicalLogisticsShippingMarks</span> | [edi3:ShippingMarks](#ShippingMarks)
<span id="NominalGrossWeightMeasure">NominalGrossWeightMeasure</span> | xsd:decimal
<span id="SeriesStartIdentificationIdentifier">SeriesStartIdentificationIdentifier</span> | xsd:token
<span id="LevelPackagingLevelCode">LevelPackagingLevelCode</span> | xsd:token
<span id="GrossVolumeMeasure">GrossVolumeMeasure</span> | xsd:decimal


<h1 id="Person">Person</h1>

Type: rdf:Class

Comments: <br/>A transport related person, such as a member of a crew or a passenger.<br/>A person who is authorized to sign a document, such as a customs officer or other government official.<br/>An individual human being in a position to give assistance or information.<br/>

Properties: 

Name | Type 
-|-
<span id="DeclaredSpecifiedPersonalEffects">DeclaredSpecifiedPersonalEffects</span> | [edi3:PersonalEffects](#PersonalEffects)
<span id="RoleText">RoleText</span> | xsd:string
<span id="BirthCountryIdentifier">BirthCountryIdentifier</span> | xsd:token
<span id="SpecifiedEmployerIdentity">SpecifiedEmployerIdentity</span> | [edi3:Identity](#Identity)
<span id="FamilyNameText">FamilyNameText</span> | xsd:string
<span id="LandlineTelephoneUniversalCommunication">LandlineTelephoneUniversalCommunication</span> | [edi3:Communication](#Communication)
<span id="EmbarkationLogisticsLocation">EmbarkationLogisticsLocation</span> | [edi3:Location](#Location)
<span id="GivenNameText">GivenNameText</span> | xsd:string
<span id="TitleTitleCode">TitleTitleCode</span> | xsd:token
<span id="ResidenceCountryCountryIdentifier">ResidenceCountryCountryIdentifier</span> | xsd:token
<span id="SpecifiedPersonIdentity">SpecifiedPersonIdentity</span> | [edi3:Identity](#Identity)
<span id="EmailURIUniversalCommunication">EmailURIUniversalCommunication</span> | [edi3:Communication](#Communication)
<span id="DisembarkationLogisticsLocation">DisembarkationLogisticsLocation</span> | [edi3:Location](#Location)
<span id="MobileTelephoneUniversalCommunication">MobileTelephoneUniversalCommunication</span> | [edi3:Communication](#Communication)
<span id="TelephoneTelecommunicationCommunication">TelephoneTelecommunicationCommunication</span> | [edi3:Communication](#Communication)
<span id="BirthDateTime">BirthDateTime</span> | xsd:dateTime
<span id="MiddleNameText">MiddleNameText</span> | xsd:string
<span id="GenderCode">GenderCode</span> | xsd:token
<span id="SpecifiedBirthAddress">SpecifiedBirthAddress</span> | [edi3:Address](#Address)
<span id="CategoryCode">CategoryCode</span> | xsd:token
<span id="RoleCode">RoleCode</span> | xsd:token
<span id="BirthplaceNameText">BirthplaceNameText</span> | xsd:string
<span id="EmailURIEmailCommunication">EmailURIEmailCommunication</span> | [edi3:Communication](#Communication)
<span id="SpecifiedTaxRegistration">SpecifiedTaxRegistration</span> | [edi3:Registration](#Registration)
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="NationalityTradeCountry">NationalityTradeCountry</span> | [edi3:Country](#Country)
<span id="NameText">NameText</span> | xsd:string
<span id="InTransitIndicator">InTransitIndicator</span> | xsd:boolean
<span id="TravelIdentityReferencedDocument">TravelIdentityReferencedDocument</span> | [edi3:Document](#Document)
<span id="FaxTelecommunicationCommunication">FaxTelecommunicationCommunication</span> | [edi3:Communication](#Communication)
<span id="SpecificCertifiedAccreditation">SpecificCertifiedAccreditation</span> | [edi3:Accreditation](#Accreditation)
<span id="TravelVisaReferencedDocument">TravelVisaReferencedDocument</span> | [edi3:Document](#Document)
<span id="AttainedAcademicQualification">AttainedAcademicQualification</span> | [edi3:Qualification](#Qualification)


<h1 id="Inventory">Inventory</h1>

Type: rdf:Class

Comments: <br/>A stores item, such as for onboard use during a journey.<br/>Supply chain goods and materials held in stock.<br/>

Properties: 

Name | Type 
-|-
<span id="StockQuantity">StockQuantity</span> | xsd:decimal
<span id="AverageDurationDateTime">AverageDurationDateTime</span> | xsd:dateTime
<span id="DispositionReferencedDocument">DispositionReferencedDocument</span> | [edi3:Document](#Document)
<span id="TypeCode">TypeCode</span> | xsd:token
<span id="PlannedStockQuantity">PlannedStockQuantity</span> | xsd:decimal
<span id="AverageDemandQuantity">AverageDemandQuantity</span> | xsd:decimal
<span id="MinimumStockQuantity">MinimumStockQuantity</span> | xsd:decimal
<span id="MaximumStockQuantity">MaximumStockQuantity</span> | xsd:decimal
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="SequenceNumeric">SequenceNumeric</span> | xsd:decimal
<span id="SpecifiedSupplyChainEvent">SpecifiedSupplyChainEvent</span> | [edi3:Event](#Event)
<span id="PlannedStockCalculationDateTime">PlannedStockCalculationDateTime</span> | xsd:dateTime
<span id="SpecifiedLogisticsLocation">SpecifiedLogisticsLocation</span> | [edi3:Location](#Location)
<span id="CalculationDateTime">CalculationDateTime</span> | xsd:dateTime
<span id="OnboardQuantity">OnboardQuantity</span> | xsd:decimal
<span id="RemarkNote">RemarkNote</span> | [edi3:Note](#Note)
<span id="MaximumStockLevelMeasure">MaximumStockLevelMeasure</span> | xsd:decimal
<span id="MinimumStockLevelMeasure">MinimumStockLevelMeasure</span> | xsd:decimal


<h1 id="Cargo">Cargo</h1>

Type: rdf:Class

Comments: Information about goods being transported identifying their nature for customs, statistical or transport purposes.

Properties: 

Name | Type 
-|-
<span id="TypeCargoCategoryCode">TypeCargoCategoryCode</span> | xsd:token
<span id="IdentificationText">IdentificationText</span> | xsd:string
<span id="StatisticalClassificationCargoCommodityCategoryCode">StatisticalClassificationCargoCommodityCategoryCode</span> | xsd:token


<h1 id="Organization">Organization</h1>

Type: rdf:Class

Comments: An organization set up on a legal basis as a business, government body, department, charity, or financial institution.

Properties: 

Name | Type 
-|-
<span id="TypeCode">TypeCode</span> | xsd:token
<span id="EstablishedDateTime">EstablishedDateTime</span> | xsd:dateTime
<span id="TradingBusinessNameText">TradingBusinessNameText</span> | xsd:string
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="NameText">NameText</span> | xsd:string
<span id="AuthorizedLegalRegistration">AuthorizedLegalRegistration</span> | [edi3:Registration](#Registration)
<span id="PostalTradeAddress">PostalTradeAddress</span> | [edi3:Address](#Address)
<span id="BusinessTypeCode">BusinessTypeCode</span> | xsd:token


<h1 id="PersonalEffects">PersonalEffects</h1>

Type: rdf:Class

Comments: Specified privately owned articles for personal use by an individual.

Properties: 

Name | Type 
-|-
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="SequenceNumeric">SequenceNumeric</span> | xsd:decimal
<span id="OnboardQuantity">OnboardQuantity</span> | xsd:decimal


<h1 id="TransportEquipment">TransportEquipment</h1>

Type: rdf:Class

Comments: <br/>A piece of equipment used to hold, protect or secure cargo for logistics purposes.<br/>A referenced piece of equipment used to hold, protect or secure cargo for logistics purposes.<br/>A piece of transport equipment that is associated with another piece of transport equipment, such as a maritime container placed on a rail wagon for transportation.<br/>A piece of attached transport equipment, such as a chain or a tarpaulin.<br/>

Properties: 

Name | Type 
-|-
<span id="ReportingIOTDeviceCommunicationPairing">ReportingIOTDeviceCommunicationPairing</span> | [edi3:Pairing](#Pairing)
<span id="CarrierAssignedBookingIdentificationIdentifier">CarrierAssignedBookingIdentificationIdentifier</span> | xsd:token
<span id="NetWeightWeightUnitMeasure">NetWeightWeightUnitMeasure</span> | xsd:decimal
<span id="DeliveryTransportEvent">DeliveryTransportEvent</span> | [edi3:Event](#Event)
<span id="CarriedAssociatedTransportEquipment">CarriedAssociatedTransportEquipment</span> | [edi3:TransportEquipment](#TransportEquipment)
<span id="LegalStatusTransportEquipmentLegalStatusCode">LegalStatusTransportEquipmentLegalStatusCode</span> | xsd:token
<span id="ContainedConsignmentQuantity">ContainedConsignmentQuantity</span> | xsd:decimal
<span id="ReleaseIdentifier">ReleaseIdentifier</span> | xsd:token
<span id="CarrierTradeParty">CarrierTradeParty</span> | [edi3:Party](#Party)
<span id="LoadingTransportInstructions">LoadingTransportInstructions</span> | [edi3:Instructions](#Instructions)
<span id="UnloadingTransportEvent">UnloadingTransportEvent</span> | [edi3:Event](#Event)
<span id="CharacteristicTransportEquipmentSizeTypeCode">CharacteristicTransportEquipmentSizeTypeCode</span> | xsd:token
<span id="ShipperReferenceInformationText">ShipperReferenceInformationText</span> | xsd:string
<span id="LoadingRemarkText">LoadingRemarkText</span> | xsd:string
<span id="ApplicableLogisticsServiceCharge">ApplicableLogisticsServiceCharge</span> | [edi3:ServiceCharge](#ServiceCharge)
<span id="QuarantineQuarantineInstructions">QuarantineQuarantineInstructions</span> | [edi3:Instructions](#Instructions)
<span id="RequiredLaneLengthLinearUnitMeasure">RequiredLaneLengthLinearUnitMeasure</span> | xsd:decimal
<span id="CharacteristicText">CharacteristicText</span> | xsd:string
<span id="OperatingTradeParty">OperatingTradeParty</span> | [edi3:Party](#Party)
<span id="ReleaseRestrictionText">ReleaseRestrictionText</span> | xsd:string
<span id="SettingTransportSettingTemperature">SettingTransportSettingTemperature</span> | [edi3:Temperature](#Temperature)
<span id="AdditionalTransportInstructions">AdditionalTransportInstructions</span> | [edi3:Instructions](#Instructions)
<span id="InformationText">InformationText</span> | xsd:string
<span id="AffixedLogisticsSeal">AffixedLogisticsSeal</span> | [edi3:Seal](#Seal)
<span id="HaulageArrangementTransportEquipmentHaulageArrangementsCode">HaulageArrangementTransportEquipmentHaulageArrangementsCode</span> | xsd:token
<span id="NotifiedTradeParty">NotifiedTradeParty</span> | [edi3:Party](#Party)
<span id="UnitQuantity">UnitQuantity</span> | xsd:decimal
<span id="ContainedAssociatedTransportEquipment">ContainedAssociatedTransportEquipment</span> | [edi3:TransportEquipment](#TransportEquipment)
<span id="AssociatedReferencedDocument">AssociatedReferencedDocument</span> | [edi3:Document](#Document)
<span id="HumidityPercent">HumidityPercent</span> | xsd:decimal
<span id="LoadingTransportEvent">LoadingTransportEvent</span> | [edi3:Event](#Event)
<span id="TransportMovementStatusTransportEquipmentMovementStatusCode">TransportMovementStatusTransportEquipmentMovementStatusCode</span> | xsd:token
<span id="StorageTransportEvent">StorageTransportEvent</span> | [edi3:Event](#Event)
<span id="GrossWeightWeightUnitMeasure">GrossWeightWeightUnitMeasure</span> | xsd:decimal
<span id="ConsolidationTransportEvent">ConsolidationTransportEvent</span> | [edi3:Event](#Event)
<span id="ReportedLogisticsStatus">ReportedLogisticsStatus</span> | [edi3:Status](#Status)
<span id="LoadingLengthLinearUnitMeasure">LoadingLengthLinearUnitMeasure</span> | xsd:decimal
<span id="LinearSpatialDimension">LinearSpatialDimension</span> | [edi3:Dimension](#Dimension)
<span id="ReturnableIndicator">ReturnableIndicator</span> | xsd:boolean
<span id="HandlingHandlingInstructions">HandlingHandlingInstructions</span> | [edi3:Instructions](#Instructions)
<span id="RelatedCommunicationEvent">RelatedCommunicationEvent</span> | [edi3:Event](#Event)
<span id="PositioningTransportEvent">PositioningTransportEvent</span> | [edi3:Event](#Event)
<span id="AttachedAttachedTransportEquipment">AttachedAttachedTransportEquipment</span> | [edi3:TransportEquipment](#TransportEquipment)
<span id="ActualTransportRoute">ActualTransportRoute</span> | [edi3:Route](#Route)
<span id="PickUpTransportEvent">PickUpTransportEvent</span> | [edi3:Event](#Event)
<span id="ScheduledTransportRoute">ScheduledTransportRoute</span> | [edi3:Route](#Route)
<span id="PowerSupplyTypeText">PowerSupplyTypeText</span> | xsd:string
<span id="ManufacturingFormattedDateTime">ManufacturingFormattedDateTime</span> | xsd:dateTime
<span id="TareWeightWeightUnitMeasure">TareWeightWeightUnitMeasure</span> | xsd:decimal
<span id="ManufacturerTradeParty">ManufacturerTradeParty</span> | [edi3:Party](#Party)
<span id="StowagePositionIdentifier">StowagePositionIdentifier</span> | xsd:token
<span id="SealedIndicator">SealedIndicator</span> | xsd:boolean
<span id="UsedCapacityTransportEquipmentFullnessCode">UsedCapacityTransportEquipmentFullnessCode</span> | xsd:token
<span id="DeliveryDeliveryInstructions">DeliveryDeliveryInstructions</span> | [edi3:Instructions](#Instructions)
<span id="SequenceNumeric">SequenceNumeric</span> | xsd:decimal
<span id="LoadingSequenceNumeric">LoadingSequenceNumeric</span> | xsd:decimal
<span id="SpecifiedLogisticsTransportMeans">SpecifiedLogisticsTransportMeans</span> | [edi3:TransportMeans](#TransportMeans)
<span id="UnloadingSequenceNumeric">UnloadingSequenceNumeric</span> | xsd:decimal
<span id="AttachedMonitoringIOTDevice">AttachedMonitoringIOTDevice</span> | [edi3:IOTDevice](#IOTDevice)
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="OperationalStatusTransportEquipmentOperationalStatusCode">OperationalStatusTransportEquipmentOperationalStatusCode</span> | xsd:token
<span id="LoadedTransportDangerousGoods">LoadedTransportDangerousGoods</span> | [edi3:DangerousGoods](#DangerousGoods)
<span id="SupplierPartyRoleTransportEquipmentSupplierPartyRoleCode">SupplierPartyRoleTransportEquipmentSupplierPartyRoleCode</span> | xsd:token
<span id="LoadedSupplyChainConsignmentItem">LoadedSupplyChainConsignmentItem</span> | [edi3:ConsignmentItem](#ConsignmentItem)
<span id="GrossVolumeVolumeUnitMeasure">GrossVolumeVolumeUnitMeasure</span> | xsd:decimal
<span id="DamageRemarkText">DamageRemarkText</span> | xsd:string
<span id="ReportingIOTDeviceTransportEvent">ReportingIOTDeviceTransportEvent</span> | [edi3:Event](#Event)
<span id="SpecifiedLogisticsRiskAnalysisResult">SpecifiedLogisticsRiskAnalysisResult</span> | [edi3:RiskAnalysisResult](#RiskAnalysisResult)
<span id="TransportServicesBuyerTradeParty">TransportServicesBuyerTradeParty</span> | [edi3:Party](#Party)
<span id="ContainedSupplyChainConsignment">ContainedSupplyChainConsignment</span> | [edi3:Consignment](#Consignment)
<span id="SealQuantity">SealQuantity</span> | xsd:decimal
<span id="LoadingTradeParty">LoadingTradeParty</span> | [edi3:Party](#Party)
<span id="PowerSupplyTypeCode">PowerSupplyTypeCode</span> | xsd:token
<span id="AccompaniedIndicator">AccompaniedIndicator</span> | xsd:boolean
<span id="UnloadingTransportInstructions">UnloadingTransportInstructions</span> | [edi3:Instructions](#Instructions)
<span id="LoadedPackageQuantity">LoadedPackageQuantity</span> | xsd:decimal
<span id="RequestedTransportRoute">RequestedTransportRoute</span> | [edi3:Route](#Route)
<span id="ApplicableNote">ApplicableNote</span> | [edi3:Note](#Note)
<span id="PowerSupplyConnectorQuantity">PowerSupplyConnectorQuantity</span> | xsd:decimal
<span id="AirFlowAirFlowUnitMeasure">AirFlowAirFlowUnitMeasure</span> | xsd:decimal
<span id="BondedWarehouseStorageTransportEvent">BondedWarehouseStorageTransportEvent</span> | [edi3:Event](#Event)


<h1 id="Consignment">Consignment</h1>

Type: rdf:Class

Comments: <br/>A separately identifiable collection of goods items to be transported or available to be transported from one consignor to one consignee in a supply chain via one or more modes of transport where each consignment is the subject of one single transport contract.<br/>A referenced, separately identifiable collection of goods items to be transported or available to be transported from one consignor to one consignee via one or more modes of transport where each consignment is the subject of one single transport contract.<br/>

Properties: 

Name | Type 
-|-
<span id="IntermediateConsigneeTradeParty">IntermediateConsigneeTradeParty</span> | [edi3:Party](#Party)
<span id="TransshipmentLogisticsLocation">TransshipmentLogisticsLocation</span> | [edi3:Location](#Location)
<span id="ApplicableCrossBorderCustomsValuation">ApplicableCrossBorderCustomsValuation</span> | [edi3:CustomsValuation](#CustomsValuation)
<span id="DemurrageInformationText">DemurrageInformationText</span> | xsd:string
<span id="NetWeightWeightUnitMeasure">NetWeightWeightUnitMeasure</span> | xsd:decimal
<span id="CustomsExportAgentTradeParty">CustomsExportAgentTradeParty</span> | [edi3:Party](#Party)
<span id="DeliveryTransportEvent">DeliveryTransportEvent</span> | [edi3:Event](#Event)
<span id="InsuranceApplicableTradeCurrencyExchange">InsuranceApplicableTradeCurrencyExchange</span> | [edi3:CurrencyExchange](#CurrencyExchange)
<span id="ConsignorAssignedIdentifier">ConsignorAssignedIdentifier</span> | xsd:token
<span id="DevanningTransportEvent">DevanningTransportEvent</span> | [edi3:Event](#Event)
<span id="OriginTradeGeopoliticalRegion">OriginTradeGeopoliticalRegion</span> | [edi3:GeopoliticalRegion](#GeopoliticalRegion)
<span id="IncludedSupplyChainConsignmentItem">IncludedSupplyChainConsignmentItem</span> | [edi3:ConsignmentItem](#ConsignmentItem)
<span id="ShipStoresIndicator">ShipStoresIndicator</span> | xsd:boolean
<span id="CarrierTradeParty">CarrierTradeParty</span> | [edi3:Party](#Party)
<span id="CODAmount">CODAmount</span> | xsd:decimal
<span id="AtDepartureLogisticsTransportMovement">AtDepartureLogisticsTransportMovement</span> | [edi3:TransportMovement](#TransportMovement)
<span id="LoadingTransportInstructions">LoadingTransportInstructions</span> | [edi3:Instructions](#Instructions)
<span id="ApplicableLogisticsServiceCharge">ApplicableLogisticsServiceCharge</span> | [edi3:ServiceCharge](#ServiceCharge)
<span id="GoodsReleaseRestrictionText">GoodsReleaseRestrictionText</span> | xsd:string
<span id="UnloadingLogisticsLocation">UnloadingLogisticsLocation</span> | [edi3:Location](#Location)
<span id="LoadingLogisticsLocation">LoadingLogisticsLocation</span> | [edi3:Location](#Location)
<span id="ExportExitDateTime">ExportExitDateTime</span> | xsd:dateTime
<span id="ApplicableTradeAllowanceCharge">ApplicableTradeAllowanceCharge</span> | [edi3:AllowanceCharge](#AllowanceCharge)
<span id="PickUpTradeParty">PickUpTradeParty</span> | [edi3:Party](#Party)
<span id="InformationText">InformationText</span> | xsd:string
<span id="ConsigneeAgentTradeParty">ConsigneeAgentTradeParty</span> | [edi3:Party](#Party)
<span id="CarrierAcceptanceLogisticsLocation">CarrierAcceptanceLogisticsLocation</span> | [edi3:Location](#Location)
<span id="BorderCrossingLogisticsTransportMovement">BorderCrossingLogisticsTransportMovement</span> | [edi3:TransportMovement](#TransportMovement)
<span id="ApplicableTransportDangerousGoods">ApplicableTransportDangerousGoods</span> | [edi3:DangerousGoods](#DangerousGoods)
<span id="NotifiedTradeParty">NotifiedTradeParty</span> | [edi3:Party](#Party)
<span id="ReExportTradeCountry">ReExportTradeCountry</span> | [edi3:Country](#Country)
<span id="TotalAllowanceChargeAmount">TotalAllowanceChargeAmount</span> | xsd:decimal
<span id="CarrierAcceptanceFormattedDateTime">CarrierAcceptanceFormattedDateTime</span> | xsd:dateTime
<span id="ImportTradeCountry">ImportTradeCountry</span> | [edi3:Country](#Country)
<span id="CustomsIdentificationIdentifier">CustomsIdentificationIdentifier</span> | xsd:token
<span id="ManifestAssociatedReferencedDocument">ManifestAssociatedReferencedDocument</span> | [edi3:Document](#Document)
<span id="TransportEquipmentQuantity">TransportEquipmentQuantity</span> | xsd:decimal
<span id="AssociatedReferencedDocument">AssociatedReferencedDocument</span> | [edi3:Document](#Document)
<span id="HaulageHaulageInstructions">HaulageHaulageInstructions</span> | [edi3:Instructions](#Instructions)
<span id="ApplicableTradeCurrencyExchange">ApplicableTradeCurrencyExchange</span> | [edi3:CurrencyExchange](#CurrencyExchange)
<span id="StorageTransportEvent">StorageTransportEvent</span> | [edi3:Event](#Event)
<span id="NilCustomsValueIndicator">NilCustomsValueIndicator</span> | xsd:boolean
<span id="RelatedBookingTypeText">RelatedBookingTypeText</span> | xsd:string
<span id="GrossWeightWeightUnitMeasure">GrossWeightWeightUnitMeasure</span> | xsd:decimal
<span id="ExportTradeCountry">ExportTradeCountry</span> | [edi3:Country](#Country)
<span id="TotalCollectChargeAmount">TotalCollectChargeAmount</span> | xsd:decimal
<span id="ServiceChargeApplicableTradeCurrencyExchange">ServiceChargeApplicableTradeCurrencyExchange</span> | [edi3:CurrencyExchange](#CurrencyExchange)
<span id="TransportSplitDescriptionText">TransportSplitDescriptionText</span> | xsd:string
<span id="GroupingCentreTradeParty">GroupingCentreTradeParty</span> | [edi3:Party](#Party)
<span id="UtilizedLogisticsTransportEquipment">UtilizedLogisticsTransportEquipment</span> | [edi3:TransportEquipment](#TransportEquipment)
<span id="TransportTransportService">TransportTransportService</span> | [edi3:Service](#Service)
<span id="DeclaredValueForCustomsAmount">DeclaredValueForCustomsAmount</span> | xsd:decimal
<span id="ReportedLogisticsStatus">ReportedLogisticsStatus</span> | [edi3:Status](#Status)
<span id="EstimatedApplicableLogisticsServiceCharge">EstimatedApplicableLogisticsServiceCharge</span> | [edi3:ServiceCharge](#ServiceCharge)
<span id="LoadingLengthLinearUnitMeasure">LoadingLengthLinearUnitMeasure</span> | xsd:decimal
<span id="ConnectingCarrierTradeParty">ConnectingCarrierTradeParty</span> | [edi3:Party](#Party)
<span id="InsurancePremiumAmount">InsurancePremiumAmount</span> | xsd:decimal
<span id="HandlingHandlingInstructions">HandlingHandlingInstructions</span> | [edi3:Instructions](#Instructions)
<span id="PreviousAdministrativeReferencedDocument">PreviousAdministrativeReferencedDocument</span> | [edi3:Document](#Document)
<span id="CustomsImportAgentTradeParty">CustomsImportAgentTradeParty</span> | [edi3:Party](#Party)
<span id="LoadingInformationText">LoadingInformationText</span> | xsd:string
<span id="TransportTransportEvent">TransportTransportEvent</span> | [edi3:Event](#Event)
<span id="TransitLogisticsLocation">TransitLogisticsLocation</span> | [edi3:Location](#Location)
<span id="ConsigneeAssignedIdentifier">ConsigneeAssignedIdentifier</span> | xsd:token
<span id="TotalChargeAmount">TotalChargeAmount</span> | xsd:decimal
<span id="NetVolumeVolumeUnitMeasure">NetVolumeVolumeUnitMeasure</span> | xsd:decimal
<span id="PickUpTransportEvent">PickUpTransportEvent</span> | [edi3:Event](#Event)
<span id="ShipToTradeParty">ShipToTradeParty</span> | [edi3:Party](#Party)
<span id="TransportLogisticsPackage">TransportLogisticsPackage</span> | [edi3:Package](#Package)
<span id="InsuranceValueAmount">InsuranceValueAmount</span> | xsd:decimal
<span id="DangerousGoodsNotifierTradeParty">DangerousGoodsNotifierTradeParty</span> | [edi3:Party](#Party)
<span id="RiskFactorCode">RiskFactorCode</span> | xsd:token
<span id="ConsignorProvidedBorderClearanceTransportInstructions">ConsignorProvidedBorderClearanceTransportInstructions</span> | [edi3:Instructions](#Instructions)
<span id="PreCarriageLogisticsTransportMovement">PreCarriageLogisticsTransportMovement</span> | [edi3:TransportMovement](#TransportMovement)
<span id="FinalDestinationTradeCountry">FinalDestinationTradeCountry</span> | [edi3:Country](#Country)
<span id="CarrierProvidedInformationText">CarrierProvidedInformationText</span> | xsd:string
<span id="ConsignmentItemQuantity">ConsignmentItemQuantity</span> | xsd:decimal
<span id="AtArrivalLogisticsTransportMovement">AtArrivalLogisticsTransportMovement</span> | [edi3:TransportMovement](#TransportMovement)
<span id="PaymentArrangementTransportServicePaymentArrangementCode">PaymentArrangementTransportServicePaymentArrangementCode</span> | xsd:token
<span id="TransportEquipmentSplitGoodsIndicator">TransportEquipmentSplitGoodsIndicator</span> | xsd:boolean
<span id="IncludedReferencedSupplyChainConsignment">IncludedReferencedSupplyChainConsignment</span> | [edi3:Consignment](#Consignment)
<span id="ShipFromTradeParty">ShipFromTradeParty</span> | [edi3:Party](#Party)
<span id="FOBAmount">FOBAmount</span> | xsd:decimal
<span id="CustomsRequiredInvoiceReferencedDocument">CustomsRequiredInvoiceReferencedDocument</span> | [edi3:Document](#Document)
<span id="WarehouseArrivalDateTime">WarehouseArrivalDateTime</span> | xsd:dateTime
<span id="TradedParcelIdentifier">TradedParcelIdentifier</span> | xsd:token
<span id="ConsignorAgentTradeParty">ConsignorAgentTradeParty</span> | [edi3:Party](#Party)
<span id="ConsigneeTradeParty">ConsigneeTradeParty</span> | [edi3:Party](#Party)
<span id="DeliveryDeliveryInstructions">DeliveryDeliveryInstructions</span> | [edi3:Instructions](#Instructions)
<span id="PackageQuantity">PackageQuantity</span> | xsd:decimal
<span id="ConsolidatorTradeParty">ConsolidatorTradeParty</span> | [edi3:Party](#Party)
<span id="NilInsuranceValueIndicator">NilInsuranceValueIndicator</span> | xsd:boolean
<span id="InvoiceApplicableTradeCurrencyExchange">InvoiceApplicableTradeCurrencyExchange</span> | [edi3:CurrencyExchange](#CurrencyExchange)
<span id="SequenceNumeric">SequenceNumeric</span> | xsd:decimal
<span id="LoadingSequenceNumeric">LoadingSequenceNumeric</span> | xsd:decimal
<span id="PackageTypeText">PackageTypeText</span> | xsd:string
<span id="UnloadingSequenceNumeric">UnloadingSequenceNumeric</span> | xsd:decimal
<span id="CarrierAgentTradeParty">CarrierAgentTradeParty</span> | [edi3:Party](#Party)
<span id="TotalDisbursementAmount">TotalDisbursementAmount</span> | xsd:decimal
<span id="DeliveryInformationText">DeliveryInformationText</span> | xsd:string
<span id="LoadingBaseportLogisticsLocation">LoadingBaseportLogisticsLocation</span> | [edi3:Location](#Location)
<span id="ContainerizationIndicator">ContainerizationIndicator</span> | xsd:boolean
<span id="CargoToleranceInformationText">CargoToleranceInformationText</span> | xsd:string
<span id="ChargeableTransportationStageQuantity">ChargeableTransportationStageQuantity</span> | xsd:decimal
<span id="NatureIdentificationTransportCargo">NatureIdentificationTransportCargo</span> | [edi3:Cargo](#Cargo)
<span id="CustomsTransitAgentTradeParty">CustomsTransitAgentTradeParty</span> | [edi3:Party](#Party)
<span id="TotalPrepaidChargeAmount">TotalPrepaidChargeAmount</span> | xsd:decimal
<span id="InvoiceeAssociatedTradeParty">InvoiceeAssociatedTradeParty</span> | [edi3:Party](#Party)
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="SpecifiedLogisticsTransportMovement">SpecifiedLogisticsTransportMovement</span> | [edi3:TransportMovement](#TransportMovement)
<span id="TotalExportExitToImportEntryChargeAmount">TotalExportExitToImportEntryChargeAmount</span> | xsd:decimal
<span id="DeclaredForCustomsLogisticsLocation">DeclaredForCustomsLogisticsLocation</span> | [edi3:Location](#Location)
<span id="FreightForwarderAssignedIdentifier">FreightForwarderAssignedIdentifier</span> | xsd:token
<span id="OnCarriageLogisticsTransportMovement">OnCarriageLogisticsTransportMovement</span> | [edi3:TransportMovement](#TransportMovement)
<span id="FinalDestinationLogisticsLocation">FinalDestinationLogisticsLocation</span> | [edi3:Location](#Location)
<span id="GrossVolumeVolumeUnitMeasure">GrossVolumeVolumeUnitMeasure</span> | xsd:decimal
<span id="DestinationTradeCountry">DestinationTradeCountry</span> | [edi3:Country](#Country)
<span id="ExporterTradeParty">ExporterTradeParty</span> | [edi3:Party](#Party)
<span id="ImporterTradeParty">ImporterTradeParty</span> | [edi3:Party](#Party)
<span id="OriginTradeCountry">OriginTradeCountry</span> | [edi3:Country](#Country)
<span id="ApplicableCrossBorderRegulatoryProcedure">ApplicableCrossBorderRegulatoryProcedure</span> | [edi3:RegulatoryProcedure](#RegulatoryProcedure)
<span id="DeliveryTradeParty">DeliveryTradeParty</span> | [edi3:Party](#Party)
<span id="ConsignorTradeParty">ConsignorTradeParty</span> | [edi3:Party](#Party)
<span id="WarehouseStorageTransportEvent">WarehouseStorageTransportEvent</span> | [edi3:Event](#Event)
<span id="AssociatedTradeParty">AssociatedTradeParty</span> | [edi3:Party](#Party)
<span id="ConsignorProvidedInformationText">ConsignorProvidedInformationText</span> | xsd:string
<span id="SpecifiedLogisticsRiskAnalysisResult">SpecifiedLogisticsRiskAnalysisResult</span> | [edi3:RiskAnalysisResult](#RiskAnalysisResult)
<span id="TransportServicesBuyerTradeParty">TransportServicesBuyerTradeParty</span> | [edi3:Party](#Party)
<span id="ChargeableWeightWeightUnitMeasure">ChargeableWeightWeightUnitMeasure</span> | xsd:decimal
<span id="MainCarriageLogisticsTransportMovement">MainCarriageLogisticsTransportMovement</span> | [edi3:TransportMovement](#TransportMovement)
<span id="CargoInsuranceInstructionsInformationText">CargoInsuranceInstructionsInformationText</span> | xsd:string
<span id="ApplicableTransportCargoInsurance">ApplicableTransportCargoInsurance</span> | [edi3:CargoInsurance](#CargoInsurance)
<span id="LoadingListQuantity">LoadingListQuantity</span> | xsd:decimal
<span id="UnloadingBaseportLogisticsLocation">UnloadingBaseportLogisticsLocation</span> | [edi3:Location](#Location)
<span id="ConsigneeReceiptLogisticsLocation">ConsigneeReceiptLogisticsLocation</span> | [edi3:Location](#Location)
<span id="SpecifiedTradeDeliveryTerms">SpecifiedTradeDeliveryTerms</span> | [edi3:DeliveryTerms](#DeliveryTerms)
<span id="SummaryDescriptionText">SummaryDescriptionText</span> | xsd:string
<span id="NilCarriageValueIndicator">NilCarriageValueIndicator</span> | xsd:boolean
<span id="AvailabilityDueDateTime">AvailabilityDueDateTime</span> | xsd:dateTime
<span id="AssociatedInvoiceDiscountAmount">AssociatedInvoiceDiscountAmount</span> | xsd:decimal
<span id="IncludedReferencedSupplyChainConsignmentItem">IncludedReferencedSupplyChainConsignmentItem</span> | [edi3:ConsignmentItem](#ConsignmentItem)
<span id="PhysicalLogisticsShippingMarks">PhysicalLogisticsShippingMarks</span> | [edi3:ShippingMarks](#ShippingMarks)
<span id="ExaminationTransportEvent">ExaminationTransportEvent</span> | [edi3:Event](#Event)
<span id="CarrierAssignedIdentifier">CarrierAssignedIdentifier</span> | xsd:token
<span id="TransshipmentPermissionIndicator">TransshipmentPermissionIndicator</span> | xsd:boolean
<span id="AssociatedInvoiceAmount">AssociatedInvoiceAmount</span> | xsd:decimal
<span id="AssociatedInvoiceDiscountPercent">AssociatedInvoiceDiscountPercent</span> | xsd:decimal
<span id="ExportTradeGeopoliticalRegion">ExportTradeGeopoliticalRegion</span> | [edi3:GeopoliticalRegion](#GeopoliticalRegion)
<span id="DeconsolidatorTradeParty">DeconsolidatorTradeParty</span> | [edi3:Party](#Party)
<span id="DespatchTradeParty">DespatchTradeParty</span> | [edi3:Party](#Party)
<span id="CarrierAcceptanceDateTime">CarrierAcceptanceDateTime</span> | xsd:dateTime
<span id="DeclaredValueForCarriageAmount">DeclaredValueForCarriageAmount</span> | xsd:decimal
<span id="TransitTradeCountry">TransitTradeCountry</span> | [edi3:Country](#Country)
<span id="TransportContractReferencedDocument">TransportContractReferencedDocument</span> | [edi3:Document](#Document)
<span id="FreightForwarderTradeParty">FreightForwarderTradeParty</span> | [edi3:Party](#Party)
<span id="RelatedSupplyChainTradeTransaction">RelatedSupplyChainTradeTransaction</span> | [edi3:TradeTransaction](#TradeTransaction)
<span id="BondedWarehouseStorageTransportEvent">BondedWarehouseStorageTransportEvent</span> | [edi3:Event](#Event)
<span id="VanningTransportEvent">VanningTransportEvent</span> | [edi3:Event](#Event)


<h1 id="MonetarySummation">MonetarySummation</h1>

Type: rdf:Class

Comments: <br/>A collection of monetary amount totals, specified at header level, for a trade settlement.<br/>A collection of monetary amount totals specified for a trade settlement payment.<br/>A collection of monetary amount totals, specified at line level, for a trade settlement.<br/>

Properties: 

Name | Type 
-|-
<span id="InsuranceChargeTotalAmount">InsuranceChargeTotalAmount</span> | xsd:decimal
<span id="NetIncludingTaxesLineTotalAmount">NetIncludingTaxesLineTotalAmount</span> | xsd:decimal
<span id="RoundingAmount">RoundingAmount</span> | xsd:decimal
<span id="TotalAllowanceChargeAmount">TotalAllowanceChargeAmount</span> | xsd:decimal
<span id="ProductValueExcludingTobaccoTaxInformationAmount">ProductValueExcludingTobaccoTaxInformationAmount</span> | xsd:decimal
<span id="AllowanceTotalAmount">AllowanceTotalAmount</span> | xsd:decimal
<span id="RetailValueExcludingTaxInformationAmount">RetailValueExcludingTaxInformationAmount</span> | xsd:decimal
<span id="NetLineTotalAmount">NetLineTotalAmount</span> | xsd:decimal
<span id="TotalDiscountAmount">TotalDiscountAmount</span> | xsd:decimal
<span id="EquivalentTransferTotalAmount">EquivalentTransferTotalAmount</span> | xsd:decimal
<span id="TotalRetailValueInformationAmount">TotalRetailValueInformationAmount</span> | xsd:decimal
<span id="ExcludingTaxesLineTotalAmount">ExcludingTaxesLineTotalAmount</span> | xsd:decimal
<span id="ApplicableHeaderBalanceOut">ApplicableHeaderBalanceOut</span> | [edi3:BalanceOut](#BalanceOut)
<span id="TaxBasisTotalAmount">TaxBasisTotalAmount</span> | xsd:decimal
<span id="ChargeTotalAmount">ChargeTotalAmount</span> | xsd:decimal
<span id="TotalPrepaidAmount">TotalPrepaidAmount</span> | xsd:decimal
<span id="PaymentTotalAmount">PaymentTotalAmount</span> | xsd:decimal
<span id="LineTotalAmount">LineTotalAmount</span> | xsd:decimal
<span id="DuePayableAmount">DuePayableAmount</span> | xsd:decimal
<span id="ApplicablePaymentBalanceOut">ApplicablePaymentBalanceOut</span> | [edi3:BalanceOut](#BalanceOut)
<span id="BalanceOutAmount">BalanceOutAmount</span> | xsd:decimal
<span id="IncludingTaxesLineTotalAmount">IncludingTaxesLineTotalAmount</span> | xsd:decimal
<span id="ProductWeightLossInformationAmount">ProductWeightLossInformationAmount</span> | xsd:decimal
<span id="InformationAmount">InformationAmount</span> | xsd:decimal
<span id="TotalDiscountBasisAmount">TotalDiscountBasisAmount</span> | xsd:decimal
<span id="GrandTotalAmount">GrandTotalAmount</span> | xsd:decimal
<span id="GrandTotalSpecifiedFinancialAdjustment">GrandTotalSpecifiedFinancialAdjustment</span> | [edi3:Adjustment](#Adjustment)
<span id="AdjustedBalanceOutAmount">AdjustedBalanceOutAmount</span> | xsd:decimal
<span id="GrossLineTotalAmount">GrossLineTotalAmount</span> | xsd:decimal
<span id="TotalDepositFeeInformationAmount">TotalDepositFeeInformationAmount</span> | xsd:decimal


<h1 id="PaymentDiscountTerms">PaymentDiscountTerms</h1>

Type: rdf:Class

Comments: Trade terms and conditions by which a discount is or can be applied to a payable amount.

Properties: 

Name | Type 
-|-
<span id="BasisAmount">BasisAmount</span> | xsd:decimal
<span id="CalculationPercent">CalculationPercent</span> | xsd:decimal
<span id="BasisPeriodMeasure">BasisPeriodMeasure</span> | xsd:decimal
<span id="BasisDateTime">BasisDateTime</span> | xsd:dateTime


<h1 id="FinancialCard">FinancialCard</h1>

Type: rdf:Class

Comments: A card used to represent a financial account for a trade settlement.

Properties: 

Name | Type 
-|-
<span id="IssuingCompanyNameText">IssuingCompanyNameText</span> | xsd:string
<span id="TypeCode">TypeCode</span> | xsd:token
<span id="MicrochipIndicator">MicrochipIndicator</span> | xsd:boolean
<span id="ValidFromDateTime">ValidFromDateTime</span> | xsd:dateTime
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="CardholderNameText">CardholderNameText</span> | xsd:string
<span id="CreditLimitAmount">CreditLimitAmount</span> | xsd:decimal
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="ExpiryDate">ExpiryDate</span> | xsd:date
<span id="InterestRatePercent">InterestRatePercent</span> | xsd:decimal
<span id="VerificationNumeric">VerificationNumeric</span> | xsd:decimal


<h1 id="Party">Party</h1>

Type: rdf:Class

Comments: <br/>An individual, a group, or a body having a role related to a location.<br/>An individual, a group, or a body having a role as a requestor.<br/>An individual, a group, or a body having a role in a trade business function.<br/>

Properties: 

Name | Type 
-|-
<span id="RoleText">RoleText</span> | xsd:string
<span id="ApplicableLogisticsServiceCharge">ApplicableLogisticsServiceCharge</span> | [edi3:ServiceCharge](#ServiceCharge)
<span id="LogoAssociatedSpecifiedBinaryFile">LogoAssociatedSpecifiedBinaryFile</span> | [edi3:BinaryFile](#BinaryFile)
<span id="SpecifiedProprietaryIdentity">SpecifiedProprietaryIdentity</span> | [edi3:Identity](#Identity)
<span id="SpecifiedAuthoritativeSignatoryPerson">SpecifiedAuthoritativeSignatoryPerson</span> | [edi3:Person](#Person)
<span id="BEIIdentificationIdentifier">BEIIdentificationIdentifier</span> | xsd:token
<span id="GlobalIdentificationIdentifier">GlobalIdentificationIdentifier</span> | xsd:token
<span id="SpecifiedLegalOrganization">SpecifiedLegalOrganization</span> | [edi3:Organization](#Organization)
<span id="TypeCode">TypeCode</span> | xsd:token
<span id="EndPointURIUniversalCommunication">EndPointURIUniversalCommunication</span> | [edi3:Communication](#Communication)
<span id="SpecifiedProjectOrganization">SpecifiedProjectOrganization</span> | [edi3:Organization](#Organization)
<span id="SpecifiedGovernmentRegistration">SpecifiedGovernmentRegistration</span> | [edi3:Registration](#Registration)
<span id="OwnedCreditorFinancialAccount">OwnedCreditorFinancialAccount</span> | [edi3:FinancialAccount](#FinancialAccount)
<span id="FaxUniversalCommunication">FaxUniversalCommunication</span> | [edi3:Communication](#Communication)
<span id="DefinedTradeContact">DefinedTradeContact</span> | [edi3:Contact](#Contact)
<span id="SpecifiedTransportPerson">SpecifiedTransportPerson</span> | [edi3:Person](#Person)
<span id="LanguageLanguageCode">LanguageLanguageCode</span> | xsd:token
<span id="SpecifiedProjectPerson">SpecifiedProjectPerson</span> | [edi3:Person](#Person)
<span id="RoleCode">RoleCode</span> | xsd:token
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="GLNIdentificationIdentifier">GLNIdentificationIdentifier</span> | xsd:token
<span id="RegisteredIdentificationIdentifier">RegisteredIdentificationIdentifier</span> | xsd:token
<span id="SpecifiedTaxRegistration">SpecifiedTaxRegistration</span> | [edi3:Registration](#Registration)
<span id="TelephoneUniversalCommunication">TelephoneUniversalCommunication</span> | [edi3:Communication](#Communication)
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="SpecifiedLogisticsLocation">SpecifiedLogisticsLocation</span> | [edi3:Location](#Location)
<span id="URIUniversalCommunication">URIUniversalCommunication</span> | [edi3:Communication](#Communication)
<span id="ProvidedTransportService">ProvidedTransportService</span> | [edi3:Service](#Service)
<span id="RolePartyRoleCode">RolePartyRoleCode</span> | xsd:token
<span id="NameText">NameText</span> | xsd:string
<span id="AccessRightsCode">AccessRightsCode</span> | xsd:token
<span id="AssociatedTradeParty">AssociatedTradeParty</span> | [edi3:Party](#Party)
<span id="SpecifiedLogisticsRiskAnalysisResult">SpecifiedLogisticsRiskAnalysisResult</span> | [edi3:RiskAnalysisResult](#RiskAnalysisResult)
<span id="CountryIdentifier">CountryIdentifier</span> | xsd:token
<span id="SpecifiedCreditorFinancialAccount">SpecifiedCreditorFinancialAccount</span> | [edi3:FinancialAccount](#FinancialAccount)
<span id="SpecifiedFinancialIdentity">SpecifiedFinancialIdentity</span> | [edi3:Identity](#Identity)
<span id="PostalTradeAddress">PostalTradeAddress</span> | [edi3:Address](#Address)
<span id="SpecifiedContactPerson">SpecifiedContactPerson</span> | [edi3:Person](#Person)
<span id="QualityAssuranceIndicator">QualityAssuranceIndicator</span> | xsd:boolean
<span id="DUNSIdentificationIdentifier">DUNSIdentificationIdentifier</span> | xsd:token
<span id="LineOfCreditSpecifiedFinancingFinancialAccount">LineOfCreditSpecifiedFinancingFinancialAccount</span> | [edi3:FinancialAccount](#FinancialAccount)


<h1 id="MaterialComponent">MaterialComponent</h1>

Type: rdf:Class

Comments: An unused and rejected as unwanted component of transport material.

Properties: 

Name | Type 
-|-
<span id="RemainingDeliveryTransportEvent">RemainingDeliveryTransportEvent</span> | [edi3:Event](#Event)
<span id="MaximumDedicatedStorageCapacityVolumeUnitMeasure">MaximumDedicatedStorageCapacityVolumeUnitMeasure</span> | xsd:decimal
<span id="RetainedVolumeUnitMeasure">RetainedVolumeUnitMeasure</span> | xsd:decimal
<span id="PlannedDischargedVolumeUnitMeasure">PlannedDischargedVolumeUnitMeasure</span> | xsd:decimal
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="EstimatedGeneratedVolumeUnitMeasure">EstimatedGeneratedVolumeUnitMeasure</span> | xsd:decimal


<h1 id="FinancialInstitution">FinancialInstitution</h1>

Type: rdf:Class

Comments: <br/>A bank, building society, credit union, stock brokerage, or similar business of the party that receives money.<br/>A bank, building society, credit union, stock brokerage, or similar business of the party that owes money.<br/>A sub-division of a bank, building society, credit union, stock brokerage, or similar business; established primarily to provide financial services and financial transactions.<br/>

Properties: 

Name | Type 
-|-
<span id="AustrianBankleitzahlIdentificationIdentifier">AustrianBankleitzahlIdentificationIdentifier</span> | xsd:token
<span id="CanadianPaymentsAssociationIdentificationIdentifier">CanadianPaymentsAssociationIdentificationIdentifier</span> | xsd:token
<span id="RussianCentralBankIdentificationIdentifier">RussianCentralBankIdentificationIdentifier</span> | xsd:token
<span id="SpecifiedProprietaryIdentity">SpecifiedProprietaryIdentity</span> | [edi3:Identity](#Identity)
<span id="UKSortCodeIdentificationIdentifier">UKSortCodeIdentificationIdentifier</span> | xsd:token
<span id="SpanishDomesticInterbankingIdentificationIdentifier">SpanishDomesticInterbankingIdentificationIdentifier</span> | xsd:token
<span id="SouthAfricanNCCIdentificationIdentifier">SouthAfricanNCCIdentificationIdentifier</span> | xsd:token
<span id="CHIPSParticipantIdentificationIdentifier">CHIPSParticipantIdentificationIdentifier</span> | xsd:token
<span id="PolishNationalClearingIdentificationIdentifier">PolishNationalClearingIdentificationIdentifier</span> | xsd:token
<span id="NewZealandNCCIdentificationIdentifier">NewZealandNCCIdentificationIdentifier</span> | xsd:token
<span id="SwissBCIdentificationIdentifier">SwissBCIdentificationIdentifier</span> | xsd:token
<span id="AustralianSNIdentificationIdentifier">AustralianSNIdentificationIdentifier</span> | xsd:token
<span id="IndianFinancialSystemIdentificationIdentifier">IndianFinancialSystemIdentificationIdentifier</span> | xsd:token
<span id="SubDivisionBranchFinancialInstitution">SubDivisionBranchFinancialInstitution</span> | [edi3:FinancialInstitution](#FinancialInstitution)
<span id="LocationFinancialInstitutionAddress">LocationFinancialInstitutionAddress</span> | [edi3:Address](#Address)
<span id="ItalianDomesticIdentificationIdentifier">ItalianDomesticIdentificationIdentifier</span> | xsd:token
<span id="CHIPSUniversalIdentificationIdentifier">CHIPSUniversalIdentificationIdentifier</span> | xsd:token
<span id="JapanFinancialInstitutionCommonIdentificationIdentifier">JapanFinancialInstitutionCommonIdentificationIdentifier</span> | xsd:token
<span id="ClearingSystemNameText">ClearingSystemNameText</span> | xsd:string
<span id="HongKongBankIdentificationIdentifier">HongKongBankIdentificationIdentifier</span> | xsd:token
<span id="HellenicBankIdentificationIdentifier">HellenicBankIdentificationIdentifier</span> | xsd:token
<span id="PortugueseNCCIdentificationIdentifier">PortugueseNCCIdentificationIdentifier</span> | xsd:token
<span id="AdditionalClearingSystemIdentifier">AdditionalClearingSystemIdentifier</span> | xsd:token
<span id="BICIdentifier">BICIdentifier</span> | xsd:token
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="FedwireRoutingNumberIdentificationIdentifier">FedwireRoutingNumberIdentificationIdentifier</span> | xsd:token
<span id="NameText">NameText</span> | xsd:string
<span id="GermanBankleitzahlIdentificationIdentifier">GermanBankleitzahlIdentificationIdentifier</span> | xsd:token
<span id="SICIdentificationIdentifier">SICIdentificationIdentifier</span> | xsd:token
<span id="AustralianBSBIdentificationIdentifier">AustralianBSBIdentificationIdentifier</span> | xsd:token


<h1 id="ComplexDescription">ComplexDescription</h1>

Type: rdf:Class

Comments: An aggregation of descriptive information consisting of different but related characteristics that together constitute a work item complex description.

Properties: 

Name | Type 
-|-
<span id="SubsetWorkItemComplexDescription">SubsetWorkItemComplexDescription</span> | [edi3:ComplexDescription](#ComplexDescription)
<span id="ContractualLanguageCode">ContractualLanguageCode</span> | xsd:token
<span id="RequestingSpecificationQuery">RequestingSpecificationQuery</span> | [edi3:Query](#Query)
<span id="ContentText">ContentText</span> | xsd:string
<span id="RespondingSpecificationResponse">RespondingSpecificationResponse</span> | [edi3:Response](#Response)


<h1 id="GeopoliticalRegion">GeopoliticalRegion</h1>

Type: rdf:Class

Comments: A collection of countries and/or economies united for trade purposes.

Properties: 

Name | Type 
-|-
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="NameText">NameText</span> | xsd:string
<span id="IncludedTradeCountry">IncludedTradeCountry</span> | [edi3:Country](#Country)


<h1 id="GeographicalMultiSurface">GeographicalMultiSurface</h1>

Type: rdf:Class

Comments: A collection of surfaces on the Earth (reference ISO 19136).

Properties: 

Name | Type 
-|-
<span id="AssociatedSpecifiedGeographicalObjectCharacteristic">AssociatedSpecifiedGeographicalObjectCharacteristic</span> | [edi3:GeographicalObjectCharacteristic](#GeographicalObjectCharacteristic)


<h1 id="Communication">Communication</h1>

Type: rdf:Class

Comments: <br/>The exchange of thoughts, messages, or information, as universally exchanged by speech, signals, writing, or behaviour between persons and/or organizations.<br/>An address for the delivery of electronic mail.<br/>Information necessary to establish an electronic telecommunication connection for the purpose of a telephone or facsimile exchange.<br/>

Properties: 

Name | Type 
-|-
<span id="URIIdentifier">URIIdentifier</span> | xsd:token
<span id="UsageSpecifiedPreference">UsageSpecifiedPreference</span> | [edi3:Preference](#Preference)
<span id="LocalNumberText">LocalNumberText</span> | xsd:string
<span id="SpecialDeviceTypeText">SpecialDeviceTypeText</span> | xsd:string
<span id="ChannelCommunicationChannelCode">ChannelCommunicationChannelCode</span> | xsd:token
<span id="CountryNumberCode">CountryNumberCode</span> | xsd:token
<span id="UseCode">UseCode</span> | xsd:token
<span id="CompleteNumberText">CompleteNumberText</span> | xsd:string
<span id="InternalAccessText">InternalAccessText</span> | xsd:string
<span id="AreaNumberCode">AreaNumberCode</span> | xsd:token


<h1 id="Context">Context</h1>

Type: rdf:Class

Comments: The scenario or setting of an exchanged document, such as its business process application context.

Properties: 

Name | Type 
-|-
<span id="SubsetSpecifiedDocumentContextParameter">SubsetSpecifiedDocumentContextParameter</span> | [edi3:Parameter](#Parameter)
<span id="BIMSpecifiedDocumentContextParameter">BIMSpecifiedDocumentContextParameter</span> | [edi3:Parameter](#Parameter)
<span id="ApplicationSpecifiedDocumentContextParameter">ApplicationSpecifiedDocumentContextParameter</span> | [edi3:Parameter](#Parameter)
<span id="ProcessingTransactionDateTime">ProcessingTransactionDateTime</span> | xsd:dateTime
<span id="GuidelineSpecifiedDocumentContextParameter">GuidelineSpecifiedDocumentContextParameter</span> | [edi3:Parameter](#Parameter)
<span id="ScenarioSpecifiedDocumentContextParameter">ScenarioSpecifiedDocumentContextParameter</span> | [edi3:Parameter](#Parameter)
<span id="MessageStandardSpecifiedDocumentContextParameter">MessageStandardSpecifiedDocumentContextParameter</span> | [edi3:Parameter](#Parameter)
<span id="BusinessProcessSpecifiedDocumentContextParameter">BusinessProcessSpecifiedDocumentContextParameter</span> | [edi3:Parameter](#Parameter)
<span id="UserSpecifiedDocumentContextParameter">UserSpecifiedDocumentContextParameter</span> | [edi3:Parameter](#Parameter)
<span id="SpecifiedTransactionIdentifier">SpecifiedTransactionIdentifier</span> | xsd:token


<h1 id="CustomsValuation">CustomsValuation</h1>

Type: rdf:Class

Comments: A cross-border trade related assessment of the worth of an object, such as its monetary value, for customs purposes.

Properties: 

Name | Type 
-|-
<span id="BuyerSellerRelationshipIndicator">BuyerSellerRelationshipIndicator</span> | xsd:boolean
<span id="ChargeApportionMethodCode">ChargeApportionMethodCode</span> | xsd:token
<span id="SalePriceConditionIndicator">SalePriceConditionIndicator</span> | xsd:boolean
<span id="ApplicableTradeCurrencyExchange">ApplicableTradeCurrencyExchange</span> | [edi3:CurrencyExchange](#CurrencyExchange)
<span id="AddedAdjustmentAmount">AddedAdjustmentAmount</span> | xsd:decimal
<span id="TypeCode">TypeCode</span> | xsd:token
<span id="OtherChargeAmount">OtherChargeAmount</span> | xsd:decimal
<span id="AddedAdjustmentPercent">AddedAdjustmentPercent</span> | xsd:decimal
<span id="WTOAdditionCode">WTOAdditionCode</span> | xsd:token
<span id="SaleRestrictionText">SaleRestrictionText</span> | xsd:string
<span id="MethodCode">MethodCode</span> | xsd:token
<span id="RoyaltyLicenseFeeIndicator">RoyaltyLicenseFeeIndicator</span> | xsd:boolean
<span id="SaleRestrictionIndicator">SaleRestrictionIndicator</span> | xsd:boolean
<span id="BuyerSellerRelationshipPriceInfluenceIndicator">BuyerSellerRelationshipPriceInfluenceIndicator</span> | xsd:boolean
<span id="DeductedAdjustmentPercent">DeductedAdjustmentPercent</span> | xsd:decimal


<h1 id="DeliveryTerms">DeliveryTerms</h1>

Type: rdf:Class

Comments: Conditions agreed upon between the parties with regard to the delivery of goods and or services for trade purposes.

Properties: 

Name | Type 
-|-
<span id="DeliveryTypeDeliveryTermsCode">DeliveryTypeDeliveryTermsCode</span> | xsd:token
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="PartialDeliveryAllowedIndicator">PartialDeliveryAllowedIndicator</span> | xsd:boolean
<span id="FunctionDeliveryTermsFunctionCode">FunctionDeliveryTermsFunctionCode</span> | xsd:token
<span id="DeliveryDiscontinuationCode">DeliveryDiscontinuationCode</span> | xsd:token


<h1 id="Keyword">Keyword</h1>

Type: rdf:Class

Comments: A significant word, part of word or phrase that is used to enable indexing of or searching within a textual repository, such as a product catalogue or library.

Properties: 

Name | Type 
-|-


<h1 id="CurrencyExchange">CurrencyExchange</h1>

Type: rdf:Class

Comments: The conversion of one currency to another for trade purposes.

Properties: 

Name | Type 
-|-
<span id="ConversionRateDateTime">ConversionRateDateTime</span> | xsd:dateTime
<span id="AssociatedReferencedDocument">AssociatedReferencedDocument</span> | [edi3:Document](#Document)
<span id="SourceUnitBasisNumeric">SourceUnitBasisNumeric</span> | xsd:decimal
<span id="SourceCurrencyCurrencyCode">SourceCurrencyCurrencyCode</span> | xsd:token
<span id="MarketIdentifier">MarketIdentifier</span> | xsd:token
<span id="TargetCurrencyCurrencyCode">TargetCurrencyCurrencyCode</span> | xsd:token
<span id="ConversionRate">ConversionRate</span> | xsd:decimal


<h1 id="Dimension">Dimension</h1>

Type: rdf:Class

Comments: <br/>A measure of spatial extent associated with this work item, such as length, breadth, or height.<br/>A measure of spatial extent of an object, such as the length, breadth or height of a shipping container.<br/>

Properties: 

Name | Type 
-|-
<span id="WidthMeasure">WidthMeasure</span> | xsd:decimal
<span id="TypeCode">TypeCode</span> | xsd:token
<span id="DiameterLinearUnitMeasure">DiameterLinearUnitMeasure</span> | xsd:decimal
<span id="ValueMeasure">ValueMeasure</span> | xsd:decimal
<span id="ComponentWorkItemDimension">ComponentWorkItemDimension</span> | [edi3:Dimension](#Dimension)
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="ContractualLanguageCode">ContractualLanguageCode</span> | xsd:token
<span id="LengthMeasure">LengthMeasure</span> | xsd:decimal
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="TypeDimensionTypeCode">TypeDimensionTypeCode</span> | xsd:token


<h1 id="BinaryFile">BinaryFile</h1>

Type: rdf:Class

Comments: A specified computer file or program stored in a binary format.

Properties: 

Name | Type 
-|-
<span id="IncludedBinaryObject">IncludedBinaryObject</span> | xsd:base64Binary
<span id="FileNameText">FileNameText</span> | xsd:string
<span id="EncodingCode">EncodingCode</span> | xsd:token
<span id="AuthorNameText">AuthorNameText</span> | xsd:string
<span id="SizeMeasure">SizeMeasure</span> | xsd:decimal
<span id="TitleText">TitleText</span> | xsd:string
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="AccessAvailabilitySpecifiedPeriod">AccessAvailabilitySpecifiedPeriod</span> | [edi3:Period](#Period)
<span id="AccessText">AccessText</span> | xsd:string
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="VersionIdentifier">VersionIdentifier</span> | xsd:token
<span id="CharacterSetCode">CharacterSetCode</span> | xsd:token
<span id="MIMECode">MIMECode</span> | xsd:token


<h1 id="Section">Section</h1>

Type: rdf:Class

Comments: The parts into which a label is or may be divided.

Properties: 

Name | Type 
-|-
<span id="IncludedSectionSegment">IncludedSectionSegment</span> | [edi3:Segment](#Segment)
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token


<h1 id="GeographicalPoint">GeographicalPoint</h1>

Type: rdf:Class

Comments: A point on the surface of the Earth (reference ISO 19136).

Properties: 

Name | Type 
-|-
<span id="AssociatedSpecifiedGeographicalObjectCharacteristic">AssociatedSpecifiedGeographicalObjectCharacteristic</span> | [edi3:GeographicalObjectCharacteristic](#GeographicalObjectCharacteristic)
<span id="AssociatedLogisticsLocation">AssociatedLogisticsLocation</span> | [edi3:Location](#Location)


<h1 id="Marketplace">Marketplace</h1>

Type: rdf:Class

Comments: An actual or virtual place where buyers and sellers interact, directly or through intermediaries, to trade goods or services.

Properties: 

Name | Type 
-|-
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="VirtualIndicator">VirtualIndicator</span> | xsd:boolean
<span id="OrderingAvailablePeriod">OrderingAvailablePeriod</span> | [edi3:Period](#Period)
<span id="NameText">NameText</span> | xsd:string
<span id="WebsiteURIIdentifier">WebsiteURIIdentifier</span> | xsd:token


<h1 id="Authentication">Authentication</h1>

Type: rdf:Class

Comments: A proof that a document is genuine.

Properties: 

Name | Type 
-|-
<span id="InformationText">InformationText</span> | xsd:string
<span id="ProviderTradeParty">ProviderTradeParty</span> | [edi3:Party](#Party)
<span id="RepresentationTypeCode">RepresentationTypeCode</span> | xsd:token
<span id="StatementText">StatementText</span> | xsd:string
<span id="SignatoryImageBinaryObject">SignatoryImageBinaryObject</span> | xsd:base64Binary
<span id="TypeGovernmentActionCode">TypeGovernmentActionCode</span> | xsd:token
<span id="CategoryCode">CategoryCode</span> | xsd:token
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="StatementCode">StatementCode</span> | xsd:token
<span id="IssueLogisticsLocation">IssueLogisticsLocation</span> | [edi3:Location](#Location)
<span id="SignatoryText">SignatoryText</span> | xsd:string
<span id="ProviderReferencedParty">ProviderReferencedParty</span> | [edi3:Party](#Party)
<span id="IncludedDocumentClause">IncludedDocumentClause</span> | [edi3:Clause](#Clause)
<span id="LocationProviderTradeParty">LocationProviderTradeParty</span> | [edi3:Party](#Party)


<h1 id="Parameter">Parameter</h1>

Type: rdf:Class

Comments: <br/>A set of measurable factors that specifies the conditions within which an entity operates correctly.<br/>A set of measurable factors that specifies the conditions of its operation within a specific context.<br/>A feature that is fixed for a particular document context.<br/>

Properties: 

Name | Type 
-|-
<span id="DefinedSpecifiedRange">DefinedSpecifiedRange</span> | [edi3:Range](#Range)
<span id="ValueText">ValueText</span> | xsd:string
<span id="TypeCode">TypeCode</span> | xsd:token
<span id="SpecifiedDocumentVersion">SpecifiedDocumentVersion</span> | [edi3:Version](#Version)
<span id="RequestedSpecifiedRange">RequestedSpecifiedRange</span> | [edi3:Range](#Range)
<span id="ValueMeasure">ValueMeasure</span> | xsd:decimal
<span id="ValueAllowedIndicator">ValueAllowedIndicator</span> | xsd:boolean
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="NameText">NameText</span> | xsd:string
<span id="ChangeableIndicator">ChangeableIndicator</span> | xsd:boolean


<h1 id="PaymentPenaltyTerms">PaymentPenaltyTerms</h1>

Type: rdf:Class

Comments: Trade terms and conditions by which a penalty is or can be applied to a payable amount.

Properties: 

Name | Type 
-|-
<span id="CalculationPercent">CalculationPercent</span> | xsd:decimal
<span id="BasisPeriodMeasure">BasisPeriodMeasure</span> | xsd:decimal
<span id="ActualPenaltyAmount">ActualPenaltyAmount</span> | xsd:decimal
<span id="BasisDateTime">BasisDateTime</span> | xsd:dateTime


<h1 id="Event">Event</h1>

Type: rdf:Class

Comments: <br/>A significant occurrence or happening communicated by means of sending or receiving information, such as transmitting digital data by using the internet.<br/>A significant occurrence or happening during transport.<br/>A referenced significant occurrence or happening during transport.<br/>A significant occurrence or happening in a supply chain.<br/>

Properties: 

Name | Type 
-|-
<span id="TransportMeansStayOccurrenceSpecifiedPeriod">TransportMeansStayOccurrenceSpecifiedPeriod</span> | [edi3:Period](#Period)
<span id="AssociatedSpecifiedGeographicalFeature">AssociatedSpecifiedGeographicalFeature</span> | [edi3:GeographicalFeature](#GeographicalFeature)
<span id="ExpectedIndicator">ExpectedIndicator</span> | xsd:boolean
<span id="CargoFacilityRelatedLogisticsLocation">CargoFacilityRelatedLogisticsLocation</span> | [edi3:Location](#Location)
<span id="ReceivedFormattedDateTime">ReceivedFormattedDateTime</span> | xsd:dateTime
<span id="UnitQuantity">UnitQuantity</span> | xsd:decimal
<span id="OccurrenceDateTime">OccurrenceDateTime</span> | xsd:dateTime
<span id="RequestedOccurrenceDateTime">RequestedOccurrenceDateTime</span> | xsd:dateTime
<span id="TypeCode">TypeCode</span> | xsd:token
<span id="StaySpecifiedReferencedTransportEvent">StaySpecifiedReferencedTransportEvent</span> | [edi3:Event](#Event)
<span id="ScheduledArrivalRelatedDateTime">ScheduledArrivalRelatedDateTime</span> | xsd:dateTime
<span id="ActualOccurrenceSpecifiedPeriod">ActualOccurrenceSpecifiedPeriod</span> | [edi3:Period](#Period)
<span id="ScheduledDepartureRelatedFormattedDateTime">ScheduledDepartureRelatedFormattedDateTime</span> | xsd:dateTime
<span id="OccurrenceLogisticsLocation">OccurrenceLogisticsLocation</span> | [edi3:Location](#Location)
<span id="ScheduledArrivalRelatedFormattedDateTime">ScheduledArrivalRelatedFormattedDateTime</span> | xsd:dateTime
<span id="ActualOccurrenceDateTime">ActualOccurrenceDateTime</span> | xsd:dateTime
<span id="EstimatedTransportMeansArrivalOccurrenceDateTime">EstimatedTransportMeansArrivalOccurrenceDateTime</span> | xsd:dateTime
<span id="SpecifiedTransportInstructions">SpecifiedTransportInstructions</span> | [edi3:Instructions](#Instructions)
<span id="ActualArrivalRelatedDateTime">ActualArrivalRelatedDateTime</span> | xsd:dateTime
<span id="ScheduledOccurrenceDateTime">ScheduledOccurrenceDateTime</span> | xsd:dateTime
<span id="ValueMeasure">ValueMeasure</span> | xsd:decimal
<span id="OccurrenceSpecifiedPeriod">OccurrenceSpecifiedPeriod</span> | [edi3:Period](#Period)
<span id="DelaySpecifiedReferencedTransportEvent">DelaySpecifiedReferencedTransportEvent</span> | [edi3:Event](#Event)
<span id="FrequencyCode">FrequencyCode</span> | xsd:token
<span id="RequestedRelatedReferencedTransportService">RequestedRelatedReferencedTransportService</span> | [edi3:Service](#Service)
<span id="ScheduledOccurrenceSpecifiedPeriod">ScheduledOccurrenceSpecifiedPeriod</span> | [edi3:Period](#Period)
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="ConveyanceFacilityRelatedLogisticsLocation">ConveyanceFacilityRelatedLogisticsLocation</span> | [edi3:Location](#Location)
<span id="AdditionalSecurityMeasuresApplicableNote">AdditionalSecurityMeasuresApplicableNote</span> | [edi3:Note](#Note)
<span id="EarliestOccurrenceDateTime">EarliestOccurrenceDateTime</span> | xsd:dateTime
<span id="ReportedConditionTypeLogisticsStatusCode">ReportedConditionTypeLogisticsStatusCode</span> | xsd:token
<span id="TimeOccurrenceTimeOnlyFormattedDateTime">TimeOccurrenceTimeOnlyFormattedDateTime</span> | xsd:dateTime
<span id="ArrivalRelatedDateTime">ArrivalRelatedDateTime</span> | xsd:dateTime
<span id="OperationalResponsibleTradeParty">OperationalResponsibleTradeParty</span> | [edi3:Party](#Party)
<span id="ReportingMonitoringIOTDevice">ReportingMonitoringIOTDevice</span> | [edi3:IOTDevice](#IOTDevice)
<span id="RelatedSpecifiedObservation">RelatedSpecifiedObservation</span> | [edi3:Observation](#Observation)
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="RelatedTransportRoute">RelatedTransportRoute</span> | [edi3:Route](#Route)
<span id="SecurityLevelCode">SecurityLevelCode</span> | xsd:token
<span id="ScheduledDepartureRelatedDateTime">ScheduledDepartureRelatedDateTime</span> | xsd:dateTime
<span id="ValueUnitMeasure">ValueUnitMeasure</span> | xsd:decimal
<span id="LatestOccurrenceDateTime">LatestOccurrenceDateTime</span> | xsd:dateTime
<span id="DueDateTime">DueDateTime</span> | xsd:dateTime
<span id="EstimatedOccurrenceDateTime">EstimatedOccurrenceDateTime</span> | xsd:dateTime
<span id="DelayOccurrenceSpecifiedPeriod">DelayOccurrenceSpecifiedPeriod</span> | [edi3:Period](#Period)
<span id="PreviousAssociatedSpecifiedGeographicalFeature">PreviousAssociatedSpecifiedGeographicalFeature</span> | [edi3:GeographicalFeature](#GeographicalFeature)
<span id="ReasonTypeCode">ReasonTypeCode</span> | xsd:token
<span id="DepartureRelatedDateTime">DepartureRelatedDateTime</span> | xsd:dateTime
<span id="LaycanOccurrenceSpecifiedPeriod">LaycanOccurrenceSpecifiedPeriod</span> | [edi3:Period](#Period)
<span id="CertifyingTradeParty">CertifyingTradeParty</span> | [edi3:Party](#Party)
<span id="ReasonCode">ReasonCode</span> | xsd:token
<span id="ApplicableNote">ApplicableNote</span> | [edi3:Note](#Note)
<span id="DescriptionBinaryObject">DescriptionBinaryObject</span> | xsd:base64Binary


<h1 id="GeographicalMultiCurve">GeographicalMultiCurve</h1>

Type: rdf:Class

Comments: A collection of curves on the surface of the Earth (reference ISO 19136).

Properties: 

Name | Type 
-|-
<span id="AssociatedSpecifiedDirectPositionList">AssociatedSpecifiedDirectPositionList</span> | [edi3:DirectPositionList](#DirectPositionList)
<span id="AssociatedSpecifiedGeographicalObjectCharacteristic">AssociatedSpecifiedGeographicalObjectCharacteristic</span> | [edi3:GeographicalObjectCharacteristic](#GeographicalObjectCharacteristic)


<h1 id="LinearRing">LinearRing</h1>

Type: rdf:Class

Comments: A specified array of points which define a closed loop which is not self intersecting.

Properties: 

Name | Type 
-|-
<span id="SpecifiedFLUXGeographicalCoordinate">SpecifiedFLUXGeographicalCoordinate</span> | [edi3:GeographicalCoordinate](#GeographicalCoordinate)
<span id="CoordinateText">CoordinateText</span> | xsd:string
<span id="CoordinateSpecifiedDirectPosition">CoordinateSpecifiedDirectPosition</span> | [edi3:DirectPosition](#DirectPosition)


<h1 id="TradeAgreement">TradeAgreement</h1>

Type: rdf:Class

Comments: <br/>The contractual terms of a line trade agreement.<br/>The contractual terms of a subordinate line trade agreement.<br/>The contractual terms of a header trade agreement.<br/>

Properties: 

Name | Type 
-|-
<span id="ApplicableTradePaymentTerms">ApplicableTradePaymentTerms</span> | [edi3:PaymentTerms](#PaymentTerms)
<span id="GrossPriceProductTradePrice">GrossPriceProductTradePrice</span> | [edi3:Price](#Price)
<span id="UltimateCustomerOrderReferencedDocument">UltimateCustomerOrderReferencedDocument</span> | [edi3:Document](#Document)
<span id="PickUpOrderFulfilmentLeadTimeDurationUnitMeasure">PickUpOrderFulfilmentLeadTimeDurationUnitMeasure</span> | xsd:decimal
<span id="SupplyInstructionReferencedDocument">SupplyInstructionReferencedDocument</span> | [edi3:Document](#Document)
<span id="TargetMarketTradeCountry">TargetMarketTradeCountry</span> | [edi3:Country](#Country)
<span id="PrimeContractSellerTradeParty">PrimeContractSellerTradeParty</span> | [edi3:Party](#Party)
<span id="BuyerApprovedFormattedDateTime">BuyerApprovedFormattedDateTime</span> | xsd:dateTime
<span id="BuyerReferenceText">BuyerReferenceText</span> | xsd:string
<span id="BlanketOrderReferencedDocument">BlanketOrderReferencedDocument</span> | [edi3:Document](#Document)
<span id="ImmediatePreviousPriceListReferencedDocument">ImmediatePreviousPriceListReferencedDocument</span> | [edi3:Document](#Document)
<span id="IncludedSpecifiedMarketplace">IncludedSpecifiedMarketplace</span> | [edi3:Marketplace](#Marketplace)
<span id="MinimumOrderQuantityOrderingSpecifiedPeriod">MinimumOrderQuantityOrderingSpecifiedPeriod</span> | [edi3:Period](#Period)
<span id="DemandForecastReferencedDocument">DemandForecastReferencedDocument</span> | [edi3:Document](#Document)
<span id="CarrierTradeParty">CarrierTradeParty</span> | [edi3:Party](#Party)
<span id="ResaleSpecifiedPeriod">ResaleSpecifiedPeriod</span> | [edi3:Period](#Period)
<span id="ItemSellerTradeParty">ItemSellerTradeParty</span> | [edi3:Party](#Party)
<span id="SpecifiedProcuringProject">SpecifiedProcuringProject</span> | [edi3:Project](#Project)
<span id="SellerAssignedAccountantTradeParty">SellerAssignedAccountantTradeParty</span> | [edi3:Party](#Party)
<span id="ApplicableLogisticsLocation">ApplicableLogisticsLocation</span> | [edi3:Location](#Location)
<span id="PreviousOrderReferencedDocument">PreviousOrderReferencedDocument</span> | [edi3:Document](#Document)
<span id="BuyerRequisitionerTradeParty">BuyerRequisitionerTradeParty</span> | [edi3:Party](#Party)
<span id="DeliveryOrderFulfilmentLeadTimeDurationUnitMeasure">DeliveryOrderFulfilmentLeadTimeDurationUnitMeasure</span> | xsd:decimal
<span id="ProcurementTradeParty">ProcurementTradeParty</span> | [edi3:Party](#Party)
<span id="PreviousOrderChangeReferencedDocument">PreviousOrderChangeReferencedDocument</span> | [edi3:Document](#Document)
<span id="CatalogueInformationProviderTradeParty">CatalogueInformationProviderTradeParty</span> | [edi3:Party](#Party)
<span id="OriginalOrderReferencedDocument">OriginalOrderReferencedDocument</span> | [edi3:Document](#Document)
<span id="QuotationRequestResponseReferencedDocument">QuotationRequestResponseReferencedDocument</span> | [edi3:Document](#Document)
<span id="EconomicOrderQuantity">EconomicOrderQuantity</span> | xsd:decimal
<span id="MinimumProductOrderableQuantity">MinimumProductOrderableQuantity</span> | xsd:decimal
<span id="CatalogueSubscriptionReferencedDocument">CatalogueSubscriptionReferencedDocument</span> | [edi3:Document](#Document)
<span id="SellerOrderReferencedDocument">SellerOrderReferencedDocument</span> | [edi3:Document](#Document)
<span id="SellerTaxRepresentativeTradeParty">SellerTaxRepresentativeTradeParty</span> | [edi3:Party](#Party)
<span id="BuyerTradeParty">BuyerTradeParty</span> | [edi3:Party](#Party)
<span id="LetterOfCreditReferencedDocument">LetterOfCreditReferencedDocument</span> | [edi3:Document](#Document)
<span id="ResaleProductUnitMeasureCode">ResaleProductUnitMeasureCode</span> | xsd:token
<span id="OrderPriceProductTradePrice">OrderPriceProductTradePrice</span> | [edi3:Price](#Price)
<span id="ProgramMissionProject">ProgramMissionProject</span> | [edi3:Project](#Project)
<span id="NetPriceProductTradePrice">NetPriceProductTradePrice</span> | [edi3:Price](#Price)
<span id="ApplicableSupplyChainForecastTerms">ApplicableSupplyChainForecastTerms</span> | [edi3:ForecastTerms](#ForecastTerms)
<span id="BuyerAssignedAccountantTradeParty">BuyerAssignedAccountantTradeParty</span> | [edi3:Party](#Party)
<span id="CatalogueReferencedDocument">CatalogueReferencedDocument</span> | [edi3:Document](#Document)
<span id="ReferenceText">ReferenceText</span> | xsd:string
<span id="ExclusivitySpecifiedPeriod">ExclusivitySpecifiedPeriod</span> | [edi3:Period](#Period)
<span id="PurchaseConditionsReferencedDocument">PurchaseConditionsReferencedDocument</span> | [edi3:Document](#Document)
<span id="IncrementalProductOrderableQuantity">IncrementalProductOrderableQuantity</span> | xsd:decimal
<span id="ApplicableTradeDeliveryTerms">ApplicableTradeDeliveryTerms</span> | [edi3:DeliveryTerms](#DeliveryTerms)
<span id="QuotationRequestReferencedDocument">QuotationRequestReferencedDocument</span> | [edi3:Document](#Document)
<span id="ExportLicenceReferencedDocument">ExportLicenceReferencedDocument</span> | [edi3:Document](#Document)
<span id="ImportLicenceReferencedDocument">ImportLicenceReferencedDocument</span> | [edi3:Document](#Document)
<span id="InformationUseRestrictionIndicator">InformationUseRestrictionIndicator</span> | xsd:boolean
<span id="ShippingSpecifiedPeriod">ShippingSpecifiedPeriod</span> | [edi3:Period](#Period)
<span id="SalesConditionsReferencedDocument">SalesConditionsReferencedDocument</span> | [edi3:Document](#Document)
<span id="ContractReferencedDocument">ContractReferencedDocument</span> | [edi3:Document](#Document)
<span id="OrderResponseReferencedDocument">OrderResponseReferencedDocument</span> | [edi3:Document](#Document)
<span id="RequisitionerReferencedDocument">RequisitionerReferencedDocument</span> | [edi3:Document](#Document)
<span id="RequisitionReferencedDocument">RequisitionReferencedDocument</span> | [edi3:Document](#Document)
<span id="OrderProductUnitMeasureCode">OrderProductUnitMeasureCode</span> | xsd:token
<span id="BuyerAgentTradeParty">BuyerAgentTradeParty</span> | [edi3:Party](#Party)
<span id="RevisionIdentificationIdentifier">RevisionIdentificationIdentifier</span> | xsd:token
<span id="PriceListReferencedDocument">PriceListReferencedDocument</span> | [edi3:Document](#Document)
<span id="PreviousOrderResponseReferencedDocument">PreviousOrderResponseReferencedDocument</span> | [edi3:Document](#Document)
<span id="BuyerOrderReferencedDocument">BuyerOrderReferencedDocument</span> | [edi3:Document](#Document)
<span id="DeliveryPriorityPriorityDescriptionCode">DeliveryPriorityPriorityDescriptionCode</span> | xsd:token
<span id="SalesReportReferencedDocument">SalesReportReferencedDocument</span> | [edi3:Document](#Document)
<span id="QuotationProposalResponseReferencedDocument">QuotationProposalResponseReferencedDocument</span> | [edi3:Document](#Document)
<span id="PromotionalDealReferencedDocument">PromotionalDealReferencedDocument</span> | [edi3:Document](#Document)
<span id="CatalogueInformationReceiverTradeParty">CatalogueInformationReceiverTradeParty</span> | [edi3:Party](#Party)
<span id="MaximumProductOrderableQuantity">MaximumProductOrderableQuantity</span> | xsd:decimal
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="GuaranteedProductLifeSpanSpecifiedPeriod">GuaranteedProductLifeSpanSpecifiedPeriod</span> | [edi3:Period](#Period)
<span id="ProductReorderableIndicator">ProductReorderableIndicator</span> | xsd:boolean
<span id="RelevantTradeParty">RelevantTradeParty</span> | [edi3:Party](#Party)
<span id="BuyerTaxRepresentativeTradeParty">BuyerTaxRepresentativeTradeParty</span> | [edi3:Party](#Party)
<span id="ProductEndUserTradeParty">ProductEndUserTradeParty</span> | [edi3:Party](#Party)
<span id="CatalogueRequestReferencedDocument">CatalogueRequestReferencedDocument</span> | [edi3:Document](#Document)
<span id="ApplicableCrossBorderRegulatoryProcedure">ApplicableCrossBorderRegulatoryProcedure</span> | [edi3:RegulatoryProcedure](#RegulatoryProcedure)
<span id="SalesAgentTradeParty">SalesAgentTradeParty</span> | [edi3:Party](#Party)
<span id="MarketplaceOrderReferencedDocument">MarketplaceOrderReferencedDocument</span> | [edi3:Document](#Document)
<span id="PricingBaseApplicableLogisticsLocation">PricingBaseApplicableLogisticsLocation</span> | [edi3:Location](#Location)
<span id="AdditionalReferencedDocument">AdditionalReferencedDocument</span> | [edi3:Document](#Document)
<span id="MaximumOrderQuantityOrderingSpecifiedPeriod">MaximumOrderQuantityOrderingSpecifiedPeriod</span> | [edi3:Period](#Period)
<span id="ItemBuyerTradeParty">ItemBuyerTradeParty</span> | [edi3:Party](#Party)
<span id="QuotationProposalReferencedDocument">QuotationProposalReferencedDocument</span> | [edi3:Document](#Document)
<span id="SupportCentreTradeParty">SupportCentreTradeParty</span> | [edi3:Party](#Party)
<span id="SellerReferenceText">SellerReferenceText</span> | xsd:string
<span id="QuotationReferencedDocument">QuotationReferencedDocument</span> | [edi3:Document](#Document)
<span id="ProductAvailabilityCode">ProductAvailabilityCode</span> | xsd:token
<span id="QuoteReferencedTradeWorkflowObject">QuoteReferencedTradeWorkflowObject</span> | [edi3:WorkflowObject](#WorkflowObject)
<span id="ImpactCode">ImpactCode</span> | xsd:token
<span id="PriorityCode">PriorityCode</span> | xsd:token
<span id="OrderingSpecifiedPeriod">OrderingSpecifiedPeriod</span> | [edi3:Period](#Period)
<span id="SellerTradeParty">SellerTradeParty</span> | [edi3:Party](#Party)
<span id="EngineeringChangeReferencedDocument">EngineeringChangeReferencedDocument</span> | [edi3:Document](#Document)
<span id="ProductMadeToOrderIndicator">ProductMadeToOrderIndicator</span> | xsd:boolean


<h1 id="DirectPosition">DirectPosition</h1>

Type: rdf:Class

Comments: A specified physical location described within a coordinate reference system.

Properties: 

Name | Type 
-|-
<span id="UOMLabelListText">UOMLabelListText</span> | xsd:string
<span id="NameText">NameText</span> | xsd:string
<span id="AxisLabelListText">AxisLabelListText</span> | xsd:string
<span id="CountNumeric">CountNumeric</span> | xsd:decimal


<h1 id="AllowanceCharge">AllowanceCharge</h1>

Type: rdf:Class

Comments: <br/>A component of pricing, such as an allowance or charge for trade purposes.<br/>The applied allowance or charge component of pricing.<br/>

Properties: 

Name | Type 
-|-
<span id="UnitBasisAmount">UnitBasisAmount</span> | xsd:decimal
<span id="ReasonAllowanceChargeReasonCode">ReasonAllowanceChargeReasonCode</span> | xsd:token
<span id="BasisAmount">BasisAmount</span> | xsd:decimal
<span id="ReasonText">ReasonText</span> | xsd:string
<span id="ChargeIndicator">ChargeIndicator</span> | xsd:boolean
<span id="CalculationPercent">CalculationPercent</span> | xsd:decimal
<span id="ActualTradeCurrencyExchange">ActualTradeCurrencyExchange</span> | [edi3:CurrencyExchange](#CurrencyExchange)
<span id="ActualAmount">ActualAmount</span> | xsd:decimal
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="CategoryTradeTax">CategoryTradeTax</span> | [edi3:Tax](#Tax)
<span id="SequenceNumeric">SequenceNumeric</span> | xsd:decimal
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="CategoryAppliedTax">CategoryAppliedTax</span> | [edi3:Tax](#Tax)
<span id="TypeAllowanceChargeIdentificationCode">TypeAllowanceChargeIdentificationCode</span> | xsd:token
<span id="ReasonCode">ReasonCode</span> | xsd:token
<span id="PrepaidIndicator">PrepaidIndicator</span> | xsd:boolean


<h1 id="Label">Label</h1>

Type: rdf:Class

Comments: A label used for identifying goods for logistics purposes, such as a barcode, a radio frequency tag or a Vehicle Identification Number (VIN).

Properties: 

Name | Type 
-|-
<span id="LayoutTypeCode">LayoutTypeCode</span> | xsd:token
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="SizeCode">SizeCode</span> | xsd:token
<span id="SeriesStartIdentifier">SeriesStartIdentifier</span> | xsd:token
<span id="IncludedLabelSection">IncludedLabelSection</span> | [edi3:Section](#Section)


<h1 id="Tax">Tax</h1>

Type: rdf:Class

Comments: <br/>A total levy or payment for the support of a government that is required of persons, groups, or businesses within the domain of that government.<br/>A trade related fiscal levy or duty.<br/>A registered tax or duty system pertaining to an authority.<br/>

Properties: 

Name | Type 
-|-
<span id="BasisQuantity">BasisQuantity</span> | xsd:decimal
<span id="CalculationSequenceNumeric">CalculationSequenceNumeric</span> | xsd:decimal
<span id="CategoryNameText">CategoryNameText</span> | xsd:string
<span id="CurrencyCurrencyCode">CurrencyCurrencyCode</span> | xsd:token
<span id="UnitBasisAmount">UnitBasisAmount</span> | xsd:decimal
<span id="CustomsDutyIndicator">CustomsDutyIndicator</span> | xsd:boolean
<span id="SellerPayableTaxSpecifiedTradeAccountingAccount">SellerPayableTaxSpecifiedTradeAccountingAccount</span> | [edi3:AccountingAccount](#AccountingAccount)
<span id="SelfAssessedBasisQuantity">SelfAssessedBasisQuantity</span> | xsd:decimal
<span id="BasisAmount">BasisAmount</span> | xsd:decimal
<span id="CategoryTaxCategoryCode">CategoryTaxCategoryCode</span> | xsd:token
<span id="ApplicablePercent">ApplicablePercent</span> | xsd:decimal
<span id="TypeCode">TypeCode</span> | xsd:token
<span id="TypeTaxTypeCode">TypeTaxTypeCode</span> | xsd:token
<span id="TypeText">TypeText</span> | xsd:string
<span id="PaymentMethodPaymentMethodCode">PaymentMethodPaymentMethodCode</span> | xsd:token
<span id="GuaranteeCode">GuaranteeCode</span> | xsd:token
<span id="JurisdictionText">JurisdictionText</span> | xsd:string
<span id="ExemptionAuthorizationIdentificationIdentifier">ExemptionAuthorizationIdentificationIdentifier</span> | xsd:token
<span id="ExemptionReasonCode">ExemptionReasonCode</span> | xsd:token
<span id="BuyerRepayableTaxSpecifiedTradeAccountingAccount">BuyerRepayableTaxSpecifiedTradeAccountingAccount</span> | [edi3:AccountingAccount](#AccountingAccount)
<span id="PlaceApplicableTradeLocation">PlaceApplicableTradeLocation</span> | [edi3:Location](#Location)
<span id="RateApplicablePercent">RateApplicablePercent</span> | xsd:decimal
<span id="TaxExemptionAuthorityIdentificationIdentifier">TaxExemptionAuthorityIdentificationIdentifier</span> | xsd:token
<span id="BuyerDeductibleTaxSpecifiedTradeAccountingAccount">BuyerDeductibleTaxSpecifiedTradeAccountingAccount</span> | [edi3:AccountingAccount](#AccountingAccount)
<span id="ServiceSupplyTradeCountry">ServiceSupplyTradeCountry</span> | [edi3:Country](#Country)
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="BuyerNonDeductibleTaxSpecifiedTradeAccountingAccount">BuyerNonDeductibleTaxSpecifiedTradeAccountingAccount</span> | [edi3:AccountingAccount](#AccountingAccount)
<span id="RefundAmount">RefundAmount</span> | xsd:decimal
<span id="CalculationMethodCode">CalculationMethodCode</span> | xsd:token
<span id="SellerRefundableTaxSpecifiedTradeAccountingAccount">SellerRefundableTaxSpecifiedTradeAccountingAccount</span> | [edi3:AccountingAccount](#AccountingAccount)
<span id="CalculatedAmount">CalculatedAmount</span> | xsd:decimal
<span id="TariffDeductionQuantity">TariffDeductionQuantity</span> | xsd:decimal
<span id="TaxBasisAllowanceRate">TaxBasisAllowanceRate</span> | xsd:decimal
<span id="GuaranteeText">GuaranteeText</span> | xsd:string
<span id="AllowanceChargeBasisAmount">AllowanceChargeBasisAmount</span> | xsd:decimal
<span id="SpecifiedTradeAccountingAccount">SpecifiedTradeAccountingAccount</span> | [edi3:AccountingAccount](#AccountingAccount)
<span id="ExemptionIndicator">ExemptionIndicator</span> | xsd:boolean
<span id="RegimeTypeCustomsDutyRegimeTypeCode">RegimeTypeCustomsDutyRegimeTypeCode</span> | xsd:token
<span id="DueDateTypeTimeReferenceCode">DueDateTypeTimeReferenceCode</span> | xsd:token
<span id="PaymentIdentifier">PaymentIdentifier</span> | xsd:token
<span id="SelfAssessedBasisAmount">SelfAssessedBasisAmount</span> | xsd:decimal
<span id="SelfAssessedCalculatedAmount">SelfAssessedCalculatedAmount</span> | xsd:decimal
<span id="ExemptionReasonText">ExemptionReasonText</span> | xsd:string
<span id="InformationAmount">InformationAmount</span> | xsd:decimal
<span id="TaxPointDate">TaxPointDate</span> | xsd:date
<span id="DeductionAmount">DeductionAmount</span> | xsd:decimal
<span id="GrandTotalAmount">GrandTotalAmount</span> | xsd:decimal
<span id="CalculatedRate">CalculatedRate</span> | xsd:decimal
<span id="LineTotalBasisAmount">LineTotalBasisAmount</span> | xsd:decimal
<span id="RateCode">RateCode</span> | xsd:token


<h1 id="Process">Process</h1>

Type: rdf:Class

Comments: A naturally occurring or designed sequence of operations or events that create, transform, or touch a product, such as manufacturing, treating, packaging, and storing.

Properties: 

Name | Type 
-|-
<span id="CompletionSpecifiedPeriod">CompletionSpecifiedPeriod</span> | [edi3:Period](#Period)
<span id="OperationTradeCountry">OperationTradeCountry</span> | [edi3:Country](#Country)
<span id="OperatorTradeParty">OperatorTradeParty</span> | [edi3:Party](#Party)
<span id="ApplicableProcessCharacteristic">ApplicableProcessCharacteristic</span> | [edi3:Characteristic](#Characteristic)


<h1 id="BreakdownStatement">BreakdownStatement</h1>

Type: rdf:Class

Comments: A detailed statement of work, prices, and dimensions for this valuation.

Properties: 

Name | Type 
-|-
<span id="TypeCode">TypeCode</span> | xsd:token
<span id="DefaultLanguageCode">DefaultLanguageCode</span> | xsd:token
<span id="ItemBasicWorkItem">ItemBasicWorkItem</span> | [edi3:WorkItem](#WorkItem)
<span id="CreationSpecifiedBinaryFile">CreationSpecifiedBinaryFile</span> | [edi3:BinaryFile](#BinaryFile)
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="CommentText">CommentText</span> | xsd:string
<span id="ContractualLanguageCode">ContractualLanguageCode</span> | xsd:token
<span id="ReferencedSpecifiedBinaryFile">ReferencedSpecifiedBinaryFile</span> | [edi3:BinaryFile](#BinaryFile)
<span id="RequestedActionCode">RequestedActionCode</span> | xsd:token
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="TotalCalculatedPrice">TotalCalculatedPrice</span> | [edi3:Price](#Price)
<span id="ChangedRecordedStatus">ChangedRecordedStatus</span> | [edi3:Status](#Status)
<span id="MeasurementMethodIdentificationIdentifier">MeasurementMethodIdentificationIdentifier</span> | xsd:token
<span id="NameText">NameText</span> | xsd:string
<span id="ItemGroupedWorkItem">ItemGroupedWorkItem</span> | [edi3:WorkItem](#WorkItem)
<span id="ReaderSpecifiedBinaryFile">ReaderSpecifiedBinaryFile</span> | [edi3:BinaryFile](#BinaryFile)
<span id="DefaultCurrencyCurrencyCode">DefaultCurrencyCurrencyCode</span> | xsd:token
<span id="PriceListIdentificationIdentifier">PriceListIdentificationIdentifier</span> | xsd:token


<h1 id="ForecastTerms">ForecastTerms</h1>

Type: rdf:Class

Comments: A set of terms and conditions by which a supply chain forecast has been or will be made.

Properties: 

Name | Type 
-|-
<span id="ForecastTypeCode">ForecastTypeCode</span> | xsd:token
<span id="FrequencyCode">FrequencyCode</span> | xsd:token
<span id="DateTypeCode">DateTypeCode</span> | xsd:token


<h1 id="GeographicalLine">GeographicalLine</h1>

Type: rdf:Class

Comments: A connection between two points on the surface of the Earth (reference ISO 19136).

Properties: 

Name | Type 
-|-
<span id="AssociatedSpecifiedGeographicalObjectCharacteristic">AssociatedSpecifiedGeographicalObjectCharacteristic</span> | [edi3:GeographicalObjectCharacteristic](#GeographicalObjectCharacteristic)
<span id="AssociatedLogisticsLocation">AssociatedLogisticsLocation</span> | [edi3:Location](#Location)


<h1 id="GeographicalObjectCharacteristic">GeographicalObjectCharacteristic</h1>

Type: rdf:Class

Comments: An attribute of a geographical object.

Properties: 

Name | Type 
-|-
<span id="PhysicalIndicator">PhysicalIndicator</span> | xsd:boolean
<span id="GeometryCollectionIndicator">GeometryCollectionIndicator</span> | xsd:boolean
<span id="ShapeTypeText">ShapeTypeText</span> | xsd:string
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="NameText">NameText</span> | xsd:string
<span id="DescriptionReferenceText">DescriptionReferenceText</span> | xsd:string


<h1 id="Version">Version</h1>

Type: rdf:Class

Comments: A specific variant of a document.

Properties: 

Name | Type 
-|-
<span id="NameText">NameText</span> | xsd:string
<span id="IssueDateTime">IssueDateTime</span> | xsd:dateTime


<h1 id="Registration">Registration</h1>

Type: rdf:Class

Comments: <br/>The recording of items or details for a specific legal purpose.<br/>The recording of items or details for a governmental purpose.<br/>Registration with a specific tax authority.<br/>

Properties: 

Name | Type 
-|-
<span id="LastRegisteredYearDateTime">LastRegisteredYearDateTime</span> | xsd:dateTime
<span id="ValiditySpecifiedPeriod">ValiditySpecifiedPeriod</span> | [edi3:Period](#Period)
<span id="TypeCode">TypeCode</span> | xsd:token
<span id="LastRegisteredYearFormattedDateTime">LastRegisteredYearFormattedDateTime</span> | xsd:dateTime
<span id="CategoryCode">CategoryCode</span> | xsd:token
<span id="LicenceIdentifier">LicenceIdentifier</span> | xsd:token
<span id="AssociatedRegisteredTax">AssociatedRegisteredTax</span> | [edi3:Tax](#Tax)
<span id="IOSSIdentificationIdentifier">IOSSIdentificationIdentifier</span> | xsd:token
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="VersionIdentifier">VersionIdentifier</span> | xsd:token
<span id="CountryIdentifier">CountryIdentifier</span> | xsd:token
<span id="RecordedDate">RecordedDate</span> | xsd:date


<h1 id="GeographicalCoordinate">GeographicalCoordinate</h1>

Type: rdf:Class

Comments: <br/>The latitude and longitude of a specified place, by which its relative situation on the globe is known. The height above the sea level constitutes a third coordinate.<br/>A set of geographical coordinates of a specific point such as the longitude, latitude and altitude.<br/>

Properties: 

Name | Type 
-|-
<span id="LatitudeDirectionIndicator">LatitudeDirectionIndicator</span> | xsd:boolean
<span id="LongitudeDirectionIndicator">LongitudeDirectionIndicator</span> | xsd:boolean
<span id="TimeZoneText">TimeZoneText</span> | xsd:string
<span id="AlternativeSourceSystemIdentifier">AlternativeSourceSystemIdentifier</span> | xsd:token
<span id="AltimetricSystemIdentifier">AltimetricSystemIdentifier</span> | xsd:token
<span id="UsedCSEngineeringCoordinateReferenceSystem">UsedCSEngineeringCoordinateReferenceSystem</span> | [edi3:CoordinateReferenceSystem](#CoordinateReferenceSystem)
<span id="SystemIdentifier">SystemIdentifier</span> | xsd:token
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="TimeZoneFormattedDateTime">TimeZoneFormattedDateTime</span> | xsd:dateTime
<span id="LatitudeMeasure">LatitudeMeasure</span> | xsd:decimal
<span id="AcquisitionDateTime">AcquisitionDateTime</span> | xsd:dateTime
<span id="LongitudeMeasure">LongitudeMeasure</span> | xsd:decimal
<span id="UsedGeographicalCoordinateSourceSystem">UsedGeographicalCoordinateSourceSystem</span> | [edi3:CoordinateSourceSystem](#CoordinateSourceSystem)
<span id="TimeZoneCode">TimeZoneCode</span> | xsd:token


<h1 id="Production">Production</h1>

Type: rdf:Class

Comments: The making or manufacturing of goods, such as from components or raw materials.

Properties: 

Name | Type 
-|-
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token


<h1 id="TransportMovement">TransportMovement</h1>

Type: rdf:Class

Comments: The conveyance (physical carriage) of goods or other objects used for logistics transport purposes.

Properties: 

Name | Type 
-|-
<span id="InspectionTradeParty">InspectionTradeParty</span> | [edi3:Party](#Party)
<span id="CarriedMaterialGoodsCharacteristic">CarriedMaterialGoodsCharacteristic</span> | [edi3:GoodsCharacteristic](#GoodsCharacteristic)
<span id="PassengerNationalityTradeCountry">PassengerNationalityTradeCountry</span> | [edi3:Country](#Country)
<span id="CarrierTradeParty">CarrierTradeParty</span> | [edi3:Party](#Party)
<span id="ManifestRelatedReferencedDocument">ManifestRelatedReferencedDocument</span> | [edi3:Document](#Document)
<span id="UnloadingTransportEvent">UnloadingTransportEvent</span> | [edi3:Event](#Event)
<span id="ApplicableLogisticsServiceCharge">ApplicableLogisticsServiceCharge</span> | [edi3:ServiceCharge](#ServiceCharge)
<span id="TransitDirectionTransportMeansDirectionCode">TransitDirectionTransportMeansDirectionCode</span> | xsd:token
<span id="StageTransportMovementStageCode">StageTransportMovementStageCode</span> | xsd:token
<span id="InformationText">InformationText</span> | xsd:string
<span id="TransportMeansSecurityOfficerTransportPerson">TransportMeansSecurityOfficerTransportPerson</span> | [edi3:Person](#Person)
<span id="NotifiedTradeParty">NotifiedTradeParty</span> | [edi3:Party](#Party)
<span id="FirstArrivalTransportEvent">FirstArrivalTransportEvent</span> | [edi3:Event](#Event)
<span id="TradedParcelQuantity">TradedParcelQuantity</span> | xsd:decimal
<span id="ManifestOnboardIndicator">ManifestOnboardIndicator</span> | xsd:boolean
<span id="PassengerQuantity">PassengerQuantity</span> | xsd:decimal
<span id="ModeText">ModeText</span> | xsd:string
<span id="TransportEquipmentQuantity">TransportEquipmentQuantity</span> | xsd:decimal
<span id="LoadingTransportEvent">LoadingTransportEvent</span> | [edi3:Event](#Event)
<span id="CargoDescriptionText">CargoDescriptionText</span> | xsd:string
<span id="SpecialSpecifiedTransportInstructions">SpecialSpecifiedTransportInstructions</span> | [edi3:Instructions](#Instructions)
<span id="TerminalOperatorAssignedIdentificationIdentifier">TerminalOperatorAssignedIdentificationIdentifier</span> | xsd:token
<span id="ReportedTransportWasteMaterial">ReportedTransportWasteMaterial</span> | [edi3:Material](#Material)
<span id="TransportContractRelatedReferencedDocument">TransportContractRelatedReferencedDocument</span> | [edi3:Document](#Document)
<span id="TypeText">TypeText</span> | xsd:string
<span id="PassengerListRelatedReferencedDocument">PassengerListRelatedReferencedDocument</span> | [edi3:Document](#Document)
<span id="ServiceText">ServiceText</span> | xsd:string
<span id="CommodityConsolidatorTradeParty">CommodityConsolidatorTradeParty</span> | [edi3:Party](#Party)
<span id="SpecifiedCalculatedEmission">SpecifiedCalculatedEmission</span> | [edi3:Emission](#Emission)
<span id="CycleText">CycleText</span> | xsd:string
<span id="BorderCrossingTransportEvent">BorderCrossingTransportEvent</span> | [edi3:Event](#Event)
<span id="CarriedInactiveReferencedTransportMeans">CarriedInactiveReferencedTransportMeans</span> | [edi3:TransportMeans](#TransportMeans)
<span id="TradingConsolidatorAssignedIdentificationIdentifier">TradingConsolidatorAssignedIdentificationIdentifier</span> | xsd:token
<span id="StevedoreTradeParty">StevedoreTradeParty</span> | [edi3:Party](#Party)
<span id="ArrivalTransportEvent">ArrivalTransportEvent</span> | [edi3:Event](#Event)
<span id="AssociatedLogisticsConvoy">AssociatedLogisticsConvoy</span> | [edi3:Convoy](#Convoy)
<span id="ReportedSecurityInformationText">ReportedSecurityInformationText</span> | xsd:string
<span id="CrewSpecifiedPersonalEffects">CrewSpecifiedPersonalEffects</span> | [edi3:PersonalEffects](#PersonalEffects)
<span id="LoadingInspectionSpecifiedTransportInstructions">LoadingInspectionSpecifiedTransportInstructions</span> | [edi3:Instructions](#Instructions)
<span id="ExcessTransportTransportService">ExcessTransportTransportService</span> | [edi3:Service](#Service)
<span id="CommodityConsolidatorAgentTradeParty">CommodityConsolidatorAgentTradeParty</span> | [edi3:Party](#Party)
<span id="ScheduledIdentificationIdentifier">ScheduledIdentificationIdentifier</span> | xsd:token
<span id="PackageQuantity">PackageQuantity</span> | xsd:decimal
<span id="ConsignmentQuantity">ConsignmentQuantity</span> | xsd:decimal
<span id="CallTransportEvent">CallTransportEvent</span> | [edi3:Event](#Event)
<span id="SpecifiedHandlingInstructions">SpecifiedHandlingInstructions</span> | [edi3:Instructions](#Instructions)
<span id="CallPurposeCode">CallPurposeCode</span> | xsd:token
<span id="CarrierAgentTradeParty">CarrierAgentTradeParty</span> | [edi3:Party](#Party)
<span id="ShipToShipTransportEvent">ShipToShipTransportEvent</span> | [edi3:Event](#Event)
<span id="UnloadingInspectionSpecifiedTransportInstructions">UnloadingInspectionSpecifiedTransportInstructions</span> | [edi3:Instructions](#Instructions)
<span id="BorderCrossingDateTime">BorderCrossingDateTime</span> | xsd:dateTime
<span id="DangerousGoodsIndicator">DangerousGoodsIndicator</span> | xsd:boolean
<span id="CrewNationalityTradeCountry">CrewNationalityTradeCountry</span> | [edi3:Country](#Country)
<span id="CrewTransportPerson">CrewTransportPerson</span> | [edi3:Person](#Person)
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="CrewListRelatedReferencedDocument">CrewListRelatedReferencedDocument</span> | [edi3:Document](#Document)
<span id="OnboardStoresItemInventory">OnboardStoresItemInventory</span> | [edi3:Inventory](#Inventory)
<span id="ConsortiumCarrierTradeParty">ConsortiumCarrierTradeParty</span> | [edi3:Party](#Party)
<span id="DocumentaryInstructionsNotifiedTradeParty">DocumentaryInstructionsNotifiedTradeParty</span> | [edi3:Party](#Party)
<span id="UsedLogisticsTransportMeans">UsedLogisticsTransportMeans</span> | [edi3:TransportMeans](#TransportMeans)
<span id="NVOCCCarrierTradeParty">NVOCCCarrierTradeParty</span> | [edi3:Party](#Party)
<span id="TerminalOperatorTradeParty">TerminalOperatorTradeParty</span> | [edi3:Party](#Party)
<span id="NameText">NameText</span> | xsd:string
<span id="StatusStatusCode">StatusStatusCode</span> | xsd:token
<span id="ApplicableCrossBorderRegulatoryProcedure">ApplicableCrossBorderRegulatoryProcedure</span> | [edi3:RegulatoryProcedure](#RegulatoryProcedure)
<span id="SpecifiedLogisticsRiskAnalysisResult">SpecifiedLogisticsRiskAnalysisResult</span> | [edi3:RiskAnalysisResult](#RiskAnalysisResult)
<span id="MasterResponsibleTransportPerson">MasterResponsibleTransportPerson</span> | [edi3:Person](#Person)
<span id="UnloadingInspectionTradeParty">UnloadingInspectionTradeParty</span> | [edi3:Party](#Party)
<span id="ItineraryTransportRoute">ItineraryTransportRoute</span> | [edi3:Route](#Route)
<span id="ModeTransportModeCode">ModeTransportModeCode</span> | xsd:token
<span id="OnboardTransportPerson">OnboardTransportPerson</span> | [edi3:Person](#Person)
<span id="LoadingInspectionTradeParty">LoadingInspectionTradeParty</span> | [edi3:Party](#Party)
<span id="SailingAdviceNotificationInformationText">SailingAdviceNotificationInformationText</span> | xsd:string
<span id="PilotageExemptionIdentifier">PilotageExemptionIdentifier</span> | xsd:token
<span id="ISPSRelatedReferencedDocument">ISPSRelatedReferencedDocument</span> | [edi3:Document](#Document)
<span id="ServiceCode">ServiceCode</span> | xsd:token
<span id="ClosingDateTime">ClosingDateTime</span> | xsd:dateTime
<span id="TransshipmentIntermediateTransportEvent">TransshipmentIntermediateTransportEvent</span> | [edi3:Event](#Event)
<span id="StayIdentifier">StayIdentifier</span> | xsd:token
<span id="SailingAdviceNotifiedTradeParty">SailingAdviceNotifiedTradeParty</span> | [edi3:Party](#Party)
<span id="LiftingInstructionsRelatedReferencedDocument">LiftingInstructionsRelatedReferencedDocument</span> | [edi3:Document](#Document)
<span id="SpecifiedTransportEvent">SpecifiedTransportEvent</span> | [edi3:Event](#Event)
<span id="DepartureTransportEvent">DepartureTransportEvent</span> | [edi3:Event](#Event)


<h1 id="Convoy">Convoy</h1>

Type: rdf:Class

Comments: A number of means of transport following each other with a common logistics purpose.

Properties: 

Name | Type 
-|-
<span id="MaximumWidthLinearUnitMeasure">MaximumWidthLinearUnitMeasure</span> | xsd:decimal
<span id="PowerActiveLogisticsTransportMeans">PowerActiveLogisticsTransportMeans</span> | [edi3:TransportMeans](#TransportMeans)
<span id="PowerInactiveLogisticsTransportMeans">PowerInactiveLogisticsTransportMeans</span> | [edi3:TransportMeans](#TransportMeans)
<span id="TransportMeansQuantity">TransportMeansQuantity</span> | xsd:decimal


<h1 id="Polygon">Polygon</h1>

Type: rdf:Class

Comments: A planar surface, defined by one exterior boundary and zero or more interior boundaries. Each interior boundary defines a hole in the polygon.

Properties: 

Name | Type 
-|-
<span id="AssociatedSpecifiedGeographicalObjectCharacteristic">AssociatedSpecifiedGeographicalObjectCharacteristic</span> | [edi3:GeographicalObjectCharacteristic](#GeographicalObjectCharacteristic)
<span id="AssociatedLogisticsLocation">AssociatedLogisticsLocation</span> | [edi3:Location](#Location)
<span id="ExteriorSpecifiedLinearRing">ExteriorSpecifiedLinearRing</span> | [edi3:LinearRing](#LinearRing)


<h1 id="BalanceOut">BalanceOut</h1>

Type: rdf:Class

Comments: <br/>Offset header information to ensure that debits and credits are equal for a transaction.<br/>Offset information to ensure that debits and credits are equal for a transaction.<br/>

Properties: 

Name | Type 
-|-
<span id="OccurrenceDateTime">OccurrenceDateTime</span> | xsd:dateTime
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="ReasonDescriptionText">ReasonDescriptionText</span> | xsd:string
<span id="CalculatedAmount">CalculatedAmount</span> | xsd:decimal
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="ReasonCode">ReasonCode</span> | xsd:token


<h1 id="Route">Route</h1>

Type: rdf:Class

Comments: A way or course taken from one location to another for the purpose of transporting cargo and or passengers.

Properties: 

Name | Type 
-|-
<span id="FrequencyTypeCode">FrequencyTypeCode</span> | xsd:token
<span id="ItineraryStopTransportEvent">ItineraryStopTransportEvent</span> | [edi3:Event](#Event)
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="DeparturePointText">DeparturePointText</span> | xsd:string
<span id="MapBinaryObject">MapBinaryObject</span> | xsd:base64Binary
<span id="ScheduledSpecifiedPeriod">ScheduledSpecifiedPeriod</span> | [edi3:Period](#Period)
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="StatusStatusCode">StatusStatusCode</span> | xsd:token
<span id="SecurityLevelCode">SecurityLevelCode</span> | xsd:token
<span id="TransportMeansText">TransportMeansText</span> | xsd:string
<span id="FrequencyEffectiveSpecifiedPeriod">FrequencyEffectiveSpecifiedPeriod</span> | [edi3:Period](#Period)


<h1 id="CountrySubDivision">CountrySubDivision</h1>

Type: rdf:Class

Comments: A political or physical area or region within the political boundaries of a country used or referenced for trade purposes.

Properties: 

Name | Type 
-|-
<span id="FunctionTypeLocationFunctionCode">FunctionTypeLocationFunctionCode</span> | xsd:token
<span id="TypeCode">TypeCode</span> | xsd:token
<span id="SuperordinateTradeCountrySubDivision">SuperordinateTradeCountrySubDivision</span> | [edi3:CountrySubDivision](#CountrySubDivision)
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="NameText">NameText</span> | xsd:string
<span id="ActivityAuthorizedTradeParty">ActivityAuthorizedTradeParty</span> | [edi3:Party](#Party)
<span id="HierarchicalLevelCode">HierarchicalLevelCode</span> | xsd:token


<h1 id="GoodsCharacteristic">GoodsCharacteristic</h1>

Type: rdf:Class

Comments: A distinctive feature of a material contained within physical goods.

Properties: 

Name | Type 
-|-
<span id="AbsolutePresenceWeightMeasure">AbsolutePresenceWeightMeasure</span> | xsd:decimal
<span id="TypeCode">TypeCode</span> | xsd:token
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="AbsolutePresenceVolumeMeasure">AbsolutePresenceVolumeMeasure</span> | xsd:decimal


<h1 id="Circle">Circle</h1>

Type: rdf:Class

Comments: A planar surface specified as one completely round flat shape in the mathematical sense.

Properties: 

Name | Type 
-|-
<span id="AssociatedSpecifiedGeographicalObjectCharacteristic">AssociatedSpecifiedGeographicalObjectCharacteristic</span> | [edi3:GeographicalObjectCharacteristic](#GeographicalObjectCharacteristic)
<span id="AssociatedLogisticsLocation">AssociatedLogisticsLocation</span> | [edi3:Location](#Location)
<span id="RadiusMeasure">RadiusMeasure</span> | xsd:decimal


<h1 id="TestSpecificationReport">TestSpecificationReport</h1>

Type: rdf:Class

Comments: A report that specifies a certification test and its attributes.

Properties: 

Name | Type 
-|-
<span id="ResultText">ResultText</span> | xsd:string
<span id="StandardNameText">StandardNameText</span> | xsd:string


<h1 id="Characteristic">Characteristic</h1>

Type: rdf:Class

Comments: A prominent attribute or aspect of a product.

Properties: 

Name | Type 
-|-
<span id="ValueText">ValueText</span> | xsd:string
<span id="TypeCode">TypeCode</span> | xsd:token
<span id="ApplicableProductCharacteristicCondition">ApplicableProductCharacteristicCondition</span> | [edi3:Condition](#Condition)
<span id="MeasurementMethodCode">MeasurementMethodCode</span> | xsd:token
<span id="ValueMeasure">ValueMeasure</span> | xsd:decimal
<span id="ContentTypeCode">ContentTypeCode</span> | xsd:token
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="ValueDateTime">ValueDateTime</span> | xsd:dateTime
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="ValueCode">ValueCode</span> | xsd:token
<span id="ValueSpecifiedBinaryFile">ValueSpecifiedBinaryFile</span> | [edi3:BinaryFile](#BinaryFile)
<span id="ValueIndicator">ValueIndicator</span> | xsd:boolean


<h1 id="Period">Period</h1>

Type: rdf:Class

Comments: <br/>A specified period of time.<br/>A specific period of time such as the length of time between two known date/time points, from a start date onwards, or up to an end date for which something is available.<br/>

Properties: 

Name | Type 
-|-
<span id="OpenIndicator">OpenIndicator</span> | xsd:boolean
<span id="DurationMeasure">DurationMeasure</span> | xsd:decimal
<span id="ContinuousIndicator">ContinuousIndicator</span> | xsd:boolean
<span id="PurposeCode">PurposeCode</span> | xsd:token
<span id="StartDateTime">StartDateTime</span> | xsd:dateTime
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="InclusiveIndicator">InclusiveIndicator</span> | xsd:boolean
<span id="SequenceNumeric">SequenceNumeric</span> | xsd:decimal
<span id="SeasonCode">SeasonCode</span> | xsd:token
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="EndDateTime">EndDateTime</span> | xsd:dateTime
<span id="NameText">NameText</span> | xsd:string
<span id="StartDateFlexibilityCode">StartDateFlexibilityCode</span> | xsd:token


<h1 id="TradeLineItem">TradeLineItem</h1>

Type: rdf:Class

Comments: <br/>A collection of information specific to a subordinate item being used or reported on for trade purposes.<br/>A collection of information specific to an item being used or reported on for supply chain trade purposes.<br/>

Properties: 

Name | Type 
-|-
<span id="AdditionalIdentificationIdentifier">AdditionalIdentificationIdentifier</span> | xsd:token
<span id="SpecifiedGoodsProduction">SpecifiedGoodsProduction</span> | [edi3:Production](#Production)
<span id="DescriptionCode">DescriptionCode</span> | xsd:token
<span id="RequiredApplicableReferencedProduct">RequiredApplicableReferencedProduct</span> | [edi3:Product](#Product)
<span id="TypeExtensionCode">TypeExtensionCode</span> | xsd:token
<span id="SpecifiedLineTradeAgreement">SpecifiedLineTradeAgreement</span> | [edi3:TradeAgreement](#TradeAgreement)
<span id="ComplementaryApplicableReferencedProduct">ComplementaryApplicableReferencedProduct</span> | [edi3:Product](#Product)
<span id="AdditionalApplicableReferencedProduct">AdditionalApplicableReferencedProduct</span> | [edi3:Product](#Product)
<span id="BarcodeIdentificationIdentifier">BarcodeIdentificationIdentifier</span> | xsd:token
<span id="InvoiceAssociatedReferencedDocument">InvoiceAssociatedReferencedDocument</span> | [edi3:Document](#Document)
<span id="PhysicalLogisticsPackage">PhysicalLogisticsPackage</span> | [edi3:Package](#Package)
<span id="ComponentApplicableReferencedProduct">ComponentApplicableReferencedProduct</span> | [edi3:Product](#Product)
<span id="ReferenceReferencedDocument">ReferenceReferencedDocument</span> | [edi3:Document](#Document)
<span id="SpecifiedSubordinateLineTradeDelivery">SpecifiedSubordinateLineTradeDelivery</span> | [edi3:TradeDelivery](#TradeDelivery)
<span id="TypeCode">TypeCode</span> | xsd:token
<span id="SubstitutedReferencedProduct">SubstitutedReferencedProduct</span> | [edi3:Product](#Product)
<span id="AssociatedDocumentLineDocument">AssociatedDocumentLineDocument</span> | [edi3:Document](#Document)
<span id="SpecifiedLineTradeSettlement">SpecifiedLineTradeSettlement</span> | [edi3:TradeSettlement](#TradeSettlement)
<span id="SpecifiedReferencedProduct">SpecifiedReferencedProduct</span> | [edi3:Product](#Product)
<span id="SpecifiedLineTradeDelivery">SpecifiedLineTradeDelivery</span> | [edi3:TradeDelivery](#TradeDelivery)
<span id="PhysicalReferencedLogisticsPackage">PhysicalReferencedLogisticsPackage</span> | [edi3:Package](#Package)
<span id="SubstituteApplicableReferencedProduct">SubstituteApplicableReferencedProduct</span> | [edi3:Product](#Product)
<span id="AccessoryApplicableReferencedProduct">AccessoryApplicableReferencedProduct</span> | [edi3:Product](#Product)
<span id="SpecifiedSubordinateLineTradeAgreement">SpecifiedSubordinateLineTradeAgreement</span> | [edi3:TradeAgreement](#TradeAgreement)
<span id="AssertedDocumentAuthentication">AssertedDocumentAuthentication</span> | [edi3:Authentication](#Authentication)
<span id="SequenceNumeric">SequenceNumeric</span> | xsd:decimal
<span id="RequisitionerSpecifiedTradeProduct">RequisitionerSpecifiedTradeProduct</span> | [edi3:Product](#Product)
<span id="SpecifiedSubordinateLineTradeSettlement">SpecifiedSubordinateLineTradeSettlement</span> | [edi3:TradeSettlement](#TradeSettlement)
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="IncludedSubordinateTradeLineItem">IncludedSubordinateTradeLineItem</span> | [edi3:TradeLineItem](#TradeLineItem)
<span id="ApplicableTradeProduct">ApplicableTradeProduct</span> | [edi3:Product](#Product)
<span id="SpecifiedTradeProduct">SpecifiedTradeProduct</span> | [edi3:Product](#Product)
<span id="AssociatedLogisticsTransportEquipment">AssociatedLogisticsTransportEquipment</span> | [edi3:TransportEquipment](#TransportEquipment)
<span id="IncludedWithinSupplyChainConsignmentItem">IncludedWithinSupplyChainConsignmentItem</span> | [edi3:ConsignmentItem](#ConsignmentItem)
<span id="ReferencedLogisticsPackage">ReferencedLogisticsPackage</span> | [edi3:Package](#Package)


<h1 id="Range">Range</h1>

Type: rdf:Class

Comments: A row, line or series, commonly used to express the difference between lowest and highest values.

Properties: 

Name | Type 
-|-
<span id="StartIdentifier">StartIdentifier</span> | xsd:token
<span id="EndIdentifier">EndIdentifier</span> | xsd:token
<span id="MaximumValueMeasure">MaximumValueMeasure</span> | xsd:decimal
<span id="TotalItemQuantity">TotalItemQuantity</span> | xsd:decimal
<span id="MinimumValueMeasure">MinimumValueMeasure</span> | xsd:decimal


<h1 id="Certification">Certification</h1>

Type: rdf:Class

Comments: The process of certifying that a certain product has passed performance and quality assurance tests, or qualification requirements stipulated in regulations.

Properties: 

Name | Type 
-|-
<span id="ResponsibleAgencyText">ResponsibleAgencyText</span> | xsd:string
<span id="StandardText">StandardText</span> | xsd:string
<span id="AssertionText">AssertionText</span> | xsd:string


<h1 id="TradeSettlement">TradeSettlement</h1>

Type: rdf:Class

Comments: <br/>The information, at a line level, that enables the reconciliation of a financial transaction with the item(s) that the financial transaction is intended to settle, for example a commercial invoice.<br/>The information, at a subordinate line level, that enables the reconciliation of a financial transaction with the item(s) that the financial transaction is intended to settle, for example a commercial invoice.<br/>The information that enables the reconciliation of a payment with the item(s) that the payment is intended to settle, for example a commercial invoice.<br/>The information, at a header level, that enables the reconciliation of a financial transaction, with the item(s) that the financial transaction is intended to settle, such as a commercial invoice.<br/>

Properties: 

Name | Type 
-|-
<span id="InvoiceCurrencyCurrencyCode">InvoiceCurrencyCurrencyCode</span> | xsd:token
<span id="SpecifiedAdvancePayment">SpecifiedAdvancePayment</span> | [edi3:Payment](#Payment)
<span id="AdditionalDescriptionText">AdditionalDescriptionText</span> | xsd:string
<span id="TotalAdjustmentAmount">TotalAdjustmentAmount</span> | xsd:decimal
<span id="ScheduledPaymentDateTime">ScheduledPaymentDateTime</span> | xsd:dateTime
<span id="RequestedFinancingRatePercent">RequestedFinancingRatePercent</span> | xsd:decimal
<span id="SubtotalCalculatedTradeTax">SubtotalCalculatedTradeTax</span> | [edi3:Tax](#Tax)
<span id="PriceApplicableTradeCurrencyExchange">PriceApplicableTradeCurrencyExchange</span> | [edi3:CurrencyExchange](#CurrencyExchange)
<span id="RequestedFinancingAmount">RequestedFinancingAmount</span> | xsd:decimal
<span id="SpecifiedTradeSettlementLineMonetarySummation">SpecifiedTradeSettlementLineMonetarySummation</span> | [edi3:MonetarySummation](#MonetarySummation)
<span id="InvoiceReferencedDocument">InvoiceReferencedDocument</span> | [edi3:Document](#Document)
<span id="ReferencedLineTradeTransaction">ReferencedLineTradeTransaction</span> | [edi3:TradeTransaction](#TradeTransaction)
<span id="NextInvoiceDateTime">NextInvoiceDateTime</span> | xsd:dateTime
<span id="QuotationCurrencyCurrencyCode">QuotationCurrencyCurrencyCode</span> | xsd:token
<span id="SalesSpecifiedTradeAccountingAccount">SalesSpecifiedTradeAccountingAccount</span> | [edi3:AccountingAccount](#AccountingAccount)
<span id="ClosingBookDueDateTime">ClosingBookDueDateTime</span> | xsd:dateTime
<span id="ApplicableTradeTax">ApplicableTradeTax</span> | [edi3:Tax](#Tax)
<span id="AssociatedReferencedDocument">AssociatedReferencedDocument</span> | [edi3:Document](#Document)
<span id="SpecifiedTradeAllowanceCharge">SpecifiedTradeAllowanceCharge</span> | [edi3:AllowanceCharge](#AllowanceCharge)
<span id="CreditorReferenceTypeText">CreditorReferenceTypeText</span> | xsd:string
<span id="PaymentAmount">PaymentAmount</span> | xsd:decimal
<span id="SpecifiedFinancialAdjustment">SpecifiedFinancialAdjustment</span> | [edi3:Adjustment](#Adjustment)
<span id="SpecifiedLogisticsServiceCharge">SpecifiedLogisticsServiceCharge</span> | [edi3:ServiceCharge](#ServiceCharge)
<span id="CreditReasonText">CreditReasonText</span> | xsd:string
<span id="LetterOfCreditReferencedDocument">LetterOfCreditReferencedDocument</span> | [edi3:Document](#Document)
<span id="AssociatedDocumentLineDocument">AssociatedDocumentLineDocument</span> | [edi3:Document](#Document)
<span id="CreditNoteAmount">CreditNoteAmount</span> | xsd:decimal
<span id="PaymentReferenceText">PaymentReferenceText</span> | xsd:string
<span id="SpecifiedTradeSettlementPaymentMonetarySummation">SpecifiedTradeSettlementPaymentMonetarySummation</span> | [edi3:MonetarySummation](#MonetarySummation)
<span id="ProFormaInvoiceReferencedDocument">ProFormaInvoiceReferencedDocument</span> | [edi3:Document](#Document)
<span id="SpecifiedPaymentInstalmentPlan">SpecifiedPaymentInstalmentPlan</span> | [edi3:InstalmentPlan](#InstalmentPlan)
<span id="ReceivableSpecifiedTradeAccountingAccount">ReceivableSpecifiedTradeAccountingAccount</span> | [edi3:AccountingAccount](#AccountingAccount)
<span id="FactoringAgreementReferencedDocument">FactoringAgreementReferencedDocument</span> | [edi3:Document](#Document)
<span id="BillingSpecifiedPeriod">BillingSpecifiedPeriod</span> | [edi3:Period](#Period)
<span id="SpecifiedTradeSettlementHeaderMonetarySummation">SpecifiedTradeSettlementHeaderMonetarySummation</span> | [edi3:MonetarySummation](#MonetarySummation)
<span id="PayerReferenceText">PayerReferenceText</span> | xsd:string
<span id="DebitNoteAmount">DebitNoteAmount</span> | xsd:decimal
<span id="PriceCurrencyCurrencyCode">PriceCurrencyCurrencyCode</span> | xsd:token
<span id="InvoiceeTradeParty">InvoiceeTradeParty</span> | [edi3:Party](#Party)
<span id="PayeeTradeParty">PayeeTradeParty</span> | [edi3:Party](#Party)
<span id="PaymentCurrencyCurrencyCode">PaymentCurrencyCurrencyCode</span> | xsd:token
<span id="PurchaseSpecifiedTradeAccountingAccount">PurchaseSpecifiedTradeAccountingAccount</span> | [edi3:AccountingAccount](#AccountingAccount)
<span id="UltimatePayeeTradeParty">UltimatePayeeTradeParty</span> | [edi3:Party](#Party)
<span id="FactoringListReferencedDocument">FactoringListReferencedDocument</span> | [edi3:Document](#Document)
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="SpecifiedTradeSettlementPaymentMeans">SpecifiedTradeSettlementPaymentMeans</span> | [edi3:PaymentMeans](#PaymentMeans)
<span id="OrderApplicableTradeCurrencyExchange">OrderApplicableTradeCurrencyExchange</span> | [edi3:CurrencyExchange](#CurrencyExchange)
<span id="InvoiceApplicableTradeCurrencyExchange">InvoiceApplicableTradeCurrencyExchange</span> | [edi3:CurrencyExchange](#CurrencyExchange)
<span id="OrderCurrencyCurrencyCode">OrderCurrencyCurrencyCode</span> | xsd:token
<span id="CreditorReferenceIssuerIdentifier">CreditorReferenceIssuerIdentifier</span> | xsd:token
<span id="InvoiceIssuerReferenceText">InvoiceIssuerReferenceText</span> | xsd:string
<span id="PriceCurrencyCode">PriceCurrencyCode</span> | xsd:token
<span id="PayerTradeParty">PayerTradeParty</span> | [edi3:Party](#Party)
<span id="InvoiceDateTime">InvoiceDateTime</span> | xsd:dateTime
<span id="DuePayableAmount">DuePayableAmount</span> | xsd:decimal
<span id="InvoicerTradeParty">InvoicerTradeParty</span> | [edi3:Party](#Party)
<span id="PayableSpecifiedTradeAccountingAccount">PayableSpecifiedTradeAccountingAccount</span> | [edi3:AccountingAccount](#AccountingAccount)
<span id="PaymentApplicableTradeCurrencyExchange">PaymentApplicableTradeCurrencyExchange</span> | [edi3:CurrencyExchange](#CurrencyExchange)
<span id="RelevantTradeParty">RelevantTradeParty</span> | [edi3:Party](#Party)
<span id="AdditionalReferencedDocument">AdditionalReferencedDocument</span> | [edi3:Document](#Document)
<span id="QuotationApplicableTradeCurrencyExchange">QuotationApplicableTradeCurrencyExchange</span> | [edi3:CurrencyExchange](#CurrencyExchange)
<span id="TaxCurrencyCurrencyCode">TaxCurrencyCurrencyCode</span> | xsd:token
<span id="CreditorReferenceIdentifier">CreditorReferenceIdentifier</span> | xsd:token
<span id="SpecifiedTradeSettlementFinancialCard">SpecifiedTradeSettlementFinancialCard</span> | [edi3:FinancialCard](#FinancialCard)
<span id="TotalInvoiceAmount">TotalInvoiceAmount</span> | xsd:decimal
<span id="SpecifiedTradePaymentTerms">SpecifiedTradePaymentTerms</span> | [edi3:PaymentTerms](#PaymentTerms)
<span id="CreditorReferenceTypeCode">CreditorReferenceTypeCode</span> | xsd:token
<span id="DiscountIndicator">DiscountIndicator</span> | xsd:boolean
<span id="CreditReasonCode">CreditReasonCode</span> | xsd:token


<h1 id="Payment">Payment</h1>

Type: rdf:Class

Comments: <br/>A discharge of obligations in respect of funds or securities, transferred through one of several payments, between two or more parties.<br/>The specific discharge obligations in respect of funds or securities transferred between two or more parties as part of a trade settlement.<br/>A prepaid discharge of obligations in respect of funds or securities transferred between two or more parties.<br/>

Properties: 

Name | Type 
-|-
<span id="InstructionIdentifier">InstructionIdentifier</span> | xsd:token
<span id="EndToEndIdentificationIdentifier">EndToEndIdentificationIdentifier</span> | xsd:token
<span id="ClosingBookDueDateTime">ClosingBookDueDateTime</span> | xsd:dateTime
<span id="SpecifiedFinancingRequestResultDocument">SpecifiedFinancingRequestResultDocument</span> | [edi3:Document](#Document)
<span id="SpecifiedPaymentTradeSettlement">SpecifiedPaymentTradeSettlement</span> | [edi3:TradeSettlement](#TradeSettlement)
<span id="FormattedReceivedFormattedDateTime">FormattedReceivedFormattedDateTime</span> | xsd:dateTime
<span id="IncludedTradeTax">IncludedTradeTax</span> | [edi3:Tax](#Tax)
<span id="SequenceIdentifier">SequenceIdentifier</span> | xsd:token
<span id="PaidAmount">PaidAmount</span> | xsd:decimal
<span id="RequestedExecutionDateTime">RequestedExecutionDateTime</span> | xsd:dateTime


<h1 id="Price">Price</h1>

Type: rdf:Class

Comments: <br/>A sum of money for which something is or may be bought or sold for trade purposes.<br/>A reference to a sum of money for which something is or may be bought or sold.<br/>Information related to a calculated price.<br/>

Properties: 

Name | Type 
-|-
<span id="MinimumQuantity">MinimumQuantity</span> | xsd:decimal
<span id="OrderUnitConversionFactorNumeric">OrderUnitConversionFactorNumeric</span> | xsd:decimal
<span id="NetPriceIndicator">NetPriceIndicator</span> | xsd:boolean
<span id="MaximumQuantity">MaximumQuantity</span> | xsd:decimal
<span id="AppliedTradeAllowanceCharge">AppliedTradeAllowanceCharge</span> | [edi3:AllowanceCharge](#AllowanceCharge)
<span id="AssociatedReferencedDocument">AssociatedReferencedDocument</span> | [edi3:Document](#Document)
<span id="TypePriceTypeCode">TypePriceTypeCode</span> | xsd:token
<span id="ValiditySpecifiedPeriod">ValiditySpecifiedPeriod</span> | [edi3:Period](#Period)
<span id="TypeCode">TypeCode</span> | xsd:token
<span id="TypeText">TypeText</span> | xsd:string
<span id="UnitAmount">UnitAmount</span> | xsd:decimal
<span id="ChangeReasonText">ChangeReasonText</span> | xsd:string
<span id="ComparisonMethodCode">ComparisonMethodCode</span> | xsd:token
<span id="IncludedTradeTax">IncludedTradeTax</span> | [edi3:Tax](#Tax)
<span id="TradeComparisonReferencePrice">TradeComparisonReferencePrice</span> | [edi3:Price](#Price)
<span id="RelatedAppliedAllowanceCharge">RelatedAppliedAllowanceCharge</span> | [edi3:AllowanceCharge](#AllowanceCharge)
<span id="ChargeAmount">ChargeAmount</span> | xsd:decimal
<span id="DeliveryTradeLocation">DeliveryTradeLocation</span> | [edi3:Location](#Location)


<h1 id="SupplyPlan">SupplyPlan</h1>

Type: rdf:Class

Comments: Specification of the delivery time and quantity bucket in a supply chain demand forecast or delivery schedule.

Properties: 

Name | Type 
-|-
<span id="DeliveryNoteReferencedDocument">DeliveryNoteReferencedDocument</span> | [edi3:Document](#Document)
<span id="ActualQuantity">ActualQuantity</span> | xsd:decimal
<span id="CommitmentLevelCode">CommitmentLevelCode</span> | xsd:token
<span id="SynchronizationDateTime">SynchronizationDateTime</span> | xsd:dateTime
<span id="MinusToleranceQuantity">MinusToleranceQuantity</span> | xsd:decimal
<span id="ShipToTradeParty">ShipToTradeParty</span> | [edi3:Party](#Party)
<span id="ApplicableSpecifiedPeriod">ApplicableSpecifiedPeriod</span> | [edi3:Period](#Period)
<span id="PlannedQuantity">PlannedQuantity</span> | xsd:decimal
<span id="DeliverySupplyChainEvent">DeliverySupplyChainEvent</span> | [edi3:Event](#Event)
<span id="ContractReferencedDocument">ContractReferencedDocument</span> | [edi3:Document](#Document)
<span id="ScheduledDeliverySupplyChainEvent">ScheduledDeliverySupplyChainEvent</span> | [edi3:Event](#Event)
<span id="SpecifiedLogisticsLocation">SpecifiedLogisticsLocation</span> | [edi3:Location](#Location)
<span id="PlusToleranceQuantity">PlusToleranceQuantity</span> | xsd:decimal
<span id="ToleranceQuantity">ToleranceQuantity</span> | xsd:decimal
<span id="ConfirmedDeliverySupplyChainEvent">ConfirmedDeliverySupplyChainEvent</span> | [edi3:Event](#Event)


<h1 id="Observation">Observation</h1>

Type: rdf:Class

Comments: A specified act or instance of viewing or noting a fact or occurrence for some scientific or other special purpose.

Properties: 

Name | Type 
-|-
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="ApplicableNote">ApplicableNote</span> | [edi3:Note](#Note)


<h1 id="Packaging">Packaging</h1>

Type: rdf:Class

Comments: Any material with which supply chain goods are packaged, such as a box or bubble wrap.

Properties: 

Name | Type 
-|-
<span id="MaximumLinearSpatialDimension">MaximumLinearSpatialDimension</span> | [edi3:Dimension](#Dimension)
<span id="TypePackageTypeCode">TypePackageTypeCode</span> | xsd:token
<span id="ContentLayerQuantity">ContentLayerQuantity</span> | xsd:decimal
<span id="ApplicableDisposalInstructions">ApplicableDisposalInstructions</span> | [edi3:Instructions](#Instructions)
<span id="AdditionalInstructionIndicator">AdditionalInstructionIndicator</span> | xsd:boolean
<span id="TypeText">TypeText</span> | xsd:string
<span id="MaximumStackabilityQuantity">MaximumStackabilityQuantity</span> | xsd:decimal
<span id="TotalUnitQuantity">TotalUnitQuantity</span> | xsd:decimal
<span id="LinearSpatialDimension">LinearSpatialDimension</span> | [edi3:Dimension](#Dimension)
<span id="ReturnableIndicator">ReturnableIndicator</span> | xsd:boolean
<span id="WeightMeasure">WeightMeasure</span> | xsd:decimal
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="ConditionCode">ConditionCode</span> | xsd:token
<span id="AdditionalInstructionCode">AdditionalInstructionCode</span> | xsd:token
<span id="MinimumLinearSpatialDimension">MinimumLinearSpatialDimension</span> | [edi3:Dimension](#Dimension)
<span id="LayerTotalUnitQuantity">LayerTotalUnitQuantity</span> | xsd:decimal
<span id="DisposalMethodCode">DisposalMethodCode</span> | xsd:token
<span id="MaximumStackabilityWeightMeasure">MaximumStackabilityWeightMeasure</span> | xsd:decimal
<span id="ApplicableMaterialGoodsCharacteristic">ApplicableMaterialGoodsCharacteristic</span> | [edi3:GoodsCharacteristic](#GoodsCharacteristic)
<span id="CustomerFacingTotalUnitQuantity">CustomerFacingTotalUnitQuantity</span> | xsd:decimal
<span id="SpecifiedPackagingMarking">SpecifiedPackagingMarking</span> | [edi3:Marking](#Marking)
<span id="InstructionCode">InstructionCode</span> | xsd:token


<h1 id="Sensor">Sensor</h1>

Type: rdf:Class

Comments: An object which can detect and measure physical properties and which can record, indicate and transmit such measurements.

Properties: 

Name | Type 
-|-
<span id="ValueMeasure">ValueMeasure</span> | xsd:decimal
<span id="ManufacturerTradeParty">ManufacturerTradeParty</span> | [edi3:Party](#Party)
<span id="PositionCode">PositionCode</span> | xsd:token
<span id="DefinedControlSettingParameter">DefinedControlSettingParameter</span> | [edi3:Parameter](#Parameter)
<span id="DefinedOperationalParameter">DefinedOperationalParameter</span> | [edi3:Parameter](#Parameter)
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="OwnerTradeParty">OwnerTradeParty</span> | [edi3:Party](#Party)
<span id="GrantedProductCertificate">GrantedProductCertificate</span> | [edi3:Certificate](#Certificate)
<span id="ActualReportedCalibratedMeasurement">ActualReportedCalibratedMeasurement</span> | [edi3:Measurement](#Measurement)
<span id="RemainingBatteryChargePercent">RemainingBatteryChargePercent</span> | xsd:decimal
<span id="ScheduledReportedCalibratedMeasurement">ScheduledReportedCalibratedMeasurement</span> | [edi3:Measurement](#Measurement)
<span id="PrecisionCalibratedMeasurement">PrecisionCalibratedMeasurement</span> | [edi3:Measurement](#Measurement)


<h1 id="Certificate">Certificate</h1>

Type: rdf:Class

Comments: A collection of data for a piece of written, printed or electronic matter that provides information or evidence about the product.

Properties: 

Name | Type 
-|-
<span id="TypeCode">TypeCode</span> | xsd:token
<span id="ActualEffectiveDateTime">ActualEffectiveDateTime</span> | xsd:dateTime
<span id="PurposeCode">PurposeCode</span> | xsd:token
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="IssuingPartyIdentifier">IssuingPartyIdentifier</span> | xsd:token
<span id="RequestedEffectiveDateTime">RequestedEffectiveDateTime</span> | xsd:dateTime
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="ApplicableObjectCode">ApplicableObjectCode</span> | xsd:token
<span id="IssueReasonCode">IssueReasonCode</span> | xsd:token
<span id="IssueDateTime">IssueDateTime</span> | xsd:dateTime


<h1 id="IOTDevice">IOTDevice</h1>

Type: rdf:Class

Comments: An IOT (Internet of Things) piece of mechanical or electronic equipment which can collect, report and autonomously transmit digital data.

Properties: 

Name | Type 
-|-
<span id="ProviderTradeParty">ProviderTradeParty</span> | [edi3:Party](#Party)
<span id="LatestReceivedSignalDateTime">LatestReceivedSignalDateTime</span> | xsd:dateTime
<span id="TypeCode">TypeCode</span> | xsd:token
<span id="LatestReceivedGeographicalCoordinate">LatestReceivedGeographicalCoordinate</span> | [edi3:GeographicalCoordinate](#GeographicalCoordinate)
<span id="RelatedCommunicationEvent">RelatedCommunicationEvent</span> | [edi3:Event](#Event)
<span id="ManufacturerTradeParty">ManufacturerTradeParty</span> | [edi3:Party](#Party)
<span id="PositionCode">PositionCode</span> | xsd:token
<span id="PowerSourceTypeCode">PowerSourceTypeCode</span> | xsd:token
<span id="ReportedTransportEvent">ReportedTransportEvent</span> | [edi3:Event](#Event)
<span id="InterfaceOEMEquipment">InterfaceOEMEquipment</span> | [edi3:Equipment](#Equipment)
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="OwnerTradeParty">OwnerTradeParty</span> | [edi3:Party](#Party)
<span id="OperatorTradeParty">OperatorTradeParty</span> | [edi3:Party](#Party)
<span id="GrantedProductCertificate">GrantedProductCertificate</span> | [edi3:Certificate](#Certificate)
<span id="EmbeddedMonitoringSensor">EmbeddedMonitoringSensor</span> | [edi3:Sensor](#Sensor)
<span id="AttachedAssetIdentificationIdentifier">AttachedAssetIdentificationIdentifier</span> | xsd:token
<span id="ReportingSensorCommunicationPairing">ReportingSensorCommunicationPairing</span> | [edi3:Pairing](#Pairing)
<span id="RemainingBatteryChargePercent">RemainingBatteryChargePercent</span> | xsd:decimal
<span id="OperationalStatusCode">OperationalStatusCode</span> | xsd:token
<span id="RemoteMonitoringSensor">RemoteMonitoringSensor</span> | [edi3:Sensor](#Sensor)


<h1 id="Measurement">Measurement</h1>

Type: rdf:Class

Comments: <br/>A measurement established by a device which is tested to a calibration standard of known accuracy.<br/>An amount, size, or extent as established by measuring.<br/>

Properties: 

Name | Type 
-|-
<span id="ToleranceMeasure">ToleranceMeasure</span> | xsd:decimal
<span id="TypeCode">TypeCode</span> | xsd:token
<span id="ActualMeasure">ActualMeasure</span> | xsd:decimal
<span id="MethodText">MethodText</span> | xsd:string
<span id="ValueMeasure">ValueMeasure</span> | xsd:decimal
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="ValueCode">ValueCode</span> | xsd:token
<span id="VersionIdentifier">VersionIdentifier</span> | xsd:token
<span id="QuantificationTypeCode">QuantificationTypeCode</span> | xsd:token
<span id="TolerancePercent">TolerancePercent</span> | xsd:decimal
<span id="ConditionMeasure">ConditionMeasure</span> | xsd:decimal


<h1 id="Temperature">Temperature</h1>

Type: rdf:Class

Comments: <br/>Temperature settings instructed for storage or movement of goods.<br/>A specified temperature value or range of values.<br/>Temperature settings for a transport movement, such as a required storage temperature range.<br/>

Properties: 

Name | Type 
-|-
<span id="InformationTemperatureSettingInstructions">InformationTemperatureSettingInstructions</span> | [edi3:Instructions](#Instructions)
<span id="TypeTemperatureTypeCode">TypeTemperatureTypeCode</span> | xsd:token
<span id="ValueTemperatureUnitMeasure">ValueTemperatureUnitMeasure</span> | xsd:decimal
<span id="MaximumValueMeasure">MaximumValueMeasure</span> | xsd:decimal
<span id="MaximumValueTemperatureUnitMeasure">MaximumValueTemperatureUnitMeasure</span> | xsd:decimal
<span id="MinimumValueMeasure">MinimumValueMeasure</span> | xsd:decimal


<h1 id="Emission">Emission</h1>

Type: rdf:Class

Comments: A calculation of the pollution (including noise, heat, and radiation etc.) discharged into the environment by a residential, commercial, or industrial facility or by a means of transport, such as a vessel, aircraft or truck.

Properties: 

Name | Type 
-|-
<span id="PollutionMeasure">PollutionMeasure</span> | xsd:decimal
<span id="WeightWeightUnitMeasure">WeightWeightUnitMeasure</span> | xsd:decimal
<span id="AffectedDistanceLinearUnitMeasure">AffectedDistanceLinearUnitMeasure</span> | xsd:decimal


<h1 id="Standard">Standard</h1>

Type: rdf:Class

Comments: A referenced norm or requirement that establishes uniform criteria, methods, processes and practices, such as in engineering or technical areas.

Properties: 

Name | Type 
-|-
<span id="URIIdentifier">URIIdentifier</span> | xsd:token
<span id="PartIdentificationIdentifier">PartIdentificationIdentifier</span> | xsd:token
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="VersionIdentifier">VersionIdentifier</span> | xsd:token
<span id="ElementVersionIdentifier">ElementVersionIdentifier</span> | xsd:token


<h1 id="PaymentTerms">PaymentTerms</h1>

Type: rdf:Class

Comments: Terms and conditions by which payment has been or will be made for trade purposes.

Properties: 

Name | Type 
-|-
<span id="DueFormattedDateTime">DueFormattedDateTime</span> | xsd:dateTime
<span id="PartialPaymentAmount">PartialPaymentAmount</span> | xsd:decimal
<span id="DirectDebitMandateIdentificationIdentifier">DirectDebitMandateIdentificationIdentifier</span> | xsd:token
<span id="PartialPaymentPercent">PartialPaymentPercent</span> | xsd:decimal
<span id="FromEventPaymentTermsEventTimeReferenceCode">FromEventPaymentTermsEventTimeReferenceCode</span> | xsd:token
<span id="ApplicableTradePaymentDiscountTerms">ApplicableTradePaymentDiscountTerms</span> | [edi3:PaymentDiscountTerms](#PaymentDiscountTerms)
<span id="PaymentMeansIdentificationIdentifier">PaymentMeansIdentificationIdentifier</span> | xsd:token
<span id="TypePaymentTermsTypeCode">TypePaymentTermsTypeCode</span> | xsd:token
<span id="SettlementPeriodMeasure">SettlementPeriodMeasure</span> | xsd:decimal
<span id="PayeeTradeParty">PayeeTradeParty</span> | [edi3:Party](#Party)
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="InstructionTypeCode">InstructionTypeCode</span> | xsd:token
<span id="IdentificationPaymentTermsIdentifier">IdentificationPaymentTermsIdentifier</span> | xsd:token
<span id="DueDateDateTime">DueDateDateTime</span> | xsd:dateTime
<span id="InstructionCode">InstructionCode</span> | xsd:token


<h1 id="GeographicalFeature">GeographicalFeature</h1>

Type: rdf:Class

Comments: Representation of real world phenomenon associated with a location relative to the Earth, such as cities, buildings, roads, rivers, forests and lakes.

Properties: 

Name | Type 
-|-
<span id="IncludedSpecifiedGeographicalPoint">IncludedSpecifiedGeographicalPoint</span> | [edi3:GeographicalPoint](#GeographicalPoint)
<span id="IncludedSpecifiedCircle">IncludedSpecifiedCircle</span> | [edi3:Circle](#Circle)
<span id="IncludedSpecifiedGeographicalMultiCurve">IncludedSpecifiedGeographicalMultiCurve</span> | [edi3:GeographicalMultiCurve](#GeographicalMultiCurve)
<span id="CollectionIndicator">CollectionIndicator</span> | xsd:boolean
<span id="IncludedSpecifiedPolygon">IncludedSpecifiedPolygon</span> | [edi3:Polygon](#Polygon)
<span id="IncludedSpecifiedGeographicalGrid">IncludedSpecifiedGeographicalGrid</span> | [edi3:GeographicalGrid](#GeographicalGrid)
<span id="IncludedSpecifiedGeographicalMultiSurface">IncludedSpecifiedGeographicalMultiSurface</span> | [edi3:GeographicalMultiSurface](#GeographicalMultiSurface)
<span id="UsedCSEngineeringCoordinateReferenceSystem">UsedCSEngineeringCoordinateReferenceSystem</span> | [edi3:CoordinateReferenceSystem](#CoordinateReferenceSystem)
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="NameText">NameText</span> | xsd:string
<span id="UsedGeographicalCoordinateSourceSystem">UsedGeographicalCoordinateSourceSystem</span> | [edi3:CoordinateSourceSystem](#CoordinateSourceSystem)
<span id="IncludedSpecifiedGeographicalMultiPoint">IncludedSpecifiedGeographicalMultiPoint</span> | [edi3:GeographicalMultiPoint](#GeographicalMultiPoint)
<span id="CoordinateReferenceSystemIdentifier">CoordinateReferenceSystemIdentifier</span> | xsd:token
<span id="IncludedSpecifiedGeographicalLine">IncludedSpecifiedGeographicalLine</span> | [edi3:GeographicalLine](#GeographicalLine)


<h1 id="Segment">Segment</h1>

Type: rdf:Class

Comments: The parts into which a segment is or may be divided.

Properties: 

Name | Type 
-|-
<span id="TypeCode">TypeCode</span> | xsd:token
<span id="ImageBinaryObject">ImageBinaryObject</span> | xsd:base64Binary
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token


<h1 id="ConsignmentItem">ConsignmentItem</h1>

Type: rdf:Class

Comments: <br/>A reference to an item within a supply chain consignment of goods separately identified for transport and customs purposes.<br/>An item within a supply chain consignment of goods separately identified for transport and customs purposes.<br/>

Properties: 

Name | Type 
-|-
<span id="NetWeightWeightUnitMeasure">NetWeightWeightUnitMeasure</span> | xsd:decimal
<span id="DeliveryTransportEvent">DeliveryTransportEvent</span> | [edi3:Event](#Event)
<span id="OriginTradeGeopoliticalRegion">OriginTradeGeopoliticalRegion</span> | [edi3:GeopoliticalRegion](#GeopoliticalRegion)
<span id="ApplicableLogisticsServiceCharge">ApplicableLogisticsServiceCharge</span> | [edi3:ServiceCharge](#ServiceCharge)
<span id="QuarantineQuarantineInstructions">QuarantineQuarantineInstructions</span> | [edi3:Instructions](#Instructions)
<span id="DamageRemarksText">DamageRemarksText</span> | xsd:string
<span id="InformationText">InformationText</span> | xsd:string
<span id="ApplicableTransportDangerousGoods">ApplicableTransportDangerousGoods</span> | [edi3:DangerousGoods](#DangerousGoods)
<span id="TariffQuantity">TariffQuantity</span> | xsd:decimal
<span id="GlobalIdentificationIdentifier">GlobalIdentificationIdentifier</span> | xsd:token
<span id="SecondTypeExtensionCode">SecondTypeExtensionCode</span> | xsd:token
<span id="AssociatedReferencedDocument">AssociatedReferencedDocument</span> | [edi3:Document](#Document)
<span id="GrossWeightWeightUnitMeasure">GrossWeightWeightUnitMeasure</span> | xsd:decimal
<span id="ExportTradeCountry">ExportTradeCountry</span> | [edi3:Country](#Country)
<span id="DeclaredValueForCustomsAmount">DeclaredValueForCustomsAmount</span> | xsd:decimal
<span id="ImportTypeCode">ImportTypeCode</span> | xsd:token
<span id="ReportedLogisticsStatus">ReportedLogisticsStatus</span> | [edi3:Status](#Status)
<span id="LoadingLengthLinearUnitMeasure">LoadingLengthLinearUnitMeasure</span> | xsd:decimal
<span id="LinearSpatialDimension">LinearSpatialDimension</span> | [edi3:Dimension](#Dimension)
<span id="HandlingHandlingInstructions">HandlingHandlingInstructions</span> | [edi3:Instructions](#Instructions)
<span id="PreviousAdministrativeReferencedDocument">PreviousAdministrativeReferencedDocument</span> | [edi3:Document](#Document)
<span id="SpecialInstructionsText">SpecialInstructionsText</span> | xsd:string
<span id="TotalChargeAmount">TotalChargeAmount</span> | xsd:decimal
<span id="NationalTypeExtensionCode">NationalTypeExtensionCode</span> | xsd:token
<span id="TypeExtensionGoodsTypeExtensionCode">TypeExtensionGoodsTypeExtensionCode</span> | xsd:token
<span id="PickUpTransportEvent">PickUpTransportEvent</span> | [edi3:Event](#Event)
<span id="InvoiceAmount">InvoiceAmount</span> | xsd:decimal
<span id="FirstTypeExtensionCode">FirstTypeExtensionCode</span> | xsd:token
<span id="TransportLogisticsPackage">TransportLogisticsPackage</span> | [edi3:Package](#Package)
<span id="InsuranceValueAmount">InsuranceValueAmount</span> | xsd:decimal
<span id="AssociatedReferencedLogisticsTransportEquipment">AssociatedReferencedLogisticsTransportEquipment</span> | [edi3:TransportEquipment](#TransportEquipment)
<span id="ManufacturerTradeParty">ManufacturerTradeParty</span> | [edi3:Party](#Party)
<span id="FOBAmount">FOBAmount</span> | xsd:decimal
<span id="TypeGoodsTypeCode">TypeGoodsTypeCode</span> | xsd:token
<span id="BorderClearanceTransportInstructions">BorderClearanceTransportInstructions</span> | [edi3:Instructions](#Instructions)
<span id="PackageQuantity">PackageQuantity</span> | xsd:decimal
<span id="SequenceNumeric">SequenceNumeric</span> | xsd:decimal
<span id="PackageTypeText">PackageTypeText</span> | xsd:string
<span id="IncludedSupplyChainTradeLineItem">IncludedSupplyChainTradeLineItem</span> | [edi3:TradeLineItem](#TradeLineItem)
<span id="ApplicableLogisticsTransportMeans">ApplicableLogisticsTransportMeans</span> | [edi3:TransportMeans](#TransportMeans)
<span id="TradeLineItemQuantity">TradeLineItemQuantity</span> | xsd:decimal
<span id="DeliveryInstructionsText">DeliveryInstructionsText</span> | xsd:string
<span id="CargoToleranceInformationText">CargoToleranceInformationText</span> | xsd:string
<span id="NatureIdentificationTransportCargo">NatureIdentificationTransportCargo</span> | [edi3:Cargo](#Cargo)
<span id="ExportTypeCode">ExportTypeCode</span> | xsd:token
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="TotalExportExitToImportEntryChargeAmount">TotalExportExitToImportEntryChargeAmount</span> | xsd:decimal
<span id="DeclaredForCustomsLogisticsLocation">DeclaredForCustomsLogisticsLocation</span> | [edi3:Location](#Location)
<span id="GrossVolumeVolumeUnitMeasure">GrossVolumeVolumeUnitMeasure</span> | xsd:decimal
<span id="DestinationTradeCountry">DestinationTradeCountry</span> | [edi3:Country](#Country)
<span id="OriginTradeCountry">OriginTradeCountry</span> | [edi3:Country](#Country)
<span id="ApplicableCrossBorderRegulatoryProcedure">ApplicableCrossBorderRegulatoryProcedure</span> | [edi3:RegulatoryProcedure](#RegulatoryProcedure)
<span id="DeliveryTradeParty">DeliveryTradeParty</span> | [edi3:Party](#Party)
<span id="ChargeableWeightWeightUnitMeasure">ChargeableWeightWeightUnitMeasure</span> | xsd:decimal
<span id="TransportTransportSettingTemperature">TransportTransportSettingTemperature</span> | [edi3:Temperature](#Temperature)
<span id="ImportationTradeCountry">ImportationTradeCountry</span> | [edi3:Country](#Country)
<span id="PhysicalLogisticsShippingMarks">PhysicalLogisticsShippingMarks</span> | [edi3:ShippingMarks](#ShippingMarks)
<span id="ExaminationTransportEvent">ExaminationTransportEvent</span> | [edi3:Event](#Event)
<span id="ExportTradeGeopoliticalRegion">ExportTradeGeopoliticalRegion</span> | [edi3:GeopoliticalRegion](#GeopoliticalRegion)
<span id="DespatchTradeParty">DespatchTradeParty</span> | [edi3:Party](#Party)
<span id="DeclaredValueForStatisticsAmount">DeclaredValueForStatisticsAmount</span> | xsd:decimal
<span id="DeclaredValueForCarriageAmount">DeclaredValueForCarriageAmount</span> | xsd:decimal
<span id="TransitTradeCountry">TransitTradeCountry</span> | [edi3:Country](#Country)
<span id="TransportContractReferencedDocument">TransportContractReferencedDocument</span> | [edi3:Document](#Document)
<span id="ApplicableNote">ApplicableNote</span> | [edi3:Note](#Note)
<span id="VanningTransportEvent">VanningTransportEvent</span> | [edi3:Event](#Event)


<h1 id="ServiceCharge">ServiceCharge</h1>

Type: rdf:Class

Comments: A charge made for a logistics related service.

Properties: 

Name | Type 
-|-
<span id="CalculationBasisText">CalculationBasisText</span> | xsd:string
<span id="ChargeCategoryCode">ChargeCategoryCode</span> | xsd:token
<span id="CalculationBasisLogisticsChargeCalculationBasisCode">CalculationBasisLogisticsChargeCalculationBasisCode</span> | xsd:token
<span id="IdentificationFreightChargeTypeIdentifier">IdentificationFreightChargeTypeIdentifier</span> | xsd:token
<span id="AllowanceChargeText">AllowanceChargeText</span> | xsd:string
<span id="PaymentPlaceLogisticsLocation">PaymentPlaceLogisticsLocation</span> | [edi3:Location](#Location)
<span id="TariffClassFreightChargeTariffClassCode">TariffClassFreightChargeTariffClassCode</span> | xsd:token
<span id="PaymentArrangementTransportServicePaymentArrangementCode">PaymentArrangementTransportServicePaymentArrangementCode</span> | xsd:token
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="SpecifiedTradeSettlementPaymentMeans">SpecifiedTradeSettlementPaymentMeans</span> | [edi3:PaymentMeans](#PaymentMeans)
<span id="AppliedFromLogisticsLocation">AppliedFromLogisticsLocation</span> | [edi3:Location](#Location)
<span id="PayingPartyRoleChargePayingPartyRoleCode">PayingPartyRoleChargePayingPartyRoleCode</span> | xsd:token
<span id="DisbursementAmount">DisbursementAmount</span> | xsd:decimal
<span id="ServiceCategoryCode">ServiceCategoryCode</span> | xsd:token
<span id="AppliedToLogisticsLocation">AppliedToLogisticsLocation</span> | [edi3:Location](#Location)
<span id="AppliedTradeTax">AppliedTradeTax</span> | [edi3:Tax](#Tax)
<span id="CategoryTransportServiceCategoryCode">CategoryTransportServiceCategoryCode</span> | xsd:token
<span id="FreightInvoiceTypeCode">FreightInvoiceTypeCode</span> | xsd:token
<span id="TransportPaymentMethodCode">TransportPaymentMethodCode</span> | xsd:token


<h1 id="SecurityTag">SecurityTag</h1>

Type: rdf:Class

Comments: A product tag device to provide protection from a peril such as theft.

Properties: 

Name | Type 
-|-
<span id="LocationCode">LocationCode</span> | xsd:token


<h1 id="Declaration">Declaration</h1>

Type: rdf:Class

Comments: A collection of data for a piece of written, printed or electronic matter that is exchanged between two parties as a formal declaration.

Properties: 

Name | Type 
-|-
<span id="IssueFormattedDateTime">IssueFormattedDateTime</span> | xsd:dateTime
<span id="ApplicableCrossBorderCustomsValuation">ApplicableCrossBorderCustomsValuation</span> | [edi3:CustomsValuation](#CustomsValuation)
<span id="DeclarantTradeParty">DeclarantTradeParty</span> | [edi3:Party](#Party)
<span id="CustomsValueSpecifiedAmount">CustomsValueSpecifiedAmount</span> | xsd:decimal
<span id="StatisticalValueSpecifiedAmount">StatisticalValueSpecifiedAmount</span> | xsd:decimal
<span id="JurisdictionEntryFormattedDateTime">JurisdictionEntryFormattedDateTime</span> | xsd:dateTime
<span id="AssociatedReferencedDocument">AssociatedReferencedDocument</span> | [edi3:Document](#Document)
<span id="GrossWeightSpecifiedWeightUnitMeasure">GrossWeightSpecifiedWeightUnitMeasure</span> | xsd:decimal
<span id="TotalInvoiceSpecifiedAmount">TotalInvoiceSpecifiedAmount</span> | xsd:decimal
<span id="PrincipalAssociatedTradeParty">PrincipalAssociatedTradeParty</span> | [edi3:Party](#Party)
<span id="ProcedureCode">ProcedureCode</span> | xsd:token
<span id="DeclarantAgentTradeParty">DeclarantAgentTradeParty</span> | [edi3:Party](#Party)
<span id="TypeDocumentCode">TypeDocumentCode</span> | xsd:token
<span id="TotalPackageSpecifiedQuantity">TotalPackageSpecifiedQuantity</span> | xsd:decimal
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="VersionIdentifier">VersionIdentifier</span> | xsd:token
<span id="PreviousReferencedDocument">PreviousReferencedDocument</span> | [edi3:Document](#Document)
<span id="SpecificCircumstanceCode">SpecificCircumstanceCode</span> | xsd:token
<span id="CurrencyExchangeRate">CurrencyExchangeRate</span> | xsd:decimal
<span id="SubmissionLogisticsLocation">SubmissionLogisticsLocation</span> | [edi3:Location](#Location)


<h1 id="DangerousGoods">DangerousGoods</h1>

Type: rdf:Class

Comments: Goods which may contain a substance which poses risks to people and/or the environment during transportation which is regulated by dangerous goods regulations.

Properties: 

Name | Type 
-|-
<span id="NetWeightWeightUnitMeasure">NetWeightWeightUnitMeasure</span> | xsd:decimal
<span id="HazardTypeCode">HazardTypeCode</span> | xsd:token
<span id="UNDGIdentificationCode">UNDGIdentificationCode</span> | xsd:token
<span id="ReportableQuantity">ReportableQuantity</span> | xsd:decimal
<span id="HazardClassificationIdentifier">HazardClassificationIdentifier</span> | xsd:token
<span id="TransportExpertTradeContact">TransportExpertTradeContact</span> | [edi3:Contact](#Contact)
<span id="InformationText">InformationText</span> | xsd:string
<span id="ExplosiveCompatibilityGroupCode">ExplosiveCompatibilityGroupCode</span> | xsd:token
<span id="QValueNumeric">QValueNumeric</span> | xsd:decimal
<span id="SpecifiedLogisticsPackage">SpecifiedLogisticsPackage</span> | [edi3:Package](#Package)
<span id="LowerPartOrangeHazardPlacardIdentifier">LowerPartOrangeHazardPlacardIdentifier</span> | xsd:token
<span id="PackingInstructionTypeCode">PackingInstructionTypeCode</span> | xsd:token
<span id="TechnicalNameText">TechnicalNameText</span> | xsd:string
<span id="ProperShippingNameText">ProperShippingNameText</span> | xsd:string
<span id="GrossWeightWeightUnitMeasure">GrossWeightWeightUnitMeasure</span> | xsd:decimal
<span id="FlashpointTemperatureMeasurement">FlashpointTemperatureMeasurement</span> | [edi3:Measurement](#Measurement)
<span id="AllPackedInOneInformationText">AllPackedInOneInformationText</span> | xsd:string
<span id="HazardCategoryCode">HazardCategoryCode</span> | xsd:token
<span id="HandlingHandlingInstructions">HandlingHandlingInstructions</span> | [edi3:Instructions](#Instructions)
<span id="RadioactiveRadioactiveMaterial">RadioactiveRadioactiveMaterial</span> | [edi3:Material](#Material)
<span id="ComplianceDeclarationInformationText">ComplianceDeclarationInformationText</span> | xsd:string
<span id="EmergencyTradeContact">EmergencyTradeContact</span> | [edi3:Contact](#Contact)
<span id="PollutantLevelCode">PollutantLevelCode</span> | xsd:token
<span id="SupplementaryInformationText">SupplementaryInformationText</span> | xsd:string
<span id="AssociatedReferencedLogisticsTransportEquipment">AssociatedReferencedLogisticsTransportEquipment</span> | [edi3:TransportEquipment](#TransportEquipment)
<span id="EmergencyTemperatureMeasurement">EmergencyTemperatureMeasurement</span> | [edi3:Measurement](#Measurement)
<span id="PackagingDangerLevelDangerousGoodsPackagingLevelCode">PackagingDangerLevelDangerousGoodsPackagingLevelCode</span> | xsd:token
<span id="TREMIdentifier">TREMIdentifier</span> | xsd:token
<span id="RegulationDangerousGoodsRegulationCode">RegulationDangerousGoodsRegulationCode</span> | xsd:token
<span id="MFAGIdentifier">MFAGIdentifier</span> | xsd:token
<span id="AuthorizationInformationText">AuthorizationInformationText</span> | xsd:string
<span id="IMDGSegregationGroupCode">IMDGSegregationGroupCode</span> | xsd:token
<span id="ExplosiveCargoNetWeightWeightUnitMeasure">ExplosiveCargoNetWeightWeightUnitMeasure</span> | xsd:decimal
<span id="PackageTypePackageTypeCode">PackageTypePackageTypeCode</span> | xsd:token
<span id="ControlTemperatureMeasurement">ControlTemperatureMeasurement</span> | [edi3:Measurement](#Measurement)
<span id="GrossVolumeVolumeUnitMeasure">GrossVolumeVolumeUnitMeasure</span> | xsd:decimal
<span id="TunnelRestrictionCode">TunnelRestrictionCode</span> | xsd:token
<span id="OverpackInformationText">OverpackInformationText</span> | xsd:string
<span id="AdditionalHazardClassificationIdentifier">AdditionalHazardClassificationIdentifier</span> | xsd:token
<span id="EMSIdentifier">EMSIdentifier</span> | xsd:token
<span id="ShipperDeclarationInformationText">ShipperDeclarationInformationText</span> | xsd:string
<span id="RegulatoryAuthorityNameText">RegulatoryAuthorityNameText</span> | xsd:string
<span id="UpperPartOrangeHazardPlacardIdentifier">UpperPartOrangeHazardPlacardIdentifier</span> | xsd:token
<span id="MarinePollutantIndicator">MarinePollutantIndicator</span> | xsd:boolean
<span id="HazardClassVersionIdentifier">HazardClassVersionIdentifier</span> | xsd:token
<span id="MarkingText">MarkingText</span> | xsd:string
<span id="SpecialProvisionIdentifier">SpecialProvisionIdentifier</span> | xsd:token
<span id="RegulationNameText">RegulationNameText</span> | xsd:string
<span id="LimitedQuantityCode">LimitedQuantityCode</span> | xsd:token
<span id="AircraftLimitationInformationText">AircraftLimitationInformationText</span> | xsd:string


<h1 id="QuantityAnalysis">QuantityAnalysis</h1>

Type: rdf:Class

Comments: The quantity analysis for this work item.

Properties: 

Name | Type 
-|-
<span id="ActualQuantity">ActualQuantity</span> | xsd:decimal
<span id="TypeCode">TypeCode</span> | xsd:token
<span id="BreakdownWorkItemQuantityAnalysis">BreakdownWorkItemQuantityAnalysis</span> | [edi3:QuantityAnalysis](#QuantityAnalysis)
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="ContractualLanguageCode">ContractualLanguageCode</span> | xsd:token
<span id="PrimaryClassificationCode">PrimaryClassificationCode</span> | xsd:token
<span id="AlternativeClassificationCode">AlternativeClassificationCode</span> | xsd:token
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="ChangedRecordedStatus">ChangedRecordedStatus</span> | [edi3:Status](#Status)
<span id="ActualQuantityPercent">ActualQuantityPercent</span> | xsd:decimal
<span id="ActualQuantityWorkItemDimension">ActualQuantityWorkItemDimension</span> | [edi3:Dimension](#Dimension)


<h1 id="Pairing">Pairing</h1>

Type: rdf:Class

Comments: The process by which two potentially communicating entities are linked.

Properties: 

Name | Type 
-|-
<span id="MethodCode">MethodCode</span> | xsd:token
<span id="TargetEntityIdentifier">TargetEntityIdentifier</span> | xsd:token
<span id="PairedIndicator">PairedIndicator</span> | xsd:boolean


<h1 id="CoordinateSourceSystem">CoordinateSourceSystem</h1>

Type: rdf:Class

Comments: Properties defining a geographical coordinate source system used in different places around the world to identify locations on the earth.

Properties: 

Name | Type 
-|-
<span id="UsedSignalSourceQuantity">UsedSignalSourceQuantity</span> | xsd:decimal
<span id="SignalSourceAvailableQuantity">SignalSourceAvailableQuantity</span> | xsd:decimal
<span id="SourceTypeCode">SourceTypeCode</span> | xsd:token
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token


<h1 id="Condition">Condition</h1>

Type: rdf:Class

Comments: A state that applies to a product characteristic.

Properties: 

Name | Type 
-|-
<span id="ValueMeasure">ValueMeasure</span> | xsd:decimal
<span id="NameText">NameText</span> | xsd:string


<h1 id="ShippingMarks">ShippingMarks</h1>

Type: rdf:Class

Comments: Physical markings or labels on individual packages or transport units for logistics purposes.

Properties: 

Name | Type 
-|-
<span id="VINLogisticsLabel">VINLogisticsLabel</span> | [edi3:Label](#Label)
<span id="RFIDLogisticsLabel">RFIDLogisticsLabel</span> | [edi3:Label](#Label)
<span id="BarcodeLogisticsLabel">BarcodeLogisticsLabel</span> | [edi3:Label](#Label)
<span id="MarkingText">MarkingText</span> | xsd:string


<h1 id="Service">Service</h1>

Type: rdf:Class

Comments: <br/>A service associated with a transport movement.<br/>A referenced service associated with a specified event during transport movement.<br/>

Properties: 

Name | Type 
-|-
<span id="InformationText">InformationText</span> | xsd:string
<span id="RequesterTradeParty">RequesterTradeParty</span> | [edi3:Party](#Party)
<span id="ResponsibleTradeParty">ResponsibleTradeParty</span> | [edi3:Party](#Party)
<span id="PaymentArrangementTransportServicePaymentArrangementCode">PaymentArrangementTransportServicePaymentArrangementCode</span> | xsd:token
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="EffectiveSpecifiedPeriod">EffectiveSpecifiedPeriod</span> | [edi3:Period](#Period)
<span id="ChargeAmount">ChargeAmount</span> | xsd:decimal
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="PriorityTransportServicePriorityCode">PriorityTransportServicePriorityCode</span> | xsd:token
<span id="URIUniversalCommunication">URIUniversalCommunication</span> | [edi3:Communication](#Communication)
<span id="NameText">NameText</span> | xsd:string
<span id="CategoryTypeCode">CategoryTypeCode</span> | xsd:token
<span id="ContractIdentificationIdentifier">ContractIdentificationIdentifier</span> | xsd:token
<span id="ServiceRequirementTransportServiceRequirementCode">ServiceRequirementTransportServiceRequirementCode</span> | xsd:token
<span id="SpecifiedTransportRoute">SpecifiedTransportRoute</span> | [edi3:Route](#Route)


<h1 id="Material">Material</h1>

Type: rdf:Class

Comments: <br/>Material capable of undergoing spontaneous nuclear decay involving emission of ionizing radiation in the form of particles or gamma rays.<br/>Any materials unused and rejected as unwanted during a transport movement.<br/>

Properties: 

Name | Type 
-|-
<span id="LowDispersibleInformationText">LowDispersibleInformationText</span> | xsd:string
<span id="CompositionDescriptionText">CompositionDescriptionText</span> | xsd:string
<span id="TypeCode">TypeCode</span> | xsd:token
<span id="CriticalitySafetyIndexNumeric">CriticalitySafetyIndexNumeric</span> | xsd:decimal
<span id="CompleteDeliveryIndicator">CompleteDeliveryIndicator</span> | xsd:boolean
<span id="NextDeliveryTransportEvent">NextDeliveryTransportEvent</span> | [edi3:Event](#Event)
<span id="SpecialFormInformationText">SpecialFormInformationText</span> | xsd:string
<span id="IncludedTransportWasteMaterialComponent">IncludedTransportWasteMaterialComponent</span> | [edi3:MaterialComponent](#MaterialComponent)
<span id="RadionuclideNameText">RadionuclideNameText</span> | xsd:string
<span id="PreviousDeliveryTransportEvent">PreviousDeliveryTransportEvent</span> | [edi3:Event](#Event)
<span id="FissileExceptionIndicator">FissileExceptionIndicator</span> | xsd:boolean
<span id="ReceptionFacilityTradeContact">ReceptionFacilityTradeContact</span> | [edi3:Contact](#Contact)


<h1 id="CargoInsurance">CargoInsurance</h1>

Type: rdf:Class

Comments: Insurance coverage for cargo during transport movements.

Properties: 

Name | Type 
-|-
<span id="ContractGeneralConditionsText">ContractGeneralConditionsText</span> | xsd:string
<span id="CoverageTradeParty">CoverageTradeParty</span> | [edi3:Party](#Party)
<span id="CoverageDescriptionText">CoverageDescriptionText</span> | xsd:string


<h1 id="Marking">Marking</h1>

Type: rdf:Class

Comments: An inscription, stamp or label on packaging, such as to indicate date, ownership, quality, manufacture or origin.

Properties: 

Name | Type 
-|-
<span id="ContentCode">ContentCode</span> | xsd:token
<span id="ContentDateTime">ContentDateTime</span> | xsd:dateTime
<span id="ContentText">ContentText</span> | xsd:string
<span id="TypePackagingMarkingCode">TypePackagingMarkingCode</span> | xsd:token
<span id="BarcodeTypeCode">BarcodeTypeCode</span> | xsd:token
<span id="ContentAmount">ContentAmount</span> | xsd:decimal


<h1 id="TransportMeans">TransportMeans</h1>

Type: rdf:Class

Comments: <br/>The devices used to convey goods or other objects from place to place during logistics cargo movements.<br/>Reference to a device or method used to convey people, goods, or other objects from place to place.<br/>

Properties: 

Name | Type 
-|-
<span id="CompanySecurityOfficerTransportPerson">CompanySecurityOfficerTransportPerson</span> | [edi3:Person](#Person)
<span id="ForwardDraughtLevelMeasure">ForwardDraughtLevelMeasure</span> | xsd:decimal
<span id="DriverAccompaniedIndicator">DriverAccompaniedIndicator</span> | xsd:boolean
<span id="ApplicableLogisticsServiceCharge">ApplicableLogisticsServiceCharge</span> | [edi3:ServiceCharge](#ServiceCharge)
<span id="AttachedLogisticsTransportEquipment">AttachedLogisticsTransportEquipment</span> | [edi3:TransportEquipment](#TransportEquipment)
<span id="RequiredLaneLengthLinearUnitMeasure">RequiredLaneLengthLinearUnitMeasure</span> | xsd:decimal
<span id="TypeTransportMeansTypeCode">TypeTransportMeansTypeCode</span> | xsd:token
<span id="OperatorNationalityTradeCountry">OperatorNationalityTradeCountry</span> | [edi3:Country](#Country)
<span id="ConferenceCode">ConferenceCode</span> | xsd:token
<span id="TypeText">TypeText</span> | xsd:string
<span id="GrossWeightWeightUnitMeasure">GrossWeightWeightUnitMeasure</span> | xsd:decimal
<span id="ServiceProviderTradeParty">ServiceProviderTradeParty</span> | [edi3:Party](#Party)
<span id="CertifiedCalculatedEmission">CertifiedCalculatedEmission</span> | [edi3:Emission](#Emission)
<span id="ApprovedSecurityPlanOnboardIndicator">ApprovedSecurityPlanOnboardIndicator</span> | xsd:boolean
<span id="WasteReportingExemptionIndicator">WasteReportingExemptionIndicator</span> | xsd:boolean
<span id="AftDraughtLevelMeasure">AftDraughtLevelMeasure</span> | xsd:decimal
<span id="RegistrationTransportEvent">RegistrationTransportEvent</span> | [edi3:Event](#Event)
<span id="CargoGrossWeightWeightUnitMeasure">CargoGrossWeightWeightUnitMeasure</span> | xsd:decimal
<span id="ManufacturingFormattedDateTime">ManufacturingFormattedDateTime</span> | xsd:dateTime
<span id="TareWeightWeightUnitMeasure">TareWeightWeightUnitMeasure</span> | xsd:decimal
<span id="ManufacturerTradeParty">ManufacturerTradeParty</span> | [edi3:Party](#Party)
<span id="LoadedCargoMeasure">LoadedCargoMeasure</span> | xsd:decimal
<span id="ISSCReferencedDocument">ISSCReferencedDocument</span> | [edi3:Document](#Document)
<span id="SequenceNumeric">SequenceNumeric</span> | xsd:decimal
<span id="SpecifiedHandlingInstructions">SpecifiedHandlingInstructions</span> | [edi3:Instructions](#Instructions)
<span id="OwnerAgentTradeParty">OwnerAgentTradeParty</span> | [edi3:Party](#Party)
<span id="ISPSSecurityLevelCode">ISPSSecurityLevelCode</span> | xsd:token
<span id="SpecifiedIdentifiedFault">SpecifiedIdentifiedFault</span> | [edi3:Fault](#Fault)
<span id="AttachedMonitoringIOTDevice">AttachedMonitoringIOTDevice</span> | [edi3:IOTDevice](#IOTDevice)
<span id="RequiredTransportService">RequiredTransportService</span> | [edi3:Service](#Service)
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="OwnerTradeParty">OwnerTradeParty</span> | [edi3:Party](#Party)
<span id="NameText">NameText</span> | xsd:string
<span id="OperatorTradeParty">OperatorTradeParty</span> | [edi3:Party](#Party)
<span id="SpecifiedSpatialDimension">SpecifiedSpatialDimension</span> | [edi3:Dimension](#Dimension)
<span id="HelipadIndicator">HelipadIndicator</span> | xsd:boolean
<span id="RegistrationTradeCountry">RegistrationTradeCountry</span> | [edi3:Country](#Country)
<span id="ISSCIssuingAuthorityTradeParty">ISSCIssuingAuthorityTradeParty</span> | [edi3:Party](#Party)
<span id="ManoeuvringSpeedMeasure">ManoeuvringSpeedMeasure</span> | xsd:decimal
<span id="DraughtLevelMeasure">DraughtLevelMeasure</span> | xsd:decimal
<span id="LengthLinearUnitMeasure">LengthLinearUnitMeasure</span> | xsd:decimal


<h1 id="ProductInstance">ProductInstance</h1>

Type: rdf:Class

Comments: An individual trade product or batch of similar trade products produced by human or mechanical effort or by a natural process.

Properties: 

Name | Type 
-|-
<span id="InspectionSupplyChainEvent">InspectionSupplyChainEvent</span> | [edi3:Event](#Event)
<span id="ActualQuantity">ActualQuantity</span> | xsd:decimal
<span id="AppliedProductHandlingProcess">AppliedProductHandlingProcess</span> | [edi3:Process](#Process)
<span id="PackagingSupplyChainEvent">PackagingSupplyChainEvent</span> | [edi3:Event](#Event)
<span id="ExpiryDateTime">ExpiryDateTime</span> | xsd:dateTime
<span id="BestBeforeDateTime">BestBeforeDateTime</span> | xsd:dateTime
<span id="SupplierAssignedSerialIdentificationIdentifier">SupplierAssignedSerialIdentificationIdentifier</span> | xsd:token
<span id="OriginLogisticsLocation">OriginLogisticsLocation</span> | [edi3:Location](#Location)
<span id="ProductionSupplyChainEvent">ProductionSupplyChainEvent</span> | [edi3:Event](#Event)
<span id="BatchIdentificationIdentifier">BatchIdentificationIdentifier</span> | xsd:token
<span id="GlobalSerialIdentificationIdentifier">GlobalSerialIdentificationIdentifier</span> | xsd:token
<span id="SerialIdentificationIdentifier">SerialIdentificationIdentifier</span> | xsd:token
<span id="ApplicableProductCharacteristic">ApplicableProductCharacteristic</span> | [edi3:Characteristic](#Characteristic)
<span id="LotIdentificationIdentifier">LotIdentificationIdentifier</span> | xsd:token
<span id="RegistrationIdentificationIdentifier">RegistrationIdentificationIdentifier</span> | xsd:token
<span id="ApplicableMaterialGoodsCharacteristic">ApplicableMaterialGoodsCharacteristic</span> | [edi3:GoodsCharacteristic](#GoodsCharacteristic)
<span id="KanbanIdentificationIdentifier">KanbanIdentificationIdentifier</span> | xsd:token


<h1 id="Contact">Contact</h1>

Type: rdf:Class

Comments: A person or a department that acts as a point of contact with another person or department in a trading relationship.

Properties: 

Name | Type 
-|-
<span id="InstantMessagingUniversalCommunication">InstantMessagingUniversalCommunication</span> | [edi3:Communication](#Communication)
<span id="EmailURIUniversalCommunication">EmailURIUniversalCommunication</span> | [edi3:Communication](#Communication)
<span id="MobileTelephoneUniversalCommunication">MobileTelephoneUniversalCommunication</span> | [edi3:Communication](#Communication)
<span id="TypeContactTypeCode">TypeContactTypeCode</span> | xsd:token
<span id="FaxUniversalCommunication">FaxUniversalCommunication</span> | [edi3:Communication](#Communication)
<span id="JobTitleText">JobTitleText</span> | xsd:string
<span id="SpecifiedNote">SpecifiedNote</span> | [edi3:Note](#Note)
<span id="PersonIdentificationIdentifier">PersonIdentificationIdentifier</span> | xsd:token
<span id="TelephoneUniversalCommunication">TelephoneUniversalCommunication</span> | [edi3:Communication](#Communication)
<span id="ResponsibilityText">ResponsibilityText</span> | xsd:string
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="VOIPUniversalCommunication">VOIPUniversalCommunication</span> | [edi3:Communication](#Communication)
<span id="AuthorizedPersonNameText">AuthorizedPersonNameText</span> | xsd:string
<span id="DirectTelephoneUniversalCommunication">DirectTelephoneUniversalCommunication</span> | [edi3:Communication](#Communication)
<span id="DepartmentNameText">DepartmentNameText</span> | xsd:string
<span id="PersonNameText">PersonNameText</span> | xsd:string
<span id="SpecifiedContactPerson">SpecifiedContactPerson</span> | [edi3:Person](#Person)


<h1 id="WorkflowObject">WorkflowObject</h1>

Type: rdf:Class

Comments: An object used in the management of the status changes in a business process.

Properties: 

Name | Type 
-|-
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="PreviousStatusCode">PreviousStatusCode</span> | xsd:token


<h1 id="Response">Response</h1>

Type: rdf:Class

Comments: A response to a specification query.

Properties: 

Name | Type 
-|-
<span id="ContractualLanguageCode">ContractualLanguageCode</span> | xsd:token
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="ContentText">ContentText</span> | xsd:string
<span id="QueryIdentificationIdentifier">QueryIdentificationIdentifier</span> | xsd:token


<h1 id="Equipment">Equipment</h1>

Type: rdf:Class

Comments: Hardware or software typically marketed by a company other than the original manufacturer.

Properties: 

Name | Type 
-|-
<span id="PollingRateMeasure">PollingRateMeasure</span> | xsd:decimal
<span id="ApplicablePhysicalCharacteristic">ApplicablePhysicalCharacteristic</span> | [edi3:Characteristic](#Characteristic)
<span id="PollingCapabilityIndicator">PollingCapabilityIndicator</span> | xsd:boolean
<span id="ManufacturerTradeParty">ManufacturerTradeParty</span> | [edi3:Party](#Party)
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token


<h1 id="DirectPositionList">DirectPositionList</h1>

Type: rdf:Class

Comments: The specified list of coordinates for a physical location, expressed as a sequence of direct positions.

Properties: 

Name | Type 
-|-
<span id="UOMLabelListText">UOMLabelListText</span> | xsd:string
<span id="NameText">NameText</span> | xsd:string
<span id="AxisLabelListText">AxisLabelListText</span> | xsd:string
<span id="CountNumeric">CountNumeric</span> | xsd:decimal
<span id="CoordinateText">CoordinateText</span> | xsd:string


<h1 id="Schedule">Schedule</h1>

Type: rdf:Class

Comments: A series of planned activities or things to be done in this supply chain.

Properties: 

Name | Type 
-|-
<span id="OccurrenceDateTime">OccurrenceDateTime</span> | xsd:dateTime
<span id="TypeCode">TypeCode</span> | xsd:token
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token


<h1 id="Clause">Clause</h1>

Type: rdf:Class

Comments: A distinct article or provision in a document, which requires compliance.

Properties: 

Name | Type 
-|-
<span id="URLIdentifier">URLIdentifier</span> | xsd:token
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="ContentText">ContentText</span> | xsd:string
<span id="AssociatedSpecifiedPeriod">AssociatedSpecifiedPeriod</span> | [edi3:Period](#Period)


<h1 id="RegulatedGoods">RegulatedGoods</h1>

Type: rdf:Class

Comments: Articles of trade or commerce which are subject to, or controlled by a rule, regulation, or law at a particular point during their logistics lifecycle.

Properties: 

Name | Type 
-|-


<h1 id="GeographicalGrid">GeographicalGrid</h1>

Type: rdf:Class

Comments: The combination of the latitude and longitude forming a graticule, used for specifying the position of any location on the surface of the Earth, without consideration of altitude or depth (reference ISO 19136).

Properties: 

Name | Type 
-|-
<span id="OriginAssociatedSpecifiedDirectPositionList">OriginAssociatedSpecifiedDirectPositionList</span> | [edi3:DirectPositionList](#DirectPositionList)
<span id="AxisNameText">AxisNameText</span> | xsd:string
<span id="CellText">CellText</span> | xsd:string
<span id="AssociatedSpecifiedGeographicalObjectCharacteristic">AssociatedSpecifiedGeographicalObjectCharacteristic</span> | [edi3:GeographicalObjectCharacteristic](#GeographicalObjectCharacteristic)
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="LowLimitText">LowLimitText</span> | xsd:string
<span id="AssociatedLogisticsLocation">AssociatedLogisticsLocation</span> | [edi3:Location](#Location)
<span id="DimensionNumeric">DimensionNumeric</span> | xsd:decimal
<span id="OffsetVectorNumeric">OffsetVectorNumeric</span> | xsd:decimal


<h1 id="Location">Location</h1>

Type: rdf:Class

Comments: <br/>A location where a transport service takes place.<br/>A physical location or place used or referenced for trade purposes.<br/>A physical location or place which is a subordinate location of a location.<br/>A physical location or place which is a subordinate location of a subordinate location.<br/>A logistics related physical location or place.<br/>

Properties: 

Name | Type 
-|-
<span id="CountryCountryIdentifier">CountryCountryIdentifier</span> | xsd:token
<span id="AssociatedSpecifiedGeographicalFeature">AssociatedSpecifiedGeographicalFeature</span> | [edi3:GeographicalFeature](#GeographicalFeature)
<span id="InspectionSupplyChainEvent">InspectionSupplyChainEvent</span> | [edi3:Event](#Event)
<span id="PhysicalGeographicalCoordinate">PhysicalGeographicalCoordinate</span> | [edi3:GeographicalCoordinate](#GeographicalCoordinate)
<span id="StaySpecifiedPeriod">StaySpecifiedPeriod</span> | [edi3:Period](#Period)
<span id="DescriptionText">DescriptionText</span> | xsd:string
<span id="TypeLocationFunctionCode">TypeLocationFunctionCode</span> | xsd:token
<span id="CountryNameText">CountryNameText</span> | xsd:string
<span id="ServicingSpecifiedLocationParty">ServicingSpecifiedLocationParty</span> | [edi3:Party](#Party)
<span id="IdentificationIdentifier">IdentificationIdentifier</span> | xsd:token
<span id="NameText">NameText</span> | xsd:string
<span id="SubordinateSubordinateLocation">SubordinateSubordinateLocation</span> | [edi3:Location](#Location)
<span id="SubordinateSubordinateSubordinateLocation">SubordinateSubordinateSubordinateLocation</span> | [edi3:Location](#Location)
<span id="PreviousAssociatedSpecifiedGeographicalFeature">PreviousAssociatedSpecifiedGeographicalFeature</span> | [edi3:GeographicalFeature](#GeographicalFeature)
<span id="PostalTradeAddress">PostalTradeAddress</span> | [edi3:Address](#Address)


<h1 id="SizeDescriptionText">SizeDescriptionText</h1>

Type: rdf:Property

Comments: A size description, expressed as text, for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="CategoryTransportEquipmentCategoryCode">CategoryTransportEquipmentCategoryCode</h1>

Type: rdf:Property

Comments: <br/>The code specifying the category of this referenced piece of logistics transport equipment.<br/>The code specifying the category for this piece of logistics transport equipment, such as container or trailer.<br/>A code specifying a category of this piece of attached transport equipment.<br/>

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="OperationalCategoryCargoOperationalCategoryCode">OperationalCategoryCargoOperationalCategoryCode</h1>

Type: rdf:Property

Comments: The code specifying the operational category for this transport cargo, such as obnoxious or military.

Domains: 

[edi3:Cargo](#Cargo)


<h1 id="TaxApplicableTradeCurrencyExchange">TaxApplicableTradeCurrencyExchange</h1>

Type: rdf:Property

Comments: A currency exchange applicable to a tax in this header trade settlement.

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="ConstraintIndicator">ConstraintIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not the project is constrained by an authority such as the World Trade Organization (WTO) for this procuring project.

Domains: 

[edi3:Project](#Project)


<h1 id="CurrencyCode">CurrencyCode</h1>

Type: rdf:Property

Comments: <br/>The code specifying the currency of this debtor financial account (Reference ISO 4217 codes).<br/>The code specifying the currency for this registered tax.<br/>The code specifying the currency of this creditor financial account (Reference ISO 4217 codes).<br/>

Domains: 

[edi3:FinancialAccount](#FinancialAccount)
[edi3:Tax](#Tax)


<h1 id="NominalGrossWeightWeightUnitMeasure">NominalGrossWeightWeightUnitMeasure</h1>

Type: rdf:Property

Comments: The measure of the nominal gross weight (mass) of this referenced logistics package and its contents.

Domains: 

[edi3:Package](#Package)


<h1 id="IncludedSpecifiedGeographicalSurface">IncludedSpecifiedGeographicalSurface</h1>

Type: rdf:Property

Comments: The geographical surface included in this geographical feature.

Domains: 

[edi3:GeographicalFeature](#GeographicalFeature)


<h1 id="ActualLoadingSupplyChainEvent">ActualLoadingSupplyChainEvent</h1>

Type: rdf:Property

Comments: <br/>The actual loading event, at line level, for this trade delivery.<br/>The actual loading event, at header level, for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="TypeProcessTypeCode">TypeProcessTypeCode</h1>

Type: rdf:Property

Comments: The code specifying the type of product handling process.

Domains: 

[edi3:Process](#Process)


<h1 id="TargetUnitBaseNumeric">TargetUnitBaseNumeric</h1>

Type: rdf:Property

Comments: The numeric unit basis of the target currency used in this trade related currency exchange rate calculation.

Domains: 

[edi3:CurrencyExchange](#CurrencyExchange)


<h1 id="TaxTotalAmount">TaxTotalAmount</h1>

Type: rdf:Property

Comments: <br/>A monetary value of the total of all tax amounts being reported in this trade settlement line monetary summation.<br/>A monetary value of the total of all tax amounts reported in this trade settlement payment monetary summation.<br/>A monetary value of the total of all tax amounts being reported in this trade settlement header monetary summation.<br/>

Domains: 

[edi3:MonetarySummation](#MonetarySummation)


<h1 id="AdditionalStatementNote">AdditionalStatementNote</h1>

Type: rdf:Property

Comments: An additional statement note for this exchanged declaration.

Domains: 

[edi3:Declaration](#Declaration)


<h1 id="ActualDepartureRelatedDateTime">ActualDepartureRelatedDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time or other date time value of the actual departure related to this transport event.

Domains: 

[edi3:Event](#Event)


<h1 id="LocalConsigneeAgentTradeParty">LocalConsigneeAgentTradeParty</h1>

Type: rdf:Property

Comments: The local party authorized to act for or on behalf of the consignee for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="FormattedPickUpAvailabilityFormattedDateTime">FormattedPickUpAvailabilityFormattedDateTime</h1>

Type: rdf:Property

Comments: The formatted date, time, date time, or other date time value, at header level, when this trade delivery is available for pick-up.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="InvoiceCurrencyCurrencyCode">InvoiceCurrencyCurrencyCode</h1>

Type: rdf:Property

Comments: The code specifying the invoice currency for this header trade settlement.

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="SellByDateTime">SellByDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time, or other date time value by after which the items contained in the trade product instance should not be sold.

Domains: 

[edi3:ProductInstance](#ProductInstance)


<h1 id="ApplicableLineTradeAgreement">ApplicableLineTradeAgreement</h1>

Type: rdf:Property

Comments: A trade agreement applicable to this line trade transaction, such as payment or delivery terms.

Domains: 

[edi3:TradeTransaction](#TradeTransaction)


<h1 id="IntermediateConsigneeTradeParty">IntermediateConsigneeTradeParty</h1>

Type: rdf:Property

Comments: A party that is an intermediate consignee for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="ProductOrderableIndicator">ProductOrderableIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not the product can be ordered according to this line trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="TransshipmentLogisticsLocation">TransshipmentLogisticsLocation</h1>

Type: rdf:Property

Comments: A transshipment location for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="ApplicableTradePaymentTerms">ApplicableTradePaymentTerms</h1>

Type: rdf:Property

Comments: The payment terms applicable to this header trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="AbstractText">AbstractText</h1>

Type: rdf:Property

Comments: A textual abstract of the content of the work item complex description.

Domains: 

[edi3:ComplexDescription](#ComplexDescription)


<h1 id="ResultDocumentAuthentication">ResultDocumentAuthentication</h1>

Type: rdf:Property

Comments: The authentication of the results of this applied chemical treatment.

Domains: 

[edi3:ChemicalTreatment](#ChemicalTreatment)


<h1 id="CompleteDateTime">CompleteDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time or other date time value for a complete specified period of time expressed as a specific month, a specific week, etc.

Domains: 

[edi3:Period](#Period)


<h1 id="ApplicableTradePaymentPenaltyTerms">ApplicableTradePaymentPenaltyTerms</h1>

Type: rdf:Property

Comments: Trade payment penalty terms applicable to these trade payment terms.

Domains: 

[edi3:PaymentTerms](#PaymentTerms)


<h1 id="LanguageLanguageIdentifier">LanguageLanguageIdentifier</h1>

Type: rdf:Property

Comments: <br/>An identifier for a language used in this referenced document.<br/>A unique identifier of a language related to this transport person, such as their spoken or correspondence language.<br/>

Domains: 

[edi3:Document](#Document)
[edi3:Person](#Person)


<h1 id="GrossPriceProductTradePrice">GrossPriceProductTradePrice</h1>

Type: rdf:Property

Comments: <br/>A gross product price in this line trade agreement.<br/>A gross product price in this subordinate line trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="OpenIndicator">OpenIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not an entity is open during this specified period.

Domains: 

[edi3:Period](#Period)


<h1 id="BasisQuantity">BasisQuantity</h1>

Type: rdf:Property

Comments: <br/>The quantity on which the trade price is based.<br/>The quantity used as the basis for calculating the amount of this trade related tax, levy or duty.<br/>The quantity on which this trade allowance charge is based.<br/>A quantity on which the reference price is based.<br/>

Domains: 

[edi3:Price](#Price)
[edi3:AllowanceCharge](#AllowanceCharge)
[edi3:Tax](#Tax)


<h1 id="FinancedTotalAmount">FinancedTotalAmount</h1>

Type: rdf:Property

Comments: <br/>A financed total monetary value in this financing summary document.<br/>A monetary value of the financed total amount in this financing request result document.<br/>

Domains: 

[edi3:Document](#Document)


<h1 id="CalculationSequenceNumeric">CalculationSequenceNumeric</h1>

Type: rdf:Property

Comments: A numeric expression of the sequence in which this trade related tax is to be or has been applied when multiple taxes are applicable per calculation, such as first "Value Added Tax (VAT)", second "Transfer".

Domains: 

[edi3:Tax](#Tax)


<h1 id="UltimateCustomerOrderReferencedDocument">UltimateCustomerOrderReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>An ultimate customer order document referenced for this line trade agreement.<br/>An ultimate customer order document referenced for this header trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="PerPackageUnitQuantity">PerPackageUnitQuantity</h1>

Type: rdf:Property

Comments: <br/>A number of units per package in this referenced logistics package.<br/>The number of units per package, at line level, in this trade delivery.<br/>A number of units per package in this logistics package.<br/>The number of units per package in this subordinate line trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)
[edi3:Package](#Package)


<h1 id="IssueFormattedDateTime">IssueFormattedDateTime</h1>

Type: rdf:Property

Comments: <br/>The date, time, date time or other date time value for the issuance of this supply chain trade transaction.<br/>The date, time, date time or other date time value for the issuance of this exchanged declaration.<br/>

Domains: 

[edi3:TradeTransaction](#TradeTransaction)
[edi3:Declaration](#Declaration)


<h1 id="UseDescriptionText">UseDescriptionText</h1>

Type: rdf:Property

Comments: A textual description of a use of this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="DeclaredSpecifiedPersonalEffects">DeclaredSpecifiedPersonalEffects</h1>

Type: rdf:Property

Comments: Personal effects use declared by a transport person.

Domains: 

[edi3:Person](#Person)


<h1 id="ReportingIOTDeviceCommunicationPairing">ReportingIOTDeviceCommunicationPairing</h1>

Type: rdf:Property

Comments: An IOT device reported communication pairing for this piece of logistics transport equipment.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="ApplicableCrossBorderCustomsValuation">ApplicableCrossBorderCustomsValuation</h1>

Type: rdf:Property

Comments: <br/>A customs valuation applicable to this supply chain consignment item.<br/>Customs valuation information applicable to this exchanged declaration.<br/>A cross-border customs valuation applicable to this supply chain consignment.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:Consignment](#Consignment)
[edi3:Declaration](#Declaration)


<h1 id="CrewQuantity">CrewQuantity</h1>

Type: rdf:Property

Comments: The number of crew members for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="ReferenceFormattedDateTime">ReferenceFormattedDateTime</h1>

Type: rdf:Property

Comments: The reference date or date time for this referenced document.

Domains: 

[edi3:Document](#Document)


<h1 id="CarrierAssignedBookingIdentificationIdentifier">CarrierAssignedBookingIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>A carrier assigned booking identifier for this piece of referenced logistics transport equipment.<br/>A carrier assigned booking identifier for this piece of logistics transport equipment.<br/>

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="HeightMeasure">HeightMeasure</h1>

Type: rdf:Property

Comments: The measure of the height component of this spatial dimension.

Domains: 

[edi3:Dimension](#Dimension)


<h1 id="PollutantIndicator">PollutantIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not these transported dangerous goods have a pollutant content.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="ApplicableReturnableAssetInstructions">ApplicableReturnableAssetInstructions</h1>

Type: rdf:Property

Comments: Returnable asset instructions for this supply chain packaging.

Domains: 

[edi3:Packaging](#Packaging)


<h1 id="CategoryNameText">CategoryNameText</h1>

Type: rdf:Property

Comments: A category name, expressed as text, of this trade related tax, levy or duty.

Domains: 

[edi3:Tax](#Tax)


<h1 id="SectionNameText">SectionNameText</h1>

Type: rdf:Property

Comments: A section name, expressed as text, for this referenced document.

Domains: 

[edi3:Document](#Document)


<h1 id="PickUpOrderFulfilmentLeadTimeDurationUnitMeasure">PickUpOrderFulfilmentLeadTimeDurationUnitMeasure</h1>

Type: rdf:Property

Comments: The measure of the expected time interval between the receipt of an order and its pick-up fulfilment according to this line trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="SupplyInstructionReferencedDocument">SupplyInstructionReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>A supply instruction document referenced in this line trade agreement.<br/>A supply instruction document referenced in this header trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="IdentificationTypeText">IdentificationTypeText</h1>

Type: rdf:Property

Comments: An identifier type, expressed as text, for this proprietary identity.

Domains: 

[edi3:Identity](#Identity)


<h1 id="TestIndicator">TestIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not this exchanged document context is a test.

Domains: 

[edi3:Context](#Context)


<h1 id="CurrencyCurrencyCode">CurrencyCurrencyCode</h1>

Type: rdf:Property

Comments: <br/>The code specifying the currency for this trade related tax, levy or duty [UNCL 6345].<br/>The code specifying the currency of this financing financial account.<br/>The code specifying the currency in this financing request document.<br/>

Domains: 

[edi3:FinancialAccount](#FinancialAccount)
[edi3:Tax](#Tax)
[edi3:Document](#Document)


<h1 id="MaximumLinearSpatialDimension">MaximumLinearSpatialDimension</h1>

Type: rdf:Property

Comments: <br/>The maximum linear spatial dimensions of this supply chain packaging.<br/>Maximum linear spatial dimensions of this trade product.<br/>

Domains: 

[edi3:Packaging](#Packaging)
[edi3:Product](#Product)


<h1 id="DemurrageInformationText">DemurrageInformationText</h1>

Type: rdf:Property

Comments: Demurrage information, expressed as text, for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="DueFormattedDateTime">DueFormattedDateTime</h1>

Type: rdf:Property

Comments: <br/>The due date for this instalment payment.<br/>The date, time, date time, or other date time value of the due date specified by these trade payment terms.<br/>

Domains: 

[edi3:Payment](#Payment)
[edi3:PaymentTerms](#PaymentTerms)


<h1 id="TargetMarketTradeCountry">TargetMarketTradeCountry</h1>

Type: rdf:Property

Comments: <br/>A target market country for this line trade agreement.<br/>A target market country for this header trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="NetWeightWeightUnitMeasure">NetWeightWeightUnitMeasure</h1>

Type: rdf:Property

Comments: <br/>A measure of the net weight (mass) of this supply chain consignment item which excludes all packaging.<br/>A measure of the net weight (mass) of this referenced consignment which excludes the weight of packaging and the weight of any transport equipment.<br/>A measure of the net weight (mass) of this consignment which excludes the weight of packaging of this supply chain consignment and that of any transport equipment.<br/>The measure of the net weight (mass) of these transported dangerous goods.<br/>The measure of the net weight (mass) of this piece of referenced logistics transport equipment.<br/>The measure of the net weight (mass) of this logistics means of transport, such as the net tonnage of a vessel determined in accordance with the provisions of the International Convention on Tonnage Measurement of Ships, 1969.<br/>The measure of the net weight (mass) of this piece of logistics transport equipment.<br/>The measure, at line level, of the net weight (mass) of this trade delivery.<br/>The measure of the net weight (mass) of the contents of this referenced logistics package.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:TransportEquipment](#TransportEquipment)
[edi3:TradeDelivery](#TradeDelivery)
[edi3:Consignment](#Consignment)
[edi3:Package](#Package)
[edi3:TransportMeans](#TransportMeans)
[edi3:DangerousGoods](#DangerousGoods)


<h1 id="InspectionTradeParty">InspectionTradeParty</h1>

Type: rdf:Property

Comments: An inspection party for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="PartialPaymentAmount">PartialPaymentAmount</h1>

Type: rdf:Property

Comments: A monetary value of a partial payment in these trade payment terms.

Domains: 

[edi3:PaymentTerms](#PaymentTerms)


<h1 id="SpecifiedAdvancePayment">SpecifiedAdvancePayment</h1>

Type: rdf:Property

Comments: An advance payment specified in this header trade settlement.

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="FinancedRatePercent">FinancedRatePercent</h1>

Type: rdf:Property

Comments: The financed rate, expressed as a percentage, in this financing request result document.

Domains: 

[edi3:Document](#Document)


<h1 id="RecyclingTypeCode">RecyclingTypeCode</h1>

Type: rdf:Property

Comments: The code specifying the type of recycling for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="AdditionalInformationNote">AdditionalInformationNote</h1>

Type: rdf:Property

Comments: A note providing additional information for this supply chain trade line item.

Domains: 

[edi3:TradeLineItem](#TradeLineItem)


<h1 id="AdditionalIdentificationIdentifier">AdditionalIdentificationIdentifier</h1>

Type: rdf:Property

Comments: An additional unique identifier for this supply chain trade line item.

Domains: 

[edi3:TradeLineItem](#TradeLineItem)


<h1 id="SpecifiedGoodsProduction">SpecifiedGoodsProduction</h1>

Type: rdf:Property

Comments: A production of goods specified for this supply chain trade line Item.

Domains: 

[edi3:TradeLineItem](#TradeLineItem)


<h1 id="CompletionSpecifiedPeriod">CompletionSpecifiedPeriod</h1>

Type: rdf:Property

Comments: The specified period of completion for this product handling process.

Domains: 

[edi3:Process](#Process)


<h1 id="PurposeText">PurposeText</h1>

Type: rdf:Property

Comments: The purpose, expressed as text, of this exchanged document.

Domains: 

[edi3:Document](#Document)


<h1 id="PrimeContractSellerTradeParty">PrimeContractSellerTradeParty</h1>

Type: rdf:Property

Comments: <br/>The seller party acting as the prime contractor for this line trade agreement.<br/>The seller party acting as the prime contractor for this header trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="UnavailableQuantity">UnavailableQuantity</h1>

Type: rdf:Property

Comments: The quantity, at line level, unavailable for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="StatusCode">StatusCode</h1>

Type: rdf:Property

Comments: <br/>The code specifying the status, at line level, for this trade delivery.<br/>The code specifying the status of this trade workflow object.<br/>A code specifying a status for this trade product.<br/>The code specifying the status of this control setting parameter.<br/>The code specifying the status, at header level, for this trade delivery.<br/>The code specifying the status of this work item quantity analysis, such as partial, approved, not approved.<br/>The code specifying the status of this operational parameter.<br/>A code specifying the status of this basic work item.<br/>The code specifying a status for this supply chain inventory.<br/>A code specifying the status of this supply chain schedule.<br/>

Domains: 

[edi3:Schedule](#Schedule)
[edi3:TradeDelivery](#TradeDelivery)
[edi3:Product](#Product)
[edi3:Parameter](#Parameter)
[edi3:QuantityAnalysis](#QuantityAnalysis)
[edi3:WorkItem](#WorkItem)
[edi3:Inventory](#Inventory)
[edi3:WorkflowObject](#WorkflowObject)


<h1 id="CustomsExportAgentTradeParty">CustomsExportAgentTradeParty</h1>

Type: rdf:Property

Comments: The party acting as an agent for, or on behalf of, the consignor with respect to the customs export procedures for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="AdditionalStreetNameText">AdditionalStreetNameText</h1>

Type: rdf:Property

Comments: The additional name of a street, expressed as text, for this trade address.

Domains: 

[edi3:Address](#Address)


<h1 id="DeliveryTransportEvent">DeliveryTransportEvent</h1>

Type: rdf:Property

Comments: <br/>A delivery event for this piece of logistics transport equipment.<br/>The delivery event for this supply chain consignment item.<br/>The delivery event for this supply chain consignment.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:TransportEquipment](#TransportEquipment)
[edi3:Consignment](#Consignment)


<h1 id="LanguageCode">LanguageCode</h1>

Type: rdf:Property

Comments: A code specifying a language for this requesting party.

Domains: 

[edi3:Party](#Party)


<h1 id="AdditionalDescriptionText">AdditionalDescriptionText</h1>

Type: rdf:Property

Comments: <br/>The description, expressed as text, of additional information supplied to enable the matching of an entry with the items that the payment is intended to settle.<br/>An additional textual description for this trade product.<br/>

Domains: 

[edi3:TradeSettlement](#TradeSettlement)
[edi3:Product](#Product)


<h1 id="NetBudgetAmount">NetBudgetAmount</h1>

Type: rdf:Property

Comments: The monetary value of the net budget for this procuring project.

Domains: 

[edi3:Project](#Project)


<h1 id="InsuranceApplicableTradeCurrencyExchange">InsuranceApplicableTradeCurrencyExchange</h1>

Type: rdf:Property

Comments: A currency exchange applicable to an insurance charge for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="DueInForecastedQuantity">DueInForecastedQuantity</h1>

Type: rdf:Property

Comments: <br/>The due in forecasted quantity, at header level, for this trade delivery.<br/>The due in forecasted quantity, at line level, for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="CompanySecurityOfficerTransportPerson">CompanySecurityOfficerTransportPerson</h1>

Type: rdf:Property

Comments: A person who is a company security officer for this logistics transport means.

Domains: 

[edi3:TransportMeans](#TransportMeans)


<h1 id="ExtensionNumberText">ExtensionNumberText</h1>

Type: rdf:Property

Comments: The extension number, expressed as text, assigned to this telecommunication number.

Domains: 

[edi3:Communication](#Communication)


<h1 id="CountrySubDivisionIdentifier">CountrySubDivisionIdentifier</h1>

Type: rdf:Property

Comments: <br/>The identifier of the country sub-division for this logistics related location.<br/>A unique identifier of the country sub-division for this trade address.<br/>The unique identifier of a country sub-division for this financial institution address (Reference ISO 3166 and UN/ECE Rec 3).<br/>The identifier of the country sub-division for this registration.<br/>

Domains: 

[edi3:Address](#Address)
[edi3:Registration](#Registration)
[edi3:Location](#Location)


<h1 id="DescriptionCode">DescriptionCode</h1>

Type: rdf:Property

Comments: <br/>The code specifying the description of these haulage instructions.<br/>The code specifying a description of this supply chain trade line item.<br/>A code specifying a description of these handling instructions.<br/>The code specifying a description of these transport instructions.<br/>The code specifying a description of these temperature setting instructions.<br/>The code specifying a description of these delivery instructions.<br/>The code specifying the description of these quarantine instructions.<br/>

Domains: 

[edi3:Instructions](#Instructions)
[edi3:TradeLineItem](#TradeLineItem)


<h1 id="SubsetSpecifiedDocumentContextParameter">SubsetSpecifiedDocumentContextParameter</h1>

Type: rdf:Property

Comments: A subset context parameter specified for this exchanged document context.

Domains: 

[edi3:Context](#Context)


<h1 id="CarriedMaterialGoodsCharacteristic">CarriedMaterialGoodsCharacteristic</h1>

Type: rdf:Property

Comments: Material characteristics of goods carried during this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="DefinedSpecifiedRange">DefinedSpecifiedRange</h1>

Type: rdf:Property

Comments: A defined range specified for this operational parameter.

Domains: 

[edi3:Parameter](#Parameter)


<h1 id="SynchronizationQuantity">SynchronizationQuantity</h1>

Type: rdf:Property

Comments: The value specifying the quantity for a synchronization of this supply chain supply plan.

Domains: 

[edi3:SupplyPlan](#SupplyPlan)


<h1 id="ModelNameText">ModelNameText</h1>

Type: rdf:Property

Comments: The model name, expressed as text, for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="MarkingInstructionMarkingInstructionCode">MarkingInstructionMarkingInstructionCode</h1>

Type: rdf:Property

Comments: A code specifying a marking instruction for these logistics shipping marks.

Domains: 

[edi3:ShippingMarks](#ShippingMarks)


<h1 id="InsuranceChargeTotalAmount">InsuranceChargeTotalAmount</h1>

Type: rdf:Property

Comments: A monetary value of the total of all insurance charges being reported in this trade settlement header monetary summation.

Domains: 

[edi3:MonetarySummation](#MonetarySummation)


<h1 id="TotalAdjustmentAmount">TotalAdjustmentAmount</h1>

Type: rdf:Property

Comments: <br/>A monetary value of the total adjustment for this header trade settlement.<br/>The monetary value of the total adjustment for this line trade settlement.<br/>

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="DesignationText">DesignationText</h1>

Type: rdf:Property

Comments: A designation, expressed as text, for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="CarriedAssociatedTransportEquipment">CarriedAssociatedTransportEquipment</h1>

Type: rdf:Property

Comments: A piece of transport equipment carried on this piece of logistics transport equipment, such as a container placed on a rail wagon.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="DeclarantTradeParty">DeclarantTradeParty</h1>

Type: rdf:Property

Comments: The trade party acting as the declarant for this exchanged declaration.

Domains: 

[edi3:Declaration](#Declaration)


<h1 id="CustomsValueSpecifiedAmount">CustomsValueSpecifiedAmount</h1>

Type: rdf:Property

Comments: The monetary value specified for customs purposes in this exchanged declaration.

Domains: 

[edi3:Declaration](#Declaration)


<h1 id="BuyerApprovedFormattedDateTime">BuyerApprovedFormattedDateTime</h1>

Type: rdf:Property

Comments: <br/>The date, time, date time, or other date time value of approval by the buyer for this line trade agreement.<br/>The date, time, date time, or other date time value of approval by the buyer for this header trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="ApplicableSpecifiedTemperature">ApplicableSpecifiedTemperature</h1>

Type: rdf:Property

Comments: The specified temperature applicable for this applied chemical treatment.

Domains: 

[edi3:ChemicalTreatment](#ChemicalTreatment)


<h1 id="LegalStatusTransportEquipmentLegalStatusCode">LegalStatusTransportEquipmentLegalStatusCode</h1>

Type: rdf:Property

Comments: The code specifying the legal status of this piece of logistics transport equipment with respect to a specific law such as the "Container Convention Code".

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="ApplicableTransportSettingTemperature">ApplicableTransportSettingTemperature</h1>

Type: rdf:Property

Comments: A transport related temperature setting applicable to these handling instructions.

Domains: 

[edi3:Instructions](#Instructions)


<h1 id="HazardTypeCode">HazardTypeCode</h1>

Type: rdf:Property

Comments: A code specifying the type of hazard for these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="ConversionRateDateTime">ConversionRateDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time or other date time value of the conversion rate for this trade related currency exchange.

Domains: 

[edi3:CurrencyExchange](#CurrencyExchange)


<h1 id="DepositValueSpecifiedAmount">DepositValueSpecifiedAmount</h1>

Type: rdf:Property

Comments: A deposit value specified in these returnable asset instructions.

Domains: 

[edi3:Instructions](#Instructions)


<h1 id="ProprietaryAccountNameText">ProprietaryAccountNameText</h1>

Type: rdf:Property

Comments: <br/>The proprietary account name, expressed as text, of this debtor financial account.<br/>The proprietary account name, expressed as text, of this creditor financial account.<br/>

Domains: 

[edi3:FinancialAccount](#FinancialAccount)


<h1 id="PostcodeCode">PostcodeCode</h1>

Type: rdf:Property

Comments: <br/>The code specifying the postcode for this financial institution address.<br/>A code specifying the postcode of this trade address.<br/>

Domains: 

[edi3:Address](#Address)


<h1 id="CreditAvailableAmount">CreditAvailableAmount</h1>

Type: rdf:Property

Comments: A monetary value of the credit available for this trade settlement financial card.

Domains: 

[edi3:FinancialCard](#FinancialCard)


<h1 id="BuyerReferenceText">BuyerReferenceText</h1>

Type: rdf:Property

Comments: <br/>A buyer reference, expressed as text, for this line trade agreement.<br/>A buyer reference, expressed as text, for this header trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="IrishNSCIdentificationIdentifier">IrishNSCIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique Irish National Sorting Code (NSC) identifier as assigned by the Irish Payments Services Organisation (IPSO) for this creditor financial institution.<br/>The unique Irish National Sorting Code (NSC) identifier as assigned by the Irish Payments Services Organisation (IPSO) for this debtor financial institution.<br/>

Domains: 

[edi3:FinancialInstitution](#FinancialInstitution)


<h1 id="ContainedConsignmentQuantity">ContainedConsignmentQuantity</h1>

Type: rdf:Property

Comments: The number of consignments contained in this piece of logistics transport equipment.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="ScheduledPaymentDateTime">ScheduledPaymentDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time or other date time value of the scheduled payment of this header trade settlement.

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="CreationFormattedDateTime">CreationFormattedDateTime</h1>

Type: rdf:Property

Comments: <br/>The date, time, date time or other date time value for the creation of this financing request document.<br/>The date, time, date time, or other date time value of a creation of this exchanged document.<br/>

Domains: 

[edi3:Document](#Document)


<h1 id="TransportMovementRiskRelatedCode">TransportMovementRiskRelatedCode</h1>

Type: rdf:Property

Comments: A code specifying a transport movement related risk for this logistics risk analysis result.

Domains: 

[edi3:RiskAnalysisResult](#RiskAnalysisResult)


<h1 id="AgencyIdentifier">AgencyIdentifier</h1>

Type: rdf:Property

Comments: The identifier of the agency for this referenced standard.

Domains: 

[edi3:Standard](#Standard)


<h1 id="URIIdentifier">URIIdentifier</h1>

Type: rdf:Property

Comments: <br/>The Uniform Resource Identifier (URI), such as a web or an email address, for this universal communication.<br/>The Uniform Resource Identifier (URI) for this email communication.<br/>The Uniform Resource Identifier (URI) for this referenced standard.<br/>The unique Uniform Resource Identifier (URI) for this specified binary file.<br/>

Domains: 

[edi3:Standard](#Standard)
[edi3:BinaryFile](#BinaryFile)
[edi3:Communication](#Communication)


<h1 id="MinimumQuantity">MinimumQuantity</h1>

Type: rdf:Property

Comments: The minimum quantity in a range for which this trade price applies.

Domains: 

[edi3:Price](#Price)


<h1 id="CreationDateTime">CreationDateTime</h1>

Type: rdf:Property

Comments: <br/>The date, time, date time, or other date time value of the creation of this valuation breakdown statement.<br/>The date or date time value of the creation of this acknowledgement document.<br/>

Domains: 

[edi3:Document](#Document)
[edi3:BreakdownStatement](#BreakdownStatement)


<h1 id="SeasonDescriptionText">SeasonDescriptionText</h1>

Type: rdf:Property

Comments: A season description, expressed as text, for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="FinalDeliveryIndicator">FinalDeliveryIndicator</h1>

Type: rdf:Property

Comments: <br/>The indication, at header level, of whether or not this trade delivery is the final delivery.<br/>The indication, at line level, of whether or not this trade delivery is the final delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="FinalAssemblyTradeCountry">FinalAssemblyTradeCountry</h1>

Type: rdf:Property

Comments: A final assembly country for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="PassengerNationalityTradeCountry">PassengerNationalityTradeCountry</h1>

Type: rdf:Property

Comments: Passenger nationality details for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="IssuingCompanyNameText">IssuingCompanyNameText</h1>

Type: rdf:Property

Comments: The issuing company name, expressed as text, for this trade settlement financial card.

Domains: 

[edi3:FinancialCard](#FinancialCard)


<h1 id="BlanketOrderReferencedDocument">BlanketOrderReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>The blanket order document referenced in this line trade agreement.<br/>The blanket order document referenced in this header trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="ReleaseIdentifier">ReleaseIdentifier</h1>

Type: rdf:Property

Comments: The release identifier for this piece of logistics transport equipment.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="MemberSpecifiedGeographicalLine">MemberSpecifiedGeographicalLine</h1>

Type: rdf:Property

Comments: A geographical line member of this geographical multi-curve.

Domains: 

[edi3:GeographicalMultiCurve](#GeographicalMultiCurve)


<h1 id="LineItemQuantity">LineItemQuantity</h1>

Type: rdf:Property

Comments: <br/>The number of line items in this exchanged document.<br/>The number of line items for this supply chain trade transaction.<br/>

Domains: 

[edi3:TradeTransaction](#TradeTransaction)
[edi3:Document](#Document)


<h1 id="ActualDateTime">ActualDateTime</h1>

Type: rdf:Property

Comments: <br/>The actual date, time, date time, or other date time value of this financial adjustment.<br/>The actual date, time, date time, or other date time value of this delivery adjustment.<br/>The actual date, time, date time, or other date time value of this document authentication.<br/>

Domains: 

[edi3:Adjustment](#Adjustment)
[edi3:Authentication](#Authentication)


<h1 id="BreakdownHeaderBalanceOut">BreakdownHeaderBalanceOut</h1>

Type: rdf:Property

Comments: A balance out breakdown of this header balance out.

Domains: 

[edi3:BalanceOut](#BalanceOut)


<h1 id="PromotionalVariantIdentificationIdentifier">PromotionalVariantIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The promotional variant identifier for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="ConsignorAssignedIdentifier">ConsignorAssignedIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique identifier assigned by the consignor to this referenced supply chain consignment.<br/>The unique identifier assigned by the consignor to this supply chain consignment.<br/>

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="AustrianBankleitzahlIdentificationIdentifier">AustrianBankleitzahlIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique Austrian Bankleitzahl identifier for this creditor financial institution.<br/>The unique Austrian Bankleitzahl identifier for this debtor financial institution.<br/>

Domains: 

[edi3:FinancialInstitution](#FinancialInstitution)


<h1 id="ConfirmedDespatchSupplyChainEvent">ConfirmedDespatchSupplyChainEvent</h1>

Type: rdf:Property

Comments: <br/>The despatch event, at line level, confirmed for this trade delivery.<br/>The despatch event, at header level, confirmed for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="RoleText">RoleText</h1>

Type: rdf:Property

Comments: <br/>A role, expressed as text, for this trade party.<br/>A role, expressed as text, of this transport person.<br/>A role, expressed as text, for this contact person.<br/>

Domains: 

[edi3:Party](#Party)
[edi3:Person](#Person)


<h1 id="DisposalTradeParty">DisposalTradeParty</h1>

Type: rdf:Property

Comments: <br/>A disposal party, at header level, for this trade delivery.<br/>A disposal party, at line level, for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="RequestedFinancingRatePercent">RequestedFinancingRatePercent</h1>

Type: rdf:Property

Comments: The financing rate, expressed as a percentage, requested for this header trade settlement.

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="OriginCriteriaText">OriginCriteriaText</h1>

Type: rdf:Property

Comments: The origin criteria, expressed as text, for this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="DeliveryNoteReferencedDocument">DeliveryNoteReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>The delivery note document, at header level, referenced for this trade delivery.<br/>A delivery note document referenced by this supply chain supply plan.<br/>The delivery note document, at line level, referenced for this trade delivery.<br/>

Domains: 

[edi3:SupplyPlan](#SupplyPlan)
[edi3:TradeDelivery](#TradeDelivery)


<h1 id="LineFiveText">LineFiveText</h1>

Type: rdf:Property

Comments: <br/>The fifth free form line, expressed as text, of this trade address.<br/>The fifth free form line, expressed as text, of this financial institution address.<br/>

Domains: 

[edi3:Address](#Address)


<h1 id="UnitBasisAmount">UnitBasisAmount</h1>

Type: rdf:Property

Comments: <br/>A monetary value that constitutes the per unit basis on which this trade related tax, levy or duty is calculated.<br/>The monetary value of the unit basis on which the allowance or charge is calculated.<br/>

Domains: 

[edi3:AllowanceCharge](#AllowanceCharge)
[edi3:Tax](#Tax)


<h1 id="ManufacturingProcessDescriptionText">ManufacturingProcessDescriptionText</h1>

Type: rdf:Property

Comments: A textual description of the manufacturing process for this goods production.

Domains: 

[edi3:Production](#Production)


<h1 id="ImmediatePreviousPriceListReferencedDocument">ImmediatePreviousPriceListReferencedDocument</h1>

Type: rdf:Property

Comments: The immediate previous price list document referenced in this line trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="CountryCountryIdentifier">CountryCountryIdentifier</h1>

Type: rdf:Property

Comments: <br/>The identifier of a country for this birth address.<br/>The unique identifier of a country for this trade address.<br/>The unique identifier of a country location used or referenced in trade.<br/>The unique identifier of a country for this logistics location.<br/>

Domains: 

[edi3:Address](#Address)
[edi3:Location](#Location)


<h1 id="IncludedSpecifiedMarketplace">IncludedSpecifiedMarketplace</h1>

Type: rdf:Property

Comments: A marketplace included in this line trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="TypePaymentMeansCode">TypePaymentMeansCode</h1>

Type: rdf:Property

Comments: The code specifying the type of trade settlement payment means, such as cash or check.

Domains: 

[edi3:PaymentMeans](#PaymentMeans)


<h1 id="IntendedUseText">IntendedUseText</h1>

Type: rdf:Property

Comments: An intended use, expressed as text, for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="TransportMeansStayOccurrenceSpecifiedPeriod">TransportMeansStayOccurrenceSpecifiedPeriod</h1>

Type: rdf:Property

Comments: The specified period during which the transport means is held at a location.

Domains: 

[edi3:Event](#Event)


<h1 id="DevanningTransportEvent">DevanningTransportEvent</h1>

Type: rdf:Property

Comments: <br/>A transport devanning event for this supply chain consignment, i.e. the unloading of this consignment at the place of delivery.<br/>A transport devanning event for this referenced supply chain consignment, i.e. the unloading of this consignment at the place of delivery.<br/>

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="ComparisonOperatorCode">ComparisonOperatorCode</h1>

Type: rdf:Property

Comments: A code specifying the operator, such as, less than, greater than or equal to, for comparing two actual measures.

Domains: 

[edi3:Measurement](#Measurement)


<h1 id="ForwardDraughtLevelMeasure">ForwardDraughtLevelMeasure</h1>

Type: rdf:Property

Comments: The draught level measured at the fore end of this transport means.

Domains: 

[edi3:TransportMeans](#TransportMeans)


<h1 id="LineFourText">LineFourText</h1>

Type: rdf:Property

Comments: <br/>The fourth free form line, expressed as text, of this financial institution address.<br/>The fourth free form line, expressed as text, of this trade address.<br/>

Domains: 

[edi3:Address](#Address)


<h1 id="SubtotalCalculatedTradeTax">SubtotalCalculatedTradeTax</h1>

Type: rdf:Property

Comments: <br/>A tax subtotal calculated for this header trade settlement.<br/>A tax subtotal calculated for this line trade settlement.<br/>

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="OriginTradeGeopoliticalRegion">OriginTradeGeopoliticalRegion</h1>

Type: rdf:Property

Comments: <br/>The geopolitical region of origin for this supply chain consignment item.<br/>The geopolitical region of origin for this supply chain consignment.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:Consignment](#Consignment)


<h1 id="IncludedSupplyChainConsignmentItem">IncludedSupplyChainConsignmentItem</h1>

Type: rdf:Property

Comments: A consignment item included in this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="RequiredApplicableReferencedProduct">RequiredApplicableReferencedProduct</h1>

Type: rdf:Property

Comments: A required product applicable for this supply chain trade line item.

Domains: 

[edi3:TradeLineItem](#TradeLineItem)


<h1 id="HandlingCode">HandlingCode</h1>

Type: rdf:Property

Comments: <br/>A code specifying these handling instructions.<br/>A code specifying delivery handling instructions.<br/>

Domains: 

[edi3:Instructions](#Instructions)


<h1 id="ShipStoresIndicator">ShipStoresIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not this supply chain consignment is for ship stores, such as for consumption on the means of transport.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="MinimumOrderQuantityOrderingSpecifiedPeriod">MinimumOrderQuantityOrderingSpecifiedPeriod</h1>

Type: rdf:Property

Comments: The minimum order quantity ordering period specified in this line trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="UrgencyText">UrgencyText</h1>

Type: rdf:Property

Comments: An urgency, expressed as text, of this exchanged document.

Domains: 

[edi3:Document](#Document)


<h1 id="RelevantTradeLocation">RelevantTradeLocation</h1>

Type: rdf:Property

Comments: The trade location relevant for these trade delivery terms.

Domains: 

[edi3:DeliveryTerms](#DeliveryTerms)


<h1 id="UNDGIdentificationCode">UNDGIdentificationCode</h1>

Type: rdf:Property

Comments: The code specifying the unique United Nations Dangerous Goods (UNDG) number assigned to these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="UnloadingReportedTransportEvent">UnloadingReportedTransportEvent</h1>

Type: rdf:Property

Comments: A transport unloading event reported for this logistics status.

Domains: 

[edi3:Status](#Status)


<h1 id="DepartureReportedTransportEvent">DepartureReportedTransportEvent</h1>

Type: rdf:Property

Comments: A transport departure event reported for this logistics status.

Domains: 

[edi3:Status](#Status)


<h1 id="DriverAccompaniedIndicator">DriverAccompaniedIndicator</h1>

Type: rdf:Property

Comments: <br/>The indication of whether or not this logistics means of transport is accompanied by a driver.<br/>The indication of whether or not this referenced means of transport is accompanied by a driver.<br/>

Domains: 

[edi3:TransportMeans](#TransportMeans)


<h1 id="OrderUnitConversionFactorNumeric">OrderUnitConversionFactorNumeric</h1>

Type: rdf:Property

Comments: The value used as the factor to convert the order unit into the price unit for this trade price.

Domains: 

[edi3:Price](#Price)


<h1 id="AssociatedSpecifiedGeographicalFeature">AssociatedSpecifiedGeographicalFeature</h1>

Type: rdf:Property

Comments: <br/>A geographical feature associated with this communication event.<br/>A geographical feature associated with this transport event.<br/>A geographical feature associated with this logistics location.<br/>

Domains: 

[edi3:Event](#Event)
[edi3:Location](#Location)


<h1 id="TypeExtensionCode">TypeExtensionCode</h1>

Type: rdf:Property

Comments: The code used as an extension to the type code for further specifying a type of supply chain trade line item.

Domains: 

[edi3:TradeLineItem](#TradeLineItem)


<h1 id="DemandForecastReferencedDocument">DemandForecastReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>A demand forecast document referenced in this line trade agreement.<br/>A demand forecast document referenced in this header trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="FourthSignatoryDocumentAuthentication">FourthSignatoryDocumentAuthentication</h1>

Type: rdf:Property

Comments: The fourth signature, also known as the third counter signature, that has been authenticated on this exchanged document indicating where appropriate the authentication party.

Domains: 

[edi3:Document](#Document)


<h1 id="ConsumptionSupplyChainSchedule">ConsumptionSupplyChainSchedule</h1>

Type: rdf:Property

Comments: A supply chain consumption schedule, at line level, for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="InstructionIdentifier">InstructionIdentifier</h1>

Type: rdf:Property

Comments: The unique identifier of the instruction for this trade settlement payment.

Domains: 

[edi3:Payment](#Payment)


<h1 id="PriceApplicableTradeCurrencyExchange">PriceApplicableTradeCurrencyExchange</h1>

Type: rdf:Property

Comments: The currency exchange applicable to the price in this header trade settlement.

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="RequestedFinancingAmount">RequestedFinancingAmount</h1>

Type: rdf:Property

Comments: A financing monetary value requested for this header trade settlement.

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="DirectDebitMandateIdentificationIdentifier">DirectDebitMandateIdentificationIdentifier</h1>

Type: rdf:Property

Comments: An identifier of a direct debit mandate in these trade payment terms.

Domains: 

[edi3:PaymentTerms](#PaymentTerms)


<h1 id="CityNameText">CityNameText</h1>

Type: rdf:Property

Comments: <br/>The name, expressed as text, of the city, town or village of this birth address.<br/>The name, expressed as text, of the city, town or village of this financial institution address.<br/>The name, expressed as text, of the city, town or village of this trade address.<br/>

Domains: 

[edi3:Address](#Address)


<h1 id="CarrierTradeParty">CarrierTradeParty</h1>

Type: rdf:Property

Comments: <br/>A carrier party for this piece of logistics transport equipment.<br/>A carrier party for this line trade agreement.<br/>A carrier party for this logistics transport movement.<br/>The carrier party, at header level, for this trade agreement.<br/>The carrier party for this supply chain consignment.<br/>The carrier party for this referenced supply chain consignment.<br/>

Domains: 

[edi3:TransportEquipment](#TransportEquipment)
[edi3:Consignment](#Consignment)
[edi3:TransportMovement](#TransportMovement)
[edi3:TradeAgreement](#TradeAgreement)


<h1 id="CODAmount">CODAmount</h1>

Type: rdf:Property

Comments: The monetary value of the COD (Cash On Delivery) amount to be collected by the carrier upon delivery of this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="ManifestRelatedReferencedDocument">ManifestRelatedReferencedDocument</h1>

Type: rdf:Property

Comments: A referenced manifest document related to this transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="AtDepartureLogisticsTransportMovement">AtDepartureLogisticsTransportMovement</h1>

Type: rdf:Property

Comments: The logistics transport movement for this supply chain consignment at the point when the means of transport departs a country or regional border.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="ResaleSpecifiedPeriod">ResaleSpecifiedPeriod</h1>

Type: rdf:Property

Comments: The resale period specified in this line trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="ItemSellerTradeParty">ItemSellerTradeParty</h1>

Type: rdf:Property

Comments: The item seller party for this line trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="SpecifiedProcuringProject">SpecifiedProcuringProject</h1>

Type: rdf:Property

Comments: The procuring project specified for this header trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="IncludedBinaryObject">IncludedBinaryObject</h1>

Type: rdf:Property

Comments: A binary object included in this specified binary file.

Domains: 

[edi3:BinaryFile](#BinaryFile)


<h1 id="SpecifiedLineTradeAgreement">SpecifiedLineTradeAgreement</h1>

Type: rdf:Property

Comments: The line trade agreement specified for this supply chain trade line item.

Domains: 

[edi3:TradeLineItem](#TradeLineItem)


<h1 id="SellerAssignedAccountantTradeParty">SellerAssignedAccountantTradeParty</h1>

Type: rdf:Property

Comments: The party assigned as an accountant by the seller for this header trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="WidthMeasure">WidthMeasure</h1>

Type: rdf:Property

Comments: The measure of the width component of this spatial dimension.

Domains: 

[edi3:Dimension](#Dimension)


<h1 id="CustomsDutyIndicator">CustomsDutyIndicator</h1>

Type: rdf:Property

Comments: <br/>The indication of whether or not this trade related tax, levy or duty is a customs duty.<br/>The indication of whether or not this registered tax is a customs duty.<br/>

Domains: 

[edi3:Tax](#Tax)


<h1 id="ExpectedIndicator">ExpectedIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not this transport event is or was expected.

Domains: 

[edi3:Event](#Event)


<h1 id="ReportableQuantity">ReportableQuantity</h1>

Type: rdf:Property

Comments: The reportable quantity for these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="SellerPayableTaxSpecifiedTradeAccountingAccount">SellerPayableTaxSpecifiedTradeAccountingAccount</h1>

Type: rdf:Property

Comments: The seller payable tax specified accounting account for this trade related tax, levy or duty.

Domains: 

[edi3:Tax](#Tax)


<h1 id="MarketingPhraseText">MarketingPhraseText</h1>

Type: rdf:Property

Comments: A catch phrase, expressed as text, for marketing of this trade product feature.

Domains: 

[edi3:Feature](#Feature)


<h1 id="LoadingTransportInstructions">LoadingTransportInstructions</h1>

Type: rdf:Property

Comments: <br/>Loading instructions for this piece of logistics transport equipment.<br/>Loading instructions for this supply chain consignment.<br/>

Domains: 

[edi3:TransportEquipment](#TransportEquipment)
[edi3:Consignment](#Consignment)


<h1 id="UnloadingTransportEvent">UnloadingTransportEvent</h1>

Type: rdf:Property

Comments: <br/>The unloading event during which goods will be or have been unloaded from the means of transport used for this logistics transport movement.<br/>The unloading event for this piece of logistics transport equipment.<br/>

Domains: 

[edi3:TransportEquipment](#TransportEquipment)
[edi3:TransportMovement](#TransportMovement)


<h1 id="CharacteristicTransportEquipmentSizeTypeCode">CharacteristicTransportEquipmentSizeTypeCode</h1>

Type: rdf:Property

Comments: <br/>The code specifying the characteristics, such as size and type, of this referenced piece of logistics transport equipment.<br/>The code specifying the characteristics, i.e. size and type, of this piece of attached transport equipment.<br/>The code specifying the characteristic or characteristics of this piece of logistics transport equipment, such as the ISO 6346 transport equipment size and type code.<br/>

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="ShipperReferenceInformationText">ShipperReferenceInformationText</h1>

Type: rdf:Property

Comments: Shipper reference information, expressed as text, for this piece of logistics transport equipment.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="SpecifiedTradeSettlementLineMonetarySummation">SpecifiedTradeSettlementLineMonetarySummation</h1>

Type: rdf:Property

Comments: The monetary summation totals specified for this line trade settlement.

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="AssertionCode">AssertionCode</h1>

Type: rdf:Property

Comments: A code specifying an assertion for this trade product certification, such as claims that a product is free from peanuts.

Domains: 

[edi3:Certification](#Certification)


<h1 id="ModificationForecastedQuantity">ModificationForecastedQuantity</h1>

Type: rdf:Property

Comments: <br/>The modification of a previously forecasted quantity, at header level, for this trade delivery.<br/>The modification of a forecasted quantity, at line level, for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="OverallLengthLinearUnitMeasure">OverallLengthLinearUnitMeasure</h1>

Type: rdf:Property

Comments: The overall length measure of this logistics convoy.

Domains: 

[edi3:Convoy](#Convoy)


<h1 id="TypeCargoCategoryCode">TypeCargoCategoryCode</h1>

Type: rdf:Property

Comments: The code, such as UNECE Recommendation 21 single digit codes, specifying the type of transported cargo.

Domains: 

[edi3:Cargo](#Cargo)


<h1 id="StockQuantity">StockQuantity</h1>

Type: rdf:Property

Comments: The quantity of stock in this supply chain inventory.

Domains: 

[edi3:Inventory](#Inventory)


<h1 id="GoodsOwnershipChangeFormattedDateTime">GoodsOwnershipChangeFormattedDateTime</h1>

Type: rdf:Property

Comments: <br/>The date, time, date time, or other date time value, at header level, when the goods ownership of this trade delivery changed.<br/>The date, time, date time, or other date time value for the goods ownership change, at line level, for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="StatisticalValueSpecifiedAmount">StatisticalValueSpecifiedAmount</h1>

Type: rdf:Property

Comments: The monetary value specified for statistical purposes in this exchanged declaration.

Domains: 

[edi3:Declaration](#Declaration)


<h1 id="LoadingRemarkText">LoadingRemarkText</h1>

Type: rdf:Property

Comments: A loading remark, expressed as text, for this piece of logistics transport equipment.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="InvoiceReferencedDocument">InvoiceReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>An invoice document referenced in this line trade settlement.<br/>An invoice document referenced by this header trade settlement.<br/>

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="CertificationBasisText">CertificationBasisText</h1>

Type: rdf:Property

Comments: A basis for a certification, expressed as text, for this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="ReasonLogisticsStatusCode">ReasonLogisticsStatusCode</h1>

Type: rdf:Property

Comments: A code specifying a reason for this logistics status [UNECE Recommendation 24].

Domains: 

[edi3:Status](#Status)


<h1 id="ComplementaryApplicableReferencedProduct">ComplementaryApplicableReferencedProduct</h1>

Type: rdf:Property

Comments: A referenced complementary product applicable for this supply chain trade line item.

Domains: 

[edi3:TradeLineItem](#TradeLineItem)


<h1 id="RecyclingProcedureText">RecyclingProcedureText</h1>

Type: rdf:Property

Comments: A recycling procedure, expressed as text, for these disposal instructions.

Domains: 

[edi3:Instructions](#Instructions)


<h1 id="ReasonAllowanceChargeReasonCode">ReasonAllowanceChargeReasonCode</h1>

Type: rdf:Property

Comments: The code specifying the reason for this trade allowance charge.

Domains: 

[edi3:AllowanceCharge](#AllowanceCharge)


<h1 id="HazardClassificationIdentifier">HazardClassificationIdentifier</h1>

Type: rdf:Property

Comments: The unique identifier of a hazard class applicable to these transported dangerous goods as defined by the relevant governing regulation authority.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="ApplicableLogisticsLocation">ApplicableLogisticsLocation</h1>

Type: rdf:Property

Comments: A logistics location or place applicable to this header trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="ApplicableLogisticsServiceCharge">ApplicableLogisticsServiceCharge</h1>

Type: rdf:Property

Comments: <br/>A service charge, such as a freight charge, applicable to this logistics means of transport.<br/>A logistics service charge applicable to this supply chain consignment item.<br/>A logistics service charge applicable to this trade party.<br/>A service charge, such as a freight charge, applicable to this logistics transport movement.<br/>A service charge applicable to this piece of logistics transport equipment.<br/>A logistics service charge applicable to this supply chain consignment, such as freight or insurance charges.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:Party](#Party)
[edi3:TransportEquipment](#TransportEquipment)
[edi3:Consignment](#Consignment)
[edi3:TransportMovement](#TransportMovement)
[edi3:TransportMeans](#TransportMeans)


<h1 id="AttachedLogisticsTransportEquipment">AttachedLogisticsTransportEquipment</h1>

Type: rdf:Property

Comments: A piece of logistics transport equipment attached to this logistics means of transport.

Domains: 

[edi3:TransportMeans](#TransportMeans)


<h1 id="SubordinateBasicWorkItem">SubordinateBasicWorkItem</h1>

Type: rdf:Property

Comments: A subordinate work item for this basic work item.

Domains: 

[edi3:WorkItem](#WorkItem)


<h1 id="ExitCustomsOfficeSpecifiedLogisticsLocation">ExitCustomsOfficeSpecifiedLogisticsLocation</h1>

Type: rdf:Property

Comments: The location of the specified customs office at which the goods which are subject to this cross-border regulatory procedure leave the customs territory of destination.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="TransportExpertTradeContact">TransportExpertTradeContact</h1>

Type: rdf:Property

Comments: The expert to be contacted for details about the transport of these dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="AppliedAmount">AppliedAmount</h1>

Type: rdf:Property

Comments: A monetary value applied to this logistics service charge.

Domains: 

[edi3:ServiceCharge](#ServiceCharge)


<h1 id="GoodsReleaseRestrictionText">GoodsReleaseRestrictionText</h1>

Type: rdf:Property

Comments: A goods release restriction, expressed as text, for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="UnloadingLogisticsLocation">UnloadingLogisticsLocation</h1>

Type: rdf:Property

Comments: The logistics location where the supply chain consignment is unloaded.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="ReferencedLineTradeTransaction">ReferencedLineTradeTransaction</h1>

Type: rdf:Property

Comments: A trade transaction referenced in this line trade settlement.

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="AverageDurationDateTime">AverageDurationDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time, or other date time of the average duration for this supply chain inventory.

Domains: 

[edi3:Inventory](#Inventory)


<h1 id="AnnualQuotaQuantity">AnnualQuotaQuantity</h1>

Type: rdf:Property

Comments: The annual quota quantity under this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="PostOfficeBoxText">PostOfficeBoxText</h1>

Type: rdf:Property

Comments: <br/>The post office box, expressed as text, for this financial institution address.<br/>The unique identifier, expressed as text, of a container commonly referred to as a box, in a post office or other postal service location, assigned to a person or organization, where postal items may be kept for this trade address.<br/>

Domains: 

[edi3:Address](#Address)


<h1 id="JurisdictionEntryFormattedDateTime">JurisdictionEntryFormattedDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time or other date time value when the items which are a subject of this exchanged declaration enter a jurisdiction, such as the actual date of arrival of a means of transport.

Domains: 

[edi3:Declaration](#Declaration)


<h1 id="AttachedProductSecurityTag">AttachedProductSecurityTag</h1>

Type: rdf:Property

Comments: A tag device attached to this trade product to provide protection from a peril such as theft.

Domains: 

[edi3:Product](#Product)


<h1 id="BirthCountryIdentifier">BirthCountryIdentifier</h1>

Type: rdf:Property

Comments: The identifier of the birth country of this transport person.

Domains: 

[edi3:Person](#Person)


<h1 id="ElectronicPresentationIndicator">ElectronicPresentationIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not this referenced document is presented in an electronic format.

Domains: 

[edi3:Document](#Document)


<h1 id="TypePackageTypeCode">TypePackageTypeCode</h1>

Type: rdf:Property

Comments: <br/>A code specifying the type of logistics package.<br/>The code specifying the type of supply chain packaging.<br/>The code specifying the type of referenced logistics package.<br/>

Domains: 

[edi3:Packaging](#Packaging)
[edi3:Package](#Package)


<h1 id="NetPriceIndicator">NetPriceIndicator</h1>

Type: rdf:Property

Comments: An indication of whether or not the reference price is a net price.

Domains: 

[edi3:Price](#Price)


<h1 id="ReasonInformationText">ReasonInformationText</h1>

Type: rdf:Property

Comments: <br/>Information, expressed as text, related to the reason for this financing status.<br/>Information, expressed as text, related to the reason for this cancellation status.<br/>Reason information, expressed as text, for this acknowledgement document.<br/>

Domains: 

[edi3:Status](#Status)
[edi3:Document](#Document)


<h1 id="QuarantineQuarantineInstructions">QuarantineQuarantineInstructions</h1>

Type: rdf:Property

Comments: <br/>Quarantine instructions for this supply chain consignment item.<br/>Quarantine instructions for this piece of logistics transport equipment.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:TransportEquipment](#TransportEquipment)


<h1 id="MaximumQuantity">MaximumQuantity</h1>

Type: rdf:Property

Comments: The maximum quantity in a range for which the trade price applies.

Domains: 

[edi3:Price](#Price)


<h1 id="ConditionTypeTransportServiceConditionCode">ConditionTypeTransportServiceConditionCode</h1>

Type: rdf:Property

Comments: A code specifying a type of condition for this transport service, such as a contract or carriage condition.

Domains: 

[edi3:Service](#Service)


<h1 id="ReverseBilledQuantity">ReverseBilledQuantity</h1>

Type: rdf:Property

Comments: The reverse billed quantity, at line level, for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="EndToEndIdentificationIdentifier">EndToEndIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The unique identifier for the end-to-end processing of this trade settlement payment, such as an identifier assigned by an initiating party to unambiguously identify the transaction.

Domains: 

[edi3:Payment](#Payment)


<h1 id="ProportionalConstituentPercent">ProportionalConstituentPercent</h1>

Type: rdf:Property

Comments: The percentage presence of the material within the goods for this material goods characteristic.

Domains: 

[edi3:GoodsCharacteristic](#GoodsCharacteristic)


<h1 id="LogoAssociatedSpecifiedBinaryFile">LogoAssociatedSpecifiedBinaryFile</h1>

Type: rdf:Property

Comments: A file containing a specified binary representation of a logo associated with this trade party.

Domains: 

[edi3:Party](#Party)


<h1 id="CanadianPaymentsAssociationIdentificationIdentifier">CanadianPaymentsAssociationIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique Canadian Payments Association Routing Number identifier for this debtor financial institution.<br/>The unique Canadian Payments Association Routing Number identifier for this creditor financial institution.<br/>

Domains: 

[edi3:FinancialInstitution](#FinancialInstitution)


<h1 id="RequestedDeliverySupplyChainEvent">RequestedDeliverySupplyChainEvent</h1>

Type: rdf:Property

Comments: <br/>A delivery event, at header level, requested for this trade delivery.<br/>A delivery event, at line level, requested for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="DispositionReferencedDocument">DispositionReferencedDocument</h1>

Type: rdf:Property

Comments: A disposition document referenced in this supply chain inventory.

Domains: 

[edi3:Inventory](#Inventory)


<h1 id="ContentLayerQuantity">ContentLayerQuantity</h1>

Type: rdf:Property

Comments: The number of content layers that are or may be packaged with this supply chain packaging, such as the number of layers of product on a pallet.

Domains: 

[edi3:Packaging](#Packaging)


<h1 id="RussianCentralBankIdentificationIdentifier">RussianCentralBankIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique Russian Central Bank Identification Code identifier for this debtor financial institution.<br/>The unique Russian Central Bank Identification Code identifier for this creditor financial institution.<br/>

Domains: 

[edi3:FinancialInstitution](#FinancialInstitution)


<h1 id="CommunicationCapabilityCode">CommunicationCapabilityCode</h1>

Type: rdf:Property

Comments: The code specifying the communication capability of this monitoring IOT device.

Domains: 

[edi3:IOTDevice](#IOTDevice)


<h1 id="TransitDirectionTransportMeansDirectionCode">TransitDirectionTransportMeansDirectionCode</h1>

Type: rdf:Property

Comments: The code specifying the transit direction of this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="LoadingLogisticsLocation">LoadingLogisticsLocation</h1>

Type: rdf:Property

Comments: The logistics location where the supply chain consignment is loaded.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="AdditionalApplicableReferencedProduct">AdditionalApplicableReferencedProduct</h1>

Type: rdf:Property

Comments: A referenced product additionally applicable with this supply chain trade line item.

Domains: 

[edi3:TradeLineItem](#TradeLineItem)


<h1 id="RecyclingDescriptionCode">RecyclingDescriptionCode</h1>

Type: rdf:Property

Comments: A code describing recycling in these disposal instructions.

Domains: 

[edi3:Instructions](#Instructions)


<h1 id="PreviousOrderReferencedDocument">PreviousOrderReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>The previous order document referenced in this line trade agreement.<br/>The previous order document referenced in this header trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="BuyerRequisitionerTradeParty">BuyerRequisitionerTradeParty</h1>

Type: rdf:Property

Comments: <br/>A party who is a buyer requisitioner in this line trade agreement.<br/>A party who is a buyer requisitioner in this header trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="RequiredLaneLengthLinearUnitMeasure">RequiredLaneLengthLinearUnitMeasure</h1>

Type: rdf:Property

Comments: <br/>The measure of the external length required in a lane for this logistics transport means.<br/>The measure of the length required in a lane for this piece of logistics transport equipment.<br/>

Domains: 

[edi3:TransportEquipment](#TransportEquipment)
[edi3:TransportMeans](#TransportMeans)


<h1 id="TypeTransportMeansTypeCode">TypeTransportMeansTypeCode</h1>

Type: rdf:Property

Comments: <br/>The code specifying the type of referenced transport means [Reference UNECE Recommendation 28].<br/>The code specifying the type of logistics means of transport (Reference UNECE Recommendation 28).<br/>

Domains: 

[edi3:TransportMeans](#TransportMeans)


<h1 id="CharacteristicText">CharacteristicText</h1>

Type: rdf:Property

Comments: <br/>The characteristics, expressed as text, of a referenced piece of logistics transport equipment, such as size and type.<br/>The textual description of the characteristics, i.e. size and type, of this piece of attached transport equipment.<br/>The characteristic or characteristics, expressed as text, of a piece of logistics transport equipment, such as its size and type.<br/>The textual description of the characteristics, i.e. size and type, of this piece of associated transport equipment.<br/>

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="AuthorizationText">AuthorizationText</h1>

Type: rdf:Property

Comments: An authorization, expressed as text, for this financing request document.

Domains: 

[edi3:Document](#Document)


<h1 id="NetIncludingTaxesLineTotalAmount">NetIncludingTaxesLineTotalAmount</h1>

Type: rdf:Property

Comments: <br/>A monetary value of the total of all line amounts, including line level allowances and charges and including line level taxes, being reported in this trade settlement line monetary summation.<br/>A monetary value of the total of all line amounts, including line level allowances and charges and including line level taxes, being reported in this trade settlement header monetary summation.<br/>

Domains: 

[edi3:MonetarySummation](#MonetarySummation)


<h1 id="TelexUniversalCommunication">TelexUniversalCommunication</h1>

Type: rdf:Property

Comments: Telegraphy (Telex) communication information for this trade contact.

Domains: 

[edi3:Contact](#Contact)


<h1 id="TransportEquipmentRiskRelatedCode">TransportEquipmentRiskRelatedCode</h1>

Type: rdf:Property

Comments: A code specifying a transport equipment related risk for this logistics risk analysis result.

Domains: 

[edi3:RiskAnalysisResult](#RiskAnalysisResult)


<h1 id="NextInvoiceDateTime">NextInvoiceDateTime</h1>

Type: rdf:Property

Comments: A date, time, date time or other date time value of a next invoice or invoices in this header trade settlement.

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="DeductedAdjustmentAmount">DeductedAdjustmentAmount</h1>

Type: rdf:Property

Comments: The monetary value of the adjustment deducted for this cross-border customs valuation.

Domains: 

[edi3:CustomsValuation](#CustomsValuation)


<h1 id="ApplicableDisposalInstructions">ApplicableDisposalInstructions</h1>

Type: rdf:Property

Comments: <br/>Disposal instructions for this supply chain packaging.<br/>Disposal instructions applicable to this trade product.<br/>

Domains: 

[edi3:Packaging](#Packaging)
[edi3:Product](#Product)


<h1 id="ExportExitDateTime">ExportExitDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time or other date time value when this supply chain consignment will exit, or has exited from the last port, airport, or border post of the country of export.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="DueInAvailableQuantity">DueInAvailableQuantity</h1>

Type: rdf:Property

Comments: <br/>The due in available quantity, at header level, for this trade delivery.<br/>The due in available quantity, at line level, for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="OperatingTradeParty">OperatingTradeParty</h1>

Type: rdf:Property

Comments: The party that operates this piece of logistics transport equipment.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="ApplicableTradeAllowanceCharge">ApplicableTradeAllowanceCharge</h1>

Type: rdf:Property

Comments: An allowance or charge applicable to this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="ConditionSealConditionCode">ConditionSealConditionCode</h1>

Type: rdf:Property

Comments: A code specifying a condition of this logistics seal.

Domains: 

[edi3:Seal](#Seal)


<h1 id="DamageRemarksText">DamageRemarksText</h1>

Type: rdf:Property

Comments: Damage remarks, expressed as text, for this supply chain consignment item.

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)


<h1 id="LineOneText">LineOneText</h1>

Type: rdf:Property

Comments: <br/>The first free form line, expressed as text, of this financial institution address.<br/>The first free form line, expressed as text, of this trade address.<br/>

Domains: 

[edi3:Address](#Address)


<h1 id="ReleaseRestrictionText">ReleaseRestrictionText</h1>

Type: rdf:Property

Comments: The release restriction, expressed as text, for this piece of logistics transport equipment.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="SpecifiedEmployerIdentity">SpecifiedEmployerIdentity</h1>

Type: rdf:Property

Comments: An employer identity specified for this contact person.

Domains: 

[edi3:Person](#Person)


<h1 id="StageTransportMovementStageCode">StageTransportMovementStageCode</h1>

Type: rdf:Property

Comments: The code specifying the stage of this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="AppliedSpecifiedPeriod">AppliedSpecifiedPeriod</h1>

Type: rdf:Property

Comments: A period during which this chemical treatment is applied.

Domains: 

[edi3:ChemicalTreatment](#ChemicalTreatment)


<h1 id="DeliveryOrderFulfilmentLeadTimeDurationUnitMeasure">DeliveryOrderFulfilmentLeadTimeDurationUnitMeasure</h1>

Type: rdf:Property

Comments: The measure of the expected time interval between the receipt of an order and its delivery fulfilment according to this line trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="QuotationCurrencyCurrencyCode">QuotationCurrencyCurrencyCode</h1>

Type: rdf:Property

Comments: The code specifying the quotation currency for this header trade settlement.

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="EntryCustomsOfficeSpecifiedLogisticsLocation">EntryCustomsOfficeSpecifiedLogisticsLocation</h1>

Type: rdf:Property

Comments: The location of the specified customs office at which the goods subject to this cross-border regulatory procedure, enter the customs territory of entry.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="PickUpTradeParty">PickUpTradeParty</h1>

Type: rdf:Property

Comments: The pick-up trade party for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="AssociatedMeasurement">AssociatedMeasurement</h1>

Type: rdf:Property

Comments: A measurement associated with this document clause.

Domains: 

[edi3:Clause](#Clause)


<h1 id="AmendmentPurposeCode">AmendmentPurposeCode</h1>

Type: rdf:Property

Comments: A code specifying a purpose of an amendment to this exchanged document.

Domains: 

[edi3:Document](#Document)


<h1 id="MaximumStackabilityWeightApplicableWeightUnitMeasure">MaximumStackabilityWeightApplicableWeightUnitMeasure</h1>

Type: rdf:Property

Comments: The maximum stackability weight applicable to these handling instructions.

Domains: 

[edi3:Instructions](#Instructions)


<h1 id="SettingTransportSettingTemperature">SettingTransportSettingTemperature</h1>

Type: rdf:Property

Comments: <br/>A temperature setting for this piece of referenced logistics transport equipment, such as storage temperature or operational temperature.<br/>A temperature setting for this piece of logistics transport equipment, such as storage temperature or operational temperature.<br/>

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="AppliedTradeAllowanceCharge">AppliedTradeAllowanceCharge</h1>

Type: rdf:Property

Comments: An allowance or charge applied to the trade price.

Domains: 

[edi3:Price](#Price)


<h1 id="AdditionalTransportInstructions">AdditionalTransportInstructions</h1>

Type: rdf:Property

Comments: Additional instructions for this piece of logistics transport equipment.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="FamilyNameText">FamilyNameText</h1>

Type: rdf:Property

Comments: <br/>The family name expressed as text for this distinct chemical.<br/>The name, expressed as text, that this contact person shares with members of his/her family.<br/>A family name, expressed as text, for this transport person.<br/>

Domains: 

[edi3:Chemical](#Chemical)
[edi3:Person](#Person)


<h1 id="InformationText">InformationText</h1>

Type: rdf:Property

Comments: <br/>Information, expressed as text, for this trade settlement payment means.<br/>Information, expressed as text, for this document status.<br/>Information, expressed as text, for this exchanged document.<br/>Information, expressed as text, for this supply chain consignment item.<br/>Information, expressed as text, for this referenced document.<br/>Information, expressed as text, for this referenced logistics package.<br/>Information, expressed as text, for this logistics transport movement.<br/>Information, expressed as text, concerning the transport of these dangerous goods.<br/>Information, expressed as text, for this document authentication.<br/>Information, expressed as text, for this supply chain consignment.<br/>Information, expressed as text, for this logistics package.<br/>Information, expressed as text, in this section segment.<br/>Information, expressed as text, for this piece of logistics transport equipment.<br/>Information, expressed as text, for this transport service.<br/>Information, expressed as text, for this supply chain trade transaction.<br/>

Domains: 

[edi3:Status](#Status)
[edi3:TransportEquipment](#TransportEquipment)
[edi3:Service](#Service)
[edi3:Consignment](#Consignment)
[edi3:Document](#Document)
[edi3:Segment](#Segment)
[edi3:PaymentMeans](#PaymentMeans)
[edi3:TradeTransaction](#TradeTransaction)
[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:Authentication](#Authentication)
[edi3:TransportMovement](#TransportMovement)
[edi3:Package](#Package)
[edi3:DangerousGoods](#DangerousGoods)


<h1 id="DrainedNetWeightMeasure">DrainedNetWeightMeasure</h1>

Type: rdf:Property

Comments: The measure of the drained net weight (mass) of this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="ConsigneeAgentTradeParty">ConsigneeAgentTradeParty</h1>

Type: rdf:Property

Comments: The party authorized to act for or on behalf of the consignee for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="LandlineTelephoneUniversalCommunication">LandlineTelephoneUniversalCommunication</h1>

Type: rdf:Property

Comments: Landline telephone communication information for this transport person.

Domains: 

[edi3:Person](#Person)


<h1 id="LastRegisteredYearDateTime">LastRegisteredYearDateTime</h1>

Type: rdf:Property

Comments: The last year in which this legal registration was registered.

Domains: 

[edi3:Registration](#Registration)


<h1 id="SubordinateTradeCountrySubDivision">SubordinateTradeCountrySubDivision</h1>

Type: rdf:Property

Comments: <br/>A subordinate country sub-division within this trade country sub-division.<br/>A trade country sub-division that is subordinate to this trade country, such as a state, a county, a canton, a province.<br/>

Domains: 

[edi3:CountrySubDivision](#CountrySubDivision)
[edi3:Country](#Country)


<h1 id="BIMSpecifiedDocumentContextParameter">BIMSpecifiedDocumentContextParameter</h1>

Type: rdf:Property

Comments: A Business Information Master (BIM) context parameter specified for this exchanged document context.

Domains: 

[edi3:Context](#Context)


<h1 id="FunctionTypeLocationFunctionCode">FunctionTypeLocationFunctionCode</h1>

Type: rdf:Property

Comments: The code specifying the function type of this trade country sub-division.

Domains: 

[edi3:CountrySubDivision](#CountrySubDivision)


<h1 id="CarrierAcceptanceLogisticsLocation">CarrierAcceptanceLogisticsLocation</h1>

Type: rdf:Property

Comments: <br/>The location where this referenced supply chain consignment will be or has been accepted by the carrier.<br/>The location where this supply chain consignment will be, or has been, accepted by the carrier.<br/>

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="IncludedSpecifiedGeographicalPoint">IncludedSpecifiedGeographicalPoint</h1>

Type: rdf:Property

Comments: The geographical point included in this geographical feature.

Domains: 

[edi3:GeographicalFeature](#GeographicalFeature)


<h1 id="SubWorksTypeCode">SubWorksTypeCode</h1>

Type: rdf:Property

Comments: A code specifying the type of sub works, such as land surveying or information technology consulting, for this procuring project.

Domains: 

[edi3:Project](#Project)


<h1 id="ActualDiscountAmount">ActualDiscountAmount</h1>

Type: rdf:Property

Comments: A monetary value of the actual discount in these trade payment discount terms.

Domains: 

[edi3:PaymentDiscountTerms](#PaymentDiscountTerms)


<h1 id="SelfAssessedBasisQuantity">SelfAssessedBasisQuantity</h1>

Type: rdf:Property

Comments: The quantity on which this trade related tax, levy or duty has been calculated on a self-assessment basis.

Domains: 

[edi3:Tax](#Tax)


<h1 id="CoordinateReferenceDimensionText">CoordinateReferenceDimensionText</h1>

Type: rdf:Property

Comments: <br/>A coordinate reference dimension, expressed as text, for this specified direct position list.<br/>A coordinate reference dimension, expressed as text, for this specified direct position.<br/>

Domains: 

[edi3:DirectPosition](#DirectPosition)
[edi3:DirectPositionList](#DirectPositionList)


<h1 id="BarcodeIdentificationIdentifier">BarcodeIdentificationIdentifier</h1>

Type: rdf:Property

Comments: A unique barcode identifier for this supply chain trade line item.

Domains: 

[edi3:TradeLineItem](#TradeLineItem)


<h1 id="BuyerSellerRelationshipIndicator">BuyerSellerRelationshipIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not there is a relationship between the buyer and the seller, such as a financial relationship, for this cross-border customs valuation.

Domains: 

[edi3:CustomsValuation](#CustomsValuation)


<h1 id="IncludedSpecifiedCircle">IncludedSpecifiedCircle</h1>

Type: rdf:Property

Comments: A circle included in this specified geographical feature.

Domains: 

[edi3:GeographicalFeature](#GeographicalFeature)


<h1 id="MinimumValueTemperatureUnitMeasure">MinimumValueTemperatureUnitMeasure</h1>

Type: rdf:Property

Comments: <br/>The measure of the lowest value of this transport setting temperature, such as a minimum temperature value of four degrees Celsius.<br/>The measure of the lowest value of a range for this specified temperature, such as a minimum temperature value of four degrees Celsius.<br/>

Domains: 

[edi3:Temperature](#Temperature)


<h1 id="CopyIssuedQuantity">CopyIssuedQuantity</h1>

Type: rdf:Property

Comments: The number of copies issued of this exchanged document.

Domains: 

[edi3:Document](#Document)


<h1 id="WorksTypeCode">WorksTypeCode</h1>

Type: rdf:Property

Comments: A code specifying the type of work, such as surveying or consulting, for this procuring project.

Domains: 

[edi3:Project](#Project)


<h1 id="SpecifiedProprietaryIdentity">SpecifiedProprietaryIdentity</h1>

Type: rdf:Property

Comments: <br/>A proprietary identity specified for this creditor financial institution.<br/>A proprietary identity specified for this trade party.<br/>A proprietary Identity specified for this person.<br/>A proprietary identity specified for this requesting party.<br/>

Domains: 

[edi3:Party](#Party)
[edi3:FinancialInstitution](#FinancialInstitution)
[edi3:Identity](#Identity)


<h1 id="InvoiceAssociatedReferencedDocument">InvoiceAssociatedReferencedDocument</h1>

Type: rdf:Property

Comments: An invoice document associated to this supply chain trade line item.

Domains: 

[edi3:TradeLineItem](#TradeLineItem)


<h1 id="ReturnedQuantity">ReturnedQuantity</h1>

Type: rdf:Property

Comments: The quantity, at line level, returned for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="PatternCode">PatternCode</h1>

Type: rdf:Property

Comments: The code specifying the pattern of this label section.

Domains: 

[edi3:Section](#Section)


<h1 id="IncludedTradeProductGroup">IncludedTradeProductGroup</h1>

Type: rdf:Property

Comments: A product group included in this supply chain trade transaction.

Domains: 

[edi3:TradeTransaction](#TradeTransaction)


<h1 id="ExplosiveCompatibilityGroupCode">ExplosiveCompatibilityGroupCode</h1>

Type: rdf:Property

Comments: The code specifying the explosive compatibility group for these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="RemainingRequestedQuantity">RemainingRequestedQuantity</h1>

Type: rdf:Property

Comments: <br/>The remaining quantity, at header level, requested for this trade delivery.<br/>The remaining quantity, at line level, requested for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="RequiredCertificationTestSpecificationReport">RequiredCertificationTestSpecificationReport</h1>

Type: rdf:Property

Comments: A report of a certification test and its attributes that is required for this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="BorderCrossingLogisticsTransportMovement">BorderCrossingLogisticsTransportMovement</h1>

Type: rdf:Property

Comments: A border crossing logistics transport movement for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="ProviderTradeParty">ProviderTradeParty</h1>

Type: rdf:Property

Comments: <br/>The provider party for this monitoring IOT device.<br/>The trade party providing this document authentication.<br/>

Domains: 

[edi3:Authentication](#Authentication)
[edi3:IOTDevice](#IOTDevice)


<h1 id="InspectionSupplyChainEvent">InspectionSupplyChainEvent</h1>

Type: rdf:Property

Comments: <br/>The inspection event for this trade product instance.<br/>A supply chain inspection event at this logistics location.<br/>

Domains: 

[edi3:ProductInstance](#ProductInstance)
[edi3:Location](#Location)


<h1 id="ApplicableTransportDangerousGoods">ApplicableTransportDangerousGoods</h1>

Type: rdf:Property

Comments: <br/>The transport dangerous goods details, at line level, applicable to this trade delivery.<br/>Dangerous goods transport details applicable to this referenced supply chain consignment item.<br/>Transport dangerous goods information applicable to these logistics regulated goods.<br/>Dangerous goods applicable to the transport of this supply chain consignment.<br/>Dangerous goods transport details applicable to this supply chain consignment item.<br/>Transport dangerous goods information applicable for this trade product.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:TradeDelivery](#TradeDelivery)
[edi3:Consignment](#Consignment)
[edi3:Product](#Product)
[edi3:RegulatedGoods](#RegulatedGoods)


<h1 id="AffixedLogisticsSeal">AffixedLogisticsSeal</h1>

Type: rdf:Property

Comments: <br/>A seal affixed to this piece of referenced logistics transport equipment.<br/>A seal affixed to this piece of logistics transport equipment.<br/>

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="ActualQuantity">ActualQuantity</h1>

Type: rdf:Property

Comments: <br/>The actual quantity for this work item quantity analysis.<br/>The actual quantity of items in this trade product instance.<br/>The actual quantity added or subtracted as a result of this financial adjustment.<br/>The actual quantity in this supply chain supply plan.<br/>The actual quantity added or subtracted as a result of this delivery adjustment.<br/>

Domains: 

[edi3:Adjustment](#Adjustment)
[edi3:SupplyPlan](#SupplyPlan)
[edi3:QuantityAnalysis](#QuantityAnalysis)
[edi3:ProductInstance](#ProductInstance)


<h1 id="QValueNumeric">QValueNumeric</h1>

Type: rdf:Property

Comments: The number of the Q-Value for these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="FromDeliveryLifeSpanDurationUnitMeasure">FromDeliveryLifeSpanDurationUnitMeasure</h1>

Type: rdf:Property

Comments: The measure of the life span of this trade product from date of delivery.

Domains: 

[edi3:Product](#Product)


<h1 id="BuildingNameText">BuildingNameText</h1>

Type: rdf:Property

Comments: The name, expressed as text, of a building, a house or other structure on a street at this trade address.

Domains: 

[edi3:Address](#Address)


<h1 id="HaulageArrangementTransportEquipmentHaulageArrangementsCode">HaulageArrangementTransportEquipmentHaulageArrangementsCode</h1>

Type: rdf:Property

Comments: The code specifying the arrangement for the haulage of this piece of logistics transport equipment.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="TransportMeansSecurityOfficerTransportPerson">TransportMeansSecurityOfficerTransportPerson</h1>

Type: rdf:Property

Comments: The officer responsible for the security of the means of transport used for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="CargoFacilityRelatedLogisticsLocation">CargoFacilityRelatedLogisticsLocation</h1>

Type: rdf:Property

Comments: The location of a cargo facility related to this transport event.

Domains: 

[edi3:Event](#Event)


<h1 id="ToleranceMeasure">ToleranceMeasure</h1>

Type: rdf:Property

Comments: <br/>The measure of the tolerance of this calibrated measurement.<br/>The measure of the tolerance of this geographical coordinate source system.<br/>

Domains: 

[edi3:Measurement](#Measurement)
[edi3:CoordinateSourceSystem](#CoordinateSourceSystem)


<h1 id="ProcurementTradeParty">ProcurementTradeParty</h1>

Type: rdf:Property

Comments: <br/>The procurement party for this line trade agreement.<br/>The procurement party for this header trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="PageIdentifier">PageIdentifier</h1>

Type: rdf:Property

Comments: The identifier of the page for this referenced document.

Domains: 

[edi3:Document](#Document)


<h1 id="SpecifiedAuthoritativeSignatoryPerson">SpecifiedAuthoritativeSignatoryPerson</h1>

Type: rdf:Property

Comments: A person specified to sign on behalf of this trade party.

Domains: 

[edi3:Party](#Party)


<h1 id="PhysicalLogisticsPackage">PhysicalLogisticsPackage</h1>

Type: rdf:Property

Comments: A physical logistics package for this supply chain trade line item.

Domains: 

[edi3:TradeLineItem](#TradeLineItem)


<h1 id="PreviousOrderChangeReferencedDocument">PreviousOrderChangeReferencedDocument</h1>

Type: rdf:Property

Comments: The previous order change document referenced in this header trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="RoundingAmount">RoundingAmount</h1>

Type: rdf:Property

Comments: A monetary value of a rounding amount being applied in this trade settlement header monetary summation.

Domains: 

[edi3:MonetarySummation](#MonetarySummation)


<h1 id="UKSortCodeIdentificationIdentifier">UKSortCodeIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique United Kingdom (UK) Sort Code identifier as assigned by the UK Payment Association (APACS) for this debtor financial institution.<br/>The unique United Kingdom (UK) Sort Code identifier as assigned by the UK Payment Association (APACS) for this creditor financial institution.<br/>

Domains: 

[edi3:FinancialInstitution](#FinancialInstitution)


<h1 id="NotifiedTradeParty">NotifiedTradeParty</h1>

Type: rdf:Property

Comments: <br/>A party to be notified about this logistics transport movement.<br/>A party who has been or will be notified about this referenced supply chain consignment.<br/>A party who has been or will be notified about this piece of logistics transport equipment.<br/>A party who has been or will be notified about this supply chain consignment.<br/>

Domains: 

[edi3:TransportEquipment](#TransportEquipment)
[edi3:Consignment](#Consignment)
[edi3:TransportMovement](#TransportMovement)


<h1 id="BEIIdentificationIdentifier">BEIIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique Business Entity Identifier (BEI) as defined by ISO 9362 (Banking telecommunication messages, Bank Identifier Codes) for this requesting party.<br/>The Business Entity Identifier (BEI) as defined by ISO 9362 (Banking telecommunication messages, Bank Identifier Codes) for this financial identity.<br/>

Domains: 

[edi3:Party](#Party)
[edi3:Identity](#Identity)


<h1 id="ValuationBasisAmount">ValuationBasisAmount</h1>

Type: rdf:Property

Comments: The monetary value of the basis on which the valuation is, or will be, calculated for this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="UsageSpecifiedPreference">UsageSpecifiedPreference</h1>

Type: rdf:Property

Comments: The specified preference for the usage of this telecommunication method.

Domains: 

[edi3:Communication](#Communication)


<h1 id="MarketingDescriptionText">MarketingDescriptionText</h1>

Type: rdf:Property

Comments: A marketing description, expressed as text, for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="IssuerTradeParty">IssuerTradeParty</h1>

Type: rdf:Property

Comments: <br/>The trade related party that issues this referenced document.<br/>The party that issues this exchanged document.<br/>

Domains: 

[edi3:Document](#Document)


<h1 id="SalesSpecifiedTradeAccountingAccount">SalesSpecifiedTradeAccountingAccount</h1>

Type: rdf:Property

Comments: <br/>A sales accounting account specified for this header trade settlement.<br/>A sales accounting account specified for this line trade settlement.<br/>

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="AbsolutePresenceWeightMeasure">AbsolutePresenceWeightMeasure</h1>

Type: rdf:Property

Comments: The weight measure of the absolute presence of this material goods characteristic.

Domains: 

[edi3:GoodsCharacteristic](#GoodsCharacteristic)


<h1 id="DespatchAdviceReferencedDocument">DespatchAdviceReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>The despatch advice document, at line level, referenced for this trade delivery.<br/>The despatch advice document, at header level, referenced for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="NominalGrossVolumeVolumeUnitMeasure">NominalGrossVolumeVolumeUnitMeasure</h1>

Type: rdf:Property

Comments: The measure of the nominal gross volume of this referenced logistics package.

Domains: 

[edi3:Package](#Package)


<h1 id="FirstArrivalTransportEvent">FirstArrivalTransportEvent</h1>

Type: rdf:Property

Comments: The first arrival event for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="UPICIdentificationIdentifier">UPICIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique Universal Payment Identification Code (UPIC) identifier used by the New York Clearing House for this financing financial account.<br/>The unique Universal Payment Identification Code (UPIC) identifier used by the New York Clearing House for this debtor financial account.<br/>The unique Universal Payment Identification Code (UPIC) identifier used by the New York Clearing House for this creditor financial account.<br/>

Domains: 

[edi3:FinancialAccount](#FinancialAccount)


<h1 id="SocialSecurityIdentificationIdentifier">SocialSecurityIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The social security identifier for this person.

Domains: 

[edi3:Identity](#Identity)


<h1 id="DueInReturnedQuantity">DueInReturnedQuantity</h1>

Type: rdf:Property

Comments: The due in returned quantity, at line level, for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="ReceivedFormattedDateTime">ReceivedFormattedDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time, or other date time value when information related to this transport event was received, from the perspective of the receiver.

Domains: 

[edi3:Event](#Event)


<h1 id="EmbarkationLogisticsLocation">EmbarkationLogisticsLocation</h1>

Type: rdf:Property

Comments: An embarkation location for this transport person.

Domains: 

[edi3:Person](#Person)


<h1 id="UnitQuantity">UnitQuantity</h1>

Type: rdf:Property

Comments: <br/>The number of units of attached transport equipment.<br/>The number of units for this transport event.<br/>The number of units of this type of logistics transport equipment.<br/>The number of units of this type of referenced logistics transport equipment.<br/>A unit quantity of this referenced product.<br/>A number of units for this supply chain event.<br/>The number of units for this communication event.<br/>

Domains: 

[edi3:TransportEquipment](#TransportEquipment)
[edi3:Event](#Event)
[edi3:Product](#Product)


<h1 id="TariffQuantity">TariffQuantity</h1>

Type: rdf:Property

Comments: <br/>A tariff quantity for this cross-border regulatory procedure.<br/>The tariff quantity in this supply chain consignment item.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="ReExportTradeCountry">ReExportTradeCountry</h1>

Type: rdf:Property

Comments: A re-export country for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="LocalNumberText">LocalNumberText</h1>

Type: rdf:Property

Comments: The communication number, expressed as text and not including country access code or the area number code, for this telecommunication.

Domains: 

[edi3:Communication](#Communication)


<h1 id="IBANIdentificationIdentifier">IBANIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique International Bank Account Number (IBAN) identifier for this financing financial account.<br/>The unique International Bank Account Number (IBAN) identifier for this debtor financial account.<br/>The unique International Bank Account Number (IBAN) identifier for this creditor financial account.<br/>

Domains: 

[edi3:FinancialAccount](#FinancialAccount)


<h1 id="AppliedProductHandlingProcess">AppliedProductHandlingProcess</h1>

Type: rdf:Property

Comments: A product handling process applied to this trade product instance, such as manufacturing or storage.

Domains: 

[edi3:ProductInstance](#ProductInstance)


<h1 id="TotalAllowanceChargeAmount">TotalAllowanceChargeAmount</h1>

Type: rdf:Property

Comments: <br/>A monetary value of a total allowance and charge reported in this trade settlement header monetary summation.<br/>A monetary value of a total allowance and charge reported in this trade settlement line monetary summation.<br/>The total monetary value of all allowances and charges for this supply chain consignment.<br/>

Domains: 

[edi3:Consignment](#Consignment)
[edi3:MonetarySummation](#MonetarySummation)


<h1 id="OperatorNationalityTradeCountry">OperatorNationalityTradeCountry</h1>

Type: rdf:Property

Comments: The country of nationality of the operator of this logistics means of transport.

Domains: 

[edi3:TransportMeans](#TransportMeans)


<h1 id="TradedParcelQuantity">TradedParcelQuantity</h1>

Type: rdf:Property

Comments: The number of traded parcels of cargo being transported in this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="AccreditingBodyNameText">AccreditingBodyNameText</h1>

Type: rdf:Property

Comments: The name of the accrediting body, expressed as text, for this certified accreditation.

Domains: 

[edi3:Accreditation](#Accreditation)


<h1 id="ContainedAssociatedTransportEquipment">ContainedAssociatedTransportEquipment</h1>

Type: rdf:Property

Comments: A piece of transport equipment contained within this piece of logistics transport equipment, such as a pallet.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="RelevantGeometryTypeText">RelevantGeometryTypeText</h1>

Type: rdf:Property

Comments: The type of geometry, expressed as text, relevant for this geographical object characteristic.

Domains: 

[edi3:GeographicalObjectCharacteristic](#GeographicalObjectCharacteristic)


<h1 id="ComponentApplicableReferencedProduct">ComponentApplicableReferencedProduct</h1>

Type: rdf:Property

Comments: A referenced component product applicable for this supply chain trade line item.

Domains: 

[edi3:TradeLineItem](#TradeLineItem)


<h1 id="PackagingSupplyChainEvent">PackagingSupplyChainEvent</h1>

Type: rdf:Property

Comments: The packaging event for this trade product instance.

Domains: 

[edi3:ProductInstance](#ProductInstance)


<h1 id="ClosingBookDueDateTime">ClosingBookDueDateTime</h1>

Type: rdf:Property

Comments: <br/>A date, time, date time or other date time value of a closing book due date for this trade settlement payment.<br/>The date, time, date time or other date time value when the book closing is due for this header trade settlement.<br/>

Domains: 

[edi3:Payment](#Payment)
[edi3:TradeSettlement](#TradeSettlement)


<h1 id="GlobalIdentificationIdentifier">GlobalIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique global identifier for this exchanged document.<br/>A unique global identifier for this referenced product.<br/>The unique global identifier for this logistics package.<br/>A globally unique identifier of this trade party.<br/>A unique global identifier for this referenced document.<br/>The global identifier for this referenced logistics package.<br/>A unique global identifier for this trade product.<br/>A global identifier for this supply chain consignment item.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:Party](#Party)
[edi3:Product](#Product)
[edi3:Package](#Package)
[edi3:Document](#Document)


<h1 id="CarrierAcceptanceFormattedDateTime">CarrierAcceptanceFormattedDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time or other date time value when this referenced supply chain consignment will be, or has been, accepted by the carrier.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="CatalogueInformationProviderTradeParty">CatalogueInformationProviderTradeParty</h1>

Type: rdf:Property

Comments: <br/>The party that provides catalogue information for this line trade agreement.<br/>The party that provides catalogue information for this header trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="SpanishDomesticInterbankingIdentificationIdentifier">SpanishDomesticInterbankingIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique Spanish Domestic Interbanking Code identifier as assigned by the Centro de Cooperacion Interbancaria (CCI) for this debtor financial institution.<br/>The unique Spanish Domestic Interbanking Code identifier as assigned by the Centro de Cooperacion Interbancaria (CCI) for this creditor financial institution.<br/>

Domains: 

[edi3:FinancialInstitution](#FinancialInstitution)


<h1 id="LegalClassificationCode">LegalClassificationCode</h1>

Type: rdf:Property

Comments: The code specifying the legal classification of this organization, such as Incorporated (Inc), Limited Liability Corporation (LLC) or non-profit.

Domains: 

[edi3:Organization](#Organization)


<h1 id="ImportTradeCountry">ImportTradeCountry</h1>

Type: rdf:Property

Comments: The import country for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="CommonNameText">CommonNameText</h1>

Type: rdf:Property

Comments: <br/>A common name, expressed as text, for this trade product.<br/>A common name, expressed as text, for this distinct chemical.<br/>

Domains: 

[edi3:Chemical](#Chemical)
[edi3:Product](#Product)


<h1 id="SecondTypeExtensionCode">SecondTypeExtensionCode</h1>

Type: rdf:Property

Comments: The code used as a second extension to the type code for further specifying the type of supply chain consignment item.

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)


<h1 id="FirstAgentSpecifiedCreditorFinancialInstitution">FirstAgentSpecifiedCreditorFinancialInstitution</h1>

Type: rdf:Property

Comments: The creditor financial institution specified as the first agent in this financing request document.

Domains: 

[edi3:Document](#Document)


<h1 id="SpecifiedLogisticsPackage">SpecifiedLogisticsPackage</h1>

Type: rdf:Property

Comments: <br/>A logistics package specified for these transported dangerous goods.<br/>A logistics package specified for this supply chain trade transaction.<br/>A logistics package, at line level, specified for this trade delivery.<br/>

Domains: 

[edi3:TradeTransaction](#TradeTransaction)
[edi3:TradeDelivery](#TradeDelivery)
[edi3:DangerousGoods](#DangerousGoods)


<h1 id="CommitmentLevelCode">CommitmentLevelCode</h1>

Type: rdf:Property

Comments: <br/>A code specifying a commitment level in these supply chain forecast terms.<br/>The code specifying the commitment level for this supply chain supply plan, such as fabrication or raw material.<br/>

Domains: 

[edi3:SupplyPlan](#SupplyPlan)
[edi3:ForecastTerms](#ForecastTerms)


<h1 id="PresentationSpecifiedBinaryFile">PresentationSpecifiedBinaryFile</h1>

Type: rdf:Property

Comments: A binary file presentation specified for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="GoodsPhysicalStateTypeText">GoodsPhysicalStateTypeText</h1>

Type: rdf:Property

Comments: A type, expressed as text, for the physical state of the goods, at header level, for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="TestNameText">TestNameText</h1>

Type: rdf:Property

Comments: A test name, expressed as text, for this certification test specification report.

Domains: 

[edi3:TestSpecificationReport](#TestSpecificationReport)


<h1 id="SeriesEndIdentifier">SeriesEndIdentifier</h1>

Type: rdf:Property

Comments: The unique identifier of the end of a series of logistics labels.

Domains: 

[edi3:Label](#Label)


<h1 id="AdditionalInstructionIndicator">AdditionalInstructionIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not there is an additional instruction for this supply chain packaging.

Domains: 

[edi3:Packaging](#Packaging)


<h1 id="CustomsIdentificationIdentifier">CustomsIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>A unique identifier, for customs purposes, for this exchanged document.<br/>The identifier, for customs purposes, for this referenced supply chain consignment.<br/>A unique identifier, for customs purposes, for this consignment.<br/>

Domains: 

[edi3:Consignment](#Consignment)
[edi3:Document](#Document)


<h1 id="SellerAssignedIdentificationIdentifier">SellerAssignedIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique seller assigned identifier for this trade product.<br/>The unique seller assigned identifier for this referenced product.<br/>

Domains: 

[edi3:Product](#Product)


<h1 id="AvailableSupplyChainInventory">AvailableSupplyChainInventory</h1>

Type: rdf:Property

Comments: Inventory available, at line level, for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="ApplicableTradeTax">ApplicableTradeTax</h1>

Type: rdf:Property

Comments: <br/>A tax applicable to this line trade settlement.<br/>A tax, levy or duty applicable to this cross-border regulatory procedure.<br/>A tax applicable to this subordinate line trade settlement.<br/>A tax applicable to this header trade settlement.<br/>The tax applicable to this payment trade settlement.<br/>

Domains: 

[edi3:TradeSettlement](#TradeSettlement)
[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="ManifestOnboardIndicator">ManifestOnboardIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not the manifest for this logistics transport movement is onboard.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="EndItemTypeCode">EndItemTypeCode</h1>

Type: rdf:Property

Comments: A code specifying a type of end item for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="OccurrenceDateTime">OccurrenceDateTime</h1>

Type: rdf:Property

Comments: <br/>The date time of the occurrence of this applied chemical treatment.<br/>A date, time, date time, or other date time value of an occurrence of this supply chain event.<br/>The date, time, date time, or other date time value of an occurrence of this payment balance out.<br/>The date, time, date time, or other date time value of an occurrence of this communication event.<br/>The date, time, date time, or other date time value of an occurrence of this header balance out.<br/>A date, time, date time, or other date time of an occurrence in this supply chain schedule.<br/>

Domains: 

[edi3:ChemicalTreatment](#ChemicalTreatment)
[edi3:Schedule](#Schedule)
[edi3:Event](#Event)
[edi3:BalanceOut](#BalanceOut)


<h1 id="RequesterTradeParty">RequesterTradeParty</h1>

Type: rdf:Property

Comments: <br/>A trade party requesting this transport service.<br/>A trade party requesting this referenced transport service.<br/>

Domains: 

[edi3:Service](#Service)


<h1 id="RequestedDespatchSupplyChainEvent">RequestedDespatchSupplyChainEvent</h1>

Type: rdf:Property

Comments: <br/>A despatch event, at line level, requested for this trade delivery.<br/>A despatch event, at header level, requested for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="GivenNameText">GivenNameText</h1>

Type: rdf:Property

Comments: <br/>The name, expressed as text, given to this contact person, usually by parents at birth.<br/>A given name, expressed as text, for this transport person.<br/>

Domains: 

[edi3:Person](#Person)


<h1 id="ManifestAssociatedReferencedDocument">ManifestAssociatedReferencedDocument</h1>

Type: rdf:Property

Comments: A referenced manifest document associated to this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="IncludedSpecifiedGeographicalMultiCurve">IncludedSpecifiedGeographicalMultiCurve</h1>

Type: rdf:Property

Comments: The geographical multi-curve included in this geographical feature.

Domains: 

[edi3:GeographicalFeature](#GeographicalFeature)


<h1 id="RequestedOccurrenceDateTime">RequestedOccurrenceDateTime</h1>

Type: rdf:Property

Comments: The requested date, time, date time, or other date time value of the occurrence of this transport event.

Domains: 

[edi3:Event](#Event)


<h1 id="PassengerQuantity">PassengerQuantity</h1>

Type: rdf:Property

Comments: The number of passengers for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="ExportLicenceControlClassificationIdentifier">ExportLicenceControlClassificationIdentifier</h1>

Type: rdf:Property

Comments: The identifier of the export licence classification for control purposes relevant to this cross-border regulatory procedure, such as per the Wassenaar agreement concerning trade in weapons and dual-use goods and technologies.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="OriginalOrderReferencedDocument">OriginalOrderReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>The original order document referenced in this header trade agreement.<br/>The original order document referenced in this line trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="ChargeApportionMethodCode">ChargeApportionMethodCode</h1>

Type: rdf:Property

Comments: The code specifying the method of the apportion of charges for this cross-border customs valuation.

Domains: 

[edi3:CustomsValuation](#CustomsValuation)


<h1 id="ConferenceCode">ConferenceCode</h1>

Type: rdf:Property

Comments: The code specifying the conference for this logistics means of transport.

Domains: 

[edi3:TransportMeans](#TransportMeans)


<h1 id="QuotationRequestResponseReferencedDocument">QuotationRequestResponseReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>The quotation request response document referenced in this line trade agreement.<br/>The quotation request response document referenced in this header trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="ExpiryDateTime">ExpiryDateTime</h1>

Type: rdf:Property

Comments: <br/>The date, time, date time, or other date time value when this product certificate expires.<br/>The date, time, date time, or other date time value of expiry of the items contained in the trade product instance.<br/>

Domains: 

[edi3:ProductInstance](#ProductInstance)
[edi3:Certificate](#Certificate)


<h1 id="DespatchNoteAssociatedReferencedDocument">DespatchNoteAssociatedReferencedDocument</h1>

Type: rdf:Property

Comments: A despatch note associated with this logistics package.

Domains: 

[edi3:Package](#Package)


<h1 id="BasisAmount">BasisAmount</h1>

Type: rdf:Property

Comments: <br/>The monetary value used as the basis in calculating the applied tax.<br/>A monetary value used as a basis to calculate the discount in these trade payment discount terms.<br/>A monetary value used as a basis to calculate these trade payment penalty terms.<br/>The monetary value that is the basis on which the applied allowance charge is calculated.<br/>A monetary value used as the basis on which this trade related tax, levy or duty is calculated.<br/>The monetary value that is the basis on which this trade allowance charge is calculated.<br/>

Domains: 

[edi3:AllowanceCharge](#AllowanceCharge)
[edi3:PaymentPenaltyTerms](#PaymentPenaltyTerms)
[edi3:Tax](#Tax)
[edi3:PaymentDiscountTerms](#PaymentDiscountTerms)


<h1 id="ModeText">ModeText</h1>

Type: rdf:Property

Comments: The mode, expressed as text, of this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="GoodsPhysicalStateDescriptionCode">GoodsPhysicalStateDescriptionCode</h1>

Type: rdf:Property

Comments: The code specifying a description for the physical state of the goods, at header level, for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="TransportEquipmentQuantity">TransportEquipmentQuantity</h1>

Type: rdf:Property

Comments: <br/>The number of pieces of transport equipment for this logistics transport movement.<br/>A number of pieces of transport equipment, such as containers or similar unit load devices, in this supply chain consignment.<br/>

Domains: 

[edi3:Consignment](#Consignment)
[edi3:TransportMovement](#TransportMovement)


<h1 id="AssociatedReferencedDocument">AssociatedReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>An associated document referenced for this trade price.<br/>A referenced document associated with this supply chain trade transaction, such as the purchase order, invoice or packing list.<br/>A referenced document associated with this supply chain consignment, such as the certificate of origin or dangerous goods note.<br/>A referenced document associated with this piece of logistics transport equipment.<br/>A document associated with this line trade settlement.<br/>A referenced document associated with this referenced supply chain consignment item.<br/>An associated document referenced for this trade related currency exchange.<br/>A referenced document associated with this exchanged declaration.<br/>A referenced document associated with this supply chain consignment item.<br/>

Domains: 

[edi3:TradeTransaction](#TradeTransaction)
[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:TradeSettlement](#TradeSettlement)
[edi3:Price](#Price)
[edi3:TransportEquipment](#TransportEquipment)
[edi3:Consignment](#Consignment)
[edi3:Declaration](#Declaration)
[edi3:CurrencyExchange](#CurrencyExchange)


<h1 id="LatestReceivedSignalDateTime">LatestReceivedSignalDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time or other date time value of the latest received signal for this monitoring IOT device, from the perspective of the receiver.

Domains: 

[edi3:IOTDevice](#IOTDevice)


<h1 id="TypePriceTypeCode">TypePriceTypeCode</h1>

Type: rdf:Property

Comments: The code specifying the type of trade price.

Domains: 

[edi3:Price](#Price)


<h1 id="SouthAfricanNCCIdentificationIdentifier">SouthAfricanNCCIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique South African National Clearing Code (NCC) identifier as assigned by the South African Bankers Services Company Ltd. (BankServ) for this debtor financial institution.<br/>The unique South African National Clearing Code (NCC) identifier as assigned by the South African Bankers Services Company Ltd. (BankServ) for this creditor financial institution.<br/>

Domains: 

[edi3:FinancialInstitution](#FinancialInstitution)


<h1 id="CHIPSParticipantIdentificationIdentifier">CHIPSParticipantIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique (United States) Clearing House Interbank Payment System (CHIPS) Participant Identifier (ID) as assigned by the New York Clearing House for this debtor financial institution.<br/>The unique (United States) Clearing House Interbank Payment System (CHIPS) Participant Identifier (ID) as assigned by the New York Clearing House for this creditor financial institution.<br/>

Domains: 

[edi3:FinancialInstitution](#FinancialInstitution)


<h1 id="TransportIndexNumeric">TransportIndexNumeric</h1>

Type: rdf:Property

Comments: The transport index number of this radioactive material.

Domains: 

[edi3:Material](#Material)


<h1 id="CalculationBasisText">CalculationBasisText</h1>

Type: rdf:Property

Comments: The basis, expressed as text, on which this logistics service charge is to be calculated, such as by volume or per unit.

Domains: 

[edi3:ServiceCharge](#ServiceCharge)


<h1 id="ApplicableReferencedStandard">ApplicableReferencedStandard</h1>

Type: rdf:Property

Comments: <br/>The referenced standard that is applicable to this product classification.<br/>The referenced standard that is applicable to this product characteristic.<br/>

Domains: 

[edi3:Classification](#Classification)
[edi3:Characteristic](#Characteristic)


<h1 id="CategoryTaxCategoryCode">CategoryTaxCategoryCode</h1>

Type: rdf:Property

Comments: The code specifying the category to which this trade related tax, levy or duty applies, such as codes for "Exempt from Tax", "Standard Rate", "Free Export Item - Tax Not Charged" [Reference United Nations Code List (UNCL) 5305].

Domains: 

[edi3:Tax](#Tax)


<h1 id="SpecifiedTradeAllowanceCharge">SpecifiedTradeAllowanceCharge</h1>

Type: rdf:Property

Comments: <br/>An allowance or charge specified for this line trade settlement.<br/>An allowance or charge specified for this header trade settlement.<br/>

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="HumidityPercent">HumidityPercent</h1>

Type: rdf:Property

Comments: The percent of the humidity (moisture content) within this piece of logistics transport equipment.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="ValiditySpecifiedPeriod">ValiditySpecifiedPeriod</h1>

Type: rdf:Property

Comments: <br/>A specified period for which this trade price is valid.<br/>The period of time during which this government registration is valid.<br/>A specific validity period for this logistics status.<br/>A specified validity period for this document status.<br/>

Domains: 

[edi3:Status](#Status)
[edi3:Price](#Price)
[edi3:Registration](#Registration)


<h1 id="LowerPartOrangeHazardPlacardIdentifier">LowerPartOrangeHazardPlacardIdentifier</h1>

Type: rdf:Property

Comments: The unique lower part of the orange hazard placard identifier for these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="RepresentationTypeCode">RepresentationTypeCode</h1>

Type: rdf:Property

Comments: The code specifying the type of representation of this document authentication, such as direct or indirect.

Domains: 

[edi3:Authentication](#Authentication)


<h1 id="EconomicOrderQuantity">EconomicOrderQuantity</h1>

Type: rdf:Property

Comments: <br/>The economic order quantity, at line level, for this trade delivery.<br/>The economic order quantity for this line trade agreement.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)
[edi3:TradeAgreement](#TradeAgreement)


<h1 id="TitleTitleCode">TitleTitleCode</h1>

Type: rdf:Property

Comments: The code specifying the title of this contact person, such as Ms., Doctor, Mister.

Domains: 

[edi3:Person](#Person)


<h1 id="PackingInstructionTypeCode">PackingInstructionTypeCode</h1>

Type: rdf:Property

Comments: The code specifying a type of packing instruction for these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="HaulageHaulageInstructions">HaulageHaulageInstructions</h1>

Type: rdf:Property

Comments: Haulage instructions for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="LowDispersibleInformationText">LowDispersibleInformationText</h1>

Type: rdf:Property

Comments: Information, expressed as text, describing the low dispersion properties of this radioactive material.

Domains: 

[edi3:Material](#Material)


<h1 id="AcceptedTransactionOriginalTotalAmount">AcceptedTransactionOriginalTotalAmount</h1>

Type: rdf:Property

Comments: An original total monetary value of accepted transactions in this financing summary document.

Domains: 

[edi3:Document](#Document)


<h1 id="CollectionIndicator">CollectionIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not this specified geographical feature is a collection of features.

Domains: 

[edi3:GeographicalFeature](#GeographicalFeature)


<h1 id="ProductGroupIdentifier">ProductGroupIdentifier</h1>

Type: rdf:Property

Comments: A unique identifier for a product group for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="MatchingCommunicationEvent">MatchingCommunicationEvent</h1>

Type: rdf:Property

Comments: A matching event for this communication pairing.

Domains: 

[edi3:Pairing](#Pairing)


<h1 id="ApplicablePercent">ApplicablePercent</h1>

Type: rdf:Property

Comments: The percent of trade tax applicable, such as to an object or an activity.

Domains: 

[edi3:Tax](#Tax)


<h1 id="CompositionDescriptionText">CompositionDescriptionText</h1>

Type: rdf:Property

Comments: The textual description of the composition of this radioactive material.

Domains: 

[edi3:Material](#Material)


<h1 id="SalePriceConditionIndicator">SalePriceConditionIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not there is a condition imposed on the sale price of the goods for this cross-border customs valuation.

Domains: 

[edi3:CustomsValuation](#CustomsValuation)


<h1 id="DurationMeasure">DurationMeasure</h1>

Type: rdf:Property

Comments: A measure of the length of time for this specified time period such as hours, days, weeks, months, years.

Domains: 

[edi3:Period](#Period)


<h1 id="LoadingTransportEvent">LoadingTransportEvent</h1>

Type: rdf:Property

Comments: <br/>The loading event during which goods will be or have been loaded into or onto the means of transport used for this logistics transport movement.<br/>The loading event for this piece of logistics transport equipment.<br/>

Domains: 

[edi3:TransportEquipment](#TransportEquipment)
[edi3:TransportMovement](#TransportMovement)


<h1 id="ResidenceCountryCountryIdentifier">ResidenceCountryCountryIdentifier</h1>

Type: rdf:Property

Comments: The identifier of the residence country of this contact person.

Domains: 

[edi3:Person](#Person)


<h1 id="ApplicableHeaderTradeSettlement">ApplicableHeaderTradeSettlement</h1>

Type: rdf:Property

Comments: The trade settlement header applicable to this supply chain trade transaction.

Domains: 

[edi3:TradeTransaction](#TradeTransaction)


<h1 id="MinimumProductOrderableQuantity">MinimumProductOrderableQuantity</h1>

Type: rdf:Property

Comments: The minimum product orderable quantity for this line trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="ThirdSignatoryDocumentAuthentication">ThirdSignatoryDocumentAuthentication</h1>

Type: rdf:Property

Comments: The third signature, also known as the second counter signature, that has been authenticated on this exchanged document indicating where appropriate the authentication party.

Domains: 

[edi3:Document](#Document)


<h1 id="TechnicalNameText">TechnicalNameText</h1>

Type: rdf:Property

Comments: A technical name, expressed as text, for these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="AdditionalReasonText">AdditionalReasonText</h1>

Type: rdf:Property

Comments: Information, expressed as text, related to the reason for this validation status.

Domains: 

[edi3:Status](#Status)


<h1 id="SpecifiedPersonIdentity">SpecifiedPersonIdentity</h1>

Type: rdf:Property

Comments: The person identity specified for this contact person.

Domains: 

[edi3:Person](#Person)


<h1 id="ResultText">ResultText</h1>

Type: rdf:Property

Comments: A result, expressed as text, reported in this certification test specification report.

Domains: 

[edi3:TestSpecificationReport](#TestSpecificationReport)


<h1 id="ReferenceReferencedDocument">ReferenceReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>Other documents referenced by this exchanged document.<br/>A document referenced by this acknowledgement document.<br/>A document referenced for this supply chain trade line item.<br/>

Domains: 

[edi3:TradeLineItem](#TradeLineItem)
[edi3:Document](#Document)


<h1 id="DeclarationLodgementLogisticsLocation">DeclarationLodgementLogisticsLocation</h1>

Type: rdf:Property

Comments: The location at which a declaration has been lodged for this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="SpecifiedLegalOrganization">SpecifiedLegalOrganization</h1>

Type: rdf:Property

Comments: The legally constituted organization specified for this trade party.

Domains: 

[edi3:Party](#Party)


<h1 id="RequestedQuantity">RequestedQuantity</h1>

Type: rdf:Property

Comments: <br/>The quantity, at header level, requested for this trade delivery.<br/>The quantity, at line level, requested for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="CargoDescriptionText">CargoDescriptionText</h1>

Type: rdf:Property

Comments: The textual description of the cargo for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="ApplicableTradeCurrencyExchange">ApplicableTradeCurrencyExchange</h1>

Type: rdf:Property

Comments: <br/>The trade related currency exchange applicable to this cross-border customs valuation.<br/>A currency exchange applicable to this supply chain consignment.<br/>The applicable currency exchange for this cross-border regulatory procedure.<br/>

Domains: 

[edi3:CustomsValuation](#CustomsValuation)
[edi3:RegulatoryProcedure](#RegulatoryProcedure)
[edi3:Consignment](#Consignment)


<h1 id="AddedAdjustmentAmount">AddedAdjustmentAmount</h1>

Type: rdf:Property

Comments: The monetary value of the adjustment added for this cross-border customs valuation.

Domains: 

[edi3:CustomsValuation](#CustomsValuation)


<h1 id="ProductValueExcludingTobaccoTaxInformationAmount">ProductValueExcludingTobaccoTaxInformationAmount</h1>

Type: rdf:Property

Comments: A monetary value which constitutes the total product value, excluding tobacco tax, stated for information purposes in this trade settlement header monetary summation.

Domains: 

[edi3:MonetarySummation](#MonetarySummation)


<h1 id="DeliverySupplyChainSchedule">DeliverySupplyChainSchedule</h1>

Type: rdf:Property

Comments: A supply chain delivery schedule, at line level, for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="SpecifiedFinancingRequestResultDocument">SpecifiedFinancingRequestResultDocument</h1>

Type: rdf:Property

Comments: The financing request result document specified for this instalment payment.

Domains: 

[edi3:Payment](#Payment)


<h1 id="TransportMovementStatusTransportEquipmentMovementStatusCode">TransportMovementStatusTransportEquipmentMovementStatusCode</h1>

Type: rdf:Property

Comments: The code specifying the transport movement status for this piece of logistics transport equipment, such as for export, for import, or for transhipment.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="CatalogueSubscriptionReferencedDocument">CatalogueSubscriptionReferencedDocument</h1>

Type: rdf:Property

Comments: A catalogue subscription document referenced in this header trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="ValueText">ValueText</h1>

Type: rdf:Property

Comments: <br/>The value, expressed as text, of this document context parameter.<br/>The value, expressed as text, of this control setting parameter.<br/>The value, expressed as text, of this operational parameter.<br/>A value, expressed as text, for this product characteristic.<br/>

Domains: 

[edi3:Characteristic](#Characteristic)
[edi3:Parameter](#Parameter)


<h1 id="SpecifiedDeliveryAdjustment">SpecifiedDeliveryAdjustment</h1>

Type: rdf:Property

Comments: A delivery adjustment, at line level, specified for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="PlannedReleaseSupplyChainEvent">PlannedReleaseSupplyChainEvent</h1>

Type: rdf:Property

Comments: The release event, at header level, planned for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="SpecifiedSubordinateLineTradeDelivery">SpecifiedSubordinateLineTradeDelivery</h1>

Type: rdf:Property

Comments: The delivery specified for this subordinate trade line item.

Domains: 

[edi3:TradeLineItem](#TradeLineItem)


<h1 id="SpecialSpecifiedTransportInstructions">SpecialSpecifiedTransportInstructions</h1>

Type: rdf:Property

Comments: Special transport instructions specified for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="SpecifiedPaymentTradeSettlement">SpecifiedPaymentTradeSettlement</h1>

Type: rdf:Property

Comments: A trade settlement payment specified for this trade settlement payment.

Domains: 

[edi3:Payment](#Payment)


<h1 id="GrossWeightSpecifiedWeightUnitMeasure">GrossWeightSpecifiedWeightUnitMeasure</h1>

Type: rdf:Property

Comments: The gross weight measure specified in this exchanged declaration.

Domains: 

[edi3:Declaration](#Declaration)


<h1 id="DebitFormattedDateTime">DebitFormattedDateTime</h1>

Type: rdf:Property

Comments: The debit date, time, date time, or other date time value of this financial booking.

Domains: 

[edi3:Booking](#Booking)


<h1 id="MaximumWidthLinearUnitMeasure">MaximumWidthLinearUnitMeasure</h1>

Type: rdf:Property

Comments: The maximum width measure for this logistics convoy.

Domains: 

[edi3:Convoy](#Convoy)


<h1 id="UnitCalculatedPrice">UnitCalculatedPrice</h1>

Type: rdf:Property

Comments: A unit calculated price for this basic work item.

Domains: 

[edi3:WorkItem](#WorkItem)


<h1 id="TypeCode">TypeCode</h1>

Type: rdf:Property

Comments: <br/>The code specifying the type of product characteristic condition.<br/>The code specifying the type of requesting party.<br/>The code specifying the type of this radioactive material.<br/>The code specifying the type of trade geopolitical region.<br/>A code specifying the type of valuation breakdown statement.<br/>The code specifying the type of procuring project, such as goods, works and service.<br/>A code specifying the type of supply chain event.<br/>A code specifying a type of measurement.<br/>The code specifying a type of parameter for this control setting parameter.<br/>A code specifying the type of stores inventory item.<br/>The code specifying the type of this specification response.<br/>A code specifying a type of specified personal effects.<br/>A code specifying the type of basic work item.<br/>The code specifying the type of this calculated emission.<br/>A code specifying the type of this legal registration.<br/>The code specifying the type of section segment.<br/>The code specifying the type of this product security tag.<br/>The code specifying the type of communication event.<br/>The code specifying the applied tax type such as VAT.<br/>A code specifying the type of trade party that is independent of its role.<br/>A code specifying a type of cross-border regulatory procedure.<br/>A code specifying the type of trade product.<br/>The code specifying a type of monitoring sensor.<br/>The code specifying the type of creditor financial account.<br/>The code specifying the type of debtor financial account.<br/>The code specifying the type of distinct chemical.<br/>A code specifying the type of supply chain schedule.<br/>A code specifying a type of OEM equipment.<br/>The code specifying the type of trade product feature.<br/>The code specifying the type of this operational parameter.<br/>The code specifying the type of specification query.<br/>The code specifying the type of financial institution address.<br/>The code specifying the type of work item quantity analysis.<br/>The code specifying a type of this specified range.<br/>A code specifying the type of calculated price.<br/>The code specifying the type of supply chain trade line item.<br/>The code specifying the type of transport event.<br/>A code specifying a type of government registration.<br/>A code specifying the type of this work item group.<br/>The code specifying the type of monitoring IOT device.<br/>The code specifying the type of this certified accreditation, such as a type of driving license.<br/>A code specifying a type of country sub-division for trade purposes.<br/>The code specifying the type of cross-border customs valuation.<br/>The code specifying the type of supply chain trade transaction.<br/>A code specifying a type of product characteristic.<br/>The code specifying the type of this trade settlement financial card, such as debit or credit.<br/>A code specifying the type of product certificate.<br/>The code specifying the type of this work item dimension.<br/>The code specifying the type of material goods characteristic.<br/>A code specifying a type of legally set up organization.<br/>A code specifying a type of transport waste material component.<br/>The code specifying the type of registered tax.<br/>

Domains: 

[edi3:Measurement](#Measurement)
[edi3:Organization](#Organization)
[edi3:Query](#Query)
[edi3:Address](#Address)
[edi3:PersonalEffects](#PersonalEffects)
[edi3:Emission](#Emission)
[edi3:Product](#Product)
[edi3:Tax](#Tax)
[edi3:WorkItem](#WorkItem)
[edi3:Feature](#Feature)
[edi3:BreakdownStatement](#BreakdownStatement)
[edi3:Segment](#Segment)
[edi3:TradeTransaction](#TradeTransaction)
[edi3:FinancialCard](#FinancialCard)
[edi3:Party](#Party)
[edi3:SecurityTag](#SecurityTag)
[edi3:MaterialComponent](#MaterialComponent)
[edi3:Registration](#Registration)
[edi3:Accreditation](#Accreditation)
[edi3:QuantityAnalysis](#QuantityAnalysis)
[edi3:GeopoliticalRegion](#GeopoliticalRegion)
[edi3:CountrySubDivision](#CountrySubDivision)
[edi3:GoodsCharacteristic](#GoodsCharacteristic)
[edi3:Condition](#Condition)
[edi3:CustomsValuation](#CustomsValuation)
[edi3:RegulatoryProcedure](#RegulatoryProcedure)
[edi3:Characteristic](#Characteristic)
[edi3:Material](#Material)
[edi3:Dimension](#Dimension)
[edi3:TradeLineItem](#TradeLineItem)
[edi3:Range](#Range)
[edi3:Response](#Response)
[edi3:Project](#Project)
[edi3:Chemical](#Chemical)
[edi3:Equipment](#Equipment)
[edi3:Price](#Price)
[edi3:FinancialAccount](#FinancialAccount)
[edi3:Schedule](#Schedule)
[edi3:Parameter](#Parameter)
[edi3:Event](#Event)
[edi3:Inventory](#Inventory)
[edi3:Sensor](#Sensor)
[edi3:IOTDevice](#IOTDevice)
[edi3:Certificate](#Certificate)


<h1 id="LatestReceivedGeographicalCoordinate">LatestReceivedGeographicalCoordinate</h1>

Type: rdf:Property

Comments: The latest geographical coordinates received by this monitoring IOT device, from the perspective of the receiver.

Domains: 

[edi3:IOTDevice](#IOTDevice)


<h1 id="SellerOrderReferencedDocument">SellerOrderReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>The seller generated order document referenced in this subordinate line trade agreement.<br/>The seller generated order document referenced in this header trade agreement.<br/>The seller generated order document referenced in this line trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="TypeTaxTypeCode">TypeTaxTypeCode</h1>

Type: rdf:Property

Comments: The code specifying the type of trade related tax, levy or duty, such as a code for a Value Added Tax (VAT) [Reference United Nations Code List (UNCL) 5153].

Domains: 

[edi3:Tax](#Tax)


<h1 id="SubstitutedReferencedProduct">SubstitutedReferencedProduct</h1>

Type: rdf:Property

Comments: A referenced product substituted for this supply chain trade line item.

Domains: 

[edi3:TradeLineItem](#TradeLineItem)


<h1 id="TotalQuantityWorkItemQuantityAnalysis">TotalQuantityWorkItemQuantityAnalysis</h1>

Type: rdf:Property

Comments: An analysis of the total quantity for this basic work item.

Domains: 

[edi3:WorkItem](#WorkItem)


<h1 id="DeclarantAssignedDeclarationIdentifier">DeclarantAssignedDeclarationIdentifier</h1>

Type: rdf:Property

Comments: The declarant assigned identifier of a declaration for this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="ExportCustomsOfficeSpecifiedLogisticsLocation">ExportCustomsOfficeSpecifiedLogisticsLocation</h1>

Type: rdf:Property

Comments: The location of the specified customs office which is responsible for export formalities for the goods which are subject to this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="TerminalOperatorAssignedIdentificationIdentifier">TerminalOperatorAssignedIdentificationIdentifier</h1>

Type: rdf:Property

Comments: A unique identifier for this logistics transport movement as assigned by a terminal operator.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="ContentUnitQuantity">ContentUnitQuantity</h1>

Type: rdf:Property

Comments: The number of content units of this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="FormattedReceivedFormattedDateTime">FormattedReceivedFormattedDateTime</h1>

Type: rdf:Property

Comments: The formatted date or date time value when an advance payment has been received.

Domains: 

[edi3:Payment](#Payment)


<h1 id="ReportedTransportWasteMaterial">ReportedTransportWasteMaterial</h1>

Type: rdf:Property

Comments: Waste material reported for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="AcceptanceDateTime">AcceptanceDateTime</h1>

Type: rdf:Property

Comments: <br/>The date, time, date time, or other date time value for the acceptance of this exchanged document.<br/>The date, time, date time, or other date time value of the acceptance of this referenced document.<br/>

Domains: 

[edi3:Document](#Document)


<h1 id="FileNameText">FileNameText</h1>

Type: rdf:Property

Comments: The file name, expressed as text, of this specified binary file.

Domains: 

[edi3:BinaryFile](#BinaryFile)


<h1 id="ProperShippingNameText">ProperShippingNameText</h1>

Type: rdf:Property

Comments: The proper shipping name, expressed as text, for these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="CreditorReferenceTypeText">CreditorReferenceTypeText</h1>

Type: rdf:Property

Comments: A creditor reference type, expressed as text, for this header trade settlement.

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="StaySpecifiedReferencedTransportEvent">StaySpecifiedReferencedTransportEvent</h1>

Type: rdf:Property

Comments: A stay specified for this referenced transport event.

Domains: 

[edi3:Event](#Event)


<h1 id="AllowanceTotalAmount">AllowanceTotalAmount</h1>

Type: rdf:Property

Comments: <br/>A monetary value of the total of all allowance amounts being reported in this trade settlement header monetary summation.<br/>A monetary value of the total of all allowance amounts being reported in this trade settlement line monetary summation.<br/>

Domains: 

[edi3:MonetarySummation](#MonetarySummation)


<h1 id="PaymentAmount">PaymentAmount</h1>

Type: rdf:Property

Comments: <br/>A monetary value of a payment for this header trade settlement.<br/>A monetary value of a payment for this line trade settlement.<br/>

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="StorageTransportEvent">StorageTransportEvent</h1>

Type: rdf:Property

Comments: <br/>A storage event for this supply chain consignment.<br/>A storage event specifying when and where this piece of logistics transport equipment will be, or has been, stored.<br/>

Domains: 

[edi3:TransportEquipment](#TransportEquipment)
[edi3:Consignment](#Consignment)


<h1 id="IncludedProductContentUnitQuantity">IncludedProductContentUnitQuantity</h1>

Type: rdf:Property

Comments: The number of content units of products included in this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="InteriorSpecifiedLinearRing">InteriorSpecifiedLinearRing</h1>

Type: rdf:Property

Comments: An interior linear ring specified for this polygon.

Domains: 

[edi3:Polygon](#Polygon)


<h1 id="IncludedSpecifiedPolygon">IncludedSpecifiedPolygon</h1>

Type: rdf:Property

Comments: <br/>The polygon included in this geographical feature.<br/>A polygon included in this geographical multi-surface.<br/>The polygon included in this geographical surface.<br/>

Domains: 

[edi3:GeographicalFeature](#GeographicalFeature)
[edi3:GeographicalSurface](#GeographicalSurface)
[edi3:GeographicalMultiSurface](#GeographicalMultiSurface)


<h1 id="InformationTemperatureSettingInstructions">InformationTemperatureSettingInstructions</h1>

Type: rdf:Property

Comments: Informational instructions for achieving, maintaining, using or responding to this transport setting temperature.

Domains: 

[edi3:Temperature](#Temperature)


<h1 id="BreakdownWorkItemQuantityAnalysis">BreakdownWorkItemQuantityAnalysis</h1>

Type: rdf:Property

Comments: A quantity analysis breakdown of this work item quantity analysis.

Domains: 

[edi3:QuantityAnalysis](#QuantityAnalysis)


<h1 id="ResponseDateTime">ResponseDateTime</h1>

Type: rdf:Property

Comments: A date, time, date time, or other date time value of a response of the exchanged document.

Domains: 

[edi3:Document](#Document)


<h1 id="NilCustomsValueIndicator">NilCustomsValueIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not this supply chain consignment has a nil value for customs.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="ConsignmentSupplyChainInventory">ConsignmentSupplyChainInventory</h1>

Type: rdf:Property

Comments: Supply chain consignment inventory, at line level, for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="RetailValueExcludingTaxInformationAmount">RetailValueExcludingTaxInformationAmount</h1>

Type: rdf:Property

Comments: A monetary value which constitutes the retail value, excluding all duties and taxes, stated for information purposes in this trade settlement header monetary summation.

Domains: 

[edi3:MonetarySummation](#MonetarySummation)


<h1 id="SellerTaxRepresentativeTradeParty">SellerTaxRepresentativeTradeParty</h1>

Type: rdf:Property

Comments: The party acting as a tax representative for the seller for this header trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="ContractualDocumentClause">ContractualDocumentClause</h1>

Type: rdf:Property

Comments: <br/>A contractual clause of this exchanged document.<br/>A contractual document clause specified for this financing request document.<br/>A contractual clause of this referenced document.<br/>

Domains: 

[edi3:Document](#Document)


<h1 id="TransportContractRelatedReferencedDocument">TransportContractRelatedReferencedDocument</h1>

Type: rdf:Property

Comments: A transport contract document related to this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="DefaultLanguageCode">DefaultLanguageCode</h1>

Type: rdf:Property

Comments: The code specifying the default language for this valuation breakdown statement.

Domains: 

[edi3:BreakdownStatement](#BreakdownStatement)


<h1 id="PaymentMethodCode">PaymentMethodCode</h1>

Type: rdf:Property

Comments: The code specifying the method by which a payment may be made for this trade settlement payment means.

Domains: 

[edi3:PaymentMeans](#PaymentMeans)


<h1 id="TypeText">TypeText</h1>

Type: rdf:Property

Comments: <br/>A type, expressed as text for this transport route.<br/>The type, expressed as text, of this trade related tax, levy or duty.<br/>The type, expressed as text, of supply chain packaging.<br/>A type, expressed as text, of this referenced logistics package.<br/>The type, expressed as text, of this referenced transport means.<br/>The type, expressed as text, of this logistics means of transport.<br/>A type, expressed as text, for this trade price.<br/>The type, as expressed as text, of the logistics transport movement.<br/>A type, expressed as text, of this logistics package.<br/>

Domains: 

[edi3:Price](#Price)
[edi3:Packaging](#Packaging)
[edi3:Tax](#Tax)
[edi3:TransportMovement](#TransportMovement)
[edi3:Package](#Package)
[edi3:TransportMeans](#TransportMeans)
[edi3:Route](#Route)


<h1 id="BrandOwnerTradeParty">BrandOwnerTradeParty</h1>

Type: rdf:Property

Comments: The party that owns the brand of this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="RelatedBookingTypeText">RelatedBookingTypeText</h1>

Type: rdf:Property

Comments: The type of booking, expressed as text, related to this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="GrossWeightWeightUnitMeasure">GrossWeightWeightUnitMeasure</h1>

Type: rdf:Property

Comments: <br/>A measure of the gross weight (mass) of this supply chain consignment item which includes packaging but excludes any transport equipment.<br/>The measure of the gross weight (mass) of this piece of logistics transport equipment which is the weight (mass) including loaded goods, packing and transport equipment.<br/>The measure of the gross weight (mass) of this piece of referenced logistics transport equipment which is the weight (mass) including loaded goods, packing and transport equipment.<br/>The measure, at line level, of the gross weight (mass) of this line trade delivery.<br/>The measure of the gross weight (mass) of this referenced logistics package and its contents.<br/>The measure of the weight (mass) of these transported dangerous goods including packaging but excluding the transport equipment.<br/>The measure of the gross weight (mass) of this logistics means of transport including cargo, such as the measure of the overall size of a vessel determined in accordance with the provisions of the International Convention on Tonnage Measurement of Ships, 1969.<br/>A measure of the gross weight (mass) of this supply chain consignment which includes the weight of packaging but which excludes the weight of any transport equipment.<br/>A measure of the gross weight (mass) of this referenced supply chain consignment which includes the weight of packaging but which excludes the weight of any transport equipment.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:TransportEquipment](#TransportEquipment)
[edi3:TradeDelivery](#TradeDelivery)
[edi3:Consignment](#Consignment)
[edi3:Package](#Package)
[edi3:DangerousGoods](#DangerousGoods)
[edi3:TransportMeans](#TransportMeans)


<h1 id="ApplicableProductCharacteristicCondition">ApplicableProductCharacteristicCondition</h1>

Type: rdf:Property

Comments: A condition applicable to this product characteristic.

Domains: 

[edi3:Characteristic](#Characteristic)


<h1 id="PartialPaymentPercent">PartialPaymentPercent</h1>

Type: rdf:Property

Comments: A partial payment, expressed as a percent, in these trade payment terms.

Domains: 

[edi3:PaymentTerms](#PaymentTerms)


<h1 id="DiameterLinearUnitMeasure">DiameterLinearUnitMeasure</h1>

Type: rdf:Property

Comments: The measure of the diameter component for this spatial dimension.

Domains: 

[edi3:Dimension](#Dimension)


<h1 id="SpecifiedFinancialAdjustment">SpecifiedFinancialAdjustment</h1>

Type: rdf:Property

Comments: <br/>A financial adjustment specified for this line trade settlement.<br/>A financial adjustment specified for this header trade settlement.<br/>

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="UltimateShipToDeliveryFormattedDateTime">UltimateShipToDeliveryFormattedDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time, or other date time value, at header level, when this trade delivery is delivered to the ultimate ship to party.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="TotalInvoiceSpecifiedAmount">TotalInvoiceSpecifiedAmount</h1>

Type: rdf:Property

Comments: The total invoice monetary value specified in this exchanged declaration.

Domains: 

[edi3:Declaration](#Declaration)


<h1 id="EndPointURIUniversalCommunication">EndPointURIUniversalCommunication</h1>

Type: rdf:Property

Comments: The communication address of the end point URI for this trade party.

Domains: 

[edi3:Party](#Party)


<h1 id="SynchronizationDateTime">SynchronizationDateTime</h1>

Type: rdf:Property

Comments: A date, time, date time, or other date time value of a synchronization of the supply chain supply plan.

Domains: 

[edi3:SupplyPlan](#SupplyPlan)


<h1 id="ConditionDocumentStatusCode">ConditionDocumentStatusCode</h1>

Type: rdf:Property

Comments: The code specifying the condition of this document status.

Domains: 

[edi3:Status](#Status)


<h1 id="AltitudeMeasure">AltitudeMeasure</h1>

Type: rdf:Property

Comments: <br/>The measure of the altitude that reflects the vertical elevation of an object above a surface for this geographical coordinate (Reference ISO 6709).<br/>The measure of the altitude that reflects the vertical elevation of an object above a surface for this specified geographical coordinate (Reference ISO 6709).<br/>

Domains: 

[edi3:GeographicalCoordinate](#GeographicalCoordinate)


<h1 id="TypeCashAccountTypeCode">TypeCashAccountTypeCode</h1>

Type: rdf:Property

Comments: The code specifying the type of financing financial account.

Domains: 

[edi3:FinancialAccount](#FinancialAccount)


<h1 id="UsedDistinctChemical">UsedDistinctChemical</h1>

Type: rdf:Property

Comments: A chemical used during this applied chemical treatment.

Domains: 

[edi3:ChemicalTreatment](#ChemicalTreatment)


<h1 id="PhysicalGeographicalCoordinate">PhysicalGeographicalCoordinate</h1>

Type: rdf:Property

Comments: <br/>Geographical coordinate information for this logistics related location.<br/>Physical geographical coordinate information for this subordinate location.<br/>Physical geographical coordinate information for this subordinate of a subordinate location.<br/>

Domains: 

[edi3:Location](#Location)


<h1 id="ReasonText">ReasonText</h1>

Type: rdf:Property

Comments: <br/>A reason, expressed as text, for this financial adjustment.<br/>The reason, expressed as text, for this trade allowance charge.<br/>A reason, expressed as text, for this financing status.<br/>A reason, expressed as text, for this validation status.<br/>A reason, expressed as text, for this document status.<br/>A reason, expressed as text, for this delivery adjustment.<br/>A reason, expressed as text, for this cancellation status.<br/>A reason, expressed as text, for this logistics status.<br/>

Domains: 

[edi3:Status](#Status)
[edi3:Adjustment](#Adjustment)
[edi3:AllowanceCharge](#AllowanceCharge)


<h1 id="ExpiryFormattedDateTime">ExpiryFormattedDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time or other date time value when this certified accreditation expires.

Domains: 

[edi3:Accreditation](#Accreditation)


<h1 id="BuyerTradeParty">BuyerTradeParty</h1>

Type: rdf:Property

Comments: <br/>The buyer party for this line trade agreement.<br/>The buyer party for this header trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="PaymentMethodPaymentMethodCode">PaymentMethodPaymentMethodCode</h1>

Type: rdf:Property

Comments: <br/>The code specifying the payment method for this cross-border regulatory procedure, such as by deferred payment method.<br/>The code specifying the payment method for this trade related tax, levy or duty.<br/>

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)
[edi3:Tax](#Tax)


<h1 id="TransitReleaseCustomsOfficeSpecifiedLogisticsLocation">TransitReleaseCustomsOfficeSpecifiedLogisticsLocation</h1>

Type: rdf:Property

Comments: A location of a specified customs office at which the goods which are subject to this cross-border regulatory procedure are released from a customs transit regime.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="ExportTradeCountry">ExportTradeCountry</h1>

Type: rdf:Property

Comments: <br/>The export country for this supply chain consignment item.<br/>The export country for this supply chain consignment.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:Consignment](#Consignment)


<h1 id="TotalCollectChargeAmount">TotalCollectChargeAmount</h1>

Type: rdf:Property

Comments: The total monetary value of all freight and other service charges which are to be collected from the consignee at or after delivery for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="NetLineTotalAmount">NetLineTotalAmount</h1>

Type: rdf:Property

Comments: <br/>A monetary value of the total of all line amounts, including line level allowances and charges and excluding line level taxes, being reported in this trade settlement header monetary summation.<br/>A monetary value of the total of all line amounts, including line level allowances and charges and excluding line level taxes, being reported in this trade settlement line monetary summation.<br/>A monetary value of the net total of all line amounts, including line level allowances and charges and excluding line level taxes, being reported in this trade settlement payment monetary summation.<br/>

Domains: 

[edi3:MonetarySummation](#MonetarySummation)


<h1 id="PreviousRevisionIdentificationIdentifier">PreviousRevisionIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>An identifier for a previous revision of this referenced document.<br/>The unique identifier of the previous revision of this exchanged document.<br/>

Domains: 

[edi3:Document](#Document)


<h1 id="SpecifiedLogisticsServiceCharge">SpecifiedLogisticsServiceCharge</h1>

Type: rdf:Property

Comments: <br/>A logistics service charge specified for this header trade settlement.<br/>A logistics service charge specified for this line trade settlement.<br/>

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="ConsolidationTransportEvent">ConsolidationTransportEvent</h1>

Type: rdf:Property

Comments: A consolidation event specifying when and where this piece of logistics transport equipment will be, or has been, stuffed.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="CreditReasonText">CreditReasonText</h1>

Type: rdf:Property

Comments: A textual description of the reason for a credit being given in this header trade settlement.

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="PrePackagedIndicator">PrePackagedIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not this trade product is pre-packaged.

Domains: 

[edi3:Product](#Product)


<h1 id="LastRegisteredYearFormattedDateTime">LastRegisteredYearFormattedDateTime</h1>

Type: rdf:Property

Comments: The last registered year of this government registration.

Domains: 

[edi3:Registration](#Registration)


<h1 id="ServiceChargeApplicableTradeCurrencyExchange">ServiceChargeApplicableTradeCurrencyExchange</h1>

Type: rdf:Property

Comments: A currency exchange applicable to a service charge for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="PlannedStockQuantity">PlannedStockQuantity</h1>

Type: rdf:Property

Comments: The planned stock quantity for this supply chain inventory.

Domains: 

[edi3:Inventory](#Inventory)


<h1 id="LatitudeDirectionIndicator">LatitudeDirectionIndicator</h1>

Type: rdf:Property

Comments: <br/>The indication of whether the latitude compass direction from the Equator meridian to the meridian of a specific place is North (+) or South (-)  (Reference ISO 6709).<br/>The indication of whether the latitude compass direction from the Equator meridian to the meridian of a specific place for this specified geographical coordinate is North (+) or South (-).  (Reference ISO 6709).<br/>

Domains: 

[edi3:GeographicalCoordinate](#GeographicalCoordinate)


<h1 id="ScheduledArrivalRelatedDateTime">ScheduledArrivalRelatedDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time or other date time value of the scheduled arrival related to this transport event.

Domains: 

[edi3:Event](#Event)


<h1 id="TransportInformationNote">TransportInformationNote</h1>

Type: rdf:Property

Comments: A transport information note for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="FlashpointTemperatureMeasurement">FlashpointTemperatureMeasurement</h1>

Type: rdf:Property

Comments: A measurement of the flashpoint temperature of these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="DestroyedQuantity">DestroyedQuantity</h1>

Type: rdf:Property

Comments: The quantity, at line level, destroyed for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="BestBeforeDateTime">BestBeforeDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time, or other date time value before which it is best to consume the items contained in this trade product instance.

Domains: 

[edi3:ProductInstance](#ProductInstance)


<h1 id="UsedSignalSourceQuantity">UsedSignalSourceQuantity</h1>

Type: rdf:Property

Comments: The quantity of the used signal source of this geographical coordinate source system.

Domains: 

[edi3:CoordinateSourceSystem](#CoordinateSourceSystem)


<h1 id="ActualOccurrenceSpecifiedPeriod">ActualOccurrenceSpecifiedPeriod</h1>

Type: rdf:Property

Comments: The actual period of time during which this transport event occurred.

Domains: 

[edi3:Event](#Event)


<h1 id="PartIdentificationIdentifier">PartIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The identifier of a part of this referenced standard, such as a section or topic.

Domains: 

[edi3:Standard](#Standard)


<h1 id="GuaranteeCode">GuaranteeCode</h1>

Type: rdf:Property

Comments: <br/>The code specifying an undertaking given in cash, bond or as a written guarantee to ensure that an obligation will be fulfilled for this trade related tax, levy or duty.<br/>The code specifying an undertaking given in cash, bond or as a written guarantee to ensure that an obligation will be fulfilled for this cross-border regulatory procedure.<br/>

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)
[edi3:Tax](#Tax)


<h1 id="LongitudeDirectionIndicator">LongitudeDirectionIndicator</h1>

Type: rdf:Property

Comments: <br/>The indication of whether the longitude as a compass direction from the Greenwich meridian to the meridian of a specific place is East (+) or West (-) for this geographical coordinate (Reference ISO 6709).<br/>The indication of whether the longitude as a compass direction from the Greenwich meridian to the meridian of a specific place is East (+) or West (-) for this specified geographical coordinate. (Reference ISO 6709).<br/>

Domains: 

[edi3:GeographicalCoordinate](#GeographicalCoordinate)


<h1 id="PlannedPickUpSupplyChainEvent">PlannedPickUpSupplyChainEvent</h1>

Type: rdf:Property

Comments: <br/>The pick-up event, at header level, planned for this trade delivery.<br/>The pick-up event, at line level, planned for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="InstantMessagingUniversalCommunication">InstantMessagingUniversalCommunication</h1>

Type: rdf:Property

Comments: Instant messaging communication information for this trade contact.

Domains: 

[edi3:Contact](#Contact)


<h1 id="JurisdictionText">JurisdictionText</h1>

Type: rdf:Property

Comments: <br/>A jurisdiction, expressed as text, for this registered tax.<br/>A jurisdiction, expressed as text, to which this trade related tax, levy or duty applies.<br/>

Domains: 

[edi3:Tax](#Tax)


<h1 id="AgreementInformationText">AgreementInformationText</h1>

Type: rdf:Property

Comments: Agreement information, expressed as text, in this financing request document, such as a collection mandate.

Domains: 

[edi3:Document](#Document)


<h1 id="ChargeFreeQuantity">ChargeFreeQuantity</h1>

Type: rdf:Property

Comments: The quantity, at line level, free of charge, in this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="TransportSplitDescriptionText">TransportSplitDescriptionText</h1>

Type: rdf:Property

Comments: <br/>The textual description of the transport split of this referenced supply chain consignment across different transport means or transport equipment.<br/>The textual description of the transport split of this supply chain consignment across different transport means or transport equipment.<br/>

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="PaymentOfficeLogisticsLocation">PaymentOfficeLogisticsLocation</h1>

Type: rdf:Property

Comments: The location of an office at which a payment relevant to this cross-border regulatory procedure is made.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="SpecifiedProjectOrganization">SpecifiedProjectOrganization</h1>

Type: rdf:Property

Comments: The project organization, such as a business or government body, for this requesting party.

Domains: 

[edi3:Party](#Party)


<h1 id="ChargeCategoryCode">ChargeCategoryCode</h1>

Type: rdf:Property

Comments: The code specifying the category of charge for this logistics service charge.

Domains: 

[edi3:ServiceCharge](#ServiceCharge)


<h1 id="QuantityVariationTypeCode">QuantityVariationTypeCode</h1>

Type: rdf:Property

Comments: The code specifying the type of quantity variation, at line level, for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="StatementText">StatementText</h1>

Type: rdf:Property

Comments: The statement, expressed as text, for this document authentication.

Domains: 

[edi3:Authentication](#Authentication)


<h1 id="GroupingCentreTradeParty">GroupingCentreTradeParty</h1>

Type: rdf:Property

Comments: A grouping centre party for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="LetterOfCreditReferencedDocument">LetterOfCreditReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>The letter of credit document referenced in this header trade agreement.<br/>The letter of credit document referenced in this line trade agreement.<br/>The letter of credit document referenced in this header trade settlement.<br/>

Domains: 

[edi3:TradeSettlement](#TradeSettlement)
[edi3:TradeAgreement](#TradeAgreement)


<h1 id="MinusToleranceQuantity">MinusToleranceQuantity</h1>

Type: rdf:Property

Comments: The minus tolerance quantity from the planned or requested quantity in this supply chain supply plan.

Domains: 

[edi3:SupplyPlan](#SupplyPlan)


<h1 id="UtilizedLogisticsTransportEquipment">UtilizedLogisticsTransportEquipment</h1>

Type: rdf:Property

Comments: <br/>Logistics transport equipment utilized for this referenced supply chain consignment.<br/>Logistics transport equipment utilized for this supply chain consignment.<br/>

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="ResaleProductUnitMeasureCode">ResaleProductUnitMeasureCode</h1>

Type: rdf:Property

Comments: The code specifying the resale product unit of measure, such as kilogram or litre, for this trade line agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="CentreSpecifiedGeographicalPoint">CentreSpecifiedGeographicalPoint</h1>

Type: rdf:Property

Comments: The geographical point which defines the centre of this specified circle.

Domains: 

[edi3:Circle](#Circle)


<h1 id="PolishNationalClearingIdentificationIdentifier">PolishNationalClearingIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique Polish National Clearing Code identifier for this debtor financial institution.<br/>The unique Polish National Clearing Code identifier for this creditor financial institution.<br/>

Domains: 

[edi3:FinancialInstitution](#FinancialInstitution)


<h1 id="PassportIdentificationIdentifier">PassportIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The passport identifier for this person.

Domains: 

[edi3:Identity](#Identity)


<h1 id="TransportTransportService">TransportTransportService</h1>

Type: rdf:Property

Comments: A transport service for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="RemainingDeliveryTransportEvent">RemainingDeliveryTransportEvent</h1>

Type: rdf:Property

Comments: A delivery event for this remaining transport waste material component.

Domains: 

[edi3:MaterialComponent](#MaterialComponent)


<h1 id="CalculationBasisLogisticsChargeCalculationBasisCode">CalculationBasisLogisticsChargeCalculationBasisCode</h1>

Type: rdf:Property

Comments: The code specifying a basis on which this logistics service charge is to be calculated, such as by volume or per unit.

Domains: 

[edi3:ServiceCharge](#ServiceCharge)


<h1 id="ServiceProviderTradeParty">ServiceProviderTradeParty</h1>

Type: rdf:Property

Comments: A trade party providing services for this logistics means of transport.

Domains: 

[edi3:TransportMeans](#TransportMeans)


<h1 id="ChargeIndicator">ChargeIndicator</h1>

Type: rdf:Property

Comments: <br/>The indication of whether or not the applied allowance charge is a charge.<br/>The indication of whether or not the trade allowance charge is a charge.<br/>

Domains: 

[edi3:AllowanceCharge](#AllowanceCharge)


<h1 id="IdentificationFreightChargeTypeIdentifier">IdentificationFreightChargeTypeIdentifier</h1>

Type: rdf:Property

Comments: The unique identifier for this logistics service charge.

Domains: 

[edi3:ServiceCharge](#ServiceCharge)


<h1 id="UltimateShipToTradeParty">UltimateShipToTradeParty</h1>

Type: rdf:Property

Comments: <br/>The ultimate ship to party, at line level, for this trade delivery.<br/>The ultimate ship to party, at header level, for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="CustomerAssignedIdentificationIdentifier">CustomerAssignedIdentificationIdentifier</h1>

Type: rdf:Property

Comments: A unique customer assigned identifier for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="AllPackedInOneInformationText">AllPackedInOneInformationText</h1>

Type: rdf:Property

Comments: All packed in one information, expressed as text, for these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="PayeePartyCreditorFinancialAccount">PayeePartyCreditorFinancialAccount</h1>

Type: rdf:Property

Comments: A creditor financial account of the payee party for this trade settlement payment means.

Domains: 

[edi3:PaymentMeans](#PaymentMeans)


<h1 id="SpecifiedDocumentVersion">SpecifiedDocumentVersion</h1>

Type: rdf:Property

Comments: The document version specified for this document context parameter.

Domains: 

[edi3:Parameter](#Parameter)


<h1 id="IdentityCardIdentificationIdentifier">IdentityCardIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The identity card identifier for this person.

Domains: 

[edi3:Identity](#Identity)


<h1 id="MarkedSerialNumberIndicator">MarkedSerialNumberIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not this trade product is marked with a serial number.

Domains: 

[edi3:Product](#Product)


<h1 id="AssociatedDocumentLineDocument">AssociatedDocumentLineDocument</h1>

Type: rdf:Property

Comments: <br/>A document line associated with this line trade settlement.<br/>The document line associated with this trade line item.<br/>The document line associated with this supply chain trade transaction.<br/>

Domains: 

[edi3:TradeTransaction](#TradeTransaction)
[edi3:TradeSettlement](#TradeSettlement)
[edi3:TradeLineItem](#TradeLineItem)


<h1 id="TraderAssignedIdentificationIdentifier">TraderAssignedIdentificationIdentifier</h1>

Type: rdf:Property

Comments: A unique trader assigned identifier for this exchanged document.

Domains: 

[edi3:Document](#Document)


<h1 id="CreditNoteAmount">CreditNoteAmount</h1>

Type: rdf:Property

Comments: A monetary value of the credit note for this header trade settlement.

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="FromEventPaymentTermsEventTimeReferenceCode">FromEventPaymentTermsEventTimeReferenceCode</h1>

Type: rdf:Property

Comments: The code specifying the event from which these trade payment terms are offered for a length of time.

Domains: 

[edi3:PaymentTerms](#PaymentTerms)


<h1 id="FrequencyTypeCode">FrequencyTypeCode</h1>

Type: rdf:Property

Comments: The code specifying the type of frequency for this transport route, such as weekly, bi-monthly or daily.

Domains: 

[edi3:Route](#Route)


<h1 id="OrderPriceProductTradePrice">OrderPriceProductTradePrice</h1>

Type: rdf:Property

Comments: An order price for a product in this line trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="IncludedSpecifiedGeographicalGrid">IncludedSpecifiedGeographicalGrid</h1>

Type: rdf:Property

Comments: The geographical grid included in this geographical feature.

Domains: 

[edi3:GeographicalFeature](#GeographicalFeature)


<h1 id="ClassNameText">ClassNameText</h1>

Type: rdf:Property

Comments: A class name, expressed as text, for this product classification.

Domains: 

[edi3:Classification](#Classification)


<h1 id="ExemptionAuthorizationIdentificationIdentifier">ExemptionAuthorizationIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The unique identifier of the exemption authorization for this trade tax.

Domains: 

[edi3:Tax](#Tax)


<h1 id="CancelledQuantity">CancelledQuantity</h1>

Type: rdf:Property

Comments: The quantity, at line level, cancelled for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="ApplicationSpecifiedDocumentContextParameter">ApplicationSpecifiedDocumentContextParameter</h1>

Type: rdf:Property

Comments: An application context parameter specified for this exchanged document context.

Domains: 

[edi3:Context](#Context)


<h1 id="PrincipalAssociatedTradeParty">PrincipalAssociatedTradeParty</h1>

Type: rdf:Property

Comments: A principal trade party associated with this exchanged declaration.

Domains: 

[edi3:Declaration](#Declaration)


<h1 id="DeclaredValueForCustomsAmount">DeclaredValueForCustomsAmount</h1>

Type: rdf:Property

Comments: <br/>The monetary value declared for customs purposes for this supply chain consignment.<br/>The monetary value of this supply chain consignment item as declared for customs purposes.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:Consignment](#Consignment)


<h1 id="ApplicableTradePaymentDiscountTerms">ApplicableTradePaymentDiscountTerms</h1>

Type: rdf:Property

Comments: Trade payment discount terms applicable to these trade payment terms.

Domains: 

[edi3:PaymentTerms](#PaymentTerms)


<h1 id="PassengerListRelatedReferencedDocument">PassengerListRelatedReferencedDocument</h1>

Type: rdf:Property

Comments: The passenger list document related to this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="ExemptionReasonCode">ExemptionReasonCode</h1>

Type: rdf:Property

Comments: <br/>The code specifying the exemption reason for this registered tax.<br/>A code specifying a reason for exemption from this trade related tax, levy or duty.<br/>

Domains: 

[edi3:Tax](#Tax)


<h1 id="MaximumStackabilityQuantity">MaximumStackabilityQuantity</h1>

Type: rdf:Property

Comments: The number of units of this type of supply chain packaging which can be stacked on top of each other.

Domains: 

[edi3:Packaging](#Packaging)


<h1 id="IndexValue">IndexValue</h1>

Type: rdf:Property

Comments: The index value for this basic work item.

Domains: 

[edi3:WorkItem](#WorkItem)


<h1 id="ProcessingTransactionDateTime">ProcessingTransactionDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time, or other date time value of the processing of a transaction for this exchanged document context.

Domains: 

[edi3:Context](#Context)


<h1 id="ImportTypeCode">ImportTypeCode</h1>

Type: rdf:Property

Comments: The code specifying the import type of supply chain consignment item.

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)


<h1 id="TotalDiscountAmount">TotalDiscountAmount</h1>

Type: rdf:Property

Comments: A monetary value of a total discount reported in this trade settlement header monetary summation.

Domains: 

[edi3:MonetarySummation](#MonetarySummation)


<h1 id="ReportedLogisticsStatus">ReportedLogisticsStatus</h1>

Type: rdf:Property

Comments: <br/>A logistics status reported for this supply chain consignment item.<br/>A logistics status reported for this cross-border regulatory procedure.<br/>A logistics status reported for this supply chain consignment.<br/>A status reported for this piece of logistics transport equipment.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:TransportEquipment](#TransportEquipment)
[edi3:RegulatoryProcedure](#RegulatoryProcedure)
[edi3:Consignment](#Consignment)


<h1 id="CertifiedCalculatedEmission">CertifiedCalculatedEmission</h1>

Type: rdf:Property

Comments: A certified level of pollution calculated for an emission from this logistics transport means.

Domains: 

[edi3:TransportMeans](#TransportMeans)


<h1 id="PaymentReferenceText">PaymentReferenceText</h1>

Type: rdf:Property

Comments: <br/>A payment reference, expressed as text, for this line trade settlement.<br/>A payment reference, expressed as text, for this header trade settlement.<br/>

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="ServiceText">ServiceText</h1>

Type: rdf:Property

Comments: The service, expressed as text, of this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="PhysicalIndicator">PhysicalIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not this geographical object can be characterized as physical.

Domains: 

[edi3:GeographicalObjectCharacteristic](#GeographicalObjectCharacteristic)


<h1 id="SpecifiedTradeSettlementPaymentMonetarySummation">SpecifiedTradeSettlementPaymentMonetarySummation</h1>

Type: rdf:Property

Comments: The monetary summation totals specified for this payment trade settlement.

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="EstimatedApplicableLogisticsServiceCharge">EstimatedApplicableLogisticsServiceCharge</h1>

Type: rdf:Property

Comments: An estimated logistics service charge applicable to this supply chain consignment, such as freight or insurance charges.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="SupplierAssignedSerialIdentificationIdentifier">SupplierAssignedSerialIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The unique supplier assigned serial identifier for this trade product instance.

Domains: 

[edi3:ProductInstance](#ProductInstance)


<h1 id="EncodingCode">EncodingCode</h1>

Type: rdf:Property

Comments: The code specifying the encoding of this specified binary file.

Domains: 

[edi3:BinaryFile](#BinaryFile)


<h1 id="ProFormaInvoiceReferencedDocument">ProFormaInvoiceReferencedDocument</h1>

Type: rdf:Property

Comments: The pro-forma invoice document referenced by this header trade settlement.

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="SpecifiedGovernmentRegistration">SpecifiedGovernmentRegistration</h1>

Type: rdf:Property

Comments: A governmental registration specified for this trade party.

Domains: 

[edi3:Party](#Party)


<h1 id="LocationCode">LocationCode</h1>

Type: rdf:Property

Comments: The code specifying the location of this product security tag.

Domains: 

[edi3:SecurityTag](#SecurityTag)


<h1 id="IncludedTradeProduct">IncludedTradeProduct</h1>

Type: rdf:Property

Comments: A trade product included in this line trade transaction.

Domains: 

[edi3:TradeTransaction](#TradeTransaction)


<h1 id="TotalUnitQuantity">TotalUnitQuantity</h1>

Type: rdf:Property

Comments: A total number of units contained in this supply chain packaging.

Domains: 

[edi3:Packaging](#Packaging)


<h1 id="TypeTemperatureTypeCode">TypeTemperatureTypeCode</h1>

Type: rdf:Property

Comments: The code specifying the type of transport setting temperature [Reference United Nations Code List (UNCL) 6245].

Domains: 

[edi3:Temperature](#Temperature)


<h1 id="CountrySubDivisionNameText">CountrySubDivisionNameText</h1>

Type: rdf:Property

Comments: <br/>The name, expressed as text, of the sub-division of a country for this birth address.<br/>The name, expressed as text, of a country sub-division within this financial institution address.<br/>A name, expressed as text, of the sub-division of a country for this trade address.<br/>

Domains: 

[edi3:Address](#Address)


<h1 id="BBANIdentificationIdentifier">BBANIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique Basic Bank Account Number (BBAN) identifier used as part of a National Account Numbering Scheme(s) for this creditor financial account.<br/>The unique Basic Bank Account Number (BBAN) identifier used as part of a National Account Numbering Scheme for this financing financial account.<br/>The unique Basic Bank Account Number (BBAN) identifier used as part of a National Account Numbering Scheme(s) for this debtor financial account.<br/>

Domains: 

[edi3:FinancialAccount](#FinancialAccount)


<h1 id="ScheduledDepartureRelatedFormattedDateTime">ScheduledDepartureRelatedFormattedDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time or other date time value of the scheduled departure related to this referenced transport event.

Domains: 

[edi3:Event](#Event)


<h1 id="OccurrenceLogisticsLocation">OccurrenceLogisticsLocation</h1>

Type: rdf:Property

Comments: <br/>The logistics location where this communication event will occur or has occurred.<br/>A logistics location where this supply chain event occurs.<br/>The logistics location where this transport event occurs.<br/>

Domains: 

[edi3:Event](#Event)


<h1 id="ReferenceTypeReferenceCode">ReferenceTypeReferenceCode</h1>

Type: rdf:Property

Comments: The code specifying the reference type of this referenced document.

Domains: 

[edi3:Document](#Document)


<h1 id="GuaranteeMethodPaymentGuaranteeMeansCode">GuaranteeMethodPaymentGuaranteeMeansCode</h1>

Type: rdf:Property

Comments: The code specifying the method of guarantee for this trade settlement payment means.

Domains: 

[edi3:PaymentMeans](#PaymentMeans)


<h1 id="ProcedureCode">ProcedureCode</h1>

Type: rdf:Property

Comments: A code specifying a procedure for this exchanged declaration.

Domains: 

[edi3:Declaration](#Declaration)


<h1 id="ItemBasicWorkItem">ItemBasicWorkItem</h1>

Type: rdf:Property

Comments: <br/>A basic work item within this grouped work item.<br/>A basic work item in this valuation breakdown statement.<br/>A basic work item in this basic work item.<br/>

Domains: 

[edi3:WorkItem](#WorkItem)
[edi3:BreakdownStatement](#BreakdownStatement)


<h1 id="AllowanceChargeText">AllowanceChargeText</h1>

Type: rdf:Property

Comments: The allowance or charge, expressed as text, for this logistics service charge.

Domains: 

[edi3:ServiceCharge](#ServiceCharge)


<h1 id="LoadingLengthLinearUnitMeasure">LoadingLengthLinearUnitMeasure</h1>

Type: rdf:Property

Comments: <br/>A measure of the loading length which is the length along a means of transport over which the complete width and height is needed for loading all the goods items in this supply chain consignment.<br/>The measure of the loading length of this piece of logistics transport equipment.<br/>The measure of the loading length of this supply chain consignment item.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:TransportEquipment](#TransportEquipment)
[edi3:Consignment](#Consignment)


<h1 id="ResponsibleAgencyText">ResponsibleAgencyText</h1>

Type: rdf:Property

Comments: The agency, expressed as text, responsible for this trade product certification.

Domains: 

[edi3:Certification](#Certification)


<h1 id="FormulaDescriptionText">FormulaDescriptionText</h1>

Type: rdf:Property

Comments: The textual description of the formula for this distinct chemical.

Domains: 

[edi3:Chemical](#Chemical)


<h1 id="EquivalentTransferTotalAmount">EquivalentTransferTotalAmount</h1>

Type: rdf:Property

Comments: A monetary value transferred as an equivalent amount in the credit transfer payment in this trade settlement payment monetary summation, such as the amount transferred between debtor and creditor, before deduction of charges, expressed in the currency of the debtor's account, and transferred into a different currency.

Domains: 

[edi3:MonetarySummation](#MonetarySummation)


<h1 id="AutomaticDataCaptureMethodTypeAutomaticDataCaptureMethodCode">AutomaticDataCaptureMethodTypeAutomaticDataCaptureMethodCode</h1>

Type: rdf:Property

Comments: A code specifying an automatic data capture method type for this packaging marking.

Domains: 

[edi3:Marking](#Marking)


<h1 id="AuthorNameText">AuthorNameText</h1>

Type: rdf:Property

Comments: A name of an author, expressed as text, of this specified binary file.

Domains: 

[edi3:BinaryFile](#BinaryFile)


<h1 id="LinearSpatialDimension">LinearSpatialDimension</h1>

Type: rdf:Property

Comments: <br/>The linear spatial dimensions of this piece of logistics transport equipment.<br/>Linear spatial dimensions of this trade product.<br/>The linear spatial dimensions of this logistics package.<br/>The linear spatial dimensions of this supply chain packaging.<br/>The linear spatial dimensions of this supply chain consignment item.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:TransportEquipment](#TransportEquipment)
[edi3:Packaging](#Packaging)
[edi3:Product](#Product)
[edi3:Package](#Package)


<h1 id="CommodityConsolidatorTradeParty">CommodityConsolidatorTradeParty</h1>

Type: rdf:Property

Comments: The commodity consolidator party for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="ConditionValidationDocumentStatusCode">ConditionValidationDocumentStatusCode</h1>

Type: rdf:Property

Comments: The code specifying the condition of this validation status.

Domains: 

[edi3:Status](#Status)


<h1 id="ReturnableIndicator">ReturnableIndicator</h1>

Type: rdf:Property

Comments: <br/>The indication of whether or not this piece of logistics transport equipment is returnable.<br/>The indication of whether or not this logistics package is returnable.<br/>The indication of whether or not this supply chain packaging is returnable.<br/>

Domains: 

[edi3:TransportEquipment](#TransportEquipment)
[edi3:Packaging](#Packaging)
[edi3:Package](#Package)


<h1 id="ConnectingCarrierTradeParty">ConnectingCarrierTradeParty</h1>

Type: rdf:Property

Comments: A connecting carrier party for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="CriticalitySafetyIndexNumeric">CriticalitySafetyIndexNumeric</h1>

Type: rdf:Property

Comments: The criticality safety index number of this radioactive material.

Domains: 

[edi3:Material](#Material)


<h1 id="MicrochipIndicator">MicrochipIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not this trade settlement financial card has a microchip.

Domains: 

[edi3:FinancialCard](#FinancialCard)


<h1 id="SpecifiedCalculatedEmission">SpecifiedCalculatedEmission</h1>

Type: rdf:Property

Comments: A calculated emission specified for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="ProgramMissionProject">ProgramMissionProject</h1>

Type: rdf:Property

Comments: A mission project program for this line trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="NetPriceProductTradePrice">NetPriceProductTradePrice</h1>

Type: rdf:Property

Comments: <br/>A net product price in this subordinate line trade agreement.<br/>A net product price in this line trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="CycleText">CycleText</h1>

Type: rdf:Property

Comments: The cycle, as expressed as text, of this logistics transport movement, such as twice a day.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="InspectionReferenceReferencedDocument">InspectionReferenceReferencedDocument</h1>

Type: rdf:Property

Comments: A referenced inspection document for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="HazardCategoryCode">HazardCategoryCode</h1>

Type: rdf:Property

Comments: The code specifying the hazard category for these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="SignatoryImageBinaryObject">SignatoryImageBinaryObject</h1>

Type: rdf:Property

Comments: The signatory image, expressed as a binary object, for this document authentication.

Domains: 

[edi3:Authentication](#Authentication)


<h1 id="ResultNote">ResultNote</h1>

Type: rdf:Property

Comments: The note describing the results of this applied chemical treatment.

Domains: 

[edi3:ChemicalTreatment](#ChemicalTreatment)


<h1 id="MaximumDedicatedStorageCapacityVolumeUnitMeasure">MaximumDedicatedStorageCapacityVolumeUnitMeasure</h1>

Type: rdf:Property

Comments: The measure of the maximum dedicated storage capacity for this transport waste material component.

Domains: 

[edi3:MaterialComponent](#MaterialComponent)


<h1 id="ApplicableSupplyChainForecastTerms">ApplicableSupplyChainForecastTerms</h1>

Type: rdf:Property

Comments: <br/>The supply chain forecast terms applicable to this line trade agreement.<br/>The supply chain forecast terms applicable to this header trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="AcceptanceSupplyChainEvent">AcceptanceSupplyChainEvent</h1>

Type: rdf:Property

Comments: <br/>An acceptance delivery event, at line level, for this trade delivery.<br/>An acceptance delivery event, at header level, for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="EmailURIUniversalCommunication">EmailURIUniversalCommunication</h1>

Type: rdf:Property

Comments: <br/>The email URI (Uniform Resource Identifier) communication for this transport person.<br/>The email URI communication information for this trade contact.<br/>

Domains: 

[edi3:Person](#Person)
[edi3:Contact](#Contact)


<h1 id="NewZealandNCCIdentificationIdentifier">NewZealandNCCIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique New Zealand National Clearing Code (NCC) identifier as assigned by the New Zealand Bankers' Association (NZBA) for this creditor financial institution.<br/>The unique New Zealand National Clearing Code (NCC) identifier as assigned by the New Zealand Bankers' Association (NZBA) for this debtor financial institution.<br/>

Domains: 

[edi3:FinancialInstitution](#FinancialInstitution)


<h1 id="DisembarkationLogisticsLocation">DisembarkationLogisticsLocation</h1>

Type: rdf:Property

Comments: A disembarkation location for this transport person.

Domains: 

[edi3:Person](#Person)


<h1 id="SalesMethodCode">SalesMethodCode</h1>

Type: rdf:Property

Comments: The code specifying a sales method, such as an auction clock or mediation, for this specified marketplace.

Domains: 

[edi3:Marketplace](#Marketplace)


<h1 id="GuidelineSpecifiedDocumentContextParameter">GuidelineSpecifiedDocumentContextParameter</h1>

Type: rdf:Property

Comments: A guideline context parameter specified for this exchanged document context.

Domains: 

[edi3:Context](#Context)


<h1 id="TypeSealTypeCode">TypeSealTypeCode</h1>

Type: rdf:Property

Comments: The code specifying the type of logistics seal.

Domains: 

[edi3:Seal](#Seal)


<h1 id="UnitAmount">UnitAmount</h1>

Type: rdf:Property

Comments: A monetary value of the unit of this trade price.

Domains: 

[edi3:Price](#Price)


<h1 id="CalculationPercent">CalculationPercent</h1>

Type: rdf:Property

Comments: <br/>The percentage applied to calculate this trade allowance charge.<br/>The percent used to calculate the discount in these trade payment discount terms.<br/>The percentage used to calculate the applied allowance charge.<br/>The percent applied to calculate these trade payment penalty terms.<br/>

Domains: 

[edi3:AllowanceCharge](#AllowanceCharge)
[edi3:PaymentPenaltyTerms](#PaymentPenaltyTerms)
[edi3:PaymentDiscountTerms](#PaymentDiscountTerms)


<h1 id="InsurancePremiumAmount">InsurancePremiumAmount</h1>

Type: rdf:Property

Comments: The monetary value of the insurance premium for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="QuantityVariationReasonCode">QuantityVariationReasonCode</h1>

Type: rdf:Property

Comments: The code specifying the reason for the quantity variation, at line level, for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="PollingRateMeasure">PollingRateMeasure</h1>

Type: rdf:Property

Comments: The measure of the polling rate for this OEM equipment.

Domains: 

[edi3:Equipment](#Equipment)


<h1 id="HandlingHandlingInstructions">HandlingHandlingInstructions</h1>

Type: rdf:Property

Comments: <br/>Handling instructions for this supply chain consignment item.<br/>Handling instructions for this supply chain consignment, such as where or how specified packages or containers are to be loaded on a means of transport.<br/>Handling instructions for the transported dangerous goods.<br/>Handling instructions for this piece of logistics transport equipment.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:TransportEquipment](#TransportEquipment)
[edi3:Consignment](#Consignment)
[edi3:DangerousGoods](#DangerousGoods)


<h1 id="PaymentPlaceLogisticsLocation">PaymentPlaceLogisticsLocation</h1>

Type: rdf:Property

Comments: The location of the place of payment of this logistics service charge.

Domains: 

[edi3:ServiceCharge](#ServiceCharge)


<h1 id="SpecifiedPaymentInstalmentPlan">SpecifiedPaymentInstalmentPlan</h1>

Type: rdf:Property

Comments: The payment instalment plan specified for this header trade settlement.

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="BuyerAssignedAccountantTradeParty">BuyerAssignedAccountantTradeParty</h1>

Type: rdf:Property

Comments: The party assigned as an accountant by the buyer for this header trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="CatalogueReferencedDocument">CatalogueReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>A catalogue document referenced in this header trade agreement.<br/>A catalogue document referenced by this line trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="ReceivableSpecifiedTradeAccountingAccount">ReceivableSpecifiedTradeAccountingAccount</h1>

Type: rdf:Property

Comments: <br/>A receivable accounting account specified for this line trade settlement.<br/>A receivable accounting account specified for this header trade settlement.<br/>

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="IncludedReferencedProduct">IncludedReferencedProduct</h1>

Type: rdf:Property

Comments: An included product referenced from this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="RecipientAssignedIdentificationIdentifier">RecipientAssignedIdentificationIdentifier</h1>

Type: rdf:Property

Comments: A unique recipient assigned identifier for this exchanged document.

Domains: 

[edi3:Document](#Document)


<h1 id="RadioactiveRadioactiveMaterial">RadioactiveRadioactiveMaterial</h1>

Type: rdf:Property

Comments: The radioactive material transported as dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="TransactionNatureCode">TransactionNatureCode</h1>

Type: rdf:Property

Comments: A code specifying the nature of a transaction for this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="PayerSpecifiedDebtorFinancialInstitution">PayerSpecifiedDebtorFinancialInstitution</h1>

Type: rdf:Property

Comments: The debtor financial institution of the payer party specified for this trade settlement payment means.

Domains: 

[edi3:PaymentMeans](#PaymentMeans)


<h1 id="InnerPackQuantity">InnerPackQuantity</h1>

Type: rdf:Property

Comments: The number of inner packs of this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="OwnedCreditorFinancialAccount">OwnedCreditorFinancialAccount</h1>

Type: rdf:Property

Comments: The creditor financial account owned by this trade party.

Domains: 

[edi3:Party](#Party)


<h1 id="RelatedCommunicationEvent">RelatedCommunicationEvent</h1>

Type: rdf:Property

Comments: <br/>A communication event related to this piece of logistics transport equipment.<br/>A communication event related to this monitoring IOT device.<br/>

Domains: 

[edi3:TransportEquipment](#TransportEquipment)
[edi3:IOTDevice](#IOTDevice)


<h1 id="LodgementLogisticsLocation">LodgementLogisticsLocation</h1>

Type: rdf:Property

Comments: <br/>The logistics related location where this referenced document has been lodged.<br/>The location where this exchanged document has been lodged.<br/>

Domains: 

[edi3:Document](#Document)


<h1 id="MobileTelephoneUniversalCommunication">MobileTelephoneUniversalCommunication</h1>

Type: rdf:Property

Comments: <br/>The mobile telephone communication information for this trade contact.<br/>Mobile telephone communication information for this transport person.<br/>

Domains: 

[edi3:Person](#Person)
[edi3:Contact](#Contact)


<h1 id="IncludedAmount">IncludedAmount</h1>

Type: rdf:Property

Comments: A monetary value included in this referenced document.

Domains: 

[edi3:Document](#Document)


<h1 id="BorderCrossingTransportEvent">BorderCrossingTransportEvent</h1>

Type: rdf:Property

Comments: A border crossing event for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="ChangeReasonText">ChangeReasonText</h1>

Type: rdf:Property

Comments: A reason, expressed as text, for a change of this trade price.

Domains: 

[edi3:Price](#Price)


<h1 id="TimeZoneText">TimeZoneText</h1>

Type: rdf:Property

Comments: The time zone, expressed as text, for this geographical coordinate.

Domains: 

[edi3:GeographicalCoordinate](#GeographicalCoordinate)


<h1 id="SpecifiedLineTradeSettlement">SpecifiedLineTradeSettlement</h1>

Type: rdf:Property

Comments: A line trade settlement specified for this supply chain trade line item.

Domains: 

[edi3:TradeLineItem](#TradeLineItem)


<h1 id="ScenarioSpecifiedDocumentContextParameter">ScenarioSpecifiedDocumentContextParameter</h1>

Type: rdf:Property

Comments: A scenario context parameter specified for this exchanged document context.

Domains: 

[edi3:Context](#Context)


<h1 id="PaymentMeansIdentificationIdentifier">PaymentMeansIdentificationIdentifier</h1>

Type: rdf:Property

Comments: An identifier of a payment means in these trade payment terms.

Domains: 

[edi3:PaymentTerms](#PaymentTerms)


<h1 id="CarriedInactiveReferencedTransportMeans">CarriedInactiveReferencedTransportMeans</h1>

Type: rdf:Property

Comments: Details of transport means inactively carried during the transport movement, such as trucks on a Roll-On/Roll-Off (RORO) ferry.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="DeliveryTypeDeliveryTermsCode">DeliveryTypeDeliveryTermsCode</h1>

Type: rdf:Property

Comments: The code specifying the type of delivery for these trade delivery terms.

Domains: 

[edi3:DeliveryTerms](#DeliveryTerms)


<h1 id="PositioningTransportEvent">PositioningTransportEvent</h1>

Type: rdf:Property

Comments: A positioning event specifying when and where this piece of logistics transport equipment will be, or has been, positioned, i.e. delivered and available for pick-up.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="MeasurementMethodCode">MeasurementMethodCode</h1>

Type: rdf:Property

Comments: A code specifying a measurement method for this product characteristic.

Domains: 

[edi3:Characteristic](#Characteristic)


<h1 id="FactoringAgreementReferencedDocument">FactoringAgreementReferencedDocument</h1>

Type: rdf:Property

Comments: A factoring agreement document referenced in this header trade settlement.

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="ContentCode">ContentCode</h1>

Type: rdf:Property

Comments: <br/>Content, expressed as a code, of this packaging marking.<br/>A code specifying the content of this note.<br/>

Domains: 

[edi3:Note](#Note)
[edi3:Marking](#Marking)


<h1 id="ForecastTypeCode">ForecastTypeCode</h1>

Type: rdf:Property

Comments: The code specifying the forecast type in these supply chain forecast terms.

Domains: 

[edi3:ForecastTerms](#ForecastTerms)


<h1 id="AttachedAttachedTransportEquipment">AttachedAttachedTransportEquipment</h1>

Type: rdf:Property

Comments: Transport equipment attached to this piece of logistics transport equipment, such as ropes or refrigeration units.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="RemarkText">RemarkText</h1>

Type: rdf:Property

Comments: A remark, expressed as text, for this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="TypeGovernmentActionCode">TypeGovernmentActionCode</h1>

Type: rdf:Property

Comments: The code specifying the type of document authentication.

Domains: 

[edi3:Authentication](#Authentication)


<h1 id="PreviousAdministrativeReferencedDocument">PreviousAdministrativeReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>A previous administrative referenced document for this supply chain consignment item.<br/>A previous administrative referenced document for this supply chain consignment.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:Consignment](#Consignment)


<h1 id="ComplianceDeclarationInformationText">ComplianceDeclarationInformationText</h1>

Type: rdf:Property

Comments: Compliance declaration information, expressed as text, for these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="TelephoneTelecommunicationCommunication">TelephoneTelecommunicationCommunication</h1>

Type: rdf:Property

Comments: Telephone communication information for this contact person.

Domains: 

[edi3:Person](#Person)


<h1 id="SealingPartyRoleSealingPartyRoleCode">SealingPartyRoleSealingPartyRoleCode</h1>

Type: rdf:Property

Comments: The code specifying the role of the party responsible for the sealing of this logistics seal.

Domains: 

[edi3:Seal](#Seal)


<h1 id="ActualTransportRoute">ActualTransportRoute</h1>

Type: rdf:Property

Comments: An actual route for this piece of logistics transport equipment.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="SpecifiedDeliveryInstructions">SpecifiedDeliveryInstructions</h1>

Type: rdf:Property

Comments: <br/>Delivery instructions, at header level, specified for this trade delivery.<br/>Delivery instructions, at line level, specified for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="ActualMeasure">ActualMeasure</h1>

Type: rdf:Property

Comments: An actual measure for this measurement.

Domains: 

[edi3:Measurement](#Measurement)


<h1 id="GeometryCollectionIndicator">GeometryCollectionIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not this geographical object can be characterized as a geometry collection.

Domains: 

[edi3:GeographicalObjectCharacteristic](#GeographicalObjectCharacteristic)


<h1 id="GFMTransferRejectedQuantity">GFMTransferRejectedQuantity</h1>

Type: rdf:Property

Comments: The Government Furnished Material (GFM) transfer rejected quantity, at line level, for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="ReferenceText">ReferenceText</h1>

Type: rdf:Property

Comments: <br/>A reference, expressed as text, for this line trade agreement.<br/>A reference, expressed as text, for this header trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="ExclusivitySpecifiedPeriod">ExclusivitySpecifiedPeriod</h1>

Type: rdf:Property

Comments: The exclusivity period specified in this line trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="SpecifiedReferencedProduct">SpecifiedReferencedProduct</h1>

Type: rdf:Property

Comments: The referenced product specified for this subordinate trade line item.

Domains: 

[edi3:TradeLineItem](#TradeLineItem)


<h1 id="TypePaymentTermsTypeCode">TypePaymentTermsTypeCode</h1>

Type: rdf:Property

Comments: A code specifying the type of trade payment terms.

Domains: 

[edi3:PaymentTerms](#PaymentTerms)


<h1 id="ComparisonMethodCode">ComparisonMethodCode</h1>

Type: rdf:Property

Comments: The code specifying the comparison method for this reference price.

Domains: 

[edi3:Price](#Price)


<h1 id="CustomsImportAgentTradeParty">CustomsImportAgentTradeParty</h1>

Type: rdf:Property

Comments: The party acting as an agent for, or on behalf of, the consignee with respect to the customs import procedures for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="RequiredLogisticsSeal">RequiredLogisticsSeal</h1>

Type: rdf:Property

Comments: A seal required by this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="EstablishedDateTime">EstablishedDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time, or other date time value when this legally set up organization was established.

Domains: 

[edi3:Organization](#Organization)


<h1 id="BillingSpecifiedPeriod">BillingSpecifiedPeriod</h1>

Type: rdf:Property

Comments: <br/>A billing period specified for this header trade settlement.<br/>A billing period specified for this line trade settlement.<br/>

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="LoadingInformationText">LoadingInformationText</h1>

Type: rdf:Property

Comments: Loading information, expressed as text, for this supply chain consignment, such as advice and instructions.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="ApplicablePhysicalCharacteristic">ApplicablePhysicalCharacteristic</h1>

Type: rdf:Property

Comments: A physical characteristic applicable to this OEM equipment.

Domains: 

[edi3:Equipment](#Equipment)


<h1 id="SpecifiedLineTradeDelivery">SpecifiedLineTradeDelivery</h1>

Type: rdf:Property

Comments: The line trade delivery specified for this supply chain trade line item.

Domains: 

[edi3:TradeLineItem](#TradeLineItem)


<h1 id="PurchaseConditionsReferencedDocument">PurchaseConditionsReferencedDocument</h1>

Type: rdf:Property

Comments: A purchase conditions document referenced in this header trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="SpecifiedTradeSettlementHeaderMonetarySummation">SpecifiedTradeSettlementHeaderMonetarySummation</h1>

Type: rdf:Property

Comments: The monetary summation totals specified for this header trade settlement.

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="BirthDateTime">BirthDateTime</h1>

Type: rdf:Property

Comments: <br/>The birth date of this transport person.<br/>The date, time, date time or other date time value which specifies the birth date for this contact person.<br/>

Domains: 

[edi3:Person](#Person)


<h1 id="HighLimitText">HighLimitText</h1>

Type: rdf:Property

Comments: The tuple of elements, expressed as text, indicating the high limit of this geographical grid specifying the diagonally opposing corner of each axis.

Domains: 

[edi3:GeographicalGrid](#GeographicalGrid)


<h1 id="UrgencyCode">UrgencyCode</h1>

Type: rdf:Property

Comments: The code specifying the urgency for this exchanged document.

Domains: 

[edi3:Document](#Document)


<h1 id="MaximumIdentificationIdentifier">MaximumIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The maximum unique identifier used for these logistics seals.

Domains: 

[edi3:Seal](#Seal)


<h1 id="FinancedAppliedRatePercent">FinancedAppliedRatePercent</h1>

Type: rdf:Property

Comments: The financed applied rate, expressed as a percentage, in this financing summary document.

Domains: 

[edi3:Document](#Document)


<h1 id="SizeMeasure">SizeMeasure</h1>

Type: rdf:Property

Comments: The measure of the size of this specified binary file.

Domains: 

[edi3:BinaryFile](#BinaryFile)


<h1 id="BuyerRepayableTaxSpecifiedTradeAccountingAccount">BuyerRepayableTaxSpecifiedTradeAccountingAccount</h1>

Type: rdf:Property

Comments: The buyer repayable tax specified accounting account for this trade related tax, levy or duty.

Domains: 

[edi3:Tax](#Tax)


<h1 id="MaximumStorageHumidityApplicableMeasure">MaximumStorageHumidityApplicableMeasure</h1>

Type: rdf:Property

Comments: The measure of the maximum storage humidity applicable to these handling instructions.

Domains: 

[edi3:Instructions](#Instructions)


<h1 id="IncrementalProductOrderableQuantity">IncrementalProductOrderableQuantity</h1>

Type: rdf:Property

Comments: The incremental product orderable quantity for this line trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="TransportTransportEvent">TransportTransportEvent</h1>

Type: rdf:Property

Comments: An event occurring during the transport of this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="ApplicableTradeDeliveryTerms">ApplicableTradeDeliveryTerms</h1>

Type: rdf:Property

Comments: <br/>The terms of delivery applicable to this line trade agreement.<br/>The terms of delivery applicable to this header trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="CertificationEvidenceReferenceReferencedDocument">CertificationEvidenceReferenceReferencedDocument</h1>

Type: rdf:Property

Comments: A referenced certification evidence document for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="BasisPeriodMeasure">BasisPeriodMeasure</h1>

Type: rdf:Property

Comments: <br/>The measure of the basis period for these trade payment discount terms.<br/>The measure of the period used as a basis to calculate these trade payment penalty terms.<br/>

Domains: 

[edi3:PaymentPenaltyTerms](#PaymentPenaltyTerms)
[edi3:PaymentDiscountTerms](#PaymentDiscountTerms)


<h1 id="ScheduledArrivalRelatedFormattedDateTime">ScheduledArrivalRelatedFormattedDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time or other date time value of the scheduled arrival related to this referenced transport event.

Domains: 

[edi3:Event](#Event)


<h1 id="TradingConsolidatorAssignedIdentificationIdentifier">TradingConsolidatorAssignedIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The unique identifier for this logistics transport movement as assigned by the trading consolidator.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="PollingCapabilityIndicator">PollingCapabilityIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not this OEM equipment has a polling capability.

Domains: 

[edi3:Equipment](#Equipment)


<h1 id="PayerPartyDebtorFinancialAccount">PayerPartyDebtorFinancialAccount</h1>

Type: rdf:Property

Comments: The debtor financial account of the payer party for this trade settlement payment means.

Domains: 

[edi3:PaymentMeans](#PaymentMeans)


<h1 id="ConsignmentDestinationSpecifiedLogisticsLocation">ConsignmentDestinationSpecifiedLogisticsLocation</h1>

Type: rdf:Property

Comments: A consignment destination location specified for this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="SourceUnitBasisNumeric">SourceUnitBasisNumeric</h1>

Type: rdf:Property

Comments: The numeric unit basis of the source currency used in this trade related currency exchange rate calculation.

Domains: 

[edi3:CurrencyExchange](#CurrencyExchange)


<h1 id="StevedoreTradeParty">StevedoreTradeParty</h1>

Type: rdf:Property

Comments: A stevedore party for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="FormattedPickUpAvailabilityDateTime">FormattedPickUpAvailabilityDateTime</h1>

Type: rdf:Property

Comments: The formatted date, time, date time, or other date time value, at line level, when this delivery is available for pick-up.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="ValidFromDateTime">ValidFromDateTime</h1>

Type: rdf:Property

Comments: The date from which this trade settlement financial card is valid.

Domains: 

[edi3:FinancialCard](#FinancialCard)


<h1 id="PlannedDeliverySupplyChainEvent">PlannedDeliverySupplyChainEvent</h1>

Type: rdf:Property

Comments: <br/>A delivery event, at line level, planned for this trade delivery.<br/>A delivery event, at header level, planned for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="ApprovedSecurityPlanOnboardIndicator">ApprovedSecurityPlanOnboardIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not there is an approved security plan onboard this logistics transport means.

Domains: 

[edi3:TransportMeans](#TransportMeans)


<h1 id="AuthenticationMethodCode">AuthenticationMethodCode</h1>

Type: rdf:Property

Comments: A code specifying an authentication method for this certified accreditation.

Domains: 

[edi3:Accreditation](#Accreditation)


<h1 id="PlaceApplicableTradeLocation">PlaceApplicableTradeLocation</h1>

Type: rdf:Property

Comments: A location where this trade tax is applicable.

Domains: 

[edi3:Tax](#Tax)


<h1 id="ArrivalTransportEvent">ArrivalTransportEvent</h1>

Type: rdf:Property

Comments: An arrival event for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="PowerActiveLogisticsTransportMeans">PowerActiveLogisticsTransportMeans</h1>

Type: rdf:Property

Comments: A means of transport actively powering this logistics convoy.

Domains: 

[edi3:Convoy](#Convoy)


<h1 id="ActualEffectiveDateTime">ActualEffectiveDateTime</h1>

Type: rdf:Property

Comments: The actual effective date, time, date time or other date time value for this product certificate.

Domains: 

[edi3:Certificate](#Certificate)


<h1 id="SwissBCIdentificationIdentifier">SwissBCIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique Swiss Bank Code (BC) identifier for this debtor financial institution.<br/>The unique Swiss Bank Code (BC) identifier for this creditor financial institution.<br/>

Domains: 

[edi3:FinancialInstitution](#FinancialInstitution)


<h1 id="CoverageCode">CoverageCode</h1>

Type: rdf:Property

Comments: The code specifying the coverage of this transport cargo insurance.

Domains: 

[edi3:CargoInsurance](#CargoInsurance)


<h1 id="TransitLogisticsLocation">TransitLogisticsLocation</h1>

Type: rdf:Property

Comments: A location of transit for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="SuperordinateTradeCountrySubDivision">SuperordinateTradeCountrySubDivision</h1>

Type: rdf:Property

Comments: A superordinate country sub-division for this trade country sub-division.

Domains: 

[edi3:CountrySubDivision](#CountrySubDivision)


<h1 id="SourceCurrencyCurrencyCode">SourceCurrencyCurrencyCode</h1>

Type: rdf:Property

Comments: The code specifying the source currency of a trade related currency conversion.

Domains: 

[edi3:CurrencyExchange](#CurrencyExchange)


<h1 id="ConsigneeAssignedIdentifier">ConsigneeAssignedIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique identifier assigned by the consignee to this supply chain consignment.<br/>The unique identifier assigned by the consignee to this referenced supply chain consignment.<br/>

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="DepositValueValiditySpecifiedPeriod">DepositValueValiditySpecifiedPeriod</h1>

Type: rdf:Property

Comments: The specified period during which the deposit value specified in these returnable asset instructions is valid.

Domains: 

[edi3:Instructions](#Instructions)


<h1 id="MethodText">MethodText</h1>

Type: rdf:Property

Comments: A measurement method expressed as text.

Domains: 

[edi3:Measurement](#Measurement)


<h1 id="SubjectCode">SubjectCode</h1>

Type: rdf:Property

Comments: A code specifying the subject of this note.

Domains: 

[edi3:Note](#Note)


<h1 id="ItemQuantity">ItemQuantity</h1>

Type: rdf:Property

Comments: <br/>The number of referenced logistics packages at this level.<br/>The number of logistics packages at this level.<br/>

Domains: 

[edi3:Package](#Package)


<h1 id="QuotationRequestReferencedDocument">QuotationRequestReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>The quotation request document referenced in this header trade agreement.<br/>The quotation request document referenced in this line trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="FromOpeningLifeSpanDurationUnitMeasure">FromOpeningLifeSpanDurationUnitMeasure</h1>

Type: rdf:Property

Comments: The measure of the life span of this trade product from date of opening.

Domains: 

[edi3:Product](#Product)


<h1 id="GrossWeightMeasure">GrossWeightMeasure</h1>

Type: rdf:Property

Comments: <br/>A measure of the gross weight (mass) of this trade product.<br/>The measure of the gross weight (mass) of this logistics package and its contents.<br/>

Domains: 

[edi3:Product](#Product)
[edi3:Package](#Package)


<h1 id="TypeContactTypeCode">TypeContactTypeCode</h1>

Type: rdf:Property

Comments: The code specifying the type of trade contact.

Domains: 

[edi3:Contact](#Contact)


<h1 id="WasteReportingExemptionIndicator">WasteReportingExemptionIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not there is a waste reporting exemption for this logistics means of transport.

Domains: 

[edi3:TransportMeans](#TransportMeans)


<h1 id="PhysicalReferencedLogisticsPackage">PhysicalReferencedLogisticsPackage</h1>

Type: rdf:Property

Comments: A physical logistics package referenced for this supply chain trade line item.

Domains: 

[edi3:TradeLineItem](#TradeLineItem)


<h1 id="RelatedSpecifiedBinaryFile">RelatedSpecifiedBinaryFile</h1>

Type: rdf:Property

Comments: A binary file related to this specified observation.

Domains: 

[edi3:Observation](#Observation)


<h1 id="SubstituteApplicableReferencedProduct">SubstituteApplicableReferencedProduct</h1>

Type: rdf:Property

Comments: A referenced substitute product applicable for this supply chain trade line item.

Domains: 

[edi3:TradeLineItem](#TradeLineItem)


<h1 id="AssociatedLogisticsConvoy">AssociatedLogisticsConvoy</h1>

Type: rdf:Property

Comments: The convoy associated with this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="EmergencyTradeContact">EmergencyTradeContact</h1>

Type: rdf:Property

Comments: The person or department to be contacted in the event of any emergency related to these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="SpecialInstructionsText">SpecialInstructionsText</h1>

Type: rdf:Property

Comments: Special instructions, expressed as text, for this supply chain consignment item.

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)


<h1 id="TotalChargeAmount">TotalChargeAmount</h1>

Type: rdf:Property

Comments: <br/>The total monetary value of all freight and other service charges for this supply chain consignment.<br/>The monetary value of all freight and other service charges for this supply chain consignment item.<br/>A monetary value of the total charges, including tariff and non-tariff charges, for this cross-border regulatory procedure.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:RegulatoryProcedure](#RegulatoryProcedure)
[edi3:Consignment](#Consignment)


<h1 id="OperationTradeCountry">OperationTradeCountry</h1>

Type: rdf:Property

Comments: The trade country where the operation of this product handling process occurs.

Domains: 

[edi3:Process](#Process)


<h1 id="PollutantLevelCode">PollutantLevelCode</h1>

Type: rdf:Property

Comments: The code specifying the level of pollution of these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="NationalTypeExtensionCode">NationalTypeExtensionCode</h1>

Type: rdf:Property

Comments: The code used as a national extension to the type code for further specifying the type of supply chain consignment item.

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)


<h1 id="AftDraughtLevelMeasure">AftDraughtLevelMeasure</h1>

Type: rdf:Property

Comments: The draught level measured at the aft end of this transport means.

Domains: 

[edi3:TransportMeans](#TransportMeans)


<h1 id="ExportLicenceReferencedDocument">ExportLicenceReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>The export licence document referenced in this line trade agreement.<br/>The export licence document referenced in this header trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="RequestedSpecifiedRange">RequestedSpecifiedRange</h1>

Type: rdf:Property

Comments: A requested range specified for this control setting parameter.

Domains: 

[edi3:Parameter](#Parameter)


<h1 id="MiddleNameText">MiddleNameText</h1>

Type: rdf:Property

Comments: The middle name, expressed as text, of this contact person, usually given by parents at birth.

Domains: 

[edi3:Person](#Person)


<h1 id="RegistrationTransportEvent">RegistrationTransportEvent</h1>

Type: rdf:Property

Comments: A registration event of this logistics transport means.

Domains: 

[edi3:TransportMeans](#TransportMeans)


<h1 id="ActualOccurrenceDateTime">ActualOccurrenceDateTime</h1>

Type: rdf:Property

Comments: The actual date, time, date time, or other date time value of the occurrence of this transport event.

Domains: 

[edi3:Event](#Event)


<h1 id="RelatedSupplyChainConsignment">RelatedSupplyChainConsignment</h1>

Type: rdf:Property

Comments: <br/>A consignment, at line level, related to this line trade delivery.<br/>A consignment, at header level, related to this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="EstimatedTransportMeansArrivalOccurrenceDateTime">EstimatedTransportMeansArrivalOccurrenceDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time, or other date time value when the arrival of a means of transport at the location of this transport event is estimated to occur.

Domains: 

[edi3:Event](#Event)


<h1 id="NetVolumeVolumeUnitMeasure">NetVolumeVolumeUnitMeasure</h1>

Type: rdf:Property

Comments: <br/>The measure, at line level, of the net volume of this line trade delivery.<br/>A measure of the net volume of this supply chain consignment item which excludes all packaging.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)
[edi3:Consignment](#Consignment)


<h1 id="ChangerNameText">ChangerNameText</h1>

Type: rdf:Property

Comments: The name of the person or system, expressed as text, that changed this recorded status.

Domains: 

[edi3:Status](#Status)


<h1 id="GenderCode">GenderCode</h1>

Type: rdf:Property

Comments: A code specifying the gender of this transport person.

Domains: 

[edi3:Person](#Person)


<h1 id="OriginAssociatedSpecifiedDirectPositionList">OriginAssociatedSpecifiedDirectPositionList</h1>

Type: rdf:Property

Comments: The direct position list associated with the origin of this geographical grid.

Domains: 

[edi3:GeographicalGrid](#GeographicalGrid)


<h1 id="LineStatusLineStatusCode">LineStatusLineStatusCode</h1>

Type: rdf:Property

Comments: The code specifying the status of this document line.

Domains: 

[edi3:Document](#Document)


<h1 id="PayerReferenceText">PayerReferenceText</h1>

Type: rdf:Property

Comments: <br/>The payer reference, expressed as text, for this header trade settlement.<br/>The payer reference, expressed as text, for this line trade settlement.<br/>

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="TypeExtensionGoodsTypeExtensionCode">TypeExtensionGoodsTypeExtensionCode</h1>

Type: rdf:Property

Comments: <br/>The code used as an extension to the type code for further specifying the type of referenced supply chain consignment item.<br/>The code used as an extension to the type code for further specifying the type of supply chain consignment item.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)


<h1 id="BuyerOrderFormattedDateTime">BuyerOrderFormattedDateTime</h1>

Type: rdf:Property

Comments: <br/>The date, time, date time, or other date time value, at line level, of the buyer order for this trade delivery.<br/>The date, time, date time, or other date time value, at header level, of the buyer order for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="SubsetWorkItemComplexDescription">SubsetWorkItemComplexDescription</h1>

Type: rdf:Property

Comments: The complex description subset for this work item complex description.

Domains: 

[edi3:ComplexDescription](#ComplexDescription)


<h1 id="DebitNoteAmount">DebitNoteAmount</h1>

Type: rdf:Property

Comments: A monetary value of the debit note for this header trade settlement.

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="ImportLicenceReferencedDocument">ImportLicenceReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>The import licence document referenced in this line trade agreement.<br/>The import licence document referenced in this header trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="InformationUseRestrictionIndicator">InformationUseRestrictionIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not the use of the information provided in this line trade agreement is restricted.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="MarketDeliveryApplicableInstructedTemperature">MarketDeliveryApplicableInstructedTemperature</h1>

Type: rdf:Property

Comments: The instructed temperature for market delivery applicable to these handling instructions.

Domains: 

[edi3:Instructions](#Instructions)


<h1 id="DeclarantAgentTradeParty">DeclarantAgentTradeParty</h1>

Type: rdf:Property

Comments: The trade party acting as an agent for the declarant for this exchanged declaration.

Domains: 

[edi3:Declaration](#Declaration)


<h1 id="PickUpTransportEvent">PickUpTransportEvent</h1>

Type: rdf:Property

Comments: <br/>The pick-up event for this supply chain consignment.<br/>A pick-up transport event for this supply chain consignment item.<br/>A pick-up event specifying when and where this piece of logistics transport equipment will be, or has been, collected, i.e. picked-up by the carrier.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:TransportEquipment](#TransportEquipment)
[edi3:Consignment](#Consignment)


<h1 id="FaxUniversalCommunication">FaxUniversalCommunication</h1>

Type: rdf:Property

Comments: <br/>Fax communication information for this location party.<br/>Fax communication information for this trade contact.<br/>

Domains: 

[edi3:Party](#Party)
[edi3:Contact](#Contact)


<h1 id="RateApplicablePercent">RateApplicablePercent</h1>

Type: rdf:Property

Comments: The applicable rate, expressed as a percentage, for this trade tax, levy or duty.

Domains: 

[edi3:Tax](#Tax)


<h1 id="InvoiceAmount">InvoiceAmount</h1>

Type: rdf:Property

Comments: A monetary value for an invoice for this supply chain consignment item.

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)


<h1 id="SettlementPeriodMeasure">SettlementPeriodMeasure</h1>

Type: rdf:Property

Comments: The measure of the number of settlement periods from this trade payment term time reference to the latest payment date, such as 30 days, 3 months.

Domains: 

[edi3:PaymentTerms](#PaymentTerms)


<h1 id="TotalRetailValueInformationAmount">TotalRetailValueInformationAmount</h1>

Type: rdf:Property

Comments: <br/>A monetary value which constitutes the total retail value stated for information purposes in this trade settlement header monetary summation.<br/>A monetary value which constitutes the total retail value stated for information purposes in this trade settlement line monetary summation.<br/>

Domains: 

[edi3:MonetarySummation](#MonetarySummation)


<h1 id="SpecifiedTransportInstructions">SpecifiedTransportInstructions</h1>

Type: rdf:Property

Comments: An instruction or a set of instructions specified for this transport event.

Domains: 

[edi3:Event](#Event)


<h1 id="LatestRevisionDateTime">LatestRevisionDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time, or other date time value for the latest revision of this document line.

Domains: 

[edi3:Document](#Document)


<h1 id="ReceiptSupplyChainSchedule">ReceiptSupplyChainSchedule</h1>

Type: rdf:Property

Comments: A supply chain receipt schedule, at line level, for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="ShipToTradeParty">ShipToTradeParty</h1>

Type: rdf:Property

Comments: <br/>The ship to party for this supply chain consignment.<br/>The ship to party, at line level, for this trade delivery.<br/>The ship to party, at header level, for this trade delivery.<br/>The ship to trade party for this supply chain supply plan.<br/>

Domains: 

[edi3:SupplyPlan](#SupplyPlan)
[edi3:TradeDelivery](#TradeDelivery)
[edi3:Consignment](#Consignment)


<h1 id="MaterialIdentifier">MaterialIdentifier</h1>

Type: rdf:Property

Comments: <br/>The identifier of the material to which these disposal instructions apply.<br/>An identifier of the material to which these returnable asset instructions apply.<br/>

Domains: 

[edi3:Instructions](#Instructions)


<h1 id="ScheduledTransportRoute">ScheduledTransportRoute</h1>

Type: rdf:Property

Comments: A scheduled or planned route for this piece of logistics transport equipment.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="ActualArrivalRelatedDateTime">ActualArrivalRelatedDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time or other date time value of the actual arrival related to this transport event.

Domains: 

[edi3:Event](#Event)


<h1 id="SupplementaryInformationText">SupplementaryInformationText</h1>

Type: rdf:Property

Comments: Supplementary information, expressed as text, concerning the transport of these dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="OriginLogisticsLocation">OriginLogisticsLocation</h1>

Type: rdf:Property

Comments: <br/>A location of origin for this supply chain product instance.<br/>A location of origin for this trade product.<br/>

Domains: 

[edi3:Product](#Product)
[edi3:ProductInstance](#ProductInstance)


<h1 id="MolecularWeightMeasure">MolecularWeightMeasure</h1>

Type: rdf:Property

Comments: The measure of the molecular weight (in grams) for this distinct chemical.

Domains: 

[edi3:Chemical](#Chemical)


<h1 id="RelatedFinancialBooking">RelatedFinancialBooking</h1>

Type: rdf:Property

Comments: The financial booking related to this financing summary document.

Domains: 

[edi3:Document](#Document)


<h1 id="UnitTypeCode">UnitTypeCode</h1>

Type: rdf:Property

Comments: A code specifying a type of unit for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="TotalQuantityClassificationCode">TotalQuantityClassificationCode</h1>

Type: rdf:Property

Comments: The code specifying the classification of the total quantity for this basic work item.

Domains: 

[edi3:WorkItem](#WorkItem)


<h1 id="ReportedSecurityInformationText">ReportedSecurityInformationText</h1>

Type: rdf:Property

Comments: Reported security information, expressed as text, for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="FirstTypeExtensionCode">FirstTypeExtensionCode</h1>

Type: rdf:Property

Comments: The code used as a first extension to the type code for further specifying the type of supply chain consignment item.

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)


<h1 id="AverageDemandQuantity">AverageDemandQuantity</h1>

Type: rdf:Property

Comments: The average demand quantity for this supply chain inventory.

Domains: 

[edi3:Inventory](#Inventory)


<h1 id="TermsAndConditionsDescriptionText">TermsAndConditionsDescriptionText</h1>

Type: rdf:Property

Comments: A textual description of the terms and conditions for these returnable asset instructions.

Domains: 

[edi3:Instructions](#Instructions)


<h1 id="PowerSupplyTypeText">PowerSupplyTypeText</h1>

Type: rdf:Property

Comments: The type of power supply, expressed as text, for this piece of logistics transport equipment, such as diesel fuel or electricity.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="SpecifiedBirthAddress">SpecifiedBirthAddress</h1>

Type: rdf:Property

Comments: The birth address specified for this contact person.

Domains: 

[edi3:Person](#Person)


<h1 id="PayeeSpecifiedCreditorFinancialInstitution">PayeeSpecifiedCreditorFinancialInstitution</h1>

Type: rdf:Property

Comments: The creditor financial institution of the payee party specified for this trade settlement payment means.

Domains: 

[edi3:PaymentMeans](#PaymentMeans)


<h1 id="CategoryCode">CategoryCode</h1>

Type: rdf:Property

Comments: <br/>A code specifying a category for this transport person, such as a member of crew or passenger.<br/>The code specifying a category for this exchanged document.<br/>The code specifying the category of this referenced document.<br/>A code specifying a category for this cross-border regulatory procedure, such as the appendices of the CITES Convention.<br/>The code specifying the category for this logistics risk analysis result.<br/>A code specifying a category for this document authentication.<br/>The code specifying the category of this certified accreditation, such as driving or academic.<br/>A code specifying a category of this government registration.<br/>

Domains: 

[edi3:RiskAnalysisResult](#RiskAnalysisResult)
[edi3:Registration](#Registration)
[edi3:Authentication](#Authentication)
[edi3:RegulatoryProcedure](#RegulatoryProcedure)
[edi3:Accreditation](#Accreditation)
[edi3:Document](#Document)
[edi3:Person](#Person)


<h1 id="TariffClassFreightChargeTariffClassCode">TariffClassFreightChargeTariffClassCode</h1>

Type: rdf:Property

Comments: The code specifying the tariff class for this logistics service charge which represents an entry in a table of fixed charges [Reference United Nations Code List (UNCL) 5243].

Domains: 

[edi3:ServiceCharge](#ServiceCharge)


<h1 id="ContinuousIndicator">ContinuousIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not this specified period is continuous.

Domains: 

[edi3:Period](#Period)


<h1 id="TransportLogisticsPackage">TransportLogisticsPackage</h1>

Type: rdf:Property

Comments: <br/>Transport packages for this supply chain consignment.<br/>Transport packages for this referenced supply chain consignment.<br/>A transport package for this referenced supply chain consignment item.<br/>A transport package for this supply chain consignment item.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:Consignment](#Consignment)


<h1 id="ResponsibleAgencyActionGovernmentActionCode">ResponsibleAgencyActionGovernmentActionCode</h1>

Type: rdf:Property

Comments: A code specifying an action for a responsible agency in this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="ProductionSupplyChainEvent">ProductionSupplyChainEvent</h1>

Type: rdf:Property

Comments: The production event for this trade product instance.

Domains: 

[edi3:ProductInstance](#ProductInstance)


<h1 id="ScheduledOccurrenceDateTime">ScheduledOccurrenceDateTime</h1>

Type: rdf:Property

Comments: The scheduled date, time, date time, or other date time value of the occurrence of this transport event.

Domains: 

[edi3:Event](#Event)


<h1 id="RetainedVolumeUnitMeasure">RetainedVolumeUnitMeasure</h1>

Type: rdf:Property

Comments: The measure for this retained transport waste material component.

Domains: 

[edi3:MaterialComponent](#MaterialComponent)


<h1 id="AssociatedSpecifiedDirectPositionList">AssociatedSpecifiedDirectPositionList</h1>

Type: rdf:Property

Comments: <br/>The direct position list associated with this geographical multi-point.<br/>The direct position list associated with this geographical multi-curve.<br/>The direct position list associated with this geographical point.<br/>The direct position list associated with this geographical line.<br/>

Domains: 

[edi3:GeographicalPoint](#GeographicalPoint)
[edi3:GeographicalMultiCurve](#GeographicalMultiCurve)
[edi3:GeographicalMultiPoint](#GeographicalMultiPoint)
[edi3:GeographicalLine](#GeographicalLine)


<h1 id="ApplicableSpecifiedPeriod">ApplicableSpecifiedPeriod</h1>

Type: rdf:Property

Comments: <br/>A period applicable to this cross-border regulatory procedure.<br/>The period applicable for this supply chain supply plan.<br/>

Domains: 

[edi3:SupplyPlan](#SupplyPlan)
[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="PlannedQuantity">PlannedQuantity</h1>

Type: rdf:Property

Comments: The planned quantity in this supply chain supply plan.

Domains: 

[edi3:SupplyPlan](#SupplyPlan)


<h1 id="LatestDespatchedQuantity">LatestDespatchedQuantity</h1>

Type: rdf:Property

Comments: The latest quantity, at line level, despatched in this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="CargoGrossWeightWeightUnitMeasure">CargoGrossWeightWeightUnitMeasure</h1>

Type: rdf:Property

Comments: The measure of the total gross weight (mass) of all cargo loaded onto this logistics means of transport, including packaging but excluding any associated transport equipment.

Domains: 

[edi3:TransportMeans](#TransportMeans)


<h1 id="StatusDocumentStatusCode">StatusDocumentStatusCode</h1>

Type: rdf:Property

Comments: <br/>The code specifying the status for this referenced document.<br/>The code specifying the status of this exchanged document.<br/>

Domains: 

[edi3:Document](#Document)


<h1 id="ProjectedSupplyChainSupplyPlan">ProjectedSupplyChainSupplyPlan</h1>

Type: rdf:Property

Comments: A supply plan, at line level, projected for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="InsuranceValueAmount">InsuranceValueAmount</h1>

Type: rdf:Property

Comments: <br/>The monetary value of this supply chain consignment item as covered by an insurance policy.<br/>The monetary value of this supply chain consignment as covered by an insurance policy.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:Consignment](#Consignment)


<h1 id="ManufactureTradeCountry">ManufactureTradeCountry</h1>

Type: rdf:Property

Comments: The country of manufacture of this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="OffsetProcessingStatusText">OffsetProcessingStatusText</h1>

Type: rdf:Property

Comments: A status of an offset processing, expressed as text, for this exchanged document, such as the process offsetted by this document.

Domains: 

[edi3:Document](#Document)


<h1 id="ShippingSpecifiedPeriod">ShippingSpecifiedPeriod</h1>

Type: rdf:Property

Comments: The shipping period specified in this header trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="PriceCurrencyCurrencyCode">PriceCurrencyCurrencyCode</h1>

Type: rdf:Property

Comments: The code specifying the price currency for this header trade settlement.

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="DangerousGoodsNotifierTradeParty">DangerousGoodsNotifierTradeParty</h1>

Type: rdf:Property

Comments: The party responsible for providing the dangerous goods notification in accordance with the dangerous goods regulations relevant for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="CityIdentifier">CityIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique identifier of the city for this financial institution address, such as United Nations Location Code (UNLOCODE).<br/>The identifier of the city for this trade address, such as United Nations Location Code (UNLOCODE).<br/>

Domains: 

[edi3:Address](#Address)


<h1 id="NetWeightMeasure">NetWeightMeasure</h1>

Type: rdf:Property

Comments: <br/>The measure of the net weight of this logistics package, i.e. the weight (mass) of the contents.<br/>A measure of the net weight (mass) of this trade product.<br/>

Domains: 

[edi3:Product](#Product)
[edi3:Package](#Package)


<h1 id="RejectionResponseDateTime">RejectionResponseDateTime</h1>

Type: rdf:Property

Comments: A date, time, date time, or other date time value of a rejection response of the exchanged document.

Domains: 

[edi3:Document](#Document)


<h1 id="IncludedSpecifiedGeographicalMultiSurface">IncludedSpecifiedGeographicalMultiSurface</h1>

Type: rdf:Property

Comments: The geographical multi-surface included in this geographical feature.

Domains: 

[edi3:GeographicalFeature](#GeographicalFeature)


<h1 id="CreationSpecifiedBinaryFile">CreationSpecifiedBinaryFile</h1>

Type: rdf:Property

Comments: A specified binary file used to create this valuation breakdown statement.

Domains: 

[edi3:BreakdownStatement](#BreakdownStatement)


<h1 id="ImageBinaryObject">ImageBinaryObject</h1>

Type: rdf:Property

Comments: The image, expressed as a binary object, for this section segment.

Domains: 

[edi3:Segment](#Segment)


<h1 id="RiskFactorCode">RiskFactorCode</h1>

Type: rdf:Property

Comments: The code specifying a risk factor for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="InventoryManagerTradeParty">InventoryManagerTradeParty</h1>

Type: rdf:Property

Comments: <br/>An inventory manager party, at line level, for this trade delivery.<br/>An inventory manager party, at header level, for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="ConsignorProvidedBorderClearanceTransportInstructions">ConsignorProvidedBorderClearanceTransportInstructions</h1>

Type: rdf:Property

Comments: Border clearance instructions provided by the consignor for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="AlternativeSourceSystemIdentifier">AlternativeSourceSystemIdentifier</h1>

Type: rdf:Property

Comments: An alternative source system identifier for this geographical coordinate.

Domains: 

[edi3:GeographicalCoordinate](#GeographicalCoordinate)


<h1 id="AccessoryApplicableReferencedProduct">AccessoryApplicableReferencedProduct</h1>

Type: rdf:Property

Comments: A referenced accessory product applicable for this supply chain trade line item.

Domains: 

[edi3:TradeLineItem](#TradeLineItem)


<h1 id="ReceivedQuantity">ReceivedQuantity</h1>

Type: rdf:Property

Comments: The quantity, at line level, received for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="IndividualPackageQuantity">IndividualPackageQuantity</h1>

Type: rdf:Property

Comments: The quantity within the individual package, at line level, for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="InvoiceeTradeParty">InvoiceeTradeParty</h1>

Type: rdf:Property

Comments: <br/>The party to whom an invoice is issued for this header trade settlement.<br/>The party to whom an invoice is issued for this line trade settlement.<br/>

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="MinimumStockQuantity">MinimumStockQuantity</h1>

Type: rdf:Property

Comments: The minimum stock quantity in this CI supply chain inventory.

Domains: 

[edi3:Inventory](#Inventory)


<h1 id="ValueMeasure">ValueMeasure</h1>

Type: rdf:Property

Comments: <br/>The measure of the value of this spatial dimension.<br/>The measure value for this control setting parameter.<br/>The measure of the value for this monitoring sensor.<br/>The measured value for this work item dimension.<br/>The value of a measure for this calibrated measurement.<br/>The measure value for this operational parameter.<br/>A measure of a value for this product characteristic.<br/>The measure of a value for this communication event.<br/>The measure of the value for this product characteristic condition.<br/>

Domains: 

[edi3:Measurement](#Measurement)
[edi3:Condition](#Condition)
[edi3:Characteristic](#Characteristic)
[edi3:Event](#Event)
[edi3:Parameter](#Parameter)
[edi3:Dimension](#Dimension)
[edi3:Sensor](#Sensor)


<h1 id="ComponentWorkItemDimension">ComponentWorkItemDimension</h1>

Type: rdf:Property

Comments: A work item component dimension for this work item dimension.

Domains: 

[edi3:Dimension](#Dimension)


<h1 id="OriginalRequiredQuantity">OriginalRequiredQuantity</h1>

Type: rdf:Property

Comments: The number of originals required of this exchanged document.

Domains: 

[edi3:Document](#Document)


<h1 id="PollutionMeasure">PollutionMeasure</h1>

Type: rdf:Property

Comments: A measure of the pollution calculated for this emission.

Domains: 

[edi3:Emission](#Emission)


<h1 id="PreCarriageLogisticsTransportMovement">PreCarriageLogisticsTransportMovement</h1>

Type: rdf:Property

Comments: <br/>A pre-carriage logistics transport movement for this referenced supply chain consignment.<br/>A pre-carriage logistics transport movement for this supply chain consignment.<br/>

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="TypeDocumentCode">TypeDocumentCode</h1>

Type: rdf:Property

Comments: <br/>The code specifying the type of exchanged document.<br/>The code specifying the type of referenced document.<br/>The code specifying the type of this exchanged declaration.<br/>A code specifying a type of acknowledgement document.<br/>

Domains: 

[edi3:Declaration](#Declaration)
[edi3:Document](#Document)


<h1 id="DefinedTradeContact">DefinedTradeContact</h1>

Type: rdf:Property

Comments: <br/>A trade contact defined for this location party.<br/>A trade contact defined for this trade party.<br/>

Domains: 

[edi3:Party](#Party)


<h1 id="IncludedTradeTax">IncludedTradeTax</h1>

Type: rdf:Property

Comments: <br/>A tax included in this trade price.<br/>A tax included in this advance payment.<br/>

Domains: 

[edi3:Payment](#Payment)
[edi3:Price](#Price)


<h1 id="SpecifiedSubordinateLineTradeAgreement">SpecifiedSubordinateLineTradeAgreement</h1>

Type: rdf:Property

Comments: The trade agreement specified for this subordinate trade line item.

Domains: 

[edi3:TradeLineItem](#TradeLineItem)


<h1 id="ManufacturingFormattedDateTime">ManufacturingFormattedDateTime</h1>

Type: rdf:Property

Comments: <br/>The manufacturing date, time, date time, or other date time value for this piece of logistics transport equipment.<br/>The manufacturing date, time, date time, or other date time value for this logistics means of transport.<br/>

Domains: 

[edi3:TransportEquipment](#TransportEquipment)
[edi3:TransportMeans](#TransportMeans)


<h1 id="SpecifiedTransportPerson">SpecifiedTransportPerson</h1>

Type: rdf:Property

Comments: A transport related person specified for this location party.

Domains: 

[edi3:Party](#Party)


<h1 id="ResponsibleTradeParty">ResponsibleTradeParty</h1>

Type: rdf:Property

Comments: A trade party responsible for this transport service.

Domains: 

[edi3:Service](#Service)


<h1 id="ContentTypeCode">ContentTypeCode</h1>

Type: rdf:Property

Comments: A code specifying the content type of this product characteristic.

Domains: 

[edi3:Characteristic](#Characteristic)


<h1 id="RelationshipTypeCode">RelationshipTypeCode</h1>

Type: rdf:Property

Comments: A code specifying a type of relationship for this referenced product.

Domains: 

[edi3:Product](#Product)


<h1 id="StandardText">StandardText</h1>

Type: rdf:Property

Comments: The standard, expressed as text, for this trade product certification.

Domains: 

[edi3:Certification](#Certification)


<h1 id="TypeAddressTypeCode">TypeAddressTypeCode</h1>

Type: rdf:Property

Comments: A code specifying the type of this trade address, such as business address or home address.

Domains: 

[edi3:Address](#Address)


<h1 id="DeliverySupplyChainEvent">DeliverySupplyChainEvent</h1>

Type: rdf:Property

Comments: A delivery event for this supply chain supply plan.

Domains: 

[edi3:SupplyPlan](#SupplyPlan)


<h1 id="IncludedSectionSegment">IncludedSectionSegment</h1>

Type: rdf:Property

Comments: A segment included in this label section.

Domains: 

[edi3:Section](#Section)


<h1 id="MessageStandardSpecifiedDocumentContextParameter">MessageStandardSpecifiedDocumentContextParameter</h1>

Type: rdf:Property

Comments: The message standard document context parameter specified for this exchanged document context.

Domains: 

[edi3:Context](#Context)


<h1 id="AltimetricSystemIdentifier">AltimetricSystemIdentifier</h1>

Type: rdf:Property

Comments: The unique identifier of the system used for measuring the altitude.

Domains: 

[edi3:GeographicalCoordinate](#GeographicalCoordinate)


<h1 id="SequenceIdentifier">SequenceIdentifier</h1>

Type: rdf:Property

Comments: The sequence identifier for this instalment payment.

Domains: 

[edi3:Payment](#Payment)


<h1 id="ValueAllowedIndicator">ValueAllowedIndicator</h1>

Type: rdf:Property

Comments: <br/>The indication of whether or not this control setting parameter value is allowed.<br/>The indication of whether or not this operational parameter value is allowed.<br/>

Domains: 

[edi3:Parameter](#Parameter)


<h1 id="StorageInformationNote">StorageInformationNote</h1>

Type: rdf:Property

Comments: A storage information note for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="OccurrenceSpecifiedPeriod">OccurrenceSpecifiedPeriod</h1>

Type: rdf:Property

Comments: <br/>A specified period of time for the occurrence of this referenced transport event.<br/>A specified period of time during which this supply chain event occurs.<br/>A specified period of time during which this transport event occurs.<br/>

Domains: 

[edi3:Event](#Event)


<h1 id="FinalDestinationTradeCountry">FinalDestinationTradeCountry</h1>

Type: rdf:Property

Comments: <br/>The country of final destination, at header level, for this header trade delivery.<br/>The country of final destination, at line level, for line trade delivery.<br/>The final destination country for this supply chain consignment.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)
[edi3:Consignment](#Consignment)


<h1 id="CarrierProvidedInformationText">CarrierProvidedInformationText</h1>

Type: rdf:Property

Comments: Information, expressed as text, provided by the carrier for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="LicenceIdentifier">LicenceIdentifier</h1>

Type: rdf:Property

Comments: The identifier of a licence for this government registration.

Domains: 

[edi3:Registration](#Registration)


<h1 id="PaymentChannelPaymentMeansChannelCode">PaymentChannelPaymentMeansChannelCode</h1>

Type: rdf:Property

Comments: The code specifying the payment channel through which this trade settlement payment is to be processed (Reference United Nations Code List (UNCL) 4435).

Domains: 

[edi3:PaymentMeans](#PaymentMeans)


<h1 id="LanguageLanguageCode">LanguageLanguageCode</h1>

Type: rdf:Property

Comments: A code specifying a language for this trade party.

Domains: 

[edi3:Party](#Party)


<h1 id="CrewSpecifiedPersonalEffects">CrewSpecifiedPersonalEffects</h1>

Type: rdf:Property

Comments: Personal effects of an individual member of the crew for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="BrandRangeNameText">BrandRangeNameText</h1>

Type: rdf:Property

Comments: The brand range name, expressed as text, for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="DelaySpecifiedReferencedTransportEvent">DelaySpecifiedReferencedTransportEvent</h1>

Type: rdf:Property

Comments: A delay specified for this referenced transport event.

Domains: 

[edi3:Event](#Event)


<h1 id="ApplicableHeaderTradeDelivery">ApplicableHeaderTradeDelivery</h1>

Type: rdf:Property

Comments: A trade delivery header applicable to this supply chain trade transaction.

Domains: 

[edi3:TradeTransaction](#TradeTransaction)


<h1 id="GlobalExtensionIdentificationIdentifier">GlobalExtensionIdentificationIdentifier</h1>

Type: rdf:Property

Comments: A global extension identifier for this trade product, such as a prefix or a suffix.

Domains: 

[edi3:Product](#Product)


<h1 id="TitleText">TitleText</h1>

Type: rdf:Property

Comments: A title, expressed as text, for this specified binary file.

Domains: 

[edi3:BinaryFile](#BinaryFile)


<h1 id="CancellationReasonText">CancellationReasonText</h1>

Type: rdf:Property

Comments: A cancellation reason, expressed as text, in this financing request document.

Domains: 

[edi3:Document](#Document)


<h1 id="LineIdentifier">LineIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique identifier of a line in this referenced document.<br/>The unique identifier of this document line.<br/>

Domains: 

[edi3:Document](#Document)


<h1 id="AustralianSNIdentificationIdentifier">AustralianSNIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The Australian Small Network (SN) identifier as assigned by the Australian Payments Clearing Association (APCA) for this creditor financial institution.

Domains: 

[edi3:FinancialInstitution](#FinancialInstitution)


<h1 id="ActualTradeCurrencyExchange">ActualTradeCurrencyExchange</h1>

Type: rdf:Property

Comments: The actual trade currency exchange for this trade allowance charge.

Domains: 

[edi3:AllowanceCharge](#AllowanceCharge)


<h1 id="ConsignmentItemQuantity">ConsignmentItemQuantity</h1>

Type: rdf:Property

Comments: <br/>The number of consignment items separately defined for transport or customs purposes within this referenced supply chain consignment.<br/>The number of consignment items separately defined for transport or customs purposes within this supply chain consignment.<br/>

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="AssociatedReferencedLogisticsTransportEquipment">AssociatedReferencedLogisticsTransportEquipment</h1>

Type: rdf:Property

Comments: <br/>A piece of transport equipment associated with this referenced supply chain consignment item.<br/>A referenced piece of transport equipment associated with this supply chain consignment item.<br/>Referenced transport equipment associated with the dangerous goods.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:DangerousGoods](#DangerousGoods)


<h1 id="AtArrivalLogisticsTransportMovement">AtArrivalLogisticsTransportMovement</h1>

Type: rdf:Property

Comments: The logistics transport movement for this supply chain consignment at the point when the means of transport arrives in a country or at a regional border.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="GroupIdentificationIdentifier">GroupIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The group identifier in this financing request document.

Domains: 

[edi3:Document](#Document)


<h1 id="IndianFinancialSystemIdentificationIdentifier">IndianFinancialSystemIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique Indian Financial System Code identifier for this creditor financial institution.<br/>The unique Indian Financial System Code identifier for this debtor financial institution.<br/>

Domains: 

[edi3:FinancialInstitution](#FinancialInstitution)


<h1 id="IncludedProductTypeQuantity">IncludedProductTypeQuantity</h1>

Type: rdf:Property

Comments: The number of different product types included at the next lower level in this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="FirstSignatoryDocumentAuthentication">FirstSignatoryDocumentAuthentication</h1>

Type: rdf:Property

Comments: The first or primary signature that authenticates this exchanged document.

Domains: 

[edi3:Document](#Document)


<h1 id="PayeeTradeParty">PayeeTradeParty</h1>

Type: rdf:Property

Comments: <br/>The payee party for this payment trade settlement.<br/>A payee party in these trade payment terms.<br/>A payee party for this header trade settlement.<br/>

Domains: 

[edi3:TradeSettlement](#TradeSettlement)
[edi3:PaymentTerms](#PaymentTerms)


<h1 id="EmergencyTemperatureMeasurement">EmergencyTemperatureMeasurement</h1>

Type: rdf:Property

Comments: The measurement of the emergency temperature of these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="MarketIdentifier">MarketIdentifier</h1>

Type: rdf:Property

Comments: The unique identifier of the currency exchange market from which the exchange rate is taken for trade purposes.

Domains: 

[edi3:CurrencyExchange](#CurrencyExchange)


<h1 id="BrandNameText">BrandNameText</h1>

Type: rdf:Property

Comments: The brand name, expressed as text, for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="TareWeightWeightUnitMeasure">TareWeightWeightUnitMeasure</h1>

Type: rdf:Property

Comments: <br/>The measure of the tare weight (mass) of this logistics means of transport which is the weight (mass) including permanent equipment but excluding goods and loose accessories.<br/>The measure of the tare weight (mass) of this piece of logistics transport equipment which is the weight (mass) including permanent equipment but excluding goods and loose accessories.<br/>

Domains: 

[edi3:TransportEquipment](#TransportEquipment)
[edi3:TransportMeans](#TransportMeans)


<h1 id="StaySpecifiedPeriod">StaySpecifiedPeriod</h1>

Type: rdf:Property

Comments: A period of stay at this logistics location.

Domains: 

[edi3:Location](#Location)


<h1 id="TargetCurrencyCurrencyCode">TargetCurrencyCurrencyCode</h1>

Type: rdf:Property

Comments: The code specifying the target currency of a trade related currency conversion.

Domains: 

[edi3:CurrencyExchange](#CurrencyExchange)


<h1 id="SpecifiedProjectPerson">SpecifiedProjectPerson</h1>

Type: rdf:Property

Comments: The project person specified for this requesting party.

Domains: 

[edi3:Party](#Party)


<h1 id="ExcludingTaxesLineTotalAmount">ExcludingTaxesLineTotalAmount</h1>

Type: rdf:Property

Comments: A monetary value of the total of all line amounts, excluding all duties and taxes, being reported in this trade settlement header monetary summation.

Domains: 

[edi3:MonetarySummation](#MonetarySummation)


<h1 id="PurposeCode">PurposeCode</h1>

Type: rdf:Property

Comments: <br/>A code specifying the purpose of this product certificate.<br/>The code specifying the purpose of this specified period.<br/>

Domains: 

[edi3:Period](#Period)
[edi3:Certificate](#Certificate)


<h1 id="RequiredAppliedChemicalTreatment">RequiredAppliedChemicalTreatment</h1>

Type: rdf:Property

Comments: A chemical treatment applied as required by this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="ShapeTypeText">ShapeTypeText</h1>

Type: rdf:Property

Comments: The type of shape, expressed as text, such as a semi-circle, for this geographical object characteristic.

Domains: 

[edi3:GeographicalObjectCharacteristic](#GeographicalObjectCharacteristic)


<h1 id="PaymentArrangementTransportServicePaymentArrangementCode">PaymentArrangementTransportServicePaymentArrangementCode</h1>

Type: rdf:Property

Comments: <br/>The code specifying the payment arrangement for this logistics service charge [Reference United Nations Code List (UNCL) 4237].<br/>The code specifying the payment arrangements for this supply chain consignment.<br/>The code specifying the payment arrangement for this transport service.<br/>

Domains: 

[edi3:ServiceCharge](#ServiceCharge)
[edi3:Consignment](#Consignment)
[edi3:Service](#Service)


<h1 id="TotalPackageSpecifiedQuantity">TotalPackageSpecifiedQuantity</h1>

Type: rdf:Property

Comments: The total package quantity specified in this exchanged declaration.

Domains: 

[edi3:Declaration](#Declaration)


<h1 id="StartIdentifier">StartIdentifier</h1>

Type: rdf:Property

Comments: The identifier of the start of this specified range.

Domains: 

[edi3:Range](#Range)


<h1 id="QuantityDiscrepancyNatureCode">QuantityDiscrepancyNatureCode</h1>

Type: rdf:Property

Comments: The code specifying the nature of the discrepancy of the quantity, at line level, for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="TransportEquipmentSplitGoodsIndicator">TransportEquipmentSplitGoodsIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not the goods in this supply chain consignment are split across more than one piece of transport equipment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="PaymentCurrencyCurrencyCode">PaymentCurrencyCurrencyCode</h1>

Type: rdf:Property

Comments: <br/>The code specifying the payment currency for this header trade settlement.<br/>The code specifying the currency for this payment trade settlement.<br/>

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="SpecifiedCancellationStatus">SpecifiedCancellationStatus</h1>

Type: rdf:Property

Comments: A status of a cancellation specified for this financing request document, such as accepted.

Domains: 

[edi3:Document](#Document)


<h1 id="ActualFormattedDateTime">ActualFormattedDateTime</h1>

Type: rdf:Property

Comments: An actual date, time, date time, or other date time value of this financial booking.

Domains: 

[edi3:Booking](#Booking)


<h1 id="ItineraryStopTransportEvent">ItineraryStopTransportEvent</h1>

Type: rdf:Property

Comments: An itinerary stop event for this transport route, such as a port call in a vessel schedule.

Domains: 

[edi3:Route](#Route)


<h1 id="IncludedReferencedSupplyChainConsignment">IncludedReferencedSupplyChainConsignment</h1>

Type: rdf:Property

Comments: A referenced consignment included in this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="ShipFromTradeParty">ShipFromTradeParty</h1>

Type: rdf:Property

Comments: <br/>The ship from party, at header level, for this trade delivery.<br/>The ship from party for this supply chain consignment.<br/>The ship from party, at line level, for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)
[edi3:Consignment](#Consignment)


<h1 id="TrackingSystemIdentifier">TrackingSystemIdentifier</h1>

Type: rdf:Property

Comments: An identifier for a tracking system of this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="PackagingDangerLevelDangerousGoodsPackagingLevelCode">PackagingDangerLevelDangerousGoodsPackagingLevelCode</h1>

Type: rdf:Property

Comments: The code specifying the level of danger that the packaging of these dangerous goods must cover for transport purposes.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="IssuerAssignedIdentificationIdentifier">IssuerAssignedIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The unique issuer assigned identifier for this referenced document.

Domains: 

[edi3:Document](#Document)


<h1 id="RemarksText">RemarksText</h1>

Type: rdf:Property

Comments: <br/>A remark, expressed as text, regarding this referenced document.<br/>A remark, expressed as text, regarding this exchanged document.<br/>

Domains: 

[edi3:Document](#Document)


<h1 id="TaxExemptionAuthorityIdentificationIdentifier">TaxExemptionAuthorityIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The unique tax exemption authority identifier for this trade tax.

Domains: 

[edi3:Tax](#Tax)


<h1 id="SupplySpecifiedSupplyChainSchedule">SupplySpecifiedSupplyChainSchedule</h1>

Type: rdf:Property

Comments: A supply (replenishment) schedule, specified at line level, for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="BICIdentificationIdentifier">BICIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The Bank Identifier Code (BIC) as defined by ISO 9362 (Banking telecommunication messages, Bank Identifier Codes) for this financial identity.

Domains: 

[edi3:Identity](#Identity)


<h1 id="LoadingInspectionSpecifiedTransportInstructions">LoadingInspectionSpecifiedTransportInstructions</h1>

Type: rdf:Property

Comments: Loading inspection instructions specified for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="StartDateTime">StartDateTime</h1>

Type: rdf:Property

Comments: <br/>The date, time, date time or other date time value for the start of this specified period of time.<br/>The date, time, date time or other date time value for the start of this available period of time.<br/>

Domains: 

[edi3:Period](#Period)


<h1 id="DeliveryApplicableInstructedTemperature">DeliveryApplicableInstructedTemperature</h1>

Type: rdf:Property

Comments: The instructed temperature for delivery applicable to these handling instructions.

Domains: 

[edi3:Instructions](#Instructions)


<h1 id="ManufacturerTradeParty">ManufacturerTradeParty</h1>

Type: rdf:Property

Comments: <br/>The manufacturer party for this OEM equipment.<br/>The manufacturer party of this monitoring IOT device.<br/>A manufacturer party for this trade product.<br/>The manufacturer party for this monitoring sensor.<br/>The party which manufactured this supply chain consignment item.<br/>The manufacturer party specified for this piece of logistics transport equipment.<br/>The manufacturer party for this logistics means of transport.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:Equipment](#Equipment)
[edi3:TransportEquipment](#TransportEquipment)
[edi3:Product](#Product)
[edi3:TransportMeans](#TransportMeans)
[edi3:Sensor](#Sensor)
[edi3:IOTDevice](#IOTDevice)


<h1 id="FOBAmount">FOBAmount</h1>

Type: rdf:Property

Comments: <br/>The monetary value for this supply chain consignment item as calculated under FOB (Free On Board) delivery terms.<br/>The monetary value that has to be, or has been, paid for this supply chain consignment as calculated under FOB (Free on Board) delivery terms.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:Consignment](#Consignment)


<h1 id="OtherChargeAmount">OtherChargeAmount</h1>

Type: rdf:Property

Comments: A monetary value added or subtracted from the total invoice price not previously taken into account for this cross-border customs valuation.

Domains: 

[edi3:CustomsValuation](#CustomsValuation)


<h1 id="AttachmentBinaryObject">AttachmentBinaryObject</h1>

Type: rdf:Property

Comments: A binary object that is attached or otherwise appended to this referenced document.

Domains: 

[edi3:Document](#Document)


<h1 id="PlannedDischargedVolumeUnitMeasure">PlannedDischargedVolumeUnitMeasure</h1>

Type: rdf:Property

Comments: The planned measure for this discharged transport waste material component.

Domains: 

[edi3:MaterialComponent](#MaterialComponent)


<h1 id="PurchaseSpecifiedTradeAccountingAccount">PurchaseSpecifiedTradeAccountingAccount</h1>

Type: rdf:Property

Comments: <br/>A purchase accounting account specified for this line trade settlement.<br/>A purchase accounting account specified for this header trade settlement.<br/>

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="ActualAmount">ActualAmount</h1>

Type: rdf:Property

Comments: <br/>An actual monetary value of the trade allowance charge.<br/>The actual monetary value of the applied allowance charge.<br/>An actual monetary value added or subtracted as a result of this delivery adjustment.<br/>An actual monetary value added or subtracted as a result of this financial adjustment.<br/>

Domains: 

[edi3:Adjustment](#Adjustment)
[edi3:AllowanceCharge](#AllowanceCharge)


<h1 id="ResponsibleAgencyInvolvementResponsibleGovernmentAgencyInvolvementCode">ResponsibleAgencyInvolvementResponsibleGovernmentAgencyInvolvementCode</h1>

Type: rdf:Property

Comments: A code specifying a responsible agency involved in this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="LoadedCargoMeasure">LoadedCargoMeasure</h1>

Type: rdf:Property

Comments: The measure of the cargo loaded onto this logistics means of transport, such as the number of barrels of oil or other quantity of breakbulk cargo.

Domains: 

[edi3:TransportMeans](#TransportMeans)


<h1 id="FrequencyCode">FrequencyCode</h1>

Type: rdf:Property

Comments: <br/>The code specifying a frequency for this supply chain event.<br/>A code specifying a frequency in these supply chain forecast terms.<br/>

Domains: 

[edi3:Event](#Event)
[edi3:ForecastTerms](#ForecastTerms)


<h1 id="CustomerSupplyChainInventory">CustomerSupplyChainInventory</h1>

Type: rdf:Property

Comments: Supply chain customer inventory, at line level, for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="SalesConditionsReferencedDocument">SalesConditionsReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>A sales conditions document referenced in this header trade agreement.<br/>A sales conditions document referenced by this line trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="UltimatePayeeTradeParty">UltimatePayeeTradeParty</h1>

Type: rdf:Property

Comments: An ultimate payee party in this header trade settlement.

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="FactoringListReferencedDocument">FactoringListReferencedDocument</h1>

Type: rdf:Property

Comments: A factoring list document referenced in this header trade settlement.

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="SubDivisionBranchFinancialInstitution">SubDivisionBranchFinancialInstitution</h1>

Type: rdf:Property

Comments: <br/>The branch financial institution for this debtor financial institution.<br/>The branch financial institution for this creditor financial institution.<br/>

Domains: 

[edi3:FinancialInstitution](#FinancialInstitution)


<h1 id="MaximumStockQuantity">MaximumStockQuantity</h1>

Type: rdf:Property

Comments: The maximum stock quantity in this CI supply chain inventory.

Domains: 

[edi3:Inventory](#Inventory)


<h1 id="ProprietaryIdentificationIdentifier">ProprietaryIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The proprietary identifier for this financing financial account.<br/>The unique proprietary identifier for this creditor financial account.<br/>The unique proprietary identifier for this debtor financial account.<br/>

Domains: 

[edi3:FinancialAccount](#FinancialAccount)


<h1 id="UsedCSEngineeringCoordinateReferenceSystem">UsedCSEngineeringCoordinateReferenceSystem</h1>

Type: rdf:Property

Comments: <br/>The CS (Coordinate System) engineering coordinate reference system used for this specified geographical feature.<br/>The CS (Coordinate System) engineering coordinate reference system used for this geographical coordinate.<br/>

Domains: 

[edi3:GeographicalCoordinate](#GeographicalCoordinate)
[edi3:GeographicalFeature](#GeographicalFeature)


<h1 id="TypeGoodsTypeCode">TypeGoodsTypeCode</h1>

Type: rdf:Property

Comments: <br/>The code specifying the type of supply chain consignment item.<br/>The code specifying the type of referenced supply chain consignment item.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)


<h1 id="ApplicableHeaderBalanceOut">ApplicableHeaderBalanceOut</h1>

Type: rdf:Property

Comments: A header balance out applicable to this trade settlement header monetary summation.

Domains: 

[edi3:MonetarySummation](#MonetarySummation)


<h1 id="TREMIdentifier">TREMIdentifier</h1>

Type: rdf:Property

Comments: The unique TRansport EMergency (TREM) card identifier for these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="PlannedShipFromDeliverySupplyChainEvent">PlannedShipFromDeliverySupplyChainEvent</h1>

Type: rdf:Property

Comments: The event of the planned ship from delivery, at header level, for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="BuyerDeductibleTaxSpecifiedTradeAccountingAccount">BuyerDeductibleTaxSpecifiedTradeAccountingAccount</h1>

Type: rdf:Property

Comments: The buyer deductible tax specified accounting account for this trade related tax, levy or duty.

Domains: 

[edi3:Tax](#Tax)


<h1 id="TheoreticalWeightWeightUnitMeasure">TheoreticalWeightWeightUnitMeasure</h1>

Type: rdf:Property

Comments: The measure, at line level, of the theoretical weight of this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="SpecialDeviceTypeText">SpecialDeviceTypeText</h1>

Type: rdf:Property

Comments: The special device type, expressed as text, for this telecommunication communication, such as a device for the hearing impaired.

Domains: 

[edi3:Communication](#Communication)


<h1 id="LocationFinancialInstitutionAddress">LocationFinancialInstitutionAddress</h1>

Type: rdf:Property

Comments: <br/>The location address for this debtor financial institution.<br/>The location address for this branch of a financial institution.<br/>The location address for this creditor financial institution.<br/>

Domains: 

[edi3:FinancialInstitution](#FinancialInstitution)


<h1 id="ServiceSupplyTradeCountry">ServiceSupplyTradeCountry</h1>

Type: rdf:Property

Comments: The country or country sub-division where a service was supplied for this trade tax.

Domains: 

[edi3:Tax](#Tax)


<h1 id="QuotaIdentifier">QuotaIdentifier</h1>

Type: rdf:Property

Comments: A quota identifier for this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="RegulationConformityIdentifier">RegulationConformityIdentifier</h1>

Type: rdf:Property

Comments: An identifier assigned to indicate conformity with a regulation or standard for this trade product, such as "CE" which declares that the product conforms with the essential requirements of the applicable EC directives.

Domains: 

[edi3:Product](#Product)


<h1 id="AddedAdjustmentPercent">AddedAdjustmentPercent</h1>

Type: rdf:Property

Comments: The adjustment added, expressed as a percentage, for this cross-border customs valuation.

Domains: 

[edi3:CustomsValuation](#CustomsValuation)


<h1 id="SpecifiedValidationStatus">SpecifiedValidationStatus</h1>

Type: rdf:Property

Comments: The status of the validation specified for this financing request document, such as error.

Domains: 

[edi3:Document](#Document)


<h1 id="JobTitleText">JobTitleText</h1>

Type: rdf:Property

Comments: The job title, position or designation, expressed as text, of this trade contact within an organization, such as Director, Software Engineer, Purchasing Manager.

Domains: 

[edi3:Contact](#Contact)


<h1 id="RoleCode">RoleCode</h1>

Type: rdf:Property

Comments: <br/>A code specifying a role of this location party.<br/>A code specifying a role of this transport person.<br/>

Domains: 

[edi3:Party](#Party)
[edi3:Person](#Person)


<h1 id="ExcessTransportTransportService">ExcessTransportTransportService</h1>

Type: rdf:Property

Comments: An excess transport service for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="DocumentURLIdentifier">DocumentURLIdentifier</h1>

Type: rdf:Property

Comments: The Uniform Resource Locator (URL) of the web location of the document for this supply chain trade transaction.

Domains: 

[edi3:TradeTransaction](#TradeTransaction)


<h1 id="WeightMeasure">WeightMeasure</h1>

Type: rdf:Property

Comments: A measure of the weight of this supply chain packaging.

Domains: 

[edi3:Packaging](#Packaging)


<h1 id="CustomsRequiredInvoiceReferencedDocument">CustomsRequiredInvoiceReferencedDocument</h1>

Type: rdf:Property

Comments: A referenced invoice document required by customs for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="RequestedRelatedReferencedTransportService">RequestedRelatedReferencedTransportService</h1>

Type: rdf:Property

Comments: A requested service related to this transport event.

Domains: 

[edi3:Event](#Event)


<h1 id="ContractReferencedDocument">ContractReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>A referenced contract document for this supply chain supply plan.<br/>A contract document referenced in this line trade agreement.<br/>A contract document referenced in this header trade agreement.<br/>

Domains: 

[edi3:SupplyPlan](#SupplyPlan)
[edi3:TradeAgreement](#TradeAgreement)


<h1 id="SignalSourceAvailableQuantity">SignalSourceAvailableQuantity</h1>

Type: rdf:Property

Comments: The quantity of signal source available for this geographical coordinate source system.

Domains: 

[edi3:CoordinateSourceSystem](#CoordinateSourceSystem)


<h1 id="ScheduledOccurrenceSpecifiedPeriod">ScheduledOccurrenceSpecifiedPeriod</h1>

Type: rdf:Property

Comments: The scheduled period of time specified for the occurrence of this transport event.

Domains: 

[edi3:Event](#Event)


<h1 id="PurposeMessageFunctionCode">PurposeMessageFunctionCode</h1>

Type: rdf:Property

Comments: A code specifying the purpose of this exchanged document, such as request or reminder.

Domains: 

[edi3:Document](#Document)


<h1 id="OrderResponseReferencedDocument">OrderResponseReferencedDocument</h1>

Type: rdf:Property

Comments: The order response document referenced in this header trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="ShipmentIdentificationIdentifier">ShipmentIdentificationIdentifier</h1>

Type: rdf:Property

Comments: An identifier, such as the Unique Consignment Reference (UCR), for the shipment which is the subject of this supply chain trade transaction.

Domains: 

[edi3:TradeTransaction](#TradeTransaction)


<h1 id="ItalianDomesticIdentificationIdentifier">ItalianDomesticIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique Italian Domestic Identification Code identifier as assigned by the Associazione Bancaria Italiana (ABI) for this debtor financial institution.<br/>The unique Italian Domestic Identification Code identifier as assigned by the Associazione Bancaria Italiana (ABI) for this creditor financial institution.<br/>

Domains: 

[edi3:FinancialInstitution](#FinancialInstitution)


<h1 id="WarehouseArrivalDateTime">WarehouseArrivalDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time or other date time value of the arrival of this supply chain consignment at a warehouse.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="IncludedSupplyChainPackaging">IncludedSupplyChainPackaging</h1>

Type: rdf:Property

Comments: <br/>Packaging included, at line level, in this trade delivery.<br/>Packaging included in this subordinate line trade delivery.<br/>Packaging, at header level, included in this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="StowagePositionIdentifier">StowagePositionIdentifier</h1>

Type: rdf:Property

Comments: The stowage position identifier for this piece of logistics transport equipment.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="CompleteDeliveryIndicator">CompleteDeliveryIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not a transport waste material delivery is complete.

Domains: 

[edi3:Material](#Material)


<h1 id="RegulationDangerousGoodsRegulationCode">RegulationDangerousGoodsRegulationCode</h1>

Type: rdf:Property

Comments: The code specifying a regulation applicable to these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="ConversionRate">ConversionRate</h1>

Type: rdf:Property

Comments: The rate factor used for conversion from the source currency to the target currency for trade purposes.

Domains: 

[edi3:CurrencyExchange](#CurrencyExchange)


<h1 id="GroupedTransactionTotalAmount">GroupedTransactionTotalAmount</h1>

Type: rdf:Property

Comments: A total monetary value of grouped transactions in this financing request document.

Domains: 

[edi3:Document](#Document)


<h1 id="DescriptionText">DescriptionText</h1>

Type: rdf:Property

Comments: <br/>The textual description of these quarantine instructions.<br/>A textual description of this specified binary file.<br/>A textual description of this header balance out.<br/>A textual description of this referenced logistics package.<br/>A textual description of this logistics service charge.<br/>A textual description of this logistics related location.<br/>The textual description of this procuring project.<br/>A textual description of these trade payment terms.<br/>A textual description of this identified fault.<br/>The textual description of this transport service.<br/>A textual description of this registered tax.<br/>A textual description of this product certificate.<br/>A textual description of this logistics package.<br/>A textual description of this payment balance out.<br/>A textual description of these trade delivery terms.<br/>A textual description of this specified period of time.<br/>A textual description of this supply chain schedule.<br/>A textual description of these transport instructions.<br/>A textual description of these disposal instructions.<br/>The textual description of this available period.<br/>The textual description for this specified observation.<br/>A textual description of this valuation breakdown statement.<br/>The textual description of this work item dimension.<br/>The textual description of this trade settlement financial card.<br/>A textual description of this trade party.<br/>A textual description for this referenced product.<br/>A textual description of this operational parameter.<br/>A textual description of this product characteristic.<br/>The textual description of this transport event.<br/>A textual description of this stores inventory item.<br/>The textual description of the applied allowance charge.<br/>A textual description of these temperature setting instructions.<br/>A textual description of this spatial dimension.<br/>A textual description of this header trade settlement.<br/>A textual description of this measurement.<br/>A textual description of this supply chain packaging.<br/>A textual description of these delivery instructions.<br/>The textual description of this logistics risk analysis result.<br/>A textual description of this supply chain event.<br/>The textual description of this logistics status.<br/>A textual description of these handling instructions.<br/>A textual description of these specified personal effects.<br/>The textual description of this specified geographical feature.<br/>A textual description of this control setting parameter.<br/>A textual description for this transport waste material component.<br/>The textual description of this transport route.<br/>The textual description of this document status.<br/>A textual description of this material goods characteristic.<br/>A textual description for this trade product.<br/>A textual description of this trade product feature.<br/>The textual description of this work item quantity analysis.<br/>The textual description of this requesting party.<br/>The textual description of this certified accreditation.<br/>A textual description of this communication event.<br/>The textual description of these haulage instructions.<br/>A textual description of this exchanged document.<br/>The textual description for this geographical object characteristic.<br/>

Domains: 

[edi3:Measurement](#Measurement)
[edi3:PersonalEffects](#PersonalEffects)
[edi3:AllowanceCharge](#AllowanceCharge)
[edi3:Product](#Product)
[edi3:Fault](#Fault)
[edi3:Tax](#Tax)
[edi3:PaymentTerms](#PaymentTerms)
[edi3:GeographicalFeature](#GeographicalFeature)
[edi3:Document](#Document)
[edi3:Feature](#Feature)
[edi3:BreakdownStatement](#BreakdownStatement)
[edi3:RiskAnalysisResult](#RiskAnalysisResult)
[edi3:FinancialCard](#FinancialCard)
[edi3:Party](#Party)
[edi3:ServiceCharge](#ServiceCharge)
[edi3:MaterialComponent](#MaterialComponent)
[edi3:GeographicalObjectCharacteristic](#GeographicalObjectCharacteristic)
[edi3:Accreditation](#Accreditation)
[edi3:QuantityAnalysis](#QuantityAnalysis)
[edi3:BalanceOut](#BalanceOut)
[edi3:Route](#Route)
[edi3:Status](#Status)
[edi3:GoodsCharacteristic](#GoodsCharacteristic)
[edi3:DeliveryTerms](#DeliveryTerms)
[edi3:Characteristic](#Characteristic)
[edi3:Period](#Period)
[edi3:Service](#Service)
[edi3:Instructions](#Instructions)
[edi3:Dimension](#Dimension)
[edi3:BinaryFile](#BinaryFile)
[edi3:Project](#Project)
[edi3:TradeSettlement](#TradeSettlement)
[edi3:Schedule](#Schedule)
[edi3:Packaging](#Packaging)
[edi3:Observation](#Observation)
[edi3:Event](#Event)
[edi3:Parameter](#Parameter)
[edi3:Package](#Package)
[edi3:Inventory](#Inventory)
[edi3:Location](#Location)
[edi3:Certificate](#Certificate)


<h1 id="SpecifiedTradeSettlementPaymentMeans">SpecifiedTradeSettlementPaymentMeans</h1>

Type: rdf:Property

Comments: <br/>The trade settlement payment means specified for this logistics service charge.<br/>A payment means specified for this header trade settlement.<br/>The payment means specified for this payment trade settlement.<br/>

Domains: 

[edi3:TradeSettlement](#TradeSettlement)
[edi3:ServiceCharge](#ServiceCharge)


<h1 id="FunctionDescriptionText">FunctionDescriptionText</h1>

Type: rdf:Property

Comments: A textual description of a function for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="RequisitionerReferencedDocument">RequisitionerReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>A requisitioner document referenced in this line trade agreement.<br/>A requisitioner document referenced in this header trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="AxisNameText">AxisNameText</h1>

Type: rdf:Property

Comments: An axis name, expressed as text, for this geographical grid.

Domains: 

[edi3:GeographicalGrid](#GeographicalGrid)


<h1 id="ConveyanceFacilityRelatedLogisticsLocation">ConveyanceFacilityRelatedLogisticsLocation</h1>

Type: rdf:Property

Comments: A location of a conveyance facility related to this transport event.

Domains: 

[edi3:Event](#Event)


<h1 id="TypeLocationFunctionCode">TypeLocationFunctionCode</h1>

Type: rdf:Property

Comments: <br/>The code specifying the type of subordinate of a subordinate location.<br/>The code specifying the type of subordinate location.<br/>A code specifying the type of transport service location.<br/>A code specifying the type of this logistics related location.<br/>

Domains: 

[edi3:Location](#Location)


<h1 id="TradedParcelIdentifier">TradedParcelIdentifier</h1>

Type: rdf:Property

Comments: A traded parcel identifier for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="TotalConsignmentValueAmount">TotalConsignmentValueAmount</h1>

Type: rdf:Property

Comments: The total monetary value for a consignment for this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="AvailableQuantity">AvailableQuantity</h1>

Type: rdf:Property

Comments: The quantity, at line level, available for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="ConsignorAgentTradeParty">ConsignorAgentTradeParty</h1>

Type: rdf:Property

Comments: The party authorized to act for or on behalf of the consignor for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="ActualDespatchSupplyChainEvent">ActualDespatchSupplyChainEvent</h1>

Type: rdf:Property

Comments: <br/>An actual despatch event, at header level, for this trade delivery.<br/>An actual despatch event, at line level, for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="CHIPSUniversalIdentificationIdentifier">CHIPSUniversalIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The (United States) Clearing House Interbank Payments System (CHIPS) Universal Identification (UID) as assigned by the New York Clearing House for this financial identity.<br/>The unique (United States) Clearing House Interbank Payments System (CHIPS) Universal Identification (UID) as assigned by the New York Clearing House for this debtor financial institution.<br/>The unique (United States) Clearing House Interbank Payments System (CHIPS) Universal Identification (UID) as assigned by the New York Clearing House for this creditor financial institution.<br/>

Domains: 

[edi3:FinancialInstitution](#FinancialInstitution)
[edi3:Identity](#Identity)


<h1 id="AdditionalSecurityMeasuresApplicableNote">AdditionalSecurityMeasuresApplicableNote</h1>

Type: rdf:Property

Comments: A note providing additional security measures applicable to this transport event.

Domains: 

[edi3:Event](#Event)


<h1 id="SpecifiedNote">SpecifiedNote</h1>

Type: rdf:Property

Comments: A note specified for this trade contact.

Domains: 

[edi3:Contact](#Contact)


<h1 id="MarketingTradeProductFeature">MarketingTradeProductFeature</h1>

Type: rdf:Property

Comments: A marketing feature of this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="InclusiveIndicator">InclusiveIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not the start and end dates are included in this specified period.

Domains: 

[edi3:Period](#Period)


<h1 id="StreetNameText">StreetNameText</h1>

Type: rdf:Property

Comments: <br/>The name, expressed as text, of the street or thoroughfare for this financial institution address.<br/>A name, expressed as text, of a street or thoroughfare for this trade address.<br/>

Domains: 

[edi3:Address](#Address)


<h1 id="ConsigneeTradeParty">ConsigneeTradeParty</h1>

Type: rdf:Property

Comments: <br/>The consignee party for this supply chain consignment.<br/>The consignee party for this referenced supply chain consignment.<br/>

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="AppliedFromLogisticsLocation">AppliedFromLogisticsLocation</h1>

Type: rdf:Property

Comments: The start location from which this logistics service charge should be applied.

Domains: 

[edi3:ServiceCharge](#ServiceCharge)


<h1 id="CommodityConsolidatorAgentTradeParty">CommodityConsolidatorAgentTradeParty</h1>

Type: rdf:Property

Comments: The commodity consolidator agent party for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="CommentText">CommentText</h1>

Type: rdf:Property

Comments: <br/>A comment, expressed as text, for this work item group.<br/>A comment, expressed as text, for this valuation breakdown statement.<br/>A comment, expressed as text, for this basic work item.<br/>

Domains: 

[edi3:WorkItem](#WorkItem)
[edi3:BreakdownStatement](#BreakdownStatement)


<h1 id="IssuingPartyIdentifier">IssuingPartyIdentifier</h1>

Type: rdf:Property

Comments: The identifier for the party issuing this product certificate.

Domains: 

[edi3:Certificate](#Certificate)


<h1 id="SubordinateLineIdentifier">SubordinateLineIdentifier</h1>

Type: rdf:Property

Comments: <br/>An identifier of a subordinate line of this document line.<br/>The identifier of the subordinate line of this referenced document.<br/>

Domains: 

[edi3:Document](#Document)


<h1 id="EarliestOccurrenceDateTime">EarliestOccurrenceDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time, or other date time value of the earliest occurrence of this supply chain event.

Domains: 

[edi3:Event](#Event)


<h1 id="ActualPenaltyAmount">ActualPenaltyAmount</h1>

Type: rdf:Property

Comments: A monetary value of the actual penalty in these trade payment penalty terms.

Domains: 

[edi3:PaymentPenaltyTerms](#PaymentPenaltyTerms)


<h1 id="JapanFinancialInstitutionCommonIdentificationIdentifier">JapanFinancialInstitutionCommonIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The Japan Financial Institution Common identifier as assigned by the Japanese Bankers Association for this debtor financial institution.<br/>The Japan Financial Institution Common identifier as assigned by the Japanese Bankers Association for this creditor financial institution.<br/>

Domains: 

[edi3:FinancialInstitution](#FinancialInstitution)


<h1 id="OrderApplicableTradeCurrencyExchange">OrderApplicableTradeCurrencyExchange</h1>

Type: rdf:Property

Comments: The currency exchange applicable to the order currency in this header trade settlement.

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="RequestedEffectiveDateTime">RequestedEffectiveDateTime</h1>

Type: rdf:Property

Comments: The requested effective date, time, date time or other date time value for this product certificate.

Domains: 

[edi3:Certificate](#Certificate)


<h1 id="ContractualLanguageCode">ContractualLanguageCode</h1>

Type: rdf:Property

Comments: <br/>The code specifying the contractual language for this work item quantity analysis.<br/>The code specifying the contractual language for this work item complex description.<br/>The code specifying the contractual language for this basic work item.<br/>The code specifying the contractual language for this grouped work item.<br/>The code specifying the contractual language for this work item dimension.<br/>The code specifying the contractual language for this specification response.<br/>The code specifying the contractual language for this valuation breakdown statement.<br/>The code specifying the contractual language for this specification query.<br/>

Domains: 

[edi3:Response](#Response)
[edi3:Query](#Query)
[edi3:ComplexDescription](#ComplexDescription)
[edi3:Dimension](#Dimension)
[edi3:QuantityAnalysis](#QuantityAnalysis)
[edi3:WorkItem](#WorkItem)
[edi3:BreakdownStatement](#BreakdownStatement)


<h1 id="ConsumptionReportReferencedDocument">ConsumptionReportReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>The consumption report document, at header level, referenced for this trade delivery.<br/>The consumption report document, at line level, referenced from this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="LoadingReportedTransportEvent">LoadingReportedTransportEvent</h1>

Type: rdf:Property

Comments: A transport loading event reported for this logistics status.

Domains: 

[edi3:Status](#Status)


<h1 id="SealedIndicator">SealedIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not this piece of logistics transport equipment is sealed.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="UsedSupplyChainPackaging">UsedSupplyChainPackaging</h1>

Type: rdf:Property

Comments: Supply chain packaging used for this logistics package.

Domains: 

[edi3:Package](#Package)


<h1 id="IdentificationText">IdentificationText</h1>

Type: rdf:Property

Comments: Identification, expressed as text, of this transport cargo that is sufficient to identify it for customs, statistical or transport purposes.

Domains: 

[edi3:Cargo](#Cargo)


<h1 id="RequestingSpecificationQuery">RequestingSpecificationQuery</h1>

Type: rdf:Property

Comments: A requesting specification query for this work item complex description.

Domains: 

[edi3:ComplexDescription](#ComplexDescription)


<h1 id="ReasonDescriptionText">ReasonDescriptionText</h1>

Type: rdf:Property

Comments: <br/>A textual description of the reason for this header balance out.<br/>A textual description of the reason for this payment balance out.<br/>

Domains: 

[edi3:BalanceOut](#BalanceOut)


<h1 id="BorderClearanceTransportInstructions">BorderClearanceTransportInstructions</h1>

Type: rdf:Property

Comments: <br/>Border clearance instructions for this supply chain consignment item.<br/>Border clearance instructions for this cross-border regulatory procedure.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="BilledQuantity">BilledQuantity</h1>

Type: rdf:Property

Comments: The quantity, at line level, billed for in this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="SpecifiedRequestingParty">SpecifiedRequestingParty</h1>

Type: rdf:Property

Comments: The requesting party specified in this financing request document.

Domains: 

[edi3:Document](#Document)


<h1 id="AssertedDocumentAuthentication">AssertedDocumentAuthentication</h1>

Type: rdf:Property

Comments: A document authentication asserted for this supply chain trade line item.

Domains: 

[edi3:TradeLineItem](#TradeLineItem)


<h1 id="ClearingSystemNameText">ClearingSystemNameText</h1>

Type: rdf:Property

Comments: <br/>The clearing system name, expressed as text, for this creditor financial institution.<br/>The clearing system name, expressed as text, for this debtor financial institution.<br/>

Domains: 

[edi3:FinancialInstitution](#FinancialInstitution)


<h1 id="MFAGIdentifier">MFAGIdentifier</h1>

Type: rdf:Property

Comments: The unique Medical First Aid Guide (MFAG) identifier for these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="CellText">CellText</h1>

Type: rdf:Property

Comments: The cell value, expressed as text, for this geographical grid.

Domains: 

[edi3:GeographicalGrid](#GeographicalGrid)


<h1 id="AssociatedFinancingRequestResultDocument">AssociatedFinancingRequestResultDocument</h1>

Type: rdf:Property

Comments: The financing request result document associated with this supply chain trade transaction.

Domains: 

[edi3:TradeTransaction](#TradeTransaction)


<h1 id="TurnInReceivedQuantity">TurnInReceivedQuantity</h1>

Type: rdf:Property

Comments: The turn in quantity, at line level, received for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="ConditionCode">ConditionCode</h1>

Type: rdf:Property

Comments: <br/>A code specifying the condition of this supply chain packaging.<br/>The code specifying the condition for this recorded status.<br/>

Domains: 

[edi3:Status](#Status)
[edi3:Packaging](#Packaging)


<h1 id="MemberSpecifiedGeographicalPoint">MemberSpecifiedGeographicalPoint</h1>

Type: rdf:Property

Comments: A geographical point member of this geographical multi-point feature.

Domains: 

[edi3:GeographicalMultiPoint](#GeographicalMultiPoint)


<h1 id="BuyerNonDeductibleTaxSpecifiedTradeAccountingAccount">BuyerNonDeductibleTaxSpecifiedTradeAccountingAccount</h1>

Type: rdf:Property

Comments: The buyer non-deductible tax specified accounting account for this trade related tax, levy or duty.

Domains: 

[edi3:Tax](#Tax)


<h1 id="TariffAmount">TariffAmount</h1>

Type: rdf:Property

Comments: A monetary value of a tariff for this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="ContentDateTime">ContentDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time or other date time value for the content of this packaging marking.

Domains: 

[edi3:Marking](#Marking)


<h1 id="ScheduledIdentificationIdentifier">ScheduledIdentificationIdentifier</h1>

Type: rdf:Property

Comments: A unique identifier for this logistics transport movement, such as a voyage number, flight number, or trip number, as stated in a schedule.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="PlannedSupplyChainConsignment">PlannedSupplyChainConsignment</h1>

Type: rdf:Property

Comments: <br/>A consignment, at line level, planned for this trade delivery.<br/>A consignment, at header level, planned for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="InnerPackContentUnitQuantity">InnerPackContentUnitQuantity</h1>

Type: rdf:Property

Comments: The number of content units in an inner pack of this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="DirectionAccountingDebitCreditStatusCode">DirectionAccountingDebitCreditStatusCode</h1>

Type: rdf:Property

Comments: The code specifying whether the financial adjustment must be subtracted or added.

Domains: 

[edi3:Adjustment](#Adjustment)


<h1 id="RequisitionReferencedDocument">RequisitionReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>A requisition document referenced in this line trade agreement.<br/>A requisition document referenced in this header trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="BatchIdentificationIdentifier">BatchIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>A batch identifier for this trade product.<br/>The unique batch identifier for this trade product instance.<br/>

Domains: 

[edi3:Product](#Product)
[edi3:ProductInstance](#ProductInstance)


<h1 id="UsedCapacityTransportEquipmentFullnessCode">UsedCapacityTransportEquipmentFullnessCode</h1>

Type: rdf:Property

Comments: The code specifying the used capacity of this piece of logistics transport equipment, such as full or empty.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="OrderProductUnitMeasureCode">OrderProductUnitMeasureCode</h1>

Type: rdf:Property

Comments: The code specifying the order product unit of measure, such as kilogram or litre, for this line trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="VINLogisticsLabel">VINLogisticsLabel</h1>

Type: rdf:Property

Comments: A Vehicle Identification Number (VIN) label that is a part of these logistics shipping marks.

Domains: 

[edi3:ShippingMarks](#ShippingMarks)


<h1 id="ISSCReferencedDocument">ISSCReferencedDocument</h1>

Type: rdf:Property

Comments: The referenced ISSC (International Ship Security Certificate) document for this logistics transport means.

Domains: 

[edi3:TransportMeans](#TransportMeans)


<h1 id="DeliveryDeliveryInstructions">DeliveryDeliveryInstructions</h1>

Type: rdf:Property

Comments: <br/>Delivery instructions for this supply chain consignment.<br/>Delivery instructions for this piece of logistics transport equipment.<br/>

Domains: 

[edi3:TransportEquipment](#TransportEquipment)
[edi3:Consignment](#Consignment)


<h1 id="PositionCode">PositionCode</h1>

Type: rdf:Property

Comments: <br/>The code specifying a position of this monitoring sensor.<br/>The code specifying the position of this monitoring IOT device.<br/>

Domains: 

[edi3:Sensor](#Sensor)
[edi3:IOTDevice](#IOTDevice)


<h1 id="ReportedConditionTypeLogisticsStatusCode">ReportedConditionTypeLogisticsStatusCode</h1>

Type: rdf:Property

Comments: The code specifying the type of reported condition for this transport event.

Domains: 

[edi3:Event](#Event)


<h1 id="GoodsReceiptNoteReferencedDocument">GoodsReceiptNoteReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>A goods receipt note document, at header level, referenced for this trade delivery.<br/>The goods receipt note document, at line level, referenced for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="SpecifiedInstalmentPayment">SpecifiedInstalmentPayment</h1>

Type: rdf:Property

Comments: An instalment payment specified for this instalment plan.

Domains: 

[edi3:InstalmentPlan](#InstalmentPlan)


<h1 id="InformationNote">InformationNote</h1>

Type: rdf:Property

Comments: <br/>A note with information, at line level, for this trade delivery.<br/>A note with information, at header level, for this trade delivery.<br/>An information note for this trade product.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)
[edi3:Product](#Product)


<h1 id="AttentionOfText">AttentionOfText</h1>

Type: rdf:Property

Comments: The name, expressed as text, of a person or department in the organization to whom incoming mail is marked with words such as 'for the attention of' or 'FAO' or 'ATTN' for this trade address.

Domains: 

[edi3:Address](#Address)


<h1 id="RFIDLogisticsLabel">RFIDLogisticsLabel</h1>

Type: rdf:Property

Comments: A Radio Frequency Identification (RFID) label that is a part of these logistics shipping marks.

Domains: 

[edi3:ShippingMarks](#ShippingMarks)


<h1 id="PackageQuantity">PackageQuantity</h1>

Type: rdf:Property

Comments: <br/>The number of packages within this supply chain consignment.<br/>The number of packages in this logistics transport movement.<br/>The package quantity for this supply chain consignment item.<br/>The number of packages in this subordinate line trade delivery.<br/>The number of packages, at line level, in this trade delivery.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:TradeDelivery](#TradeDelivery)
[edi3:Consignment](#Consignment)
[edi3:TransportMovement](#TransportMovement)


<h1 id="AdditionalInstructionCode">AdditionalInstructionCode</h1>

Type: rdf:Property

Comments: A code specifying an additional instruction for this supply chain packaging.

Domains: 

[edi3:Packaging](#Packaging)


<h1 id="SalesAgentAssignedIdentificationIdentifier">SalesAgentAssignedIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The unique identifier assigned by the sales agent to identify this supply chain trade transaction.

Domains: 

[edi3:TradeTransaction](#TradeTransaction)


<h1 id="CategoryTradeTax">CategoryTradeTax</h1>

Type: rdf:Property

Comments: A tax category of this trade allowance charge.

Domains: 

[edi3:AllowanceCharge](#AllowanceCharge)


<h1 id="AssociatedSpecifiedGeographicalObjectCharacteristic">AssociatedSpecifiedGeographicalObjectCharacteristic</h1>

Type: rdf:Property

Comments: <br/>The geographical object characteristic associated with this geographical multi-surface.<br/>The geographical object characteristic associated with this specified polygon.<br/>The geographical object characteristic associated with this specified circle.<br/>The geographical object characteristic associated with this geographical surface.<br/>The geographical object characteristic associated with this geographical multi-curve.<br/>The geographical object characteristic associated with this geographical grid.<br/>The geographical object characteristic associated with this linear ring.<br/>The geographical object characteristic associated with this geographical multi-point.<br/>The geographical object characteristic associated with this geographical point.<br/>The geographical object characteristic associated with this geographical line.<br/>

Domains: 

[edi3:GeographicalPoint](#GeographicalPoint)
[edi3:Circle](#Circle)
[edi3:GeographicalMultiCurve](#GeographicalMultiCurve)
[edi3:Polygon](#Polygon)
[edi3:LinearRing](#LinearRing)
[edi3:GeographicalSurface](#GeographicalSurface)
[edi3:GeographicalMultiSurface](#GeographicalMultiSurface)
[edi3:GeographicalMultiPoint](#GeographicalMultiPoint)
[edi3:GeographicalGrid](#GeographicalGrid)
[edi3:GeographicalLine](#GeographicalLine)


<h1 id="ConsignmentQuantity">ConsignmentQuantity</h1>

Type: rdf:Property

Comments: The number of consignments in this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="ContentVariableMeasureIndicator">ContentVariableMeasureIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not instances of this trade product have a content variable measure, such as weight, length or volume.

Domains: 

[edi3:Product](#Product)


<h1 id="AssociatedRegisteredTax">AssociatedRegisteredTax</h1>

Type: rdf:Property

Comments: The registered tax associated with this tax registration.

Domains: 

[edi3:Registration](#Registration)


<h1 id="ConsolidatorTradeParty">ConsolidatorTradeParty</h1>

Type: rdf:Property

Comments: The party responsible for the consolidation of this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="AuthorizationInformationText">AuthorizationInformationText</h1>

Type: rdf:Property

Comments: Authorization information, expressed as text, for these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="TradeComparisonReferencePrice">TradeComparisonReferencePrice</h1>

Type: rdf:Property

Comments: A price that provides a trade comparison with this trade price.

Domains: 

[edi3:Price](#Price)


<h1 id="NilInsuranceValueIndicator">NilInsuranceValueIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not this supply chain consignment has a nil value for insurance.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="FinancedTransactionSpecifiedQuantity">FinancedTransactionSpecifiedQuantity</h1>

Type: rdf:Property

Comments: The number of financed transactions specified in this financing summary document.

Domains: 

[edi3:Document](#Document)


<h1 id="UOMLabelListText">UOMLabelListText</h1>

Type: rdf:Property

Comments: <br/>An ordered list of Unit Of Measure (UOM) labels, expressed as text, for this specified direct position list.<br/>An ordered list of Unit Of Measure (UOM) labels, expressed as text, for this specified direct position.<br/>

Domains: 

[edi3:DirectPosition](#DirectPosition)
[edi3:DirectPositionList](#DirectPositionList)


<h1 id="InvoiceApplicableTradeCurrencyExchange">InvoiceApplicableTradeCurrencyExchange</h1>

Type: rdf:Property

Comments: <br/>The currency exchange applicable to the invoice in this header trade settlement.<br/>A currency exchange applicable to the invoice for this supply chain consignment.<br/>

Domains: 

[edi3:TradeSettlement](#TradeSettlement)
[edi3:Consignment](#Consignment)


<h1 id="GlobalSerialIdentificationIdentifier">GlobalSerialIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The unique global serial identifier for this trade product instance.

Domains: 

[edi3:ProductInstance](#ProductInstance)


<h1 id="SequenceNumeric">SequenceNumeric</h1>

Type: rdf:Property

Comments: <br/>The sequence number for this supply chain consignment item.<br/>The sequence number of this logistics status, such as within a status report.<br/>A sequence number for this supply chain consignment.<br/>The sequence number of this logistics package.<br/>A sequence number for this stores inventory item.<br/>The sequence number differentiating this logistics transport means from others.<br/>The sequence number for this referenced supply chain consignment.<br/>The sequence number of this referenced logistics package.<br/>A sequence number for this specified period.<br/>A sequence number for this supply chain trade line item.<br/>The sequence number for this referenced supply chain consignment item.<br/>The sequence number for applying this trade allowance charge.<br/>A sequence number for these specified personal effects.<br/>The sequence number differentiating this piece of logistics transport equipment from others in a set of transport equipment.<br/>

Domains: 

[edi3:Status](#Status)
[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:PersonalEffects](#PersonalEffects)
[edi3:TransportEquipment](#TransportEquipment)
[edi3:AllowanceCharge](#AllowanceCharge)
[edi3:Consignment](#Consignment)
[edi3:Period](#Period)
[edi3:Package](#Package)
[edi3:TradeLineItem](#TradeLineItem)
[edi3:TransportMeans](#TransportMeans)
[edi3:Inventory](#Inventory)


<h1 id="TimeOccurrenceTimeOnlyFormattedDateTime">TimeOccurrenceTimeOnlyFormattedDateTime</h1>

Type: rdf:Property

Comments: A time value of an occurrence of this supply chain event.

Domains: 

[edi3:Event](#Event)


<h1 id="ReferenceDateTime">ReferenceDateTime</h1>

Type: rdf:Property

Comments: <br/>The reference date, time, date time or other date time value for this logistics status.<br/>The reference date, time, date time or other date time value for this document status.<br/>

Domains: 

[edi3:Status](#Status)


<h1 id="BuyerAgentTradeParty">BuyerAgentTradeParty</h1>

Type: rdf:Property

Comments: The buyer agent party for this header trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="ArrivalRelatedDateTime">ArrivalRelatedDateTime</h1>

Type: rdf:Property

Comments: An arrival date, time, date time, or other date time value related to this transport event.

Domains: 

[edi3:Event](#Event)


<h1 id="RequestedResponseTypeCode">RequestedResponseTypeCode</h1>

Type: rdf:Property

Comments: A code specifying a type of response requested for this exchanged document.

Domains: 

[edi3:Document](#Document)


<h1 id="RevisionIdentificationIdentifier">RevisionIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>An identifier for the revision of this header trade agreement.<br/>An identifier for the revision of this line trade agreement.<br/>A unique identifier for a revision of this referenced document.<br/>The unique identifier of the revision of this exchanged document.<br/>

Domains: 

[edi3:Document](#Document)
[edi3:TradeAgreement](#TradeAgreement)


<h1 id="TradingBusinessNameText">TradingBusinessNameText</h1>

Type: rdf:Property

Comments: The trading business name, expressed as text, of this legally set up organization.

Domains: 

[edi3:Organization](#Organization)


<h1 id="ReferenceFileBinaryObject">ReferenceFileBinaryObject</h1>

Type: rdf:Property

Comments: A reference file binary object related to this basic work item.

Domains: 

[edi3:WorkItem](#WorkItem)


<h1 id="CallTransportEvent">CallTransportEvent</h1>

Type: rdf:Property

Comments: A call event for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="RefundAmount">RefundAmount</h1>

Type: rdf:Property

Comments: A monetary value of the refund of this trade related tax, levy or duty.

Domains: 

[edi3:Tax](#Tax)


<h1 id="AccessAvailabilitySpecifiedPeriod">AccessAvailabilitySpecifiedPeriod</h1>

Type: rdf:Property

Comments: The specified period when access to this binary file is available.

Domains: 

[edi3:BinaryFile](#BinaryFile)


<h1 id="ConsumerGenderDescriptionText">ConsumerGenderDescriptionText</h1>

Type: rdf:Property

Comments: A consumer gender description, expressed as text, for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="LoadingSequenceNumeric">LoadingSequenceNumeric</h1>

Type: rdf:Property

Comments: <br/>The sequence number differentiating this piece of logistics transport equipment from others during loading.<br/>The loading sequence number for this supply chain consignment.<br/>

Domains: 

[edi3:TransportEquipment](#TransportEquipment)
[edi3:Consignment](#Consignment)


<h1 id="AssertionText">AssertionText</h1>

Type: rdf:Property

Comments: An assertion, expressed as text, for this trade product certification, such as that this product is free from peanuts.

Domains: 

[edi3:Certification](#Certification)


<h1 id="TaxBasisTotalAmount">TaxBasisTotalAmount</h1>

Type: rdf:Property

Comments: <br/>A monetary value of the total of all tax basis amounts being reported in this trade settlement line monetary summation.<br/>A monetary value of the total of all tax basis amounts being reported in this trade settlement monetary summation.<br/>

Domains: 

[edi3:MonetarySummation](#MonetarySummation)


<h1 id="OrderCurrencyCurrencyCode">OrderCurrencyCurrencyCode</h1>

Type: rdf:Property

Comments: The code specifying the currency of the order for this header trade settlement.

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="PriceListReferencedDocument">PriceListReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>The price list document referenced in this line trade agreement.<br/>The price list document referenced in this header trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="PlannedDespatchSupplyChainEvent">PlannedDespatchSupplyChainEvent</h1>

Type: rdf:Property

Comments: <br/>A despatch event, at line level, planned for this trade delivery.<br/>A despatch event, at header level, planned for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="PreviousOrderResponseReferencedDocument">PreviousOrderResponseReferencedDocument</h1>

Type: rdf:Property

Comments: The previous order response document referenced in this header trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="SpecifiedLogisticsTransportMeans">SpecifiedLogisticsTransportMeans</h1>

Type: rdf:Property

Comments: A transport means specified for this piece of logistics transport equipment.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="CreditorReferenceIssuerIdentifier">CreditorReferenceIssuerIdentifier</h1>

Type: rdf:Property

Comments: An identifier of the creditor reference issuer for this header trade settlement.

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="PackageTypeText">PackageTypeText</h1>

Type: rdf:Property

Comments: <br/>A type of package, expressed as text, for this supply chain consignment.<br/>A package type, expressed as text, for this supply chain consignment item.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:Consignment](#Consignment)


<h1 id="SystemIdentifier">SystemIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique identifier of the classification system for this product classification.<br/>The unique identifier of the reference system used for measuring a geographical coordinate.<br/>The unique identifier of the system used for measuring this specified geographical coordinate.<br/>

Domains: 

[edi3:GeographicalCoordinate](#GeographicalCoordinate)
[edi3:Classification](#Classification)


<h1 id="ChannelCommunicationChannelCode">ChannelCommunicationChannelCode</h1>

Type: rdf:Property

Comments: The code specifying the channel or manner in which a universal communication can be made, such as telephone or email.

Domains: 

[edi3:Communication](#Communication)


<h1 id="IMDGSegregationGroupCode">IMDGSegregationGroupCode</h1>

Type: rdf:Property

Comments: The code specifying the IMDG (International Maritime Dangerous Goods regulation) segregation group for these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="PowerInactiveLogisticsTransportMeans">PowerInactiveLogisticsTransportMeans</h1>

Type: rdf:Property

Comments: A means of transport not actively powering this logistics convoy.

Domains: 

[edi3:Convoy](#Convoy)


<h1 id="GLNIdentificationIdentifier">GLNIdentificationIdentifier</h1>

Type: rdf:Property

Comments: A Global Location Number (GLN) identifier for this trade party.

Domains: 

[edi3:Party](#Party)


<h1 id="SpecifiedHandlingInstructions">SpecifiedHandlingInstructions</h1>

Type: rdf:Property

Comments: <br/>Handling instructions, at header level, specified for this trade delivery.<br/>Handling instructions specified for this logistics means of transport.<br/>Handling instructions specified for this logistics transport movement.<br/>Handling instructions, at line level, specified for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)
[edi3:TransportMovement](#TransportMovement)
[edi3:TransportMeans](#TransportMeans)


<h1 id="UnloadingSequenceNumeric">UnloadingSequenceNumeric</h1>

Type: rdf:Property

Comments: <br/>The unloading sequence number for this supply chain consignment.<br/>The sequence number differentiating this piece of logistics transport equipment from others during unloading.<br/>

Domains: 

[edi3:TransportEquipment](#TransportEquipment)
[edi3:Consignment](#Consignment)


<h1 id="HongKongBankIdentificationIdentifier">HongKongBankIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique Hong Kong Bank Code identifier for this debtor financial institution.<br/>The unique Hong Kong Bank Code identifier for this creditor financial institution.<br/>

Domains: 

[edi3:FinancialInstitution](#FinancialInstitution)


<h1 id="OperationalResponsibleTradeParty">OperationalResponsibleTradeParty</h1>

Type: rdf:Property

Comments: The operational responsible party for this communication event.

Domains: 

[edi3:Event](#Event)


<h1 id="OwnerAgentTradeParty">OwnerAgentTradeParty</h1>

Type: rdf:Property

Comments: The owner agent trade party for this logistics means of transport.

Domains: 

[edi3:TransportMeans](#TransportMeans)


<h1 id="VariantDescriptionText">VariantDescriptionText</h1>

Type: rdf:Property

Comments: A textual description of a variant of this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="SerialIdentificationIdentifier">SerialIdentificationIdentifier</h1>

Type: rdf:Property

Comments: A unique serial identifier for this trade product instance.

Domains: 

[edi3:ProductInstance](#ProductInstance)


<h1 id="PowerSourceTypeCode">PowerSourceTypeCode</h1>

Type: rdf:Property

Comments: The code specifying a type of power source for this monitoring IOT device.

Domains: 

[edi3:IOTDevice](#IOTDevice)


<h1 id="RegisteredIdentificationIdentifier">RegisteredIdentificationIdentifier</h1>

Type: rdf:Property

Comments: A registered identifier of this trade party.

Domains: 

[edi3:Party](#Party)


<h1 id="CountryNumberCode">CountryNumberCode</h1>

Type: rdf:Property

Comments: The country access code for this telecommunication number.

Domains: 

[edi3:Communication](#Communication)


<h1 id="AdditionalInformationIncludedNote">AdditionalInformationIncludedNote</h1>

Type: rdf:Property

Comments: An additional information note included for this financing request document.

Domains: 

[edi3:Document](#Document)


<h1 id="UseCode">UseCode</h1>

Type: rdf:Property

Comments: The code specifying the use of this telecommunication such as for business purposes or private.

Domains: 

[edi3:Communication](#Communication)


<h1 id="ChargeTotalAmount">ChargeTotalAmount</h1>

Type: rdf:Property

Comments: <br/>A monetary value of the total of all charge amounts being reported in this trade settlement header monetary summation.<br/>A monetary value of the total of all charge amounts being reported in this trade settlement line monetary summation.<br/>

Domains: 

[edi3:MonetarySummation](#MonetarySummation)


<h1 id="ReceivingAdviceReferencedDocument">ReceivingAdviceReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>A receiving advice document, at header level, referenced for this trade delivery.<br/>A receiving advice document, at line level, referenced for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="DefinedControlSettingParameter">DefinedControlSettingParameter</h1>

Type: rdf:Property

Comments: A control setting parameter defined for this monitoring sensor.

Domains: 

[edi3:Sensor](#Sensor)


<h1 id="ExplosiveCargoNetWeightWeightUnitMeasure">ExplosiveCargoNetWeightWeightUnitMeasure</h1>

Type: rdf:Property

Comments: The measure of the explosive cargo weight applicable to these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="PreviousDeliverySupplyChainEvent">PreviousDeliverySupplyChainEvent</h1>

Type: rdf:Property

Comments: A previous delivery event, at header level, for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="SetTriggerAccountingDocumentCode">SetTriggerAccountingDocumentCode</h1>

Type: rdf:Property

Comments: A code specifying a set trigger for this trade accounting account to be used in response to a specific event or a set of events.

Domains: 

[edi3:AccountingAccount](#AccountingAccount)


<h1 id="ReferencedSpecifiedBinaryFile">ReferencedSpecifiedBinaryFile</h1>

Type: rdf:Property

Comments: <br/>A specified binary file referenced by this grouped work item.<br/>A specified binary file referenced by this basic work item.<br/>A specified binary file referenced by this valuation breakdown statement.<br/>

Domains: 

[edi3:WorkItem](#WorkItem)
[edi3:BreakdownStatement](#BreakdownStatement)


<h1 id="ClassCode">ClassCode</h1>

Type: rdf:Property

Comments: The code specifying the class for this product classification.

Domains: 

[edi3:Classification](#Classification)


<h1 id="ISPSSecurityLevelCode">ISPSSecurityLevelCode</h1>

Type: rdf:Property

Comments: The code specifying the International Ship and Port facility Security (ISPS) level assigned to this logistics means of transport.

Domains: 

[edi3:TransportMeans](#TransportMeans)


<h1 id="SeasonCode">SeasonCode</h1>

Type: rdf:Property

Comments: <br/>The code specifying the season for this specified period.<br/>A code specifying a season for this trade product.<br/>

Domains: 

[edi3:Product](#Product)
[edi3:Period](#Period)


<h1 id="DriversLicenceIdentificationIdentifier">DriversLicenceIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The drivers licence identifier for this person.

Domains: 

[edi3:Identity](#Identity)


<h1 id="CallPurposeCode">CallPurposeCode</h1>

Type: rdf:Property

Comments: A code specifying a call purpose for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="ProductionDiscontinuedDateTime">ProductionDiscontinuedDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time, or other date time value of the discontinuation of the production of this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="RelatedAppliedAllowanceCharge">RelatedAppliedAllowanceCharge</h1>

Type: rdf:Property

Comments: Applied allowance charge information related to this calculated price.

Domains: 

[edi3:Price](#Price)


<h1 id="ReportSubmissionDateTime">ReportSubmissionDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time or other date time value of the submission of the report being acknowledged by this acknowledgment document.

Domains: 

[edi3:Document](#Document)


<h1 id="PartialDeliveryAllowedIndicator">PartialDeliveryAllowedIndicator</h1>

Type: rdf:Property

Comments: <br/>The indication, at line level, of whether or not this trade delivery can be partially delivered.<br/>The indication of whether or not these trade delivery terms allow a partial delivery.<br/>The indication, at header level, of whether or not this trade delivery can be partially delivered.<br/>

Domains: 

[edi3:DeliveryTerms](#DeliveryTerms)
[edi3:TradeDelivery](#TradeDelivery)


<h1 id="LogisticsServiceProviderTradeParty">LogisticsServiceProviderTradeParty</h1>

Type: rdf:Property

Comments: A logistics service provider party, at line level, for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="SignatoryDocumentAuthentication">SignatoryDocumentAuthentication</h1>

Type: rdf:Property

Comments: <br/>A signatory authentication for this referenced document.<br/>A signatory document authentication for this exchanged document.<br/>

Domains: 

[edi3:Document](#Document)


<h1 id="SpecifiedIdentifiedFault">SpecifiedIdentifiedFault</h1>

Type: rdf:Property

Comments: An identified defect specified for this logistics means of transport.

Domains: 

[edi3:TransportMeans](#TransportMeans)


<h1 id="RequisitionerSpecifiedTradeProduct">RequisitionerSpecifiedTradeProduct</h1>

Type: rdf:Property

Comments: The product specified by the requisitioner for this supply chain trade line item.

Domains: 

[edi3:TradeLineItem](#TradeLineItem)


<h1 id="MultipleReferencesIndicator">MultipleReferencesIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not this acknowledgement document has multiple references.

Domains: 

[edi3:Document](#Document)


<h1 id="CalculationMethodCode">CalculationMethodCode</h1>

Type: rdf:Property

Comments: The code specifying the method by which this trade related tax, levy or duty is calculated, such as codes for "tax calculated after line total summation", "tax calculated before line total summation", "tax back calculated based on grand total".

Domains: 

[edi3:Tax](#Tax)


<h1 id="ApplicableTradeProductCertification">ApplicableTradeProductCertification</h1>

Type: rdf:Property

Comments: A certification applicable to this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="UltimateShipToDeliverySupplyChainEvent">UltimateShipToDeliverySupplyChainEvent</h1>

Type: rdf:Property

Comments: The ultimate ship to delivery event, at header level, for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="PayingPartyRoleChargePayingPartyRoleCode">PayingPartyRoleChargePayingPartyRoleCode</h1>

Type: rdf:Property

Comments: The code specifying the role of the party responsible for paying this logistics service charge.

Domains: 

[edi3:ServiceCharge](#ServiceCharge)


<h1 id="SellerRefundableTaxSpecifiedTradeAccountingAccount">SellerRefundableTaxSpecifiedTradeAccountingAccount</h1>

Type: rdf:Property

Comments: The seller refundable tax specified accounting account for this trade related tax, levy or duty.

Domains: 

[edi3:Tax](#Tax)


<h1 id="SpecifiedFLUXGeographicalCoordinate">SpecifiedFLUXGeographicalCoordinate</h1>

Type: rdf:Property

Comments: Geographical coordinate information specified for this linear ring.

Domains: 

[edi3:LinearRing](#LinearRing)


<h1 id="PrimaryClassificationCode">PrimaryClassificationCode</h1>

Type: rdf:Property

Comments: <br/>A code specifying the primary classification for this work item group.<br/>A code specifying a primary classification value for this work item quantity analysis.<br/>A code specifying the primary classification for this basic work item.<br/>

Domains: 

[edi3:QuantityAnalysis](#QuantityAnalysis)
[edi3:WorkItem](#WorkItem)


<h1 id="InvoiceIssuerReferenceText">InvoiceIssuerReferenceText</h1>

Type: rdf:Property

Comments: <br/>The invoice issuer reference, expressed as text, for this header trade settlement.<br/>The invoice issuer reference, expressed as text, for this line settlement.<br/>

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="NextDeliveryTransportEvent">NextDeliveryTransportEvent</h1>

Type: rdf:Property

Comments: A next delivery event for this transport waste material.

Domains: 

[edi3:Material](#Material)


<h1 id="BuyerOrderReferencedDocument">BuyerOrderReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>A buyer generated order document referenced in this line trade agreement.<br/>A buyer generated order document referenced in this subordinate line trade agreement.<br/>The buyer generated order document referenced in this header trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="LineCountNumeric">LineCountNumeric</h1>

Type: rdf:Property

Comments: The count of the number of lines in this exchanged document.

Domains: 

[edi3:Document](#Document)


<h1 id="CarrierAgentTradeParty">CarrierAgentTradeParty</h1>

Type: rdf:Property

Comments: <br/>The carrier agent trade party for this logistics transport movement.<br/>The party acting as the agent of the carrier for this supply chain consignment.<br/>

Domains: 

[edi3:Consignment](#Consignment)
[edi3:TransportMovement](#TransportMovement)


<h1 id="DisbursementAmount">DisbursementAmount</h1>

Type: rdf:Property

Comments: A monetary value of a disbursement for this logistics service charge.

Domains: 

[edi3:ServiceCharge](#ServiceCharge)


<h1 id="PublicationDateTime">PublicationDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time, or other date time value of the publication of this document line.

Domains: 

[edi3:Document](#Document)


<h1 id="CountryNameText">CountryNameText</h1>

Type: rdf:Property

Comments: <br/>A name, expressed as text, of the country for this trade address.<br/>The name, expressed as text, of the country within this financial institution address.<br/>The country name, expressed as text, of this logistics location.<br/>The name, expressed as text, of a country location used or referenced in trade.<br/>

Domains: 

[edi3:Address](#Address)
[edi3:Location](#Location)


<h1 id="BirthplaceNameText">BirthplaceNameText</h1>

Type: rdf:Property

Comments: The name, expressed as text, of the place where this transport person was born.

Domains: 

[edi3:Person](#Person)


<h1 id="SenderRecipientSequenceIdentificationIdentifier">SenderRecipientSequenceIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The sender-recipient sequence identifier for this supply chain trade transaction.

Domains: 

[edi3:TradeTransaction](#TradeTransaction)


<h1 id="ShipToShipTransportEvent">ShipToShipTransportEvent</h1>

Type: rdf:Property

Comments: A ship to ship event for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="IncludedSupplyChainTradeLineItem">IncludedSupplyChainTradeLineItem</h1>

Type: rdf:Property

Comments: <br/>A supply chain trade line item which is included in this trade product group.<br/>A trade line item included in this supply chain trade transaction.<br/>A supply chain trade line item included in this logistics package.<br/>A trade line item included in this supply chain consignment item.<br/>A trade line item included in this referenced supply chain consignment item.<br/>

Domains: 

[edi3:TradeTransaction](#TradeTransaction)
[edi3:ProductGroup](#ProductGroup)
[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:Package](#Package)


<h1 id="MarketingMeasure">MarketingMeasure</h1>

Type: rdf:Property

Comments: A marketing measure for this trade product feature.

Domains: 

[edi3:Feature](#Feature)


<h1 id="TotalDisbursementAmount">TotalDisbursementAmount</h1>

Type: rdf:Property

Comments: The monetary value of total disbursement for this supply chain consignment, such as the amount to be collected by the carrier according to the order given by the consignor.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="ApplicableLogisticsTransportMeans">ApplicableLogisticsTransportMeans</h1>

Type: rdf:Property

Comments: The means of transport applicable to this supply chain consignment item.

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)


<h1 id="TradeLineItemQuantity">TradeLineItemQuantity</h1>

Type: rdf:Property

Comments: <br/>The number of trade line items in this supply chain consignment item.<br/>The number of trade line items in this referenced supply chain consignment item.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)


<h1 id="SpecialFormInformationText">SpecialFormInformationText</h1>

Type: rdf:Property

Comments: Information, expressed as text, describing the special form for this radioactive material.

Domains: 

[edi3:Material](#Material)


<h1 id="DeparturePointText">DeparturePointText</h1>

Type: rdf:Property

Comments: A departure point, expressed as text, for this transport route.

Domains: 

[edi3:Route](#Route)


<h1 id="HellenicBankIdentificationIdentifier">HellenicBankIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique Hellenic Bank Identification Code identifier for this debtor financial institution.<br/>The unique Hellenic Bank Identification Code identifier for this creditor financial institution.<br/>

Domains: 

[edi3:FinancialInstitution](#FinancialInstitution)


<h1 id="PersonIdentificationIdentifier">PersonIdentificationIdentifier</h1>

Type: rdf:Property

Comments: A unique identifier for this trade contact person.

Domains: 

[edi3:Contact](#Contact)


<h1 id="URLIdentifier">URLIdentifier</h1>

Type: rdf:Property

Comments: The Uniform Resource Locator (URL) for this document clause.

Domains: 

[edi3:Clause](#Clause)


<h1 id="EffectiveSpecifiedPeriod">EffectiveSpecifiedPeriod</h1>

Type: rdf:Property

Comments: <br/>The period within which this document line is effective.<br/>The specified period during which this transport service is effective.<br/>The specified period within which this referenced document is effective.<br/>The specified period within which this exchanged document is effective.<br/>

Domains: 

[edi3:Service](#Service)
[edi3:Document](#Document)


<h1 id="LayoutTypeCode">LayoutTypeCode</h1>

Type: rdf:Property

Comments: The code specifying the layout type of this logistics label.

Domains: 

[edi3:Label](#Label)


<h1 id="DeliveryInformationText">DeliveryInformationText</h1>

Type: rdf:Property

Comments: The delivery information, expressed as text, for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="BuyerAssignedCategoryCode">BuyerAssignedCategoryCode</h1>

Type: rdf:Property

Comments: The code specifying the category assigned by the buyer for this document line.

Domains: 

[edi3:Document](#Document)


<h1 id="LengthMeasure">LengthMeasure</h1>

Type: rdf:Property

Comments: The measure of the length component of this spatial dimension.

Domains: 

[edi3:Dimension](#Dimension)


<h1 id="MinimumLinearSpatialDimension">MinimumLinearSpatialDimension</h1>

Type: rdf:Property

Comments: <br/>Minimum linear spatial dimensions of this trade product.<br/>The minimum linear spatial dimensions of this supply chain packaging.<br/>

Domains: 

[edi3:Packaging](#Packaging)
[edi3:Product](#Product)


<h1 id="ReportedTransportEvent">ReportedTransportEvent</h1>

Type: rdf:Property

Comments: A transport event reported by this monitoring IOT device.

Domains: 

[edi3:IOTDevice](#IOTDevice)


<h1 id="ChargeAmount">ChargeAmount</h1>

Type: rdf:Property

Comments: <br/>The monetary value of the charge for this transport service.<br/>A monetary value of the trade price charge.<br/>The monetary value of a charged reference price.<br/>A monetary value of the calculated price to be charged.<br/>

Domains: 

[edi3:Price](#Price)
[edi3:Service](#Service)


<h1 id="ServiceCategoryCode">ServiceCategoryCode</h1>

Type: rdf:Property

Comments: The code specifying the category of service for this logistics service charge.

Domains: 

[edi3:ServiceCharge](#ServiceCharge)


<h1 id="PortugueseNCCIdentificationIdentifier">PortugueseNCCIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique Portuguese National Clearing Code (NCC) identifier for this creditor financial institution.<br/>The unique Portuguese National Clearing Code (NCC) identifier for this debtor financial institution.<br/>

Domains: 

[edi3:FinancialInstitution](#FinancialInstitution)


<h1 id="UnloadingInspectionSpecifiedTransportInstructions">UnloadingInspectionSpecifiedTransportInstructions</h1>

Type: rdf:Property

Comments: Unloading inspection instructions specified for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="CompleteNumberText">CompleteNumberText</h1>

Type: rdf:Property

Comments: <br/>The text string of characters that make up the complete number for this telecommunication.<br/>The text string of characters that make up the complete number for this universal communication.<br/>

Domains: 

[edi3:Communication](#Communication)


<h1 id="EmailURIEmailCommunication">EmailURIEmailCommunication</h1>

Type: rdf:Property

Comments: The email Uniform Resource Identifier (URI) communication for this contact person.

Domains: 

[edi3:Person](#Person)


<h1 id="ImmediatePayableTotalChargeAmount">ImmediatePayableTotalChargeAmount</h1>

Type: rdf:Property

Comments: A monetary value of the total charges, including tariff and non-tariff charges, immediately payable for this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="MapBinaryObject">MapBinaryObject</h1>

Type: rdf:Property

Comments: Binary object data that is the map of this transport route.

Domains: 

[edi3:Route](#Route)


<h1 id="LoadingBaseportLogisticsLocation">LoadingBaseportLogisticsLocation</h1>

Type: rdf:Property

Comments: The baseport location at which this supply chain consignment is to be loaded on a means of transport according to the transport contract.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="ValueDateTime">ValueDateTime</h1>

Type: rdf:Property

Comments: The value for this product characteristic expressed as a date, time, date time, or other date time value.

Domains: 

[edi3:Characteristic](#Characteristic)


<h1 id="ApplicableProductCharacteristic">ApplicableProductCharacteristic</h1>

Type: rdf:Property

Comments: <br/>A product characteristic applicable to this trade product instance.<br/>A characteristic applicable to this trade product.<br/>

Domains: 

[edi3:Product](#Product)
[edi3:ProductInstance](#ProductInstance)


<h1 id="CalculatedAmount">CalculatedAmount</h1>

Type: rdf:Property

Comments: <br/>A monetary value resulting from the calculation of this trade related tax, levy or duty.<br/>The monetary value resulting from the calculation of the applied tax.<br/>A monetary value calculated for this header balance out.<br/>A monetary value calculated for this payment balance out.<br/>

Domains: 

[edi3:Tax](#Tax)
[edi3:BalanceOut](#BalanceOut)


<h1 id="BorderCrossingDateTime">BorderCrossingDateTime</h1>

Type: rdf:Property

Comments: A date, time, date time or other date time value when this logistics transport movement crosses a border.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="DeliveryInstructionsText">DeliveryInstructionsText</h1>

Type: rdf:Property

Comments: Delivery instructions, expressed as text, for this supply chain consignment item.

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)


<h1 id="ConditionFinancingStatusCode">ConditionFinancingStatusCode</h1>

Type: rdf:Property

Comments: The code specifying the condition of this financing status.

Domains: 

[edi3:Status](#Status)


<h1 id="WeightWeightUnitMeasure">WeightWeightUnitMeasure</h1>

Type: rdf:Property

Comments: A weight for which this calculated emission is measured.

Domains: 

[edi3:Emission](#Emission)


<h1 id="PriceListItemIdentificationIdentifier">PriceListItemIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique identifier of a price list item for this basic work item.<br/>The identifier of a price list item for this grouped work item.<br/>

Domains: 

[edi3:WorkItem](#WorkItem)


<h1 id="PhysicalFormDescriptionText">PhysicalFormDescriptionText</h1>

Type: rdf:Property

Comments: A textual description of the physical form of this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="ContainerizationIndicator">ContainerizationIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not this supply chain consignment is to be transported in a container or containers.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="RelationshipTypeReferenceCode">RelationshipTypeReferenceCode</h1>

Type: rdf:Property

Comments: The code specifying the type of relationship between this referenced document and another artefact, such as a replacement of an original document.

Domains: 

[edi3:Document](#Document)


<h1 id="ExemptionClaimantTradeParty">ExemptionClaimantTradeParty</h1>

Type: rdf:Property

Comments: A party who claims an exemption from this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="StatementNote">StatementNote</h1>

Type: rdf:Property

Comments: A statement note for this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="PerformanceDateTime">PerformanceDateTime</h1>

Type: rdf:Property

Comments: A date, time, date time, or other date time value on which this cross-border regulatory procedure was, or will be, performed.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="WTOAdditionCode">WTOAdditionCode</h1>

Type: rdf:Property

Comments: The code specifying any additions necessary under the World Trade Organization (WTO) Valuation Agreement used for the assessment of this cross-border customs valuation.

Domains: 

[edi3:CustomsValuation](#CustomsValuation)


<h1 id="CardholderNameText">CardholderNameText</h1>

Type: rdf:Property

Comments: The cardholder name as it appears on this trade settlement financial card. This may include both an individual authorized to use the card as well as the organization that owns the card.

Domains: 

[edi3:FinancialCard](#FinancialCard)


<h1 id="SpecifiedSupplyChainEvent">SpecifiedSupplyChainEvent</h1>

Type: rdf:Property

Comments: A supply chain event specified for this supply chain inventory.

Domains: 

[edi3:Inventory](#Inventory)


<h1 id="VersionIdentificationIdentifier">VersionIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The unique identifier for the version of this exchanged document.

Domains: 

[edi3:Document](#Document)


<h1 id="PriceCurrencyCode">PriceCurrencyCode</h1>

Type: rdf:Property

Comments: The code specifying the price currency for this line trade settlement.

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="FunctionDeliveryTermsFunctionCode">FunctionDeliveryTermsFunctionCode</h1>

Type: rdf:Property

Comments: A code specifying a function of these trade delivery terms.

Domains: 

[edi3:DeliveryTerms](#DeliveryTerms)


<h1 id="DangerousGoodsIndicator">DangerousGoodsIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not dangerous goods are carried for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="CargoToleranceInformationText">CargoToleranceInformationText</h1>

Type: rdf:Property

Comments: <br/>Cargo tolerance information, expressed as text, for this supply chain consignment item.<br/>Cargo tolerance information, expressed as text, for this supply chain consignment.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:Consignment](#Consignment)


<h1 id="ChargeableTransportationStageQuantity">ChargeableTransportationStageQuantity</h1>

Type: rdf:Property

Comments: The number of separately chargeable transportation stages to be covered by this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="CrewNationalityTradeCountry">CrewNationalityTradeCountry</h1>

Type: rdf:Property

Comments: Crew nationality details for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="DeferredPayableTotalChargeAmount">DeferredPayableTotalChargeAmount</h1>

Type: rdf:Property

Comments: A monetary value of the total charges, including tariff and non-tariff charges, deferred for this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="DeliveryPriorityPriorityDescriptionCode">DeliveryPriorityPriorityDescriptionCode</h1>

Type: rdf:Property

Comments: <br/>The code specifying the delivery priority for this header trade agreement.<br/>The code specifying the delivery priority for this line trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="FromProductionLifeSpanDurationUnitMeasure">FromProductionLifeSpanDurationUnitMeasure</h1>

Type: rdf:Property

Comments: The measure of the life span of this trade product from date of production.

Domains: 

[edi3:Product](#Product)


<h1 id="IncludedTransportWasteMaterialComponent">IncludedTransportWasteMaterialComponent</h1>

Type: rdf:Property

Comments: A material component included in this transport waste.

Domains: 

[edi3:Material](#Material)


<h1 id="SalesReportReferencedDocument">SalesReportReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>The sales report document referenced in this header trade agreement.<br/>The sales report document referenced in this line trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="SpecifiedDocumentStatus">SpecifiedDocumentStatus</h1>

Type: rdf:Property

Comments: Status information specified for this referenced document.

Domains: 

[edi3:Document](#Document)


<h1 id="ServicingSpecifiedLocationParty">ServicingSpecifiedLocationParty</h1>

Type: rdf:Property

Comments: A servicing party specified for this logistics related location.

Domains: 

[edi3:Location](#Location)


<h1 id="AccessText">AccessText</h1>

Type: rdf:Property

Comments: Access information, expressed as text, for this specified binary file, such as security and download parameters.

Domains: 

[edi3:BinaryFile](#BinaryFile)


<h1 id="ItemIdentificationIdentifier">ItemIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The unique identifier of an item in this acknowledgement document.

Domains: 

[edi3:Document](#Document)


<h1 id="TotalPrepaidAmount">TotalPrepaidAmount</h1>

Type: rdf:Property

Comments: A monetary value of a prepaid total reported in this trade settlement header monetary summation.

Domains: 

[edi3:MonetarySummation](#MonetarySummation)


<h1 id="NatureIdentificationTransportCargo">NatureIdentificationTransportCargo</h1>

Type: rdf:Property

Comments: <br/>Transport cargo details of this supply chain consignment sufficient to identify its nature for customs, statistical or transport purposes.<br/>Transport cargo details of this referenced supply chain consignment item sufficient to identify its nature for customs, statistical or transport purposes.<br/>Transport cargo details of this supply chain consignment item sufficient to identify its nature for customs, statistical or transport purposes.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:Consignment](#Consignment)


<h1 id="FormattedIssueFormattedDateTime">FormattedIssueFormattedDateTime</h1>

Type: rdf:Property

Comments: The formatted date or date time for the issuance of this referenced document.

Domains: 

[edi3:Document](#Document)


<h1 id="AlternativeClassificationCode">AlternativeClassificationCode</h1>

Type: rdf:Property

Comments: <br/>A code specifying an alternative classification for this work item group.<br/>A code specifying an alternative classification value for this work item quantity analysis.<br/>A code specifying an alternative classification for this basic work item.<br/>

Domains: 

[edi3:QuantityAnalysis](#QuantityAnalysis)
[edi3:WorkItem](#WorkItem)


<h1 id="ExportTypeCode">ExportTypeCode</h1>

Type: rdf:Property

Comments: The code specifying the export type of supply chain consignment item.

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)


<h1 id="ProductUnitQuantity">ProductUnitQuantity</h1>

Type: rdf:Property

Comments: <br/>The number of product units in this subordinate line trade delivery.<br/>The number of product units, at line level, in this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="CustomsTransitAgentTradeParty">CustomsTransitAgentTradeParty</h1>

Type: rdf:Property

Comments: The party acting as an agent for, or on behalf of, the consignor with respect to customs transit procedures for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="AdditionalClearingSystemIdentifier">AdditionalClearingSystemIdentifier</h1>

Type: rdf:Property

Comments: An additional clearing system identifier for this creditor financial institution.

Domains: 

[edi3:FinancialInstitution](#FinancialInstitution)


<h1 id="TariffDeductionQuantity">TariffDeductionQuantity</h1>

Type: rdf:Property

Comments: <br/>A quantity to be deducted from the tariff quantity for the calculation of this trade related tax, duty or levy.<br/>A quantity to be deducted from the tariff quantity for this cross-border regulatory procedure.<br/>

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)
[edi3:Tax](#Tax)


<h1 id="DefinedOperationalParameter">DefinedOperationalParameter</h1>

Type: rdf:Property

Comments: An operational parameter defined for this monitoring sensor.

Domains: 

[edi3:Sensor](#Sensor)


<h1 id="ValueTemperatureUnitMeasure">ValueTemperatureUnitMeasure</h1>

Type: rdf:Property

Comments: <br/>The measure of the value of this transport setting temperature, such as a temperature value of ten degrees Celsius.<br/>The measure of the value of this specified temperature, such as a temperature value of ten degrees Celsius.<br/>

Domains: 

[edi3:Temperature](#Temperature)


<h1 id="CrewTransportPerson">CrewTransportPerson</h1>

Type: rdf:Property

Comments: A person who is a member of the crew of the means of transport used for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="TotalPrepaidChargeAmount">TotalPrepaidChargeAmount</h1>

Type: rdf:Property

Comments: The total monetary value of all freight and other service charges which have been paid in advance for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="FormattedUltimateShipToDeliveryFormattedDateTime">FormattedUltimateShipToDeliveryFormattedDateTime</h1>

Type: rdf:Property

Comments: The formatted date, time, date time, or other date time value, at line level, when this trade delivery is delivered to the ultimate ship to party.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="PackageTypePackageTypeCode">PackageTypePackageTypeCode</h1>

Type: rdf:Property

Comments: The code specifying the package type for the transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="ApplicableLineTradeDelivery">ApplicableLineTradeDelivery</h1>

Type: rdf:Property

Comments: A trade delivery applicable to this line trade transaction.

Domains: 

[edi3:TradeTransaction](#TradeTransaction)


<h1 id="IOSSIdentificationIdentifier">IOSSIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The Import One Stop Shop (IOSS) identifier for this tax registration.

Domains: 

[edi3:Registration](#Registration)


<h1 id="QuotationProposalResponseReferencedDocument">QuotationProposalResponseReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>The quotation proposal response document referenced in this line trade agreement.<br/>The quotation proposal response document referenced in this header trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="SynonymNameText">SynonymNameText</h1>

Type: rdf:Property

Comments: A synonym name, expressed as text, for this distinct chemical.

Domains: 

[edi3:Chemical](#Chemical)


<h1 id="InstructionTypeCode">InstructionTypeCode</h1>

Type: rdf:Property

Comments: A code specifying a type of instruction for these trade payment terms.

Domains: 

[edi3:PaymentTerms](#PaymentTerms)


<h1 id="SpecifiedTaxRegistration">SpecifiedTaxRegistration</h1>

Type: rdf:Property

Comments: <br/>A tax registration specified for this trade party.<br/>A tax registration specified for this contact person.<br/>

Domains: 

[edi3:Party](#Party)
[edi3:Person](#Person)


<h1 id="TelephoneUniversalCommunication">TelephoneUniversalCommunication</h1>

Type: rdf:Property

Comments: <br/>Telephone communication information for this trade contact.<br/>Telephone communication information for this location party.<br/>A telephone communication for this trade party.<br/>

Domains: 

[edi3:Party](#Party)
[edi3:Contact](#Contact)


<h1 id="BuyerSignatoryDocumentAuthentication">BuyerSignatoryDocumentAuthentication</h1>

Type: rdf:Property

Comments: The buyer signature that authenticates this exchanged document.

Domains: 

[edi3:Document](#Document)


<h1 id="ReportingMonitoringIOTDevice">ReportingMonitoringIOTDevice</h1>

Type: rdf:Property

Comments: An IOT device for this transport reporting event.

Domains: 

[edi3:Event](#Event)


<h1 id="AgentAssignedCustomerIdentificationIdentifier">AgentAssignedCustomerIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The agent assigned customer identifier for this financial identity.

Domains: 

[edi3:Identity](#Identity)


<h1 id="SpecifiedSubordinateLineTradeSettlement">SpecifiedSubordinateLineTradeSettlement</h1>

Type: rdf:Property

Comments: A trade settlement specified for this subordinate trade line item.

Domains: 

[edi3:TradeLineItem](#TradeLineItem)


<h1 id="ContractGeneralConditionsText">ContractGeneralConditionsText</h1>

Type: rdf:Property

Comments: The contract general conditions, expressed as text, for this transport cargo insurance.

Domains: 

[edi3:CargoInsurance](#CargoInsurance)


<h1 id="GoodsPhysicalStateDescriptionText">GoodsPhysicalStateDescriptionText</h1>

Type: rdf:Property

Comments: A textual description for the physical state of the goods, at header level, for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="AcceptableSpecifiedPeriod">AcceptableSpecifiedPeriod</h1>

Type: rdf:Property

Comments: The specified period within which this referenced document may be accepted.

Domains: 

[edi3:Document](#Document)


<h1 id="PlannedStockCalculationDateTime">PlannedStockCalculationDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time, or other date time value of the planned stock calculation of this supply chain inventory.

Domains: 

[edi3:Inventory](#Inventory)


<h1 id="ActualWorkItemComplexDescription">ActualWorkItemComplexDescription</h1>

Type: rdf:Property

Comments: <br/>An actual complex description for this basic work item.<br/>An actual complex description for this work item group.<br/>

Domains: 

[edi3:WorkItem](#WorkItem)


<h1 id="TotalBudgetAmount">TotalBudgetAmount</h1>

Type: rdf:Property

Comments: The monetary value of the total budget which includes net amount, taxes, and material and instalment costs for this procuring project.

Domains: 

[edi3:Project](#Project)


<h1 id="ResponsibilityText">ResponsibilityText</h1>

Type: rdf:Property

Comments: A responsibility, expressed as text, of this trade contact.

Domains: 

[edi3:Contact](#Contact)


<h1 id="PayerTradeParty">PayerTradeParty</h1>

Type: rdf:Property

Comments: <br/>The payer party for this payment trade settlement.<br/>The payer party for this line trade settlement.<br/>The payer party for this header trade settlement.<br/>

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="PromotionalDealReferencedDocument">PromotionalDealReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>The promotional deal document referenced in this line trade agreement.<br/>The promotional deal document referenced in this header trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="NominalGrossVolumeMeasure">NominalGrossVolumeMeasure</h1>

Type: rdf:Property

Comments: The measure of the nominal gross volume of this logistics package.

Domains: 

[edi3:Package](#Package)


<h1 id="LayerTotalUnitQuantity">LayerTotalUnitQuantity</h1>

Type: rdf:Property

Comments: The total number of units in a layer of this supply chain packaging.

Domains: 

[edi3:Packaging](#Packaging)


<h1 id="CreditLimitAmount">CreditLimitAmount</h1>

Type: rdf:Property

Comments: A monetary value of the credit limit for this trade settlement financial card.

Domains: 

[edi3:FinancialCard](#FinancialCard)


<h1 id="TransportMovementTypeTransportMovementTypeCode">TransportMovementTypeTransportMovementTypeCode</h1>

Type: rdf:Property

Comments: A code specifying the transport movement type, such as import, export, transit, for this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="TaxBasisAllowanceRate">TaxBasisAllowanceRate</h1>

Type: rdf:Property

Comments: The rate of the tax basis allowance (deduction or discount) used to calculate the trade related tax, levy or duty.

Domains: 

[edi3:Tax](#Tax)


<h1 id="CatalogueInformationReceiverTradeParty">CatalogueInformationReceiverTradeParty</h1>

Type: rdf:Property

Comments: The party that receives catalogue information for this header trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="RequestedActionCode">RequestedActionCode</h1>

Type: rdf:Property

Comments: <br/>A code specifying a requested action for this basic work item.<br/>A code specifying a requested action for this grouped work item.<br/>A code specifying the requested action for this valuation breakdown statement.<br/>

Domains: 

[edi3:WorkItem](#WorkItem)
[edi3:BreakdownStatement](#BreakdownStatement)


<h1 id="InterfaceOEMEquipment">InterfaceOEMEquipment</h1>

Type: rdf:Property

Comments: An interface between an OEM (Original Equipment Manufacturer) equipment and this monitoring IOT device.

Domains: 

[edi3:IOTDevice](#IOTDevice)


<h1 id="AttachedMonitoringIOTDevice">AttachedMonitoringIOTDevice</h1>

Type: rdf:Property

Comments: <br/>An IOT device attached to this piece of logistics transport equipment.<br/>An IOT device attached to this logistics transport means.<br/>

Domains: 

[edi3:TransportEquipment](#TransportEquipment)
[edi3:TransportMeans](#TransportMeans)


<h1 id="LegalRightsOwnerTradeParty">LegalRightsOwnerTradeParty</h1>

Type: rdf:Property

Comments: The party that owns the legal rights for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="PaymentTotalAmount">PaymentTotalAmount</h1>

Type: rdf:Property

Comments: <br/>A monetary value of a payment total reported in this trade settlement payment monetary summation.<br/>A monetary value of a payment total reported in this header trade settlement payment monetary summation.<br/>A monetary value of a payment total reported in this trade settlement line monetary summation.<br/>

Domains: 

[edi3:MonetarySummation](#MonetarySummation)


<h1 id="ScheduledDeliverySupplyChainEvent">ScheduledDeliverySupplyChainEvent</h1>

Type: rdf:Property

Comments: A scheduled delivery event in this supply chain supply plan.

Domains: 

[edi3:SupplyPlan](#SupplyPlan)


<h1 id="RelatedSpecifiedObservation">RelatedSpecifiedObservation</h1>

Type: rdf:Property

Comments: An observation related to this transport event.

Domains: 

[edi3:Event](#Event)


<h1 id="ControlTemperatureMeasurement">ControlTemperatureMeasurement</h1>

Type: rdf:Property

Comments: The measurement of the control temperature of these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="InvoiceeAssociatedTradeParty">InvoiceeAssociatedTradeParty</h1>

Type: rdf:Property

Comments: An invoicee trade party associated with this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="RadionuclideNameText">RadionuclideNameText</h1>

Type: rdf:Property

Comments: The name of the radionuclide, expressed as text, of this radioactive material.

Domains: 

[edi3:Material](#Material)


<h1 id="RequiredTransportService">RequiredTransportService</h1>

Type: rdf:Property

Comments: A transport service required for this logistics means of transport.

Domains: 

[edi3:TransportMeans](#TransportMeans)


<h1 id="ScheduledSpecifiedPeriod">ScheduledSpecifiedPeriod</h1>

Type: rdf:Property

Comments: The specified period during which this transport route is scheduled.

Domains: 

[edi3:Route](#Route)


<h1 id="InvoiceDateTime">InvoiceDateTime</h1>

Type: rdf:Property

Comments: <br/>The date, time, date time or other date time value of the invoice in this header trade settlement.<br/>The date, time, date time or other date time value of the invoice in this line trade settlement.<br/>

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="AgentTradeParty">AgentTradeParty</h1>

Type: rdf:Property

Comments: A party representing another party for this exchanged document.

Domains: 

[edi3:Document](#Document)


<h1 id="LineTotalAmount">LineTotalAmount</h1>

Type: rdf:Property

Comments: <br/>A monetary value of the line amount total being reported in this trade settlement line monetary summation.<br/>A monetary value of the line amount total being reported in this trade settlement header monetary summation.<br/>

Domains: 

[edi3:MonetarySummation](#MonetarySummation)


<h1 id="BICIdentifier">BICIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique Bank Identification Code (BIC) as defined in ISO 9362 for this creditor financial institution.<br/>The unique Bank Identification Code (BIC) as defined in ISO 9362 for this debtor financial institution.<br/>

Domains: 

[edi3:FinancialInstitution](#FinancialInstitution)


<h1 id="ResponsibleAgencyResponsibleGovernmentAgencyCode">ResponsibleAgencyResponsibleGovernmentAgencyCode</h1>

Type: rdf:Property

Comments: The code specifying the agency responsible for this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="SourceTypeCode">SourceTypeCode</h1>

Type: rdf:Property

Comments: The code specifying a type of source for this geographical coordinate source system.

Domains: 

[edi3:CoordinateSourceSystem](#CoordinateSourceSystem)


<h1 id="ConfirmedPickUpSupplyChainEvent">ConfirmedPickUpSupplyChainEvent</h1>

Type: rdf:Property

Comments: <br/>The pick-up event, at header level, confirmed for this trade delivery.<br/>The pick-up event, at line level, confirmed for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="ActualUnloadingSupplyChainEvent">ActualUnloadingSupplyChainEvent</h1>

Type: rdf:Property

Comments: <br/>The actual unloading event, at line level, for this trade delivery.<br/>The actual unloading event, at header level, for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="MaximumProductOrderableQuantity">MaximumProductOrderableQuantity</h1>

Type: rdf:Property

Comments: The maximum product orderable quantity for this line trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="IdentificationIdentifier">IdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique identifier for this supply chain trade line item.<br/>A unique identifier for this subordinate trade line item.<br/>The unique identifier for this branch of a financial institution.<br/>An identifier of this referenced transport service.<br/>The identifier for this referenced logistics package.<br/>An identifier of this referenced transport means, such as the International Maritime Organization number for a vessel.<br/>The unique identifier of this acknowledgement document.<br/>A unique identifier for this logistics related location, such as a United Nations Location Code (UNLOCODE) or GS1 Global Location Number (GLN).<br/>The identifier for this product certificate.<br/>An identifier for this trade settlement payment means.<br/>The unique identifier for this specification response.<br/>A unique identifier for this trade address.<br/>The unique identifier of this exchanged document.<br/>A unique identifier for this supply chain trade transaction.<br/>The identifier for this specified geographical feature.<br/>The identifier of this operational parameter.<br/>The unique identifier for this transport event.<br/>The identifier for this production of goods.<br/>The unique identifier for this trade country sub-division.<br/>An identifier for this transport service location, such as a United Nations Location Code (UNLOCODE) or GS1 Global Location Number (GLN).<br/>A unique identifier for this note.<br/>An identifier for this monitoring IOT device.<br/>A unique identifier of this piece of attached transport equipment.<br/>The unique identifier for this supply chain event.<br/>The unique identifier of this specified period.<br/>The identifier for this specified marketplace.<br/>The unique identifier for this location used or referenced in trade.<br/>The unique identifier for this logistics package.<br/>The unique identifier for this requesting party.<br/>An identifier for this line trade agreement.<br/>The unique identifier for this document version.<br/>A unique identifier of this location party.<br/>The unique identifier for this transport person.<br/>A unique identifier for this logistics seal.<br/>An identifier for this government registration.<br/>An identifier of this logistics means of transport, such as the International Maritime Organization number of a vessel.<br/>A unique identifier for this supply chain consignment item.<br/>The unique identifier for this valuation breakdown statement.<br/>The identifier of this label section.<br/>The unique identifier for this employer identity.<br/>The unique identifier for this geographical coordinate.<br/>A unique identifier for this legal registration.<br/>The identifier, at header level, for this trade delivery.<br/>The unique identifier for this trade accounting account.<br/>The unique identifier for this tax registration.<br/>A unique identifier for this referenced supply chain consignment.<br/>The unique identifier for this specification query.<br/>A unique identifier for this product characteristic.<br/>A unique identifier for this supply chain consignment.<br/>An identifier of this supply chain schedule.<br/>The unique identifier for this trade product feature.<br/>The identifier of this control setting parameter.<br/>The unique identifier for this basic work item.<br/>An identifier of this monitoring sensor.<br/>The unique identifier for this logistics transport movement, such as a voyage number, flight number, or trip number.<br/>The unique identifier of this spatial dimension.<br/>An identifier of this OEM equipment.<br/>The identifier for this specified observation.<br/>The unique identifier of this piece of logistics transport equipment.<br/>The identifier for this calibrated measurement.<br/>The identifier for this payment balance out.<br/>An identifier for this header trade agreement.<br/>A unique identifier for this document authentication.<br/>The unique identifier of this document context parameter.<br/>The unique identifier for this subordinate location, such as a United Nations Location Code (UNLOCODE) or GS1 Global Location Number (GLN).<br/>The unique identifier of this logistics label.<br/>An identifier for this exchanged declaration.<br/>An identifier for this certified accreditation.<br/>The identifier of this handling instructions.<br/>The unique identifier for this work item dimension.<br/>The unique identifier of this procuring project.<br/>An identifier for this geographical grid.<br/>The unique identifier for this trade geopolitical region.<br/>The unique identifier for this work item group.<br/>The identifier for this geographical object characteristic.<br/>The identifier for this communication event.<br/>The unique identifier of this transport route.<br/>A unique identifier for this referenced product.<br/>The unique identifier of this document clause.<br/>The unique identifier for this subordinate of a subordinate location, such as a United Nations Location Code (UNLOCODE) or GS1 Global Location Number (GLN).<br/>A unique identifier for this legally set up organization.<br/>The identifier of this document line document.<br/>The identifier of this trade workflow object.<br/>The identifier of this section segment.<br/>A unique identifier for this specified binary file.<br/>The identifier for this geographical coordinate source system.<br/>A unique identifier of this trade party.<br/>A proprietary identifier.<br/>An identifier for this trade product group.<br/>The unique identifier for this trade allowance charge.<br/>The unique identifier for this referenced piece of logistics transport equipment, such as a number, mark or name.<br/>The unique identifier of this transport service.<br/>A unique identifier for this referenced document.<br/>The identifier of this referenced standard.<br/>The unique identifier, commonly known as the card number, of this trade settlement financial card.<br/>An identifier, at line level, for this trade delivery.<br/>A unique identifier for this trade product.<br/>The identifier for this header balance out.<br/>The unique identifier for this trade contact.<br/>The unique identifier for this work item quantity analysis.<br/>A unique number, mark or name which identifies this associated piece of transport equipment.<br/>

Domains: 

[edi3:ProductGroup](#ProductGroup)
[edi3:Address](#Address)
[edi3:Query](#Query)
[edi3:AllowanceCharge](#AllowanceCharge)
[edi3:Label](#Label)
[edi3:Product](#Product)
[edi3:Document](#Document)
[edi3:WorkItem](#WorkItem)
[edi3:Feature](#Feature)
[edi3:BreakdownStatement](#BreakdownStatement)
[edi3:TradeTransaction](#TradeTransaction)
[edi3:GeographicalObjectCharacteristic](#GeographicalObjectCharacteristic)
[edi3:Version](#Version)
[edi3:Registration](#Registration)
[edi3:GeographicalCoordinate](#GeographicalCoordinate)
[edi3:Production](#Production)
[edi3:TransportMovement](#TransportMovement)
[edi3:Accreditation](#Accreditation)
[edi3:Identity](#Identity)
[edi3:BalanceOut](#BalanceOut)
[edi3:Route](#Route)
[edi3:CountrySubDivision](#CountrySubDivision)
[edi3:Characteristic](#Characteristic)
[edi3:Period](#Period)
[edi3:Instructions](#Instructions)
[edi3:AccountingAccount](#AccountingAccount)
[edi3:TradeLineItem](#TradeLineItem)
[edi3:PaymentMeans](#PaymentMeans)
[edi3:Project](#Project)
[edi3:Note](#Note)
[edi3:TradeDelivery](#TradeDelivery)
[edi3:Observation](#Observation)
[edi3:Seal](#Seal)
[edi3:Package](#Package)
[edi3:Person](#Person)
[edi3:IOTDevice](#IOTDevice)
[edi3:Sensor](#Sensor)
[edi3:Certificate](#Certificate)
[edi3:Measurement](#Measurement)
[edi3:Organization](#Organization)
[edi3:TransportEquipment](#TransportEquipment)
[edi3:Consignment](#Consignment)
[edi3:Standard](#Standard)
[edi3:GeographicalFeature](#GeographicalFeature)
[edi3:Segment](#Segment)
[edi3:FinancialCard](#FinancialCard)
[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:Party](#Party)
[edi3:FinancialInstitution](#FinancialInstitution)
[edi3:Declaration](#Declaration)
[edi3:QuantityAnalysis](#QuantityAnalysis)
[edi3:CoordinateSourceSystem](#CoordinateSourceSystem)
[edi3:GeopoliticalRegion](#GeopoliticalRegion)
[edi3:Service](#Service)
[edi3:Dimension](#Dimension)
[edi3:TransportMeans](#TransportMeans)
[edi3:BinaryFile](#BinaryFile)
[edi3:Section](#Section)
[edi3:Contact](#Contact)
[edi3:WorkflowObject](#WorkflowObject)
[edi3:Response](#Response)
[edi3:Marketplace](#Marketplace)
[edi3:Equipment](#Equipment)
[edi3:Authentication](#Authentication)
[edi3:Schedule](#Schedule)
[edi3:Event](#Event)
[edi3:Parameter](#Parameter)
[edi3:Clause](#Clause)
[edi3:GeographicalGrid](#GeographicalGrid)
[edi3:Location](#Location)
[edi3:TradeAgreement](#TradeAgreement)


<h1 id="ValueCode">ValueCode</h1>

Type: rdf:Property

Comments: <br/>The code specifying a value for this calibrated measurement.<br/>The code specifying the value of this product characteristic.<br/>

Domains: 

[edi3:Measurement](#Measurement)
[edi3:Characteristic](#Characteristic)


<h1 id="OperationalStatusTransportEquipmentOperationalStatusCode">OperationalStatusTransportEquipmentOperationalStatusCode</h1>

Type: rdf:Property

Comments: The code specifying the operational status for this piece of logistics transport equipment, such as to be repaired or to be shifted.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="DespatchSupplyChainSchedule">DespatchSupplyChainSchedule</h1>

Type: rdf:Property

Comments: A supply chain despatch schedule, at line level, for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="VariableMeasureIndicator">VariableMeasureIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not instances of this trade product have a variable measure, such as weight, length or volume.

Domains: 

[edi3:Product](#Product)


<h1 id="OwnerTradeParty">OwnerTradeParty</h1>

Type: rdf:Property

Comments: <br/>The owner party of this monitoring IOT device.<br/>The owner party of this monitoring sensor.<br/>The party owning this logistics means of transport.<br/>

Domains: 

[edi3:TransportMeans](#TransportMeans)
[edi3:Sensor](#Sensor)
[edi3:IOTDevice](#IOTDevice)


<h1 id="SpecifiedLogisticsLocation">SpecifiedLogisticsLocation</h1>

Type: rdf:Property

Comments: <br/>A location specified for this logistics status.<br/>A location specified for this supply chain supply plan.<br/>A location specified for this stores inventory item.<br/>A logistics related location or place specified for this trade party.<br/>The location specified for this supply chain inventory.<br/>

Domains: 

[edi3:Status](#Status)
[edi3:Party](#Party)
[edi3:SupplyPlan](#SupplyPlan)
[edi3:Inventory](#Inventory)


<h1 id="CrewListRelatedReferencedDocument">CrewListRelatedReferencedDocument</h1>

Type: rdf:Property

Comments: The crew list document related to this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="TimeZoneFormattedDateTime">TimeZoneFormattedDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time, or other date time value for the time zone of this geographical coordinate.

Domains: 

[edi3:GeographicalCoordinate](#GeographicalCoordinate)


<h1 id="RelatedTransportRoute">RelatedTransportRoute</h1>

Type: rdf:Property

Comments: The route related to this transport event.

Domains: 

[edi3:Event](#Event)


<h1 id="SpecifiedFinancingStatus">SpecifiedFinancingStatus</h1>

Type: rdf:Property

Comments: The financing status specified in this financing request result document.

Domains: 

[edi3:Document](#Document)


<h1 id="PriorityTransportServicePriorityCode">PriorityTransportServicePriorityCode</h1>

Type: rdf:Property

Comments: The code specifying the priority of this transport service.

Domains: 

[edi3:Service](#Service)


<h1 id="SpecifiedLogisticsTransportMovement">SpecifiedLogisticsTransportMovement</h1>

Type: rdf:Property

Comments: A logistics transport movement specified for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="URIIdentificationIdentifier">URIIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The unique Uniform Resource Identifier (URI) for this referenced document.

Domains: 

[edi3:Document](#Document)


<h1 id="AdditionalReferenceReferencedDocument">AdditionalReferenceReferencedDocument</h1>

Type: rdf:Property

Comments: An additional referenced document for this trade product, such as a manual or a certificate.

Domains: 

[edi3:Product](#Product)


<h1 id="GeoCoordinateIdentificationGeographicalCoordinate">GeoCoordinateIdentificationGeographicalCoordinate</h1>

Type: rdf:Property

Comments: An identification of a set of geographical coordinates for this trade address.

Domains: 

[edi3:Address](#Address)


<h1 id="LoadedTransportDangerousGoods">LoadedTransportDangerousGoods</h1>

Type: rdf:Property

Comments: Dangerous goods loaded into this piece of logistics transport equipment.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="TotalExportExitToImportEntryChargeAmount">TotalExportExitToImportEntryChargeAmount</h1>

Type: rdf:Property

Comments: <br/>The monetary value of the total charge or charges of freight, insurance and other services for this supply chain consignment calculated from the export exit location to the import entry location.<br/>The monetary value of the total charge or charges of freight, insurance and other services for this supply chain consignment item calculated from the export exit location to the import entry location.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:Consignment](#Consignment)


<h1 id="IncludedSubordinateTradeLineItem">IncludedSubordinateTradeLineItem</h1>

Type: rdf:Property

Comments: A subordinate trade line item included in this supply chain trade line item.

Domains: 

[edi3:TradeLineItem](#TradeLineItem)


<h1 id="DeclaredForCustomsLogisticsLocation">DeclaredForCustomsLogisticsLocation</h1>

Type: rdf:Property

Comments: <br/>The location of this supply chain consignment as declared for customs.<br/>The location of this supply chain consignment item as declared for customs.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:Consignment](#Consignment)


<h1 id="OnboardStoresItemInventory">OnboardStoresItemInventory</h1>

Type: rdf:Property

Comments: A stores inventory item held onboard for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="GuaranteeText">GuaranteeText</h1>

Type: rdf:Property

Comments: <br/>The undertaking, expressed as text, given in cash, bond or as a written guarantee to ensure that an obligation will be fulfilled for this cross-border regulatory procedure.<br/>The undertaking, expressed as text, given in cash, bond or as a written guarantee to ensure that an obligation will be fulfilled for this trade related tax, levy or duty.<br/>

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)
[edi3:Tax](#Tax)


<h1 id="CreditFormattedDateTime">CreditFormattedDateTime</h1>

Type: rdf:Property

Comments: The credit date, time, date time, or other date time value of this financial booking.

Domains: 

[edi3:Booking](#Booking)


<h1 id="FreightForwarderAssignedIdentifier">FreightForwarderAssignedIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique identifier assigned by the freight forwarder to this referenced supply chain consignment.<br/>The unique identifier assigned by the freight forwarder to this supply chain consignment.<br/>

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="DeliveryDiscontinuationCode">DeliveryDiscontinuationCode</h1>

Type: rdf:Property

Comments: The code specifying the delivery discontinuation for this trade delivery terms.

Domains: 

[edi3:DeliveryTerms](#DeliveryTerms)


<h1 id="StorageApplicableInstructedTemperature">StorageApplicableInstructedTemperature</h1>

Type: rdf:Property

Comments: The instructed temperature for storage applicable to these handling instructions.

Domains: 

[edi3:Instructions](#Instructions)


<h1 id="FedwireRoutingNumberIdentificationIdentifier">FedwireRoutingNumberIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique Fedwire Routing Number identifier as assigned by the American Bankers Association (ABA) for this debtor financial institution.<br/>The unique Fedwire Routing Number identifier as assigned by the American Bankers Association (ABA) for this creditor financial institution.<br/>

Domains: 

[edi3:FinancialInstitution](#FinancialInstitution)


<h1 id="ConsignmentRiskRelatedCode">ConsignmentRiskRelatedCode</h1>

Type: rdf:Property

Comments: A code specifying a consignment related risk for this logistics risk analysis result.

Domains: 

[edi3:RiskAnalysisResult](#RiskAnalysisResult)


<h1 id="SuppliedFromTradeCountry">SuppliedFromTradeCountry</h1>

Type: rdf:Property

Comments: A country of supply for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="TotalQuantity">TotalQuantity</h1>

Type: rdf:Property

Comments: <br/>The total quantity for this basic work item.<br/>The total quantity of this work item group.<br/>

Domains: 

[edi3:WorkItem](#WorkItem)


<h1 id="RejectedQuantity">RejectedQuantity</h1>

Type: rdf:Property

Comments: The quantity, at line level, rejected for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="SubClassCode">SubClassCode</h1>

Type: rdf:Property

Comments: The code specifying the sub class for this product classification.

Domains: 

[edi3:Classification](#Classification)


<h1 id="SecondSignatoryDocumentAuthentication">SecondSignatoryDocumentAuthentication</h1>

Type: rdf:Property

Comments: The second signature, also known as the first counter signature, that has been authenticated on this exchanged document indicating where appropriate the authentication party.

Domains: 

[edi3:Document](#Document)


<h1 id="SupplierPartyRoleTransportEquipmentSupplierPartyRoleCode">SupplierPartyRoleTransportEquipmentSupplierPartyRoleCode</h1>

Type: rdf:Property

Comments: The code specifying the role of the party responsible for supplying this piece of logistics transport equipment, such as the carrier or the buyer.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="DuePayableAmount">DuePayableAmount</h1>

Type: rdf:Property

Comments: <br/>A monetary value that is an amount due and payable for this trade settlement header monetary summation, such as the amount due to the creditor.<br/>A monetary value that is an amount due and payable for this trade settlement line monetary summation, such as the amount due to the creditor.<br/>A monetary value that is an exact amount due and payable for this header trade settlement, such as the amount due to the creditor.<br/>

Domains: 

[edi3:TradeSettlement](#TradeSettlement)
[edi3:MonetarySummation](#MonetarySummation)


<h1 id="LoadedSupplyChainConsignmentItem">LoadedSupplyChainConsignmentItem</h1>

Type: rdf:Property

Comments: A consignment item loaded onto, or into, this piece of logistics transport equipment.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="OnCarriageLogisticsTransportMovement">OnCarriageLogisticsTransportMovement</h1>

Type: rdf:Property

Comments: An on-carriage logistics transport movement for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="ApplicableObjectCode">ApplicableObjectCode</h1>

Type: rdf:Property

Comments: A code specifying an object, such as item, animal, person or organization applicable for this product certificate.

Domains: 

[edi3:Certificate](#Certificate)


<h1 id="LatitudeMeasure">LatitudeMeasure</h1>

Type: rdf:Property

Comments: <br/>The measure of the latitude as an angular distance north or south from the Equator meridian to the meridian of a specific place for this specified geographical coordinate. (Reference ISO 6709).<br/>The measure of the latitude as an angular distance north or south from the Equator meridian to the meridian of a specific place for this geographical coordinate (Reference ISO 6709).<br/>

Domains: 

[edi3:GeographicalCoordinate](#GeographicalCoordinate)


<h1 id="AllowanceChargeBasisAmount">AllowanceChargeBasisAmount</h1>

Type: rdf:Property

Comments: A monetary value used as the allowance and charge basis on which this trade related tax, levy or duty is calculated.

Domains: 

[edi3:Tax](#Tax)


<h1 id="GuaranteedProductLifeSpanSpecifiedPeriod">GuaranteedProductLifeSpanSpecifiedPeriod</h1>

Type: rdf:Property

Comments: The guaranteed product life span specified in this line trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="FullyDeliveredIndicator">FullyDeliveredIndicator</h1>

Type: rdf:Property

Comments: <br/>The indication, at header level, of whether or not this trade delivery is fully delivered.<br/>The indication, at line level, of whether or not this trade delivery is fully delivered.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="EndItemNameText">EndItemNameText</h1>

Type: rdf:Property

Comments: An end item name, expressed as text, for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="ConsortiumCarrierTradeParty">ConsortiumCarrierTradeParty</h1>

Type: rdf:Property

Comments: A consortium carrier party for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="NationalityTradeCountry">NationalityTradeCountry</h1>

Type: rdf:Property

Comments: A country that constitutes a nationality by origin, birth, or naturalization for this transport person.

Domains: 

[edi3:Person](#Person)


<h1 id="DocumentaryInstructionsNotifiedTradeParty">DocumentaryInstructionsNotifiedTradeParty</h1>

Type: rdf:Property

Comments: A party to be notified of the documentary instructions for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="SpecifiedTradeAccountingAccount">SpecifiedTradeAccountingAccount</h1>

Type: rdf:Property

Comments: A specified accounting account for this trade related tax, levy or duty.

Domains: 

[edi3:Tax](#Tax)


<h1 id="ConciseDescriptionText">ConciseDescriptionText</h1>

Type: rdf:Property

Comments: A concise textual description for this trade product, such as the description used on a shelf or printed on a receipt.

Domains: 

[edi3:Product](#Product)


<h1 id="InvoicerTradeParty">InvoicerTradeParty</h1>

Type: rdf:Property

Comments: The party issuing the invoice for this header trade settlement.

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="ExemptionIndicator">ExemptionIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not there is an exemption from this trade tax.

Domains: 

[edi3:Tax](#Tax)


<h1 id="ParentLineIdentifier">ParentLineIdentifier</h1>

Type: rdf:Property

Comments: The unique identifier of the parent line to this document line.

Domains: 

[edi3:Document](#Document)


<h1 id="VirtualIndicator">VirtualIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not this specified marketplace is virtual, such as a web-based marketplace.

Domains: 

[edi3:Marketplace](#Marketplace)


<h1 id="ProductReorderableIndicator">ProductReorderableIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not the product can be reordered according to this line trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="RegimeTypeCustomsDutyRegimeTypeCode">RegimeTypeCustomsDutyRegimeTypeCode</h1>

Type: rdf:Property

Comments: The code specifying a type of regime applicable to the assessment or calculation of this trade related tax, levy or duty, such as a preferential duty rate.

Domains: 

[edi3:Tax](#Tax)


<h1 id="TotalCalculatedPrice">TotalCalculatedPrice</h1>

Type: rdf:Property

Comments: <br/>A total calculated price for this basic work item.<br/>A total calculated price for this valuation breakdown statement.<br/>A total calculated price for this work item group.<br/>

Domains: 

[edi3:WorkItem](#WorkItem)
[edi3:BreakdownStatement](#BreakdownStatement)


<h1 id="LineStatusReasonCode">LineStatusReasonCode</h1>

Type: rdf:Property

Comments: The code specifying the line status reason for this document line.

Domains: 

[edi3:Document](#Document)


<h1 id="ActualReceiptSupplyChainEvent">ActualReceiptSupplyChainEvent</h1>

Type: rdf:Property

Comments: <br/>The actual receipt event, at header level, for this trade delivery.<br/>The actual receipt event, at line level, for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="ApplicableTradeProduct">ApplicableTradeProduct</h1>

Type: rdf:Property

Comments: A product applicable for this subordinate trade line item.

Domains: 

[edi3:TradeLineItem](#TradeLineItem)


<h1 id="URIUniversalCommunication">URIUniversalCommunication</h1>

Type: rdf:Property

Comments: <br/>The Uniform Resource Identifier (URI) communication for this transport service, such as its website or email address.<br/>Uniform Resource Identifier (URI) communication information for this location party, such as a web or email address.<br/>A Uniform Resource Identifier (URI) communication for this trade party, such as a web or email address.<br/>

Domains: 

[edi3:Party](#Party)
[edi3:Service](#Service)


<h1 id="UsedLogisticsTransportMeans">UsedLogisticsTransportMeans</h1>

Type: rdf:Property

Comments: The means of transport used for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="SubmissionDateTime">SubmissionDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time or other date time value for the formal submission of this exchanged document to a receiver by a sender.

Domains: 

[edi3:Document](#Document)


<h1 id="InvoiceReferenceReferencedDocument">InvoiceReferenceReferencedDocument</h1>

Type: rdf:Property

Comments: The invoice document referenced for this financial adjustment.

Domains: 

[edi3:Adjustment](#Adjustment)


<h1 id="OrderingAvailablePeriod">OrderingAvailablePeriod</h1>

Type: rdf:Property

Comments: An available ordering period for this specified marketplace.

Domains: 

[edi3:Marketplace](#Marketplace)


<h1 id="PayableSpecifiedTradeAccountingAccount">PayableSpecifiedTradeAccountingAccount</h1>

Type: rdf:Property

Comments: <br/>A payable accounting account specified for this header trade settlement.<br/>A payable accounting account specified for this line trade settlement.<br/>

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="LowLimitText">LowLimitText</h1>

Type: rdf:Property

Comments: The tuple of elements, expressed as text, indicating the low limit of this geographical grid specifying the offset of each axis.

Domains: 

[edi3:GeographicalGrid](#GeographicalGrid)


<h1 id="ApplicableHeaderTradeAgreement">ApplicableHeaderTradeAgreement</h1>

Type: rdf:Property

Comments: A trade agreement header applicable to this supply chain trade transaction, such as payment or delivery terms.

Domains: 

[edi3:TradeTransaction](#TradeTransaction)


<h1 id="FinalDestinationLogisticsLocation">FinalDestinationLogisticsLocation</h1>

Type: rdf:Property

Comments: The final destination location for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="TreatmentTransportEvent">TreatmentTransportEvent</h1>

Type: rdf:Property

Comments: A treatment event for this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="GrossVolumeVolumeUnitMeasure">GrossVolumeVolumeUnitMeasure</h1>

Type: rdf:Property

Comments: <br/>The measure of the gross volume of this piece of referenced logistics transport equipment.<br/>The measure, at line level, of the gross volume of this trade delivery.<br/>The measure of the gross volume of this piece of logistics transport equipment.<br/>A measure of the gross volume, normally calculated by multiplying the maximum length, width and height, of this referenced supply chain consignment.<br/>The measure of the gross volume of this referenced logistics package.<br/>The measure of the gross volume, normally calculated by multiplying the maximum length, width and height dimensions of these transported dangerous goods.<br/>A measure of the gross volume, normally calculated by multiplying the maximum length, width and height of this supply chain consignment.<br/>A measure of the gross volume, normally calculated by multiplying the maximum length, width and height of this supply chain consignment item.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:TransportEquipment](#TransportEquipment)
[edi3:TradeDelivery](#TradeDelivery)
[edi3:Consignment](#Consignment)
[edi3:Package](#Package)
[edi3:DangerousGoods](#DangerousGoods)


<h1 id="SaleRestrictionText">SaleRestrictionText</h1>

Type: rdf:Property

Comments: A restriction, expressed as text, imposed on the sale of the goods for this cross-border customs valuation.

Domains: 

[edi3:CustomsValuation](#CustomsValuation)


<h1 id="DueInRequestedQuantity">DueInRequestedQuantity</h1>

Type: rdf:Property

Comments: <br/>The due in requested quantity, at line level, for this trade delivery.<br/>The due in requested quantity, at header level, for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="CalculationDateTime">CalculationDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time, or other date time value of the calculation of this supply chain inventory.

Domains: 

[edi3:Inventory](#Inventory)


<h1 id="EndDateTime">EndDateTime</h1>

Type: rdf:Property

Comments: <br/>The date, time, date time or other date time value for the end of this specified period of time.<br/>The date, time, date time or other date time value for the end of this available period of time.<br/>

Domains: 

[edi3:Period](#Period)


<h1 id="VersionIdentifier">VersionIdentifier</h1>

Type: rdf:Property

Comments: <br/>The identifier of a version of this calibrated measurement.<br/>The unique version identifier for this specified binary file.<br/>The identifier of the version of this government registration.<br/>The identifier of the version of this referenced standard.<br/>The identifier for the version of this exchanged declaration.<br/>

Domains: 

[edi3:Measurement](#Measurement)
[edi3:Registration](#Registration)
[edi3:Standard](#Standard)
[edi3:Declaration](#Declaration)
[edi3:BinaryFile](#BinaryFile)


<h1 id="ChangedRecordedStatus">ChangedRecordedStatus</h1>

Type: rdf:Property

Comments: <br/>A changed recorded status for this basic work item.<br/>A changed recorded status for this work item quantity analysis.<br/>A changed recorded status for this valuation breakdown statement.<br/>A changed recorded status for this grouped work item.<br/>

Domains: 

[edi3:QuantityAnalysis](#QuantityAnalysis)
[edi3:WorkItem](#WorkItem)
[edi3:BreakdownStatement](#BreakdownStatement)


<h1 id="MeasurementMethodIdentificationIdentifier">MeasurementMethodIdentificationIdentifier</h1>

Type: rdf:Property

Comments: A unique identifier of a method of measurement for this valuation breakdown statement.

Domains: 

[edi3:BreakdownStatement](#BreakdownStatement)


<h1 id="SizeCode">SizeCode</h1>

Type: rdf:Property

Comments: The code specifying the size of this logistics label.

Domains: 

[edi3:Label](#Label)


<h1 id="GoodsPhysicalStateTypeCode">GoodsPhysicalStateTypeCode</h1>

Type: rdf:Property

Comments: The code specifying the type of physical state of the goods, at header level, for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="LotIdentificationIdentifier">LotIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The unique lot identifier for this trade product instance.

Domains: 

[edi3:ProductInstance](#ProductInstance)


<h1 id="NVOCCCarrierTradeParty">NVOCCCarrierTradeParty</h1>

Type: rdf:Property

Comments: A Non-Vessel Operating Common Carrier (NVOCC) carrier party for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="CopyIndicator">CopyIndicator</h1>

Type: rdf:Property

Comments: <br/>The indication of whether or not the referenced document is a copy.<br/>The indication of whether or not this exchanged document is a copy.<br/>The indication of whether or not this financing request document is a copy rather than an original.<br/>

Domains: 

[edi3:Document](#Document)


<h1 id="ProvidedTransportService">ProvidedTransportService</h1>

Type: rdf:Property

Comments: <br/>A transport service provided by this trade party.<br/>A transport service provided by this location party.<br/>

Domains: 

[edi3:Party](#Party)


<h1 id="ManufacturerAssignedIdentificationIdentifier">ManufacturerAssignedIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>A unique manufacturer assigned identifier for this trade product.<br/>A unique manufacturer assigned identifier for this referenced product.<br/>

Domains: 

[edi3:Product](#Product)


<h1 id="GeneticModificationExtentCode">GeneticModificationExtentCode</h1>

Type: rdf:Property

Comments: The code specifying the extent of a genetic modification to this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="DestinationTradeCountry">DestinationTradeCountry</h1>

Type: rdf:Property

Comments: <br/>The destination country for this supply chain consignment item.<br/>The destination country for this supply chain consignment.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:Consignment](#Consignment)


<h1 id="ParentIdentificationIdentifier">ParentIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The parent identifier for this referenced logistics package.<br/>The unique parent identifier for this logistics package.<br/>

Domains: 

[edi3:Package](#Package)


<h1 id="AppliedToLogisticsLocation">AppliedToLogisticsLocation</h1>

Type: rdf:Property

Comments: The end location at which this logistics service charge is no longer to be applied.

Domains: 

[edi3:ServiceCharge](#ServiceCharge)


<h1 id="RolePartyRoleCode">RolePartyRoleCode</h1>

Type: rdf:Property

Comments: A code specifying the role of this trade party.

Domains: 

[edi3:Party](#Party)


<h1 id="FormattedLatestProductDataChangeFormattedDateTime">FormattedLatestProductDataChangeFormattedDateTime</h1>

Type: rdf:Property

Comments: The formatted date, time, date time, or other date time value of the latest change in the product data for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="PaymentApplicableTradeCurrencyExchange">PaymentApplicableTradeCurrencyExchange</h1>

Type: rdf:Property

Comments: <br/>The currency exchange applicable to the payment in this header trade settlement.<br/>The currency exchange applicable to this payment trade settlement.<br/>

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="TerminalOperatorTradeParty">TerminalOperatorTradeParty</h1>

Type: rdf:Property

Comments: A terminal operator party for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="NameText">NameText</h1>

Type: rdf:Property

Comments: <br/>The name, expressed as text, of this referenced transport means, such as the vessel name.<br/>A name, expressed as text, of this academic qualification.<br/>The name, expressed as text, for this requesting party.<br/>A name, expressed as text, for this trade product.<br/>The name, expressed as text, for this branch of a financial institution.<br/>A name, expressed as text, of this legally set up organization.<br/>The name, expressed as text, for this logistics transport movement.<br/>The name, expressed as text, for this specified marketplace.<br/>The name, expressed as text, for this valuation breakdown statement.<br/>The name, expressed as text, of this location used or referenced in trade.<br/>A name, expressed as text, of this applied chemical treatment.<br/>The name, expressed as text, of this operational parameter.<br/>The name, expressed as text, of this trade geopolitical region.<br/>The name, expressed as text, of this procuring project.<br/>A name, expressed as text, of this exchanged document.<br/>The name, expressed as text, of this control setting parameter.<br/>The name, expressed as text, of this trade accounting account.<br/>A name, expressed as text, for this location party.<br/>A name, expressed as text, of this transport service location.<br/>The name, expressed as text, of this specified geographical feature.<br/>The name, expressed as text, of this logistics means of transport.<br/>The name, expressed as text, of this subordinate of a subordinate location.<br/>A name, expressed as text, of this specified period.<br/>A name, expressed as text, for this referenced document.<br/>The name, expressed as text, for this geographical object characteristic.<br/>A name, expressed as text, for this product characteristic condition.<br/>The name, expressed as text, of this document version.<br/>A name, expressed as text, for this keyword.<br/>The name or set of names, expressed as text, by which this transport person is known.<br/>The name, expressed as text, of this transport service.<br/>The name, expressed as text, for this debtor financial institution.<br/>A name, expressed as text, of this logistics related location.<br/>The name, expressed as text, for this trade product group.<br/>The name, expressed as text, of this specified direct position list.<br/>A name, expressed as text, of this trade country sub-division.<br/>The name, expressed as text, of this authoritative signatory person.<br/>A name, expressed as text, for this referenced product.<br/>The name, expressed as text, of this subordinate location.<br/>The name, expressed as text, of the reference for this specified direct position.<br/>The name, expressed as text, for this creditor financial institution.<br/>The name, expressed as text, for this trade party.<br/>The name, expressed as text, for this acknowledgement document.<br/>A name, expressed as text, of this trade country.<br/>A name, expressed as text, for this trade product feature.<br/>

Domains: 

[edi3:DirectPosition](#DirectPosition)
[edi3:ProductGroup](#ProductGroup)
[edi3:Organization](#Organization)
[edi3:Product](#Product)
[edi3:GeographicalFeature](#GeographicalFeature)
[edi3:Document](#Document)
[edi3:Feature](#Feature)
[edi3:BreakdownStatement](#BreakdownStatement)
[edi3:ChemicalTreatment](#ChemicalTreatment)
[edi3:Party](#Party)
[edi3:GeographicalObjectCharacteristic](#GeographicalObjectCharacteristic)
[edi3:Version](#Version)
[edi3:FinancialInstitution](#FinancialInstitution)
[edi3:TransportMovement](#TransportMovement)
[edi3:GeopoliticalRegion](#GeopoliticalRegion)
[edi3:Condition](#Condition)
[edi3:CountrySubDivision](#CountrySubDivision)
[edi3:Keyword](#Keyword)
[edi3:Service](#Service)
[edi3:Period](#Period)
[edi3:AccountingAccount](#AccountingAccount)
[edi3:TransportMeans](#TransportMeans)
[edi3:Project](#Project)
[edi3:Qualification](#Qualification)
[edi3:Marketplace](#Marketplace)
[edi3:DirectPositionList](#DirectPositionList)
[edi3:Parameter](#Parameter)
[edi3:Country](#Country)
[edi3:Person](#Person)
[edi3:Location](#Location)


<h1 id="RequestOverrideCode">RequestOverrideCode</h1>

Type: rdf:Property

Comments: A code specifying a request, including a reason, to override previously submitted information for this cross-border regulatory procedure, such as due to an error condition.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="ControlRequirementIndicator">ControlRequirementIndicator</h1>

Type: rdf:Property

Comments: <br/>The indication of whether or not this exchanged document has specific control requirements.<br/>The indication of whether or not this acknowledgement document has a control requirement.<br/>The indication of whether or not a control is required for this cross-border regulatory procedure.<br/>

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)
[edi3:Document](#Document)


<h1 id="OriginalIssuedQuantity">OriginalIssuedQuantity</h1>

Type: rdf:Property

Comments: The number of originals issued of this exchanged document.

Domains: 

[edi3:Document](#Document)


<h1 id="ExporterTradeParty">ExporterTradeParty</h1>

Type: rdf:Property

Comments: The party who exports this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="ConditionCancellationDocumentStatusCode">ConditionCancellationDocumentStatusCode</h1>

Type: rdf:Property

Comments: The code specifying the condition of this cancellation status.

Domains: 

[edi3:Status](#Status)


<h1 id="AppliedTradeTax">AppliedTradeTax</h1>

Type: rdf:Property

Comments: A tax that is applied to this logistics service charge.

Domains: 

[edi3:ServiceCharge](#ServiceCharge)


<h1 id="PlusToleranceQuantity">PlusToleranceQuantity</h1>

Type: rdf:Property

Comments: The plus tolerance quantity from the planned or requested quantity in this supply chain supply plan.

Domains: 

[edi3:SupplyPlan](#SupplyPlan)


<h1 id="ImporterTradeParty">ImporterTradeParty</h1>

Type: rdf:Property

Comments: The party who imports this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="PreviousReferencedDocument">PreviousReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>A previous document related to this cross-border regulatory procedure.<br/>A previous document referenced for this exchanged declaration.<br/>

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)
[edi3:Declaration](#Declaration)


<h1 id="DesignatedProductClassification">DesignatedProductClassification</h1>

Type: rdf:Property

Comments: A product classification designated for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="SeriesStartIdentifier">SeriesStartIdentifier</h1>

Type: rdf:Property

Comments: The unique identifier of the start of a series of logistics labels.

Domains: 

[edi3:Label](#Label)


<h1 id="ApplicablePaymentBalanceOut">ApplicablePaymentBalanceOut</h1>

Type: rdf:Property

Comments: A balance out applicable to this trade settlement payment monetary summation.

Domains: 

[edi3:MonetarySummation](#MonetarySummation)


<h1 id="GermanBankleitzahlIdentificationIdentifier">GermanBankleitzahlIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique German Bankleitzahl identifier for this debtor financial institution.<br/>The unique German Bankleitzahl identifier for this creditor financial institution.<br/>

Domains: 

[edi3:FinancialInstitution](#FinancialInstitution)


<h1 id="TunnelRestrictionCode">TunnelRestrictionCode</h1>

Type: rdf:Property

Comments: The code specifying the tunnel restriction for these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="StatementCode">StatementCode</h1>

Type: rdf:Property

Comments: The code specifying the statement for this document authentication.

Domains: 

[edi3:Authentication](#Authentication)


<h1 id="AccessRightsCode">AccessRightsCode</h1>

Type: rdf:Property

Comments: The code specifying the access rights, such as unlimited, restricted, prohibited, for this requesting party.

Domains: 

[edi3:Party](#Party)


<h1 id="RelevantTradeParty">RelevantTradeParty</h1>

Type: rdf:Property

Comments: <br/>A party relevant for this line trade agreement.<br/>A relevant party for this header trade agreement.<br/>A relevant party for this header trade settlement.<br/>

Domains: 

[edi3:TradeSettlement](#TradeSettlement)
[edi3:TradeAgreement](#TradeAgreement)


<h1 id="BuyerTaxRepresentativeTradeParty">BuyerTaxRepresentativeTradeParty</h1>

Type: rdf:Property

Comments: The party acting as a tax representative for the buyer for this header trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="BusinessProcessSpecifiedDocumentContextParameter">BusinessProcessSpecifiedDocumentContextParameter</h1>

Type: rdf:Property

Comments: A business process context parameter specified for this exchanged document context.

Domains: 

[edi3:Context](#Context)


<h1 id="OriginTradeCountry">OriginTradeCountry</h1>

Type: rdf:Property

Comments: <br/>A country of origin for this supply chain consignment.<br/>A country of origin for this trade product.<br/>The country of origin where this supply chain consignment item has been produced.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:Consignment](#Consignment)
[edi3:Product](#Product)


<h1 id="AssociatedLogisticsLocation">AssociatedLogisticsLocation</h1>

Type: rdf:Property

Comments: <br/>A logistics location associated with this specified geographical point.<br/>A logistics location associated with this specified geographical line.<br/>A logistics location associated with this specified geographical grid.<br/>A logistics location associated with this specified circle.<br/>A logistics location associated with this specified polygon.<br/>

Domains: 

[edi3:GeographicalPoint](#GeographicalPoint)
[edi3:Circle](#Circle)
[edi3:Polygon](#Polygon)
[edi3:GeographicalLine](#GeographicalLine)
[edi3:GeographicalGrid](#GeographicalGrid)


<h1 id="RadiusMeasure">RadiusMeasure</h1>

Type: rdf:Property

Comments: The measure of the radius for this specified circle.

Domains: 

[edi3:Circle](#Circle)


<h1 id="SeriesEndIdentificationIdentifier">SeriesEndIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique identifier of the end of a series of packages within this logistics package.<br/>The identifier of the end of a series of packages within this referenced logistics package.<br/>

Domains: 

[edi3:Package](#Package)


<h1 id="SICIdentificationIdentifier">SICIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique Swiss Interbank Clearing (SIC) Code identifier for this debtor financial institution.<br/>The unique Swiss Interbank Clearing (SIC) Code identifier for this creditor financial institution.<br/>

Domains: 

[edi3:FinancialInstitution](#FinancialInstitution)


<h1 id="AcknowledgementStatusAcknowledgementCode">AcknowledgementStatusAcknowledgementCode</h1>

Type: rdf:Property

Comments: A code specifying an acknowledgment status for this acknowledgement document.

Domains: 

[edi3:Document](#Document)


<h1 id="ProductEndUserTradeParty">ProductEndUserTradeParty</h1>

Type: rdf:Property

Comments: <br/>The party acting as the end user for the products in this line trade agreement.<br/>The party acting as the end user for the products in this header trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="SpecificCircumstanceCode">SpecificCircumstanceCode</h1>

Type: rdf:Property

Comments: The code specifying a specific circumstance in this exchanged declaration.

Domains: 

[edi3:Declaration](#Declaration)


<h1 id="DueDateTypeTimeReferenceCode">DueDateTypeTimeReferenceCode</h1>

Type: rdf:Property

Comments: The code specifying a type of due date for this trade tax.

Domains: 

[edi3:Tax](#Tax)


<h1 id="StatusStatusCode">StatusStatusCode</h1>

Type: rdf:Property

Comments: <br/>The code specifying a status for a transport route, such as planned or actual.<br/>A code specifying a status for this acknowledgement document.<br/>The code specifying a status for the logistics transport movement, such as estimated or final.<br/>

Domains: 

[edi3:TransportMovement](#TransportMovement)
[edi3:Document](#Document)
[edi3:Route](#Route)


<h1 id="CategoryTypeCode">CategoryTypeCode</h1>

Type: rdf:Property

Comments: <br/>A code specifying the category type of this referenced transport service.<br/>A code specifying a type of category for this transport service.<br/>

Domains: 

[edi3:Service](#Service)


<h1 id="UserSpecifiedDocumentContextParameter">UserSpecifiedDocumentContextParameter</h1>

Type: rdf:Property

Comments: A user specified document context parameter specified for this exchanged document context.

Domains: 

[edi3:Context](#Context)


<h1 id="CatalogueRequestReferencedDocument">CatalogueRequestReferencedDocument</h1>

Type: rdf:Property

Comments: A catalogue request document referenced in this header trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="CategoryAppliedTax">CategoryAppliedTax</h1>

Type: rdf:Property

Comments: The applied tax category of this applied allowance charge.

Domains: 

[edi3:AllowanceCharge](#AllowanceCharge)


<h1 id="VOIPUniversalCommunication">VOIPUniversalCommunication</h1>

Type: rdf:Property

Comments: Voice Over Internet Protocol (VOIP) communication information for this trade contact.

Domains: 

[edi3:Contact](#Contact)


<h1 id="ApplicableCrossBorderRegulatoryProcedure">ApplicableCrossBorderRegulatoryProcedure</h1>

Type: rdf:Property

Comments: <br/>A cross-border regulatory procedure applicable to this logistics transport movement.<br/>A cross-border regulatory procedure applicable to this supply chain consignment.<br/>A cross-border regulatory procedure applicable to this header trade agreement.<br/>A cross-border regulatory procedure applicable to this referenced supply chain consignment.<br/>A cross-border regulatory procedure applicable to this supply chain consignment item.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:Consignment](#Consignment)
[edi3:TransportMovement](#TransportMovement)
[edi3:TradeAgreement](#TradeAgreement)


<h1 id="DeliveryTradeParty">DeliveryTradeParty</h1>

Type: rdf:Property

Comments: <br/>The party to whom this referenced supply chain consignment will be or has been delivered.<br/>The party to whom this supply chain consignment item will be or has been delivered.<br/>The party to whom this supply chain consignment will be, or has been, delivered.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:Consignment](#Consignment)


<h1 id="ImportCustomsOfficeSpecifiedLogisticsLocation">ImportCustomsOfficeSpecifiedLogisticsLocation</h1>

Type: rdf:Property

Comments: The location of the specified customs office which is responsible for import formalities for the goods which are subject to this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="ColourCode">ColourCode</h1>

Type: rdf:Property

Comments: <br/>The code specifying the colour for this trade product.<br/>The code specifying the colour of this logistics package.<br/>The code specifying the colour of this referenced logistics package.<br/>

Domains: 

[edi3:Product](#Product)
[edi3:Package](#Package)


<h1 id="UtilizedReferencedLogisticsTransportEquipment">UtilizedReferencedLogisticsTransportEquipment</h1>

Type: rdf:Property

Comments: A piece of logistics transport equipment, at line level, utilized for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="ConsignorTradeParty">ConsignorTradeParty</h1>

Type: rdf:Property

Comments: <br/>The consignor party for this referenced supply chain consignment.<br/>The consignor party for this supply chain consignment.<br/>

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="SalesAgentTradeParty">SalesAgentTradeParty</h1>

Type: rdf:Property

Comments: The agent party representing the seller for this header trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="WarehouseStorageTransportEvent">WarehouseStorageTransportEvent</h1>

Type: rdf:Property

Comments: A warehouse storage event for this referenced supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="StandardNameText">StandardNameText</h1>

Type: rdf:Property

Comments: The name, expressed as text, of the standard applicable for this certification test specification report.

Domains: 

[edi3:TestSpecificationReport](#TestSpecificationReport)


<h1 id="SpecifiedTradeProduct">SpecifiedTradeProduct</h1>

Type: rdf:Property

Comments: A product specified for this supply chain trade line item.

Domains: 

[edi3:TradeLineItem](#TradeLineItem)


<h1 id="DamageRemarkText">DamageRemarkText</h1>

Type: rdf:Property

Comments: A damage remark, expressed as text, for this piece of logistics transport equipment.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="ReferencedReferencedDocument">ReferencedReferencedDocument</h1>

Type: rdf:Property

Comments: A document referenced by this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="ChemicalConcentrationMeasure">ChemicalConcentrationMeasure</h1>

Type: rdf:Property

Comments: A measure of the chemical concentration of this applied chemical treatment.

Domains: 

[edi3:ChemicalTreatment](#ChemicalTreatment)


<h1 id="UsedToDateQuotaQuantity">UsedToDateQuotaQuantity</h1>

Type: rdf:Property

Comments: The quantity of the quota used to date under this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="ReportingIOTDeviceTransportEvent">ReportingIOTDeviceTransportEvent</h1>

Type: rdf:Property

Comments: An IOT device reported transport event for this piece of logistics transport equipment.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="OperatorTradeParty">OperatorTradeParty</h1>

Type: rdf:Property

Comments: <br/>The party operating this logistics means of transport.<br/>A trade party who is an operator of this product handling process.<br/>The operator party, such as terminal operator, service provider, network operator of this monitoring IOT device.<br/>

Domains: 

[edi3:Process](#Process)
[edi3:TransportMeans](#TransportMeans)
[edi3:IOTDevice](#IOTDevice)


<h1 id="AssociatedTradeParty">AssociatedTradeParty</h1>

Type: rdf:Property

Comments: <br/>A trade party associated with this supply chain consignment.<br/>A party associated with this trade party, such as a local agent of a shipping line.<br/>

Domains: 

[edi3:Party](#Party)
[edi3:Consignment](#Consignment)


<h1 id="ConsignorProvidedInformationText">ConsignorProvidedInformationText</h1>

Type: rdf:Property

Comments: Information, expressed as text, provided by the consignor for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="DisposalMethodCode">DisposalMethodCode</h1>

Type: rdf:Property

Comments: A code specifying the disposal method of this supply chain packaging.

Domains: 

[edi3:Packaging](#Packaging)


<h1 id="MarketplaceOrderReferencedDocument">MarketplaceOrderReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>The marketplace generated order document referenced in this header trade agreement.<br/>The marketplace generated order document referenced in this line trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="ReportReceiptDateTime">ReportReceiptDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time or other date time value of the receipt of the report being acknowledged by this acknowledgment document.

Domains: 

[edi3:Document](#Document)


<h1 id="SpecifiedLogisticsRiskAnalysisResult">SpecifiedLogisticsRiskAnalysisResult</h1>

Type: rdf:Property

Comments: <br/>A result of a logistics risk analysis calculation specified for this supply chain consignment.<br/>A result of a logistics risk analysis calculation specified for this transport equipment.<br/>A result of a logistics risk analysis calculation specified for this trade party.<br/>A result of a logistics risk analysis calculation specified for this transport movement.<br/>A result of a logistics risk analysis specified for this referenced supply chain consignment.<br/>

Domains: 

[edi3:Party](#Party)
[edi3:TransportEquipment](#TransportEquipment)
[edi3:Consignment](#Consignment)
[edi3:TransportMovement](#TransportMovement)


<h1 id="TransportServicesBuyerTradeParty">TransportServicesBuyerTradeParty</h1>

Type: rdf:Property

Comments: <br/>The party which is the buyer of the transport services for this supply chain consignment.<br/>The transport services buyer party for this piece of logistics transport equipment.<br/>

Domains: 

[edi3:TransportEquipment](#TransportEquipment)
[edi3:Consignment](#Consignment)


<h1 id="SpecifiedSpatialDimension">SpecifiedSpatialDimension</h1>

Type: rdf:Property

Comments: Spatial dimensions specified for this logistics means of transport.

Domains: 

[edi3:TransportMeans](#TransportMeans)


<h1 id="SecurityInformationNote">SecurityInformationNote</h1>

Type: rdf:Property

Comments: A security information note for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="ClassProductCharacteristic">ClassProductCharacteristic</h1>

Type: rdf:Property

Comments: A product class characteristic for this product classification.

Domains: 

[edi3:Classification](#Classification)


<h1 id="AxisLabelListText">AxisLabelListText</h1>

Type: rdf:Property

Comments: <br/>An ordered list of axis labels, expressed as text, for this specified direct position.<br/>An ordered list of axis labels, expressed as text, for this specified direct position list.<br/>

Domains: 

[edi3:DirectPosition](#DirectPosition)
[edi3:DirectPositionList](#DirectPositionList)


<h1 id="OnboardQuantity">OnboardQuantity</h1>

Type: rdf:Property

Comments: <br/>An onboard quantity for this stores inventory item.<br/>An onboard number of these specified personal effects.<br/>

Domains: 

[edi3:PersonalEffects](#PersonalEffects)
[edi3:Inventory](#Inventory)


<h1 id="IntermediarySpecifiedCreditorFinancialInstitution">IntermediarySpecifiedCreditorFinancialInstitution</h1>

Type: rdf:Property

Comments: The creditor financial institution specified as the intermediary in this financing request document.

Domains: 

[edi3:Document](#Document)


<h1 id="InTransitIndicator">InTransitIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not this transport person is in transit.

Domains: 

[edi3:Person](#Person)


<h1 id="CostReferenceDimensionPatternText">CostReferenceDimensionPatternText</h1>

Type: rdf:Property

Comments: The cost reference dimension pattern, expressed as text, for this trade accounting account.

Domains: 

[edi3:AccountingAccount](#AccountingAccount)


<h1 id="MethodNameText">MethodNameText</h1>

Type: rdf:Property

Comments: The name, expressed as text, of the method of this applied chemical treatment.

Domains: 

[edi3:ChemicalTreatment](#ChemicalTreatment)


<h1 id="CountryIdentifier">CountryIdentifier</h1>

Type: rdf:Property

Comments: <br/>The identifier of the country for this government registration.<br/>An identifier of the country in which this legal registration is valid.<br/>The unique identifier of a country for this financial institution address (Reference ISO 3166 and UN/ECE Rec 3).<br/>A unique country identifier for this location party.<br/>

Domains: 

[edi3:Party](#Party)
[edi3:Address](#Address)
[edi3:Registration](#Registration)


<h1 id="MasterResponsibleTransportPerson">MasterResponsibleTransportPerson</h1>

Type: rdf:Property

Comments: The person legally responsible for the operation of the means of transport used for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="ProcedureText">ProcedureText</h1>

Type: rdf:Property

Comments: <br/>A procedure, expressed as text, for these handling instructions.<br/>A procedure, expressed as text, for these temperature setting instructions.<br/>

Domains: 

[edi3:Instructions](#Instructions)


<h1 id="PricingBaseApplicableLogisticsLocation">PricingBaseApplicableLogisticsLocation</h1>

Type: rdf:Property

Comments: The logistics location applicable to the pricing base for this header trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="MarketingCampaignReferenceReferencedDocument">MarketingCampaignReferenceReferencedDocument</h1>

Type: rdf:Property

Comments: A referenced marketing campaign document for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="EndIdentifier">EndIdentifier</h1>

Type: rdf:Property

Comments: The identifier of the end of this specified range.

Domains: 

[edi3:Range](#Range)


<h1 id="ChargeableWeightWeightUnitMeasure">ChargeableWeightWeightUnitMeasure</h1>

Type: rdf:Property

Comments: <br/>A measure of a chargeable weight of this supply chain consignment.<br/>A measure of the supply chain consignment item weight on which charges are to be based.<br/>The measure of the chargeable weight, at line level, for this trade delivery.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:TradeDelivery](#TradeDelivery)
[edi3:Consignment](#Consignment)


<h1 id="ItemGroupedWorkItem">ItemGroupedWorkItem</h1>

Type: rdf:Property

Comments: <br/>A grouped work item within this grouped work item.<br/>A grouped work item in this valuation breakdown statement.<br/>

Domains: 

[edi3:WorkItem](#WorkItem)
[edi3:BreakdownStatement](#BreakdownStatement)


<h1 id="ObtainedFormattedDateTime">ObtainedFormattedDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time or other date time value when this certified accreditation was obtained.

Domains: 

[edi3:Accreditation](#Accreditation)


<h1 id="UnloadingInspectionTradeParty">UnloadingInspectionTradeParty</h1>

Type: rdf:Property

Comments: The inspection party for the unloading of this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="SubordinateSubordinateLocation">SubordinateSubordinateLocation</h1>

Type: rdf:Property

Comments: A location subordinate to this logistics related location.

Domains: 

[edi3:Location](#Location)


<h1 id="DimensionNumeric">DimensionNumeric</h1>

Type: rdf:Property

Comments: The dimension, expressed as a number, of this geographical grid.

Domains: 

[edi3:GeographicalGrid](#GeographicalGrid)


<h1 id="RegisteredDeferredPaymentPayerIdentifier">RegisteredDeferredPaymentPayerIdentifier</h1>

Type: rdf:Property

Comments: The identifier of the registered deferred payment payer for this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="ChangedDateTime">ChangedDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time, or other date time value when this recorded status changed.

Domains: 

[edi3:Status](#Status)


<h1 id="StartDateFlexibilityCode">StartDateFlexibilityCode</h1>

Type: rdf:Property

Comments: The code specifying the flexibility of the start date of this specified period.

Domains: 

[edi3:Period](#Period)


<h1 id="AdditionalReferencedDocument">AdditionalReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>An additional document, at header level, referenced for this trade delivery.<br/>An additional document referenced in this subordinate line trade agreement.<br/>An additional document referenced in this line trade agreement.<br/>An additional document referenced in this header trade agreement.<br/>An additional document, at line level, referenced for this trade delivery.<br/>An additional document referenced in this line trade settlement.<br/>

Domains: 

[edi3:TradeSettlement](#TradeSettlement)
[edi3:TradeDelivery](#TradeDelivery)
[edi3:TradeAgreement](#TradeAgreement)


<h1 id="DeliveryTradeLocation">DeliveryTradeLocation</h1>

Type: rdf:Property

Comments: A delivery location for this trade price.

Domains: 

[edi3:Price](#Price)


<h1 id="GrantedProductCertificate">GrantedProductCertificate</h1>

Type: rdf:Property

Comments: <br/>A product certificate granted for this monitoring IOT device.<br/>A product certificate granted for this monitoring sensor.<br/>

Domains: 

[edi3:Sensor](#Sensor)
[edi3:IOTDevice](#IOTDevice)


<h1 id="PaymentIdentifier">PaymentIdentifier</h1>

Type: rdf:Property

Comments: The unique identifier of the payment of this trade related tax, levy or duty.

Domains: 

[edi3:Tax](#Tax)


<h1 id="CategoryTransportServiceCategoryCode">CategoryTransportServiceCategoryCode</h1>

Type: rdf:Property

Comments: The code specifying the category of this logistics service charge [Reference United Nations Code List (UNCL) 5237].

Domains: 

[edi3:ServiceCharge](#ServiceCharge)


<h1 id="QuotationApplicableTradeCurrencyExchange">QuotationApplicableTradeCurrencyExchange</h1>

Type: rdf:Property

Comments: The currency exchange applicable to the quotation currency in this header trade settlement.

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="ConfigurableIndicator">ConfigurableIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not this trade product is configurable.

Domains: 

[edi3:Product](#Product)


<h1 id="CountNumeric">CountNumeric</h1>

Type: rdf:Property

Comments: <br/>A count for this specified direct position.<br/>A count for this specified direct position list.<br/>

Domains: 

[edi3:DirectPosition](#DirectPosition)
[edi3:DirectPositionList](#DirectPositionList)


<h1 id="IssueReasonCode">IssueReasonCode</h1>

Type: rdf:Property

Comments: The code specifying the reason why this product certificate was issued.

Domains: 

[edi3:Certificate](#Certificate)


<h1 id="RecipientTradeParty">RecipientTradeParty</h1>

Type: rdf:Property

Comments: <br/>A trade related party that receives this referenced document.<br/>A trade party that receives this exchanged document.<br/>

Domains: 

[edi3:Document](#Document)


<h1 id="OverpackInformationText">OverpackInformationText</h1>

Type: rdf:Property

Comments: Overpack information, expressed as text, for these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="ReferenceIdentificationIdentifier">ReferenceIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The unique identifier of another work item referenced by this basic work item.

Domains: 

[edi3:WorkItem](#WorkItem)


<h1 id="ItineraryTransportRoute">ItineraryTransportRoute</h1>

Type: rdf:Property

Comments: A route in the itinerary of this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="BalanceOutAmount">BalanceOutAmount</h1>

Type: rdf:Property

Comments: <br/>A monetary value that is an amount balanced out for this trade settlement header monetary summation.<br/>A monetary value that is an amount balanced out for this trade settlement payment monetary summation.<br/>

Domains: 

[edi3:MonetarySummation](#MonetarySummation)


<h1 id="LineStatusReasonText">LineStatusReasonText</h1>

Type: rdf:Property

Comments: A reason, expressed as text, for the line status in this document line.

Domains: 

[edi3:Document](#Document)


<h1 id="FreightInvoiceTypeCode">FreightInvoiceTypeCode</h1>

Type: rdf:Property

Comments: A code specifying a type of freight invoice of this logistics service charge.

Domains: 

[edi3:ServiceCharge](#ServiceCharge)


<h1 id="CoordinateText">CoordinateText</h1>

Type: rdf:Property

Comments: <br/>A coordinate, expressed as text, for this specified linear ring.<br/>The coordinate, expressed as text, for this specified direct position list.<br/>

Domains: 

[edi3:DirectPositionList](#DirectPositionList)
[edi3:LinearRing](#LinearRing)


<h1 id="MaximumOrderQuantityOrderingSpecifiedPeriod">MaximumOrderQuantityOrderingSpecifiedPeriod</h1>

Type: rdf:Property

Comments: The maximum order quantity ordering period specified in this line trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="IdentificationCountryIdentifier">IdentificationCountryIdentifier</h1>

Type: rdf:Property

Comments: A unique identifier for this trade country.

Domains: 

[edi3:Country](#Country)


<h1 id="TaxCurrencyCurrencyCode">TaxCurrencyCurrencyCode</h1>

Type: rdf:Property

Comments: The code specifying the tax currency for this header trade settlement.

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="IBEIIdentificationIdentifier">IBEIIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The International Business Entity Identifier (IBEI) for this financial identity.

Domains: 

[edi3:Identity](#Identity)


<h1 id="MainCarriageLogisticsTransportMovement">MainCarriageLogisticsTransportMovement</h1>

Type: rdf:Property

Comments: A main carriage logistics transport movement for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="ModelIdentificationIdentifier">ModelIdentificationIdentifier</h1>

Type: rdf:Property

Comments: A unique model identifier for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="ReaderSpecifiedBinaryFile">ReaderSpecifiedBinaryFile</h1>

Type: rdf:Property

Comments: A specified binary file used to read this valuation breakdown statement.

Domains: 

[edi3:BreakdownStatement](#BreakdownStatement)


<h1 id="TransportTransportSettingTemperature">TransportTransportSettingTemperature</h1>

Type: rdf:Property

Comments: The transport temperature setting for this supply chain consignment item.

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)


<h1 id="IncludedTradeCountry">IncludedTradeCountry</h1>

Type: rdf:Property

Comments: A country included in this trade geopolitical region.

Domains: 

[edi3:GeopoliticalRegion](#GeopoliticalRegion)


<h1 id="AcquisitionDateTime">AcquisitionDateTime</h1>

Type: rdf:Property

Comments: <br/>The date, time, date time or other date time value of the acquisition of this geographical coordinate.<br/>The date, time, date time, or other date time value of an acquisition for this cross-border regulatory procedure.<br/>

Domains: 

[edi3:GeographicalCoordinate](#GeographicalCoordinate)
[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="PartyRiskRelatedCode">PartyRiskRelatedCode</h1>

Type: rdf:Property

Comments: A code specifying a party related risk for this logistics risk analysis result.

Domains: 

[edi3:RiskAnalysisResult](#RiskAnalysisResult)


<h1 id="CreditorReferenceIdentifier">CreditorReferenceIdentifier</h1>

Type: rdf:Property

Comments: The identifier of the creditor reference for this header trade settlement, such as a specific identifier assigned by the creditor to reference the financial transaction.

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="NetVolumeMeasure">NetVolumeMeasure</h1>

Type: rdf:Property

Comments: A measure of a net volume for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="DescriptionReferenceText">DescriptionReferenceText</h1>

Type: rdf:Property

Comments: The description reference, expressed as text, for this geographical object characteristic.

Domains: 

[edi3:GeographicalObjectCharacteristic](#GeographicalObjectCharacteristic)


<h1 id="ContainedSupplyChainConsignment">ContainedSupplyChainConsignment</h1>

Type: rdf:Property

Comments: A consignment contained in this piece of logistics transport equipment.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="CareOfText">CareOfText</h1>

Type: rdf:Property

Comments: The name, expressed as text, of a person or organization at this trade address to whom incoming mail is marked with words such as 'care of' or 'C/O'.

Domains: 

[edi3:Address](#Address)


<h1 id="AuthorizedPersonNameText">AuthorizedPersonNameText</h1>

Type: rdf:Property

Comments: The name, expressed as text, of the authorized person for this trade contact.

Domains: 

[edi3:Contact](#Contact)


<h1 id="CargoInsuranceInstructionsInformationText">CargoInsuranceInstructionsInformationText</h1>

Type: rdf:Property

Comments: Cargo insurance instructions, expressed as text, for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="CopyRequiredQuantity">CopyRequiredQuantity</h1>

Type: rdf:Property

Comments: The number of copies required of this exchanged document.

Domains: 

[edi3:Document](#Document)


<h1 id="EmbeddedMonitoringSensor">EmbeddedMonitoringSensor</h1>

Type: rdf:Property

Comments: An embedded sensor of this monitoring IOT device.

Domains: 

[edi3:IOTDevice](#IOTDevice)


<h1 id="ImportationTradeCountry">ImportationTradeCountry</h1>

Type: rdf:Property

Comments: The importation country for this supply chain consignment item.

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)


<h1 id="MaximumValueMeasure">MaximumValueMeasure</h1>

Type: rdf:Property

Comments: <br/>The measure of the maximum value of this instructed temperature.<br/>The measure of the maximum value for this specified range.<br/>

Domains: 

[edi3:Temperature](#Temperature)
[edi3:Range](#Range)


<h1 id="HelipadIndicator">HelipadIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not there is a helipad on this logistics means of transport.

Domains: 

[edi3:TransportMeans](#TransportMeans)


<h1 id="BuyerAssignedIdentificationIdentifier">BuyerAssignedIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique buyer assigned identifier for this trade product.<br/>The unique buyer assigned identifier for this referenced product.<br/>

Domains: 

[edi3:Product](#Product)


<h1 id="LongitudeMeasure">LongitudeMeasure</h1>

Type: rdf:Property

Comments: <br/>The measure of the longitude as an angular distance east or west from the Greenwich meridian to the meridian of a specific place (Reference ISO 6709).<br/>The measure of the longitude as an angular distance east or west from the Greenwich meridian to the meridian of a specific place for this specified geographical coordinate. (Reference ISO 6709).<br/>

Domains: 

[edi3:GeographicalCoordinate](#GeographicalCoordinate)


<h1 id="LanguageIdentifier">LanguageIdentifier</h1>

Type: rdf:Property

Comments: A unique identifier for a language used in this exchanged document.

Domains: 

[edi3:Document](#Document)


<h1 id="SpecifiedTradeSettlementFinancialCard">SpecifiedTradeSettlementFinancialCard</h1>

Type: rdf:Property

Comments: <br/>A financial card specified in this header trade settlement.<br/>A financial card specified in this line trade settlement.<br/>

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="DirectTelephoneUniversalCommunication">DirectTelephoneUniversalCommunication</h1>

Type: rdf:Property

Comments: The direct telephone communication information for this trade contact.

Domains: 

[edi3:Contact](#Contact)


<h1 id="ExteriorSpecifiedLinearRing">ExteriorSpecifiedLinearRing</h1>

Type: rdf:Property

Comments: The exterior linear specified ring for this polygon.

Domains: 

[edi3:Polygon](#Polygon)


<h1 id="NonTariffChargeAmount">NonTariffChargeAmount</h1>

Type: rdf:Property

Comments: A monetary value of all non-tariff charges for this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="SealQuantity">SealQuantity</h1>

Type: rdf:Property

Comments: The quantity of seals for this piece of logistics transport equipment.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="IncludingTaxesLineTotalAmount">IncludingTaxesLineTotalAmount</h1>

Type: rdf:Property

Comments: <br/>A monetary value of the line total, including taxes, being reported in this trade settlement line monetary summation.<br/>A monetary value of the line total, including taxes, being reported in this trade settlement payment monetary summation.<br/>A monetary value of the total of all line amounts, including all duties and taxes, being reported in this trade settlement header monetary summation.<br/>

Domains: 

[edi3:MonetarySummation](#MonetarySummation)


<h1 id="ConsumerAgeDescriptionText">ConsumerAgeDescriptionText</h1>

Type: rdf:Property

Comments: A consumer age description, expressed as text, for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="AffectedDistanceLinearUnitMeasure">AffectedDistanceLinearUnitMeasure</h1>

Type: rdf:Property

Comments: The affected distance over which this calculated emission is measured.

Domains: 

[edi3:Emission](#Emission)


<h1 id="SecurityLevelCode">SecurityLevelCode</h1>

Type: rdf:Property

Comments: <br/>A code specifying a security level for this transport route.<br/>A security level code for this transport event.<br/>

Domains: 

[edi3:Event](#Event)
[edi3:Route](#Route)


<h1 id="ApplicableTransportCargoInsurance">ApplicableTransportCargoInsurance</h1>

Type: rdf:Property

Comments: The cargo insurance applicable to this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="BarcodeLogisticsLabel">BarcodeLogisticsLabel</h1>

Type: rdf:Property

Comments: A barcode label that is a part of these logistics shipping marks.

Domains: 

[edi3:ShippingMarks](#ShippingMarks)


<h1 id="UsedGeographicalCoordinateSourceSystem">UsedGeographicalCoordinateSourceSystem</h1>

Type: rdf:Property

Comments: <br/>The geographical coordinate source system used for this specified geographical feature.<br/>The geographical coordinate source system used for this geographical coordinate.<br/>

Domains: 

[edi3:GeographicalCoordinate](#GeographicalCoordinate)
[edi3:GeographicalFeature](#GeographicalFeature)


<h1 id="ValueSpecifiedBinaryFile">ValueSpecifiedBinaryFile</h1>

Type: rdf:Property

Comments: The value for this product characteristic expressed in a binary file.

Domains: 

[edi3:Characteristic](#Characteristic)


<h1 id="ContentText">ContentText</h1>

Type: rdf:Property

Comments: <br/>A content, expressed as text, of this note.<br/>Content, expressed as text, of this packaging marking.<br/>The content, expressed as text, of this specification response.<br/>The content, expressed as text, of this specification query.<br/>Content, expressed as text, of this document clause.<br/>Content, expressed as text, for this work item complex description.<br/>

Domains: 

[edi3:Response](#Response)
[edi3:Query](#Query)
[edi3:Note](#Note)
[edi3:ComplexDescription](#ComplexDescription)
[edi3:Marking](#Marking)
[edi3:Clause](#Clause)


<h1 id="SpecifiedTransactionIdentifier">SpecifiedTransactionIdentifier</h1>

Type: rdf:Property

Comments: The identifier of a specified transaction in this exchanged document context.

Domains: 

[edi3:Context](#Context)


<h1 id="MaximumValueTemperatureUnitMeasure">MaximumValueTemperatureUnitMeasure</h1>

Type: rdf:Property

Comments: <br/>The measure of the highest value of a range for this specified temperature, such as a maximum temperature value of fourteen degrees Celsius.<br/>The measure of the highest value of this transport setting temperature, such as a maximum temperature value of fourteen degrees Celsius.<br/>

Domains: 

[edi3:Temperature](#Temperature)


<h1 id="SpecifiedCreditorFinancialAccount">SpecifiedCreditorFinancialAccount</h1>

Type: rdf:Property

Comments: <br/>The creditor financial account, used for crediting, specified for this requesting party.<br/>The creditor financial account, used for crediting, specified for this financing summary document.<br/>A creditor financial account specified for this trade settlement payment means.<br/>

Domains: 

[edi3:Party](#Party)
[edi3:Document](#Document)
[edi3:PaymentMeans](#PaymentMeans)


<h1 id="ControlResultText">ControlResultText</h1>

Type: rdf:Property

Comments: A control result, expressed as text, for this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="TravelIdentityReferencedDocument">TravelIdentityReferencedDocument</h1>

Type: rdf:Property

Comments: A referenced travel identity document for this transport person.

Domains: 

[edi3:Person](#Person)


<h1 id="ItemBuyerTradeParty">ItemBuyerTradeParty</h1>

Type: rdf:Property

Comments: The item buyer party for this line trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="SelfAssessedBasisAmount">SelfAssessedBasisAmount</h1>

Type: rdf:Property

Comments: A monetary value of the amount on which this trade related tax, levy or duty has been calculated on a self-assessment basis.

Domains: 

[edi3:Tax](#Tax)


<h1 id="ScheduledDepartureRelatedDateTime">ScheduledDepartureRelatedDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time or other date time value of the scheduled departure related to this transport event.

Domains: 

[edi3:Event](#Event)


<h1 id="SpecifiedFinancialIdentity">SpecifiedFinancialIdentity</h1>

Type: rdf:Property

Comments: The financial identity specified for this trade party.

Domains: 

[edi3:Party](#Party)


<h1 id="CurrencyExchangeRate">CurrencyExchangeRate</h1>

Type: rdf:Property

Comments: The rate of currency exchange in this exchanged declaration.

Domains: 

[edi3:Declaration](#Declaration)


<h1 id="FormattedCancellationAnnouncedLaunchFormattedDateTime">FormattedCancellationAnnouncedLaunchFormattedDateTime</h1>

Type: rdf:Property

Comments: The formatted date, time, date time, or other date time value of the cancellation of the announced launch of this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="FaxTelecommunicationCommunication">FaxTelecommunicationCommunication</h1>

Type: rdf:Property

Comments: Facsimile communication information for this contact person.

Domains: 

[edi3:Person](#Person)


<h1 id="PaidAmount">PaidAmount</h1>

Type: rdf:Property

Comments: <br/>A monetary value paid or to be paid for this instalment payment.<br/>The monetary value of the funds or securities paid in this advance payment.<br/>

Domains: 

[edi3:Payment](#Payment)


<h1 id="ApplicableKeyword">ApplicableKeyword</h1>

Type: rdf:Property

Comments: A keyword applicable to this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="DepartmentNameText">DepartmentNameText</h1>

Type: rdf:Property

Comments: <br/>The name, expressed as text, of a department for this trade address.<br/>The name, expressed as text, of a department within this financial institution address.<br/>The name, expressed as text, of the department to which this trade contact belongs within an organization.<br/>

Domains: 

[edi3:Address](#Address)
[edi3:Contact](#Contact)


<h1 id="UsedLogisticsLabel">UsedLogisticsLabel</h1>

Type: rdf:Property

Comments: A logistics label, at line level, used for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="TypeAccountingAccountTypeCode">TypeAccountingAccountTypeCode</h1>

Type: rdf:Property

Comments: The code specifying the type of trade accounting account, such as general (main), secondary, cost accounting or budget account.

Domains: 

[edi3:AccountingAccount](#AccountingAccount)


<h1 id="ModeTransportModeCode">ModeTransportModeCode</h1>

Type: rdf:Property

Comments: The code specifying the mode, such as by air, sea, rail, road or inland waterway, for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="RegistrationTradeCountry">RegistrationTradeCountry</h1>

Type: rdf:Property

Comments: The country of registration of this logistics means of transport.

Domains: 

[edi3:TransportMeans](#TransportMeans)


<h1 id="ProductWeightLossInformationAmount">ProductWeightLossInformationAmount</h1>

Type: rdf:Property

Comments: A monetary value of the loss of weight of a product, such as fresh goods, stated for information purposes in this trade settlement line monetary summation.

Domains: 

[edi3:MonetarySummation](#MonetarySummation)


<h1 id="MethodCode">MethodCode</h1>

Type: rdf:Property

Comments: <br/>The code specifying the method of this communication pairing.<br/>The code specifying the method by which this cross-border customs valuation is determined.<br/>

Domains: 

[edi3:CustomsValuation](#CustomsValuation)
[edi3:Pairing](#Pairing)


<h1 id="TotalInvoiceAmount">TotalInvoiceAmount</h1>

Type: rdf:Property

Comments: A monetary value of the total invoice on which this header trade settlement is calculated.

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="ValueUnitMeasure">ValueUnitMeasure</h1>

Type: rdf:Property

Comments: The measure of a value for this transport event.

Domains: 

[edi3:Event](#Event)


<h1 id="PreviousStatusCode">PreviousStatusCode</h1>

Type: rdf:Property

Comments: The code specifying the previous status of this trade workflow object.

Domains: 

[edi3:WorkflowObject](#WorkflowObject)


<h1 id="ClaimRelatedTradeParty">ClaimRelatedTradeParty</h1>

Type: rdf:Property

Comments: The claim related party for this financial adjustment.

Domains: 

[edi3:Adjustment](#Adjustment)


<h1 id="CitySubDivisionNameText">CitySubDivisionNameText</h1>

Type: rdf:Property

Comments: A name, expressed as text, of a sub-division of a city for this trade address, for example a district or borough.

Domains: 

[edi3:Address](#Address)


<h1 id="PersonNameText">PersonNameText</h1>

Type: rdf:Property

Comments: The name, expressed as text, of this trade contact person.

Domains: 

[edi3:Contact](#Contact)


<h1 id="ReasonFinancingStatusReasonCode">ReasonFinancingStatusReasonCode</h1>

Type: rdf:Property

Comments: The code specifying the reason for this financing status.

Domains: 

[edi3:Status](#Status)


<h1 id="LoadingTradeParty">LoadingTradeParty</h1>

Type: rdf:Property

Comments: The party that loads this piece of logistics transport equipment.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="IssueDateTime">IssueDateTime</h1>

Type: rdf:Property

Comments: <br/>The date, time, date time, or other date time value for the issuance of this document line.<br/>The date, time, date time or other date time value for the issuance of this acknowledgement document.<br/>The date, time, date time or other date time value for the issuance of this exchanged document.<br/>The date, time, date and time or other date time value of issue of this document version.<br/>The date, time, date time, or other date time value when this product certificate was issued.<br/>

Domains: 

[edi3:Version](#Version)
[edi3:Document](#Document)
[edi3:Certificate](#Certificate)


<h1 id="QueryIdentificationIdentifier">QueryIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The unique identifier for the query to which this response refers.

Domains: 

[edi3:Response](#Response)


<h1 id="BuyerSuppliedPartsReferenceReferencedDocument">BuyerSuppliedPartsReferenceReferencedDocument</h1>

Type: rdf:Property

Comments: A buyer supplier parts document referenced for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="ContractIdentificationIdentifier">ContractIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The contract identifier of this referenced transport service.

Domains: 

[edi3:Service](#Service)


<h1 id="AdditionalHazardClassificationIdentifier">AdditionalHazardClassificationIdentifier</h1>

Type: rdf:Property

Comments: The unique identifier of an additional hazard class applicable to these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="PlannedShipToDeliverySupplyChainEvent">PlannedShipToDeliverySupplyChainEvent</h1>

Type: rdf:Property

Comments: <br/>The planned ship to delivery event, at line level, for this trade delivery.<br/>The planned ship to delivery event, at header level, for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="ActualDeliverySupplyChainEvent">ActualDeliverySupplyChainEvent</h1>

Type: rdf:Property

Comments: <br/>An actual delivery event, at line level, for this trade delivery.<br/>An actual delivery event, at header level, for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="IdentificationPaymentTermsIdentifier">IdentificationPaymentTermsIdentifier</h1>

Type: rdf:Property

Comments: The unique identifier of these trade payment terms.

Domains: 

[edi3:PaymentTerms](#PaymentTerms)


<h1 id="IssueLogisticsLocation">IssueLogisticsLocation</h1>

Type: rdf:Property

Comments: <br/>The logistics related location where this referenced document has been issued.<br/>The issue location for this document authentication.<br/>The location where this exchanged document has been issued.<br/>

Domains: 

[edi3:Authentication](#Authentication)
[edi3:Document](#Document)


<h1 id="OnboardTransportPerson">OnboardTransportPerson</h1>

Type: rdf:Property

Comments: A person onboard this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="AttachedSpecifiedBinaryFile">AttachedSpecifiedBinaryFile</h1>

Type: rdf:Property

Comments: <br/>A binary file attached to this exchanged document.<br/>A specified binary file attached to this referenced document.<br/>

Domains: 

[edi3:Document](#Document)


<h1 id="TimeZoneCode">TimeZoneCode</h1>

Type: rdf:Property

Comments: The code specifying the time zone of this geographical coordinate.

Domains: 

[edi3:GeographicalCoordinate](#GeographicalCoordinate)


<h1 id="LoadingListQuantity">LoadingListQuantity</h1>

Type: rdf:Property

Comments: The number of loading lists, manifests or similar documents for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="SignatoryText">SignatoryText</h1>

Type: rdf:Property

Comments: The signatory, expressed as text, for this document authentication.

Domains: 

[edi3:Authentication](#Authentication)


<h1 id="TargetEntityIdentifier">TargetEntityIdentifier</h1>

Type: rdf:Property

Comments: The identifier of the target entity for this communication pairing.

Domains: 

[edi3:Pairing](#Pairing)


<h1 id="ExpiryDate">ExpiryDate</h1>

Type: rdf:Property

Comments: The date of expiry up to which this trade settlement financial card is valid.

Domains: 

[edi3:FinancialCard](#FinancialCard)


<h1 id="SubordinateSubordinateSubordinateLocation">SubordinateSubordinateSubordinateLocation</h1>

Type: rdf:Property

Comments: The location subordinate to this subordinate location.

Domains: 

[edi3:Location](#Location)


<h1 id="PowerSupplyTypeCode">PowerSupplyTypeCode</h1>

Type: rdf:Property

Comments: The code specifying the type of power supply for this piece of logistics transport equipment, such as diesel fuel or electricity.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="SelfAssessedCalculatedAmount">SelfAssessedCalculatedAmount</h1>

Type: rdf:Property

Comments: A monetary value of the self-assessed calculated amount of this trade related tax, levy or duty.

Domains: 

[edi3:Tax](#Tax)


<h1 id="LatestOccurrenceDateTime">LatestOccurrenceDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time, or other date time value of the latest occurrence of this supply chain event.

Domains: 

[edi3:Event](#Event)


<h1 id="CoverageTradeParty">CoverageTradeParty</h1>

Type: rdf:Property

Comments: The coverage party for this transport cargo insurance.

Domains: 

[edi3:CargoInsurance](#CargoInsurance)


<h1 id="DueDateTime">DueDateTime</h1>

Type: rdf:Property

Comments: The due date, time, date time, or other date time value of this supply chain event.

Domains: 

[edi3:Event](#Event)


<h1 id="EMSIdentifier">EMSIdentifier</h1>

Type: rdf:Property

Comments: The unique transport emergency procedure (EMS) identifier applicable for these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="SpecifiedTradePaymentTerms">SpecifiedTradePaymentTerms</h1>

Type: rdf:Property

Comments: <br/>Payment terms specified for this header trade settlement.<br/>Payment terms specified for this line trade settlement.<br/>

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="RequestedExecutionDateTime">RequestedExecutionDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time or other date time value of the requested execution of this trade settlement payment.

Domains: 

[edi3:Payment](#Payment)


<h1 id="RespondingSpecificationResponse">RespondingSpecificationResponse</h1>

Type: rdf:Property

Comments: A responding specification response for this work item complex description.

Domains: 

[edi3:ComplexDescription](#ComplexDescription)


<h1 id="TransportMeansText">TransportMeansText</h1>

Type: rdf:Property

Comments: A means of transport, expressed as text, for this transport route.

Domains: 

[edi3:Route](#Route)


<h1 id="InterestRatePercent">InterestRatePercent</h1>

Type: rdf:Property

Comments: The interest rate expressed as a percentage for this trade settlement financial card.

Domains: 

[edi3:FinancialCard](#FinancialCard)


<h1 id="ElementVersionIdentifier">ElementVersionIdentifier</h1>

Type: rdf:Property

Comments: The identifier of the version of a specific element within the referenced standard, such as the version of a data element.

Domains: 

[edi3:Standard](#Standard)


<h1 id="ApproverSignatoryDocumentAuthentication">ApproverSignatoryDocumentAuthentication</h1>

Type: rdf:Property

Comments: The approver signature that authenticates this exchanged document.

Domains: 

[edi3:Document](#Document)


<h1 id="SpecificCertifiedAccreditation">SpecificCertifiedAccreditation</h1>

Type: rdf:Property

Comments: A certified accreditation specific to this transport person.

Domains: 

[edi3:Person](#Person)


<h1 id="ProviderReferencedParty">ProviderReferencedParty</h1>

Type: rdf:Property

Comments: The referenced party providing this document authentication.

Domains: 

[edi3:Authentication](#Authentication)


<h1 id="QuotationProposalReferencedDocument">QuotationProposalReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>The quotation proposal document referenced in this line trade agreement.<br/>The quotation proposal document referenced in this header trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="AmendmentReasonCode">AmendmentReasonCode</h1>

Type: rdf:Property

Comments: A code specifying a reason for an amendment to this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="UnloadingBaseportLogisticsLocation">UnloadingBaseportLogisticsLocation</h1>

Type: rdf:Property

Comments: The baseport location at which this supply chain consignment is to be unloaded from a means of transport according to the transport contract.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="ConsigneeReceiptLogisticsLocation">ConsigneeReceiptLogisticsLocation</h1>

Type: rdf:Property

Comments: The location at which this supply chain consignment will be or has been received by the consignee.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="AttachedAssetIdentificationIdentifier">AttachedAssetIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The identifier for the asset, such as a container, to which this monitoring IOT device is attached.

Domains: 

[edi3:IOTDevice](#IOTDevice)


<h1 id="SpecifiedCrossBorderCustomsProcedure">SpecifiedCrossBorderCustomsProcedure</h1>

Type: rdf:Property

Comments: A customs procedure specified for this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="EstimatedOccurrenceDateTime">EstimatedOccurrenceDateTime</h1>

Type: rdf:Property

Comments: The estimated date, time, date time, or other date time value of the occurrence of this transport event.

Domains: 

[edi3:Event](#Event)


<h1 id="InternalAccessText">InternalAccessText</h1>

Type: rdf:Property

Comments: Access information, expressed as text, for the internal access telecommunication number, such as the United States Defense Network Service number.

Domains: 

[edi3:Communication](#Communication)


<h1 id="ConditionLogisticsStatusCode">ConditionLogisticsStatusCode</h1>

Type: rdf:Property

Comments: The code specifying this logistics status condition [UNECE Recommendation 24].

Domains: 

[edi3:Status](#Status)


<h1 id="DelayOccurrenceSpecifiedPeriod">DelayOccurrenceSpecifiedPeriod</h1>

Type: rdf:Property

Comments: A specified period of time during which this transport event is delayed.

Domains: 

[edi3:Event](#Event)


<h1 id="ReportingSensorCommunicationPairing">ReportingSensorCommunicationPairing</h1>

Type: rdf:Property

Comments: A sensor communication pairing reported for this monitoring IOT device.

Domains: 

[edi3:IOTDevice](#IOTDevice)


<h1 id="ActualPickUpSupplyChainEvent">ActualPickUpSupplyChainEvent</h1>

Type: rdf:Property

Comments: <br/>The actual pick-up event, at header level, for this trade delivery.<br/>The actual pick-up event, at line level, for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="RegistrationIdentificationIdentifier">RegistrationIdentificationIdentifier</h1>

Type: rdf:Property

Comments: A unique registration identifier, such as a vehicle licence plate identification, for this trade product instance.

Domains: 

[edi3:ProductInstance](#ProductInstance)


<h1 id="TypeDimensionTypeCode">TypeDimensionTypeCode</h1>

Type: rdf:Property

Comments: The code specifying the type of spatial dimension, such as thickness, area, or volume.

Domains: 

[edi3:Dimension](#Dimension)


<h1 id="ExemptionReasonText">ExemptionReasonText</h1>

Type: rdf:Property

Comments: <br/>A reason, expressed as text, for exemption from this registered tax.<br/>The reason, expressed as text, for exemption from this trade related tax, levy or duty.<br/>

Domains: 

[edi3:Tax](#Tax)


<h1 id="LoadingInspectionTradeParty">LoadingInspectionTradeParty</h1>

Type: rdf:Property

Comments: The loading inspection party for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="MaximumStackabilityApplicableQuantity">MaximumStackabilityApplicableQuantity</h1>

Type: rdf:Property

Comments: The maximum number of units which can be stacked on top of each other according to these handling instructions.

Domains: 

[edi3:Instructions](#Instructions)


<h1 id="ActualReportedCalibratedMeasurement">ActualReportedCalibratedMeasurement</h1>

Type: rdf:Property

Comments: An actual calibrated measurement reported for this monitoring sensor.

Domains: 

[edi3:Sensor](#Sensor)


<h1 id="ApplicableSupplyChainPackaging">ApplicableSupplyChainPackaging</h1>

Type: rdf:Property

Comments: Packaging applicable for use with this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="SupportCentreTradeParty">SupportCentreTradeParty</h1>

Type: rdf:Property

Comments: The support centre party for this line trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="PreviousDeliveryTransportEvent">PreviousDeliveryTransportEvent</h1>

Type: rdf:Property

Comments: A previous delivery event for this transport waste material.

Domains: 

[edi3:Material](#Material)


<h1 id="CreditorReferenceTypeCode">CreditorReferenceTypeCode</h1>

Type: rdf:Property

Comments: A code specifying the creditor reference type for this header trade settlement.

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="ShipperDeclarationInformationText">ShipperDeclarationInformationText</h1>

Type: rdf:Property

Comments: Shipper declaration information, expressed as text, for these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="RoyaltyLicenseFeeIndicator">RoyaltyLicenseFeeIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not there is a royalty or licence fee related to the goods for this cross-border customs valuation.

Domains: 

[edi3:CustomsValuation](#CustomsValuation)


<h1 id="InformationAmount">InformationAmount</h1>

Type: rdf:Property

Comments: <br/>A monetary value of an amount being reported for information in this trade settlement monetary summation.<br/>A monetary value of an amount being reported for information for this trade related tax, levy or duty.<br/>A monetary value of an amount being reported for information in this trade settlement header monetary summation.<br/>

Domains: 

[edi3:Tax](#Tax)
[edi3:MonetarySummation](#MonetarySummation)


<h1 id="ActivityAuthorizedTradeParty">ActivityAuthorizedTradeParty</h1>

Type: rdf:Property

Comments: A party that is authorized to perform an activity in this trade country sub-division.

Domains: 

[edi3:CountrySubDivision](#CountrySubDivision)


<h1 id="IncludedNote">IncludedNote</h1>

Type: rdf:Property

Comments: <br/>A note included in this referenced document.<br/>A note included in this exchanged document.<br/>A note included in this document line.<br/>

Domains: 

[edi3:Document](#Document)


<h1 id="SellerReferenceText">SellerReferenceText</h1>

Type: rdf:Property

Comments: <br/>A seller reference, expressed as text, for this header trade agreement.<br/>A seller reference, expressed as text, for this line trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="SpecifiedTradeDeliveryTerms">SpecifiedTradeDeliveryTerms</h1>

Type: rdf:Property

Comments: Delivery terms specified for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="PreviousAssociatedSpecifiedGeographicalFeature">PreviousAssociatedSpecifiedGeographicalFeature</h1>

Type: rdf:Property

Comments: <br/>A geographical feature previously associated with this logistics location.<br/>A geographical feature previously associated with this transport event.<br/>

Domains: 

[edi3:Event](#Event)
[edi3:Location](#Location)


<h1 id="ISSCIssuingAuthorityTradeParty">ISSCIssuingAuthorityTradeParty</h1>

Type: rdf:Property

Comments: The trade party authorized to issue the International Ship Security Certificate (ISSC) for this logistics means of transport.

Domains: 

[edi3:TransportMeans](#TransportMeans)


<h1 id="QuotationReferencedDocument">QuotationReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>The quotation document referenced in this line trade agreement.<br/>The quotation document referenced in this header trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="AuthorizedLegalRegistration">AuthorizedLegalRegistration</h1>

Type: rdf:Property

Comments: A legal registration authorized for this legally set up organization.

Domains: 

[edi3:Organization](#Organization)


<h1 id="ManoeuvringSpeedMeasure">ManoeuvringSpeedMeasure</h1>

Type: rdf:Property

Comments: The manoeuvring speed measured for this logistics means of transport.

Domains: 

[edi3:TransportMeans](#TransportMeans)


<h1 id="RemainingBatteryChargePercent">RemainingBatteryChargePercent</h1>

Type: rdf:Property

Comments: <br/>The percentage of the remaining battery charge of this monitoring IOT device.<br/>The percentage of the remaining battery charge of this monitoring sensor.<br/>

Domains: 

[edi3:Sensor](#Sensor)
[edi3:IOTDevice](#IOTDevice)


<h1 id="RecordedDate">RecordedDate</h1>

Type: rdf:Property

Comments: The date that this government registration was recorded.

Domains: 

[edi3:Registration](#Registration)


<h1 id="ColourDescriptionText">ColourDescriptionText</h1>

Type: rdf:Property

Comments: A textual description of the colour of this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="CancellationDateTime">CancellationDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time, or other date time value of a cancellation of the exchanged document.

Domains: 

[edi3:Document](#Document)


<h1 id="FrequencyEffectiveSpecifiedPeriod">FrequencyEffectiveSpecifiedPeriod</h1>

Type: rdf:Property

Comments: A specified period of time for which a frequency is effective for this transport route.

Domains: 

[edi3:Route](#Route)


<h1 id="SummaryDescriptionText">SummaryDescriptionText</h1>

Type: rdf:Property

Comments: A textual summary description of this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="HandlingText">HandlingText</h1>

Type: rdf:Property

Comments: Delivery handling instructions expressed as text.

Domains: 

[edi3:Instructions](#Instructions)


<h1 id="TotalDiscountBasisAmount">TotalDiscountBasisAmount</h1>

Type: rdf:Property

Comments: A monetary value of a total discount basis reported in this trade settlement header monetary summation.

Domains: 

[edi3:MonetarySummation](#MonetarySummation)


<h1 id="RegulatoryAuthorityNameText">RegulatoryAuthorityNameText</h1>

Type: rdf:Property

Comments: The name, expressed as text, for the regulatory authority for these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="NilCarriageValueIndicator">NilCarriageValueIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not this supply chain consignment has a nil value for carriage.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="TaxPointDate">TaxPointDate</h1>

Type: rdf:Property

Comments: <br/>The date of the tax point when taxes, such as VAT, are to be applied.<br/>The date of the tax point when this trade related tax, levy or duty becomes applicable.<br/>

Domains: 

[edi3:Tax](#Tax)


<h1 id="DraughtLevelMeasure">DraughtLevelMeasure</h1>

Type: rdf:Property

Comments: The measure of the draught level of this logistics means of transport.

Domains: 

[edi3:TransportMeans](#TransportMeans)


<h1 id="SailingAdviceNotificationInformationText">SailingAdviceNotificationInformationText</h1>

Type: rdf:Property

Comments: Sailing advice notification information, expressed as text, for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="QuantificationTypeCode">QuantificationTypeCode</h1>

Type: rdf:Property

Comments: The code specifying a quantification type for this calibrated measurement, such as measured, calculated, or estimated.

Domains: 

[edi3:Measurement](#Measurement)


<h1 id="AccompaniedIndicator">AccompaniedIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not this piece of logistics transport equipment is accompanied, such as by a transport means.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="ValueIndicator">ValueIndicator</h1>

Type: rdf:Property

Comments: The value for this product characteristic expressed as an indicator.

Domains: 

[edi3:Characteristic](#Characteristic)


<h1 id="DespatchedQuantity">DespatchedQuantity</h1>

Type: rdf:Property

Comments: <br/>The quantity, at header level, despatched in this trade delivery.<br/>The quantity, at line level, despatched for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="OperationalStatusCode">OperationalStatusCode</h1>

Type: rdf:Property

Comments: The code specifying the operational status, such as broken, stolen, unpaired, inactive of this monitoring IOT device.

Domains: 

[edi3:IOTDevice](#IOTDevice)


<h1 id="ScheduledReportedCalibratedMeasurement">ScheduledReportedCalibratedMeasurement</h1>

Type: rdf:Property

Comments: A scheduled calibrated measurement reported for this monitoring sensor.

Domains: 

[edi3:Sensor](#Sensor)


<h1 id="PilotageExemptionIdentifier">PilotageExemptionIdentifier</h1>

Type: rdf:Property

Comments: The identifier of a pilotage exemption for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="OrderSupplyChainSchedule">OrderSupplyChainSchedule</h1>

Type: rdf:Property

Comments: A supply chain order schedule, at line level, for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="TolerancePercent">TolerancePercent</h1>

Type: rdf:Property

Comments: The percent of tolerance of this calibrated measurement.

Domains: 

[edi3:Measurement](#Measurement)


<h1 id="UpperPartOrangeHazardPlacardIdentifier">UpperPartOrangeHazardPlacardIdentifier</h1>

Type: rdf:Property

Comments: The unique upper part of the orange hazard placard identifier for these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="MinimumStorageHumidityApplicableMeasure">MinimumStorageHumidityApplicableMeasure</h1>

Type: rdf:Property

Comments: The measure of the minimum storage humidity applicable to these handling instructions.

Domains: 

[edi3:Instructions](#Instructions)


<h1 id="IncludedDocumentClause">IncludedDocumentClause</h1>

Type: rdf:Property

Comments: A document clause included in this document authentication.

Domains: 

[edi3:Authentication](#Authentication)


<h1 id="ReasonTypeCode">ReasonTypeCode</h1>

Type: rdf:Property

Comments: The code specifying the reason type for this referenced transport event.

Domains: 

[edi3:Event](#Event)


<h1 id="ActualQuantityPercent">ActualQuantityPercent</h1>

Type: rdf:Property

Comments: The percentage of a total quantity that the actual quantity of this work item quantity analysis represents.

Domains: 

[edi3:QuantityAnalysis](#QuantityAnalysis)


<h1 id="ISPSRelatedReferencedDocument">ISPSRelatedReferencedDocument</h1>

Type: rdf:Property

Comments: The International Ship and Port facility Security code (ISPS) document related to this transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="FissileExceptionIndicator">FissileExceptionIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not this radioactive material is a fissile exception.

Domains: 

[edi3:Material](#Material)


<h1 id="MarinePollutantIndicator">MarinePollutantIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not these transported dangerous goods have a marine pollutant content.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="AmountTypeAccountingAmountTypeCode">AmountTypeAccountingAmountTypeCode</h1>

Type: rdf:Property

Comments: The code specifying the amount type for this trade accounting account.

Domains: 

[edi3:AccountingAccount](#AccountingAccount)


<h1 id="AvailabilityDueDateTime">AvailabilityDueDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time or other date time value when this supply chain consignment is due to be available.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="AssociatedInvoiceDiscountAmount">AssociatedInvoiceDiscountAmount</h1>

Type: rdf:Property

Comments: A monetary value of the discount on an invoice associated with this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="OrderQuantity">OrderQuantity</h1>

Type: rdf:Property

Comments: The quantity, at line level, ordered for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="ServiceCode">ServiceCode</h1>

Type: rdf:Property

Comments: The code specifying the service of this logistics transport movement, such as regular, milk run or spot service.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="AgreedQuantity">AgreedQuantity</h1>

Type: rdf:Property

Comments: <br/>The quantity, at header level, agreed for this trade delivery.<br/>The quantity, at line level, agreed for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="CoordinateSpecifiedDirectPosition">CoordinateSpecifiedDirectPosition</h1>

Type: rdf:Property

Comments: The specified direct position of a coordinate for this linear ring.

Domains: 

[edi3:LinearRing](#LinearRing)


<h1 id="DeductionAmount">DeductionAmount</h1>

Type: rdf:Property

Comments: A monetary value of the deduction from this trade related tax, levy or duty.

Domains: 

[edi3:Tax](#Tax)


<h1 id="TotalItemQuantity">TotalItemQuantity</h1>

Type: rdf:Property

Comments: The total number of items in this specified range.

Domains: 

[edi3:Range](#Range)


<h1 id="RevisionDateTime">RevisionDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time or other date time value for the revision of this exchanged document.

Domains: 

[edi3:Document](#Document)


<h1 id="IdentificationCode">IdentificationCode</h1>

Type: rdf:Property

Comments: A code specifying an identified fault.

Domains: 

[edi3:Fault](#Fault)


<h1 id="ClosingDateTime">ClosingDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time, or other date time value by which cargo should be loaded onto the means of transport for the departure of this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="DeferredPaymentMethodIndicator">DeferredPaymentMethodIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not the deferred payment method is applicable to this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="ProductAvailabilityCode">ProductAvailabilityCode</h1>

Type: rdf:Property

Comments: The code specifying the product availability according to this line trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="GrandTotalAmount">GrandTotalAmount</h1>

Type: rdf:Property

Comments: <br/>A monetary value of the grand total of this trade settlement header monetary summation, to include addition and subtraction of individual summation amounts.<br/>A monetary value of the grand total of the basis plus tax for this trade tax.<br/>A monetary value of a grand total reported in this trade settlement payment monetary summation.<br/>A monetary value of the grand total of this trade settlement line monetary summation, to include addition and subtraction of individual summation amounts.<br/>

Domains: 

[edi3:Tax](#Tax)
[edi3:MonetarySummation](#MonetarySummation)


<h1 id="HazardClassVersionIdentifier">HazardClassVersionIdentifier</h1>

Type: rdf:Property

Comments: The unique identifier of the version of a hazard class for these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="LocationProviderTradeParty">LocationProviderTradeParty</h1>

Type: rdf:Property

Comments: The trade party providing the location for this document authentication.

Domains: 

[edi3:Authentication](#Authentication)


<h1 id="UUIDLineIdentifier">UUIDLineIdentifier</h1>

Type: rdf:Property

Comments: The universally unique identifier (UUID) of this document line.

Domains: 

[edi3:Document](#Document)


<h1 id="DepartureRelatedDateTime">DepartureRelatedDateTime</h1>

Type: rdf:Property

Comments: A departure date, time, date time, or other date time value related to this transport event.

Domains: 

[edi3:Event](#Event)


<h1 id="IncludedReferencedSupplyChainConsignmentItem">IncludedReferencedSupplyChainConsignmentItem</h1>

Type: rdf:Property

Comments: A referenced consignment item included in this referenced supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="PhysicalLogisticsShippingMarks">PhysicalLogisticsShippingMarks</h1>

Type: rdf:Property

Comments: <br/>Physical logistics shipping marks and barcode information for this referenced supply chain consignment item.<br/>Physical logistics shipping marks and barcoding information related to this supply chain consignment.<br/>Physical shipping marks and barcode information for this logistics package.<br/>Physical logistics shipping marks in this referenced logistics package.<br/>Physical logistics shipping marks and barcode information for this supply chain consignment item.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:Consignment](#Consignment)
[edi3:Package](#Package)


<h1 id="DueDateDateTime">DueDateDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time, or other date time value for a due date specified by these trade payment terms.

Domains: 

[edi3:PaymentTerms](#PaymentTerms)


<h1 id="NominalGrossWeightMeasure">NominalGrossWeightMeasure</h1>

Type: rdf:Property

Comments: The measure of the nominal gross weight (mass) of this logistics package and its contents.

Domains: 

[edi3:Package](#Package)


<h1 id="DiscountIndicator">DiscountIndicator</h1>

Type: rdf:Property

Comments: <br/>The indication of whether or not a discount applies to the item in this line trade settlement.<br/>The indication of whether or not this header trade settlement includes a discount amount.<br/>

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="AbsolutePresenceVolumeMeasure">AbsolutePresenceVolumeMeasure</h1>

Type: rdf:Property

Comments: The volume measure of the absolute presence of this material goods characteristic.

Domains: 

[edi3:GoodsCharacteristic](#GoodsCharacteristic)


<h1 id="ExaminationTransportEvent">ExaminationTransportEvent</h1>

Type: rdf:Property

Comments: <br/>An examination event for this supply chain consignment.<br/>An examination event for this cross-border regulatory procedure.<br/>An examination event for this supply chain consignment item.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:RegulatoryProcedure](#RegulatoryProcedure)
[edi3:Consignment](#Consignment)


<h1 id="RemarkNote">RemarkNote</h1>

Type: rdf:Property

Comments: A note containing a remark for this supply chain inventory.

Domains: 

[edi3:Inventory](#Inventory)


<h1 id="MarkingText">MarkingText</h1>

Type: rdf:Property

Comments: <br/>Marking, expressed as text, for these transported dangerous goods.<br/>Marking, expressed as text, for these logistics shipping marks.<br/>

Domains: 

[edi3:ShippingMarks](#ShippingMarks)
[edi3:DangerousGoods](#DangerousGoods)


<h1 id="IncludedSpecifiedGeographicalMultiPoint">IncludedSpecifiedGeographicalMultiPoint</h1>

Type: rdf:Property

Comments: The geographical multi-point included in this geographical feature.

Domains: 

[edi3:GeographicalFeature](#GeographicalFeature)


<h1 id="CarrierAssignedIdentifier">CarrierAssignedIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique identifier assigned by the carrier to this supply chain consignment, such as a booking reference number when cargo space is reserved prior to loading.<br/>The unique identifier assigned by the carrier to this referenced supply chain consignment, such as a booking reference number when cargo space is reserved prior to loading.<br/>

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="SpecialProvisionIdentifier">SpecialProvisionIdentifier</h1>

Type: rdf:Property

Comments: The unique identifier of the special provision for these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="SpecifiedProductCertificate">SpecifiedProductCertificate</h1>

Type: rdf:Property

Comments: A product certificate specified for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="BankAssignedIdentificationIdentifier">BankAssignedIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The bank assigned identifier for this financial identity.

Domains: 

[edi3:Identity](#Identity)


<h1 id="PairedIndicator">PairedIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not the entity is paired in this communication pairing.

Domains: 

[edi3:Pairing](#Pairing)


<h1 id="TransshipmentPermissionIndicator">TransshipmentPermissionIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not transshipment is permitted for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="DefaultCurrencyCurrencyCode">DefaultCurrencyCurrencyCode</h1>

Type: rdf:Property

Comments: The code specifying the default currency for this valuation breakdown statement.

Domains: 

[edi3:BreakdownStatement](#BreakdownStatement)


<h1 id="AssociatedSpecifiedPeriod">AssociatedSpecifiedPeriod</h1>

Type: rdf:Property

Comments: A period of time associated with this document clause.

Domains: 

[edi3:Clause](#Clause)


<h1 id="AssociatedInvoiceAmount">AssociatedInvoiceAmount</h1>

Type: rdf:Property

Comments: A monetary value of an invoice associated with this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="PostalTradeAddress">PostalTradeAddress</h1>

Type: rdf:Property

Comments: <br/>A postal address for this location party.<br/>The postal address for this trade party.<br/>The postal trade address information for this logistics related location.<br/>A postal address for this legally set up organization.<br/>

Domains: 

[edi3:Organization](#Organization)
[edi3:Party](#Party)
[edi3:Location](#Location)


<h1 id="AlienRegistrationIdentificationIdentifier">AlienRegistrationIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The alien registration identifier for this person.

Domains: 

[edi3:Identity](#Identity)


<h1 id="CharacterSetCode">CharacterSetCode</h1>

Type: rdf:Property

Comments: The code specifying the character set for this specified binary file.

Domains: 

[edi3:BinaryFile](#BinaryFile)


<h1 id="TypePackagingMarkingCode">TypePackagingMarkingCode</h1>

Type: rdf:Property

Comments: A code specifying a type of packaging marking.

Domains: 

[edi3:Marking](#Marking)


<h1 id="LineThreeText">LineThreeText</h1>

Type: rdf:Property

Comments: <br/>The third free form line, expressed as text, of this financial institution address.<br/>The third free form line, expressed as text, of this trade address.<br/>

Domains: 

[edi3:Address](#Address)


<h1 id="CoordinateReferenceSystemIdentifier">CoordinateReferenceSystemIdentifier</h1>

Type: rdf:Property

Comments: The identifier of the coordinate reference system for this geographical feature.

Domains: 

[edi3:GeographicalFeature](#GeographicalFeature)


<h1 id="ShipmentScheduleReferencedDocument">ShipmentScheduleReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>The shipment schedule document, referenced at header level, for this trade delivery.<br/>The shipment schedule document referenced, at line level, for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="TransportPaymentMethodCode">TransportPaymentMethodCode</h1>

Type: rdf:Property

Comments: The code specifying the transport payment method for this logistics service charge.

Domains: 

[edi3:ServiceCharge](#ServiceCharge)


<h1 id="BarcodeTypeCode">BarcodeTypeCode</h1>

Type: rdf:Property

Comments: A code specifying a type of barcode for this packaging marking.

Domains: 

[edi3:Marking](#Marking)


<h1 id="BuildingNumberText">BuildingNumberText</h1>

Type: rdf:Property

Comments: <br/>The building number, expressed as text, in this trade address.<br/>The number, expressed as text, of the building on a street for this financial institution address.<br/>

Domains: 

[edi3:Address](#Address)


<h1 id="MaximumStackabilityWeightMeasure">MaximumStackabilityWeightMeasure</h1>

Type: rdf:Property

Comments: The measure of the maximum stackability weight of this supply chain packaging.

Domains: 

[edi3:Packaging](#Packaging)


<h1 id="LineTwoText">LineTwoText</h1>

Type: rdf:Property

Comments: <br/>The second free form line, expressed as text, of this trade address.<br/>The second free form line, expressed as text, of this financial institution address.<br/>

Domains: 

[edi3:Address](#Address)


<h1 id="QuantityVariationReasonText">QuantityVariationReasonText</h1>

Type: rdf:Property

Comments: A reason, expressed as text, for a quantity variation, at line level, for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="IndustryAssignedIdentificationIdentifier">IndustryAssignedIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>A unique industry assigned identifier for this referenced product.<br/>A unique industry assigned identifier for this product.<br/>

Domains: 

[edi3:Product](#Product)


<h1 id="TransitCustomsOfficeSpecifiedLogisticsLocation">TransitCustomsOfficeSpecifiedLogisticsLocation</h1>

Type: rdf:Property

Comments: A location of a specified customs office which is responsible for transit formalities en route for the goods which are subject to this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="SaleRestrictionIndicator">SaleRestrictionIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not there is any restriction imposed on the sale of the goods for this cross-border customs valuation.

Domains: 

[edi3:CustomsValuation](#CustomsValuation)


<h1 id="AssociatedInvoiceDiscountPercent">AssociatedInvoiceDiscountPercent</h1>

Type: rdf:Property

Comments: A percent that is a discount on an invoice amount associated with this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="SubmissionLogisticsLocation">SubmissionLogisticsLocation</h1>

Type: rdf:Property

Comments: The submission location for this exchanged declaration.

Domains: 

[edi3:Declaration](#Declaration)


<h1 id="MSDSReferenceReferencedDocument">MSDSReferenceReferencedDocument</h1>

Type: rdf:Property

Comments: A Material Safety Data Sheet (MSDS) document referenced for this product.

Domains: 

[edi3:Product](#Product)


<h1 id="OffsetVectorNumeric">OffsetVectorNumeric</h1>

Type: rdf:Property

Comments: The offset vector, expressed as a number, which indicates the offset of cells along each axis for this geographical grid.

Domains: 

[edi3:GeographicalGrid](#GeographicalGrid)


<h1 id="ArrivalReportedTransportEvent">ArrivalReportedTransportEvent</h1>

Type: rdf:Property

Comments: A transport arrival event reported for this logistics status.

Domains: 

[edi3:Status](#Status)


<h1 id="SpecifiedContactPerson">SpecifiedContactPerson</h1>

Type: rdf:Property

Comments: <br/>A contact person specified for this trade party.<br/>The contact person specified for this trade contact.<br/>

Domains: 

[edi3:Party](#Party)
[edi3:Contact](#Contact)


<h1 id="ScientificNameText">ScientificNameText</h1>

Type: rdf:Property

Comments: <br/>The scientific name, expressed as text, for this distinct chemical.<br/>A scientific name, expressed as text, for this trade product.<br/>

Domains: 

[edi3:Chemical](#Chemical)
[edi3:Product](#Product)


<h1 id="ApplicableTradeSettlementFinancialCard">ApplicableTradeSettlementFinancialCard</h1>

Type: rdf:Property

Comments: A financial card applicable to this trade settlement payment means.

Domains: 

[edi3:PaymentMeans](#PaymentMeans)


<h1 id="RemoteMonitoringSensor">RemoteMonitoringSensor</h1>

Type: rdf:Property

Comments: A remote sensor of this monitoring IOT device.

Domains: 

[edi3:IOTDevice](#IOTDevice)


<h1 id="ExportTradeGeopoliticalRegion">ExportTradeGeopoliticalRegion</h1>

Type: rdf:Property

Comments: <br/>The geopolitical region of export for this supply chain consignment item.<br/>The geopolitical region of export for this supply chain consignment.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:Consignment](#Consignment)


<h1 id="DeconsolidatorTradeParty">DeconsolidatorTradeParty</h1>

Type: rdf:Property

Comments: The party responsible for the deconsolidation of this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="ReasonAdjustmentReasonCode">ReasonAdjustmentReasonCode</h1>

Type: rdf:Property

Comments: The code specifying a reason for this delivery adjustment.

Domains: 

[edi3:Adjustment](#Adjustment)


<h1 id="PreviousProcedureTypeCode">PreviousProcedureTypeCode</h1>

Type: rdf:Property

Comments: A code specifying a type of previous procedure for this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="CalculatedRate">CalculatedRate</h1>

Type: rdf:Property

Comments: <br/>The rate used to calculate the applied tax.<br/>The rate used to calculate the amount of this trade related tax, levy or duty.<br/>

Domains: 

[edi3:Tax](#Tax)


<h1 id="TravelVisaReferencedDocument">TravelVisaReferencedDocument</h1>

Type: rdf:Property

Comments: A referenced travel visa document for this transport person.

Domains: 

[edi3:Person](#Person)


<h1 id="QuoteReferencedTradeWorkflowObject">QuoteReferencedTradeWorkflowObject</h1>

Type: rdf:Property

Comments: The quote trade workflow object referenced in this header trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="SubordinateIdentificationIdentifier">SubordinateIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>A subordinate identifier, at line level, for this trade delivery.<br/>A subordinate identifier, at header level, for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="ApplicableMaterialGoodsCharacteristic">ApplicableMaterialGoodsCharacteristic</h1>

Type: rdf:Property

Comments: <br/>Material goods characteristic applicable to this supply chain packaging.<br/>A material goods characteristic applicable to this trade product.<br/>A distinguishing material feature applicable to this trade product instance.<br/>

Domains: 

[edi3:Packaging](#Packaging)
[edi3:Product](#Product)
[edi3:ProductInstance](#ProductInstance)


<h1 id="PriceListIdentificationIdentifier">PriceListIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The identifier of a price list for this valuation breakdown statement.

Domains: 

[edi3:BreakdownStatement](#BreakdownStatement)


<h1 id="ContentAmount">ContentAmount</h1>

Type: rdf:Property

Comments: Content, expressed as a monetary amount, for this packaging marking.

Domains: 

[edi3:Marking](#Marking)


<h1 id="TransshipmentIntermediateTransportEvent">TransshipmentIntermediateTransportEvent</h1>

Type: rdf:Property

Comments: A transshipment intermediate event during this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="GrandTotalSpecifiedFinancialAdjustment">GrandTotalSpecifiedFinancialAdjustment</h1>

Type: rdf:Property

Comments: The financial adjustment of the grand total specified for this trade settlement header monetary summation.

Domains: 

[edi3:MonetarySummation](#MonetarySummation)


<h1 id="IssuingTradeParty">IssuingTradeParty</h1>

Type: rdf:Property

Comments: The party issuing this logistics seal.

Domains: 

[edi3:Seal](#Seal)


<h1 id="UnloadingTransportInstructions">UnloadingTransportInstructions</h1>

Type: rdf:Property

Comments: Unloading instructions for this piece of logistics transport equipment.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="DespatchTradeParty">DespatchTradeParty</h1>

Type: rdf:Property

Comments: <br/>The party from whom this supply chain consignment will be or has been despatched.<br/>The party from whom this referenced supply chain consignment will be or has been despatched.<br/>The party from whom this supply chain consignment item will be or has been despatched.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:Consignment](#Consignment)


<h1 id="StayIdentifier">StayIdentifier</h1>

Type: rdf:Property

Comments: The unique identifier of a stay in a port, airport or other place of service for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="LaycanOccurrenceSpecifiedPeriod">LaycanOccurrenceSpecifiedPeriod</h1>

Type: rdf:Property

Comments: The specified period of laycan time during which this transport event occurs.

Domains: 

[edi3:Event](#Event)


<h1 id="AssociatedLogisticsTransportEquipment">AssociatedLogisticsTransportEquipment</h1>

Type: rdf:Property

Comments: A piece of transport equipment associated with this supply chain trade line item.

Domains: 

[edi3:TradeLineItem](#TradeLineItem)


<h1 id="ExportIndicator">ExportIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not this trade product is for export.

Domains: 

[edi3:Product](#Product)


<h1 id="LoadedPackageQuantity">LoadedPackageQuantity</h1>

Type: rdf:Property

Comments: <br/>The number of packages loaded into or onto this piece of referenced logistics transport equipment.<br/>The number of packages loaded into or onto this piece of logistics transport equipment.<br/>

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="SenderTradeParty">SenderTradeParty</h1>

Type: rdf:Property

Comments: <br/>The party that sends this exchanged document.<br/>The trade related party that sends this referenced document.<br/>

Domains: 

[edi3:Document](#Document)


<h1 id="CustomerFacingTotalUnitQuantity">CustomerFacingTotalUnitQuantity</h1>

Type: rdf:Property

Comments: The total number of units of this supply chain packaging facing the customer, such as would be seen when this packaging is placed on a retail shelf.

Domains: 

[edi3:Packaging](#Packaging)


<h1 id="UltimateCustomerAssignedExtensionIdentificationIdentifier">UltimateCustomerAssignedExtensionIdentificationIdentifier</h1>

Type: rdf:Property

Comments: An ultimate customer assigned extension identifier for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="StatisticalClassificationCargoCommodityCategoryCode">StatisticalClassificationCargoCommodityCategoryCode</h1>

Type: rdf:Property

Comments: The code specifying a statistical classification for this transport cargo.

Domains: 

[edi3:Cargo](#Cargo)


<h1 id="RequestedTransportRoute">RequestedTransportRoute</h1>

Type: rdf:Property

Comments: A requested route for this piece of logistics transport equipment.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="ConditionMeasure">ConditionMeasure</h1>

Type: rdf:Property

Comments: A measure of a condition for this measurement.

Domains: 

[edi3:Measurement](#Measurement)


<h1 id="AbbreviatedNameText">AbbreviatedNameText</h1>

Type: rdf:Property

Comments: The abbreviated name, expressed as text, of this academic qualification.

Domains: 

[edi3:Qualification](#Qualification)


<h1 id="CarrierAcceptanceDateTime">CarrierAcceptanceDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time or other date time value when this supply chain consignment will be, or has been, accepted by the carrier.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="SubjectText">SubjectText</h1>

Type: rdf:Property

Comments: The subject, expressed as text, of this note.

Domains: 

[edi3:Note](#Note)


<h1 id="IncludedSpecifiedGeographicalLine">IncludedSpecifiedGeographicalLine</h1>

Type: rdf:Property

Comments: The geographical line included in this geographical feature.

Domains: 

[edi3:GeographicalFeature](#GeographicalFeature)


<h1 id="SeriesStartIdentificationIdentifier">SeriesStartIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique start identifier of a series of packages within this logistics package.<br/>The identifier of the start of a series of packages within this referenced logistics package.<br/>

Domains: 

[edi3:Package](#Package)


<h1 id="MaximumStockLevelMeasure">MaximumStockLevelMeasure</h1>

Type: rdf:Property

Comments: The measure of the maximum stock level for this supply chain inventory.

Domains: 

[edi3:Inventory](#Inventory)


<h1 id="AttainedAcademicQualification">AttainedAcademicQualification</h1>

Type: rdf:Property

Comments: <br/>An academic qualification attained by this authoritative signatory person.<br/>An academic qualification attained by this transport person.<br/>

Domains: 

[edi3:Person](#Person)


<h1 id="ResponseReasonCode">ResponseReasonCode</h1>

Type: rdf:Property

Comments: A code specifying a response reason for this exchanged document.

Domains: 

[edi3:Document](#Document)


<h1 id="ImpactCode">ImpactCode</h1>

Type: rdf:Property

Comments: <br/>The code specifying the impact for this header trade agreement.<br/>The code specifying the impact for this line trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="SpecifiedPackagingMarking">SpecifiedPackagingMarking</h1>

Type: rdf:Property

Comments: A marking specified for this supply chain packaging, such as an inscription, stamp or label to indicate date, ownership, quality, manufacture or origin.

Domains: 

[edi3:Packaging](#Packaging)


<h1 id="BuyerSellerRelationshipPriceInfluenceIndicator">BuyerSellerRelationshipPriceInfluenceIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not the buyer seller relationship influences the price of the goods for this cross-border customs valuation.

Domains: 

[edi3:CustomsValuation](#CustomsValuation)


<h1 id="SystemNameText">SystemNameText</h1>

Type: rdf:Property

Comments: A name, expressed as text, of the classification system for this product classification.

Domains: 

[edi3:Classification](#Classification)


<h1 id="TypeAllowanceChargeIdentificationCode">TypeAllowanceChargeIdentificationCode</h1>

Type: rdf:Property

Comments: The code specifying the type of this trade allowance charge.

Domains: 

[edi3:AllowanceCharge](#AllowanceCharge)


<h1 id="LevelPackagingLevelCode">LevelPackagingLevelCode</h1>

Type: rdf:Property

Comments: <br/>The code specifying the level of this logistics package.<br/>The code specifying the level of this referenced logistics package.<br/>

Domains: 

[edi3:Package](#Package)


<h1 id="DeclaredValueForStatisticsAmount">DeclaredValueForStatisticsAmount</h1>

Type: rdf:Property

Comments: The monetary value of this supply chain consignment item as declared for statistical purposes.

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)


<h1 id="LengthLinearUnitMeasure">LengthLinearUnitMeasure</h1>

Type: rdf:Property

Comments: The measure of the length of this logistics means of transport.

Domains: 

[edi3:TransportMeans](#TransportMeans)


<h1 id="ToleranceQuantity">ToleranceQuantity</h1>

Type: rdf:Property

Comments: The quantity of tolerance from the planned quantity in this supply chain supply plan.

Domains: 

[edi3:SupplyPlan](#SupplyPlan)


<h1 id="DeclaredValueForCarriageAmount">DeclaredValueForCarriageAmount</h1>

Type: rdf:Property

Comments: <br/>The monetary value of this supply chain consignment as declared by the shipper or his agent for the purpose of varying the carrier's level of liability from that provided in the contract of carriage, in case of loss or damage to goods or delayed delivery.<br/>The monetary value of this supply chain consignment item as declared by the shipper or his agent for the purpose of varying the carrier's level of liability from that provided in the contract of carriage, in case of loss or damage to goods or delayed delivery.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:Consignment](#Consignment)


<h1 id="PriorityCode">PriorityCode</h1>

Type: rdf:Property

Comments: <br/>The code specifying the priority for this line trade agreement.<br/>The code specifying the priority for this header trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="HierarchicalLevelCode">HierarchicalLevelCode</h1>

Type: rdf:Property

Comments: The code specifying the hierarchical level of this trade country sub-division.

Domains: 

[edi3:CountrySubDivision](#CountrySubDivision)


<h1 id="IncludedWithinSupplyChainConsignmentItem">IncludedWithinSupplyChainConsignmentItem</h1>

Type: rdf:Property

Comments: The consignment item within which this supply chain trade line item is included.

Domains: 

[edi3:TradeLineItem](#TradeLineItem)


<h1 id="RegulationNameText">RegulationNameText</h1>

Type: rdf:Property

Comments: A name, expressed as text, for a regulation of these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="SpecifiedDebtorFinancialAccount">SpecifiedDebtorFinancialAccount</h1>

Type: rdf:Property

Comments: A debtor financial account specified for this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="TransitTradeCountry">TransitTradeCountry</h1>

Type: rdf:Property

Comments: <br/>A transit country for this supply chain consignment.<br/>A transit country for this supply chain consignment item.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:Consignment](#Consignment)


<h1 id="AustralianBSBIdentificationIdentifier">AustralianBSBIdentificationIdentifier</h1>

Type: rdf:Property

Comments: <br/>The unique Australian Bank State Branch (BSB) Code identifier as assigned by the Australian Payments Clearing Association (APCA) for this debtor financial institution.<br/>The unique Australian Bank State Branch (BSB) Code identifier as assigned by the Australian Payments Clearing Association (APCA) for this creditor financial institution.<br/>

Domains: 

[edi3:FinancialInstitution](#FinancialInstitution)


<h1 id="AccountNameText">AccountNameText</h1>

Type: rdf:Property

Comments: <br/>The account name, expressed as text, of this financing financial account.<br/>The account name, expressed as text, of this debtor financial account.<br/>The account name, expressed as text, of this creditor financial account.<br/>

Domains: 

[edi3:FinancialAccount](#FinancialAccount)


<h1 id="BusinessTypeCode">BusinessTypeCode</h1>

Type: rdf:Property

Comments: A code specifying the type of business of this legally set up organization.

Domains: 

[edi3:Organization](#Organization)


<h1 id="SailingAdviceNotifiedTradeParty">SailingAdviceNotifiedTradeParty</h1>

Type: rdf:Property

Comments: A party to be notified of the sailing advice for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="CertifyingTradeParty">CertifyingTradeParty</h1>

Type: rdf:Property

Comments: A certifying party for this transport event.

Domains: 

[edi3:Event](#Event)


<h1 id="InstructionCode">InstructionCode</h1>

Type: rdf:Property

Comments: <br/>A code specifying an instruction for this supply chain packaging.<br/>A code specifying an instruction for these trade payment terms.<br/>

Domains: 

[edi3:Packaging](#Packaging)
[edi3:PaymentTerms](#PaymentTerms)


<h1 id="GoodsStatusCode">GoodsStatusCode</h1>

Type: rdf:Property

Comments: The code specifying the goods status for this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="LiftingInstructionsRelatedReferencedDocument">LiftingInstructionsRelatedReferencedDocument</h1>

Type: rdf:Property

Comments: A referenced lifting instructions document related to this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="WebsiteURIIdentifier">WebsiteURIIdentifier</h1>

Type: rdf:Property

Comments: A website Uniform Resource Identifier (URI) for this specified marketplace.

Domains: 

[edi3:Marketplace](#Marketplace)


<h1 id="SubBrandNameText">SubBrandNameText</h1>

Type: rdf:Property

Comments: The sub-brand name, expressed as text, for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="ApplicableProcessCharacteristic">ApplicableProcessCharacteristic</h1>

Type: rdf:Property

Comments: A process characteristic applicable to this product handling process.

Domains: 

[edi3:Process](#Process)


<h1 id="LimitedQuantityCode">LimitedQuantityCode</h1>

Type: rdf:Property

Comments: A code specifying facilitations for transport of limited quantities of these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="OrderingSpecifiedPeriod">OrderingSpecifiedPeriod</h1>

Type: rdf:Property

Comments: The ordering period specified in this line trade agreement.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="TransportContractReferencedDocument">TransportContractReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>A transport contract document for this supply chain consignment item.<br/>The transport contract document for this referenced supply chain consignment, such as an airwaybill or a seawaybill.<br/>The referenced transport contract document for this supply chain consignment, such as an airwaybill or a seawaybill.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:Consignment](#Consignment)


<h1 id="AdjustedBalanceOutAmount">AdjustedBalanceOutAmount</h1>

Type: rdf:Property

Comments: <br/>A monetary value that is an adjusted amount balanced out for this trade settlement payment monetary summation.<br/>A monetary value that is an adjusted amount balanced out for this trade settlement header monetary summation.<br/>

Domains: 

[edi3:MonetarySummation](#MonetarySummation)


<h1 id="QualityAssuranceIndicator">QualityAssuranceIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not this trade party is quality assured.

Domains: 

[edi3:Party](#Party)


<h1 id="SellerTradeParty">SellerTradeParty</h1>

Type: rdf:Property

Comments: <br/>The seller party for this header trade agreement.<br/>The seller party for this line trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="IndividualTradeProductInstance">IndividualTradeProductInstance</h1>

Type: rdf:Property

Comments: An individual instance of this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="ProprietaryTypeText">ProprietaryTypeText</h1>

Type: rdf:Property

Comments: <br/>A proprietary type, expressed as text, for this referenced document.<br/>The proprietary type, expressed as text, of this creditor financial account, such as the nature or use of the creditor account.<br/>The proprietary type, expressed as text, of this debtor financial account, such as the nature or use of the debtor account.<br/>The proprietary type, expressed as text, of this financing financial account, such as the nature or use.<br/>

Domains: 

[edi3:FinancialAccount](#FinancialAccount)
[edi3:Document](#Document)


<h1 id="CoverageDescriptionText">CoverageDescriptionText</h1>

Type: rdf:Property

Comments: The textual description of the coverage of this transport cargo insurance.

Domains: 

[edi3:CargoInsurance](#CargoInsurance)


<h1 id="DateTypeCode">DateTypeCode</h1>

Type: rdf:Property

Comments: A code specifying a type of date in these supply chain forecast terms.

Domains: 

[edi3:ForecastTerms](#ForecastTerms)


<h1 id="SpecifiedTransportEvent">SpecifiedTransportEvent</h1>

Type: rdf:Property

Comments: A transport event specified for this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="MinimumStockLevelMeasure">MinimumStockLevelMeasure</h1>

Type: rdf:Property

Comments: The measure of the minimum stock level for this supply chain inventory.

Domains: 

[edi3:Inventory](#Inventory)


<h1 id="ServiceRequirementTransportServiceRequirementCode">ServiceRequirementTransportServiceRequirementCode</h1>

Type: rdf:Property

Comments: A code specifying a service requirement for this transport service.

Domains: 

[edi3:Service](#Service)


<h1 id="VerificationNumeric">VerificationNumeric</h1>

Type: rdf:Property

Comments: The unique card verification number for security purposes to help verify the card user is in actual possession of this trade settlement financial card.

Domains: 

[edi3:FinancialCard](#FinancialCard)


<h1 id="ReferencedLogisticsPackage">ReferencedLogisticsPackage</h1>

Type: rdf:Property

Comments: A logistics package referenced in this supply chain trade line item.

Domains: 

[edi3:TradeLineItem](#TradeLineItem)


<h1 id="OverDeliveryAllowedIndicator">OverDeliveryAllowedIndicator</h1>

Type: rdf:Property

Comments: <br/>The indication, at line level, of whether or not over delivery is allowed for this trade delivery.<br/>The indication, at header level, of whether or not over delivery is allowed for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="KanbanIdentificationIdentifier">KanbanIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The unique kanban identifier for this trade product instance.

Domains: 

[edi3:ProductInstance](#ProductInstance)


<h1 id="LineTotalBasisAmount">LineTotalBasisAmount</h1>

Type: rdf:Property

Comments: A monetary value used as the line total basis on which this trade related tax, levy or duty is calculated.

Domains: 

[edi3:Tax](#Tax)


<h1 id="AreaDensityMeasure">AreaDensityMeasure</h1>

Type: rdf:Property

Comments: The measure of the area density, such as paper density 100 gsm, of this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="CreditReasonCode">CreditReasonCode</h1>

Type: rdf:Property

Comments: The code specifying the reason for a credit being given in this header trade settlement.

Domains: 

[edi3:TradeSettlement](#TradeSettlement)


<h1 id="ConfirmedReleaseSupplyChainEvent">ConfirmedReleaseSupplyChainEvent</h1>

Type: rdf:Property

Comments: <br/>The confirmed release event, at header level, for this trade delivery.<br/>The release event, at line level, confirmed for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="GrossLineTotalAmount">GrossLineTotalAmount</h1>

Type: rdf:Property

Comments: <br/>A monetary value of the total of all line amounts, excluding line level allowances and charges and taxes, being reported in this trade settlement header monetary summation.<br/>A monetary value of the total of all line amounts, excluding line level allowances and charges and taxes, being reported in this trade settlement line monetary summation.<br/>

Domains: 

[edi3:MonetarySummation](#MonetarySummation)


<h1 id="FreightForwarderTradeParty">FreightForwarderTradeParty</h1>

Type: rdf:Property

Comments: The freight forwarder party for this supply chain consignment.

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="ReasonCode">ReasonCode</h1>

Type: rdf:Property

Comments: <br/>A code specifying a reason for this document status.<br/>The code specifying the reason for this payment balance out.<br/>A code specifying a reason for this financial adjustment.<br/>The code specifying a reason for this communication event.<br/>The code specifying the reason for this validation status.<br/>The code specifying the reason for this applied allowance charge.<br/>The code specifying the reason for this cancellation status.<br/>The code specifying the reason for this header balance out.<br/>

Domains: 

[edi3:Status](#Status)
[edi3:Adjustment](#Adjustment)
[edi3:AllowanceCharge](#AllowanceCharge)
[edi3:Event](#Event)
[edi3:BalanceOut](#BalanceOut)


<h1 id="ActualQuantityWorkItemDimension">ActualQuantityWorkItemDimension</h1>

Type: rdf:Property

Comments: A work item dimension of the actual quantity in this work item quantity analysis.

Domains: 

[edi3:QuantityAnalysis](#QuantityAnalysis)


<h1 id="IndexText">IndexText</h1>

Type: rdf:Property

Comments: <br/>The index, expressed as text, to be used for this basic work item.<br/>The index, expressed as text, to be used for this grouped work item.<br/>

Domains: 

[edi3:WorkItem](#WorkItem)


<h1 id="DeductedAdjustmentPercent">DeductedAdjustmentPercent</h1>

Type: rdf:Property

Comments: The adjustment deducted, expressed as a percentage, for this cross-border customs valuation.

Domains: 

[edi3:CustomsValuation](#CustomsValuation)


<h1 id="PrecisionCalibratedMeasurement">PrecisionCalibratedMeasurement</h1>

Type: rdf:Property

Comments: A calibrated measurement of precision for this monitoring sensor.

Domains: 

[edi3:Sensor](#Sensor)


<h1 id="ApplicableNote">ApplicableNote</h1>

Type: rdf:Property

Comments: <br/>A note providing information applicable to this supply chain consignment item.<br/>A note providing information applicable to this transport event.<br/>A note providing information applicable to this piece of logistics transport equipment.<br/>A note providing information applicable to this specified observation.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:TransportEquipment](#TransportEquipment)
[edi3:Observation](#Observation)
[edi3:Event](#Event)


<h1 id="GroupedTransactionSpecifiedQuantity">GroupedTransactionSpecifiedQuantity</h1>

Type: rdf:Property

Comments: The number of grouped transactions specified in this financing request document.

Domains: 

[edi3:Document](#Document)


<h1 id="AreaNumberCode">AreaNumberCode</h1>

Type: rdf:Property

Comments: The code specifying the area number for this telecommunication.

Domains: 

[edi3:Communication](#Communication)


<h1 id="MinimumValueMeasure">MinimumValueMeasure</h1>

Type: rdf:Property

Comments: <br/>The measure of the minimum value for this specified range.<br/>The measure of the minimum value of this instructed temperature.<br/>

Domains: 

[edi3:Temperature](#Temperature)
[edi3:Range](#Range)


<h1 id="TermsAndConditionsDescriptionCode">TermsAndConditionsDescriptionCode</h1>

Type: rdf:Property

Comments: The code specifying the description of the terms and conditions for these returnable asset instructions.

Domains: 

[edi3:Instructions](#Instructions)


<h1 id="EstimatedGeneratedVolumeUnitMeasure">EstimatedGeneratedVolumeUnitMeasure</h1>

Type: rdf:Property

Comments: The estimated measure for this generated transport waste material component.

Domains: 

[edi3:MaterialComponent](#MaterialComponent)


<h1 id="SpecifiedTransportRoute">SpecifiedTransportRoute</h1>

Type: rdf:Property

Comments: A transport route specified for this transport service.

Domains: 

[edi3:Service](#Service)


<h1 id="TradeNameText">TradeNameText</h1>

Type: rdf:Property

Comments: A trade name, expressed as text, for this trade product.

Domains: 

[edi3:Product](#Product)


<h1 id="BasisDateTime">BasisDateTime</h1>

Type: rdf:Property

Comments: <br/>The date, time, date time, or other date time value used as the basis to calculate these trade payment penalty terms.<br/>The date, time, date time, or other date time value used as the basis to calculate the discount in the trade payment discount terms.<br/>

Domains: 

[edi3:PaymentPenaltyTerms](#PaymentPenaltyTerms)
[edi3:PaymentDiscountTerms](#PaymentDiscountTerms)


<h1 id="ConfirmedDeliverySupplyChainEvent">ConfirmedDeliverySupplyChainEvent</h1>

Type: rdf:Property

Comments: <br/>A confirmed delivery event in this supply chain supply plan.<br/>The confirmed delivery event, at line level, for this trade delivery.<br/>

Domains: 

[edi3:SupplyPlan](#SupplyPlan)
[edi3:TradeDelivery](#TradeDelivery)


<h1 id="LevelCode">LevelCode</h1>

Type: rdf:Property

Comments: The code specifying the level for this logistics risk analysis result.

Domains: 

[edi3:RiskAnalysisResult](#RiskAnalysisResult)


<h1 id="PowerSupplyConnectorQuantity">PowerSupplyConnectorQuantity</h1>

Type: rdf:Property

Comments: The number of power supply connectors for this piece of logistics transport equipment.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="AirFlowAirFlowUnitMeasure">AirFlowAirFlowUnitMeasure</h1>

Type: rdf:Property

Comments: The measure of the air flow for this piece of logistics transport equipment.

Domains: 

[edi3:TransportEquipment](#TransportEquipment)


<h1 id="SpecifiedSupplyChainSchedule">SpecifiedSupplyChainSchedule</h1>

Type: rdf:Property

Comments: A supply chain schedule, specified at line level, for this trade delivery.

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="EngineeringChangeReferencedDocument">EngineeringChangeReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>The engineering change document referenced in this line trade agreement.<br/>The engineering change document referenced in this header trade agreement.<br/>

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="ChangeableIndicator">ChangeableIndicator</h1>

Type: rdf:Property

Comments: <br/>The indication whether or not this operational parameter is changeable.<br/>The indication whether or not this control setting parameter is changeable.<br/>

Domains: 

[edi3:Parameter](#Parameter)


<h1 id="AircraftLimitationInformationText">AircraftLimitationInformationText</h1>

Type: rdf:Property

Comments: Aircraft limitation information, expressed as text, for these transported dangerous goods.

Domains: 

[edi3:DangerousGoods](#DangerousGoods)


<h1 id="ProductMadeToOrderIndicator">ProductMadeToOrderIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not, according to this line trade agreement, the product is manufactured, built or customized only after receipt of order.

Domains: 

[edi3:TradeAgreement](#TradeAgreement)


<h1 id="ReferenceAcknowledgementDocument">ReferenceAcknowledgementDocument</h1>

Type: rdf:Property

Comments: The acknowledgement document referenced in this document line.

Domains: 

[edi3:Document](#Document)


<h1 id="TotalDepositFeeInformationAmount">TotalDepositFeeInformationAmount</h1>

Type: rdf:Property

Comments: A monetary value of the total deposit fee stated for information purposes in this trade settlement header monetary summation.

Domains: 

[edi3:MonetarySummation](#MonetarySummation)


<h1 id="ReceiptDateTime">ReceiptDateTime</h1>

Type: rdf:Property

Comments: The date, time, date time, or other date time value for the formal receipt of this referenced document.

Domains: 

[edi3:Document](#Document)


<h1 id="GrossVolumeMeasure">GrossVolumeMeasure</h1>

Type: rdf:Property

Comments: <br/>A measure of the gross volume for this trade product.<br/>The measure of the gross volume of this logistics package.<br/>

Domains: 

[edi3:Product](#Product)
[edi3:Package](#Package)


<h1 id="ControlStartDateConfirmationIndicator">ControlStartDateConfirmationIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not the start date of a control has been confirmed for this cross-border regulatory procedure.

Domains: 

[edi3:RegulatoryProcedure](#RegulatoryProcedure)


<h1 id="RelatedSupplyChainTradeTransaction">RelatedSupplyChainTradeTransaction</h1>

Type: rdf:Property

Comments: <br/>A trade transaction related to this supply chain consignment.<br/>A trade transaction related to this referenced supply chain consignment.<br/>

Domains: 

[edi3:Consignment](#Consignment)


<h1 id="BondedWarehouseStorageTransportEvent">BondedWarehouseStorageTransportEvent</h1>

Type: rdf:Property

Comments: <br/>A bonded warehouse storage event for this supply chain consignment.<br/>A bonded warehouse storage event specifying when and where this piece of logistics transport equipment will be, or has been, stored.<br/>

Domains: 

[edi3:TransportEquipment](#TransportEquipment)
[edi3:Consignment](#Consignment)


<h1 id="IncludedLabelSection">IncludedLabelSection</h1>

Type: rdf:Property

Comments: A section included in this logistics label.

Domains: 

[edi3:Label](#Label)


<h1 id="DepartureTransportEvent">DepartureTransportEvent</h1>

Type: rdf:Property

Comments: A departure event during this logistics transport movement.

Domains: 

[edi3:TransportMovement](#TransportMovement)


<h1 id="PackingListReferencedDocument">PackingListReferencedDocument</h1>

Type: rdf:Property

Comments: <br/>The packing list document, at line level, referenced for this trade delivery.<br/>The packing list document, at header level, referenced for this trade delivery.<br/>

Domains: 

[edi3:TradeDelivery](#TradeDelivery)


<h1 id="PrepaidIndicator">PrepaidIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not this trade allowance charge is prepaid.

Domains: 

[edi3:AllowanceCharge](#AllowanceCharge)


<h1 id="MIMECode">MIMECode</h1>

Type: rdf:Property

Comments: The code specifying the Multipurpose Internet Mail Extensions (MIME) type for this specified binary file.

Domains: 

[edi3:BinaryFile](#BinaryFile)


<h1 id="VanningTransportEvent">VanningTransportEvent</h1>

Type: rdf:Property

Comments: <br/>The vanning event for this supply chain consignment item, i.e. the loading of this consignment item at the place of original despatch.<br/>The vanning event (the loading of this consignment at the place of its original despatch) for this referenced supply chain consignment.<br/>The vanning event for this supply chain consignment, i.e. the loading of this consignment at the place of original despatch.<br/>

Domains: 

[edi3:ConsignmentItem](#ConsignmentItem)
[edi3:Consignment](#Consignment)


<h1 id="ReceptionFacilityTradeContact">ReceptionFacilityTradeContact</h1>

Type: rdf:Property

Comments: A reception facility contact for this transport waste material.

Domains: 

[edi3:Material](#Material)


<h1 id="RateCode">RateCode</h1>

Type: rdf:Property

Comments: The code specifying the rate for this trade related tax, levy or duty.

Domains: 

[edi3:Tax](#Tax)


<h1 id="DescriptionBinaryObject">DescriptionBinaryObject</h1>

Type: rdf:Property

Comments: Binary object data, such as a photograph, describing this supply chain event.

Domains: 

[edi3:Event](#Event)


<h1 id="TransportMeansQuantity">TransportMeansQuantity</h1>

Type: rdf:Property

Comments: The number of means of transport in this logistics convoy.

Domains: 

[edi3:Convoy](#Convoy)


<h1 id="AuthenticatedOriginalIndicator">AuthenticatedOriginalIndicator</h1>

Type: rdf:Property

Comments: The indication of whether or not this referenced document is an authenticated original.

Domains: 

[edi3:Document](#Document)


<h1 id="SenderAssignedIdentificationIdentifier">SenderAssignedIdentificationIdentifier</h1>

Type: rdf:Property

Comments: A unique sender assigned identifier for this exchanged document.

Domains: 

[edi3:Document](#Document)


<h1 id="DUNSIdentificationIdentifier">DUNSIdentificationIdentifier</h1>

Type: rdf:Property

Comments: The unique nine-digit Data Universal Numbering System (DUNS) identifier for this trade party.

Domains: 

[edi3:Party](#Party)


<h1 id="LineOfCreditSpecifiedFinancingFinancialAccount">LineOfCreditSpecifiedFinancingFinancialAccount</h1>

Type: rdf:Property

Comments: <br/>The financing financial account, used for managing the line of credit, specified for this requesting party.<br/>The financing financial account, used for managing the line of credit, specified for this financing summary document.<br/>

Domains: 

[edi3:Party](#Party)
[edi3:Document](#Document)


