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
[includedReferencedConsignment](./includedReferencedConsignment) | [ReferencedConsignment](./ReferencedConsignment) | A referenced consignment included in this supply chain consignment.

Parent of:

- 

Used in :

- 
