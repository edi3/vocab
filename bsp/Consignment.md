Name: Consignment

Type: rdf:Class

Description: A separately identifiable collection of goods items to be transported or available to be transported from one consignor to one consignee in a supply chain via one or more modes of transport where each consignment is the subject of one single transport contract.


Properties:

name | type | description
-|-|-
[identification](./identification) | [Identifier](./Identifier) | A unique identifier.
[consignorAssigned](./consignorAssigned) | [Identifier](./Identifier) | The unique identifier assigned by the consignor to this supply chain consignment.
[consigneeAssigned](./consigneeAssigned) | [Identifier](./Identifier) | The unique identifier assigned by the consignee to this supply chain consignment.
[customsIdentification](./customsIdentification) | [Identifier](./Identifier) | A unique identifier, for customs purposes.
[carrierAssigned](./carrierAssigned) | [Identifier](./Identifier) | The unique identifier assigned by the carrier to this supply chain consignment, such as a booking reference number when cargo space is reserved prior to loading.
[freightForwarderAssigned](./freightForwarderAssigned) | [Identifier](./Identifier) | The unique identifier assigned by the freight forwarder to this supply chain consignment.
[tradedParcel](./tradedParcel) | [Identifier](./Identifier) | A traded parcel identifier for this supply chain consignment.
[FOB](./FOB) | [Amount](./Amount) | The monetary value that has to be, or has been, paid for this supply chain consignment as calculated under FOB (Free on Board) delivery terms.
[insuranceValue](./insuranceValue)	|	[Amount](./Amount)  | The monetary value of this supply chain consignment as covered by an insurance policy.
[insurancePremium](./insurancePremium)  |	[Amount](./Amount)  | The monetary value of the insurance premium for this supply chain consignment.
[associatedInvoice](./associatedInvoice) |	[Amount](./Amount)  | A monetary value of an invoice associated with this supply chain consignment.
[totalCharge](./totalCharge)		|   [Amount](./Amount)  | The total monetary value of all freight and other service charges for this supply chain consignment.
[totalCollectCharge](./totalCollectCharge)|   [Amount](./Amount)  | The total monetary value of all freight and other service charges which are to be collected from the consignee at or after delivery for this supply chain consignment.
[totalPrepaidCharge](./totalPrepaidCharge)|   [Amount](./Amount)  | The total monetary value of all freight and other service charges which have been paid in advance for this supply chain consignment.
[totalAllowanceCharge](./totalAllowanceCharge)|   [Amount](./Amount)  | The total monetary value of all allowances and charges for this supply chain consignment.
[totalDisbursement](./totalDisbursement)|   [Amount](./Amount)  | The monetary value of total disbursement for this supply chain consignment, such as the amount to be collected by the carrier according to the order given by the consignor.
[totalExportExitToImportEntryCharge](./totalExportExitToImportEntryCharge)|   [Amount](./Amount)  | The monetary value of the total charge or charges of freight, insurance and other services for this supply chain consignment calculated from the export exit location to the import entry location.
[declaredValueForCustoms](./declaredValueForCustoms)|   [Amount](./Amount)  | The monetary value declared for customs purposes for this supply chain consignment.
[COD](./COD)|   [Amount](./Amount)  | The monetary value of the COD (Cash On Delivery) amount to be collected by the carrier upon delivery of this supply chain consignment.
[associatedInvoiceDiscount](./associatedInvoiceDiscount)|   [Amount](./Amount)  | A monetary value of the discount on an invoice associated with this supply chain consignment.
[declaredValueForCarriage](./declaredValueForCarriage)|   [Amount](./Amount)  | The monetary value of this supply chain consignment as declared by the shipper or his agent for the purpose of varying the carrier's level of liability from that provided in the contract of carriage, in case of loss or damage to goods or delayed delivery.
[riskFactor](./riskFactor) | [Code](./Code) | The code specifying a risk factor for this supply chain consignment.
[paymentArrangementTransportService](./paymentArrangementTransportService) | [PaymentArrangementCode](./PaymentArrangementCode) | The code specifying the payment arrangements for this supply chain consignment.



[includedReferencedConsignment](./includedReferencedConsignment) | [ReferencedConsignment](./ReferencedConsignment) | A referenced consignment included in this supply chain consignment.

Parent of:

- 

Used in :

- [HeaderTradeDelivery](./HeaderTradeDelivery)
- [LineTradeDelivery](./LineTradeDelivery)
- [TransportEquipment](./TransportEquipment)
