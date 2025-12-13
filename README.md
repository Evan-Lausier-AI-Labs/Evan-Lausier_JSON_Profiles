# Evan Lausier - JSON Integration Profiles

A collection of JSON integration profiles for 3PL/WMS system integrations, primarily for use with NetSuite and middleware platforms like Celigo.

## Profile Catalog

| Profile | Type | Description |
|---------|------|-------------|
| [Inbound_Purchase_Order](./Inbound_Purchase_Order) | Request | Create inbound purchase orders (RMAs) via Instalink API |
| [Material](./Material) | Request | Create/update materials (items/SKUs) via Instalink API v2 |
| [Sales_Outbound_Order](./Sales_Outbound_Order) | Request | Create outbound sales orders for fulfillment |
| [Fulfillment_Records_Enlinx](./Fulfillment_Records_Enlinx) | Response | Retrieve fulfillment/shipment data from Enlinx 3PL |
| [Fulfillment_Records_Lion](./Fulfillment_Records_Lion) | Response | Retrieve fulfillment data with package-level detail from Lion 3PL |
| [Inventory_Adjustments](./Inventory_Adjustments) | Response | Retrieve inventory adjustment records |
| [Receipt_Records](./Receipt_Records) | Response | Retrieve receipt/receiving records (RMA receipts) |

## Profile Types

- **Request**: JSON payloads sent TO 3PL/WMS systems
- **Response**: JSON structures returned FROM 3PL/WMS systems

## Use Cases

These profiles are designed for:
- NetSuite ↔ 3PL integrations
- Celigo/middleware data mapping
- API documentation and testing
- Integration development reference

## Author

**Evan Lausier**  
Director of Strategy, Technology & Transformation  
[GitHub](https://github.com/Evan-Lausier-AI-Labs)
